# RESTful API Blog - Documentation

## Project Overview
A RESTful API blog application built with Node.js, Express.js and MongoDB.

## Project Structure
restful-api-blog/
├── config/
│   └── db.js          # MongoDB connection
├── controllers/
│   ├── postController.js      # Post CRUD operations
│   └── commentController.js   # Comment operations
├── middleware/
│   └── authMiddleware.js      # JWT authentication
├── models/
│   ├── Post.js        # Post schema
│   └── Comment.js     # Comment schema
├── routes/
│   ├── postRoutes.js      # Post routes
│   └── commentRoutes.js   # Comment routes
├── .env               # Environment variables
├── .gitignore
├── package.json
├── README.md
└── server.js          # Entry point
## API Reference

### Posts
| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | /api/posts | Get all posts |
| GET | /api/posts/:id | Get single post |
| POST | /api/posts | Create post |
| PUT | /api/posts/:id | Update post |
| DELETE | /api/posts/:id | Delete post |

### Comments
| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | /api/comments/:postId/comments | Get comments |
| POST | /api/comments/:postId/comments | Add comment |
| DELETE | /api/comments/:id | Delete comment |

## Author
Anjalo Mathew - Codtech Internship Task 2