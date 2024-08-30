# Express.js Quote Gnerator API

## General Info

This is a challenge project from Codecademy, desinged to test our knowledge of creating backends with Express.js.
I created a small web app that allows users to create, read, update, delete data (CRUD).

The following requirements have to be met:

- the server should listen on port 4001
- the api should have a GET **/api/quotes/random** route that sends back a random quote from the quotes data
- the api should have a GET **api/quotes** route that will return different results depending below conditions
  - if the request has no query params, it returns all available quotes
  - if there is a query strinng with a **person** attribute, it should return all the quotes attributed to the specified person
  - if there are no quotes for the requested person, an empty array should be returned
- the api should have a POST **/api/quotes** route for adding new quotes with two properties: _quote_ with the quote text itself, and _person_ with the person who is crediting with saying the quote
- extra challenges:
  - ✅ include a **PUT** route for updating quotes
  - ✅ include a **DELETE** route for deleting quotes
  - ✅ include the year of each quote
