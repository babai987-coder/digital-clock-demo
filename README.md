# Digital Clock (Dark/Light Mode + Date)

## Overview
A simple, responsive digital clock web app that:
- Displays the current time (updates every second)
- Shows the current date below the time
- Supports dark and light themes with a toggle
- Remembers your theme preference and respects your system setting by default

## Setup
1. Download or clone this project.
2. Open `index.html` in any modern web browser. No build tools or servers required.

## Usage
- Time and date update automatically every second.
- Use the theme switch (sun/moon toggle) in the header to switch between dark and light modes.
- Your selection is saved in your browser (localStorage). If you haven’t explicitly chosen a theme, the app follows your device’s system theme and updates if it changes.

## Improvements from previous version (Round 2)
- Added a dark/light mode toggle with a polished switch UI and accessible `role="switch"`.
- Implemented persistent theme preference using localStorage.
- App now respects system theme by default and reacts to system changes unless a user preference is set.
- Added full date display (e.g., Wednesday, October 22, 2025) below the time.
- Refined styling and layout for better readability and responsiveness.