I know this is late submission but will be happy if I get at least partial credit. Thank you.




Database class holds an ArrayList of Movie objects.

The database can be saved to a text file and also read in Movie objects from text file.

Constructor for objects of class Database Takes in ArrayList of Movie objects that is set to the class field.


Constructor for objects of class Movie with provided movie fields takes as arguments:
 movieTitle, movieDirector, movieActor1, movieActor2, movieActor3,movieRating.

throws FileNotFoundException if provided filename does not exist (in same directory as this program)
throws IllegalStateException if format of line with Movie information does not conform to what was expected
throws IOException if any file reading errors


saveMoviesToFile functiion Saves all movies in database to specified file, If file already exists it will be overwritten.


