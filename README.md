# Space Invaders Retro Game
This repository features a simple Space Invaders style video game. The code was part of a several chapter assignment from Python Crash Course Vol 2, written by Eric Matthes. A link to his book and online resources will be provided below.

https://ehmatthes.github.io/pcc_2e/regular_index/

# Important Notes: Adding manuverability
I modified the spaceship flight code to allow movement in both the x and Y directions. (The game originally only let the player shift left and right, or just X.) Although this modification makes the ship flight more manuvareble, it introduced a bug that needs to be fixed in the future. For example, if the player flies the ship straight up to collide with the group of aliens, the game gets stuck in a loop where the ship remains at the exact coordinates but the aliens attempt to descend to the bottom of the screen. This means there is a constant collision between the perimeter of the two objects. This triggers the end of the game, and leaves the ship in place.


