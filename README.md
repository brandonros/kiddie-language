# kiddie-language
Write plain English, get code

Proof of concept on whether top-tier business analysts can replace programmers by architecting entire systems using plain English instead of a programming language.

## Services

Create a template that asks:

1. request method
1. request path
1. request body/parameters (name + type)
1. logic
1. response format

Logic can include:

1. interfacing with other services (internal + external/third party)
1. interfacing with message queue/database/key value store
1. performing data manipulation (filter/reduce/map with basic arithmetic/boolean logic)

## UI

Create a template that asks:

1. page title
1. page path
1. outline of elements on page
1. logic

Logic can include:

1. Presenting notifcations
1. Calling a service (submitting a collection of input fields)
1. Linking to another page

## Batch jobs

Create a template that asks:

1. when job should run
1. logic

Logic can include:

1. Looping over rows returned from a database query
1. performing data manipulation (filter/reduce/map with basic arithmetic/boolean logic)
