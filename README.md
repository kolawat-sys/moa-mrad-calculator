# MOA / MRAD Calculator — Range × Angle × Target Size

**A simple online calculator for MOA and MRAD (MIL) subtension.** Spun off from [COF Calculator](https://github.com/kolawat-sys/COF-calculator-22lr).

🔫 **[Open the live calculator →](https://kolawat-sys.github.io/moa-mrad-calculator/)**

---

## What it does

Enter any 2 values and the 3rd is calculated automatically:

| Field | Units (toggle) |
|---|---|
| **Range** | meter ↔ yard |
| **Angular size** | MOA ↔ MRAD (MIL) |
| **Target size** | inch ↔ cm |

Switching a unit converts the value in that field — the physical quantity stays the same.

Also shows:
- All values in every unit side by side
- What 1 MOA, ¼ MOA, 1 MIL and 0.1 MIL cover at the current range (inch + cm)

## Formula

- size = range × angle (radians) — standard small-angle subtension
- 1 MOA = π / 10,800 rad (true MOA) → 1.047" @ 100 yd · 2.909 cm @ 100 m
- 1 MRAD = 0.001 rad → 3.6" @ 100 yd · 10 cm @ 100 m

## How to use

- **Online:** open the link above on any device
- **Offline:** download `index.html` and open it in any modern browser

Single-file HTML, vanilla JavaScript, no build step.

---

## Credit & License

**Created by [Kolawat Runelert](https://www.instagram.com/precisiondynamiclab) · IG [@precisiondynamiclab](https://www.instagram.com/precisiondynamiclab) · GitHub [@kolawat-sys](https://github.com/kolawat-sys)**

- ✅ Free to copy, share, print, post for non-commercial / community use
- ❌ Attribution required — keep the author name and IG handle
- 🚫 Commercial use requires permission

© 2026 Kolawat Runelert · Released for the Thai PRS community 🇹🇭
