# Movie Search App

This is a movie search application built using ReactJS that allows users to search for movies using the OMDB API. Users can input movie titles in the search bar, and the application will fetch and display a list of movies matching the search criteria.

## Features

-   **Search Movies**: Users can enter a movie title in the search bar and click the search icon to initiate a search.
    
-   **Display Results**: The application will display a list of movies matching the search criteria, complete with movie posters and basic information.
    
-   **No Results Message**: If no movies are found for the given search term, a "No movies found" message is displayed.
    

## Prerequisites

Before you begin, ensure you have met the following requirements:

-   [Node.js](https://nodejs.org/) installed on your machine.
-   An API key from [OMDb API](https://www.omdbapi.com/). You'll need to create an account and get an API key. Make sure to set it as an environment variable in your project.

## Installation

1.  Clone the repository to your local machine:
    
```bash
git clone https://github.com/zanellafernanda/movie-search.git
```
    
2.  Change to the project directory:
    
```bash
cd movie-search-app 
```
3.  Install the project dependencies:
    
```bash
npm install
```
4.  Set your OMDB API key as an environment variable. You can do this by creating a `.env` file in the project's root directory and adding the following line:
    
```bash
REACT_APP_OMDB_API_KEY=YOUR_OMDB_API_KEY
```
    
5.  Start the development server:
    
```bash    
npm start
```
    
6.  Open your browser and go to [http://localhost:3000](http://localhost:3000/) to use the application.
    

## Usage

1.  Enter a movie title in the search input field.
    
2.  Click the search icon or press Enter to initiate the search.
    
3.  The application will display a list of movies matching the search criteria.
    

## Dependencies

-   [React](https://reactjs.org/): A JavaScript library for building user interfaces.
-   [OMDb API](https://www.omdbapi.com/): The Open Movie Database API used for fetching movie data.

## Contributing

1.  Fork the project.
    
2.  Create your feature branch:
    
```bash
git checkout -b feature/your-feature
```
    
3.  Commit your changes:
  
  ```bash
 git commit -m 'Add some feature
 ```
    
4.  Push to the branch:
    
```bash
git push origin feature/your-feature
```
    
5.  Create a new Pull Request.
    

## Contact

If you have any questions or suggestions, please feel free to [contact me](https://www.linkedin.com/in/fernanda-zanella/).

----------

Enjoy searching for your favorite movies with the Movie Search.
