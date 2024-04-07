[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YyUO0xtt)
# COMP2150  - Level Design Document
### Name: [Kerry Lin]
### Student number: [47116749] 

## 1. Player Experience (734 words - Links not counted) 
### 1.1. Discovery
Throughout my level, the player is implicitly taught the core gameplay mechanics, while leaving a lenient window of safety while they gradually learn to put together and utilize the core mechanics in unison with others. The following examples will serve to showcase these design practices.

    The spawn room allows the place to jump and walk around in a completely safe environment. This tells the player that the jumping mechanics have to be understood before proceeding. Different platformers have static jump heights and others allow the player to go slightly higher if they hold the jump button for longer. For the player to be able to exit the room, they learn that holding the jump key increases their height.

![](DocImages/1.1_1.png)
    
    Environmental storytelling is used to indicate there are secrets hidden to the player that they'll have to wonder and explore the level to discover. This is implicitly stated as there is no direct path to reach the area above and the random plateau not inconspicuously placed in a way to let them see the secret room.

![](DocImages/1.1_2.png)

    This is the player's first introduction to danger, in the form of the acid pool below. To ease the player into learning what challenge lies ahead, there is a safety platform above that the player can jump up onto, to jump onto the further platform. This aligns with good level design practices by allowing for safe experimentation with this low risk encounter.

![](DocImages/1.1_3.png)

    The next platforming challenge the player faces is jumping to the higher up section on the right. Similarly to the last example, if they ever fall to the bottom, there's a safety net underneath.

![](DocImages/1.1_4.png)

### 1.2. Drama

The intensity curve follows a similar pattern to that of modern narratives arcs. The player begins in a safety net, they are then introduced to more mechanics that represent the rising tension. This builds up to the crisis moment, where the player falls to the very bottom of the level. They get a section which symbolises the point of relief. And the rest of the level slowly introduces new ways to use the already introduced mechanics all building up to the final climax where the player gets sent at extremely fast speeds towards the finish line utilising the movement mechanics they learnt throughout the level.

    Low-risk opening section:

![](DocImages/1.2_1.png)

    Crisis moment:

![](DocImages/1.2_2.png)

    Tension relief:

![](DocImages/1.2_3.png)

    Slow dramatic build up

![](DocImages/1.2_4.png)

    Super fast climax section:

![](DocImages/1.2_5.png)

Parts of the level that are fast correspond to either the level's climax or crisis. Slow platforms represent the dramatic build up. Places where the player is able to move at their own speed are when the player can release tension.

### 1.3. Challenge
For this level, the challenge mainly comes from platforming; more specifically the moving platforms instead of the combat mechanics. I've designed several different sections where I utilize moving platforms in non-uniform ways.

    This first encounter takes the combat mechanics which the player just learnt and adds an extra dynamic by introducing moving platforms. The player can jump on top of it and play around it in their own safe space.

![](DocImages/1.3_2.png)

    This second moving platform introduces them to a more interesting challenge

![](DocImages/1.3_3.png)

    This next section introduces the player to upward moving platforms sanctioning off half an axis of their movement. There's a dynamic between the movement and combat mechanics where they have to get used to the different movement axis, they have to make sure they don't get crushed by the ceiling all the while fighting off the enemies on their platform at the same time.

![](DocImages/1.3_4.png)

    Building off the previous section, where before, only half an axis is removed, this final section fully removes the x-axis forcing the player to the right at a very fast speed increasing the challenge towards a final send off where they get the key and complete the level.

![](DocImages/1.3_5.png)


### 1.4. Exploration

    In terms of aesthetics, the level is divided by the backgrounds. Areas are coloured to correspond to the level of intensity.

![](DocImages/1.4_6.png)
![](DocImages/1.4_5.png)


    As stated in 1.1, the player is immediately introduced to there being secret areas to explore as shown by the obvious visibility of secret areas in a place were they're can't access it. This invites them to think of ways to circle back and get to that secret part they saw earlier.

![](DocImages/1.4_1.png)
![](DocImages/1.4_2.png)
![](DocImages/1.4_4.png)

    When the player goes by the 'regular' route, strange pathways are visible. Below is an example in the 'crisis' moment when the player falls down the pitfall.

![](DocImages/1.4_3.png)



## 2. Core Gameplay (396 words)
### 2.1. Checkpoints

Checkpoints are placed in areas before the difficult platforming or combat encounters. The area but be clear of danger. This checkpoint is used to hold the progress of the player and works hand-in-hand with designing player 'safety.'

