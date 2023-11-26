### Goals and limitations of the project

The main goal of the project is to get familiar with communication using Http Api as well as introduction to testing process automation using Postman.
Http Api, which I've tested is available and described at https://www.purgomalum.com/
Purgomalum involves searching for and removing unwanted words contained in a previously created list of banned words.
Within the project I chose several ednpoints (the most interesting in my opinion) and wrote various types of tests in Postman.
HTTP Api ensures communication between two systems using HTTP protocol. One system (server) exposes endpoints, which can be used by another system or systems (clients). Every endpoint description consist of url address, HTTP method, request parameters, request expected content and response format. In addition HTTP request can contain other elements like headers or cookies.
What can we send in HTTP request? Actually everything :) We can send data in JSON or XML format, files or just simple string. What does HTTP response consist of? Essentially it contains HTTP status, which indicates whether out request has been processed successfully. Response content can contain various type of data, cookies and headers, as does HTTP request content.
HTTP Api is widely used in mircoservices architecture as well as in classical communication between client and server.

### Disify HTTP Api tests collection.
I divided tests into two folders:
* Purgomalu
* Purgomalum converting to xml + error handling

Inside every folder I created several test cases, which check HTTP response correctness as well as non-functional aspects like response time. Generally tests check whether Disify HTTP Api works as intended (at least according to documentation)
