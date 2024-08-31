# Connect_4-java

A simple console-based implementation of the classic Connect 4 game in Java.

## Introduction

Connect4 is a two-player connection game in which the players take turns dropping colored discs from the top into a vertically suspended grid. The objective of the game is to be the first to form a horizontal, vertical, or diagonal line of four of one's own discs.

This project is a simple Java-based implementation of Connect4 that can be played in the console. Players 'A' and 'B' can take turns to drop their discs into one of the seven columns until one player wins or the board is full.

## How to Play

- Players choose a column number to drop their discs into the grid.
- The game alternates turns between Player 'A' and Player 'B'.
- The first player to align four of their discs vertically, horizontally, or diagonally wins.
- If the board fills up completely without any player forming a line of four discs, the game ends in a tie.

## Installation

1. Ensure you have Java installed on your computer. You can download it from [here](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html).

2. Clone the repository or download the source code:

    git clone https://github.com/kaviyasrinivasan/connect_4-java.git
    cd connect_4-java

3. Compile the Java program:
    javac Connect_4.java
   
   To start the game, run the following command in your terminal:
    java Connect_4
