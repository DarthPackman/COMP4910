---
title: 'The Tea: Location-Based Anonymous Web Forum'
pubDate: 2023-03-10
author: 'DarthPackman'
description: 'A robust web application developed for COMP 3540 that allows users to anonymously "Spill The Tea" (post information). The core feature is the geographic filtering of content, ensuring users only view posts relevant to their real-world location.'
image:
    url: 'https://www.cobramode.com/wp-content/uploads/2021/07/cobramode-logo-website-big-1024x550.png'
    alt: 'The Tea logo, showing a stylized pink teacup.'
tags: ["Class Project", "PHP", "MySQL", "Web Development", "Database Integration", "Location Services", "CRUD Operations"]
video_url: ''
---

**The Tea** was the term project for **COMP 3540 (Adv Web Design & Programming)**, a functional web forum designed to allow users to **anonymously** create, interact with, and view posts. The system was built from the ground up, demanding robust server-side scripting and secure database management to handle user accounts and content.

## Core Technical Implementation

1.  **Geographic Content Filtering**: Implemented a core feature where the main content view ("Spill The Tea" page) **dynamically filters posts** based on the user's browser-provided location data and the location attached to each post. This ensures a localized, relevant social experience.
2.  **Full CRUD Functionality**: Programmed complete **CRUD (Create, Read, Update, Delete)** operations for both **User Accounts** and **Posts** using server-side **PHP** logic and a **MySQL** database (`TEA_USERS`, `TEA_POSTS` tables). This includes managing post content, user data, and vote scores.
3.  **Secure Authentication Flow**: Designed and implemented user registration and login, with all data managed through the backend. The system successfully handles complex account operations such as **editing email/password** and **deleting the full account**.
4.  **Database Design**: Structured a relational database in **MySQL (phpMyAdmin)** to securely store post information (ID, Text, Date, Location, Vote\_Score) and user account data (ID, Email, Password). Crucially, the system hides the `user` and `location` fields on the posts to maintain anonymity.

## Final Result

This project demonstrated strong skills in advanced, server-side web application development using a **PHP and MySQL stack**. It successfully merged database interaction with front-end features (upvoting/downvoting) and advanced browser features (geolocation) to deliver a unique, fully functional social forum.

You can view the repository [here](https://github.com/DarthPackman/TheTea).
