# Spider-Man Game

A browser-based Spider-Man side-scrolling action game built with **HTML5 Canvas, CSS3, and vanilla JavaScript**.

The player controls Spider-Man across rooftop sections, jumps between obstacles, and shoots web projectiles at enemies. The game includes a score display, health system, soundtracks, sound effects, pause controls, and a restart screen.

## Features

- HTML5 Canvas-based gameplay
- Side-scrolling rooftop environment
- Spider-Man movement, jumping, and web shooting
- Enemy characters and projectile interactions
- Score display
- Player health and gradual health regeneration
- Background music and web-shooting sound effect
- Pause menu with resume, music mute, sound-effect mute, and slow-motion options
- Game Over screen with final score and restart option
- Custom image, font, and audio assets

## Controls

| Key | Action |
| --- | --- |
| `←` | Move left |
| `→` | Move right |
| `↑` | Jump |
| `Spacebar` | Shoot web |
| `Esc` | Pause / Resume |

## Getting Started

### 1. Download or clone the project

Download this repository and extract the project folder.

### 2. Keep the project structure

Make sure the folders stay in their original locations:

```text
Spider-Man-Game/
├── audio/
│   ├── 60-theme-song.mp3
│   ├── amazing-spider-man-2.mp3
│   ├── animated-series-theme.mp3
│   ├── old-theme.mp3
│   └── shooting-web.mp3
├── css/
│   └── spiderman-game.css
├── fonts/
│   ├── Adventure.ttf
│   └── pixel.otf
├── images/
│   └── ... game images and sprites
├── index.html
└── spiderman-game.js
```

### 3. Run the game

Open `index.html` in a modern web browser.

If your browser restricts local file resources, run the folder with a local development server (for example, the **Live Server** extension in Visual Studio Code), then open the local URL it provides.

## Technologies Used

- **HTML5** — page structure and Canvas element
- **CSS3** — layout and game menu styling
- **JavaScript** — game loop, controls, player/enemy logic, collision handling, and audio
- **HTML5 Canvas API** — rendering the game scene

No JavaScript framework or package installation is required.

## Project Notes

- Keep `audio/`, `css/`, `fonts/`, and `images/` alongside `index.html` and `spiderman-game.js`. The game loads these assets using relative paths.
- The game canvas is initialized at **711 × 400** pixels.
- The game starts loading its image assets when the page is opened.
- The source code identifies the original author in the HTML metadata as **Chandula Janith (RedEdge967)**. Retain appropriate attribution if you redistribute or modify the project.
- Check the usage rights of included images, fonts, and audio before publishing or redistributing the project.

---

Made with HTML, CSS, and JavaScript.
