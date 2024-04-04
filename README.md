[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YyUO0xtt)
# COMP2150  - Level Design Document
### Name: Liam Wallbridge
### Student number: 47799099

This document discusses and reflects on the design of your platformer level for the Level Design assessment. It should be 1500 words. Make sure you delete this and all other instructional text throughout the document before checking your word count prior to submission. Hint: You can check word count by copying this text into a Word or Google doc.

Your document must include images. To insert an image into your documentation, place it in the "DocImages" folder in this repo, then place the below text where you want the image to appear:

```
![Place any alt text here](DocImages/<IMAGE NAME AND FILE EXTENSION>)
```

Example:

![This is the alt text for an image!](DocImages/exampleimage.png)


----------------------------------------------------------------------------------------------------------------------------


## 1. Player Experience (~700 words)
Outline and justify how your level design facilitates the core player experience goals outlined in the assignment spec. Each section should be supported by specific examples and screenshots of your game encounters that highlight design choices made to facilitate that particular experience.

### 1.1. Discovery
What does the player learn? How does your encounter and broader level design facilitate learning in a way that follows good design practice?

### 1.2. Drama
What is the intensity curve? How does your design facilitate increasing yet modulating intensity, with moments of tension and relief? 

### 1.3. Challenge
What are the main challenges? How have you designed and balanced these challenges to control the difficulty curve and keep the player in the flow channel?

### 1.4. Exploration
How does your level design facilitate autonomy and invite the player to explore? How do your aesthetic and layout choices create distinct and memorable spaces and/or places?


----------------------------------------------------------------------------------------------------------------------------


## 2. Core Gameplay
A section on Core Gameplay, where storyboards are used to outline how you introduce the player to each of the required gameplay elements in the first section of the game. Storyboards should follow the format provided in lectures.

Storyboards can be combined when multiple mechanics are introduced within a single encounter. Each section should include a sentence or two to briefly justify why you chose to introduce the mechanic/s to the player in that sequence.

You should restructure the headings below to match the order they appear in your level.

### 2.1. Acid
A placed a small acid pool at the beginning for the player to jump over. A block is placed hanging over the acid implying that the player cannot walk through it, and instead is required to jump. Acid is used again underneath the moving platforms on the first section, so it is important that players understand that it is dangerous.

### 2.2. Spikes
I added spikes at the beginning so that players can quickly learn about them. The second spike encounter is intended to catch players who have not yet learnt the mechanics of spikes.

### 2.3. Health Pickups
I placed health pickups near spots of danger so that players can learn from mistakes. If they are to walk into acid or spikes, they will have a readily available health pickup, learning both the mechanics of health, as well as the dangers.

### 2.4. Checkpoints
I placed a checkpoint before the moving platform to teach players that falling into acid will teleport them back to the checkpoint.

### 2.5. Moving Platforms
I used a simple horizontal moving platform at the beginning to show how the basic platform movement works.

### 2.6. Passthrough Platforms
I used passthrough platforms as a progression block to ensure that players learn the functionality of crouching and passthrough. They cannot progress without obtaining the staff which is behind two passthrough platforms.

### 2.7. Weapon Pickup (Staff)
I used the optional destructible columns to teach the player how to use the staff, as well as a chomper hidden behind the columns. Since the columns can be destroyed, players should assume that chompers can be too. This teaches players how to defeat enemies with a staff.

### 2.8. Chompers
In the staff encounter players discover that chompers are melee-focused enemies and can be defeated with weapons.

### 2.9. Keys
I placed a key between the destructible columns as a hint towards the level goal. The player learns that keys can be picked up, and that there are two other keys hidden somewhere in the level. Later in section three, I placed a key next to the KeyDoor to show the player that the door is the end goal.

### 2.10. Spitters
I placed three spitters on separate floating platforms with an increased detection range. They will teach the player that spitters are projectile-based enemies and can also be defeated with weapons.

### 2.11. Weapon Pickup (Gun)
The gun is placed here to teach the player that they can crouch and shoot, shoot or even jump and shoot to hit enemies (the spitters).


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

Use the below table to indicate any Generative AI or writing assistance tools used in creating your document. Please be honest and thorough in your reporting, as this will allow us to give you the marks you have earnt. Place any drafts or other evidence inside this repository. This form and related evidence do not count to your word count.
An example has been included. Please replace this with any actual tools, and add more as necessary.


### Tool Used: ChatGPT
**Nature of Use** Finding relevant design theory.

**Evidence Attached?** Screenshot of ChatGPT conversation included in the folder "GenAI" in this repo.

**Additional Notes:** I used ChatGPT to try and find some more relevant design theory that I could apply to my game. After googling them, however, I found most of them were inaccurate, and some didn't exist. One theory mentioned, however, was useful, and I've incorporated it into my work.

### Tool Used: Example
**Nature of Use** Example Text

**Evidence Attached?** Example Text

**Additional Notes:** Example Text


