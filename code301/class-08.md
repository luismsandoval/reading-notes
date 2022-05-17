# Class 08

## APIs

The following reading notes cover the design of an API, this includes issues to consider when designing an API.

1. What does REST stand for?

   - Representational State Transfer

2. REST APIs are designed around a ____.

   - Resources (any object, data, or service)

3. What is an identifier of a resource? Give an example.

   - A URI is used to identify that resource. Here is an example from the Microsoft docs:

   ```
   https://adventure-works.com/orders/1
   ```

4. What are the most common HTTP verbs?

   - GET, POST, PUT, PATCH, DELETE

5. What should the URIs be based on?

   - URIs should be based on the resource, a noun, when possible. Here's an example of a do and don't from the Microsoft docs:

   ```
   https://adventure-works.com/orders // Good

   https://adventure-works.com/create-order // Avoid
   ```

6. Give an example of a good URI.

   - https://my-example.com/customers

7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

   - Bad. From my understanding, a chatty web API has multiple small resources, and this can cause more requests being sent to the server.

8. What status code does a successful GET request return?

   - 200 (OK)

9. What status code does an unsuccessful GET request return?

   - 404 (Not Found)

10. What status code does a successful POST request return?

    - 201 (Created)

11. What status code does a successful DELETE request return?

    - 204 (No Content)


## Things I want to know more about

- What is best practice for using PUT to update an API, without compromising the client?

- What is best practice for combining data into one resource, to avoid chatty APIs?

## Sources

- [RESTful web API design](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)
