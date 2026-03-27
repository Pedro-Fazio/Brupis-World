# Introduction to Brupi's World
This project was developed as a hobby. It is a 2D platformer game where the user can collect coins and defeat monsters spawned across the map. Although the game is short, containing only about 1 hour of gameplay, it features an interesting story and dialogues with Brupi (the main character).

# How to play Brupi's World
Playing is simple: just download the project repository, go to the **Game Build** folder, and click on **Brupi World.exe**.

# Game Controls
The game features only two simple mechanics: character movement controls and shooting projectiles at enemies.
![alt text](https://i.imgur.com/7cu9lWu.png)

# Enemies
The game features **four** different types of enemies, each with its own characteristics:

### Wolf
![alt text](https://i.imgur.com/2SkRilf.png)

🡪 Deals contact damage
🡪 Speed may vary from wolf to wolf
🡪 Chases the character
🡪 Cannot jump between platforms
🡪 Collides with walls
🡪 Dangerous in closed environments

**Tip against this enemy:**
Shoot the wolf before it reaches you, or you can avoid them by simply moving to another platform. Since they cannot jump between platforms, they won't bother you anymore.

### Bee
![alt text](https://i.imgur.com/BIWLKPv.png)

🡪 Deals contact damage
🡪 Usually spawns in swarms
🡪 Follows the character
🡪 Can fly
🡪 Can pass through walls

**Tip against this enemy:**
Move to an open area and shoot the bees while walking backward.

### Frog
![alt text](https://i.imgur.com/fPdRs2Q.png)

🡪 Always stays in the same place
🡪 Does not change facing direction (cannot turn around)
🡪 Constantly shoots fire projectiles
🡪 Always placed in strategic locations on the map
🡪 Has a fire rate of 1.8s between each projectile
🡪 Deals contact damage

**Tip against this enemy:**
Try to approach frogs from behind, as they only shoot forward and are highly vulnerable from the back. Another way to defeat them is to use the shooting interval to create an opening and attack.

### Carnivorous Plant
![alt text](https://i.imgur.com/PBSOzmn.png)

🡪 Always stays in the same place
🡪 Does not change facing direction (cannot turn around)
🡪 Not very dangerous unless approached
🡪 Always placed in strategic locations on the map
🡪 Deals contact damage

**Tip against this enemy:**
Do not get close to the carnivorous plants and shoot them from a distance.

# Character dialogues and instructions
Occasionally, small black orbs with orange borders or even little signs will appear around the map. When passing through these triggers, an instruction screen or a dialogue from Brupi will pop up.
![alt text](https://i.imgur.com/bPY72kx.png)

# Collectibles
There are two types of collectibles the user can interact with: ones that add to the player's score and others that increase health points.
![alt text](https://i.imgur.com/6Vrolhv.png)

# Menu
The menu design was created using Photoshop CS6. All images generated from the PSCS6 edits for its creation are in the **Used Images** directory.
![alt text](https://i.imgur.com/s2vymQv.png)

# Character creation
The idea when creating the game was to portray just another day in Brupi's life. It's as if she goes through this routine every day, making it normal for her to eliminate forest animals for valuable coins, return to her simple little house, and go to sleep. This short story is told through her dialogues with the player and by analyzing her surroundings.

**To create her, I tried to convey the following characteristics to the player:**
- Charismatic
- Unaware of the full picture
- No malice in her actions

**Character design**
Her design was entirely hand-drawn on paper and then digitized using Photoshop CS6, while all in-game sprites were sourced from the [Unity Asset Store](https://assetstore.unity.com/).
![alt text](https://i.imgur.com/IudgTtH.png)

# Bugs

### Jump Bug
This bug occurs when jumping to a higher platform and touching it too quickly, causing the character to be unable to jump anymore. The player must move sideways to be able to jump again. This bug also affects the character's sprite: in certain situations, upon jumping, it fails to restore the idle animation, making it look like the character is falling endlessly.
![alt text](https://i.imgur.com/ALyzFa0.png)

### Health Bug
At certain points in the gameplay, the character stops taking damage from enemies, making Brupi immortal as long as she stands still. Everything returns to normal once the player moves.
![alt text](https://i.imgur.com/z9qNErq.png)

### Infinite Fall Bug
This isn't exactly a bug, but rather bad map design. A certain part of the map lacks a wall to keep the player inside, allowing the player to jump out of bounds and fall endlessly.
![alt text](https://i.imgur.com/y7GfBN7.png)

# Final thoughts
In the end, creating this little game was a lot of fun! 
I built it to test what I was learning about Unity using C#. I chose a 2D platformer because it was the simplest way to start and see practical results, and also because 2D sprites and map tiles are much easier to find and adjust than 3D ones. I brainstormed with some friends who gave me ideas, and some helped with drawing, character name ideas, and even a bit of map design and story. Overall, it was a great experience for me.

### Credits
Here are some essential pieces for the creation of this project:
- Paper drawings of the character versions: Ana Luiza Oliveira and Bruna Oliveira
- Help with the character's name: Bruna Ferreira
- All sprites were taken from: https://assetstore.unity.com
- Music used: Magic Scout - Farm; Magic Scout - Cottage; Magic Scout - Northen Glade, sourced from: https://incompetech.com
