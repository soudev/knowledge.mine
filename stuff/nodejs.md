# Node.js

<!-- toc -->
* [Visão Geral](#visão-geral)
* [Sites Oficiais](#sites-oficiais)
* [Aprendizado](#aprendizado)
* [Comunidades e Grupos](#comunidades-e-grupos)
* [Casos de Uso](#casos-de-uso)
  * [IBM developerWorks](#ibm-developerworks)
* [Projetos Interessantes](#projetos-interessantes)
  * [Desenvolvimento](#desenvolvimento)
    * [Configuração do Ambiente](#configuração-do-ambiente)
      * [dotFiles: Mac OS X config](#dotfiles-mac-os-x-config)
    * [Exemplos](#exemplos)
      * [Boilerplate](#boilerplate)
  * [Código](#código)
    * [Performance, Proteção e Otimização](#performance-proteção-e-otimização)
    * [Análise](#análise)
  * [Monitoramento e Logs](#monitoramento-e-logs)
  * [Versionamento](#versionamento)
  * [Identificadores](#identificadores)
  * [Encurtador de URLs](#encurtador-de-urls)
  * [Desencurtador de URLs](#desencurtador-de-urls)
  * [Controle de Fluxo de Execução](#controle-de-fluxo-de-execução)
  * [Git e GitHub](#git-e-github)
  * [Integração com Java](#integração-com-java)
  * [BitCoins](#bitcoins)
  * [Photoshop CC](#photoshop-cc)
  * [Torrent](#torrent)
  * [Node.js no Servidor](#nodejs-no-servidor)
    * [OAuth](#oauth)
    * [Fórum](#fórum)
    * [Gerenciador de Conteúdo](#gerenciador-de-conteúdo)
    * [Jogos](#jogos)
  * [Site Estático](#site-estático)
  * [Hardware](#hardware)
    * [Node Copter](#node-copter)
    * [Lego Mindstorms](#lego-mindstorms)
    * [Tessel](#tessel)
    * [Espruino](#espruino)
    * [Arduino](#arduino)
    * [RaspberryPi](#raspberrypi)
* [Abstract Syntax Tree](#abstract-syntax-tree)
* [Dicas](#dicas)
  * [portable code](#portable-code)
  * [fake data](#fake-data)
  * [command and shell](#command-and-shell)
  * [process manager](#process-manager)
  * [Produção](#produção)
  * [REST](#rest)
  * [Authentication](#authentication)
    * [WebID](#webid)
  * [Módulo](#módulo)
  * [url rewrite proxy](#url-rewrite-proxy)
  * [NPM](#npm)
  * [CORS](#cors)
  * [Armazenamento](#armazenamento)
  * [Virtualização](#virtualização)
    * [Docker](#docker)
  * [Nuvem](#nuvem)
    * [Pessoal](#pessoal)
    * [Amazon AWS](#amazon-aws)
      * [Amazon S3](#amazon-s3)
    * [Windows Azure](#windows-azure)
  * [Mobile](#mobile)
    * [iOS](#ios)
  * [Desktop](#desktop)
    * [Node Webkit](#node-webkit)
      * [node-webkit: exemplos](#node-webkit-exemplos)
      * [node-webkit: Aplicações e Empresas que utilizam](#node-webkit-aplicações-e-empresas-que-utilizam)
  * [Modulos e Frameworks](#modulos-e-frameworks)
    * [Socket.io](#socketio)
    * [Connect](#connect)
    * [Express.js](#expressjs)
    * [Meteor](#meteor)
  * [Ferramentas](#ferramentas)
    * [Visual Studio](#visual-studio)
    * [Eclipse IDE](#eclipse-ide)
    * [JetBrains](#jetbrains)
  * [Testes](#testes)

<!-- toc stop -->

## Visão Geral

**Motivação**

> Um dos motivos do interesse pelo Node.js é a possibilidade de executar códigos JavaScript sem a necessidade de um Web Browser. Com isto e sobre o Node.js surgiram muitas ferramentas de automatização, qualidade e teste de software para projetos FrontEnd.

> Um exemplo de uso do Node.js com o Jenkins CI pode ser encontrado no : [ci.angularjs.org](http://ci.angularjs.org/) | [configurações](https://github.com/angular/ci.angularjs.org) - o qual é utilizado pelo framework MVC JavaScript Angular.js


* [Utilizando o Node.js em um Windows sem Administrador](https://gist.github.com/erkobridee/4089098)

* [Node.js Infographic :: The State of Node | Strong Loop](http://strongloop.com/infographic)

* [O que as empresas dizem sobre o Node.js](http://nodejs.org/industry/)

* [[SlideShare] Conhecendo mundo Node.js](http://www.slideshare.net/caioribeiropereira/conhecendo-mundo-nodejs-12813969)

* [O que exatamente é o Node.js? | IBM developerWorks](http://www.ibm.com/developerworks/br/library/os-nodejs/)

* [A Case-by-Case Introduction to Node.js | Toptal](http://www.toptal.com/nodejs/why-the-hell-would-i-use-node-js)

--

* [[GitHub] zeMirco / nodejs-pdf-docs](https://github.com/zeMirco/nodejs-pdf-docs) - Node.js Manual & Documentation (.pdf, .mobi, .epub)

--

* [[GitHub] erkobridee / lab-nodejs](https://github.com/erkobridee/lab-nodejs) - Laboratório de testes com o Node.js

* [[GitHub] simonholmes / knowing-node](https://github.com/simonholmes/knowing-node/) - Holds the code files from my Knowing Node tutorials



## Sites Oficiais

* [Node.js](http://nodejs.org/)

* [Node.js API DOCS](http://nodejs.org/api/)

* [Node.js Manual](http://nodemanual.org/latest/)

* [GitHub : Joyent / Node.js : Wiki / Modules](https://github.com/joyent/node/wiki/modules)

* [npm - Node Packaged Modules](https://npmjs.org/)

* [Node.js Jenkins-CI](http://jenkins.nodejs.org/) - To  support a higher degree of stability, and hopefully catch issues sooner,  we (node.js team) have a Jenkins instance running every commit through  the test suite, on each operating system we support.

  * [NodeJS Plugin - Jenkins | Jenkins Wiki](https://wiki.jenkins-ci.org/display/JENKINS/NodeJS+Plugin)


## Aprendizado

* [Enter the World of Node.js | SitePoint](http://www.sitepoint.com/enter-world-node-js/)

* [How to Node](http://howtonode.org/)

* [5 Free Beginner Friendly Books for Learning Node.js | CodeCondo](http://codecondo.com/5-free-beginner-friendly-books-learning-node-js/)

* [The Node Beginner Book](http://www.nodebeginner.org/)

* [[GitHub] rockbot / node-for-beginners](https://github.com/rockbot/node-for-beginners) - A list of resources for Node.js Newbies!

* [An Absolute Beginner's Guide to Node.js | Modulus Blog](http://blog.modulus.io/absolute-beginners-guide-to-nodejs)

* [The Absolute Beginner’s Guide to Node.js | Codeship](http://blog.codeship.io/2014/05/07/nodejs-beginners-guide.html)

* [[GitHub] maxogden / art-of-node](https://github.com/maxogden/art-of-node) - The Art of Node.js : a short introduction to node.js

* [[GitHub] rvagg / learnyounode](https://github.com/rvagg/learnyounode) - Learn You The Node.js For Much Win! An intro to Node.js via a set of self-guided workshops.

* [Node.js for Beginners | Nettuts+](http://net.tutsplus.com/tutorials/javascript-ajax/node-js-for-beginners/)

* [Node School](http://nodeschool.io/) - Learn Node.JS with interactive lessons

* [Node.js: A Jumpstart for Devs | NewCircle](https://thenewcircle.com/s/post/1534/nodejs_tutorial_videos_geolocation_app)

--

* [Node.js | Underground WebDev](http://udgwebdev.com/nodejs/)

* [Node.js para leigos (Versão completa) | Underground WebDev](http://www.udgwebdev.com/nodejs-para-leigos/)

* [Quer aprender Node.js? (Atualizado) | Underground WebDev](http://udgwebdev.com/quer-aprender-node-js-atualizado/)

--

* [Teach Yourself Node.JS in 10 Steps | Pony Foo](http://blog.ponyfoo.com/2013/07/12/teach-yourself-nodejs-in-10-steps)

* [7 tips for a Node.js padawan | Tech Talk — Medium](https://medium.com/tech-talk/e7c0b0e5ce3c) - Node.js development is extremely fun and satisfying. There are over 35k modules to choose from, and overall node is very easy to develop a working application that can scale easily

--

* [[SlideShare] Nodejs Explained with Examples](http://www.slideshare.net/gabriele.lana/nodejs-explained-with-examples)

* [Understanding how to create a nodejs package.json | Nodejitsu](http://package.json.nodejitsu.com/) - Package.json: an interactive guide

* [Entendendo o Event-loop do Node.js | iMasters](http://imasters.com.br/front-end/javascript/entendendo-o-event-loop-do-node-js/)

* [Understanding the node.js event loop](http://blog.mixu.net/2011/02/01/understanding-the-node-js-event-loop/)

* [Mastering Node.js](http://visionmedia.github.com/masteringnode/) Open Source Node eBook

* [Learning Server-Side JavaScript with Node.js](http://net.tutsplus.com/tutorials/javascript-ajax/learning-serverside-javascript-with-node-js/)

* [Node.js : Require and Exports](http://openmymind.net/2012/2/3/Node-Require-and-Exports/)

* [How to Use Exports in NodeJS | Liang Zan](http://blog.liangzan.net/blog/2012/06/04/how-to-use-exports-in-nodejs/)

* [Export This: Interface Design Patterns for Node.js Modules | Bites from Good Eggs](http://bites.goodeggs.com/posts/export-this/)

* [How I write Node.js modules](http://substack.net/how_I_write_modules)

* [Learn Node.js Completely and with Confidence](http://javascriptissexy.com/learn-node-js-completely-and-with-confidence/)

* [Getting Started with Node.js, Coffeescript, MongoDB, and more - Matt Kopala](http://mattkopala.com/blog/2012/02/12/getting-started-with-nodejs/)

* [5 Talks to Learn More About Node.js](http://blog.modulus.io/five-talks-learn-more-nodejs)

* [[YouTube] Node.js Explained](https://www.youtube.com/watch?v=L0pjVcIsU6A)

* [Using Node.s Event Module | Nettuts+](http://net.tutsplus.com/tutorials/javascript-ajax/using-nodes-event-module/)

* [Understanding Exceptions and Domains in Node.js | How to JS](http://www.howtojs.org/understanding-exceptions-domains-in-nodejs/)


## Comunidades e Grupos

* [NodeBR](http://nodebr.com/) - é o repositório de artigos da comunidade brasileira de node.js

* [Node.js Brasil](http://nodejsbrasil.com.br/) - Blog comunitário da comunidade de Node.js brasileira

  * [Grupo no Facebook](https://www.facebook.com/groups/nodejsbrasil/)

  * [Grupo no Google+](https://plus.google.com/u/0/communities/114677724833864547063)

* [npm awesome](http://npmawesome.com/)


## Casos de Uso

* [Projects, Applications, and Companies Using Node](https://github.com/joyent/node/wiki/Projects,-Applications,-and-Companies-Using-Node) - GitHub wiki : joyent / node

* [Industry | Nodejs.org](http://nodejs.org/industry/)

* [Can You Count on Node? - Blog - Joyent](http://joyent.com/blog/can-you-count-on-node)

--

* [Geekli.st](https://geekli.st/erkobridee/invite/196DA487FB) - rede social construída com Node.js | [Sobre a Geekli.st e tecnologias utilizadas](https://geekli.st/about)

* [GitMoon](http://www.gitmoon.com/) Social analytics for Node.js developers | [GitHub : code](https://github.com/yaronn/gitmoon)

* [Building CSSDB: a short case-study on the build of a small Node.js / MongoDB application](http://rowanmanning.com/posts/building-cssdb/)

* [How We Built eBay’s First Node.js Application](http://www.ebaytechblog.com/2013/05/17/how-we-built-ebays-first-node-js-application/)

* [Getting Physical: Networked Hardware with Node.js | InfoQ](http://www.infoq.com/presentations/Hardware-Nodejs-WiFi-XBee) - Ted Hayes discusses WiFi, XBee and their associated network topologies, and demoes controlling a networked pong game with a physical joystick using Node.js.

* [Utilizando Node.js para automação de build e deploy no dell.com | BrazilJS 2013](http://bitbonsai.com/braziljs2013/)

* [[YouTube] The Business Case for Node](https://www.youtube.com/watch?v=bqLXjNbMZpY)

* [Node.js at PayPal | PayPal Engineering Blog](https://www.paypal-engineering.com/2013/11/22/node-js-at-paypal/)

  * [How PayPal is Being Revolutionized by Node.js and Lean UX | nearForm](http://www.nearform.com/nodecrunch/release-the-kracken-how-paypal-is-being-revolutionized-by-node-js-and-lean-ux)

* [Why Node.js is becoming the go-to technology in the Enterprise | Node Crunch](http://www.nearform.com/nodecrunch/node-js-becoming-go-technology-enterprise)


### IBM developerWorks

* [Developing mobile apps with Node.js and MongoDB, Part 1: A team's methods and results](http://www.ibm.com/developerworks/java/library/mo-nodejs-1/index.html)

* [Developing mobile apps with Node.js and MongoDB, Part 2: Hints and tips](http://www.ibm.com/developerworks/mobile/library/mo-nodejs-2/index.html)


## Projetos Interessantes

* [Node Twitter Sentiment | Michael Herman](http://mherman.org/blog/2014/02/19/node-twitter-sentiment/)

* [[GitHub] thisandagain / sentiment](https://github.com/thisandagain/sentiment) - AFINN-based sentiment analysis for Node.js

  * [Sentiment analysis in Node.js | Nodejitsu](https://blog.nodejitsu.com/npmawesome-sentiment/)

--

* [VNC client on 200 lines of JavaScript | Minko Gechev's blog](http://blog.mgechev.com/2013/08/30/vnc-javascript-nodejs/)

--

* [[GitHub] skynetim / skynet](https://github.com/skynetim/skynet) - Machine-to-machine instant messaging platform for the internet of things

* [[GitHub] fent / node-ytdl](https://github.com/fent/node-ytdl) - Pure Javascript youtube video downloader

* [[GitHub] leetreveil / node-musicmetadata](https://github.com/leetreveil/node-musicmetadata) - Streaming music metadata parser for node, written in pure Javascript

* [[GitHub] ConradIrwin / unicode-dragon](https://github.com/ConradIrwin/unicode-dragon) - eats invalid unicode for breakfast

* [[GitHub] jtrussell / bedecked](https://github.com/jtrussell/bedecked) - Turn markdown files into html presentations you can share with dropbox (or S3, or...)

--

* [[GitHub] ltk / kurtz-kloud](https://github.com/ltk/kurtz-kloud) - A Node app for sharing screen shots

  * [My Quest for the Perfect Screenshot App | Viget](http://viget.com/flourish/my-qwest-for-the-perfect-screenshot-app)

--

* [[GitHub] jh3y / sike](https://github.com/jh3y/sike) - a cli tool that reminds you to get up and move around


### Desenvolvimento

* [NoFlo | Flow-Based Programming for JavaScript](http://noflojs.org/)

* [[GitHub] idflood / ThreeNodes.js](https://github.com/idflood/ThreeNodes.js) - This is an attempt to make something like "vvvv" in javascript, html and webgl.

--

* [Node Console](http://www.node-console.com/script/code) - test node.js apps online

* [[GitHub] MatthewMueller / coderunner](https://github.com/matthewmueller/coderunner) - Run server-side code quickly and securely in the browser

--

* [[GitHub] steves / node-jira](https://github.com/steves/node-jira) - A nodejs wrapper for the JIRA REST API

--

* [[GitHub] shakyShane / browser-sync](https://github.com/shakyShane/browser-sync) - Keep multiple browsers & devices in sync when building websites.

* [[GitHub] sindresorhus / pageres](https://github.com/sindresorhus/pageres) - Get screenshots of websites in different resolutions 

--

* [[GitHub] MatthewMueller / cheerio](https://github.com/MatthewMueller/cheerio)

  * [Use Node.js to Extract Data from the Web for Fun and Profit | Stormin' The Castle](http://www.storminthecastle.com/2013/08/25/use-node-js-to-extract-data-from-the-web-for-fun-and-profit/)

  * [Mineração de dados e as funções map, reduce e filter | NodeBR - NodeJS Brasil](http://nodebr.com/mineracao-de-dados-e-as-funcoes-map-reduce-filter/)

--

* [Running and debugging Node.js application | JetBrains WebStorm Blog](http://blog.jetbrains.com/webstorm/2014/02/running-and-debugging-node-js-application/)

* [How to debug Node.js? What is the best way to debug Node.js? | { 100PercentJS }](http://www.100percentjs.com/best-way-debug-node-js/)


#### Configuração do Ambiente

* [[GitHub] feross / hostile](https://github.com/feross/hostile) - Simple, programmatic `/etc/hosts` manipulation (in node.js)

##### dotFiles: Mac OS X config

* [[GitHub] eduardolundgren / dotfiles](https://github.com/eduardolundgren/dotfiles) - The first JavaScript-based dotfiles powered by Grunt


#### Exemplos

* [[GitHub] gravityonmars / nodejs-starter](https://github.com/gravityonmars/nodejs-starter) - Simple project setup using industry's best practices and modules. Node.js, Express, Mongoose, passport.js, component.io, Jade, Stylus and Bootstrap

##### Boilerplate

* [[GitHub] bryanro / nodejs-boilerplate](https://github.com/bryanro/nodejs-boilerplate) - Template for nodejs RESTful web services and optional front-end

  * [Node.js Boilerplate: Express, Mongo, Cross-Origin, and More | bryankrosenbaum.com](http://bryankrosenbaum.com/2013/10/17/node-js-boilerplate/)

* [[GitHub] eunjae-lee / node-express-grunt-boilerplate](https://github.com/eunjae-lee/node-express-grunt-boilerplate) - A boilerplate to start a new express project based on CoffeeScript, Grunt build system, forever runner, Jade Template Engine and bootstrap

* [[GitHub] erictherobot / kano](https://github.com/erictherobot/kano) - Boilerplate for NodeJS + ExpressJS + MongoDB + Jade + Bootstrap 3 + Mocha + API's


### Código

* [Contractual - Design by contract for JavaScript](https://codemix.github.io/contractual/)


#### Performance, Proteção e Otimização

* [JXCore](http://jxcore.com/)

* [Code Protection and Packaging for Node.js Projects with JXCore | Flippin' Awesome](http://flippinawesome.org/2014/04/21/code-protection-and-packaging-for-node-js-projects-with-jxcore/)


#### Análise

* [[GitHub] t32k / stylestats](https://github.com/t32k/stylestats) - StyleStats is Node.js library to collect CSS statistics!

* [[GitHub] mdevils / node-jscs](https://github.com/mdevils/node-jscs) - JavaScript Code Style checker

* [[GitHub] es-analysis / plato](https://github.com/es-analysis/plato) - JavaScript source code visualization, static analysis, and complexity tool

  * [JavaScript Code Complexity Visualization | Ariya Hidayat](http://ariya.ofilabs.com/2013/01/javascript-code-complexity-visualization.html)


### Monitoramento e Logs

* [[GitHub] niallo / node-httpcheck](https://github.com/niallo/node-httpcheck) - Simple HTTP status checker with timeout

* [GitHub : Status Dashboard](https://github.com/obazoud/statusdashboard) - Status Dashboard is status page for your configured services or applications.

* [dnc : a CLI tool to check domain names configuration and statistics](http://www.cambus.net/dnc-a-cli-tool-to-check-domain-names-configuration-and-statistics/)

  * [[GitHub] fcambus / dnc](https://github.com/fcambus/dnc) - A CLI tool to check domain names configuration and statistics

* [[GitHub] NarrativeScience / Log.io](https://github.com/NarrativeScience/Log.io)

  * [log.io](http://logio.org/) - Real-time log monitoring in your browser


### Versionamento

* [[GitHub] webpro / release-it](https://github.com/webpro/release-it) - Interactive release tool for Git repositories. Supports to build and release to a distribution/component repository. Publish to npm.

* [[GitHub] radubrehar / versiony](https://github.com/radubrehar/versiony) - Node.js module to increment version number for your code/module


### Identificadores 

* [uuid | node.js modules](https://nodejsmodules.org/tags/uuid)

* [[GitHub] broofa / node-uuid](https://github.com/broofa/node-uuid) - Generate RFC-compliant UUIDs in JavaScript

* [[GitHub] dilvie / cuid](https://github.com/dilvie/cuid) - Collision-resistant ids optimized for horizontal scaling and performance

* [[GitHub] chilts / flake](https://github.com/chilts/flake) - Generate practically unique (approximately sortable) IDs in a distributed environment

* [[GitHub] substack / node-hat](https://github.com/substack/node-hat) - Generate random IDs and avoid collisions | 

  * [node.js | hashids](http://www.hashids.org/node-js/) - Generate short hashes from numbers (like YouTube and Bitly).

* [[GitHub] dylang / shortid](https://github.com/dylang/shortid) - Short id generator. Url-friendly. Non-predictable. Cluster-compatible.

  * [[GitHub] jetpks / shortness](https://github.com/jetpks/shortness) - A url shortening library written with node.js and sqlite3

* [[GitHub] UmbraEngineering / short-id](https://github.com/UmbraEngineering/short-id) - Short ID String Generation for Node.js


### Encurtador de URLs

* [[GitHub] edwardhotchkiss / short](https://github.com/edwardhotchkiss/short) - Promise-based Node.js URL Shortener (use short-id) backed by Mongoose.js

* [[GitHub] thinkroth / shortUrl](https://github.com/thinkroth/shortUrl) - Another short url service in node.js


### Desencurtador de URLs

* [[GitHub] scottksmith95 / url-expand](https://github.com/scottksmith95/url-expand) - Simple and efficient URL expander


### Controle de Fluxo de Execução

* [async](http://bredele.github.io/async/) - A collection of asynchronous patterns for nodejs and browsers

* [Async - utilities for node and the browser](https://github.com/caolan/async)

  * [Node.js async in practice: When to use what? | Sebastian Seilund](http://www.sebastianseilund.com/nodejs-async-in-practice)

  * [Different uses of node-async library | Abhiroop Patel](http://abhiroop.com/different-uses-node-async-library/)

  * [[GitHub] scottcorgan / series](https://github.com/scottcorgan/series) - Compose a series of chainable async methods

* [Cyclop - Stupid simple control flow library](https://github.com/vesln/cyclop)

* [[GitHub] luciotato / waitfor](https://github.com/luciotato/waitfor) - Sequential programming for node.js, end of callback hell

* [[GitHub] kriskowal / q](https://github.com/kriskowal/q) - A tool for making and composing asynchronous promises in JavaScript

* [[GitHub] philbooth / trier.js](https://github.com/philbooth/trier.js) - Conditional and repeated function invocation for node and browser

* [[GitHub] Sahadar / pubsub.js](https://github.com/Sahadar/pubsub.js) - JavaScript pubsub implementation with wildcards, inheritance and multisubscribtions

--

* [Como evitar o inferno de callbacks | NodeBR - NodeJS Brasil](http://nodebr.com/como-evitar-o-inferno-de-callbacks/)

* [Evitando callback hell no Node.js | Underground WebDev](http://udgwebdev.com/evitando-callback-hell-no-node-js/)


### Git e GitHub

* [Node GH](http://nodegh.io/) = NodeJS + GitHub - GitHub command line tools

* ungit : [[GitHub] FredrikNoren / ungit](https://github.com/FredrikNoren/ungit) | [npm](https://npmjs.org/package/ungit) | [[Youtube] Introduction](https://www.youtube.com/watch?v=hkBVAi3oKvo) - The easiest way to use git. On any platform. Anywhere.

* [[GitHub] creationix / js-git](https://github.com/creationix/js-git) - JS-Git an open source project implementing git client and server in pure JavaScript

* [[GitHub] nodegit / nodegit](https://github.com/nodegit/nodegit) - Native asynchronous bindings to libgit2 for Node.js

--

* [[GitHub] GitbookIO / gitbook](https://github.com/GitbookIO/gitbook) -  is a command line tool (and Node.js library) for building beautiful programming books and exercises using GitHub/Git and Markdown. 

  * [Learn Javascript](http://gitbookio.github.io/javascript/)

  * [Survive JavaScript - a Web Developer's Guide](http://survivejs.com/)

  * [gitbook.io](http://www.gitbook.io/)


### Integração com Java

* [[GitHub] dynjs / dynjs](https://github.com/dynjs/dynjs) - (almost) 100% invokedynamic js impl. DynJS is an ECMAScript runtime for the JVM.

* [[GitHub] projectodd / nodyn](https://github.com/projectodd/nodyn) - A node.js compatible framework, running on the JVM. Powered by Vert.x and the DynJS Javascript runtime.s

--

* [[GitHub] YaroslavGaponov / node-jvm](https://github.com/YaroslavGaponov/node-jvm) - java virtual machine in pure node.js

* [How to run Node.js on the JVM with Avatar.js and LoopBack | StrongLoop](http://strongloop.com/strongblog/how-to-run-node-js-on-the-jvm-with-avatar-js-and-loopback/)

* [Nashorn: The New Rhino on the Block](http://ariya.ofilabs.com/2014/03/nashorn-the-new-rhino-on-the-block.html)

* [Running Node.js applications on the JVM with Nashorn and Java 8 | CLOSED-LOOP](http://blog.jonasbandi.net/2014/03/running-nodejs-applications-on-jvm-with.html)


### BitCoins

* [[GitHub] bitpay / bitcore](https://github.com/bitpay/bitcore)

* [Bitcore](http://bitcore.io/) - A pure, powerful core for your bitcoin project. Bitcore is a complete, native interface to the Bitcoin network, and provides the core functionality needed to develop apps for bitcoin.


### Photoshop CC

* [Introducing Adobe Generator for Photoshop CC](http://blogs.adobe.com/photoshopdotcom/2013/09/introducing-adobe-generator-for-photoshop-cc.html) - Generator is based on the popular Node.js platform and plug-ins can be written in JavaScript. 

* [Generator plugins are Open Source and available on GitHub](https://github.com/adobe-photoshop/)

* [Introduction to Photoshop Generator | Lee Brimelow](http://www.leebrimelow.com/introduction-to-photoshop-generator/)


### Torrent

* [[GitHub] mafintosh / peerflix](https://github.com/mafintosh/peerflix) - a streaming torrent client

* [[GitHub] mafintosh / peerflix-engine](https://github.com/mafintosh/peerflix-engine) - The low level streaming torrent engine that peerflix will use


### Node.js no Servidor

* [[GitHub] indutny / node-spdy](https://github.com/indutny/node-spdy) - SPDY server on Node.js

* [DynoSRC](http://dinosrc.it/) - Eliminate HTTP requests for JavaScript files and serve differential updates to your users on the fly. No, really. Like, seriously.

* [[GitHub] williamwicks / litesocket](https://github.com/williamwicks/litesocket) - Realtime server events for Node.JS, using Server Sent Events (SSE)

--

* [Nodemailer](http://www.nodemailer.com/) - is an easy to use module to send e-mails with Node.JS (using SMTP or sendmail or Amazon SES or even your own method) and is unicode friendly - You can use any characters you like

  * [[GitHub] andris9 / Nodemailer](https://github.com/andris9/Nodemailer) - Send e-mails with Node.JS - easy as cake!


--

* [[GitHub] topcloud / cachemere](https://github.com/topcloud/cachemere) - A nice, smooth, cushiony layer of cache

--

* [[GitHub] giodamelio / takeapeek](https://github.com/giodamelio/takeapeek) - A simple static webserver with only one command 

* [[GitHub] dharmafly / noodle](https://github.com/dharmafly/noodle) - A node server and module which allows for cross-domain page scraping on web documents with JSONP or POST

--

* [mongo-express](http://andzdroid.github.io/mongo-express/) - Web-based MongoDB admin interface written with Node.js and express

--

* [[GitHub] simonewebdesign / real-time-web-chat](https://github.com/simonewebdesign/real-time-web-chat) - A chat built with NodeJS, ExpressJS and Socket.io | [Demo App on OpenShift](https://github.com/simonewebdesign/real-time-web-chat)

--

* [Harp - An open-source web server with built-in pre-processing](http://harpjs.com/) - Harp serves Jade, Markdown, EJS, CoffeeScript, LESS and Stylus as HTML, CSS & JavaScript—no configuration necessary. It makes front-end development a treat

  * [Introduction to the Harp Web Server | Introductory Screencast - Harp](http://harpjs.com/blog/introductory-screencast)

* [Hapi : server framework for Node.js](http://spumko.github.io/)

  * [Node.js and Hapi - Creating a REST API | Modulus Blog](http://blog.modulus.io/nodejs-and-hapi-create-rest-api)

* [[GitHub] strongloop / loopback](https://github.com/strongloop/loopback) - is an open source API framework built on top of Express optimized for mobile and web. Connect to multiple data sources, write business logic in Node.js, glue on top of your existing services and data, connect using JS, iOS & Android SDKs.

* [Introduction to the MEAN Stack | Tuts+ Code Tutorial](http://code.tutsplus.com/tutorials/introduction-to-the-mean-stack--cms-19918)

* [MEAN Stack – A Quick Start Guide | Flippin' Awesome](http://flippinawesome.org/2014/04/21/mean-stack-a-quick-start-guide/) - This article is intended to serve as a quick guide to help you get started developing with the MEAN stack. We won’t go into great detail about what each of the technologies are, instead sticking to how to set up a typical MEAN stack.

* [Creating an RSS Feed Reader With the MEAN Stack | Tuts+ Code Tutorial](http://code.tutsplus.com/tutorials/creating-an-rss-feed-reader-with-the-mean-stack--cms-20563)


#### OAuth

* [[GitHub] thomseddon / node-oauth2-server](https://github.com/thomseddon/node-oauth2-server/) - Complete, compliant and well tested module for implementing an OAuth2 Server/Provider with express in node.js

  * [Building a Node OAuth2 server | Papers: The footnotes](http://blog.papersapp.com/oauth-server-in-node-js/)


#### Fórum

* [NodeBB](https://nodebb.com/) - Forums, re-designed from the ground up to take advantage of the latest web technologies. Modern forums for the modern web.

  * [In the Loop: NodeBB, Using Node.js to Become the Discussion Platform of the Future | StrongLoop](http://strongloop.com/strongblog/in-the-loop-nodebb-using-node-js-to-become-the-discussion-platform-of-the-future/)


#### Gerenciador de Conteúdo

* [[GitHub] dai-shi / social-cms-backend](https://github.com/dai-shi/social-cms-backend) - Express middleware to provide schema-less REST APIs for creating a social networking website primarily using angular.js. It comes with built-in authentication, authorization and notification features.

* [KeystoneJS](http://keystonejs.com/) - Node.js content management system and web application platform built on express and mongo. 
  
  * [[GitHub] JedWatson / keystone](https://github.com/JedWatson/keystone) - node.js cms and web app framework


#### Jogos

* [[GitHub] NetEase / pomelo](https://github.com/NetEase/pomelo) - A fast, scalable, distributed game server framework for Node.js

* [[GitHub] pablodenadai / GameOn](https://github.com/pablodenadai/GameOn) - responsive front-end webapp built on NodeJS and Angular

  * [GameOn](http://gameon.jit.su/) - connects you with the players in your city and allows you to find, organize and share games effortlessly.


### Site Estático

* [Boilerplate for static site generation | bdadam](http://bdadam.com/blog/static-site-generation-boilerplate.html) - boilerplate code for generating static websites with node.js, GruntJS and Assembe | [[GitHub] bdadam / static-site-boilerplate](https://github.com/bdadam/static-site-boilerplate)


* [[GitHub] segmentio / metalsmith](https://github.com/segmentio/metalsmith) - An extremely simple, pluggable static site generator.

  * [Wintersmith](http://wintersmith.io/) - flexible, minimalistic, multi-platform static site generator built on top of Node.js

  * [Wintersmith: Aprendendo outro gerador de conteúdo estático | Tableless](http://tableless.com.br/wintersmith-aprendendo-outro-gerador-de-conteudo-estatico/)

  * [Metalsmith Part 1: Setting Up the Forge | Robin Thrift](http://www.robinthrift.com/posts/metalsmith-part-1-setting-up-the-forge/)

  * [Wintersmith Creating Documentation | Composite Code](http://compositecode.com/2014/02/17/wintersmith-documentation/)

* [[GitHub] ktsashes / FruitJS](https://github.com/ktsashes/FruitJS) - A Node.js script for turning your markdown documentation into a fully functional site

  * [A Taste of FruitJS | Flippin' Awesome](http://flippinawesome.org/2013/09/16/a-taste-of-fruitjs/)


* [[GitHub] tommy351 / hexo](https://github.com/tommy351/hexo)

  * [Hexo - Node.js blog framework](http://hexo.io/) - A fast, simple & powerful blog framework, powered by Node.js


* [[GitHub] bevry / docpad](https://github.com/bevry/docpad)

  * [DocPad - Streamlined Web Development](http://docpad.org/) - build on top of node.js - Empower your website frontends with layouts, meta-data, pre-processors (markdown, jade, coffeescript, etc.), partials, skeletons, file watching, querying, and an amazing plugin system. Use it either standalone, as a build script, or even as a module in a bigger system. Either way, DocPad will streamline your web development process allowing you to craft full-featured websites quicker than ever before.

  * [Primeiros passos com o Docpad | Luiz Felipe Tartarotti Fialho](http://www.felipefialho.com/blog/2013/primeiros-passos-com-o-docpad/)


* [Techy](http://krasimir.github.io/techy/)

  * [Look Ma, no CMS! | David Walsh Blog](http://davidwalsh.name/techy)

  * [[GitHub] krasimir / techy](https://github.com/krasimir/techy/) - A flat file CMS based on Gulp and AbsurdJS

  * [Simple Content Management with Node.js and Markdown | Flippin' Awesome](http://flippinawesome.org/2014/05/05/simple-content-management-with-node-js-and-markdown/)


### Hardware

#### Node Copter

* [The NodeCopter](http://nodecopter.com/) - Programming flying robots with node.js


#### Lego Mindstorms

* [Hacking Lego Mindstorms EV3 with JavaScript](http://andrew.ghost.io/hacking-lego-mindstorms-ev3-with-javascript/)


#### Tessel

* [Tessel](http://technical.io/) - JavaScript right on the hardware 

* [Tessel - Dragon Innovation](http://www.dragoninnovation.com/projects/22-tessel) - Technical Machine - hardware module that speak javascript - totally amazing

* [[YouTube] Tessel Preview: Pushing code, servos, and UDP](https://www.youtube.com/watch?v=XCwKzipBIaA)

* [[SlideShare] Tessel: The End of Web Development (as we know it)](http://www.slideshare.net/TechnicalMachine/tessel-the-end-of-web-development-as-we-know-it)


#### Espruino

* [Espruino](http://www.espruino.com/) - A JavaScript interpreter for Microcontrollers

* [Espruino quer usar Javascript para controlar sua casa | Info](http://info.abril.com.br/noticias/blogs/zonalivre/hardware/espruino-quer-usar-javascript-para-controlar-sua-casa/)


#### Arduino

* [NodeBots](http://nodebots.io/) - The Rise of JS Robotics

* [[GitHub] ecto / duino](https://github.com/ecto/duino) - Arduino framework for node.js

* [Noduino](http://semu.github.io/noduino/) - Control Arduino with Node.js, WebSockets and HTML5

* [Arduino and NodeJS Communication With Serial Ports | Danial Khosravi's Blog](http://danialk.github.io/blog/2014/04/12/arduino-and-nodejs-communication-with-serial-ports/)


#### RaspberryPi

* [Build your own Google TV Using RaspberryPi, NodeJS and Socket.io | Donald's Blog](http://blog.donaldderek.com/2013/06/build-your-own-google-tv-using-raspberrypi-nodejs-and-socket-io/)

* [Home Automation with AngularJS and node.js on a Raspberry Pi | codecentric Blogcodecentric Blog](https://blog.codecentric.de/en/2013/03/home-automation-with-angularjs-and-node-js-on-a-raspberry-pi/)

* [heimcontrol.js](http://ni-c.github.io/heimcontrol.js/) - Awesome home automation with Raspberry PI and Arduino using Node.js, MongoDB, HTML5 and Websockets

* [[GitHub] googlecreativelab / coder](https://github.com/googlecreativelab/coder) - A simple way to make web stuff on Raspberry Pi

  * [Coder Projects](http://googlecreativelab.github.io/coder-projects/)

  * [Running Google Coder On Your Existing Raspberry Pi Or Desktop PC | Gadgetoid](http://pi.gadgetoid.com/article/running-google-coder-on-your-existing-raspberry-pi-or-desktop-pc)

  * [Coder: seu mini-servidor web pessoal | iMasters](http://imasters.com.br/gerencia-de-ti/tendencias/coder-seu-mini-servidor-web-pessoal/)


## Abstract Syntax Tree

* [Abstract Syntax Tree | wikipedia](https://en.wikipedia.org/wiki/Abstract_syntax_tree)

* [[GitHub] ajaxorg / treehugger](https://github.com/ajaxorg/treehugger) - JavaScript AST (Abstract Syntax Tree) transformation tools

* [[GitHub] ariya / esprima](https://github.com/ariya/esprima) - ECMAScript parsing infrastructure for multipurpose analysis | [esprima.org](http://esprima.org)

  * [Esprima Tutorial | Harmless Programmer](http://sevinf.github.io/blog/2012/09/29/esprima-tutorial/)

  * [Fun with Esprima and Static Analysis | Toby Ho](http://tobyho.com/2013/12/02/fun-with-esprima/)

  * [[GitHub] substack / node-falafel](https://github.com/substack/node-falafel) - transform the ast on a recursive walk

    * [Falafel, Source Rewriting, and a Magicial Assert | Toby Ho](http://tobyho.com/2013/12/20/falafel-source-rewriting-magicial-assert/)

      * [[GitHub] airportyh / falafel_fun](https://github.com/airportyh/falafel_fun) - Example programs using falafel for source code rewriting

  * [[GitHub] millermedeiros / rocambole](https://github.com/millermedeiros/rocambole) - Recursively walk and transform EcmaScript AST

  * [[GitHub] btford / eshighlight](https://github.com/btford/eshighlight) - highlight javascript code based on an esprima AST

* [[GitHub] Constellation / escodegen](https://github.com/Constellation/escodegen) - ECMAScript code generator

* [[GitHub] SBoudrias / AST-query](https://github.com/SBoudrias/AST-query) - Tentative to a simple JavaScript AST modification library

* [[GitHub] substack / node-burrito](https://github.com/substack/node-burrito) - Walk and transform the javascript AST with rice and beans on the side

* [[GitHub] benjamn / ast-types](https://github.com/benjamn/ast-types) - Esprima-compatible implementation of the Mozilla JS Parser API

* [[GitHub] dresende / node-ast-transformer](https://github.com/dresende/node-ast-transformer) - Node UglifyJS AST Transformer


## Dicas

* [10 Habits of a Happy Node Hacker | Heroku](https://blog.heroku.com/archives/2014/3/11/node-habits)

* [NodeCloud](http://www.nodecloud.org/) - Node.js resources directory 

* [Managing Node.js Virtual Environments with Nave](http://forge.zeunic.com/development/2013/managing-node-js-virtual-environments-with-nave)

* [[GitHub] keremc / nodevers](https://github.com/keremc/nodevers) - a Node.js version manager

* [[GitHub] flesler / config-node](https://github.com/flesler/config-node) - Flexible lightweight configuration loader for Node

--

* [Atualizando o NodeJS no Linux | Igor Costa](http://www.igorcosta.com/atualizando-o-nodejs-linux/)

--

* [Setting up a JavaScript / Node.js development environment](http://learnjs.io/blog/2014/01/22/js-development-environment/)

* [An Introduction To Full-Stack JavaScript | Smashing Coding](http://coding.smashingmagazine.com/2013/11/21/introduction-to-full-stack-javascript)

--

* [Node.js processando em paralelo | iMasters](http://imasters.com.br/desenvolvimento/node-js-processando-em-paralelo/) 

--

* [Creating a Single Page Todo App with Node and Angular | Scotch](http://scotch.io/tutorials/javascript/creating-a-single-page-todo-app-with-node-and-angular)

--

* [[GitHub] wilmoore / selectn](https://github.com/wilmoore/selectn) - Resolves deeply-nested object properties via dot or bracket-notation for Node.js and the browser

--

* [Real-time Engines in Node.js | StrongLoop](http://strongloop.com/strongblog/real-time-engines-in-node-js/)

--

* [Tracking down a memory leak in Node.js and Socket.IO](http://jpallen.net/2013/03/08/tracking-down-a-memory-leak-in-node-js-and-socket-io/)

* [Blazing fast node.js: 10 performance tips from LinkedIn Mobile](http://engineering.linkedin.com/nodejs/blazing-fast-nodejs-10-performance-tips-linkedin-mobile)

* [Tools and Strategies for node.js Development on GitHub | Chris Wren](http://chrisawren.com/posts/Tools-and-Strategies-for-node-js-Development-on-GitHub)

* [Scaling Node.js Applications](http://cjihrig.com/blog/scaling-node-js-applications/)

--

* [Testing Tuesday #20: Continuous Deployment for node.js applications | CodeShip Blog](http://blog.codeship.io/2013/08/27/testing-tuesday-20-continuous-deployment-for-node-js-applications.html)

* [Nodejs Deployment: Building and Configuring on Amazon Linux AMI | Asaf Shakarchi](http://asaf.github.io/blog/2013/07/10/nodejs-deployment-building-and-configuring-on-amazon-linux-ami/)

* [Continuous Deployment With Github](http://codesquire.com/post/ContinuousDeployment) - github + nodejs (+ gith) + VPS

* [[GitHub] danheberden / gith](https://github.com/danheberden/gith) - simple node server that responds to github post-receive events with meaningful data

--

* [[GitHub] yyx990803 / pod](https://github.com/yyx990803/pod) - Git push deploy for Node.js

--

* [[GitHub] mikefrey / node-pac](https://github.com/mikefrey/node-pac) - pack your node_modules as *.tgz files for version control and easy deploys (not tested on Windows yeat)

  * [Deploying Node.js apps without npm using pac | Coding in the Crease](http://www.codinginthecrease.com/news_article/show/307636)

--

* [Injeção de dependência com Node.js | iMasters](http://imasters.com.br/front-end/javascript/injecao-de-dependencia-com-node-js/)

* [How AngularJS (DI) Made Me a Better Node.js Developer | Liam Kaufman](http://liamkaufman.com/blog/2013/08/06/how-angularjs-made-me-a-better-nodejs-developer/)

* [Dependency Injection in Node.JS | Tech @ i.TV](http://tech.i.tv/09-17-2013/dependency-injection-in-nodejs/)

--

* [Install node.js on a raspberry pi](http://halusanation.com/post/49221746344/install-node-js-on-a-raspberry-pi)

--

* [[GitHub] c9 / architect](https://github.com/c9/architect) - A simple yet powerful plugin system for large-scale node applications

* [[GitHub] fth-ship / code-problems](https://github.com/fth-ship/code-problems) - Common code problems solved using JavaScript - add your own problems and solutions!

--

* [[GitHub] coreybutler / node-windows](https://github.com/coreybutler/node-windows) - Windows support for Node.JS scripts (daemons, eventlog, UAC, etc)

--

* [[GitHub] LearnBoost / kue](https://github.com/learnboost/kue) - Kue is a priority job queue backed by redis, built for node.js.

* [[GitHub] eviltik / evilscan](https://github.com/eviltik/evilscan) - Massive ip/ports scanner (nodejs)

* [[GitHub] caio-ribeiro-pereira / gzipme](https://github.com/caio-ribeiro-pereira/gzipme) - A simple way to gzip your files with Node.js

* [[GitHub] ctalkington / node-archiver](https://github.com/ctalkington/node-archiver) - Creates Archives (Zip, Tar) via Node Streams

* [[GitHub] netroy / image-size](https://github.com/netroy/image-size) - NodeJS module for detecting image dimensions

* [Loading PDFs In PhantomJS Using PDF.JS | Gary Sieling](http://www.garysieling.com/blog/integrating-phantomjs-and-pdf-js-inter-process-communication)

--

* [Practical Examples of the New Node.js Streams API | StrongLoop](http://blog.strongloop.com/practical-examples-of-the-new-node-js-streams-api/)

* [How to create transform streams for manipulating data with Node.js | CodeWinds](http://codewinds.com/blog/2013-08-20-nodejs-transform-streams.html) - a programming tutorial for web developers

* [[GitHub] substack / stream-handbook](https://github.com/substack/stream-handbook) - how to write node programs with streams

* [[GitHub] caolan / highland](https://github.com/caolan/highland) - The high-level streams library for Node.js and the browser

* [[GitHub] maxogden / eol-stream](https://github.com/maxogden/eol-stream) - detect which type of EOL (AKA line-ending, newline) characters are in a stream

* [[GitHub] Obvious / sculpt](https://github.com/Obvious/sculpt) - Manipulate streams

--

* [NodeJS - parsing and transforming large XML documents | La Gentz Blog](http://blog.lagentz.com/nodejs/nodejs-parsing-and-transforming-large-xml-documents/)

* [Parse data files using Node.js streams | Nicolas Hery](http://nicolashery.com/parse-data-files-using-nodejs-streams/)

* [Parsing CSV Files With NodeJS | James Carr](http://blog.james-carr.org/2010/07/07/parsing-csv-files-with-nodejs/)

* [[GitHub] mgcrea / node-xlsx](https://github.com/mgcrea/node-xlsx) - Node.js excel parser & builder 

* [[GitHub] jlord / sheetdown](https://github.com/jlord/sheetdown) - Convert a Google Spreadsheet into a table in Markdown

  * [Introducing Sheetdown | Source](https://source.opennews.org/en-US/articles/introducing-sheetdown/)

--

* [[GitHub] Sendanor / nor-fs](https://github.com/Sendanor/nor-fs) - chainable asynchronous file system library for Node.js

* [[GitHub] vesln / fine](https://github.com/vesln/fine) - Tiny, recursive and synchronous file finder utility

--

* [[GitHub] vesln / hippie](https://github.com/vesln/hippie) - End-to-end API testing made easy

--

* [How to Create a Resumable Video Uploader in Node.js | Nettuts+](http://net.tutsplus.com/tutorials/javascript-ajax/how-to-create-a-resumable-video-uploade-in-node-js/)

* [Super simple file upload with node.js | Tanya Nam](http://tanyanam.com/everything/super-simple-file-upload-with-node-js)

* [node.js HTML5 file uploader | DavidPirek](http://www.davidpirek.com/blog/nodejs-html5-file-uploader)

* [Node.js: upload de arquivos | Kaique Silva on Svbtle](http://sigmundxox.svbtle.com/nodejs-upload-de-arquivos)

--

* [Installing and Running node.js applications within IIS on Windows - Are you mad? | Scott Hanselman](http://www.hanselman.com/blog/InstallingAndRunningNodejsApplicationsWithinIISOnWindowsAreYouMad.aspx)

* [Nginx servindo Node.js | Underground WebDev](http://udgwebdev.com/nginx-servindo-nodejs)

--

* [Instalando Cloud9 local com suporte a RunJS no Linux | GARTZ](http://gartz.com.br/instalando-cloud9-local-com-suporte-a-runjs-no-linux/)

--

* [Building Multiplayer Games with Node.js and Socket.IO | Flippin' Awesome](http://flippinawesome.org/2013/09/30/building-multiplayer-games-with-node-js-and-socket-io/)

--

* [[GitHub] bekk / retire.js](https://github.com/bekk/retire.js) - scanner detecting the use of JavaScript libraries with known vulnerabilites

--

* [Jade](http://jade-lang.com/) - node template engine

  * [Using Node.js for Static Sites: Jade | StrongLoop](http://strongloop.com/strongblog/using-node-js-for-static-sites-jade/)

  * [Jade Syntax Documentation by example](http://naltatis.github.io/jade-syntax-docs/)


### portable code

* [[Gist] Tips for Writing Portable Node.js Code](https://gist.github.com/domenic/2790533)

* [Windows and Node: Writing Portable Code | DailyJS](http://dailyjs.com/2012/05/24/windows-and-node-4/)

* [How to Write Portable Node.js Code | Node on Azure](http://nodeblog.azurewebsites.net/how-to-write-portable-nodejs-code)

* [Writing cross-platform Node.js | Shape Shed](http://shapeshed.com/writing-cross-platform-node/) - a major strength of Node.js is great cross-platform support. With a little effort you can make sure your code will run on Windows, Linux and OSX.


### fake data

* [[GitHub] Marak / Faker.js](https://github.com/marak/Faker.js) - Generate fake data in the browser and Node.js with FakerJS

* [Testing Private State and Mocking Dependencies | How To Node - NodeJS](http://howtonode.org/testing-private-state-and-mocking-deps)

* [[GitHub] boo1ean / casual](https://github.com/boo1ean/casual) - Fake data generator for javascript

* [[GitHub] infrared5 / madmin](https://github.com/infrared5/madmin) - admin console for generating mock services with RESTful URIs

* [[GitHub] bustardcelly / caddis](https://github.com/bustardcelly/caddis) - On-The-Fly Mock JSON Server

* [[GitHub] basicallydan / interfake](https://github.com/basicallydan/interfake) - Quickly create fake APIs for use in client-only tests or prototypes


### command and shell

* [Node.js as a build script | Blog - Miller Medeiros](http://blog.millermedeiros.com/node-js-as-a-build-script/)

* [Write your shell scripts in JavaScript, via Node.js | 2 ality](http://www.2ality.com/2011/12/nodejs-shell-scripting.html)

* [[GitHub] arturadib / shelljs](https://github.com/arturadib/shelljs) - Portable Unix shell commands for Node.js

* [[GitHub] typicode / shoutjs](https://github.com/typicode/shoutjs) - Make your ShellJS commands explicit and get a beautiful output

--

* [[GitHub] Cron for NodeJS](https://github.com/ncb000gt/node-cron)

* [[GitHub] shell-jobs: Cron replacement in NodeJS, made for humans](https://github.com/azer/shell-jobs)

* [How to Write a Command Line Application in Node.js | Liang Zan](http://blog.liangzan.net/blog/2012/07/30/how-to-write-a-command-line-application-in-node-dot-js/)

* [[GitHub] stephanepericat / cmdl](https://github.com/stephanepericat/cmdl) - A simple, yet powerful command-line interface builder

* [Build Custom Shells with Node Shotgun | Code Tunnel](http://codetunnel.com/blog/post/build-custom-shells-with-node-shotgun)

* [[GitHub] pstadler / flightplan](https://github.com/pstadler/flightplan) - Node.js library for streamlining application deployment or systems administration tasks.


### process manager

* [Topic: Automatically restart your node.js server after code updates | StrongLoop](http://strongloop.com/node-republic-topics/automatically-restart-your-node-js-server-after-code-updates/)

* [Comparison: Tools to Automate Restarting Node.js Server After Code Changes | StrongLoop](http://strongloop.com/strongblog/comparison-tools-to-automate-restarting-node-js-server-after-code-changes-forever-nodemon-nodesupervisor-nodedev/)

* [[GitHub] mafintosh / respawn](https://github.com/mafintosh/respawn) - Spawn a process and restart it if it crashes

* [[GitHub] oOthkOo / supervizer](https://github.com/oOthkOo/supervizer) - NodeJS fancy process manager

* [[GitHub] Unitech / pm2](https://github.com/Unitech/pm2) - CLI process manager for Node.js with native clusterization

  * [PM2 – mantendo o node.js no ar | iMasters](http://imasters.com.br/front-end/javascript/pm2-mantendo-o-node-js-no-ar/)


### Produção

* [Production Node.js Secrets](http://dshaw.github.com/2012-05-jsday/)

* [Running Node.js apps in production | Frederic Hemberger](http://fhemberger.github.io/talks/nodejs-in-production/)

  * [Resources: Running Node.js apps in production](https://github.com/fhemberger/talks/tree/master/nodejs-in-production)

* Hardening Node.js for production [part 1](http://blog.argteam.com/coding/hardening-nodejs-production-process-supervisor/) | [part 2](http://blog.argteam.com/coding/hardening-node-js-for-production-part-2-using-nginx-to-avoid-node-js-load/) | [part 3](http://blog.argteam.com/coding/hardening-node-js-for-production-part-3-zero-downtime-deployments-with-nginx/)

* [Check out our new nodejs dev & production practices library for details on designing, deploying & debugging Node.js | Joyent](https://www.joyent.com/developers/node)

* [Como configurar um servidor node.js para produção | morethings.io](http://morethings.io/javascript/node/como-configurar-um-servidor-nodejs-para-producao/)

* [Scaling Node.js Applications | Colin J. Ihrig's Blog](http://cjihrig.com/blog/scaling-node-js-applications/)


### REST

* [Full HTTPS REST server in Node.js | Bogomil Shopov](http://talkweb.eu/full-https-rest-server-in-node-js/)

* [[GitHub] imrefazekas / connect-rest](https://github.com/imrefazekas/connect-rest) - Exceptionally featureful Restful web services middleware for connect node.js

* [[GitHub] mcavage / node-restify](https://github.com/mcavage/node-restify) - node.js REST framework specifically meant for web service APIs

  * [Day 27: Restify - Build Correct REST Web Services in Node.js | OpenShift by Red Hat](https://www.openshift.com/blogs/day-27-restify-build-correct-rest-web-services-in-nodejs)

* [[GitHub] Mashape / unirest-nodejs](https://github.com/mashape/unirest-nodejs) - Node.js Unirest library built on-top of request and modeled after superagent.


### Authentication

* [Express.js Basic Authentication with Encryption | Nodewiz.biz](http://www.nodewiz.biz/expressjs-basic-authentication/)

* [Easy Node Authentication: Setup and Local | Scotch](http://scotch.io/tutorials/javascript/easy-node-authentication-setup-and-local)

* [[Slid.es] https & authentication in node.js](http://slid.es/jeroenmoors/https-authentication-in-nodejs) - by Jeroen Moors

  * [[GitHub] jeroenmoors / nodettps](https://github.com/jeroenmoors/nodettps) - https experiments with node.js

* [[GitHub] tgies / client-certificate-auth](https://github.com/tgies/client-certificate-auth) - middleware for Node.js implementing client SSL certificate authentication/authorization

* [[GitHub] kenshiro-o / login-utils](https://github.com/kenshiro-o/login-utils) - Simple authentication library

* [[GitHub] dilvie / credential](https://github.com/dilvie/credential) - Easy password hashing and verification in Node. Protects against brute force, rainbow tables, and timing attacks.

* [[GitHub] Mashape / guardian](ape/guardian) - Authentication Proxy Server, instead of dealing with providers now you can authenticate against any service with a simple json data-structure and plugin architecture.


#### WebID

* [WebID - Universal Login and Identity for the Web](http://webid.info/)

  * [WebID - Universal Login for the Web | Digital Bazaar](http://digitalbazaar.com/2010/08/07/webid/)

--

* [[GitHub] magnetik / node-webid-demo](https://github.com/magnetik/node-webid-demo)

  * [Node WebId Report](http://magnetik.github.io/node-webid-report/)



### Módulo

* [How to Make Simple Node.js Modules Work in the Browser | Richard Rodger](http://www.richardrodger.com/2013/09/27/how-to-make-simple-node-js-modules-work-in-the-browser/)

* [How to create a NodeJS NPM package | Anup Shinde](http://www.anupshinde.com/posts/how-to-create-nodejs-npm-package/) - See how to create a simple NodeJS NPM package. We'll first create a simple program, add some node_modules  to it and walk through the process of creating a NPM package, publishing it and upgrading it. We'll also walk through see some common issues that you might face for the first time.

* [Adding dependencies and data to Node-NPM package | Anup Shinde](http://www.anupshinde.com/posts/adding-dependencies-data-nodejs-npm-package/) - In the first part we created a package with no dependencies. In this part, we'll add some dependencies to our program and package. We'll also look at some additional tips that you may require when creating your first NPM package.

* [NPM Node Package Manager | Underground WebDev](http://udgwebdev.com/npm-node-package-manager/)

* [[Vimeo] Eric Elliott - Modular JavaScript With npm and Node Modules](http://vimeo.com/89258863) - An introductory look at programming with Node style modules


### url rewrite proxy

* [[GitHub] tinganho / connect-modrewrite](https://github.com/tinganho/connect-modrewrite) - Adds modrewrite functionality to your connect/express server

* [[GitHub] viart / grunt-connect-rewrite](https://github.com/viart/grunt-connect-rewrite) - Provides RewriteRules middleware for the grunt connect / express.

* [[GitHub] drewzboto / grunt-connect-proxy](https://github.com/drewzboto/grunt-connect-proxy) - Provides a http proxy as middleware for the grunt-contrib-connect plugin. With rewrite options.



### NPM

* [Meet The Face Behind NPM | Modulus Blog](http://blog.modulus.io/isaac-interview)

--

* [Keeping The npm Registry Awesome | Nodejs Blog](http://blog.nodejs.org/2013/11/26/npm-post-mortem/) - 26/11/2013

--

* [npmjs.eu - European npm mirror](http://npmjs.eu/)

  * [Using the European npm mirror | Shape Shed](http://shapeshed.com/using-the-european-npm-mirror/)

* [How to create a private npm.js repository | Clock Blog](http://clock.co.uk/tech-blogs/how-to-create-a-private-npmjs-repository)

* [A private NPM cache | Yammer Engineering](http://eng.yammer.com/a-private-npm-cache/)

* [[GitHub] mixu / npm_lazy](https://github.com/mixu/npm_lazy) - A lazy local cache for NPM to make your local deploys faster

--

* [[GitHub] deoxxa / npmrc](https://github.com/deoxxa/npmrc) - Switch between different .npmrc files with ease and grace.

* [[GitHub] floatdrop / chnpm](https://github.com/floatdrop/chnpm) - npm configuration switcher

--

* [Relato](http://bripkens.github.io/relato/) - NPM Project Statistics

* [npm Visualization | YASIV](http://www.yasiv.com/npm) | Sample: [Grunt npm dep](http://www.yasiv.com/npm#view/grunt)

* [NodeZoo](http://nodezoo.com/) - A search engine for reliable Node.js modules

* [The Node Toolbox - Node.js happiness](http://nodetoolbox.com/) - is a catalogue of Node.js packages, tools and resources with popularity ratings based on Github watchers and forks

* [Node Modules](http://node-modules.com/) - Better search for Node.js modules

* [David, a dependency management tool for Node.js projects](https://david-dm.org)

--

* [npm cheatsheet | Nodejitsu](https://blog.nodejitsu.com/npm-cheatsheet)

* [[Gist] AvnerCohen / npm-cheat-sheet.md](https://gist.github.com/AvnerCohen/4051934) - Node.js - npm Cheat Sheet

--

* [10 Cool Things You Probably Didn't Realize npm Could Do](http://blog.izs.me/post/1675072029/10-cool-things-you-probably-didnt-realize-npm-could-do)

* [9 Quick Tips About npm | Pony Foo](http://blog.ponyfoo.com/2013/12/14/9-quick-tips-about-npm)

* [NPM tricks | Devthought](http://www.devthought.com/2012/02/17/npm-tricks/)

* [Npm Tips | fiveisprime](http://fiveisprime.com/2014/04/06/npm-tips/)

--

* [Introduction to npm | SmallJS](http://smalljs.org/package-managers/npm/)

* [Tour of npm | toby ho](http://tobyho.com/2012/02/09/tour-of-npm/)

* [How to Build a Node npm Package From Scratch | Decodize](http://decodize.com/javascript/build-nodejs-npm-installation-package-scratch/)

--

* [Creating and publishing a node.js module | Quick Left Boulder Colorado](http://quickleft.com/blog/creating-and-publishing-a-node-js-module)

* [Publishing a simple package to npm | Evan Hahn](http://evanhahn.com/make-an-npm-baby/)

--

* [task automation with npm run | unix philosopher. beep boop.](http://substack.net/task_automation_with_npm_run)

  * [[Gist] using `npm run` to build and watch with less and browserify](https://gist.github.com/substack/7819530)

* [Running Scripts with npm | The Tapir's Tale](http://anders.janmyr.com/2014/03/running-scripts-with-npm.html)

--

* [Stay up-to-date with Node.js packages using npm-onupdate service | Piotr Walczyszyn's Blog](http://outof.me/stay-up-to-date-with-node-js-packages-using-npm-onupdate-service/)


### CORS

* [[GitHub] natlownes / headrest](https://github.com/natlownes/headrest) - A RESTful, CORS enabled webserver intended for use when developing single page Javascript applications

* [[GitHub] agrueneberg / Corser](https://github.com/agrueneberg/Corser) - A highly configurable, middleware compatible implementation of CORS for Node.js.


### Armazenamento

* [Node.js and SQLite | Modulus Blog](http://blog.modulus.io/nodejs-and-sqlite) - Great introduction to using SQLite with Node.js. Covers everything from installing to running queries against the database.

* [[GitHub] WebReflection / dblite](https://github.com/WebReflection/dblite) - sqlite for node.js without gyp problems

--

* [[GitHub] louischatriot / nedb](https://github.com/louischatriot/nedb) - Embedded datastore for node.js

  * [NeDB: SQLite for Node | DailyJS](http://dailyjs.com/2013/08/01/nedb/)

* [TingoDB](http://www.tingodb.com/) - Embedded JavaScript database for Node.js and node webkit

--

* [[GitHub] phidelta / abstract-store](https://github.com/phidelta/abstract-store) - a node-module to abstract key/value storage away from the underlying technology

--

* [Node.js and MongoDB | Modulus Blog](http://blog.modulus.io/getting-started-with-mongoose) - Getting Started with Mongoose

* [Intro to MongoDB on Node.js | OpenShift by Red Hat](https://www.openshift.com/blogs/intro-to-mongodb-on-nodejs)

* [Nodejs e MongoDB - Introdução ao Mongoose | NodeBR - NodeJS Brasil](view-source:http://nodebr.com/nodejs-e-mongodb-introducao-ao-mongoose/)

* [Um pouco de Node.js e MongoDB na prática | Underground WebDev](http://udgwebdev.com/um-pouco-de-node-js-e-mongodb-na-pratica) 

* [Mongoose Connection best practice | The Holmes Office](http://theholmesoffice.com/mongoose-connection-best-practice/)

--

* [[GitHub] maritz / nohm](https://github.com/maritz/nohm) - node.js implementation of a redis object relations mapper (orm). High speed queries with this ODM for Redis

--

* [[GitHub] BagosGiAr / modQuery](https://github.com/BagosGiAr/modQuery) - A module to use for MySQL queries with respect to SQL.

--

* [[GitHub] philipp-spiess / json-db](https://github.com/philipp-spiess/json-db) - A lightweight database for your node.js app.

* [[GitHub] techfort / LokiJS](https://github.com/techfort/LokiJS) - javascript embedded / in-memory database

  * [LokiJS](http://lokijs.org/) - A lightweight javascript document oriented database

* [PouchDB](http://pouchdb.com/) - the JavaScript Database that Syncs! PouchDB is an Open Source JavaScript Database inspired by Apache CouchDB that is designed to run well within the browser.

--

* CouchDB

  * [Node.js CouchDB Tutorial: Using Nano, Express Modules, Examples, CRUD Operations | TutorialIndustry.com](http://www.tutorialindustry.com/node-js-couchdb-tutorial-for-beginners)

  * [A Simple Blog with CouchDB, Bogart, and Node.js | How To Node](http://howtonode.org/bogart-couchdb)

  * [Thoughts on development using CouchDB with Node.js | Tim Branyen](http://tbranyen.com/post/thoughts-on-development-using-couchdb-with-nodejs)

  * [[GitHub] chris-l / mock-couch](https://github.com/chris-l/mock-couch) - A node.js module designed to mock a couchdb database, mostly for unit testing purposes

--

* [LevelDB and Node.js Sitting in a Tree](http://r.va.gg/presentations/node.ninjas)

--

* [[GitHub] mcavage / node-ldapjs](https://github.com/mcavage/node-ldapjs) - LDAP Client and Server API for node.js


### Virtualização

#### Docker

* [[Vimeo] Node.JS and Docker with a side of Continuous Deployment](http://vimeo.com/85864661) - Presented by Niall O'Higgins at JSLA (js.la) on Thursday January 30th 2014. Docker is an incredible new tool to manage the deployment and lifecycle of Node.JS network services. This talk will cover using them together for much Continuous Deployment win.

--

* [How to create a Docker + Node.js + MongoDB + Varnish environment | Luis Elizondo](http://luiselizondo.net/blogs/luis-elizondo/how-create-docker-nodejs-mongodb-varnish-environment)

* [Getting Started with Docker for the Node.js | CouchDB Programmer - Medium](https://medium.com/code-adventures/35c45ce2a814)

--

* [[GitHub] adamalex / docker-urlarchiver](https://github.com/adamalex/docker-urlarchiver) - Use Docker to package a Node.js script with all its dependencies, including Node

* [[GitHub] apocas / dockerode](https://github.com/apocas/dockerode) - Not just another Docker.io Remote API node.js module


### Nuvem

* [Onde hospedar aplicações Node.js | Underground WebDev](http://udgwebdev.com/onde-hospedar-aplicacoes-node-js/)


#### Pessoal

* [BipIO](https://bip.io/) - gives you the power to rapidly create workflows with the cloud components you already love, no programming required.

  * [[GitHub] bipio-server / bipio](https://github.com/bipio-server/bipio) - The BipIO API Server


* [Cozy](http://cozy.io/) - a personal Cloud you can host, hack and delete Your web apps and your data on your hardware

  * [[GitHub] mycozycloud / cozy-setup](https://github.com/mycozycloud/cozy-setup)

  * [Turn the server into the new personal device with Node.js, Cozy and CouchDB | Cozy.io](http://blog.cozycloud.cc/technic/2014/04/02/cozy-and-couchdb/)


#### Amazon AWS

* [Configurando o Node.js no Amazon EC2](http://pablocantero.com/blog/2012/01/04/configurando-o-node-js-no-amazon-ec2/)

* [Surviving AWS Failures with a Node.js and MongoDB Stack | Kinvey Backend as a Service Blog](http://www.kinvey.com/blog/104/surviving-aws-failures-with-a-nodejs-and-mongodb-stack)

* [Amazon Web Services Blog: AWS Elastic Beanstalk for Node.js](http://aws.typepad.com/aws/2013/03/aws-elastic-beanstalk-for-nodejs.html)

* [Node.js powered by BitNami](https://aws.amazon.com/marketplace/pp/B008ASK0ZE)

* [BitNami Node.js](http://bitnami.com/stack/nodejs)

* [How to install & setup Node.js on Amazon EC2 instance - complete guide](http://iconof.com/blog/how-to-install-setup-node-js-on-amazon-aws-ec2-complete-guide/)

* [Examples — AWS SDK for Node.js - Documentation](http://docs.aws.amazon.com/AWSJavaScriptSDK/guide/examples.html)

* [awsbox, a PaaS layer for Node.js: An Update on Latest Developments | Mozilla Hacks](https://hacks.mozilla.org/2013/10/awsbox-a-paas-layer-for-node-js-an-update-on-latest-developments/)
  
  * [[GitHub] mozilla / awsbox](https://github.com/mozilla/awsbox)


##### Amazon S3

* [NodeJS Deploying Files to AWS S3](http://blog.katworksgames.com/2014/01/26/nodejs-deploying-files-to-aws-s3/)

* [Upload Static Files in AWS S3 with Node.js and Grunt.js | Toontuts](http://www.toontuts.com/upload-static-files-in-aws-s3-with-node-js-and-grunt-js/)

* [[GitHub] giuliandrimba / s3-pusher](https://github.com/giuliandrimba/s3-pusher) - Publish assets to Amazon's S3 service via CLI


#### Windows Azure

* [[Blog] Node on Azure](http://nodeblog.azurewebsites.net/)

* [Node.js on Windows Azure](http://www.windowsazure.com/en-us/develop/nodejs/) - Get the tools, documentation, sample code and other resources you need to build powerful Node.js applications on Windows Azure.

* [How to Use the Blob Service from Node.js](http://www.windowsazure.com/en-us/documentation/articles/storage-nodejs-how-to-use-blob-storage/)


### Mobile

#### iOS

* [Node.app](http://nodeapp.org/) - Node.js for iOS


### Desktop

* [Build Desktop Application Using Node.js | Shift8Creative](http://www.shift8creative.com/posts/view/build-desktop-application-using-node-js) - A Quickstart using AppJs

* [[GitHub] appjs / appjs](https://github.com/appjs/appjs) - SDK on top of nodejs to build desktop apps using HTML5/CSS/JS

* [[GitHub] arturadib / node-qt](https://github.com/arturadib/node-qt) - Qt bindings for Node.js

* [[GitHub] hij1nx / node-chrome](https://github.com/hij1nx/node-chrome) - Node.js + Chrome = Networked Desktop Apps. Simple.


#### Node Webkit

* [[GitHub] rogerwang / node-webkit](https://github.com/rogerwang/node-webkit) - Call all Node.js modules directly from DOM and enable a new way of writing applications with all Web technologies.

* [[Speaker Deck] node-webkit: app runtime based on Chromium and node.js](https://speakerdeck.com/zcbenz/node-webkit-app-runtime-based-on-chromium-and-node-dot-js)

* [Creating Desktop Applications With node-webkit | StrongLoop](http://strongloop.com/strongblog/creating-desktop-applications-with-node-webkit/)

* [Introduction to HTML5 Desktop Apps With Node-Webkit | Nettuts+](http://net.tutsplus.com/tutorials/javascript-ajax/introduction-to-html5-desktop-apps-with-node-webkit/)


##### node-webkit: exemplos

* [[GitHub] Anonyfox / node-webkit-hipster-seed](https://github.com/Anonyfox/node-webkit-hipster-seed) - Bootstrap a crossplatform Desktop Application using tools you probably never heard of

* [[GitHub] zcbenz / nw-sample-apps](https://github.com/zcbenz/nw-sample-apps) - Sample apps for node-webkit


##### node-webkit: Aplicações e Empresas que utilizam

* [List of apps and companies using node webkit | rogerwang / node-webkit - GitHub Wiki](https://github.com/rogerwang/node-webkit/wiki/List-of-apps-and-companies-using-node-webkit)

--

* [[GitHub] wookiecooking / nwfaketop](https://github.com/wookiecooking/nwfaketop) - A GruntJS Compiler for Node-webkit Applications (OSX Based)

* [[GitHub] slate / slate](https://github.com/slate/slate) - modern IRC client built with web technologies and Node.js

* [[GitHub] FWeinb / screenshot-service](https://github.com/FWeinb/screenshot-service) - A simple screenshot web service powered by Express and node-webkit.

* popcorn time

  * [[twitter] popcorntimetv](https://twitter.com/popcorntimetv) - infos

  * [[GitHub] popcorn-official / popcorn-app](https://github.com/popcorn-official/popcorn-app) - An experiment using the peerflix module of nodejs and connecting a bunch of APIs. 


### Modulos e Frameworks

* [A collection of web frameworks for Node.js | Node Web Modules](http://nodewebmodules.com/)

* [Node.js Frameworks](http://nodeframework.com/) - Hand-picked registry of Node.js frameworks

--

* [Bone.io](http://bone.io/) is a lightweight framework for building high performance Realtime Single Page HTML5 Apps

--

* [Geddy](http://geddyjs.org/) - A simple, structured web framework for Node

  * [In the Loop: Geddy – a Simple Node.js Web Framework | StrongLoop](http://blog.strongloop.com/in-the-loop-geddy/)

* [total.js](http://www.totaljs.com/) - a Web framework for Node.js

--

* [[GitHub] timjansen / hanson](https://github.com/timjansen/hanson) - HanSON - JSON for Humans, with multi-line strings and comments

* [[GitHub] jprichardson / jsock](https://github.com/jprichardson/jsock) - JavaScript component for easy JSON handling over sockets or streams. Works in Node.js or the browser.

--

* [[GitHub] martinandert / counterpart](https://github.com/martinandert/counterpart) - A translation and localization library for Node.js and the browser.


* [Sails.js](http://www.sailsjs.org/) - Realtime MVC Framework for Node.js

  * [sailsCasts](http://irlnathan.github.io/sailscasts/) - Learning about sails.js one screencast at a time

* [Nombo](http://nombo.io/) - Node.js Realtime App Framework 


#### Socket.io

* [Socket.IO](http://socket.io/) - aims to make realtime apps possible in every browser and mobile device, blurring the differences between the different transport mechanisms. It's care-free realtime 100% in JavaScript.

* [[GitHub] LearnBoost / socket.io](https://github.com/learnboost/socket.io) - Realtime application framework for Node.JS, with HTML5 WebSockets and cross-browser fallbacks support

* [Getting Started With Socket.io | TysonJS](http://tysoncadenhead.com/blog/getting-started-with-socket-io)

* [[GitHub] LearnBoost / engine.io](https://github.com/learnboost/engine.io) - is the implementation of transport-based cross-browser/cross-device bi-directional communication layer for Socket.IO.

  * [The Realtime Engine | Devthought](http://www.devthought.com/2012/07/07/the-realtime-engine/)
  * [Node.js para leigos - Explorando real-time | Underground WebDev](http://udgwebdev.com/node-js-para-leigos-explorando-real-time/)
  * [Real-time com Socket.IO no Node.js | Underground WebDev](http://udgwebdev.com/real-time-com-socket-io-no-nodejs/)
  * [Express, Socket.IO e Sessions | Underground WebDev](http://udgwebdev.com/nodejs-express-socketio-e-sessions/)

* [Token-based Authentication with Socket.IO | Auth0](http://blog.auth0.com/2014/01/15/auth-with-socket-io/)


#### Connect

* [Connect](http://www.senchalabs.org/connect/) - High quality middleware for node.js

* [A short guide to Connect Middleware](http://stephensugden.com/middleware_guide/)


#### Express.js

* [Express.js](http://expressjs.com/)

* [[GitHub] likeastore / maintenance](https://github.com/likeastore/maintenance) - middleware for easy switching the app to maintenance mode

* [Kraken.js](http://krakenjs.com/) - The kraken suite is a secure and scalable layer that extends express by providing structure and convention

* [DozerJS](http://dozerjs.com/) - is a system for rapidly developing services to support front-end applications

  * [Simple Todo List App with DozerJS | fluidbyte](http://www.fluidbyte.net/simple-todo-list-app-with-dozerjs/)

* [ExpressWorks | webapplog](http://webapplog.com/expressworks/) - is an automated Express.js/Node.js workshop

* [Express.js Fundamentals | Flippin' Awesome](http://flippinawesome.org/2013/11/11/express-js-fundamentals/)

* [Node.js com Express.js nos negócios | iMasters](http://imasters.com.br/front-end/javascript/node-js-com-express-js-nos-negocios/)

* [Build a Complete MVC Website With ExpressJS | Nettuts+](http://net.tutsplus.com/tutorials/javascript-ajax/build-a-complete-mvc-web-site-with-expressjs/)

* [Super simple file upload with node.js | Tanya Nam](http://tanyanam.com/everything/super-simple-file-upload-with-node-js)

* [Building a simple blog with NodeJS and Express | KOPIS.DE](http://blog.kopis.de/2012/01/30/building-a-simple-blog-with-nodejs-and-express/) | [[GitHub] MoriTanosuke / blode](https://github.com/MoriTanosuke/blode) - Simple blog framework with NodeJS (post write in markdown)

* [ExpressJS and MySQL Sample Application and Tutorial | gist.pages](http://gistpages.com/2013/11/1/expressjs_and_mysql_sample_application_and_tutorial)

* [Using the Directory-serving middleware in Express | Raymond Camden](http://www.raymondcamden.com/index.cfm/2013/8/11/Using-the-Directoryserving-middleware-in-Express)

* [Using Express.js for APIs | StrongLoop](http://blog.strongloop.com/using-express-js-for-apis)

* [Node.js para leigos - Framework Express parte 1 | Underground WebDev](http://udgwebdev.com/node-js-para-leigos-framework-express-parte-1/) 

* [Node.js para leigos - Framework Express parte 2 | Underground WebDev](http://udgwebdev.com/node-js-para-leigos-framework-express-parte-2/)  

* [Todo App with Express.js/Node.js and MongoDB | webapplog](http://webapplog.com/todo-app-with-express-jsnode-js-and-mongodb/)

* [Passport.js](http://passportjs.org/) - Simple, unobtrusive authentication for Node.js.

  * [Getting Started with Passport | node.js knockout](http://blog.nodeknockout.com/post/66118192565/getting-started-with-passport)

--

* [[GitHub] felixge / node-formidable](https://github.com/felixge/node-formidable) - A node.js module for parsing form data, especially file uploads

  * [[GitHub] devcollectief / express-upload](https://github.com/devcollectief/express-upload) - Streaming multiple large files to AWS S3 with Multipart API, Formidable & Jquery File Upload


#### Meteor

* [meteor](http://www.meteor.com/)

* [Introdução sobre Meteor | Underground WebDev](http://udgwebdev.com/introducao-sobre-meteor/)

* [Primeiros passos com Meteor | Underground WebDev](http://udgwebdev.com/primeiros-passos-com-meteor)

* [Organizando um projeto Meteor | Underground WebDev](http://udgwebdev.com/organizando-um-projeto-meteor)

* [Quer aprender Meteor? | Underground WebDev](http://udgwebdev.com/quer-aprender-meteor)


### Ferramentas

#### Visual Studio

* [Node.js for Visual Studio | CodePlex](https://nodejstools.codeplex.com/)

* [Introducing node.js Tools for Visual Studio | Scott Hanselman](http://www.hanselman.com/blog/IntroducingNodejsToolsForVisualStudio.aspx)

* [Node.js support in Visual Studio? You bet your IDE | StrongLoop](http://strongloop.com/strongblog/node-js-support-in-visual-studio-you-bet-your-ide/)

* [Dive into Node.js development with this Visual Studio plugin | TechRepublic](http://www.techrepublic.com/article/dive-into-node-js-development-with-this-visual-studio-plugin/)

* [Stand-up: Developing a node.js application using Monaco (Part 1) | Visual Studio Online "Monaco"](http://blogs.msdn.com/b/monaco/archive/2014/03/27/stand-up-developing-a-node-js-application-using-monaco-part-1.aspx)


#### Eclipse IDE

* [Nodelipse](http://www.nodeclipse.org/) | [Sourceforge](http://sourceforge.net/projects/nodeclipse/)

#### JetBrains

* [IntelliJ IDEA :: Node.js](http://www.jetbrains.com/idea/features/nodejs.html)

* [WebStorm :: Node.js](http://www.jetbrains.com/webstorm/features/index.html#node.js)


### Testes

* [Testing and Code Coverage With Node.js Apps | Greg Jopa](http://www.gregjopa.com/2014/02/testing-and-code-coverage-with-node-js-apps/)
