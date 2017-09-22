# REST

<!-- toc -->

* [Visão Geral](#visão-geral)
* [API](#api)
* [Desgin](#desgin)
* [i18n](#i18n)
* [Desenvolvimento](#desenvolvimento)
  * [JIRA](#jira)
  * [dotNet](#dotnet)
  * [Java](#java)
    * [Monitoramento](#monitoramento)
    * [Testes](#testes)
    * [Segurança](#segurança)
  * [Python](#python)
  * [PHP](#php)
  * [Node.js](#nodejs)
* [Ferramentas](#ferramentas)
  * [Mock](#mock)
  * [Google Chrome](#google-chrome)
* [HATEOAS](#hateoas)
* [HAL](#hal)

<!-- toc stop -->


## Visão Geral

* Wiki : REST [en](http://en.wikipedia.org/wiki/Representational_state_transfer) | [pt](http://pt.wikipedia.org/wiki/REST)

* [Best Practices for Designing a Pragmatic RESTful API | Vinay Sahni](http://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api)

--

* [RAML](http://raml.org/) - RESTful API Modeling Language

## API

* CEP

  * [Correios RESTful API](https://correiosapi.apphb.com/)

    * [[GitHub] emersonsoares / AddressAPI](https://github.com/emersonsoares/AddressAPI)

  * [Postmon](http://postmon.com.br/) - Uma API para consultar CEP e encomendas de maneira fácil, rápida e gratuita

    * [Hackeando Códigos Postais | InfoQ BR](http://www.infoq.com/br/presentations/hackeando-codigos-postais)

  * [Busca CEP - API de Consulta](http://apps.widenet.com.br/busca-cep/api-de-consulta)

  * [[GitHub] prodis /correios-cep](https://github.com/prodis/correios-cep) - Get Brazilian address by zipcode, directly from Correios database. No HTML parsers

  * [API de consulta de CEP grátis | Aviso Brasil](http://avisobrasil.com.br/correio-control/api-de-consulta-de-cep/) - Finalmente, um serviço de consulta de CEP gratuito criado por uma empresa sólida, cujo negócio é lidar com Correios. Um presente para você desenvolvedor.

* [[GitHub] toddmotto / public-apis](https://github.com/toddmotto/public-apis) - A collective list of public JSON APIs for use in web development

--

* [Forecast.io](http://forecast.io/)

  * [Developer - Forecast.io](https://developer.forecast.io/)

--

* [Runscope](https://www.runscope.com/) - Debug and test your API, webhook and mobile back end service integrations.

--

* Telize

  * [JSON IP and GeoIP REST API (IP Geolocation) | Telize](http://www.telize.com/)

  * [[GitHub] fcambus / telize](https://github.com/fcambus/telize) - Telize is a JSON IP and GeoIP REST API (IP Geolocation) built on Nginx and Lua

--

* Geocode

  * [Geocode Area Names of a City to get Lat and Long | StackOverflow](http://stackoverflow.com/questions/3806548/geocode-area-names-of-a-city-to-get-lat-and-long)

  * [A Google Geocoding API | Google Developers](https://developers.google.com/maps/documentation/geocoding/?hl=pt-BR&csw=1)

    * [Exemplo JSON : Curitiba](https://maps.googleapis.com/maps/api/geocode/json?address=Curtiba&sensor=false)

    * [Latitude Longitude Finder | latlong.net](http://www.latlong.net/) - utiliza o serviço do Google como base

--

* [White House Web API Standards](https://github.com/WhiteHouse/api-standards)

* [7 erros mais comuns na hora de criar uma API | Escalabilidade](http://escalabilidade.com/2010/09/22/7-erros-mais-comuns-na-hora-de-criar-uma-api/)

* [2 steps to better API Error Codes | API UX](http://apiux.com/2013/03/28/2-steps-api-error-codes/)

* [webshell.io: The API of APIs](http://webshell.io/) - The API Combinator - Combine APIs easily in Javascript and create REST/JSON API on the fly.

--

* [Examples of the Marvel API | Raymond Camden](http://www.raymondcamden.com/index.cfm/2014/2/2/Examples-of-the-Marvel-API)

* [Evoluindo uma Arquitetura inteiramente sobre APIs: o caso da SoundCloud | InfoQ Br](http://www.infoq.com/br/presentations/evoluindo-uma-arquitetura-soundcloud) - As aplicações da SoundCloud reutilizam sua API pública; o uso de uma camada de serviços RESTful parecia uma decisão sólida, mas cada cliente tem suas próprias necessidades. A SoundCloud está migrando para um modelo onde clientes mantêm suas próprias APIs. Foram necessárias mudanças em arquitetura, tecnologias e processo. Nesta apresentação vamos explorar os desafios enfrentados e decisões tomadas.


## Desgin

* [[GitHub] interagent / http-api-design](https://github.com/interagent/http-api-design) - HTTP API design guide extracted from work on the Heroku Platform API

  * [[GitHub] Gutem / http-api-design](https://github.com/Gutem/http-api-design) - pt-Br

* [REST Patterns](http://restpatterns.org/)

* [RESTful Service](http://ajaxpatterns.org/RESTful_Service)

* [REST-ful URI design](http://blog.2partsmagic.com/restful-uri-design/)

* [API Design at GitHub](http://tech.yandex.com/events/yac/2013/talks/42/) - Get a behind-the-scenes look at development on the GitHub API team

* [Stop Designing Fragile Web APIs](http://mathieu.fenniak.net/stop-designing-fragile-web-apis/)

* [API Security and Federation Patterns | InfoQ](http://www.infoq.com/presentations/api-security-federation-patterns)

* [Não exponha seu REST | InfoQ Br](http://www.infoq.com/br/news/2013/09/nao-exponha-seu-rest)

* [Designing HTTP Interfaces and RESTful Web Services](http://www.slideshare.net/Wombert/designing-http-interfaces-and-restful-web-services-phpday11-20110514)

* [Designing REST + JSON APIs | Stormpath](https://www.stormpath.com/blog/designing-rest-json-apis)

* [Cinco passos essenciais para uma API de sucesso | iMasters](http://imasters.com.br/apis/cinco-passos-essenciais-para-uma-api-de-sucesso/)

* [[Speaker Deck] REST: Definições e Boas Práticas](https://speakerdeck.com/alextercete/rest-definicoes-e-boas-praticas) - by Alex Tercete. Apresentação realizada como parte da iniciativa VTEX Tech Talks.

--

* [API design for an event-driven world](http://shapeshed.com/api-design-for-an-event-driven-world/) - REST and HATEOS are designed around request response cycles. New thinking is needed for bidirectional, event-driven, realtime APIs.

--

* [Introducing: Restful Objects](http://www.infoq.com/articles/Intro_Restful_Objects)

* [Restful Objects Specification](http://restfulobjects.org/) [github](https://github.com/danhaywood/restfulobjects-spec)

* [RESTful API Design: Second Edition Webinar - Video & slides](http://blog.apigee.com/detail/slides_for_restful_api_design_second_edition_webinar)

* [The Good, the Bad, and the Ugly of REST APIs](http://www.infoq.com/news/2011/06/RestAPIs)

* [API Anti-Patterns: How to Avoid Common REST Mistakes](http://blog.programmableweb.com/2010/08/13/api-anti-patterns-how-to-avoid-common-rest-mistakes/)

* [[REST workflow] How to GET a Cup of Coffee](http://www.infoq.com/articles/webber-rest-workflow)

* [Richardson Maturity Model](http://martinfowler.com/articles/richardsonMaturityModel.html) - níveis de maturidade de uma aplicação/API REST

* [Arquitetura REST e o serviço web RESTful](http://sao-paulo.pm.org/artigo/2010/RESTful)

* [Como um verdadeiro sistema REST funciona: arquitetura e performance na Abril](http://www.slideshare.net/lfcipriani/como-um-verdadeiro-sistema-rest-funciona-arquitetura-e-performance-na-abril)

* [[SlideShare] RESTful Web Services](http://www.slideshare.net/gordonad/restful-web-services-13299618) - Using Spring to create a RESTful java application

* [Guru-SP - Abusando nas requisições HTTP sem medo - Luis Cipriani](http://blip.tv/agaelebe/26_11_2011_gurusp_http_cipriani-720-5879314)

* [Transferência de estado representacional – REST – via HTTP | JavascriptBrasil](http://javascriptbrasil.com/artigos/transferencia-de-estado-representacional-rest-via-http)

* [REST é a melhor escolha para seus próximos projetos de mobile/desktop/api](http://www.igorcosta.com/rest-e-a-melhor-escolha-para-seus-proximos-projetos-de-mobiledesktopapi/)

* [[PDF] RESTful Web Services - An introduction to building Web Services without tears](http://home.ccil.org/%7Ecowan/restws.pdf) (i.e., without SOAP or WSDL)

* [Designing a Secure REST (Web) API without OAuth | The Buzz Media](http://www.thebuzzmedia.com/designing-a-secure-rest-api-without-oauth-authentication/)

--

* [[SlideShare] The RESTful Soa Datagrid with Oracle](http://www.slideshare.net/EmilianoPecis/the-restful-soa-datagrid-with-oracle) - It transforms and caches any SOA based application in REST. A proxy "soap to rest" is provided, using Oracle Service Bus and Oracle Coherence.(22/04/2009) [Slide 11 é interessante]

--

* [Morte à sessão! Entenda esse tal de stateless session com tokens | Caelum](http://blog.caelum.com.br/morte-a-sessao-entenda-esse-tal-de-stateless-session-com-tokens/) - 2017/04/03


## i18n

* [Accept-Language used for locale setting | W3C](http://www.w3.org/International/questions/qa-accept-lang-locales)

* [Internationalisation in a RESTful world | OpenTable Tech UK Blog](http://tech.opentable.co.uk/blog/2014/04/02/internationalisation-in-a-restful-world/)


## Desenvolvimento

* [Learn REST: A RESTful Tutorial](http://www.restapitutorial.com/)

* [Choosing an HTTP Status Code — Stop Making It Hard | Racksburg](http://racksburg.com/choosing-an-http-status-code/)

* [httpstatuses.com](https://httpstatuses.com/) - is an easy to reference database of HTTP Status Codes with their definitions and helpful code references all in one place.

* [HTTP Status Codes](http://restpatterns.org/HTTP_Status_Codes)

* [The HTTP status codes in IIS 7.0 and in IIS 7.5 | x443](http://x443.wordpress.com/2012/12/02/the-http-status-codes-in-iis-7-0-and-in-iis-7-5/)


### JIRA

* [JIRA REST API documentation](https://docs.atlassian.com/jira/REST/latest/)

* [JIRA REST API Tutorials](https://developer.atlassian.com/display/JIRADEV/JIRA+REST+API+Tutorials)


### dotNet

* [asp.net - Web API](http://www.asp.net/web-api)

* [An Introduction To RESTful Services With WCF (.Net)](http://msdn.microsoft.com/en-us/magazine/dd315413.aspx)

* [A Guide to Designing and Building RESTful Web Services with WCF 3.5](http://msdn.microsoft.com/en-us/library/dd203052.aspx)

* [Conditional GET and ETag Support in WCF WebHttp Services](http://blogs.msdn.com/b/endpoint/archive/2010/02/25/conditional-get-and-etag-support-in-wcf-webhttp-services.aspx)

* [Criando serviços REST com WCF](http://msdn.microsoft.com/pt-br/library/dd941696.aspx)

* [Implementing 5 important principles of REST using WCF Services](http://www.codeproject.com/Articles/283550/Implementing-5-important-principles-of-REST-using)

* [ASP.NET MVC 4 - Web API - REST](http://www.asp.net/web-api)

* [ASP.NET MVC 4 - Criando e Usando uma Web API](http://www.macoratti.net/12/07/mvc4_ap2.htm)

* [WebAPI for the MVC Guy](http://wildermuth.com/2012/2/22/WebAPI_for_the_MVC_Guy)



### Java

* [RESTful API Server – Doing it the right way (Part 1) | MKBlog](http://blog.mugunthkumar.com/articles/restful-api-server-doing-it-the-right-way-part-1/)

* [RESTful API Server – Doing it the right way (Part 2) | MKBlog](http://blog.mugunthkumar.com/articles/restful-api-server-doing-it-the-right-way-part-2/)

* [Spring MVC REST Exception Handling Best Practices (part 1)](http://www.stormpath.com/blog/spring-mvc-rest-exception-handling-best-practices-part-1)

* [Build a RESTful Web Service Using Spring 3, XML Optional](http://jnb.ociweb.com/jnb/jnbNov2010.html)

* [[baeldung part 1] Bootstrapping a web application with Spring 3.1 and Java based Configuration](http://www.baeldung.com/2011/10/20/bootstraping-a-web-application-with-spring-3-1-and-java-based-configuration-part-1/)

* [Spring Data Rest - JPA Repository REST Exporter](https://github.com/SpringSource/spring-data-rest/wiki/JPA-Repository-REST-Exporter)

* [[YouTube] Spring Data REST: Easily export JPA entities directly to the web](https://www.youtube.com/watch?v=kaiH1HsacPs)

* [[GitHub] olivergierke / spring-restbucks](https://github.com/olivergierke/spring-restbucks) - Implementation of the sample from REST in Practice based on Spring projects

* [Putting Java to REST | Javalobby](http://java.dzone.com/articles/putting-java-rest)

--

* [JAX-RS 2.0, as novidades do padrão para desenvolvimento REST e o mundo das APIs | InfoQ Br](http://www.infoq.com/br/presentations/jax-rs-2-as-novidades-do-padrao-para-desenvolvimento) - Conheça as novidades da API de desenvolvimento de REST da plataforma Java e as novas funcionalidades que irão tornar o desenvolvimento mais simples, produtivo e divertido, bem como os conceitos de desenvolvimento de APIs para integração com parceiros, clientes e devices.

--

* [Building RESTful Web Services with JAX-RS](http://docs.oracle.com/javaee/6/tutorial/doc/giepu.html)

* [RESTful services with jQuery and Java using JAX-RS and Jersey](http://coenraets.org/blog/2011/12/restful-services-with-jquery-and-java-using-jax-rs-and-jersey/)

* [The Java API for RESTful Web Services (JAX-RS) - Rapidly Build Lightweight Web Services | Oracle](http://www.oracle.com/technetwork/articles/javaee/jax-rs-159890.html)

* [REST with Java (JAX-RS) using Jersey - Tutorial](http://www.vogella.com/articles/REST/)

* [[GitHub] tdiesler / javaee-tutorial](https://github.com/tdiesler/javaee-tutorial) - [JBoss JavaEE 6 Tutorial](https://docs.jboss.org/author/display/AS71/JavaEE+6+Tutorial)

* [RESTful Web services Tutorials | How to do in JAVA](http://howtodoinjava.com/restful-web-service/)

* [REST Query Language with Spring and JPA Criteria | Baeldung](http://www.baeldung.com/rest-search-language-spring-jpa-criteria) - An introduction to implementing a simple but very useful serach/filter operation on your Spring REST APIs using JPA Criteria.

--

* [Java EE 7 and JAX-RS 2.0 | Oracle Technology Network](http://www.oracle.com/technetwork/articles/java/jaxrs20-1929352.html)

* [Java EE 7 / JAX-RS 2.0 – CORS on REST | Developers's ScrapPad](http://www.developerscrappad.com/1781/java/java-ee/rest-jax-rs/java-ee-7-jax-rs-2-0-cors-on-rest-how-to-make-rest-apis-accessible-from-a-different-domain/) - How to make REST APIs accessible from a different domain

--

* [Adicionando flexibilidade à sua implementação REST com Yoga | InfoQ Br](http://www.infoq.com/br/articles/json-yoga)

* [Build HATEOAS API in Java with Spring MVC, Jersey (JAX-RS) and VRaptor | ZeroTurnaround](http://zeroturnaround.com/rebellabs/beyond-rest-how-to-build-a-hateoas-api-in-java-with-spring-mvc-jersey-jax-rs-and-vraptor/)

  * [[GitHub] jrdalpra / addresses](https://github.com/jrdalpra/addresses) - Comparing HATEOAS implementations with Jersey, Spring and VRaptor

* Jersey Spring

  * [[GitHub] jersey / examples / helloworld-spring-webapp](https://github.com/jersey/jersey/tree/2.4.1/examples/helloworld-spring-webapp) - tag: 2.4.1

  * [[GitHub] thomasma / jaxrs-jersey-springsec](https://github.com/thomasma/jaxrs-jersey-springsec)


#### Monitoramento

* [Monitoring of RESTful Jersey application | Miroslav Fuksa's blog](https://blogs.oracle.com/mira/entry/monitoring_of_restful_jersey_applicaiton)


#### Testes

* [Integration Testing of Spring MVC Applications: REST API, Part One](http://www.petrikainulainen.net/programming/spring-framework/integration-testing-of-spring-mvc-applications-rest-api-part-one/)


#### Segurança

* [REST Security Cheat Sheet | OWASP](https://www.owasp.org/index.php/REST_Security_Cheat_Sheet)

* [Secure Your REST API... The Right Way | Stormpath](http://www.stormpath.com/blog/secure-your-rest-api-right-way)

* [[baeldung part 3] Securing a RESTful Web Service with Spring Security 3.1](http://www.baeldung.com/2011/10/31/securing-a-restful-web-service-with-spring-security-3-1-part-3/)

* [[baeldung part 6] Basic and Digest authentication for a RESTful Service with Spring Security 3.1](http://www.baeldung.com/2011/11/20/basic-and-digest-authentication-for-a-restful-service-with-spring-security-3-1/)

* [Securing REST WebServices with Spring Security and Custom HTTP Request Factories](http://www.jpalace.org/docs/technotes/spring/rest-security.html)

* [[DZone ref card] Expression-Based Authorization with Spring Security 3](http://refcardz.dzone.com/refcardz/expression-based-authorization)

* [OAuth with Spring Security](http://www.javacodegeeks.com/2012/02/oauth-with-spring-security.html)

* [[GitHub] alesaudate / kickstart-springjerseyhibernate](https://github.com/alesaudate/kickstart-springjerseyhibernate) - A fully functional project configured with spring, spring security, REST (with Jersey) and Hibernate. The intent is to provide a bootstrap for this configuration. ( via [Começando rápido com Spring, Spring Security e REST](http://www.guj.com.br/java/261989-comecando-rapido-com-spring-spring-security-e-rest) )

* [Secure RESTful Services with Maven, Spring, Jersey and Spring Security](http://blogs.justenougharchitecture.com/?p=493) | [GitHub : Code](https://github.com/thomasma/jaxrs-jersey-springsec)

* [Spring Security 3 with RESTful Authentication](http://thatgeekything.blogspot.com.br/2012/08/spring-security-3-with-restful.html) | [GitHub : Code](https://github.com/joevartuli/RESTfulSpringSecurity)

* [Spring 3.1 RESTful Authentication](http://kevinpotgieter.wordpress.com/2012/05/14/spring-3-1-restful-authentication/) | [GitHub : Code](https://github.com/kevinpotgieter/example-spring-rest-authentication)

* [Reusing Persistent Token Mechanism of Spring Security](http://www.harezmi.com.tr/reusing-persistent-token-mechanism-of-spring-security/)

* [Spring - Implementing REST Authentication](http://www.objectpartners.com/2011/06/16/implementing-rest-authentication/) | [GitHub : Code](https://github.com/jurberg/rest-security)


### Python

* [Developing RESTful Web APIs with Python, Flask and MongoDB](https://speakerdeck.com/u/nicola/p/developing-restful-web-apis-with-python-flask-and-mongodb)


### PHP

* [[GitHub] phanan / htaccess](https://github.com/phanan/htaccess) - A collection of useful .htaccess snippets

--

* [Laravel 4: A Start at a RESTful API | Tuts+ Code Tutorial](http://code.tutsplus.com/tutorials/laravel-4-a-start-at-a-restful-api-updated--net-29785)

* [Laravel 4: Começando com API RESTful | Tuts+ Code Tutorial](http://code.tutsplus.com/pt/tutorials/laravel-4-a-start-at-a-restful-api-updated--net-29785)

* [API REST com Laravel | Fabio Vedovelli](http://www.vedovelli.com.br/web-development/api-rest-com-laravel/)

--

* [How to Consume Laravel API with AngularJS | SitePoint](http://www.sitepoint.com/how-to-consume-laravel-api-with-angularjs/) - 2016/02/19


### Node.js

* [Why is Node.js so popular for REST API? | LinkedIn Pulse](https://www.linkedin.com/pulse/article/20141112140704-4013609-why-is-node-js-so-popular-for-rest-api)

--

* [Creating a REST API using Node.js, Express, and MongoDB](http://coenraets.org/blog/2012/10/creating-a-rest-api-using-node-js-express-and-mongodb/)

* [[GitHub] simov / purest](https://github.com/simov/purest) - REST API client library

* [Guardian.js](http://guardianjs.com/) - Consuming OAuth services has never been easier. Guardian reduces the OAuth footprint in your code to a single request


## Ferramentas

* [Swagger](https://developers.helloreverb.com/swagger/) - is a specification and complete framework implementation for describing, producing, consuming, and visualizing RESTful web services

### Mock

* [Mocky](http://www.mocky.io/) - Mock your HTTP responses to test your REST API


### Google Chrome

* [Postman - REST Client](https://chrome.google.com/webstore/detail/postman-rest-client/fdmmgilgnpjigdojojpjoooidkmcomcm)

  * [API Building and Testing Made Easier with Postman | SitePoint](http://www.sitepoint.com/api-building-and-testing-made-easier-with-postman/) - 2016/02/26

* [Advanced REST client](https://chrome.google.com/webstore/detail/advanced-rest-client/hgmloofddffdnphfgcellkdfbfbjeloo)

* [REST Console](https://chrome.google.com/webstore/detail/rest-console/cokgbflfommojglbmbpenpphppikmonn)


## HATEOAS

*Definição:* _HATEOAS_ - Hypermedia as the Engine of Application State [wiki](http://en.wikipedia.org/wiki/HATEOAS)

* [Resources about HATEOAS - Alessandro Nadalin](http://odino.org/resources-about-hateoas/)

* [HATEOAS: The Confusing Bit from REST](http://www.slideshare.net/adorepump/hateoas-the-confusing-bit-from-rest)

* [Why HATEOAS](http://www.slideshare.net/trilancer/why-hateoas-1547275)

* [Hypermedia APIs](http://oredev.org/2010/sessions/hypermedia-apis)

* [Presentation: From REST to HATEOAS](http://www.smartjava.org/content/presentation-rest-hateoas)

* [HATEOAS RESTful Services using Spring 3.1](http://blog.furiousbob.com/2011/12/06/hateoas-restful-services-using-spring-3-1/)

* [[GitHub] SpringSource / spring-hateoas](https://github.com/SpringSource/spring-hateoas)

* [[Vimeo] Designing Hypermedia APIs by Steve Klabnik](http://vimeo.com/53223942) - Ruby on Rails did a lot to bring REST to developers, but its conception leaves the REST devotee feeling a bit empty. "Where's the hypermedia?" she says. "REST isn't RPC," he may cry. In this talk, Steve will explain how to design your APIs so that they truly embrace the web and HTTP. Pros and cons of this approach will be discussed, as well as why many aren't building things this way yet.


## HAL

*Definição:* _HAL_ is two media types (application/hal+json &  application/hal+xml) with which applications are exposed as sets of link  relations.

* [HAL - Hypertext Application Language](http://stateless.co/hal_specification.html)

* [JSON Linking with HAL](http://blog.stateless.co/post/13296666138/json-linking-with-hal)
