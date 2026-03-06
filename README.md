# Movie App using HTML, CSS, and JavaScript

## Project Description

The Movie App is a simple web application developed using HTML, CSS, and JavaScript. This application displays trending movies and allows users to search for movies.

The movie data is fetched from The Movie Database (TMDB) API and displayed dynamically on the webpage using JavaScript.

Each movie card in the application shows important movie information such as:

* **poster_path** – Displays the movie poster image
* **title** – Shows the name of the movie
* **vote_average** – Displays the movie rating
* **overview** – Provides a short description of the movie

When the webpage loads, the application automatically fetches trending movies from the TMDB API and displays them on the screen. Users can also search for any movie using the search bar at the top of the page.

## Features

* Display trending movies
* Search movies by title
* Show movie poster, title, rating, and overview
* Dynamic movie data loading using API

## Technologies Used

* HTML
* CSS
* JavaScript

## API Used

The project uses The Movie Database (TMDB) API to fetch movie data such as posters, titles, ratings, and descriptions.

## Project Structure

Movie-App
│
├── index.html
├── style.css
├── script.js
└── README.md

## How It Works

1. The webpage loads and JavaScript calls the TMDB API.
2. The API returns movie data.
3. JavaScript processes the data.
4. Movie cards are created dynamically and displayed on the webpage.
5. Users can search for movies using the search bar.

## Conclusion

This project demonstrates how to build a dynamic web application using HTML, CSS, and JavaScript by integrating an external API to fetch and display movie information.
