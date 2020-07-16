---
title: Design Considerations for Blindness
date: 2020-07-16T19:26:14.073Z
author: John Appleseed
summary: Designing and developing for blind users.
tags:
  - web accessibility
  - wcag
  - design
  - development
  - blindness
---
## As a Developer

### Web
* All content must be presented in text or text equivalent
* All functionality must be available using only the keyboard
* Use good structure and semantic HTML
* All custom controls must have correct `name`, `label`, `role`, and `value`
* Users must receive immediate feedback after all actions
* Videos require audio descriptions

### Mobile
* All features require a click action
* Custom swipe actions on web pages won't work with the screen reader turned on

## As a Designer
* Don't rely only on icons. Use icons and text together.
* Think about what order users will be navigating through your designs, and what keys they will be using.
* Consider including a pattern of keyboard shortcuts with your designs.
