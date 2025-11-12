Imagify
Live Demo


Description
Imagify is an AI-powered image generation SaaS web application built with the MERN stack. It uses the Clipdrop API to generate high-quality images and includes a secure login/signup system.

Features
AI-based image generation using the Clipdrop API.
User authentication system with login and signup functionality.
Clean and modern user interface.
Installation Instructions
Clone the repository:
git clone https://github.com/aryan2101-bit/Imagify.git
Navigate to the project directory:
cd Imagify
Server Setup
Navigate to the server folder:
cd server
Install dependencies:
npm install
Configure environment variables: Create a .env file in the server folder and add the following:

MONGODB_URI=<your-mongodb-connection-string>
JWT_SECRET=<your-jwt-secret>
CLIPDROP_API=<your-clipdrop-api-key>
Start the server:

npm run server
Client Setup
Navigate to the client folder:
cd client
Install dependencies:
npm install
Configure environment variables: Create a .env file in the client folder and add the following:

VITE_BACKEND_URL=<url-for-server-side>
Start the client:

npm run dev
Commands Summary
Server Commands
Install dependencies: npm install
Run the server: npm run server
Client Commands
Install dependencies: npm install
Run the client: npm run dev
Environment Variables Summary
Server Folder
MONGODB_URI: MongoDB connection string.
JWT_SECRET: Secret key for JSON Web Token.
CLIPDROP_API: API key for the Clipdrop API.
Client Folder
VITE_BACKEND_URL: URL of the server application.

