
# MERN Blog Website

This is a full-stack blogging application built using the MERN stack (MongoDB, Express.js, React.js, and Node.js). The application allows users to create, upload, and manage their own blogs. Users can also comment on posts and upload images to enhance their blog posts.

## Features

**- User Registration and Authentication:**
  - Users can create an account and log in securely.
  - Passwords are hashed and stored securely in the database.
  - User sessions are maintained using JSON Web Tokens (JWT).

**- Blog Creation and Management:**
  - Authenticated users can create, edit, and delete their own blog posts.
  - Rich text editor is provided for easy content creation.
  - Blogs are stored in MongoDB for persistence.

**- Commenting System:**
  - Users can add comments to blog posts.
  - Comments are displayed in a threaded format for better readability.

**- Image Upload:**
  - Users can upload images to be included in their blog posts.
  - Images are stored in the server and associated with the respective blog post.

**- Responsive Design:**
  - The application is built with a responsive design, making it accessible on various devices.

## Technologies Used

Frontend: React.js & Material-UI

Backend: Node.js & Express.js

Database: MongoDB

Authentication: JWT

## Installation and Setup

1. Clone the repository:git clone https://github.com/your-username/your-repo.git

2. Navigate to the project directory: cd your-repo

3. Install the dependencies for the server:
 
          cd server
         npm install
         

4. Install the dependencies for the client:
         cd ../client
          npm install   
          
 
5. Configure environment variables:
- Create a `.env` file in the server directory.
- Set the following environment variables:
  - `DB_CONNECTION`: MongoDB connection string
  - `JWT_SECRET`: Secret key for JWT token generation

6. Start the development server and client:
- In the server directory:
  ```
  npm run dev
  ```
- In the client directory:
  ```
  npm start
  ```

7. Access the application in your browser:

http://localhost:3000


