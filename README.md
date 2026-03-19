# MusicQuiz

A browser-based music quiz soundboard. Set up categories with YouTube clips, then run a live quiz from a Jeopardy-style grid — play a clip, let teams guess, reveal the answer.

## Features

- Grid-based soundboard with three point tiers (30, 40, 50)
- YouTube integration with configurable start/end timestamps
- Optional multiple choice answers (A, B, C, D) per question
- Setup screen with category management and drag-to-reorder
- Import/export quiz configurations as JSON
- Game state tracking — used and revealed states with visual distinction, supports mid-game reset
- Built-in "How to Use" guide with step-by-step instructions
- Dark retro UI with scanline overlay and monospace fonts
- Zero dependencies — single HTML file, runs in any modern browser

## How to Use

1. Open `index.html` in a browser
2. Go to **Setup** — name your event, add categories, and fill in questions with YouTube video IDs and clip timestamps
3. Switch to **Soundboard** — click a point circle to open a question
4. Hit **Play** to stream the clip, **Stop** when ready, and **Reveal Answer** to show the artist and song
5. Questions with multiple choice answers display options automatically when the clip plays
6. Revealed questions turn green, played-but-unrevealed questions are dimmed. Use **Reset Game** to start a fresh round with the same categories.

## Tech Stack

- Vanilla HTML, CSS, and JavaScript (no build step, no frameworks)
- YouTube IFrame Player API for audio playback
- localStorage for persisting quiz data between sessions
- Google Fonts (Bebas Neue, DM Mono)

## Credit

by Fisers Davis
