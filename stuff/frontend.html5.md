# Front-End


<!-- toc -->
* [HTML5](#html5)
  * [Aprendizado](#aprendizado)
  * [Compatibilidade](#compatibilidade)
  * [Ferramentas](#ferramentas)
  * [Caso de Uso](#caso-de-uso)
  * [Dicas](#dicas)
    * [WebRTC](#webrtc)
    * [WebGL](#webgl)
    * [Game](#game)
    * [Game Development](#game-development)
    * [Storage](#storage)
    * [Performance](#performance)
    * [Server Sent Events](#server-sent-events)
    * [Full Screen API](#full-screen-api)
    * [File System/API](#file-systemapi)
  * [Bibliotecas](#bibliotecas)
    * [WebRTC](#webrtc)
    * [Text Search](#text-search)
    * [Gesture](#gesture)
    * [Storage](#storage)
    * [Animations](#animations)
    * [Physics](#physics)
    * [WebGL](#webgl)
    * [Games](#games)
      * [Game Engine](#game-engine)
  * [Desenvolvimento de Aplicações](#desenvolvimento-de-aplicações)
    * [Offline](#offline)
      * [Christophe Coenraets](#christophe-coenraets)
      * [FT Labs](#ft-labs)
      * [Icenium](#icenium)
    * [Mobile](#mobile)
      * [Firefox OS](#firefox-os)
      * [Apache Cordova & PhoneGap](#apache-cordova-phonegap)
        * [PhoneGap](#phonegap)
        * [BlackBerry](#blackberry)
    * [Desktop](#desktop)
    * [Desktop and Mobile](#desktop-and-mobile)

<!-- toc stop -->


## HTML5

> Refere-se a nova sintaxe do HTML, além de novos recursos para serem utilizados diretamento pelo web browser, conforme apresentados: [Slides | HTML5 Rocks](http://slides.html5rocks.com/) e [Entendendo quais APIs (realmente) fazem parte do HTML5 | Tableless](http://tableless.com.br/entendendo-quais-apis-realmente-fazem-parte-do-html5/)


### Aprendizado

* [WebPlatform.org — Your Web, documented](http://www.webplatform.org/)

* [html5.org](http://html5.org/)

* [Dive Into HTML5](http://diveintohtml5.com.br/) - livro online sobre HTML5, este link da versão em português

* [HTML5 Rocks](http://www.html5rocks.com/)

* [HTML5 Doctor](http://html5doctor.com/)

* [HTML5 MDN](https://developer.mozilla.org/pt-BR/docs/HTML/HTML5) - Mozilla Developer Network | [demos](https://developer.mozilla.org/en-US/demos/)

* [HTML5 Guia de Referência - Tabless](http://tableless.com.br/html5/)

* [HTML5 Demos and Examples](http://html5demos.com/)

* [HTML5 Bookmarks - daily news articles and bookmarks](http://html5bookmarks.com/)

* [HTML5 - 20 Things I Learned About Browsers and the Web](http://www.20thingsilearned.com/en-US/html5/1)

* [Introducing HTML5: Bruce Lawson and Remy Sharp](http://introducinghtml5.com/)

* [HTML5 Canvas Tutorials](http://www.html5canvastutorials.com/)

* [Learn HTML5, CSS3, Javascript and more](http://thecodeplayer.com/)

* [Adobe & HTML](http://html.adobe.com/)

* [Adobe DevNet - HTML5, CSS3, and JavaScript](http://www.adobe.com/devnet/html5.html)

* [MSDN - HTML 5, CSS3 e JavaScript](http://msdn.microsoft.com/pt-br/asp.net/hh442325.aspx)

* [Central HTML5 da SourceForge e Microsoft](http://centralhtml5.sourceforge.net/)

* [Facebook HTML5 Resource Center - Facebook Developers](https://developers.facebook.com/html5/)

* [HTML5 Myth Busting](https://hacks.mozilla.org/2012/11/html5-mythbusting/)

* [HTML5Labs | Microsoft](http://www.html5labs.com/)

--

* [The HTML 5 JavaScript API Index](http://html5index.org/)

* [Ultimate HTML5 Cheatsheat [Infographic] | Tech King](http://www.testking.com/techking/infographics/ultimate-html5-cheatsheat/)

* [HTML5 Security Cheatsheet](https://html5sec.org/)


### Compatibilidade

* [When JavaScript Feature Detection Fails | SitePoint](http://www.sitepoint.com/javascript-feature-detection-fails/)

--

* [Mobile HTML5 - compatibility](http://mobilehtml5.org/)

* [Can I use...?](http://caniuse.com/) - Compatibility tables for support of HTML5, CSS3, SVG and more in desktop and mobile browsers.

* [HTML5 Please - Use the new and shiny responsibly](http://html5please.com/)

* [The HTML5 Test](http://html5test.com/) - verifica o quando o web browser suporta os recursos do HTML5

* [haz.io › HTML5 & CSS3 Browser Capabilities](http://haz.io/)

* [HTML5 Readiness](http://html5readiness.com/)

* [HTML5 Features - Storage](http://www.html5rocks.com/en/features/storage)

* [The CSS3 Test](http://css3test.com/)

* [Is WebRTC ready yet?](http://iswebrtcreadyyet.com/) - Browser support scorecard

* [The Developer's Guide To Writing Cross-Browser JavaScript Polyfills | Addy Osmani](http://addyosmani.com/blog/writing-polyfills/)

* [Modernizr](http://modernizr.com/) is a JavaScript library that detects HTML5 and CSS3 features in the user’s browser | [HTML5 Cross Browser Polyfills](https://github.com/Modernizr/Modernizr/wiki/HTML5-Cross-Browser-Polyfills)

  * [Modernizr - documentação em português](http://www.andrebuzzo.com.br/bibliotecaModernizr/)
  
  * [Up and Running with Modernizr | Adobe Developer Connection](http://www.adobe.com/devnet/html5/articles/up-and-running-with-modernizr.html)


### Ferramentas

* [Initializr - Start your HTML5 project in 15 seconds!](http://www.initializr.com/)

* [Tools to Package Your HTML5 App for Mobile Devices](http://jster.net/blog/tools-to-package-your-html5-app-for-mobile-devices)

* [FireShell](http://getfireshell.com/) - fiercely quick front-end boilerplate and workflows

* [Google Web Designer](https://www.google.com/webdesigner/) - Create engaging, interactive HTML5-based designs and motion graphics that can run on any device.


### Caso de Uso

* [Next Generation Web Layout: National Geographic Forest Giant | HTML5 Rocks](http://www.html5rocks.com/en/tutorials/casestudies/natgeo/)


### Dicas

* [HTML5 Boilerplate](http://html5boilerplate.com/)

* [HTML5 Up!](http://html5up.net/) - Responsive HTML5 and CSS3 Site Templates

* [HTML5 - Async Scripts | Zeno Rocha](http://zenorocha.com/html5-async-scripts/)

* [All About HTML5 tag canvas | SmartBear](http://blog.smartbear.com/software-quality/bid/283454/All-About-HTML5)

* [The progress element | HTML5 Doctor](http://html5doctor.com/the-progress-element/)

* [New HTML5 Form Input Types](http://cdn.sixrevisions.com/demos/0345-new_html5_form_input_types/new-html5-form-input-types.html)

* [HTML5 Input Types Alternative | David Walsh Blog](http://davidwalsh.name/html5-input-types-alternative)

* [What you need to know about HTML5 forms | TechRepublic](http://www.techrepublic.com/blog/web-designer/what-you-need-to-know-about-html5-forms/)

* [5 HTML5 Javascript APIs to keep an eye on](http://daker.me/2013/06/5-html5-javascript-apis-to-keep-an-eye-on.html)

* [Baterry API | Loop Infinito](http://loopinfinito.com.br/2013/03/21/battery-api/)

--

* [Canvas Inspection using Chrome DevTools - HTML5 Rocks](http://www.html5rocks.com/en/tutorials/canvas/inspection/)

* [Exploring canvas drawing techniques | Perfection kills](http://perfectionkills.com/exploring-canvas-drawing-techniques/)

* [Build a JavaScript Particle System in 200 Lines | HTML5 Hub](http://html5hub.com/build-a-javascript-particle-system/)

* [N-body planar choreographies: illustrating mathematics in HTML5 canvas |  Rectangle World](http://rectangleworld.com/blog/archives/1018) - HTML5 Canvas and JavaScript: Tutorials and Experiments

* [Using blend modes in HTML Canvas | Web Platform Team Blog](http://blogs.adobe.com/webplatform/2014/02/24/using-blend-modes-in-html-canvas/)

* [Tiny Raytracer | Gabriel Gambetta](http://www.gabrielgambetta.com/tiny_raytracer.html)

--

* [How to prefetch video/audio files for uninterrupted playback in HTML5 video/audio | Thundering Herd](http://blog.pearce.org.nz/2014/02/how-to-prefetch-videoaudio-files-for.html)

* [Capturing Audio & Video in HTML5 - HTML5 Rocks](http://www.html5rocks.com/en/tutorials/getusermedia/intro/)

* [Making HTML5 audio actually work on mobile](http://pupunzi.open-lab.com/2013/03/13/making-html5-audio-actually-work-on-mobile/)

* [How to Generate Noise with the Web Audio API | Noisehack](http://noisehack.com/generate-noise-web-audio-api/)

* [Custom Audio Effects in JavaScript with the Web Audio API | Noisehack](http://noisehack.com/custom-audio-effects-javascript-web-audio-api/)

* [How to Build a Supersaw Synthesizer with the Web Audio API | Noisehack](http://noisehack.com/how-to-build-supersaw-synth-web-audio-api/)

* [Dynamic Audio Generation In the Browser : a JavaScript Synthesizer](http://keithwhor.com/music/)

* [Writing Web Audio API code that works in every browser | Mozilla Hacks](https://hacks.mozilla.org/2013/08/writing-web-audio-api-code-that-works-in-every-browser/)

* [Frequency Modulation (FM) with Web Audio API | @GreWeb](http://greweb.me/2013/08/FM-audio-api/) | [jsfiddle](http://jsfiddle.net/greweb/s2MMR/19/)

--

* [JavaScript Dubstep Generator](http://www.mazbox.com/synths/dubstep/) - Uma lib que gera efeitos no canvas com ondas sonoras de uma música

* [HTML5 Video and Background Images](http://www.iandevlin.com/blog/2013/03/html5/html5-video-and-background-images)

* [[Speaker Deck] Augmented Reality in JavaScript](https://speakerdeck.com/zenorocha/augmented-reality-in-javascript) - by Zeno Rocha

  * [Realidade Aumentada com HTML5 | InfoQ BR](http://www.infoq.com/br/presentations/realidade-aumentada-html5)
  
* [[codepen.io] Spirograph in HTML 5](http://codepen.io/cwolves/pen/gykbc)

--

* [Introduction to WebSockets | Tech.Pro](http://tech.pro/tutorial/1167/introduction-to-websockets)

* [Configuring & Optimizing WebSocket Compression | igvita.com](http://www.igvita.com/2013/11/27/configuring-and-optimizing-websocket-compression/)

--

* [HTML5 Geolocation API - Specification and Usages | ST Solutions](http://stsbd.com/html5-geolocation-api-specifications-usages/)

* [Está perdido? Geolocalização! | Tableless](http://tableless.com.br/esta-perdido-geolocalizacao/) - Entendendo como utilizar a API de Geolocalização (geolocation) do HTML5 com Javascript.

--

* [HTML5 Web Notification](http://jaydson.org/html5-web-notifications/)

* [Criando notificações desktop com HTML5 | Andre Loureiro](http://andrel.me/criando-notificacoes-desktop-com-html5/)

--

* [[GitHub] pmneila / jsexp](https://github.com/pmneila/jsexp) - Some simulation experiments in JavaScript


#### WebRTC

* [WebRTC.org](http://www.webrtc.org/)

* [WebRTC: Update and Workarounds | Mozilla Hacks](https://hacks.mozilla.org/2013/09/webrtc-update-and-workarounds/)

* [[Speaker Deck] WebRTC Data Black Magic](https://speakerdeck.com/feross/webrtc-data-black-magic)

* [[YouTube] Real-time communication with WebRTC: Google I/O 2013](https://www.youtube.com/watch?v=p2HzZkd2A40)

* [WebRTC data channels: WebRTC data channels for high performance data exchange | HTML5 Rocks](http://www.html5rocks.com/en/tutorials/webrtc/datachannels/)

--

* [Licode](http://lynckia.com/licode/) - Open Source Communication Provider

* [Talky](https://talky.io/) - Group video chat and screen sharing


#### WebGL

* [WebGL Fundamentals | HTML5 ROCKS](http://www.html5rocks.com/en/tutorials/webgl/webgl_fundamentals/)

* [This is a list of all the WebGL related activities happening on the web](http://www.khronos.org/webgl/wiki/User_Contributions) 

* [How to write portable WebGL | CodeFlow](http://codeflow.org/entries/2013/feb/22/how-to-write-portable-webgl/)

* [WebGL Debugging and Profiling Tools | Real-Time Rendering](http://www.realtimerendering.com/blog/webgl-debugging-and-profiling-tools/)

* [9 WebGL Demo Examples Experiments | CSS Matter](http://cssmatter.com/blog/9-webgl-demo-examples-experiments/)

* [Fusing WebGL, CSS 3D and HTML - Zero to Sixty in One Second | Acko.net](http://acko.net/blog/zero-to-sixty-in-one-second/)

* [Using WebGL to Add 3D Effects to Your Website | HTML5 Hub](http://html5hub.com/using-webgl-to-add-3d-effects-to-your-website)

* [Barry Martin's Hopalong Orbits Visualizer - WebGL Experiment](http://iacopoapps.appspot.com/hopalongwebgl/) - An interactive flight through attractor orbits generated using Barry Martin's Hopalong formula.

* [Three.js and Babylon.js: a Comparison of WebGL Frameworks | SitePoint](http://www.sitepoint.com/three-js-babylon-js-comparison-webgl-frameworks/)

* [WebGL With Three.js: Basics | Nettuts+](http://net.tutsplus.com/tutorials/javascript-ajax/webgl-with-three-js-basics/)

* [Live editing WebGL shaders with Firefox Developer Tools | Mozilla Hacks](https://hacks.mozilla.org/2013/11/live-editing-webgl-shaders-with-firefox-developer-tools/)

* [WebGL – working with GLSL source files | pheelicks.com](http://www.pheelicks.com/2013/12/webgl-working-with-glsl-source-files/)


#### Game

* [HTML5 Gamepad Tester](http://html5gamepad.com/)

--

* [Largest Directory of HTML5 Games](http://html5games.com/)

* [FightCode](http://fightcodegame.com/) - Killing Robots for Fun

* [Code Combat](http://codecombat.com/) - Learn to Code JavaScript by Playing a Game

* [Full Screen Mario](http://www.fullscreenmario.com/) : a purely HTML5 remake of the original Super Mario Bros game 

  * [[GitHub] Diogenesthecynic / FullScreenMario](https://github.com/Diogenesthecynic/FullScreenMario) - An HTML5 remake of the original Super Mario Brothers - expanded for wide screens.

* [[GitHub] ellisonleao / clumsy-bird](https://github.com/ellisonleao/clumsy-bird) - A MelonJS port of the famous Flappy Bird Game

* [The JavaScript Warrior](http://jswarrior.fusioncharts.com/) - Welcome to the JSWarrior Game. Unlike traditional games, you can't control your character through a keyboard or joystick. The only way you can control your character is through JavaScript.


#### Game Development

* [Screen size management in mobile HTML5 games | HTML5 Hub](http://html5hub.com/screen-size-management-in-mobile-html5-games/)

--

* [Announcing Artillery's Project Atlas, a Hardcore RTS for the Browser | The Artillery Blog](http://blog.artillery.com/2013/09/project-atlas-and-the-artillery-platform.html) - HTML5 Game Development and Engineering. The Artillery Platform, which Atlas is built upon, uses JavaScript and WebGL to deliver a high-quality, low-latency multiplayer gaming experience to anyone with a modern web browser. The platform is centered around 3D experiences with real-time multiplayer capability and strong community support. The JavaScript-based game engine features a component-entity design, a modern deferred rendering pipeline, and development tools designed to allow creative expression and super-fast iteration.

--

* [Criando um Game Loop em HTML5 | iMasters](http://imasters.com.br/front-end/javascript/criando-um-game-loop-em-html5/)

--

* [HTML5 Game Development | Eric Terpstra](http://slides.ericterpstra.com/html5games) - A presentation on getting started creating games on the web.

* [Getting Started With HTML5 Game Development | Mozilla Hacks](https://hacks.mozilla.org/2013/09/getting-started-with-html5-game-development/)

* [Using the Web Speech API to Create Voice Driven HTML5 Games | HTML5 Hub](http://html5hub.com/using-the-web-speech-api/)

* [[GitHub] idflood / ThreeNodes.js](https://github.com/idflood/ThreeNodes.js) - This is an attempt to make something like "vvvv" in javascript, html and webgl.

* [How to Learn Three.js for Game Development | Gamedevtuts+](http://gamedev.tutsplus.com/articles/how-to-learn/how-to-learn-three-js-for-game-development/)

* [Building a 3D MMO Using WebSocket | David Walsh Blog](http://davidwalsh.name/3d-websockets)

* [Criando um MMO 3D utilizando WebSockets | iMasters](http://imasters.com.br/desenvolvimento/criando-um-mmo-3d-utilizando-websockets/)

* [Building Multiplayer HTML5 Games with Cloak | Bocoup](http://weblog.bocoup.com/building-multiplayer-html5-games-with-cloak/)

* [The Pond – building a multi-platform HTML5 game | Mozilla Hacks](https://hacks.mozilla.org/2013/11/the-pond-building-a-multi-platform-html5-game/)


#### Storage

* [HTML5 Browser Storage: the Past, Present and Future | SitePoint](http://www.sitepoint.com/html5-browser-storage-past-present-future/)

* [Web SQL DB vs. IndexedDB | JavassCrypt](http://www.javasscrypt.com/html5/web-sql-db-vs-indexeddb/)

* [IndexedDB and Date Example](http://www.raymondcamden.com/index.cfm/2013/6/6/IndexedDB-and-Date-Example)

* [Working With IndexedDB | Nettuts+](http://net.tutsplus.com/tutorials/javascript-ajax/working-with-indexeddb/)

* [Using IndexedDB to Manage 3D WebGL Assets | SitePoint](http://www.sitepoint.com/using-indexeddb-manage-3d-webgl-assets/)

* [indexeddb file system | mode·switch](http://blog.modeswitch.org/indexeddb-file-system.html)

* [Client-Side Storage Options | Tech Pro](http://tech.pro/blog/1486/client-side-storage-options)

* [Storing Javascript objects in LocalStorage | DroidIT Blog](http://blog.droidit.eu/javascript-2/storing-javascript-objects-in-localstorage/)

* [localForage: Offline Storage, Improved | Mozilla Hacks](https://hacks.mozilla.org/2014/02/localforage-offline-storage-improved/)

* [HTML5 Web Storage - Teddy Garland | Coder Wall](https://coderwall.com/p/8awebg)

* [Dropbox Datastores and Drop-Ins | Nettuts+](http://net.tutsplus.com/tutorials/javascript-ajax/dropbox-datastores-and-drop-ins/)

* [[YoutTube] Google Cloud Storage - Getting started with the JavaScript Sample Application](https://www.youtube.com/watch?v=8ytpvQJNOU8) - This demonstration covers getting started with Google Cloud Storage using JavaScript

  * [[GitHub] GoogleCloudPlatform / storage-getting-started-javascript](https://github.com/GoogleCloudPlatform/storage-getting-started-javascript/) - This is a simple web-based example of calling the Google Cloud Storage API in JavaScript


#### Performance

* [Five things you can do to make HTML5 perform better](http://christianheilmann.com/2013/01/25/five-things-you-can-do-to-make-html5-perform-better/)

* [Native Speed on the Web: JavaScript and asm.js | Alon Zakai](http://kripken.github.io/mloc_emscripten_talk/sloop.html)


#### Server Sent Events

* [HTML5 e SSE (Server Sent Events) - Igor Costa](http://www.igorcosta.com/html5-e-sse-eventsource/) 

* [Push Notifications to the Browser With Server Sent Events](http://html5hacks.com/blog/2013/04/21/push-notifications-to-the-browser-with-server-sent-events/)


#### Full Screen API

* [Fullscreen API Specification](https://dvcs.w3.org/hg/fullscreen/raw-file/tip/Overview.html#api)

* [Using fullscreen mode | MDN](https://developer.mozilla.org/en-US/docs/Web/Guide/DOM/Using_full_screen_mode)


#### File System/API

* [Exploring the FileSystem APIs | HTML5 Rocks](http://www.html5rocks.com/en/tutorials/file/filesystem/) / [Ler arquivos em JavaScript usando as APIs do arquivo | HTML5 Rocks](http://www.html5rocks.com/pt/tutorials/file/dndfiles/)

* [File Reader | Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Web/API/FileReader)

* [Ler arquivos locais em JavaScript | HTML5 Rocks](http://www.html5rocks.com/pt/tutorials/file/dndfiles/)

* [Resize an Image Using Canvas, Drag and Drop and the File API | David Walsh Blog](http://davidwalsh.name/resize-image-canvas)

* [Creating a File Encryption App with JavaScript | Tutorialzine](http://tutorialzine.com/2013/11/javascript-file-encrypter/)


### Bibliotecas

* [5 of the Best Free HTML5 Presentation Systems](http://www.sitepoint.com/5-free-html5-presentation-systems/)

* [SlideCaptain - Modern online presentation tool](https://www.slidecaptain.com/) - Made with JavaScript, HTML5, CSS3, Bootstrap, MongoDB, Node.js and AngularJS.

--

* [[GitHub] hakimel / reveal.js](https://github.com/hakimel/reveal.js/) - The HTML Presentation Framework

  * [Example Presentations | reveal.js github wiki](https://github.com/hakimel/reveal.js/wiki/Example-Presentations)

  * [reveal.js is available on npm](https://npmjs.org/package/reveal.js)

  * [Reveal.js: criando apresentações no navegador | Tableless](http://tableless.com.br/reveal-js-criando-apresentacoes-no-navegador/)

  * [slid.es](http://slid.es/) - The easiest way to create and share beautiful presentations. Online presentation tool based on reveal.js

  * [[GitHub] piatra / kreator.js](https://github.com/piatra/kreator.js) - slide tool interface for reveal.js

      * [kreator](http://piatra.jit.su/)

      * [javascript nodejs kreator reveal.js | ROSEdu Summer of Code Blog](http://soc.rosedu.org/blog/?tag=javascript-nodejs-kreator-reveal-js)

--

* [deck.js](http://imakewebthings.com/deck.js/) - presentation engine

  * [[GitHub] imakewebthings / deck.js](https://github.com/imakewebthings/deck.js)

  * [[GitHub] thiagofelix / hackynote](https://github.com/thiagofelix/hackynote) - A presentation editor and preview based on markdown. Made for hackers

  * [[GitHub] jtrussell / bedecked](https://github.com/jtrussell/bedecked) - Turn markdown files into html presentations you can share with dropbox (or S3, or...)

--

* [bespoke.js](http://markdalgleish.com/projects/bespoke.js/) - DYI presentation micro-framework

  * [Bespoke.js: The Road to 1KB (Slides)](http://markdalgleish.github.io/presentation-bespoke.js-the-road-to-1kb/)

--

* [RgbQuant.js](https://github.com/leeoniya/RgbQuant.js) - an image quantization library

* [CamanJS - JavaScript Image Manipulation](http://camanjs.com/)

--

* [Drawingboard.js](http://leimi.github.io/drawingboard.js/) - a simple canvas based drawing app that you can integrate easily on your website.

--

* [Snap.svg](http://snapsvg.io/) - is designed for modern browsers and therefore supports the newest SVG features like masking, clipping, patterns, full gradients, groups, and more.

--

* [[GitHub] mark-rolich / RulersGuides.js](https://github.com/mark-rolich/RulersGuides.js) - Creates Photoshop-like guides and rulers interface on a web page | [Demo](http://mark-rolich.github.io/RulersGuides.js/)

--

* [[GitHub] maroslaw / rainyday.js](https://github.com/maroslaw/rainyday.js) - Simulating raindrops falling on a window (use canvas)

  * [Creating a Realistic Rain Effect with Canvas and JavaScript | Flippin' Awesome](http://flippinawesome.org/2013/09/23/creating-a-realistic-rain-effect-with-canvas-and-javascript/)

  * [rainyday.js | CreativeJS](http://creativejs.com/2013/09/rainyday-js/)

--

* [[GitHub] kovacsv / JSModeler](https://github.com/kovacsv/JSModeler) - A JavaScript framework to create and visualize 3D models.

--

* [[GitHub] vagnervjs / frame-player](https://github.com/vagnervjs/frame-player) - A video player without video files, just JSON. Based on 'images frames' thought to mobile devices!

--

* [[GitHub] auduno / clmtrackr](https://github.com/auduno/clmtrackr) - Javascript library for precise tracking of facial features via Constrained Local Models

--

* [[GitHub] TalAter / annyang](https://github.com/TalAter/annyang) - A javascript library for adding voice commands to your site, using speech recognition

* [Popcorn.js](http://popcornjs.org/) - The HTML5 Media Framework

* [Audio5js](http://zohararad.github.io/audio5js/) - The HTML Audio Compatibility Layer

* [[GitHub] EvandroLG / audioJS](https://github.com/EvandroLG/audioJS) - AudioJS is a agnostic lib cross-browser to work easily with the AudioContext API of HTML5.

* [[GitHub] meenie / 8bit.js](https://github.com/meenie/8bit.js) - 8Bit.js Audio Library - Write music using 8bit oscillation sounds

* [[GitHub]  meenie / band.js](https://github.com/meenie/band.js) - Music composer interface for the Web Audio API.

  * [Retro Game Music using Web Audio and Band.js  | Flippin' Awesome](http://flippinawesome.org/2013/09/09/retro-game-music-using-web-audio-and-band-js/)

* [Ion.Sound](http://ionden.com/a/plugins/ion.sound/en.html) - jQuery-plugin for playing sounds on events

* [[GitHub] eshiota / retro-audio-js](https://github.com/eshiota/retro-audio-js) - Web Audio API based retro player that give us that nostalgic feelings

  * [Retro.js Demo](http://eshiota.com/experiments/retrojs/) - Uma lib que usa a Web Audio API para tocar teclado usando uma representação em JSON de partituras de teclado, no site tem exemplo de 3 músicas

* [Pedalboard.js](http://dashersw.github.io/pedalboard.js/) - Open-source JavaScript framework for developing audio effects with Web Audio API

--

* [heatmap.js | Create HTML5 Heatmaps with Canvas and JavaScript](http://www.patrick-wied.at/static/heatmapjs/) | [Sample](http://www.heatmapjs.com/)

  * [High Performance JS heatmaps | Codeflow](http://codeflow.org/entries/2013/feb/04/high-performance-js-heatmaps/)


* [Chart.js](http://www.chartjs.org/) - Simple HTML5 Charts using the *canvas* tag

* [Aristochart](http://dunxrion.github.io/aristochart/) - Customizável e flexível biblioteca de gráficos em Canvas

* [HumbleFinance](http://www.humblesoftware.com/finance/index) is an HTML5 data visualization tool written as a demonstration of interactive graphing in HTML5.

* [CreateJS Studio](http://createjs.com/) - A suite of Javascript libraries & tools for building rich, interactive experiences with HTML5.

* [Fabric.js](http://fabricjs.com/) is a powerful and simple Javascript canvas library. Fabric provides interactive object model on top of canvas element Fabric also has SVG-to-canvas (and canvas-to-SVG) parser.

* [KineticJS](http://kineticjs.com/) - is an HTML5 Canvas JavaScript framework that enables high performance animations, transitions, node nesting, layering, filtering, caching, event handling for desktop and mobile applications, and much more.


* [Nanoko](http://nanoko.org/) - is a JavaScript modular framework enabling flexible and sustainable HTML5 applications development and their deployment on both mobile and desktop applications. [Getting Started](http://nanoko.org/?page=gettingstarted) | *utiliza o maven como base para o projeto* |

* [Resumable.js](http://www.resumablejs.com/) - A JavaScript library providing multiple simultaneous, stable and resumable **uploads** via the HTML5 File API

* [[GitHub] mailru / FileAPI](https://github.com/mailru/FileAPI) - a set of javascript tools for working with files. Multiupload, drag'n'drop and chunked file upload. Images: crop, resize and auto orientation 

* [jsPDF](http://jspdf.com/) - A HTML5 client-side solution for generating PDFs.

* [[GitHub] FileReader.js](http://bgrins.github.io/filereader.js/) - Read Files with JavaScript!

* [[GitHub] OptimalBits / fs.js](https://github.com/OptimalBits/fs.js) - This module provides a wrapper for the HTML5 File System API inspired in nodejs fs module

* [[GitHub] sindresorhus / screenfull.js](https://github.com/sindresorhus/screenfull.js) - Simple wrapper for cross-browser usage of the JavaScript Fullscreen API

* [[GitHub] maxogden / psd.js](https://github.com/maxogden/psd.js) - PSD Parser in JavaScript | [site](http://maxogden.github.io/psd.js/)


#### WebRTC

* [[GitHub] erbbysam / webRTCCopy](https://github.com/erbbysam/webRTCCopy) - A simple file sharing application using [webRTC-data.io](https://github.com/erbbysam/webRTC-data.io)


#### Text Search

* [lunr.js - A bit like Solr, but much smaller and not as bright](http://lunrjs.com/) - Simple full-text search in your browser

  * [Building a Full-Text Index in Javascript | Gary Sieling](http://garysieling.com/blog/building-a-full-text-index-in-javascript)

* [[GitHub] brianreavis / sifter.js](https://github.com/brianreavis/sifter.js) - A library for textually searching arrays and hashes of objects by property (or multiple properties). Designed specifically for autocomplete.


#### Gesture

* [[GitHub]  roboleary / LeapTrainer.js](https://github.com/roboleary/LeapTrainer.js) - A gesture learning and recognition framework for the Leap Motion

* [[GitHub] roboleary / LeapCursor.js](https://github.com/roboleary/LeapCursor.js) - Effortless Leap Motion support for websites

* [[GitHub] EightMedia / hammer.js](https://github.com/EightMedia/hammer.js/) - A javascript library for multi-touch gestures

* [[GitHub] soyjavi / QuoJS](https://github.com/soyjavi/quojs) - Micro JavaScript Library for Mobile Devices


#### Storage

* [TaffyDB](http://www.taffydb.com/) - The JavaScript Database

* [SpahQL](http://danski.github.io/spahql/) - Query, manipulate and manage JSON data effortlessly.

* [[GitHub] chambs / minidb](https://github.com/chambs/minidb) - a simple wraper for local/session storage DOM API management

* [[GitHub] tuxracer / simple-storage](https://github.com/tuxracer/simple-storage) - Simple localStorage / sessionStorage supporting objects and arrays

* [[GitHub] tantaman / LargeLocalStorage](https://github.com/tantaman/LargeLocalStorage) - Problem: You need to store a large amount of key-value based data in IE, Chrome, Safari, AND Firefox

* [JayData](http://jaydata.org/) - The cross-platform HTML5 data-management library for JavaScript

  * [GitHub / JayData](https://github.com/jaydata)

  * [Codeplex / JayData](https://jaydata.codeplex.com/)

* [[GitHub] lcavadas / Storage.js](https://github.com/lcavadas/Storage.js) - Javascript library that wraps storage logic ( localStorage, WebSQL, IndexedDB) for all browsers

* [lawnchair](http://brian.io/lawnchair/) - simple json storage

* [[GitHub] zefhemel / persistencejs](https://github.com/zefhemel/persistencejs) - is an asynchronous Javascript database mapper library. You can use it in the browser, as well on the server (and you can share data models between them).

* [LocalStorage with Amplify.js | TysonJS](http://tysonjs.com/blog/localstorage-with-amplify-js/)

* [[GitHub] justindeguzman / locstor](https://github.com/justindeguzman/locstor) - JavaScript helper library for HTML5 localStorage

* [[GitHub] mozilla / localForage](https://github.com/mozilla/localForage) - Offline storage, improved. 

  * [localForage: Offline Storage, Improved | Mozilla Hacks](https://hacks.mozilla.org/2014/02/localforage-offline-storage-improved/)

* [[GitHub] techfort / LokiJS](https://github.com/techfort/LokiJS) - javascript embedded / in-memory database

  * [LokiJS](http://lokijs.org/) - A lightweight javascript document oriented database

* [[GitHub] jensarps / IDBWrapper](https://github.com/jensarps/IDBWrapper) - A cross-browser wrapper for IndexedDB

* [[GitHub] aaronpowell / db.js](https://github.com/aaronpowell/db.js) - is a wrapper for IndexedDB to make it easier to work against 

* [[GitHub] keithwhor / FSO.js](https://github.com/keithwhor/FSO.js/) - JavaScript FileSystemObject library for temporary and permanent client-side file storage


#### Animations

* [[GitHub] sole / tween.js](https://github.com/sole/tween.js) - Javascript tweening engine

* [Turn.js](http://www.turnjs.com/) - The page flip effect in HTML5


#### Physics

* [PhysicsJS](http://wellcaffeinated.net/PhysicsJS/) - A modular, extendable, and easy-to-use physics engine for javascript

  * [Building a 2D Browser Game with PhysicsJS | Flippin' Awesome](http://flippinawesome.org/2013/12/02/building-a-2d-browser-game-with-physicsjs/)

* [Matter.js](http://brm.io/matter-js/) - is 2D physics engine for the web


#### WebGL

* [three.js](http://mrdoob.github.io/three.js/) - JavaScript 3D library

  * [Shader Particle Engine](http://squarefeet.github.io/ShaderParticleEngine/) - A GLSL-heavy particle engine for THREE.js. Based on Stemkoski's great particle engine 

  * [The Beginner's Guide to three.js | Treehouse Blog](http://blog.teamtreehouse.com/the-beginners-guide-to-three-js)

  * [How to build a game with Three.js | Creative Bloq](http://www.creativebloq.com/3d/how-build-game-threejs-121310131)  

* [Babylon Engine for HTML5](http://www.babylonjs.com/) - Babylon.js is a webgl / javascript 3D engine.

* [Voodoo](http://www.voodoojs.com/) - is a new Javascript framework that lets you easily mix 2D and 3D content together on the same page.


#### Games

* [[GitHub] FuzzYspo0N / realtime-multiplayer-in-html5](https://github.com/FuzzYspo0N/realtime-multiplayer-in-html5) - an example using node.js, socket.io and HTML5 Canvas to explain and demonstrate realtime multiplayer games in the browser.

* [Unreal Engine in the browser](http://www.unrealengine.com/html5/)

* [EndGate](http://endgate.net/) - a game framework to build powerful HTML5 games

* [Senshi | Zolmeister](http://www.zolmeister.com/2013/09/senshi-mmo-battle-royale-inspired-html5.html) - an open source MMO Battle-Royale inspired HTML5 game

* [Goo](http://www.gootechnologies.com/)

  * [[Vimeo] Creating a Goon in Goo Create](http://vimeo.com/77723187)

  * [Goo Engine](http://www.gootechnologies.com/products/engine/)

  * [Goo Create](http://www.gootechnologies.com/products/create/)


##### Game Engine

* [JSNES](http://fir.sh/projects/jsnes/) - A JavaScript NES emulator

* [Game Closure](http://www.gameclosure.com/) - _The Game Closure DevKit_. 100% JavaScript. Build your games faster than ever before! Native speed. Write HTML5 games that outperform the competition.

* [voxel.js * blocks in yo browser](http://voxeljs.com/)

* [Joy.JS](http://joyjs.org/) - A Joyful HTML5 2D Game Engine

* [Collie](http://jindo.dev.naver.com/collie) is a Javascript library that helps to create highly optimized animations and games using HTML 5. 

* [Construct 2](http://www.scirra.com/store/free-html5-game-engine) - The Free HTML5 Game Engine

* [enchant.js](http://enchantjs.com/) - A simple JavaScript framework for creating games and apps

* [IIOEngine](http://iioengine.com/) - An interactive app framework for HTML5 built with canvas and javascript

* [Phaser 1.0](http://phaser.io/) - Desktop and Mobile HTML5 Game Framework is released

* [[GitHub] beakable / isometric](https://github.com/beakable/isometric) - HTML5 Canvas Isometric Engine

* [[GitHub] suffick / Clarity](https://github.com/suffick/Clarity) - A simple, customisable and scriptable platform game engine. [Demo](http://codepen.io/suffick/details/CqIxk)

* [[GitHub] melonjs / melonJS](https://github.com/melonjs/melonJS) - a fresh & lightweight javascript game engine


### Desenvolvimento de Aplicações


#### Offline

* [MDN - Application Cache API](https://developer.mozilla.org/en-US/docs/HTML/Using_the_application_cache)

* [Can I use offline web applications?](http://caniuse.com/offline-apps) - Compatibility table for support of offline web applications in desktop and mobile browsers.

* [Apostilas da Caelum offline com Application Cache do HTML 5](http://blog.caelum.com.br/apostilas-da-caelum-offline-com-application-cache-do-html-5/)

* [Palestra : HTML5 offline e Application Cache | Sérgio Lopes](http://sergiolopes.org/palestra-appcache-html5-offline/)

* [Load Your Game Faster with AppCache | Learning Three.js](http://learningthreejs.com/blog/2013/03/22/load-your-game-faster-with-appcache/)

* [[YouTube] O elo perdido: sincronizando webapps html5 com o servidor (node.js)](https://www.youtube.com/watch?v=JlrwvNpUJpM) - [Slides](http://goo.gl/EBrYX)

* [A Comprehensive Guide to Taking your HTML5 Game Offline | HTML5 Gamer](http://blog.sklambert.com/a-comprehensive-guide-to-taking-your-html5-game-offline/)


##### Christophe Coenraets

* [Simple Offline Data Synchronization for Mobile Web and PhoneGap Applications](http://coenraets.org/blog/2012/05/simple-offline-data-synchronization-for-mobile-web-and-phonegap-applications/)

* [Building Mobile Apps with HTML and a Local Database](http://coenraets.org/blog/2012/04/building-mobile-apps-with-html-and-a-local-database/)

* [Top 10 Performance Techniques for PhoneGap and Hybrid Apps](http://coenraets.org/blog/2013/10/top-10-performance-techniques-for-phonegap-and-hybrid-apps-slides-available/) - Slides Available


##### FT Labs

* [Tutorial 4: History API in an offline HTML5 web app](http://labs.ft.com/2013/04/offline-html5-history-api/)


##### Icenium

* [Is This Thing On? (Part 1)](http://www.icenium.com/community/blog/icenium-team-blog/2013/04/23/is-this-thing-on-part-1) - Detect and manage online/offline connectivity in Web/mobile applications


#### Mobile

* [[SlideShare] How Can HTML Compete with Native?](http://www.slideshare.net/andreasc/how-can-html-compete-with-native)

--

* [Screensiz.es](http://screensiz.es/phone) is a nifty little database of screen specifications for the most popular devices on the market.

* [Tools to Package Your HTML5 App for Mobile Devices](http://jster.net/blog/tools-to-package-your-html5-app-for-mobile-devices)

* [Response JS: mobile-first responsive design in HTML5](http://responsejs.com/)

* [Default system fonts - Android / iOS6 / WP7 - 8](http://www.jordanm.co.uk/tinytype)

* [Touch Gesture Reference Guide | LukeW](http://www.lukew.com/ff/entry.asp?1071)

* [It’s not a web app. It’s an app you install from the web | Forecast Blog](http://blog.forecast.io/its-not-a-web-app-its-an-app-you-install-from-the-web/)

* [Aplicativos Híbridos, Android e o poder da WebView](http://itweb.com.br/blogs/aplicativos-hibridos-android-e-o-poder-da-webview/)

* [Uma tonelada de truques de Web mobile | DevCast](http://devcastbrasil.com/videos/uma-tonelada-de-truques-de-web-mobile/)

* [20 Excellent Wireframing Tools for Mobile | Mashable](http://mashable.com/2013/04/02/wireframing-tools-mobile/)

* [Fries: Prototype Android apps using HTML, CSS and JavaScript](http://jaunesarmiento.me/fries/)

* [Nativo ou Web? Técnicas e Dicas em JavaScript móvel | InfoQ Br](http://www.infoq.com/br/interviews/tecnicas-javascript-movel)

* [Ionic](http://ionicframework.com/) - The Most Advanced HTML5 Mobile App Framework. Ionic utilizes AngularJS in order to create a framework most suited to develop rich and robust applications. 

  * [Sample Mobile Application with Ionic and AngularJS | Christophe Coenraets](http://coenraets.org/blog/2014/02/sample-mobile-application-with-ionic-and-angularjs/)

  * [Ionic – Mobile UI Framework for PhoneGap/Cordova Developers | Devgirl's Weblog](http://devgirl.org/2014/01/20/ionic-mobile-ui-framework-for-phonegapcordova-developers/)


##### Firefox OS

* [Localizing Firefox OS Apps | Mozilla Hacks](https://hacks.mozilla.org/2013/08/localizing-firefox-os-apps/)

* [Guia Rápido de Desenvolvimento para Firefox OS](https://leanpub.com/guiarapidofirefoxos) - Criando apps com HTML5 para o Firefox OS (eBook)

* [[GitHub] tehsis / webinstaller](https://github.com/tehsis/webinstaller) - Helper for installing Mozilla webapps

* [[GitHub] robnyman / Firefox-OS-Boilerplate-App](https://github.com/robnyman/Firefox-OS-Boilerplate-App) - Creating Firefox OS apps


##### Apache Cordova & PhoneGap

* [PhoneGap, Cordova, and what’s in a name? | PhoneGap](http://phonegap.com/2012/03/19/phonegap-cordova-and-what%E2%80%99s-in-a-name/)

* [Apache Cordova](https://cordova.apache.org/) - is a platform for building native mobile applications using HTML, CSS and JavaScript.

* [Cordova + Web Best Practices | Gaunt Face - Matthew Gaunt](http://www.gauntface.co.uk/blog/2013/07/18/cordova-web-best-practices/) - Getting PhoneGap / Cordova up and running with Yeoman


###### PhoneGap

* [PhoneGap](http://phonegap.com/) is a free and open source framework that allows you to create mobile apps using standardized web APIs for the platforms you care about.

* [Adobe PhoneGap 3.0 Released](http://phonegap.com/blog/2013/07/19/adobe-phonegap-3.0-released/)

* [Phonegap 3.0 mais rápido e muito mais adaptável | Igor Costa](http://www.igorcosta.com/phonegap-3-0-mais-rapido-e-muito-mais-adaptavel/)

* [PhoneGap 3.0 - Stuff You Should Know | Devgirl's Weblog](http://devgirl.org/2013/09/05/phonegap-3-0-stuff-you-should-know/)

* [CPBR6 slides da palestra Phonegap | Igor Costa](http://www.igorcosta.com/slides-phonegap/)

* [PhoneGap Build - Package mobile apps in the cloud.](https://build.phonegap.com/) - Simply upload your HTML5, CSS, and JavaScript assets to the Adobe® PhoneGap™ Build cloud service and we do the work of compiling for you.


* [[SlideShare] Automating PhoneGap Build](http://www.slideshare.net/coldfumonkeh/automating-phonegap-build)

* [[YouTube] Mac Mini and Jenkins as a Phonegap Build Server](https://www.youtube.com/watch?&v=tcRXB3n-5qE)

* [[GitHub] Medic - Continuous integration setup for Apache Cordova](https://github.com/filmaj/medic)
  
* [Continuous Integration of iOS Projects using Jenkins, CocoaPods, and Kiwi](http://9elements.com/io/index.php/continuous-integration-of-ios-projects-using-jenkins-cocoapods-and-kiwi/)


* **Angular.js**

  * [PhoneGap and AngularJs, The Start | Tech Pro](http://tech.pro/tutorial/1336/phonegap-and-angularjs-the-start)

  * [PhoneGap and AngularJs, Notification Service | Tech Pro](http://tech.pro/tutorial/1349/phonegap-and-angularjs-notification-service)

  * [PhoneGap and AngularJS: In App Browser | Tech Pro](http://tech.pro/tutorial/1357/phonegap-and-angularjs-in-app-browser)

  * [Building PhoneGap Apps with AngularJS | Brian Ford](http://briantford.com/blog/angular-phonegap.html)

  * [AppGyver Steroids](http://www.appgyver.com/steroids) - Build PhoneGap based apps with native performance. Rapidly. 

  * [[GitHub] calvinl / ng-phonegap](https://github.com/calvinl/ng-phonegap) - Grunt workflow for building AngularJS applications on PhoneGap
  

* **Andrew Trice**

  * [Category : Phonegap / Apache Cordova](http://www.tricedesigns.com/category/cordova/)

  * [Performance & UX Considerations For Successful PhoneGap Apps](http://www.tricedesigns.com/2013/03/11/performance-ux-considerations-for-successful-phonegap-apps/)

  * [PhoneGap Legends – A Sample Game App](http://www.tricedesigns.com/2013/03/22/phonegap-legends-a-sample-game-app/)


* **Christophe Coenraets**
  
  * [PhoneGap and PhoneGap Build in 5 Minutes](http://coenraets.org/blog/2012/12/phonegap-and-phonegap-build-in-5-minutes/)

  * [Cordova (aka PhoneGap) 3.x Tutorial](http://coenraets.org/blog/cordova-phonegap-3-tutorial/)

  * [Architecting a PhoneGap Application: Video + Slides](http://coenraets.org/blog/2013/05/architecting-a-phonegap-application-video-slides/)

  * [Top 10 Performance Techniques for PhoneGap Applications](http://coenraets.org/blog/2013/05/top-10-performance-techniques-for-phonegap-applications/)

  * [Hardware-Accelerated Page Transitions for Mobile Web Apps / PhoneGap Apps](http://coenraets.org/blog/2013/03/hardware-accelerated-page-transitions-for-mobile-web-apps-phonegap-apps)

  * [[GitHub] ccoenraets / pull-to-refresh](https://github.com/ccoenraets/pull-to-refresh) - Example of Using Pull-To-Refresh in PhoneGap / Cordova apps

  * [How to upload pictures from a PhoneGap Application to Node.js (and other servers)](http://coenraets.org/blog/2013/09/how-to-upload-pictures-from-a-phonegap-application-to-node-js-and-other-servers-2/)

  * [How to Upload Pictures from a PhoneGap App to Amazon S3](http://coenraets.org/blog/2013/09/how-to-upload-pictures-from-a-phonegap-app-to-amazon-s3/)


###### BlackBerry

* [Criando seu primeiro App com BBUI.js e Webworks para BB10 | Igor Costa](http://www.igorcosta.com/criando-seu-primeiro-app-com-bbui-js-e-webworks-para-bb10/)



#### Desktop

* [[GitHub] coolaj86 / HelloNode](https://github.com/coolaj86/HelloNode) - An installable example node app

* [AppJS](http://appjs.org/) - for Linux, Windows and Mac using HTML, CSS and Javascript

* [Chrome - Packaged Apps](http://developer.chrome.com/apps/)

* [Desktop Apps with HTML5 and the Mozilla Web Runtime](https://hacks.mozilla.org/2012/05/desktop-apps-with-html5-and-the-mozilla-web-runtime/) | [Mozilla Apps](https://developer.mozilla.org/en-US/docs/Apps)

* [TideSDK - Create multi-platform desktop apps with HTML5, CSS3 and JavaScript](http://www.tidesdk.org/) - TideSDK formerly known as Titanium Desktop is the best way to create beautiful, unique desktop apps using your web development skills.

* [Create HTML5 Desktop Apps & Games - Developers | Pokki](https://developers.pokki.com/)

* [Introduction to HTML5 Desktop Apps With Node-Webkit | Nettuts+](http://net.tutsplus.com/tutorials/javascript-ajax/introduction-to-html5-desktop-apps-with-node-webkit/)


#### Desktop and Mobile

* [Appcelerator Titanium](http://www.appcelerator.com/platform/titanium-platform/)

  * [Wunderlist 2](https://www.wunderlist.com/) | [Code - GitHub](https://github.com/erkobridee/wunderlist)

    * [[GitHub] Wunderlist](https://github.com/wunderlist)
  

* [@zaedysayao](https://twitter.com/zaedysayao) : [Rio.js](http://www.riojs.org/) - [**[SlideShare]** Construindo aplicações Desktop com HTML, CSS e JS - Rio.JS Conference 2013](http://www.slideshare.net/javamanrj/construindo-aplicaes-desktop-com-html-css-e-js-riojs-conference) | [**[Github]** Fontes mostrados durante o primeiro RioJS Conference](https://github.com/javamanrj/riojs-conference)

