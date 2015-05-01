Spring with Swagger example
=================
This project is a simple example of integration of Swagger with Spring application (with Jersey 2).

About
-----
This project was created to enhance my microseries on integration of Swagger with Jersey 2 in Spring application. For further information check out following posts from series called Spring Rest API with Swagger:
 
1. [Integration and configuration](http://jakubstas.com/spring-jersey-swagger-configuration)
2. [Creating documentation](http://jakubstas.com/spring-jersey-swagger-create-documentation)
3. [Exposing documentation](http://jakubstas.com/spring-jersey-swagger-exposing-documentation)
4. [Fine-tuning exposed documentation](http://jakubstas.com/spring-jersey-swagger-fine-tuning-exposed-documentation)

Try it out!
-----------
* **Do it yourself** and build and deploy it using your favourite IDE
* **Use embedded Jetty** and run it right away with `mvn jetty:run`

Check following URLs (running this example on your localhost):

1. [Swagger API listing](http://localhost:8080/SpringWithSwagger/rest/api-docs/)
2. [Swagger API documentation](http://localhost:8080/SpringWithSwagger/rest/api-docs/products)
3. [Swagger UI](http://localhost:8080/SpringWithSwagger/apidocs/)

Notes!
-----------

Use jetty version 2.6 to make it work for Java 6. Version 2.12 is tied up to Java 7.

http://jersey.576304.n2.nabble.com/Jersey-2-7-giving-up-on-jdk-1-6-td7582041.html
