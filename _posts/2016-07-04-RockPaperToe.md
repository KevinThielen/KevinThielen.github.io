---
layout: post
title: "RockPaperToe"
excerpt: "Mobile Multiplayer Game as Software Engineering coursework"
categories: [Java, Android, Networking]
comments: false
image:
   feature: RockPaperToe/feature.png
---

## About the Game
Rock Paper Toe is a multiplayer game for Android, written in Java and uses a Wildfly server as backend. 
The game was created as coursework for the module Software Engineering I as a four-man project.

It follows the same rules as TicTacToe, with the exception of the symbols. Instead of the symbols
"X" and "O", the player place either a "Rock", "Paper", or "Scissor", matching his own color. If the symbol "wins" against the adjacent symbols(following Rock-Paper-Toe-rules), their respective colors are changed into the current players color. If any three symbols of the same color are aligned in a horizontal, vertical or diagonal line, the player with the matching color wins the game.  

## Responsibilities
On the server side(Webservice, JavaEE/Wildfly), I worked on the login, matchmaking and gameplay.  
I also implemented the server-client-communication via soap(ksoap2), login and gameplay in the app.

The other members were responsible for the art, highscores and menus.

## Screenshots
![GameList](/img/RockPaperToe/gamelist.png)
![Highscores](/img/RockPaperToe/highscor_filled.png)
![Ingame](/img/RockPaperToe/ingame.png)
![MainMenu](/img/RockPaperToe/main_menu.png)
