Here's a comprehensive README file for your movie library web application. This README includes instructions on how to set up, run, and use the application.

```markdown
# Movie Library Web Application

This is a movie library web application built with React. It allows users to search for movies, add them to their favourites, and remove them from favourites. The application uses the OMDB API to fetch movie data.

## Features

- Search for movies using the OMDB API
- Add movies to favourites
- Remove movies from favourites
- Local storage to save favourites

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js installed on your machine. 
## Getting Started

To get a local copy up and running, follow these simple steps.

### Installation

1. Clone the repository:

```bash
git clone https://github.com/2001akash/Movie-App
```

2. Navigate to the project directory:

```bash
cd movie app
```

3. Install the dependencies:

```bash
npm install
```

### Running the Application

1. Start the development server:

```bash
npm start
```

2. Open your browser and navigate to `http://localhost:3000` to see the application running.

## Project Structure



## Usage

1. **Search for Movies:**
   - Use the search box to type in the name of the movie you want to search for. The application will fetch and display the movies that match your search query.

2. **Add to Favourites:**
   - Click on the "Add to Favourites" button that appears over a movie poster to add the movie to your favourites list.

3. **Remove from Favourites:**
   - Click on the "Remove from Favourites" button that appears over a movie poster in your favourites list to remove the movie from your favourites.

## Components

- **AddFavourites:** Component for the "Add to Favourites" button.
- **RemoveFavourites:** Component for the "Remove from Favourites" button.
- **MovieList:** Component to display the list of movies.
- **MovieListHeading:** Component for the heading of the movie list.
- **SearchBox:** Component for the search input box.



## Acknowledgements

- [OMDB API](http://www.omdbapi.com/)
- [React](https://reactjs.org/)
- [Bootstrap](https://getbootstrap.com/)



