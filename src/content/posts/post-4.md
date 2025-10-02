---
title: 'Manhunt: Location-Based Multiplayer Stealth'
pubDate: 2022-11-20
author: 'DarthPackman'
description: 'A cutting-edge, location-based multiplayer game developed for COMP 3160. Manhunt combines real-world hide-and-seek with digital tracking, demonstrating advanced integration of Google Maps API and a real-time database.'
image:
    url: 'https://github.com/DarthPackman/Handshake-Murder/blob/main/manhubnt.png'
    alt: 'Manhunt Gameplay.'
tags: ["Class Project", "Mobile Development", "Android Studio", "Java", "Firebase", "Google Maps API", "Location-Based Game", "Multiplayer"]
---

**Manhunt** is an innovative, location-based mobile game that transforms the classic game of Hunter into an intricate game of cat and mouse using modern technology. Developed for **COMP 3160 (Mobile App Development 2)**, the project's core challenge was building a robust, real-time tracking system capable of supporting fluid multiplayer gameplay across a large geographic area.

## Core Technical Implementation

1.  **Real-Time Data Architecture (Firebase)**: Structured and managed all game state and player data using a **Firebase Realtime Database**. The database controls player roles, game timers, and crucial game flow transitions (Gamestate).
2.  **Location Services Integration (Google Maps API)**: Integrated the **Google Maps API** and Android location services to obtain the user’s latitude and longitude. This data is continuously updated to the Firebase database for real-time position tracking.
3.  **Advanced Stealth Mechanic**: Implemented a core stealth feature where the **Hunter's map displays the Hunted player positions only briefly every minute**. This periodic update creates a sophisticated "last known position" mechanic, encouraging strategic movement.
4.  **Tagging System**: Created a secure, synchronized tagging system where a successful tag requires the Hunter to input a unique, randomly generated **TAG number** provided by the Hunted player.
5.  **Robust Game Logic**: Managed complex win conditions: Hunters win by tagging 90% of players, or Hunted players win if over 10% remain untagged at the end of the game timer.

## Final Result

Manhunt is a powerful demonstration of full-stack mobile development, successfully combining a real-time backend with complex location APIs to create a high-stakes, engaging multiplayer experience. This project laid the foundation for future work, including plans for adding features like Geo Fencing and customizable settings.

You can view the repository [here](https://github.com/DarthPackman/Manhunt).
