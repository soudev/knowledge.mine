# git-scm

## SCM Corporativo : pontos a serem considerados 

* Colaboração

> Facilitar ao máximo a evolução dos produtos corporativos por qualquer desenvolvedor capacitado para o mesmo

* Integração

> Garantir que a ferramenta de SCM integre-se com a maior gama de tecnologias possíveis (.NET, Java, IOS, Android, Windows Phone)

* Suporte

> Ter a possibilidade de acionar especialistas para resolver problemas ou orientar o melhor uso de alguma funcionalidade

* Curva de Aprendizado

> Garantir que a usabilidade da ferramenta de SCM seja imediata e de fácil entendimento. Se os usuários desta não a considerarem simples e intuitiva, a resistência será muito alta


## Para que serve?

Gerenciar versões de arquivos de forma distribuída.


## O que é?

* O git-scm é um Sistema de Controle de Versão Distribuído (Distributed Version Control System ou DVCS) | SCM = Source Code Management

* Os clientes não apenas fazem cópias das últimas versões dos arquivos, eles são cópias completas do repositório 

* Caso um servidor falhar, qualquer um dos repositórios dos clientes pode ser copiado de volta para o servidor para restaurá-lo (facilidade de backup)


## Qual o custo?

O git-scm é um software livre, distribuído sob os termos da versão 2 da GNU General Public License.


## Por que foi criado?

* O git-scm foi criado para atender as necessidades de desenvolvimento do Kernel do Linux

* Ser um sistema de arquivos distribuído, não apenas um gerenciador de código fonte

* Possibilitar o desenvolvimento mesmo sem acesso a rede ou a um servidor central 

* Proteger contra corrompimento de arquivos, seja por acidente ou origem maldosa

* O CVS foi utilizado como exemplo do que não fazer (o Linus Torvalds, tem uma visão similar do SVN)


### Referências

