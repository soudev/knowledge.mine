# REST URL design


<!-- toc -->
* [Informações Gerais](#informações-gerais)
* [GET, UPDATE, DELETE](#get-update-delete)
* [GET, POST](#get-post)
* [GET](#get)
  * [Paginação](#paginação)
  * [Consulta e paginação](#consulta-e-paginação)
  * [Utilidades](#utilidades)
* [Desnormalização](#desnormalização)

<!-- toc stop -->


## Informações Gerais

> Proposta de URLs para aplicações RESTful

**:app-name** - nome da aplicação

**:rest** - contexto, parte da URL que identifica a comunicação em REST

**:version** - versionamento (uso recomendado, porém não é obrigatório)

**:resource** - nome do recurso exposto (*entidade*), sendo este nome no plural


## GET, UPDATE, DELETE

```
http://:app-name/:rest/:version/:resource/:id
```

**:id** - identificador do recurso

* **GET** - recurpera o recurso do respectivo identificador

* **UPDATE** -  atualiza o recurso do respectivo identificador, sendo a representação do recurso enviado no corpo da requisição

* **DELETE** - solicita a remoção do respectivo recurso pelo seu identificador


## GET, POST

```
http://:app-name/:rest/:version/:resource
```

* **GET** - recupera uma listagem dos recursos

* **POST** - um novo recurso a ser inserido, enviado no corpo da requisição

## GET

Respectivos parâmetros que podem ser enviados.

### Paginação

```
http://:app-name/:rest/:version/:resource?page=1&size=10
```

* **page** - identifica o índice inicial para listagem [ *valor padrão sugerido: 1* ]

* **size** - quantidade de itens que irão retornar na requisição [ *valor padrão sugerido: 10* ]

* **seleção de itens na base de dados:**

_**índice inicial**_ = ((page-1) * size)

_**quantidade de itens selecionados**_ = size

* **modelo de retorno:**

```
{
  data:   {type: Array},  // itens da página
  count:  {type: Number}, // quantidade de itens na base
  page:   {type: Number}, // página atual
  pages:  {type: Number}  // quantidade de páginas
}
```

* **Atenção:_** é altamente recomendável definir valores iniciais, caso uma requisição de paginação venha sem parâmetros, isto previne de recuperar todos os itens do banco de dados (mantenha em mente, provavelmente sua base irá crescer além de 100, 1000, ... registros).


### Consulta e paginação

```
http://:app-name/:rest/:version/:resource?q=:query

http://:app-name/:rest/:version/:resource?q=:query&page=1&size=10
```

**:query** - parâmetro de consulta ou expressão de consulta

_**Observação:**_ necessário uma implementação no servidor para tratar o processamento desta query.

### Utilidades

```
http://:app-name/:rest/:version/:resource?action=:option
```

A idéia dessa proposta de URL é ter um recurso flexível para disponibilizar funcionalidades

**:option** - opção de ação solicitada. Implementações sugeridas:

* **template** - retorna uma amostra do recurso com seus respectivos atributos (é interessante também informar os tipos dos atributos)


## Desnormalização

Além das URLs acima, outras URLs podem ser implementadas para adicionar mais funcionalidades.
