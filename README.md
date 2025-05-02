# Music-APP
Music Now: A MERN Stack Music Streaming Platform

Welcome to Music Stream, a full-stack web application built with the MERN stack (MongoDB, Express.js, React, Node.js) that lets users stream music, create and manage playlists, upload songs, and search for their favorite tracks. Whether you're a music enthusiast or a developer looking to explore a modern web app, this project is a great starting point!



Features

User Authentication: Secure login and registration using JSON Web Tokens (JWT).

Song Streaming: Play songs with a custom audio player featuring Play/Pause, Next, and Previous controls.

Playlist Management: Create, edit, delete playlists, and add/remove songs.

Song Upload: Upload songs with metadata (title, artist).

Queue System: Add songs to a playback queue and navigate seamlessly.

Global Search: (In progress) Search songs and playlists across the platform.

Responsive Design: Mobile and desktop-friendly UI with Tailwind CSS.

Protected Routes: Restrict playlist and upload features to authenticated users.



Tech Stack

Frontend: React, React Router, Tailwind CSS, Axios, React Icons, React JWT

Backend: Node.js, Express.js, MongoDB, JSON Web Tokens, Multer

Database: MongoDB



Tools: Vite (frontend build), Postman (API testing), MongoDB Compass (database management)

Prerequisites

Before you begin, ensure you have the following installed:

Node.js (v16 or higher)

MongoDB (local or MongoDB Atlas)

Git (for cloning the repository)

NPM (comes with Node.js)

A modern browser (Chrome, Firefox, Edge)





Installation

Follow these steps to set up the project locally:

Clone the Repository:

git clone https://github.com/your-username/music-streaming-app.git
cd music-streaming-app



Install Backend Dependencies:

cd server
npm install



Install Frontend Dependencies:

cd ../client
npm install



Set Up MongoDB:

Start MongoDB locally: mongod

Or use MongoDB Atlas and get your connection string.



Environment Variables

Create a .env file in the server/ directory with the following variables:

MongoURI=mongodb://localhost:27017/music_streaming  # Replace with your MongoDB connection string
jwtsecret=your-secret-key                          # Replace with a secure JWT secret
PORT=1337                                          # Optional: defaults to 1337




Running the Application

Start MongoDB (if running locally):

mongod

Start the Backend:

cd server
node server


The backend runs on http://localhost:1337.



Start the Frontend:

cd client
npm run dev





The frontend runs on http://localhost:5173 (Vite default).

Access the App:

Open http://localhost:5173 in your browser.

Navigate to /home, /songs, /playlists, or /playlist/:id.
