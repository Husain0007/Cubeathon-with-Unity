# Cubeathon - A game of cubes for cube enthusiasts

Cubeathon is my first foray into Game Development made possible on Unity Version 2019.3.12f1


## Gameplay

![alt text](https://github.com/Husain0007/Cubeathon-with-Unity/blob/master/Start.png "Starting Out")

The player agent is a physics based sliding cube that glides across a plane populated with blue cubes.  
The game is made up of 3 levels of increasing difficulty.  
The navigational controls are limited to   
*a* -> for left movement  
*d* -> for right movement  
<br>
The player **wins** by completing the obstacle course  

If the player falls off the platform:  
![alt text](https://github.com/Husain0007/Cubeathon-with-Unity/blob/master/Lose1.png "Lose1")  
or collides into a another cube:  
![alt text](https://github.com/Husain0007/Cubeathon-with-Unity/blob/master/Lose2.png "Lose2")  
the player **loses** 

## Installation  
To make a user-friendly installation process I've used the [Inno SetUp Compiler](https://jrsoftware.org/isdl.php).  
With *Inno-SetUp* I have created a **.iss file** that allows for a customizable setup process.
