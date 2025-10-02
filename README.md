# **Game of 15**

## Description
The Game of 15 (also known as Fifteen Puzzle or Gems Puzzle) is a classic sliding tile puzzle.
The goal of the game is to arrange the 15 numbered tiles in numerical order by sliding adjacent tiles into the empty space. The game is played on a 4×4 grid.

## How it's written
The entire application is written in Java.
**GUI (Graphics):** Developed using Java Swing.
**Architecture:** A simple, standalone Java application.

![gameof15bild](https://github.com/user-attachments/assets/19d68b7b-af85-401f-bd47-31e60adfea9a)

## How to run the game
1. Clone the repository
2. Compile the source files
3. Start the game: Run the compiled GameWindow class

## Developer features
A cheat method is built into the code, allowing the game to be won by only moving a single tile.
How to activate the cheat mode:
Modify the method call inside the TileGenerator.actionPerformed() method to utilize the cheat logic instead of the standard winning condition check.

## Issues
Graphical Inconsistency: Some users may experience graphical issues where the game's appearance or behavior is inconsistent, especially when using multiple monitors or screens with different scaling/resolutions. 
This is likely due to Swing's reliance on the underlying operating system's graphical handling.

