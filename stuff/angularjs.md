# Angular.js

<!-- toc -->

* [Visão Geral](#visão-geral)
  * [Angular.js 2.0](#angularjs-20)
  * [Estatísticas](#estatísticas)
  * [Por que utilizar o AngularJS?](#por-que-utilizar-o-angularjs)
  * [5 Características impressionantes](#5-características-impressionantes)
    * [Two Way Data-Binding](#two-way-data-binding)
    * [Templates](#templates)
    * [MVC](#mvc)
    * [Injeção de Dependências](#injeção-de-dependências)
    * [Diretivas (Componentes)](#diretivas-componentes)
    * [Bonus: Suporte para Testes](#bonus-suporte-para-testes)
* [Aprendizado](#aprendizado)
  * [CoffeeScript](#coffeescript)
* [Tutoriais](#tutoriais)
  * [ng-newsletter: AngularJS from beginner to expert in 7 steps series](#ng-newsletter-angularjs-from-beginner-to-expert-in-7-steps-series)
  * [Dailyjs.com: Angular.js](#dailyjscom-angularjs)
  * [Tero Parviainen: Make Your Own AngularJS](#tero-parviainen-make-your-own-angularjs)
  * [One Hungry MindOne Hungry Mind: AngularJS Sticky Notes](#one-hungry-mindone-hungry-mind-angularjs-sticky-notes)
  * [Ciro Nunes: AngularJS Melhores Práticas](#ciro-nunes-angularjs-melhores-práticas)
* [Casos de Uso](#casos-de-uso)
* [Dicas](#dicas)
  * [Design e Interface](#design-e-interface)
  * [SEO](#seo)
  * [HTML5 offline](#html5-offline)
  * [Amazon AWS](#amazon-aws)
  * [Decorator](#decorator)
  * [Dynamic / Lazy Load](#dynamic-lazy-load)
  * [Building Apps](#building-apps)
  * [Google](#google)
    * [Google Spreadsheet](#google-spreadsheet)
    * [Google Analytics](#google-analytics)
  * [Internacionalização](#internacionalização)
  * [Escopo e informações](#escopo-e-informações)
  * [Yeoman, Grunt e Bower](#yeoman-grunt-e-bower)
  * [Upload File(s)](#upload-files)
  * [Autenticação](#autenticação)
  * [Mobile](#mobile)
    * [Ionic](#ionic)
    * [PhoneGap](#phonegap)
  * [Ferramentas](#ferramentas)
    * [Sublime Text](#sublime-text)
    * [Eclipse IDE](#eclipse-ide)
    * [Netbeans IDE](#netbeans-ide)
    * [JetBrains](#jetbrains)
    * [Visual Studio](#visual-studio)
* [Componentes](#componentes)
  * [Diretivas](#diretivas)
  * [Web Components](#web-components)
* [Filters](#filters)
* [Módulos](#módulos)
  * [Módulos de Armazenamento](#módulos-de-armazenamento)
  * [Módulos de Gráficos](#módulos-de-gráficos)
  * [Módulos de UI](#módulos-de-ui)
  * [ng animate](#ng-animate)
* [Projetos de Exemplo](#projetos-de-exemplo)
  * [With Gulp](#with-gulp)
  * [MEAN Stack](#mean-stack)
  * [Angular-Seed](#angular-seed)
* [Teste](#teste)
  * [Mock](#mock)
  * [CI](#ci)

<!-- toc stop -->


## Visão Geral

> **Motivação**
>
> Framework Javascript para desenvolvimento de Front-end com curva de  aprendizado rápida e produtividade similar a encontrada no Adobe Flex.
>


* O [Angular.js](http://angularjs.org/) é um projeto OpenSource, disponível no [GitHub](https://github.com/angular/angular.js), onde seu desenvolvimento e evolução conta com a participação da comunidade, enviando sugestões (código), para evolução, melhorias e correções de eventuais bugs. Conta com equipe dedicada patrocinada pela Google, onde esta tem por responsabilidade cuidar do roadmap, evolução, orquestração da colaboração vinda da comunidade (pull request's no GitHub) e disponibilizar/publicar novas versões do Angular.js.

  * [Story About Angular, Passion and Community (ng-conf 2014)](http://igorminar.github.io/story-about-angular-passion-and-community/) 
    
    * [[GitHub] IgorMinar / story-about-angular-passion-and-community](https://github.com/IgorMinar/story-about-angular-passion-and-community)


* **Curiosidade:** o criador do Angular.js era desenvolvedor Adobe Flex - [Miško Hevery](http://misko.hevery.com/about/)


* O projeto utiliza o Jenkins CI para efetuar os builds [ci.angularjs.org](http://ci.angularjs.org/) | [configurações](https://github.com/angular/ci.angularjs.org)

  * [NodeJS Plugin - Jenkins | Jenkins Wiki](https://wiki.jenkins-ci.org/display/JENKINS/NodeJS+Plugin)

* [[YouTube] Breaking Open: AngularJS. Great interview with Misko Hevery, Angularjs Framework author](https://www.youtube.com/watch?v=X0VsStcCCM8)

* [The Future of AngularJS by @briantford | Google Drive Presentation](https://docs.google.com/presentation/d/1Gv-dvU-yy6WY7SiNJ9QRo9XayPS6N2jtgWezdRpoI04/preview?sle=true#slide=id.p)

* [[YouTube] Angular.js](https://www.youtube.com/user/angularjs)

* [ng-learn](http://ng-learn.org/)

--

* [AngularJS - ng-conf 2014 - Exclusive | ng-learn](http://ng-learn.org/2014/01/NG-CONF-2014/)

* [[YouTube] ng-conf 2014](https://www.youtube.com/user/ngconfvideos)


### Angular.js 2.0

* [AngularJS 2.0 Status and Preview | ng-learn](http://ng-learn.org/2014/03/AngularJS-2-Status-Preview/)


### Estatísticas

* [AngularJS | StackOverflow](http://stackoverflow.com/questions/tagged/angularjs) - mais de 25 mil tópicos

--

* [AngularJS Developer Statistics | LinkedIn](http://www.linkedin.com/groups?groupDashboard=&gid=4896676)

* [Angularjs Jobs | Bullhorn Reach](http://www.bullhornreach.com/jobs/?q=angular)

--

* [[Indeed Job Trends] Angular.js x Backbone.js x Ext.js x Ember.js x Knockout.js](http://www.indeed.com/jobtrends?q=Angular.js%2C+Backbone.js%2C+Ext.js%2C+Ember.js%2C+Knockout.js&l=)

* [[Google Trends] Angular.js x Backbone.js x Ext.js x Ember.js x Knockout.js](https://www.google.com/trends/explore?q=AngularJS%2C+Backbone%2C+ExtJS#q=AngularJS%20%2B%20%22angular.js%22%20%2B%20%22angular%20js%22%2C%20Backbone.JS%20%2B%20%22backbonejs%22%20%2B%20backbone%20js%22%2C%20%22ExtJS%22%20%2B%20%22extjs%22%20%2B%20%22ext.js%22%2C%20EmberJS%20%2B%20%22ember.js%22%20%2B%20%22ember%20js%22%2C%20KnockoutJS%20%2B%20%22knockout.js%22%20%2B%20%22knockout%20js%22&cmpt=q)

--

* [Usage statistics and market share of AngularJS for websites | W3Techs](http://w3techs.com/technologies/details/js-angularjs/all/all)

* [Angular JS Usage Statistics | Build With](http://trends.builtwith.com/javascript/Angular-JS) - Websites using Angular JS

* [Top JavaScript MVC Frameworks | InfoQ](http://www.infoq.com/research/top-javascript-mvc-frameworks)



### Por que utilizar o AngularJS?

HTML é ótimo para documentos declarativos estátivos, porém deixa a  desejar quando se trata de aplicações web. O AngularJS possibilita  extender o vocabulário HTML em sua aplicação. O ambiente que resulta  disso é extraordinariamente expressivo, legível e aumenta a velocidade  do desenvolvimento.

O AngularJS é um conjunto de ferramentas, para construir um framework mais adequado para o desenvolvimento de aplicações.

É totalmente extensível e trabalha bem com outras bibliotecas. Cada  característica do AngularJS pode ser modificada ou substituida conforme a  necessidade do projeto.


--

* [[YouTube] Por quê o AngularJS é tão sensacional](https://www.youtube.com/watch?v=CbBfemKmtAA)

* [Why AngularJS Will Be Huge | The Official Ionic Blog](http://ionicframework.com/blog/angularjs-will-be-huge/)

* [An Overview of AngularJS for Managers | FIFOd](http://fifod.com/an-overview-of-anagularjs-for-managers/)

* [Why Angular.js?](http://jeffwhelpley.com/angularjs/) - 2014/06/09

* [Why Choose AngularJS for Your Next App? | Algoworks](http://www.algoworks.com/blog/angularjs-for-your-next-app/) - 2014/07/31

--

* [3 Reasons to Choose AngularJS for Your Next Project | Nettuts+](http://net.tutsplus.com/tutorials/javascript-ajax/3-reasons-to-choose-angularjs-for-your-next-project/)

* [5 reasons to use AngularJS in the corporate app world | Digital Caveman](http://oscarvillarreal.com/2013/05/07/5-reasons-to-use-angularjs-in-the-corporate-app-world/)

* [5 Reasons to Use (and Love) Angular JS | Jfox015](http://www.jfox015.com/angular-5-reasons-to-use-love/)

* [10 Reasons Why You Should Use AngularJS | SitePoint](http://www.sitepoint.com/10-reasons-use-angularjs/)

* [10 Reasons Web Developers Should Learn AngularJS | Wintellect](http://wintellect.com/blogs/jlikness/10-reasons-web-developers-should-learn-angularjs) - 19/09/2013


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


##### Model

O modelo são os dados da aplicação. O modelo nada mais são que  objetos JavaScript. Não há a necessidade de implementar nenhuma classe  específica do framework.


##### ViewModel

O ViewModel é um objeto que prove dados e métodos específicos para uma determinada View.

No AngularJS o ViewModel é representado pelo objeto `$scope`. O `$scope`  é um objeto JavaScript com um conjunto pequeno de funcionalidades para  monitorar e refletir as alterações nos dados entre a View e o  Controller.


##### Controller

O Controller é responsável por determinar o estado inicial do `$scope` com os métodos e dados utilizados pela View.
Vale  a pena notar que não é responsábilidade do Controller manter o estado  da aplicação, nem interagir(controlar as requisições/respostas) com os  serviços remotos.


##### View

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

* [My Experience With AngularJS - The Super-heroic JavaScript MVW Framework | Ben Nadel](http://www.bennadel.com/blog/2439-My-Experience-With-AngularJS-The-Super-heroic-JavaScript-MVW-Framework.htm) - uma boa representação gráfica, sobre o aprendizado e uso do AngularJS 

* [AngularJS: an Overview | Glenn Stovall](http://glennstovall.com/blog/2013/06/27/angularjs-an-overview/)

* [Why Does Angular.js Rock? | Angular Tips](http://angular-tips.com/blog/2013/08/why-does-angular-dot-js-rock)

* [AngularJS Insights | Pascal Precht](http://pascalprecht.github.io/slides/angularjs-insights/)

* [AngularJS – Presentation | Camilo Lopes](http://blog.camilolopes.com.br/angularjs-presentation/)

* [[SlideShare] Beginner workshop to angularjs presentation at Google](http://www.slideshare.net/therealauser/beginner-workshop-to-angularjs-presentation-at-google)

--

* [Angular Docs Guide](http://docs.angularjs.org/guide/)

* [Angular Docs Tutorial](http://docs.angularjs.org/tutorial/)

--

* [AngularJS Cheat Sheet](http://www.cheatography.com/proloser/cheat-sheets/angularjs/)

--

* [Recipes with Angular.js](http://fdietz.github.io/recipes-with-angular-js/) - A community project dedicated to collecting resources for the Angular.js framework. You find here easy to follow cookbook style recipes for issues you are likely to face when working with Angular.js.

* [[GitHub] timjacobi / angular-education](https://github.com/timjacobi/angular-education) - A collection of useful resources to learn and improve your AngularJS skills

--

* [[GitHub] nicholasess / angularjsbrasil / iniciantes.md](https://github.com/nicholasess/angularjsbrasil/blob/master/iniciantes.md)

* [[GitHub] mgechev / angularjs-style-guide](https://github.com/mgechev/angularjs-style-guide) - Community-driven set of best practices for AngularJS application development

* [[GitHub] johnpapa / angularjs-styleguide](https://github.com/johnpapa/angularjs-styleguide) - AngularJS Style Guide: A starting point for AngularJS development teams to provide consistency through good practices

--

* [The Ultimate Guide to Learning AngularJS in One Day | Todd Motto](http://toddmotto.com/ultimate-guide-to-learning-angular-js-in-one-day/)

  * [Guia Definitivo para Aprender AngularJS em Um Dia | Javascript Brasil](http://javascriptbrasil.com/2013/10/18/guia-definitivo-para-aprender-angularjs-em-um-dia/)

--

* [AngularJS - Where To Start?](http://blog.whydoifollow.com/post/angularjs-where-to-start)

* [The Angular Course](http://www.angularcourse.com/) - When you're done, you'll have full web app built with AngularJS, Firebase, Twilio, and Zapier.

* [Shaping up with Angular.js : Free CodeSchool Course](http://campus.codeschool.com/courses/shaping-up-with-angular-js/intro)

* [Egghead - AngularJS](http://egghead.io/) - curso online

* [Hands-on Angular | Tuts+](https://tutsplus.com/course/hands-on-angular/) - curso online

* [Learn AngularJS this Weekend | @jhooks](http://joelhooks.com/blog/2013/08/03/learn-angularjs-in-a-weekend/)

* [A Better Way to Learn AngularJS | Thinkster](http://www.thinkster.io/pick/51d287681e4b9c9098000013/a-better-way-to-learn-angularjs)

* [AngularJS Tutorial: Learn to build modern web apps | Thinkster](http://www.thinkster.io/pick/GUIDJbpIie/)

* [Aprenda AngularJS com estes 5 Exemplos Práticos | Javascript Brasil](http://javascriptbrasil.com/2013/10/23/aprenda-angularjs-com-estes-5-exemplos-praticos/)

* [Getting started with AngularJS | Adobe Developer Connection](http://www.adobe.com/devnet/html5/articles/getting-started-with-angularjs.html)

--

* [AngularJS in 60-ish Minutes – The eBook | Dan Wahlin](http://weblogs.asp.net/dwahlin/archive/2013/07/30/angularjs-in-60-ish-minutes-the-ebook.aspx)

* [Practical AngularJS | Leanpub](https://leanpub.com/Practical_AngularJS) - by Dinis Cruz. Real-world examples of using AngularJS in multiple scenarios and platforms (KarmaJS, Firebase, Eclipse, WebStorm, O2 Platform)

  * [Read online : Practical AngularJS | Leanpub](https://leanpub.com/Practical_AngularJS/read)

--

* [AngularJS for .NET Developers | henriquat.re](http://henriquat.re/) - a continuously deployed ebook

* [ASP.NET MVC and Angular JS with Scott Allen](http://tv.ssw.com/3061/asp-net-mvc-and-angular-js)

* [[YouTube] March - AngularJS MTV Meetup Livestream: CRUD Apps with Angular and Breeze](https://www.youtube.com/watch?v=P2ErSQj3SN8)

* [Building a Single Page Application with ASP.NET and AngularJS | Build 2014 - Channel 9](http://channel9.msdn.com/Events/Build/2014/3-644)

--

* [Atomic Design Behavior com AngularJS | Nomadev](http://nomadev.com.br/atomic-design-com-angularjs/)

--

* [Angular.js : Advanced Design Patterns and Best Practices](http://trochette.github.io/Angular-Design-Patterns-Best-Practices/)

* [A small introduction to AngularJS : data-binding, IoC/DI, directives](http://derkoe.github.io/presentations/angularjs-intro/)

* [Use AngularJS to power your web application | Year of Moo](http://www.yearofmoo.com/2012/08/use-angularjs-to-power-your-web-application.html)

* [More AngularJS Magic to Supercharge your Webapp | Year of Moo](http://www.yearofmoo.com/2012/10/more-angularjs-magic-to-supercharge-your-webapp.html)

* [An AngularJS Adventure Anthology | Angular Cats!](http://ericterpstra.com/2012/09/angular-cats-an-angularjs-adventure-anthology/)

* [Tunando o browser com AngularJS | DevCast](http://devcastbrasil.com/videos/tunando-o-browser-com-angularjs/)

* [Angular.js Views and Controllers | Backlift Blog](https://blog.backlift.com/entry/angular-tut1)

--

* [[YouTube] Google I/O 2013 - Design Decisions in AngularJS](https://www.youtube.com/watch?v=HCR7i5F5L8c)

* [[YouTube] Re-Imagining the Browser with AngularJS](https://www.youtube.com/watch?v=ersEb9vTX3Y)

* [[YouTube] AngularJS MTV Meetup: Best Practices (2012/12/11)](https://www.youtube.com/watch?v=ZhfUv0spHCY)

* [[YouTube] Writing Directives](https://www.youtube.com/watch?v=WqmeI5fZcho)

* [YouTube] AngularJS end-to-end web app tutorial - .Net [Part I](https://www.youtube.com/watch?v=Ja2xDrtylBw) | [Part II](https://www.youtube.com/watch?v=6WbVn_gYwQo) | [Part IIII](https://www.youtube.com/watch?v=ilCH2Euobz0)

--

* [Interesting Bits 8 - Angular Js](http://blog.rodolfocaldeira.com/2013/05/24/interesting-bits-8-angularjs.html) - A collection of some really useful AngularJs links.

* [Things I Wish I Were Told About Angular.js | Ruoyu Sun's](http://ruoyusun.com/2013/05/25/things-i-wish-i-were-told-about-angular-js.html)

* [[GitHub] jmcunningham / AngularJS-Learning](https://github.com/jmcunningham/AngularJS-Learning) - A bunch of links to blog posts, articles, videos, etc for learning AngularJS

* [Learn AngularJS With These 5 Practical Examples | Tutorialzine](http://tutorialzine.com/2013/08/learn-angularjs-5-examples/)

--

* [Writing an AngularJS App with Socket.IO | HTML5 Rocks](http://www.html5rocks.com/en/tutorials/frameworks/angular-websockets/)

* [$q | Angularjs Docs](http://docs.angularjs.org/api/ng.$q)

  * [Promises in AngularJS, Explained as a Cartoon | Andy Shora](http://andyshora.com/promises-angularjs-explained-as-cartoon.html)

  * [A Simple Visual Model for Promises | Flippin' Awesome](http://flippinawesome.org/2013/10/14/a-simple-visual-model-for-promises/)

  * [Promises in AngularJS | Radu's blog](http://wooptoo.com/blog/promises-in-angularjs/)

  * [Understanding Promises in Angular | Bilal Quadri](http://bilalquadri.com/blog/2014/05/18/understanding-promises-in-angular/)

  * [AngularJS Promises - The Definitive Guide | dwmkerr](http://www.dwmkerr.com/promises-in-angularjs-the-definitive-guide/)

    * [AngularJS Promises - O guia definitivo | Nomadev](http://nomadev.com.br/angularjs-promises-promessas-o-guia-definitivo/)

--

* [Creating a Single Page Todo App with Node and Angular | Scotch](http://scotch.io/tutorials/javascript/creating-a-single-page-todo-app-with-node-and-angular)

* [A Step-by-Step Guide to Your First AngularJS App | Toptal](http://www.toptal.com/angular-js/a-step-by-step-guide-to-your-first-angularjs-app)

* [Angular for the jQuery developer | ng-newsletter](http://www.ng-newsletter.com/posts/angular-for-the-jquery-developer.html)


### CoffeeScript

* [CoffeeScript and AngularJS | Alexander Hill](http://alxhill.com/blog/articles/angular-coffeescript/)


## Tutoriais

* [How to Learn AngularJS - Your AngularJS Sherpa | ng-newsletter](http://www.ng-newsletter.com/posts/how-to-learn-angular.html)

* [25 days of AngularJS Calendar - 2013 | ng-newsletter](http://www.ng-newsletter.com/advent2013) - The short, juicy guide of AngularJS information, designed to get you up and running without the fluff.

* [Building the 2048 game in AngularJS | ng-newsletter](http://www.ng-newsletter.com/posts/building-2048-in-angularjs.html)

* [Build a Single Page Application with Angular, Node & Mongo – Part I | Kevin Delemme](http://www.kdelemme.com/2014/06/16/build-single-page-app-with-angular-node-mongo-i/)

* [[YouTube] AngularJS Tutorial for Beginners - Learn Angular.js using UI-Router](https://www.youtube.com/watch?v=QETUuZ27N0w) - 19/12/2013 - [Working Angularjs Code Sample on Plunkr](http://plnkr.co/tZg6EfbMCJX1MLtUAcb1)

* [[YouTube Playlist] Pluralsight: AngularJS Fundamentals](https://www.youtube.com/playlist?list=PL1yxeQRU9I3TFalCPrYmCptJtCowJNi6C) - Full course


### ng-newsletter: AngularJS from beginner to expert in 7 steps series 

* [Part 1: How to get started](http://www.ng-newsletter.com/posts/beginner2expert-how_to_start.html)

* [Part 2: Scopes](http://www.ng-newsletter.com/posts/beginner2expert-scopes.html)

* [Part 3: Data binding and AJAX](http://www.ng-newsletter.com/posts/beginner2expert-data-binding.html)

* [Part 4 - 5: Directives - Expressions](http://www.ng-newsletter.com/posts/beginner2expert-directives.html)

* [Part 6: Services](http://www.ng-newsletter.com/posts/beginner2expert-services.html)

* [Part 7: Next steps](http://www.ng-newsletter.com/posts/beginner2expert-config.html)


### Dailyjs.com: Angular.js

* [Part 1: Google, Twitter, and AngularJS](http://dailyjs.com/2013/04/11/angularjs-1/)

* [Part 2: Let's Make a Feed Reader](http://dailyjs.com/2013/04/18/angularjs-2/)

* [Part 3: Rendering Feeds](http://dailyjs.com/2013/04/25/angularjs-3/)

* [Part 4: Managing Feeds](http://dailyjs.com/2013/05/09/angularjs-4/)

* [Part 5: Tests](http://dailyjs.com/2013/05/16/angularjs-5/)

* [Part 6: Adding Dependencies](http://dailyjs.com/2013/05/30/angularjs-6/)

* [Part 7: Form Validation](http://dailyjs.com/2013/06/06/angularjs-7/)

* [Part 8: Iterators and Data](http://dailyjs.com/2013/06/13/angularjs-8/)


### Tero Parviainen: Make Your Own AngularJS

* [Part 1: Scopes And Digest](http://teropa.info/blog/2013/11/03/make-your-own-angular-part-1-scopes-and-digest.html)


### One Hungry MindOne Hungry Mind: AngularJS Sticky Notes

* [Pt 1 - Architecture](http://onehungrymind.com/angularjs-sticky-notes-pt-1-architecture/)

* [Pt 2 - Isolated Scope](http://onehungrymind.com/angularjs-sticky-notes-pt-2-isolated-scope/)


### Ciro Nunes: AngularJS Melhores Práticas

* [Parte I: Iniciando Um Projeto](http://cironunes.github.com/angularjs-melhores-praticas-parte-I-bootstrap/)


## Casos de Uso

* [Aplicações construídas com Angular.js](http://builtwith.angularjs.org/)

* [Likeastore](https://likeastore.com/) - Social bookmarking for geeks with storage to collect and organize all your favorites. | [[GitHub] likeastore](https://github.com/likeastore)

* [Using AngularJS at Localytics](http://www.localytics.com/blog/2013/angularjs-at-localytics/) - This is the story of how we rewrote our Backbone-powered web  application in AngularJS, using nearly half the number of lines of code.  (It is a love story.)

* [How to build a large Angular.js application | GoCardless](https://gocardless.com/blog/building-a-large-angular-application/)

* [Tyto.io](http://tyto.io/) - A simple mobile framework powered by Angular.js | [[YouTube] Introduction to Tyto](https://www.youtube.com/watch?v=jiyMZLXGraw)

* [AngularJS Calculator Demo](http://www.thomporter.com/apps/angularjs_calc) - A calculator built with AngularJS, written in CoffeeScript

* [Extensionizr](http://extensionizr.com/) - Generate Chrome Extensions with AngularJS. Extensionizr helps you create the basis for your own awesome chrome extension!

* [Kodigon](http://www.yrezgui.com/kodigon) - is a webapplication which encode and decode (if possible) text or files in many algorithm formats lke Base64, MD5, SHA1, etc.

* [Plunker](http://plnkr.co/) - is an online community for creating, collaborating on and sharing your web development ideas.
  
* [[GitHub] matthiasn / BirdWatch](https://github.com/matthiasn/BirdWatch) - Tweet stream analysis and visualization using AngularJS, Bootstrap, D3.js, ElasticSearch and Play Framework | [Blog post](http://matthiasnehlsen.com/blog/2013/08/13/birdwatch-angularjs-elasticsearch-play/)

* [uFun](http://ufun.coderockr.com/) - é a maneira mais divertida de você encontrar e compartilhar seus sound memes favoritos

--

* [AngularFire](http://angularfire.com/) - A real-time backend for AngularJS from [Firebase](https://www.firebase.com/)

  * [AngularJS Tutorial: Learn to Rapidly Build Real-time Web Apps with Firebase | Thinkster](http://www.thinkster.io/pick/eHPCs7s87O/angularjs-tutorial-learn-to-rapidly-build-real-time-web-apps-with-firebase)

* [Embedding AngularJS in the physical world | ng-newsletter](http://www.ng-newsletter.com/posts/embedded-angular.html)

* [Remote Desktop Client with AngularJS and Yeoman](http://blog.mgechev.com/2014/02/08/remote-desktop-vnc-client-with-angularjs-and-yeoman/)

* [[GitHub] mgcrea / angular-7min](https://github.com/mgcrea/angular-7min) - Angular Seven Minute Workout sample mobile app w/ Cordova

* [[GitHub] CapMousse / AngularTracker](https://github.com/CapMousse/AngularTracker) - Small time tracker built with AngularJS | i18n support

* [Adobe Open Source](http://adobe.github.io/)

  * [[GitHub] adobe / adobe.github.com](https://github.com/adobe/adobe.github.com) - Adobe central hub for open source


## Dicas

* [The AngularJS Magazine | Flipboard](https://flipboard.com/section/the-angularjs-magazine-bP12ur) - All about AngularJS! Tweet article suggestions to @DanWahlin.

  * [The AngularJS Magazine – What’s New this Week? | Dan Wahlin](http://weblogs.asp.net/dwahlin/archive/2013/08/23/the-angularjs-magazine-what-s-new-this-week.aspx)

* [AngularJS Daily](http://www.angularjsdaily.com/) - Get more out of AngularJS

--

* [[Android App] AngularJS Pocket Reference](https://play.google.com/store/apps/details?id=com.angularpocketreference.app&amp;amp;hl=en)

--

* [AngularJS Tips and Tricks | AngularJS Chicago](http://angularjschicago.github.io/angular-tips-and-tricks/) - Created by the AngularJS Chicago Meetup community

* [Speeding up AngularJS with simple optimizations | JavaScript](http://www.binpress.com/tutorial/speeding-up-angular-js-with-simple-optimizations/135)

--

* [Conjunto de materiais úteis](http://mattkruse.com/angular/) - PDFs

* [Angular.js Demos, Examples, and Resources | TechSlides](http://techslides.com/angular-js-demos-examples-and-resources/)

* [AngularJS Best Practices | Jaco Pretorius](http://www.jacopretorius.net/2013/07/angularjs-best-practices.html)

* [8 Tips for Angular.js Beginners](http://vxtindia.com/blog/8-tips-for-angular-js-beginners/)

* [Fun with AngularJS | Holly Schinsky](http://devgirl.org/2013/03/21/fun-with-angularjs/)

* [AngularJS Tips and Tricks](http://deansofer.com/posts/view/14/AngularJs-Tips-and-Tricks-UPDATED)

* [Angular.js JSFiddle Examples](https://github.com/angular/angular.js/wiki/JSFiddle-Examples)

--

* [Como mudar os {{ }} do AngularJs para usar em um template que já use a mesma marcação? | Nomadev](http://nomadev.com.br/como-mudar-os-%7B%7B-%7D%7D-do-angularjs-para-usar-em-um-template-que-j%C3%A1-use-a-mesma-marca%C3%A7%C3%A3o/)

--

* [AngularJS | One Hungry MindOne Hungry Mind](http://onehungrymind.com/category/angularjs/) - A ton of great AngularJS content here

* [Write Better, Flexible Code By Using Composition In Angular.js | I ♥ Angular.js](http://iheartangularjs.com/post/66604936242/composition-in-angularjs)

--

* [AngularJS: Decisions, Decisions & My Preferred Choices | The Code Dump](http://www.codelord.net/2014/05/26/angularjs-decisions-decisions-and-my-choices/)

* [AngularJS: Clearing a few confusion points | Next Big Thing](http://blog.nebithi.com/angularjs-clearing-a-few-confusion-points/)

* [4 Smooth AngularJS Application Tips | Nathan Leclaire](http://nathanleclaire.com/blog/2014/01/04/5-smooth-angularjs-application-tips/)

--

* [Logging Client-Side Errors With AngularJS And Stacktrace.js | The Blog Of Ben Nadel](http://www.bennadel.com/blog/2542-Logging-Client-Side-Errors-With-AngularJS-And-Stacktrace-js.htm) - Ben Nadel demonstrates how he logs errors in his AngularJS applications using Stacktrace.js, and how he posts the error data to his server

* [Better Error Handling In AngularJS | Ode To Code](http://odetocode.com/blogs/scott/archive/2014/04/21/better-error-handling-in-angularjs.aspx)

--

* [Communication in Angular using the pubsub pattern | Per Ploug](http://scriptogr.am/pploug/post/communication-in-angular-using-the-pubsub-pattern)

--

* [An angular.js event bus with postal.js | Jonathan Creamer](http://jonathancreamer.com/an-angular-event-bus-with-postal-js/)

--

* [AngularJS - Providers | Thinkster](http://www.thinkster.io/angularjs/eIaGNOAlOk/angularjs-providers)

* [The life and times of the angular provider | Garabagne](http://www.garabagne.io/2014/06/08/the-life-and-times-of-the-angular-provider/)

* [understanding service types | Angular Tips](http://angular-tips.com/blog/2013/08/understanding-service-types/)

* [Entendendo os tipos de Serviços do AngularJS | pedronauck.com](http://pedronauck.com/angularjs/entendendo-os-tipos-de-servico-do-angularjs)

* [[YouTube] AngularJS Factory vs. Service](https://www.youtube.com/watch?v=A6cJasNBkyI)

* [Angular service or factory? | Iffy Can](http://iffycan.blogspot.com.br/2013/05/angular-service-or-factory.html)

* [[Gist] Difference between Service, Factory and Provider in AngularJS](https://gist.github.com/Mithrandir0x/3639232)

* [Differences Between Providers in AngularJS | Xebia Blog](http://blog.xebia.com/2013/09/01/differences-between-providers-in-angularjs/)

* [Service Providers in AngularJS and Logger Implementation | Web Development is Easy!](http://www.webdeveasy.com/service-providers-in-angularjs-and-logger-implementation/)

  * [[GitHub] naorye / angular-ny-logger](https://github.com/naorye/angular-ny-logger) - AngularJS Logger service provider

--

* [[GitHub] davej / angular-classy](https://github.com/davej/angular-classy) - Cleaner class-based controllers with Angular

--

* [Rethinking AngularJS Controllers | Todd Motto](http://toddmotto.com/rethinking-angular-js-controllers/)

* [When to use directives, controllers, or services in Angular JS | Kirk Bushell](http://kirkbushell.me/when-to-use-directives-controllers-or-services-in-angular/)

* [Understanding Angular.js services the easy way | Jonathan Creamer](http://jonathancreamer.com/understanding-angular-js-services-the-easy-way/)

* [Primer on AngularJS Services | Michael Herman](http://mherman.org/blog/2014/06/12/primer-on-angularjs-service-types/)

* [Object-oriented AngularJS Services | revolunet blog](http://blog.revolunet.com/blog/2014/02/14/angularjs-services-inheritance/)

* [How to create (singleton) AngularJS services in 4 different ways | JDriven BlogJDriven Blog](http://blog.jdriven.com/2013/03/how-to-create-singleton-angularjs-services-in-4-different-ways/)

* [Using an AngularJS Factory to Interact with a RESTful Service | Dan Wahlin](http://weblogs.asp.net/dwahlin/archive/2013/08/16/using-an-angularjs-factory-to-interact-with-a-restful-service.aspx)

* [Configuring Dependency Injection in AngularJS | @jhooks](http://joelhooks.com/blog/2013/08/18/configuring-dependency-injection-in-angularjs/)

* [Demystifying AngularJS' dependency injection | bdadam.com](http://bdadam.com/blog/demistifying-angularjs-dependency-injection.html)

* [AngularJS Best Practices #001: Constants | Two Fucking Developers](http://twofuckingdevelopers.com/2014/06/angularjs-best-practices-001-constants/)

--

* [Angular backed SVGs](http://gaslight.co/blog/angular-backed-svgs)

* [D3.js on AngularJS | ng-newsletter](http://www.ng-newsletter.com/posts/d3-on-angular.html) | [[GitHub] EpiphanyMachine / d3AngularIntegration](https://github.com/EpiphanyMachine/d3AngularIntegration) - A tutorial about the integration of d3 and Angular Directives

* [Slides from my Angular + D3 meetup talk at Google](https://vicapow.github.io/angular-d3-talk/slides/) - by @vicapow

  * [[GitHub] vicapow / angular-d3-talk](https://github.com/vicapow/angular-d3-talk)

* [Replacing (most of) d3.js with pure SVG + AngularJS | Alexandros Marinos](http://alexandros.resin.io/angular-d3-svg/)

* [[YouTube] AngularJS & D3: Directives for Visualizations](http://www.youtube.com/watch?v=aqHBLS_6gF8)

* [Facebook’s New React JavaScript Library Tutorial Rewritten in AngularJS | Medium](https://medium.com/make-your-own-apps/e71bcedc36b)

--

* [Source Modification With r.js | Merrick Christensen](http://merrickchristensen.com/articles/build-angular-with-requirejs.html) - An overview of source modification with r.js. Using ngmin and Angular.js as an example. (Require.js)

* [AngularJS: Performance basics | Alexey Migutsky](http://www.fse.guru/angularjs-performance-basics)

* [AngularJS: Performance tips | Alexey Migutsky](http://www.fse.guru/angularjs-performance-tips)

--

* [AngularJS Video Tutorial: Using angular.bootstrap to Initialize Your App | EggHead.io](http://egghead.io/lessons/angularjs-angular-bootstrap-app-init)

* [Form validation with AngularJS](http://www.ng-newsletter.com/posts/validations.html)

* [[SlideShare] Forms in AngularJS](http://www.slideshare.net/EyalV/forms-in-angularjs)

* [AngularJS Form Validation | Scotch](http://scotch.io/tutorials/javascript/angularjs-form-validation)

* [[GitHub] kelp404 / angular-validator](https://github.com/kelp404/angular-validator) - AngularJS form validation

* [AngularJS Multi-Step Form Using UI Router | Scotch](http://scotch.io/tutorials/javascript/angularjs-multi-step-form-using-ui-router)

* [Random tricks when using AngularJS](http://blog.tomaka17.com/2012/12/random-tricks-when-using-angularjs/) 

* [input radio | Angular Docs](http://docs-angularjs-org-dev.appspot.com/api/ng.directive:input.radio)

* [input radio dinâmico | jsFiddle](http://jsfiddle.net/hgxjv/4/)

* [AngularJS and Radio Buttons | Sudo Zest](http://www.mpdaugherty.com/blog/angularjs-and-radio-buttons/)

* [Wallop Slider in AngularJS | Andy Shora](http://techslides.com/angular-js-demos-examples-and-resources/)

* [Responsive template swapping with Angular Directives | CheapSteak.net](http://cheapsteak.net/posts/responsive-template-swapping-with-angular)

* [Removing the unneeded watches | Angular Tips](http://angular-tips.com/blog/2013/08/removing-the-unneeded-watches/)

* [Deep-Watching Circular Data Structures in Angular | Small Improvements](http://tech.small-improvements.com/2014/06/11/deep-watching-circular-data-structures-in-angular/)

* [Group and Display Data with Underscore and AngularJS | OdeToCode](http://odetocode.com/blogs/scott/archive/2013/08/08/group-and-display-data-with-underscore-and-angularjs.aspx)

* [Displaying json array data with AngularJS and ng-grid | Genlinux.rb](http://www.genlinux.org/2013/08/displaying-json-array-data-with-angular.html)

* [Breaking the Ice with AngularUI Utils | ng-newsletter](http://www.ng-newsletter.com/posts/angular-ui-utils.html) - creditcard parsing, custom events, maps, and an easter egg

* [Understanding Angular's Magic: Don't Bind to Primitives | The Code Dump](http://www.codelord.net/2014/05/10/understanding-angulars-magic-dont-bind-to-primitives/)

--

* [Faster AngularJS Rendering (AngularJS and ReactJS) | thierry.nicola](http://www.williambrownstreet.net/blog/2014/04/faster-angularjs-rendering-angularjs-and-reactjs/)

* [Using React for Faster Renders and Isomosphism in Angular | David and Suzi](http://davidandsuzi.com/using-react-for-faster-renders-and-isomorphism-in-angular/)

* [Why I stopped using ng-grid and rolled my own with ReactJS | Jose Garcia](http://www.josebalius.com/why-i-stopped-using-ng-grid-and-rolled-my-own-with-reactjs/)

* [ngReactGrid - An AngularJS grid using ReactJS to render | Jose Garcia](http://www.josebalius.com/ngreactgrid-an-angularjs-grid-using-reactjs-to-render/)

* [React PhoneCat: Rewriting the AngularJS Tutorial App in React | Jonas Gebhardt's Notes](https://jgebhardt.github.io/blog/react-phonecat/)

* [Integrating Components with D3 and AngularJS | egghead.io](https://egghead.io/lessons/integrating-components-with-d3-and-angularjs) - Since React is only interested in the V (view) of MVC, it plays well with other toolkits and frameworks. This includes AngularJS and D3.

--

* [Integrating Parse Data with ng-model in AngularJS | Jonathan Broquist](http://blog.jonathanbroquist.com/integrating-parse-data-with-ng-model-in-angularjs/)

--

* [Escaping the AngularJS route | Simon Friis Vindum](http://vindum.io/escape-the-angularjs-router/)

--

* [Busca no Jekyll usando AngularJS | Frelleto Blog](http://blog.frelleto.com.br/javascript/angularjs/2013/08/10/busca-no-jekyll-usando-angularjs/)

* [Searching the iTunes API asynchronously with AngularJS | John Philip Morgan](http://blog.jpamorgan.com/searching-the-itunes-api-asynchronously-with-angular-js/)

--

* [[GitHub] karlgoldstein / grunt-html2js](https://github.com/karlgoldstein/grunt-html2js) - Grunt plugin for converting AngularJS templates to JavaScript

--

* [AngularJS + Cloud Endpoints: A Recipe for Building Modern Web Applications | Cloud Platform](https://cloud.google.com/resources/articles/angularjs-cloud-endpoints-recipe-for-building-modern-web-applications)

* [Laravel 4 & AngularJS E2E secured SPA | Neoxia.com](http://blog.neoxia.com/laravel4-and-angularjs/) | [[GitHub] neoxia / laravel4-angularjs-security](https://github.com/neoxia/laravel4-angularjs-security)

--

* [Restangular on Angular | ng-newsletter](http://www.ng-newsletter.com/posts/restangular.html)

--

* [[GitHub] scalyr / angular](https://github.com/scalyr/angular) - Code to optimize AngularJS for complex pages

--

* [Creating Asynchronous Alerts, Prompts, And Confirms In AngularJS | Ben Nadel](http://www.bennadel.com/blog/2632-creating-asynchronous-alerts-prompts-and-confirms-in-angularjs.htm)

--

* [Preventing default action for an element in AngularJS](http://blog.falafel.com/Blogs/venkata-koppaka/2014/04/28/preventing-default-action-for-an-element-in-angularjs)

--

* [Generic HTTP Error Handling in AngularJS | The Code Dump](http://www.codelord.net/2014/06/25/generic-error-handling-in-angularjs/)

* [Preventing duplicated requests in Angular.js | Codebrag](http://blog.codebrag.com/post/57412530001/preventing-duplicated-requests-in-angularjs)

* [Aborting AJAX Requests Using $http And AngularJS | Ben Nadel](http://www.bennadel.com/blog/2616-aborting-ajax-requests-using-http-and-angularjs.htm)

* [AngularJS – Cross Domin Get data by $resource | Share Coding](http://sharecoding.wordpress.com/2013/09/02/angularjs-cross-domin-get-data-by-resource/)

* [[Gist] AngularJS Lesson Learned #1: Getting Invalid Session State | Mário Junior](https://gist.github.com/mariojunior/6175736)

* [[Gist] AngularJS Lesson Learned #2: Enabling HTTP Credentials | Mário Junior](https://gist.github.com/mariojunior/6175849)

--

* [Using Spring MVC and Angular? You might need this | Jose Garcia](http://www.josebalius.com/using-spring-mvc-and-angular-you-might-need-this/) - tips for legacy applications


### Design e Interface

* [[GitHub] angular / material](https://github.com/angular/material) - Material design for Angular

* [[GitHub] Ehesp / Responsive-Dashboard](https://github.com/Ehesp/Responsive-Dashboard) - Bloat free responsive dashboard - powered by AngularJS and Bootstrap (jQuery version available)


### SEO

* [What you need to know about Angular SEO | ng-newsletter](http://www.ng-newsletter.com/posts/serious-angular-seo.html)

* [AngularJS SEO | CoderWall - Jose Raya](https://coderwall.com/p/vqpfka)

* [DIY AngularJS SEO with PhantomJS (the easy way!)](http://lawsonry.com/2014/05/diy-angularjs-seo-with-phantomjs-the-easy-way/)

* [AngularJS & SEO - finally a piece of cake | weluse GmbH](https://weluse.de/blog/angularjs-seo-finally-a-piece-of-cake.html)

* [How to make AngularJS awesome with SEO | Ultimate web tips](http://www.tweetganic.com/a/331717)


### HTML5 offline

* [AngularJS IndexedDB Demo | HTML5 Zone](http://java.dzone.com/articles/angularjs-indexeddb-demo)

  * [AngularJS IndexedDB Demo | Raymond Camden](http://www.raymondcamden.com/index.cfm/2014/2/7/AngularJS-IndexedDB-Demo)


### Amazon AWS

* [AWS JS SDK - The Canonical Angular Guide | ng-newsletter](http://www.ng-newsletter.com/posts/aws-js-sdk.html)

  * [A Developer Preview of an AWS SDK for JavaScript in the Browser | Amazon Web Services Blog](http://aws.typepad.com/aws/2013/10/developer-preview-aws-sdk-for-javascript.html)

* [Demos using AWS with Node.JS and an AngularJS frontend | RecursiveRobot](http://www.recursiverobot.com/post/75281512146/demos-using-aws-with-node-js-and-an-angularjs-frontend)


### Decorator

* [Enhancing AngularJS $log using Decorators | The Solution Optimist](http://solutionoptimist.com/2013/10/07/enhance-log-using-angularjs-decorators/)

* [Experiment: decorating directives | Angular Tips](http://angular-tips.com/blog/2013/09/experiment-decorating-directives/)

* [Modifying the behavior of AngularJS’ core services | CLI nerd](http://www.cli-nerd.com/blog/2014/05/08/%24provide-dot-decorator/) - $provide.decorator()


### Dynamic / Lazy Load

* [[SlideShare] Angularjs - lazy loading techniques](http://www.slideshare.net/nirkaufman/angularjs-lazy-loading-techniques)

  * [[GitHub] nirkaufman / lazyLoadingDemo](https://github.com/nirkaufman/lazyLoadingDemo) - Demo project

  * [[GitHub] ocombe / ocLazyLoad](https://github.com/ocombe/ocLazyLoad) - Load modules on demand (lazy load) in AngularJS

* [[GitHub] marcoslin / angularAMD](https://github.com/marcoslin/angularAMD) - Facilitate use of RequireJS in AngularJS

* [Dynamically Loading Controllers and Views with AngularJS and RequireJS | Dan Wahlin](http://weblogs.asp.net/dwahlin/archive/2013/05/22/dynamically-loading-controllers-and-views-with-angularjs-and-requirejs.aspx)

* [Lazy Loading In AngularJS | IFY I/O](http://ify.io/lazy-loading-in-angularjs/)

* [[GitHubb] mikeromano38 / angular-async](https://github.com/mikeromano38/angular-async) - a module for asynchronous loading of angular components


### Building Apps

* [Building a Web App From Scratch in AngularJS | Nettuts+](http://net.tutsplus.com/tutorials/javascript-ajax/building-a-web-app-from-scratch-in-angularjs/)

* [[SlideShare] Building Better Web Apps with Angular.js (SXSW 2014)](http://www.slideshare.net/kbekessy/angular-js-sxsw2014)

--

* [Code Organization in AngularJS | Nulogy Blog](http://engineering.nulogy.com/posts/code-organization-in-angular/)

* [How to build a large Angular.js application | GoCardless](https://gocardless.com/blog/building-a-large-angular-application/)

* [Code Organization in Large AngularJS and JavaScript Applications | Cliff Meyers](http://cliffmeyers.com/blog/2013/4/21/code-organization-angularjs-javascript)

* [Building Huuuuuge Apps with AngularJS | Brian Ford](http://briantford.com/blog/huuuuuge-angular-apps.html)

* [13 Steps to AngularJS Modularization | Safari Books Online's Official Blog](http://blog.safaribooksonline.com/2014/03/27/13-step-guide-angularjs-modularization/)

* Jason Dobry

  * [Building large apps with Angular.js | Tech Pro](http://tech.pro/tutorial/1699/building-large-apps-with-angularjs)

  * [[Slid.es] Building LARGE apps with Angular.js](http://slid.es/jdobry/building-large-apps-with-angularjs)


* [How to structure large angularJS applications | Entwicklertagebuch](http://entwicklertagebuch.com/blog/2013/10/how-to-structure-large-angularjs-applications/)

* [Angular Structure: Refactoring for Growth | John Papa](http://www.johnpapa.net/angular-growth-structure/)

* [[YouTube] Writing a Massive Angular App at Google NG Conf](https://www.youtube.com/watch?v=62RvRQuMVyg) - Discuss the main technical challenges and solutions for large AngularJS applications. Learn about the main code reuse patterns and when to use them, going beyond AngularJS' $resource service for custom server communication, authorization, conditional feature loading, and more.

--

* [Simple Intro to AngularJS Web Application Development](http://blog.dewmap.com/post/51353fa6717c080200000001)

* [Building a Spreadsheet in 20 Minutes with Angular.js | Thomas Street](http://thomasstreet.net/blog/spreadsheet.html)

* [Single Page Application with Angular.js, Node.js and MongoDB (MongoJS Module) | Technical Blogs](http://www.phloxblog.in/single-page-application-angular-js-node-js-mongodb-mongojs-module/)

* [Single Page Application with Angular.js, Node.js and NeDB (NeDB Module)  | Technical Blogs](http://www.phloxblog.in/single-page-application-angular-js-node-js-nedb-nedb-module/)

* [Single Page Application with Angular.js, Node.js and CouchDB (Cradle Module) | Technical Blogs](http://www.phloxblog.in/single-page-application-angular-js-node-js-couchdb-cradle-module/)

* [AngularJS collaboration board with Socket.io | Tutorial | .net magazine](http://www.netmagazine.com/tutorials/angularjs-collaboration-board-socketio)

* [Home Automation with AngularJS and node.js on a Raspberry Pi | codecentric Blogcodecentric Blog](https://blog.codecentric.de/en/2013/03/home-automation-with-angularjs-and-node-js-on-a-raspberry-pi/)


### Google

* [Build Apps with AngularJS | Google Chrome Apps](http://developer.chrome.com/trunk/apps/angular_framework.html)

* [AngularJs web app with Google Cloud Storage backend service | dev.yathit.com](http://dev.yathit.com/tutorial/angular-js-gcs-backend.html)


#### Google Spreadsheet

* [Google Spreadsheets API | Google Developers](https://developers.google.com/google-apps/spreadsheets/)

* [Simple example of retrieving JSON feeds from Spreadsheets Data API | Google Developers](https://developers.google.com/gdata/samples/spreadsheet_sample)

--

* [Como usar uma planilha como backend JSON | Blog da Concrete](http://blog.concretesolutions.com.br/2014/07/como-usar-uma-planilha-como-backend-json/) | [exemplo no JSFiddle](http://jsfiddle.net/jfelipesp/eg4PB/)

* [How To Use Google Doc Serve JSON From Excel Spreadsheet | Next of Windows](http://www.nextofwindows.com/how-to-use-google-doc-spreadsheet-serve-json-from-excel-spreadsheet/)

* [Use a Google Spreadsheet as your JSON backend | by Martin - Coder Wall](https://coderwall.com/p/duapqq)

  * [[Plunker] angular app acessing google spreadsheet](http://plnkr.co/edit/BtbSCVOh7KJsMHjANxMP?p=preview)

  * [[GitHub] 7hny / angular-google-spreadsheet](https://github.com/7hny/angular-google-spreadsheet)

* [[GitHub] chriszarate / sheetrock](https://github.com/chriszarate/sheetrock) - Quickly connect to, query, and lazy-load data from Google Spreadsheets

* [[GitHub] jsoma / tabletop](https://github.com/jsoma/tabletop) - Tabletop.js gives spreadsheets legs


#### Google Analytics

* [Angulartics](http://luisfarzati.github.io/angulartics/) - Web analytics for AngularJS applications


### Internacionalização

* [AngularJS Localization | DailyJS](http://dailyjs.com/2014/04/08/angular-localize/)

* [[GitHub] tyson-benson / Internationalization with AngularJS](https://github.com/tyson-benson/Internationalization-with-AngularJS) - i18n

* [angular translate](http://pascalprecht.github.io/angular-translate/) - i18n for your Angular apps, made easy

  * [[YouTube] Pascal Precht - i18n with angular-translate - Dutch AngularJS Meetup](https://www.youtube.com/watch?v=9CWifOK_Wi8) - An introduction talk about how to use angular-translate to bring i18n to you Angular apps at the Dutch AngularJS Meetup.

  * [[GitHub] angular-translate / grunt-angular-translate](https://github.com/angular-translate/grunt-angular-translate) - Grunt tasks to extract translation with AngularJS and angular-translate

* [[Gist] i18n Helper function for Javascript](https://gist.github.com/3353635)

* [Easy global i18n angularJS language translations for your Angular app | ng-newsletter](http://www.ng-newsletter.com/posts/angular-translate.html)

* [Angular JS localization with Require JS i18n module | Cloud Spinners Development Blog](http://dev-blog.cloud-spinners.com/2014/02/angular-js-localization-with-require-js.html)

* [Localizing Your AngularJS Apps: Update | Coding Smackdown TV](http://codingsmackdown.tv/blog/2013/04/23/localizing-your-angularjs-apps-update/)

* [[GitHub] rubenv / angular-gettext](https://github.com/rubenv/angular-gettext) - Gettext support for Angular.js

  * [AngularJS - Part 12, Multi language support | Gabriel Schenker's Blog]()

* [[YouTube] Kod.io 2014 - AngularJS and i18n by Pascal Precht](https://www.youtube.com/watch?v=C7xqaExvaQ4)

* [Internationalization with AngularJS | Trifork Blog](http://blog.trifork.com/2014/04/10/internationalization-with-angularjs/)


### Escopo e informações

* [Scope in Angular | Nulogy Blog](http://engineering.nulogy.com/posts/scope-in-angular/)

* [Global variable with AngularJS | Coding Insight](http://www.codinginsight.com/global-variable-with-angularjs/)

* [AngularJS: 6 Common Pitfalls Using Scopes](http://thenittygritty.co/angularjs-pitfalls-using-scopes)

* [Scope creep, a deep dive into Angular's scope | Jonathan Creamer](http://jonathancreamer.com/working-with-all-the-different-kinds-of-scopes-in-angular/)

* [5 Guidelines For Avoiding Scope Soup in Angular | Techno Fattie](http://www.technofattie.com/2014/03/21/five-guidelines-for-avoiding-scope-soup-in-angular.html)

--

* [Angular JS : Sharing data between Controllers](http://ramandv.com/blog/angular-js-sharing-data/)

* [Share state between controllers in AngularJS | variadic.me](https://variadic.me/posts/2013-10-15-share-state-between-controllers-in-angularjs.html)

* [A Tale of Frankenstein and Binding to Service Values in Angular.js | stsc3000's blog](http://stsc3000.github.io/blog/2013/10/26/a-tale-of-frankenstein-and-binding-to-service-values-in-angular-dot-js/)

--

* [Understanding Angular’s $scope and $rootScope event system $emit, $broadcast and $on | Todd Motto](http://toddmotto.com/all-about-angulars-emit-broadcast-on-publish-subscribing/)

* [Communicating Between Controllers In Angular | Tyson Cadenhead](http://www.tysoncadenhead.com/blog/communicating-between-controllers-in-angular)

--

* [AngularJS: "Controller as" or "$scope"? | Code Tunnel](http://codetunnel.com/angularjs-controller-as-or-scope/)

--

* [Frictionless data preloading in AngularJS | Garble me softly](http://www.garbl.es/angularjs/preload/2014/06/07/frictionless-data-preloading-in-angularjs/)


### Yeoman, Grunt e Bower

* [Automating AngularJS With Yeoman, Grunt & Bower | Newtriks LTD](http://newtriks.com/2013/06/11/automating-angularjs-with-yeoman-grunt-and-bower/)

* [[YouTube] Frontend Workflows with Grunt and Angular JS](https://www.youtube.com/watch?v=fSAgFxjFSqY)


### Upload File(s)

* [Multipart/form-data File Upload with AngularJS | Uncorked Studios](http://uncorkedstudios.com/blog/multipartformdata-file-upload-with-angularjs)

* [A directive to manage file upload in an AngularJS application | Web Development blog](http://blog.brunoscopelliti.com/a-directive-to-manage-file-upload-in-an-angularjs-application)

* [Async upload using angular-file-upload directive and .net WebAPI service | Mono Service](http://www.mono-software.com/blog/post/Mono/233/Async-upload-using-angular-file-upload-directive-and-net-WebAPI-service/)

* [AngularJS File Upload | Web Builder Zone](http://css.dzone.com/articles/angularjs-file-upload) - Recently I had some time to play around with AngularJS. More specifically I had to implement a jQuery based [file upload widget](http://blueimp.github.io/jQuery-File-Upload/). The widget’s demo site already contains an AngularJS demo, but I wanted a minimum setup, so I started from scratch and figured out the necessary parts to implement the file upload using ASP.NET MVC as the server-side platform.

* [Uploading To S3 With AngularJS | Cheyne Wallace](http://www.cheynewallace.com/uploading-to-s3-with-angularjs/) - How to upload files directly to AWS using AngularJS and the AWS JS SDK


### Autenticação

* [[GitHub] auth0 / auth0-angular](https://github.com/auth0/auth0-angular) - This AngularJS module will help you implement client-side and server-side (API) authentication. You can use it together with [Auth0](https://auth0.com/) to add username/password authentication, support for enterprise identity like Active Directory or SAML and also for social identities like Google, Facebook or Salesforce among others to your web, API and mobile native apps.

* [[GitHub] andreareginato / ng-oauth](https://github.com/andreareginato/ng-oauth) - AngularJS directive working with the OAuth2 Implicit Flow

* [[GitHub] witoldsz / angular-http-auth](https://github.com/witoldsz/angular-http-auth) - HTTP Auth Interceptor Module

* [[GitHub] philipsorst / angular-rest-springsecurity](https://github.com/philipsorst/angular-rest-springsecurity) - An example AngularJS Application that uses a Spring Security protected Jersey REST backend based on Hibernate/JPA

* [[GitHub] Yeti-Media / angular-token-authentication](https://github.com/Yeti-Media/angular-token-authentication) - Angular token authentication are services for handling token-based authentication as a client-side session with automatic (optional) handling of REST resources in angular apps. It is divided in two modules.

--

* [[GitHub] sahat / satellizer](https://github.com/sahat/satellizer) - Token-based AngularJS Authentication

--

* [Deal with users authentication in an AngularJS web app](http://blog.brunoscopelliti.com/deal-with-users-authentication-in-an-angularjs-web-app)

* [Authentication in Single Page Applications with Angular.js - A Modest Proposal](http://www.frederiknakstad.com/authentication-in-single-page-applications-with-angular-js/)

* [Implementing basic HTTP authentication for HTTP requests in AngularJS](http://wemadeyoulook.at/blogg/implementing-basic-http-authentication-http-requests-angular/)

* [Facebook authentication in your AngularJS web app | Web Development blog](http://blog.brunoscopelliti.com/facebook-authentication-in-your-angularjs-web-app)

* [Authentication to a RESTful web service in an AngularJS web app | Web Development blog](http://blog.brunoscopelliti.com/authentication-to-a-restful-web-service-in-an-angularjs-web-app)

* [AngularJS: Send auth token with every request](http://nils-blum-oeste.net/angularjs-send-auth-token-with-every--request/)

* [Cookies vs Tokens. Getting auth right with Angular.JS | Auth0](http://blog.auth0.com/2014/01/07/angularjs-authentication-with-cookies-vs-token/)

* [Authentication in AngularJS (or similar) based application](http://www.espeo.pl/2012/02/26/authentication-in-angularjs-application)

* [Tutorial: Creating an AngularJS app with node.js and Heroku Part II | Bryan Leboff](http://techblog.appirio.com/2013/02/tutorial-creating-angularjs-app-with.html) - Instagram Authentication

* [Handling Oauth2 with Node.js and Angular.js – Passport to the rescue! | FlashICS](http://www.flashics.com/2013/11/24/handling-oauth2-with-node-js-and-angular-js-passport-to-the-rescue/)

* [Simple Authentication for Angular.js App | Alexander Beletsky](http://beletsky.net/2013/11/simple-authentication-in-angular-dot-js-app.html)

* [Authentication in Single Page Applications | VickeV.com](https://vickev.com/#!/article/authentication-in-single-page-applications-node-js-passportjs-angularjs) - Authentication in Single Page Applications (Node.js, PassportJS, AngularJS)

* [Techniques for authentication in AngularJS applications | Opinionated AngularJS — Medium](https://medium.com/opinionated-angularjs/7bbf0346acec)

  * [A collection of ideas for authentication & access control | Opinionated AngularJS — Medium](https://medium.com/opinionated-angularjs/techniques-for-authentication-in-angularjs-applications-7bbf0346acec)

* [Authentication with Ionic and Angular.js in a Cordova/Phonegap mobile web application | KD Moore Consulting](http://www.kdmooreconsulting.com/blogs/authentication-with-ionic-and-angular-js-in-a-cordovaphonegap-mobile-web-application/)


### Mobile

* [The Definitive Guide to Angular on Mobile | ng-newsletter](http://www.ng-newsletter.com/posts/angular-on-mobile.html)

* [[YouTube] Angular on the go: Using Angular to power Mobile Apps | AngularJS](https://www.youtube.com/watch?v=xOAG7Ab_Oz0) - (15/12/2013)

--

* [Mobile Angular UI](http://mobileangularui.com/) - Angular JS Mobile UI framework with Bootstrap 3 Css

* [The Answer to PhoneGap UI Development | Onsen UI](http://onsenui.io/)


#### Ionic

* [Ionic](http://ionicframework.com/) - The Most Advanced HTML5 Mobile App Framework. Ionic utilizes AngularJS in order to create a framework most suited to develop rich and robust applications. 

* [ngCordova](http://ngcordova.com/) - is a set of AngularJS extensions on top of the Cordova API to make it easier to build, test, and deploy Cordova apps with AngularJS

--

* [Pull to Refresh | Formulas | Learn Ionic](http://learn.ionicframework.com/formulas/pull-to-refresh/)

* [Building Mobile Apps with AngularJS and Ionic | The Official Ionic Blog](http://ionicframework.com/blog/angular-mobile-dev/)

--

* Christophe Coenraets

  * [Ionic Framework Tutorial - GitHub](https://ccoenraets.github.io/ionic-tutorial/)

  * [Sample Mobile Application with Ionic and AngularJS](http://coenraets.org/blog/2014/02/sample-mobile-application-with-ionic-and-angularjs/)

  * [QCon New York Slides: Creating Native-Like Mobile Apps with Cordova, AngularJS and Ionic](http://coenraets.org/blog/2014/06/qcon-new-york-slides-creating-native-like-mobile-apps-with-cordova-angularjs-and-ionic/)

  * [Employee Directory Sample App with Ionic and Node.js](http://coenraets.org/blog/2014/08/employee-directory-sample-app-with-ionic-and-node-js/)

  * [[GitHub] ccoenraets / directory-ionic-nodejs](https://github.com/ccoenraets/directory-ionic-nodejs) - Sample Employee Directory App built with Ionic and Node.js

--

* The dynamic programmer 

  > Code for this series is available on [[Github] hgarcia / dynamic-sports](https://github.com/hgarcia/dynamic-sports)

  * Part 1 - [Building an iOS app with PhoneGap, Angular.js and the ionic framework](http://blog.dynamicprogrammer.com/2014/02/26/building-ios-apps-with-phonegap-angular-and-ionic-framework.html)

  * Part 2 - [Building a basic iOS UI using Angular and Ionic](http://blog.dynamicprogrammer.com/2014/02/28/building-a-basic-UI-angular-ionic-part-2.html)

  * Part 3 - [Recording Geo location data with PhoneGap and Angular](http://blog.dynamicprogrammer.com/2014/05/05/recording-geolocation-data-PhoneGap-part-3.html)

  * Part 4 - [Refactoring the js code structure PhoneGap and Angular](http://blog.dynamicprogrammer.com/2014/05/06/refactoring-the-js-code-structure-part-4.html)

  * Part 5 - [Uploading files with PhoneGap and Angular](http://blog.dynamicprogrammer.com/2014/05/09/uploading-files-with-PhoneGap-Angular-part-5.html)

  * Part 6 - [A few different ways to improve user feedback in our Ionic application](http://blog.dynamicprogrammer.com/2014/05/16/user-feedback-on-PhoneGap-with-Ionic-part-6.html)

  * Part 7 - [Displaying current and max speed with PhoneGap and Ionic](http://blog.dynamicprogrammer.com/2014/05/21/displaying-speed-and-duration-PhoneGap-with-Ionic-part-7.html)

  * Part 8 - [Deleting files with PhoneGap](http://blog.dynamicprogrammer.com/2014/05/22/deleting-files-with-PhoneGap-part-8.html)

  * Part 9 - [Calculating distance and speed with the GeoLocation API - PhoneGap](http://blog.dynamicprogrammer.com/2014/05/23/calculate-distance-with-geolocation-and-PhoneGap-part-9.html)


#### PhoneGap

* [PhoneGap and AngularJs, The Start | Tech Pro](http://tech.pro/tutorial/1336/phonegap-and-angularjs-the-start)

* [PhoneGap and AngularJs, Notification Service | Tech Pro](http://tech.pro/tutorial/1349/phonegap-and-angularjs-notification-service)

* [PhoneGap and AngularJS: In App Browser | Tech Pro](http://tech.pro/tutorial/1357/phonegap-and-angularjs-in-app-browser)

* [Brian Ford - Building **PhoneGap** Apps with AngularJS](http://briantford.com/blog/angular-phonegap.html)

* [Quick Start Guide to PhoneGap+AngularJS | Devgirl's Weblog](http://devgirl.org/2013/06/10/quick-start-guide-phonegap-and-angularjs/)

* [How to build AngularJS based native mobile application | HTMLCenter](http://www.htmlcenter.com/blog/how-to-build-angularjs-based-native-mobile-application/)

* [AngularJS, Phonegap, and angular-seed. Let’s Go! | Project: Poppycock](http://projectpoppycock.com/angularjs-phonegap-and-angular-seed-lets-go/)

* [Sample Mobile Application with AngularJS | Christophe Coenraets](http://coenraets.org/blog/2013/11/sample-mobile-application-with-angularjs/)

--

* [[GitHub] calvinl / ng-phonegap](https://github.com/calvinl/ng-phonegap) - Grunt workflow for building AngularJS applications on PhoneGap

* [[GitHub] dsimard / grunt-angular-phonegap](https://github.com/dsimard/grunt-angular-phonegap) - Combine yeoman/generator-angular and phonegap

--

* [AppGyver Steroids](http://www.appgyver.com/steroids) - Build PhoneGap based apps with native performance. Rapidly.


### Ferramentas

* [Angular Batarang | Google Chrome](https://chrome.google.com/webstore/detail/angularjs-batarang/ighdmehidhipcmcojjgiloacoafjmpfk) - browser extension

  * [Introducing the Batarang](http://blog.angularjs.org/2012/07/introducing-angularjs-batarang.html) - dev tool

* [ng-inspector](http://ng-inspector.org/) -  is a browser extension for Chrome and Safari that adds an inspector pane to help you develop, debug and understand your AngularJS applications.


#### Sublime Text

* [[GitHub] maxhoffmann / angular-snippets](https://github.com/maxhoffmann/angular-snippets) - Angular.js Snippets for Sublime Text 2

* [[GitHub] erkobridee / sublime-angularjs-ee-snippets](https://github.com/erkobridee/sublime-angularjs-ee-snippets) - Sublime Text 2 / 3 Snippets and Completions for Angular.js and Require.js (focused to the [angularjs-ee-boilerplate](https://github.com/erkobridee/angularjs-ee-boilerplate) code)

* [[GitHub] angular-ui / AngularJS-sublime-package](https://github.com/angular-ui/AngularJS-sublime-package) - AngularJS code completion, snippets, go to definition, quick panel search, and more


#### Eclipse IDE

* [[GitHub] angelozerr / angularjs-eclipse](https://github.com/angelozerr/angularjs-eclipse) - AngularJS Eclipse IDE Plugin


#### Netbeans IDE

* [Integrated AngularJS Development | Geertjan's Blog](https://blogs.oracle.com/geertjan/entry/integrated_angularjs_development)


#### JetBrains

* [WebStorm — The smartest JavaScript IDE](http://www.jetbrains.com/webstorm/)

  * [WebStorm + AngularJS | JetBrains TV](http://tv.jetbrains.net/channel/webstorm/angularjs)

* [IntelliJ IDEA Plugins](http://plugins.jetbrains.com/plugin/6971?pr=idea)

* [[GitHub] johnlindquist / angularjs-plugin](https://github.com/johnlindquist/angularjs-plugin) - AngularJS features for the Intellij Platform (WebStorm, RubyMine, Intellij, etc)


#### Visual Studio

* [AngularJS Intellisense in Visual Studio 2012 | Mads Kristensen](http://madskristensen.net/post/angularjs-intellisense-in-visual-studio-2012)


## Componentes

* [Writing Reusable AngularJS Components with Bower | Brian Ford](http://briantford.com/blog/angular-bower.html)

* [Sharing AngularJS modules with component.js | Jayway](http://www.jayway.com/2013/06/04/sharing-angularjs-modules-with-component-js/)


### Diretivas

* [Directive | AngularJS Docs](http://docs.angularjs.org/guide/directive)

* [[GitHub] IgorMinar / directives-workshop](https://github.com/IgorMinar/directives-workshop)

--

* [Hacking Core Directives in AngularJS | Brian Ford](http://briantford.com/blog/angular-hacking-core.html)

  * [[GitHub] damienklinnert / angular-decorate](https://github.com/damienklinnert/angular-decorate) - Use AngularJS' decorate function with ease

* [How To Extend Angular's Script Directive | Techno Fattie](http://www.technofattie.com/2014/03/25/how-to-extend-angular-script-directive.html)

* [The Many Ways To Use ngClass | Scotch](http://scotch.io/tutorials/javascript/the-many-ways-to-use-ngclass)

--

* [Criando componentes](http://cironunes.com/angular-components-talk/) - by Ciro Nunes / @cironunesdev | #AngularJSSP 20 de Junho '14

--

* [Angle Brackets, Synergistic Directives | Pony Foo](http://blog.ponyfoo.com/2014/02/19/angle-brackets-synergistic-directives)

* [Little-known directives of Angular.js | CODETUNES](http://codetunes.com/2013/little-known-angular-directives/)

* [Lesser know AngularJS directives | Reverse Polarity](http://djds4rce.wordpress.com/2013/10/20/lesser-know-angularjs-directives/)

* [Introduction to Directives | henriquat.re](http://henriquat.re/directives/introduction-to-directives/introductionToDirectives.html) - AngularJS Directives - Domain-Specific Extensions to HTML

* [The Hitchhiker's Guide to the Directive | codef0rmer](http://amitgharat.wordpress.com/2013/06/08/the-hitchhikers-guide-to-the-directive/)

* [Don't Fear Directives In Angular.js | Nathan LeClaire](http://nathanleclaire.com/blog/2013/12/07/dont-fear-directives-in-angular-dot-js/)

* [Extending HTML with AngularJS Directives | CodeProject](http://www.codeproject.com/Articles/607873/Extending-HTML-with-AngularJS-Directives)

* [Let's Make Full-Ass AngularJS Directives | @jhooks](http://www.joelhooks.com/blog/2014/02/11/lets-make-full-ass-angularjs-directives)

* [[Slid.es] Deep Dive into custom Directives](http://slid.es/djsmith/deep-dive-into-custom-directives) -  by djsmith

--

* [Defer DOM Tree Binding In AngularJS With Delayed Transclusion | Ben Nadel](http://www.bennadel.com/blog/2557-Defer-DOM-Tree-Binding-In-AngularJS-With-Delayed-Transclusion.htm)

* [Using Track-By With ngRepeat In AngularJS 1.2 | Ben Nadel](http://www.bennadel.com/blog/2556-Using-Track-By-With-ngRepeat-In-AngularJS-1-2.htm)

* [AngularJS Filter for Ordering Objects (Hashes) with ngRepeat | Justin Klemm](http://justinklemm.com/angularjs-filter-ordering-objects-ngrepeat/)

  * [[GitHub] fmquaglia / ngOrderObjectBy](https://github.com/fmquaglia/ngOrderObjectBy)

* [Looking At How scope.$evalAsync() Affects Performance In AngularJS Directives | Ben Nadel](http://www.bennadel.com/blog/2635-looking-at-how-scope-evalasync-affects-performance-in-angularjs-directives.htm)

--

* [Triggering $digest Phases In Related Directives In AngularJS | Ben Nadel](http://www.bennadel.com/blog/2625-triggering-digest-phases-in-related-directives-in-angularjs.htm)

* [AngularJS - $compile: How it works, How to use it | Try, Catch, Fail](http://www.benlesh.com/2013/08/angular-compile-how-it-works-how-to-use.html)

* [Compile, Pre, and Post Linking in AngularJS | Ode To Code](http://odetocode.com/blogs/scott/archive/2014/05/28/compile-pre-and-post-linking-in-angularjs.aspx)

* [AngularJS Directives Tutorial | Fundoo Solutions](http://www.befundoo.com/university/tutorials/angularjs-directives-tutorial/)

* [AngularJS directives | Coding Insight](http://www.codinginsight.com/angularjs-directives/)

* [Build custom directives with AngularJS | ng-newsletter](http://www.ng-newsletter.com/posts/directives.html)

* [Mastering AngularJS Directives | Pascal Precht](http://pascalprecht.github.io/slides/mastering-angularjs-directives/)

* [Angular Directive Examples | Tech Pro](http://tech.pro/tutorial/1603/angular-directive-examples)

* [Refactoring to AngularJS Directive in 9 Steps | Suhair Hassan](http://suhairhassan.com/2013/10/21/refactoring-to-angularjs-directive.html)

* [AngularJS: Dynamic Directives | Thinktecture Blog](http://weblogs.thinktecture.com/pawel/2014/07/angularjs-dynamic-directives.html)

--

* [Understanding Transclusion in Angular | Nulogy Blog](http://engineering.nulogy.com/posts/transclusion-in-angular/)

* [AngularJS: Multi-transclusion | Zach Snow](http://zachsnow.com/#!/blog/2013/angularjs-multi-transclusion/)

--

* [[GitHub] wmluke / angular-blocks](https://github.com/wmluke/angular-blocks) - Template inheritance for Angular JS

  * [Template inheritance for AngularJS | The Bunsel Blog](http://www.bunselmeyer.net/#!/thoughts/angular-blocks) - I really enjoy using block-style template inheritance in Jade and Handlebars. From my understanding, this pattern was popularized by Django.

--

* [[GitHub] nlaplante / angular-google-maps](https://github.com/nlaplante/angular-google-maps) - AngularJS directives for the Google Maps Javascript API

* [[GitHub] jonashartmann / webcam-directive](https://github.com/jonashartmann/webcam-directive) - Angularjs directive to access the webcam

* [[GitHub] angular-adaptive / adaptive-motion](https://github.com/angular-adaptive/adaptive-motion) - Want to control an AngularJS app using your web cam? Check it.

* [[GitHub] rootux / angular-highcharts-directive](https://github.com/rootux/angular-highcharts-directive) - An Angular Js Directive which allows to simplify the use of Highcharts charts

* [[GitHub] wzr1337 / angular-gestures](https://github.com/wzr1337/angular-gestures) - AngularJS directive that adds support for multi touch gestures to your app. Based on hammer.js.

* [[jsfiddle] Big Text Directive with AngularJS](http://jsfiddle.net/michaeldausmann/FH9wj/) - Use AngularJS and jquery to make an input with a popup textarea for editing large text values

* [[GitHub] kentcdodds / ng-genie](https://github.com/kentcdodds/ng-genie) - Directive for [GenieJS](https://github.com/kentcdodds/genie). GenieJS was built to bring behavior found in Alfred to JavaScript.

* [textAngular](http://textangular.com/) - Lightweight Angular.js, Javascript Wysiwyg/Text-Editor

* [Angular.js Intro.js](http://code.mendhak.com/angular-intro.js/) - AngularJS directives for intro.js

* [[GitHub] klederson / angular-masonry-directive](https://github.com/klederson/angular-masonry-directive) - A very simple and 100% compatible masonry directive for AngularJS ... do you know how to use masonry? Good! You know how to use this

--

* [Datatable with fully dynamic columns in AngularJS | Entwicklertagebuch](http://entwicklertagebuch.com/blog/2013/11/datatable-with-fully-dynamic-columns-in-angularjs/)

--

* [AngularJS Directives and The Computer Science of JavaScript | Adobe Developer Connection](http://www.adobe.com/devnet/html5/articles/angularjs-directives-and-the-computer-science-of-javascript.html)

* [Understanding AngularJS transclude in directives](http://odiseo.net/angularjs/understanding-angularjs-transclude-in-directives)

* [A Look at Directives in AngularJS](http://blog.envylabs.com/post/52142458172/a-look-at-directives-in-angularjs) - Using directives, we can extract complex and repetitive parts of our user interface into easily reusable building blocks.

* [Part 5 - Custom Directive | Angular Cats!](http://ericterpstra.com/2012/09/angular-cats-part-5-custom-directive/)

* [Forced Repaints In Directive Can Cause Accidental Scrolling In AngularJS](http://www.bennadel.com/blog/2468-Forced-Repaints-In-Directive-Can-Cause-Accidental-Scrolling-In-AngularJS.htm)

* Scoping AngularJS Directives | Spectacle Labs Blog - [Part 1](http://spectaclelabs.io/blog/2013/06/22/scoping-angularjs-directives-part-1/) | [Part 2](http://spectaclelabs.io/blog/2013/06/23/scoping-angularjs-directives-part-2/)

* [AngularJS Missing Directives: Focus & Blur | The traveling hermit](http://blog.jasoncust.com/2013/08/angularjs-missing-directives-focus-blur.html)

* [AngularJS Missing Directives: Focus & Blur Part 2 | The traveling hermit](http://blog.jasoncust.com/2013/08/angularjs-missing-directives-focus-blur_14.html)

* [Dealing with focus and blur in AngularJS directives | Miroslav Magda's blog](http://blog.ejci.net/2013/08/06/dealing-with-focus-and-blur-in-angularjs-directives/)

--

* [Use Cases of AngularJS Directives | Web Development blog](http://blog.brunoscopelliti.com/use-cases-of-angularjs-directives)

* [A directive to manage file upload in an AngularJS application | Web Development blog](http://blog.brunoscopelliti.com/a-directive-to-manage-file-upload-in-an-angularjs-application)

* [[GitHub] danialfarid / angular-file-upload](https://github.com/danialfarid/angular-file-upload) - An AngularJS directive for file upload using HTML5 with FileAPI polyfill for unsupported browsers

* [AngularJS Directive to check that passwords match | Web Development blog](http://blog.brunoscopelliti.com/angularjs-directive-to-check-that-passwords-match)

* [The ngForm directive of AngularJS | Web Development blog](http://blog.brunoscopelliti.com/the-ngform-directive-of-angularjs)

* [Building a Custom AngularJS Unique Value Directive | Dan Wahlin](http://weblogs.asp.net/dwahlin/archive/2013/09/24/building-a-custom-angularjs-unique-value-directive.aspx) - To see the directive in an actual application check out the [Customer Manager sample application](https://github.com/DanWahlin/CustomerManagerStandard) 

* [Creating an AngularJS Component | Safari Books Online](http://blog.safaribooksonline.com/2013/11/07/creating-an-angularjs-component/) 
  
  * [[GitHub] jonniespratley / ng-chartjs-directive](https://github.com/jonniespratley/ng-chartjs-directive) - This is a AngularJS directive for creating charts with ChartJS

  * [[plunkr] ng-chartjs-directive example](http://embed.plnkr.co/QE2TLfiS9zabrTRKM0Vr/preview)


### Diretivas d3.js

* [D3.js in Angular.js Directive - a relief from D3 svg code in HTML Page | Technical Blogs](http://www.phloxblog.in/d3-js-angular-directive/)

* [Creating D3.js Charts using AngularJS Directives | Cloudspace](http://cloudspace.com/blog/2014/03/25/creating-d3.js-charts-using-angularjs-directives/) - 2014/03/25

* [Creating Custom D3 Directives in AngularJS | delimited](http://www.delimited.io/blog/2014/7/16/d3-directives-in-angularjs) - 2014/07/16

* [AngularJS + D3 : Implementierung einer WordCloud-Direktive | AngularJS.DE](http://angularjs.de/artikel/angularjs-d3-wordcloud)

  * [[GitHub] robinboehm / angular-d3-directives](https://github.com/robinboehm/angular-d3-directives)


### Web Components

* [Building Pluggable Components in AngularJS | codef0rmer](http://amitgharat.wordpress.com/2013/10/20/building-pluggable-components-in-angularjs/)

* [Combining AngularJS with existing Components | henriquat.re](http://henriquat.re/directives/advanced-directives-combining-angular-with-existing-components-and-jquery/angularAndJquery.html)

* [Here's the difference between Polymer and Angular | Binpress](http://www.binpress.com/blog/2014/06/26/polymer-vs-angular/) - 26/06/2014

* [[YouTube] Using Angular with Polymer elements](https://www.youtube.com/watch?v=p1NpZ-0Op0w)

* [Angular and Polymer Data Binding, Together! | Seth Ladd's Blog](http://blog.sethladd.com/2014/02/angular-and-polymer-data-binding.html)

--

* [[GitHub] webcomponents / angular-interop](https://github.com/webcomponents/angular-interop) - A demo of interoperability between Polymer and AngularJS

* [[GitHub] GabiAxel / ng-polymer-elements](https://github.com/GabiAxel/ng-polymer-elements) - Extendible AngularJS two-way binding support for Polymer core and paper elements


## Filters

* [AngularJS filters in Depth | Suhair Hassan](http://suhairhassan.com/2013/07/25/angularjs-in-depth-part-2.html)

* [Everything about custom filters in AngularJS | Todd Motto](http://toddmotto.com/everything-about-custom-filters-in-angular-js/)

* [AngularJS e filtros Brasileiros | Igor Costa](http://www.igorcosta.com/angularjs-e-filtros-brasileiros/)

  * [[GitHub] igorcosta / ng-filters-br](https://github.com/igorcosta/ng-filters-br) - Filtros dos padrões Brasileiros para quem usa o Angular e seus filtros


## Módulos

* [Angular Modules](http://ngmodules.org/) - Encontre (Módulos, Plugins e Directives) para o Angular.js 

--

* [[GitHub] davej / angular-classy](https://github.com/davej/angular-classy) - Cleaner class-based controllers with Angular

* [[GitHub] roypeled / angular-class-extender](https://github.com/roypeled/angular-class-extender) - A lightweight angular module that adds support for multiple class inheritance and method abstraction

--

* [[GitHub] decipherinc / angular-history](https://github.com/decipherinc/angular-history) - A history service for AngularJS. Undo/redo, that sort of thing. Has nothing to do with the "back" button, unless you want it to

--

* [[GitHub] mgonto / restangular](https://github.com/mgonto/restangular) - AngularJS service to handle Rest API Restful Resources properly and easily

* [[GitHub] jeffbcross / syncResource](https://github.com/jeffbcross/syncResource) - OmniBinder - One binder to bind AngularJS models to everything [Status: Experimental, In-Development : 17/09/2013] 

* [[GitHub] chinmaymk / angular-cog](https://github.com/chinmaymk/angular-cog) - declarative ajax requests for angularjs

--

* [[GitHub] pc035860 / ngQueue](https://github.com/pc035860/ngQueue) - ngQueue is an AngularJS module that helps you to handle routine sync/async queue task in AngularJS with ease.

--

* [Criando um scroll Infinito com o AngularJS e JQuery | Igor Costa](http://www.igorcosta.com/criando-um-scroll-infinito-com-o-angularjs/)

* [ngInfiniteScroll - Infinite Scrolling for AngularJS](http://binarymuse.github.com/ngInfiniteScroll/index.html)

* [[GitHub] sparkalow / angular-infinite-scroll](https://github.com/sparkalow/angular-infinite-scroll) - Angular directive for infinite scrolling.

* [[GitHub] lorenzofox3 / lrInfiniteScroll](https://github.com/lorenzofox3/lrInfiniteScroll) - directive to register handler when an element is scrolled down near its end

--

* [AngularJS + Chosen Plugin = Awesome](http://onehungrymind.com/angularjs-chosen-plugin-awesome/)

* [JQuery Mobile Angular Adapter](https://github.com/tigbro/jquery-mobile-angular-adapter)

* [[GitHub] Pasvaz / bindonce](https://github.com/Pasvaz/bindonce) - Zero watches binding for AngularJs

* [[GitHub] jtrussell / angular-selection-model](https://github.com/jtrussell/angular-selection-model) - The selection management companion for ngRepeat 

* [[GitHub] 2fdevs / videogular](https://github.com/2fdevs/videogular) - An HTML5 video player for AngularJS

* [[GitHub] caitp / ng-media](https://github.com/caitp/ng-media) - AngularJS support for HTML5 media elements

* [[GitHub] eu81273 / angular.treeview](https://github.com/eu81273/angular.treeview) - AngularJS based Treeview (no jQuery)

* [[GitHub] esvit / ng-table](https://github.com/esvit/ng-table/) - Simple table with sorting and filtering on AngularJS

* [[GitHub] marcorinck / angular-growl](https://github.com/marcorinck/angular-growl) - growl-like notifications for angularJS projects

* [[GitHub] akoenig / angular-deckgrid](https://github.com/akoenig/angular-deckgrid) - A lightweight masonry-like grid for AngularJS

* [[GitHub] Hacklone / ng-grid-panel](https://github.com/Hacklone/ng-grid-panel) - Google images like grid and panel in AngularJS

* [[GitHub] likeastore / ngDialog](https://github.com/likeastore/ngDialog) - Modals and popups provider for Angular.js applications

* [[GitHub] flowjs / ng-flow](https://github.com/flowjs/ng-flow) - Flow.js html5 file upload extension on angular.js framework

* [[GitHub] nimbly / angular-formly](https://github.com/nimbly/angular-formly) - AngularJS directive which takes JSON representing a form and renders to HTML

* [[GitHub] mchapman / forms-angular](https://github.com/mchapman/forms-angular) - Probably the most opinionated framework in the world


--

* [Angular-Wizard](http://mgonto.github.io/angular-wizard/) - Easy to use Wizard library for AngularJS

* [[GitHub] ianwalter / ng-breadcrumbs](https://github.com/ianwalter/ng-breadcrumbs) - A better AngularJS service to help with breadcrumb-style navigation between views

--

* [[GitHub] davidchang / ngReact](https://github.com/davidchang/ngReact) - Use React Components in Angular

* [[GitHub] josebalius / ngReactGrid](https://github.com/josebalius/ngReactGrid) - A really fast Angular grid using the power of React to render. Based on ng-grid and jQuery DataTables

  * [ngReactGrid 0.5.0 - Custom cells](http://www.josebalius.com/ngreactgrid-0-5-0-custom-cells/)

--

* [AngularHotkeys.js](http://chieffancypants.github.io/angular-hotkeys/) - Keyboard shortcuts for your angular apps

--

* [Adding a weel (spin.js) progress indicator to your AngularJS application](http://blog.xvitcoder.com/adding-a-weel-progress-indicator-to-your-angularjs-application/)

* [ngProgress](http://victorbjelkholm.github.io/ngProgress/) - Slim, site-wide progressbar for Angular

* [Angular Loading Bar](http://chieffancypants.github.io/angular-loading-bar/) - An automatic loading bar using angular interceptors. It works automatically, so simply include it as a dependency and it will automatically display the progress of your $http requests.

* [[GitHub] cgross / angular-busy](https://github.com/cgross/angular-busy) - Show busy/loading indicators on any element during $http requests (or any promise).

* [[GitHub] voronianski / ngActivityIndicator](https://github.com/voronianski/ngActivityIndicator) - preloaders provider for Angular.js applications with built-in styles

--

* [[GitHub] urish / angular-moment](https://github.com/urish/angular-moment) - Angular.JS directives for [Moment.JS](http://momentjs.com/) (timeago alternative)

* [[GitHub] OutlawAndy / relativeDate](https://github.com/outlawandy/relativeDate) - Angular.js service providing auto-updating, relative time labels like "about 1 minute ago"

* [[GitHub] sparkalow / angular-truncate](https://github.com/sparkalow/angular-truncate) - truncate text and add ellipses.

* [[GitHub] gil / ng-cpf-cnpj](https://github.com/gil/ng-cpf-cnpj) - AngularJS directive to validate CPF/CNPJ numbers



### Módulos de Armazenamento

* [[GitHub] jmdobry / angular-cache](https://github.com/jmdobry/angular-cache) - angular-cache is a very useful replacement for Angular's [$cacheFactory](http://docs.angularjs.org/api/ng.$cacheFactory)

--

* [[GitHub] agrublev / Angular-localStorage](https://github.com/agrublev/Angular-localStorage) - Simple AngularJS localStorage module (with two-way $scope bind into storage)

* [[GitHub] grevory / angular-local-storage](https://github.com/grevory/angular-local-storage) - An Angular module that gives you access to the browsers local storage

--

* [[GitHub] ocombe / angular-localForage](https://github.com/ocombe/angular-localForage) - Angular service & directive for [[GitHub] mozilla / localForage](https://github.com/mozilla/localForage) (Offline storage, improved.)

* [[GitHub] webcss / angular-indexedDB](https://github.com/webcss/angular-indexedDB) - An angularjs serviceprovider to utilize indexedDB with angular

--

* [[GitHub] firebase / angularFire](https://github.com/firebase/angularFire) - AngularJS bindings for [Firebase](https://www.firebase.com/quickstart/angularjs.html).


### Módulos de Gráficos

* [[GitHub] Schweigi / angular-gantt](https://github.com/schweigi/angular-gantt/) - A Gantt chart directive for Angular.js without any other dependencies

* d3.js

  * [[GitHub] chinmaymk / angular-charts](https://github.com/chinmaymk/angular-charts) - angular directives for creating common charts using d3

  * [[GitHub] WealthBar / angular-d3](https://github.com/WealthBar/angular-d3) - AngularJS directives for declaratively using D3

  * [[GitHub] cmaurer / angularjs-nvd3-directives](https://github.com/cmaurer/angularjs-nvd3-directives) - Angular.js directives for nvd3.js

* highcharts

  * [[GitHub] pablojim / highcharts-ng](https://github.com/pablojim/highcharts-ng) - AngularJS directive for Highcharts

  * [[GitHub] bielversallini / ng-highcharts](https://github.com/bielversallini/ng-highcharts) - Angular Directive for Highcharts


### Módulos de UI

* [Angular-Autolayout.js](https://thenikso.github.io/angular-autolayout/) - Constraint based layout for your AngularJS apps

* [Use Famous in your Angular projects with Famous-Angular](http://famo.us/integrations/angular/)

* [Angular Foundation](http://madmimi.github.io/angular-foundation/)

* [Angular Kendo](http://kendo-labs.github.com/angular-kendo/) - Angular-Kendo is a passthrough to the Kendo UI

  * [Customizable Dashboards With Angular Kendo UI and Bootstrap | Telerik Developer Network](http://developer.telerik.com/featured/customizable-dashboards-angular-kendo-ui-bootstrap/)

* [Angular UI](http://angular-ui.github.com/) - Componentes de UI

  * [Angular UI / UI Bootstrap](http://angular-ui.github.com/bootstrap/)

  * [Diving deep into the AngularUI Router | ng-newsletter](http://www.ng-newsletter.com/posts/angular-ui-router.html)

  * [Nested animations in AngularJS using ui-router | Dave Chenell - The Water Bear](http://thewaterbear.com/nested-animations-in-angularjs-using-ui-router/)

  * [Advanced routing and resolves | Medium](https://medium.com/opinionated-angularjs/a2fcbf874a1c) - Use the AngularUI Router instead of ngRoute

  * [[GitHub] angular-ui / AngularJS-brackets](https://github.com/angular-ui/AngularJS-brackets) - AngularJS plugin for Brackets

* [AngularStrap](https://mgcrea.github.io/angular-strap/) - Bootstrap directives for AngularJS

* [[GitHub] willmendesneto / keepr](https://github.com/willmendesneto/keepr/) - A simple list of Angular components


### ng animate

* [[SlideShare] AngularJS Animations](http://www.slideshare.net/EyalV/angularjs-animations-21435788)

* [[Slid.es] Animation in AngularJS by Gias Kay Lee](http://slides.com/gsklee/animation-in-angularjs)

* [AngularJS Animations](http://www.nganimate.org/)

* [[GitHub] Hendrixer / ng-Fx](https://github.com/Hendrixer/ng-Fx) - Simple, Beautiful animation library for Angular 

* [[GitHub] mgcrea / angular-motion](https://github.com/mgcrea/angular-motion) - Fancy CSS3 animations for AngularJS 1.2+

* [Animation in AngularJS | Year of Moo](http://www.yearofmoo.com/2013/04/animation-in-angularjs.html) - AngularJS now provides full support for animations direct from it's core

* [Enhanced Animation in AngularJS | Year of Moo](http://www.yearofmoo.com/2013/05/enhanced-animations-in-angularjs.html)

* [Remastered Animation in AngularJS 1.2 | Year of Moo](http://www.yearofmoo.com/2013/08/remastered-animation-in-angularjs-1-2.html) - Learn how to use the bigger and better animation features in AngularJS 1.2

* [Animating with AngularJS | Devgirl's Weblog](http://devgirl.org/2013/08/06/animating-with-angularjs/) | [sample app](http://devgirl.org/files/AngularAnimationsDemo/) | [Animating with AngularJS | Flippin' Awesome](http://flippinawesome.org/2013/08/05/animating-with-angularjs/)

* [Preparing for Animations in Angular 1.2.0 | John Papa](http://www.johnpapa.net/preparing-for-animations-in-angular-1-2-0/)

* [Animating AngularJS Apps: ngView | Scotch](http://scotch.io/tutorials/javascript/animating-angularjs-apps-ngview)


## Projetos de Exemplo

* [[GitHub] angular-app / angular-app](https://github.com/angular-app/angular-app) - Reference application for AngularJS

* [[GitHub] angular / angular-prs](https://github.com/angular/angular-prs)

* [ng-boilerplate | Non-Trivial AngularJS Made Easy](http://joshdmiller.github.com/ng-boilerplate/) - Everything you need to kickstart AngularJS projects: a best-practice  directory structure, an intelligent build system, and the best web  design libraries around.

* [[GitHub] kvindasAB / angular-enterprise-kickstart](https://github.com/kvindasAB/angular-enterprise-kickstart) - Angular Enterprise Kickstart - Kickstart your enterprise project. Based from ng-boilerplate

* [[GitHub] CaryLandholt / AngularFun](https://github.com/CaryLandholt/AngularFun) - AngularJS Reference Architecture

* [[GitHub] marcorinck / ngStart](https://github.com/marcorinck/ngStart) - skeleton project for new angular.js projects

* [[GitHub] ng2 / ng2](https://github.com/ng2/ng2) - minimalistic modular angular.js app generator

* [[GitHub] brunobatista / angularjs-in-action](https://github.com/brunobatista/angularjs-in-action) - Introduction course for AngularJS

--

* [[GitHub] erkobridee / angularjs-ee-boilerplate](https://github.com/erkobridee/angularjs-ee-boilerplate)

* [[GitHub] erkobridee / lab-angularjs](https://github.com/erkobridee/lab-angularjs)

* [AngularJS - Consumindo a API do GitHub](http://blog.erkobridee.com/2012/07/26/angularjs-consumindo-a-api-do-github/) | [Testar App](http://erkobridee.github.io/angularjs-github-info/) | [GitHub Code](https://github.com/erkobridee/angularjs-github-info)

--

* [Grabs - Front-End Development Environment](http://grabs.in/) - Grunt.js | Angular.js | Bower | Stylus

  * [[GitHub] sercaneraslan / grabs](https://github.com/sercaneraslan/grabs) - Front-End Development Environment

--

* [Creating Apps with Angular and Node using Yeoman | Tyler Henkel](http://tylerhenkel.com/creating-apps-with-angular-and-node-using-yeoman/)

* [[GitHub] yeoman / generator-angular](https://github.com/yeoman/generator-angular) - Yeoman generator for AngularJS

* [[GitHub] cironunes / generator-angular-next](https://github.com/cironunes/generator-angular-next)

* [[GitHub] cgross / generator-cg-angular](https://github.com/cgross/generator-cg-angular) - Yeoman generator for Enterprise Angular projects

--

* [[jsfiddle] Calculadora em AngularJS](http://jsfiddle.net/rabidGadfly/GF3Xg/)

* [AngularJS Calculator Demo](http://www.thomporter.com/apps/angularjs_calc) - A calculator built with AngularJS, written in CoffeeScript

* [[GitHub] mjhea0 / thinkful-angular](https://github.com/mjhea0/thinkful-angular) - AngularJS by Example - Building a Bitcoin Investment Calculator

* [[GitHub] thiagofelix / hackynote](https://github.com/thiagofelix/hackynote) - A presentation editor and preview based on markdown. Made for hackers

* [[GitHub] yrezgui / kodigon](https://github.com/yrezgui/kodigon) - is a web application which encode and decode (if possible) string in many algorithm formats lke Base64, MD5, SHA1, etc. It's an example of AngularJS use.

* [[GitHub] DanWahlin / CustomerManagerStandard](https://github.com/DanWahlin/CustomerManagerStandard) - Customer Manager AngularJS/BreezeJS Application.

* [[GitHub] gigablox / angular-art-gallery](https://github.com/gigablox/angular-art-gallery) - Art Gallery application using dynamic API data built with AngularJS

* [[GitHub] konsumer / music_player](https://github.com/konsumer/music_player/) - A simple audio player example that uses Angular 

* [[GitHub] pikock / bootstrap-magic](https://github.com/pikock/bootstrap-magic) - Bootstrap themes generator, featuring Bootstrap 3.1 and AngularJS. Update your variables, change it with a smooth colorpicker and get instantly the result.

* [[GitHub] arvindr21 / fileBrowserApp](https://github.com/arvindr21/fileBrowserApp) - Building a Web Based File Browser with jsTree, Angularjs and Expressjs

  * [Building a Web Based File Browser with jsTree, Angularjs and Expressjs | The Jackal of Javascript](http://thejackalofjavascript.com/file-browser-with-jstree-angularjs-and-expressjs/)

--

* [SSE (Server-Sent Events) Sample with AngularJS in Play Java | TypeSafe](https://typesafe.com/activator/template/sse-chat-template-java)

  * [[GitHub] markusjura / sse-chat-java](https://github.com/markusjura/sse-chat-java)

--

* [[GitHub] pablodenadai / GameOn](https://github.com/pablodenadai/GameOn) - responsive front-end webapp built on NodeJS and Angular

  * [GameOn](http://gameon.jit.su/) - connects you with the players in your city and allows you to find, organize and share games effortlessly.

--

* [Radian](http://radian.io/) is a scalable AngularJS framework, perfect for multi developer projects

--

* [Back&](https://www.backand.com/) - is the fastest way to build and run a hosted AngularJS-based admin with your cloud database

  * [[GitHub] backand / ngback](https://github.com/backand/ngback) - angular integration with backand.com

--

* [CleverStack](http://cleverstack.io/) - A modular way to create your Angular & Node web apps

  * [[GitHub] CleverStack / cleverstack-cli](https://github.com/CleverStack/cleverstack-cli) - CLI for CleverStack


### With Gulp

* [[GitHub] wlepinski / gulp-angularjs-starter-project](https://github.com/wlepinski/gulp-angularjs-starter-project) - A started project using AngularJS and Compass

* [Let's build: An AngularJS app with Browserify and Gulp | Mindthecode](http://mindthecode.com/lets-build-an-angularjs-app-with-browserify-and-gulp/)

  * [[GitHub] Hyra / angular-gulp-browserify-livereload-boilerplate](https://github.com/Hyra/angular-gulp-browserify-livereload-boilerplate) - Example boilerplate for using Angular, Gulp, Express with LiveReload ad Browserify

* [Create a TV Show Tracker using AngularJS, Node.js and MongoDB | Sahat Yalkabov](http://sahatyalkabov.com/create-a-tv-show-tracker-using-angularjs-nodejs-and-mongodb/)

  * [[GitHub] sahat / tvshow-tracker](https://github.com/sahat/tvshow-tracker/) - AngularJS + Node + Gulp + Mongoose + Passport Authentication + TVDB API

* [DRY dependency injection in Angular with gulp-ng-annotate | Christian Fei](http://christian.fei.ninja/dry-dependency-injection-in-angular-with-gulp-ng-annotate/)


### MEAN Stack

* [MEAN Stack](http://mean.io/) - is a boilerplate that provides a nice starting point for MongoDB, Node.js, Express, and AngularJS based applications.

* [What is the MEAN stack? | You are IT!](http://tamaspiros.co.uk/2013/09/19/what-is-the-mean-stack/)

* [[YouTube] Getting MEAN | Google Developers](http://www.youtube.com/watch?v=XwSFg8nqBFA&t=1m39s)

* [[Speaker Deck] Developing MEAN applications](https://speakerdeck.com/voronianski/developing-mean-applications) - Simple overview of modules and other stuff that we've used while building http://likeastore.com using Mongodb, Express.js, Angular.js and Node.js stack.

* [[SlideShare] The MEAN Stack: MongoDB, ExpressJS, AngularJS and Node.js](http://pt.slideshare.net/mongodb/mongodb2-21677032) - by MongoDB

* [Full-Stack JavaScript With MEAN And Yeoman | AddyOsmani.com](http://addyosmani.com/blog/full-stack-javascript-with-mean-and-yeoman/)

* [Introduction to the MEAN Stack | Tuts+ Code Tutorial](http://code.tutsplus.com/tutorials/introduction-to-the-mean-stack--cms-19918)

* [Creating an RSS Feed Reader With the MEAN Stack | Tuts+ Code Tutorial](http://code.tutsplus.com/tutorials/creating-an-rss-feed-reader-with-the-mean-stack--cms-20563)

* [Build a real-time polls application with Node.js, Express, AngularJS, and MongoDB | IBM developerWorks](http://www.ibm.com/developerworks/library/wa-nodejs-polling-app/)

--

* [[GitHub] pilwon / ultimate-seed](https://github.com/pilwon/ultimate-seed) - MEAN Stack on Steroids

* [[GitHub] rafaelalmeidaerthalhermano / mean-stack](https://github.com/rafaelalmeidaerthalhermano/mean-stack) - Esse módulo implementa um boilerplate e um gerador de aplicações em MEAN.

* [[GitHub] wlepinski / generator-meanstack](https://github.com/wlepinski/generator-meanstack) - The MEAN stack generator for Yeoman

* [[GitHub] DaftMonk / generator-angular-fullstack](https://github.com/DaftMonk/generator-angular-fullstack) - Yeoman generator for AngularJS with an Express server

  * [Angular Fullstack 2.0: Released | Tyler Henkel's](http://tylerhenkel.com/angular-fullstack-2-0-released/)


### Angular-Seed

Projeto de exemplo / estrutura inicial

* **Oficial:** [[GitHub] angular / angular-seed](https://github.com/angular/angular-seed) | [Jenkins-CI](http://ci.angularjs.org/view/angular-seed/)

* **Fork:** [[GitHub] skivvies / angular-seed](https://github.com/skivvies/angular-seed) | [Travis-CI](https://travis-ci.org/skivvies/angular-seed)

* **require.js:** 

  * [[GitHub] ysilvestrov / angular-seed](https://github.com/ysilvestrov/angular-seed)

  * [[GitHub] CleverStack / angular-seed](https://github.com/CleverStack/angular-seed) - The AngularJS based Modular Frontend for CleverStack, MEAN and so much more [require.js | karma.js | protactor]


## Teste

> **Dependência**
> 
> As ferramentas de teste, para os projetos com Angular.js necessitam e executam sobre o [Node.js](http://nodejs.org/) | [[GitHub] erkobridee / lab-nodejs](https://github.com/erkobridee/lab-nodejs)
>

```javascript
describe('testing something...', function() {
  it('should do something...', function() {
    // arrange
      
      // TODO: define code

    // act
      
      // TODO: define code

    // assertions
      
      // TODO: define code
  });
});
```

--

* [AngularJS Video Tutorial: Testing Overview | EggHead.io](http://egghead.io/lessons/angularjs-testing-overview)

* [Angular in Production: What, How, When to Test? | NewCircle](https://thenewcircle.com/s/post/1649/angular_in_production_what_how_when_to_test_ari_lerner_video)

--

* [[GitHub] ricardohbin / angularjs-meetup-sp](https://github.com/ricardohbin/angularjs-meetup-sp) - Jasmine + Angular.mocks + Karma.JS

* [[YouTube] Testing Strategies for AngularJS](https://www.youtube.com/watch?v=UYVcY9EJcRs)
  
  * [[GitHub] davemo / lineman-angular-template](https://github.com/davemo/lineman-angular-template) - A Lineman Application Template using AngularJS

--

* [[GitHub] daniellmb / angular-test-patterns](https://github.com/daniellmb/angular-test-patterns) - High Quality Guide for Testing AngularJS

--

* [Intuitive AngularJS testing with Jasmine | HP Enterprise Business Community](http://h30499.www3.hp.com/t5/HP-Software-Developers-Blog/Intuitive-AngularJS-testing-with-Jasmine/ba-p/6159427) | [[Slid.es] angularjs-testing](http://slid.es/eitanpeer/angularjs-testing) - This presentation covers Jasmine, testing angular.js with Jasmine and even a small exercise (+solution)

* [Getting started with AngularJS Unit Testing | Tech Pro](http://tech.pro/tutorial/1473/getting-started-with-angularjs-unit-testing)

* [Getting started unit testing AngularJS | 25 days of AngularJS Calendar](http://www.ng-newsletter.com/advent2013/#!/day/19)

* [How To Unit Test An Angular App | Alex Rothenberg](http://www.alexrothenberg.com/2013/08/06/how-to-unit-test-an-angular-app.html)

* [Unit Testing Best Practices in AngularJS | Andy Shora](http://andyshora.com/unit-testing-best-practices-angularjs.html)

* [Full-Spectrum Testing with AngularJS and Karma | Year of moo](http://www.yearofmoo.com/2013/01/full-spectrum-testing-with-angularjs-and-karma.html) - Learn how to fully test your AngularJS application with Karma

  * [[GitHub] yearofmoo-articles / AngularJS-Testing-Article](https://github.com/yearofmoo-articles/AngularJS-Testing-Article) - A testing repository for AngularJS

* [Advanced Testing and Debugging in AngularJS | Year of moo](http://www.yearofmoo.com/2013/09/advanced-testing-and-debugging-in-angularjs.html)

* [Writing Tests and Stomping Bugs in AngularJS | Safari Books Online's Official Blog](http://blog.safaribooksonline.com/2014/04/01/writing-tests-stomping-bugs-angularjs/)

--

* [[JSFiddle] Angular unit tests - timeout, exception](http://jsfiddle.net/eitanp461/vWecL/)

  * [$timeout | Angular API Reference](https://docs.angularjs.org/api/ng/service/$timeout)

* [Testing Interceptor Headers in AngularJS | Josh Bavari's Ramblings](https://jbavari.github.io/blog/2014/06/20/testing-interceptor-headers-in-angularjs/)

--

* [Introduction to unit test: Directives | Angular Tips](http://angular-tips.com/blog/2014/06/introduction-to-unit-test-directives/)

* [How To Test An AngularJS Directive | Newtriks LTD](http://newtriks.com/2013/04/26/how-to-test-an-angularjs-directive/)

* [[GitHub] vojtajina / ng-directive-testing](https://github.com/vojtajina/ng-directive-testing) - Simple example of testing Angular's directives

* [Testing AngularJS Directives:  Handling External Templates | Portland Webworks](http://www.portlandwebworks.com/blog/testing-angularjs-directives-handling-external-templates)

* [Testing External Templates in Angular | Nysa Vann](http://www.nysavann.com/javascript/testing/2013/10/01/testing-external-templates-in-angular.html)

--

* Try, Catch, Fail : AngularJS - Unit Testing

  * [Controllers](http://www.benlesh.com/2013/05/angularjs-unit-testing-controllers.html)

  * [Services](http://www.benlesh.com/2013/06/angular-js-unit-testing-services.html)

  * [Directives](http://www.benlesh.com/2013/06/angular-js-unit-testing-directives.html)

-- 

* [Creating an Eclipse UI to run AngularJS e2e tests using Karma | Dinis Cruz Blog](http://blog.diniscruz.com/2014/02/creating-eclipse-ui-to-run-angularjs.html)

* [[GitHub] michaelgruczel / angularJs-Jasmine-Example](https://github.com/michaelgruczel/angularJs-Jasmine-Example) - This is an extremely simple example for angular js and jasmine

--

* [[GitHub] angular / protractor](https://github.com/angular/protractor) - E2E test framework for Angular apps

  * [Protractor E2E Testing Resources | AngularJS 4U](http://angularjs4u.com/protractor/protractor-e2e-testing-resources/)

  * [Practical End-to-End Testing with Protractor | ng-newsletter](http://www.ng-newsletter.com/posts/practical-protractor.html)

  * [[YouTube] An Introduction to AngularJS End to End Testing with Protractor](https://www.youtube.com/watch?v=idb6hOxlyb8)

  * [Getting Started with Protractor and Page Objects for AngularJS E2E Testing | Gaslight](http://teamgaslight.com/blog/getting-started-with-protractor-and-page-objects-for-angularjs-e2e-testing)
  
  * [Protractor for AngularJS: writing end-to-end test has never been so fun](http://ramonvictor.github.io/protractor/slides/#/) - A step-by-step presentaion on Protractor End-to-End Testing for AngularJS

--

* [[GitHub] decipherinc / angular-debaser](https://github.com/decipherinc/angular-debaser/) - Just a better way to test AngularJS apps

--

* With Require.js

  * [Karma.js v0.12 + Require.js](https://karma-runner.github.io/0.12/plus/requirejs.html)

  * [Testing AngularJS in a RequireJS environment | Radius Engineering Blog](http://engineering.radius.com/post/77677879234/testing-angularjs-in-a-requirejs-environment)

    * [[GitHub] RadiusIntelligence / require-and-angular-test](https://github.com/RadiusIntelligence/require-and-angular-test) - Example setup for testing AngularJS applications that are built with RequireJS



### Mock

* [Prototype Angular UIs Without A Backend | OpenSource Connections](http://www.opensourceconnections.com/2013/09/16/prototype-angular-uis-without-a-backend/)

* [[GitHub] erkobridee / angular-mocks-backend](https://github.com/erkobridee/angular-mocks-backend) - Extend Angular.js Mocks to emulate backend, intercepting http requests with $httpBackend.when()

--

* [DRY Up Your $httpBackend mock | Burnside Digital Blog](http://blogs.burnsidedigital.com/2013/10/dry-up-your-httpbackend-mock/)

* [How to mock AngularJS modules and inject them in your testacular tests?](http://southdesign.de/blog/mock-angular-js-modules-for-test-di.html)

* [Supplying Mocks for Services via $provide | Tech Pro](http://tech.pro/tutorial/1517/supplying-mocks-for-services-via-provide)

* [[StackOverlfow] inject mocks into service or factory by using $provider](https://stackoverflow.com/questions/14773269/injecting-a-mock-into-an-angularjs-service/18756347#18756347)

* [Mocking Server Dependencies in JavaScript and AngularJS | Flippin' Awesome](http://flippinawesome.org/2013/09/09/mocking-server-dependencies-in-javascript-and-angularjs/)

* [How to verify JSON data with AngularJS $httpBackend | Thinking in Crowd](http://www.thinkingincrowd.me/blog/2013/06/08/how-to-verify-json-data-with-angularjs-httpbackend/)

--

* [[GitHub] atecarlos / protractor-http-mock](https://github.com/atecarlos/protractor-http-mock) - A library designed to work alongside Protractor for setting mocks for your HTTP ajax requests


### CI

* Jenkins CI : [ci.angularjs.org](http://ci.angularjs.org/) | [configurações](https://github.com/angular/ci.angularjs.org)

* [[YouTube] AngularJS CI Server Overview](https://www.youtube.com/watch?v=5GGMa6mmcg0) - 03/09/2011

--

* [The AngularJS CI Server: Automated cross-browser testing for fun and profit](http://www.meetup.com/AngularJS-MTV/events/102051832/) -  AngularJS Mountain View (Mountain View, CA) | Meetup

  * [[YouTube] Feb - AngularJS MTV Meetup Livestream: CI Server](https://www.youtube.com/watch?v=BNpV7npURhE) - 12/02/2013

    * [[Google Docs] Continuous Integration Testing of AngularJS](https://docs.google.com/presentation/d/1-j264F0Q8k3NzionQspx7fhKd2E8XPkIKItxz2qhN28)

--

* [Getting Jenkins ready for Node.js and AngularJS testing | Shane A. Stillwell](http://www.shanestillwell.com/2013/01/15/getting-jenkins-ready-for-node-js-and-angularjs-testing/) - Setting up Jenkins for Node.js + Mocha testing and such Install this stuff. Node.js via Nave.

* [Using Testacular(Karma) with Jenkins for AngularJS e2e Testing | Shane A. Stillwell](http://www.shanestillwell.com/2013/01/09/using-testacular-with-jenkins-for-angularjs-e2e-testing/)

--

* [Jenkins Configuration for a Yeoman based AngularJS web application | Portland Webworks](http://www.portlandwebworks.com/blog/jenkins-configuration-yeoman-based-angularjs-web-application)

* [Continuous Deployment with Yeoman and Jenkins | weluse GmbH](https://weluse.de/blog/continuous-deployment-with-yeoman-and-jenkins.html)

