# Superhero Battle Simulator

## Project Overview
A Python-based superhero battle simulator built using
Object-Oriented Programming principles.

The system supports different superhero types, unique
abilities, energy management, health management, and battles.

## OOP Concepts Used

### 1. Classes and Objects
Hero is the base class. IronHero, SpeedHero, and FireHero
are individual superhero types.

### 2. Inheritance
All specialized heroes inherit common functionality from Hero.

### 3. Encapsulation
Health and energy are managed using properties and methods.

### 4. Method Overriding
Each subclass implements its own special_attack() method.

### 5. Polymorphism
The battle engine calls the same special_attack() interface
for different hero objects.

## Hero Types

| Hero | Special Ability | Damage | Energy Cost |
|---|---|---:|---:|
| IronHero | Mega Punch | 30 | 20 |
| SpeedHero | Lightning Strike | 25 | 15 |
| FireHero | Fire Blast | 35 | 25 |

## Features
- Hero creation
- Normal attacks
- Unique special attacks
- Energy management
- Health management
- Turn-based battles
- Automatic winner detection

## How to Run

1. Install Python 3.
2. Open this folder in VS Code.
3. Open the terminal.
4. Run:

python superhero_battle.py

## Scalability
New hero types can be introduced by inheriting from
the Hero class and overriding special_attack().

The Battle class can work with different hero subclasses
without needing a separate battle implementation.

## Future Improvements
- More superhero classes
- Defensive abilities
- Healing and energy recovery
- Team battles
- Random attack selection
- Battle history
- Hero registration system

## Technologies
- Python 3
- Object-Oriented Programming
- 
