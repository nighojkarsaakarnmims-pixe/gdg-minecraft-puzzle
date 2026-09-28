# GDG Minecraft Sliding Puzzle 🧩🎮

An interactive, single-file 3x3 sliding block puzzle featuring a pixelated **Google Developer Groups (GDG)** logo set inside an authentic **Minecraft** deepslate dark UI aesthetic.

## Features ✨
- **Authentic Minecraft Aesthetics**: Deepslate dark stone block textures, pixel bevel borders, and pixel font (`Press Start 2P`).
- **Official GDG Branding**: Exact Google brand colors (`#4285F4`, `#EA4335`, `#34A853`, `#FBBC04`) with dark slate background.
- **Infinite Solvable Auto-Shuffle**: Guarantees a 100% solvable board state on load, reset, and round completion using inversion parity validation.
- **Synthesized 8-bit Audio**: Retro Web Audio API block placement and XP level-up chime SFX.
- **Stats & HUD**: Live move counter, timer, win tracker, hint logo overlay, and keyboard navigation (`WASD` / `Arrow Keys`).

## Deploy on Vercel 🚀

### Method 1: GitHub Integration (Recommended)
1. Create a new repository on [GitHub](https://github.com/new).
2. Upload `index.html`, `package.json`, and `README.md` to the repository.
3. Go to [Vercel Dashboard](https://vercel.com/new) -> **Import Git Repository**.
4. Click **Deploy**. Vercel will automatically host the static website!

### Method 2: Vercel CLI
Run the following in terminal:
```bash
npx vercel
```
