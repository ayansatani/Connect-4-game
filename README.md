# Connect 4 Multiplayer Game

## Overview
This is a **multiplayer Connect 4** game built using **Java**. The game uses the **TCP protocol** to connect two laptops under the same network to play the game in real-time. It allows two players to take turns, dropping their pieces into a grid, and the game checks if any player has won after each move. This project is a simple implementation of the classic Connect 4 game with multiplayer functionality over a local network.

## Features
- **Multiplayer Gameplay**: Play Connect 4 with a friend over a local network (two laptops).
- **TCP Protocol**: Uses TCP for communication between the two laptops.
- **Turn-based Play**: Players alternate turns, selecting columns to drop their pieces into the grid.
- **Winner Detection**: Automatically detects when a player has won (horizontal, vertical, or diagonal line of 4).
- **Simple Interface**: Console-based interface to interact with the game.

## Requirements
- **Java 8 or higher**: Ensure Java is installed and set up on your system.
- **Two laptops**: Both laptops must be connected to the same local network (Wi-Fi or Ethernet).
- **Run the code**: You’ll need to run the JAP_CompileScript.bat file to generate the JAPLabsSwing.jar file in bin folder or simply run the main file.

## How to Use

### 1. Clone the Repository
Clone the repository to your local machine using the following command:
```bash
git clone https://github.com/ayansatani/Connect-4-game
