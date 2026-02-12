🎬 Susie - Movie Discovery Web Application
A modern, full-stack movie discovery platform where users can explore, rate, review, and organize movies. Built with React, Node.js, and the TMDB API.

✨ Features
Homepage
Logo & Navigation - Girl head icon in header with site branding
Search Bar - Search for movies, users, and lists
Trending Movies - Recently popular movies displayed in grid
Latest News - Movie industry news and platform updates
Popular Lists - Community-curated movie lists
Recent Reviews - Latest user reviews with ratings
Coming Soon - Upcoming movie releases
Footer Links - About, Pro, News, Terms, Privacy, Contact
Movies Page
Advanced Filtering: Sort by popularity/rating/title/release, order by ascending/descending, genre filters, service filters, year filters, director filters, runtime filters, studio filters
Display: 20 movies per page with result count
Search
Search across movies, users, and lists
Movie Details Page
Poster, backdrop, description, release date, genres, services, runtime, studio, director
User reviews with ratings
Actions for logged-in users: mark watched, like, add to watchlist, write review, add to lists
Authentication
Login ("Welcome Back")
Register ("Create Account")
JWT-based auth
My Library (After Login)
Watched movies, likes, watchlist, reviews, friends, custom lists
Info Pages
About (FAQ), Pro (upgrade), News (create news), Terms, Privacy, Contact
🚀 Tech Stack
Frontend: React 18, React Router, SCSS, Axios Backend: Node.js, Express, MongoDB, Mongoose, JWT, bcryptjs API: TMDB API (e80fa731e84c04410d613444086dbe29)

📦 Quick Start
Backend
cd backend
npm install
cp .env.example .env
npm start  # runs on http://localhost:5000
Frontend
cd frontend
npm install
cp .env.example .env
npm start  # runs on http://localhost:3000
📚 Key Endpoints
POST /api/auth/register - Register
POST /api/auth/login - Login
GET /api/movies/trending - Trending movies
GET /api/movies/discover - Discover with filters
GET /api/movies/search - Search
🎨 Design
Dark theme with purple accents
Responsive design
Girl head icon (👧) logo
Happy movie watching! 🍿🎬
