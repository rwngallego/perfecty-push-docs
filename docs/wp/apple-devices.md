---
title: Apple devices - iOS/Safari
description: Apple supports the Push API under certain circumstances
---

To get the Push Notifications working on iOS or iPadOS, whe following requirements must be met:
- Minimum version 16.4 of the OS
- The page must have a valid [manifest.json](https://web.dev/articles/add-manifest) in which the property "display" must be set to "standalon" or "fullscreen"
- The page must be saved to the homescreen

If the requirements are met, the user has to open the website via the app icon on their homescreen and the notification dialogue will appear.
