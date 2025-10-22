Netflix Clone Site

Description:
This project is a Netflix-style movie streaming web application built using React (Vite) for the frontend and Node.js + Express.js for the backend.

Features:
- Fetch and display movies from the backend API.
- Movie posters and preview videos stored locally.
- Hover on a movie to play a short preview video.
- Click on a movie to play a youtube video.
- Error handling for missing or invalid movie data.
- Modular folder structure for easy maintenance.

Project Structure:
Netflix-Interview/
│
├── backend/
│   ├── assets/
│   │   ├── posters/
│   │   └── videos/
│   ├── controllers/
│   ├── routes/
│   ├── movies.json
│   └── server.js
│
├── frontend/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── styles/
│   │   ├── App.jsx
│   │   └── main.jsx
│   └── index.html
│
└── README.md

Technologies Used:
- Frontend: React (Vite)
- Backend: Node.js, Express.js
- Data Storage: Local JSON (movies.json)
- Tools: Nodemon, Axios, React Router DOM

How to Run the Project:
1. Clone the repository
git clone repository_link
cd Netflix_Interview

2.Set up and run the backend
cd backend
npm install
npm start
(The backend will run on http://localhost:5000)

3.Set up and run the frontend
cd ../frontend
npm install
npm run dev
