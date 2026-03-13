# 🐜 Ants vs SomeBees – Strategy Simulation

**Course Project – UC Berkeley CS88C**

## Overview

Ants vs SomeBees is a tower-defense style strategy game implemented in Python.  
The player deploys different types of ants to defend their colony against invading bees.

Each ant has unique abilities, and the player must strategically place them in tunnels to stop the bees before they reach the queen.

This project focuses on **object-oriented programming**, **simulation design**, and **rule-based game mechanics**.

---

## Key Concepts

This project demonstrates several important computer science concepts:

- **Object-Oriented Programming**
  - class hierarchies
  - inheritance and polymorphism
  - encapsulated game state

- **Game Simulation**
  - turn-based environment
  - rule-based interactions between agents
  - state transitions

- **Strategy Design**
  - different ant types with unique abilities
  - resource management using food
  - defensive placement strategy

---

## Ant Types

Several ants with specialized behaviors were implemented:

- **Harvester Ant**  
  Generates food resources each turn.

- **Thrower Ant**  
  Attacks bees at a distance.

- **Fire Ant**  
  Deals damage to nearby bees when defeated.

- **Bodyguard Ant**  
  Protects another ant in the same location.

- **Queen Ant**  
  Enhances the attack power of allied ants.

These units create diverse strategic combinations during gameplay.

---

## System Architecture

The simulation is built using a structured class hierarchy:

- `Insect` – base class for all entities  
- `Ant` – defensive units controlled by the player  
- `Bee` – enemy units advancing through tunnels  
- `Place` – represents locations in the colony  
- `GameState` – manages turns and game logic  

The interaction between these classes forms the core simulation engine.

---

## Gameplay Mechanics

Each game turn follows this sequence:

1. The player deploys ants using available food resources
2. Ants perform their actions (attack, generate food, etc.)
3. Bees advance through tunnels and attack ants
4. The game state updates until victory or defeat

---

## Learning Outcomes

Through this project I gained experience in:

- designing class hierarchies for complex systems
- implementing interactions between multiple object types
- modeling game rules using Python
- debugging multi-class simulation environments

---

## Note

Due to course policy, the full source code is not publicly available.

If you are interested in discussing the implementation details or reviewing the code, feel free to contact me.
