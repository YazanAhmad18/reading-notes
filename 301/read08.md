# What does REST stand for?
## REST is an architectural style for building distributed systems based on hypermedia,REST is independent of any underlying protocol and is not necessarily tied to HTTP

# REST APIs are designed around a ____.?
## resources

# What is an identifer of a resource? Give an example.
## https://adventure-works.com/orders/1

# What are the most common HTTP verbs?
## The most common operations are GET, POST, PUT, PATCH, and DELETE.

# What should the URIs be based on?
## on nouns (the resource) and not verbs (the operations on the resource).

# Give an example of a good URI.?
## https://adventure-works.com/orders 

# What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
## try to avoid "chatty" web APIs that expose a large number of small resources

# What status code does a successful GET request return?
## A successful GET method typically returns HTTP status code 200 (OK)
# What status code does an unsuccessful GET request return?
## the method should return 404 (Not Found).

# What status code does a successful POST request return?
## the method can return HTTP status code 200 and include the result of the operation in the response body

# What status code does a successful DELETE request return?
## the web server should respond with HTTP status code 204, indicating that the process has been successfully handled
