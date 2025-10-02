---
title: 'Behavioral Authentication & Anomaly Detection System'
pubDate: 2024-11-20
author: 'DarthPackman'
description: 'A security-focused project for COMP 3260 demonstrating how websites can enhance security using behavioral biometrics. The system tracks user interactions to build an authentication profile and detect anomalous, bot-like activity in real-time.'
image:
    url: 'https://www.cobramode.com/wp-content/uploads/2021/07/cobramode-logo-website-big-1024x550.png'
    alt: 'Cobramode logo.'
tags: ["Class Project", "Network Security", "Behavioral Biometrics", "Anomaly Detection", "Web Development", "JavaScript", "Firebase"]
---

This project, developed for **COMP 3260 (Computer Network Security)**, focused on implementing a robust, non-traditional security layer using **behavioral biometrics**. The system is designed to function automatically without requiring explicit user permission, making it simple to implement on any site that uses Firebase authentication.

## Core Technical Implementation

1.  **Behavioral Biometric Tracking (JavaScript)**: Implemented extensive client-side **JavaScript tracking** to collect granular user behavior metrics and generate a real-time `userScore`. Tracked metrics included:
    * **Keystroke Dynamics**: Speed and variety of keyboard presses.
    * **Mouse Activity**: Movement speed, path, and click activity.
    * **Session Metrics**: Time spent on page, scrolling activity, and window focus changes.
2.  **Real-Time Anomaly Detection & Response**: The system triggers a **custom CAPTCHA** (designed with DALL·E-generated images to be harder for AI to bypass) if the `userScore` falls below a suspicious behavior threshold.
3.  **Anti-Redliner IP Change Detection**: Programmed a crucial anti-brute force measure that uses a custom **JavaScript fetch function** to grab the user's current IP address. If the IP address changes while the user is logged in, the system automatically **logs the user out** and increments an `ipChangeCount`, ultimately leading to an **account lock** if suspicious activity continues.
4.  **Full-Stack Integration (Firebase)**: Leveraged **Firebase** for user authentication and to securely store security data, including `ipAddress`, `captchaTriggerCount`, and `accountLock` status, which informs the secondary response mechanisms.

## Final Result

This project delivered a working security prototype that is simple to integrate and monitor. It successfully demonstrates expertise in implementing advanced security concepts against attacks, specifically passive behavioral authentication and anomaly detection, within a full-stack web environment.

You can view the repository [here](https://github.com/DarthPackman/COMP3260).