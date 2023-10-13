# Spring-Security
* This framework targets two major areas of application are authentication and authorization. 
* Authentication is the process of knowing and identifying the user that wants to access.
* Authorization is the process to allow authority to perform actions in the application.
* Spring Security framework supports wide range of authentication models. These models either provided by third parties or framework itself.

* Spring Security Features
  * LDAP (Lightweight Directory Access Protocol)
  * Single sign-on
  * JAAS (Java Authentication and Authorization Service) LoginModule
  * Basic Access Authentication
  * Digest Access Authentication
  * Remember-me
  * Web Form Authentication
  * Authorization
  * Software Localization
  * HTTP Authorization
Spring Project Modules
In Spring Security 3.0, the Security module is divided into separate jar files. The purpose was to divide jar files based on their functionalities, so, the developer can integrate according to their requirement.

It also helps to set required dependency into pom.xml file of maven project.

# The following are the jar files that are included into Spring Security module.

spring-security-core.jar
spring-security-remoting.jar
spring-security-web.jar
spring-security-config.jar
spring-security-ldap.jar
spring-security-oauth2-core.jar
spring-security-oauth2-client.jar
spring-security-oauth2-jose.jar
spring-security-acl.jar
spring-security-cas.jar
spring-security-openid.jar
spring-security-test.jar

## Remoting - spring-security-remoting.jar
This jar is used to integrate security feature into the Spring remote application. We don't need it until or unless we are creating remote application. All the classes and interfaces are located into org.springframework.security.remoting package.

##  Web - spring-security-web.jar
This jar is useful for Spring Security web authentication and URL-based access control. It includes filters and web-security infrastructure.

All the classes and interfaces are located into the org.springframework.security.web package.

## Config - spring-security-config.jar
This jar file is required for Spring Security configuration using XML and Java both. It includes Java configuration code and security namespace parsing code. All the classes and interfaces are stored in org.springframework.security.config package.

## LDAP - spring-security-ldap.jar
This jar file is required only if we want to use LDAP (Lighweight Directory Access Protocol). It includes authentication and provisioning code. All the classes and interfaces are stored into org.springframework.security.ldap package.

## OAuth 2.0 Core - spring-security-oauth2-core.jar
This jar is required to integrate Oauth 2.0 Authorization Framework and OpenID Connect Core 1.0 into the application. This jar file includes the core classes for OAuth 2.0 and classes are stored into the org.springframework.security.oauth2.core package.

## OAuth 2.0 Client - spring-security-oauth2-client.jar
This jar file is required to get client support for OAuth 2.0 Authorization Framework and OpenID Connect Core 1.0. This module provides OAuth login and OpenID client support. All the classes and interfaces are available from org.springframework.security.oauth2.client package.

## OAuth 2.0 JOSE - spring-security-oauth2-jose.jar
It provides Spring Security's support for the JOSE (Javascript Object Signing and Encryption) framework. The JOSE framework provides methods to establish secure connection between clients. It contains following collection of specifications:

JWT (JSON Web Token)
JWS (JSON Web Signature)
JWE (JSON Web Encryption)
JWK (JSON Web Key)
All the classes and interfaces are available into these two packages:

org.springframework.security.oauth2.jwt and org.springframework.security.oauth2.jose.

## ACL - spring-security-acl.jar
This jar is used to apply security to domain object in the application. We can access classes and code from the org.springframework.security.acls package.

## CAS - spring-security-cas.jar
It is required for Spring Security?s CAS client integration. We can use it to integrate Spring Security web authentication with CAS single sign-on server. The source code is located into org.springframework.security.cas package.

## OpenID - spring-security-openid.jar
This jar is used for OpenID web authentication support. We can use it to authenticate users against an external OpenID server. It requires OpenID4Java and top level package is org.springframework.security.openid.

## Test - spring-security-test.jar
This jar provides support for testing Spring Security application.
