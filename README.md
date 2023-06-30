# Scrabble Game
This is a JavaFX implementation of the Scrabble game using the Model-View-ViewModel (MVVM) architecture and Observer-Observable design pattern. The game operates with Server-Socket and has two modes: Guest and Host mode. This project was developed as part of a college course and demonstrates knowledge of advanced programming concepts, including design patterns, object-oriented programming, and user interface design.

## Team
[Tal Zigelnik](https://github.com/zigelnik)<br />
[Or Shimon](https://github.com/Orshimon810)<br />
[Jonathan Cewingel](https://github.com/JoniXDrama)<br />
[Tal Lovton](https://github.com/TalLovton)

## Planning
<img src="https://github.com/zigelnik/Scrabble/assets/107995222/ca366541-eabe-4f1b-9beb-acd700e6afbf" width = "200" height = "200">
<img src="https://github.com/zigelnik/Scrabble/assets/107995222/7a2a4c10-74b9-42f4-b714-7dd72b0a7d1d" width = "200" height = "200">
<img src="https://github.com/zigelnik/Scrabble/assets/107995222/3d1b48b9-d3eb-4e8d-9eeb-571f55ce4637" width = "200" height = "200">
<img src="https://github.com/zigelnik/Scrabble/assets/107995222/ecf1b71d-1429-44e8-9063-3e21cbddb26d" width = "200" height = "200">


## Usage

**Host Mode**

In Host mode, the player starts a new game and waits for other players to join.
Start the application and select the Host mode.
Enter a username and a port number.
Click on the "Start Game" button to start the game.
Wait for other players to connect to your server.

**Guest Mode**

In Guest mode, the player joins an existing game hosted by another player.
Start the application and select the Guest mode.
Enter a username, a server IP address, and a port number.
Click on the "Join Game" button to join the game.

## Playing the Game
Once the game has started and the players have joined, the game board will be displayed at the center of the window. Each player will have a row of tiles at the bottom of the window representing their hand.
To make a move, the player can select a tile from their hand and drag it on an empty cell on the board. 
The game ends when a player has used all of their tiles or when there are no more valid moves left on the board. The player with the highest score at the end of the game wins.

## Getting Started
1. Clone this repository: git clone https://github.com/zigelnik/Scrabble.git


## Project Structure
The project is structured using the MVVM architecture and Observer-Observable design pattern. The purpose of this architecture is to separate the user interface from the underlying data model, making the code easier to read, maintain, and extend. The project is divided into three main packages:

**Model**: Contains the server and client communication methods, data model classes for the game, including the Scrabble board, tiles, and players. The classes in this package are responsible for the game's logic and state.

**View**: Contains the JavaFX view classes for the game, including the game board, player tiles, and game windows. The classes in this package are responsible for displaying the game's user interface and handling user input like name and ip/port.

**ViewModel**: Contains the view model classes for the game, which handle the game logic and communication between the model and view. The classes in this package act as intermediaries between the model and view, responding to user input, binding it to model's varbiable and updating the view accordingly.


## Demo
[<img src="https://i.imgur.com/yREfMT3.jpg" width="50%">](https://www.veed.io/embed/1c0e96a9-bece-497a-9792-cf6a589743ee)
