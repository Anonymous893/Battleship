# Battleship

This is a simple Battleship game developed using Java and utilises object oriented programming concepts. The game is played between two players and each player places their fleet of ships on a 10 x 10 board. The objective is to sink all of the opponent's ships.

##### Rules
At the beginning of the game, a board with the random placement of the five ships will be generated. Each player has a board showing their hits and misses on their opponent’s ships.

![Alt text](/Screenshots/Board.png?raw=true "Optional Title")

A _0_ represents an unattacked spot. 

Both players will take turns to enter their coordinates in the format of A1. The left character is a capital letter from A to J while the right character is a number from 1 to 10.

As the game progresses, the board will begin to change in response to the coordinates picked by the player. 

A _1_ represents a missed attack while a _2_ represents a hit.

![Alt text](/Screenshots/BoardInAction.png?raw=true "Optional Title")

A player’s goal is to sink all of their opponents ships. There are five ships and their lengths are listed below:

   * Aircraft Carrier - 6 spaces
   * Battleship - 5 spaces
   * Cruiser - 4 spaces
   * Destroyer - 3 spaces
   * Submarine - 2 spaces

At the end, once a player has won, a winning message will be displayed.

![Alt text](/Screenshots/WinningMessage.png?raw=true "Optional Title")

#### Installation 
To run this game, just download the files and run the BattleDriver.java file. I used the Eclipse IDE to work on this project.

#### Lessons and Other Comments
I created this game for fun and to practise my Java skills and knowledge of object oriented programming.
