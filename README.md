<p align="center">
  <img src="icons/icon-512.png" alt="Filmion app icon" width="160" height="160">
</p>

<h1 align="center">Filmion</h1>

<p align="center">A Krillion-style trivia game about movies and TV.</p>

Each game has seven prompts and 25 seconds per prompt. Give the rarest answer you can that is still correct. Claude judges each answer and ranks it from Plankton (4 points) to One in a Krillion (100 points).

## Modes

- **Daily**: the same seven prompts for everyone, new each day.
- **Unlimited**: random prompts that avoid ones you've already seen.
- **Custom game**: pick one franchise and all seven prompts come from it.

## App icon

The icon is a gold (`#E3B257`) film camera on a dark background. Files are in [`icons/`](icons):

| File | Use |
| --- | --- |
| `icon-1024.png` | App stores, social preview |
| `icon-512.png`, `icon-192.png` | Web app manifest |
| `apple-touch-icon.png` (180px) | iOS home screen |
| `favicon-32.png`, `favicon-16.png`, `../favicon.ico` | Browser tabs |
| `icon.svg` | Vector source |

## Note on judging

Answer judging uses Claude through the claude.ai artifact runtime. When `index.html` is opened outside claude.ai, the game loads but shows a notice that judging isn't available.
