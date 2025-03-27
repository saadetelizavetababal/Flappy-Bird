# Flappy Bird Clone

![Game Screenshot](/Assets/Screenshots/gameplay.png) <!-- Add your screenshot path -->

A classic Flappy Bird clone built with Unity, featuring:
- Smooth bird physics
- Animated wing mechanics
- Score system
- Game over screen
- Responsive controls

## 🎮 Features
- **Welcome Screen**: Play/Exit buttons
- **Game Mechanics**:
  - Spacebar to flap
  - Pipe obstacles
  - Score counter
- **Visual Effects**:
  - Animated bird wings
  - Particle effects
  - Screen shake on collision

## 🛠️ Installation
1. Clone this repository
2. Open in **Unity 2021.3+**
3. Navigate to `Assets/Scenes/Main.unity`
4. Press Play

## 📂 Project Structure
Assets/
├── Scripts/
│ ├── BirdScript.cs # Player controller
│ ├── GameManager.cs # Game state manager
│ ├── PipeSpawner.cs # Obstacle generator
│ └── LogicScript.cs # Score system
├── Prefabs/ # Reusable objects
├── Sprites/ # 2D assets
└── Audio/ # Sound effects


## ⚙️ Technical Details
- **Physics**: 2D Rigidbody with custom gravity
- **UI**: Canvas with TextMeshPro
- **Animation**: Procedural wing movement
- **Optimization**: Object pooling for pipes

## 🎨 Assets Credits
- Bird sprite: [Kenney.nl](https://kenney.nl)
- Sound effects: [freesound.org](https://freesound.org)

## 🤝 How to Contribute
1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📜 License
MIT License - See [LICENSE.md](/LICENSE.md) for details
