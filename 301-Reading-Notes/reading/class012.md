# Reading

[Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

### In your own words, describe what each group of status code represents:

100’s = informational status code.
200’s = the success code 
300’s =the redirection codes
400’s = the client error codes
500’s = the server error code

### What is a status code 202?
Is used for synchronous processing. it tells the client that the request is valid, but its processing will finish in the future
### What is a status code 308?
This tells the client to use another URL to access the resource and not use the current URL anymore. It’s helpful when we have multiple endpoints for one resource, but don’t want to implement reading from all of them.

### What code would you use if an update didn’t return data to a client?
204 No Content
### What code would you use if a resource used to exist but no longer does?
301

### What is the ‘Forbidden’ status code?
403 Forbidden - The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.


# Videos
Build A REST API With Node.js, Express, & MongoDB - Quick - First 20 minutes

* Why do we need to pull our MongoDB database string out of our server and put it into our .env? 
for security
* What is middleware?
it allows for side effects to be run without blocking state updates

* What does app.use(express.json()) do?
to accept json as body in my code. it parses incoming JSON requests and puts the parsed data in req
* What does the /:id mean in a route?
parameter
* What is the difference between PUT and PATCH?
PUT is a method of modifying resource where the client sends data that updates the entire resource .                                     	PATCH is a method of modifying resources where the client sends partial data that is to be updated without modifying the entire data.
* How do you make a default value in a schema?
* What does a 500 error status code mean?
the server encountered an unexpected condition that prevented it from fulfilling the request.
* What is the difference between a status 200 and a status 201?
The 200 status code is by far the most common returned. It means, simply, that the request was received and understood and is being processed. A 201 status code indicates that a request was successful and as a result, a resource has been created (for example a new page).
