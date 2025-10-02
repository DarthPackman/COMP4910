---
title: 'Roll For Dungeon: Dice-Driven Procedural Dungeon Generation'
pubDate: 2023-10-10
author: 'DarthPackman'
description: 'A procedural content generation (PCG) system created for COMP 4980 that uses dice mechanics to generate over three million permutations of a Dungeons & Dragons 5th Edition dungeon, drastically reducing DM preparation time.'
image:
    url: 'https://img.itch.zone/aW1nLzIyMDU1OTM3LnBuZw==/original/1bfIl7.png'
    alt: 'Cover art for Roll For Dungeon, showing a fantasy figure before a snowy crypt.'
tags: ["Class Project", "Procedural Generation", "Game Design", "System Architecture", "Tabletop RPG", "D&D 5e"] 
---

**Roll For Dungeon (RFD)** was the foundational project for **COMP 4980 (Procedural Content Generation)**, designed to solve the problem of high preparation time in tabletop RPGs. By harnessing simple **dice mechanics** in place of a complex algorithm, RFD procedurally generates entire D&D 5th Edition dungeons, ensuring unique and unpredictable adventures with minimal effort from the Dungeon Master.

## Procedural Design and System Architecture

1.  **Vast Permutation Space**: The system uses a modular design of **12 unique Room tiles** (rolled with a d12) and **8 unique Pathway tiles** (rolled with a d8). With multiple variations for each, this system delivers **nearly three million distinct dungeon layouts**.
2.  **Tiered Encounter Generation**: Rooms are further procedurally varied into three distinct encounter types (**Combat, Trap, and Puzzle**), based on a loose **5 Room Dungeon** design principle.
3.  **Modular Boss Design**: Boss encounters were custom-designed based on existing D&D 5e stat blocks and enhanced with **"Action-Oriented Monster"** principles, providing dynamic new abilities that escalate the final challenge.
4.  **Content Production Pipeline**: The project managed a multi-phase development process, using tools like **Dungeon Scrawl** and **Dungeon Alchemist** for map design, **ChatGPT** for narrative descriptions, and **Homebrewery** for final PDF layout and presentation.

## Final Result

Roll For Dungeon successfully proved that complex procedural generation outcomes can be achieved through accessible, rules-based systems rather than pure code. The final, polished PDF and tile assets create a professional, ready-to-play system that significantly reduces DM prep time.

You can download the project files and PDF documentation [here](https://drive.google.com/file/d/1Oict2wRTEKIwnXInzqD4HadbUg1zdQJa/view?usp=sharing).