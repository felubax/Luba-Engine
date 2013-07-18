Luba-Engine
===========

A 2D Videogame Development Engine based on SDL/OpenGL made on C++

Projected progress:
%2 -> [#-------------------------------------------------]

Librerias usadas:
* SDL

Librerias externas:
* SDL_image


#1: Which is the idea?
The idea is not to be an innovative 2d engine. This is a challenge for myself and any of the amateur C++ developers 
that want to join the project. Exchange ideas, team-work methodologies, and more. The main objective to make a Game Development Engine is to ease the game structure coding,
so, just to think about it, what comes to our minds are functions and processes that integrates 
tons of functions of SDL/OpenGL in just one Luba Engine function.

#2: I don´t like the Engine name.
Who the f%!k cares? This project aims to be a technical-practice to learn methodologies and algorithms between the 
project contributors, this is just to get better, the name will not impact on that.

To be continued..

===========

Objectives:
===========
#1: Print a sprite:
First objective I think we can do. Code the initialitation functions, and Luba-Engine functions for the Sprites creation, and Print-on-screen processes.

We will need:
* A function for SDL/OpenGL init: LE::Init()
* A function for SDL/OpenGL display flip: LE::UpdateDisplay()
* A function for SDL/OpenGL surface freedom and QUIT: LE::Finish()
* An optimized image loading function: LE::LoadImage(path)
* An entity class for Sprites: LE::Sprite()
* An optimized Sprite blitting to the screen surface: LE::BlitSprite(sprite)

Ideas:
* screen should be a hidden entity

_STATUS: Not init
