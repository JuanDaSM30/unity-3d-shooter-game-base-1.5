# unity-3d-shooter-game-base-1.5

Hi there! This is a 3D Shooter videogame development project built in Unity using C#. It features a hybrid architecture designed to support both Single-Player (PvE) mechanics and a foundational framework for Online Multiplayer (PvP) networking.

### 🛠️ Technical Features & Implemented Mechanics:

* **Network Architecture (Multiplayer):** Foundational implementation and structuring using **Photon Fusion / PUN** for network management. Core logic for dynamic room/lobby creation and hosting, matchmaking setup, and state synchronization for PvP.
* **Hybrid Gameplay System (PvP & PvE):** Logic integrating player-to-player combat and damage exchange, alongside AI pathfinding (NavMesh) for environmental enemies in cooperative or survival game modes.
* **Weapon & Combat Mechanics:** Weapon control, rate of fire, ammo logic, reloading systems, and hit detection implemented through Unity's Raycasting and Physics engine.
* **Game Loop & Core Systems:** State machine for seamless scene transitions (Main Menu -> Lobby -> Game Scene), basic data persistence, and overall match flow management.
* **Visual Effects & Feedback:** Implementation of particle systems for impacts/muzzle flashes, sound feedback (Audio Managers for SFX and ambient music), and dynamic user interface (UI/HUD) handling.
3D Shooter engine built in Unity with C#. Features PvE/PvP gameplay mechanics, AI pathfinding, scene transitions, and a network-ready architecture setup for multiplayer matchmaking and lobbies using Photon.
