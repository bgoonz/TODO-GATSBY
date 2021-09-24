# Not Todo Gatsby App connected to a REST API

[Gatsby Talk](https://building-apps-with-gatsby.netlify.com/)
[REST API](https://github.com/smakosh/not-todo-api)

## Prerequisites

[Yarn](https://yarnpkg.com/en/)

Please create a new file `.env.development` and put this env variable

> If you're building locally, you will have to create a new file `.env.production` and put the same env variable

```bash
API=http://localhost:5000/api
```

## Installing

Installing the dependencies

```bash
yarn
```

## Start the REST API



Prerequisites
Node Js
MongoDB Installed
Please create a new file .env and put these env variables

DB=mongodb://localhost:27017/todo
SECRET_KEY=NSA
REACT_APP_URL=http://localhost:8000 // when cors is enabled, this will be the only origin to send requests
Installing
Installing the dependencies

npm i
Start your mongodb database
npm run database
Start the dev server
npm run dev
Models
User:

username
email
password
tokens
Post:

title
isDone
date
_creator
Routes
User
POST /api/user/register
    // Register a new user and returns user data with the generated token
    // Public

POST /api/user/login
    // Login user and returns user data with the generated token
    // Public

GET /api/user/verify
    // Verifies token and returns current user data
    // Private

DELETE /api/user/logout
    // Logout
    // Private
Post
POST /api/post
    // Create a new post
    // Private

GET /api/post/all
    // Get all the posts

GET /api/post/:id
    // Get Post by ID
    // Private

DELETE /api/post/:id
    // Delete Post by ID
    // Private

PATCH /api/post/:id
    // Update a post
    // Private
Built with
Express Js
MongoDB & Mongoose
And these useful of JavaScript libraries package.json



## Start the dev server

```bash
yarn start
```

### Clean the cache

This removes the `.cache/` & `public/` folders

```bash
yarn reset
```

## Built with


- Gatsby
- React & GraphQL
- VSCode
- Unnamed
- And these useful of JavaScript libraries & Gatsby plugins [package.json](package.json)
