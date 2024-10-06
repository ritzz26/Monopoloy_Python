# Monopoloy_Python
Python Monopoly Clone - OOP Application

## Game Design
The main entity is the GameMaster which is inherits the Board class so that the board can be used in the game. 
It stores the players and the owners of each property (for rent purposes).
The game logic is handled in the `interact` function.
This function calls other helper functions that implement certain aspects of the logic such as moving the player. 

## Playing the Game
In Version 1, the game runs automatically and rolls for each player, moving them to the next block and updating the cash values of each player, unless there is a purchase decision to be made. 
