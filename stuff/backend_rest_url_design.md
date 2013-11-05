# REST URL design

> proposta de URLs para aplicações RESTful

**:app-name** - nome da aplicação

**:version** - versionamento (é recomendado o uso, porém, não é obrigatório o uso)

**:resource** - nome do recurso exposto (*entidade*), sendo este nome no plural


## GET, UPDATE, DELETE

```
http://:app-name/rest/:version/:resource/:id
```

**:id** - identificador do recurso

* **GET** - recurpera o recurso do respectivo identificador

* **UPDATE** -  atualiza o recurso do respectivo identificador, sendo a representação do recurso enviado no corpo da requisição

* **DELETE** - solicita a remoção do respectivo recurso pelo seu identificador


## GET, POST

```
http://:app-name/rest/:version/:resource
```

* **GET** - recupera uma listagem dos recursos

* **POST** - um novo recurso a ser inserido, enviado no corpo da requisição

## GET

Respectivos parâmetros que podem ser enviados 

### Paginação

```
http://:app-name/rest/:version/:resource?page=1&size=10
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

* **_Observação:_** é recomendado uma implementação default assumindo um valor padrão, mesmo se estes parâmetros não sejam informados na URL. Estes parâmetros irão possibilidar a implementação de paginação.

### Consulta e paginação

```
http://:app-name/rest/:version/:resource?q=:query

http://:app-name/rest/:version/:resource?q=:query&page=1&size=10
```

**:query** - parâmetro de consulta ou expressão de consulta

_**Observação:**_ necessário uma implementação no servidor para tratar o processamento desta query.

### Utilidades

```
http://:app-name/rest/:version/:resource?action=:option
```

A idéia dessa proposta de URL é ter um recurso flexível para disponibilizar funcionalidades

**:option** - opção de ação solicitada. Implementações sugeridas:

* **count** - retorna a quantidade/contagem de recursos disponíveis. Esta funcionalidade/informação irá ser útil para implementação de paginação

* **template** - retorna o recurso associado a URL com os parâmetros vazios, serve para conhecer a estrutura do recurso
