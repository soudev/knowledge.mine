# Virtual Machine / Máquina Virtual


<!-- toc -->
* [Docker](#docker)
  * [Ambiente de desenvolvimento](#ambiente-de-desenvolvimento)
  * [Soluções](#soluções)
  * [Caso de Uso](#caso-de-uso)
  * [Node.js](#nodejs)
  * [Red Hat](#red-hat)
  * [Amazon AMI](#amazon-ami)
  * [Google Cloud](#google-cloud)

<!-- toc stop -->


## Docker

> Docker is an open-source project to easily create lightweight, portable, self-sufficient containers from any application. The same container that a developer builds and tests on a laptop can run at scale, in production, on VMs, bare metal, OpenStack clusters, public clouds and more. 

* [docker.io](http://www.docker.io/) - an open source project to pack, ship and run any application as a lightweight container

* [Docker Image Index](https://index.docker.io/)

* [Docker by Docker | Scoop.it](http://www.scoop.it/t/docker-by-docker)

--

* [[YouTube] Introduction to Docker](https://www.youtube.com/watch?v=Q5POuMHxW-0) - Twitter University (02/10/2013).

* [[SlideShare] Docker](http://www.slideshare.net/anildigital/docker-31242748)

* [[Speaker Deck] Docker, Get used to it !](https://speakerdeck.com/julienvey/docker-get-used-to-it)

* [Docker - Getting Started](https://www.docker.io/gettingstarted/)

* [Getting Started with Docker | Servers for Hackers](http://serversforhackers.com/articles/2014/03/20/getting-started-with-docker/)

* [Docker in Practice | Food Fight](http://foodfightshow.org/2013/11/docker-in-practice.html)

--

* [Introducing Trusted Builds | Docker Blog](http://blog.docker.io/2013/11/introducing-trusted-builds/)

* [[SlideShare] Why Docker](http://www.slideshare.net/dotCloud/why-docker)

--

* [Docker - Dockerfile tutorial](https://www.docker.io/learn/dockerfile/)

* [Dockerfiles in a jiffy | The Disco Blog](http://thediscoblog.com/blog/2014/05/05/dockerfiles-in-a-jiffy/)

* Dockerfile Best Practices | Michael Crosby : [1](http://crosbymichael.com/dockerfile-best-practices.html) | [2](http://crosbymichael.com/dockerfile-best-practices-take-2.html)

* [Dockerfile deep dive | Michael Crosby](http://crosbymichael.com/dockerfile-deep-dive.html)

* [Advanced Docker Volumes | Michael Crosby](http://crosbymichael.com/advanced-docker-volumes.html)

--

* [Docker: Using Linux Containers to Support Portable Application Deployment | InfoQ](http://www.infoq.com/articles/docker-containers)

* [What is Docker?](https://medium.com/devops-programming/7f5fd023158f) - The buzzword that is taking the DevOps world by storm

--

* [Learning About Docker | Composite Code](http://compositecode.com/2013/11/20/learning-about-docker/)

* [[Gist] wsargent / docker_cheat.md](https://gist.github.com/wsargent/7049221) - Docker cheat sheet

* [Adventures in Dockerland | Open Source Community](http://community.redhat.com/adventures-in-dockerland/)

* [The Revolution will be Containerized | Joshua Barratt](https://rawgithub.com/jbarratt/dockertalk/master/talk/index.html) - The Past, Present and Future of Containers for Applications

* [[SlideShare] Scale Big With Docker — Moboom 2014](http://www.slideshare.net/jpetazzo/scale-big-with-docker-moboom-2014)

--

* [Docker : The good parts | Shrikrishna Holla](http://blog.shrikrishnaholla.in/post/2014/01/12/docker-the-good-parts/)

* [Docker: what I learned from working out what's in it for me | Brownsofa](http://brownsofa.org/blog/2014/03/14/docker-what-i-learned-from-whats-in-it-for-me/)

--

* [My Other Virtual Machine is a Container | Innovation Insights](http://insights.wired.com/profiles/blogs/my-other-virtual-machine-is-a-container)

* [Building a Multi-Purpose Docker Image | Docker News — Medium](https://medium.com/docker-news/7762378ebc2e)

--

* [Docker Explained: How To Containerize and Use Nginx as a Proxy | DigitalOcean](https://www.digitalocean.com/community/articles/docker-explained-how-to-containerize-and-use-nginx-as-a-proxy)

* [Hosting static sites with Docker and Nginx | Kyle Mathews](http://bricolage.io/hosting-static-sites-with-docker-and-nginx/)

--

* [Notes about fiddling with docker and continuous deployment ideas | Roxee Tech](http://tech.roxee.tv/2013/10/01/notes-about-fiddling-with-docker-and-continuous-deployment-ideas/)

* [Using Docker To Run Ruby Rspec CI In Jenkins | ActiveState](http://www.activestate.com/blog/2014/01/using-docker-run-ruby-rspec-ci-jenkins)

* Continuous Integration and Deployment with Jenkins and Docker [Part I](http://inpursuit.ghost.io/continuous-integration-with-jenkins-and-docker/) | [Part II](http://inpursuit.ghost.io/continuous-integration-and-deployment-with-jenkins-and-docker-part-ii/)

* [Using Docker as a Jenkins Cloud Provider | Nuxeo Blogs](http://www.nuxeo.com/blog/development/2014/02/docker-jenkins-cloud-provider/)

* [Continuous Integration Using Docker, Maven and Jenkins | Wouter Danes](http://www.wouterdanes.net/2014/04/11/continuous-integration-using-docker-maven-and-jenkins.html)

* [From zero to fully working CI server in less than 10 minutes with Drone & Docker | Jean-Philippe Boily](http://jipiboily.com/2014/from-zero-to-fully-working-ci-server-in-less-than-10-minutes-with-drone-docker)

--

* [Integration testing with Maven and Docker | Java Code Geeks](http://www.javacodegeeks.com/2014/03/integration-testing-with-maven-and-docker.html)

--

* [Docking your services with Docker | Speaker Deck](https://speakerdeck.com/hagzag/docking-your-services-with-docker) - by Haggai Philip Zagury. A presentation showing how docker & LXC will (future tense) change our lives.

--

* [Docker all the things at Atlassian: automation and wiring | Atlassian Blogs](https://blogs.atlassian.com/2013/11/docker-all-the-things-at-atlassian-automation-and-wiring/)

* [Day 21: Docker - The Missing Tutorial | OpenShift by Red Hat](https://www.openshift.com/blogs/day-21-docker-the-missing-tutorial)

* [Comparing Containers and Generating Dockerfiles with GuardRail | ScriptRock](https://www.scriptrock.com/blog/comparing-containers-generating-dockerfiles-guardrail/)

--

* [Docker on Raspberry Pi | Resin.io](http://resin.io/docker-on-raspberry-pi/)

* [Why port Docker to the Raspberry Pi? | Resin.io](http://resin.io/why-port-docker-to-the-raspberry-pi/)

--

* [[SlideShare] Running Netflix OSS on Docker with Nirmata](http://www.slideshare.net/patelrit/nirmata-docker)

* [Baidu using Docker for its PaaS | Docker Blog](http://blog.docker.io/2013/12/baidu-using-docker-for-its-paas/)

--

* [Backup Docker to Amazon S3 | stefanXO](http://blog.stefanxo.com/2014/02/backup-docker-to-amazon-s3/)


### Ambiente de desenvolvimento

* [Docker for Isolated and Reproducible Development Environments | Ana Nelson's Blog](http://blog.ananelson.com/2014/03/docker-isolated-and-reproducible/)

* [Useful Docker Bash functions and aliases | Kartar.Net](http://www.kartar.net/2014/03/some-useful-docker-bash-functions-and-aliases/)

* [Building a Development Environment with Docker | Terse Systems](http://tersesystems.com/2013/11/20/building-a-development-environment-with-docker/)

* [[SlideShare] Docker and Containers for Development and Deployment — SCALE12X](http://www.slideshare.net/jpetazzo/docker-and-containers-for-development-and-deployment-scale12x) - Docker is an Open Source engine to build, run, and manage containers. We'll explain what are Linux Containers, what powers them (under the hood), and what extra value Docker brings to the table. Then we'll see what the typical Docker workflow looks like from a developer point of view. We'll also give an Ops perspective, including deployment options. 

* [Developing with WildFly, JBoss Developer Studio and Docker | Marek Goldmann](http://goldmann.pl/blog/2013/11/20/developing-with-wildfly-jboss-developer-studio-and-docker/)

* [Deploy Java Apps With Docker = Awesome | Atlassian Blogs](https://blogs.atlassian.com/2013/06/deploy-java-apps-with-docker-awesome/)

* Rapid Prototyping a Python web application with Vagrant and Docker | Continuous Delivery Services

  * [Part 1, Development](http://continuousdelivery.uglyduckling.nl/continuous-delivery/rapid-prototyping-a-python-web-application-with-vagrant-and-docker-part-1-development/)

* [Easily Deploy Redis Backed Web Apps With Docker | Tuts+ Code Tutorial](http://code.tutsplus.com/tutorials/easily-deploy-redis-backed-web-apps-with-docker--cms-20405)

* [How to create a Docker + Node.js + MongoDB + Varnish environment | Luis Elizondo](http://luiselizondo.net/blogs/luis-elizondo/how-create-docker-nodejs-mongodb-varnish-environment)

* [Getting Started with Docker for the Node.js | CouchDB Programmer - Medium](https://medium.com/code-adventures/35c45ce2a814)

* [Docker and MongoDB Sharded Cluster | Sebastian Voss](http://sebastianvoss.com/docker-mongodb-sharded-cluster.html)

* [Vagrant 1.6 Feature Preview: Docker-Based Development Environments | Vagrant](https://www.vagrantup.com/blog/feature-preview-vagrant-1-6-docker-dev-environments.html)


* Mac OS X

  * [How To Install Docker On Mac OS X | docker](http://docs.docker.io/en/latest/installation/mac/)

  * [Lightweight Docker experience on OSX | zaiste.net](http://zaiste.net/2014/02/lightweight_docker_experience_on_osx/)

  * [Upgrade docker and boot2docker on OSX | Java Bien!](http://blog.javabien.net/2014/03/17/upgrade-docker-and-boot2docker-on-osx/)

  * [Using Docker transparently on OSX | Shane Sveller](http://shanesveller.com/blog/2014/02/04/using-docker-transparently-on-osx/)

  * [Cooking with Docker and CoreOS on OS X | Siliconfidential](http://www.siliconfidential.com/articles/docker-coreos-osx/)

  * [Unsuck your vagrant: Developing in one VM with Vagrant and Docker | Tony HB](http://tonyhb.com/unsuck-your-vagrant-developing-in-one-vm-with-vagrant-and-docker)

  * [Run Docker in VirtualBox with Vagrant on Mac OS X | Chris LaRose, Software Developer](http://cjlarose.com/2014/03/08/run-docker-with-vagrant.html)

  * [A OSX + Vagrant + Docker + Ruby on Rails Setup | Medium](https://medium.com/docker-news/117daf4ef0a5)


### Soluções

* [[GitHub] boot2docker / boot2docker](https://github.com/boot2docker/boot2docker) - Lightweight Linux for Docker

  * [[Vagrant Cloud] yungsang / boot2docker](https://vagrantcloud.com/yungsang/boot2docker)

* [Project Atomic](http://www.projectatomic.io/) - Sponsored by Red Hat, Inc. Deploy and Manage Your Docker Containers.

* [[GitHub] progrium / dokku](https://github.com/progrium/dokku) - Docker powered mini-Heroku in around 100 lines of Bash

  * [How to Use the DigitalOcean Dokku Application | DigitalOcean](https://www.digitalocean.com/community/articles/how-to-use-the-digitalocean-dokku-application)

* [[GitHub] drone / drone](https://github.com/drone/drone) - is a Continuous Integration platform built on Docker

* [[GitHub] Strider-CD / strider](https://github.com/Strider-CD/strider) - is an Open Source Continuous Deployment / Continuous Integration platform. It is written in Node.JS / JavaScript and uses MongoDB as a backing store. It is published under the BSD license.

* [Create, manage and run clusters of Docker containers using Node.js | decking.io](http://decking.io/)


### Caso de Uso

* [What people have already built using Docker | Docker](https://www.docker.io/community/#What-people-have-already-built-using-Docker)

* [Docker in education: From VMs to Containers | Docker Blog](http://blog.docker.io/2014/04/docker-in-education-interview/)

* [How Docker Helped Us Achieve the (Near) Impossible | Iron.io Blog](http://blog.iron.io/2014/04/how-docker-helped-us-achieve-near.html)


### Node.js

* [[Vimeo] Node.JS and Docker with a side of Continuous Deployment](http://vimeo.com/85864661) - Presented by Niall O'Higgins at JSLA (js.la) on Thursday January 30th 2014. Docker is an incredible new tool to manage the deployment and lifecycle of Node.JS network services. This talk will cover using them together for much Continuous Deployment win.

--

* [[GitHub] adamalex / docker-urlarchiver](https://github.com/adamalex/docker-urlarchiver) - Use Docker to package a Node.js script with all its dependencies, including Node

* [[GitHub] apocas / dockerode](https://github.com/apocas/dockerode) - Not just another Docker.io Remote API node.js module


### Red Hat

* [Red Hat Launches Latest Version of Red Hat Enterprise Linux 6](http://www.redhat.com/about/news/press-archive/2013/11/red-hat-launches-latest-version-of-red-hat-enterprise-linux-6) - RedHat just launched RHEL v6.5 featuring Docker, support for up to 4TB RAM and more! (see: Evolving Ease-of-Use, Storage, and More)

* [Red Hat and Docker](http://www.redhat.com/about/news/press-archive/2013/9/red-hat-and-dotcloud-collaborate-on-docker-to-bring-next-generation-linux-container-enhancements-to-openshift) - Red Hat and dotCloud Collaborate on Docker to Bring Next Generation Linux Container Enhancements to OpenShift Platform-as-a-Service


### Amazon AMI

* [Amazon Linux AMI 2014.03 | Amazon Web Services Blog](http://aws.typepad.com/aws/2014/03/amazon-linux-ami-201403-is-now-available.html) - which includes Linux kernel 3.10.34, Docker, Ruby 2.0 & other features


### Google Cloud

* [[Docker Index] google/cloud-sdk](https://index.docker.io/u/google/cloud-sdk/) - Google Cloud SDK bundle with all components and dependencies

