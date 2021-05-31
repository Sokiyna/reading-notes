## Which HTTP Status Code to Use for Every CRUD App

*100’s =* it is about telling the client that its request will fail before they start sending the body.
*200’s =* the code met all validation requirements at the time of sending.
*300’s =* They tell the client that the resource they are requesting isn’t available at the expected location anymore.
*400’s =* There are several causes to this, timeouts, wrong URI, missing authentication, etc.
*500’s =* These are the server error codes, These errors can be temporary or permanent. 


*What is a status code 202?*

Accepted - Often used for asynchronous processing. This code tells the client that the request was valid, but its processing will finish sometime in the future. The response body should include an URL to the finished resource with some information about when it will be available, or an URL to some monitoring endpoint that tells the client when the resource is available.

*What is a status code 308?*

This tells the client to use another URL to access the resource and not use the current URL anymore. It’s helpful when we have multiple endpoints for one resource, but don’t want to implement reading from all of them.

*What code would you use if an update didn’t return data to a client?*

204 No Content.

*What code would you use if a resource used to exist but no longer does?*

he client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.

*Why do we need to pull our MongoDB database string out of our server and put it into our .env?*

because when we deploy the server we have to change it to another MongoDB database.

*What is middleware?*

 functions that execute during the lifecycle of a request to the Express server.

 *What does app.use(express.json()) do?*

 recognize the incoming Request Object as a JSON Object.

 *What does the /:id mean in a route?*

 it means that it is a parameter and you can access it by using req.params.

 *What is the difference beween PUT and PATCH?*

 PUT: to update all of the object
PATCH: to update only what you want to update






