# GoWebPractice

The goal is to build a REST API which must include:

- An endpoint for reading from an external API
  - Write the information in a database
- An endpoint for reading the database
  - Display the information as a JSON
- Unit testing for the principal logic
- Follow conventions, best practices
- Clean architecture

## Requirements

  - Best practices
  - Go basics
  - HTTP handlers
  - Error handling
  - Structs and interfaces
  - Clean architecture
  - Unit testing
  - Database fetching
  

# Tasks

## Part 1

- Create an API
- Add an endpoint to read from a remote database (cloud or containerized)
- The database should have any information, for example:

```txt
1,bulbasaur
2,ivysaur
3,venusaur
```

- The items in the database must have an ID element (int value)
- The endpoint should get information from the database by some query field ***(example: ID)***
- The result should be displayed as a response
- Clean architecture proposal
- Use best practices
- Handle the Errors gracefully (Implement a logging middleware)

> Note: what’s listed in this deliverable is just for guidance and to help you distribute your workload; you can deliver more or fewer items if necessary. However, if you deliver fewer items at this point, you have to cover the remaining tasks in the next deliverable.

## Part 2

- Create a client to consume an external API
- Add an endpoint to consume the external API client
- The information obtained should be stored in the database
- Add unit testing
- Update the endpoint made in the first deliverable to display the result as a JSON
- Refactor if needed

## Part 3

- Add a new endpoint
- This endpoint must support different filters to fetch specific information form the database
- Unit testing

