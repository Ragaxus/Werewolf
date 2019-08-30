# Werewolf
An online multiplayer version of the social deception game Werewolf, and currently a work in progress. This project is a learning experience for me in regards to socket programming. 

This is a Javascript application running on a node express server. I am using the socket.io package as a wrapper for Javascript Websocket.

This is meant to facilitate the game in the absence of a card deck - not control all aspects of the game flow. Eventually, the app will allow players to create or join a game lobby where state is synchronized. The creator of the game will have created a deck with certain roles in it, and once the game begins, this deck will be randomly dealt to all participants. 

Players will see their card, an optional timer, and an option to say that they have been killed off. If a player presses said button, they will be removed from the game, and their role revealed to other players. The game will continue until the end of the game is detected.

# Run Locally

Run node server.js from the root directory, navigate to localhost:5000
