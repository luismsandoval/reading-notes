# Class 12

## CRUD

### Status Codes Based On REST Methodes

1. In your own words, describe what each group of status code represents:

100’s = informal status codes

200’s = success codes

300’s = redirection codes

400’s = client side error codes

500’s = server side error codes

2. What is a status code 202?

   - `Accepted` Tells the client that the process was valid.

3. What is a status code 308?

   - `Permanent Redirect` Tells the client to use another URL

4. What code would you use if an update didn’t return data to a client?

   - `204 No Content`

5. What code would you use if a resource used to exist but no longer does?

   - `410 Gone`

6. What is the ‘Forbidden’ status code?

   - `403 Forbidden`

### Build A REST API With Node.js, Express, & MongoDB

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?

  - Because when we deploy our app we wont be using our local server.

2. What is middleware?

   - Software that allows two applications to easily pass data from a database.

3. What does app.use(express.json()) do?

   - Parses JSON requests.

4. What does the /:id mean in a route?

  - The variable for the specific `_id` given to every object.

5. What is the difference between PUT and PATCH?

  - `PUT` updates all of the data. `PATCH` only updates what the user sends.

6. How do you make a default value in a schema?

  - set `default` in the schema.

7. What does a 500 error status code mean?

   - Internal server error

8. What is the difference between a status 200 and a status 201?

   - `200` is just generic OK, and `201` is a Create confirmation.
