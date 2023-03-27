# Escape-The-Maze
Escape the Maze is a simple multiplayer game that involves navigating through a maze to reach the end point before your opponent does. The game is built using the Pygame library for the graphical interface and Socket programming in Python for the multiplayer aspect. The game allows players to connect over a network and compete in real-time to reach the end of the maze.

To play the game, players need to first start the server and then connect to it using the client. Once both players have connected, they will be taken to the game screen where they can navigate through the maze using the arrow keys. The first player to reach the end of the maze wins the game.

## Requisites
Python 3.x and pygame.

## Instructions
You need to run the server first
> python server.py

Then you can execute the client up to four times
> python client.py

#### Important 

- Wait for the client to load before executing the next

- The server needs to be restarted whenever the match ends or a player is disconnected
