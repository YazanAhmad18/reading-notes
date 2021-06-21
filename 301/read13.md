# In your own words, describe what each group of status code represents:
## 100’s =This interim response indicates that everything so far is OK and that the client should continue the request, or ignore the response if the request is already finished
## 200’s =These are the success codes. They tell the client that its request was accepted
## 300’s =These are redirection codes. Uesd to tell the client that the resource they are requesting isn’t available at the expected location anymore.
## 400’s =These are the client error codes. They are all about invalid requests a client sent to a server. There are several causes to this, timeouts, wrong URI, missing authentication
## 500’s =These are the server error codes. they indicate problems with overwhelmed servers or unreachable servers behind proxies, but sometimes they can be directly related to client requests that trigger error exceptions on the server

# What is a status code 202?
## Often used for asynchronous processing. This code tells the client that the request was valid, but its processing will finish sometime in the future

# What is a status code 308?
## This tells the client to use another URL to access the resource and not use the current URL anymore

# What code would you use if an update didn’t return data to a client?
## 204 No Content

# What code would you use if a resource used to exist but no longer does?
## 410 Gone 
# What is the ‘Forbidden’ status code?
## 403 Forbidden - The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.

# Why do we need to pull our MongoDB database string out of our server and put it into our .env?

## Because mongoDB strings inside the application and when we deploy the application we use something is not our localhost

# What is middleware?
## it's code that run when the server get the request but before it gets passed to your route

# What does app.use(express.json()) do?
## Let our server accept JSON as a body instead of post element

# What does the /:id mean in a route?
## It's a parameter that we can access by typing in request

# What is the difference beween PUT and PATCH?
## PUT update the entirety of a resource, while PUT update only what the user give it.

# How do you make a defalut value in a schema?
## by using default and set the value that you want

# What does a 500 error status code mean?
## It means that there is an error at our server, not related to the user or client.

# What is the difference between a status 200 and a status 201?
## status code 200 means everything was successful, while status code 201 mean a successful creation of a resource.
