[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YyUO0xtt)
# COMP2150  - Level Design Document
### Name: Liam Wallbridge
### Student number: 47799099


----------------------------------------------------------------------------------------------------------------------------


### Level Design Sections 1-3 For Reference:
### Section1:
(DocImages/ExtraInfo_Section1.png)
### Section2:
(DocImages/ExtraInfo_Section2.png)
### Section3:
(DocImages/ExtraInfo_Section3.png)


----------------------------------------------------------------------------------------------------------------------------


## 1. Player Experience

I have designed each section of my level to facilitate the core player experience goals: Discovery, Drama, Challenge and Exploration.

### 1.1. Discovery
Upon completing my level, the player should have an understanding of the core gameplay mechanics. The three sections are used to help the player learn to different extents.

I used section one of my level as a tutorial-like stage where the player learns the core game mechanics through basic and low-challenge interactions (such as spike jumps, acid pit jumps, horizontally moving platforms, etc).

I used section two to combine two mechanics together (such as spikes + moving platforms). I did this to test the player on their knowledge/pattern recognition from section one, but to also develop their knowledge of the mechanics further.

Section three acts as a final test for the player's knowledge. Unlike section two, I combined three mechanics per encounter. (e.g. Spitters + acid + moving platforms). 

This method of introducing mechanics allows for a linear/gradual learning curve and therefore facilitates learning in a way that follows good design practice.

### 1.2. Drama

To facilitate increasing and modulating intensity, I designed each of the sections to have a hook, rising action, a climax, and a resolution.

I designed my level to increase in intensity for each section the player progresses through. At the end of each section I have created rooms without challenges to allow moments of relief. This also increases the tension for the next encounter and helps to create an effective hook for the dramatic arc.

Section 1
(DocImages/Section1_DramaticArc.png)

Section 2
(DocImages/Section2_DramaticArc.png)

Section 3
(DocImages/Section3_DramaticArc.png)

### 1.3. Challenge
My level offers a physical challenge. The majority of my level requires physical skills such as reaction time for jumping over spikes, dodging spitters, etc. An example of an Intellectual challenge in my level would be the pushable box objects, specifically in section two where the player uses a box to cross some acid.

To control the difficulty curve and maintain a consistent flow channel I designed level progression to simultaneously increase in difficulty, but also in the variety of mechanics. An example of this would be comparing section one to section two. 
Section one features simple spike obstacles that the player needs to jump over, while section two involves moving platforms with spikes that you need to avoid. They use the same mechanic but in different ways, which makes the level more challenging and entertaining at the same time, and therefore, keeps the player in the flow channel. 

Using the same mechanics in different ways also prevents the level design from jumping from an easy difficulty to an extremely challenging one (or vise versa), and can prevent frustration or boredom from occurring.

### 1.4. Exploration
The design of section one facilitates autonomy and invites the player to explore. The following is an example:
(DocImages/ExplorationEG1_S1.png)
In this area players can either drop down to section two immediately or take the top path by defeating the spitters. This layout choice allows for a more memorable experience due to the freedom it gives the player.

In contrast to section one, I designed section two to have a greater focus on exploration. There are three areas of section two that invite the player and allow for autonomous exploration.
(DocImages/ExplorationEG1_S2.png)
I designed the room in EG1 (found in the image) to be large enough that it hides both left and right sides. My intention was to invite the player to explore both the left and right sides. Upon exploring the left area, the player would discover that a key is required to progress, which would lead them to the right side of the room where they can break the destructible wall. 
EG2 and EG3 are two other examples that I implemented to invite the player to explore further. I use health pickups here as motivators for exploration.

Similarly, at the beginning of section three 
(DocImages/ExplorationEG1_S3.png)
I used platforms to hint towards a hidden area, which is intended to draw players in.

The aesthetic and layout choices of my level design create distinct and memorable spaces as they facilitate autonomy and invite players to explore.


----------------------------------------------------------------------------------------------------------------------------


## 2. Core Gameplay

### 2.1. Acid
A placed a small acid pool at the beginning for the player to jump over. A block is placed hanging over the acid implying that the player cannot walk through it, and instead is required to jump. Acid is used again underneath the moving platforms on the first section, so it is important that players understand that it is dangerous.

(DocImages/Acid&Respawn.png)

### 2.2. Spikes
I added spikes at the beginning so that players can quickly learn about them. The second spike encounter is intended to catch players who have not yet learnt the mechanics of spikes.
### 2.3. Health Pickups
I placed health pickups near spots of danger so that players can learn from mistakes. If they are to walk into acid or spikes, they will have a readily available health pickup, learning both the mechanics of health, as well as the dangers.

