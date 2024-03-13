# RestTemplate
Consuming a RESTful Web Service
Creating an application that consumes a RESTful web service.

Before you can do so, you need a source of REST resources. An example of such a service is provided at https://github.com/spring-guides/quoters. You can run that application in a separate terminal and access the result at http://localhost:8080/api/random. That address randomly fetches a quotation about Spring Boot and returns it as a JSON document. Other valid addresses include http://localhost:8080/api/ (for all the quotations) and http://localhost:8080/api/1 (for the first quotation), http://localhost:8080/api/2 (for the second quotation), and so on (up to 10 at present).
