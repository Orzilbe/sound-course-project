# sound-course-project

# Tap Tap — Rhythm Game

**Sound Design Course Project — Or Zilberberg**

A browser-based rhythm game where notes scroll down three lanes in sync with music. Hit them at the right moment using arrow keys or touch.

-----

## How to Play

### Desktop

Press the arrow keys as notes reach the hit line:

- **←** Left arrow — green lane
- **↑** Up arrow — blue lane
- **→** Right arrow — pink lane

### Mobile

Tap directly on the matching lane.

### Long Notes

Notes with a “tail” require **holding** — press and hold until the tail runs out.

-----

## ⭐ Scoring

|Accuracy|Points|
|--------|------|
|PERFECT |300   |
|GREAT   |200   |
|GOOD    |100   |
|MISS    |0     |

### Streaks & Bonuses

- Every 10 consecutive hits increases the score multiplier (×1.5, ×2, ×2.5…)
- Streak bonuses at 10, 20, 30, 40, 50, and 60 consecutive hits
- Successfully held long notes grant continuous points + a completion bonus

### Leaderboard

Top 10 high scores are saved locally (localStorage).

-----

## Tech Stack

- **HTML5 / CSS3 / Vanilla JavaScript** — no external libraries
- **HTML5 Audio API** — music sync via `audio.currentTime`
- **Touch Events API** — multi-touch support for mobile
- **CSS Animations** — visual effects (burst, feedback, countdown)
- **localStorage** — persistent leaderboard
- **Responsive Design** — adapts to desktop and mobile

-----

## Project Structure

```
├── index.html      # Main game file
├── Tap_tap.mp3     # Music track
└── README.md
```

-----

## Getting Started

1. Clone the repository:
   
   ```bash
   git clone https://orzilbe.github.io/sound-course-project/
   ```
1. Open `index.html` in a browser

Or access it directly via GitHub Pages.

-----

## Sound Design

The game is built around a futuristic neon theme with a layered audio approach:

- **Background layer** — the main music track (`Tap_tap.mp3`) sets the rhythm and energy
- **Visual feedback layer** — graphic effects (burst, glow, flash) replace traditional audio SFX, letting the music come through without interference
- **Gameplay layer** — note data (`levelData`) is mapped to music timestamps for tight synchronization

-----

## Credits

- Design & Development: Or Zilberberg
- Sound Design Course Project