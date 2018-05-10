# Front-End

<!-- toc -->
* [HTML5](#html5)
  * [Aprendizado](#aprendizado)
  * [Compatibilidade](#compatibilidade)
  * [Ferramentas](#ferramentas)
  * [Caso de Uso](#caso-de-uso)
  * [Dicas](#dicas)
    * [dicas: WebRTC](#dicas-webrtc)
    * [dicas: WebGL](#dicas-webgl)
    * [dicas: Game](#dicas-game)
    * [dicas: Desenvolvimento de Jogos](#dicas-desenvolvimento-de-jogos)
    * [dicas: Armazenamento](#dicas-armazenamento)
    * [dicas: Performance](#dicas-performance)
    * [dicas: Server Sent Events](#dicas-server-sent-events)
    * [dicas: Full Screen API](#dicas-full-screen-api)
    * [dicas: File System/API](#dicas-file-systemapi)
  * [Bibliotecas](#bibliotecas)
    * [Presentation System](#presentation-system)
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

* [Canvas Tutorial](http://billmill.org/static/canvastutorial/)

* [Learn HTML5, CSS3, Javascript and more](http://thecodeplayer.com/)

* [Adobe & HTML](http://html.adobe.com/)

* [Adobe DevNet - HTML5, CSS3, and JavaScript](http://www.adobe.com/devnet/html5.html)

* [MSDN - HTML 5, CSS3 e JavaScript](http://msdn.microsoft.com/pt-br/asp.net/hh442325.aspx)

* [Central HTML5 da SourceForge e Microsoft](http://centralhtml5.sourceforge.net/)

* [Facebook HTML5 Resource Center - Facebook Developers](https://developers.facebook.com/html5/)

* [HTML5 Myth Busting](https://hacks.mozilla.org/2012/11/html5-mythbusting/)

* [HTML5Labs | Microsoft](http://www.html5labs.com/)

--

* [Accessibility Features of HTML5](http://www.w3.org/Talks/2014/0317-HTML5-A11Y/) - With Mark Sadecki, W3C / Web Accessibility Initiative

--

* [The HTML 5 JavaScript API Index](http://html5index.org/)

* [Ultimate HTML5 Cheatsheat [Infographic] | Tech King](http://www.testking.com/techking/infographics/ultimate-html5-cheatsheat/)

* [HTML5 Security Cheatsheet](https://html5sec.org/)


### Compatibilidade

* [When JavaScript Feature Detection Fails | SitePoint](http://www.sitepoint.com/javascript-feature-detection-fails/)

--

* [Mobile HTML5 - compatibility](http://mobilehtml5.org/)

* [[Slides] The Android Browser](http://slides.com/html5test/the-android-browser)

--

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

* [Internet Explorer Web Platform Status and Roadmap | status.modern.IE](http://status.modern.ie/)


### Ferramentas

* [Initializr - Start your HTML5 project in 15 seconds!](http://www.initializr.com/)

* [Tools to Package Your HTML5 App for Mobile Devices](http://jster.net/blog/tools-to-package-your-html5-app-for-mobile-devices)

* [FireShell](http://getfireshell.com/) - fiercely quick front-end boilerplate and workflows

* [Google Web Designer](https://www.google.com/webdesigner/) - Create engaging, interactive HTML5-based designs and motion graphics that can run on any device.

* [Canva](https://www.canva.com/) - gives you everything you need to design blog graphics, presentations, Facebook covers, flyers, posters, invitations and so much more.


### Caso de Uso

* [Next Generation Web Layout: National Geographic Forest Giant | HTML5 Rocks](http://www.html5rocks.com/en/tutorials/casestudies/natgeo/)

* [Chrome Music Lab](https://musiclab.chromeexperiments.com/)


### Dicas

* [HTML5 Boilerplate](http://html5boilerplate.com/)

* [HTML5 Up!](http://html5up.net/) - Responsive HTML5 and CSS3 Site Templates

* [HTML5 - Async Scripts | Zeno Rocha](http://zenorocha.com/html5-async-scripts/)

* [The progress element | HTML5 Doctor](http://html5doctor.com/the-progress-element/)

* [New HTML5 Form Input Types](http://cdn.sixrevisions.com/demos/0345-new_html5_form_input_types/new-html5-form-input-types.html)

* [HTML5 Input Types Alternative | David Walsh Blog](http://davidwalsh.name/html5-input-types-alternative)

* [What you need to know about HTML5 forms | TechRepublic](http://www.techrepublic.com/blog/web-designer/what-you-need-to-know-about-html5-forms/)

* [5 HTML5 Javascript APIs to keep an eye on](http://daker.me/2013/06/5-html5-javascript-apis-to-keep-an-eye-on.html)

* [Baterry API | Loop Infinito](http://loopinfinito.com.br/2013/03/21/battery-api/)

* [Using Device Orientation in HTML5 | Site Point](http://www.sitepoint.com/using-device-orientation-html5/)

--

* [[GitHub] raphamorim / awesome-canvas](https://github.com/raphamorim/awesome-canvas) - A curated list of awesome HTML5 Canvas with examples, related articles and posts.

* [All About HTML5 tag canvas | SmartBear](http://blog.smartbear.com/software-quality/bid/283454/All-About-HTML5)

* [[Speaker Deck] Playground with canvas - Raphael Amorim](https://speakerdeck.com/raphamorim/playground-with-canvas) - Canvas é uma tela de bitmap que pode ser usada para a renderização de elementos gráficos ou outras imagens visuais rapidamente. No HTML5 ele permite que se desenhem elementos gráficos usando JavaScript. Vamos abordar funcionalidades e recursos e porque você deveria estar pensando em utilizar o canvas no seu próximo projeto.

* [Canvas Inspection using Chrome DevTools - HTML5 Rocks](http://www.html5rocks.com/en/tutorials/canvas/inspection/)

* [Exploring canvas drawing techniques | Perfection kills](http://perfectionkills.com/exploring-canvas-drawing-techniques/)

* [HTML5 Canvas Save Drawing as an Image | HTML5 Canvas Tutorials](http://www.html5canvastutorials.com/advanced/html5-canvas-save-drawing-as-an-image/)

* [Saving Canvas Data as an Image | Tech.pro](http://tech.pro/tutorial/1084/saving-canvas-data-as-an-image)

* [Quick one: using download attribute on links to save Canvas as PNG | Christian Heilmann](http://christianheilmann.com/2014/04/22/quick-one-using-download-attribute-on-links-to-save-canvas-as-png/)

* [[GitHub] hongru / canvas2image](https://github.com/hongru/canvas2image) - a tool for saving or converting canvas as img

* [[GitHub] niklasvh / html2canvas](https://github.com/niklasvh/html2canvas) - Screenshots with JavaScript

* [[GitHub] viliusle / Hermite-resize](https://github.com/viliusle/Hermite-resize) - Image resize/resample using Hermite filter with JavaScript.

* [Resizing an image in an HTML5 canvas | StackOverflow](https://stackoverflow.com/questions/2303690/resizing-an-image-in-an-html5-canvas)

* [HTML5 image upload, resize and crop | CodeForest](http://www.codeforest.net/html5-image-upload-resize-and-crop)

* [Resizing and Cropping Images with Canvas | Codrops](http://tympanus.net/codrops/2014/10/30/resizing-cropping-images-canvas/)

* [[GitHub] fengyuanchen / cropperjs](https://github.com/fengyuanchen/cropperjs) - JavaScript image cropper

* [[GitHub] viliusle / miniPaint](https://github.com/viliusle/miniPaint) - online image editor

* [Build a JavaScript Particle System in 200 Lines | HTML5 Hub](http://html5hub.com/build-a-javascript-particle-system/)

* [N-body planar choreographies: illustrating mathematics in HTML5 canvas |  Rectangle World](http://rectangleworld.com/blog/archives/1018) - HTML5 Canvas and JavaScript: Tutorials and Experiments

* [Using blend modes in HTML Canvas | Web Platform Team Blog](http://blogs.adobe.com/webplatform/2014/02/24/using-blend-modes-in-html-canvas/)

* [Tiny Raytracer | Gabriel Gambetta](http://www.gabrielgambetta.com/tiny_raytracer.html)

* [Realistic terrain in 130 lines | PlayfulJS](http://www.playfuljs.com/realistic-terrain-in-130-lines/)


* [[GitHub] felipenmoura / js-chroma-key](https://github.com/felipenmoura/js-chroma-key) - A chroma key effect made in JavaScript, HTML5 and CSS3 in 100 lines of js

  * [O poder do canvas em 100 linhas de JS | InfoQ Br](http://www.infoq.com/br/presentations/o-poder-do-canvas-em-100-linhas-de-js)

* [Building an HTML5 green screen (Chroma key) dynamic video player | Mark Mower - Digital Marketing Agency](http://www.metia.com/london/mark-mower/2012/12/building-an-html5-green-screen-(chroma-key)-dynamic-video-player/)

  * [HTML 5 Real time video chroma key (green screen)](http://www.xindustry.com/html5greenscreen/)

--

* [MicIO](http://colinbookman.com/2014/03/23/micio/) – HTML5 to MicroController Communication through a headphone jack

  * [[GitHub] cobookman / HTML5.MicIO](https://github.com/cobookman/HTML5.MicIO)

--

* [How to prefetch video/audio files for uninterrupted playback in HTML5 video/audio | Thundering Herd](http://blog.pearce.org.nz/2014/02/how-to-prefetch-videoaudio-files-for.html)

* [Capturing Audio & Video in HTML5 - HTML5 Rocks](http://www.html5rocks.com/en/tutorials/getusermedia/intro/)

* [Making HTML5 audio actually work on mobile](http://pupunzi.open-lab.com/2013/03/13/making-html5-audio-actually-work-on-mobile/)

* [Introduction to Web Audio API | CSS-Tricks](https://css-tricks.com/introduction-web-audio-api/) - 2017/03/06

* [How to Generate Noise with the Web Audio API | Noisehack](http://noisehack.com/generate-noise-web-audio-api/)

* [Custom Audio Effects in JavaScript with the Web Audio API | Noisehack](http://noisehack.com/custom-audio-effects-javascript-web-audio-api/)

* [How to Build a Supersaw Synthesizer with the Web Audio API | Noisehack](http://noisehack.com/how-to-build-supersaw-synth-web-audio-api/)

* [Dynamic Audio Generation In the Browser : a JavaScript Synthesizer](http://keithwhor.com/music/)

* [Writing Web Audio API code that works in every browser | Mozilla Hacks](https://hacks.mozilla.org/2013/08/writing-web-audio-api-code-that-works-in-every-browser/)

* [Frequency Modulation (FM) with Web Audio API | @GreWeb](http://greweb.me/2013/08/FM-audio-api/) | [jsfiddle](http://jsfiddle.net/greweb/s2MMR/19/)

* [Creating Sound with the Web Audio API and Oscillators | Flippin' Awesome](http://flippinawesome.org/2014/03/31/creating-sound-with-the-web-audio-api-and-oscillators/)

--

* [JavaScript Dubstep Generator](http://www.mazbox.com/synths/dubstep/) - Uma lib que gera efeitos no canvas com ondas sonoras de uma música

--

* [HTML5 Video and Background Images](http://www.iandevlin.com/blog/2013/03/html5/html5-video-and-background-images)

* [html5 video streaming from google drive](http://sourcey.com/html5-video-streaming-from-google-drive/)

* [Adding captions and subtitles to HTML5 video | MDN](https://developer.mozilla.org/en-US/Apps/Build/Manipulating_media/Adding_captions_and_subtitles_to_HTML5_video)

* [[GitHub] sampotts / plyr](https://github.com/sampotts/plyr) - A simple HTML5, YouTube and Vimeo player

--

* [[Speaker Deck] Augmented Reality in JavaScript](https://speakerdeck.com/zenorocha/augmented-reality-in-javascript) - by Zeno Rocha

  * [Realidade Aumentada com HTML5 | InfoQ BR](http://www.infoq.com/br/presentations/realidade-aumentada-html5)

* [[codepen.io] Spirograph in HTML 5](http://codepen.io/cwolves/pen/gykbc)

--

* [Using Web Workers - Web APIs | MDN](https://developer.mozilla.org/en-US/docs/Web/API/Web_Workers_API/Using_web_workers)

* [[GitHub] developit / stockroom](https://github.com/developit/stockroom) - Offload your store management to a worker

--

* Service Workers

  * [[GitHub] delapuente / service-workers-101](https://github.com/delapuente/service-workers-101) - An infographic to summarize the most important parts of the Service Workers' API

  * [A beginner’s guide to Service Workers | Samsung Internet Developers – Medium](https://medium.com/samsung-internet-dev/a-beginners-guide-to-service-workers-f76abf1960f6) - 2017/07/25

  * [ServiceWorker: A revolução da plataforma Web | BrasilJS](https://braziljs.org/blog/service-worker-a-revolucao-da-plataforma-web/) - 2016/04/04

  * [Making a Simple Site Work Offline with ServiceWorker | ponyfoo](https://ponyfoo.com/articles/simple-offline-site-serviceworker)

  * [Asset caching with service worker | Medium by @philipp.schaechtele](https://medium.com/@philipp.schaechtele/asset-caching-with-service-worker-c40dcda43842)

  * [Service Workers replacing AppCache: a sledgehammer to crack a nut | Medium by @firt](https://medium.com/@firt/service-workers-replacing-appcache-a-sledgehammer-to-crack-a-nut-5db6f473cc9b)

* Web Workers

  * [Mais Válvulas para seu Javascript | Tableless](http://tableless.com.br/mais-valvulas-para-seu-javascript/) - 2015/10/15

    * [[GitHub] ganexasi / webworker](https://github.com/ganexasi/webworker)

  * [Parallel Processing in JS | Advanced Web Machinery](https://advancedweb.hu/2016/08/09/parallel-processing-in-js/) - 2016/08/09

  * [[GitHub] mchaov / WebWorkers](https://github.com/mchaov/WebWorkers) - Demos with and without web workers

--

* [Introduction to WebSockets | Tech.Pro](http://tech.pro/tutorial/1167/introduction-to-websockets)

* [Configuring & Optimizing WebSocket Compression | igvita.com](http://www.igvita.com/2013/11/27/configuring-and-optimizing-websocket-compression/)

* [Simple WebSockets example to stream real-time events | Kim Rudolph](http://kimrudolph.de/blog/spring-4-websockets-tutorial/)

* [Tutorial: Pushing browser updates using WebSockets in Glassfish | jaxenter.com](http://jaxenter.com/tutorial-pushing-browser-updates-using-websockets-in-glassfish-46817.html)

* [Socket.io](http://socket.io/)

  * [Introducing Socket.IO 1.0 | Socket.io](http://socket.io/blog/introducing-socket-io-1-0/)

  * [Building a Real-time SMS Voting App with Socket.io and Highcharts.js | Twilio](https://www.twilio.com/blog/2012/12/building-a-real-time-sms-voting-app-part-2-socket-io-and-highcharts-js.html)

  * [Writing an AngularJS App with Socket.IO | HTML5 Rocks](http://www.html5rocks.com/en/tutorials/frameworks/angular-websockets/)

  * [Real Time Web Analytics with Node.js and Socket.IO | Christophe Coenraets](http://coenraets.org/blog/2012/10/real-time-web-analytics-with-node-js-and-socket-io/)

  * [Real-Time Chat With Node.js' Readline & Socket.io - Tuts+ Code Tutorial](http://code.tutsplus.com/tutorials/real-time-chat-with-nodejs-readline-socketio--cms-20953)

* [Near-Realtime Analytics with MongoDB, Node.js & SmoothieCharts | codecentric](https://blog.codecentric.de/en/2014/01/realtime-analytics-mongodb-nodejs-smoothiecharts/)

* WebLogic

  * [REST, SSE or WebSockets on WebLogic 10.3.6 | Java / Oracle SOA blog](http://biemond.blogspot.com.br/2014/01/rest-sse-or-websockets-on-weblogic-1036.html)

  * [[SlideShare] Oracle Coherence & WebLogic 12c Web Sockets: Delivering Real Time Push at Scale](http://www.slideshare.net/C2B2/oracle-coherence-and-weblogic-12c-web-sockets-delivering-real-time-push-at-scale)

--

* [HTML5 Geolocation API - Specification and Usages | ST Solutions](http://stsbd.com/html5-geolocation-api-specifications-usages/)

* [Está perdido? Geolocalização! | Tableless](http://tableless.com.br/esta-perdido-geolocalizacao/) - Entendendo como utilizar a API de Geolocalização (geolocation) do HTML5 com Javascript.

--

* [HTML5 Web Notification](http://jaydson.org/html5-web-notifications/)

* [Criando notificações desktop com HTML5 | Andre Loureiro](http://andrel.me/criando-notificacoes-desktop-com-html5/)

* [An Introduction to the Web Notifications API | Site Point](http://www.sitepoint.com/introduction-web-notifications-api/)

* [[GitHub] Nickersoft / push.js](https://github.com/Nickersoft/push.js) - A compact, cross-browser solution for using the JavaScript Notifications API

--

* [12 Awesome CSS3 Features That You Can Finally Start Using | Tutorialzine](http://tutorialzine.com/2013/10/12-awesome-css3-features-you-can-finally-use/)

* [[GitHub] pmneila / jsexp](https://github.com/pmneila/jsexp) - Some simulation experiments in JavaScript


#### dicas: WebRTC

* [WebRTC.org](http://www.webrtc.org/)

* [WebRTC: Update and Workarounds | Mozilla Hacks](https://hacks.mozilla.org/2013/09/webrtc-update-and-workarounds/)

* [[Speaker Deck] WebRTC Data Black Magic](https://speakerdeck.com/feross/webrtc-data-black-magic)

* [[YouTube] Real-time communication with WebRTC: Google I/O 2013](https://www.youtube.com/watch?v=p2HzZkd2A40)

* [WebRTC data channels: WebRTC data channels for high performance data exchange | HTML5 Rocks](http://www.html5rocks.com/en/tutorials/webrtc/datachannels/)

* [WebRTC: Not Quite Magic | Alex Freska](http://alexfreska.com/webrtc-not-quite-magic)

--

* [WebRTC Experiments & Demos](https://www.webrtc-experiment.com/)

  * [[GitHub] muaz-khan / WebRTC-Experiment](https://github.com/muaz-khan/WebRTC-Experiment)

  * [RecordRTC: WebRTC audio/video recording](https://www.webrtc-experiment.com/RecordRTC/)

--

* [Licode](http://lynckia.com/licode/) - Open Source Communication Provider

* [Talky](https://talky.io/) - Group video chat and screen sharing


#### dicas: WebGL

* [WebGL Fundamentals | HTML5 ROCKS](http://www.html5rocks.com/en/tutorials/webgl/webgl_fundamentals/)

* [This is a list of all the WebGL related activities happening on the web](http://www.khronos.org/webgl/wiki/User_Contributions)

--

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

--

* [The Era of WebGL | Medium](https://medium.com/p/abf669857722)

* [Non-Intrusive WebGL | Medium](https://medium.com/p/cebd176c281d)


#### dicas: Game

* [HTML5 Gamepad Tester](http://html5gamepad.com/)

--

* [Largest Directory of HTML5 Games](http://html5games.com/)

* [FightCode](http://fightcodegame.com/) - Killing Robots for Fun

* [Code Combat](http://codecombat.com/) - Learn to Code JavaScript by Playing a Game

* [Full Screen Mario](http://www.fullscreenmario.com/) : a purely HTML5 remake of the original Super Mario Bros game

  * [[GitHub] Diogenesthecynic / FullScreenMario](https://github.com/Diogenesthecynic/FullScreenMario) - An HTML5 remake of the original Super Mario Brothers - expanded for wide screens.

* [[GitHub] infusion / HTML5-Tetris](https://github.com/infusion/HTML5-Tetris) - A HTML5 Tetris Implementation

* [[GitHub] ellisonleao / clumsy-bird](https://github.com/ellisonleao/clumsy-bird) - A MelonJS port of the famous Flappy Bird Game

* [[GitHub] gloomyson / StarCraft](https://github.com/gloomyson/StarCraft) - HTML5 version for StarCraft game

* [The JavaScript Warrior](http://jswarrior.fusioncharts.com/) - Welcome to the JSWarrior Game. Unlike traditional games, you can't control your character through a keyboard or joystick. The only way you can control your character is through JavaScript.


#### dicas: Desenvolvimento de Jogos

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

* [VVVV.js](http://www.vvvvjs.com/) - the visual programming language VVVV brought to your web browser

* [How to Learn Three.js for Game Development | Gamedevtuts+](http://gamedev.tutsplus.com/articles/how-to-learn/how-to-learn-three-js-for-game-development/)

* [Building a 3D MMO Using WebSocket | David Walsh Blog](http://davidwalsh.name/3d-websockets)

* [Criando um MMO 3D utilizando WebSockets | iMasters](http://imasters.com.br/desenvolvimento/criando-um-mmo-3d-utilizando-websockets/)

* [Building Multiplayer HTML5 Games with Cloak | Bocoup](http://weblog.bocoup.com/building-multiplayer-html5-games-with-cloak/)

* [The Pond – building a multi-platform HTML5 game | Mozilla Hacks](https://hacks.mozilla.org/2013/11/the-pond-building-a-multi-platform-html5-game/)


#### dicas: Armazenamento

* [HTML5 Browser Storage: the Past, Present and Future | SitePoint](http://www.sitepoint.com/html5-browser-storage-past-present-future/)

* [A Quick Guide to Web Storage | Tutorialzine](http://tutorialzine.com/2013/11/a-quick-guide-to-web-storage/)

* [Web SQL DB vs. IndexedDB | JavassCrypt](http://www.javasscrypt.com/html5/web-sql-db-vs-indexeddb/)

--

* [IndexedDB Basic concepts - Web API Interfaces | MDN](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API/Basic_Concepts_Behind_IndexedDB)

* [An Introduction to IndexedDB | Dev.Opera](http://dev.opera.com/articles/introduction-to-indexeddb/)

* [Breaking the Borders of IndexedDB | Mozilla Hacks](https://hacks.mozilla.org/2014/06/breaking-the-borders-of-indexeddb/)

* [IndexedDB and Date Example](http://www.raymondcamden.com/index.cfm/2013/6/6/IndexedDB-and-Date-Example)

* [Working With IndexedDB | Tuts+ Code Tutorial](http://code.tutsplus.com/tutorials/working-with-indexeddb--net-34673)

* [Working With IndexedDB - Part 2 | Tuts+ Code Tutorial](http://code.tutsplus.com/tutorials/working-with-indexeddb-part-2--net-35355)

* [Using IndexedDB to Manage 3D WebGL Assets | SitePoint](http://www.sitepoint.com/using-indexeddb-manage-3d-webgl-assets/)

* [indexeddb file system | mode·switch](http://blog.modeswitch.org/indexeddb-file-system.html)

* [Indexed: Query IndexedDB Like Mongo | fluidbyte](http://fluidbyte.net/indexed-query-inexeddb-like-mongo/)

* [[GitHub] erikolson186 / zangodb](https://github.com/erikolson186/zangodb) - MongoDB-like interface for HTML5 IndexedDB

--

* [Client-Side Storage Options | Tech Pro](http://tech.pro/blog/1486/client-side-storage-options)

* [Storing Javascript objects in LocalStorage | DroidIT Blog](http://blog.droidit.eu/javascript-2/storing-javascript-objects-in-localstorage/)

* [localForage: Offline Storage, Improved | Mozilla Hacks](https://hacks.mozilla.org/2014/02/localforage-offline-storage-improved/)

* [HTML5 Web Storage - Teddy Garland | Coder Wall](https://coderwall.com/p/8awebg)

* [Dropbox Datastores and Drop-Ins | Nettuts+](http://net.tutsplus.com/tutorials/javascript-ajax/dropbox-datastores-and-drop-ins/)

* [[YoutTube] Google Cloud Storage - Getting started with the JavaScript Sample Application](https://www.youtube.com/watch?v=8ytpvQJNOU8) - This demonstration covers getting started with Google Cloud Storage using JavaScript

  * [[GitHub] GoogleCloudPlatform / storage-getting-started-javascript](https://github.com/GoogleCloudPlatform/storage-getting-started-javascript/) - This is a simple web-based example of calling the Google Cloud Storage API in JavaScript

* [Using Local Storage as a communication channel | Tech.pro](http://tech.pro/blog/6950/using-local-storage-communication-channel)

--

* [[Gist] leudanielm / GlobalEvents.js](https://gist.github.com/leudanielm/a49535053fd30274183e) - Fire events between different browser windows using localStorage


#### dicas: Performance

* [What makes WebAssembly fast? | Mozilla Hacks](https://hacks.mozilla.org/2017/02/what-makes-webassembly-fast/) - 2017/02/28

* [Why WebAssembly is Faster Than asm.js | Mozilla Hacks](https://hacks.mozilla.org/2017/03/why-webassembly-is-faster-than-asm-js/) - 2017/03/15

* [WebAssembly 101: a developer's first steps | Openbloc](http://blog.openbloc.fr/webassembly-first-steps/) - 2017/06/04

* [Five things you can do to make HTML5 perform better](http://christianheilmann.com/2013/01/25/five-things-you-can-do-to-make-html5-perform-better/)

* [Native Speed on the Web: JavaScript and asm.js | Alon Zakai](http://kripken.github.io/mloc_emscripten_talk/sloop.html)


#### dicas: Server Sent Events

* [HTML5 e SSE (Server Sent Events) - Igor Costa](http://www.igorcosta.com/html5-e-sse-eventsource/)

* [Push Notifications to the Browser With Server Sent Events](http://html5hacks.com/blog/2013/04/21/push-notifications-to-the-browser-with-server-sent-events/)


#### dicas: Full Screen API

* [Fullscreen API Specification](https://dvcs.w3.org/hg/fullscreen/raw-file/tip/Overview.html#api)

* [Using fullscreen mode | MDN](https://developer.mozilla.org/en-US/docs/Web/Guide/DOM/Using_full_screen_mode)


#### dicas: File System/API

* [Exploring the FileSystem APIs | HTML5 Rocks](http://www.html5rocks.com/en/tutorials/file/filesystem/) / [Ler arquivos em JavaScript usando as APIs do arquivo | HTML5 Rocks](http://www.html5rocks.com/pt/tutorials/file/dndfiles/)

* [File Reader | Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Web/API/FileReader)

* [Ler arquivos locais em JavaScript | HTML5 Rocks](http://www.html5rocks.com/pt/tutorials/file/dndfiles/)

* [File System and JavaScript. Processing Files in Browser | XB Software](http://xbsoftware.com/blog/file-system-javascript-processing-files-browser/)

* [Use the HTML5 File API to Work with Files Locally in the Browser | Scotch](http://scotch.io/tutorials/use-the-html5-file-api-to-work-with-files-locally-in-the-browser)

--

* [Resize an Image Using Canvas, Drag and Drop and the File API | David Walsh Blog](http://davidwalsh.name/resize-image-canvas)

* [Creating a File Encryption App with JavaScript | Tutorialzine](http://tutorialzine.com/2013/11/javascript-file-encrypter/)


### Bibliotecas

* [RgbQuant.js](https://github.com/leeoniya/RgbQuant.js) - an image quantization library

* [CamanJS - JavaScript Image Manipulation](http://camanjs.com/)

* [[GitHug] raphamorim / origami.js](https://github.com/raphamorim/origami.js) - HTML5 Canvas for Humans

--

* [Drawingboard.js](http://leimi.github.io/drawingboard.js/) - a simple canvas based drawing app that you can integrate easily on your website.

--

* [Snap.svg](http://snapsvg.io/) - is designed for modern browsers and therefore supports the newest SVG features like masking, clipping, patterns, full gradients, groups, and more.

--

* [[GitHub] mark-rolich / RulersGuides.js](https://github.com/mark-rolich/RulersGuides.js) - Creates Photoshop-like guides and rulers interface on a web page | [Demo](http://mark-rolich.github.io/RulersGuides.js/)

--

* [[GitHub] openseadragon / openseadragon](https://github.com/openseadragon/openseadragon) - An open-source, web-based viewer for zoomable images, implemented in pure JavaScript

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

* [[GitHub] eduardolundgren / tracking.js](https://github.com/eduardolundgren/tracking.js) - A modern approach for Computer Vision on the web

--

* [[GitHub] TalAter / annyang](https://github.com/TalAter/annyang) - A javascript library for adding voice commands to your site, using speech recognition

* [[GitHub] Selz / plyr](https://github.com/selz/plyr) - A simple HTML5 media player

* [Popcorn.js](http://popcornjs.org/) - The HTML5 Media Framework

* [Audio5js](http://zohararad.github.io/audio5js/) - The HTML Audio Compatibility Layer

* [[GitHub] EvandroLG / audioJS](https://github.com/EvandroLG/audioJS) - AudioJS is a agnostic lib cross-browser to work easily with the AudioContext API of HTML5.

* [[GitHub] egonelbre / jsfx](https://github.com/egonelbre/jsfx) - Javascript Sound Effect Generator

* [[GitHub] meenie / 8bit.js](https://github.com/meenie/8bit.js) - 8Bit.js Audio Library - Write music using 8bit oscillation sounds

* [[GitHub] watilde / beeplay](https://github.com/watilde/beeplay) - Write A Song In JavaScript

* [[GitHub]  meenie / band.js](https://github.com/meenie/band.js) - Music composer interface for the Web Audio API.

  * [Retro Game Music using Web Audio and Band.js  | Flippin' Awesome](http://flippinawesome.org/2013/09/09/retro-game-music-using-web-audio-and-band-js/)

* [Ion.Sound](http://ionden.com/a/plugins/ion.sound/en.html) - jQuery-plugin for playing sounds on events

* [[GitHub] eshiota / retro-audio-js](https://github.com/eshiota/retro-audio-js) - Web Audio API based retro player that give us that nostalgic feelings

  * [Retro.js Demo](http://eshiota.com/experiments/retrojs/) - Uma lib que usa a Web Audio API para tocar teclado usando uma representação em JSON de partituras de teclado, no site tem exemplo de 3 músicas

* [Pedalboard.js](http://dashersw.github.io/pedalboard.js/) - Open-source JavaScript framework for developing audio effects with Web Audio API

* [[GitHub] kylestetz / lissajous](https://github.com/kylestetz/lissajous) - A tool for programmatic audio performance in the browser using Javascript

--

* [[GitHub] openfin / fin-hypergrid](https://github.com/openfin/fin-hypergrid) - a polymer <canvas> based super high performant grid control

--

* [seen.js](http://seenjs.io/) - Render 3D scenes into SVG or HTML5 Canvas

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

* [[GitHub] chrisben / imgcache.js](https://github.com/chrisben/imgcache.js/) - JS library based on the File API to cache images for offline recovery (target: cordova/phonegap & chrome)

--

* [jsPDF](http://jspdf.com/) - A HTML5 client-side solution for generating PDFs.

  * [[GitHub] MrRio / jsPDF](https://github.com/MrRio/jsPDF) - Generate PDF files in JavaScript. HTML5 FTW : [gh-page](https://mrrio.github.io/jsPDF/)

  * [Generating PDFs from Web Pages on the Fly with jsPDF | SitePoint]() - 2016/02/16

* [PDF.js](https://mozilla.github.io/pdf.js/) - A general-purpose, web standards-based platform for parsing and rendering PDFs.

  * [How fast is PDF.js? | Mozilla Hacks](https://hacks.mozilla.org/2014/05/how-fast-is-pdf-js/)

  * [Custom PDF Rendering in JavaScript with Mozilla’s PDF.Js | SitePoint](https://www.sitepoint.com/custom-pdf-rendering/) - 2016/05/16

* [[GitHub] bpampuch / pdfmake](https://github.com/bpampuch/pdfmake) - Client/server side PDF printing in pure JavaScript

--

* [[GitHub] FileReader.js](http://bgrins.github.io/filereader.js/) - Read Files with JavaScript!

* [[GitHub] OptimalBits / fs.js](https://github.com/OptimalBits/fs.js) - This module provides a wrapper for the HTML5 File System API inspired in nodejs fs module

* [[GitHub] sindresorhus / screenfull.js](https://github.com/sindresorhus/screenfull.js) - Simple wrapper for cross-browser usage of the JavaScript Fullscreen API

* [[GitHub] maxogden / psd.js](https://github.com/maxogden/psd.js) - PSD Parser in JavaScript | [site](http://maxogden.github.io/psd.js/)

--

* [[GitHub] lukasoppermann / html5sortable](https://github.com/lukasoppermann/html5sortable) - VanillaJS sortable lists and grids using native HTML5 drag and drop API.

* [[GitHub] willianjusten / screamer-js](https://github.com/willianjusten/screamer-js) - is a Vanilla Javascript plugin to provide simple yet fully customisable web notifications using Web Notifications API.


#### Presentation System

* [5 of the Best Free HTML5 Presentation Systems](http://www.sitepoint.com/5-free-html5-presentation-systems/)

* [SlideCaptain - Modern online presentation tool](https://www.slidecaptain.com/) - Made with JavaScript, HTML5, CSS3, Bootstrap, MongoDB, Node.js and AngularJS.

--

* [[GitHub] pete-otaqui / deckard](https://github.com/pete-otaqui/deckard) - A Web Animations API driven slide deck library

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

* [[GitHub] viniciusalmeida / ninja-presentation](https://github.com/viniciusalmeida/ninja-presentation) - Do not be fooled. You do not have to be a ninja to use this toolkit for slides presentation!

--

* [WebSlides](https://webslides.tv/)

  * [[GitHub] jlantunez / webslides] - Making HTML presentations easy


#### WebRTC

* [sipML5 - The world's first open source HTML5 SIP client](http://sipml5.org/)

* [[GitHub] erbbysam / webRTCCopy](https://github.com/erbbysam/webRTCCopy) - A simple file sharing application using [webRTC-data.io](https://github.com/erbbysam/webRTC-data.io)

* [[GitHub] cowbell / sharedrop](https://github.com/cowbell/sharedrop) - HTML5 clone of Apple's AirDrop - easy P2P file transfer powered by WebRTC


#### Text Search

* [lunr.js - A bit like Solr, but much smaller and not as bright](http://lunrjs.com/) - Simple full-text search in your browser

  * [Building a Full-Text Index in Javascript | Gary Sieling](http://garysieling.com/blog/building-a-full-text-index-in-javascript)

* [[GitHub] brianreavis / sifter.js](https://github.com/brianreavis/sifter.js) - A library for textually searching arrays and hashes of objects by property (or multiple properties). Designed specifically for autocomplete.


#### Gesture

* [[GitHub]  roboleary / LeapTrainer.js](https://github.com/roboleary/LeapTrainer.js) - A gesture learning and recognition framework for the Leap Motion

* [[GitHub] EightMedia / hammer.js](https://github.com/EightMedia/hammer.js/) - A javascript library for multi-touch gestures

* [[GitHub] soyjavi / QuoJS](https://github.com/soyjavi/quojs) - Micro JavaScript Library for Mobile Devices

* [[GitHub] roboleary / LeapCursor.js](https://github.com/roboleary/LeapCursor.js) - Effortless Leap Motion support for websites

* [Kiwi.js](http://www.kiwijs.org/)

  * [[GitHub] gamelab](https://github.com/gamelab) - Kiwi.JS is a fun and friendly HTML5 game engine with a focus on WebGL and Mobile rendering

  * [Add Motion Control to a Kiwi.js Game With the Leap Motion Controller | Tuts+ Game Development Tutorial](http://gamedevelopment.tutsplus.com/tutorials/add-motion-control-to-a-kiwijs-game-with-the-leap-motion-controller--cms-20455)


#### Storage

* [FireBase](https://www.firebase.com/) - a powerful API to store and sync data in realtime

  * [[GitHub] firebase / geofire](https://github.com/firebase/geofire/) - Realtime location queries with Firebase

  * [GeoFire 2.0](https://www.firebase.com/blog/2014-06-23-geofire-two-point-oh.html) - is an open-source JavaScript library that allows you to store and query a set of items based on their geographic location

  * [Firebase Database não é bagunça! - BrazilJS](https://braziljs.org/blog/firebase-database-nao-e-bagunca/) - 2017/10/03

--

* [PouchDB](http://pouchdb.com/) - The Database that Syncs! PouchDB is an open-source JavaScript database inspired by [Apache CouchDB](https://couchdb.apache.org/) that is designed to run well within the browser.

  * [[GitHub] pouchdb / pouchdb](https://github.com/pouchdb/pouchdb) - PouchDB is a pocket-sized database

  * [10 things I learned from reading (and writing) the PouchDB source | PouchDB](http://pouchdb.com/2014/10/26/10-things-i-learned-from-reading-and-writing-the-pouchdb-source.html)

--

* [TaffyDB](http://www.taffydb.com/) - The JavaScript Database

* [SpahQL](http://danski.github.io/spahql/) - Query, manipulate and manage JSON data effortlessly.

* [[GitHub] TremayneChrist / Based](https://github.com/TremayneChrist/Based) - Client-side JavaScript database

* [[GitHub] chambs / minidb](https://github.com/chambs/minidb) - a simple wraper for local/session storage DOM API management

* [[GitHub] tuxracer / simple-storage](https://github.com/tuxracer/simple-storage) - Simple localStorage / sessionStorage supporting objects and arrays

* [[GitHub] arokor / barn](https://github.com/arokor/barn) - Fast, atomic persistent storage layer on top of localstorage

* [[GitHub] tantaman / LargeLocalStorage](https://github.com/tantaman/LargeLocalStorage) - Problem: You need to store a large amount of key-value based data in IE, Chrome, Safari, AND Firefox

* [JayData](http://jaydata.org/) - The cross-platform HTML5 data-management library for JavaScript

  * [GitHub / JayData](https://github.com/jaydata)

  * [Codeplex / JayData](https://jaydata.codeplex.com/)

* [[GitHub] lcavadas / Storage.js](https://github.com/lcavadas/Storage.js) - Javascript library that wraps storage logic ( localStorage, WebSQL, IndexedDB) for all browsers

* [lawnchair](http://brian.io/lawnchair/) - simple json storage

* [[GitHub] zefhemel / persistencejs](https://github.com/zefhemel/persistencejs) - is an asynchronous Javascript database mapper library. You can use it in the browser, as well on the server (and you can share data models between them).

* [LocalStorage with Amplify.js | TysonJS](http://tysonjs.com/blog/localstorage-with-amplify-js/)

* [[GitHub] justindeguzman / locstor](https://github.com/justindeguzman/locstor) - JavaScript helper library for HTML5 localStorage

* [[GitHub] tsironis / lockr](https://github.com/tsironis/lockr) - A minimal API wrapper for localStorage

* [[GitHub] mozilla / localForage](https://github.com/mozilla/localForage) - Offline storage, improved.

  * [localForage: Offline Storage, Improved | Mozilla Hacks](https://hacks.mozilla.org/2014/02/localforage-offline-storage-improved/)

  * [Armazenamento Offline com o LocalForage | iMasters](http://www.infoq.com/br/news/2014/04/localforage-offline-data-web)

  * [[GitHub] ask11 / storage](https://github.com/ask11/storage) - Storage is a functional wrapper around localForage. That means it's an asynchronous browser storage with multiple back-ends (IndexedDB, WebSQL, localStorage), which is built for a better offline experience.

* [[GitHub] techfort / LokiJS](https://github.com/techfort/LokiJS) - javascript embedded / in-memory database

  * [LokiJS](http://lokijs.org/) - A lightweight javascript document oriented database

  * [An introduction to LokiJS: the idiomatic way | Joe Minichino - Medium](https://medium.com/@tech_fort/an-introduction-to-lokijs-the-idiomatic-way-d24a4c546f7)

* [[GitHub] jensarps / IDBWrapper](https://github.com/jensarps/IDBWrapper) - A cross-browser wrapper for IndexedDB

* [[GitHub] aaronpowell / db.js](https://github.com/aaronpowell/db.js) - is a wrapper for IndexedDB to make it easier to work against

* [[GitHub] paldepind / synceddb](https://github.com/paldepind/synceddb) - Makes it easy to write offline-first applications with realtime syncing and server side persistence

* [[GitHub] js-data / js-data](https://github.com/js-data/js-data) - Robust framework-agnostic in-memory data store

--

* [ForerunnerDB - High Performance Web Database](http://www.forerunnerdb.com/) - is the only JavaScript database with a simple, rich JSON-based query language. Based on MongoDB's query language and built with web applications in mind, ForerunnerDB will have you up and running in minutes.

  * [[GitHub] Irrelon / ForerunnerDB](https://github.com/Irrelon/ForerunnerDB) - A JavaScript database with mongo-like query language, data-binding support, runs in the browser as a client-side DB or on the server via Node.js!

--

* [[GitHub] addyosmani / basket.js](https://github.com/addyosmani/basket.js) - A script and resource loader for caching & loading scripts with localStorage

* [[GitHub] keithwhor / FSO.js](https://github.com/keithwhor/FSO.js/) - JavaScript FileSystemObject library for temporary and permanent client-side file storage


#### Animations

* [[GitHub] sole / tween.js](https://github.com/sole/tween.js) - Javascript tweening engine

* [Turn.js](http://www.turnjs.com/) - The page flip effect in HTML5

* [[GitHub] thednp / kute.js](https://github.com/thednp/kute.js) - is a native Javascript animation engine featuring great code quality, badass performance, morphSVG, drawSVG, 2D and 3D transforms, SVG transforms, colors, as well as other CSS3 properties or presentation attributes.


#### Physics

* [PhysicsJS](http://wellcaffeinated.net/PhysicsJS/) - A modular, extendable, and easy-to-use physics engine for javascript

  * [Building a 2D Browser Game with PhysicsJS | Flippin' Awesome](http://flippinawesome.org/2013/12/02/building-a-2d-browser-game-with-physicsjs/)

* [Matter.js](http://brm.io/matter-js/) - is 2D physics engine for the web


* [Physics Sandbox](http://www.physicsandbox.com/index.html) - Fun Physics Projects

  * [[GitHub] micaeloliveira / physics-sandbox](https://github.com/micaeloliveira/physics-sandbox) - This repo contains simple physics simulations


#### WebGL

* [The Book of Shaders](http://patriciogonzalezvivo.com/2015/thebookofshaders/) - This is a gentle step-by-step guide through the abstract and complex universe of Fragment Shaders.

--

* [three.js](http://mrdoob.github.io/three.js/) - JavaScript 3D library

  * [The Beginner's Guide to three.js | Treehouse Blog](http://blog.teamtreehouse.com/the-beginners-guide-to-three-js)

  * [How to build a game with Three.js | Creative Bloq](http://www.creativebloq.com/3d/how-build-game-threejs-121310131)

  * [20 Impressive Examples for Learning WebGL with Three.js | Tutorialzine](http://tutorialzine.com/2013/09/20-impressive-examples-for-learning-webgl-with-three-js/)

  * [Shader Particle Engine](http://squarefeet.github.io/ShaderParticleEngine/) - A GLSL-heavy particle engine for THREE.js. Based on Stemkoski's great particle engine

  * [Building 3D in the browser with Three.js | Webdesigner Depot](http://www.webdesignerdepot.com/2014/04/building-3d-in-the-browser-with-three-js/)

  * [[GitHub] nxxcxx / Neural-Network](https://github.com/nxxcxx/Neural-Network) - Abstract visualization of biological neural network

* [Babylon Engine for HTML5](http://www.babylonjs.com/) - Babylon.js is a webgl / javascript 3D engine.

* [Voodoo](http://www.voodoojs.com/) - is a new Javascript framework that lets you easily mix 2D and 3D content together on the same page.

* [[GitHub] PixelsCommander / HTML-GL](https://github.com/PixelsCommander/HTML-GL) - Get as many FPS as you need and amazing effects by rendering HTML/CSS in WebGL

* [[GitHub] turbo / js](https://github.com/turbo/js) - perform massive parallel computations in your browser with GPGPU

* [[GitHub] patriciogonzalezvivo / glslEditor](https://github.com/patriciogonzalezvivo/glslEditor) - Simple WebGL Fragment Shader Editor


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

* [[GitHub] sourceful / game-engines](https://github.com/sourceful/game-engines) - HTML5 Game Engines list

--

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

* [PlayCanvas Engine](https://playcanvas.com/) -  is the world’s easiest to use WebGL Game Engine

  * [PlayCanvas Goes Open Source | Mozilla Hacks](https://hacks.mozilla.org/2014/06/playcanvas-goes-open-source/)


### Desenvolvimento de Aplicações

* [Developing Cross-Browser Extensions | Frontend Babel](http://frontendbabel.info/articles/developing-cross-browser-extensions/)

* [Installing web apps natively | 2ality](http://www.2ality.com/2014/06/installable-web-apps.html)

--

* [Web Fundamentals | Google Developers](https://developers.google.com/web/fundamentals/) - Best practices for modern web development

* [[GitHub] google / web-starter-kit](https://github.com/google/web-starter-kit)

  * [Web Starter Kit | Google Developer](https://developers.google.com/web/starter-kit/) - Boilerplate & Tooling for Multi-Device Development


#### Offline

* [Can I use offline web applications?](http://caniuse.com/offline-apps) - Compatibility table for support of offline web applications in desktop and mobile browsers.

* [[GitHub] pazguille / offline-first](https://github.com/pazguille/offline-first) - Everything you need to know to create offline-first web apps

* [[GitHub] offlinefirst / research](https://github.com/offlinefirst/research) - Links, feedback, comments, resources, anything pertaining to offline first research.

--

* [Offline | Dive into HTML5](http://diveintohtml5.info/offline.html)

* [MDN - Application Cache API](https://developer.mozilla.org/en-US/docs/HTML/Using_the_application_cache)

* [[SlideShare] HTML5 Offline & Storage](http://www.slideshare.net/gabrielso/html5-offline-storage)

* [offline and storage - tutorials | WebPlatform.org](http://docs.webplatform.org/wiki/tutorials/offline_and_storage)

* [Apostilas da Caelum offline com Application Cache do HTML 5](http://blog.caelum.com.br/apostilas-da-caelum-offline-com-application-cache-do-html-5/)

* [Palestra : HTML5 offline e Application Cache | Sérgio Lopes](http://sergiolopes.org/palestra-appcache-html5-offline/)

* [AppCache, manifest, mundo offline e ServiceWorker | Eduardo Matos](http://eduardomatos.me/appcache-manifest-e-serviceworker-as-partes-boas-e-ruins/)

* [Building Offline Experiences with HTML5 AppCache and IndexedDB | IEBlog](http://blogs.msdn.com/b/ie/archive/2011/09/27/building-offline-experiences-with-html5-appcache-and-indexeddb.aspx)

* [Criação de experiências offline com AppCache e IndexedDB | MSDN Br](http://msdn.microsoft.com/pt-br/library/jj983447.aspx)

* [Managing HTML5 Offline Storage | Google Developers](https://developers.google.com/chrome/whitepapers/storage)

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

* [60fps on the mobile web | Flipboard Engineering](http://engineering.flipboard.com/2015/02/mobile-web/)

--

* [[GitHub] appium / appium](https://github.com/appium/appium) - Automation tests for iOS and Android Apps

--

* [Screensiz.es](http://screensiz.es/phone) is a nifty little database of screen specifications for the most popular devices on the market.

* [List of displays by pixel density | Wikipedia](https://en.wikipedia.org/wiki/List_of_displays_by_pixel_density)

--

* [Create high-performance mobile UIs with Famo.us | IBM developerWorks](http://www.ibm.com/developerworks/library/wa-famous/index.html)

--

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

--

* [[GitHub] paulirish / iOS-WebView-App](https://github.com/paulirish/iOS-WebView-App) - Simple iOS app that loads a web page created to ease debugging a uiWebView

--

* [Ionic](http://ionicframework.com/) - The Most Advanced HTML5 Mobile App Framework. Ionic utilizes AngularJS in order to create a framework most suited to develop rich and robust applications.

  * [Mastering the Ionic Framework: Learn to Build & Deploy Native Speed HTML5 Based Apps | Thinkster](https://thinkster.io/ionic-framework-tutorial/)

  * [Pull to Refresh | Formulas | Learn Ionic](http://learn.ionicframework.com/formulas/pull-to-refresh/)

  * [Sample Mobile Application with Ionic and AngularJS | Christophe Coenraets](http://coenraets.org/blog/2014/02/sample-mobile-application-with-ionic-and-angularjs/)

  * [Ionic – Mobile UI Framework for PhoneGap/Cordova Developers | Devgirl's Weblog](http://devgirl.org/2014/01/20/ionic-mobile-ui-framework-for-phonegapcordova-developers/)

  * [[GitHub] ccoenraets / ionic-slides](https://github.com/ccoenraets/ionic-slides) - Slides for my Ionic talk at the Fluent Conference, April 21st 2015.


##### Firefox OS

* [Localizing Firefox OS Apps | Mozilla Hacks](https://hacks.mozilla.org/2013/08/localizing-firefox-os-apps/)

* [Guia Rápido de Desenvolvimento para Firefox OS](https://leanpub.com/guiarapidofirefoxos) - Criando apps com HTML5 para o Firefox OS (eBook)

* [[GitHub] buildingfirefoxos / bfxos-brackets](https://github.com/buildingfirefoxos/bfxos-brackets) - Building Firefox OS with Adobe Brackets extension

* [[GitHub] tehsis / webinstaller](https://github.com/tehsis/webinstaller) - Helper for installing Mozilla webapps

* [[GitHub] robnyman / Firefox-OS-Boilerplate-App](https://github.com/robnyman/Firefox-OS-Boilerplate-App) - Creating Firefox OS apps


##### Apache Cordova & PhoneGap

* [PhoneGap, Cordova, and what’s in a name? | PhoneGap](http://phonegap.com/2012/03/19/phonegap-cordova-and-what%E2%80%99s-in-a-name/)

* [Apache Cordova](https://cordova.apache.org/) - is a platform for building native mobile applications using HTML, CSS and JavaScript.

* [Cordova + Web Best Practices | Gaunt Face - Matthew Gaunt](http://www.gauntface.co.uk/blog/2013/07/18/cordova-web-best-practices/) - Getting PhoneGap / Cordova up and running with Yeoman

* [Apache Cordova, removendo os 300ms de delay entre o toque e o click | Igor Costa](http://www.igorcosta.com/apache-cordova-removendo-os-300ms-de-delay-entre-o-toque-e-o-click/)

* [Building Robust Cordova Apps with AppBuilder and Grunt | Telerik Developer Network](http://developer.telerik.com/featured/building-robust-cordova-apps-appbuilder-grunt/)


###### PhoneGap

* [PhoneGap](http://phonegap.com/) is a free and open source framework that allows you to create mobile apps using standardized web APIs for the platforms you care about.

* [Adobe PhoneGap 3.0 Released](http://phonegap.com/blog/2013/07/19/adobe-phonegap-3.0-released/)

* [Phonegap 3.0 mais rápido e muito mais adaptável | Igor Costa](http://www.igorcosta.com/phonegap-3-0-mais-rapido-e-muito-mais-adaptavel/)

* [PhoneGap 3.0 - Stuff You Should Know | Devgirl's Weblog](http://devgirl.org/2013/09/05/phonegap-3-0-stuff-you-should-know/)

* [CPBR6 slides da palestra Phonegap | Igor Costa](http://www.igorcosta.com/slides-phonegap/)

* [PhoneGap Build - Package mobile apps in the cloud.](https://build.phonegap.com/) - Simply upload your HTML5, CSS, and JavaScript assets to the Adobe® PhoneGap™ Build cloud service and we do the work of compiling for you.

* [[SlideShare] Write once, run "everywhere"](http://www.slideshare.net/horochovec/write-once-run-everywhere)

  * [[GitHub] phonegap-showcase / phonegap-ngcordova](https://github.com/phonegap-showcase/phonegap-ngcordova)

--

* [ Aula 01: Introdução ao Phonegap | Loiane Groner](http://www.loiane.com/2014/02/curso-phonegap-cordova-aula-01-introducao-ao-phonegap/)

--

* [[SlideShare] Automating PhoneGap Build](http://www.slideshare.net/coldfumonkeh/automating-phonegap-build)

* [[YouTube] Mac Mini and Jenkins as a Phonegap Build Server](https://www.youtube.com/watch?&v=tcRXB3n-5qE)

* [[GitHub] Medic - Continuous integration setup for Apache Cordova](https://github.com/filmaj/medic)

* [Continuous Integration of iOS Projects using Jenkins, CocoaPods, and Kiwi](http://9elements.com/io/index.php/continuous-integration-of-ios-projects-using-jenkins-cocoapods-and-kiwi/)

--

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

  * [Apache Cordova Tutorial](https://ccoenraets.github.io/cordova-tutorial/) - In this tutorial, you will learn strategies and best practices to build native-like mobile applications with HTML, JavaScript, and CSS. You will build an Apache Cordova (aka PhoneGap) Employee Directory application from scratch using the Single Page Architecture, HTML templates, touch events, and performance optimization techniques.

    * [[GitHub] ccoenraets / cordova-tutorial](https://github.com/ccoenraets/cordova-tutorial)

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
