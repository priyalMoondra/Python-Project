Pygame is a python library that can be used specifically to design and build games. Pygame supports only 2d games that are built using different sprites.
Pygame is not particularly best for designing games as it is very complex to use doesn’t have a proper GUI like unity but it definitely builds logic for further complex projects.
We’ve created a simple game with the following rules:-
The player can only move vertically. 
Other than player block there will be two other blocks. 
One of them will be the enemy block and one of them will be score block. 
If the player collides with the enemy block then the game over screen pops up, if the player collides with the score block the score is incremented and it is compulsory to collect all score blocks. 
Before initializing pygame library we need to install it. To install it type the below command in the terminal.
 // pip install pygame // 
After installing the pygame library we need to write the following lines to initialize the pygame library:-
import pygame
pygame.init()
