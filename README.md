# Breakout
This repo contains 3 executable jar files for different iterations of the Atari game "Breakout", due to the fact that I developed this as part of a project for university I am unfortunately not allowed to share the source code and this is why there are only the compiled executables. Requires atleast JDK-17 to run correctly, note that the game is not fairly balanced as this was not the main focus of this project.

## Iteration 1 
A very basic implementation of the breakout game serves as a template for the further iterations. 

## Iteration 2 
More advanced version where there are different types of blocks which do different things, the sturdy block which has 3 lives and also has to get hit by a sufficiently fast ball to break. The replicator block changes the paddle to 3 distinct colors indicating that the next time a ball bounces on the paddle 3 new balls will spawn alongside it at the blue portals (2 for the next hit and so on). Lastly there is a supercharged block which increases the ball size aswell as removing the collision from the blocks, this implies that the ball moves through the blocks while breaking them without bouncing off them (unless it is a sturdy block). 

## Iteration 3 
Alongside balls there are now alpha particles which do not collide with the blocks but only the walls and the paddle. Depending on the amount of alphas that are linked with each ball different behaviour occurs when the alpha particles bounce on the walls (either repelling it or attracting it). 
