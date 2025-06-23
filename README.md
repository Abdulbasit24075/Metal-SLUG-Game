# 🔫 Metal Slug-Inspired Game (C++ with Raylib)

A 2D run-and-gun shooter game inspired by the classic **Metal Slug** series, built using **C++** and the **Raylib** graphics library. This project features exciting side-scrolling gameplay, player movement, shooting mechanics, and animated enemies — all controlled via **keyboard**.

## 🎮 Features

- 🧍‍♂️ Controllable Player Character
  - Movement (left/right/jump)
  - Shooting and throwing
- 🔫 Enemy Characters
  - Level 1 basic enemy AI (walk and shoot)
- 💣 Bullet Firing System
- 💥 Basic collision detection (bullet hits enemy)
- 🗺 Side-scrolling background
- 🎨 Sprite animations for player and enemies
- 🔊 Sound effects and background music 
-  Healthbars
## 🛠 Technologies Used

- **C++**
- **Raylib** for:
  - Rendering (textures, sprites)
  - Input handling (keyboard)
  - Audio 
  - Timers and FPS control
## CONTROL SETTING

SPACEBAR( SHOOTING IN RIGHT SIDE)
K Key( SHOOTING IN upward SIDE)
Arror keys to control player movement

## 📷 Screenshots

![image](https://github.com/user-attachments/assets/0c3ac498-31fb-49f9-998d-c281ba45cd63)
![image](https://github.com/user-attachments/assets/64831545-238d-4729-bfcb-11e3e000b5eb)
![image](https://github.com/user-attachments/assets/0e7a8961-c454-4c07-8d08-884db6998c11)
![image](https://github.com/user-attachments/assets/acbf8d2b-1d34-45e7-be97-07d5f2697ada)
![image](https://github.com/user-attachments/assets/723e3b44-853d-47be-b37c-c7c01c3f3a78)
![image](https://github.com/user-attachments/assets/02679b4a-183a-4bfe-9595-65fa81ad1f16)
https://screenrec.com/share/prKGjhvEwA

## 🚀 Getting Started

### 🔧 Prerequisites

- C++ Compiler (e.g., `g++`)
- Raylib library installed  
  [How to Install Raylib](https://github.com/raysan5/raylib/wiki)

---

### 💻 How to Compile and Run

```bash
g++ main.cpp -o metal_slug -lraylib -lGL -lm -lpthread -ldl -lrt -lX11
./metal_slug

