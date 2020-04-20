# Chatie Restful API

[![OpenAPI Specification Schema Validation](https://online.swagger.io/validator?url=https://raw.githubusercontent.com/Chatie/api/master/spec/swagger.yaml)](https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/Chatie/api/master/spec/swagger.yaml)

Chatie Restful API, Powered by OpenAPI Specifiction(f.k.a. Swagger)

[Swagger Editor Online](http://editor.swagger.io/#/?import=https://raw.githubusercontent.com/Chatie/api/master/spec/swagger.yaml)

## Code Generator

We can generate both server and client code from OpenAPI Specification file.

### Server

```shell
cd server
../node_modules/.bin/yo swaggerize --framework=express --apiPath=../spec/swagger.yaml
```

### Client

```shell
```

## Spec-Driven Development

- [What is Spec Driven Development](https://www.mikestowe.com/blog/2014/11/what-is-spec-driven-development.php)
- [Building Your API for Longevity, Part 1: Spec-Driven Development](https://www.nginx.com/blog/building-api-for-longevity-spec-driven-development/)

### See Also

- [OpenAPI/Swagger-generated API Reference Documentation](https://redocly.github.io/redoc/)
- [Design Drivin API Development](http://www.slideshare.net/sofj/design-driven-api-development)
- [OpenAPI Initiative](https://www.openapis.org/)
- [Swagger Server Sample 3](https://github.com/BigstickCarpet/swagger-server/tree/master/samples/sample3)
- [Swaggerize Examples](https://github.com/subeeshcbabu/swaggerize-examples)
- [The Anatomy of a JSON Web Token](https://scotch.io/tutorials/the-anatomy-of-a-json-web-token)
- [Authenticate a Node.js API with JSON Web Tokens](https://scotch.io/tutorials/authenticate-a-node-js-api-with-json-web-tokens)
- [An Introduction to OAuth 2](https://www.digitalocean.com/community/tutorials/an-introduction-to-oauth-2)
- [Design Driven Development](http://www.slideshare.net/henrydjacob/design-driven-development)
- [Intro to RAML - API Spec Driven Development](http://www.hksilicon.com/articles/1082744)

#### gRPC

- [Introduction to gRPC: A general RPC framework that puts mobile and HTTP/2 first by Mete Atamel](https://www.youtube.com/watch?v=kUz2zjkKxFg)

## History

### master

### 0.0.1 Feb 19, 2017

Initial version

- Add [Swagger Online Editor](http://editor.swagger.io/#/?import=https://raw.githubusercontent.com/Chatie/api/master/spec/swagger.yaml)
- Add [Redocly Online Viewer](https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/Chatie/api/master/spec/swagger.yaml)
- Add [OpenAPI Specification Schema Validation](https://online.swagger.io/validator?url=https://raw.githubusercontent.com/Chatie/api/master/spec/swagger.yaml)

## Author

[Huan LI](https://github.com/huan) ([李卓桓](http://linkedin.com/in/zixia)),
Tencent TVP of Chatbot, \<zixia@zixia.net\>

[![Profile of Huan LI (李卓桓) on StackOverflow](https://stackexchange.com/users/flair/265499.png)](https://stackexchange.com/users/265499)

## Copyright & License

- Code & Docs © 2018-now Huan LI \<zixia@zixia.net\>
- Code released under the Apache-2.0 License
- Docs released under Creative Commons
