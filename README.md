# WebSec Vulnerable BBCode Web Application

This project defines a very simple Spring Web application that lets
users markup input with
[BBCode](https://en.wikipedia.org/wiki/BBCode). The BBCode
implementation is [KefirBB](http://kefirsf.org/kefirbb/).

The application is intended for use in the lab of my Web Security course - so
expect security issues, I left them in on purpose!!

## Build & Install

1. Make sure you have JDK >= 7 installed
   (Both OpenJDK and Oracle's JDK should work.)
2. In the top level directory, run `./mvnw clean install`.
   (On its first run, this will also download Maven.)
3. Run the application in its embedded Tomcat by calling
   `java -jar target/BBCode.war`. Alternatively, you can also
   deploy target/BBCode.war into a standalone Java Web container
   (Tomcat, Jetty, Glassfish, ...) of your choice.

