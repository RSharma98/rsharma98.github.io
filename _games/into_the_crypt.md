---
title: Into The Crypt
release_date: 17/04/2019
genres: 2D Platformer, Roguelike
game_engine: Unity and C#
dev_team: Independent
source_code: 
platforms: PC and Mac
images: 
    - /images/games/into_the_crypt/Filled_Level.png
    - /images/games/into_the_crypt/Empty_Level.png
    - /images/games/into_the_crypt/Main_Menu.png
    - /images/games/into_the_crypt/Skeleton_AI.gif
layout: default
---
Into The Crypt is a procedurally generated 2D Platformer I am developing for my final year project at university. The procedural generation system for the game provides a variety of possibilities for types of games in which it can be implemented, however, the game is not yet complete. Once the game is complete, I plan to open source and improve the project (especially the procedural generation system), to allow other developers to implement the system into their games.
<br><br>
The game generates levels by splitting each level into rooms (for example, a 4x4 grid), picking a start room (in top row) and end room (in bottom row) and creating a path to connect these two rooms. The rooms in this path path are then generated using pre-designed level sections and probability (this provides a balance of hand-made level design and randomness), and these rooms are then also filled with enemies and spikes (also based on probabilities and the type of room) to provide challenge to the player.
<br><br>
Along with the implementation of a procedural generation system, many other systems were implemented for the game. For example, a camera system, simple health system, collision system, and character controller. Alongside that, many efficient programming practices were applied to this project, for example, the use of Object Oriented Programming (OOP), efficient data structures and algorithms, and the use of singletons. The end result is a complete game which runs smoothly on many types of devices without any issues.
<br><br>
The source code for this game is currently unavailable due to awaiting moderation and feedback from the university. However, once that process is complete the source code will be available on my Github profile. 