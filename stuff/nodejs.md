# Node.js

<!-- toc -->

* [Visão Geral](#visão-geral)
* [Sites Oficiais](#sites-oficiais)
* [IO.js](#iojs)
* [Aprendizado](#aprendizado)
* [Comunidades e Grupos](#comunidades-e-grupos)
* [Casos de Uso](#casos-de-uso)
  * [IBM developerWorks](#ibm-developerworks)
* [Projetos Interessantes](#projetos-interessantes)
  * [Desenvolvimento](#desenvolvimento)
    * [Configuração do Ambiente](#configuração-do-ambiente)
    * [Exemplos](#exemplos)
  * [Código](#código)
    * [Documentação](#documentação)
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
  * [Crypto](#crypto)
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
    * [Mobile: iOS, Android, Windows Phone](#mobile-ios-android-windows-phone)
    * [Node Copter](#node-copter)
    * [Lego Mindstorms](#lego-mindstorms)
    * [Tessel](#tessel)
    * [Espruino](#espruino)
    * [Arduino](#arduino)
    * [RaspberryPi](#raspberrypi)
* [Abstract Syntax Tree](#abstract-syntax-tree)
* [Dicas](#dicas)
  * [Streams](#streams)
  * [portable code](#portable-code)
  * [fake data](#fake-data)
  * [command and shell](#command-and-shell)
  * [process manager](#process-manager)
  * [Produção](#produção)
  * [REST](#rest)
  * [Authentication](#authentication)
    * [WebID](#webid)
  * [url rewrite proxy](#url-rewrite-proxy)
  * [Módulo](#módulo)
  * [NPM](#npm)
  * [Yarn](#yarn)
  * [CORS](#cors)
  * [Armazenamento](#armazenamento)
  * [Virtualização](#virtualização)
    * [Vagrant](#vagrant)
    * [Docker](#docker)
  * [Nuvem](#nuvem)
    * [Pessoal](#pessoal)
    * [Google Cloud](#google-cloud)
    * [Amazon AWS](#amazon-aws)
    * [Windows Azure](#windows-azure)
  * [Mobile](#mobile)
    * [iOS](#ios)
  * [Desktop](#desktop)
    * [electron](#electron)
    * [Node Webkit](#node-webkit)
  * [Modulos e Frameworks](#modulos-e-frameworks)
    * [Socket.io](#socketio)
    * [Connect](#connect)
    * [Express.js](#expressjs)
    * [Meteor](#meteor)
  * [Testes](#testes)
    * [Test Runner](#test-runner)
  * [Ferramentas](#ferramentas)
    * [Visual Studio](#visual-studio)
    * [Eclipse IDE](#eclipse-ide)
    * [JetBrains](#jetbrains)

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

* [The emperor’s new clothes were built with Node.js | Notes (beta)](http://notes.ericjiang.com/posts/751)

--

* [[GitHub] zeMirco / nodejs-pdf-docs](https://github.com/zeMirco/nodejs-pdf-docs) - Node.js Manual & Documentation (.pdf, .mobi, .epub)

--

* [[GitHub] erkobridee / lab-nodejs](https://github.com/erkobridee/lab-nodejs) - Laboratório de testes com o Node.js

* [[GitHub] simonholmes / knowing-node](https://github.com/simonholmes/knowing-node/) - Holds the code files from my Knowing Node tutorials

* [[GitHub] sindresorhus / awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs) - Delightful Node.js packages and resources

--

* [[GitHub] woliveiras / nodejs-in-brazil](https://github.com/woliveiras/nodejs-in-brazil) - A great list about Nodejs use in Brazil

--

* [Updating NodeJS on Windows - Some Tips | Raymond Camden](https://www.raymondcamden.com/2017/05/31/updating-nodejs-on-windows-some-tips/) - 2017/05/31

--

* NVM - node version manager

  * [[GitHub] brianloveswords / nvm](https://github.com/brianloveswords/nvm) - Install and managing different versions of node and linking local versions into specific directories. Very simple setup and no need for a special shell [ `npm install -g nvm` ]

  * [[GitHub] creationix / nvm](https://github.com/creationix/nvm) - Node Version Manager - Simple bash script to manage multiple active node.js versions

  * [[GitHub] coreybutler / nvm-windows](https://github.com/coreybutler/nvm-windows) - A node.js version management utility for Windows. Ironically written in Go.

  * [Installing and using different versions of Node.js and IO.js in your development environment using NVM | Node Tuts](http://nodetuts.com/series/tools-tips-tricks/tools-tips-tricks-01.html)

  * [Utilizando versões antigas do Nodejs | William Oliveira](http://woliveiras.com.br/posts/utilizando-versoes-antigas-do-nodejs/)


* [[GitHub] tj / n](https://github.com/tj/n) - Node version management

--

* [10 Habits of a Happy Node Hacker (2016) | Heroku](https://blog.heroku.com/archives/2015/11/10/node-habits-2016)


## Sites Oficiais

* [Node.js](http://nodejs.org/)

* [Node.js API DOCS](http://nodejs.org/api/)

* [Node.js Manual](http://nodemanual.org/latest/)

* [GitHub : Joyent / Node.js : Wiki / Modules](https://github.com/joyent/node/wiki/modules)

* [npm - Node Packaged Modules](https://npmjs.org/)

* [Node.js Jenkins-CI](http://jenkins.nodejs.org/) - To  support a higher degree of stability, and hopefully catch issues sooner,  we (node.js team) have a Jenkins instance running every commit through  the test suite, on each operating system we support.

  * [NodeJS Plugin - Jenkins | Jenkins Wiki](https://wiki.jenkins-ci.org/display/JENKINS/NodeJS+Plugin)


## IO.js

> Node.js e IO.js foram unificados, primeio build do merge [Node.js v4.0.0](https://nodejs.org/en/blog/release/v4.0.0/)

* [IO.js - JavaScript I/O](https://iojs.org/)

* [[GitHub] iojs / io.js](https://github.com/iojs/io.js) - A spork of Node.js with an open governance model

* [IO.js Overview | RisingStack Engineering](http://blog.risingstack.com/iojs-overview/)

--

* v4.x

  * [Atualizando o Node.JS para sua última versão (4.x) | Medium - by @dleitee](https://medium.com/@dleitee/atualizando-o-node-js-para-sua-%C3%BAltima-vers%C3%A3o-8119a7f872a4) - 2015/09/14

  * [7 Reasons to Upgrade to Node v4 Now | cli-nerd.com](http://www.cli-nerd.com/2015/09/09/7-reasons-to-upgrade-to-node-v4-now.html) - 20150/09/09


## Aprendizado

* [Node : Complete CheatSheet | Gentlenode Studio - Journal](http://journal.gentlenode.com/node-2-node-js-cheatsheet/)

* [Enter the World of Node.js | SitePoint](http://www.sitepoint.com/enter-world-node-js/)

* [How to Node](http://howtonode.org/)

* [Node Tuts](http://nodetuts.com/) - Node.js Video Tutorials

* [5 Free Beginner Friendly Books for Learning Node.js | CodeCondo](http://codecondo.com/5-free-beginner-friendly-books-learning-node-js/)

* [The Node Beginner Book](http://www.nodebeginner.org/)

* [[GitHub] rockbot / node-for-beginners](https://github.com/rockbot/node-for-beginners) - A list of resources for Node.js Newbies!

* [[GitHub] IonicaBizau / learning-nodejs](https://github.com/IonicaBizau/learning-nodejs) - NodeJS for beginners.

* [An Absolute Beginner's Guide to Node.js | Modulus Blog](http://blog.modulus.io/absolute-beginners-guide-to-nodejs)

* [The Absolute Beginner’s Guide to Node.js | Codeship](http://blog.codeship.io/2014/05/07/nodejs-beginners-guide.html)

* [[GitHub] maxogden / art-of-node](https://github.com/maxogden/art-of-node) - The Art of Node.js : a short introduction to node.js

* [[GitHub] rvagg / learnyounode](https://github.com/rvagg/learnyounode) - Learn You The Node.js For Much Win! An intro to Node.js via a set of self-guided workshops.

* [Node.js for Beginners | Nettuts+](http://net.tutsplus.com/tutorials/javascript-ajax/node-js-for-beginners/)

* [Node School](http://nodeschool.io/) - Learn Node.JS with interactive lessons

* [Node.js: A Jumpstart for Devs | NewCircle](https://thenewcircle.com/s/post/1534/nodejs_tutorial_videos_geolocation_app)

* [Node.js Archives - Tutorials | socialchai.com](http://socialchai.com/tuts/free-online-course/node-js/)

* [[YouTube] Zero to Hero with Node.js - Code Geek](https://www.youtube.com/watch?v=jzFdRTgveXY) - 2016/11/13

* [[GitHub] azat-co / practicalnode](https://github.com/azat-co/practicalnode) - Practical Node.js, 1st and 2nd Editions [Apress]

--

* [You Don't Know Node: Quick Intro to Core Features | webapplog](http://webapplog.com/you-dont-know-node/)

  * [[GitHub] azat-co / you-dont-know-node](https://github.com/azat-co/you-dont-know-node) - You Don't Know Node.js

--

* [Node.js | Underground WebDev](http://udgwebdev.com/nodejs/)

* [Node.js para leigos (Versão completa) | Underground WebDev](http://www.udgwebdev.com/nodejs-para-leigos/)

* [Quer aprender Node.js? (Atualizado) | Underground WebDev](http://udgwebdev.com/quer-aprender-node-js-atualizado/)

* [Otimizando aplicações Node.js | Underground WebDev](http://udgwebdev.com/otimizando-aplicacoes-nodejs/)

--

* [Node.js beyond the basics | IBM developerWorks](http://www.ibm.com/developerworks/training/kp/j-kp-node/) - Rapid web application development for the cloud

--

* [Teach Yourself Node.JS in 10 Steps | Pony Foo](http://blog.ponyfoo.com/2013/07/12/teach-yourself-nodejs-in-10-steps)

* [7 tips for a Node.js padawan | Tech Talk — Medium](https://medium.com/tech-talk/e7c0b0e5ce3c) - Node.js development is extremely fun and satisfying. There are over 35k modules to choose from, and overall node is very easy to develop a working application that can scale easily

--

* [Ten Common Mistakes in Node.js Development | Toptal](http://www.toptal.com/nodejs/top-10-common-nodejs-developer-mistakes)

* [Top 10 Mistakes Node.js Developers Make | AirPair](https://www.airpair.com/node.js/posts/top-10-mistakes-node-developers-make)

  * [[GitHub] alessioalex / airpair-nodejs-mistakes](https://github.com/alessioalex/airpair-nodejs-mistakes) - Top 10 Mistakes Node.js Developers Make - Airpair article (sample code)

--

* [[SlideShare] Nodejs Explained with Examples](http://www.slideshare.net/gabriele.lana/nodejs-explained-with-examples)

* [Understanding how to create a nodejs package.json | Nodejitsu](http://package.json.nodejitsu.com/) - Package.json: an interactive guide

* [Entendendo o Event-loop do Node.js | iMasters](http://imasters.com.br/front-end/javascript/entendendo-o-event-loop-do-node-js/)

* [Understanding the node.js event loop](http://blog.mixu.net/2011/02/01/understanding-the-node-js-event-loop/)

* [Mastering Node.js](http://visionmedia.github.com/masteringnode/) Open Source Node eBook

* [Learning Server-Side JavaScript with Node.js](http://net.tutsplus.com/tutorials/javascript-ajax/learning-serverside-javascript-with-node-js/)

* [Node.js : Require and Exports](http://openmymind.net/2012/2/3/Node-Require-and-Exports/)

  * [[Gist] Better local require() paths for Node.js](https://gist.github.com/branneman/8048520)

* [How to Use Exports in NodeJS | Liang Zan](http://blog.liangzan.net/blog/2012/06/04/how-to-use-exports-in-nodejs/)

* [Export This: Interface Design Patterns for Node.js Modules | Bites from Good Eggs](http://bites.goodeggs.com/posts/export-this/)

* [How I write Node.js modules](http://substack.net/how_I_write_modules)

* [Learn Node.js Completely and with Confidence](http://javascriptissexy.com/learn-node-js-completely-and-with-confidence/)

* [Getting Started with Node.js, Coffeescript, MongoDB, and more - Matt Kopala](http://mattkopala.com/blog/2012/02/12/getting-started-with-nodejs/)

* [5 Talks to Learn More About Node.js](http://blog.modulus.io/five-talks-learn-more-nodejs)

* [[YouTube] Node.js Explained](https://www.youtube.com/watch?v=L0pjVcIsU6A)

* [Using Node.s Event Module | Nettuts+](http://net.tutsplus.com/tutorials/javascript-ajax/using-nodes-event-module/)

* [Understanding Exceptions and Domains in Node.js | How to JS](http://www.howtojs.org/understanding-exceptions-domains-in-nodejs/)

--

* [Node.js Best Practices | RisingStack Engineering](http://blog.risingstack.com/node-js-best-practices/)

* [Node.js Best Practices | Codementor](https://www.codementor.io/nodejs/tutorial/nodejs-best-practices)

* [[GitHub] RisingStack / node-style-guide](https://github.com/RisingStack/node-style-guide) - A mostly reasonable approach to JavaScript - how we write Node.js at RisingStack


## Comunidades e Grupos

* [NodeBR](http://nodebr.com/) - é o repositório de artigos da comunidade brasileira de node.js

* [Node.js Brasil](http://nodejsbrasil.com.br/) - Blog comunitário da comunidade de Node.js brasileira

  * [Grupo no Facebook](https://www.facebook.com/groups/nodejsbrasil/)

  * [Grupo no Google+](https://plus.google.com/u/0/communities/114677724833864547063)

* [Node.js World](http://nodejsworld.com/)

* [StrongLoog](http://strongloop.com/strongblog/category/portuguese/) - post em português

* [npm awesome](http://npmawesome.com/)

* [[GitHub] sindresorhus / awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs) - A curated list of delightful Node.js packages and resources


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

  * [[YouTube] Node.js at Scale with Erik Toth - Google I/O 2014](https://www.youtube.com/watch?v=bvDtEcQdGs0) - Transitioning a large organization to a new technology stack can be exciting, exhausting, and fraught with peril. We’ll look at how PayPal is using Node.js as both a technology and philosophy and what successes and pitfalls have been encountered along the way [2014/09/02]

* [Why Node.js is becoming the go-to technology in the Enterprise | Node Crunch](http://www.nearform.com/nodecrunch/node-js-becoming-go-technology-enterprise)

* [[YouTube] Sean McCullough: Transitioning Groupon to Node.js](https://www.youtube.com/watch?v=TWVblTpUlxM)

* [Node.js on the Road: Fruit Loops and Cheerios: Frontend Node At Walmart | Developer Center - Joyent](https://www.joyent.com/developers/videos/node-js-on-the-road-cincinnati-kevin-decker)

* [Building With Node.js At LinkedIn | talentbuddy.co](https://www.talentbuddy.co/blog/building-with-node-js-at-linkedin/)

* [How we built the new BBC Homepage | BBC](http://www.bbc.co.uk/blogs/internet/entries/47a96d23-ae04-444e-808f-678e6809765d)

* [Node.js for the Real World | eBay Dev Blog](http://www.technology-ebay.de/the-teams/mobile-de/blog/nodejs-real-world) - 2015/10/16

* [[YouTube] Node.js at Uber](https://www.youtube.com/watch?v=ElI5QtUISWM) - 2015/12/09


### IBM developerWorks

* [Developing mobile apps with Node.js and MongoDB, Part 1: A team's methods and results](http://www.ibm.com/developerworks/java/library/mo-nodejs-1/index.html)

* [Developing mobile apps with Node.js and MongoDB, Part 2: Hints and tips](http://www.ibm.com/developerworks/mobile/library/mo-nodejs-2/index.html)


## Projetos Interessantes

* Node.js - Linux Ubuntu and Debian support

  * Ubuntu repository - [PPA - Chris Lea](https://launchpad.net/~chris-lea/+archive/ubuntu/node.js)

  * [[GitHub] nodesource / distributions](https://github.com/nodesource/distributions) - NodeSource Node.js Binary Distributions

  * The powers of [@chrislea](https://twitter.com/chrislea) and [@nodesource](https://twitter.com/nodesource) combine to provide a new, solid *Ubuntu* and *Debian* binary repo for Node.js [blog post](https://nodesource.com/blog/chris-lea-joins-forces-with-nodesource) - 2014/07/09

  * [Installing Node.js Tutorial: Using nvm on macOS and Ubuntu | Node Source](https://nodesource.com/blog/installing-node-js-tutorial-using-nvm-on-mac-os-x-and-ubuntu/) - 2017/02/16

  * [Installing the latest Node.js on Ubuntu via nvm | SmallData](https://smalldata.tech/blog/2016/08/02/ubuntu-nodejs-nvm) - 2016/08/02

  * [Installing Node.js 8 on Linux via Package Manager | NodeSource](https://nodesource.com/blog/installing-node-js-8-tutorial-linux-via-package-manager) - 2017/05/31

--

* [[GitHub] parro-it / awesome-micro-npm-packages](https://github.com/parro-it/awesome-micro-npm-packages) - A curated list of small, focused npm packages

--

* [Runtime.js](http://runtimejs.org/) - javascript operational system for the cloud

  * [[GitHub] runtimejs / runtime](https://github.com/runtimejs/runtime)

  * [runtime.js — JavaScript library OS | Medium by  @iefserge](https://medium.com/@iefserge/runtime-js-javascript-library-os-823ada1cc3c)

--

* [[GitHub] froskie / toggl-to-timesheet](https://github.com/froskie/toggl-to-timesheet) - Generate a timesheet from a [Toggl](toggl.com) Detailed Report

* [[GitHub] filipedeschamps / cep-promise](https://github.com/filipedeschamps/cep-promise) - Busca por CEP integrado diretamente aos serviços dos correios

--

* [Node Twitter Sentiment | Michael Herman](http://mherman.org/blog/2014/02/19/node-twitter-sentiment/)

* [[GitHub] thisandagain / sentiment](https://github.com/thisandagain/sentiment) - AFINN-based sentiment analysis for Node.js

  * [Sentiment analysis in Node.js | Nodejitsu](https://blog.nodejitsu.com/npmawesome-sentiment/)

--

* [[GitHub] sqren / fb-sleep-stats](https://github.com/sqren/fb-sleep-stats) - Use Facebook to track your friends’ sleeping habits

--

* [VNC client on 200 lines of JavaScript | Minko Gechev's blog](http://blog.mgechev.com/2013/08/30/vnc-javascript-nodejs/)

--

* [[GitHub] skynetim / skynet](https://github.com/skynetim/skynet) - Machine-to-machine instant messaging platform for the internet of things

--

* [Straw](http://strawjs.com/) - Realtime processing dataflow framework for Node.js

  * [[GitHub] simonswain / straw](https://github.com/simonswain/straw)

--

* [[GitHub] VictorQueiroz / regecent](https://github.com/VictorQueiroz/regecent) - Some accents for your Regular Expressions

--

* [[GitHub] fent / node-ytdl](https://github.com/fent/node-ytdl) - Pure Javascript youtube video downloader

* [[GitHub] leetreveil / node-musicmetadata](https://github.com/leetreveil/node-musicmetadata) - Streaming music metadata parser for node, written in pure Javascript

* [[GitHub] ConradIrwin / unicode-dragon](https://github.com/ConradIrwin/unicode-dragon) - eats invalid unicode for breakfast

* [[GitHub] parshap / node-sanitize-filename](https://github.com/parshap/node-sanitize-filename) - Sanitize string for use as filename

--

* [[GitHub] jtrussell / bedecked](https://github.com/jtrussell/bedecked) - Turn markdown files into html presentations you can share with dropbox (or S3, or...)

* [[GitHub] ksky521 / nodePPT](https://github.com/ksky521/nodePPT) - This is probably the best web presentation tool so far

* [[GitHub] gjtorikian / namp](https://github.com/gjtorikian/namp) - A fork of chjj's marked that adds some additional features (markdown)

--

* [[GitHub] indus / ncc](https://github.com/indus/ncc) - node-chrome-canvas : a simple to use and performant HTML5 canvas for Node.js

* [[GitHub] madbence / node-drawille](https://github.com/madbence/node-drawille) - Drawing in terminal with unicode braille characters

* [[GitHub] bevacqua / hit-that](https://github.com/bevacqua/hit-that) - Render beautiful pixel perfect representations of websites in your terminal

* [[GitHub] yaronn / blessed-contrib](https://github.com/yaronn/blessed-contrib) - Build terminal dashboards using ascii/ansi art and javascript

* [[GitHub] felipenmoura / sos-stackoverflow-search](https://github.com/felipenmoura/sos-stackoverflow-search) - SOS - StackOverflow Search in your terminal

--

* [PhantomJS Screen Capture](http://phantomjs.org/screen-capture.html)

  * to work with web fonts

    > use PhantomJS version 2.0.0
    >
    > custom build:
    >
    > * [[GitHub] eugene1g / phantomjs - PhantomJS 2.0 bin](https://github.com/eugene1g/phantomjs/releases/tag/2.0.0-bin) - works with webfonts [ PhantomJS 2.0.0 binaries for OSX and linux (temp, until upstream is patched) ]

* [Screen capturing with PhantomJS | skipperkongen](http://skipperkongen.dk/2014/08/15/screen-capturing-with-phantomjs/)

* [Automate mobile testing: phantom.js | JonathanMH](http://jonathanmh.com/automate-mobile-testing-phantom-js/)

* [Creating thumbnails using PhantomJS and ImageMagick | Frederic Cambus](http://www.cambus.net/creating-thumbnails-using-phantomjs-and-imagemagick/)

* [Print Screen de páginas com o PhantomJS | Marcos Alves](http://blog.marcosalves.org/archives/31)

* [Web Page Clipping with PhantomJS | don't code today what you can't debug tomorrow](http://ariya.ofilabs.com/2013/04/web-page-clipping-with-phantomjs.html)

--

* [[GitHub] ltk / kurtz-kloud](https://github.com/ltk/kurtz-kloud) - A Node app for sharing screen shots

  * [My Quest for the Perfect Screenshot App | Viget](http://viget.com/flourish/my-qwest-for-the-perfect-screenshot-app)

* [[GitHub] vbauer / manet](https://github.com/vbauer/manet) - Website screenshot service powered by Node.js, SlimerJS and PhantomJS

* [[GitHub] eugeneware / html2png](https://github.com/eugeneware/html2png) - Take a screenshot of a HTML fragment or URL

--

* [[GitHub] typicode / hotel](https://github.com/typicode/hotel) - Removes the need to keep terminal tabs. Access and start your local servers from the browsers.

* [[GitHub] jh3y / sike](https://github.com/jh3y/sike) - a cli tool that reminds you to get up and move around

* [[GitHub] rschmukler / agenda](https://github.com/rschmukler/agenda) - Lightweight job scheduling for node

--

* [[GitHub] redwire / aIRChat](https://github.com/redwire/aIRChat) - A beautiful, modernized, browser-based IRC client

* [[GitHub] erming / shout](https://github.com/erming/shout) - A web IRC client

  * [Shout: An IRC Client for the Web | DailyJS](http://dailyjs.com/2014/09/09/shout/)

--

* [[GitHub] sdelements / lets-chat](https://github.com/sdelements/lets-chat) - Self-hosted chat app for small teams

--

* [SuperScript](http://superscriptjs.com/) - A language for writing Chat Bots

  * [[GitHub] silentrob / superscript](https://github.com/silentrob/superscript) - A dialogue engine for creating chat bots

--

* [Building a Slack Bot with Node.js and Chuck Norris Super Powers | Scotch](https://scotch.io/tutorials/building-a-slack-bot-with-node-js-and-chuck-norris-super-powers) - 2015/09/14

--

* [[GitHub] C2FO / nools](https://github.com/C2FO/nools) - Rete based rules engine written in javascript

* [[GitHub] gchudnov / bspec](https://github.com/gchudnov/bspec) - A JavaScript library for structuring business rules

  * [Structuring and validating business rules in JavaScript | Medium - by Grigoriy Chudnov](https://medium.com/@gchudnov/structuring-and-validating-business-rules-in-javascript-fbaa1019902a)

--

* [[GitHub] vesln / teacher](https://github.com/vesln/teacher) - Spell check for Node.js


### Desenvolvimento

* [NoFlo | Flow-Based Programming for JavaScript](http://noflojs.org/)

* [[GitHub] idflood / ThreeNodes.js](https://github.com/idflood/ThreeNodes.js) - This is an attempt to make something like "vvvv" in javascript, html and webgl.

--

* [Windows and Node: Addons | DailyJS](http://dailyjs.com/2012/05/17/windows-and-node-3/)

  * [Addons | Nodejs API](http://nodejs.org/docs/latest/api/all.html#all_addons) - use C or C++ libraries. Node modules may include both addons and JavaScript code.

* [Writing Node.js Addons | Tuts+ Code Tutorial](http://code.tutsplus.com/tutorials/writing-nodejs-addons--cms-21771)

* [Running NodeJS on Linux on Windows (with no VM) | Hacker Noon - Medium](https://hackernoon.com/running-nodejs-on-linux-on-windows-88bd12993bae) - 2016/11/16

--

* [Node Console](http://www.node-console.com/script/code) - test node.js apps online

* [[GitHub] MatthewMueller / coderunner](https://github.com/matthewmueller/coderunner) - Run server-side code quickly and securely in the browser

--

* [[GitHub] steves / node-jira](https://github.com/steves/node-jira) - A nodejs wrapper for the JIRA REST API

--

* [[GitHub] BrowserSync / browser-sync](https://github.com/BrowserSync/browser-sync) - Keep multiple browsers & devices in sync when building websites

  * [[GitHub] BrowserSync / recipes](https://github.com/BrowserSync/recipes)

  * [A BrowserSync Primer | Pony Foo](http://blog.ponyfoo.com/2014/08/12/a-browsersync-primer)

  * [Browser-sync, indispensável para desenvolver sites em vários dispositivos | caelum blog](http://blog.caelum.com.br/browser-sync-indispensavel-para-desenvolver-sites-em-varios-dispositivos/) - 2015/06/17

  * [How to Use BrowserSync for Faster Development | Scotch](https://scotch.io/tutorials/how-to-use-browsersync-for-faster-development)

--

* [[GitHub] sindresorhus / pageres](https://github.com/sindresorhus/pageres) - Get screenshots of websites in different resolutions

  * [[GitHub] sindresorhus / grunt-pageres](https://github.com/sindresorhus/grunt-pageres) - Responsive website screenshots

--

* [[GitHub] laurentj / slimerjs](https://github.com/laurentj/slimerjs) - A PhantomJS-like tool running Gecko

* [Phantomjs](http://phantomjs.org/) -  is a headless WebKit scriptable with a JavaScript API. It has fast and native support for various web standards: DOM handling, CSS selector, JSON, Canvas, and SVG

  * [[GitHub] segmentio / nightmare](https://github.com/segmentio/nightmare) - A high level wrapper for Phantomjs

  * [[GitHub] jiahaog / Revenant](https://github.com/jiahaog/Revenant) - A high level PhantomJS headless browser in Node.js ideal for task automation

  * [[GitHub] fouber / page-monitor](https://github.com/fouber/page-monitor) - capture webpage and diff the dom change with phantomjs

  * [[GitHub] redco / goose-parser](https://github.com/redco/goose-parser) - PhantomJS/Browser lib which allows to parse webpages on the Internet

--

* [CasperJS](http://casperjs.org/) is a navigation scripting & testing utility for PhantomJS and SlimerJS written in Javascript

* [Automated end to end testing at Khan Academy using Gecko | Brian R. Bondy](http://www.brianbondy.com/blog/id/167/automated-end-to-end-testing-at-khan-academy-using-gecko/)

--

* [[GitHub] johntitus / node-horseman](https://github.com/johntitus/node-horseman) - Run PhantomJS from Node

  * [Web Crawling with Node, PhantomJS and Horseman | SitePoint](http://www.sitepoint.com/web-crawling-node-phantomjs-horseman/) - 2016/02/22

--

* [[GitHub] MatthewMueller / cheerio](https://github.com/MatthewMueller/cheerio)

  * [[YouTube] Web Scraping with Node.js | freeCodeCamp](https://www.youtube.com/watch?v=eUYMiztBEdY) - 2018/02/15

  * [Web Scraping With Node.js | Smashing Magazine](http://www.smashingmagazine.com/2015/04/08/web-scraping-with-nodejs/) - 2015/04/08

  * [Scraping the Web with Node.js | Code Responsible](http://coderesponsible.com/scraping-the-web-with-node-js/) - (2015/11/15) Cheerio is a perfect solution for retrieving the data from these websites and creating your own API using Node.js.

  * [Use Node.js to Extract Data from the Web for Fun and Profit | Stormin' The Castle](http://www.storminthecastle.com/2013/08/25/use-node-js-to-extract-data-from-the-web-for-fun-and-profit/)

  * [Mineração de dados e as funções map, reduce e filter | NodeBR - NodeJS Brasil](http://nodebr.com/mineracao-de-dados-e-as-funcoes-map-reduce-filter/)

  * [Using Cheerio and MongoDB to scrape a large website | Qawelesizwe Mlilo](http://blog.ragingflame.co.za/2014/6/27/using-cheerio-and-mongodb-to-scrap-a-large-website) - (27/06/2014) Scrapping websites using node.js

  * [Microservice Series: Scraper | Hacker Noon](https://hackernoon.com/microservice-series-scraper-ee970df3e81f) - 2017/01/05

  * [Scrape any Website/Service/API with a single SQL Select Statement | Hacker Noon](https://hackernoon.com/scrape-any-website-service-api-with-a-single-sql-select-statement-8d60be1e9a49) - 2017/01/18

  * [[YouTube] Web crawler com Node.js - Capturando informações de um site](https://www.youtube.com/watch?v=2B6MpQvsQp0) - 2016/04/27

  * [[GitHub] ruipgil / scraperjs](https://github.com/ruipgil/scraperjs) - A complete and versatile web scraper

  * [[GitHub] molekilla / menio](https://github.com/molekilla/menio) - production-quality template convention to scrap web sites based on cheerio

  * [[GitHub] facundoolano / google-play-scraper](https://github.com/facundoolano/google-play-scraper) - scrapes basic app data from google play store

* [[GitHub] rchipka / node-osmosis](https://github.com/rchipka/node-osmosis) - Web scraper for NodeJS

  * [Web Scraping in Node.js with Multiple Examples | Hack Programming](https://hackprogramming.com/web-scraping-in-node-js-with-multiple-examples/) - 2017/03/08

* [[GitHub] inikulin / ineed](https://github.com/inikulin/ineed) - Web scraping and HTML-reprocessing. The easy way.

* [[GitHub] missinglink / huntsman](https://github.com/missinglink/huntsman) - Super configurable async web spider

* [[GitHub] addyosmani / oust](https://github.com/addyosmani/oust) - Extract URLs to stylesheets, scripts, links, images or HTML imports from HTML

* [[GitHub] dharmafly / noodle](https://github.com/dharmafly/noodle) - A node server and module which allows for cross-domain page scraping on web documents with JSONP or POST

* [[GitHub] rc0x03 / node-osmosis](https://github.com/rc0x03/node-osmosis) - HTML/XML parser and web scraper for NodeJS.

--

* [[GitHub] rwhitmire / tag-builder](https://github.com/rwhitmire/tag-builder) - Fluent html tag building library

--

* [Debug Node.js Apps using VS Code | Visual Studio Code](https://code.visualstudio.com/docs/nodejs/nodejs-debugging) - (2018/03/07) The Visual Studio Code editor includes Node.js debugging support. Set breakpoints, step-in, inspect variables and more.

* [Debugging Node.js with Google Chrome | Node.js Collection - Medium](https://medium.com/the-node-js-collection/debugging-node-js-with-google-chrome-4965b5f910f4) - 2017/05/25

* [Running and debugging Node.js application | JetBrains WebStorm Blog](http://blog.jetbrains.com/webstorm/2014/02/running-and-debugging-node-js-application/)

* [How to debug Node.js? What is the best way to debug Node.js? | { 100PercentJS }](http://www.100percentjs.com/best-way-debug-node-js/)

* [Debugging with Node | Krasimir Tsonev](http://krasimirtsonev.com/blog/article/debugging-with-node)

* [How to Debug Node.js with the Best Tools Available | @RisingStack](https://blog.risingstack.com/how-to-debug-nodej-js-with-the-best-tools-available/) - 2017/04/25

--

* [[GitHub] boblauer / mock-require](https://github.com/boblauer/mock-require) - Simple, intuitive mocking of Node.js modules.

* [[GitHub] moll / node-mitm](https://github.com/moll/node-mitm) - Intercept and mock outgoing Node.js network TCP connections and HTTP requests for testing. Intercepts and gives you a Net.Socket, Http.IncomingMessage and Http.ServerResponse to test and respond with. Super useful when testing code that hits remote servers

--

* [[GitHub] sourcejs / Source](https://github.com/sourcejs/Source) - Living Style Guide Engine and Maintenance Environment for Front-end Components. Core repository.

--

* [[GitHub] tombenke / kickoff](https://github.com/tombenke/kickoff) - Command line tool to easily create boilerplate code for new projects and other things based on archetypes stored in GitHub repos

* [[GitHub] google / web-starter-kit](https://github.com/google/web-starter-kit)

  * [Web Starter Kit | Google Developer](https://developers.google.com/web/starter-kit/) - Boilerplate & Tooling for Multi-Device Development


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


#### Documentação

* [JSDocs](http://usejsdoc.org/)

  * [[GitHub] jsdoc3 / jsdoc](https://github.com/jsdoc3/jsdoc) - An API documentation generator for JavaScript

* [[GitHub] rrrene / inchjs](https://github.com/rrrene/inchjs) - A documentation tool for JavaScript/NodeJS

* [[GitHub] yui / yuidoc](https://github.com/yui/yuidoc) - YUI Javascript Documentation Tool


#### Performance, Proteção e Otimização

* [JXCore](http://jxcore.com/)

* [Code Protection and Packaging for Node.js Projects with JXCore | Flippin' Awesome](http://flippinawesome.org/2014/04/21/code-protection-and-packaging-for-node-js-projects-with-jxcore/)

* [Node.js / V8 Garbage Collection & Memory Leak analysis](http://apmblog.dynatrace.com/2015/11/04/understanding-garbage-collection-and-hunting-memory-leaks-in-node-js/) - Using Garbage Collection & Memory Leaks to trace Node.js performance issues

* [Monitoring the performance of a Node.js web application - Sqreen Blog | Modern Application Security](https://blog.sqreen.io/diy-node-apm/) - 2017/11/21


#### Análise

* [[GitHub] fullstackio / cq](https://github.com/fullstackio/cq) - extract code snippets using selectors (instead of line numbers)

* [Automating Web Performance Measurement | HTML5Rocks](http://updates.html5rocks.com/2014/06/Automating-Web-Performance-Measurement)

* [[GitHub] t32k / stylestats](https://github.com/t32k/stylestats) - StyleStats is Node.js library to collect CSS statistics!

* [[GitHub] mdevils / node-jscs](https://github.com/mdevils/node-jscs) - JavaScript Code Style checker

* [[GitHub] mozilla / scanjs](https://github.com/mozilla/scanjs) - Static analysis tool for javascript code based. Scanjs uses Acorn to convert sources to AST, then walks AST looking for patterns

* [[GitHub] es-analysis / plato](https://github.com/es-analysis/plato) - JavaScript source code visualization, static analysis, and complexity tool

  * [JavaScript Code Complexity Visualization | Ariya Hidayat](http://ariya.ofilabs.com/2013/01/javascript-code-complexity-visualization.html)

* [[GitHub] gmetais / grunt-devperf](https://github.com/gmetais/grunt-devperf/) - Helps front-end developers to maintain a good quality, based on phantomas and grunt-phantomas

* [[GitHub] pmdartus / speedline](https://github.com/pmdartus/speedline) - Calculate the speed index and visual performance metrics from chrome dev tool timeline


### Monitoramento e Logs

* [[GitHub] MrRio / vtop](https://github.com/MrRio/vtop) - Wow such top. So stats. More better than regular top. Written in node.js

* [[GitHub] niallo / node-httpcheck](https://github.com/niallo/node-httpcheck) - Simple HTTP status checker with timeout

* [GitHub : Status Dashboard](https://github.com/obazoud/statusdashboard) - Status Dashboard is status page for your configured services or applications.

* [dnc : a CLI tool to check domain names configuration and statistics](http://www.cambus.net/dnc-a-cli-tool-to-check-domain-names-configuration-and-statistics/)

  * [[GitHub] fcambus / dnc](https://github.com/fcambus/dnc) - A CLI tool to check domain names configuration and statistics

* [[GitHub] NarrativeScience / Log.io](https://github.com/NarrativeScience/Log.io)

  * [log.io](http://logio.org/) - Real-time log monitoring in your browser

--

* [[GitHub] caiogondim / logdown](https://github.com/caiogondim/logdown) - Debug utility with markdown support that runs on browser and server

--

* [Streaming Logs with Transducers and Ramda | simplectic](http://simplectic.com/blog/2015/ramda-transducers-logs/)


### Versionamento

* [[GitHub] webpro / release-it](https://github.com/webpro/release-it) - Interactive release tool for Git repositories. Supports to build and release to a distribution/component repository. Publish to npm.

* [[GitHub] radubrehar / versiony](https://github.com/radubrehar/versiony) - Node.js module to increment version number for your code/module


### Identificadores

* [[GitHub] sindresorhus / hasha](https://github.com/sindresorhus/hasha) - Get the hash of a buffer/string/stream/file

* [[GitHub] planttheidea / hash-it](https://github.com/planttheidea/hash-it) - Hash any object type based on its values

--

* [[GitHub] williamkapke / bson-objectid](https://github.com/williamkapke/bson-objectid) - Construct ObjectIDs without the mongodb driver or bson module

--

* [uuid | node.js modules](https://nodejsmodules.org/tags/uuid)

* [[GitHub] broofa / node-uuid](https://github.com/broofa/node-uuid) - Generate RFC-compliant UUIDs in JavaScript

* [[GitHub] dilvie / cuid](https://github.com/dilvie/cuid) - Collision-resistant ids optimized for horizontal scaling and performance

* [[GitHub] chilts / flake](https://github.com/chilts/flake) - Generate practically unique (approximately sortable) IDs in a distributed environment

* [[GitHub] substack / node-hat](https://github.com/substack/node-hat) - Generate random IDs and avoid collisions |

  * [node.js | hashids](http://www.hashids.org/node-js/) - Generate short hashes from numbers (like YouTube and Bitly).

    * [[GitHub] ivanakimov / hashids.node.js](https://github.com/ivanakimov/hashids.node.js) - A small Node.js class to generate YouTube-like hashids from one or many numbers. Use hashids when you do not want to expose your database ids to the user

--

* [[GitHub] dylang / shortid](https://github.com/dylang/shortid) - Short id generator. Url-friendly. Non-predictable. Cluster-compatible.

  * [[GitHub] jetpks / shortness](https://github.com/jetpks/shortness) - A url shortening library written with node.js and sqlite3

* [[GitHub] UmbraEngineering / short-id](https://github.com/UmbraEngineering/short-id) - Short ID String Generation for Node.js

* [[GitHub] ai / nanoid](https://github.com/ai/nanoid) - A tiny, secure URL-friendly unique string ID generator for JavaScript

--

* [[GitHub] punkave / sluggo](https://github.com/punkave/sluggo) - High-speed, unicode-aware, browser-friendly slug generator

* [[GitHub] QubitProducts / urlite](https://github.com/QubitProducts/urlite) - A very small, fast, dependency free url parser and formatter for nodejs and the web


### Encurtador de URLs

* [[GitHub] edwardhotchkiss / short](https://github.com/edwardhotchkiss/short) - Promise-based Node.js URL Shortener (use short-id) backed by Mongoose.js

* [[GitHub] thinkroth / shortUrl](https://github.com/thinkroth/shortUrl) - Another short url service in node.js

--

* [[GitHub] matheusgimenez / dilma.co.in](https://github.com/matheusgimenez/dilma.co.in) - web app to short url's


### Desencurtador de URLs

* [[GitHub] scottksmith95 / url-expand](https://github.com/scottksmith95/url-expand) - Simple and efficient URL expander


### Controle de Fluxo de Execução

* [[GitHub] sindresorhus / promise-fun](https://github.com/sindresorhus/promise-fun) - Promise packages, patterns, chat, and tutorials

--

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

* [Node.js - Trabalhando com eventos | Nomadev](http://nomadev.com.br/node-js-trabalhando-com-eventos/)

--

* [Como evitar o inferno de callbacks | NodeBR - NodeJS Brasil](http://nodebr.com/como-evitar-o-inferno-de-callbacks/)

* [Evitando callback hell no Node.js | Underground WebDev](http://udgwebdev.com/evitando-callback-hell-no-node-js/)

* [Managing Node.js Callback Hell with Promises, Generators and Other Approaches | StrongLoop](http://strongloop.com/strongblog/node-js-callback-hell-promises-generators/)


### Git e GitHub

* [How to Build a GitHub Webhook with node.js | Backand Blog](http://blog.backand.com/github-webhook-node/)

--

* [[GitHub] philschatz / octokat.js](https://github.com/philschatz/octokat.js) - Client for the Github API using callbacks or Promises. Intended for the browser or NodeJS.

--

* [Node GH](http://nodegh.io/) = NodeJS + GitHub - GitHub command line tools

* ungit : [[GitHub] FredrikNoren / ungit](https://github.com/FredrikNoren/ungit) | [npm](https://npmjs.org/package/ungit) | [[Youtube] Introduction](https://www.youtube.com/watch?v=hkBVAi3oKvo) - The easiest way to use git. On any platform. Anywhere.

* [[GitHub] creationix / js-git](https://github.com/creationix/js-git) - JS-Git an open source project implementing git client and server in pure JavaScript

* [[GitHub] nodegit / nodegit](https://github.com/nodegit/nodegit) - Native asynchronous bindings to libgit2 for Node.js

--

* [[GitHub] IonicaBizau / git-stats](https://github.com/IonicaBizau/git-stats) - A GitHub-like contributions calendar, but locally, with all your git commits

* [[GitHub] IonicaBizau / github-stats](https://github.com/IonicaBizau/github-stats) - Visualize stats about GitHub users and projects in your terminal.

--

* [[GitHub] typicode / husky](https://github.com/typicode/husky) - Prevents bad commit or push (git hooks, pre-commit, pre-push and all that stuff...)

--

* [[GitHub] facebook / mention-bot](https://github.com/facebook/mention-bot) - Automatically mention potential reviewers on pull requests

--

* [[GitHub] bookiza / bookiza](https://github.com/bookiza/bookiza) - The book baking tool

  * [Official handbook](https://bubbl.in/book/official-handbook-by-marvin-danig/)

--

* [GitBook](https://www.gitbook.io/) - Modern Publishing, Simply taking your books from ideas to finished, polished books.

  * [[GitHub] GitbookIO / gitbook](https://github.com/GitbookIO/gitbook) - Utility for generating books and exercises using GitHub/Git and Markdown

  * [Documentation | GitBook](http://help.gitbook.io/)

  * [Learn Javascript](http://gitbookio.github.io/javascript/)

  * [Javascript Challenges](https://tcorral.github.io/javascript-challenges-book/) - This book will challenge you to learn and understand the most obscure and tricky parts of Javascript

    * [[GitHub] tcorral / javascript-challenges-book](https://github.com/tcorral/javascript-challenges-book) - Challenge yourself to learn and understand the most obscure and tricky parts of Javascript

  * [Survive JavaScript - a Web Developer's Guide](http://survivejs.com/)


### Integração com Java

* [[GitHub] dynjs / dynjs](https://github.com/dynjs/dynjs) - (almost) 100% invokedynamic js impl. DynJS is an ECMAScript runtime for the JVM.

* [[GitHub] projectodd / nodyn](https://github.com/projectodd/nodyn) - A node.js compatible framework, running on the JVM. Powered by Vert.x and the DynJS Javascript runtime.s

* [[GitHub] joeferner / node-java](https://github.com/joeferner/node-java) - Bridge API to connect with existing Java APIs.

* [[GitHub] joeferner / node-java-maven](https://github.com/joeferner/node-java-maven) - Utility for Node's java module to load mvn dependencies.

* [[GitHub] auth0-blog / nodejs-maven](https://github.com/auth0-blog/nodejs-maven) - Integrating Node.js build tools with Maven

  * [Integrating Node.js Build Tools with Maven | Auth0](https://auth0.com/blog/integrating-node-dot-js-build-tools-with-maven/) - 2017/06/07

--

* [[GitHub] YaroslavGaponov / node-jvm](https://github.com/YaroslavGaponov/node-jvm) - java virtual machine in pure node.js

* [How to run Node.js on the JVM with Avatar.js and LoopBack | StrongLoop](http://strongloop.com/strongblog/how-to-run-node-js-on-the-jvm-with-avatar-js-and-loopback/)

* [Nashorn: The New Rhino on the Block](http://ariya.ofilabs.com/2014/03/nashorn-the-new-rhino-on-the-block.html)

* [Running Node.js applications on the JVM with Nashorn and Java 8 | CLOSED-LOOP](http://blog.jonasbandi.net/2014/03/running-nodejs-applications-on-jvm-with.html)


### Crypto

* [[GitHub] chrisenytc / bloom](https://github.com/chrisenytc/bloom) - A module wrapper to encrypt and decrypt files with aes-256-cbc

* [Crypton](https://crypton.io/) - is an application framework and backend service that enables developers to build privacy-centered, scalable mobile and desktop applications without the requirement of extensive security or cryptography knowledge

  * [[GitHub] SpiderOak / crypton](https://github.com/SpiderOak/crypton/) - A framework for creating zero-knowledge web & mobile applications

* [[GitHub] digitalbazaar / forge](https://github.com/digitalbazaar/forge) - A native implementation of TLS in Javascript and tools to write crypto-based and network-heavy webapps

  * [Implement AES Strength Encryption With JavaScript | Nic Raboy's Code Blog](https://blog.nraboy.com/2014/10/implement-aes-strength-encryption-javascript/) - Implement military strength AES encryption ciphers in your JavaScript application using the Forge cryptography library.

* [[GitHub] voronianski / node-object-encrypter](https://github.com/voronianski/node-object-encrypter) - Encrypt/decrypt javascript objects as base64 strings with optional TTL support

* [[GitHub] lukechilds / base64-async](https://github.com/lukechilds/base64-async) - Non-blocking chunked Base64 encoding


### BitCoins

* [[GitHub] bitpay / bitcore](https://github.com/bitpay/bitcore)

* [Bitcore](http://bitcore.io/) - A pure, powerful core for your bitcoin project. Bitcore is a complete, native interface to the Bitcoin network, and provides the core functionality needed to develop apps for bitcoin.


### Photoshop CC

* [Introducing Adobe Generator for Photoshop CC](http://blogs.adobe.com/photoshopdotcom/2013/09/introducing-adobe-generator-for-photoshop-cc.html) - Generator is based on the popular Node.js platform and plug-ins can be written in JavaScript.

* [Generator plugins are Open Source and available on GitHub](https://github.com/adobe-photoshop/)

* [Introduction to Photoshop Generator | Lee Brimelow](http://www.leebrimelow.com/introduction-to-photoshop-generator/)


### Torrent

* [[GitHub] maxogden / torrent](https://github.com/maxogden/torrent) - download torrents with node from the CLI

* [[GitHub] mafintosh / peerflix](https://github.com/mafintosh/peerflix) - a streaming torrent client

* [[GitHub] mafintosh / peerflix-engine](https://github.com/mafintosh/peerflix-engine) - The low level streaming torrent engine that peerflix will use

* [[GitHub] jaruba / multipass-torrent](https://github.com/jaruba/multipass-torrent) - Collects information about torrents from various sources (dump, RSS, HTML pages) and associates the video files within with IMDB ID - stores data in a distributed DB

* [[GitHub] feross / webtorrent](https://github.com/feross/webtorrent) - Streaming torrent client for the web

* [[GitHub] feross / webtorrent-desktop](https://github.com/feross/webtorrent-desktop) - Streaming torrent client for OS X, Windows, and Linux

--

* [How to make your own bittorrent client | Allen's Adventures in Tech](https://allenkim67.github.io/bittorrent/2016/05/04/how-to-make-your-own-bittorrent-client.html)


### Node.js no Servidor

* [Cobol -- yes, Cobol -- gets a bridge to Node.js | InfoWorld](http://www.infoworld.com/article/2972314/application-development/cobol-nodejs-bridge.html) - 2015/08/18

  * [[Github] IonicaBizau / node-cobol](https://github.com/IonicaBizau/node-cobol) - COBOL bridge for NodeJS which allows you to run COBOL code from NodeJS

* [[GitHub] (pdf) Implementing HTTP/2 for Node.js Core](https://github.com/jasnell/presentations/blob/master/http2/NI.pdf)

--

* [[GitHub] indutny / node-spdy](https://github.com/indutny/node-spdy) - SPDY server on Node.js

* [DynoSRC](http://dinosrc.it/) - Eliminate HTTP requests for JavaScript files and serve differential updates to your users on the fly. No, really. Like, seriously.

* [[GitHub] luin / superfetch](https://github.com/luin/superfetch) - A super powerful node.js HTTP client with the support of promise.

* [[GitHub] williamwicks / litesocket](https://github.com/williamwicks/litesocket) - Realtime server events for Node.JS, using Server Sent Events (SSE)

* [[GitHub] thibauts / node-castv2-client](https://github.com/thibauts/node-castv2-client) - A Chromecast client based on the new (CASTV2) protocol

* [[GitHub] xat / castnow](https://github.com/xat/castnow) - commandline chromecast player

--

* [Down.YT](http://down.yt/) - Direct Downloads From YouTube

  * [[GitHub] matheusgimenez / down.yt](https://github.com/matheusgimenez/down.yt) - youtube downloader

* [[GitHub] MaxGfeller / youtube-mp3](https://github.com/MaxGfeller/youtube-mp3) - npm module for downloading a youtube video as mp3 file. Download the audio from Youtube videos as mp3 file. This module uses youtube-mp3.org for the conversion.

* [[GitHub] IrosTheBeggar / mstream-node](https://github.com/IrosTheBeggar/mstream-node) - A nodeJS port of the mStream project

--

* [Nodemailer](http://www.nodemailer.com/) - is an easy to use module to send e-mails with Node.JS (using SMTP or sendmail or Amazon SES or even your own method) and is unicode friendly - You can use any characters you like

  * [[GitHub] andris9 / Nodemailer](https://github.com/andris9/Nodemailer) - Send e-mails with Node.JS - easy as cake!

  * [Emails with "View in Browser" link in Node.js | Adam Niedzielski](http://blog.sundaycoding.com/blog/2016/03/03/emails-with-view-in-browser-link-in-node-dot-js/)

* [[GitHub] vdemedes / mailman](https://github.com/vdemedes/mailman) - Send emails in a comfortable way via models

--

* [[GitHub] topcloud / cachemere](https://github.com/topcloud/cachemere) - A nice, smooth, cushiony layer of cache

--

* [[GitHub] giodamelio / takeapeek](https://github.com/giodamelio/takeapeek) - A simple static webserver with only one command

--

* [mongo-express](http://andzdroid.github.io/mongo-express/) - Web-based MongoDB admin interface written with Node.js and express

--

* [[GitHub] simonewebdesign / real-time-web-chat](https://github.com/simonewebdesign/real-time-web-chat) - A chat built with NodeJS, ExpressJS and Socket.io | [Demo App on OpenShift](https://github.com/simonewebdesign/real-time-web-chat)

--

* [[GitHub] originalmachine / apogee](https://github.com/originalmachine/apogee) - Build powerful (but simple!) versioned APIs with Connect

* [[GitHub] evilpacket / helmet](https://github.com/evilpacket/helmet) - Collection of middleware to implement various security headers for Express / Connect

--

* [Synth](http://www.synthjs.com/) - The back-end web framework designed to make (Angular|Ember|Backbone)JS web apps easy to create and manage.

--

* [[GitHub] rjrodger / seneca](https://github.com/rjrodger/seneca) - A micro-services toolkit for Node.js.

--

* [[GitHub] keithwhor / nodal](https://github.com/keithwhor/nodal/) - Web Servers Made Easy With Node.js

  * [Nodal – GraphQL Playground](http://graphql.nodaljs.com/)

  * [Realtime Doesn’t Belong Everywhere — Build Scalable API Services in Node.js with Nodal | Medium by @keithwhor](https://medium.com/@keithwhor/realtime-doesn-t-belong-everywhere-build-scalable-api-services-in-node-js-with-nodal-10d0adfb66d) - 2016/03/08

* [[GitHub] evantahler / actionhero](https://github.com/evantahler/actionhero) - is a multi-transport nodejs API Server with integrated cluster capabilities and delayed tasks

--

* [Hapi : server framework for Node.js](http://spumko.github.io/)

  * [Node.js and Hapi - Creating a REST API | Modulus Blog](http://blog.modulus.io/nodejs-and-hapi-create-rest-api)

  * [hapi – Building apps and services in Node.js | Frederic Hemberger](https://frederic-hemberger.de/talks/hapi/)

  * [Introduction to Node Servers with Hapi.js - Course by @mikefrey | egghead.io](https://egghead.io/series/introduction-to-node-servers-with-hapi-js)

--

* [Express.js](http://expressjs.com/)

  * [Express.js Guide: The Comprehensive Book on Express.js](http://expressjsguide.com/)

  * [[GitHub] strongloop / express](https://github.com/strongloop/express/) - Fast, unopinionated, minimalist web framework for node.

  * [[GitHub] expressjs / multer](https://github.com/expressjs/multer) - Node.js middleware for handling `multipart/form-data`.

    * [ExpressJS File Uploading – GridFS – MongoDB | excellencenodejsblog](http://excellencenodejsblog.com/expressjs-file-uploading-gridfs-mongodb/)

  * [Upload Files to S3 in Node.js | Inspired Programming](http://inspiredjw.com/upload-files-to-s3-in-node-js/)

  * [ExpressJS Creating Custom Middileware | excellencenodejsblog](http://excellencenodejsblog.com/expressjs-creating-custom-middileware/)

  * [Handing CORS For Your Mobile App | excellencenodejsblog](http://excellencenodejsblog.com/handing-cors-for-your-mobile-app/)

* [[GitHub] strongloop / loopback](https://github.com/strongloop/loopback) - is an open source API framework built on top of Express optimized for mobile and web. Connect to multiple data sources, write business logic in Node.js, glue on top of your existing services and data, connect using JS, iOS & Android SDKs.

* Twitatron | Scott Smith

  * [[GitHub] scottksmith95 / twitatron](https://github.com/scottksmith95/twitatron) - Source code for the Twitatron tutorial series

  * [1 - Building a Production Web App With Node](http://scottksmith.com/blog/2014/10/05/twitatron-building-a-production-web-app-with-node/) - 2014/10/05

  * [2 - Building a Production Web App With Node - Views & Controllers](http://scottksmith.com/blog/2015/03/23/twitatron-building-a-production-web-app-with-node-views-and-controllers/) - 2015/03/23

--

* [mean.io](http://mean.io/) - FullStack JS - Development - MEAN - FullStack JS - Development

* [Introduction to the MEAN Stack | Tuts+ Code Tutorial](http://code.tutsplus.com/tutorials/introduction-to-the-mean-stack--cms-19918)

* [MEAN Stack – A Quick Start Guide | Flippin' Awesome](http://flippinawesome.org/2014/04/21/mean-stack-a-quick-start-guide/) - This article is intended to serve as a quick guide to help you get started developing with the MEAN stack. We won’t go into great detail about what each of the technologies are, instead sticking to how to set up a typical MEAN stack.

* [Creating an RSS Feed Reader With the MEAN Stack | Tuts+ Code Tutorial](http://code.tutsplus.com/tutorials/creating-an-rss-feed-reader-with-the-mean-stack--cms-20563)

* [Build a real-time polls application with Node.js, Express, AngularJS, and MongoDB | IBM developerWorks](http://www.ibm.com/developerworks/library/wa-nodejs-polling-app/)


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

* [Raneto](http://raneto.com/) - is an open source Knowledgebase platform that uses static Markdown files to power your Knowledgebase

  * [[GitHub] gilbitron / Raneto](https://github.com/gilbitron/Raneto) - Markdown powered Knowledgebase for Nodejs

* [[GitHub] Requarks / wiki](https://github.com/Requarks/wiki) - A modern, lightweight and powerful wiki app built on NodeJS, Git and Markdown


#### Jogos

* [[GitHub] NetEase / pomelo](https://github.com/NetEase/pomelo) - A fast, scalable, distributed game server framework for Node.js

* [[GitHub] pablodenadai / GameOn](https://github.com/pablodenadai/GameOn) - responsive front-end webapp built on NodeJS and Angular

  * [GameOn](http://gameon.jit.su/) - connects you with the players in your city and allows you to find, organize and share games effortlessly.


### Site Estático

* [Build a static site generator in 40 lines with Node.js | Douglas Matoso](https://medium.com/douglas-matoso-english/build-static-site-generator-nodejs-8969ebe34b22) - 2017/09/14

  * [[GitHub] doug2k1 / nanogen](https://github.com/doug2k1/nanogen/) - Micro static site generator in Node.js

--

* [Boilerplate for static site generation | bdadam](http://bdadam.com/blog/static-site-generation-boilerplate.html) - boilerplate code for generating static websites with node.js, GruntJS and Assembe | [[GitHub] bdadam / static-site-boilerplate](https://github.com/bdadam/static-site-boilerplate)

--

* [[GitHub] segmentio / metalsmith](https://github.com/segmentio/metalsmith) - An extremely simple, pluggable static site generator.

  * [Metalsmith Part 1: Setting Up the Forge | Robin Thrift](http://www.robinthrift.com/posts/metalsmith-part-1-setting-up-the-forge/)

* [Wintersmith](http://wintersmith.io/) - flexible, minimalistic, multi-platform static site generator built on top of Node.js

  * [Wintersmith: Aprendendo outro gerador de conteúdo estático | Tableless](http://tableless.com.br/wintersmith-aprendendo-outro-gerador-de-conteudo-estatico/)

  * [Wintersmith Creating Documentation | Composite Code](http://compositecode.com/2014/02/17/wintersmith-documentation/)

  * [Getting Started with Wintersmith: A Node.js-based Static Site Generator | SitePoint](http://www.sitepoint.com/getting-started-wintersmith-nodejs-static-site-generator/)

* [[GitHub] ktsashes / FruitJS](https://github.com/ktsashes/FruitJS) - A Node.js script for turning your markdown documentation into a fully functional site

  * [A Taste of FruitJS | Flippin' Awesome](http://flippinawesome.org/2013/09/16/a-taste-of-fruitjs/)

--

* [[GitHub] tommy351 / hexo](https://github.com/tommy351/hexo)

  * [Hexo - Node.js blog framework](http://hexo.io/) - A fast, simple & powerful blog framework, powered by Node.js

  * [Migrando de WordPress para Hexo | William Oliveira](http://woliveiras.com.br/posts/Migrando-de-Wordpress-para-Hexo/)

  * [How to Create a Blog with Hexo On Ubuntu 14.04 | DigitalOcean](https://www.digitalocean.com/community/tutorials/how-to-create-a-blog-with-hexo-on-ubuntu-14-04) - 2016/02/04

--

* [[GitHub] bevry / docpad](https://github.com/bevry/docpad)

  * [DocPad - Streamlined Web Development](http://docpad.org/) - build on top of node.js - Empower your website frontends with layouts, meta-data, pre-processors (markdown, jade, coffeescript, etc.), partials, skeletons, file watching, querying, and an amazing plugin system. Use it either standalone, as a build script, or even as a module in a bigger system. Either way, DocPad will streamline your web development process allowing you to craft full-featured websites quicker than ever before.

  * [Primeiros passos com o Docpad | Luiz Felipe Tartarotti Fialho](http://www.felipefialho.com/blog/2013/primeiros-passos-com-o-docpad/)

--

* [Techy](http://krasimir.github.io/techy/)

  * [Look Ma, no CMS! | David Walsh Blog](http://davidwalsh.name/techy)

  * [[GitHub] krasimir / techy](https://github.com/krasimir/techy/) - A flat file CMS based on Gulp and AbsurdJS

  * [Simple Content Management with Node.js and Markdown | Flippin' Awesome](http://flippinawesome.org/2014/05/05/simple-content-management-with-node-js-and-markdown/)

--

* [[GitHub] Crossbow-js / crossbow](https://github.com/Crossbow-js/crossbow) - Static Site Generator API - built for speed & extensibility

--

* [CMS.js](https://cdmedia.github.io/cms.js/) - Javascript CMS

  * [[GitHub] cdmedia / cms.js](https://github.com/cdmedia/cms.js) - The Javascript Site Generator

* [[GitHub] netlify / netlify-cms](https://github.com/netlify/netlify-cms) - A CMS for Static Site Generators

  * [Using Preact with Storybook 3 | Netlify](view-source:https://www.netlify.com/blog/2018/01/17/using-preact-with-storybook-3/) - (2018/01/17) Storybook is built for React, so if you're using Preact you'll need to do a bit of configuration to get it going. This tutorial will help you get up and running with Storybook 3 and Preact

--

* [[GitHub] gatsbyjs / gatsby](https://github.com/gatsbyjs/gatsby) - Transform plain text into dynamic blogs and websites using React.js

--

* [[GitHub] sintaxi / harp](https://github.com/sintaxi/harp) - Static Site Server/Generator with built-in preprocessing

  * [Introduction to the Harp Web Server | Introductory Screencast - Harp](http://harpjs.com/blog/introductory-screencast)


### Hardware

* [[GitHub] octalmage / robotjs](https://github.com/octalmage/robotjs) - Node.js Desktop Automation.

* [[GitHub] sandeepmistry / bleno](https://github.com/sandeepmistry/bleno) - A node.js module for implementing BLE (Bluetooth low energy) peripherals

* [Cylon.js](http://cylonjs.com/) - is a JavaScript framework for robotics, physical computing, and the Internet of Things using Node.js. It provides a simple, yet powerful way to create JavaScript robots that incorporate multiple, different hardware devices at the same time

* [An Introduction to NodeBots | SitePoint](http://www.sitepoint.com/an-introduction-to-nodebots/) - 2015/07/20

* [JerryScript](https://samsung.github.io/jerryscript/) - is the lightweight JavaScript engine intended to run on a very constrained devices such as microcontrollers

  * [[GitHub] Samsung / jerryscript](https://github.com/Samsung/jerryscript)


#### Mobile: iOS, Android, Windows Phone

* [NativeScript](https://www.nativescript.org/) - Cross-Platform Native Development with Javascript. Build truly native apps with JavaScript. Develop iOS, Android and Windows Phone apps from a single code base.

  * [[GitHub Org] NativeScript](https://github.com/NativeScript)

  * [Building Your Own NativeScript Modules for npm | Telerik Developer Network](http://developer.telerik.com/featured/building-your-own-nativescript-modules-for-npm/)


#### Node Copter

* [The NodeCopter](http://nodecopter.com/) - Programming flying robots with node.js


#### Lego Mindstorms

* [Hacking Lego Mindstorms EV3 with JavaScript](http://andrew.ghost.io/hacking-lego-mindstorms-ev3-with-javascript/)


#### Tessel

* [Tessel](http://technical.io/) - JavaScript right on the hardware

* [Tessel - Dragon Innovation](http://www.dragoninnovation.com/projects/22-tessel) - Technical Machine - hardware module that speak javascript - totally amazing

* [[YouTube] Tessel Preview: Pushing code, servos, and UDP](https://www.youtube.com/watch?v=XCwKzipBIaA)

* [[SlideShare] Tessel: The End of Web Development (as we know it)](http://www.slideshare.net/TechnicalMachine/tessel-the-end-of-web-development-as-we-know-it)

--

* [Tessel Powered Plant Watering System | Max Ogden Blogotronz](http://maxogden.com/tessel-powered-plant-watering-system.html) - Make a water pump that can be turned on and off over HTTP using only JavaScript.


#### Espruino

* [Espruino](http://www.espruino.com/) - A JavaScript interpreter for Microcontrollers

* [Espruino quer usar Javascript para controlar sua casa | Info](http://info.abril.com.br/noticias/blogs/zonalivre/hardware/espruino-quer-usar-javascript-para-controlar-sua-casa/)


#### Arduino

* [NodeBots](http://nodebots.io/) - The Rise of JS Robotics

* [[GitHub] ecto / duino](https://github.com/ecto/duino) - Arduino framework for node.js

* [Noduino](http://semu.github.io/noduino/) - Control Arduino with Node.js, WebSockets and HTML5

* [Arduino and NodeJS Communication With Serial Ports | Danial Khosravi's Blog](http://danialk.github.io/blog/2014/04/12/arduino-and-nodejs-communication-with-serial-ports/)

* [[GitHub] rwaldron / johnny-five](https://github.com/rwaldron/johnny-five) - JavaScript Robotics and IoT programming framework, developed at Bocoup. Based on Arduino Firmata Protocol

  * [How to Program an Arduino with JavaScript | Stack Abuse](http://stackabuse.com/how-to-program-an-arduino-with-javascript/) - 2015/09/23


#### RaspberryPi

* [Build your own Google TV Using RaspberryPi, NodeJS and Socket.io | Donald's Blog](http://blog.donaldderek.com/2013/06/build-your-own-google-tv-using-raspberrypi-nodejs-and-socket-io/)

* [Home Automation with AngularJS and node.js on a Raspberry Pi | codecentric Blogcodecentric Blog](https://blog.codecentric.de/en/2013/03/home-automation-with-angularjs-and-node-js-on-a-raspberry-pi/)

* [heimcontrol.js](http://ni-c.github.io/heimcontrol.js/) - Awesome home automation with Raspberry PI and Arduino using Node.js, MongoDB, HTML5 and Websockets

* [[GitHub] GladysProject / Gladys](https://github.com/GladysProject/Gladys) - Your home automation assistant built with Node.js and AngularJS

* [[GitHub] googlecreativelab / coder](https://github.com/googlecreativelab/coder) - A simple way to make web stuff on Raspberry Pi

  * [Coder Projects](http://googlecreativelab.github.io/coder-projects/)

  * [Running Google Coder On Your Existing Raspberry Pi Or Desktop PC | Gadgetoid](http://pi.gadgetoid.com/article/running-google-coder-on-your-existing-raspberry-pi-or-desktop-pc)

  * [Coder: seu mini-servidor web pessoal | iMasters](http://imasters.com.br/gerencia-de-ti/tendencias/coder-seu-mini-servidor-web-pessoal/)


## Abstract Syntax Tree

* [Abstract Syntax Tree | wikipedia](https://en.wikipedia.org/wiki/Abstract_syntax_tree)

* [Working with JavaScript AST | redradix](http://blog.redradix.com/working-with-javascript-ast/) - 2015/08/14

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

* [[GitHub] RReverser / estemplate](https://github.com/RReverser/estemplate) - Proper (AST-based) JavaScript code templating with source maps support


## Dicas

* [10 Habits of a Happy Node Hacker | Heroku](https://blog.heroku.com/archives/2014/3/11/node-habits)

* [NodeCloud](http://www.nodecloud.org/) - Node.js resources directory

--

* [[GitHub] zeit / pkg](https://github.com/zeit/pkg) - Package your Node.js project into an executable

  * [Standalone Express API Binaries with pkg | The Code Barbarian](http://thecodebarbarian.com/standalone-express-apis-binaries-with-pkg.html) - 2017/05/03

--

* [Managing Node.js Virtual Environments with Nave](http://forge.zeunic.com/development/2013/managing-node-js-virtual-environments-with-nave)

* [[GitHub] keremc / nodevers](https://github.com/keremc/nodevers) - a Node.js version manager

* [[GitHub] flesler / config-node](https://github.com/flesler/config-node) - Flexible lightweight configuration loader for Node

* [[GitHub] dpup / node-flags](https://github.com/dpup/node-flags) - Flag handling library for node.js

--

* [Writing Node.js Addons | Tuts+ Code Tutorial](http://code.tutsplus.com/tutorials/writing-nodejs-addons--cms-21771)

* [Shared memory with node.js | Varuna Jayasiri](http://blog.varunajayasiri.com/shared-memory-with-nodejs) - This is more like a tutorial on writing a simple node.js add-on to share memory among node.js processes. One of the limitations of node.js/io.js is that they are single threaded.

--

* [[GitHub] motdotla / dotenv](https://github.com/motdotla/dotenv) - Loads environment variables from .env for nodejs projects.

  * [Here’s how you can actually use Node environment variables | freeCodeCamp](https://medium.freecodecamp.org/heres-how-you-can-actually-use-node-environment-variables-8fdf98f53a0a) - 2018/03/08

--

* [How to Implement Node + React Isomorphic JavaScript & Why it Matters | StrongLoop](https://strongloop.com/strongblog/node-js-react-isomorphic-javascript-why-it-matters/)

--

* [Atualizando o NodeJS no Linux | Igor Costa](http://www.igorcosta.com/atualizando-o-nodejs-linux/)

--

* [Setting up a JavaScript / Node.js development environment](http://learnjs.io/blog/2014/01/22/js-development-environment/)

* [An Introduction To Full-Stack JavaScript | Smashing Coding](http://coding.smashingmagazine.com/2013/11/21/introduction-to-full-stack-javascript)

--

* [Node.js processando em paralelo | iMasters](http://imasters.com.br/desenvolvimento/node-js-processando-em-paralelo/)

--

* [Node.js: managing child processes | Tech Pro](http://tech.pro/tutorial/2074/nodejs-managing-child-processes)

--

* [Creating a Single Page Todo App with Node and Angular | Scotch](http://scotch.io/tutorials/javascript/creating-a-single-page-todo-app-with-node-and-angular)

--

* [[GitHub] wilmoore / selectn](https://github.com/wilmoore/selectn) - Resolves deeply-nested object properties via dot or bracket-notation for Node.js and the browser

--

* [Real-time Engines in Node.js | StrongLoop](http://strongloop.com/strongblog/real-time-engines-in-node-js/)

--

* [Tracking down a memory leak in Node.js and Socket.IO](http://jpallen.net/2013/03/08/tracking-down-a-memory-leak-in-node-js-and-socket-io/)

* [Tools and Strategies for node.js Development on GitHub | Chris Wren](http://chrisawren.com/posts/Tools-and-Strategies-for-node-js-Development-on-GitHub)

* [Scaling Node.js Applications](http://cjihrig.com/blog/scaling-node-js-applications/)

--

* [Blazing fast node.js: 10 performance tips from LinkedIn Mobile](http://engineering.linkedin.com/nodejs/blazing-fast-nodejs-10-performance-tips-linkedin-mobile)

* [Node.js in Flames | Netflix](http://techblog.netflix.com/2014/11/nodejs-in-flames.html) - 2014/11/19 : We’ve been busy building our next-generation Netflix.com web application using Node.js

--

* [Testing Tuesday #20: Continuous Deployment for node.js applications | CodeShip Blog](http://blog.codeship.io/2013/08/27/testing-tuesday-20-continuous-deployment-for-node-js-applications.html)

* [Nodejs Deployment: Building and Configuring on Amazon Linux AMI | Asaf Shakarchi](http://asaf.github.io/blog/2013/07/10/nodejs-deployment-building-and-configuring-on-amazon-linux-ami/)

* [Continuous Deployment With Github](http://codesquire.com/post/ContinuousDeployment) - github + nodejs (+ gith) + VPS

* [[GitHub] danheberden / gith](https://github.com/danheberden/gith) - simple node server that responds to github post-receive events with meaningful data

--

* [[GitHub] marcells / node-build-monitor](https://github.com/marcells/node-build-monitor) - A Build Monitor written in Node.js, which supports several build services and can be easily extended

--

* [[GitHub] yyx990803 / pod](https://github.com/yyx990803/pod) - Git push deploy for Node.js

--

* [[GitHub] mikefrey / node-pac](https://github.com/mikefrey/node-pac) - pack your node_modules as `*.tgz` files for version control and easy deploys (not tested on Windows yeat)

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

* [[GitHub] pgte / simple-redis-safe-work-queue](https://github.com/pgte/simple-redis-safe-work-queue) - Node.js Redis-based simple and safe work queue

--

* [[GitHub] eviltik / evilscan](https://github.com/eviltik/evilscan) - Massive ip/ports scanner (nodejs)

* [[GitHub] caio-ribeiro-pereira / gzipme](https://github.com/caio-ribeiro-pereira/gzipme) - A simple way to gzip your files with Node.js

* [[GitHub] ctalkington / node-archiver](https://github.com/ctalkington/node-archiver) - Creates Archives (Zip, Tar) via Node Streams

* [[GitHub] antelle / node-stream-zip](https://github.com/antelle/node-stream-zip) - node.js library for fast reading of large ZIPs

* [Loading PDFs In PhantomJS Using PDF.JS | Gary Sieling](http://www.garysieling.com/blog/integrating-phantomjs-and-pdf-js-inter-process-communication)

* [Como adicionar marca d'água com Node.js e ffmpeg | Nomadev](http://nomadev.com.br/como-adicionar-marca-d%C3%A1gua-com-node-js-e-ffmpeg/)

* [[GitHub] netroy / image-size](https://github.com/netroy/image-size) - NodeJS module for detecting image dimensions

* [[GitHub] lovell / sharp](https://github.com/lovell/sharp) - High performance Node.js image processing, the fastest module to resize JPEG, PNG, WebP and TIFF images. Uses the libvips library.

--

* [[GitHub] posthtml / posthtml](https://github.com/posthtml/posthtml) - is a tool to transform HTML/XML with JS plugins.

--

* [[GitHub] open-xml-templating / docxtemplater](https://github.com/open-xml-templating/docxtemplater) - Generate docx and pptx (microsoft word documents) from templates, from Node.js, the Browser and the command line

* [[GitHub] Leonidas-from-XIV / node-xml2js](https://github.com/Leonidas-from-XIV/node-xml2js) - XML to JavaScript object converter

* [[GitHub] tuananh / camaro](https://github.com/tuananh/camaro) - is an utility to transform XML to JSON, using Node.js binding to native XML parser pugixml, one of the fastest XML parser around.

* [Convert CSV to JSON in JavaScript | TechSlides](http://techslides.com/convert-csv-to-json-in-javascript)

* [Parsing CSV Files With NodeJS | James Carr](http://blog.james-carr.org/2010/07/07/parsing-csv-files-with-nodejs/)

* [[GitHub] gkindel / CSV-JS](https://github.com/gkindel/CSV-JS) - A Comma-Separated Values parser for JavaScript. Standards-based, stand alone, and no regular expressions

* [[GitHub] knrz / CSV.js](https://github.com/knrz/CSV.js) - A simple, blazing-fast CSV parser and encoder. Full RFC 4180 compliance

* [[GitHub] mholt / PapaParse](https://github.com/mholt/PapaParse) - Fast and powerful CSV (delimited text) parser that gracefully handles large files and malformed input

* [[GitHub] nickpisacane / CsvBuilder](https://github.com/nickpisacane/CsvBuilder) - Easily encode complex JSON objects to CSV with CsvBuilder's schema-like API

* [[GitHub] C2FO / fast-csv](https://github.com/C2FO/fast-csv) - CSV parser for node

  * [[YouTube] Fast-CSV - processando CSVs com JS para quem está com pressa | DevPleno](https://www.youtube.com/watch?v=zVlm_zUfitE) - 2017/10/04

* [[GitHub] mgcrea / node-xlsx](https://github.com/mgcrea/node-xlsx) - Node.js excel parser & builder

* [[GitHub] SheetJS / js-xlsx](https://github.com/SheetJS/js-xlsx) - XLSX / XLSM / XLSB / XLS / SpreadsheetML (Excel Spreadsheet) / ODS parser and writer

* [[GitHub] jlord / sheetdown](https://github.com/jlord/sheetdown) - Convert a Google Spreadsheet into a table in Markdown

  * [Introducing Sheetdown | Source](https://source.opennews.org/en-US/articles/introducing-sheetdown/)

--

* [Processing a large dataset in less than 100 lines of Node.js with async.queue | Node.js Collection - Medium](https://medium.com/the-node-js-collection/processing-a-large-dataset-in-less-than-100-lines-of-node-js-with-async-queue-9766a78fa088) - 2017/06/12

--

* [[GitHub] substack / node-resolve](https://github.com/substack/node-resolve) - Implements the node.js require.resolve() algorithm

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

  * [A Jade Tutorial for Beginners | SitePoint](http://www.sitepoint.com/jade-tutorial-for-beginners/) - 2016/02/17

--

* [[GitHub] fdaciuk / hmh](https://github.com/fdaciuk/hmh) - How many hours? Calculate hours, using time spaces.

* [[GitHub] fdaciuk / hmh-cli](https://github.com/fdaciuk/hmh-cli) - How many hours? Calculate hours, using time spaces on terminal.

--

* [Node e TypeScript | Medium - by @programadriano](https://medium.com/@programadriano/node-e-typescript-f632deabe356) - 2017/07/17


### Streams

* [[YouTube] Nodebp April 2014: The History of Node.js Streams](https://www.youtube.com/watch?v=g5ewQEuXjsQ)

* [Practical Examples of the New Node.js Streams API | StrongLoop](http://blog.strongloop.com/practical-examples-of-the-new-node-js-streams-api/)

* [Introduction to Node.js Streams | SitePoint](http://www.sitepoint.com/introduction-to-streams/)

* [Intro to Node streams | tagtree.tv](http://tagtree.tv/intro-to-node-streams)

* [Basic use of Node.js streams | CodeWinds](http://codewinds.com/blog/2013-08-02-streams-basics.html)

* [Node.js Stream Playground | John Resig](http://ejohn.org/blog/node-js-stream-playground/)

* [Node.js Transform Streams vs. Through2 Streams | Ben Nadel](http://www.bennadel.com/blog/2663-node-js-transform-streams-vs-through2-streams.htm)

* [How to create transform streams for manipulating data with Node.js | CodeWinds](http://codewinds.com/blog/2013-08-20-nodejs-transform-streams.html) - a programming tutorial for web developers

* [[YouTube] Streams - FunFunFunction #13](https://www.youtube.com/watch?v=UD2dZw9iHCc) - 2016/01/03

--

* [NodeJS - parsing and transforming large XML documents | La Gentz Blog](http://blog.lagentz.com/nodejs/nodejs-parsing-and-transforming-large-xml-documents/)

* [Parse data files using Node.js streams | Nicolas Hery](http://nicolashery.com/parse-data-files-using-nodejs-streams/)

--

* [[GitHub] substack / stream-handbook](https://github.com/substack/stream-handbook) - how to write node programs with streams

* [[GitHub] substack / stream-adventure](https://github.com/substack/stream-adventure) - go on an educational stream adventure!

* [[GitHub] caolan / highland](https://github.com/caolan/highland) - The high-level streams library for Node.js and the browser

* [[GitHub] maxogden / eol-stream](https://github.com/maxogden/eol-stream) - detect which type of EOL (AKA line-ending, newline) characters are in a stream

* [[GitHub] Obvious / sculpt](https://github.com/Obvious/sculpt) - Manipulate streams

* [[GitHub] Medium / pipette](https://github.com/Medium/pipette) - Stream and pipe utilities for Node

* [[GitHub] adlawson / urine.js](https://github.com/adlawson/urine.js) - This library provides a simple CLI and a JavaScript API for sampling data from a stream or file for testing or limiting data consumption.

--

* [[GitHub] wearefractal / vinyl-fs](https://github.com/wearefractal/vinyl-fs) - Vinyl adapter for the file system

* [[GitHub] rvagg / through2](https://github.com/rvagg/through2) - Tiny wrapper around Node streams2 Transform to avoid explicit subclassing noise



### portable code

* [[Gist] Tips for Writing Portable Node.js Code](https://gist.github.com/domenic/2790533)

* [Windows and Node: Writing Portable Code | DailyJS](http://dailyjs.com/2012/05/24/windows-and-node-4/)

* [How to Write Portable Node.js Code | Node on Azure](http://nodeblog.azurewebsites.net/how-to-write-portable-nodejs-code)

* [Writing cross-platform Node.js | Shape Shed](http://shapeshed.com/writing-cross-platform-node/) - a major strength of Node.js is great cross-platform support. With a little effort you can make sure your code will run on Windows, Linux and OSX.


### fake data

* [MockBin](http://mockbin.com/) - allows you to generate custom endpoints to test, mock, and track HTTP requests & responses between libraries, sockets and APIs.

* [Testing Private State and Mocking Dependencies | How To Node - NodeJS](http://howtonode.org/testing-private-state-and-mocking-deps)

* [[GitHub] Marak / Faker.js](https://github.com/marak/Faker.js) - Generate fake data in the browser and Node.js with FakerJS

* [[GitHub] boo1ean / casual](https://github.com/boo1ean/casual) - Fake data generator for javascript

* [[GitHub] infrared5 / madmin](https://github.com/infrared5/madmin) - admin console for generating mock services with RESTful URIs

* [[GitHub] bustardcelly / caddis](https://github.com/bustardcelly/caddis) - On-The-Fly Mock JSON Server

* [[GitHub] basicallydan / interfake](https://github.com/basicallydan/interfake) - Quickly create fake APIs for use in client-only tests or prototypes

* [[GitHug] adleroliveira / dreamjs](https://github.com/adleroliveira/dreamjs) - A lightweight json data generator.

* [[GitHub] dreyacosta / JSONServer](https://github.com/dreyacosta/JSONServer) - Small JSON file server for REST API mock


### command and shell

* [Building command line tools with Node.js | Atlassian Developers](https://developer.atlassian.com/blog/2015/11/scripting-with-node/) - 2015/11/17

* [Node.js as a build script | Blog - Miller Medeiros](http://blog.millermedeiros.com/node-js-as-a-build-script/)

* [Write your shell scripts in JavaScript, via Node.js | 2 ality](http://www.2ality.com/2011/12/nodejs-shell-scripting.html)

* [[GitHub] arturadib / shelljs](https://github.com/arturadib/shelljs) - Portable Unix shell commands for Node.js

* [[GitHub] typicode / shoutjs](https://github.com/typicode/shoutjs) - Make your ShellJS commands explicit and get a beautiful output

* [[GitHub] dthree / cash](https://github.com/dthree/cash) - Cross-platform Linux without the suck

--

* [[GitHub] gribnoysup / wunderbar](https://github.com/gribnoysup/wunderbar) - Simple horizontal bar chart printer for your terminal

--

* [[GitHub] Cron for NodeJS](https://github.com/ncb000gt/node-cron)

* [[GitHub] shell-jobs: Cron replacement in NodeJS, made for humans](https://github.com/azer/shell-jobs)

* [[GitHub] node-schedule / node-schedule](https://github.com/node-schedule/node-schedule) - A cron-like and not-cron-like job scheduler for Node

* [[GitHub] rschmukler / agenda](https://github.com/rschmukler/agenda) - Lightweight job scheduling for node (uses [mongodb](https://www.mongodb.org/) to store jobs)

  * [[GitHub] moudy / agenda-ui](https://github.com/moudy/agenda-ui) - A UI to view Agenda jobs

--

* [Build Custom Shells with Node Shotgun | Code Tunnel](http://codetunnel.com/blog/post/build-custom-shells-with-node-shotgun)

* [[GitHub] pstadler / flightplan](https://github.com/pstadler/flightplan) - Node.js library for streamlining application deployment or systems administration tasks.

--

* [[GitHub] nathanpeck / clui](https://github.com/nathanpeck/clui) - Command Line UI toolkit for Node.js

--

* [Building a simple command line tool with npm | The npm Blog](http://blog.npmjs.org/post/118810260230/building-a-simple-command-line-tool-with-npm)

* [How to Write a Command Line Application in Node.js | Liang Zan](http://blog.liangzan.net/blog/2012/07/30/how-to-write-a-command-line-application-in-node-dot-js/)

* [Command-line utilities with Node.js | cruft.io](http://cruft.io/posts/node-command-line-utilities/) - An overview of command-line interfaces and using node.js to create command-line utilities

* [Criando uma ferramenta de CLI com NodeJS | Da2k Blog](http://blog.da2k.com.br/2015/03/20/criando-uma-ferramenta-de-cli-com-nodejs/)

* [Construindo ferramentas de linha de comando com node.js | @millermedeiros / Abril 2015](http://slides.millermedeiros.com/nodebr/cli/) - Dicas de como estruturar ferramentas de linha de comando, facilitando a manutenção e aumentando a flexibilidade dos programas. Introdução básica sobre princípios de design do UNIX, principalmente sobre modularidade, composição e boas práticas.

* [Simple build tools: npm scripts vs Makefile vs runjs | @hackernoon](https://hackernoon.com/simple-build-tools-npm-scripts-vs-makefile-vs-runjs-31e578278162) - 2016/10/03

* [How to Use npm Scripts as Your Build Tool - Course by @elijahmanor | @eggheadio](https://egghead.io/courses/how-to-use-npm-scripts-as-your-build-tool)

--

* [[GitHug] SamVerschueren / listr](https://github.com/SamVerschueren/listr) - Terminal task list

--

* [[GitHub] ruyadorno / ipt](https://github.com/ruyadorno/ipt) - Interactive Pipe To: The missing cli interactive workflow

* [[GitHub] stephanepericat / cmdl](https://github.com/stephanepericat/cmdl) - A simple, yet powerful command-line interface builder

* [[GitHub] tj / commander.js](https://github.com/tj/commander.js) - node.js command-line interfaces made easy

  * [commander.js - nodejs command-line interfaces made easy | TJ Holowaychuk](http://tjholowaychuk.tumblr.com/post/9103188408/commander-js-nodejs-command-line-interfaces-made)

* [[GitHub] SBoudrias / Inquirer.js](https://github.com/SBoudrias/Inquirer.js) - A collection of common interactive command line user interfaces

* [[GitHub] f / omelette](https://github.com/f/omelette) - Omelette.js Simple Autocompletion Helper for Node

--

* [[GitHub] bucaran / parsec](https://github.com/bucaran/parsec) - is a lovingly crafted command line options parser using ES6 generators in around 100 LOC.

* [[GitHub] yargs / yargs](https://github.com/yargs/yargs) - yargs the modern, pirate-themed successor to optimist.

* [[GitHub] lukeed / mri](https://github.com/lukeed/mri) - Quickly scan for CLI flags and arguments

--

* [[GitHub] sindresorhus / speed-test](https://github.com/sindresorhus/speed-test) - Test your internet connection speed and ping using speedtest.net from the CLI

* [[GitHub] sindresorhus / wallpaper](https://github.com/sindresorhus/wallpaper) - Get or set the desktop wallpaper

  * [[GitHub] sindresorhus / node-osx-wallpaper](https://github.com/sindresorhus/node-osx-wallpaper) - Get or set the desktop wallpaper on OS X

  * [[GitHub] sindresorhus / linux-wallpaper](https://github.com/sindresorhus/linux-wallpaper) - Get or set the desktop wallpaper on Linux

  * [[GitHub] sindresorhus / win-wallpaper](https://github.com/sindresorhus/win-wallpaper) - Get or set the desktop wallpaper on Windows

--

* [[GitHub] node-modules / detect-port](https://github.com/node-modules/detect-port) - JavaScript Implementation of Port Detector

--

* [[GitHub] theuves / dicio](https://github.com/theuves/dicio) - Dicionário de Português via Linha de Comando

--

* [[GitHub] cronvel / terminal-kit](https://github.com/cronvel/terminal-kit) - Terminal utilities for node.js

* [[GitHub] chjj / term.js](https://github.com/chjj/term.js) - A terminal written in javascript.

  * [Docker + term.js  = Bash Fiddle | Thinapps  blog](https://thinapps.org/blog/post/128030184289/docker-termjs-bash-fiddle)

* [[GitHub] Kikobeats / oh-my-terminal](https://github.com/Kikobeats/oh-my-terminal) - Simple and unmistakable terminal interface for NodeJS

* [[GitHub] mudasobwa / TermColorBuilder](https://github.com/mudasobwa/TermColorBuilder) - Webpage to quickly generate terminal escape sentenses in human-like manner


### process manager

* [Node.js process load balance performance: comparing cluster module, iptables and Nginx | Medium by @fermads](https://medium.com/@fermads/node-js-process-load-balancing-comparing-cluster-iptables-and-nginx-6746aaf38272) - 2016/05/05

--

* [[GitHub] sindresorhus / fkill-cli](https://github.com/sindresorhus/fkill-cli) - Fabulously kill processes. Cross-platform.

* [[GitHub] flipace / whoport](https://github.com/flipace/whoport) - A simple CLI tool to check if and which PID uses a given port number and optionally kill it.

* [[GitHub] zzarcon / psaux](https://github.com/zzarcon/psaux) - Process status in Node.js as you've always wanted

* [[GitHub] sindresorhus / exit-hook](https://github.com/sindresorhus/exit-hook) - Run some code when the process exits

* [Topic: Automatically restart your node.js server after code updates | StrongLoop](http://strongloop.com/node-republic-topics/automatically-restart-your-node-js-server-after-code-updates/)

* [Comparison: Tools to Automate Restarting Node.js Server After Code Changes | StrongLoop](http://strongloop.com/strongblog/comparison-tools-to-automate-restarting-node-js-server-after-code-changes-forever-nodemon-nodesupervisor-nodedev/)

* [[GitHub] mafintosh / respawn](https://github.com/mafintosh/respawn) - Spawn a process and restart it if it crashes

* [[GitHub] oOthkOo / supervizer](https://github.com/oOthkOo/supervizer) - NodeJS fancy process manager

* [[GitHub] Unitech / pm2](https://github.com/Unitech/pm2) - CLI process manager for Node.js with native clusterization

  * [Launching Production Node Apps With PM2 | DailyDrip](https://www.dailydrip.com/blog/launching-production-node-apps-with-pm2.html) - 2017/07/04

  * [PM2 – mantendo o node.js no ar | iMasters](http://imasters.com.br/front-end/javascript/pm2-mantendo-o-node-js-no-ar/)

  * [Goodbye node-forever, hello PM2 | devo.ps](http://devo.ps/blog/goodbye-node-forever-hello-pm2/)

  * [Manage processes programmatically with PM2 | Keymetrics APM](http://getkeymetrics.com/2014/07/02/manage-processes-programmatically-with-pm2/)

  * [Node.js: production management with PM2 | nicolasramz](http://www.warpdesign.fr/node-js-production-management-with-pm2/)

  * [[GitHub] Unitech / pm2-interface](https://github.com/Unitech/pm2-interface/) - Control pm2 via RPC and receive real time notifications

    * [pm2-interface: #1 Build your own logger | keymetrics.io](http://keymetrics.io/2014/07/10/pm2-interface-1-build-your-own-logger/)


### Produção

* [Production Node.js Secrets](http://dshaw.github.com/2012-05-jsday/)

* [Running Node.js apps in production | Frederic Hemberger](http://fhemberger.github.io/talks/nodejs-in-production/)

  * [Resources: Running Node.js apps in production](https://github.com/fhemberger/talks/tree/master/nodejs-in-production)

* Hardening Node.js for production [part 1](http://blog.argteam.com/coding/hardening-nodejs-production-process-supervisor/) | [part 2](http://blog.argteam.com/coding/hardening-node-js-for-production-part-2-using-nginx-to-avoid-node-js-load/) | [part 3](http://blog.argteam.com/coding/hardening-node-js-for-production-part-3-zero-downtime-deployments-with-nginx/)

* [Check out our new nodejs dev & production practices library for details on designing, deploying & debugging Node.js | Joyent](https://www.joyent.com/developers/node)

* [Como configurar um servidor node.js para produção | morethings.io](http://morethings.io/javascript/node/como-configurar-um-servidor-nodejs-para-producao/)

* [Using Node.js in Production | Flippin' Awesome](http://flippinawesome.org/2014/06/23/using-node-js-in-production/)

* [Operating Node.js in Production | RisingStack Engineering](http://blog.risingstack.com/operating-node-in-production/)

--

* [Scaling Node.js Applications | Colin J. Ihrig's Blog](http://cjihrig.com/blog/scaling-node-js-applications/)


### REST

* [Full HTTPS REST server in Node.js | Bogomil Shopov](http://talkweb.eu/full-https-rest-server-in-node-js/)

* [[GitHub] imrefazekas / connect-rest](https://github.com/imrefazekas/connect-rest) - Exceptionally featureful Restful web services middleware for connect node.js

* [[GitHub] mcavage / node-restify](https://github.com/mcavage/node-restify) - node.js REST framework specifically meant for web service APIs

  * [Day 27: Restify - Build Correct REST Web Services in Node.js | OpenShift by Red Hat](https://www.openshift.com/blogs/day-27-restify-build-correct-rest-web-services-in-nodejs)

* [[GitHub] Mashape / unirest-nodejs](https://github.com/mashape/unirest-nodejs) - Node.js Unirest library built on-top of request and modeled after superagent.

* [Developing a RESTful API With Node and TypeScript | Michael Herman](http://mherman.org/blog/2016/11/05/developing-a-restful-api-with-node-and-typescript/) - 2016/11/05

  * [[GitHub] mjhea0 / typescript-node-api](https://github.com/mjhea0/typescript-node-api)


### Authentication

* [Express.js Basic Authentication with Encryption | Nodewiz.biz](http://www.nodewiz.biz/expressjs-basic-authentication/)

* [Easy Node Authentication: Setup and Local | Scotch](http://scotch.io/tutorials/javascript/easy-node-authentication-setup-and-local)

* [Authenticate a Node.js API with JSON Web Tokens | Scotch](https://scotch.io/tutorials/authenticate-a-node-js-api-with-json-web-tokens)

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


### url rewrite proxy

* [[GitHub] tinganho / connect-modrewrite](https://github.com/tinganho/connect-modrewrite) - Adds modrewrite functionality to your connect/express server

* [[GitHub] viart / grunt-connect-rewrite](https://github.com/viart/grunt-connect-rewrite) - Provides RewriteRules middleware for the grunt connect / express.

* [[GitHub] drewzboto / grunt-connect-proxy](https://github.com/drewzboto/grunt-connect-proxy) - Provides a http proxy as middleware for the grunt-contrib-connect plugin. With rewrite options.


### Módulo

* [How to Make Simple Node.js Modules Work in the Browser | Richard Rodger](http://www.richardrodger.com/2013/09/27/how-to-make-simple-node-js-modules-work-in-the-browser/)

* [How to create a NodeJS NPM package | Anup Shinde](http://www.anupshinde.com/posts/how-to-create-nodejs-npm-package/) - See how to create a simple NodeJS NPM package. We'll first create a simple program, add some node_modules  to it and walk through the process of creating a NPM package, publishing it and upgrading it. We'll also walk through see some common issues that you might face for the first time.

* [Adding dependencies and data to Node-NPM package | Anup Shinde](http://www.anupshinde.com/posts/adding-dependencies-data-nodejs-npm-package/) - In the first part we created a package with no dependencies. In this part, we'll add some dependencies to our program and package. We'll also look at some additional tips that you may require when creating your first NPM package.

* [NPM Node Package Manager | Underground WebDev](http://udgwebdev.com/npm-node-package-manager/)

* [[Vimeo] Eric Elliott - Modular JavaScript With npm and Node Modules](http://vimeo.com/89258863) - An introductory look at programming with Node style modules

* [[GitHub] ericdouglas / rooted](https://github.com/ericdouglas/rooted) - Requiring modules/folders/files in the right way

* [Writing Native Node.js Modules - Node.js at Scale | @RisingStack](https://blog.risingstack.com/writing-native-node-js-modules/) - (2016/11/28) This article explains how native Node.js modules work, and how you can use them to increase the performance of your application.

* [Writing a Node.js module in TypeScript | The Practical Dev](https://dev.to/dkundel/writing-a-nodejs-module-in-typescript) - (2017/07/21) Learn how to write a module using TypeScript that can be consumed with both JavaScript and TypeScript in Node.js or the browser.

* [Using ES modules natively in Node.js | 2ality](http://2ality.com/2017/09/native-esm-node.html) - (2017/09/12) Starting with version 8.5.0, Node.js supports ES modules natively, behind a command line option.


### NPM

* [[GitHub] sindresorhus / awesome-npm](https://github.com/sindresorhus/awesome-npm) - Awesome npm resources and tips

* [[GitHub] parro-it / canibekikked](https://github.com/parro-it/canibekikked) - Tool to check if any of your NPM repositories name are trademarked

--

* [Fixing npm permissions | NPM Getting Started](https://docs.npmjs.com/getting-started/fixing-npm-permissions)

> Mac OS X

```bash
$ cd ~/
$ sudo chown -R `whoami` .npm
```

```bash
# add on the bash_profile

alias npmplease="rm -rf node_modules/ && rm -f package-lock.json && npm install"
```

--

* [Meet The Face Behind NPM | Modulus Blog](http://blog.modulus.io/isaac-interview)

--

* [Keeping The npm Registry Awesome | Nodejs Blog](http://blog.nodejs.org/2013/11/26/npm-post-mortem/) - 26/11/2013

--

* [npx | npm](https://www.npmjs.com/package/npx)

  * [Introducing npx: an npm package runner | Kat Marchán – Medium](https://medium.com/@maybekatz/introducing-npx-an-npm-package-runner-55f7d4bd282b) - 2017/07/11

--

* [npm: how-to-npm](https://www.npmjs.com/package/how-to-npm) - A module to teach you how to module

* [[GitHub] opreaadrian / packo](https://github.com/opreaadrian/packo) - node module (npm module) CLI generator

--

* [How to create a private npm.js repository | Clock Blog](http://clock.co.uk/tech-blogs/how-to-create-a-private-npmjs-repository)

* [A private NPM cache | Yammer Engineering](http://eng.yammer.com/a-private-npm-cache/)

* [Setting up NPM registries | Medium](https://medium.com/javascript-and-the-server/setting-up-npm-registries-2d6b45eb12ed)

* [npmjs.eu - European npm mirror](http://npmjs.eu/)

  * [Using the European npm mirror | Shape Shed](http://shapeshed.com/using-the-european-npm-mirror/)

* [[GitHub] mixu / npm_lazy](https://github.com/mixu/npm_lazy) - A lazy local cache for NPM to make your local deploys faster

* [[GitHub] cnpm / cnpmjs.org](https://github.com/cnpm/cnpmjs.org) - Private npm registry and web for Enterprise, base on MySQL and Simple Store Service

  * [[GitHub] cnpm / cnpm](https://github.com/cnpm/cnpm) - cnpm: npm client for cnpmjs.org

--

* [[GitHub] georgy / nexus-npm-repository-plugin](https://github.com/georgy/nexus-npm-repository-plugin) - Sonatype Nexus OSS plugin for npm (https://www.npmjs.org) repository suport

--

* [[GitHub] inikulin / dmn](https://github.com/inikulin/dmn) - Node package dependency cleaner and .npmignore file generator

> Because I don't need your tests in my production!

--

* [[GitHub] deoxxa / npmrc](https://github.com/deoxxa/npmrc) - Switch between different .npmrc files with ease and grace.

* [[GitHub] floatdrop / chnpm](https://github.com/floatdrop/chnpm) - npm configuration switcher

--

* [Relato](http://bripkens.github.io/relato/) - NPM Project Statistics

* [npm Visualization | YASIV](http://www.yasiv.com/npm) | Sample: [Grunt npm dep](http://www.yasiv.com/npm#view/grunt)

* [NodeZoo](http://nodezoo.com/) - A search engine for reliable Node.js modules

* [The Node Toolbox - Node.js happiness](http://nodetoolbox.com/) - is a catalogue of Node.js packages, tools and resources with popularity ratings based on Github watchers and forks

--

* [David, a dependency management tool for Node.js projects](https://david-dm.org)

* [[GitHub] dylang / npm-check](https://github.com/dylang/npm-check) - Check for outdated, incorrect, and unused dependencies

--

* [npms](https://npms.io/) - was built to empower the javascript community by providing a better and open source search for node modules.

  * [[GitHub] npms-io](https://github.com/npms-io) - A better and open source search for node modules

* [npm Search](http://npmsearch.com/)

  * [[GitHub] solids / npmsearch](https://github.com/solids/npmsearch) - blazing fast npm search utility

* [Node Modules](http://node-modules.com/) - Better search for Node.js modules

* [Browse npm](http://browsenpm.org/)

* [searchnod.es](http://searchnod.es/) - code search for npm

--

* [[GitHub] 720kb / ndm](https://github.com/720kb/ndm) - Npm Desktop Manager

* [[GitHub] travishorn / npm-package-store](https://github.com/travishorn/npm-package-store) - A web app that displays updates for your globally installed NPM modules

--

* [npm cheatsheet | Nodejitsu](https://blog.nodejitsu.com/npm-cheatsheet)

* [[Gist] AvnerCohen / npm-cheat-sheet.md](https://gist.github.com/AvnerCohen/4051934) - Node.js - npm Cheat Sheet

* [Node : NPM CheatSheet | Gentlenode Studio - Journal](http://journal.gentlenode.com/node-1-npm-cheatsheet/)

--

* [10 Tips and Tricks That Will Make You an npm Ninja | SitePoint](https://www.sitepoint.com/10-npm-tips-and-tricks/) - 2016/11/09

* [NPM tricks | Devthought](http://www.devthought.com/2012/02/17/npm-tricks/)

* [Npm Tips | fiveisprime](http://fiveisprime.com/2014/04/06/npm-tips/)

* [10 Cool Things You Probably Didn't Realize npm Could Do](http://blog.izs.me/post/1675072029/10-cool-things-you-probably-didnt-realize-npm-could-do)

* [9 Quick Tips About npm | Pony Foo](http://blog.ponyfoo.com/2013/12/14/9-quick-tips-about-npm)

* [8 NPM tips for better Node development | Scott Smith](http://scottksmith.com/blog/2014/06/25/8-npm-tips-for-better-node-development/)

* [Node.js - Como mostrar o que está sendo instalado pelo NPM? | Nomadev](http://nomadev.com.br/node-js-como-mostrar-o-que-est%C3%A1-sendo-instalado-pelo-npm/)

* [Installing past or future versions of npm packages | 2ality](http://www.2ality.com/2015/12/npm-install-tag-version.html) - 2015/12/20

* [[GitHub] nolanlawson / slow-deps](https://github.com/nolanlawson/slow-deps) - Measure which dependencies in a project are slowest to npm install

--

* [Introduction to npm | SmallJS](http://smalljs.org/package-managers/npm/)

* [Tour of npm | toby ho](http://tobyho.com/2012/02/09/tour-of-npm/)

--

* [[GitHub] inikulin / publish-please](https://github.com/inikulin/publish-please) - Safe and highly functional replacement for `npm publish`

* [How to Build an npm Package | Treehouse Blog](http://blog.teamtreehouse.com/build-npm-package)

* [How to Build a Node npm Package From Scratch | Decodize](http://decodize.com/javascript/build-nodejs-npm-installation-package-scratch/)

* [Creating and publishing a node.js module | Quick Left Boulder Colorado](http://quickleft.com/blog/creating-and-publishing-a-node-js-module)

* [Publishing a simple package to npm | Evan Hahn](http://evanhahn.com/make-an-npm-baby/)

* [Your first Node.js package | NodeSource Blog](https://nodesource.com/blog/your-first-nodejs-package)

* [How to Create and Publish Your First Node.js Module | Medium by @jdaudier](https://medium.com/@jdaudier/how-to-create-and-publish-your-first-node-js-module-444e7585b738)

* [How to publish your package on npm | Hacker Noon](https://hackernoon.com/how-to-publish-your-package-on-npm-7fc1f5aae600) - 2017/04/08

* [[YouTube] How to use bundleDependencies (to avoid unpublish blues)](https://www.youtube.com/watch?v=qOGRUfdSiaM)

--

* [how npm handles the "scripts" field | npm docs](https://docs.npmjs.com/misc/scripts)

* [task automation with npm run | unix philosopher. beep boop.](http://substack.net/task_automation_with_npm_run)

  * [[Gist] using `npm run` to build and watch with less and browserify](https://gist.github.com/substack/7819530)

* [Running Scripts with npm | The Tapir's Tale](http://anders.janmyr.com/2014/03/running-scripts-with-npm.html)

* [How to Use npm as a Build Tool | Keith Cirkel](http://blog.keithcirkel.co.uk/how-to-use-npm-as-a-build-tool/) - 2014/12/09

* [[GitHub] wehkamp / npm-scripts-watcher](https://github.com/wehkamp/npm-scripts-watcher) - Globbing file watcher to automatically run npm scripts.

--

* [NPM for Everything | Alexander Beletsky](http://beletsky.net/2015/04/npm-for-everything.html) - NPM as dependency manager, task runner both for front and back end.

  * [[GitHub] alexbeletsky / brick](https://github.com/alexbeletsky/brick) - My boilerplate project for Node.js / React.js development

--

* [[GitHub] siddharthkp / cost-of-modules](https://github.com/siddharthkp/cost-of-modules) - Find out which of your dependencies are slowing you down

* [[GitHub] nolanlawson / slow-deps](https://github.com/nolanlawson/slow-deps) - Measure which dependencies in a project are slowest to npm install

* [[GitHub] cmtt / depwalk](https://github.com/cmtt/depwalk) - Walk through and verify your bower and npm dependencies

* [Stay up-to-date with Node.js packages using npm-onupdate service | Piotr Walczyszyn's Blog](http://outof.me/stay-up-to-date-with-node-js-packages-using-npm-onupdate-service/)

* [[GitHub] tjunnone / npm-check-updates](https://github.com/tjunnone/npm-check-updates) - Find newer versions of package dependencies than what your package.json or bower.json allows

### Yarn

* [[GitHub] yarnpkg / yarn](Fast, reliable, and secure dependency management)

--

* [NPM vs Yarn Cheat Sheet | Red Shift](https://shift.infinite.red/npm-vs-yarn-cheat-sheet-8755b092e5cc) - 2016/10/16

--

* [Yarn: A new package manager for JavaScript | Engineering Blog - Facebook Code](https://code.facebook.com/posts/1840075619545360) - 2016/10/11

* [Facebook launches Yarn, a JavaScript package manager built for speed | The Next Web](http://thenextweb.com/dd/2016/10/12/facebook-launches-yarn-a-faster-npm-client/) - 2016/10/12

* [Yarn Roundup: What you need to know about Facebook’s new JS Package Manager | StatusCode](https://medium.com/statuscode/roundup-of-yarn-links-npm-javascript-abad6a5ddbf6)


### CORS

* [[GitHub] natlownes / headrest](https://github.com/natlownes/headrest) - A RESTful, CORS enabled webserver intended for use when developing single page Javascript applications

* [[GitHub] agrueneberg / Corser](https://github.com/agrueneberg/Corser) - A highly configurable, middleware compatible implementation of CORS for Node.js.

* [[GitHub] suissa / cors-server](https://github.com/suissa/cors-server) - CORS Server with Node.js

  * [CORS Server em Node.js | Nomadev](http://nomadev.com.br/cors-server-em-node-js/)


### Armazenamento

* [[GitHub] nodeadmin / nodeadmin](https://github.com/nodeadmin/nodeadmin) - A fantastically elegant interface for MySQL and Node.js/Express management

--

* [Knex.js](http://knexjs.org/) - An SQL Query Builder for JavaScript. (Covers MySQL, PostgreSQL, SQLite3, and WebSQL.)

  * [[GitHub] tgriesser / knex](https://github.com/tgriesser/knex) - A query builder for PostgreSQL, MySQL and SQLite3, designed to be flexible, portable, and fun to use

--

* [[GitHub] naturalatlas / migrat](https://github.com/naturalatlas/migrat) - A pluggable Node.js data migration tool.

--

* [Node.js and SQLite | Modulus Blog](http://blog.modulus.io/nodejs-and-sqlite) - Great introduction to using SQLite with Node.js. Covers everything from installing to running queries against the database.

* [[GitHub] WebReflection / dblite](https://github.com/WebReflection/dblite) - sqlite for node.js without gyp problems

* [[GitHub] kriasoft / node-sqlite](https://github.com/kriasoft/node-sqlite) - SQLite client library for Node.js applications (SQlite3, ES6 Promise, ES7 async/await, Babel) and SQL-based migrations API

--

* [[GitHub] google / lovefield](https://github.com/google/lovefield) - A cross-browser, SQL-like, relational query engine for Web in pure JavaScript.

--

* [[GitHub] robconery / massive-js](https://github.com/robconery/massive-js) - A simple relational data access tool for NodeJS. (PostgreSQL)

* [Postgres and Node - Hands on using Postgres as a Document Store with MassiveJS | Craig Kerstiens](http://www.craigkerstiens.com/2015/12/08/massive-json/) - 2015/12/08

  * [[GitHub] craigkerstiens / json_node_example](https://github.com/craigkerstiens/json_node_example)

--

* [[GitHub] oracle / node-oracledb](https://github.com/oracle/node-oracledb) - Oracle Database driver for Node.js

  * [Announcing the Official Node.js Connector for the Oracle Database by Oracle | StrongLoop](https://strongloop.com/strongblog/official-node-js-connector-oracle-database/) - 2014/01/27

--

* [[GitHub] patriksimek / node-mssql](https://github.com/patriksimek/node-mssql) - An easy-to-use MSSQL database connector for Node.js / io.js.

--

* [[GitHub] sequelize / sequelize](https://github.com/sequelize/sequelize/) - Sequelize is an easy-to-use multi sql dialect ORM for Node.js & io.js. It currently supports MySQL, MariaDB, SQLite, PostgreSQL and MSSQL.

  * [PostgreSQL, MySQL, MariaDB, SQLite e MSSQL no Node.js | Alan Hoffmeister](https://alanhoff.com/posts/postgresql-mysql-mariadb-sqlite-e-mssql-no-nodejs.html)

--

* [[GitHub] mapbox / stickshift](https://github.com/mapbox/stickshift) - A clean & modern SQL data interface

--

* [[GitHub] BagosGiAr / modQuery](https://github.com/BagosGiAr/modQuery) - A module to use for MySQL queries with respect to SQL.

* [[GitHub] tracker1 / mssql-ng](https://github.com/tracker1/mssql-ng) - Next Generation MS-SQL Client Interface for Node.js/io.js

--

* [[GitHub] louischatriot / nedb](https://github.com/louischatriot/nedb) - Embedded datastore for node.js

  * [NeDB: SQLite for Node | DailyJS](http://dailyjs.com/2013/08/01/nedb/)

* [TingoDB](http://www.tingodb.com/) - Embedded JavaScript database for Node.js and node webkit

--

* [[GitHub] phidelta / abstract-store](https://github.com/phidelta/abstract-store) - a node-module to abstract key/value storage away from the underlying technology

--

* [[GitHub] Ivshti / linvodb3](https://github.com/Ivshti/linvodb3) - Persistent database for Node.js/NW.js/Electron with MongoDB/Mongoose-like features and interface.

--

* [Getting Started with Node.js and MongoDB | NodeSource](https://nodesource.com/blog/getting-started-with-node-js-and-mongodb) - 2017/06/21

* [Intro to MongoDB on Node.js | OpenShift by Red Hat](https://www.openshift.com/blogs/intro-to-mongodb-on-nodejs)

* [Um pouco de Node.js e MongoDB na prática | Underground WebDev](http://udgwebdev.com/um-pouco-de-node-js-e-mongodb-na-pratica)

* [Full Text Search with MongoDB and Node.js | MongoHQ Blog](http://blog.mongohq.com/full-text-search-with-mongodb-and-node-js/)

* [[GitHub] LearnBoost / mongoose](https://github.com/LearnBoost/mongoose) - MongoDB object modeling designed to work in an asynchronous environment

  * [Node.js and MongoDB | Modulus Blog](http://blog.modulus.io/getting-started-with-mongoose) - Getting Started with Mongoose

  * [Nodejs e MongoDB - Introdução ao Mongoose | NodeBR - NodeJS Brasil](view-source:http://nodebr.com/nodejs-e-mongodb-introducao-ao-mongoose/)

  * [Mongoose Connection best practice | The Holmes Office](http://theholmesoffice.com/mongoose-connection-best-practice/)

  * [[SlideShare] Mongoose - Melhores práticas usando MongoDB e Node.js](http://www.slideshare.net/suissapg/mongoose-melhores-prticas-usando-mongodb-e-nodejs)

  * [Mongoose Aggregation – Count, Group, Match, Project | excellencenodejsblog](http://excellencenodejsblog.com/mongoose-aggregation-count-group-match-project/)

  * [NodeJS MongoDB : Schema Validation, Middleware | excellencenodejsblog](http://excellencenodejsblog.com/nodejs-mongodb-advance-operations-mongoose/)

  * [GridFS Using Mongoose – NodeJS | excellencenodejsblog](http://excellencenodejsblog.com/gridfs-using-mongoose-nodejs/)

* [[GitHub] meritt / easymongo](https://github.com/meritt/easymongo) - The easiest MongoDB API

--

* [[GitHub] maritz / nohm](https://github.com/maritz/nohm) - node.js implementation of a redis object relations mapper (orm). High speed queries with this ODM for Redis

--

* [[GitHub] tcs-de / nodecache](https://github.com/tcs-de/nodecache) - a node internal caching module

--

* [[GitHub] simonlast / node-persist](https://github.com/simonlast/node-persist) - Super-easy persistent data structures in Node.js

* [[GitHub] punkave / prettiest](https://github.com/punkave/prettiest) - Improbably easy data storage and locking for command line scripts. Pairs well with shelljs and a nice chianti.

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

#### Vagrant

* [[GitHub] Dev-Dipesh / Vagrant-Ansible-NewRelic-setup-for-Node.Js-on-both-Windows-and-Linux](https://github.com/Dev-Dipesh/Vagrant-Ansible-NewRelic-setup-for-Node.Js-on-both-Windows-and-Linux) - This is a Vagrant, Ansible & NewRelic setup for Node.JS on all OS

#### Docker

* [[Vimeo] Node.JS and Docker with a side of Continuous Deployment](http://vimeo.com/85864661) - Presented by Niall O'Higgins at JSLA (js.la) on Thursday January 30th 2014. Docker is an incredible new tool to manage the deployment and lifecycle of Node.JS network services. This talk will cover using them together for much Continuous Deployment win.

--

* [Uma breve introdução ao Docker com Node.js | BrasilJS](https://braziljs.org/blog/uma-breve-introducao-ao-docker-com-nodejs/) - 2016/09/21

* [Dockerizing a Node.js web app | Node.js](https://nodejs.org/en/docs/guides/nodejs-docker-webapp/)

* [How to Dockerize your Node application | Luca Mezzalira](https://lucamezzalira.com/2016/04/03/how-to-dockerize-your-node-application/) - 2016/04/03

* [Dockerizing a Node.js Web Application | Semaphore](https://semaphoreci.com/community/tutorials/dockerizing-a-node-js-web-application)

* [How to create a Docker + Node.js + MongoDB + Varnish environment | Luis Elizondo](http://luiselizondo.net/blogs/luis-elizondo/how-create-docker-nodejs-mongodb-varnish-environment)

* [Getting Started with Docker for the Node.js | CouchDB Programmer - Medium](https://medium.com/code-adventures/35c45ce2a814)

* [Develop a NodeJS app with Docker | sqldump](http://blog.abhinav.ca/blog/2014/06/17/develop-a-nodejs-app-with-docker/)

* [Node.js: Utilizando o docker para construir e entregar as suas aplicações | Kaique Silva](http://sigmundxox.svbtle.com/docker-nodejs-containers)

* [Getting Started with Docker for the Node.js Developer | AirPair](https://www.airpair.com/node.js/posts/getting-started-with-docker-for-the-nodejs-dev)

* [[SlideShare] Microservices with Node and Docker](http://www.slideshare.net/subfuzion/microservices-with-node-and-docker) - 2015/10/14

* [How to Dockerize your Node application | Luca Mezzalira](http://lucamezzalira.com/2016/04/03/how-to-dockerize-your-node-application/) - 2016/04/03

--

* [[GitHub] adamalex / docker-urlarchiver](https://github.com/adamalex/docker-urlarchiver) - Use Docker to package a Node.js script with all its dependencies, including Node

* [[GitHub] apocas / dockerode](https://github.com/apocas/dockerode) - Not just another Docker.io Remote API node.js module

* [[GitHub] TechnologyAdvice / DevLab](https://github.com/TechnologyAdvice/DevLab) - Containerize your development workflow.


### Nuvem

* [Onde hospedar aplicações Node.js | Underground WebDev](http://udgwebdev.com/onde-hospedar-aplicacoes-node-js/)


#### Pessoal

* [BipIO](https://bip.io/) - gives you the power to rapidly create workflows with the cloud components you already love, no programming required.

  * [[GitHub] bipio-server / bipio](https://github.com/bipio-server/bipio) - The BipIO API Server


* [Cozy](http://cozy.io/) - a personal Cloud you can host, hack and delete Your web apps and your data on your hardware

  * [[GitHub] mycozycloud / cozy-setup](https://github.com/mycozycloud/cozy-setup)

  * [Turn the server into the new personal device with Node.js, Cozy and CouchDB | Cozy.io](http://blog.cozycloud.cc/technic/2014/04/02/cozy-and-couchdb/)


#### Google Cloud

* [[GitHub] GoogleCloudPlatform / gcloud-node](https://github.com/GoogleCloudPlatform/gcloud-node) - Google Cloud Client Library for Node.js


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

--

* [[GitHub] serverless / serverless](https://github.com/serverless/serverless) - The Serverless Application Framework – Build and maintain web, mobile and IoT applications running on [AWS Lambda](https://aws.amazon.com/lambda/) and API Gateway (formerly known as JAWS)


##### Amazon S3

* [NodeJS Deploying Files to AWS S3](http://blog.katworksgames.com/2014/01/26/nodejs-deploying-files-to-aws-s3/)

* [Upload Static Files in AWS S3 with Node.js and Grunt.js | Toontuts](http://www.toontuts.com/upload-static-files-in-aws-s3-with-node-js-and-grunt-js/)

* [[GitHub] giuliandrimba / s3-pusher](https://github.com/giuliandrimba/s3-pusher) - Publish assets to Amazon's S3 service via CLI

* [[GitHub] visionmobile / bloody-simple-s3](https://github.com/visionmobile/bloody-simple-s3) - A bloody simple S3 client, based on the official AWS SDK


#### Windows Azure

* [[Blog] Node on Azure](http://nodeblog.azurewebsites.net/)

* [Node.js on Windows Azure](http://www.windowsazure.com/en-us/develop/nodejs/) - Get the tools, documentation, sample code and other resources you need to build powerful Node.js applications on Windows Azure.

* [How to Use the Blob Service from Node.js](http://www.windowsazure.com/en-us/documentation/articles/storage-nodejs-how-to-use-blob-storage/)


### Mobile

#### iOS

* [Node.app](http://nodeapp.org/) - Node.js for iOS


### Desktop

* [Build Desktop Application Using Node.js | Shift8Creative](http://www.shift8creative.com/posts/view/build-desktop-application-using-node-js) - A Quickstart using AppJs

* [Beyond The Browser: From Web Apps To Desktop Apps | Smashing Magazine](https://www.smashingmagazine.com/2017/03/beyond-browser-web-desktop-apps/) - 2017/03/21

--

* [[GitHub] appjs / appjs](https://github.com/appjs/appjs) - SDK on top of nodejs to build desktop apps using HTML5/CSS/JS

* [[GitHub] arturadib / node-qt](https://github.com/arturadib/node-qt) - Qt bindings for Node.js

* [[GitHub] hij1nx / node-chrome](https://github.com/hij1nx/node-chrome) - Node.js + Chrome = Networked Desktop Apps. Simple.

* [[Vimeo] Native Node.js Apps](http://vimeo.com/97881078) - Native NodeJS apps are a relatively new breed of apps coming out of the NodeJS community that combine NodeJS and Webkit

--

* [[GitHub] princejwesley / Mancy](https://github.com/princejwesley/Mancy) - >_ Electron based Javascript REPL

--

* [[GitHub] RSATom / WebChimera.js](https://github.com/RSATom/WebChimera.js) - libvlc binding for node.js/io.js/Node-Webkit/NW.js/Electron

--

* [Breach](http://breach.cc/) - A browser for the HTML5 era Entirely written in Javascript. Free. Modular. Hackable.

* [Vivaldi](https://vivaldi.com/) - has a powerful feature set, but thats not all. One of the things that makes Vivaldi unique is that it’s built on modern Web technologies. We use JavaScript and React to create the user interface — with the help of Node.js, Browserify and a long list of NPM modules. Vivaldi is the web built with the web.

--

* [NW.js & Electron Compared (2016 Edition) | TangibleJS](http://tangiblejs.com/posts/nw-js-and-electron-compared-2016-edition)


#### electron

* [[GitHub] sindresorhus / awesome-electron](https://github.com/sindresorhus/awesome-electron) - Useful resources for creating apps with Electron

* [[GitHub] atom / electron](https://github.com/atom/electron) - Build cross platform desktop apps with web technologies. Formerly known as Atom Shell.

* [Quick Start | Electron](http://electron.atom.io/docs/latest/tutorial/quick-start/)

  * [[GitHub] atom / electron-quick-start](https://github.com/atom/electron-quick-start) - Clone to try a simple Electron app

--

* [Announcing TypeScript support in Electron | Electron](https://electron.atom.io/blog/2017/06/01/typescript) - 2017/06/01

--

* [15 Essential Packages to Get Started With Electron | NodeSource](https://nodesource.com/blog/fifteen-essential-packages-to-get-started-with-electron/) - 2016/09/02

--

* [Building a desktop application with Electron | Developers Writing — Medium](https://medium.com/developers-writing/building-a-desktop-application-with-electron-204203eeb658) - A detailed guide on building your very own sound machine using JavaScript, Node.js and Electron.

* [Primeiros passos com Electron | Medium by @raphaelporto](https://medium.com/@raphaelporto/primeiros-passos-com-electron-2cfbda828f0d) - Não há dúvidas, JavaScript tem crescido muito nos últimos anos. Isso se deve muito ao engine V8, que proporcionou a criação do NodeJS e outras ferramentas incríveis. Entre elas temos o Electron, um framework que nos permite criar aplicações desktop com JavaScript.

* [Creating Desktop Applications With AngularJS and GitHub Electron | Scotch.io](https://scotch.io/tutorials/creating-desktop-applications-with-angularjs-and-github-electron) - 2015/09/28

* [Building Cross-platform Desktop Apps with Electron | Toptal](http://www.toptal.com/javascript/electron-cross-platform-desktop-apps-easy)

  * [[GitHub] stephanepericat / toptal-electron-loki-demo](https://github.com/stephanepericat/toptal-electron-loki-demo) - Electron: Cross-platform Desktop Apps Made Easy

* [Building Hybrid Applications with Electron | Several People Are Coding - Medium](https://slack.engineering/building-hybrid-applications-with-electron-dc67686de5fb) - 2016/10/26

* [Automatically Build and Publish Node and Electron Applications for Linux  | Sessions by Pusher](https://pusher.com/sessions/meetup/london-node-user-group/automatically-build-and-publish-node-and-electron-applications-for-linux) - Martin Wimpress speaking at London Node User Group in April, 2017

--

* [[GitHub] JamesTheHacker / Neuron](https://github.com/JamesTheHacker/Neuron) - Neuron - Electron, ES6, React, PouchDB, Sass, Webpack

--

* [Sqlectron](https://sqlectron.github.io/) - One single DB client for any relational DB (initial support MySql and PostgreSQL)

* [[GitHub] jiahaog / nativefier](https://github.com/jiahaog/nativefier) - Wrap any web page natively without even thinking, across Windows, OSX and Linux

* [[GitHub] romannurik / MaterialColorsApp](https://github.com/romannurik/MaterialColorsApp) - A handy little Mac app that gives you quick access to the standard material design color palette

* [[GitHub] appetizermonster / hain](https://github.com/appetizermonster/hain) - An 'alt+space' launcher for Windows, built with Electron

* [[GitHub] mafintosh / playback](https://github.com/mafintosh/playback) - Video player built using electron and node.js

* [[GitHub] hackjutsu / Lepton](https://github.com/hackjutsu/Lepton) - Cross-platform snippet/note manager based on GitHub Gist.

* [[GitHub] buttercup-pw / buttercup](https://github.com/buttercup-pw/buttercup) - Javascript Password Vault - Multi-Platform Desktop Application

* [[GitHub] antonycourtney / tad](https://github.com/antonycourtney/tad) - A desktop application for viewing and analyzing tabular data

* [[GitHub] saenzramiro / rambox](https://github.com/saenzramiro/rambox/) - Free and Open Source messaging and emailing app that combines common web applications into one


#### Node Webkit

* [[GitHub] nwjs / nw.js](https://github.com/nwjs/nw.js) - Call all Node.js modules directly from DOM and enable a new way of writing applications with all Web technologies.

  * [[GitHub] jyapayne / Web2Executable](https://github.com/jyapayne/Web2Executable) - Uses node-webkit to generate "native" apps for already existing web apps.

* [[Speaker Deck] node-webkit: app runtime based on Chromium and node.js](https://speakerdeck.com/zcbenz/node-webkit-app-runtime-based-on-chromium-and-node-dot-js)

* [Creating Desktop Applications With node-webkit | StrongLoop](http://strongloop.com/strongblog/creating-desktop-applications-with-node-webkit/)

* [Introduction to HTML5 Desktop Apps With Node-Webkit | Tuts+ Code Tutorial](http://code.tutsplus.com/tutorials/introduction-to-html5-desktop-apps-with-node-webkit--net-36296)

* [Iniciando com Node Webkit | Beto Muniz](http://betomuniz.com/blog/iniciando-com-node-webkit/)

* [Aplicativo Desktop com Nwjs + AngularJS + Bootstrap + Sqlite | Clube dos Geeks](http://clubedosgeeks.com.br/programacao/node-js/aplicativo-desktop-com-nwjs-angularjs-bootstrap-sqlite) - 2016/03/18

  * [[GitHub] ClubeDosGeeksCoding / nwjs-angularjs-sqlite](https://github.com/ClubeDosGeeksCoding/nwjs-angularjs-sqlite) - Aplicação exemplo com AngularJS, NwJS, SQLite e Bootstrap

--

* [[GitHub] mllrsohn / node-webkit-builder](https://github.com/mllrsohn/node-webkit-builder) - npm module to create a node-webkit build

* [[GitHub] mllrsohn / grunt-node-webkit-builder](https://github.com/mllrsohn/grunt-node-webkit-builder) - Let you build your node-webkit apps for mac, win and linux with grunt. It will download the prebuilt binaries for a specify version, unpacks it, creates a release folder, create the app.nw file for a specified directory and copys the app.nw file where it belongs.


##### node-webkit: exemplos

* [[GitHub] kessler / nw-ninja](https://github.com/kessler/nw-ninja) - minimal node-webkit starter project for ninjas

* [[GitHub] Anonyfox / node-webkit-hipster-seed](https://github.com/Anonyfox/node-webkit-hipster-seed) - Bootstrap a crossplatform Desktop Application using tools you probably never heard of

* [[GitHub] vhpoet / nwjs-boilerplate](https://github.com/vhpoet/nwjs-boilerplate) - nw.js (node-webkit) boilerplate

* [[GitHub] zcbenz / nw-sample-apps](https://github.com/zcbenz/nw-sample-apps) - Sample apps for node-webkit


##### node-webkit: Aplicações e Empresas que utilizam

* [List of apps and companies using node webkit | rogerwang / node-webkit - GitHub Wiki](https://github.com/rogerwang/node-webkit/wiki/List-of-apps-and-companies-using-node-webkit)

--

* [[GitHub] pbojinov / nodeifications](https://github.com/pbojinov/nodeifications) - Simple cross platform desktop notifications for node-webkit

* [[GitHub] wookiecooking / nwfaketop](https://github.com/wookiecooking/nwfaketop) - A GruntJS Compiler for Node-webkit Applications (OSX Based)

* [[GitHub] slate / slate](https://github.com/slate/slate) - modern IRC client built with web technologies and Node.js

* [[GitHub] FWeinb / screenshot-service](https://github.com/FWeinb/screenshot-service) - A simple screenshot web service powered by Express and node-webkit.

* [[GitHub] kevva / imagemin-app](https://github.com/kevva/imagemin-app) - imagemin as an OS X, Linux and Windows app

* [Fenix](http://fenixwebserver.com/) - Finally, a simple static desktop web server

  * [[GitHub] coreybutler / fenix](https://github.com/coreybutler/fenix) - A software app that manages development web servers and webhooks

* [[GitHub] yamalight / HumblePlayer](https://github.com/yamalight/HumblePlayer) - music player for your HumbleBundle soundtracks (made with node-webkit and Angular)

* [[GitHub] jaruba / PowderPlayer](https://github.com/jaruba/PowderPlayer/) - Hybrid between a Torrent Client and a Player (torrent streaming)

* [Popcorn Time](https://popcorntime.sh/)

  * [[twitter] Popcorn Time App](https://twitter.com/popcorntimetv)

  * [[GitHub] popcorn-official](https://github.com/popcorn-official)

    * Repository unavailable due to DMCA takedown :: [[GitHub] popcorn-official / popcorn-app](https://github.com/popcorn-official/popcorn-app) - An experiment using the peerflix module of nodejs and connecting a bunch of APIs.

* [Time 4 Popcorn](http://www.time4popcorn.com/)

  * [[twitter] Time 4 Popcorn](https://twitter.com/Time4Popcorn)


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


* [[GitHub] gimm / gulp-live-server](https://github.com/gimm/gulp-live-server) - serve your nodejs/static app live

* [[GitHub] tapio / live-server](https://github.com/tapio/live-server) - A simple development http server with live reload capability

  * [Live Server | Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

  * [atom-live-server | Atom Package](https://atom.io/packages/atom-live-server)


#### Socket.io

* [Socket.IO](http://socket.io/) - aims to make realtime apps possible in every browser and mobile device, blurring the differences between the different transport mechanisms. It's care-free realtime 100% in JavaScript.

* [[GitHub] LearnBoost / socket.io](https://github.com/learnboost/socket.io) - Realtime application framework for Node.JS, with HTML5 WebSockets and cross-browser fallbacks support

* [Getting Started With Socket.io | TysonJS](http://tysoncadenhead.com/blog/getting-started-with-socket-io)

* [[GitHub] LearnBoost / engine.io](https://github.com/learnboost/engine.io) - is the implementation of transport-based cross-browser/cross-device bi-directional communication layer for Socket.IO.

* [[GitHub] Ezelia / eureca.io](https://github.com/Ezelia/eureca.io) - eureca.io : a nodejs bidirectional RPC using primus as transport layer

* [The Realtime Engine | Devthought](http://www.devthought.com/2012/07/07/the-realtime-engine/)

* [Token-based Authentication with Socket.IO | Auth0](http://blog.auth0.com/2014/01/15/auth-with-socket-io/)

* [Build a Node.js-powered Chatroom Web App: Node, MongoDB and Socket | SitePoint](http://www.sitepoint.com/build-node-js-powered-chatroom-web-app-node-mongodb-socket/)

* Underground WebDev

  * [Node.js para leigos - Explorando real-time | Underground WebDev](http://udgwebdev.com/node-js-para-leigos-explorando-real-time/)

  * [Real-time com Socket.IO no Node.js](http://udgwebdev.com/real-time-com-socket-io-no-nodejs/)

  * [Express, Socket.IO e Sessions | Underground WebDev](http://udgwebdev.com/nodejs-express-socketio-e-sessions/)

  * [Criando um chat usando session do Express 4 no Socket.IO 1.0](http://udgwebdev.com/criando-um-chat-usando-session-do-express-4-no-socket-io-1-0/)


#### Connect

* [Connect](http://www.senchalabs.org/connect/) - High quality middleware for node.js

* [A short guide to Connect Middleware](http://stephensugden.com/middleware_guide/)


#### Express.js

* [Express.js](http://expressjs.com/)

  * [TJ Holowaychuk Passes Sponsorship of Express to StrongLoop | StrongLoop](http://strongloop.com/strongblog/tj-holowaychuk-sponsorship-of-express/) - 29/07/2014

  * [[GitHub] strongloop / express](https://github.com/strongloop/express) - Sinatra inspired web development framework for node.js -- insanely fast, flexible, and simple

--

* [Express 4 Tutorial - Simple Server - Danial Khosravi's Blog](https://danialk.github.io/blog/2014/12/05/express-4-tutorial-simple-server/)

--

* [[GitHub] likeastore / maintenance](https://github.com/likeastore/maintenance) - middleware for easy switching the app to maintenance mode

* [Kraken.js](http://krakenjs.com/) - The kraken suite is a secure and scalable layer that extends express by providing structure and convention

* [DozerJS](http://dozerjs.com/) - is a system for rapidly developing services to support front-end applications

  * [Simple Todo List App with DozerJS | fluidbyte](http://www.fluidbyte.net/simple-todo-list-app-with-dozerjs/)

* [ExpressWorks | webapplog](http://webapplog.com/expressworks/) - is an automated Express.js/Node.js workshop

* [Express.js Fundamentals | Flippin' Awesome](http://flippinawesome.org/2013/11/11/express-js-fundamentals/)

* [Node.js com Express.js nos negócios | iMasters](http://imasters.com.br/front-end/javascript/node-js-com-express-js-nos-negocios/)

* [Build a Complete MVC Website With ExpressJS | Nettuts+](http://net.tutsplus.com/tutorials/javascript-ajax/build-a-complete-mvc-web-site-with-expressjs/)

* [Super simple file upload with node.js | Tanya Nam](http://tanyanam.com/everything/super-simple-file-upload-with-node-js)

* [Uploading files made fun with Express js and Blueimp file upload | The Jackal of Javascript](http://thejackalofjavascript.com/uploading-files-made-fun/)

* [Building a simple blog with NodeJS and Express | KOPIS.DE](http://blog.kopis.de/2012/01/30/building-a-simple-blog-with-nodejs-and-express/) | [[GitHub] MoriTanosuke / blode](https://github.com/MoriTanosuke/blode) - Simple blog framework with NodeJS (post write in markdown)

* [ExpressJS and MySQL Sample Application and Tutorial | gist.pages](http://gistpages.com/2013/11/1/expressjs_and_mysql_sample_application_and_tutorial)

* [Using the Directory-serving middleware in Express | Raymond Camden](http://www.raymondcamden.com/index.cfm/2013/8/11/Using-the-Directoryserving-middleware-in-Express)

* [Using Express.js for APIs | StrongLoop](http://blog.strongloop.com/using-express-js-for-apis)

* [Node.js para leigos - Framework Express parte 1 | Underground WebDev](http://udgwebdev.com/node-js-para-leigos-framework-express-parte-1/)

* [Node.js para leigos - Framework Express parte 2 | Underground WebDev](http://udgwebdev.com/node-js-para-leigos-framework-express-parte-2/)

* [Primeiros passos com Express 4 | Underground WebDev](http://udgwebdev.com/primeiros-passos-com-express-4/)

* [Todo App with Express.js/Node.js and MongoDB | webapplog](http://webapplog.com/todo-app-with-express-jsnode-js-and-mongodb/)

* [Passport.js](http://passportjs.org/) - Simple, unobtrusive authentication for Node.js.

  * [Getting Started with Passport | node.js knockout](http://blog.nodeknockout.com/post/66118192565/getting-started-with-passport)

  * [Social Authentication for Node.js Apps With Passport | Tuts+ Code Article](http://code.tutsplus.com/articles/social-authentication-for-nodejs-apps-with-passport--cms-21618)

* [List All REST Endpoints built using Express or Restify | The Jackal of Javascript](http://thejackalofjavascript.com/list-all-rest-endpoints/)

* [Simple server side cache for Express.js with Node.js | Node.js Collection - Medium](https://medium.com/the-node-js-collection/simple-server-side-cache-for-express-js-with-node-js-45ff296ca0f0) - 2017/07/18

--

* [[GitHub] felixge / node-formidable](https://github.com/felixge/node-formidable) - A node.js module for parsing form data, especially file uploads

  * [[GitHub] devcollectief / express-upload](https://github.com/devcollectief/express-upload) - Streaming multiple large files to AWS S3 with Multipart API, Formidable & Jquery File Upload

--

* [[GitHub] PixelsCommander / ViralJS](https://github.com/PixelsCommander/ViralJS) - Express.JS middleware to enable P2P distribution for your app. Your decentralized CDN made easy.

--

* [[GitHub] DIMLEO / express-life](https://github.com/DIMLEO/express-life) - ump start a project with express.js


#### Meteor

* [meteor](http://www.meteor.com/)

* [Introdução sobre Meteor | Underground WebDev](http://udgwebdev.com/introducao-sobre-meteor/)

* [Primeiros passos com Meteor | Underground WebDev](http://udgwebdev.com/primeiros-passos-com-meteor)

* [Organizando um projeto Meteor | Underground WebDev](http://udgwebdev.com/organizando-um-projeto-meteor)

* [Quer aprender Meteor? | Underground WebDev](http://udgwebdev.com/quer-aprender-meteor)

* [Build & Deploy Rich UI JavaScript Apps, FAST! | Telerik Developer Network](http://developer.telerik.com/featured/build-deploy-rich-ui-javascript-apps-fast/)


### Testes

* [Testing and Code Coverage With Node.js Apps | Greg Jopa](http://www.gregjopa.com/2014/02/testing-and-code-coverage-with-node-js-apps/)

* [Getting started with Node.js and Jasmine | Semaphore](https://semaphoreci.com/community/tutorials/getting-started-with-node-js-and-jasmine)

* [[GitHub] dareid / chakram](https://github.com/dareid/chakram) - REST API test framework. BDD and exploits promises

* [[GitHub] shoreditch-ops / artillery](https://github.com/shoreditch-ops/artillery) - Modern load testing toolkit for HTTP, Socket.io, WebSockets and more.


#### Test Runner

* [[GitHub] vdemedes / trevor](https://github.com/vdemedes/trevor) - Your own Travis CI to run tests locally

--

* [[GitHub] airportyh / testem](https://github.com/airportyh/testem) - Test'em 'Scripts! A test runner that makes Javascript unit testing fun

* [[GitHub] karma-runner / karma](https://github.com/karma-runner/karma) - Spectacular Test Runner for JavaScript

* [[GitHub] mochajs / mocha](https://github.com/mochajs/mocha) - simple, flexible, fun javascript test framework for node.js & the browser. (BDD, TDD, QUnit styles via interfaces)

  * [Getting started with Node.js and Mocha | Semaphore](https://semaphoreci.com/community/tutorials/getting-started-with-node-js-and-mocha)

* [[GitHub] Codeception / CodeceptJS](https://github.com/codeception/codeceptjs/) - Modern Era Aceptance Testing Framework for NodeJS


### Ferramentas

* [[GitHub] stefanjudis / perf-tooling](https://github.com/stefanjudis/perf-tooling) - List of tools for performance analysis and monitoring


#### Visual Studio

* [Node.js for Visual Studio | CodePlex](https://nodejstools.codeplex.com/)

* [[GitHub] Microsoft / nodejstools](https://github.com/Microsoft/nodejstools) - NTVS is a free, open source plugin that turns Visual Studio into a Node.js IDE.

--

* [Introducing node.js Tools for Visual Studio | Scott Hanselman](http://www.hanselman.com/blog/IntroducingNodejsToolsForVisualStudio.aspx)

* [Node.js support in Visual Studio? You bet your IDE | StrongLoop](http://strongloop.com/strongblog/node-js-support-in-visual-studio-you-bet-your-ide/)

* [Dive into Node.js development with this Visual Studio plugin | TechRepublic](http://www.techrepublic.com/article/dive-into-node-js-development-with-this-visual-studio-plugin/)

* [Stand-up: Developing a node.js application using Monaco (Part 1) | Visual Studio Online "Monaco"](http://blogs.msdn.com/b/monaco/archive/2014/03/27/stand-up-developing-a-node-js-application-using-monaco-part-1.aspx)

* [Introducing Gulp, Grunt, Bower, and npm support for Visual Studio | Scott Hanselman](http://www.hanselman.com/blog/IntroducingGulpGruntBowerAndNpmSupportForVisualStudio.aspx)

* [Using Grunt, Gulp and Bower in Visual Studio 2013 and 2015 | DotNetCurry](http://www.dotnetcurry.com/visualstudio/1096/using-grunt-gulp-bower-visual-studio-2013-2015)

--

* [Node.js Tools 1.0 for Visual Studio | The Visual Studio Blog](http://blogs.msdn.com/b/visualstudio/archive/2015/03/25/node-js-tools-1-0-for-visual-studio.aspx) - 2015/03/25


#### Eclipse IDE

* [Nodelipse](http://www.nodeclipse.org/) | [Sourceforge](http://sourceforge.net/projects/nodeclipse/)

#### JetBrains

* [IntelliJ IDEA :: Node.js](http://www.jetbrains.com/idea/features/nodejs.html)

* [WebStorm :: Node.js](http://www.jetbrains.com/webstorm/features/index.html#node.js)
