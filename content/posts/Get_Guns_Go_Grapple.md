---
title: "Get Guns Go Grapple [Capstone 3]"
date: 2022-07-15T15:23:16+08:00
draft: false
toc: false
images:
tags:
  - 3rd Capstone
---

## My Contributions

- Player Movement
- Player Shooting and Reloading
- Player Grappling
- Weapon Crate
- Player Skill


#### Movement

Made use of Unity's Physics velocity to move the player to make it easier to compute for the movement due to the grappling's mechanic.

#### Shooting and Reloading

Simply used Raycast for the shooting mechanic. For the reloading, I tried to use the animation events but it was so buggy since it couldn't be called for some reason so I ended up scratching it and just used Task for the wait time before the player can shoot again.

#### Grapple

I found 2 ways on doing the grappling mechanic in Unity. 1st way is by using Spring Joints and the other way is by manual computation of the swing of the player through player's rigidbody position and velocity. I chose to use the latter one for me to be able to understand the Rigidbody any further. I found a [github blog](http://shanekim.me/how-to-make-a-3d-grappling-hook.html) regarding this and used it for guidance. 



#### Weapon Crate

 There are originally 4 weapons in the game. Due to time constraints, I wasn't able to do a lot more complex coding for it. To be able to randomize it, I used the weight random system to be able to get random weapons. The weapon crate is only a one-time use and is subject to change once we finalize things for the future of the game.

 ![Weapon Crate](https://github.com/Jaxeetee/Jaxeetee.github.io/blob/main/resources/_gen/images/Weapon_Crate.png)

#### Player Skill

The original plan was to 

