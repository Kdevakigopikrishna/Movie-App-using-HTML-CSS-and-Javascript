Movie App using HTML, CSS, and JavaScript
Project Description

The Movie App is a simple web application developed using HTML, CSS, and JavaScript. This application displays trending movies and allows users to search for movies easily.

The movie data is fetched from the The Movie Database (TMDB) API and displayed dynamically on the webpage using JavaScript.

Each movie card in the application shows important movie information such as:

poster_path – Displays the movie poster image

title – Shows the name of the movie

vote_average – Displays the movie rating

overview – Provides a short description of the movie

When the webpage loads, the application automatically fetches trending movies from the TMDB API and displays them in a grid layout. Users can also search for any movie using the search bar provided at the top of the page.

Features

Display trending movies

Search movies by title

Show movie poster, title, rating, and overview

Dynamic movie data loading using API

Responsive movie cards with hover overview effect

Technologies Used

HTML – For creating the structure of the webpage

CSS – For styling and layout design

JavaScript – For fetching API data and adding functionality

API Used

This project uses the The Movie Database (TMDB) API to fetch movie data.

Example API endpoints used:

Discover Movies API

Search Movies API

Project Structure
Movie-App
│
├── index.html     # Main HTML structure
├── style.css      # Styling of the webpage
├── script.js      # JavaScript logic and API calls
└── README.md      # Project documentation
How It Works

The webpage loads and JavaScript calls the TMDB API.

The API returns movie data in JSON format.

JavaScript processes the data.

Movie cards are created dynamically.

The user can search for movies using the search bar.

Learning Outcomes

This project helps beginners understand:

API integration in JavaScript

Fetching and displaying dynamic data

DOM manipulation

Basic front-end web development concepts

Conclusion

The Movie App demonstrates how to build a dynamic web application using HTML, CSS, and JavaScript by integrating an external movie database API to fetch and display real-time movie information.
