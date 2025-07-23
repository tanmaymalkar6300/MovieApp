

<div align="center">
 
  <div>
    <img src="https://img.shields.io/badge/-React_JS-black?style=for-the-badge&logoColor=white&logo=react&color=61DAFB" alt="react.js" />
    <img src="https://img.shields.io/badge/-Appwrite-black?style=for-the-badge&logoColor=white&logo=appwrite&color=FD366E" alt="appwrite" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
  </div>

  <h3 align="center">🎬 React Movie App with Appwrite Backend</h3>

  <div align="center">
    A fully responsive movie discovery app using React, Appwrite, and Tailwind CSS.
  </div>
</div>



## 📋 Table of Contents

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Getting Started](#getting-started)
5. 💡 [Project Structure](#structure)
6. 📸 [Screenshots](#screenshots)

---

## 🤖 Introduction

This project is a responsive movie browsing application built using **React** for the frontend, **Appwrite** for backend services (auth, DB, storage), and **Tailwind CSS** for styling. It fetches real-time movie data from the **TMDB API** and allows users to search, view details, and explore trending films.

I built this app to deepen my knowledge in modern frontend development with React and to explore Appwrite as a full-stack backend alternative to Firebase.

---

## ⚙️ Tech Stack

- **React.js** – UI rendering and routing
- **Appwrite** – Authentication, database, storage
- **Tailwind CSS** – Styling with utility-first classes
- **Vite** – Fast development bundler
- **TMDB API** – Movie data source

---

## 🔋 Features

- 🔍 **Search Movies** – Query titles using live TMDB API.
- 🎥 **View Movie Details** – Posters, language, rating, release year.
- 📈 **Trending Section** – Highlighting trending content.
- 🌓 **Light/Dark Mode Toggle** (added by me)
- ❤️ **Add to Favorites** (added by me using localStorage)
- 📱 **Fully Responsive UI** – Works across screen sizes.
- ⚡ **Performance-first Build** – Powered by Vite.

---

## 🤸 Getting Started

### Prerequisites

- Node.js
- npm
- Git

### Clone & Setup

```bash
git clone https://github.com/yourusername/react-movie-app.git
cd react-movie-app
npm install
````

### Configure `.env`

Create a `.env.local` file:

```env
VITE_TMDB_API_KEY=your_tmdb_api_key
VITE_APPWRITE_PROJECT_ID=your_appwrite_project
VITE_APPWRITE_DATABASE_ID=your_db_id
VITE_APPWRITE_COLLECTION_ID=your_collection_id
```

> You can get a TMDB API key by signing up at [TMDB Developer Portal](https://developer.themoviedb.org/reference/intro/getting-started)

### Start Dev Server

```bash
npm run dev
```

Then open [http://localhost:5173](http://localhost:5173)

---

## 💡 Project Structure

```
📁 react-movie-app
├── public/
│   └── static assets
├── src/
│   ├── App.jsx
│   ├── appwrite.js
│   ├── components/
│   │   └── Spinner.jsx
│   └── styles/
├── .env.local
├── package.json
└── vite.config.js
```






---

## 🙋 About Me

I’m actively building real-world full stack apps using React and backend platforms like Appwrite/Firebase. This project is part of my journey to strengthen frontend skills and understand cloud-based architecture.

Feel free to connect or ask me about the code.

---
