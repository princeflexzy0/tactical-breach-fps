# TACTICAL BREACH

A tactical first-person shooter built with Three.js.

[![make.fun bounty](https://make.fun/b/threejs-fps-02/badge.svg)](https://make.fun/bounty/threejs-fps-02)
[![rank](https://make.fun/b/threejs-fps-02/rank/princeflexzy0%2Ftactical-breach-fps.svg)](https://make.fun/bounty/threejs-fps-02)
[![reward](https://make.fun/b/threejs-fps-02/reward/princeflexzy0%2Ftactical-breach-fps.svg)](https://make.fun/bounty/threejs-fps-02)

## Play

Open `index.html` in any modern browser — no build step needed.

## Controls

| Key | Action |
|-----|--------|
| WASD | Move |
| Mouse | Look |
| LMB | Shoot |
| R | Reload |
| F | Switch weapon |
| Q | Throw grenade |
| Shift | Sprint |
| Space | Jump |

## Features

- Full tactical FPS with Three.js
- Two weapons: Assault Rifle + Pistol
- Enemy AI with state machine (idle / chase / attack / hurt / dead)
- Wave-based combat — enemies get harder each wave
- Procedural audio (gunshots, footsteps, explosions, reloads)
- Minimap, kill feed, health bar, ammo HUD
- Grenade with explosion radius damage
- Pointer Lock controls, weapon bob, screen shake
- Fog, dynamic lighting, shadow maps

## Run

```bash
# No install needed — just open index.html
open index.html

# Or serve locally:
npx serve .
```

Built with [Three.js](https://threejs.org) r165 — entry for [make.fun/bounty/threejs-fps-02](https://make.fun/bounty/threejs-fps-02).
