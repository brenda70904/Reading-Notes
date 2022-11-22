### In your own words, describe what each group of status code represents:
100’s = telling the client it’s working on it 
200’s = success code
300’s = redirection code. 
400’s = error code with the request is invalid. 
500’s = server is down.
### What is a status code 202? 
The request was accepted. 
### What is a status code 308? 
It’s telling the client to use another URL since the current URL is no longer available.
### What code would you use if an update didn’t return data to a client?	
404 
### What code would you use if a resource used to exist but no longer does? 
308
### What is the ‘Forbidden’ status code? 
403

## Build A REST API With Node.js, Express, & MongoDB

### Why do we need to pull our MongoDB database string out of our server and put it into our .env? 
So when we push our code to the public, the bad guy won’t have the access to change your mess up our database. 
### What is middleware? 
Cors 
### What does app.use(express.json()) do? 
Parse the file 
### What does the /:id mean in a route? 
Specific route to get the data fro the database. 
### What is the difference between PUT and PATCH?  
Put will update all, patch update partial. 
### How do you make a default value in a schema?
### What does a 500 error status code mean? 
Server error code. 
### What is the difference between a status 200 and a status 201?  
200 is ok, 201 means created. 

[Build A REST API With Node.js, Express, & MongoDB](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)

[HTTP Status Codes for Beginners](https://aloneonahill.com/blog/http-status-codes/)
