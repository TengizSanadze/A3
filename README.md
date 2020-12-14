This was one of those first code I wrote wich had couple variables and loops in it. After that I learned a lot modified code.It  has constructor for objects of class Database,
scanner to Read one line of the text file into a string, line split to Split the line by comma into a String array, function to Add a movie to the database, throw a NullPointerException if object in argument is not set,  another function to Deletes all the Movie objects in the current database ArrayList, another function to Displays all movie titles in the database and a lot more. 


Database class holds an ArrayList of Movie objects.

The database can be saved to a text file and also read in Movie objects from text file.

Constructor for objects of class Database Takes in ArrayList of Movie objects that is set to the class field.


Constructor for objects of class Movie with provided movie fields takes as arguments:
 movieTitle, movieDirector, movieActor1, movieActor2, movieActor3,movieRating.

throws FileNotFoundException if provided filename does not exist (in same directory as this program)
throws IllegalStateException if format of line with Movie information does not conform to what was expected
throws IOException if any file reading errors


saveMoviesToFile functiion Saves all movies in database to specified file, If file already exists it will be overwritten.


