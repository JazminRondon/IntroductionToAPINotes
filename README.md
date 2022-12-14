# IntroductionToAPINotes
Notes from chapter 1-6

APIs (application programming interfaces)
An API is the tool that makes a website's data
digestible for a computer

When two systems (websites, desktops, smartphones) link up through
an API, we say they are "integrated."


Server: A powerful computer that runs an API
 • API: The "hidden" portion of a website that is meant for computer
consumption
 • Client: A program that exchanges data with a server through an
API 


A computer protocol is an accepted set of rules that govern
how two computers can speak to each other

Communication in HTTP centers around a concept called the RequestResponse Cycle. The client sends the server a request to do something.
The server, in turn, sends the client a response saying whether or not
the server could do what the client asked. 

To make a valid request, the client needs to include four things:
 1 URL (Uniform Resource Locator) 1
 2 Method
 3 List of Headers
 4 Body
 
 The four methods most commonly seen in APIs are:
 • GET - Asks the server to retrieve a resource
 • POST - Asks the server to create a new resource
 • PUT - Asks the server to edit/update an existing resource
 • DELETE - Asks the server to delete a resource
 
 Send a GET request without any body data.
 2 Send a POST request and type your favorite kind of pizza in the
body field.
 3 Send a PUT request and type a new ingredient to add to your
pizza in the body field.
 4 Send a DELETE request without any body data. 
 
 
 Headers provide meta-information about a request
 
 These four pieces — URL, method, headers, and body — make up a
complete HTTP request

 HTTP responses have
a very similar structure to requests. The main difference is that instead
of a method and a URL, the response includes a status code-----Status codes are three-digit numbers that each have a unique meaning.
When used correctly in an API, this little number can communicate a lot
of info to the client.

• Request - consists of a URL (http://…), a method (GET, POST, PUT,
DELETE), a list of headers (User-Agent…), and a body (data).
 • Response - consists of a status code (200, 404…), a list of headers,
and a body.

JSON: JavaScript Object Notation
 • Object: a thing or noun (person, pizza order...)
 • Key: an attribute about an object (color, toppings...)
 • Value: the value of an attribute (blue, pepperoni...)
 • Associative array: a nested object
 • XML: Extensible Markup Language 


The key terms we learned were:
 • Authentication: process of the client proving its identity to the
server
 • Credentials: secret pieces of info used to prove the client's
identity (username, password...)
 • Basic Auth: scheme that uses an encoded username and
password for credentials
 • API Key Auth: scheme that uses a unique key for credentials
 • Authorization Header: the HTTP header used to hold credentials
