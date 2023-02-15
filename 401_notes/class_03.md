# Review: ES6 Classes

### Classes are a template for creating ____.
Object

### Can a class declaration be hoisted?
No,class declarations are not hoisted.

### How would you describe a constructor and contextual “this” to a non-technical friend?
constructor is like a blueprint for class, the word `this` help the web browser know which you are referring to which class.

# Using Express Routing

### Within Express, what does routing refer to?
Refer to client's response. 

### What is the difference between a route path and a route method?
Routh path combines the request method, it can define endpoints with the request. Route paths can be strings, string patterns, or regular expressions.
A route method is obtained from one of the HTTP methods and is attached to an object. 

### When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?
When you have next middleware or function to invoke, you can pass in `next()`. 

### What is an Express Router?

### By what mean do we initialize express.Router() in an express server?

### What do we use route middleware for?
Middleware functions can Execute any code, make changes to the request and the response objects and end the request-response cycle.



[using middleware](https://expressjs.com/en/guide/using-middleware.html#:~:text=Middleware%20functions%20can%20perform%20the,End%20the%20request%2Dresponse%20cycle.)

[Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)

[Express Routing](https://expressjs.com/en/guide/routing.html)

[Learn to Use the New Router in ExpressJS 4.0](https://www.digitalocean.com/community/tutorials/learn-to-use-the-new-router-in-expressjs-4)