(DocImages/Spikes&HealthPickups.png)

### 2.4. Checkpoints
I placed a checkpoint before the moving platform to teach players that falling into acid will teleport them back to the checkpoint.
### 2.5. Moving Platforms
I used a simple horizontal moving platform at the beginning to show how the basic platform movement works.

(DocImages/Checkpoints&MovingPlatforms.png)

### 2.6. Passthrough Platforms
I used passthrough platforms as a progression block to ensure that players learn the functionality of crouching and passthrough. They cannot progress without obtaining the staff which is behind two passthrough platforms.
### 2.7. Weapon Pickup (Staff)
I used the optional destructible columns to teach the player how to use the staff, as well as a chomper hidden behind the columns. Since the columns can be destroyed, players should assume that chompers can be too. This teaches players how to defeat enemies with a staff.
### 2.8. Chompers
In the staff encounter players discover that chompers are melee-focused enemies and can be defeated with weapons.
### 2.9. Keys
I placed a key between the destructible columns as a hint towards the level goal. The player learns that keys can be picked up, and that there are two other keys hidden somewhere in the level. Later in section three, I placed a key next to the KeyDoor to show the player that the door is the end goal.

(DocImages/PassthroughPlatforms&Staff&Keys&Chompers.png)

### 2.10. Spitters
I placed three spitters on separate floating platforms with an increased detection range. They will teach the player that spitters are projectile-based enemies and can also be defeated with weapons.
### 2.11. Weapon Pickup (Gun)
The gun is placed here to teach the player that they can crouch and shoot, shoot or even jump and shoot to hit enemies (the spitters).

(DocImages/Gun&Spitter&Crouch.png)


----------------------------------------------------------------------------------------------------------------------------


## 3. Spatiotemporal Design
 
### 3.1.1 Molecule Diagram – Section 1
(DocImages/Molecule_Section1.png)
### 3.1.2 Molecule Diagram – Section 2
(DocImages/Molecule_Section2.png)
### 3.1.3 Molecule Diagram – Section 3
(DocImages/Molecule_Section3.png)

### 3.2.1. Level Map – Section 1
(DocImages/Section1_1.png)
(DocImages/Section1_2.png)
### 3.2.2. Level Map – Section 2
(DocImages/Section2_1.png)
### 3.2.3. Level Map – Section 3
(DocImages/Section3_1.png)


----------------------------------------------------------------------------------------------------------------------------


## 4. Iterative Design

Iterative design has helped in the process of improving my level design. 
While designing my level I encountered issues particularly with Exploration and Challenge.

In terms of exploration, my level design was too linear and did not leave room for player exploration.
Challenge, however, was only a problem in section three.

To fix these issues I employed an agile game design approach to iterate on the designs for sections two and three of my level design. 
Specifically through the use of working prototypes, which I later playtested and evaluated. The following are examples of my previous prototypes:

(DocImages/Q4_Eg1_OLD.png)
(DocImages/Q4_Eg1_NEW.png)
In this part of section one I intended for the player to use the gun and crouching mechanics to defeat the spitter enemies. 
However, upon playtesting, I noticed that it was just as easy to use the staff and that players could potentially overlook the gun feature. 
To avoid this, I increased the distance between the staircase and the spitters. Otherwise, I could’ve introduced the gun before the staff.

I also made changes to the floating platforms, the hole leading to section two, and the area on the right. 
I made the platforms wider to make platforming less challenging for section one, as later sections would have more physically challenging platforms. 
I gave the area on the right and the hole both passthrough platforms to make it clearer where the player needs to go next, as well as to make the section less linear 
and allow for the player to explore the area more.


(DocImages/Q4_Eg2_OLD.png)
(DocImages/Q4_Eg2_NEW.png)
To allow for more exploration in between sections two and three, I added an extra room for the KeyDoor, rather than having it in the middle of section two.
The room features a set of platforms which are placed to invite the player to explore freely without any dangers. 
It is designed to lower the intensity of the dramatic arc before section three (the climax).


(DocImages/Q4_Eg3_OLD.png)
(DocImages/Q4_Eg3_NEW.png)
While creating section three I was having trouble deciding on a design which would test the knowledge of the player as well as provide a good challenge. 
The first iteration of section three was far too challenging. This was due to the mixture of small platforms, acid with no checkpoint, and an excessive amount of enemies. 
Adding moving platforms allowed for more freedom when dodging the spitters projectiles, as well as using the gun to defeat them. 
The checkpoint is to prevent players from redoing the same obstacle.



----------------------------------------------------------------------------------------------------------------------------


## Generative AI Use Acknowledgement

### Tool Used: None