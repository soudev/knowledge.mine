# React.js

<!-- toc -->

- [Main references](#main-references)
- [Learn](#learn)
- [Tips](#tips)
- [Project setup](#project-setup)
  * [Using parcel](#using-parcel)
  * [Using webpack](#using-webpack)
  * [React starter kit](#react-starter-kit)
- [UI/Styles](#uistyles)
  * [React and css](#react-and-css)
    + [React and Sass](#react-and-sass)
  * [CSS in JS - React style components](#css-in-js---react-style-components)
  * [React components](#react-components)
    + [React compound components](#react-compound-components)
    + [React UI components](#react-ui-components)
- [Patterns](#patterns)
- [Router](#router)
- [Fetch Data](#fetch-data)
  * [Axios](#axios)
  * [Fetch API](#fetch-api)
- [LocalStorage](#localstorage)
- [RxJS](#rxjs)
- [Flux Architecture](#flux-architecture)
  * [Redux](#redux)
  * [Redux fetch data](#redux-fetch-data)
- [Testing](#testing)
- [Peer-to-peer](#peer-to-peer)
- [Real time](#real-time)
  * [Socket.io](#socketio)
- [i18n - Internationalization](#i18n---internationalization)
- [Performance](#performance)
  * [React server-side rendering](#react-server-side-rendering)
- [React.js 16+](#reactjs-16)
  * [Context API](#context-api)
  * [Render Props](#render-props)
- [Mobile](#mobile)
  * [React Native](#react-native)
- [preact](#preact)

<!-- tocstop -->

---

## Main references

* [React](https://facebook.github.io/react/) - A JavaScript library for building user interfaces

  * [New React Developer Tools | React Blog](https://facebook.github.io/react/blog/2015/09/02/new-react-developer-tools.html) - 2015/09/02

  * [React Components](http://react-components.com/)

  * [React.parts](http://react.parts/)  - A catalog of React Native components

* [CodeSandbox](https://codesandbox.io/) - Online playground for React


## Learn

* [[YouTube] Learn to Code: How React.js Works | Fullstack Academy](https://www.youtube.com/watch?v=mLMfx8BEt8g) - 2017/01/31

* [[YouTube] The Secrets of React's Virtual DOM](https://www.youtube.com/watch?v=-DX3vJiqxm4) - A talk from FutureJS by Pete Hunt of Facebook

--

* [[GitHub] enaqx / awesome-react](https://github.com/enaqx/awesome-react) - A collection of awesome React libraries, resources and shiny things

* [[GitHub] petehunt / react-howto](https://github.com/petehunt/react-howto) - Your guide to the (sometimes overwhelming!) React ecosystem.

--

* [[GitHub] react-brasil / empresas-que-usam-react-no-brasil](https://github.com/react-brasil/empresas-que-usam-react-no-brasil) - Repositório que mostra empresas e projetos que utilizam React no Brasil

--

* [From JSXTransformer to Babel | Stoyan's phpied.com](http://www.phpied.com/from-jsxtransformer-to-babel/) - 2015/06/22

--

* [[YouTube] Talk #54 - React para iniciantes | Pagar.me Talks](https://www.youtube.com/watch?v=hHDMKZ3T6Kw) - 2017/12/14

* [Learn React](http://learnreact.com/)

* [React in 7 Minutes - React Video Tutorial #free | @eggheadio](https://egghead.io/lessons/react-react-in-7-minutes)

* [ReactJS For Stupid People | Andrew Ray's Blog](http://blog.andrewray.me/reactjs-for-stupid-people/)

* [React.js Fundamentals](http://courses.reactjsprogram.com/courses/reactjsfundamentals) - If you're new to React.js, there's no better place to learn React.js and the React ecosystem than with this React.js fundamentals course

* [10 obstáculos frequentes encontrados pelos novos tripulantes do React | React Brasil](https://medium.com/reactbrasil/10-obst%C3%A1culos-frequentes-encontrados-pelos-novos-tripulantes-do-react-7672c4facf58) - 2018/03/13

* [React Tutorial: A Comprehensive Guide to learning React.js in 2018 | tylermcginnis.com](https://tylermcginnis.com/reactjs-tutorial-a-comprehensive-guide-to-building-apps-with-react/) - 2018/03/12

* [Everything You Should Know About React: The Basics You Need to Start Building | freeCodeCamp](https://medium.freecodecamp.org/everything-you-need-to-know-about-react-eaedf53238c4) - 2017/11/12

* [20 Things You Must Learn Before Writing Your First React App | Medium by @jdan](https://medium.com/@jdan/20-things-you-must-learn-before-writing-your-first-react-app-c9cc08246ec7) - 2016/11/17

* [Fullstack React: 30 Days of React](https://www.fullstackreact.com/30-days-of-react/) - 2017/01/13

* [Começando com React.js | jscasts](http://jscasts.teachable.com/courses/comecando-com-react-js) - O tutorial que você queria, mostrando de forma simplificada suas principais características e vantagens

* [Como começar a sua aplicação React em poucos minutos | Code Prestige - Medium](https://medium.com/code-prestige/configurando-aplica%C3%A7%C3%B5es-react-em-2-minutos-894025cbef82) - 2016/08/04

* [React: do básico ao avançado - Parte 1 | BrasilJS](https://braziljs.org/blog/react-do-basico-ao-avancado-parte-1/) - 2016/10/17

* [[GitBook] React com ES6: de Padawan a Mestre Jedi](https://skilloio.gitbooks.io/react-de-padawan-a-mestre-jedi/)

  * [[GitHub] skilloio / react-es6-padawan-to-jedi-book](https://github.com/skilloio/react-es6-padawan-to-jedi-book) - Uma introdução simples e completa para React usando ES6 e Babel

* [React Tips](http://react.tips/) - Best React.js tips and tricks.

* [React basic in just 1 hour | Udemy](https://www.udemy.com/react-basic-in-just-1-hour/)

  * [[plunker] react.js first contact, doing basics tests with ECMAScript 5](http://embed.plnkr.co/OIWlahbUG7RqE5dsiYy2/)

  * [[plunker] react.js first contact, doing basics tests with ECMAScript 6](http://plnkr.co/edit/STMlKzr1pWOlqDF2dnlI)

* DevPleno

  * [[YouTube playlist] ReactJS na Prática | DevPleno](https://www.youtube.com/watch?v=Ckp23FEAVQ8&list=PLBNBxpMAbyhXehTmR9nLxV3hVtVOZYIvd)

  * [[YouTube] Hands-on ReactJS | DevPleno](https://www.youtube.com/watch?v=n9aP7mFX2Ac&list=PLBNBxpMAbyhXSRcKIKWg04FTPGNy-ZPMa)

* Ihatetomatoes

  * [[YouTube playlist] React Tutorials 2017 | Ihatetomatoes](https://www.youtube.com/watch?v=OXmpxz_-pBU&list=PLkEZWD8wbltnXlfyhS5qSMTNb26utkOkI)

* LearnCode.academy

  * [[YouTube playlist] React JS Tutorials | LearnCode.academy](https://www.youtube.com/watch?v=MhkGQAoc7bc&list=PLoYCgNOIyGABj2GQSlDRjgvXtqfDxKm5b)

* [[YouTube] 8 Tips For Getting Better At React | LevelUpTuts](https://www.youtube.com/watch?v=BncMF2aTL0w) - 2017/11/07

* [[YouTube] React - The Complete Guide - Sneak Peek - First 2 Hours | Academind](https://www.youtube.com/watch?v=pgAvVxowaYU) - 2017/10/26

  * [[Udemy] React 16 - The Complete Guide (incl. React Router 4 & Redux)](https://www.udemy.com/react-the-complete-guide-incl-redux/) - Dive in and learn React from scratch! Learn Reactjs, Redux, React Routing, Animations, Next.js basics and way more!

* [[YouTube] The 2017 React Development Starter Guide | CodingTheSmartWay.com](https://www.youtube.com/watch?v=7ojad6QYuqI) - 2017/04/23

* [[YouTube] React Tutorial for Beginners - Codepen.io | Dev Coffee](https://www.youtube.com/watch?v=ZnRFerIP8aA) - 2017/01/10

* [[YouTube] React JS Crash Course | Traversy Media](https://www.youtube.com/watch?v=A71aqufiNtQ) - 2016/11/12

* [[YouTube] Zero to Hero with React js | TechKeka](https://www.youtube.com/watch?v=-40p_dZccPg) - 2016/10/28

* [Learn React Fundamentals and Advanced Patterns | @kentcdodds](https://blog.kentcdodds.com/learn-react-fundamentals-and-advanced-patterns-eac90341c9db) - 2017/12/04

  * [The Beginner's Guide to ReactJS - Course by @kentcdodds | egghead.io](https://egghead.io/courses/the-beginner-s-guide-to-reactjs)

    * [[GitHub] aderaaij / notes-on-the-beginner-s-guide-to-reactjs](https://github.com/aderaaij/notes-on-the-beginner-s-guide-to-reactjs) - My notes on 'The beginners guide to ReactJS' on egghead.io

  * [Advanced React Component Patterns - Course by @kentcdodds | egghead.io](https://egghead.io/courses/advanced-react-component-patterns)

--

* [[GitHub] kentcdodds / advanced-react-patterns-v2](https://github.com/kentcdodds/advanced-react-patterns-v2)

--

* [Learn React.js from Top 45 Tutorials for the past year (v.2018) | Mybridge for Professionals](https://medium.mybridge.co/learn-react-js-from-top-45-tutorials-for-the-past-year-v-2018-28b7f4d4b2c4) - 2018/01/17


## Tips

* [[GitHub] react-cosmos / react-cosmos](https://github.com/react-cosmos/react-cosmos) - Dev tool for creating reusable React components

--

* [[Gist] sebmarkbage / ElementFactoriesAndJSX.md](https://gist.github.com/sebmarkbage/d7bce729f38730399d28#comment-1377720) - New React Element Factories and JSX

* [[GitHub] reactjs / react-future](https://github.com/reactjs/react-future) - Specs & docs for potential future and experimental React APIs and JavaScript syntax.

--

* [Intro to the React Framework | Development – Tuts+](http://dev.tutsplus.com/tutorials/intro-to-the-react-framework--net-35660)

* [Getting Started with React and JSX | SitePoint](http://www.sitepoint.com/getting-started-react-jsx/)

* [React.js: an interactive tutorial to get started | webdesignporto.com](http://webdesignporto.com/react-js-an-interactive-tutorial-to-get-started/)

* [Nixtu: How I Learned to Stop Worrying and Love React | Nixtu](http://www.nixtu.info/2014/07/how-i-learned-to-stop-worrying-and-love.html)

* [The React Quick Start Guide | jackcallister.com](http://www.jackcallister.com/2015/01/05/the-react-quick-start-guide.html) - (2015/01/05)

--

* [5 Practical Examples For Learning The React Framework | Tutorialzine](http://tutorialzine.com/2014/07/5-practical-examples-for-learning-facebooks-react-framework/)

* [11 React Examples | The Practical Dev](https://dev.to/drminnaar/11-react-examples-2e6d) - 2018/01/01

--

* [The best way to bind event handlers in React | freeCodeCamp](https://medium.freecodecamp.org/the-best-way-to-bind-event-handlers-in-react-282db2cf1530) - 2018/05/08

--

* [Prop Drilling | kentcdodds](https://blog.kentcdodds.com/prop-drilling-bb62e02cb691) - 2018/05/21

--

* [How to write highly readable React code — 10 coding style tips | freeCodeCamp](https://medium.freecodecamp.org/10-points-to-remember-thatll-help-you-master-coding-in-reactjs-library-d0520d8c73d8) - 2018/01/03

* [Clean Code vs. Dirty Code: React Best Practices | American Express Engineering Blog](http://americanexpress.io/clean-code-dirty-code/) - 2017/11/16

* [Simplifying Code with React | kevindangoor.com](http://www.kevindangoor.com/2014/05/simplifying-code-with-react/)

* [One Mixin to rule them all | Front-end Development — Medium](https://medium.com/front-end-development-2/3885aadb3c1a)

* [React Mixins By Example | Simble Studios](http://simblestudios.com/blog/development/react-mixins-by-example.html)

* [React Components for Cat Videos | David and Suzi](http://davidandsuzi.com/react-components-for-cat-videos/)

* [React Tutorial: Two way data binding | Void Canvas](http://voidcanvas.com/react-tutorial-two-way-data-binding/)

* [How to Organize a Large React Application and Make It Scale | SitePoint](https://www.sitepoint.com/organize-large-react-application/) - 2017/04/26

* [Writing Scalable React Apps with the Component Folder Pattern | Styled Components - Medium](https://medium.com/styled-components/component-folder-pattern-ee42df37ec68) - 2017/08/28

--

* [[SlideShare] Reconciling ReactJS as a View Layer Replacement (MidwestJS 2014)](http://www.slideshare.net/ZachLendon/reconciling-react-as-a-view-layer-replacement-midwestjs-2014) - 2014/08/15

--

* [Creating AngularJS-Inspired "Directive" Components In ReactJS | Ben Nadel](http://www.bennadel.com/blog/2890-creating-angularjs-inspired-directive-components-in-reactjs.htm) - 2015/08/17

* [Faster AngularJS Rendering (AngularJS and ReactJS) | thierry.nicola](http://www.williambrownstreet.net/blog/2014/04/faster-angularjs-rendering-angularjs-and-reactjs/)

--

* [D3 and React - the future of charting components? | the Binary blog](http://10consulting.com/2014/02/19/d3-plus-reactjs-for-charting/)

* [Integrating D3.js visualizations in a React app | Nicolas Hery](http://nicolashery.com/integrating-d3js-visualizations-in-a-react-app/)

* [[GitHub] borisyankov / react-sparklines](https://github.com/borisyankov/react-sparklines) - Beautiful and expressive Sparklines React component

--

* [Visualization is for Sharing: Using React for Portable Data Visualization | Viget](http://viget.com/extend/visualization-is-for-sharing-using-react-for-portable-data-visualization)

--

* [Publishing your first React component on NPM | Cameron Nokes](http://cameronnokes.com/blog/publishing-your-first-react-component-on-npm) - 2015/07/16

* [A Guide to Building a React Component for npm | DailyJS – Medium](https://medium.com/dailyjs/a-guide-to-building-a-react-component-for-npm-68f03b314753) - 2018/01/09

--

* [Essential React Libraries in 2018 | RWieruch](https://www.robinwieruch.de/essential-react-libraries-framework/) - 2018/01/11

--

* [[GitHub] nitish24p / react-worker-image](https://github.com/nitish24p/react-worker-image) - React component to fetch image resources via web workers

* [[GitHub] FormidableLabs / urql](https://github.com/FormidableLabs/urql) - Universal React Query Library (GraphQL client)

* [[GitHub] ruanyf / react-demos](https://github.com/ruanyf/react-demos) - a collection of simple demos of React.js

* [Tic Tac React (Part 1) | Brian Barnett](http://w.brianbar.net/2014/08/tic-tac-react-part-1/)

  * [[GitHub] brian3kb / tic_tac_reactjs](https://github.com/brian3kb/tic_tac_reactjs) - Simple tic tac toe game built with reactjs

* [[GitHub] andrewgleave / react-weather](https://github.com/andrewgleave/react-weather) - Example React weather app using forecast.io's API

* [[GitHub] alexcurtis / react-treebeard](https://github.com/alexcurtis/react-treebeard) - React Tree View Component. Data-Driven, Fast, Efficient and Customisable.

* [[GitHub] probablyup / markdown-to-jsx](https://github.com/probablyup/markdown-to-jsx) - Interprets GFM markdown text and outputs a React JSX equivalent

--

* [[GitHub] PixelsCommander / ReactiveElements](https://github.com/PixelsCommander/ReactiveElements) - Allows to use React.js component as HTML element (web component)

--

* [[GitHub] Chrisui / react-hotkeys](https://github.com/Chrisui/react-hotkeys) - Declarative hotkey and focus area management for React

* [[GitHub] gilbarbara / react-joyride](https://github.com/gilbarbara/react-joyride) - Create walkthroughs and guided tours for your ReactJS apps.

--

* [[GitHub] raphamorim / react-tv](https://github.com/raphamorim/react-tv) - React development for TVs (Renderer for low memory applications and Packager for TVs)

--

* [[GitHub] Flipboard / react-canvas](https://github.com/flipboard/react-canvas) - High performance <canvas> rendering for React components

  * [60fps on the mobile web | Flipboard Engineering](http://engineering.flipboard.com/2015/02/mobile-web/)

  * [My “reaction” to react-canvas — Front-end Development | Medium - Codrin Iftimie](https://medium.com/front-end-development-2/my-reaction-to-react-canvas-e181a0189d4c)

* [React Hot Loader](https://gaearon.github.io/react-hot-loader/) - Tweak React components in real time

--

* [Introducing React Food Truck | Burke Knows Words](https://burkeknowswords.com/introducing-react-food-truck-b23ea1e2cf79) - (2017/11/30) React Food Truck is a curated set of extensions for discerning React developers who use VS Code.


## Project setup

* [How to keep a fast build with Browserify and ReactJS | Avisi Blog](http://blog.avisi.nl/2014/04/25/how-to-keep-a-fast-build-with-browserify-and-reactjs/)

* [Browserify and Gulp with React | Mozilla Hacks](https://hacks.mozilla.org/2014/08/browserify-and-gulp-with-react/)


### Using parcel

> [Parcel](https://parceljs.org/)

* [[YouTube] React, Typescript and Sass with Parcel - Part 1 | Richard Oliver Bray](https://www.youtube.com/watch?v=jdFaLrzfDB0) - 2018/01/22

* [[YouTube] React, Typescript and Sass with Parcel - Part 2 | Richard Oliver Bray](https://www.youtube.com/watch?v=Px_2JE1vBkI) - 2018/01/22


### Using webpack

> [Webpack](https://webpack.js.org/)

* [How to streamline your development process and create a React.js app using Webpack 4 | freeCodeCamp](https://medium.freecodecamp.org/how-to-develop-react-js-apps-fast-using-webpack-4-3d772db957e4) - 2018/05/09

* [Webpack 4 Tutorial: from 0 Conf to Production Mode | Valentino Gagliardi](https://www.valentinog.com/blog/webpack-4-tutorial/) - 2018/04/01

  * [[GitHub] valentinogagliardi / webpack-4-quickstart](https://github.com/valentinogagliardi/webpack-4-quickstart) - Webpack 4 tutorial: All You Need to Know, from 0 Conf to Production Mode

* [[YouTube] React & Webpack 4 From Scratch - No CLI | Traversy Media](https://www.youtube.com/watch?v=deyxI-6C2u4) - 2018/03/29

  * [[GitHub] bradtraversy / react_webpack_starter](https://github.com/bradtraversy/react_webpack_starter) - React 16 and Webpack 4 starter pack

* [React — Setup mínimo com Webpack | Douglas Matoso](https://blog.dmatoso.com/react-setup-m%C3%ADnimo-com-webpack-ec33b116ac07) - 2017/08/28

  * [[GitHub] doug2k1 / react-minimal-setup](https://github.com/doug2k1/react-minimal-setup)

* [[YouTube] Webpack 3 - ES6 + React + Sass | Steven Pérez](https://www.youtube.com/watch?v=_w6KaIy_RP0) - 2017/07/17

  * [[GitHub] StevenPerez / tutorial-webpack](https://github.com/StevenPerez/tutorial-webpack) - Este repositorio contiene el material explicado en el video tutorial de Webpack 3

* [[YouTube] ReactJS with Webpack Tutorial - Setup & ReactJS Router/Navigation David Acosta](https://www.youtube.com/watch?v=w9-1T1D0xlQ) - 2017/06/03

  * [[GitHub] gugui3z24 / ReactJS-Webpack-Tutorial](https://github.com/gugui3z24/ReactJS-Webpack-Tutorial) - Setting a ReactJS Development Environment Using Webpack

* [[GitHub] roebuk / aletta](https://github.com/roebuk/aletta) - is a progressive blogging application created with React using webpack as devtool.

* TypeScript

  * [React & Typescript with Webpack | gitconnected](https://levelup.gitconnected.com/react-typescript-with-webpack-2fceebb8faf) - 2018/01/10

  * [React & Typescript with Webpack part 2 | Richard Oliver Bray – Medium](https://medium.com/@richbray/react-typescript-with-webpack-part-2-aa02d150c59b) - 2018/01/10


### React starter kit

* [Starter Kits | React](https://reactjs.org/community/starter-kits.html)

--

* [[GitHub] facebookincubator / create-react-app](https://github.com/facebookincubator/create-react-app) - Create React apps with no build configuration.

  * [[GitHub] tuchk4 / awesome-create-react-app](https://github.com/tuchk4/awesome-create-react-app) - Awesome list of Create React App articles / tutorials / videos and FAQ

  * [Create Apps with No Configuration | React Blog](https://facebook.github.io/react/blog/2016/07/22/create-apps-with-no-configuration.html) - 2016/07/22

  * [What's New in Create React App | React Blog](https://facebook.github.io/react/blog/2017/05/18/whats-new-in-create-react-app.html) - 2017/05/18

* [[GitHub] timarney / react-app-rewired](https://github.com/timarney/react-app-rewired) - Override create-react-app webpack configs without ejecting

  * [React / Create React App — But I don’t wanna Eject | Tim Arney - Medium](https://medium.com/@timarney/but-i-dont-wanna-eject-3e3da5826e39) - 2016/12/01

* [[GitHub] MyNameIsURL / react-bootstrap-website](https://github.com/MyNameIsURL/react-bootstrap-website) - React-Bootstrap Tutorial posted to [YouTube](https://www.youtube.com/watch?v=jgVkR5EKI68)

--

* [[GitHub] nozzle / react-static](https://github.com/nozzle/react-static) - A progressive static-site generator for React

* [[GitHub] zeit / next.js](https://github.com/zeit/next.js) - Framework for server-rendered or statically-exported React apps

--

* [[GitHub] richardkall / react-starter](https://github.com/richardkall/react-starter) - Boilerplate for universal React applications

* [[GitHub] este / este](https://github.com/este/este) - The best dev stack and starter kit for React universal web/mobile apps.

* [[GitHub] mxstbr / react-boilerplate](https://github.com/mxstbr/react-boilerplate) - A highly scalable, offline-first foundation with the best developer experience and a focus on performance and best practices

* [[GitHub] alexandernanberg / react-boilerplate](https://github.com/alexandernanberg/react-boilerplate) - Minimal react boilerplate

  * [[GitHub] alexandernanberg / react-toolkit](https://github.com/alexandernanberg/react-toolkit)

* [[GitHub] dtonys / universal-web-boilerplate](https://github.com/dtonys/universal-web-boilerplate) - Modern react boilerplate featuring universal rendering and code splitting

* [[GitHub] kriasoft / react-starter-kit](https://github.com/kriasoft/react-starter-kit) - Facebook React Starter Kit - a skeleton for a typical web application / single-page application (SPA). Technology stack: Gulp, Webpack, BrowserSync, React.js, Bootstrap

* [[GitHub] Granze / react-starterify](https://github.com/Granze/react-starterify) - React JS application skeleton using Browserify and other awesome tools

* [[GitHub] obetomuniz / reeakt](https://github.com/obetomuniz/reeakt) - A modern React boilerplate to awesome web applications

* [[GitHub] zeit / next.js](https://github.com/zeit/next.js/) - Framework for server-rendered or statically-exported React apps

--

* [[GitHub] CVarisco / create-component-app](https://github.com/CVarisco/create-component-app) - Tool to generate different types of React components from the terminal

  * [create-component-app v1 is out now 🎉 | Hacker Noon](https://hackernoon.com/create-component-app-v1-is-out-now-6ca0217992e9) - 2017/10/25

  * [Pare de copiar e colar componentes React e use o create-component-app | Diego Martins de Pinho - Medium](https://medium.com/@DiegoMartinsDePinho/pare-de-copiar-e-colar-componentes-react-e-use-o-create-component-app-25f0c7e21588) - 2017/10/26


## UI/Styles

### React and css

* [Styling React | SurviveJS](https://survivejs.com/react/advanced-techniques/styling-react/)

* [4. Four ways to style react components | codeburst.io](https://codeburst.io/4-four-ways-to-style-react-components-ac6f323da822)

* [[YouTube] Tech Talk: Make CSS Functional | Fullstack Academy](https://www.youtube.com/watch?v=eHS1Ohybb_k) - 2017/01/23

* [[YouTube] David Wells - CSS in React | reactjs sf meetup](https://www.youtube.com/watch?v=U86-MFPsarQ) - 2016/07/11

  * [[Speaker Deck] Bulletproof CSS in React](https://speakerdeck.com/davidwells/bulletproof-css-in-react) - 2016/06/30

* [Stop using CSS in JavaScript for web development | Gajus Kuizinas – Medium](https://medium.com/@gajus/stop-using-css-in-javascript-for-web-development-fa32fb873dcc) - 2017/04/27

  * [[GitHub] gajus / react-css-modules](https://github.com/gajus/react-css-modules) - Seamless mapping of class names to CSS modules inside of React components

  * [[GitHub] gajus / babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) - Transforms styleName to className using compile time CSS module resolution


#### React and Sass

* [[Stack Overflow] React component theme using sass variables depending on React prop value](https://stackoverflow.com/questions/42388393/react-component-theme-using-sass-variables-depending-on-react-prop-value)

--

* [Styling React Components in Sass | HugoGiraudel](https://hugogiraudel.com/2015/06/18/styling-react-components-in-sass/) - 2015/06/18

* [Adding a CSS Preprocessor (Sass, Less etc.) | create-reat-app docs](https://github.com/facebook/create-react-app/blob/master/packages/react-scripts/template/README.md#adding-a-css-preprocessor-sass-less-etc)

* [How To Include SASS In Your React Project | AutomationFuel](https://www.automationfuel.com/sass-react-webpack/)

* [[YouTube] Sass setup in create-react-app project | Jordan Rhea](https://www.youtube.com/watch?v=tWp0oxbzZ3s) - 2017/01/21

  * [[Gist] rheajt / readme.md](https://gist.github.com/rheajt/2f2f070291e39e86cf44705aa74e412e) - sass setup for create-react-app cli tool

* [[YouTube] Using Pre-processors Scss and Sass with Create-React-App | Jordan Rhea](https://www.youtube.com/watch?v=2QaI5ajg4Hw) - 2017/10/11

* [[YouTube] Sass styles in create-react-app | Code With Nate](https://www.youtube.com/watch?v=B_zZDa80FVo) - 2017/11/03


### CSS in JS - React style components

* [Getting started with CSS modules in React | Pusher Blog](https://blog.pusher.com/css-modules-react/) - 2018/02/15

* [[YouTube] React JS Style Components | Full Stack Talks](https://www.youtube.com/watch?v=gNeavlJ7lNY) - 2016/08/31

  * [“Scale” FUD and Style Components | learnreact](https://medium.learnreact.com/scale-fud-and-style-components-c0ce87ec9772) - 2016/07/18

  * [[jsbin] Example Style Components around Twitter Bootstrap buttons](http://jsbin.com/zifitu/edit?js,output)

--

* [[GitHub] emotion-js / emotion](https://github.com/emotion-js/emotion) - style as a function of state

* [[GitHub] styled-components / styled-components](https://github.com/styled-components/styled-components) - Visual primitives for the component age

  * [Quick Tip: How to Style React Components with styled-components | SitePoint](https://www.sitepoint.com/style-react-components-styled-components/) - 2017/04/20

  * [Styling in React: From External CSS to Styled Components | SitePoint](https://www.sitepoint.com/style-react-components-styled-components/) - 2017/09/07

  * [[YouTube Playlist] Tutorial: Build a portfolio with ReactJs | FroDev](https://www.youtube.com/watch?v=QR40RON4S-4&list=PLeQcRHIS0mbiyZ4rrbfu7CSfCTT0t4lSD) - using styled components

    * [[GitHub] chuson1996 / portfolio-tutorial](https://github.com/chuson1996/portfolio-tutorial)

* [[GitHub] airbnb / react-with-styles](https://github.com/airbnb/react-with-styles) - Use CSS-in-JavaScript with themes for React without being tightly coupled to one implementation

  * [react-with-styles | Airbnb Engineering](http://airbnb.io/projects/react-with-styles/)

* [[GitHub] paypal / glamorous](https://github.com/paypal/glamorous) - Maintainable CSS with React

  * [[YouTube] Maintainable CSS in React (JS@PayPal Summer 2017) | Kent C. Dodds](https://www.youtube.com/watch?v=3-4KsXPO2Q4) - 2017/07/20

* [[GitHub] linkedin / css-blocks](https://github.com/linkedin/css-blocks) - High performance, maintainable stylesheets.

* [[GitHub] marcohamersma / react-easy-styleguide](https://github.com/marcohamersma/react-easy-styleguide) - Easy styleguide/component library tool for React projects with support for global styles. Works great with create-react-app

* [[GitHub] rtsao / styletron](https://github.com/rtsao/styletron) - Universal, high-performance JavaScript styles


### React components

#### React compound components

* [[YouTube] Ryan Florence - Compound Components | Phoenix ReactJS](https://www.youtube.com/watch?v=hEGg-3pIHlE) - 2017/04/01

* [3 easy steps to writing compound components | Steven Natera – Medium](https://medium.com/@stevennatera/3-easy-steps-to-writing-compound-components-5d4647b7bb7) - (2018/05/12) Let’s dive into the world of clean React code with compound components. [Sandbox Editor Example](https://codesandbox.io/s/n4yl5n9vp0).


#### React UI components

* [Using ReactJS and KendoUI Together | if & else](http://www.ifandelse.com/using-reactjs-and-kendoui-together/)

* [[GitHub] mlaursen / react-md](https://github.com/mlaursen/react-md) - React material design

* [[GitHub] callemall / material-ui](https://github.com/callemall/material-ui) - React Components that Implement Google's Material Design

* [React Bootstrap](https://react-bootstrap.github.io/) - The most popular front-end framework, rebuilt for React

* [React Components - reusable components by Khan Academy](https://khan.github.io/react-components/)

* [[GitHub] plaxdan / react-topcoat](https://github.com/plaxdan/react-topcoat) - Topcoat components built with the React library

* [React: HotKeys, Google Maps, Dataminr's UI Components | DailyJS](http://dailyjs.com/2015/04/07/react-components/)

* [[GitHub] danilowoz / create-react-content-loader](https://github.com/danilowoz/create-react-content-loader/) - Now you can use this tool to create your react-content-loader easily

* [[GitHub] uber / react-vis](https://github.com/uber/react-vis) - Data-Visualization oriented components

  * [Data visualization with react-vis | DailyJS – Medium](https://medium.com/dailyjs/data-visualization-with-react-vis-bd2587fe1660) - 2018/03/08

* [[GitHub] YazanAabeed / react-tabs](https://github.com/YazanAabeed/react-tabs) - Simple React Tabs using the new react ContextAPI

  * [[Sandbox Editor] React tabs component](https://codesandbox.io/s/n3jmxm05w4)

* [[GitHub] didierbrun / react-path-recognizer](https://github.com/didierbrun/react-path-recognizer) - Path recognizing component for React


## Patterns

* [You Don’t Need Redux, MobX, RxJS, Cerebral | Fox Donut – Medium](https://medium.com/@foxdonut00/you-dont-need-redux-mobx-rxjs-cerebral-6a735b150a02) - 2018/04/29

--

* Using advanced design patterns to create flexible and reusable React components | ITNEXT (with react 16+)

  * [Part 1: Compound Components](https://itnext.io/using-advanced-design-patterns-to-create-flexible-and-reusable-react-components-part-1-dd495fa1823) - 2018/04/02

  * [Part 2: Context API](https://itnext.io/using-advanced-design-patterns-to-create-flexible-and-reusable-react-components-part-2-react-3c5662b997ab) - 2018/04/09

* [Advanced React/Redux Techniques | How to Use Refs on Connected Components | ITNEXT](https://itnext.io/advanced-react-redux-techniques-how-to-use-refs-on-connected-components-e27b55c06e34) - 2018/05/11


## Router

* [All About React Router 4 | CSS-Tricks](https://css-tricks.com/react-router-4/) - 2017/08/07

* [React Router v4: Philosophy and Introduction | tylermcginnis.com](https://tylermcginnis.com/react-router-philosophy-introduction/) - 2018/01/10

* [Basic intro to React Router v4 | Jason Arnold – Medium](https://medium.com/@thejasonfile/basic-intro-to-react-router-v4-a08ae1ba5c42) - 2017/09/18

* [Handling 404 pages (catch all routes) with React Router v4 | tylermcginnis.com](https://tylermcginnis.com/react-router-handling-404-pages/) - 2018/01/18

* [Nested routes with React Router v4 | tylermcginnis.com](https://tylermcginnis.com/react-router-nested-routes/) - 2018/01/29

* [A Simple React Router v4 Tutorial | Paul Sherman – Medium](https://medium.com/@pshrmn/a-simple-react-router-v4-tutorial-7f23ff27adf) - 2017/03/11

* [[GitHub] ReactTraining / react-router](https://github.com/ReactTraining/react-router) - Declarative routing for React

* [[GitHub] pedsmoreira / named-react-router](https://github.com/pedsmoreira/named-react-router) - Use named routes with react-router v4

* [Protected routes and Authentication with React and Node.js | Medium](https://medium.com/strapi/protected-routes-and-authentication-with-react-and-node-js-d31d234644cd) - 2018/02/21

* tabs

  * [Bootstrap Tabs, React Router, and the active class | Brandon Lehr](http://brandonlehr.com/bootstrap-tabs-react-router-and-the-active-class/) - 2016/06/06

  * [[GitHub] chacestew / react-router-tabs](https://github.com/chacestew/react-router-tabs) - Simple navigation tabs for React Router 4


## Fetch Data

### Axios

> [[GitHub] axios / axios](https://github.com/axios/axios) - Promise based HTTP client for the browser and node.js

* [[YouTube] How to use Axios with React | Paul Halliday](https://www.youtube.com/watch?v=oQnojIyTXb8) - 2018/03/16

  * [Using Axios with React | Alligator.io](https://alligator.io/react/axios-react/)

### Fetch API

> * [[GitHub] github / fetch](https://github.com/github/fetch) - A window.fetch JavaScript polyfill.

* [[YouTube] React 101 - 6/11 - How to use Fetch API with React | Ihatetomatoes](https://www.youtube.com/watch?v=aNMY0lrWZXU) - 2017/11/08

* [YouTube] Using APIs in React - Create a Weather Application | React tutorial for Beginners

  * [Part 1](https://www.youtube.com/watch?v=204C9yNeOYI)

  * [Part 2](https://www.youtube.com/watch?v=P0vsGO4svUM)

  * [[GitHub] hamza-mirza / react-weather-app](https://github.com/hamza-mirza/react-weather-app) - Source code for a React weather app tutorial.

* [Create React App with an Express Backend | Dave Ceddia](https://daveceddia.com/create-react-app-express-backend/) - 2017/04/19


## LocalStorage

* [[YouTube] React 101 - 7/11 - How to use localStorage with React | Ihatetomatoes](https://www.youtube.com/watch?v=ZZS1irWSfxc) - 2017/11/09


## RxJS

* Using RxJS with React.js: – Fahad Ibnay Heylaal – Medium

  * [Part I — Introduction](https://medium.com/@fahad19/using-rxjs-with-react-js-part-i-introduction-4d027ef55aa6) - 2017/03/19

  * [Part 2— Streaming props to Component](https://medium.com/@fahad19/using-rxjs-with-react-js-part-2-streaming-props-to-component-c7792bc1f40f) - 2017/03/19

  * [Part 3 — Dispatching events from Component](https://medium.com/@fahad19/using-rxjs-with-react-js-part-3-dispatching-events-from-component-1808d383cbf0) - 2017/03/22


## Flux Architecture

* [Flux](https://facebook.github.io/flux/)

  * [Flux: An Application Architecture for React | React Blog](https://facebook.github.io/react/blog/2014/05/06/flux.html)

  * [[GitHub] yahoo / flux-examples](https://github.com/yahoo/flux-examples) - Isomorphic React + Flux examples using Dispatchr, Fetchr, and Routr


### Redux

* [[GitHub] reactjs / redux](https://github.com/reactjs/redux) - Predictable state container for JavaScript apps

--

* [[Gist] datchley / react-redux-style-guide.md](https://gist.github.com/datchley/4e0d05c526d532d1b05bf9b48b174faf) - React + Redux Style Guide

* [A Guide to creating Web Applications with React and Redux | Hackernoon](https://hackernoon.com/a-guide-to-creating-web-applications-with-react-and-redux-2f6bc0775951) - 2017/10/31

* [Reactjs and Redux best practices | Abhishek Nalwaya](http://nalwaya.com/javascript/2016/05/02/react-js-best-practices.html) - 2016/05/02

* [an interesting alternative to mocking the #redux dispatch function in order to test middleware | @alexandereardon - twitter](https://twitter.com/alexandereardon/status/996625171610923008)

--

* [Analyze Redux | TOAST UI – Medium](https://medium.com/@toastui/analyze-redux-f1424a5eaa8e) - 2018/05/17

* [Building Chrome Extensions in React+Redux | goguardian](http://blog.goguardian.com/nerds/chrome-extensions-in-react)

* [How Redux can make you a better developer | COBE](https://medium.cobeisfresh.com/how-redux-can-make-you-a-better-developer-30a094d5e3ec) - 2017/11/08

* [Redux Examples](https://react.rocks/tag/Redux)

* [[GitHub] markerikson / react-redux-links](https://github.com/markerikson/react-redux-links) - Curated tutorial and resource links I've collected on React, Redux, ES6, and more

* [[GitHub] erikras / ducks-modular-redux](https://github.com/erikras/ducks-modular-redux) - A proposal for bundling reducers, action types and actions when using Redux

* [Scaling your Redux App with ducks | freeCodeCamp](https://medium.freecodecamp.org/scaling-your-redux-app-with-ducks-6115955638be) - 2017/01/22

  * [[GitHub] FortechRomania / react-redux-complete-example](https://github.com/FortechRomania/react-redux-complete-example) - A react+redux example project

--

* [[YouTube] React-Redux best practice - Better architect applications |
Provash Shoumma](https://www.youtube.com/watch?v=w4t527D69vI) - 2017/10/19

* [[YouTube playlist] Redux Tutorials | LearnCode.academy](https://www.youtube.com/watch?v=1w-oQ-i1XB8&list=PLoYCgNOIyGADILc3iUJzygCqC8Tt3bRXt)

* [[YouTube] Aprenda Redux em 5 minutos | V Plus Plus](https://www.youtube.com/watch?v=Bg0xlUYAp0c) - 2017/04/10

* [[YouTube] Adding Redux to a Simple React App | Dave Ceddia](https://www.youtube.com/watch?v=sX3KeP7v7Kg) - 2017/12/30

* [[YouTube] Redux Tutorial - Learn React/Redux in one video | Learn Coding Tutorials](https://www.youtube.com/watch?v=OSSpVLpuVWA) - 2018/02/12

* [[YouTube playlist] Redux Tutorial | LearnCode.academy](https://www.youtube.com/watch?v=1w-oQ-i1XB8&list=PLoYCgNOIyGADILc3iUJzygCqC8Tt3bRXt)

* [[YouTube] Redux Crash Course With React | Traversy Media](https://www.youtube.com/watch?v=93p3LxR9xfM) - 2018/03/17

  * [[GitHub] bradtraversy / redux_crash_course](https://github.com/bradtraversy/redux_crash_course) - Simple implementation of Redux with React 16

* [[GitHub] redux-offline / redux-offline](https://github.com/redux-offline/redux-offline) - Build Offline-First Apps for Web and React Native

* [Developing Games with React, Redux, and SVG - Part 1 | @auth0](https://auth0.com/blog/developing-games-with-react-redux-and-svg-part-1/) - (2018/02/06) Learn how to make React and Redux control a bunch of SVG elements to create a game.

* [[slides] Redesigning Redux](https://slides.com/shmck/redesigning-redux) - 2018/03/22

* [How to Build a Chat Application using React, Redux, Redux-Saga, and Web Sockets | freeCodeCamp](https://medium.freecodecamp.org/how-to-build-a-chat-application-using-react-redux-redux-saga-and-web-sockets-47423e4bc21a) - 2017/12/07

  * [[YouTube] Build a Chat Application using React, Redux, Redux-Saga, and Web Sockets - Tutorial | freeCodeCamp](https://www.youtube.com/watch?v=x_fHXt9V3zQ) - 2018/01/26

    * [[GitHub] beaucarnes / fcc-project-tutorials / chat](https://github.com/beaucarnes/fcc-project-tutorials/tree/master/chat)


### Redux fetch data

* [[GitHub] oviava / react-redux-axios-example](https://github.com/oviava/react-redux-axios-example) - Example async data fetch with spinner

* [[GitHub] redux-saga / redux-saga](https://github.com/redux-saga/redux-saga) - An alternative side effect model for Redux apps

  * [[YouTube] How to add Redux Saga to Create React App | Ben Awad](https://www.youtube.com/watch?v=Bq_Hkj-G-4c) - 2017/08/10

  * [[YouTube] Fetching data from an API using Redux Saga | Ben Awad](https://www.youtube.com/watch?v=jQ4YD7Ip6T4) - 2017/08/11

    * [[GitHub] benawad / cra-redux-saga](https://github.com/benawad/cra-redux-saga/tree/2_fetch_from_api) - A simple example that uses Redux Saga and Create React App


## Testing

* [Testing | React Community](https://reactjs.org/community/testing.html)

* [[YouTube] Testing Practices and Principles Workshop (Assert.js Conf) - Kent C. Dodds](https://www.youtube.com/watch?v=VQZx1Z3sW0E) - 2018/03/22

* [[GitHub] kentcdodds / react-testing-library](https://github.com/kentcdodds/react-testing-library) - Simple and complete React DOM testing utilities that encourage good testing practices.

  * [Introducing the react-testing-library 🐐 | kentcdodds](https://blog.kentcdodds.com/introducing-the-react-testing-library-e3a274307e65) - 2018/04/02

* [Testing React Apps | Jest - Facebook](https://facebook.github.io/jest/docs/en/tutorial-react.html)

* [Testing React Components Best Practices | selleo – Medium](https://medium.com/selleo/testing-react-components-best-practices-2f77ac302d12) - 2017/03/03

* [Testing React with Enzyme and Jest: A Video Series](https://javascriptplayground.com/testing-react-enzyme-jest/) - First five episodes are free.


---

## Peer-to-peer

* [Build a Peer-to-Peer File Sharing Component in React & PeerJS | SitePoint](http://www.sitepoint.com/file-sharing-component-react/) - 2016/04/11

  * [[GitHub] sitepoint-editors / react-filesharer](https://github.com/sitepoint-editors/react-filesharer) - A React peer-to-peer file sharing component, using PeerJS


## Real time

### Socket.io

* [[GitHub] Cretezy / Noderize / examples / chat-socket-react](https://github.com/Cretezy/Noderize/tree/master/examples/chat-socket-react) - chat server + react chat client

* [Combining React with Socket.io for real-time goodness | DailyJS](https://medium.com/dailyjs/combining-react-with-socket-io-for-real-time-goodness-d26168429a34) - 2017/06/08

* [Build A Real-Time Twitter Stream with Node and React.js | Scotch](https://scotch.io/tutorials/build-a-real-time-twitter-stream-with-node-and-react-js)

  * [[GitHub] scotch-io / react-tweets](https://github.com/scotch-io/react-tweets)

* [Real Time Trader Desktop with React, Node.js, and Socket.io | Christophe Coenraets](http://coenraets.org/blog/2015/03/real-time-trader-desktop-with-react-node-js-and-socket-io/) - 2015/03/24

  * [[GitHub] ccoenraets / react-trader](https://github.com/ccoenraets/react-trader) - Sample application built with React and Socket.io

* [ReactJS and Socket.IO Chat Application | Danial Khosravi's Blog](https://danialk.github.io/blog/2013/06/16/reactjs-and-socket-dot-io-chat-application/) - 2015/07/13

  * [[GitHub] DanialK / ReactJS-Realtime-Chat](https://github.com/DanialK/ReactJS-Realtime-Chat) - ReactJS and Socket.IO Chat Application

* [[YouTube] 15 - Curso React - SocketIO + React | codigofacilito](https://www.youtube.com/watch?v=KkjtC1UrUCI)

* [[YouTube Playlist] Real Time Chat App with ReactJS and Socket.io | Leon Watson](https://www.youtube.com/watch?v=84GXJANOYFw&list=PLfUtdEcvGHFHdOYFXj4cY6ZIFkSp6MOuY)

* [[YouTube] Hangout #1 - Desenvolvendo um chat com React e Node.js do zero | Deividy Metheler Zachetti](https://www.youtube.com/watch?v=jetavHnJFxw) - 2018/03/02

  * [[YouTube] Hangout #2 - Usando Redux com React na prática | Deividy Metheler Zachetti](https://www.youtube.com/watch?v=ds6BuQbtQg0) - 2018/03/09

  * [[GitHub] fullninja / livechat](https://github.com/fullninja/livechat) - Final version of live chat, start development in youtube hangout

* [[YouTube] Basic Real-time Web App using React and Feathersjs | Ben Awad](https://www.youtube.com/watch?v=l2OIBV4RfAU) - Learn how to use sockets with react, redux, and [feathersjs](https://feathersjs.com/).

  * Project template : [[GitHub] benawad / react-template](https://github.com/benawad/react-template) - Has all the boilerplate filled out for react + react-router + redux + redux-saga + semantic-ui

  * [[GitHub] benawad / basic-realtime-react-client](https://github.com/benawad/basic-realtime-react-client) - Basic websockets example using React for the client and feathersjs for the backend


## i18n - Internationalization

* [React & Redux - Internationalisation | David Bushell – Web Design (UK)](https://dbushell.com/2018/04/05/react-redux-internationalisation/) - 2018/04/05

* [Building an Awesome App with i18n in React | PhraseApp Blog](https://phraseapp.com/blog/posts/react-i18n-app/) - 2018/02/26

  * [[GitHub] ashour / react-i18n-demo](https://github.com/ashour/react-i18n-demo/) - React i18n demo apps — companions to PhraseApp blog article

* [[GitHub] alexdrel / i18n-react](https://github.com/alexdrel/i18n-react) - React (JS) text internationalization and externalizing

  * [Getting started with internationalization (i18n) in React | Our Code World](https://ourcodeworld.com/articles/read/395/getting-started-with-internationalization-i18n-in-react) - 2017/02/19

* [[GitHub] i18next / react-i18next](https://github.com/i18next/react-i18next) - Internationalization for react done right. Using the i18next i18n ecosystem.

  * [I18n with React and i18next | Alligator.io](https://alligator.io/react/i18n-with-react-and-i18next/) - 2017/10/24

* [[GitHub] yahoo / react-intl](https://github.com/yahoo/react-intl) - Internationalize React apps. This library provides React components and an API to format dates, numbers, and strings, including pluralization and handling translations.

  * [Internationalization in React | freeCodeCamp](https://medium.freecodecamp.org/internationalization-in-react-7264738274a0)

---

## Performance

* [[GitHub] amsul / react-performance](https://github.com/amsul/react-performance) - Helpers to debug and record component render performance

* [Debugging React performance with React 16 and Chrome Devtools | Building Calibre](https://building.calibreapp.com/debugging-react-performance-with-react-16-and-chrome-devtools-c90698a522ad) - 2017/11/27

* [How to greatly improve your React app performance | MyHeritage Engineering – Medium](https://medium.com/myheritage-engineering/how-to-greatly-improve-your-react-app-performance-e70f7cbbb5f6) - 2017/11/21

* [45% Faster React Functional Components, Now | Missive App – Medium](https://medium.com/missive-app/45-faster-react-functional-components-now-3509a668e69f) - 2017/05/03

* [Optimizing loading time for big React apps | SmartboxTv Engineering – Medium](https://medium.com/smartboxtv-engineering/optimizing-loading-time-for-big-react-apps-cf13bbf63c57) - 2017/04/04

* [Tips to optimise rendering of a set of elements in React | Medium by @lavrton](https://blog.lavrton.com/how-to-optimise-rendering-of-a-set-of-elements-in-react-ad01f5b161ae) - (2016/05/11) There is a guide to increase React performance. The advanced tip will increase speed by 20 times.

* [Optimize React Performance | DailyJS](https://medium.com/dailyjs/optimize-react-performance-c1a491ed9c36) - (2017/08/12) How to improve React performance in production and avoid common mistakes

* [Twitter Lite and High Performance React Progressive Web Apps at Scale | Medium by @paularmstrong](https://medium.com/@paularmstrong/twitter-lite-and-high-performance-react-progressive-web-apps-at-scale-d28a00e780a3) - 2017/04/11

---

### React server-side rendering

* [[GitHub] rherwig / template-react-16-ssr](https://github.com/rherwig/template-react-16-ssr) - Server-side rendering template using express and react 16


---

## React.js 16+

* [Novidades do React 16 | Willian Justen](https://willianjusten.com.br/novidades-do-react-16/) - 2017/09/28

* [Using a React 16 Portal to do something cool | Hackernoon](https://hackernoon.com/using-a-react-16-portal-to-do-something-cool-2a2d627b0202) - 2017/11/07

* [Usando os portais do React para criar modais mais práticos | CodePrestige - Medium](https://medium.com/code-prestige/usando-os-portais-do-react-para-criar-modais-mais-pr%C3%A1ticos-fe1db6ab68f2) - 2017/11/22


### Context API

* [Context API | React Docs](https://reactjs.org/docs/context.html)

* [[GitHub] diegohaz / awesome-react-context](https://github.com/diegohaz/awesome-react-context) - A curated list of stuff related to the new React Context API

* [Understanding the React Context API | Alligator.io](https://alligator.io/react/context-api/) - 2018/04/24

* [Migrating to React’s New Context API | kentcdodds](https://blog.kentcdodds.com/migrating-to-reacts-new-context-api-b15dc7a31ea0) - 2018/04/23

* [Putting Things in Context With React | CSS-Tricks](https://css-tricks.com/putting-things-in-context-with-react/) - 2018/03/21

* [React’s new Context API | Codementor](https://www.codementor.io/kentcdodds/react-s-new-context-api-gqlqavqyv) - 2018/02/14

* [React’s new Context API | kentcdodds](https://blog.kentcdodds.com/reacts-%EF%B8%8F-new-context-api-70c9fe01596b) - 2018/02/05

  * [[CodeSandbox] Example of React's new context API](https://codesandbox.io/s/n4r0qq898j)

* [React’s safe Context API | codeburst](https://codeburst.io/reacts-impending-safe-context-api-630d119c93f4) - 2018/03/08

  * [[Codepen] Day & Night toggle w/ React Context API ☀️🌔😎](https://codepen.io/jh3y/pen/WzeJZz)

* [How to Use New React Context Api detailed | codeburst](https://codeburst.io/how-react-context-api-works-detailed-4fc483d93fd0) - 2018/04/05

  * [[GitHub] saigowthamr / React-context-api](https://github.com/saigowthamr/React-context-api) - how react context api works

* [[YouTube] React Context API | Dave Bennett - Development](https://www.youtube.com/watch?v=W_0z_6pMokA) - 2018/03/21

* [[YouTube] React 16.3 - New Context API, Updated Lifecycle Hooks, New Ref API | Academind](https://www.youtube.com/watch?v=yaZzJ37Qb0U) - 2018/04/04

* [[YouTube] Migrating from Redux to the New React Context API |
Handlebar Labs](https://www.youtube.com/watch?v=ISgz8F9z0aM) - 2018/03/13

  * [[YouTube] HandlebarLabs / currency-converter-starter](https://github.com/HandlebarLabs/currency-converter-starter) - Code for the React Native Basics: Build a Currency Converter Course | changes : [moving from redux to the context api](https://github.com/HandlebarLabs/currency-converter-starter/compare/e96b8b31529291029ce56d9cd1dab352a4a09102...dfd226dee89d2aa723470b567fab3a957e294822)

* [How to create react-tabs using ContextAPI | DailyJS](https://medium.com/dailyjs/how-to-create-react-tabs-using-contextapi-932c7bec35c7) - 2018/05/11


### Render Props

* [[GitHub] jaredpalmer / awesome-react-render-props](https://github.com/jaredpalmer/awesome-react-render-props) - Awesome list of React components with render props

* [[GitHub] jaredpalmer / awesome-react-render-props](https://github.com/jaredpalmer/awesome-react-render-props) - Awesome list of React components with render props

* [[GitHub] jaredpalmer / react-fns](https://github.com/jaredpalmer/react-fns) - Browser API's turned into declarative React components and HoC's

* [Use a Render Prop! | componentDidBlog](https://cdb.reacttraining.com/use-a-render-prop-50de598f11ce) - 2017/09/18

* [Answers to common questions about render props | kentcdodds](https://blog.kentcdodds.com/answers-to-common-questions-about-render-props-a9f84bb12d5d) - 2018/02/12

* [Testing React components using render props | kentcdodds](https://blog.kentcdodds.com/testing-%EF%B8%8F-components-using-render-props-5623ab1814c) - 2018/01/08

---

## Mobile

* [Sample Mobile Application with React and Cordova | Christophe Coenraets](http://coenraets.org/blog/2014/12/sample-mobile-application-with-react-and-cordova/)

  * [[GitHub] ccoenraets / react-employee-directory](https://github.com/ccoenraets/react-employee-directory) - Sample Application with the React Framework

--

* [reapp : Hybrid apps, fast](http://reapp.io/) - Make beautiful hybrid apps that feel great with React, Webpack and ES6

* [Make your own React production version with webpack | Topheman JS](http://dev.topheman.com/make-your-react-production-minified-version-with-webpack/) - 2015/11/12


### React Native

* [React Native](https://facebook.github.io/react-native/) - enables you to build world-class application experiences on native platforms using a consistent developer experience based on JavaScript and React.

* [[GitHub] facebook / react-native](https://github.com/facebook/react-native) - A framework for building native apps with React.

* [React Native: Bringing modern web techniques to mobile | Engineering Blog | Facebook Code](https://code.facebook.com/posts/1014532261909640/react-native-bringing-modern-web-techniques-to-mobile/)

* [React Native Fundamentals | Video Tutorial Series - @eggheadio](https://egghead.io/series/react-native-fundamentals)

* [How Facebook Focuses on the Most Important Element of an App  | Airbnb Engineering](http://nerds.airbnb.com/facebook-react-native/) - 2015/08/31

* [Why You Should Consider React Native For Your Mobile App | Smashing Magazine](https://www.smashingmagazine.com/2016/04/consider-react-native-mobile-app/) - 2016/04/07

--

* [[GitHub] Microsoft / reactxp](https://github.com/Microsoft/reactxp) - Library for cross-platform app development.

* [[GitHub] garthenweb / react-native-e2etest](https://github.com/garthenweb/react-native-e2etest)

* [[GitHub] gabrielbull / react-desktop](https://github.com/gabrielbull/react-desktop) - React UI Components for macOS Sierra and Windows 10

--

* [Deco IDE](https://www.decosoftware.com/) - the React Native IDE


---

## preact

* [[GitHub] developit / preact](https://github.com/developit/preact) - Fast 3kb React alternative with the same ES6 API. Components & Virtual DOM.

* [[GitHub] developit / preact-cli](https://github.com/developit/preact-cli) - Your next Preact PWA starts in 30 seconds.

--

* [Getting started with PreactJS — A Step By Step Guide | Codeinfuse](https://blog.codeinfuse.com/getting-started-with-preactjs-a-step-by-step-guide-f3197f871753) - (2017/06/08) PreactJS is a fast 3kB alternative to React with the same ES6 API

* [Up and running with Preact - Course by @shaneosbourne | @eggheadio](https://egghead.io/courses/up-and-running-with-preact)

* [Introduction to Preact — a smaller, faster React alternative | @LogRocketJS](https://blog.logrocket.com/introduction-to-preact-a-smaller-faster-react-alternative-ad5532eb6d79) - 2017/08/14

* [How I Cut My React Javascript Bundle Size In Half With Three Lines of Code | codeburst](https://codeburst.io/how-i-cut-my-react-javascript-bundle-size-in-half-with-three-lines-of-code-fe7798ecbd3f) - 2018/01/26

--

* [[GitHub] synacor / wiretie](https://github.com/synacor/wiretie) - A Higher Order Component for Preact that resolves (async) values from a model and passes them down as props.

* [[GitHub] synacor / preact-i18n](https://github.com/synacor/preact-i18n) - Simple localization for Preact
