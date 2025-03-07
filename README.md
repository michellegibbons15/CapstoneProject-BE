# PlayRVA - Back-End

PlayRVA is a Node.js and Express-based back-end application that provides API services for managing sports facilities, parks, leagues, and community interactions in the Richmond, VA area. It includes authentication, event management, and community features.

## Tech Stack:

- Node.js - JavaScript runtime
- Express - Web framework for Node.js
- MySQL - Relational database
- Sequelize - ORM for database management
- dotenv - Environment variable management

## Installation

<u>Clone the repository:</u>

git clone https://github.com/yourusername/capstoneproject-be.git
cd capstoneproject-be

<u>Install dependencies:</u>

npm install

<u>Set up the environment variables:</u>
Create a .env file in the root directory and add the following (change as needed):

PORT=8081
DB_HOST=localhost
DB_PORT=3306
DB_USER=root
DB_PASSWORD=root 
DB_NAME= 'the database you are trying to use'

## Start the server:

npm start

## API Endpoints

<u>Authentication:</u>
- POST /api/users/signup - Register a new user
- POST /api/users/login - Authenticate user and return JWT

<u>Events:</u>
- GET /api/events - Retrieve all events
- POST /api/events - Create a new event
- DELETE /api/events/:id - Delete an event

<u>Community:</u>
- -GET /api/posts - Fetch all community posts
- POST /api/posts - Create a post
- POST /api/comments - Add a comment
- POST /api/likes - Like a post


## Usage:
- Ensure MySQL is running and properly configured with the credentials in .env.
- Use Postman or a similar tool to test API requests (I used ThunderClient).
- The front-end (React) will consume these endpoints to display data.
