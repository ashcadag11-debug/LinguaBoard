# LinguaBoard

A daily language puzzle. Match languages to a 3×3 grid based on linguistics, script, and translation facts.

Built by [MachineTranslation.com](https://www.machinetranslation.com).

## Play

Live: https://mtashcdg.github.io/LinguaBoard/

## What's in here

|     Path     |                   What it is                                          |
|----------|---|
| `index.html` | The entire game — markup, styles, and logic in one file               |
| `fonts/`     | Self-hosted Poppins, Playfair Display, and Space Mono (woff2)          |
| `.nojekyll`  | Tells GitHub Pages to serve the files as-is, without Jekyll processing |

No build step, no dependencies, no external requests. Open `index.html` in any
browser and it runs.

## Notes

- Validates cleanly against the W3C HTML5 spec.
- Progress, streaks, and stats are stored in `localStorage`. Where a browser
  blocks storage (third-party iframes in Safari, for example), the game falls
  back to an in-memory store and stays playable for the session.
- Layout switches to a three-column desktop view at 1240px and above.
