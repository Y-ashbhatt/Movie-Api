# MovieMania

A single-page movie site that showcases the top 5 trending searches from the Appwrite Database and allows users to search for movies using the TMDB API. The site also displays the most popular movies currently trending via the same API.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [What I Learned](#what-i-learned)
- [Future Enhancements](#future-enhancements)
- [Author](#author)

---

## Overview

MovieMania is a visually engaging and highly interactive platform designed for movie enthusiasts. By combining the power of Appwrite Database and TMDB API, it delivers a seamless experience for discovering trending and popular movies. This project is a perfect playground for understanding API integrations and database interactions while enhancing UI/UX skills.

---

## Features

- **Trending Searches:** Displays the top 5 trending searches fetched dynamically from the Appwrite Database.
- **Search Movies:** Search for movies by title using the TMDB API with debouncing for optimal performance.
- **Popular Movies:** View a curated list of the most popular movies trending right now.
- **Responsive Design:** Optimized for mobile and desktop viewing using Tailwind CSS.
- **Real-Time Updates:** Reflects real-time changes in trending searches.

---

## Tech Stack

### Frontend
- **React**: For building the user interface.
- **Tailwind CSS**: For styling the application.
- **Debouncing with React**: Ensures efficient and responsive search functionality.

### Backend
- **Appwrite**: Used for managing trending searches.

### API
- **TMDB API**: For movie data, including search results and trending movies.

### Database
- **Appwrite Database**: Stores and retrieves trending searches.

---

## Getting Started

### Prerequisites

- Node.js installed (version 16+ recommended)
- Appwrite Server setup and running
- TMDB API Key

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/moviemania.git
   ```

2. Navigate to the project directory:
   ```bash
   cd moviemania
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Create a `.env` file in the root directory and add the following:
   ```env
   VITE_TMDB_API_KEY=your_tmdb_api_key
   VITE_APPWRITE_PROJECT_ID=your_appwrite_project_id
   VITE_APPWRITE_DATABASE_ID=your_appwrite_database_id
   VITE_APPWRITE_COLLECTION_ID=your_appwrite_collection_id
   ```

5. Start the development server:
   ```bash
   npm run dev
   ```

---

## Usage

1. Open the application in your browser at the provided development server URL.
2. View the top 5 trending searches on the homepage.
3. Use the search bar to find movies by title. The search input utilizes debouncing to limit API calls and improve performance.
4. Explore the most popular movies under the "Popular Movies" section.

---

## What I Learned

- Setting up and using Appwrite as a backend solution for storing and fetching data.
- Integrating third-party APIs (TMDB) into a React application.
- Implementing debouncing in React to optimize search performance.
- Managing environment variables to secure API keys.
- Creating a responsive and visually appealing UI using Tailwind CSS.
- Handling asynchronous data fetching and error management in React.

---

## Future Enhancements

- **Authentication:** Allow users to log in and save their favorite movies.
- **Pagination:** Add pagination to the search results and popular movies sections.
- **Advanced Search Filters:** Include options for filtering by genre, release year, and ratings.
- **Dark Mode:** Add a dark mode toggle for improved user experience.
- **Performance Optimization:** Use lazy loading and caching for faster data retrieval.

---


## Author

**Yash Bhatt**  
[GitHub](https://github.com/y-ashbhatt)  
[LinkedIn](https://www.linkedin.com/in/yashbhatt30)

