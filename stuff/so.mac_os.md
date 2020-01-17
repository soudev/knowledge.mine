# Mac OS X

<!-- toc -->

* [Dicas](#dicas)
* [Games](#games)
* [Audio e Vídeo](#audio-e-vídeo)
  * [Media Center](#media-center)
  * [Editores de Vídeo](#editores-de-vídeo)
  * [Editores de Audio](#editores-de-audio)
* [Setup Environment](#setup-environment)
  * [Fontes](#fontes)
  * [Colors](#colors)
  * [dotFiles](#dotfiles)
* [Desenvolvimento](#desenvolvimento)
  * [UNIX](#unix)
  * [Shell](#shell)
  * [AWS](#aws)
  * [Swift](#swift)
  * [Ruby](#ruby)
  * [Java](#java)
  * [Node.js](#nodejs)
  * [JavaScript](#javascript)
  * [SQL](#sql)
* [Hardware](#hardware)
  * [mackbook pro 2015](#mackbook-pro-2015)
    * [HDD para SSD](#hdd-para-ssd)
    * [Trocar o DVD por um segundo HD](#trocar-o-dvd-por-um-segundo-hd)
  * [mackbook pro setup 2017](#mackbook-pro-setup-2017)
* [OS](#os)
  * [Mavericks](#mavericks)
  * [El Capitan](#el-capitan)
* [Hackintosh](#hackintosh)

<!-- toc stop -->


## Dicas

* [Startup key combinations for Mac | Apple Support](https://support.apple.com/en-us/HT201255)

* [Reset the DNS cache in OS X | Apple Support](https://support.apple.com/en-us/HT202516) - Learn how to reset (flush) the DNS cache.

* [Find (and kill) process locking port 3000 on Mac | StackOverflow](https://stackoverflow.com/questions/3855127/find-and-kill-process-locking-port-3000-on-mac)

--

* message on the login screen ([tweet](https://twitter.com/chadwhitaker/status/1004441991415922688))

```
sudo defaults write /Library/Preferences/com.apple.loginwindow LoginwindowText "MESSAGE HERE"
```

--

* check the stored WiFi password

```
security find-generic-password -wa [wifi network name]
```

--

* [[GitHub] jaywcjlove / awesome-mac](https://github.com/jaywcjlove/awesome-mac/blob/master/README-en.md) - collection of awesome Mac applications and tools for developers and designers.

* [[GitHub] serhii-londar / open-source-mac-os-apps](https://github.com/serhii-londar/open-source-mac-os-apps) - Awesome list of open source applications for macOS.

--

* [iStats Menu | bjango](https://bjango.com/mac/istatmenus/) - an advance mac system monitor for your menubar

* [[GitHub] Chris911 / iStats](https://github.com/Chris911/iStats) - Ruby gem for your mac stats

* [[GitHub] DanielStormApps / Fanny](https://github.com/DanielStormApps/Fanny) - Monitor your Mac's fan speed and CPU temperature from your Notification Center.

* [[GitHub] gjiazhe / Up-Down](https://github.com/gjiazhe/Up-Down) - A menu bar widget for OS X that monitors upload and download speeds

* [[GitHub] matryer / bitbar](https://github.com/matryer/bitbar) - Put the output from any script or program in your Mac OS X Menu Bar

--

* [[GitHub] vutran / dext](https://github.com/vutran/dext) - A smart launcher for Mac. Powered by JavaScript

--

* [Muzzle](https://muzzleapp.com/) - silence embarrassing notifications

* [numi](http://numi.io/) - beautiful calculator for mac

* [16 apps gratuitos para Mac que você não pode deixar de conhecer | BR-Mac.org](http://br-mac.org/2014/01/16-apps-gratuitos-para-mac-que-voce-nao-pode-deixar-de-conhecer.html)

--

* [Configurando o Terminal no Mac OS X | Simples Ideias](http://simplesideias.com.br/configurando-o-terminal-no-mac-os-x)

* [TermHere | Mac App Store](https://itunes.apple.com/us/app/termhere/id1114363220) - jump from a Finder window to a terminal window in the same directory

--

* [Homebrew](http://brew.sh/) - is a package manager for OS X | [github](https://github.com/Homebrew/homebrew)

  * [Cakebrew - The Mac App for Homebrew](https://www.cakebrew.com/) | [github](https://github.com/brunophilipe/Cakebrew)

--

* [AppCleaner | freemacsoft](http://freemacsoft.net/appcleaner/) - is a small application which allows you to thoroughly uninstall unwanted apps.

--

* [Alfred](https://www.alfredapp.com/)

* [Lacona](https://www.lacona.io/)

* [Cerebro App](https://cerebroapp.com/) – open-source productivity booster with a brain

  * [[GitHub] KELiON / cerebro](https://github.com/KELiON/cerebro) - Open-source productivity booster with a brain

  * [[YouTube] Use o CEREBRO para agilizar a sua vida no Linux, Windows e macOS | Diolinux](https://www.youtube.com/watch?v=AsSFcmoUGfA)

--

* [Rescue Time](https://www.rescuetime.com/) - helps you understand your daily habits so you can focus and be more productive.

* [SelfControl](https://selfcontrolapp.com/) - is a free and open-source application for Mac OS X that lets you block your own access to distracting websites, your mail servers, or anything else on the Internet. Just set a period of time to block for, add sites to your blacklist, and click "Start." Until that timer expires, you will be unable to access those sites--even if you restart your computer or delete the application.

--

* [[GitHub] zehfernandes / pliim](https://github.com/zehfernandes/pliim) - One click and be ready to go up on stage and shine! (macOS 10.11 or above)

* [[GitHub] Eun / DisableMonitor](https://github.com/Eun/DisableMonitor) - Easily disable or enable a monitor on your Mac

* Move windows

  * [Moom](http://manytricks.com/moom/) - Do you spend a lot of time moving and zooming windows, so you can better see and work with all the content on your Mac? Instead of doing that work yourself, let Moom handle the task for you. - U$ 10

  * [BetterTouchTool](http://www.boastr.de/) - BetterTouchTool is a great, feature packed FREE app that allows you to configure many gestures for your Magic Mouse, Macbook Trackpad and Magic Trackpad. It also allows you to configure actions for keyboard shortcuts, normal mice and the Apple Remote.

  * [Spectacle](http://spectacleapp.com/) - Move and resize windows with ease. Free and OpenSource.

    * [[GitHub] eczarny / spectacle](https://github.com/eczarny/spectacle) - Spectacle allows you to easily organize your windows without using a mouse.

  * [[GitHub] fikovnik / ShiftIt](https://github.com/fikovnik/ShiftIt) - Managing windows size and position in OSX

--

* [[GitHub] jipegit / OSXAuditor](https://github.com/jipegit/OSXAuditor) - is a free Mac OS X computer forensics tool

--

* [[GitHub] prasmussen / chrome-cli](https://github.com/prasmussen/chrome-cli) - Control Google Chrome from the command line

* [Como usar o editor iMovie; veja os truques para Mac | Dicas e Tutoriais | TechTudo](http://www.techtudo.com.br/dicas-e-tutoriais/noticia/2014/02/como-usar-o-editor-imovie-veja-os-truques-para-mac.html)

* [Recordit](http://recordit.co/) - Record screencasts fast & free! with GIF Support!

--

* [[Apple Store] Dash (Docs & Snippets)](https://itunes.apple.com/br/app/dash-docs-snippets/id458034879?l=en&mt=12)

--

* [Como saber a condição da bateria do MacBook e aumentar sua vida útil | TechTudo](http://www.techtudo.com.br/dicas-e-tutoriais/noticia/2014/06/como-saber-condicao-da-bateria-do-macbook-e-aumentar-sua-vida-util.html)

* [Making the Touch Bar finally useful :: By abandoning crappy Apple guidelines | vas3k's blog](http://vas3k.com/blog/touchbar/) - 2018/04/02


## Games

* [OpenTTD](http://www.openttd.org/) - is an open source simulation game based upon Transport Tycoon Deluxe

* [OpenRA](http://www.openra.net/) - is a project that recreates and modernizes the classic Command & Conquer real time strategy games. We have developed a flexible open source game engine (the OpenRA engine) that provides a common platform for rebuilding and reimagining classic 2D and 2.5D RTS games (the OpenRA mods).

  * [[GitHub] OpenRA / OpenRA](https://github.com/OpenRA/OpenRA)

* [OpenEmu](http://openemu.org/) - Multiple Video Game System

--

* [Descent Game | GameNostalgia](http://gamesnostalgia.com/en/game/descent) - is a 3D sci-fi first-person shooter notable for the six axis movement, developed by Parallax Software and released by Interplay in 1995.


## Audio e Vídeo

* [[GitHub] JadenGeller / Helium](https://github.com/JadenGeller/Helium) - A floating browser window for OS X

* [[GitHub] romankisil / eqMac2](https://github.com/romankisil/eqMac2) - System-wide Audio Equalizer for the Mac


### Media Center

* [Plex](https://plex.tv/) - organizes your video, music, and photo collections and streams them to all of your screens.

* [Stremio](http://www.strem.io/) - Watch videos, movies, TV series and TV channels instantly.


### Editores de Vídeo

* [[GitHub] wulkano / kap](https://github.com/wulkano/kap) - An open-source screen recorder built with web technology

* [How to record screencast videos with Mac OSX | The Next Web](http://thenextweb.com/apple/2011/01/15/how-to-record-quick-easy-screencast-videos-with-mac-osx/)

* [ScreenFlow | Telestream](http://www.telestream.net/screenflow/) - Screen recording and video editing software for creating high-quality software demos, video tutorials, video training, and presentations.


### Editores de Audio

* [Audacity: Free Audio Editor and Recorder](http://audacity.sourceforge.net/) - é um editor de audio de código aberto, e entre seus recursos estão a reprodução e gravação, importação e exportação de vários formatos de audio (MP3, Ogg, WAV, FLAC e AIFF).

* [Ardour](http://ardour.org/) - é um editor de código aberto utilizado normalmente por profissionais em audio digital. Para editar, o aplcativo possui recursos como arrastar, cortar, dividir e estender partes de uma trilha de audio. Também é possivel capturar sons e realizar mixagens. Além disso, permite a integração com o Jack OS X e a possibilidade de expostar arquivos TOC e CUE. Está disponível para Mac OS X e Linux.

* [OcenAudio](http://www.ocenaudio.com.br/)

  * [Ocenaudio: um editor de arquivos de áudio gratuito, rápido, simplificado e feito no Brasil | MeioBit](http://meiobit.com/294171/ocenaudio-um-editor-de-arquivos-de-audio-gratuito-rapido-simplificado-e-feito-brasil/)


## Setup Environment

* [[GitHub] sb2nov / mac-setup](https://github.com/sb2nov/mac-setup) - Installing Development environment on Mac OS X

* [Setup a Mac Dev Machine From Scratch | Laracasts](https://laracasts.com/series/setup-a-mac-dev-machine-from-scratch)

* [SublimeText, iTerm, and Chrome setup | Damian Le Nouaille](http://www.damln.com/log/setup/)

* [[Gist] millermedeiros / osx_setup.md](https://gist.github.com/millermedeiros/6615994) - Mac OS X Mountain Lion setup

* [[Gist] zenorocha / osx-setup.md](https://gist.github.com/zenorocha/7159780) - Setup Mac OS X Mavericks (10.9)


### Fontes

* [Web Font Generator for Mac OSX | FontPrep](http://fontprep.com/)

  * [[GitHub] briangonzalez / fontprep](https://github.com/briangonzalez/fontprep) - The missing font generator for Mac OSX


### Colors

* [LSCOLORS Generator | Geoff Greer](http://geoff.greer.fm/lscolors/) - terminal `export LSCOLORS=GxFxCxDxBxegedabagaced`

* [[GitHub] hukl / Smyck-Color-Scheme](https://github.com/hukl/Smyck-Color-Scheme) - Color Scheme for Terminal.app, iTerm2, Vim, MacVim, Sublime Text2 and Textmate


### dotFiles

* [[GitHub] webpro / awesome-dotfiles](https://github.com/webpro/awesome-dotfiles) - A curated list of dotfiles resources.

--

* [dotfiles.github.io](http://dotfiles.github.io/)

* [[GitHub] mathiasbynens / dotfiles](https://github.com/mathiasbynens/dotfiles) - .files, including ~/.osx — sensible hacker defaults for OS X

* [[GitHub] paulirish / dotfiles](https://github.com/paulirish/dotfiles)

* [[GitHub] addyosmani / dotfiles](https://github.com/addyosmani/dotfiles)

* [[GitHub] zenorocha / dotfiles](https://github.com/zenorocha/dotfiles) - OS X dotfiles

* [[GitHub] davidsonfellipe / dotfiles](https://github.com/davidsonfellipe/dotfiles) - OS X dotfiles

* [[GitHub] luanmuniz / dotfiles](https://github.com/luanmuniz/dotfiles) - Script de configuração de workspace

* [[GitHub] holman / dotfiles](https://github.com/holman/dotfiles)

--

* [[GitHub] alrra / dotfiles](https://github.com/alrra/dotfiles) - OS X / Ubuntu dotfiles

--

* [[GitHub] eduardolundgren / dotfiles](https://github.com/eduardolundgren/dotfiles) - The first JavaScript-based dotfiles powered by Grunt


## Desenvolvimento

* [Make your app extensible with JavaScript Core | iOS App Development - Medium](https://medium.com/ios-os-x-development/make-your-app-extensible-with-javascript-core-7074061f2b05)


### UNIX

* [VIM Adventures](http://vim-adventures.com/) - is an online game based on VIM's keyboard shortcuts. It's the "Zelda meets text editing" game. So come have some fun and learn some VIM!

* [Desvendando o editor Vim | Blog Caelum](http://blog.caelum.com.br/desvendando-o-editor-vim/)


### Shell

* [[GitHub] guarinogabriel / Mac-CLI](https://github.com/guarinogabriel/Mac-CLI) - OS X command line tools for developers – The ultimate tool to manage your Mac. It provides a huge set of command line commands that automatize the usage of your OS X system.

* [[GitHub] herrbischoff / awesome-osx-command-line](https://github.com/herrbischoff/awesome-osx-command-line) - Use your OS X terminal shell to do awesome things

* [Unix: a base de tudo! | Blog - Vitor Britto](http://www.vitorbritto.com.br/blog/unix-a-base-de-tudo/)

* [.bashrc generator](http://bashrcgenerator.com/) - create your .bashrc PS1 with a drag and drop interface

* [The Bash Guide](http://guide.bash.academy/) - A complete guide for newcomers and advanced users to correct usage and deep understanding of the bash shell language.

* [[GitHub] alexanderepstein / Bash-Snippets](https://github.com/alexanderepstein/Bash-Snippets) - A collection of small bash scripts for heavy terminal users


### AWS

* [[GitHub] kwent / aws-launcher](https://github.com/kwent/aws-launcher) - AWS Launcher. Launch AWS Services from your macOS dock.


### Swift

* [Swift](https://developer.apple.com/swift/)

* [Swift Blog | Apple Developer](https://developer.apple.com/swift/blog/)

* [The Swift Programming Language - Book | iTunes](https://itunes.apple.com/br/book/swift-programming-language/id881256329)

* [Swift Cheat Sheet and Quick Reference | Ray Wenderlich](http://www.raywenderlich.com/73967/swift-cheat-sheet-and-quick-reference)

* [[GitHub] fullstackio / FlappySwift](https://github.com/fullstackio/FlappySwift) - swift implementation of flappy bird. More at [fullstackedu.com](https://www.fullstackedu.com/)


### Ruby

* [[GitHub] sstephenson / rbenv](https://github.com/sstephenson/rbenv) - Groom your app’s Ruby environment


### Java

* [Java for OS X | Apple Support](http://support.apple.com/kb/DL1572)

--

* [JDK 8 Installation for OS X | Oracle Documentation](https://docs.oracle.com/javase/8/docs/technotes/guides/install/mac_jdk.html)

* [JDK 7 Installation for Mac OS X | Oracle Documentation](http://docs.oracle.com/javase/7/docs/webnotes/install/mac/mac-jdk.html)

--

* [[Gist] How To Install Java 8 on Mac](https://gist.github.com/tomysmile/a9a7aee85ff73454bd57e198ad90e614)

* [How to install JDK 8 on Mac OS X | dalanzg.github.io](https://dalanzg.github.io/tips-tutorials/mac/2015/11/22/how-to-install-jdk-8-on-mac-os-x/) - 2015/11/22

* [How do I update Java for my Mac? | Java](https://www.java.com/en/download/help/mac_java_update.xml) - Java 7+

* [[StackOverflow] Installing Java on OS X 10.9 (Mavericks)](https://stackoverflow.com/questions/19533528/installing-java-on-os-x-10-9-mavericks)

--

* [How to Set $JAVA_HOME environment variable on Mac OS X | mkyong.com](mkyong.com)

--

* [[GitHub] wonder-mice / mac-java-launcher](https://github.com/wonder-mice/mac-java-launcher) - Launcher for bundled java application on Mac OS

* WebStorm 9.0.2

```
  > inicialmente pede pelo java 1.6

  alterar:

/Applications/WebStorm.app/Contents/Info.plist

  procura por JVMVersion:

    substitui do 1.6* para 1.6+
```

### Node.js

* [[StackOverflow] NPM throws error without sudo](https://stackoverflow.com/questions/16151018/npm-throws-error-without-sudo)

* [[GitHub] creationix / nvm](https://github.com/creationix/nvm) - Node Version Manager - Simple bash script to manage multiple active node.js versions

* [How to uninstall Node.js on Mac | Maxwhale.com](http://www.maxwhale.com/how-to-uninstall-node-js-on-mac/)

* [[gist] Mac OS X uninstall script for packaged install of node.js](https://gist.github.com/nicerobot/2697848)


### JavaScript

* [[GitHub] dtinth / JXA-Cookbook](https://github.com/dtinth/JXA-Cookbook) - Cookbook for JavaScript for Automation in Mac OS X Yosemite


### SQL

* [[GitHub] sequelpro / sequelpro](https://github.com/sequelpro/sequelpro) - MySQL database management for Mac OS X

* [SQuirreL SQL Client](http://squirrel-sql.sourceforge.net/) - It is Java / JDBC and supports a very wide range of SQL backends. It is also plugin-based and has a surprising number of plugins.

* [RazorSQL - Query, Edit, Browse, and Manage Databases](http://www.razorsql.com/) - has been tested on over 30 databases, can connect to databases via either JDBC or ODBC.

* [GUI Tools for PostgreSQL on the Mac](http://postgresapp.com/documentation/gui-tools.html)


## Hardware

### mackbook pro 2015

#### HDD para SSD

>
> Dica: antes de iniciar a instalação do SO, formate o SSD no padrão: `Mac OS Extended (Journaled)`
>
> Lembre-se: crie um nome, por exemplo: `Macintosh SSD`
>

* [Dobre a performance do seu Mac fazendo um upgrade de SSD | MacMagazine](http://macmagazine.com.br/2014/09/06/dobre-a-performance-do-seu-mac-fazendo-um-upgrade-de-ssd/) - 2014/09/06


#### Trocar o DVD por um segundo HD

* [Unibody Laptop Dual Drive | iFixit](https://www.ifixit.com/Store/Mac/Unibody-Laptop-Dual-Drive/IF107-080)

* [[YouTube] Mac Book Pro - Second Hard Drive Install Tutorial DIY](https://www.youtube.com/watch?v=dSwIoSnz7aY) - In this video we take out the Optical hard drive in my macbook pro (2011 Coire i5) And Replace it with a 1 TB hard drive. We do this by adding a caddie in place of the optical Hard drive. [2013/08/01]

  * [Universal Macbook Hard drive Caddie | Amazon](http://amzn.com/B004FM4UGE)


### mackbook pro setup 2017

* [[YouTube] Ultimate Macbook Pro 5K Dual Monitor Desk Setup Tour (2017) | Danny Winget
](https://www.youtube.com/watch?v=HhHoJ6NwOAc) - 2017/08/18

* [[YouTube] FutureProof MacBook Pro Setup 2017 - USB-C Heaven! | TeQreation](https://www.youtube.com/watch?v=8FPUlPJtL9s) - 2017/07/28

* [[YouTube] My Ultimate MacBook Pro Setup 2017! | UrAvgConsumer](https://www.youtube.com/watch?v=Jn20LcQ9Qco) - 2017/07/27


## OS

### Mavericks

* [Everything You Need to Know About OS X Mavericks | Mac.AppStorm](http://mac.appstorm.net/reviews/os-x-reviews/everything-you-need-to-know-about-os-x-mavericks/)

* [Command Line Tools on OSX Mavericks | Marcos Junior](http://webmarcos.net/2013/11/20/command-line-tools-on-osx-mavericks/)

* [Como criar um pendrive de instalação do OS X Mavericks | Meio Bit](http://meiobit.com/270071/como-instalar-os-x-mavericks-atraves-do-pendrive-usb/)

* [How to Create an OS X Mavericks USB Installation Drive | Lifehacker](http://lifehacker.com/how-to-create-an-os-x-mavericks-usb-installation-drive-1450280026)


### El Capitan

* [How to Burn OS X El Capitan to a USB Flash Drive | Lifehacker](http://lifehacker.com/how-to-burn-os-x-el-capitan-to-a-usb-flash-drive-1733425133) - 2015/09/30

  * [PSA: An Expired Certificate Means You'll Need to Remake Any OS X USB Boot Drives | Lifehacker](http://lifehacker.com/psa-an-expired-certificate-means-youll-need-to-remake-1762704972)


## Hackintosh

* [[YouTube] Xiaomi NoteBook PRO HACKINTOSH GUIA DE INSTALAÇÃO](https://www.youtube.com/watch?v=I81H24Iu52U) - 2018/02/28

* [[YouTube] Super Simple Hackintosh Install 2018](https://www.youtube.com/watch?v=12BvDIMAy6Y) - 2018/01/04
