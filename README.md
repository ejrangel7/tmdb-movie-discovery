# Movie App

A responsive movie discovery application built with vanilla JavaScript and The Movie Database (TMDB) API.

## Features

- Browse daily trending movies
- Search movies by title
- Explore movies by genre
- View movie posters, summaries, ratings, and details
- Discover related titles
- Navigate between home, category, search, and detail views

## Tech stack

- JavaScript
- HTML5
- CSS3
- TMDB API
- Responsive web design

## Project structure

```text
movie-app/
├── src/
│   ├── main.js         # API requests and rendering logic
│   ├── navigation.js   # View navigation
│   └── node.js         # DOM references
├── styles/             # Application styles
└── index.html          # Application entry point
```

## Run locally

This is a client-side application. Clone the repository and serve the project directory with any local static web server. Node.js and Python are not part of the application; they are only optional tools for starting a local server. Use either option below.

### Option 1 — Node.js (recommended)

If Node.js and npm are installed:

```bash
npx serve .
```

Open the local address displayed in the terminal, commonly [http://localhost:3000](http://localhost:3000).

### Option 2 — Python

On Windows, if Python is installed:

```bash
py -m http.server 8000
```

On macOS or Linux, if Python 3 is installed:

```bash
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000).

Only one of these options is required.

## What this project demonstrates

- Working with asynchronous API requests
- Rendering dynamic data in the browser
- Search and category filtering
- URL hash-based navigation
- Responsive interface development

## Current status

This is a functional learning project. Planned improvements include moving API configuration out of client-side code, adding loading and error states, improving accessibility, and introducing automated tests.

## License

Distributed under the MIT License.

## Author

[Edward Rangel](https://github.com/ejrangel7) — Senior Full Stack Software Engineer
