= Tic-Tac-Toe Game (C)

== Overview

The Tic-Tac-Toe Game is a simple yet engaging implementation of the classic game in C. It offers modes for player-vs-player and player-vs-computer gameplay, with the latter featuring three levels of difficulty: easy, medium, and hard. The system is designed with a console-based interface for straightforward interaction.

== Key Features

- *Player vs Player Mode:*
  - Two players can compete against each other.
  
- *Player vs Computer Mode:*
  - Single player mode against the computer.
  - Three difficulty levels: easy, medium, and hard.

- *Score Tracking:*
  - Keeps track of the scores of each player across multiple games.

- *Board Reset Functionality:*
  - Automatically resets the game board after each match.

- *Console-Based Interface:*
  - Users can easily interact with the game through a console-based interface.

== Usage

1. *Clone or Download the Source Code:*
   - Get the source code from the repository.

2. *Compile the Code:*
   [source,bash]
   ----
   gcc -o tic_tac_toe tic_tac_toe.c
   ----

3. *Run the Compiled Program:*
   [source,bash]
   ----
   ./tic_tac_toe
   ----

== Game Rules

- The game is played on a 3x3 grid.
- Players take turns to mark a space on the grid with their symbol (X or O).
- The first player to align three of their symbols vertically, horizontally, or diagonally wins.
- If the grid is filled and no player has aligned three symbols, the game is a draw.

== Contributions

Contributions to this project are welcome. Feel free to fork the repository and submit pull requests.

