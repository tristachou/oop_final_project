# Don't Step on the Spikes (OOP Final Project)

![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Qt](https://img.shields.io/badge/Qt-%23217346.svg?style=for-the-badge&logo=Qt&logoColor=white)
![Visual Studio](https://img.shields.io/badge/Visual%20Studio-5C2D91.svg?style=for-the-badge&logo=visual-studio&logoColor=white)


> **Note**: This project was developed as a final assignment for an Object-Oriented Programming course (Jan 2021).

## Introduction

**Don't Step on the Spikes** is a multiplayer party platformer game inspired by *Ultimate Chicken Horse*. The goal is simple: race your friends from the starting point to the flag on the right. 

However, the path isn't easy. In valid "party game" fashion, players can place traps—like ice patches, spiderwebs, and cannons—to hinder their opponents. The catch? You have to dodge your own traps too!

## Features

- **Multiplayer Networking**: Supports 4-player real-time gameplay using a Client-Server architecture (TCP Sockets via QtNetwork).
- **Dynamic Level Building**: Players modify the level in real-time by placing obstacles and traps.
- **Object-Oriented Design**: Utilizes C++ OOP principles (Encapsulation, Inheritance, Polymorphism) to manage game entities like `Role` (Player) and `Trap`.
- **Custom Physics Engine**: Implements basic physics for movement, jumping, friction, and collision detection.
- **Game Assets**: Includes custom sprites and audio (Sound effects & BGM).

## Tech Stack

- **Language**: C++ (C++11/14 Standard)
- **Framework**: Qt 5 (Qt Widgets, Qt Network, Qt Multimedia)
- **IDE**: Visual Studio
- **Architecture**: Client-Server (Socket Programming)

## Installation & Build

### Prerequisites
- Visual Studio (2019 or later recommended)
- Qt 5 Extension for Visual Studio
- Qt 5 Development Libraries

### Setup
1.  Clone the repository.
2.  Open the solution file `oop_final_project_20210105.sln` in Visual Studio.
3.  Ensure the Qt version is correctly configured in the VS Qt extension settings.
4.  Build the solution (Release/Debug x64 or x86 depending on your Qt kit).

## How to Play

1.  **Launch the Game**: Start the application.
2.  **Connect**: The game attempts to connect to the server (default IP: `10.101.2.8`). *Note: Requires a running server instance.*
3.  **Gameplay**:
    - **Move**: Arrow Keys / WASD (Configurable)
    - **Jump**: Spacebar
    - **Place Trap**: Select a trap from the UI and click on the grid to place it.

## Lessons Learned

This project was a significant milestone in learning software collaboration and architecture:
- **Networking**: Gained practical experience with socket programming and handling packet serialization/deserialization.
- **Teamwork**: Collaborated on game logic, artwork, and networking protocols.
- **Qt Framework**: Learned to leverage Qt for both UI and core logic.

## Demo

[Watch the Gameplay Demo](https://www.youtube.com/watch?v=EXr-rL2-Hy0)

> **Note**: The video showcases 4 synchronized screen recordings from different computers, demonstrating the real-time multiplayer networking capability.

---
*Created by Trista - 2021*


