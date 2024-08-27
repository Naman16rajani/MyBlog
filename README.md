# MyBlog

This is a blog application built using the MERN stack (MongoDB, Express, React, Node.js). The app allows users to create, read, update, and delete blog posts, manage user authentication, and handle photo uploads. Morgan is used for logging HTTP requests.


## Features
- User authentication with JWT (JSON Web Tokens)
- CRUD (Create, Read, Update, Delete) operations for blog posts
- View a list of all posts or individual post details
- Responsive design for mobile and desktop devices
- Photo upload and save functionality
- Logging HTTP requests with Morgan
## Technologies Used
- Frontend: React, Redux, Axios, CSS
- Backend: Node.js, Express.js, MongoDB, Mongoose
- Authentication: JSON Web Tokens (JWT)
- Database: MongoDB (via Mongoose)
- Logging: Morgan
- File Uploads: Multer

## Usage
- Home Page: Displays a list of all blog posts.
- Create Post: Allows logged-in users to create a new blog post.
- Edit Post: Allows the author to edit their own posts.
- Delete Post: Allows the author to delete their own posts.
- Authentication: Users can sign up, log in, and log out.
- Photo Upload: Users can upload and save photos for their blog posts.
## API Endpoints
### Blog Routes
- GET /api/blog/all-blog: Retrieve all blog posts
- POST /api/blog/create-blog: Create a new blog post (requires authentication)
- PUT /api/blog/update-blog/:id Update an existing blog post (requires authentication)
- GET /api/blog/get-blog/:id Retrieve a specific blog post by ID
- DELETE /api/blog/delete-blog/:id Delete a specific blog post (requires authentication)
- GET /api/blog/user-blog/:id Retrieve all blog posts by a specific user
### User Routes
- GET /api/user/all-users: Retrieve all users
- POST /api/user/register: Register a new user
- POST /api/user/login: Log in a user
