# Hallows Island

A cozy-spooky 3D top-down island adventure that runs in the browser and installs on your phone as a full-screen app.

Create your character, then explore a moonlit island: take quests from Pumpkin Pete and Keeper Wick, fish off the dock, mine glowing crystals, chop trees for wood, harvest pumpkins, fight skeletons in the graveyard, trade with Hazel the merchant, and build, upgrade and decorate your house inside and out.

## Play

**https://slickxhead.github.io/Hallows-Island/**

## Install on your phone

**iPhone / iPad (Safari)**
1. Open the link above in Safari.
2. Tap the Share button, then **Add to Home Screen**.
3. Launch **Hallows** from your home screen. It opens full screen.

**Android (Chrome)**
1. Open the link above in Chrome.
2. Tap **Install App** on the title screen, or open the ⋮ menu and choose **Install app**.
3. Launch **Hallows** from your home screen or app drawer.

After the first launch the game works offline. Progress is saved on the device.

## Controls

| Action | Phone | Keyboard |
| --- | --- | --- |
| Move | Joystick (push far to run) | WASD / arrows, Shift to run |
| Interact | USE button | E |
| Slash / Fire burst / Spirit bolt | Skill buttons | J (Space) / K / L |
| Bag / Quests / Build | Top-right buttons | I / Q / B |
| Pause | Menu button | Esc |

## Characters

The player character is a 3D model generated with Tripo3D, split into parts, rigged, and animated with Tripo motion presets: idle, walk, run, slash, cast, dig, lift, victory and a knock-down. The game colors it from your character-creator choices, blends walk and run by speed, and plays attacks on the upper body so you can fight while moving. The original blocky character is still available as **Classic** in the character creator.

## Files

- `index.html` — the whole game (three.js r128, loaded from cdnjs and cached for offline use)
- `models/hero.glb` — the rigged player character
- `models/heroine.glb` — the rigged girl character (her own idle, walk and run; the boy's actions retargeted onto her)
- `models/pete.glb` — Pumpkin Pete (your model, cut down and given a simple skeleton so he can stroll the plaza)
- `manifest.webmanifest`, `sw.js`, `icons/` — what makes it installable as an app
