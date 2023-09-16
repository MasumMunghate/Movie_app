# Movie_app

getMovie(): This function is triggered when the button (btn) is clicked. It does the following:
 Clears the previous search results from the root element.
 Retrieves the movie name entered by the user from the movie input field.
 Uses the OMDB API (a movie database) to search for movies using the entered movie name.
 Processes the response from the API and extracts movie information (title, year, poster) for each movie in the search results.
 Calls another function, getMovies(movie), for each movie to create a new HTML element for displaying the movie information.
 Appends the new HTML elements to the root element.

getMovies(movie): This function creates an HTML structure to display the movie information (title, year, poster) for each movie. It creates a new div for each movie and appends it to the root element.
Event Listener: btn.addEventListener("click", getMovie): This event listener is triggered when the search button (btn) is clicked. It calls the getMovie() function, initiating the movie search based on the user's input.
