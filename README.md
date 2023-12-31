[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly/education/web-development-immersive)

# Cookbook App

## Prerequisites

- Express
- Mongoose & MongoDB
- Mongoose Queries
- Routes & Controllers
- Postman

## Instructions

1. Fork and clone this repository.
2. Change into the new directory.
3. Install dependencies by running `npm install`
4. Run `npm audit fix` to make sure all packages are up to date
5. Fulfill the listed requirements.

Starter code is available to you in the main project repo. You are
required to turn in your submission by making a pull request on the original
repository.

## Requirements

1. Start your server from the terminal by running: `npm run dev`
2. Your connection and seed files are already set up for you. Start by working through the prompts inside

- `Author.js`
- `Cookbook.js`

3. Run `mongod` in your terminal. In a different tab, seed your data from the command line. Use mongo to make sure your data was inserted.
4. Review the prompts that are provided to you in the following files:

- `server.js`
- `controllers/cookbookRoutes.js`
- `controllers/authorRoutes.js`

5. In the order the files are listed above, work through the prompts, adding your code block under each prompt. Check each route as you complete them.
6. Submit with a pull request on this repo.

## Routing Table

Update the below routing table with the routes

AUTHORS

| **URL**                 | **HTTP Verb** | **Action** | **Description**     |
| ----------------------- | ------------- | ---------- | ------------------- |
| /api/authors            | GET           | index      | get all authors     |
| /api/authors/:firstName | GET           | show       | get author by name  |
| /api/authors            | POST          | create     | create a new author |
| /api/authors/:firstName | PUT           | update     | update an author    |

COOKBOOKS

| **URL**                     | **HTTP Verb** | **Action** | **Description**       |
| --------------------------- | ------------- | ---------- | --------------------- |
| /api/cookbooks              | GET           | index      | get all cookbooks     |
| /api/cookbooks/title/:title | GET           | show       | get cookbook by title |
| /api/cookbooks/year/:year   | GET           | show       | get cookbooks by year |
| /api/cookbooks              | POST          | create     | create a new CKB      |`
| /api/cookbooks              | PUT           | update     | update a CKB          |
| /api/cookbooks/:title       | DELETE        | delete     | delete a CKB          |
