---
title: Into The Crypt
release_date: 17/04/2019
genres: 2D Platformer, Roguelike
game_engine: Unity and C#
dev_team: Independent (School Project)
source_code: 
download: https://drive.google.com/file/d/1hDErt2SzTbh4mqt9IOEFf-rExq65xEQj/view?usp=sharing
platforms: PC and Mac
images: 
    - /images/games/into_the_crypt/Filled_Level.png
    - /images/games/into_the_crypt/Empty_Level.png
    - /images/games/into_the_crypt/Main_Menu.png
    - /images/games/into_the_crypt/Skeleton_AI.gif
videos:
    - https://youtu.be/jHPvtC61ZAE
layout: default
---
Into The Crypt is a procedurally generated 2D Platformer I developed for my individual final year project at University. The game was fully designed and programmed by me, however, assets (such as art and audio) were obtained from internet sources and some guidance was provided throughout the project by my project supervisor. Although this game was submitted for my final year project, my hope is to further develop the procedural generation system and open source it to allow it to be used by other developers without the need to invest resources into developing the system from scratch.
<br><br>
The goal with this game was to develop a 2D Platformer that utilises a procedural generation system for the level design to provide levels with a mix of randomness and hand-made design to provide authentic replayable levels. This system was implemented over six months from scratch through plenty of reading and additionally many other systems were implemented to compliment the procedural generation system - such as a physics system, health system, camera system, enemy AI system, along with some other minor systems.
<br><br>
The procedural generation system in the game is heavily inspired by Spelunky, where the level is split into rooms and a path is made between two rooms (the start room - picked randomly from top row and the end room - picked randomly from bottom row) by moving left/right and down. Each room in this path is then split into different room types - start, end, corridor, drop, and landing - and this room type determines which level template is used to fill the tiles in the room 
and then applies some mutation to the tiles to provide some variation. The final step of this level generation process is filling the room with enemies, spikes, and coins based on the type of room, probability, and the exact layout of the room.
<br><br>
Throughout the development of this game I learnt and applied many good programming practices to this project - for example the use of Object Oriented Programming (OOP), efficient data structures and algorithms, and the use of singletons. The end result is a complete game which runs smoothly on many types of devices without any issues (as proven by public testing). 