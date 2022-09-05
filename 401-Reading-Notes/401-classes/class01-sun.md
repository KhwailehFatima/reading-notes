# Reading Notes

* What's the difference between PUT and PATCH?

The main difference between PUT and PATCH requests is witnessed in the way the server processes the enclosed entity to update the resource identified by the Request-URI. When making a PUT request, the enclosed entity is viewed as the modified version of the resource saved on the original server, and the client is requesting to replace it. However, with PATCH, the enclosed entity boasts a set of instructions that describe how a resource stored on the original server should be partially modified to create a new version.

The second difference is when it comes to idempotency. HTTP PUT is said to be idempotent since it always yields the same results every after making several requests. On the other hand, HTTP PATCH is basically said to be non-idempotent. However, it can be made to be idempotent based on where it is implemented

* Provide links to 3 services or tools that allow you to "mock" an API for development like json-server
1) Nock
2) MockServer
3) Beeceptor
4) Mockoon

* Compare and contrast Swagger and APIDoc.js 1 Which HTTP status codes should be sent with each type of (un)successful API call?


* Compare and contrast SOAP and ReST

Representational state transfer (REST) is a set of architectural principles. 

Simple object access protocol (SOAP) is an official protocol maintained by the World Wide Web Consortium (W3C).

 The main difference is that SOAP is a protocol while REST is not. Typically, an API will adhere to either REST or SOAP, depending on the use case and preferences of the developer.

 # Document the following Vocabulary Terms

 ## Term
 Web Server: is software and hardware that uses HTTP (Hypertext Transfer Protocol) and other protocols to respond to client requests made over the World Wide Web.
 
 Express: is a node js web application framework that provides broad features for building web and mobile applications.

 Routing: is a process in which a user is directed to different pages based on their action or request.

WRRC: is a web request response cycle.


Which 3 things had you heard about previously and now have better clarity on?
1- Express and how it is Work 2- Routing 3- middleware

Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
1- More about Routing 2- More about TDD 3- more about CI/CD 3- More about State Management


What are you most excited about trying to implement or see how it works?
Express