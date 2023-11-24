= Tic-Tac-Toe Game README

This repository hosts a C implementation of the classic Tic-Tac-Toe game. It includes both player-vs-player and player-vs-computer modes, with the latter featuring three difficulty levels: easy, medium, and hard.

== Features

* *Player vs Player Mode*: Enables two players to compete against each other.
* *Player vs Computer Mode*: A single player can play against the computer, which has three difficulty levels: easy, medium, and hard.
* *Score Tracking*: Tracks the scores of each player across games.
* *Board Reset*: Automatically resets the game board after each match.

== Requirements

To run this game, ensure that you have a C compiler like GCC installed on your system.

== Installation

. Clone the repository or download the source code.
. Compile the code using a C compiler. For example, with GCC:
+
[source,bash]
----
gcc -o tic_tac_toe tic_tac_toe.c
----
. Run the compiled program:
+
[source,bash]
----
./tic_tac_toe
----

== Usage

Follow the on-screen instructions after running the program. Choose between playing against another player or against the computer. In the player-vs-computer mode, you can select the difficulty level.

== Game Rules

* The game is played on a 3x3 grid.
* Players alternate turns to mark a space on the grid with their symbol (X or O).
* The first player to get three of their symbols in a row (vertically, horizontally, or diagonally) is the winner.
* If all spaces are filled and no player has three in a row, the game is a draw.

== Contributions

Feel free to fork the repository and submit pull requests to contribute to this project.

