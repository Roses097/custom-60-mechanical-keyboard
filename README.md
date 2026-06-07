# MECA-00

> A custom mechanical keyboard built from scratch as part of [Hack Club's Keeb](https://keeb.hackclub.com/) grant program.  
> Inspired by the Eva Unit-00, From Neon Evangelion Genesis.

---

## What is this?

Meca-00 is my first custom mechanical keyboard, designed and assembled by hand. Every part was chosen, every solder joint made, and every line of firmware written by me. No kits. No shortcuts.

This repo documents the full build process — from the first idea to the final keystroke.

---

## Build Overview

| Part | Details |
|------|---------|
| **Microcontroller** | Orpheus Pico |
| **Switches** | MX-style (TBD) |
| **Keycaps** | White blank DSA |
| **Diodes** | Through-hole 1N4148 |
| **Firmware** | QMK (planned) |
| **Form factor** | 60% (planned) |

> ⚠️ This table will be updated as I decide which parts to use.

---

## Why this name?

Unit-00 is the Evangelion prototype 00 in Neon Genesis Evangelion. Unstable, experimental, and the first of the series.

This keyboard is my Unit-00. It's my first try, i already tried to make a keybaord myself but always got stuck on the wiring part... It might be hard, but i'll make it.

---

## Build Log

- [ ] Plan layout & finalize BOM
- [ ] Design PCB in KiCad
- [ ] Design case
- [ ] Order parts via Keeb grant
- [ ] Solder components
- [ ] Flash firmware
- [ ] First keystroke 🎉

- PCB design (KiCad)
- Mechanical keyboard firmware (QMK)
- CAD for case design

---

## Files

```
meca-00/
├── pcb/          # KiCad project files
├── case/         # Case & plate design files
├── firmware/     # QMK config
└── README.md     # You're here
```

---
### 2026-06-07 — Planning & BOM
Finalized full keyboard spec: compact 60% QWERTY, detachable right-side module (6 macro 
keys + 0.96" OLED), EVQWGD001 clone side scroll encoder, SK6812 MINI-E RGB LEDs under 
every switch, Silent White Outemu switches, magnetic pogo pin module connector, frosted 
acrylic sandwich case via JLCPCB. Created BOM in Excel with all prices and sources. 
Designed layouts in Keyboard Layout Editor (main 60% + module). Committed all planning 
files to repo.
---
*Built by Ray as part of [Hack Club Keeb](https://keeb.hackclub.com/).*
