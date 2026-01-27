# Maze-Runner-Game-
🎮 An interactive maze game with GUI and terminal versions | Built with C++, JavaScript, HTML &amp; CSS | Multiple difficulty levels | File I/O operations

# 🎮 Maze Runner Game

An engaging maze navigation game featuring both **terminal-based** and **web-based GUI** versions. Challenge yourself across multiple difficulty levels and find your way to victory!


## ✨ Features

### 🎯 Core Gameplay
- **Three Difficulty Levels**: Easy (11×21), Normal (15×31), Hard (21×41)
- **Smart Player Controls**: WASD movement with intuitive navigation
- **Dynamic Maze Generation**: Randomized mazes for endless replayability
- **Save/Load System**: Store and retrieve custom mazes
- **Lives System**: 3 attempts before game over
- **Goal-Oriented**: Navigate from start (^) to end (E)

### 💻 Dual Versions
- **C++ Console Version**: Classic terminal-based gameplay
- **Web GUI Version**: Modern, visually appealing interface with:
  - Smooth animations
  - Responsive design
  - Enhanced graphics
  - Interactive controls

### 📊 Technical Features
- File I/O operations for maze persistence
- Error logging system
- Input validation and exception handling
- Modular code architecture
- Cross-platform compatibility

## 🚀 Getting Started

### Prerequisites
**For C++ Version:**
- C++ compiler (GCC/MinGW/MSVC)
- Standard C++ library support

**For Web Version:**
- Any modern web browser
- No installation required!

### Installation & Running

#### 🖥️ C++ Terminal Version
```bash
# Clone the repository
git clone https://github.com/yourusername/maze-runner-game.git
cd maze-runner-game

# Compile the C++ code
g++ -o maze_game maze_game.cpp

# Run the game
./maze_game
```

#### 🌐 Web GUI Version
```bash
# Simply open the HTML file
# Option 1: Double-click index.html

# Option 2: Use a local server
python -m http.server 8000
# Then visit: http://localhost:8000
```

## 🎮 How to Play

1. **Select Difficulty**: Choose Easy, Normal, or Hard
2. **Load or Generate**: Use existing maze or create a new one
3. **Navigate**: Use W/A/S/D keys to move
   - W = Move Up ⬆️
   - A = Move Left ⬅️
   - S = Move Down ⬇️
   - D = Move Right ➡️
4. **Avoid Walls**: Hit 3 walls and it's game over! 💥
5. **Reach the Exit**: Find the 'E' marker to win! 🏆

## 📁 Project Structure
```
maze-runner-game/
│
├── maze_game.cpp          # C++ source code
├── index.html             # Web version main file
├── style.css              # Styling for GUI
├── script.js              # Game logic for web version
├── mazeEasy.txt          # Easy maze storage
├── mazeNormal.txt        # Normal maze storage
├── mazeHard.txt          # Hard maze storage
├── errors.txt            # Error logging file
└── README.md             # This file
```

## 🛠️ Technologies Used

### C++ Version
- **Language**: C++ (Standard Library)
- **File I/O**: `<fstream>`
- **Random Generation**: `<cstdlib>`, `<ctime>`
- **Exception Handling**: try-catch blocks

### Web Version
- **HTML5**: Structure and layout
- **CSS3**: Styling, animations, responsive design
- **JavaScript**: Game logic, DOM manipulation, event handling

## 🎨 Features Breakdown

### C++ Implementation Highlights
```cpp
✅ Dynamic 2D array maze generation
✅ File-based maze persistence
✅ Error logging system
✅ Input validation
✅ Randomized path generation
✅ Player collision detection
```

### Web GUI Enhancements
```javascript
✅ Visual maze rendering
✅ Smooth player animations
✅ Real-time score tracking
✅ Responsive controls
✅ Modern UI/UX design
✅ Mobile-friendly interface
```

## 📸 Screenshots

### Terminal Version
```
####################
#^                 #
# ##### ########## #
# #   #          # #
# # # # ######## # #
#   #          #E  #
####################
```

### Web GUI Version

<img width="1679" height="892" alt="image" src="https://github.com/user-attachments/assets/53aaf8ab-0dc9-41fe-85d0-c57367697bbb" />


## 🎯 Future Enhancements

- [ ] Multiplayer mode
- [ ] Timer and scoring system
- [ ] Power-ups and collectibles
- [ ] Sound effects and background music
- [ ] Leaderboard system
- [ ] Maze editor
- [ ] Mobile app version
- [ ] AI pathfinding visualization

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Syed Usman Ali Shah**
- GitHub: [syedusmanshah055@gmail.com](https://github.com/Syed-Usman-Ali-Shah)
- LinkedIn:(https://www.linkedin.com/in/syed-usman-ali-shah-497129361?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)

## 🙏 Acknowledgments

- Inspired by classic maze games
- Built as a learning project for C++ and web development
- Thanks to the open-source community

## 📧 Contact

Have questions or suggestions? Feel free to reach out!

- Email: syedusmanshah055@gmail.com
- Open an issue on GitHub

---

⭐ **Star this repo if you found it helpful!** ⭐

Made with ❤️ and C++
```

---


Copyright (c) 2025 Syed-Usman-Ali-Shah

Permission is hereby granted, free of charge, to any person obtaining a copy...
```

### **2. .gitignore File:**
```
# Compiled files
*.exe
*.out
*.o
*.obj

# Editor files
.vscode/
.idea/
*.swp

# OS files
.DS_Store
Thumbs.db

# Log files
errors.txt
