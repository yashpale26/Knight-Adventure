Knight Adventure
Knight Adventure is a 2D action-platformer built with the Unity Engine. Take control of a courageous knight navigating through increasingly difficult parkour-style levels, battling enemies, and collecting gold while mastering precise movement and combat.

🎮 Gameplay Features
  Action Platforming: Challenging 2D parkour mechanics across 3 distinct levels that increase in difficulty.
  Dynamic Combat:
  Player: Fully animated movement, jumping, and attacking system. Includes a health management system and automatic respawn upon death.
  AI Enemies: Intelligent enemies that patrol, detect the player within range, follow for pursuit, and execute attacks.
  Progression System:
  Coin Collection: Gather coins scattered throughout the levels to increase your score.
  Level Scaling: Each level introduces tougher platforming challenges and enemy placements.
  Immersive Audio: Integrated background music and sound effects to enhance the atmosphere.
  
🛠️ Technical Details
  Game Engine: Unity
  Programming Language: C#
  Genre: 2D Platformer / Action
  Perspective: Side-scroller
  Key Scripts & Logic
  Player Controller: Handles physics-based movement, jump logic, and animation state switching.
  Enemy AI: Implements range-detection logic and a "follow-target" state machine.
  Health System: Manages damage calculation for both the player and enemies.
  Level Manager: Controls level transitions, coin tallies, and player respawning.
  
🚀 Installation
  Clone the repository:
  Bash
  git clone https://github.com/[Your-Username]/Knight-Adventure.git

Open in Unity:
  Launch the Unity Hub.
  Click Add and select the cloned project folder.
  Ensure you are using the appropriate Unity version (e.g., 2021.x or 2022.x).
  Play the Game:
  Open Scenes/Level1 from the Project window.
  Press the Play button at the top of the editor.
  
🕹️ Controls
  Move: A / D or Left / Right Arrow
  Jump: Space
  Attack: Left Mouse Button
  
📂 Project Structure
  /Assets/Scripts: All C# logic for player, enemy, and game management.
  /Assets/Sprites: 2D character animations, tilesets, and environment assets.
  /Assets/Prefabs: Pre-configured game objects (Player, Enemy, Coins).
  /Assets/Audio: Music and SFX files.
  /Assets/Scenes: The 3 game levels.
  
📜 License
  This project is licensed under the MIT License - see the LICENSE file for details.

Author
  Yash Ganpat Pale * Developed as a showcase of 2D Game Development in Unity.
