# Recipe Finder

Recipe Finder is a responsive web application for discovering meals from around the world. Users can search by meal name or keyword, browse matching recipe cards, and open a detailed view containing the meal category, ingredients, measurements, cooking instructions, and an optional YouTube tutorial.

The application uses [TheMealDB API](https://www.themealdb.com/api.php) for recipe data and is built with HTML, CSS, and vanilla JavaScript, so it does not require a framework or build step.

## Features

- Search for recipes by meal name or keyword
- Display recipe images, names, and categories
- View ingredients, measurements, and cooking instructions
- Link to a YouTube recipe video when one is available
- Show helpful validation, empty-result, and API error messages
- Adapt the layout for desktop and mobile screens

## Skills demonstrated

This project demonstrates practical front-end web development skills, including:

- Writing semantic HTML and connecting page structure to JavaScript
- Creating responsive layouts with CSS Grid, Flexbox, media queries, and custom properties
- Fetching data from a REST API with `fetch`, `async`, and `await`
- Parsing JSON and transforming API data into dynamic HTML
- Using DOM selection, event listeners, event delegation, and class-based UI state
- Handling user input, missing results, and network errors
- Working with template literals, arrays, loops, and conditional rendering
- Integrating third-party services such as TheMealDB and Font Awesome

## Run locally

No installation is required. Open `index.html` in a browser, or serve the folder with a local development server. An internet connection is required to load recipe data and Font Awesome icons.

## Project files

- `index.html` defines the application structure.
- `style.css` provides the responsive design and visual styling.
- `script.js` handles searching, API requests, rendering, and recipe details.
