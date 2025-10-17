# Digital Clock with Dark/Light Mode

## Overview
A simple, responsive digital clock web app that displays the current time and date, with a dark/light mode toggle. The selected theme is remembered across visits and can also follow the system preference if no explicit choice is made.

## Setup
- No build steps required.
- Download or clone the project and open index.html in any modern web browser.

## Usage
- Open index.html.
- The current time updates every second.
- The current date is displayed beneath the time and updates automatically.
- Use the toggle in the top-right to switch between light and dark modes.
  - Your choice is saved and will persist on reload.
  - If you haven’t chosen a theme, the app follows your system’s color scheme.

## Improvements in Round 2
- Added dark/light mode toggle with:
  - Smooth transitions.
  - Preference persistence via localStorage.
  - System preference detection and automatic updates when no explicit choice is stored.
- Displayed the current date beneath the time, localized to the user’s browser locale.
- Minor UI/UX polish: accessible toggle, responsive typography, and meta theme-color for better mobile appearance.