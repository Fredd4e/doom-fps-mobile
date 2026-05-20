# 🔫 Doom FPS Mobile

A browser-based 3D first-person shooter inspired by classic Doom, featuring modern Three.js graphics, **physics-driven particle effects**, and **touch-optimized controls** perfect for playing on your phone.

**Play it now on GitHub Pages:** https://Fredd4e.github.io/doom-fps-mobile/

## Recent Fixes & Improvements (May 2026)
- **Camera aligned correctly**: Fixed pitch control direction so dragging finger **up** now looks **up** (intuitive). Better initial pitch and sensitivity.
- **Goblin enemies fixed**: Replaced broken/missing texture with high-quality **procedural canvas sprite** (pixel-art style imp/goblin with horns + glowing eyes). Always loads, no external image dependency. Proper upright billboard + gentle bob animation so the image displays correctly.
- General polish: Muzzle flash on shoot, richer death/explosion particles, added ceiling + extra cover pillars, improved spawn points, keyboard (WASD + Space) support for desktop, brief intro message, tuned gameplay values, cleaner code.

## Features
- Full 3D first-person view with smooth touch drag to look around
- On-screen buttons for movement (forward/backward/strafe) and shooting
- Projectile physics with velocity, gravity and lifetime
- Satisfying particle effects with gravity and bouncing debris on impact
- Dark, atmospheric Doom-like arena with ceiling, pillars and warm lighting
- Shoot goblins for score — satisfying explosions with particles!
- Fully static site, works great on mobile browsers (and desktop)

## How to Play on Your Phone

1. Open **https://Fredd4e.github.io/doom-fps-mobile/** in Chrome or Firefox on your phone.
2. **Look**: Drag your finger across the 3D view to turn and aim (now correctly aligned).
3. **Move**: Tap and hold the directional buttons at the bottom left.
4. **Shoot**: Tap or hold the big red **SHOOT** button. Bullets fly with physics + muzzle flash.
5. Destroy the goblins to rack up points. Have fun blasting!

> **Tip**: Enable GitHub Pages in repo Settings > Pages if the site doesn't load immediately (set source to `main` branch, root folder).

## Controls Summary
| Action       | Control                          |
|--------------|----------------------------------|
| Look/Aim     | Drag finger on screen (up=look up) |
| Forward      | ↑ button                       |
| Backward     | ↓ button                       |
| Strafe Left  | ← button                       |
| Strafe Right | → button                       |
| Shoot        | Big red SHOOT button             |
| (Desktop)    | WASD + Space to shoot            |

## Tech Stack
- Three.js (r128) for 3D rendering
- Vanilla JavaScript + Tailwind CSS (CDN)
- GitHub Pages for hosting

Built as a fun prototype. Feel free to fork and improve!

*Created for Fredd4e — enjoy your mobile FPS!*