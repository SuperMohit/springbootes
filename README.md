# Spring Boot Elasticsearch Demo Application

In this, we are going to see how to configure Elasticsearch with Spring Boot application. We will be using Spring Boot 1.3.2.Release. It comes with Elasticsearch 1.5.2. If you want to use another version, you can do it by defining following in your build.gradle. 

Caution: Be aware Spring Boot 1.3.2.Release is compatible with Elasticsearch 1.5.2. If you use another version, it may cause compatibility issues[more details here](http://docs.spring.io/spring-boot/docs/current/reference/html/howto-build.html#howto-customize-dependency-versions).

```
  buildscript {
  	ext['elasticsearch.version'] = '1.7.4'
  }

```
