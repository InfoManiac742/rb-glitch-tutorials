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
<img src=img/long_range_trainer_1.gif>
<img src=img/long_range_trainer_2.gif>
<img src=img/long_range_trainer_3.gif>
<img src=img/long_range_trainer_4.gif>

This is not a long-range trainer because her line of sight is only three tiles long instead of four:  
<img src=img/not_long_range_trainer_1.gif>

This is also not a long-range trainer because even though his line of sight extends to the edge of the screen, the cliff face prevents us from scrolling him on-screen at the same time he catches us:  
<img src=img/not_long_range_trainer_2.gif>

#### Execution
1. Position yourself so that the trainer is just off-screen.
2. Press the direction on the D-pad to move into the trainers line of sight while simultaneously scrolling them on-screen.
3. Once you start walking to the next tile, **hold** (do not tap) the Start button. (You have 17 frames to make this input, or around 0.28 seconds.)

If you did everything correctly, the Start menu should pop up while in the trainer's line of sight without them spotting:  
<img src=img/trainer_fly_1.gif>

4. Use Fly/Teleport/Dig/an Escape Rope.

The trainer will then spot you, causing the <img src=img/exclamation.png> icon to appear, but you will escape before they walk over to you and start the battle.

Here is an example of the process in full:  
<img src=img/trainer_fly_2.gif>

### Method 2: Death Warp
#### Requirements
1. An undefeated trainer in front of a tile where wild Pokémon can be encountered
2. Patience and/or luck

This method is much simpler than the long-range trainer method, but it is luck-dependent.

#### Execution
1. Save next to the trainer.
2. Step into the trainer's line of sight and hope for a wild encounter. If there is no encounter, reset the game and try again.
3. Once a wild Pokémon has been encountered, lose the battle and black out.

As you black out, the trainer engaged music will play, and the <img src=img/exclamation.png> icon will appear for a split second.

<img src=img/death_warp.gif>

## Part 2: Fixing the side effects
We've just successfully caused the game to start the process of beginning of a trainer battle. This means that we've essentially "stored" a trainer battle on the map where we set up the glitch, and can use this to manipulate a glitched battle when we next return to that map. However, there are two roadblocks that we need to clear first:

1. The Start menu and most textboxes are disabled. (This only applies if you used the long-range trainer method.)
2. Since the game started (but never finished) the process of having the trainer walk toward the player, the game still thinks that an NPC is being moved. Because of this, if we returned to the map where we initiated the glitch right now, no battle would occur. (Note that if you used the death warp method to encounter a Pokémon immediately in front of the trainer, then this doesn't apply, since the trainer never had to start moving in the first place.)

Luckily, there's a simple way to kill two Pidgeys with one Geodude: having another trainer spot us will not only fix Problem 1, but the act of the trainer walking up to us will also fix Problem 2. There's one very important catch though: **the trainer must walk up to you**. Otherwise, the game will softlock.

<img src=img/trainer2_good.png>|<img src=img/trainer2_bad1.png> <img src=img/trainer2_bad2.png>
:---:|:---:
Good|Softlocks

It is highly recommended that you lose to this trainer, as this will allow you to battle them again for future trainer escape glitches. Additionally, by choosing this second trainer carefully, you can combine this with Step 3 of the glitch, setting up the special stat (more on that later).

### Alternative method (trainerless)
If you don't have any other trainers left to walk up to you, don't worry, there's another way to fix these side effects. First, in order to re-enable textboxes, head to a Pokémon Center and use the PC. (Unlike most textboxes, PCs are not disabled.) Go to Bill's PC and change boxes, which lets you save the game. Now you can reset the game (this can be done by holding A+B+Start+Select) and load your save, which will re-enable textboxes.

For the second step, you need to trigger a scripted NPC movement. You have several options:
1. Having the NPC outside the Pewter mart lead you to the museum
2. Pushing a boulder with strength
3. Defeating the champion (Professor Oak walks during the post-battle cutscene)

## Part 3: Setting up the special stat
At this point, returning to the map where you set up the glitch will trigger an encounter. Which Pokémon you encounter is determined by the special stat of the last Pokémon that you fought.
