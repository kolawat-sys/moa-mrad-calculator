# MOA & MIL Calculator — Target Size Calculator

A clean, mobile-first calculator for MOA and MIL (MRAD) subtension — work out up to **5 targets at once**. Spun off from [COF Calculator](https://kolawat-sys.github.io/cof-calculator-22lr/).

🔫 **[Open the live calculator →](https://kolawat-sys.github.io/moa-mrad-calculator/)**

## What it does

Each target links three values:

| Field | Units (tap to toggle) |
|---|---|
| Range | meter ↔ yard |
| Angle | MOA ↔ MIL (MRAD) |
| Target size | inch ↔ cm |

**Lock one, two run free.** Tap the circle beside a row to lock that value. Type either of the other two and the third is calculated for you (● marks the result).

- Lock **range** → change angle or size, the other follows
- Lock **size** → see the angle at any range, or the range for any angle
- Lock **angle** → find the size at any range, or vice versa

Switching a unit converts the value in that field — the physical quantity stays the same.

### Built for the field

- **5 independent targets** — plan a whole stage at once; each target has its own lock and units
- **Starts empty** — no default numbers to delete; tapping a filled box selects it so you can type over it
- **Large, high-contrast text** and finger-sized tap targets for phones
- **Light and dark mode** — follows your phone, or tap ◐ to switch
- ↺ clears a single target

## Formula

```
size = range × angle (radians)  — standard small-angle subtension
1 MOA = π / 10,800 rad (true MOA) → 1.047" @ 100 yd · 2.909 cm @ 100 m
1 MIL = 0.001 rad                 → 3.6"   @ 100 yd · 10 cm   @ 100 m
1 yd = 0.9144 m · 1 in = 2.54 cm · 1 MIL = 3.4377 MOA
```

## How to use

- **Online:** open the link above on any device
- **Offline:** download `index.html` and `pdl-logo.webp` into the same folder and open `index.html` in any modern browser

Single-file HTML, vanilla JavaScript, no build step.

## Credit & License

Created by **Kolawat Runelert** · Precision Dynamic Lab
IG [@precisiondynamiclab](https://www.instagram.com/precisiondynamiclab) · YouTube [@Runelert](https://www.youtube.com/@Runelert) · GitHub [@kolawat-sys](https://github.com/kolawat-sys)

- ✅ Free to copy, share, print, post for non-commercial / community use
- ❌ Attribution required — keep the author name and IG handle
- 🚫 Commercial use requires permission

© 2026 Kolawat Runelert · Released for the Thai PRS community 🇹🇭
