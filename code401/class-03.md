# Express REST API

## ES6 Classes

1. Classes are a template for creating \_\_\_\_.

   - Objects! {}

2. Can a class declaration be hoisted?

   - Yes they can be hoisted _but_ its values would not yet be defined, throwing a `reference error`.

3. How would you describe a constructor and contextual “this” to a non-technical friend?

   - A constructor is a method for creating and initializing an object created with a `class`. `this` refers to the direct object.

## Using Express Routing

1. Within Express, what does routing refer to?

   - Routing refers to how an apps endpoints(URI) respond to requests from the client side.

2. What is the difference between a route path and a route method?

   - Route methods refer to HTTP methods (GET, POST, etc) attached to an instance of the class.

   ```javascript
   app.get("/", (req, res) => {
     res.send("GET request to the homepage");
   });
   ```

   - Route paths refer to the endpoints where requests can be made. These paths can be strings, string patterns, regex.

   `/about` in the example below is the route path.

   ```javascript
   app.get("/about", (req, res) => {
     res.send("about");
   });
   ```

3. When is it appropriate to add `next` as a parameter to a route handler and what must you do if `next` has been passed to your middleware as a parameter?

   -

## Express Routing

1. What is an Express Router?

   - A _mini express app_, with just the routing stuff. (i.e. `.use`, `.get`, `.param`, `route`)

2. By what mean do we initialize `express.Router()` in an express server?

   - `express.Router()` is initialized in `app.use()` to apply the routes to our application.

3. What do we use route middleware for?

   - Route middleware is _a way to do something before a request is processed._ Route middleware can be used to run on every request, like checking user authentication

## Sources

1. [ES6 Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)

2. [Using Express Routing](https://expressjs.com/en/guide/routing.html)

3. [Express Routing](https://www.digitalocean.com/community/tutorials/learn-to-use-the-new-router-in-expressjs-4)
