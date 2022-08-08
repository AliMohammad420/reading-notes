# Reading 

**Status Codes Based On REST Methods**

100’s = informational
200’s = The request was fulfilled.
300’s = redirection
400’s = bad request
500’s = server error

What is a status code 202?<br>
The HyperText Transfer Protocol (HTTP) 202 Accepted response status code indicates that the request has been accepted for processing, but the processing has not been completed; in fact, processing may not have started yet. The request might or might not eventually be acted upon, as it might be disallowed when processing actually takes place.<br>
What is a status code 308?<br>
The HyperText Transfer Protocol (HTTP) 308 Permanent Redirect redirect status response code indicates that the resource requested has been definitively moved to the URL given by the Location headers. A browser redirects to this page and search engines update their links to the resource (in 'SEO-speak', it is said that the 'link-juice' is sent to the new URL).<br>
What code would you use if an update didn’t return data to a client?<br>
If an existing resource is modified, either the 200 (OK) or 204 (No Content) response codes SHOULD be sent to indicate successful completion of the request.<br>
What code would you use if a resource used to exist but no longer does?<br>
The HyperText Transfer Protocol (HTTP) 410 Gone client error response code indicates that access to the target resource is no longer available at the origin server and that this condition is likely to be permanent.<br>
What is the ‘Forbidden’ status code?<br>
Answer: The HTTP 403 Forbidden client error status response code indicates that the server understood the request but refuses to authorize it.<br>

# Video

**Build A REST API With Node.js, Express, & MongoDB - Quick **

1) you will retrieve your database deployment's connection string. Whitelist your IP address to allow access to your Atlas cluster.
2) Middleware is a type of computer software that provides services to software applications beyond those available from the operating system
3) It parses incoming JSON requests and puts the parsed data in req.
4) it's a dynamic route, so req.params.id will be whatever comes after summary/ in that specific request. 
5) PUT is a method of modifying resource where the client sends data that updates the entire resource . PATCH is a method of modifying resources where the client sends partial data that is to be updated without modifying the entire data
6) Your schemas can define default values for certain paths. If you create a new document without that path set, the default will kick in.
7) the server encountered an unexpected condition that prevented it from fulfilling the request.
8) The 200 status code is by far the most common returned. It means, simply, that the request was received and understood and is being processed. A 201 status code indicates that a request was successful and as a result, a resource has been created 
