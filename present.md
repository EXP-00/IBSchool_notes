# Presentation of project Dead Voxel

## inspiration and dissection of inspiration
- My project is inspired by two games, Hades and Ultrakill
- The player controls a machine in an otherworldly environment, with their HP constantly depleting, they have to destroy enemies to survive.
- This mechanic is inspired by Ultrakill, where in it the player is a robot fueled by organic blood. thus, the only way to heal in that game is to get close to enemies and deal damage, which then spills blood on the player. This encourages the player to interact with the environment constantly and makes healing part of the main gameplay loop.

## Main premise
- The game is fast paced, but few of the enemies have ranged attacks. Thus, they are given great speed to catch up with the player. The player has a variety of ranged and melee weapons to choose from, but the main combat experience always involves being aware of your environment, and avoiding the enemy attacks in the easiest way. Distance keeping is thus overpowered in this game, so the levels are also very constricting in order to limit the player.
- **game flow diagram**

## Important gameplay system
- the most complex system is by far the catalyst system, my game's accessory system.
- In the early development stages, the player only had three slots, and the catalysts doesn't really have a clear function. Some gave you great speeds, some gave you lightning chains when you hit a enemy, and some let you activate an ability to send a shockwave.
- after analyzing the boons in Hades, I found that they are all passive abilities, and effects are either defensive, or offensive only when the player attacks.
- so I structured the catalysts the same way. Each only does one specific function and task, and the player is no longer limited to 3 slots. I made sure to make everything get exponentially stronger as the game progress, so I made the player able to upgrade their slots from 1-6 slots, and make it so they can equip up to five stacks of each catalyst, which all stacks correspondingly.
- For example, entanglement will initiate a echo attack at 50% damage on the enemy after a hit for 50% chance. every extra stack will add 50% to chance factor, with each 100% meaning it can shoot more then one echo shot at once.

## Vfx and artistic choice
- the game is called dead voxels, partly because everything is in a low poly style and the Vfx are also mostly cubic.
- **pictures of various vfx**
- For the design of the levels and enemies, the walls have highly reflective white edges to create a sharp and cold environment, while the enemies emit red light in order to direct the player's attention.

## Music
- the music uses orchestral instruments, but also the organ, in order to create a profaned feel to the game and to contrast with the simple environment of the levels. It tells a story about the enemies themselves which the player finds out that the music is the embodiment of their pain trapped in the asylum forever fighting to the end.

## Complex enemy behaviors
- **flowchart of enemy behavior**
- pictures of improtant code
