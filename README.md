# Brupi's World - 2D Platformer (Unity / C#)

![Main Menu](https://i.imgur.com/s2vymQv.png)

## Overview
Brupi's World is a 2D platformer developed in Unity to explore game engine mechanics, 2D physics, and Object-Oriented Programming (OOP) principles in C#. The project served as a practical laboratory to understand the Unity Engine's component-based architecture, implementing custom C# scripts for character control, enemy AI behavior, and UI state management.

## Tech Stack & Tools
* **Engine:** Unity 2D
* **Language:** C#
* **Physics:** Unity Physics2D (Rigidbody2D, BoxCollider2D, CircleCollider2D)
* **Design:** Adobe Photoshop CS6 (UI and Sprite Concept Art)

---

## Technical Implementation Highlights

### 1. Character Controller & Physics
* **Movement & Jumping:** Implemented using `Rigidbody2D` velocity manipulation and force vectors (`AddForce`) for responsive platforming controls.
* **Collision Detection:** Utilized customized Physics Layers and `OnCollisionEnter2D` to manage interactions between the player, ground, and dynamic entities.

### 2. Enemy AI & Behaviors
Developed distinct behavioral logic for four types of enemies, demonstrating state management and physics overrides:

* **Wolf (Tracking AI):** Uses ground-based physics and `Transform.position` updates to calculate vectors and chase the player object.

![Wolf AI](https://i.imgur.com/2SkRilf.png)

* **Bee (Flying Mechanics):** Overrides standard gravity (`Rigidbody2D.gravityScale = 0`) to simulate flying mechanics and uses layer collision matrices to ignore specific terrain obstacles.

![Bee AI](https://i.imgur.com/BIWLKPv.png)

* **Frog (Ranged/Static):** Implements C# Coroutines (`IEnumerator`) or `InvokeRepeating` to handle fire rate cooldowns (1.8s) and instantiate projectile prefabs at runtime.

![Frog AI](https://i.imgur.com/fPdRs2Q.png)

* **Carnivorous Plant (Static Hazard):** Utilizes fixed Colliders to define environmental hazard zones.

### 3. Trigger Events, UI & Game State

![Trigger System](https://i.imgur.com/bPY72kx.png)

* **Environment Triggers:** Used `OnTriggerEnter2D` to detect player proximity to specific map coordinates, firing events to render dialogue UI overlays and tutorial instructions.
* **Collectibles Management:** Handled item pickup via trigger events, dynamically updating the global game state (score and health points) and destroying the collected objects (`Destroy(gameObject)`).

![Collectibles](https://i.imgur.com/6Vrolhv.png)

---

## Known Technical Debt & Edge Cases
As an exploratory learning project, there are identified edge cases in the physics engine and state machine that serve as valuable technical learnings:
* **Jump State Desync:** Rapidly colliding with higher platforms can cause the jump state boolean to lock, requiring horizontal movement input to reset the state. Additionally, the Animator component occasionally fails to transition from the "Jumping" to "Idle" animation state.
* **Invulnerability Glitch (i-Frames):** An issue in the damage cooldown logic where remaining perfectly still prevents the physics engine from re-triggering the damage collision event.
* **Missing Kill Volumes:** The absence of a "Kill Volume" (out-of-bounds trigger) at the bottom edges of the map results in infinite `Rigidbody2D` free-fall instead of triggering a respawn sequence.

---

## Concept & Development Process
The character design process involved hand-drawn concept art on paper, which was later digitized and processed using Adobe Photoshop CS6 before being integrated into the Unity Engine.

![Character Design Process](https://i.imgur.com/IudgTtH.png)

## Credits & Assets
* **Concept Art & Naming:** Ana Luiza Oliveira, Bruna Oliveira, Bruna Ferreira.
* **Assets:** [Unity Asset Store](https://assetstore.unity.com/)
* **Audio:** Kevin MacLeod (incompetech.com) - *Magic Scout* series.
