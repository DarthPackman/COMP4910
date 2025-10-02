---
title: 'Text Trails: State Machine and Data-Driven C++ Auto-Battler'
pubDate: 2024-10-10
author: 'DarthPackman'
description: 'A text-based auto-battler game developed for COMP 3140 (Object-Oriented Design and Programming) in C++. The core architecture utilizes a State Machine pattern to manage combat logic and character behaviors.'
image:
    url: 'https://www.cobramode.com/wp-content/uploads/2021/07/cobramode-logo-website-big-1024x550.png'
    alt: 'Cobramode logo.'
tags: ["Class Project", "C++", "Object-Oriented Design", "State Machine", "Game Development", "Combat Logic"]
---

**Text Trails** was a team project for **COMP 3140**, focused on applying rigorous **Object-Oriented Design (OOD)** principles to create a reusable and scalable text-based auto-battler game. The goal was to manage complex combat interactions, character customization, and level progression using core OOD concepts implemented in **C++**.

## Core OOD and System Implementation

1.  **State Machine Design Pattern**: The core combat logic for both player and enemy characters is governed by a **State Machine**. This pattern dictates character actions by cycling through states such as `AttackState`, `DefendState`, and `IdleState`. This approach ensures reusable and decoupled combat behaviors.
2.  **Encapsulated Combat Logic**: Battle mechanics rely on highly encapsulated classes (`Defense`, `Offense`, `Armour`, and `Weapon`) that manage specific data and behavior. Damage is calculated based on the attacker's `Offense` power versus the defender's `Armour` and `Defense` metrics.
3.  **Modular Character Progression**: Implemented a data-driven progression system where character statistics, leveling, and equipment effects are fully modular. Players and enemies grow in power dynamically, ensuring a balanced challenge across dungeons.
4.  **Extensive C++ Implementation**: The entire project structure, including all core character, state, and item classes, was built in C++ to demonstrate mastery of the language's object-oriented features, as evidenced by the detailed UML class diagram.

## Final Result

**Text Trails** successfully delivered a fully functional, text-based auto-battler that serves as a robust demonstration of disciplined OOD. It showcases expertise in implementing complex design patterns like the State Machine to manage dynamic game logic.

You can view the repository [here](https://github.com/DarthPackman/Text-Trials).