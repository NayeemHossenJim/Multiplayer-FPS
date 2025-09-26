# 🔥 BLASTER - Multiplayer FPS

<div align="center">
  
  ![Unreal Engine](https://img.shields.io/badge/Unreal_Engine-5.4-blue?style=for-the-badge&logo=unrealengine&logoColor=white)
  ![C++](https://img.shields.io/badge/C++-17-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
  ![Platform](https://img.shields.io/badge/Platform-Windows-0078d4?style=for-the-badge&logo=windows&logoColor=white)
  ![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
  
  **An intense multiplayer first-person shooter built with Unreal Engine 5**
  
  🎯 *Fast-paced combat* • 🌐 *Online multiplayer* • 🎮 *Competitive gameplay*
  
</div>

---

## 🚀 Features

### 🎮 Core Gameplay
- **Intense FPS Combat** - Fast-paced first-person shooter mechanics
- **Smooth Character Movement** - Responsive controls with jumping, crouching, and fluid locomotion
- **Professional Animation System** - Custom animation blueprints with state machines
- **Third-Person Camera** - Dynamic camera system with spring arm component

### 🌐 Multiplayer Systems
- **Session Management** - Create, find, join, and destroy multiplayer sessions
- **Network Architecture** - Robust online subsystem integration
- **Scalable Lobbies** - Support for multiple players per session
- **Real-time Synchronization** - Smooth multiplayer experience

### 🎨 Visual Excellence
- **Unreal Engine 5** - Cutting-edge graphics and rendering
- **Mixamo Animations** - Professional character animations
- **Starter Content** - High-quality assets and materials
- **Custom Character Models** - Detailed player characters

---

## 🛠️ Technical Stack

<table>
<tr>
<td align="center"><strong>Engine</strong></td>
<td align="center"><strong>Language</strong></td>
<td align="center"><strong>Platform</strong></td>
<td align="center"><strong>Architecture</strong></td>
</tr>
<tr>
<td align="center">Unreal Engine 5.4</td>
<td align="center">C++17 & Blueprints</td>
<td align="center">Windows (Primary)</td>
<td align="center">Client-Server</td>
</tr>
</table>

### 🏗️ Project Structure
```
📁 Blaster/
├── 🎯 Source/           # C++ source code
│   └── Blaster/         # Main game module
├── 🎨 Content/          # Game assets & blueprints
│   ├── Blueprints/      # Character & game blueprints
│   ├── Maps/            # Game levels
│   └── AnimStarterPack/ # Character animations
├── 🔌 Plugins/          # Custom plugins
│   └── MultiplayerSessions/  # Network session management
└── ⚙️ Config/           # Game configuration files
```

---

## 🎯 Key Systems

### 🤖 Character System
- **BlasterCharacter** - Main player character with movement and input
- **BlasterAnimInstance** - Animation state management
- **Enhanced Input** - Modern input binding system

### 🌐 Multiplayer Framework
- **MultiplayerSessionsSubsystem** - Session lifecycle management
- **Menu System** - UI for hosting and joining games
- **Online Subsystem** - Network communication layer

### 🎮 Game Features
- Responsive movement controls (WASD + Mouse)
- Jumping and air control
- Smooth camera follow system
- Animation blending and state machines

---

## 🚀 Getting Started

### Prerequisites
- Unreal Engine 5.4+
- Visual Studio 2022 (for C++ development)
- Windows 10/11
- DirectX 12 compatible graphics card

### 🔧 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/NayeemHossenJim/Multiplayer-FPS.git
   cd Multiplayer-FPS
   ```

2. **Generate project files**
   ```bash
   # Right-click on Blaster.uproject and select "Generate Visual Studio project files"
   ```

3. **Build the project**
   ```bash
   # Open Blaster.sln in Visual Studio and build in Development Editor configuration
   ```

4. **Launch the game**
   ```bash
   # Open Blaster.uproject in Unreal Editor
   ```

### 🎮 Quick Play
1. Press **Play** in the Unreal Editor
2. Use **WASD** to move
3. **Mouse** to look around
4. **Spacebar** to jump
5. Access multiplayer menu for online play

---

## 🎯 Gameplay Controls

| Action | Key/Input |
|--------|-----------|
| Move Forward/Backward | W / S |
| Strafe Left/Right | A / D |
| Look Around | Mouse |
| Jump | Spacebar |
| Menu Navigation | UI Buttons |

---

## 🛠️ Development

### 🏗️ Building from Source

```bash
# Clone the repository
git clone https://github.com/NayeemHossenJim/Multiplayer-FPS.git

# Generate project files
Right-click Blaster.uproject → "Generate Visual Studio project files"

# Build in Visual Studio
Open Blaster.sln → Build → Development Editor
```

### 🔌 Plugin Architecture

- **MultiplayerSessions** - Custom plugin for network session management
- **Enhanced Input** - Modern input handling
- **Online Subsystem** - Network infrastructure

---

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. 🍴 **Fork** the repository
2. 🌟 **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. 💾 **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. 📤 **Push** to the branch (`git push origin feature/amazing-feature`)
5. 🔃 **Open** a Pull Request

### 📋 Contribution Guidelines
- Follow Unreal Engine C++ coding standards
- Test multiplayer functionality thoroughly
- Update documentation for new features
- Ensure compatibility with Unreal Engine 5.4+

---

## 🎮 Screenshots & Demos

*Coming Soon - Gameplay screenshots and video demonstrations*

---

## 📈 Roadmap

### 🎯 Planned Features
- [ ] Weapon system implementation
- [ ] Health and damage mechanics
- [ ] Multiple game modes (Deathmatch, Team vs Team)
- [ ] Map variety and level design
- [ ] Player progression system
- [ ] Audio system integration
- [ ] UI/UX improvements
- [ ] Performance optimizations

---

## 🐛 Known Issues

- None currently reported

*Found a bug? Please [open an issue](https://github.com/NayeemHossenJim/Multiplayer-FPS/issues) with detailed steps to reproduce.*

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- **Epic Games** - For Unreal Engine 5
- **Mixamo** - For character animations
- **Community Contributors** - For feedback and support

---

<div align="center">
  
  **⭐ Star this repository if you found it helpful! ⭐**
  
  Made with ❤️ by [NayeemHossenJim](https://github.com/NayeemHossenJim)
  
  ---
  
  *Ready to blast into action? Let's build the ultimate multiplayer FPS together!* 🚀
  
</div>