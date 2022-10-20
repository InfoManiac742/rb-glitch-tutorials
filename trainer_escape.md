# Trainer Escape Glitch

This tutorial explains the process of setting up the trainer escape glitch (also known as Trainer-Fly or the Mew Glitch), as well as a simplified explanation of how the glitch works.

## Overview
The trainer escape glitch allows the player to interrupt the process of being spotted by a player. After battling another trainer to fix some side effects, returning to the map where the glitch was initiated will allow the player to battle a Pokémon with the index number matching the special stat of the last Pokémon fought.

## Part 1: Setting up the glitch
There are two ways to initiate the trainer escape glitch: with a long-range trainer or with a death warp. We will examine each of these in turn.

### Method 1: Long-Range Trainer
#### Requirements
1. An undefeated long-range trainer
2. Fly, Teleport, Dig, or an Escape Rope (depending on the area the long-range trainer is in)

A long-range trainer is a trainer such that it's possible for the player to enter the trainer's line of sight immediately after scrolling them on-screen.

Here are some examples of long-range trainers:  
<img src=long_range_trainer_1.gif>
<img src=long_range_trainer_2.gif>
<img src=long_range_trainer_3.gif>
<img src=long_range_trainer_4.gif>

This is not a long-range trainer because her line of sight is only three tiles long instead of four:  
<img src=not_long_range_trainer_1.gif>

This is also not a long-range trainer because even though his line of sight extends to the edge of the screen, the cliff face prevents us from scrolling him on-screen at the same time he catches us:  
<img src=not_long_range_trainer_2.gif>

#### Execution
1. Position yourself so that the trainer is just off-screen.
2. Press the direction on the D-pad to move into the trainers line of sight while simultaneously scrolling them on-screen.
3. Once you start walking to the next tile, **hold** (do not tap) the Start button. (You have 17 frames to make this input, or around 0.28 seconds.)

If you did everything correctly, the Start menu should pop up while in the trainer's line of sight without them spotting:  
<img src=trainer_fly_1.gif>

4. Use Fly/Teleport/Dig/an Escape Rope.

The trainer will then spot you, causing the <img src=exclamation.png> icon to appear, but you will escape before they walk over to you and start the battle.

Here is an example of the process in full:  
<img src=trainer_fly_2.gif>

### Method 2: Death Warp
#### Requirements
1. An undefeated trainer in front of a tile where wild Pokémon can be encountered
2. Patience and/or luck

This method is much simpler than the long-range trainer method, but it is luck-dependent.

#### Execution
1. Save next to the trainer.
2. Step into the trainer's line of sight and hope for a wild encounter. If there is no encounter, reset the game and try again.
3. Once a wild Pokémon has been encountered, lose the battle and black out.

As you black out, the trainer engaged music will play, and the <img src=exclamation.png> icon will appear for a split second.

<img src=death_warp.gif>

## Part 2: Explanation
For exactly one frame after they appear on-screen, trainers are incapable of detecting a player. This lets us perform an action (in this case, opening the menu) during that one frame. By holding down the Start button while the character is moving, we can buffer our Start input so that the menu pops up on the first possible frame. Because the game is essentially "paused" in the Start menu, the trainer will not catch us until we close the Start menu. When we escape the trainer (such as by flying away), the game unpauses itself, and the trainer catches us and begins the process of moving towards us. However, we immediately cancel this when the map is unloaded, but the game still remembers that there is supposed to be a trainer battle 
