# 🎬 Movie Recommendation App

A beginner-friendly movie discovery app built using **React** and **Vite**, integrating the **TMDB API** for real-time movie data and **Appwrite** for backend storage.  
This project was made as part of my journey to **understand React better by building something practical and fun**.

---

## 📚 Purpose of the Project

I created this project to:
- Practice building a React application from scratch
- Learn how to manage component state and side effects using `useState` and `useEffect`
- Understand API integrations (TMDB for data, Appwrite for backend)
- Work with debouncing, dynamic rendering, and conditional UI
- Explore modern tooling like Vite, Tailwind CSS, and Vercel deployment

---

## 🌟 Features

- 🔍 Search for movies using TMDB API  
- 📈 View trending movies (stored in Appwrite)  
- 🌀 Loading spinner for better UX  
- ⚡ Debounced search input  
- 📱 Mobile-friendly, clean UI  
- 🧠 Clear component structure (Search, MovieCard, Spinner, etc.)

---

## 🛠️ Tech Stack

| Frontend        | Backend/API        | Tools & Services       |
|-----------------|--------------------|-------------------------|
| React (Vite)    | Appwrite (Cloud)   | TMDB API (Movie data)   |
| Tailwind CSS    | Appwrite Database  | Vercel (Deployment)     |
| JavaScript      | Appwrite SDK       | Git, GitHub             |

---

## ⚙️ Getting Started

1. **Clone the repo**
   ```bash
   git clone https://github.com/your-username/movie-app.git
   cd movie-app
Install dependencies

bash
Copy
Edit
npm install
Setup .env file

env
Copy
Edit
VITE_TMDB_API_KEY=your_tmdb_v4_bearer_token
VITE_APPWRITE_PROJECT_ID=your_appwrite_project_id
VITE_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
VITE_APPWRITE_DATABASE_ID=your_database_id
VITE_APPWRITE_COLLECTION_ID=your_collection_id
Run it

bash
Copy
Edit
npm run dev
🚀 Deployment (Vercel)
Add your env variables in Vercel → Project Settings → Environment Variables

Set build command to npm run build

Set output directory to dist

🙌 Acknowledgements
TMDB API

Appwrite

Vercel

Inspired by real-world movie UIs

👨‍💻 About Me
Hi! I'm Ashish, a CSE student exploring frontend development and React.
This project helped me a lot in understanding how components, props, state, effects, and API calls all work together.
