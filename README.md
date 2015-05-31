# WebSec Vulnerable BBCode Web Application

This project defines a very simple Spring Web application that lets
users markup input with
[BBCode](https://en.wikipedia.org/wiki/BBCode). The BBCode
implementation is [KefirBB](http://kefirsf.org/kefirbb/).

The application is intended for use in the lab of my Web Security - so
expect security issues!

## Build & Install

1. Make sure you have JDK 7 or newer as well as Maven 3 installed.
2. In the top level directory, run `mvn clean install`.
3. Deploy target/BBCode.war into a Java Web container (Tomcat, Jetty, Glassfish, ...)

