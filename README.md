# PinUp - Physics Vertical Flipper Platformer

A physics-driven vertical climber built with Unity 2D and C#. PinUp combines high-speed pinball mechanics with the high-stakes vertical climb structure of precision rage games such as *Getting Over It*. Players navigate an ascending gauntlet of dynamic obstacles, rotating crossbars, and collapsing platforms using motor-driven dual flippers.

---

## Overview

In PinUp, progression is earned one level at a time. The player launches a weighted pinball upward through successive obstacle chambers. Missing a flipper hit or mistiming a shot can result in the ball dropping through previous levels back toward the base, creating an intense risk-and-reward gameplay loop.

The game features dynamic stage streaming, procedural color transitions between game stages, continuous collision physics, and responsive multi-touch controls for mobile and desktop platforms.

---

## Visual Showcase

> [!NOTE]
> The images below are placeholders. This image requires updating with final in-game captures.

### Gameplay in Action
![Gameplay Flipper Climb](screenshots/gameplay-flipper-climb.png)
*Placeholder: This image requires updating with live gameplay capture.*

---

### Stage Progression & Procedural Gradient Transition
![Stage Progression Overview](screenshots/stage-progression-overview.png)
*Placeholder: This image requires updating with stage transition capture.*

---

### Controls & Input Architecture
![Controls and Architecture](screenshots/controls-and-architecture.png)
*Placeholder: This image requires updating with controls & settings overlay capture.*

---

### Plinko Recovery & Bottom Zone
![Plinko Recovery Zone](screenshots/plinko-recovery-zone.png)
*Placeholder: This image requires updating with bottom safety zone capture.*

---

## Core Gameplay

- **High-Stakes Vertical Climbing**: Propel the ball upward chamber-by-chamber using twin flippers. A missed shot sends the ball tumbling down through earlier stages, requiring quick reflexes to recover.
- **Dual-Touch Controls**: Tap the left or right side of the screen to activate each flipper independently, with full multi-touch and keyboard support.
- **Stage Progression & Gradient Transitions**: Advance through 10 Stage 1 levels into Stage 2 with a seamless procedural color gradient connecting the themes.
- **Dynamic Hazards**: Navigate rotating crossbars, crushing traps, breakable platforms, and dropping boulders calibrated with realistic physical inertia.
- **Active Level Streaming**: Automatically activates levels near the player and culls distant chambers to preserve smooth 60+ FPS performance.
- **Settings & Audio Controls**: Integrated pause screen with instant toggles and volume sliders for music and sound effects.

---

## Controls Reference

| Action | PC / Keyboard | Mouse | Mobile / Touch |
| :--- | :--- | :--- | :--- |
| Left Flipper | Left Arrow / A / Space | Left Click (Left Half) | Tap Left Screen Half |
| Right Flipper | Right Arrow / D / Space | Left Click (Right Half) | Tap Right Screen Half |
| Table Nudge | Up Arrow / W | - | Nudge Action |
| Pause / Resume | Escape / P | Top-Right Button | Tap Pause Icon |
| Quick Restart | R | Retry Button | Tap Retry Button |

---

## Technical Architecture

```
PinUp-Showcase/
├── screenshots/
│   ├── gameplay-flipper-climb.png
│   ├── stage-progression-overview.png
│   ├── controls-and-architecture.png
│   └── plinko-recovery-zone.png
└── README.md
```

### Tech Stack
- **Game Engine**: Unity 2022.3 LTS
- **Scripting Language**: C# 9.0 (.NET Standard 2.1)
- **Physics**: Unity 2D Physics (`Rigidbody2D`, `HingeJoint2D`, `CircleCollider2D`, `BoxCollider2D`)
- **Rendering**: Universal 2D Sprite Renderer with runtime procedural gradient generation
- **UI Framework**: Unity UI (uGUI) with Canvas Scaler

---

## Repository Links

- **Private Development Repository**: `https://github.com/kevnevv/PinUp` (Full project source, Unity scenes, assets, and project settings)
- **Public Showcase Repository**: `https://github.com/kevnevv/PinUp-Showcase` (Showcase documentation and media assets)

---

## License

This showcase repository and its documentation are distributed under the MIT License. Game design, original artwork, and codebase are copyright KevNev.
