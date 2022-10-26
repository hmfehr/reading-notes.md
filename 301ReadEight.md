# [API Design Best Practices](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)


### What does REST stand for?
* REpresentational State Transfer

### REST APIs are designed around a ____.
* REST APIs are designed around resources, which are any kind of object, data, or service that can be accessed by the client.


### What is an identifier of a resource? Give an example.
* A resource has an identifier, which is a URI that uniquely identifies that resource. For example, the URI for a particular customer order might be:
* ex: https://adventure-works.com/orders/1


### What are the most common HTTP verbs?
* The most common operations are GET, POST, PUT, PATCH, and DELETE. 

### What should the URIs be based on?
* Clients interact with a service by exchanging representations of resources. Many web APIs use JSON as the exchange format. For example, a GET request to the URI listed above might return this response body:

### Give an example of a good URI.
* URI `/add?operand1=99&operand2=1` would return a response message with the body containing the value 100. However, only use these forms of URIs sparingly.

### What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
* The more requests, the bigger the load. Therefore, try to avoid "chatty" web APIs that expose a large number of small resources. Such an API may require a client application to send multiple requests to find all of the data that it requires. Instead, you might want to denormalize the data and combine related information into bigger resources that can be retrieved with a single request.

### What status code does a successful `GET` request return?
* A successful GET method typically returns HTTP status code 200 (OK).

### What status code does an unsuccessful `GET` request return?
* If the resource cannot be found, the method should return 404 (Not Found).

### What status code does a successful `POST` request return?
* If a POST method creates a new resource, it returns HTTP status code 201 (Created). The URI of the new resource is included in the Location header of the response. The response body contains a representation of the resource.

### What status code does a successful `DELETE` request return?
* If the delete operation is successful, the web server should respond with HTTP status code 204 (No Content), indicating that the process has been successfully handled, but that the response body contains no further information
