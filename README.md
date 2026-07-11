# 🎬 MovieBuzz - Mobile Movie Recommendation App

MovieBuzz is a modern cross-platform mobile application that helps users discover trending movies, explore detailed information, and receive personalized recommendations. The application provides a clean and intuitive interface for browsing movies, viewing ratings, cast information, trailers, and much more using real-time movie data.

---

## Features

- Search movies instantly
- Browse Trending, Popular and Top Rated movies
- View detailed movie information
- Watch official movie trailers
- Explore cast and crew details
- Personalized movie recommendations
- Responsive and modern mobile UI
- Fast API integration with TMDB
- Smooth navigation between screens

---

## Tech Stack

### Frontend
- Flutter
- Dart

### Backend
- FastAPI
- Python

### Database
- SQLite

### APIs
- TMDB (The Movie Database)

### Tools
- VS Code
- Android Studio
- Git
- GitHub
- Postman

---

## Project Structure

```
MovieBuzz/
│
├── backend/
│   ├── app/
│   ├── routes/
│   ├── models/
│   ├── database/
│   └── main.py
│
├── frontend/
│   ├── lib/
│   ├── screens/
│   ├── widgets/
│   ├── services/
│   └── assets/
│
├── screenshots/
├── README.md
└── requirements.txt
```

---

## Installation

### Clone Repository

```bash
git clone https://github.com/1029piyush/MovieBuzz-mobile-application-.git
```

### Navigate to Project

```bash
cd MovieBuzz-mobile-application-
```

### Backend Setup

```bash
cd backend

python -m venv venv

# Windows
venv\Scripts\activate

# Linux / macOS
source venv/bin/activate

pip install -r requirements.txt

uvicorn main:app --reload
```

Backend will start at:

```
http://127.0.0.1:8000
```

---

### Frontend Setup

```bash
cd frontend

flutter pub get

flutter run
```

---

## API Used

This project uses the **TMDB (The Movie Database) API** to retrieve movie information including:

- Trending Movies
- Popular Movies
- Top Rated Movies
- Upcoming Movies
- Movie Details
- Cast Information
- Trailers
- Recommendations

Create your own API key from:

https://developer.themoviedb.org/

---

## Screenshots

> Add application screenshots here.

Example:

```
screenshots/
│
├── home.png
├── search.png
├── details.png
├── recommendation.png
```

---

## Future Improvements

- User Authentication
- Watchlist
- Favorites
- Offline Caching
- AI Movie Recommendation Engine
- Voice Search
- Dark Mode
- Multi-language Support
- Streaming Platform Availability
- Push Notifications

---

## Learning Outcomes

Through this project, I gained practical experience with:

- Mobile Application Development
- REST API Integration
- Backend Development using FastAPI
- Database Design
- Flutter State Management
- Clean Project Architecture
- Git Version Control

---

## Repository

GitHub Repository:

https://github.com/1029piyush/MovieBuzz-mobile-application-.git

---

## Author

**Piyush Satish Raghorte**

B.Tech – Computer Science and Business Systems

Interested in:
- Mobile Development
- Cloud Computing
- DevOps
- Artificial Intelligence
- Software Engineering

GitHub:
https://github.com/1029piyush

---

## License

This project is created for educational and learning purposes.
