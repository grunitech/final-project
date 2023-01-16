# Project Submission

    How should I submit my final project?

* [Repository](#repository)
  * [Single Repository](#single-repository)
  * [Multiple Repositories](#multiple-repositories)
* [Testing](#testing)
* [Code Style](#code-style)
  * [Files](#files)
* [Implementation Constrains](#implementation-constrains)
  * [Server](#server)
    * [Server 3rd Parties](#server-3rd-parties)
  * [Client](#client)
* [FAQ](#faq)
  * [Can I use `Next.js` for my project?](#can-i-use-nextjs-for-my-project)
  * [Can I use a CSS framework?](#can-i-use-a-css-framework)
  * [Do I have to use database?](#do-i-have-to-use-database)
  * [If I want to use database, can I use Prisma?](#if-i-want-to-use-database-can-i-use-prisma)

## Repository

You have 2 options to submit your project. Choose one of the following options.

### Single Repository

* [ ] Contain directory with the React application named "client"
* [ ] Contain directory with the Express application named "server"

### Multiple Repositories

* [ ] Repository contain React application
* [ ] Repository contain Express application

_Projects should be at the top of the repository._

## Testing

* [ ] Any testable function/class should have unit-test (client & server)
* [ ] Component should be tested using Cypress (do not test the routed components)
* [ ] The Express endpoints should have E2E tests

## Code Style

* [ ] Projects should be written in TypeScript
* [ ] Don't leave commented code
* [ ] Don't leave unused code
* [ ] Liner/Formatter

### Files

* [ ] Don't commit the node modules
* [ ] Don't commit the built JavaScript (TypeScript only)


### Errors

* [ ] Do not submit project with build errors
* [ ] Do not submit project with console errors
* [ ] Do not submit project with nodejs errors

## Implementation Constrains

### Server

* [ ] Should listen to port `3333`
* [ ] Should allow CORS requests
* [ ] Should run tests using `npm test`
* [ ] Should start using `npm start`

#### Server 3rd Parties

If your implementation rely on database, provide details and a script to create and populate all required data.

* [ ] Database details (type, connection arguments)
* [ ] Database creation script

### Client

* [ ] Should run tests using `npm test`
* [ ] Should start using `npm start`

<!--tests, structure, definition for auto-testing-->

## FAQ

### Can I use `Next.js` for my project?

    no.

### Can I use a CSS framework?

    yes.

### Do I have to use database?

    no.

### If I want to use database, can I use Prisma?

    yes. If some installatiion reqiured, you have to provide all details.
