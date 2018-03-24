# Virtual Machine / Máquina Virtual

<!-- toc -->

* [Docker](#docker)
  * [Informações](#informações)
  * [Aprendizado](#aprendizado)
  * [Dockerfile](#dockerfile)
  * [Dicas](#dicas)
  * [Private Registry](#private-registry)
  * [Ambiente de desenvolvimento](#ambiente-de-desenvolvimento)
    * [Mac OS X](#mac-os-x)
    * [Windows](#windows)
  * [Continuous Integration](#continuous-integration)
  * [Raspberry Pi](#raspberry-pi)
  * [Caso de Uso](#caso-de-uso)
  * [Soluções](#soluções)
  * [Node.js](#nodejs)
  * [Oracle](#oracle)
  * [Red Hat](#red-hat)
  * [Amazon Cloud](#amazon-cloud)
  * [Google Cloud](#google-cloud)
  * [Windows Azure](#windows-azure)

<!-- toc stop -->


## Docker

> Docker is an open-source project to easily create lightweight, portable, self-sufficient containers from any application. The same container that a developer builds and tests on a laptop can run at scale, in production, on VMs, bare metal, OpenStack clusters, public clouds and more.

* [Docker](http://www.docker.com/) - an open source project to pack, ship and run any application as a lightweight container

  * [What is Docker?](https://www.docker.com/whatisdocker/)

  * [Docker Hub Registry](https://registry.hub.docker.com/) - Repositories of Docker Images

  * [Try it!](https://www.docker.com/tryit/) - tutorial online

  * [DockerCon | Docker Blog](http://blog.docker.com/category/dockercon-2/)

--

* [[GitHub] docker / docker](https://github.com/docker/docker) - the open-source application container engine

--

* [Docker by Docker | Scoop.it](http://www.scoop.it/t/docker-by-docker)

* [[GitHub] wsargent / docker-cheat-sheet](https://github.com/wsargent/docker-cheat-sheet)

* [[GitHub] veggiemonk / awesome-docker](https://github.com/veggiemonk/awesome-docker) - A curated list of Docker resources and projects


### Informações

* 2013

  * [[SlideShare] Introduction to Docker](http://www.slideshare.net/dotCloud/intro-docker-october-2013) - 2013/10/29

* 2014

  * [[Speaker Deck] Small presentation about what's new in the Docker Platform](https://speakerdeck.com/vieux/whats-new-in-the-latest-docker-release-and-docker-hub-at-braintree) - 2014/08/19

  * [[SlideShare] Docker, Linux Containers (LXC), and security](http://www.slideshare.net/jpetazzo/docker-linux-containers-lxc-and-security) - 2014/08/20

  * [Docker Client disponível para Microsoft Windows | InfoQ Br](http://www.infoq.com/br/news/2014/11/docker-client-windows) - 2014/11/20

  * DockerCon Europe

    * [[SlideShare] Dockercon Europe 2014 - Continuous Delivery leveraging on Docker CaaS](http://fr.slideshare.net/adrienblind/dockercon-europe-2014-continuous-delivery-leveraging-on-docker-caas)

    * [DockerCon Europe keynote: State of the Art in Microservices by Adrian Cockcroft (Battery Ventures) | Docker Blog](https://blog.docker.com/2014/12/dockercon-europe-keynote-state-of-the-art-in-microservices-by-adrian-cockcroft-battery-ventures/)

* 2015

  * [Docker e containers: uma introdução rápida | Info Br - QConBr 2015](http://www.infoq.com/br/presentations/docker-e-containers) - Já ouviu falar do Docker, mas não teve a oportunidade de se aprofundar e vê-lo em ação? Agora é a hora! Nesta palestra será apresentado os conceitos essenciais do Docker, como executar os containers, criar suas próprias imagens, interagir com o “Docker Hub” e mais.


### Aprendizado

* [[SlideShare] Docker](http://www.slideshare.net/anildigital/docker-31242748)

* [[YouTube] Introduction to Docker](https://www.youtube.com/watch?v=Q5POuMHxW-0) - Twitter University (02/10/2013).

* [[YouTube] Why we built Docker](https://www.youtube.com/watch?v=3N3n9FzebAA) - dotScale 2013 - Solomon Hykes (01/08/2013)

* [Docker - docs](https://docs.docker.com/)

* [Docker - training](https://training.docker.com/)

--

* [Try Docker | Code School](https://www.codeschool.com/courses/try-docker)

--

* [Docker Playground](http://play-with-docker.com/)

  * [Play with docker classroom](http://training.play-with-docker.com/)

* [[GitHub] portainer / portainer](https://github.com/portainer/portainer) - Simple management UI for Docker

  * [Putting a UI around Docker with Portainer | Containerizers](https://cntnr.io/putting-a-ui-around-docker-with-portainer-c8ba07874f9d) - 2017/01/09

--

* [Starting with Docker | Sergio Rodriguez – Medium](https://medium.com/@saysduran/starting-with-docker-c2ed6046184b) - 2017/10/30

* [[GitHub] prakhar1989 / docker-curriculum](https://github.com/prakhar1989/docker-curriculum) - (Docker for Beginners) A comprehensive tutorial on getting started with Docker.

* [[Speaker Deck] Docker, Get used to it!](https://speakerdeck.com/julienvey/docker-get-used-to-it)

* [Docker - What is Docker?](https://www.docker.com/whatisdocker)

* [What is Docker?](https://medium.com/devops-programming/7f5fd023158f) - The buzzword that is taking the DevOps world by storm

* [Getting Started with Docker | Servers for Hackers](http://serversforhackers.com/articles/2014/03/20/getting-started-with-docker/)

* [Docker in Practice | Food Fight](http://foodfightshow.org/2013/11/docker-in-practice.html)

* [[SlideShare] Why Docker](http://www.slideshare.net/dotCloud/why-docker)

* [[SpeakerDeck] Introduction to Docker - Ship it with Docker!](https://speakerdeck.com/slok/ship-it-with-docker)

* [[SlideShare] DockerCon EU 2015: Getting Started with Docker](http://www.slideshare.net/Docker/getting-started-with-docker) - 2015/11/23

* [Docker: tudo o que você precisava saber, mas não te contaram | InfoQ Br](http://www.infoq.com/br/presentations/docker-tudo-que-precisava-saber)

* [Docker - Beginner's tutorial | talPor Solutions Blog](https://blog.talpor.com/2015/01/docker-beginners-tutorial/)

* [Getting Started with Docker: Simplifying Devops | Toptal](http://www.toptal.com/devops/getting-started-with-docker-simplifying-devops)

* [Docker's - Beginner Guide | hack.guides()](http://tutorials.pluralsight.com/devops/docker-s-beginner-guide)

* [A Short Guide to a Super Productive Docker Development Environment | Nicholas Rempel](https://nrempel.com/guides/docker-development-environment/)

--

* [[YouTube] Docker em 20 minutos](https://www.youtube.com/watch?v=caGS9EztYlc) - 2016/02/25

* [[YouTube] Docker do básico à orquestração de containers - Wellington Silva | Laravel Brasil](https://www.youtube.com/watch?v=mR2px-mKjd0) - 2015/05/12

--

* [Visualizing Docker Containers and Images | Probably Done Before](http://merrigrove.blogspot.in/2015/10/visualizing-docker-containers-and-images.html)

--

* [Understanding the key differences between LXC and Docker | Flockport](http://www.flockport.com/lxc-vs-docker/)

--

* [As baleias na Nuvem: entenda como funciona o Docker | iMasters](http://imasters.com.br/infra/linux/baleias-na-nuvem-entenda-como-funciona-o-docker/)

--

* [[Gist] wsargent / docker_cheat.md](https://gist.github.com/wsargent/7049221) - Docker cheat sheet

--

* [Learning About Docker | Composite Code](http://compositecode.com/2013/11/20/learning-about-docker/)

* [The Docker Guidebook | KenCochrane.net](http://kencochrane.net/blog/2013/08/the-docker-guidebook/)

* [Valuable Docker Links | nkode.io](http://www.nkode.io/2014/08/24/valuable-docker-links.html)

--

* [Adventures in Dockerland | Open Source Community](http://community.redhat.com/adventures-in-dockerland/)

* [The Revolution will be Containerized | Joshua Barratt](https://rawgithub.com/jbarratt/dockertalk/master/talk/index.html) - The Past, Present and Future of Containers for Applications

  * [[YouTube] The Revolution Will Be Containerized: (Docker)](https://www.youtube.com/watch?v=LNAzzHS1Rho)

* [[SlideShare] Scale Big With Docker — Moboom 2014](http://www.slideshare.net/jpetazzo/scale-big-with-docker-moboom-2014)

* [A Practical Introduction to Docker Containers | Red Hat Developer Blog](https://developerblog.redhat.com/2014/05/15/practical-introduction-to-docker-containers/)

* [Using Docker & Ansible by John Minnihan @Gluecon 2014 | DevOps.com](http://devops.com/blogs/using-docker-ansible/)

* [Criando ambientes de forma simples com Docker e Ansible | InfoQ Br](http://www.infoq.com/br/presentations/criando-ambientes-de-forma-simples-com-docker-e-ansible) - 2015/12/04

* [Docker na vida real | InfoQ Br](http://www.infoq.com/br/presentations/docker-na-vida-real) - 2015/10/14

* [Iniciando com o Docker: dicas práticas para começar a usar agora mesmo | Blog do Elasticpush](http://elasticpush.com/blog/iniciando-com-o-docker-dicas-praticas-para-comecar-a-usar-agora-mesmo/) - 2016/02/04


### Dockerfile

* [Docker - Dockerfile tutorial](https://www.docker.io/learn/dockerfile/)

* [Dockerfiles in a jiffy | The Disco Blog](http://thediscoblog.com/blog/2014/05/05/dockerfiles-in-a-jiffy/)

* Dockerfile Best Practices | Michael Crosby : [1](http://crosbymichael.com/dockerfile-best-practices.html) | [2](http://crosbymichael.com/dockerfile-best-practices-take-2.html)

* [Dockerfile deep dive | Michael Crosby](http://crosbymichael.com/dockerfile-deep-dive.html)


### Dicas

* [Comparing Application Deployment: 2005 vs. 2015 | James Ward](http://www.jamesward.com/2015/06/08/comparing-application-deployment-2005-vs-2015) - 2015/06/08

--

* [[YouTube] 15 Docker Tips in 15 Minutes](https://www.youtube.com/watch?v=BJT9bA64Hcc) - Twitter University (19/12/2013).

* [Some Docker Tips and Tricks | Wouter Danes](http://www.wouterdanes.net/2014/04/16/some-docker-tips-and-tricks.html)

* [Ten Docker Tips and Tricks That Will Make You Sing A Whale Song of Joy | Docker Blog](http://blog.docker.com/2014/07/10-docker-tips-and-tricks-that-will-make-you-sing-a-whale-song-of-joy/)

--

* [Docker : The good parts | Shrikrishna Holla](http://blog.shrikrishnaholla.in/post/2014/01/12/docker-the-good-parts/)

* [Docker: what I learned from working out what's in it for me | Brownsofa](http://brownsofa.org/blog/2014/03/14/docker-what-i-learned-from-whats-in-it-for-me/)

* [Advanced Docker Volumes | Michael Crosby](http://crosbymichael.com/advanced-docker-volumes.html)

--

* [Docker Desktop: Your Desktop over ssh running inside of a Docker container | Docker Blog](https://blog.docker.com/2013/07/docker-desktop-your-desktop-over-ssh-running-inside-of-a-docker-container/) - 2013/07/08

* [Docker Containers on the Desktop | Jessie Frazelle's Blog](https://blog.jessfraz.com/post/docker-containers-on-the-desktop/) - 2015/02/21

  * [[GitHub] jfrazelle / dockerfiles](https://github.com/jfrazelle/dockerfiles) - Various Dockerfiles

--

* [My Other Virtual Machine is a Container | Innovation Insights](http://insights.wired.com/profiles/blogs/my-other-virtual-machine-is-a-container)

* [Building a Multi-Purpose Docker Image | Docker News — Medium](https://medium.com/docker-news/7762378ebc2e)

--

* [How to Train Your Docker Cloud | InfoQ En](http://www.infoq.com/presentations/docker-cloud-clocker) - (2015/05/16) Andrew Kennedy talks about the reasons for creating a Docker cloud and how they realized that to do this properly they needed first class networking to handle composite distributed applications such as Riak. It was a short step from this to using Brooklyn itself to bootstrap a Docker cloud effectively colonizing the infrastructure. And so Clocker was born.

  * [[GitHub] brooklyncentral / clocker](https://github.com/brooklyncentral/clocker) - creates and manages a Docker cloud infrastructure | [site](https://brooklyncentral.github.io/clocker/)

--

* [Backup Docker to Amazon S3 | stefanXO](http://blog.stefanxo.com/2014/02/backup-docker-to-amazon-s3/)

* [Difference between save and export in Docker | Thomas Uhrig](http://tuhrig.de/difference-between-save-and-export-in-docker/)

* [Layering of Docker images | Thomas Uhrig](http://tuhrig.de/layering-of-docker-images/)

--

* [Docking your services with Docker | Speaker Deck](https://speakerdeck.com/hagzag/docking-your-services-with-docker) - by Haggai Philip Zagury. A presentation showing how docker & LXC will (future tense) change our lives.

--

* [Docker all the things at Atlassian: automation and wiring | Atlassian Blogs](https://blogs.atlassian.com/2013/11/docker-all-the-things-at-atlassian-automation-and-wiring/)

* [Day 21: Docker - The Missing Tutorial | OpenShift by Red Hat](https://www.openshift.com/blogs/day-21-docker-the-missing-tutorial)

* [Comparing Containers and Generating Dockerfiles with GuardRail | ScriptRock](https://www.scriptrock.com/blog/comparing-containers-generating-dockerfiles-guardrail/)

--

* [Como ter sucesso executando o Docker em produção | InfoQ Br](http://www.infoq.com/br/news/2015/12/docker-producao) - 2015/12/09

* [Deploy ágil com Docker | iMasters](http://imasters.com.br/desenvolvimento/deploy-agil-com-docker/) - 2016/03/07

--

* [Introducing Trusted Builds | Docker Blog](http://blog.docker.io/2013/11/introducing-trusted-builds/)

* [Docker: Using Linux Containers to Support Portable Application Deployment | InfoQ](http://www.infoq.com/articles/docker-containers)

* [Docker: Git for deployment](http://blog.scoutapp.com/articles/2013/08/28/docker-git-for-deployment)

--

* [Docker Explained: How To Containerize and Use Nginx as a Proxy | DigitalOcean](https://www.digitalocean.com/community/articles/docker-explained-how-to-containerize-and-use-nginx-as-a-proxy)

* [Hosting static sites with Docker and Nginx | Kyle Mathews](http://bricolage.io/hosting-static-sites-with-docker-and-nginx/)

--

* [On-demand activation of Docker containers with systemd | Atlassian Developers](https://developer.atlassian.com/blog/2015/03/docker-systemd-socket-activation/)

--

* [Migrating your Gitlab infrastructure into Docker | Jscrambler Blog](https://blog.jscrambler.com/migrating-your-gitlab-infrastructure-into-docker/)

--

* [Reducing Deploy Risk With Docker’s New Health Check Instruction | New Relic blog](https://blog.newrelic.com/2016/08/24/docker-health-check-instruction/) - 2016/08/24

--

* [Sonatype Nexus](http://www.sonatype.org/nexus/)

  * [[GitHub] sonatype / docker-nexus](https://github.com/sonatype/docker-nexus) - Docker image for Sonatype Nexus

  * [[GitHub] sonatype / docker-nexus3](https://github.com/sonatype/docker-nexus3) - Dockerized version of Nexus Repo Manager 3

* [Integration testing with Maven and Docker | Java Code Geeks](http://www.javacodegeeks.com/2014/03/integration-testing-with-maven-and-docker.html)

* [[GitHub] spotify / docker-maven-plugin](https://github.com/spotify/docker-maven-plugin) - A maven plugin for docker

* [Dockerizing Mule ESB Enterprise | codecentric Blog](https://blog.codecentric.de/en/2014/10/dockerizing-mule-esb-enterprise/)

* [Running a Selenium Grid using Docker and Compose | Nightlight](http://www.conductor.com/nightlight/running-selenium-grid-using-docker-compose/)

* [Arun Gupta: Receitas para publicar aplicações Java EE com Docker e Kubernetes | InfoQ Br](http://www.infoq.com/br/news/2015/05/javaee-docker-kubernetes)

  * [[SlideShare] Package your Java EE Application using Docker and Kubernetes](http://www.slideshare.net/arungupta1/package-your-java-ee-application-using-docker-and-kubernetes)

* [[GitHub] coreos / flannel](https://github.com/coreos/flannel) - is a network fabric for containers, designed for Kubernetes


### Private Registry

* [[YouTube] Docker: How to Use Your Own Private Registry](https://www.youtube.com/watch?v=CAewZCBT4PI) - Twitter University (12/11/2013)

* [Working with a Docker Repository | Docker Docs](http://docs.docker.io/use/workingwithrepository/)

* [How to use your own Registry | Docker Blog](http://blog.docker.io/2013/07/how-to-use-your-own-registry/)

* [Docker Registry or How to Run your own Private Docker Image Repository | codecentric Blogcodecentric Blog](https://blog.codecentric.de/en/2014/02/docker-registry-run-private-docker-image-repository/)

* [Deploying your own Private Docker Registry | ActiveState](http://www.activestate.com/blog/2014/01/deploying-your-own-private-docker-registry)


### Ambiente de desenvolvimento

* [Useful Docker Bash functions and aliases | Kartar.Net](http://www.kartar.net/2014/03/some-useful-docker-bash-functions-and-aliases/)

* [Why and How to Use Docker for Development | Iron.io Blog — Medium](https://medium.com/iron-io-blog/why-and-how-to-use-docker-for-development-a156c1de3b24)

* [Docker for Mac and Windows Beta: the simplest way to use Docker on your laptop | Docker Blog](https://blog.docker.com/2016/03/docker-for-mac-windows-beta/) - 2016/03/24

--

* A Docker Dev Environment in 24 Hours! | salesforceIQ Blog - [Part 1](https://engineering.salesforceiq.com/2013/10/31/a-docker-dev-environment-in-24-hours-part-1-of-2.html) | [Part 2](https://engineering.salesforceiq.com/2013/11/05/a-docker-dev-environment-in-24-hours-part-2-of-2.html)

  * [[GitHub] relateiq / docker_public](https://github.com/relateiq/docker_public) - Instant RelateIQ Development Environment

  * [[YouTube] Chef Versus Docker at RelateIQ](https://www.youtube.com/watch?v=lS7xVHIl9zU) - Twitter University (26/11/2013)

  * [DockerCon video: Docker at RelateIQ | Docker Blog](http://blog.docker.com/2014/07/dockercon-video-docker-at-relateiq/)

  * [[SlideShare] Running Docker in Production - Dockercon EU 2015](http://www.slideshare.net/relateiq/dockercon-eu-2015) - 2015/11/21

* [Building a Development Environment with Docker | Terse Systems](http://tersesystems.com/2013/11/20/building-a-development-environment-with-docker/)

* [Docker for Isolated and Reproducible Development Environments | Ana Nelson's Blog](http://blog.ananelson.com/2014/03/docker-isolated-and-reproducible/)

* [[SlideShare] Docker and Containers for Development and Deployment — SCALE12X](http://www.slideshare.net/jpetazzo/docker-and-containers-for-development-and-deployment-scale12x) - Docker is an Open Source engine to build, run, and manage containers. We'll explain what are Linux Containers, what powers them (under the hood), and what extra value Docker brings to the table. Then we'll see what the typical Docker workflow looks like from a developer point of view. We'll also give an Ops perspective, including deployment options.

--

* [Efficient development workflow using Git submodules and Docker Compose | AirPair](https://www.airpair.com/docker/posts/efficiant-development-workfow-using-git-submodules-and-docker-compose)

* [A sample Docker workflow with Nginx, Node.js and Redis | Anand Mani Sankar](http://anandmanisankar.com/posts/docker-container-nginx-node-redis-example/)

* [Waiting for dependencies in Docker Compose | OneGeek](http://www.onegeek.com.au/articles/waiting-for-dependencies-in-docker-compose) - Using Docker Compose to automate your test process is awesome, but waiting for dependent services can result in flakey tests. In this post, I demonstrate the use of Dockerize to simplify this process.

--

* [From Vagrant To Docker | ScaleIt!](http://dahlgren.so/software/2014/05/11/From-Vagrant-To-Docker/) - Speeding up the development cycle

* [From Vagrant To Docker Continued | ScaleIt!](http://dahlgren.so/software/2014/05/17/From-Vagrant-To-Docker-Continued/) - A slightly more complex example

--

* [Dockerizing a PHP Application | Semaphore](https://semaphoreci.com/community/tutorials/dockerizing-a-php-application)

* [Creating a Docker Container to run PHP, NGINX and Hip Hop VM (HHVM) | SEED Official Blog](http://blog.seedtech.io/post/91801062414/creating-a-docker-container-to-run-php-nginx-and-hip)

* [Criando um Lamp com seu Docker | iMasters](http://imasters.com.br/desenvolvimento/criando-um-lamp-com-seu-docker/) - 2016/03/09

* [[YouTube] Configurando ambiente PHP no Windows com Docker](https://www.youtube.com/watch?v=xVHa4eLmork) - 2016/02/26

* [How to scale Laravel horizontally with Docker | Medium by @andrewmclagan](https://medium.com/@andrewmclagan/you-thought-laravel-homestead-was-easy-say-hello-to-docker-2c0639a0501)

--

* [Getting Started with Java Development on Docker | The Giant Swarm Blog](http://blog.giantswarm.io/getting-started-with-java-development-on-docker/) - (2015/07/08) Introduction to Java Development on Docker using an example with Spark and Maven

* [Developing with WildFly, JBoss Developer Studio and Docker | Marek Goldmann](http://goldmann.pl/blog/2013/11/20/developing-with-wildfly-jboss-developer-studio-and-docker/)

* [Deploy Java Apps With Docker = Awesome | Atlassian Blogs](https://blogs.atlassian.com/2013/06/deploy-java-apps-with-docker-awesome/)

* [Screencast of Docker Tooling for Eclipse | JBoss Tools](http://tools.jboss.org/blog/docker_tooling_eclipse_mars.html)

--

* [A Docker primer – from zero to a running Django app](https://ochronus.com/docker-primer-django/)

* Rapid Prototyping a Python web application with Vagrant and Docker | Continuous Delivery Services

  * [Part 1, Development](http://continuousdelivery.uglyduckling.nl/continuous-delivery/rapid-prototyping-a-python-web-application-with-vagrant-and-docker-part-1-development/)

--

* [Easily Deploy Redis Backed Web Apps With Docker | Tuts+ Code Tutorial](http://code.tutsplus.com/tutorials/easily-deploy-redis-backed-web-apps-with-docker--cms-20405)

--

* [How to create a Docker + Node.js + MongoDB + Varnish environment | Luis Elizondo](http://luiselizondo.net/blogs/luis-elizondo/how-create-docker-nodejs-mongodb-varnish-environment)

* [Getting Started with Docker for the Node.js | CouchDB Programmer - Medium](https://medium.com/code-adventures/35c45ce2a814)

* [Node.js: Utilizando o docker para construir e entregar as suas aplicações | Kaique Silva](http://sigmundxox.svbtle.com/docker-nodejs-containers)

* [Develop a NodeJS App With Docker | sqldump](http://blog.abhinav.ca/blog/2014/06/17/develop-a-nodejs-app-with-docker/)

* [Docker + NodeJS Dev Environment: Take 2 - Container Linking | sqldump](http://blog.abhinav.ca/blog/2014/07/25/docker-nodejs-dev-environment-take-2/)

* Link entre containers | iMasters

  * [parte 01](http://imasters.com.br/tecnologia/redes-e-servidores/link-entre-containers-parte-01/) - 2015/11/23

  * [parte 02](http://imasters.com.br/tecnologia/redes-e-servidores/link-entre-containers-parte-02/) - 2015/12/02

--

* [Docker and MongoDB Sharded Cluster | Sebastian Voss](http://sebastianvoss.com/docker-mongodb-sharded-cluster.html)

* [Vagrant 1.6 Feature Preview: Docker-Based Development Environments | Vagrant](http://www.vagrantup.com/blog/feature-preview-vagrant-1-6-docker-dev-environments.html)

--

* [[GitHub] EwanValentine / SymfonyAngularDocker](https://github.com/EwanValentine/SymfonyAngularDocker) - Symfony angular docker example

  * [Running Angularjs and Symfony2 on Docker | Ewan Valentine](http://ewanvalentine.io/running-angularjs-and-symfony-projects-on-docker/)

--

* [[GitHub] c0b / chrome-in-docker](https://github.com/c0b/chrome-in-docker) - run Google Chrome in container (as a perfect headless browser)


#### Mac OS X

* [Installing Docker on Mac OS X | Docker](http://docs.docker.io/installation/mac/)

* [[GitHub] nlf / dlite](https://github.com/nlf/dlite) - The simplest way to use Docker on OS X

--

* [A productive development environment with Docker on OS X | @brikis98](http://www.ybrikman.com/writing/2015/05/19/docker-osx-dev/) - (2015/05/19) A productive development environment with Docker on OS X

* [Lightweight Docker experience on OSX | zaiste.net](http://zaiste.net/2014/02/lightweight_docker_experience_on_osx/)

* [Upgrade docker and boot2docker on OSX | Java Bien!](http://blog.javabien.net/2014/03/17/upgrade-docker-and-boot2docker-on-osx/)

* [Boot 2 Docker: How to set up Postgres, Elasticsearch and Redis on Mac OS X | maori.geek](http://www.maori.geek.nz/post/boot_2_docker_how_to_set_up_postgres_elasticsearch_and_redis_on_mac_os_x)

* [Using Docker transparently on OSX | Shane Sveller](http://shanesveller.com/blog/2014/02/04/using-docker-transparently-on-osx/)

* [Cooking with Docker and CoreOS on OS X | Siliconfidential](http://www.siliconfidential.com/articles/docker-coreos-osx/)

* [Unsuck your vagrant: Developing in one VM with Vagrant and Docker | Tony HB](http://tonyhb.com/unsuck-your-vagrant-developing-in-one-vm-with-vagrant-and-docker)

* [Run Docker in VirtualBox with Vagrant on Mac OS X | Chris LaRose, Software Developer](http://cjlarose.com/2014/03/08/run-docker-with-vagrant.html)

* [A OSX + Vagrant + Docker + Ruby on Rails Setup | Medium](https://medium.com/docker-news/117daf4ef0a5)


#### Windows

* [Installing Docker on Windows | Docker](http://docs.docker.io/installation/windows/)

--

* [[SlideShare] Run Docker On Windows Using Vagrant](http://www.slideshare.net/julienbarbier42/run-docker-on-windows-using-vagrant)

* [Docker on Windows with VMware Workstation and Vagrant | vByron.com](http://vbyron.com/blog/docker-windows-vmware-workstation-vagrant/)

* [The tale of Docker on Windows (or: I wish I had a Mac)](http://scalableapps.com/the-tale-of-docker-on-windows-or-i-wish-i-had-a-mac/)

* [Docker Machine on Windows - How To Setup You Hosts | Enterprise Software Development with Java](http://blog.eisele.net/2015/05/docker-maschine-on-windows-host-setup-howto.html)

* [Running Docker Containers On Windows Server 2016 (Quick Start Guide) | Ashley Poole](http://ashleypoole.co.uk/2016/docker-containers-windows-server-2016-guide/)

--

* [Running .NET apps on Docker | Randoom](http://friism.com/running-net-apps-on-docker)


### Continuous Integration

* [Notes about fiddling with docker and continuous deployment ideas | Roxee Tech](http://tech.roxee.tv/2013/10/01/notes-about-fiddling-with-docker-and-continuous-deployment-ideas/)

* [Using Docker To Run Ruby Rspec CI In Jenkins | ActiveState](http://www.activestate.com/blog/2014/01/using-docker-run-ruby-rspec-ci-jenkins)

* Continuous Integration and Deployment with Jenkins and Docker [Part I](http://inpursuit.ghost.io/continuous-integration-with-jenkins-and-docker/) | [Part II](http://inpursuit.ghost.io/continuous-integration-and-deployment-with-jenkins-and-docker-part-ii/)

* [Using Docker as a Jenkins Cloud Provider | Nuxeo Blogs](http://www.nuxeo.com/blog/development/2014/02/docker-jenkins-cloud-provider/)

* [Continuous Integration Using Docker, Maven and Jenkins | Wouter Danes](http://www.wouterdanes.net/2014/04/11/continuous-integration-using-docker-maven-and-jenkins.html)

  * [[GitHub] wouterd / docker-maven-plugin](https://github.com/wouterd/docker-maven-plugin) - A maven plugin to manage docker containers and images for integration tests

* [From zero to fully working CI server in less than 10 minutes with Drone & Docker | Jean-Philippe Boily](http://jipiboily.com/2014/from-zero-to-fully-working-ci-server-in-less-than-10-minutes-with-drone-docker)

* [Move fast and don’t break things! Testing with Jenkins, Ansible and Docker | Rackspace Developer Center](http://developer.rackspace.com/blog/move-fast-and-dont-break-things-testing-with-jenkins-ansible-and-docker.html)

* [Creating containerized build environments with the Jenkins Pipeline plugin and Docker. Well, almost. |  Damnhandy](http://damnhandy.com/2016/03/06/creating-containerized-build-environments-with-the-jenkins-pipeline-plugin-and-docker-well-almost/) - 2016/03/06

* [Automated End-To-End Testing with Protractor, Docker and Jenkins | @Smaato](http://blog.smaato.com/automated-end-to-end-testing-with-protractor-docker-jenkins) - 2016/03/09

--

* [[GitHub] SeleniumHQ / docker-selenium](https://github.com/SeleniumHQ/docker-selenium) - Docker images for Selenium Standalone Server


### Raspberry Pi

* [Docker on Raspberry Pi | Resin.io](http://resin.io/docker-on-raspberry-pi/)

* [Why port Docker to the Raspberry Pi? | Resin.io](http://resin.io/why-port-docker-to-the-raspberry-pi/)

* [How to use Docker Compose to run complex multi container apps on your Raspberry Pi | Docker Pirates ARMed with explosive stuff](http://blog.hypriot.com/post/docker-compose-nodejs-haproxy/)

* [OpenVpn rodando com Docker no Raspberry Pi | iMasters](http://imasters.com.br/open-hardware-2/openvpn-rodando-com-docker-no-raspberry-pi/) - 2017/01/05


### Caso de Uso

* [Use Cases | Docker Inc](http://www.docker.com/resources/usecases/)

* [What people have already built using Docker | Docker](https://www.docker.io/community/#What-people-have-already-built-using-Docker)

* [Docker in education: From VMs to Containers | Docker Blog](http://blog.docker.io/2014/04/docker-in-education-interview/)

* [How Docker Helped Us Achieve the (Near) Impossible | Iron.io Blog](http://blog.iron.io/2014/04/how-docker-helped-us-achieve-near.html)

* [[YouTube] Docker at Spotify](https://www.youtube.com/watch?v=pts6F00GFuU) - Twitter University (11/12/2013)

* [[YouTube] Docker ♥ Mesos](https://www.youtube.com/watch?v=2MmnggSmTJo) - Twitter University (25/11/2013). OpenTable's Aish Fenton explains why Docker loves [Mesos](https://mesos.apache.org/), and how OpenTable uses the powerful combination.

* [[SlideShare] Running Netflix OSS on Docker with Nirmata](http://www.slideshare.net/patelrit/nirmata-docker)

* [Baidu using Docker for its PaaS | Docker Blog](http://blog.docker.io/2013/12/baidu-using-docker-for-its-paas/)

* [How We Use Docker To Continuously Deliver Microservices - Part 1 | Contino](http://contino.co.uk/use-docker-continuously-deliver-microservices-part-1/)

* [Containers for test environments using Docker | SpeedLedger Tech blog](http://engineering.speedledger.com/?p=73)

* [The Realities of Docker in Production | Heavybit Blog](http://blog.heavybit.com/blog/2015/3/23/dockermeetup) - Docker seems like a fundamentally better abstraction for packaging and deploying applications in a persistent way across multiple environments. Amongst individual developers and sys admins it's praised, but at a recent Docker in Production Meetup at Heavybit -- engineers from ClusterHQ, Iron.io, RelateIQ and Docker gathered to talk about what it looks like in production.

* [Lessons learned running Docker in production | Treehouse Engineering – Medium](https://medium.com/treehouse-engineering/lessons-learned-running-docker-in-production-5dce99ece770) - 2016/04/05

--

* [[GitHub] remie / YouTransfer](https://github.com/remie/YouTransfer) - The simple but elegant self-hosted file transfer & sharing solution


### Soluções

* [[GitHub] boot2docker / boot2docker](https://github.com/boot2docker/boot2docker) - Lightweight Linux for Docker

  * [[Vagrant Cloud] yungsang / boot2docker](https://vagrantcloud.com/yungsang/boot2docker)

--

* [Kitematic](https://kitematic.com/) - The easiest way to use Docker on Mac

  * [[GitHub] kitematic / kitematic](https://github.com/kitematic/kitematic) - Mac app for managing Docker containers

--

* [RancherOS | Rancher Labs](http://rancher.com/rancher-os/) - A minimalist distribution of Linux designed from the ground up to run Docker containers

  * [[GitHub] rancherio / rancher](https://github.com/rancherio/rancher) - A Platform for Operating Docker in Production

  * [Conheça o Rancher, um painel para Docker | iMasters](http://imasters.com.br/desenvolvimento/conheca-o-rancher-um-painel-para-docker/) - 2016/01/20

--

* [[GitHub] phusion / baseimage-docker](https://github.com/phusion/baseimage-docker) - A minimal Ubuntu base image modified for Docker-friendliness

* [Using docker with CoreOS | CoreOS](https://coreos.com/using-coreos/docker/)

--

* [Project Atomic](http://www.projectatomic.io/) - Sponsored by Red Hat, Inc. Deploy and Manage Your Docker Containers.

* [[GitHub] progrium / dokku](https://github.com/progrium/dokku) - Docker powered mini-Heroku in around 100 lines of Bash

  * [How to Use the DigitalOcean Dokku Application | DigitalOcean](https://www.digitalocean.com/community/articles/how-to-use-the-digitalocean-dokku-application)

--

* [[GitHub] drone / drone](https://github.com/drone/drone) - is a Continuous Integration platform built on Docker

* [[GitHub] Strider-CD / strider](https://github.com/Strider-CD/strider) - is an Open Source Continuous Deployment / Continuous Integration platform. It is written in Node.JS / JavaScript and uses MongoDB as a backing store. It is published under the BSD license.

--

* [Create, manage and run clusters of Docker containers using Node.js | decking.io](http://decking.io/)

* [Kickstart a Couchbase cluster with Docker | sqldump](http://blog.abhinav.ca/blog/2014/07/31/kickstart-a-couchbase-cluster-with-docker/)

--

* [[GitHub] rogaha / docker-desktop](https://github.com/rogaha/docker-desktop) - Docker Desktop enables you to create virtual desktops that can be accessed remotely. It comes with Firefox and Libreoffice already installed!

--

* [[GitHub] shipyard / shipyard](https://github.com/shipyard/shipyard) - Docker Management

* [[GitHub] crosbymichael / dockerui](https://github.com/crosbymichael/dockerui) - A web interface for docker

--

* [Gandalf.io](https://gandalf.io/) -  Affordable Docker Private Registries

--

* [Flocker](https://clusterhq.com/flocker/) -  is an open-source container data volume manager for your Dockerized applications

  * [Persistindo dados – Flocker | iMasters](http://imasters.com.br/desenvolvimento/devops/persistindo-dados-flocker/) - 2016/05/30

--

* [[GitHub] cusspvz / autotune.docker](https://github.com/cusspvz/autotune.docker) - autotune is a MUST HAVE (2MB) system tuner for ALL your docker hosts


### Node.js

* [[Vimeo] Node.JS and Docker with a side of Continuous Deployment](http://vimeo.com/85864661) - Presented by Niall O'Higgins at JSLA (js.la) on Thursday January 30th 2014. Docker is an incredible new tool to manage the deployment and lifecycle of Node.JS network services. This talk will cover using them together for much Continuous Deployment win.

--

* [[GitHub] adamalex / docker-urlarchiver](https://github.com/adamalex/docker-urlarchiver) - Use Docker to package a Node.js script with all its dependencies, including Node

* [[GitHub] apocas / dockerode](https://github.com/apocas/dockerode) - Not just another Docker.io Remote API node.js module

--

* [Uma breve introdução ao Docker com Node.js | BrasilJS](https://braziljs.org/blog/uma-breve-introducao-ao-docker-com-nodejs/) - 2016/09/21

* [How to Dockerize your Node application | Luca Mezzalira](https://lucamezzalira.com/2016/04/03/how-to-dockerize-your-node-application/) - 2016/04/03

* [Getting Started with Docker for the Node.js Developer | AirPair](https://www.airpair.com/node.js/posts/getting-started-with-docker-for-the-nodejs-dev)

* [Node with Docker - continuous integration and delivery | Michael Herman](http://mherman.org/blog/2015/03/06/node-with-docker-continuous-integration-and-delivery/)

* [Minimal Docker Containers for Node.js | @RisingStack](https://blog.risingstack.com/minimal-docker-containers-for-node-js/) - 2016/02/10

* [How to Dockerize your Node application | Luca Mezzalira](http://lucamezzalira.com/2016/04/03/how-to-dockerize-your-node-application/) - 2016/04/03

### Oracle

* [[GitHut] oracle / docker-images](https://github.com/oracle/docker-images) - Official source for Docker configurations, images, and examples of Dockerfiles for Oracle products


### Red Hat

* [Red Hat Launches Latest Version of Red Hat Enterprise Linux 6](http://www.redhat.com/about/news/press-archive/2013/11/red-hat-launches-latest-version-of-red-hat-enterprise-linux-6) - RedHat just launched RHEL v6.5 featuring Docker, support for up to 4TB RAM and more! (see: Evolving Ease-of-Use, Storage, and More)

* [Red Hat and Docker](http://www.redhat.com/about/news/press-archive/2013/9/red-hat-and-dotcloud-collaborate-on-docker-to-bring-next-generation-linux-container-enhancements-to-openshift) - Red Hat and dotCloud Collaborate on Docker to Bring Next Generation Linux Container Enhancements to OpenShift Platform-as-a-Service


### Amazon Cloud

* [Docker Now Available on VisualOps | Medium](https://medium.com/@visualops/docker-now-available-on-visualops-d52c40832298) | [VisualOps](http://www.visualops.io/)

* [Amazon Linux AMI 2014.03 | Amazon Web Services Blog](http://aws.typepad.com/aws/2014/03/amazon-linux-ami-201403-is-now-available.html) - which includes Linux kernel 3.10.34, Docker, Ruby 2.0 & other features

* [DockerCon Video: Running Docker on AWS | Docker Blog](http://blog.docker.com/2014/06/dockercon-video-running-docker-on-aws/)


### Google Cloud

* [[Docker Index] google/cloud-sdk](https://index.docker.io/u/google/cloud-sdk/) - Google Cloud SDK bundle with all components and dependencies

* [[YouTube] Google I/O 2014 - Containerizing the Cloud with Docker on Google Cloud Platform](https://www.youtube.com/watch?v=tsk0pWf4ipw)


### Windows Azure

* [Dockercon video: Easy Docker on Microsoft Azure | Docker Blog](http://blog.docker.com/2014/07/dockercon-video-easy-docker-on-microsoft-azure/)

* [Docker on Azure](http://1drv.ms/1kfrLev)

* [Publishing an ASP.NET 5 app to Docker on Linux with Visual Studio | Scott Hanselman](http://www.hanselman.com/blog/PublishingAnASPNET5AppToDockerOnLinuxWithVisualStudio.aspx)
