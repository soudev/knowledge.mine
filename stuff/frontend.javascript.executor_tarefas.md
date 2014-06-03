# Front-End


<!-- toc -->
* [JavaScript](#javascript)
  * [Executor de Tarefas](#executor-de-tarefas)
    * [Bundy](#bundy)
    * [Gulp](#gulp)
    * [Grunt](#grunt)
      * [Aprendizado](#aprendizado)
      * [Ferramentas](#ferramentas)
      * [Plugins](#plugins)
      * [Dicas](#dicas)
      * [Testes](#testes)
      * [Exemplos de Uso](#exemplos-de-uso)
      * [Construído sobre o Grunt.js](#construído-sobre-o-gruntjs)

<!-- toc stop -->


## JavaScript

### Executor de Tarefas

> **Dependência**
> 
> As ferramentas de automatização/tarefas necessitam e executam sobre o Node.js

* [[GitHub] vitorbritto / makefy](https://github.com/vitorbritto/makefy) - An easy way to automate build tasks with Makefile

* [task automation with npm run | unix philosopher. beep boop.](http://substack.net/task_automation_with_npm_run)

--

* [flour](http://ricardo.cc/cake-flour/) - A ferramenta brasileira Flour consiste em um conjunto de ferramentas para projetos javascript com foco na objetividade para rodar tarefas comuns, como: compilação, minificação, validação e concatenação de arquivos.

* [Brunch](http://brunch.io) - ultra-fast HTML5 build tool

* [[GitHub] fez / fez](https://github.com/fez/fez) - File-based build tool for Javascript

  * [Using Grunt? Consider Fez | Flippin' Awesome](http://flippinawesome.org/2014/02/24/using-grunt-consider-fez/)

--

* [Gulp, Grunt, Whatever | Pony Foo](http://blog.ponyfoo.com/2014/01/09/gulp-grunt-whatever)

* [Grunt vs Gulp - Beyond the Numbers | Jack Hsu](http://jaysoo.ca/2014/01/27/gruntjs-vs-gulpjs/)

* [Build Wars: Gulp vs Grunt](http://markdalgleish.github.io/presentation-build-wars-gulp-vs-grunt/)


#### Bundy

* [Bundy](https://github.com/michaldudek/Bundy) - If you are working on a JavaScript library, plugin or a widget and  want to quickly "bundle" it (minify all JavaScript and CSS files, put  them in single files, copy other assets, eg. images and fonts, to  release directory), then Bundy is for you.


#### Gulp

* [gulp.js](http://gulpjs.com) - the streaming build system

* [gulp - The vision, history, and future of the project | Medium](https://medium.com/p/3828e8126466)

--

* [Gulp: O novo automatizador | Tableless](http://tableless.com.br/gulp-o-novo-automatizador/)

* [Bye bye Grunt.js, hello Gulp.js! | Caelum](http://blog.caelum.com.br/bye-bye-grunt-js-hello-gulp-js/)

* [Gulp JS: como se tornar Expert em minutos | morethings.io](http://morethings.io/javascript/gulpjs-como-se-tornar-expert-em-minutos/)

* [Getting started with gulp | Mark Goodyear](http://markgoodyear.com/2014/01/getting-started-with-gulp/)

* [Quick intro to Gulp.js | Code Fellows](http://www.codefellows.org/blogs/quick-intro-to-gulp-js)

* [My First Gulp Adventure | Pony Foo](http://blog.ponyfoo.com/2014/01/27/my-first-gulp-adventure)

* [Writing Tasks in Gulp.js | pixeldonor](http://www.pixeldonor.com/2014/feb/20/writing-tasks-gulpjs/)

* [Managing Your Build Tasks With Gulp.js | Tuts+ Code Tutorial](http://code.tutsplus.com/tutorials/managing-your-build-tasks-with-gulpjs--net-36910)

* [How to build an Asset Pipeline with Gulpjs for any webapp | FrontEnd Journal](http://www.frontendjournal.com/how-to-build-an-asset-pipeline-with-gulpjs-for-any-webapp/)

* [Usando Gulp com WordPress para automatizar tarefas | claudiosmweb.com](http://claudiosmweb.com/wordpress/usando-gulp-com-wordpress/)

* [Gulp + Browserify: The Everything Post | Viget](http://viget.com/extend/gulp-browserify-starter-faq)

* [[GitHub] gulpjs / gulp / docs / recipes / split-tasks-across-multiple-files.md](https://github.com/gulpjs/gulp/blob/master/docs/recipes/split-tasks-across-multiple-files.md) Split Gulp tasks into multiple files

--

* [Exploring A Generator For Gulp.js | Yeoman](http://yeoman.io/blog/gulp-explore.html)

* [Getting gulpy | Medium](https://medium.com/p/a2010c13d3d5) - Advanced tips for using gulp.js

--

* [Speedtesting Gulp and Grunt | labs@tmw](http://labs.tmw.co.uk/2014/01/speedtesting-gulp-and-grunt/)

* [[GitHub] ryanbenson / Front-End-Gulp-Boilerplate](https://github.com/ryanbenson/Front-End-Gulp-Boilerplate) - Front-end boilerplate for Gulp with everything you need to get started

--

* [Gulpfiction](http://gulpfiction.divshot.io/#/cdf3b0ac-4591-4b70-8c54-cd5eb838856c) - Visual web editor to get started with Gulp

* [[GitHub] sindresorhus / gulp-app](https://github.com/sindresorhus/gulp-app) - gulp as an app (OS X) [node-webkit]



#### Grunt

> **Sobre**
> 
> O Grunt é uma aplicação de linha de comando que tem como objetivo automatizar tarefas, principalmente tarefas em aplicações JavaScript.

> **Quem utiliza?**
> 
> [Lista](http://gruntjs.com/who-uses-grunt) de quem utiliza o Grunt.js
> 
> Dentre os ultilizadores, está o [JQuery](http://jquery.com/), [[GitHub] jquery / jquery](https://github.com/jquery/jquery) ([Gruntfile.js](https://github.com/jquery/jquery/blob/master/Gruntfile.js)), o qual utiliza para gerenciar os builds e testes da biblioteca.

* [Grunt: The JavaScript Task Runner](http://gruntjs.com/)


##### Aprendizado

* [Grunt: Getting started](https://github.com/gruntjs/grunt/wiki/Getting-started)

* [[GitHub] gruntbrasil / grunt-docs](https://github.com/gruntbrasil/grunt-docs) - Documentacão do Grunt

* [Getting started with Grunt | Blog - Fronto](http://fronto.be/blog/detail/getting-started-with-grunt)

* [GruntJS - Por onde começar? | Volts Digital](http://www.voltsdigital.com.br/labs/gruntjs-por-onde-comecar/)

* [Stop being the Grunt - use Grunt.js | Josh Bavari](https://jbavari.github.io/Dont-Be-a-Grunt-Use-Grunt-Slides/) - A presentation telling what Grunt.js is and Why to use it

* [Sample Gruntfile - Grunt: The JavaScript Task Runner](http://gruntjs.com/sample-gruntfile)

* [[YouTube] Grunt - The Basics](https://www.youtube.com/watch?v=q3Sqljpr-Vc) | [[GitHub] CaryLandholt / Tutorial-Grunt-TheBasics](https://github.com/CaryLandholt/Tutorial-Grunt-TheBasics)

* [Meet Grunt: The Build Tool for JavaScript | Nettuts+](http://net.tutsplus.com/tutorials/javascript-ajax/meeting-grunt-the-build-tool-for-javascript/)

* [Building JavaScript projects with Grunt](http://ruudud.github.com/2012/12/22/grunt/)

* [Grunt: A build tool for front-end projects](http://frederic-hemberger.de/artikel/grunt-buildtool-for-frontend-projects/)

* [Automação de tarefas com o Grunt JS - Parte I | Javascript Brasil](http://javascriptbrasil.com/2013/10/08/automacao-de-tarefas-com-grunt-parte-1/)

* [Get Up And Running With Grunt | Smashing Coding](http://coding.smashingmagazine.com/2013/10/29/get-up-running-grunt/)

* [Writing an Awesome Build Script with Grunt | SitePoint](http://www.sitepoint.com/writing-awesome-build-script-grunt/)

* [Grunt Tips and Tricks | Pony Foo](http://blog.ponyfoo.com/2013/11/13/grunt-tips-and-tricks)

  * [[GitHub] bevacqua / unbox](https://github.com/bevacqua/unbox) - Unbox a node application with a well-designed build-oriented approach in minutes

* [Building Your First Grunt Plugin | Flippin' Awesome](http://flippinawesome.org/2014/05/29/building-your-first-grunt-plugin/)

--

* [Supercharging your Gruntfile: How to squeeze the most out of your build configuration | HTML5 Rocks](http://www.html5rocks.com/en/tutorials/tooling/supercharging-your-gruntfile/)

--

* [[GitHub] bazevedo / grunt-workflow](https://github.com/bazevedo/grunt-workflow) - dicas para um workflow com grunt

* [Merrick Christensen - Grunt.js Workflow](http://merrickchristensen.com/articles/gruntjs-workflow.html)

* [Grunt.js takes your workflow to the next level | Adnane Belmadiaf](http://daker.me/2013/06/gruntjs-takes-your-workflow-to-the-next-level.html)

* [Grunt JS: Automatize tarefas e otimize o seu workflow | Henrique Silvério](http://blog.henriquesilverio.com/javascript-e-jquery/grunt-js-automatize-tarefas-e-otimize-o-seu-workflow/)

* [Automating The Development, Build, and Deployment Process with Grunt | David Tucker](http://davidtucker.net/articles/automating-with-grunt/)

* [Automating Complex Workflows with Grunt Custom Tasks | Flippin' Awesome](http://flippinawesome.org/2013/09/23/automating-complex-workflows-with-grunt-custom-tasks/)

* [[Speaker Deck] Automating Front-end Workflow](https://speakerdeck.com/addyosmani/automating-front-end-workflow) - by Addy Osmani

* [[SlideShare] Grunt.js and Yeoman, Continous Integration](http://www.slideshare.net/DavidAm/gruntjs-and-yeoman-continous-integration)

--

* [Grunt: você deveria estar usando! | .openBlog()](http://openblog.github.com/2013/03/22/grunt/)

* [Automação de build de front-end com Grunt.js | Caelum](http://blog.caelum.com.br/automacao-de-build-de-front-end-com-grunt-js/)

* [A primer into front-end tooling (Grunt.js) for an open-source workflow | Tech Pro](http://tech.pro/tutorial/1456/a-primer-into-front-end-tooling-gruntjs-for-an-open-source-workflow)

* [[YouTube] Grunt JavaScript Automation for the Lazy Developer](https://www.youtube.com/watch?v=bntNYzCrzvE)

* [Advanced Grunt tooling | Chris Wren](http://chrisawren.com/posts/Advanced-Grunt-tooling)

--

* [Dynamic Grunt Targets Using Templates | oncletom.io](https://oncletom.io/2013/dynamic-grunt-targets-using-templates/)

--

* [Easy JavaScript Documentation with YUIDocs and Grunt.js | Tech.Pro](http://tech.pro/tutorial/1729/easy-javascript-documentation-with-yuidocs-and-gruntjs)

* [[GitHub] vitorbritto / gruntify](https://github.com/vitorbritto/gruntify) - A Sweet way to use Grunt


##### Ferramentas

* [Grunt Task Runner Extension for Chrome Developer Tools](https://github.com/vladikoff/grunt-devtools)

* [Run grunt.js from IntelliJ](http://omar.gy/run-grunt-js-from-intellij/)

* [[GitHub] tvooo / sublime-grunt](https://github.com/tvooo/sublime-grunt) - A Grunt plugin for Sublime Text


##### Plugins

* [Grunt.js Plugins](http://gruntjs.com/plugins)

--

* [[GitHub] shakyShane / grunt-browser-sync](https://github.com/shakyShane/grunt-browser-sync) - Grunt Task for keeping multiple browsers & devices in sync when building websites.

  * [BrowserSync + Yeoman Webapp Generator | QuickCast](http://quick.as/q0rsnr8)

--

* [[GitHub] tschaub / grunt-newer](https://github.com/tschaub/grunt-newer) - Configure Grunt tasks to run with newer files only

--

* [[GitHub] yeoman / grunt-filerev](https://github.com/yeoman/grunt-filerev) - Static asset revisioning through file content hash

--

* [[GitHub] jgallen23 / grunt-inline-css](https://github.com/jgallen23/grunt-inline-css) - Grunt task for turning an html file with linked css to inline css. Great for emails.

* [[GitHub] sindresorhus / time-grunt](https://github.com/sindresorhus/time-grunt) - Displays the elapsed execution time of grunt tasks - Node.js module

* [[GitHub] terrykingcha / grunt-depconcat](https://github.com/terrykingcha/grunt-depconcat) - Concat depended files

--

* [[GitHub] karlgoldstein / grunt-html2js](https://github.com/karlgoldstein/grunt-html2js) - Grunt plugin for converting AngularJS templates to JavaScript

* [[GitHub] hariadi / grunt-wp2md](https://github.com/hariadi/grunt-wp2md) - Convert WordPress XML to static Markdown files

* [[GitHub] scottstanfield / grunt-markdown-to-json](https://github.com/scottstanfield/grunt-markdown-to-json) 

* [[GitHub] alanshaw / grunt-markdown-pdf](https://github.com/alanshaw/grunt-markdown-pdf) - Grunt plugin to convert markdown documents to PDF. 

--

* [[GitHub] dylang / grunt-notify](https://github.com/dylang/grunt-notify) - Automatic Notifications when Grunt tasks fail

* [[GitHub] dylang / grunt-prompt](https://github.com/dylang/grunt-prompt) - Add interactive UI to your Gruntfile on the command line

--

* [[GitHub] Grunt-generate / grunt-generate](https://github.com/grunt-generate/grunt-generate) - Grunt task that generates files from user-defined templates

--

* [[GitHub] rubenv / grunt-git](https://github.com/rubenv/grunt-git) - Git commands for grunt

* [[GitHub] btford / grunt-merge-conflict](https://github.com/btford/grunt-merge-conflict) - Grunt plugin for preventing you from accidentally comitting a merge conflict into your project

* [[GitHub] thanpolas / grunt-github-pages](https://github.com/thanpolas/grunt-github-pages) - Push to gh-pages no problem

* [grunt-build-gh-pages](https://github.com/pajtai/grunt-build-gh-pages) - Grunt task to take build directory from current task and move it to another branch | examplo: [exploratory-javascript-tests](https://github.com/pajtai/exploratory-javascript-tests)

--

* [[GitHub] zonak / grunt-ftp-deploy](https://github.com/zonak/grunt-ftp-deploy) - Grunt task for code deployment over ftp

--

* [[GitHub] astronaughts / grunt-play](https://github.com/astronaughts/grunt-play) - play sound with grunt

  * [[GitHub] wlepinski / grunt-peao](https://github.com/wlepinski/grunt-peao)

--

* [[GitHub] ddprrt / connect-php](https://github.com/ddprrt/connect-php)

  * [The magic of grunt-contrib-connect, and how to run PHP with it | front-end technology talk](http://fettblog.eu/blog/2013/11/17/the-magic-of-grunt-contrib-connect-and-how-to-run-php-with-it/)

##### grunt plugins: proxy

* [[GitHub] drewzboto / grunt-connect-proxy](https://github.com/drewzboto/grunt-connect-proxy)

  * [Using grunt-connect-proxy | frontend technology talk](http://www.fettblog.eu/blog/2013/09/20/using-grunt-connect-proxy/)

##### grunt plugins: performance

* [[GitHub] tjgq / grunt-throttle](https://github.com/tjgq/grunt-throttle) - Grunt task for simulating slow connections

* [[GitHub] gmetais / grunt-devperf](https://github.com/gmetais/grunt-devperf/) - Helps front-end developers to maintain a good quality, based on phantomas and grunt-phantomas

##### grunt plugins: code analysis

* [[GitHub] rhiokim / grunt-sloc](https://github.com/rhiokim/grunt-sloc) - Source line of codes plugin for Grunt.js

* [[GitHub] vigetlabs / grunt-complexity](https://github.com/vigetlabs/grunt-complexity) - A JavaScript complexity analysis grunt task

* [[GitHub] ActivearkJWT / grunt-size-report](https://github.com/ActivearkJWT/grunt-size-report) - Genrate size report of your project

* [[GitHub] jsoverson / grunt-plato](https://github.com/jsoverson/grunt-plato) - Generate static analysis reports with plato through grunt


##### Dicas

* [maintainable grunt example](https://github.com/erkobridee/lab-nodejs/tree/master/javascript/grunt/maintainable-grunt) - on [GitHub] erkobridee / lab-nodejs

* [Grunt.js: Custom Tasks | Quick Left](http://quickleft.com/blog/grunt-js-custom-tasks)

* [Running Grunt tasks without grunt-cli](http://www.andrewduthie.com/post/running-grunt-tasks-without-grunt-cli/)

--

* [Grunt Boilerplate | Integralist](http://integralist.co.uk/Grunt-Boilerplate.html)

* [Using Grunt.js with CSS](http://blog.pamelafox.org/2012/05/using-gruntjs-with-css.html) | [[GitHub] source grunt file](https://github.com/pamelafox/5lide/blob/master/editor/grunt.js)

* [Otimize suas tarefas com o Grunt! | Luiz Felipe Tartarotti Fialho](http://www.felipefialho.com/blog/2013/grunt-voce-deveria-estar-usando/)

* [Using Grunt-contrib-livereload With Yeoman's Grunt-regarde](http://blog.jaredlaser.com/blog/2013/05/07/using-grunt-contrib-livereload-with-yeomans-grunt-regarde)

* [Dica Rápida: Utilizando LiveReload no Grunt | Vitor Britto](http://www.vitorbritto.com/blog/utilizando-livereload-no-grunt/)

* [Grunt Markdown - Markdown Preview using Grunt | James Morrin](http://www.treasonx.com/posts/GruntMarkDown.html)

* [[Gist] rhumaric / Gruntfile-connect-open.js](https://gist.github.com/rhumaric/5577257) - Sample configuration of grunt-contrib-connect and grunt-open to serve your project and open a browser tab to the appropriate URL

* [Making Maven GruntJS | Addy Osmani](http://addyosmani.com/blog/making-maven-grunt/)

* [Generate multi-resolution images for srcset with Grunt | Addy Osmani](http://addyosmani.com/blog/generate-multi-resolution-images-for-srcset-with-grunt/)

* [Tools for image optimization | Addy Osmani](http://addyosmani.com/blog/image-optimization-tools/)

* [Managing Bower Components with Grunt | Flippin Awesome](http://flippinawesome.org/2014/01/27/managing-bower-components-with-grunt/)

* [[GitHub] bevacqua / buildfirst / ch04 / 07_aws-deployments](https://github.com/bevacqua/buildfirst/tree/master/ch04/07_aws-deployments) - Walkthrough: Deploying to Amazon EC2 with Grunt 

* [Setup Grunt on Jenkins | sideroad](http://sideroad.secret.jp/articles/grunt-on-jenkins/) - Grunt is suitable for building JavaScript project as concat, minify, jshint and unit test. Jenkins is suitable for CI as using SCM polling, scheduler. I think these tools makes our development faster. This is sample of front-end javascript project and building with Grunt on Jenkins.

  * [[GitHub] sideroad / sample-jenkins-grunt](https://github.com/sideroad/sample-jenkins-grunt) - Sample project of build with Grunt on Jenkins


##### Testes

* [Building and Testing JavaScript With GruntJS](http://tanepiper.com/blog/2012/11/25/building-and-testing-javascript-with-gruntjs/)

* [Testing your JavaScript with Jasmine and Grunt](http://floatleft.com/notebook/testing-your-javascript-with-jasmine-and-grunt)

* [[GitHub] jsoverson / grunt-contrib-jasmine-example](https://github.com/jsoverson/grunt-contrib-jasmine-example) - Example application to help get you started using jasmine through grunt

* [[GitHub] netzzwerg / example-grunt-jasmine-require](https://github.com/netzzwerg/example-grunt-jasmine-require) - Example project for testing jasmine with requirejs and grunt

* [Backbone, RequireJS, Jasmine, PhantomJS, and Grunt](http://hdnrnzk.me/2013/01/10/backbone-requirejs-jasmine-phantomjs-and-grunt/)

* [Testing your responsive design with PhantomJS | Adnane Belmadiaf](http://daker.me/2013/07/testing-your-responsive-design-with-phantomjs.html)

* [Grunt - Synchronised Testing Between Browsers/Devices4 | Matt Bailey](http://blog.mattbailey.co/post/50337824984/grunt-synchronised-testing-between-browsers-devices)

* [Headless testing with Jasmine, PhantomJS and Grunt | simonsmith.io](http://simonsmith.io/headless-testing-with-jasmine-phantomjs-and-grunt/)


##### Exemplos de Uso

* [[GitHub] erkobridee / lab-nodejs / javascript / grunt](https://github.com/erkobridee/lab-nodejs/tree/master/javascript/grunt)

* [[GitHub] davidtucker / grunt-line-remover](https://github.com/davidtucker/grunt-line-remover) - A really simple Grunt plugin to remove lines from files based on regular expressions

* [[GitHub] felixlaumon / kickstart](https://github.com/felixlaumon/kickstart) - is a starter template for building your next web app. It allows you to dive right into writing actual code. Kickstart uses **_Grunt_** and **_Bower_** and includes LiveReload, LESS, Jade, RequireJS, and JSHint

* [Automatically download & use FrontEnd JS dependencies with Bower + Grunt boilerplate free](http://www.blogeek.com.ar/2013/04/25/automatically-download-use-frontend-js-dependencies-with-bower-grunt-boilerplate-free/)

* [[GitHub] wookiecooking / nwfaketop](https://github.com/wookiecooking/nwfaketop) - A GruntJS Compiler for Node-webkit Applications (OSX Based)


##### Construído sobre o Grunt.js

* [Lineman](http://www.linemanjs.com/) - Build awesome web apps, easily. Lineman got its name from finding that the word "grunt" was first used to describe unskilled railroad workers. Grunts that made the cut were promoted to linemen.

  * [[GitHub] linemanjs / lineman-angular-template](https://github.com/linemanjs/lineman-angular-template) - A Lineman Application Template using AngularJS

