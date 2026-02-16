# 数独 Sudoku-Meischter Kimchi

**schwäbisch denke · logisch löse**

A Sudoku teaching app with a Swabian AI teacher that explains human solving strategies in a mix of Schwäbisch, German, and English.

## Features

- **Three human strategies** taught step-by-step:
  - **Naked Singles** — when only one number fits a cell
  - **Hidden Singles** — when a number can only go in one place in a unit
  - **Cross-Hatching** — scanning from the most frequent digit
- **Puzzle generator** with three difficulty levels (Leicht / Mittel / Schwer)
- **Candidate notes** toggle to see possible numbers per cell
- **Mobile-first** touch-optimized design
- **Schwäbisch teacher** personality with dialect explanations

## Quick Start — GitHub Pages

1. **Fork or push** this repo to your GitHub account

2. **Enable GitHub Pages:**
   - Go to your repo → **Settings** → **Pages**
   - Source: **Deploy from a branch**
   - Branch: **main** (or master), folder: **/ (root)**
   - Click **Save**

3. **Done!** Your app will be live at:
   ```
   https://YOUR-USERNAME.github.io/sudoku-meischter/
   ```

## Local Testing

Just open `index.html` in a browser. No build step, no dependencies to install.

```bash
# Or use a local server for best results:
python3 -m http.server 8000
# Then open http://localhost:8000
```

## Tech Stack

- React 18 (via CDN)
- Babel standalone (JSX transpilation in-browser)
- Zero build step, single HTML file
- Pure CSS, no frameworks

## Project Structure

```
sudoku-meischter/
├── index.html    ← the entire app (self-contained)
└── README.md     ← you are here
```

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| 1-9 | Place number |
| Backspace/Delete | Clear cell |
| Arrow keys | Navigate grid |
| H | Request hint |

## Roadmap

- [ ] Claude AI conversational tutor
- [ ] More strategies (Naked Pairs, Pointing Pairs)
- [ ] Timer and statistics
- [ ] Daily puzzle
- [ ] PWA for homescreen install
- [ ] Python engine (backend on Google Cloud Run)

## License

MIT — do whatever you want with it.

---

*Made with ❤️ and lekkerer Zwiebelkuchen und en Süßmoscht*
