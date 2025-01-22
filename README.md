# Made This in README.md

Welcome to the Made This project! This repository is a demonstration of different methods for making API calls in JavaScript, featuring various approaches from traditional XHR to modern async/await syntax.

## Overview

This application demonstrates four different ways to make API calls:

1. Using XMLHttpRequest (XHR)
2. Using the Fetch API with promises
3. Using Fetch with async/await
4. Using a custom XHR implementation with async/await

The app fetches posts from the JSONPlaceholder API and displays them in a styled list.

## Project Structure

```
├── index.html          # Main HTML file
├── style.css          # Styling
└── main.js            # JavaScript implementation
```

## Installation

1. Clone the repository
```bash
git clone [repository-url]
```

2. Open `index.html` in your browser

## Usage

The project demonstrates different methods to fetch data. By default, it uses the XHR with async/await method. To use other methods, uncomment the desired function call in `main.js`:

```javascript
// fetchUsingXHR();
// fetchUsingFetchMethod();
// fetchUsingAsyncAwaitMethod();
fetchUsingXHRAndAsyncAwait();
```

## Features

- Multiple API call implementations
- Clean and responsive UI
- Error handling
- Modern styling with Flexbox
- Real-time data display

## Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript
- JSONPlaceholder API
