
# Savage Auth

A full-stack application featuring user authentication and an interactive message board. Users can create an account, log in, post messages, vote on messages, and delete them.

## Features

- User registration and login
- Password hashing using bcrypt
- Create and display messages
- Thumbs-up and thumbs-down voting
- Delete messages

## Technologies Used

- Frontend: HTML, CSS, JavaScript, EJS, Bootstrap, Font Awesome

- Backend: Node.js, Express.js

- Database: MongoDB, Mongoose

- Authentication: Passport.js, bcrypt, express-session

## How It Works

1. Users register or log in through an authentication form.
2. Passport.js validates credentials against user information stored in MongoDB.
3. Authenticated users are redirected to their profile page.
4. Users can submit messages through an HTML form.
5. Fetch requests send HTTP requests to Express routes.
6. The server updates the MongoDB database and the page refreshes to display the changes.

### Installation

- Clone the repository:

- run nom install 

## What I Practiced

- Implementing local authentication with Passport.js
- Understanding password hashing and session management
- Connecting a Node.js application to MongoDB
- Working with Express routes and HTTP methods
- Performing create, read, update, and delete operations
- Understanding how frontend interactions trigger backend operations

## Installation

1. Clone repo
2. run `npm install`

## Usage

1. run `node server.js`
2. Navigate to `localhost:8080`

## Credit

Modified from Scotch.io's auth tutorial
