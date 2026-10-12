# Exam Clock

A simple exam clock for proctoring. It shows the current time, a live countdown and a notes board for rules, clarifications or typo fixes, and you can project it all in fullscreen.

**Live:** https://kevinnie2003.github.io/exam-clock/

## Features

- **Countdown:** set an end time, or use a shortcut such as +50 min or +2:00. Use the −5 / +5 / +10 buttons to extend or shorten the exam. The countdown turns amber at 15 minutes, red at 5 minutes, and blinks at time's up.
- **Notes:** bold, italic, underline, bullet and numbered lists (Tab to indent), text colors, highlight and text size. Type `- ` or `1. ` to start a list.
- **Presentation mode:** press `P` or click Present. The clocks sit across the top, and the notes fill the rest of the screen and shrink to fit. Press `Esc` to exit.
- **Screen stays on:** while presenting, the page asks the browser to keep the screen from dimming or sleeping.
- **Works in light and dark mode,** following your system setting.

## How it works

It's a single `index.html` with no server, no build step and no dependencies. Everything you enter is saved in your own browser (localStorage), so it survives a refresh, but nothing is shared between devices or people. Anyone opening the page starts with a blank clock.

## Run locally

Open `index.html` in a browser. To host your own copy, fork this repo and enable GitHub Pages on the `main` branch.
