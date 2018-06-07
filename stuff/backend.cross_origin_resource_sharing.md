# Cross Origin Resource Sharing (CORS)

* [CORS | the frontendian](https://frontendian.co/cors) - (2018/06/03) is subject tinged with dread for many web developers. Like tales of a mythical sea beast, every developer has a story to tell about the day CORS seized upon one of their web requests, dragging it down into the inexorable depths, never to be seen again.

---

**Request Variables**

```
This middleware allows cross-domain XHR using the html5 postMessage API.

Access-Control-Allow-Origin: http://foo.example
Access-Control-Allow-Methods: POST, GET, OPTIONS, PUT, DELETE

XS_SHARING_ALLOWED_HEADERS = ['Content-Type', 'X-Requested-With']{code}
```


* [Middlware to allow's your django server to respond appropriately to cross domain XHR](https://gist.github.com/barrabinfc/426829) - python code

* [The JSONP Hack | Unicode Girl](http://www.unicodegirl.com/jsonp-hack.html) -  In this post we try to understand how the JSONP hack works, and we write our own version of jQuery's getJSON.

* [[GitHub] jpillora / xdomain](https://github.com/jpillora/xdomain) - a JQuery plugin to do cross-domain AJAX requests via postMessage

* [Cross Domain Javascript, Lessons Learned | Software Alchemist](http://avalanche123.com/blog/2011/10/10/cross-domain-javascript-lessons-learned/)

---

* [JSONProxy](http://jsonp.jit.su/) - Enables cross-domain requests to any JSON API | [[GitHub] afeld / jsonp](https://github.com/afeld/jsonp) - A simple JSON proxy

* [Dug.js — A JSONP to HTML Script | Rog.ie](http://rog.ie/blog/dugjs-a-jsonp-to-html-script)


# Node.js

## Express

> express 4.x

```javascript
var express = require('express');
var app = express();
...
app.use(function (req, res, next) {
  res.setHeader('Access-Control-Allow-Origin', '*');
  res.setHeader('Access-Control-Allow-Methods', 'GET, POST, OPTIONS, PUT, PATCH, DELETE');
  res.setHeader('Access-Control-Allow-Headers', 'Origin, X-AUTH-TOKEN, X-Requested-With, Content-Type, Accept');
  next();
});

app.options('*', function (req, res) {
  res.setHeader('Access-Control-Allow-Origin', '*');
  res.setHeader('Access-Control-Allow-Methods', 'GET, POST, OPTIONS, PUT, PATCH, DELETE');
  res.setHeader('Access-Control-Allow-Headers', 'Origin, X-AUTH-TOKEN, X-Requested-With, Content-Type, Accept');
  res.send(200);
});
...
```

# Java

* [CORS Filter](http://software.dzhuvinov.com/cors-filter.html)

  * [StackOverflow Question](http://stackoverflow.com/questions/11096195/spring-and-http-options-request/16021886#16021886)

  * [[Bitbucket] CORS Filter Git repo](https://bitbucket.org/thetransactioncompany/cors-filter)

  * [CORS Filter : Configuration](http://software.dzhuvinov.com/cors-filter-configuration.html)

  ```xml
  <dependency>
    <groupId>com.thetransactioncompany</groupId>
    <artifactId>cors-filter</artifactId>
    <version>1.3.2</version>
  </dependency>
  ```


## Jersey

* [Cross Origin Resource Sharing (CORS) Web Service Endpoints with JSON Using Jersey](http://www.iceycake.com/2012/06/cross-origin-resource-sharing-cors-json-web-service-endpoints-using-jersey/)

* [CORS-Compliant REST API with Jersey and ContainerResponseFilter](http://blog.usul.org/cors-compliant-rest-api-with-jersey-and-containerresponsefilter/)

## Spring

* [[Gist] keesun / CorsInterceptor.java](https://gist.github.com/keesun/2245179) - CORS Spring Interceptor Demo

* [[Gist] kdonald / CorisFilter.java](https://gist.github.com/kdonald/2232095) - Basic Cross Origin Resource Sharing (CORS) support

* [Spring MVC 3 enable Cross Origin Resource Sharing - 24 Aug 2012](http://vraidsys.com/2012/08/spring-mvc-3-enable-cross-origin-resource-sharing/)
