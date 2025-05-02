# 🎵 Music Now: A MERN Stack Music Streaming Platform

Welcome to Music Now, a full-stack web application built with the MERN stack (MongoDB, Express.js, React, Node.js). This platform enables users to stream music, manage playlists, upload songs, and discover their favorite tracks. Whether you're a music lover or a developer exploring modern web applications, this project offers a solid foundation!

---

## 🚀 Features

* 🔐 User Authentication: Secure login and registration using JSON Web Tokens (JWT).
* 🎧 Song Streaming: Custom audio player with Play, Pause, Next, and Previous controls.
* 📂 Playlist Management: Create, edit, delete playlists, and add/remove songs.
* 📤 Song Upload: Upload tracks with metadata like title and artist.
* 📜 Queue System: Add songs to a playback queue and control playback seamlessly.
* 🔎 Global Search: (In Progress) Search for songs and playlists across the platform.
* 📱 Responsive Design: Fully responsive UI using Tailwind CSS for mobile and desktop views.
* 🔐 Protected Routes: Only authenticated users can manage playlists and upload songs.

---

## 🛠 Tech Stack

* Frontend:

  * React
  * React Router
  * Tailwind CSS
  * Axios
  * React Icons
  * React JWT

* Backend:

  * Node.js
  * Express.js
  * MongoDB
  * JSON Web Tokens
  * Multer

* Database:

  * MongoDB

* Tools:

  * Vite (Frontend Build Tool)
  * Postman (API Testing)
  * MongoDB Compass (Database Management)

---

## 📋 Prerequisites

Ensure the following are installed on your system:

* Node.js (v16 or higher)
* MongoDB (local instance or MongoDB Atlas)
* Git
* NPM (comes with Node.js)
* A modern browser (Chrome, Firefox, Edge)

---

## ⚙️ Installation

1. Clone the Repository:

   ```bash
   git clone https://github.com/your-username/music-streaming-app.git
   cd music-streaming-app
   ```

2. Install Backend Dependencies:

   ```bash
   cd server
   npm install
   ```

3. Install Frontend Dependencies:

   ```bash
   cd ../client
   npm install
   ```

---

## 🧪 MongoDB Setup

Start MongoDB locally:

```bash
mongod
```

Or use MongoDB Atlas and get your connection string.

---

## 🔐 Environment Variables

Create a .env file inside the server/ directory with the following content:

```env
MongoURI=mongodb://localhost:27017/music_streaming  # Replace with your MongoDB connection string
jwtsecret=your-secret-key                          # Replace with a secure JWT secret
PORT=1337                                          # Optional: defaults to 1337
```

---

## ▶️ Running the Application

Start MongoDB (if not already running):

```bash
mongod
```

Start the Backend:

```bash
cd server
node server
```

The backend will be running at: [http://localhost:1337](http://localhost:1337)

Start the Frontend:

```bash
cd client
npm run dev
```

The frontend will be running at: [http://localhost:5173](http://localhost:5173)

---

## 🌐 Access the App

Open your browser and navigate to:

* /home
* /songs
* /playlists
* /playlist/\:id

🎶 Enjoy your music streaming experience!

---

## 📬 Contact

For any questions or collaboration, feel free to reach out at:

📧 [your-email@example.com](mailto:varshini_kota@srmap.edu.in)
