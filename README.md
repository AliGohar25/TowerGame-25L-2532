# TowerGame-25L-2532
TowerDefense_OOP 
This project is a Tower Defense Game developed as an OOP semester project at NUCES.
The game is built using C++ and SFML library and demonstrates object-oriented programming concepts such as inheritance, polymorphism, encapsulation, and dynamic memory management.

The player defends a path by placing towers that automatically attack incoming enemies.

 Game Objective

The objective of the game is to:

Survive all enemy waves
Prevent enemies from reaching the end of the path
Earn gold by killing enemies
Strategically place and upgrade towers 

 Object-Oriented Programming Concepts Used

This project implements core OOP principles:

1. Inheritance

Entity → base class
Enemy, Tower, Projectile inherit from Entity
2. Polymorphism
Virtual functions like update() and render()
Different enemy and tower behaviors
3. Encapsulation
Data members are protected/private
Access controlled via getter/setter functions
4. Abstraction
Abstract base classes like Tower and Enemy
5. Dynamic Memory Management
Enemies and towers created using new
Proper cleanup using delete

 Game Features

Multiple enemy types with unique abilities
Multiple tower types with different stats
Wave-based progression system
Gold and scoring system
Health system (lives)
Path-based enemy movement
Projectile collision detection
Splash damage and slow effects
Win/Lose conditions

 Game Architecture

The game is structured into the following main components:

Game Engine (Game class)
Handles main loop, events, updates, and rendering
Entities
Enemy system
Tower system
Projectile system
Map System
Grid-based path
Waypoint navigation
Wave System
Controls enemy spawning
Difficulty scaling

 Enemy Types

Basic Enemy → Balanced stats
Fast Enemy → High speed, low HP
Tank Enemy → High HP, slow speed
Flying Enemy → Ignores path constraints
Healer Enemy → Regenerates health over time

 Tower Types

Slow Tower → Applies slow effect
Cannon Tower → High damage splash attacks
Machine Gun Tower → Fast firing rate
Sniper Tower → Long range, high damage
Bomb Tower → Area damage explosion

 Controls

1–5 → Select tower type
Left Click → Place tower
Right Click → Cancel selection
Esc → Deselect tower

🧾 Requirements

C++ compiler (g++)
SFML library installed

Compile Command:

g++ main.cpp -o TowerDefense -lsfml-graphics -lsfml-window -lsfml-system

🚀 How to Run

Windows:
TowerDefense.exe

Linux:

./TowerDefense
