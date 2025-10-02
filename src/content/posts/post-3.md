---
title: 'Handshake Murder: Prototyping Proximity Games'
pubDate: 2022-03-15
author: 'DarthPackman'
description: 'A unique mobile app game, developed for COMP 2160, centered on identifying and eliminating targets. The project showcased critical mobile development resourcefulness by pivoting from deprecated NFC technology to a functional code-based solution integrated with Firebase.'
image:
    url: 'https://img.itch.zone/aW1nLzgwNjQ0MDEuanBn/original/qSUE8z.jpg'
    alt: 'Handshake Murder concept art or screenshot.'
tags: ["Class Project", "Mobile Development", "Android Studio", "Java", "Firebase", "Prototyping", "UIUX"]
video_url: ''
---

For **COMP 2160 (Mobile App Development 1)**, I developed **Handshake Murder**, a strategic social deduction game focused on proximity-based interaction. The project provided critical experience in navigating the complexities of mobile development, requiring strategic resourcefulness when faced with API obsolescence.

## Core Technical & Implementation Challenges

1.  **Backend Integration (Firebase)**: The final working **"handshake"** mechanism was successfully implemented using **Firebase** to manage real-time communication between players. The prototype utilized an **input field and a button** to trigger a code handshake, with Firebase managing the secure, real-time transfer of elimination and identity data.
2.  **Navigating Deprecated APIs**: The initial design prioritized utilizing proximity hardware features like **Android Beam** and **NFC handshakes**. When these proved deprecated or unstable for a functional prototype, the challenge pivoted to creating a reliable, software-based solution.
3.  **Client-Server Role Management (Java)**: All core gameplay and state management logic (Host/Client, Murderer/Investigator) were programmed in **Android Studio using Java**. This included handling game timers, player roles, and tracking elimination events.
4.  **UI/UX Design**: Designed and implemented a comprehensive game interface, including key real-time indicators like a **Player Count/Health Bar**, **Killer Progress Bar**, and **Timer**, crucial for facilitating interactive social play.

## Final Result

This project stands as a robust demonstration of core mobile programming techniques and a showcase of **critical problem-solving** in overcoming technical hurdles imposed by hardware constraints. It validates my ability to integrate a mobile frontend with a multi-user backend service like **Firebase**.

You can view the full source code and technical documentation in the repository [here](https://github.com/DarthPackman/Handshake-Murder).
