# Express, NPM, TDD, CI/CD

## An introduction to NodeJS and Express

1. Explain middleware, answer as though I were a non-technical recruiter.

   - Middleware is functions that perform some operation on the rew or res, then calls the next function in the stack.

2. Express the most popular \_\_ \_\_.

   - _Node web framework_

3. Express is “unopinionated.” What does that mean?

   - This means that you can insert many compatible middleware into the request in any order you like.

4. What is a module and why is modularity useful to us as developers?

   - A JS file that can be imported into other code using `require()`. It's used to shortcut your code.

## What is NPM?

1. What version of npm are you running on your machine?

   - 8.1.2

2. What command would you type to install a library/package called ‘jshint’ into your node project?

   - `npm install jshint`

## What is TDD?

1. Explain why tests are important. Please explain as though I were your non technical elder.

   - Testing allows the developer to quickly catch bugs and where they are happening, so the developer can easily identify and fix the issue.

2. What are three expected benefits of testing?

   1. Reduction in defect rates.

   2. Reduce effort needed in projects final phase.

   3. Leads to improved design qualities in the code.

3. Name at least 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.

   - Individual:

     1. Writing overly Trivial tests.

     2. Forgetting to run tests frequently.

   - Team:

     1. Partial adoption - only used by a few devs.

     2. Poor maintenance of the tests.

## CI/CD

1. What are three benefits of Continuous Integration?

   1. Ensure everyone's changes are being integrated.

   2. Easily catch bugs.

   3. Reduce merge conflicts.

2. What is the difference between Continuos Delivery and Continuous Deployment?

   - Continuous delivery is software that is developed to be realeased at any time. Continuous deployment is a process that allows you to deploy new features immediately.

3. Explain how GitHub fits into this process assuming the listener comes from a non-technical background.

   - GitHub sends messages about the code to be integrated by running automated tests.

## Sources

[An introduction to NodeJS and Express](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction)

[What is NPM?](https://docs.npmjs.com/getting-started/what-is-npm)

[What is TDD?](https://www.agilealliance.org/glossary/tdd/)

[CI/CD](https://www.youtube.com/watch?v=xSv_m3KhUO8)
