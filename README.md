# Console Minesweeper

This is a console (No GUI) implementation  of minesweeper written in java with OOPS using five classes.



### Cell class

This class contains information about the state of the cell and methods to modify them
and a cell board matrix.


### Board class

This class initializes the cell board matrix with input size. 
It randomly generates mines and sets the number of mines in proximity.
It also contains the method to print an array.


### Run class

This class controls the main game flow. 
It has methods to reveal a cell and cascading reveal(if applicable).
It can set or remove a flag. 


### MineSweeper

This class is the entry point of the program.
It has the game loop and method to determine if the player wins or loses.
It can exit the game or start new game if player wins or loses.


### Tools

This class was used during development and testing and is not used by the main program.
It has method to reveal all the cells and hide the cells earlier revealed by the reveal method.