![](DocImages/2.1_1.png)
![](DocImages/2.1_2.png)

### 2.2. Acid

Player is introduced to acid pits and taught to be careful of environmental hazards. As this is an early section, help is given in the form of the upper passthrough platform. 

![](DocImages/2.2_1.png)
![](DocImages/2.2_2.png)
![](DocImages/2.2_3.png)
![](DocImages/2.2_4.png)

### 2.3. Passthrough Platforms

Passthrough platforms are introduced in the same area as 2.1 and 2.2. The player infers that the platform is passthrough through the implicit environmental cue of the ceiling above. 

![](DocImages/2.3_2.png)


### 2.4. Health Pickups

Health pickups are introduced in the first platforming section to add a level of forgiveness for the first time the player has to deal with danger in their movement.

![](DocImages/2.4_1.png)
![](DocImages/2.4_2.png)


### 2.5. Spikes

Spikes are introduces right after the health pickups because it's a similar mechanic to acid in that the player should try not to touch it. If the player jumps too short, they're taught that it knocks the player back. They then have a second try.

![](DocImages/2.5_1.png)
![](DocImages/2.5_2.png)


### 2.6. Keys

The player is introduced to the key via a must-grab key. The key then unlocks the door to where they can pass through.

![](DocImages/2.6_1.png)
![](DocImages/2.6_2.png)
![](DocImages/2.6_3.png)

### 2.7 and 2.8 Weapon Pickup (Staff), Chompers

This is the player's first introduction to the combat system of the game. They are introduced to enemies first as it needs to be established that they are living creates that deal damage. The player is then given a way to combat the harm after having no way to do so before. 

![](DocImages/2.7_1.png)
![](DocImages/2.7_2.png)
![](DocImages/2.7_3.png)
![](DocImages/2.7_4.png)
![](DocImages/2.7_5.png)
![](DocImages/2.7_6.png)
![](DocImages/2.7_7.png)
![](DocImages/2.7_8.png)
![](DocImages/2.7_9.png)

### 2.9 and 2.10 Spitters and Moving Platforms

As the combat was just introduced, some more combat and movement dynamics are introduced in the form of moving platforms and ranged enemies. The player learns of this new enemy as well as the need to wait for moving platforms to come back. This is important for the player to learn for the section to follow

![](DocImages/2.8_1.png)
![](DocImages/2.8_2.png)
![](DocImages/2.8_3.png)
![](DocImages/2.8_4.png)


### 2.11. Weapon Pickup (Gun)

The gun is introduced at the very end of the game to trigger the climax sequence. The player is introduced to the gun's shooting mechanics in a very straightforward way as it shouldn't detract from the core challenge; being the movement. Two spitters are presented with one being elevated. The player learns that they have to duck to shoot a spitter on level ground.

![](DocImages/2.11_1.png)
![](DocImages/2.11_2.png)
![](DocImages/2.11_3.png)
![](DocImages/2.11_4.png)




## 3. Spatiotemporal Design
A section on Spatiotemporal Design, which includes your molecule diagram and annotated level maps (one for each main section of your level). These diagrams may be made digitally or by hand, but must not be created from screenshots of your game. The annotated level maps should show the structure you intend to build, included game elements, and the path the player is expected to take through the level. Examples of these diagrams are included in the level design lectures.

No additional words are necessary for this section (any words should only be within your images/diagrams).
 
### 3.1. Molecule Diagram

![](DocImages/3.1.png)


### 3.2. Level Map – Section 1

Key:

Green --> Correct Path

Yellow --> Fall

Red --> Death

![](DocImages/3.2.png)


### 3.3.	Level Map – Section 2

![](DocImages/3.3.png)

### 3.4.	Level Map – Section 3

![](DocImages/3.4.png)


## 4. Iterative Design (~400 words)

Iterative design has helped thoroughly when it came to introducing new elements of gameplay such as movement, combat, platforming but in particular it seemed to help the most in figuring out the dramatic tension.

    My early design of the first combat encounters with spitters and chompers were as follows.

    Firstly the player sees the enemy notices that it's a living enemy

![](DocImages/2.7_1.png)

    Then they acquire the staff and test out the combat mechanics.

![](DocImages/2.7_2.png)

    On paper this seemed like a very intuitive way to introduce enemies and combat to the player but it didn't work out the way I wanted when I implemented it. The main issue arose with the dramatic tension.


    Below is an image of the main crisis of the game

![](DocImages/1.4_3.png)


## Generative AI Use Acknowledgement
None

