# Adobe Flex

* [Adobe Flex | Adobe](http://www.adobe.com/br/products/flex.html)

  * Atualmente o desenvolvimento do Framework está sob responsabilidade da [Apache Flex | Apache](http://flex.apache.org/) e sua respectiva comunidade. 

  * [Flex Developer Center](http://www.adobe.com/devnet/flex.html)

  * Histório e informações gerais : [wikipédia pt-BR](http://pt.wikipedia.org/wiki/Adobe_Flex)

> *Nota:* 
> Segundo informações oficiais a empresa Adobe, mudou seu foco e prioridade para o desenvolvimento de aplicações RIA, sendo favorário ao HTML 5 no lugar de soluções baseadas em plugins. Devido a falha e falta de uma boa estratégia de comunicação este comunicado fez com que muitos desistissem de investir em futuros projetos o uso do Adobe Flex, tendo um exodo em massa dos então desenvolvedores Flex, para o desenvolvimento JavaScript com foco nos recursos do HTML 5


## Desenvolvimento 

### Codificação

* O Desenvolvimento utilizando o framework Adobe Flex consite em 2 linguagems:

  * [MXML | wikipédia pt-BR](http://pt.wikipedia.org/wiki/MXML) - linguagem de marcação para definição de interface e componentes visuais

  * [ActionScript | wikipédia pt-BR](http://pt.wikipedia.org/wiki/ActionScript) 3 - linguagem script orientada a objetos utilizada na codificação

* O produto resultado (compilado) de uma aplicação desenvolvida com Adobe Flex é um arquivo binário [SWF | wikipédia pt-BR](http://pt.wikipedia.org/wiki/SWF), o qual executa sobre a máquina vitual [Flash Player | wikipédia pt-BR](http://pt.wikipedia.org/wiki/Adobe_Flash_Player)  (a qual é um plugin para os web browsers).


### Estrutura das aplicações

* É importante ter em mente que os sistemas que utilizam o Adobe Flex, possuem uma estrutura cliente - servidor. 

  * O código do cliente, este é codificado e desenvolvido usando o Adobe Flex e como dito anteriormente, o resultado deste, o produto binário swf, é executado no plugin Adobe Flash, presente nos web browsers, na máquinas dos clientes. O Adobe Flex possibilita que estas aplicações possuam recursos avançados e ricos de interatividade e processamento, que possibilita uma interface rica.

  * O código referente a lógica e regras de negócio do sistema, esta parte fica sob responsabilidade da parte servidor, onde se pode utilizar as linguagens de programação tradicionais, por exemplo: Java, .Net, etc.

  * A comunicação entre cliente - servidor, em sistemas que utilizem o Adobe Flex, utiliza-se o protocolo de comunicação AMF ( [Action Message Format | wikipédia en-US](http://en.wikipedia.org/wiki/Action_Message_Format) ), o qual possibilita uma comunicação de objetos representados em ambos os lados, sendo esta comunicação em formato binário, reduzindo a quantidade de bytes trafegados. 

    * Para utilizar esta comunicação é necessário utilizar no lado do servidor, um suporte para que os objetos sejam codificiados/decoficiados neste protocolo, no caso de aplicações Java no servidor, temos o [Adobe BlazeDS](http://sourceforge.net/adobe/blazeds/wiki/Home/) (entre outros), e em aplicações .Net temos o [FluorineFx](http://fluorine.thesilentgroup.com/) (entre outros)

    * Post interessante sobre do que se trata o protocolo AMF : [What the hell is AMF? | Lee Brimelow](http://www.leebrimelow.com/what-the-hell-is-amf/)


### Ferramentas

* [Adobe Flash Builder](http://www.adobe.com/br/products/flash-builder.html) - ferramenta paga da Adobe. (Ferramenta baseada no Eclipse IDE) *Observação:* Nas últimas versões da ferramenta foi descontinuado a funcionalidade de Design Preview para do desenvolvimento da interface utilizando o MXML.

  * [Flash Builder Developer Center | Adobe Developer Connection](http://www.adobe.com/devnet/flash-builder.html)

* [ActionScript, Flex & AIR plugin | IntelliJ IDEA - JetBrains](http://www.jetbrains.com/idea/features/flex_ide.html)

* [FDT](http://fdt.powerflasher.com/) is a flexible development toolkit in Eclipse for interactive developers

* [FlashDevelop](http://www.flashdevelop.org/) -  is a free and open source code editor for every developer


## Frameworks

* [Mate Framework](http://mate.asfusion.com/)

  * [What is Mate?](http://mate.jottit.com/)


* Swiz Framework
  
  * [Code | GitHub](https://github.com/swiz/swiz-framework)

  * [Docs | Jira](https://swizframework.jira.com/wiki/display/SWIZ/Home)

  * [Sample application using the Swiz Framework and BlazeDS | Christophe Coenraets](http://coenraets.org/blog/2009/02/sample-application-using-the-swiz-framework-and-blazeds/)

  * [Desenvolvimento Flex com o Swiz Framework | InfoQ Br](http://www.infoq.com/br/news/2009/02/swiz-framework)

  * [[Flex & AIR] Swiz Framework – meus primeiros passos | Erko Bridee](http://blog.erkobridee.com/2010/07/13/flex-air-swiz-framework-meus-primeiros-passos/)


## Material de apoio ao desenvolvimento

* [Adobe Developer Connection](http://www.adobe.com/devnet.html)

  * [Flex Developer Center](http://www.adobe.com/devnet/flex.html)

  * [Flash Builder Developer Center](http://www.adobe.com/devnet/flash-builder.html)

  * [Tour de Flex](http://www.adobe.com/devnet/flex/tourdeflex.html)

* [Adobe Flex 4.6 | Adobe Help](http://help.adobe.com/en_US/flex/using/index.html)

* [Scalenine](http://www.scalenine.com/) - temas


### Aprendizado

* [Flex in a Week video training | Adobe Developer Connection](http://www.adobe.com/devnet/flex/videotraining.html)

* [Getting Started Videos | Apache Flex](http://flex.apache.org/doc-videos.html)

* [Flex 3 Getting Started Experience | Adobe Learn](https://learn.adobe.com/wiki/display/Flex/Getting+Started)

* [[PDF] Adobe Flex a partir do zero](http://msdevstudio.net/mywork/FlexTutor/Flex_Book_Part_1_2_3_4_5.pdf) - O livro - Msdevstudio.net

* [Adobe Flex Tutorial | Tutorials Point](http://www.tutorialspoint.com/flex/)


### Blogs, posts sobre Flex

* [Erko Bridee](http://blog.erkobridee.com/c/dev/adobe/)

* [Fábio Vedovelli](http://blog.vedovelli.com.br/?cat=12)

* [Igor Costa](http://www.igorcosta.com/tag/flex/)

* [Igor Musardo](http://musardos.com.br/category/desenvolvimento-software/flex/)

* [Stefan Horochovec](http://www.horochovec.com.br/blog/category/flex/)

* [Vinícius Lourenço](http://blog.vilourenco.com.br/category/flex/)