* [Git | Wikipedia PT](https://pt.wikipedia.org/wiki/Git)

* [Uma Breve História do Git | Pro Git](http://git-scm.com/book/pt-br/Primeiros-passos-Uma-Breve-Hist%C3%B3ria-do-Git)

* [Sobre Controle de Versão | Pro Git](http://git-scm.com/book/pt-br/Primeiros-passos-Sobre-Controle-de-Vers%C3%A3o)



## Objetivos do git-scm

* Velocidade

* Capacidade de lidar com grande volume de dados

* Design simples

* Suporte robusto ao desenvolvimento não linear

  * Facilidade de criar e mesclar milhares de branches paralelos

* Totalmente distribuído

  * Possibilita definir e utilizar vários tipos de [workflow's](http://git-scm.com/about/distributed)

* Capaz de lidar com grandes projetos

  * Exemplo: Kernel do Linux




## Principais características

[Noções Básicas de Git | Pro Git](http://git-scm.com/book/pt-br/Primeiros-passos-No%C3%A7%C3%B5es-B%C3%A1sicas-de-Git)

* Snapshots, E Não Diferenças

> O git-scm rastreia todas as alterações ocorridas
>
> A maior diferença entre Git e qualquer outro VCS (Subversion e similares inclusos) está na forma que o Git trata os dados.

* Quase Todas Operações São Locais

> Apenas as operações de sincronização com outros repositórios que não são locais

* git-scm Tem Integridade

> A forma com que o Git identifica/versiona as alterações, utilizando checksum (algoritmo SHA-1), ou comumente chamado hash, garante a integridade e unicidade das alterações, com isso reduzindo inumeros problemas na hora de mesclar (merge) conteúdos dos arquivos, atividades executadas comumente em projetos.

* git-scm Geralmente Só Adiciona Dados

> Isso significa que todas as alterações no projeto são adicionadas na "base de dados" local do git-scm, com isso permitindo e possibilitando fazer qualquer alteração (experiência), que futuramente possa ser desfeita, sem nenhuma complicação

* Os Três Estados

> Refere-se aos 3 estados possíveis de um arquivo no repositório local:
> consolidado (committed), modificado (modified) e preparado (staged)
>
> em uma das 3 possíveis sessões do repositório local:
> o diretório do Git (git directory, repository), o diretório de trabalho (working directory), e a área de preparação (staging area)




## Exemplos de Workflows

> Possibilita definir e utilizar vários tipos de [workflow's](http://git-scm.com/about/distributed)

* Estilo SVN

* Colaborativo

* Ditadorial

### Colaboração

* [Git (e Github) para dados | iMasters](http://imasters.com.br/desenvolvimento/git-e-github-para-dados/)

* [Kivo Uses Git To Make Collaborating On Documents Easier, Starting With PowerPoint | TechCrunch](http://techcrunch.com/2013/08/05/kivo-uses-git-to-make-collaborating-on-documents-easier-starting-with-powerpoint/)




## Integração com ferramentas

### Java

#### IDE

* [Eclipse](http://www.eclipse.org/)

  * A partir do [Eclipse Juno SR2 (4.2.2)](http://www.eclipse.org/downloads/packages/release/juno/sr2) - o Eclipse vem com o plugin do eGit junto

  * [EGit | GitHub Eclipse](https://eclipse.github.com/) - para versões anteriores ao Eclipse 4.2.2, necessário instalar este plugin para utilizar o Git diretamente dentro do Eclipse

* [IntellyJ IDEA | Jetbrains](http://www.jetbrains.com/idea/) - possui suporte integrado para Git

* [Netbeans](https://netbeans.org/) - possui suporte integrado para Git


#### Build e Integração Contínua

* [Jenkins CI](http://jenkins-ci.org/) | [git plugin](https://wiki.jenkins-ci.org/display/JENKINS/Git+Plugin)

* [Hudson CI](http://hudson-ci.org/) | [git plugin](http://wiki.hudson-ci.org/display/HUDSON/Git+Plugin)

* [Atlassian Bamboo](https://www.atlassian.com/software/bamboo) - a ferramenta disponibiliza junto um suporte para uso do [git | Bamboo Docs](https://confluence.atlassian.com/display/BAMBOO/Git)


### Microsoft .Net

* Notícia sobre o início do suporte da Microsoft ao Git 

  * [Visual Studio 2012 ganha suporte a Git | InfoQ Br](http://www.infoq.com/br/news/2013/02/vs2012-suporte-git)

  * [Git init VS | Brian Harry's blog : MSDN](https://blogs.msdn.com/b/bharry/archive/2013/01/30/git-init-vs.aspx)

  * [Microsoft Announces Git Support For Visual Studio, Team Foundation Server And Service | TechCrunch](http://techcrunch.com/2013/01/30/microsoft-announces-git-support-for-visual-studio-team-foundation-server-and-service/) (30/01/2013)

  * [TFS Now Integrated with Git | Visual Studio Magazine](http://visualstudiomagazine.com/articles/2012/08/13/tfs-now-integrated-with-git.aspx) (13/08/2012)

  * [Getting started with Git and TFS | ALM Guide - Esteban Garcia](http://www.almguide.com/2013/04/getting-started-with-git-and-tfs/)


* [Visual Studio 2012 update 3](https://www.microsoft.com/en-us/download/details.aspx?id=39305) | [Visual Studio Tools for Git](http://visualstudiogallery.msdn.microsoft.com/abafc7d6-dcaa-40f4-8a5e-d6724bdb980c) - Free

* [Getting Started with Git in Visual Studio and Team Foundation Service | MSDN](https://blogs.msdn.com/b/visualstudioalm/archive/2013/01/30/getting-started-with-git-in-visual-studio-and-team-foundation-service.aspx)

* [Create a new code project in a local Git repo using Visual Studio with Git | Team Foundation Service](http://tfs.visualstudio.com/en-us/learn/create-code-project-vs-git.aspx)

* [Git support for Visual Studio - Git, TFS, and VS put into Context | Scott Hanselman](http://www.hanselman.com/blog/GitSupportForVisualStudioGitTFSAndVSPutIntoContext.aspx)

* [Use Git and Xcode with TFS](http://tfs.visualstudio.com/en-us/learn/use-git-and-xcode-with-tfs.aspx)

* [NuGet](https://www.nuget.org/) - [sobre](http://msdn.microsoft.com/pt-br/magazine/hh547106.aspx) | repositório [git no codeplex](https://nuget.codeplex.com/SourceControl/latest) | projetos no [GitHub](https://github.com/NuGet)


### Apple

* [XCode](https://developer.apple.com/technologies/tools/whats-new.html) - possui suporte integrado para Git

  * [Xcode iPhone beginner projects with GitHub integration | Leniel Macaferi's blog](http://www.leniel.net/2011/08/xcode-iphone-beginner-projects-git.html)


### Clientes

#### Windows

* [msysgit](http://msysgit.github.io/)

* [Atlassian SourceTree](http://www.sourcetreeapp.com/) - Git e Mercurial | apenas para Windows 7 ou superior

* [TortoiseGit](https://code.google.com/p/tortoisegit/)

#### Mac OS X

* [Atlassian SourceTree](http://www.sourcetreeapp.com/) -  Git e Mercurial

* [GitX](http://gitx.frim.nl/)


#### Windows, Linux e Mac OS X

* [GitEye | CollabNet](http://www.collab.net/giteyeapp)

* [SmartGit](http://www.syntevo.com/smartgithg)

* [Git-Cola](http://git-cola.github.com/)

* ungit : [[GitHub] FredrikNoren / ungit](https://github.com/FredrikNoren/ungit) | [npm](https://npmjs.org/package/ungit) | [[Youtube] Introduction](https://www.youtube.com/watch?v=hkBVAi3oKvo) - Aplicação visual para manipulação de um repositório git visualmente. Funciona em qualquer plataforma, porém necessita do [Node.js](http://nodejs.org/) para executar.


### Gestão de git-scm gratuítos e OpenSource

* [GitLab](http://gitlab.org/) - Software de gerenciamento de git-scm. Mantenha e gerencie seu código no seu próprio servidor git. [[GitHub] gitlabhq / gitlabhq](https://github.com/gitlabhq/gitlabhq)

* [Gitorious](http://getgitorious.com/) | [Installation](https://gitorious.org/gitorious/pages/Installation)

* [Redmine](http://www.redmine.org/) - gerenciamento de projetos, possui integração com SCMs (SVN, CVS, [Git](http://www.redmine.org/projects/redmine/wiki/HowTo_configure_Redmine_for_advanced_git_integration), Mercurial, Bazaar e Darcs)




## Suporte comercial / empresarial

* Suporte comercial no Brasil, desconhecido se existe


### RedHat 

* A RedHat oferece suporte ao uso do git-scm no RedHat Enterprise Linux a partir da versão 5

  * [Documentação | RedHat Enterprise Linux](https://access.redhat.com/site/documentation/Red_Hat_Enterprise_Linux/)

  * [Chapter 2. Collaborating](https://access.redhat.com/site/documentation/en-US/Red_Hat_Enterprise_Linux/6/html/Developer_Guide/collaborating.html)

    * [2.3. Git](https://access.redhat.com/site/documentation/en-US/Red_Hat_Enterprise_Linux/6/html/Developer_Guide/collaboration.git.html)


### Microsoft

* A Microsoft oferece suporte ao uso do git-scm dentro do Team Foundation Server a partir do 2012, sendo uma das opções disponíveis para o versionamento de código ao criar um novo projeto no TFS

  * [Enterprise grade Git - Brian Harry's blog | MSDN Blogs](http://blogs.msdn.com/b/bharry/archive/2013/06/19/enterprise-grade-git.aspx)

  * [Create a new code project in a local Git repo using Visual Studio with Git | Team Foundation Service](http://tfs.visualstudio.com/en-us/learn/create-code-project-vs-git.aspx)

  * [Create, Connect, and Publish using Visual Studio with Git - Visual Studio ALM + Team Foundation Server Blog | MSDN Blogs](http://blogs.msdn.com/b/visualstudioalm/archive/2013/02/06/set-up-connect-and-publish-using-visual-studio-with-git.aspx)


### Atlassian

* [Atlassian Stash](https://www.atlassian.com/software/stash/overview) - Enterprise Git Repository Management | [Pricing](https://www.atlassian.com/software/stash/pricing)

* [Git Tutorials and Training | Atlassian](https://www.atlassian.com/git)


### Github

* [GitHub Enterprise](https://enterprise.github.com/) - Bring GitHub to work. The best way to build and ship software, on your servers. | [Pricing](https://enterprise.github.com/pricing)

* [GitHub Enterprise Features](http://teach.github.com/articles/github-enterprise-features/)

* [GitHub Training](http://training.github.com/)


### CollabNet

* [TeamForge for Git | CollabNet](http://www.collab.net/products/teamforge/git-for-the-enterprise) - [preços do suporte](http://www.collab.net/support/support-programs#git), também possuem [ALM](http://www.collab.net/support/support-programs#alm)


### Gitorious

* [Gitorious behind your firewall](http://www.gitorious.com/local_install/) | [Princing](http://www.gitorious.com/pricing) | [Professional support](http://www.gitorious.com/support) | [Git training](http://www.gitorious.com/training)




## Job trends

* [git, subversion, mercurial, github, clearcase, jazz | Indeed](http://www.indeed.com/jobtrends?q=git%2C+subversion%2C+mercurial%2C+github%2C+clearcase%2C+jazz&l=)




## Git em empresas

* [Git Turns 8, Sees Wide Adoption in the Enterprise | Linux.com](http://www.linux.com/news/enterprise/systems-management/715287-git-turns-8-enterprise-wide-adoption/) (20/04/2013)

* [Why the (legacy) Enterprise is Scared of Git – and what you can do about it – Laurence Sweeney | Opscode Blog](http://www.opscode.com/blog/chefconf-talks/why-the-legacy-enterprise-is-scared-of-git-and-what-you-can-do-about-it-laurence-sweeney/)

* [Thoughts on Git and 'Enterprise Open Source' | Guilherme Chapiewski](http://guilherme.pro/2012/06/12/thoughts-on-git-and-enterprise-open-source/)

* [Using Git in Enterprise environment | Programmers Stack Exchange](http://programmers.stackexchange.com/questions/96915/using-git-in-enterprise-environment)

---

* [Why DVCS, git, Atlassian Stash? | AppFusions](http://www.appfusions.com/display/StashSCMImporter/Why+DVCS,+git,+and+Atlassian+Stash)

* [Git Patterns and Anti-Patterns | DZone Refcardz](http://refcardz.dzone.com/refcardz/git-patterns-and-anti-patterns) - Scaling from Workgroup to Enterprise

* [Git Behind the Firewall with Atlassian Stash | Matthew Riley](http://matthewriley.us/git-behind-the-firewall-with-atlassian-stash/) (28/02/2013)

* [Git Branching and Forking in the Enterprise | Atlassian](http://blogs.atlassian.com/2013/05/git-branching-and-forking-in-the-enterprise-why-fork/) - Why Fork?

---

* [ALM vendors scramble to add support for Git | Ovum](http://ovum.com/2013/06/19/alm-vendors-scramble-to-add-support-for-git/)

* IBM

  * [Rational Team Concert](https://jazz.net/products/rational-team-concert/)

    * [Integrating other SCM Systems with Rational Team Concert 2.0 | Jazz Community](https://jazz.net/library/article/194/) - Git e IBM RTC

    * [Integrating Rational Team Concert and Git | Help - IBM Rational Software](http://pic.dhe.ibm.com/infocenter/clmhelp/v4r0m2/index.jsp?topic=%2Fcom.ibm.team.connector.cq.doc%2Ftopics%2Fc_integ_git.html)

  * [Collaborative Lifecycle Management](https://jazz.net/products/clm/)

    * [Connect Rational CLM to Atlassian JIRA, HP ALM, and Git or Gerrit | Jazz Community](https://jazz.net/products/clm/features/clm_integrations) - possibilidade de integrar ao Atlassian Jira e ao Git

    * [[YouTube] IBM Rational Lifecycle Integration Adapter Standard Edition Overview](https://www.youtube.com/watch?v=irNeT1UWvmE) - This video introduces IBM Rational Lifecycle Adapters for HP ALM, Atlassian JIRA and Git, and how they integrate IBM Rational ALM tools (Rational Requirements Composer, Rational Team Concert and Rational Quality Manager) with non-IBM tools (HP ALM, JIRA and Git). The topics addressed include: - Rational Lifecycle Adapters - Open Services for Lifecycle Collaboration (OSLC) - Rational Adapter for HP ALM - Rational Adapter for Git - Rational Adapter for JIRA



## Quem usa?

### Listados no : git-scm

#### Empresas

* [Google](http://www.google.com) : projetos OpenSource no [GitHub](https://github.com/google)

* [Facebook](https://www.facebook.com/) : projetos OpenSource no [GitHub](https://github.com/facebook)

* [Microsoft](https://www.microsoft.com/) : [ASP.net](https://aspnetwebstack.codeplex.com/) no CodePlex

  * O [CodePlex](https://www.codeplex.com/) também possibilita a [escolha de repositório Git](https://codeplex.codeplex.com/wikipage?title=Using%20Git%20with%20CodePlex&referringTitle=Source%20Control) para o versionamento de código dos projetos hospedados lá.

  * Projetos OpenSource do time do Windows Azune SDK no [GitHub](http://windowsazure.github.io/)

* [Twitter](https://twitter.com/) : projetos OpenSource no [GitHub](https://github.com/twitter)

* [LinkedIn](http://www.linkedin.com/) : projetos OpenSource no [GitHub](https://github.com/linkedin)

* [NETFLIX](http://netflix.com) : projetos OpenSource no [GitHub](https://github.com/netflix)


#### Projetos

* [The Perl Programming Language](http://www.perl.org/) : repositório próprio de [git](http://perl5.git.perl.org/perl.git)

* [PostgreSQL](http://www.postgresql.org/) : repositório próprio de [git](http://git.postgresql.org/gitweb/)

* [Android](http://www.android.com/) : repositório próprio de [git](https://android-review.googlesource.com/#/q/status:open,n,z)

* [Linux Kernel](https://www.kernel.org/) : repositório próprio de [git](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git)

* [Ruby on Rails](http://rubyonrails.org/) : repositório no [GitHub](https://github.com/rails/rails)

* [QT](http://qt-project.org/) : repositório no [Gitorious](https://qt.gitorious.org/)

* [Gnome](https://www.gnome.org/) : repositório próprio de [git](https://git.gnome.org/browse/)

* [Eclipse](http://eclipse.org/) : repositório próprio de [git](http://git.eclipse.org/c/)

* [KDE](http://kde.org/) : repositório próprio de [git](http://quickgit.kde.org/)

* [The X.Org Foundation](http://www.x.org/wiki/) : repositório git no [freedesktop.org](http://cgit.freedesktop.org/), conforme verificado nesta [documentação](http://www.x.org/wiki/Development/BuildingX/?action=show&redirect=Development%2Fgit) para os desenvolvedores


### Não listados no : git-scm

#### Empresas

* [SAP](http://www.sap.com/) : projetos OpenSource no [GitHub](http://sap.github.io/)

* [Joyent](https://www.joyent.com/) : projetos OpenSource no [GitHub](https://github.com/joyent)

* [NASA](http://www.nasa.gov/) : projetos OpenSource no [GitHub](https://github.com/nasa)

* [BBC News](http://www.bbc.co.uk/news/) : projetos OpenSource no [GitHub](https://github.com/BBC-News)

* [Abril](http://www.abril.com.br/) : projetos OpenSource no [GitHub](https://github.com/abril)

* [Globo.com](http://www.globo.com/) : projetos OpenSource no [GitHub](https://github.com/globocom)

* [OpenSuse](http://www.opensuse.org/) : repositório no [Gitorious](https://gitorious.org/opensuse)

* [XBMC Media Center](http://xbmc.org/) : repositório no [Gitorious](https://gitorious.org/xbmc)

* [Rakuten](http://www.rakuten.co.jp/) : projetos internos em [git utilizando o Atlassian Stash](https://www.atlassian.com/company/customers/case-studies/rakuten) | Empresa de e-Commerce japonesa.

* [Orbitz](http://www.orbitz.com/) : projetos internos em [git utilizando o Atlassian Stash](https://www.atlassian.com/company/customers/case-studies/orbitz) | Empresa de e-Commerce norte americana.

* [Zarafa](http://www.zarafa.com/) : projetos em um [git](https://git.zarafa.com/) próprio | empresa especializada em sistemas de mensagem e colaboração. Mais informações sobre: [1](http://www.linuxnewmedia.com.br/lm/noticia/um_repositorio_git_para_o_zarafa) | [2](http://www.zarafa.com/news/2-february-2012-zarafa-catalyses-software-development-collaboration-launching-gitzarafacom)

* [Kivo](http://www.kivo.com/) - solução para MS Power Point, na qual é utilizado o git-scm para gerenciar o versionamento e o trabalho colaborativo em apresentações. 

  * [Kivo Uses Git To Make Collaborating On Documents Easier, Starting With PowerPoint | TechCrunch](http://techcrunch.com/2013/08/05/kivo-uses-git-to-make-collaborating-on-documents-easier-starting-with-powerpoint/)

* [CERN](http://home.web.cern.ch/) - Organização Europeia para a Investigação Nuclear, maior laboratório de física de partículas do mundo e referência global no assunto, faz uso do sistema em suas pesquisas relacionadas a partículas de energia. 

  * Projetos OpenSource no [GitHub](https://github.com/CERN)

  * Projetos Git hospedados pelo CERN : [git.cern.ch](http://git.cern.ch/pubweb/)

  * CERN › IT DEPARTMENT › SERVICES › [GIT SERVICE](http://information-technology.web.cern.ch/services/git-service)



#### Projetos

* [Spring Source](http://www.springsource.org/) : projetos OpenSource no [GitHub](https://github.com/SpringSource)

* [JBoss Community](https://community.jboss.org/) : projetos OpenSource no [GitHub](https://github.com/jbossorg)

* [Node.js](http://nodejs.org/) : projeto no [GitHub](https://github.com/joyent/node)


#### Governo : Brasil

* [PloneGovBr](http://www.softwarelivre.gov.br/plone) : projetos OpenSource no [GitHub](https://github.com/plonegovbr)

* [DadosGovBr](http://dados.gov.br/) : projetos OpenSource no [GitHub](https://github.com/dadosgovbr)

* [Demoiselle](http://www.frameworkdemoiselle.gov.br/) - é um conjunto de seis projetos, sendo cinco de software e um processo de desenvolvimento (Framework em Java criado pelo [SERPRO](http://www.serpro.gov.br/)). Projetos OpenSource no [GitHub](https://github.com/demoiselle)


#### Governo : Estados Unidos

* [The White House](http://www.whitehouse.gov/) | [Developers](http://www.whitehouse.gov/developers) : projetos OpenSource no [GitHub](https://github.com/WhiteHouse)

* [Project Open Data](http://project-open-data.github.io/) : projetos OpenSource no [GitHub](https://github.com/project-open-data)



## Posso confiar em uma solução OpenSource?

* Relembrando que o git-scm foi criado para manter e comportar o desenvolvimento do Kernel do Linux, para ter uma pequena noção da importância do Kernel do Linux, é bom saber onde este é utilizado

* [10 coisas que não existiriam se não fosse o Linux | TecMundo](http://www.tecmundo.com.br/linux/12021-10-coisas-que-nao-existiriam-se-nao-fosse-o-linux.htm) - O sistema operacional livre mais famoso do mundo está em vários lugares é mais importante do que você pode imaginar.

  * Grandes servidores

  * Sistemas de controle de tráfego aéreo

  * Sistemas de alta tecnologia para controle de tráfego

  * Android

  * Trem de alta velocidade japonês

  * Bolsa de Nova York

  * Carros inteligentes da Toyota

  * Acelerador de partícula (CERN)

  * Submarinos nucleares

