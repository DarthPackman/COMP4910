---
title: 'Doki Doki Dragoons: Chain Reaction Auto-Battler Design'
pubDate: 2025-01-26
author: 'DarthPackman'
description: 'A survival auto-battler game developed for the Dokibird Game Jam under the theme "Chain Reaction." The game introduces a novel progression system where weapon archetypes detonate, renew, or spread status effects to create cascading combat chains.'
image:
    url: 'https://darthpackman.itch.io/dokidokidragoons'
    alt: 'Doki Doki Dragoons gameplay screenshot showing the Dragoon character and various weapon effects.'
tags: ["Game Jam", "Unity", "C#", "Auto-Battler", "Chain Reaction", "Game Design", "Progression System"]
---

**Doki Doki Dragoons** was an ambitious survival auto-battler created for the **Dokibird Game Jam**, directly addressing the theme **"Chain Reaction."** Inspired by *Vampire Survivors*, the project focuses on an elaborate **chaining status effects system** where the player's 16 available weapons work together to create cascading combat loops, requiring strategic weapon selection to successfully survive a 15-minute challenge.

## Advanced Progression & Combat System

1.  **Chain Reaction Logic**: The core mechanic revolves around **four distinct weapon archetypes** (*Regular*, *Egg*, *Tall*, *Chonky*), each linked by a progression chart that dictates how debuffs are applied, renewed, or detonated.
    * **Chain Effects**: The *Chonky* archetype detonates the *Egg* archetype, which renews the *Regular* archetype, and so on, creating a constant, challenging combat feedback loop.
2.  **Modular Weapon System (16 Weapons)**: Designed and implemented 16 unique weapons categorized by archetype (*Melee*, *Projectile*, *Aura*, *Zone*) and effect. Weapon effects include core damage (`Wing Slap`), unique debuffs (`Weaken` with a 25% damage reduction ), and utility effects (`Knockback`).
3.  **Weapon Ordering and Cooldown**: Implemented a core gameplay loop where the player must strategically select a **Weapon Order**. Weapons fire sequentially, with each weapon being **active for 5 seconds** before going on cooldown and cycling to the next weapon in the player's order.
4.  **Survival Progression**: The core loop challenges the player to **Grow** (select upgrades), **Kill** (enemies), **Reward** (gain resources), and face a constantly escalating **Challenge**. Upgrades and Evolutions are offered upon level-up, requiring a minimum of **two matching weapon archetypes** to achieve a powerful Evolution.

## Final Result & Vision

Doki Doki Dragoons showcases high proficiency in abstract system design and the rapid development of complex, interconnected game systems. The project successfully executed a highly technical vision, blending humorous mood with heroically themed, challenging gameplay in the distinctive Dokiville world.

You can play the game and experiment with the weapon chains on [Itch.io](https://darthpackman.itch.io/dokidokidragoons).