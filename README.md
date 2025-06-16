
# 🎬 Full-Stack Netflix Clone (MERN + TMDB)

A sleek, full-stack **Netflix clone** built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js) and integrated with the **TMDB API**. This project replicates core streaming features, demonstrates clean modular architecture, secure user authentication, and dynamic movie/TV discovery – making it a solid addition to any full-stack portfolio.

---

## 📌 Project Highlights

- 🧩 **End-to-End MERN Stack**: Robust integration between frontend and backend layers
- 🔐 **Authentication**: Secure user registration/login with JWT and protected routes
- 📺 **Live Movie & TV Fetching**: Integrated with **TMDB API** for dynamic content
- 🧭 **Search Feature**: Instantly search shows/movies across genres
- ⚙️ **Modular API Structure**: Organized and scalable backend for maintainability
- 💅 **Responsive UI**: Styled with Tailwind CSS for a modern Netflix-like experience
- 🛠️ **Reader-Friendly**: Clean code, clear structure, and deploy-ready setup

---

## 📁 Folder Structure

```text
Netflix-clone-demo-main/
├── backend/                  # Node/Express backend
│   ├── config/               # DB connection and env vars
│   ├── controllers/          # Business logic for movies, auth, etc.
│   ├── middleware/           # JWT auth middleware
│   ├── models/               # Mongoose schemas
│   ├── routes/               # API endpoints (auth, movie, tv, search)
│   ├── services/             # TMDB API integration logic
│   ├── utils/                # Token generation helper
│   └── server.js             # Backend entry point
│
├── frontend/                 # React-based frontend
│   ├── public/
│   ├── src/
│   │   ├── components/       # UI components (e.g. cards, navbar)
│   │   ├── pages/            # Page components (Home, Login, etc.)
│   │   ├── services/         # API call functions
│   │   ├── App.js            # App root
│   │   └── index.js          # React DOM entry
│   └── index.html
│
├── .env.sample               # Sample env config
├── .gitignore
├── README.md
├── package.json
├── package-lock.json
````

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/sohamd58/Netflix-clone-demo.git
cd Netflix-clone-demo
```

### 2. Install Dependencies

#### Backend

```bash
cd backend
npm install
```

#### Frontend

```bash
cd ../frontend
npm install
```

### 3. Environment Variables

Create a `.env` file inside the `backend/` directory with the following:

```env
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
TMDB_API_KEY=your_tmdb_api_key
```

### 4. Run the Application

Use two terminals to run backend and frontend:

```bash
# Terminal 1: Backend
cd backend
npm run dev
```

```bash
# Terminal 2: Frontend
cd frontend
npm start
```

---

## 🧩 Tech Stack

* **Frontend**: React, React Router, Tailwind CSS
* **Backend**: Express.js, Node.js, MongoDB, Mongoose
* **Authentication**: JWT, bcryptjs
* **API Integration**: TMDB API for live content
* **Utilities**: dotenv, axios, nodemon, concurrently

---

## 📣 Contributing

Pull requests are welcome! Found a bug or want to suggest an enhancement? Open an issue or submit a PR. Let’s collaborate and build better software!

---

⭐ **Star this repo** if you liked it!
📫 **Connect with me** on [LinkedIn](https://www.linkedin.com/in/soham-d1758) or GitHub!

---
