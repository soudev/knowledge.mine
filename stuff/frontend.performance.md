# Front-End


<!-- toc -->
* [Performance](#performance)
  * [Rendering](#rendering)
  * [CDN](#cdn)
    * [Fallback](#fallback)
    * [CDNs](#cdns)
  * [Dynamic (Script) Loading](#dynamic-script-loading)
    * [LABjs](#labjs)
    * [YepNope](#yepnope)

<!-- toc stop -->


## Performance

* [Como perder peso (no browser)](http://browserdiet.com/pt/) - O guia definitivo de performance para o desenvolvedor front-end

  * [[Speaker Deck] Como Perder Peso (no browser)](https://speakerdeck.com/zenorocha/como-perder-peso-no-browser/) - Apresentação do Zeno Rocha no Rio.js

--

* [[GitHub] davidsonfellipe / awesome-wpo](https://github.com/davidsonfellipe/awesome-wpo) - A curated list of Web Performance Optimization. Everyone can contribute here!

--

* [Website Performance Optimization Checklist](http://lab.abhinayrathore.com/website-performance-optimization-checklist/) - Website Performance Optimization Checklist for building high performace websites.

--

* [WURFL.io](http://wurfl.io/) - Client Side, meet Server Side

  * [Server-Side Device Detection With JavaScript | Smashing Magazine](http://www.smashingmagazine.com/2014/07/01/server-side-device-detection-with-javascript/)

--

* [9 ways to optimize your front end performance | Tech.Pro](http://tech.pro/tutorial/1254/9-ways-to-optimize-your-front-end-performance)

* [9 More Ways to Optimize Your Front End Performance | Tech.Pro](http://tech.pro/tutorial/1261/9-more-ways-to-optimize-your-front-end-performance)

* [Another 9 Ways to Optimize Your Front End Performance | Tech.Pro](http://tech.pro/tutorial/1400/another-9-ways-to-optimize-your-front-end-performance)

--

* [Need for Speed – How to Improve your Website Performance | Dev Bridge](http://www.devbridge.com/articles/need-for-speed-how-to-improve-your-website-performance/)

* [How we make RWD sites load fast as heck | Filament Group](http://www.filamentgroup.com/lab/performance-rwd.html)

--

* [Otimização de imagens com media queries | iMasters](http://imasters.com.br/front-end/css/otimizacao-de-imagens-com-media-queries/)

* [Qual é a velocidade de carregamento do seu site? | Caelum](http://blog.caelum.com.br/teste-a-velocidade-de-carregamento-do-seu-site/) - Seu site pode até carregar rápido no seu computador. Mas como ele fica numa conexão 3G? E em uma edge? e em uma 256kbps? Conheça algumas ferramentas que possibilitam enxergar como seu site fica numa conexão lenta.

* [Medindo performance e latência com a Navigation Timing API | Tableless](http://tableless.com.br/navigation-timing-api/)

* [Capturing – Improving Performance of the Adaptive Web](https://hacks.mozilla.org/2013/03/capturing-improving-performance-of-the-adaptive-web/)

* [How To Make Your Websites Faster On Mobile Devices | Smashing Mobile](http://mobile.smashingmagazine.com/2013/04/03/build-fast-loading-mobile-website/)

* [Kratu](http://google.github.com/kratu/) : client-side analysis framework to create simple and powerful renditions of data

* [Deploying JavaScript Applications | Alex Sexton](http://alexsexton.com/blog/2013/03/deploying-javascript-applications/)

* [Acochambramento - Deixe o embed do YouTube mais leve e personalizado no seu Blog | EvelRyu](http://evelryu.com.br/deixe-o-embed-do-youtube-mais-leve-e-personalizado-no-seu-blog/)

* [Performance Optimizing for Smart Layers | AddThis Blog](http://www.addthis.com/blog/2013/09/17/performance-optimizing-for-smart-layers)

--

* [sitespeed.io](http://www.sitespeed.io/) - is an open source tool that helps you analyze your website speed and performance based on performance best practices and metrics

* [WebPagetest](http://www.webpagetest.org/) - Website Performance and Optimization Test

* [PageSpeed](https://developers.google.com/speed/pagespeed/) - Analyze and optimize your website with PageSpeed tools to implement the web performance best practices

  * [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/)

--

* [Qual a dose certa de JavaScript | Tableless](http://tableless.com.br/qual-dose-certa-de-javascript/) - Um pouco de JavaScript não obstrusivo e quais as estratégias para garantir uma boa performance e acessibilidade em aplicações ricas.

* [The seven rules of unobtrusive JavaScript | Dev.Opera](http://dev.opera.com/articles/view/the-seven-rules-of-unobtrusive-javascrip/)

--

* [Loading webfonts with high performance on responsive websites](http://bdadam.com/blog/loading-webfonts-with-high-performance.html) - Optimally loading webfonts is not a trivial taks. Here is a simple guide, how to do it. No blinking, no blocking.

* [Better webfont loading with using localStorage and providing WOFF2 support | http://bdadam.com/](http://bdadam.com/blog/better-webfont-loading-with-localstorage-and-woff2.html)

--

* [Web Tracing Framework by Google](http://google.github.io/tracing-framework/) - Rich tools for instrumenting, analyzing, and visualizing web apps | [Github project](http://google.github.io/tracing-framework/)

    * [Web Tracing framework do Google ajuda você se livrar do código porco | Igor Costa](http://www.igorcosta.com/web-tracing-framework-do-google-codigo-porco/)


### Rendering

* [Solving rendering performance puzzles | JakeArchibald](http://jakearchibald.com/2013/solving-rendering-perf-puzzles/)

* [Optimising for 60fps everywhere | GoSquared Engineering](https://engineering.gosquared.com/optimising-60fps-everywhere-in-javascript)

* [[Speaker Deck] CSS Performance Tooling](https://speakerdeck.com/addyosmani/css-performance-tooling) - by Addy Osmani [2014/09/13]


### CDN

* [CDNperf](http://www.cdnperf.com/) - JavaScript CDN Performance in Numbers

--

* [A importância de uma CDN | iMasters](http://imasters.com.br/desenvolvimento/a-importancia-de-uma-cdn/) - definição: [CDN (Content Delivery Network)](http://pt.wikipedia.org/wiki/Content_delivery_network)

* [3 reasons why you should let Google host jQuery for you | Encosia](http://encosia.com/3-reasons-why-you-should-let-google-host-jquery-for-you/)

* [7 Reasons to use a Content Delivery Network](http://www.sitepoint.com/7-reasons-to-use-a-cdn/)

* [Cloudflare’s CDNJS vs. Google Hosted Libraries – SHOCKING Results](http://www.baldnerd.com/make-your-site-faster-cloudflares-cdnjs-vs-google-hosted-libraries-shocking-results/)

* [Schemeless URLs](http://log4dev.com/2013/06/14/schemeless-urls/) - recurso utilizado por alguns CDNs como Google por exemplo.

* [jsDelivr - The advanced open source public CDN | Mozilla Hacks](https://hacks.mozilla.org/2014/03/jsdelivr-the-advanced-open-source-public-cdn/)

--

* [Small things add up | Chris Hates Writing](http://chrishateswriting.com/post/68794699432/small-things-add-up) - How 4chan is saving 275GB each year and saving its users 46TB each *month* with one weird trick! (Well, two.) 


#### Fallback
  
* [JQuery CDN with fall back to local file](http://joeyiodice.com/jquery-cdn-with-fallback-to-local-file)

* [Fallback for CDN hosted jQuery](http://css-tricks.com/snippets/jquery/fallback-for-cdn-hosted-jquery/)

* [A Simple and Robust jQuery 1.4 CDN Failover in One Line](http://happyworm.com/blog/2010/01/28/a-simple-and-robust-cdn-failover-for-jquery-14-in-one-line/) 
* [[Gist] using yepnope for twitter js and css with local fallback](https://gist.github.com/joelclermont/3735026)
  
  
#### CDNs
  
* [GitHub as CDN](http://code.lancepollard.com/github-as-a-cdn/) - Cache your Javascripts, Stylesheets, and Web Assets with Github Pages

* [Google CDN](https://developers.google.com/speed/libraries/)

* [CDNJS](http://cdnjs.com/)

* [jsDelivr](http://www.jsdelivr.com/) - A free super-fast CDN for developers and webmasters

* [BootstrapCDN](http://www.bootstrapcdn.com/)

* [CreateJS CDN Libraries](http://code.createjs.com/)


### Dynamic (Script) Loading

* [JavaScript Madness: Dynamic Script Loading](http://unixpapa.com/js/dyna.html)

* [[SlideShare] JavaScript performance patterns](http://www.slideshare.net/stoyan/javascript-performance-patterns)

* [Adiar a análise de javascript, carregando scripts de forma assíncrona](http://lorindo.com/adiar-a-analise-de-javascript-carregando-scripts-de-forma-assincrona/)

* [Head JS :: The only script in your HEAD](http://headjs.com/)

* [[GitHub] berklee / nbl](https://github.com/berklee/nbl) - NBL is a tiny non-blocking JavaScript lazy loader

* [Aload - Loads images, scripts, styles, iframes, videos and audio asynchronously](https://github.com/pazguille/aload)  

* [[GitHub] toddmotto / echo](https://github.com/toddmotto/echo) - Simple raw JavaScript image lazy loading

* [conditioner.js](http://conditionerjs.com/) - A javascript library for loading and unloading behavior based on environment conditions.

* [[GitHub] mercadolibre / lazy.js](https://github.com/mercadolibre/lazy.js) - A tiny and dependency-free JavaScript library for lazy loading resources.

* [[GitHub] helixten / load-cdn](https://github.com/helixten/load-cdn) - Load Script over CDN with MD5 Checks

  * [Load Script over CDN with MD5 Checks | zubair](http://blog.zubair.io/load-cdn/)


#### LABjs
  
* [LABjs](http://labjs.com/) - Loading And Blocking JavaScript

* [Snippet to load LABjs itself dynamically](https://gist.github.com/getify/603980)
  

#### YepNope
  
* [yepnope.js | A Conditional Loader For Your Polyfills!](http://yepnopejs.com/)

* [An Introduction to YepNope.js | Nettuts+](http://net.tutsplus.com/tutorials/javascript-ajax/easy-script-loading-with-yepnope-js/)

