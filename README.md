# Digital Clock with Dark/Light Mode (Round 2)

## Overview
A simple, elegant digital clock web app that:
- Displays the current time and updates every second.
- Shows the full current date below the time.
- Includes a dark/light mode toggle with smooth transitions.
- Remembers your theme preference using local storage.
- Respects the system color scheme when no manual preference is set.

## Setup
No build tools required.

1. Download or copy `index.html`.
2. Open `index.html` in any modern browser.

## Usage
- The time updates every second automatically.
- The date is shown below the time in a readable format (e.g., Wednesday, October 17, 2025).
- Click the “Dark/Light” toggle button in the top-right to switch themes.
- Your theme choice is saved and persists across page reloads.
- If you haven’t chosen a theme, the app follows your system’s light/dark preference.

## Improvements in Round 2
From the previous version (basic digital clock), this upgrade includes:
- Added a dark/light mode toggle with:
  - Smooth theme transitions
  - Accessibility (aria-pressed state and descriptive labels)
  - Persistent preference via `localStorage`
  - Fallback to system preference when no manual choice is stored
- Display of the current date beneath the time using a locale-aware, full-date format.
- Visual refinements and responsive layout for better readability.