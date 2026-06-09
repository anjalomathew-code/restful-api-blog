# RESTful API Blog

A RESTful API for a blog application built with Node.js, Express, and MongoDB.

## Features
- Create, Read, Update, Delete blog posts
- Add and delete comments on posts
- JWT Authentication middleware
- MongoDB database integration

## Technologies Used
- Node.js
- Express.js
- MongoDB & Mongoose
- JWT (JSON Web Tokens)
- dotenv

## Installation

1. Clone the repository
2. Run `npm install`
3. Create `.env` file and add your MongoDB URI
4. Run `npm start`

## API Endpoints

### Posts
- GET /api/posts - Get all posts
- GET /api/posts/:id - Get single post
- POST /api/posts - Create a post
- PUT /api/posts/:id - Update a post
- DELETE /api/posts/:id - Delete a post

### Comments
- GET /api/comments/:postId/comments - Get all comments
- POST /api/comments/:postId/comments - Add a comment
- DELETE /api/comments/:id - Delete a comment

## Author
Anjalo Mathew