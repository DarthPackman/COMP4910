---
title: 'Dungeoneer: Seed-Based Runtime PCG Dungeon Crawler'
pubDate: 2023-10-15
author: 'DarthPackman'
description: 'A 3rd-person, Z-targeting dungeon crawler developed in Unity for COMP 4980. This project showcases advanced runtime procedural content generation (PCG) for environments, characters, enemy stats, and music.'
image:
    url: 'https://darthpackman.itch.io/dungeoneer'
    alt: 'Dungeoneer title screen showing a character with a torch.'
tags: ["Class Project", "Procedural Generation", "Unity", "C#", "Game Development", "Runtime Generation", "Modular Design"]
---

**Dungeoneer** was a multi-faceted group project for **COMP 4980 (Procedural Content Generation)** that shifted from a walking simulator to a **3rd-person Z-Targeting Dungeon Crawler**. This project was a deep dive into **seed-based, adaptive PCG**, where core game elements—from the terrain mesh to individual enemy attributes—are generated *at runtime* based on a central world seed.

## Core PCG Systems & Implementation

1.  **Modular Room Generation (Grid-Based PCG)**: Implemented a proprietary **grid-set system** to manage tile generation, ensuring room types (A, B, C) only spawn in designated areas (e.g., C-types only in corners) to create structurally sound dungeons. Rooms are instantiated and destroyed using colliders for efficient **chunk loading**.
2.  **Character & Enemy PCG (My Contribution)**: Led the development of **Character PCG** in **C#**, where the **CharacterSeed** dictates multiple parameters at runtime, including:
    * **Visuals**: Randomizing armor pieces and head models.
    * **Mechanical Stats**: Generating enemy attributes like movement speed, attack strength, and detection range.
    * **Patrol AI**: Determining the enemy's patrol path and order using the **CharacterSeed** to add mechanical variety.
3.  **Dynamic Music Integration**: Assisted with a novel **mood-based music generation** system where a room's seed determines a mood value, which, in turn, selects pre-generated audio files (piano, bass, drums) with matching mood values, ensuring sonic coherence.

## Final Result

Dungeoneer is a showcase of my ability to implement complex, multi-layered PCG systems in a challenging development environment (Unity). It demonstrates expertise in using modular design to create high-variance content, including custom enemy AI states (Attack, Chase, Patrol) and traversal mechanics (Jump, Dodge Roll).

You can play the game on [Itch.io](https://darthpackman.itch.io/dungeoneer).