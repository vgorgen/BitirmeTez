# FAWE - Elemental Multiplayer Combat Game

![FAWE Logo](Assets/Art/UI/fawelogo.png)

## Project Overview

FAWE (Fire, Air, Water, Earth) is a multiplayer elemental combat game developed in Unity with Netcode for GameObjects. This project was created as a graduation thesis to demonstrate the implementation of multiplayer networking, elemental-based gameplay mechanics, and real-time combat systems.

## Game Features

### Elemental System
- Four playable elements: Fire, Air, Water, and Earth
- Each element has unique abilities and visual effects
- Elemental interactions and weaknesses (e.g., Water beats Fire, Fire beats Air)
- Element-specific damage multipliers in combat

### Multiplayer Features
- Complete lobby system with host/client architecture
- Real-time player synchronization
- Player name and status display
- Ready system for game start coordination
- Seamless joining through lobby codes

### Combat System
- First-person perspective gameplay
- Four ability slots per character (primary attack + 3 special abilities)
- Cooldown-based ability system
- Projectile and area-of-effect abilities
- Health and damage system with networked synchronization

### Enemies
- Multiple enemy types (Orcs, Golems)
- AI-driven behavior
- Enemy spawning system with network synchronization

## Technical Implementation

### Networking
- Built with Unity's Netcode for GameObjects framework
- Relay services for NAT traversal
- Network variables for synchronized game state
- ClientRPC and ServerRPC for client-server communication

### Architecture
- Component-based design with clear separation of concerns
- ScriptableObjects for ability and game data
- Service-based architecture for networking and game systems

### UI System
- Main menu for game creation and joining
- In-game HUD with player status, ability cooldowns, and match information
- Lobby UI for player readiness and game settings

## Development Process

This project demonstrates proficiency in:
- C# programming within Unity
- Network programming concepts and implementation
- Game systems design and architecture
- UI/UX implementation for multiplayer games
- Asset integration and management

## Future Improvements

Potential areas for expanding the project:
- Additional elemental abilities and combinations
- More enemy types and AI behaviors
- Enhanced visual effects for abilities
- Expanded game modes (PvP, cooperative, etc.)
- Progression and unlockable content

## Credits

Developed by Samet Veysel as a graduation thesis project.

### Assets
- Various visual effects and models sourced from the Unity Asset Store
- Sound effects and music from appropriate sources with licensing
- Custom-developed code and game systems

## Installation and Setup

1. Clone the repository
2. Open the project in Unity (version 2022.3 or newer recommended)
3. Install required packages through the Package Manager:
   - Netcode for GameObjects
   - Unity Services Core
   - Unity Services Authentication
   - Unity Services Relay
   - Unity Services Lobbies
4. Set up Unity Services in the Project Settings
5. Build and run the game

## How to Play

1. Launch the game
2. Enter your player name
3. Create a new lobby or join an existing one with a code
4. Select your elemental character (Fire, Air, Water, or Earth)
5. Ready up when all players have joined
6. Coordinate with your team to defeat enemies
7. Use your elemental abilities (Keys: LMB, Q, E, X) to attack
8. Defeat all enemies to win!

---

This project was created as a demonstration of game development and networking skills. Feel free to contact me with any questions or feedback! 