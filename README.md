# 🎬 Movie App  

A modern and responsive movie application built with **React**, **TailwindCSS**, and **Appwrite**, utilizing **TMDB API** for fetching movie data. This app provides users with an intuitive interface to search, browse, and explore movies effortlessly.  

## 🚀 Features  

- 🔍 **Search Movies** – Real-time search with debouncing using `react-use`.  
- 📜 **Movie Details** – View comprehensive details, including ratings, genres, and descriptions.  
- 🎞️ **Trending & Popular Movies** – Fetch trending, top-rated, and upcoming movies from TMDB.  
- 🖥️ **Responsive UI** – Styled using **TailwindCSS** for a clean and modern design.  
- 🔐 **User Authentication** – Integrated with **Appwrite** for secure user authentication.  
- 💾 **Favorites & Watchlist** – Save movies to your personal watchlist (if implemented).  

## 🛠️ Tech Stack  

- **Frontend**: React, TailwindCSS  
- **State Management**: React hooks, React-use (for debouncing)  
- **Backend & Auth**: Appwrite  
- **API**: TMDB API  

## 📦 Installation  

1. Clone the repository:  
   ```bash
   git clone https://github.com/shahnawaz2003/movie-app.git
   cd movie-app

## 📦 Install dependencies:
     
     npm install

## 📦 Create a .env file in the root directory:
    
    VITE_TMDB_API_KEY=your_tmdb_api_key
    VITE_APPWRITE_PROJECT_ID=your_appwrite_project_id
    VITE_APPWRITE_DATABASE_ID=your_appwrite_database_id
    VITE_APPWRITE_COLLECTION_ID=your_appwrite_collection_id
    
## 📦 Start the Development Server:
    npm run dev
