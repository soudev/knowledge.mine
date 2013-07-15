# Angular.js

## Visão Geral

> **Motivação**
>
> Framework Javascript para desenvolvimento de Front-end com curva de  aprendizado rápida e produtividade similar a encontrada no Adobe Flex.
>


* o [Angular.js](http://angularjs.org/) é mantido pela Google

* o código e desenvolvimento é realizado no [repositório do GitHub](https://github.com/angular/angular.js)

* o criador do Angular.js era desenvolvedor Adobe Flex - [Miško Hevery](http://misko.hevery.com/about/)

* O projeto utiliza o Jenkins CI para efetuar os builds [ci.angularjs.org](http://ci.angularjs.org/) | [configurações](https://github.com/angular/ci.angularjs.org)

* [[YouTube] Breaking Open: AngularJS. Great interview with Misko Hevery, Angularjs Framework author](https://www.youtube.com/watch?v=X0VsStcCCM8)


### Estatísticas

* [Usage statistics and market share of AngularJS for websites | W3Techs](http://w3techs.com/technologies/details/js-angularjs/all/all)

* [Angular JS Usage Statistics | Build With](http://trends.builtwith.com/javascript/Angular-JS) - Websites using Angular JS

* [AngularJS Developer Statistics | LinkedIn](http://www.linkedin.com/groups?groupDashboard=&gid=4896676)



### Por que utilizar o AngularJS?

HTML é ótimo para documentos declarativos estátivos, porém deixa a  desejar quando se trata de aplicações web. O AngularJS possibilita  extender o vocabulário HTML em sua aplicação. O ambiente que resulta  disso é extraordinariamente expressivo, legível e aumenta a velocidade  do desenvolvimento.

O AngularJS é um conjunto de ferramentas, para construir um framework mais adequado para o desenvolvimento de aplicações.

É totalmente extensível e trabalha bem com outras bibliotecas. Cada  característica do AngularJS pode ser modificada ou substituida conforme a  necessidade do projeto.

* [5 reasons to use AngularJS in the corporate app world | Digital Caveman](http://oscarvillarreal.com/2013/05/07/5-reasons-to-use-angularjs-in-the-corporate-app-world/)



### 5 Características impressionantes

**Fonte:** [5 Awesome AngularJS Features | Nettuts+](http://net.tutsplus.com/tutorials/javascript-ajax/5-awesome-angularjs-features/)


#### Two Way Data-Binding

Facilita muito a interação entre o View e o Controller. É  provavelmente uma das carateristicas mais legais do AngularJS e irá te  salvar de ter que escrever código redundante para atualização de  informações, tanto na view, quando no controller.

--

#### Templates

No AngularJS, um template é nada mais que um pedaço de código HTML.  Este código HTML do template é extendido para conter instruções de como o  modelo deve ser exibido e atualizado pela view.

--

#### MVC

O AngularJS incorpora os princípios básicos do padrão MVC de como  implementar o client-side de aplicações web, entretanto não implementa o  modelo tradicional do MVC, e sim um padrão próximo ao MVVM  (Model-View-ViewModel).


##### - Model

O modelo são os dados da aplicação. O modelo nada mais são que  objetos JavaScript. Não há a necessidade de implementar nenhuma classe  específica do framework.


##### - ViewModel

O ViewModel é um objeto que prove dados e métodos específicos para uma determinada View.

No AngularJS o ViewModel é representado pelo objeto `$scope`. O `$scope`  é um objeto JavaScript com um conjunto pequeno de funcionalidades para  monitorar e refletir as alterações nos dados entre a View e o  Controller.


##### - Controller

O Controller é responsável por determinar o estado inicial do `$scope` com os métodos e dados utilizados pela View.
Vale  a pena notar que não é responsábilidade do Controller manter o estado  da aplicação, nem interagir(controlar as requisições/respostas) com os  serviços remotos.


##### - View

A View é o HTML resultante do pós processamento do AngularJS do HTML que inclui as extensões de interação com o modelo.

Esta divisão cria uma fundação sólida para a arquitetura da  aplicação. Onde o `$scope` possui as referências dos dados, o Controller  define o comportamento e a View lida com o layout e as interações com o  Controller, que responde de acordo com a interação.

--

#### Injeção de Dependências

O AngularJS possui um suporte interno para injeção de dependências, o  que torna o desenvolvimento da aplicação mais fácil, compreensível e  testável.

--

#### Diretivas (Componentes)

Diretivas é o que possibilita extender o HTML e criar tags  customizadas, possibilitando criar componentes, os quais poderão ser  reaproveitados em futuros projetos.

--

#### Bonus: Suporte para Testes

O time do AngularJS sentiu a necessidade de que o código JavaScript  precisava de uma filosofia de testes. Tendo isso em mente o AngularJS  foi projetado para que as aplicações que fossem implementadas utilizando  o AngularJS fossem o mais fácil possível de serem testadas. Com isso  não existe desculpas de não escrever testes para as aplicações  construídas com o AngularJS.


## Aprendizado

* [AngularJS: an Overview | Glenn Stovall](http://glennstovall.com/blog/2013/06/27/angularjs-an-overview/)

* [Angular Docs Guide](http://docs.angularjs.org/guide/)

* [AngularJS Cheat Sheet](http://www.cheatography.com/proloser/cheat-sheets/angularjs/)

* [AngularJS - Where To Start?](http://blog.whydoifollow.com/post/angularjs-where-to-start)

* [Egghead - AngularJS](http://egghead.io/) - curso online

* [A Better Way to Learn AngularJS | Thinkster](http://www.thinkster.io/pick/51d287681e4b9c9098000013/a-better-way-to-learn-angularjs)

* [Angular.js : Advanced Design Patterns and Best Practices](http://trochette.github.io/Angular-Design-Patterns-Best-Practices/)

* [A small introduction to AngularJS : data-binding, IoC/DI, directives](http://derkoe.github.io/presentations/angularjs-intro/)

* [Use AngularJS to power your web application | Year of Moo](http://www.yearofmoo.com/2012/08/use-angularjs-to-power-your-web-application.html)

* [More AngularJS Magic to Supercharge your Webapp | Year of Moo](http://www.yearofmoo.com/2012/10/more-angularjs-magic-to-supercharge-your-webapp.html)

* [An AngularJS Adventure Anthology | Angular Cats!](http://ericterpstra.com/2012/09/angular-cats-an-angularjs-adventure-anthology/)

* [Tunando o browser com AngularJS | DevCast](http://devcastbrasil.com/videos/tunando-o-browser-com-angularjs/)

* [ASP.NET MVC and Angular JS with Scott Allen](http://tv.ssw.com/3061/asp-net-mvc-and-angular-js)

* [Angular.js Views and Controllers | Backlift Blog](https://blog.backlift.com/entry/angular-tut1)

--

* [Code Organization in Large AngularJS and JavaScript Applications](http://cliffmeyers.com/blog/2013/4/21/code-organization-angularjs-javascript)

--

* [[YouTube] Google I/O 2013 - Design Decisions in AngularJS](https://www.youtube.com/watch?v=HCR7i5F5L8c)

* [[YouTube] Re-Imagining the Browser with AngularJS](https://www.youtube.com/watch?v=ersEb9vTX3Y)

* [[YouTube] AngularJS MTV Meetup: Best Practices (2012/12/11)](https://www.youtube.com/watch?v=ZhfUv0spHCY)

* [[YouTube] Writing Directives](https://www.youtube.com/watch?v=WqmeI5fZcho)

* [YouTube] AngularJS end-to-end web app tutorial - .Net [Part I](https://www.youtube.com/watch?v=Ja2xDrtylBw) | [Part II](https://www.youtube.com/watch?v=6WbVn_gYwQo) | [Part IIII](https://www.youtube.com/watch?v=ilCH2Euobz0)

--

* [Interesting Bits 8 - Angular Js](http://blog.rodolfocaldeira.com/2013/05/24/interesting-bits-8-angularjs.html) - A collection of some really useful AngularJs links.

* [Things I Wish I Were Told About Angular.js](http://ruoyusun.com/2013/05/25/things-i-wish-i-were-told-about-angular-js.html)

* [[GitHub] jmcunningham / AngularJS-Learning](https://github.com/jmcunningham/AngularJS-Learning) - A bunch of links to blog posts, articles, videos, etc for learning AngularJS


### Dailyjs.com : Angular.js

* [Part 1: Google, Twitter, and AngularJS](http://dailyjs.com/2013/04/11/angularjs-1/)

* [Part 2: Let's Make a Feed Reader](http://dailyjs.com/2013/04/18/angularjs-2/)

* [Part 3: Rendering Feeds](http://dailyjs.com/2013/04/25/angularjs-3/)

* [Part 4: Managing Feeds](http://dailyjs.com/2013/05/09/angularjs-4/)

* [Part 5: Tests](http://dailyjs.com/2013/05/16/angularjs-5/)

* [Part 6: Adding Dependencies](http://dailyjs.com/2013/05/30/angularjs-6/)

* [Part 7: Form Validation](http://dailyjs.com/2013/06/06/angularjs-7/)

* [Part 8: Iterators and Data](http://dailyjs.com/2013/06/13/angularjs-8/)


## Caso de Uso

* [Aplicações construídas com Angular.js](http://builtwith.angularjs.org/)

* [Using AngularJS at Localytics](http://www.localytics.com/blog/2013/angularjs-at-localytics/) - This is the story of how we rewrote our Backbone-powered web  application in AngularJS, using nearly half the number of lines of code.  (It is a love story.)

* [Tyto.io](http://tyto.io/) - A simple mobile framework powered by Angular.js | [[YouTube] Introduction to Tyto](https://www.youtube.com/watch?v=jiyMZLXGraw)

* [AngularJS Calculator Demo](http://www.thomporter.com/apps/angularjs_calc) - A calculator built with AngularJS, written in CoffeeScript


## Dicas

* [Conjunto de materiais úteis](http://mattkruse.com/angular/) - PDFs

* [8 Tips for Angular.js Beginners](http://vxtindia.com/blog/8-tips-for-angular-js-beginners/)

* [Fun with AngularJS | Holly Schinsky](http://devgirl.org/2013/03/21/fun-with-angularjs/)

* [AngularJS Tips and Tricks](http://deansofer.com/posts/view/14/AngularJs-Tips-and-Tricks-UPDATED)

* [Angular.js JSFiddle Examples](https://github.com/angular/angular.js/wiki/JSFiddle-Examples)

* [[Gist] Difference between Service, Factory and Provider in AngularJS](https://gist.github.com/Mithrandir0x/3639232)

* [How to create (singleton) AngularJS services in 4 different ways | JDriven BlogJDriven Blog](http://blog.jdriven.com/2013/03/how-to-create-singleton-angularjs-services-in-4-different-ways/)

* [Build Apps with AngularJS | Google Chrome Apps](http://developer.chrome.com/trunk/apps/angular_framework.html)

* [Simple Intro to AngularJS Web Application Development](http://blog.dewmap.com/post/51353fa6717c080200000001)

* [Building a Spreadsheet in 20 Minutes with Angular.js | Thomas Street](http://thomasstreet.net/blog/spreadsheet.html)

* [AngularJS collaboration board with Socket.io | Tutorial | .net magazine](http://www.netmagazine.com/tutorials/angularjs-collaboration-board-socketio)

* [[SlideShare] AngularJS Animations](http://www.slideshare.net/EyalV/angularjs-animations-21435788)

* [Adding a weel (spin.js) progress indicator to your AngularJS application](http://blog.xvitcoder.com/adding-a-weel-progress-indicator-to-your-angularjs-application/)

* [Facebook’s New React JavaScript Library Tutorial Rewritten in AngularJS | Medium](https://medium.com/make-your-own-apps/e71bcedc36b)

* [Source Modification With r.js | Merrick Christensen](http://merrickchristensen.com/articles/build-angular-with-requirejs.html) - An overview of source modification with r.js. Using ngmin and Angular.js as an example. (Require.js)

* [Form validation with AngularJS](http://www.ng-newsletter.com/posts/validations.html)

* [Random tricks when using AngularJS](http://blog.tomaka17.com/2012/12/random-tricks-when-using-angularjs/) 


### Internacionalização

* [[GitHub] tyson-benson / Internationalization with AngularJS](https://github.com/tyson-benson/Internationalization-with-AngularJS) - i18n

* [[Gist] i18n Helper function for Javascript](https://gist.github.com/3353635)


### Componentes

* [Writing Reusable AngularJS Components with Bower | Brian Ford](http://briantford.com/blog/angular-bower.html)

* [Sharing AngularJS modules with component.js | Jayway](http://www.jayway.com/2013/06/04/sharing-angularjs-modules-with-component-js/)


### Escopo e informações

* [Global variable with AngularJS | Coding Insight](http://www.codinginsight.com/global-variable-with-angularjs/)

* [AngularJS: 6 Common Pitfalls Using Scopes](http://thenittygritty.co/angularjs-pitfalls-using-scopes)

* [Angular JS : Sharing data between Controllers](http://ramandv.com/blog/angular-js-sharing-data/)


### Yeoman, Grunt e Bower

* [Automating AngularJS With Yeoman, Grunt & Bower | Newtriks LTD](http://newtriks.com/2013/06/11/automating-angularjs-with-yeoman-grunt-and-bower/)

* [[YouTube] Frontend Workflows with Grunt and Angular JS](https://www.youtube.com/watch?v=fSAgFxjFSqY)


### Autenticação

* [[GitHub] philipsorst / angular-rest-springsecurity](https://github.com/philipsorst/angular-rest-springsecurity) - An example AngularJS Application that uses a Spring Security protected Jersey REST backend based on Hibernate/JPA

* [Deal with users authentication in an AngularJS web app](http://blog.brunoscopelliti.com/deal-with-users-authentication-in-an-angularjs-web-app)

* [Authentication in Single Page Applications with Angular.js - A Modest Proposal](http://www.frederiknakstad.com/authentication-in-single-page-applications-with-angular-js/)

* [Implementing basic HTTP authentication for HTTP requests in AngularJS](http://wemadeyoulook.at/blogg/implementing-basic-http-authentication-http-requests-angular/)

* [Facebook authentication in your AngularJS web app | Web Development blog](http://blog.brunoscopelliti.com/facebook-authentication-in-your-angularjs-web-app)

* [AngularJS: Send auth token with every request](http://nils-blum-oeste.net/angularjs-send-auth-token-with-every--request/)

* [Authentication in AngularJS (or similar) based application](http://www.espeo.pl/2012/02/26/authentication-in-angularjs-application)

* [Tutorial: Creating an AngularJS app with node.js and Heroku Part II | Bryan Leboff](http://techblog.appirio.com/2013/02/tutorial-creating-angularjs-app-with.html) - Instagram Authentication


### PhoneGap

* [PhoneGap and AngularJs, The Start | Tech Pro](http://tech.pro/tutorial/1336/phonegap-and-angularjs-the-start)

* [PhoneGap and AngularJs, Notification Service | Tech Pro](http://tech.pro/tutorial/1349/phonegap-and-angularjs-notification-service)

* [PhoneGap and AngularJS: In App Browser | Tech Pro](http://tech.pro/tutorial/1357/phonegap-and-angularjs-in-app-browser)

* [Brian Ford - Building **PhoneGap** Apps with AngularJS](http://briantford.com/blog/angular-phonegap.html)


### Directive

* [AngularJS Directives Tutorial | Fundoo Solutions](http://www.befundoo.com/university/tutorials/angularjs-directives-tutorial/)

* [[GitHub] rootux / angular-highcharts-directive](https://github.com/rootux/angular-highcharts-directive) - An Angular Js Directive which allows to simplify the use of Highcharts charts

* [[GitHub] wzr1337 / angular-gestures](https://github.com/wzr1337/angular-gestures) - AngularJS directive that adds support for multi touch gestures to your app. Based on hammer.js.

* [[jsfiddle] Big Text Directive with AngularJS](http://jsfiddle.net/michaeldausmann/FH9wj/) - Use AngularJS and jquery to make an input with a popup textarea for editing large text values

* [AngularJS Directives and The Computer Science of JavaScript | Adobe Developer Connection](http://www.adobe.com/devnet/html5/articles/angularjs-directives-and-the-computer-science-of-javascript.html)

* [Understanding AngularJS transclude in directives](http://odiseo.net/angularjs/understanding-angularjs-transclude-in-directives)

* [A Look at Directives in AngularJS](http://blog.envylabs.com/post/52142458172/a-look-at-directives-in-angularjs) - Using directives, we can extract complex and repetitive parts of our user interface into easily reusable building blocks.

* [Part 5 - Custom Directive | Angular Cats!](http://ericterpstra.com/2012/09/angular-cats-part-5-custom-directive/)

* [Forced Repaints In Directive Can Cause Accidental Scrolling In AngularJS](http://www.bennadel.com/blog/2468-Forced-Repaints-In-Directive-Can-Cause-Accidental-Scrolling-In-AngularJS.htm)


### AngularJS Sticky Notes | One Hungry MindOne Hungry Mind

* [Pt 1 - Architecture](http://onehungrymind.com/angularjs-sticky-notes-pt-1-architecture/)

* [Pt 2 - Isolated Scope](http://onehungrymind.com/angularjs-sticky-notes-pt-2-isolated-scope/)


### AngularJS: Melhores Práticas | Ciro Nunes

* [Parte I: Iniciando Um Projeto](http://cironunes.github.com/angularjs-melhores-praticas-parte-I-bootstrap/)


### Ferramentas

* [Introducing the Batarang](http://blog.angularjs.org/2012/07/introducing-angularjs-batarang.html) - dev tool

* [[GitHub] maxhoffmann / angular-snippets](https://github.com/maxhoffmann/angular-snippets) - Angular.js Snippets for Sublime Text 2


## Módulos

* [Angular Modules](http://ngmodules.org/) - Encontre (Módulos, Plugins e Directives) para o Angular.js 

* [Angular UI](http://angular-ui.github.com/) - Componentes de UI

* [Angular UI / UI Bootstrap](http://angular-ui.github.com/bootstrap/)

* [AngularStrap](http://mgcrea.github.com/angular-strap/) - Bootstrap directives for AngularJS

* [Angular Kendo](http://kendo-labs.github.com/angular-kendo/) - Angular-Kendo is a passthrough to the Kendo UI

* [ngInfiniteScroll - Infinite Scrolling for AngularJS](http://binarymuse.github.com/ngInfiniteScroll/index.html)

* [Criando um scroll Infinito com o AngularJS e JQuery | Igor Costa](http://www.igorcosta.com/criando-um-scroll-infinito-com-o-angularjs/)

* [AngularJS + Chosen Plugin = Awesome](http://onehungrymind.com/angularjs-chosen-plugin-awesome/)

* [JQuery Mobile Angular Adapter](https://github.com/tigbro/jquery-mobile-angular-adapter)

* [n3-charts.line-chart](http://angular-d3.github.io/line-chart/) - Awesome charts for AngularJS, powered by D3.js.

### ng animate

* [Animation in AngularJS | Year of Moo](http://www.yearofmoo.com/2013/04/animation-in-angularjs.html) - AngularJS now provides full support for animations direct from it's core

* [AngularJS Animations](http://www.nganimate.org/)


## Projetos de Exemplo

* [[GitHub] angular-app / angular-app](https://github.com/angular-app/angular-app) - Reference application for AngularJS

* [ng-boilerplate | Non-Trivial AngularJS Made Easy](http://joshdmiller.github.com/ng-boilerplate/) - Everything you need to kickstart AngularJS projects: a best-practice  directory structure, an intelligent build system, and the best web  design libraries around.

* [[GitHub] CaryLandholt / AngularFun](https://github.com/CaryLandholt/AngularFun) - AngularJS Reference Architecture

* [[GitHub] erkobridee / lab-angularjs](https://github.com/erkobridee/lab-angularjs)

* [AngularJS - Consumindo a API do GitHub](http://blog.erkobridee.com/2012/07/26/angularjs-consumindo-a-api-do-github/) | [Testar App](http://erkobridee.github.io/angularjs-github-info/) | [GitHub Code](https://github.com/erkobridee/angularjs-github-info)

* [MEAN Stack](http://mean.io/) - is a boilerplate that provides a nice starting point for MongoDB, Node.js, Express, and AngularJS based applications.


### Angular-Seed

Projeto de exemplo / estrutura inicial

* **Oficial:** [[GitHub] angular / angular-seed](https://github.com/angular/angular-seed) | [Jenkins-CI](http://ci.angularjs.org/view/angular-seed/)

* **Fork:** [[GitHub] skivvies / angular-seed](https://github.com/skivvies/angular-seed) | [Travis-CI](https://travis-ci.org/skivvies/angular-seed)

* **require.js:** [[GitHub] ysilvestrov / angular-seed](https://github.com/ysilvestrov/angular-seed)


## Teste

> **Dependência**
> 
> As ferramentas de teste, para os projetos com Angular.js necessitam e executam sobre o [Node.js](http://nodejs.org/) | [[GitHub] erkobridee / lab-nodejs](https://github.com/erkobridee/lab-nodejs)
>

* [[GitHub] ricardohbin / angularjs-meetup-sp](https://github.com/ricardohbin/angularjs-meetup-sp) - Jasmine + Angular.mocks + Karma.JS

* [How To Test An AngularJS Directive | Newtriks LTD](http://newtriks.com/2013/04/26/how-to-test-an-angularjs-directive/)

* [How to mock AngularJS modules and inject them in your testacular tests?](http://southdesign.de/blog/mock-angular-js-modules-for-test-di.html)
