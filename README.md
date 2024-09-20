# Vampire Survivors in Pygame
Author: Johnny Nguyen  
Email: johnny.nguyenha@gmail.com or johnnynguyenha@csu.fullerton.edu  
## Summary
"Vampire Survivors in Pygame" is a game developed by Johnny Nguyen made using Pygame. Pygame is a Python library that helps developers create games. "Vampire Survivors in Pygame" is inspired by the original game "Vampire Survivors", in which the player is surrounded by a constant stream of enemies and the player must eliminate them. "Vampire Survivors in Pygame" is a simple game where the player shoots enemies that spawn randomly around the player. The player must move and shoot at enemies to survive. If the player gets hit by an enemy, the player dies and the game is over. If the player shoots a bullet at an enemy and it hits, the enemy is destroyed. The gun of the player follows the cursor of the player, up to a max distance away from the player.
![{20971DAB-41BB-4F35-91E1-019D986B3DE7}](https://github.com/user-attachments/assets/06d9a62d-18c3-4f33-855b-31956d933a64)


## Elements
"Vampire Survivors in Pygame" showcases and utilizes various essential elements of game design.  
✓ Collisions  
✓ Music/Audio  
✓ Movement  
✓ Random Generation of Objects  
✓ Tilesets  
✓ Camera  
✓ Animation  
✓ Importing Sprites  
✓ Timers  
✓ Knowledge of Rects, Sprites, Image, Key Detection  
✓ Objected Oriented  
✓ Gun follows cursor based on angle between gun and player  

## Notes
- Enemies are randomly generated throughout the screen based on a tile system.  
- Gun is rotated based on the angle between cursor and player, and side of screen the cursor is at.  
- Masks are used, hitboxes are accurate.  
- Timers used to ensure player cannot shoot too fast or enemies spawn too fast.  
- Camera is fixed on player. As player moves, the camera does as well.  
- Bullets are deleted after a certain amount of time and when colliding with an enemy.  
- FPS of the game does not affect gameplay elements.  

## Controls
W - Move up  
A - Move left  
S - Move down  
D - Move right  
Left Click - Shoot bullet   

## Running
To run, Python must be installed. In addition, Pygame-ce and pytmx must be installed.   
Pygame can be installed via   
```
pip install pygame-ce  
or   
pip3 install pygame-ce  
```
Pytmx is used to import the tileset and can be installed via
```
pip install pytmx 
or   
pip3 install pytmx 
```
Afterwards, the game can be ran using 
```
python "main.py"  
or  
python3 "main.py"  
```
