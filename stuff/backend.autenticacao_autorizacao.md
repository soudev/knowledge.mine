# Autenticação & Autorização 

* [Authentication for Single Page Apps | madhatted.com](http://madhatted.com/2014/6/17/authentication-for-single-page-apps)


## OAuth

* [[SlideShare] OAuth with Restful Web Services](http://www.slideshare.net/vinayhulgar/oauth-with-restful-web-services)

* [[GitHub] smarx / othw](https://github.com/smarx/othw) - OAuth 2 the Hard Way - calling the Dropbox API without any Dropbox or OAuth libraries

* [JAX-RS: OAuth2 | Apache CXF](https://cxf.apache.org/docs/jax-rs-oauth2.html)

* [The OAuth Bible](http://oauthbible.com)


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

* [JaSig CAS](http://www.jasig.org/cas/) OpenSource / Free | [GitHub : code](https://github.com/Jasig/cas)

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



