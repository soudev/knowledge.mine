# Autenticação & Autorização

<!-- toc -->

  * [Geral](#geral)
  * [x509](#x509)
    + [nodejs x509](#nodejs-x509)
  * [JWT](#jwt)
  * [OAuth](#oauth)
    + [Two-Factor Authentication](#two-factor-authentication)
  * [SAML](#saml)
  * [WS-Trust](#ws-trust)
  * [Identity Server](#identity-server)
- [CAS](#cas)
  * [Microsoft ADFS / Microsoft ACS / SWT](#microsoft-adfs--microsoft-acs--swt)

<!-- tocstop -->


## Geral

* [Authentication for Single Page Apps | madhatted.com](http://madhatted.com/2014/6/17/authentication-for-single-page-apps)

* [10 Things You Should Know about Tokens | Auth0](https://auth0.com/blog/2014/01/27/ten-things-you-should-know-about-tokens-and-cookies/) - (2014/01/27) Explore in more detail some of the most common questions around token-based authentication.

* [What is and how does Single Sign On work? | Auth0 Blog](https://auth0.com/blog/2015/09/23/what-is-and-how-does-single-sign-on-work/) - (2015/09/23) In this post you will learn about Single Sign On and how to use it for your web apps


## x509

* [x509 - Certificate display and signing utility | OpenSSL](https://www.openssl.org/docs/apps/x509.html)

* [DER vs. CRT vs. CER vs. PEM Certificates and How To Convert Them | InfoSSL](https://info.ssl.com/article.aspx?id=12149)

--

* [X.509 Certificates | CAS User Manual](https://wiki.jasig.org/display/CASUM/X.509+Certificates)

* [X.509 Login Handler | Shibboleth 2 - Confluence](https://wiki.shibboleth.net/confluence/display/SHIB2/X.509+Login+Handler)


### nodejs x509

* [How to generate self-signed certificate for usage in Express4 or Node.js HTTP | Warehouse](http://blog.matoski.com/articles/node-express-generate-ssl/)

--

* [HTTPS Authorized Certs with Node.js | Circle Engineering](http://engineering.circle.com/https-authorized-certs-with-node-js/) - 2015/02/02

* [Using client certs in node.js | Ceejbot](http://ceejbot.tumblr.com/post/39969163196/using-client-certs-in-node-js)

* [Client and Server side SSL with NodeJS | Vanja Komadinovic](https://vanjakom.wordpress.com/2011/08/11/client-and-server-side-ssl-with-nodejs/)

  * [[GitHub] vanjakom / JavaScriptPlayground /client_server_ssl_nodejs](https://github.com/vanjakom/JavaScriptPlayground/tree/master/client_server_ssl_nodejs)

--

* [[GitHub] tgies / client-certificate-auth](https://github.com/tgies/client-certificate-auth) - middleware for Node.js implementing client SSL certificate authentication/authorization

  * [HTTPS & Authentication - Belgian node.js User Group | Slides](11/12/2013) - 2013/12/11 [#52 - cert authentication](http://slides.com/jeroenmoors/https-authentication-in-nodejs#/52)

    * [[GitHub] jeroenmoors / nodettps / https_with_belgian_eid.js](https://github.com/jeroenmoors/nodettps/blob/master/https_with_belgian_eid.js)

--

* [[GitHub] yorkie / node-x509](https://github.com/yorkie/node-x509) - Simple X509 certificate parser

* [[GitHub] TheThingSystem / node-x509-keygen](https://github.com/TheThingSystem/node-x509-keygen) - node.js module to generate self-signed certificate via openssl spawn


## JWT

> JSON Web Token

* [The Anatomy of a JSON Web Token | Scotch](https://scotch.io/tutorials/the-anatomy-of-a-json-web-token)

* [Authenticate a Node.js API with JSON Web Tokens | Scotch](https://scotch.io/tutorials/authenticate-a-node-js-api-with-json-web-tokens)

* [Create and Verify JWTs With Node.js | Stormpath](https://stormpath.com/blog/nodejs-jwt-create-verify/)

  * [[GitHub] jwtk / njwt](https://github.com/jwtk/njwt) - Node.js JWT support - create, verify, ninjafy

* [Build Secure User Interfaces Using JSON Web Tokens (JWTs) | Stormpath](https://stormpath.com/blog/build-secure-user-interfaces-using-jwts/)


## OAuth

* [[SlideShare] OAuth with Restful Web Services](http://www.slideshare.net/vinayhulgar/oauth-with-restful-web-services)

* [[GitHub] smarx / othw](https://github.com/smarx/othw) - OAuth 2 the Hard Way - calling the Dropbox API without any Dropbox or OAuth libraries

* [JAX-RS: OAuth2 | Apache CXF](https://cxf.apache.org/docs/jax-rs-oauth2.html)

* [The OAuth Bible](http://oauthbible.com)

--

* [Beer Locker: Building a RESTful API with Node - OAuth2 Server | Scott Smith](http://scottksmith.com/blog/2014/07/02/beer-locker-building-a-restful-api-with-node-oauth2-server/)

* [OAuth2 - uma abordagem para segurança de aplicações e APIs REST | InfoQ Br](http://www.infoq.com/br/presentations/oauth2-uma-bordagem-para-seguranca) - O OAuth2 é um framework de autorização aberto, poderoso e flexível que pode ser usado para proteção de aplicações e APIs REST. Com OAuth2 é possível prover um mecanismo padronizado para Identity Management, em que todos os componentes do sistema possam interagir de um modo seguro, usualmente onde uma aplicação cliente necessita de acesso a um recurso protegido, agindo no lugar do usuário. 2014/09/26

--

* [[GitHub] globocom / oauth2u](https://github.com/globocom/oauth2u) - OAuth 2 server implementation

* [[GitHub] lucadegasperi / oauth2-server-laravel](https://github.com/lucadegasperi/oauth2-server-laravel) - A OAuth 2.0 bridge for Laravel and Lumen


### Two-Factor Authentication

* [From Theory to Practice: Adding Two-Factor Authentication to Node.js | Auth0 ](https://auth0.com/blog/2015/08/20/from-theory-to-practice-adding-two-factor-to-node-dot-js/) - 2015/08/20


## SAML

*Definição:* _SAML_ - Security Assertion Markup Language


* [Configuring Single Sign-On with Web Browsers and HTTP Clients](http://docs.oracle.com/cd/E23943_01/web.1111/e13707/saml.htm#i1112531)

* [Configuring Single Sign-On using SAML in WebLogic Server 9.2](http://www.oracle.com/technetwork/articles/entarch/sso-with-saml-099684.html)

* [SAML Single Sign-On Service for Google Apps](https://developers.google.com/google-apps/sso/saml_reference_implementation)

* [[SlideShare] Introduction to SAML 2.0](http://www.slideshare.net/koivimik/introduction-to-saml-20)

* [Spring Security - SAML Extension](http://static.springsource.org/spring-security/site/extensions/saml/index.html)

  * [[GitHub] SpringSource/spring-security-saml](https://github.com/SpringSource/spring-security-saml) - SAML extension for the Spring Security project


## WS-Trust

* [Using WS-Trust for token transformation | IBM developerWorks](http://www.ibm.com/developerworks/websphere/library/techarticles/1003_chades/1003_chades.html) - WS-Trust provides a standard way to send security token requests to a Security Token Service (STS). This specification can be used to manage token transformation when crossing the various security boundaries of the information system. This article introduces WS-Trust concepts and its basic use to manage token exchange.

## Identity Server

* [Thinktecture IdentityServer](http://thinktecture.github.com/) - IdentityServer is a light-weight, .NET based security token service that supports various protocols and token formats

* [AuthBridge](http://authbridge.auth10.com/) is a server written in ASP.NET/C# using [WIF](http://msdn.microsoft.com/en-us/security/aa570351.aspx) and [DotNetOpenAuth](http://www.dotnetopenauth.net/),  that speaks WS-Federation and SAML tokens on one side and OpenID,  OAuth, WS-Federation or any other protocol on the identity provider

# CAS

*Definição:* _CAS_ - Central Authentication Service

* [[GitHub] apereo / cas](https://github.com/apereo/cas) - Apereo CAS - Enterprise Single Sign On for all earthlings and beyond.

* [[YouTube] CAS in 10 Minutes - Jasig's Central Authentication Service (CAS) Single Sign-On Open Source](https://www.youtube.com/watch?v=wx98IaaBLfw)

* [Configurando SSO no Spring Security com o JaSig CAS](http://sfohart.blogspot.com.br/2011/04/single-sign-on-configurando-sso-no.html) | [Youtube](https://www.youtube.com/watch?v=0r2N083pgeI)

## Microsoft ADFS / Microsoft ACS / SWT

*Definições:*

_STS_ - Security Token Service

_SWT_ - Simple Web Token

_ADFS_ - Active Directory Federation Services

--

* [Active Directory Federation Services - ADFS 2.0](http://technet.microsoft.com/library/dd727958.aspx)

  * [ADFS 2.0 Step-by-Step Guide: Federation with Oracle Identity Federation](http://technet.microsoft.com/en-us/library/ff849212.aspx)

  * [Securing REST Services](http://msdn.microsoft.com/en-us/library/hh446531.aspx)

  * [[PDF] ADFS Step-by-Step Guide - Bandwidthco Computer Security](http://www.bandwidthco.com/whitepapers/os/windows/ad/ADFS%20Step-by-Step%20Guide.pdf)

  * [Configuring ADFS Servers for Success and Failure Auditing of User Logon Events | Agile IT](http://www.agileit.com/news/configuring-adfs-servers-for-success-and-failure-auditing-of-user-logon-events/)

* [How To Request SWT Token From ACS And How To Validate It At The REST WCF Service Hosted In Windows Azure](http://blogs.msdn.com/b/alikl/archive/2011/06/05/how-to-request-swt-token-from-acs-and-how-to-validate-it-at-the-rest-wcf-service-hosted-in-windows-azure.aspx)

* [ACS SAML / ADFS v2 Sample](http://blogs.msdn.com/b/justinjsmith/archive/2009/11/14/acs-saml-adfs-v2-sample.aspx)

* [SAML Token Provider](http://msdn.microsoft.com/en-us/library/aa355062.aspx)

* Claim based Authentication [Part 1](http://www.codeproject.com/Articles/268236/Claim-based-Authentication-and-WIF) / [Part 2](http://www.codeproject.com/Articles/278940/Claim-based-Authentication-and-WIF-Part-2) / [Part 3](http://www.codeproject.com/Articles/290606/Claim-based-Authetication-WIF-Part-3)

* [Token Service](http://www.syfuhs.net/category/Token-Service.aspx)

* [Requesting a Token from ADFS 2.0 using WS-Trust with Username and Password](http://leandrob.com/2012/04/requesting-a-token-from-adfs-2-0-using-ws-trust-with-username-and-password/)

* [Request a token from ADFS using WS-Trust from iOS, Objective-C, IPhone, IPad, Android, Java, Node.js or any platform or language](http://leandrob.com/2012/02/request-a-token-from-adfs-using-ws-trust-from-ios-objective-c-iphone-ipad-android-java-node-js-or-any-platform-or-language/)

* [ADFS WS-Trust client for Node.js](http://leandrob.com/2012/08/adfs-ws-trust-client-for-node-js/)

* [Active Directory (ADFS) to Authenticate Node.js Apps in MS Azure](http://www.newvem.com/using-active-directory-federation-services-adfs-to-authenticate-authorize-node-js-apps-in-windows-azure/)

* [Convert SAML token to SWT token using ACS](http://blogs.microsoft.co.il/blogs/applisec/archive/2011/11/16/convert-saml-token-to-swt-token-using-acs.aspx)

* [Windows Identity Foundation Simplifies User Access for Developers](http://msdn.microsoft.com/en-us/security/aa570351.aspx)

* [Securing Web API REST services with ADFS and ACS](http://www.mexia.com.au/securing-web-api-rest-services-with-adfs-and-acs/)


* [Troubleshooting ADFS 2.0 | DZone](http://dotnet.dzone.com/articles/troubleshooting-adfs-20)

* [Entries in ADFS v2 | The Identity Guy](http://www.theidentityguy.com/articles/tag/adfs-v2)

* [ADFS with Non-Standard HTTPS Port | Certified Security Solutions](http://www.css-security.com/blog/adfs-with-non-standard-https-port/)
