# Unity Super Mario Bros Tutorial

[![Unity](https://img.shields.io/badge/Unity-2021.3%2B-blue.svg)](https://unity.com/)
[![License](https://img.shields.io/badge/License-Educational-green.svg)](LICENSE)

A comprehensive 2D Super Mario Bros clone developed in Unity, serving as an educational resource to demonstrate fundamental game development principles such as physics simulation, level design, and game feel mechanics.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Key Scripts](#key-scripts)
- [Contributing](#contributing)
- [License](#license)
- [Resources](#resources)
- [Acknowledgments](#acknowledgments)

## Overview

This project faithfully recreates the iconic Super Mario Bros gameplay within the Unity engine. Participants guide Mario across side-scrolling environments, gathering coins, evading adversaries, and leveraging power-ups to advance. As a tutorial, it elucidates core game development concepts, equipping developers with the knowledge to construct engaging 2D platformers.

## Features

- **Authentic Gameplay Mechanics**: Precise movement, jumping dynamics, and physics interactions mirroring the original title.
- **Power-Up System**: Incorporate Super Mushrooms for size enhancement and Starman for temporary invincibility.
- **Enemy Interactions**: Encounter Goombas and Koopas equipped with intelligent AI behaviors.
- **Interactive Level Elements**: Diverse blocks, pipes, and environmental objects for dynamic exploration.
- **Progression Tracking**: Comprehensive scoring, life management, and level advancement systems.
- **Polished Visuals**: Fluid sprite animations and detailed death sequences.
- **Dynamic Camera System**: Side-scrolling camera that intelligently tracks player movement.

## Prerequisites

- **Unity Editor**: Version 2021.3 (LTS) or newer
- **Supported Platforms**: Windows, macOS, or Linux
- **Basic Knowledge**: Familiarity with Unity and C# scripting is recommended

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/zigurous/unity-super-mario-tutorial.git
   cd unity-super-mario-tutorial
   ```

2. **Launch in Unity**:
   - Open Unity Hub
   - Select "Open" and navigate to the cloned project directory
   - Allow Unity to import assets and resolve dependencies automatically

3. **Execute the Project**:
   - Load the primary scene: `Assets/Scenes/1-1.unity`
   - Initiate playback within the Unity Editor to experience the game

## Usage

### Controls
- **Movement**: Arrow Keys or WASD for left/right navigation
- **Jump**: Spacebar or Z key
- **Sprint**: Hold Shift during movement for accelerated speed

### Gameplay Mechanics
- Accumulate coins to elevate your score
- Neutralize enemies by evasion or direct confrontation
- Interact with question blocks to unveil power-ups
- Ascend the flag pole to conclude the level successfully

## Project Structure

```
Assets/
├── Materials/          # Physics materials defining collision properties
├── Prefabs/            # Reusable game object templates (characters, enemies, blocks)
├── Scenes/             # Unity scene files representing individual levels
├── Scripts/            # C# scripts governing game logic and behaviors
└── Sprites/            # 2D graphical assets and textures
```

## Key Scripts

- **Player.cs**: Oversees player state management, including size transformations and power-up effects
- **PlayerMovement.cs**: Manages physics-based movement, jumping, and collision responses
- **GameManager.cs**: Handles overarching game state, level transitions, life tracking, and coin collection
- **Goomba.cs** & **Koopa.cs**: Implement enemy artificial intelligence and behavioral patterns
- **BlockHit.cs**: Defines interactions for destructible and interactive blocks
- **SideScrollingCamera.cs**: Ensures smooth camera tracking aligned with player position
- **AnimatedSprite.cs**: Facilitates sprite animation sequencing and rendering

## Contributing

We welcome contributions from the community. To participate:

1. Fork the repository
2. Establish a feature branch (`git checkout -b feature/YourFeature`)
3. Implement your modifications (`git commit -m 'Introduce YourFeature'`)
4. Push changes to your branch (`git push origin feature/YourFeature`)
5. Submit a Pull Request for review

Please adhere to standard coding practices and include comprehensive documentation for new features.

## License

This project is intended solely for educational purposes. All rights to the original Super Mario Bros intellectual property remain with Nintendo. Respect copyright and trademark guidelines.

## Resources

- [**Repository**](https://github.com/zigurous/unity-super-mario-tutorial)
- [**Download Archive**](https://github.com/zigurous/unity-super-mario-tutorial/archive/refs/heads/main.zip)
- [**Tutorial Videos**](https://youtube.com/playlist?list=PLqlFiJjSZ2x1mrMpSQgYdRm8PyWRTg6He)

## Acknowledgments

- Inspired by the timeless Super Mario Bros series by Nintendo
- Developed as part of an educational initiative to advance game development skills
- Special thanks to the Unity community for ongoing support and resources

---

*For inquiries or support, please open an issue on the GitHub repository.*
