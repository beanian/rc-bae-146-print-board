# BAe 146 Print Board

Interactive build tracker for a 3D-printed **British Aerospace 146** (70mm EDF twin,
1:15 scale, ~1800mm wingspan) in **LW-PLA**, finished in the **airberlin red/white livery**.

**Live page:** https://beanian.github.io/rc-bae-146-print-board/

## What it does

- **Kanban board** — drag parts (or use the ◀ ▶ buttons) across *To Print → Printing → Printed → Assembled*. Progress is saved in your browser.
- **Print modes** — vase / no-vase / PLA / top-layers / walls, per the original slicer notes.
- **Livery colour layer** — each part carries a suggested filament colour for the airberlin scheme:
  - 🔴 **Red LW-PLA** — the whole vertical fin (Rudder section) and the rear fuselage / tailcone wrap (`Fuse 9–11` + corners).
  - 🟠 **Two-tone** — `Fuse 8` sits on the diagonal white/red sweep (colour-change at Z, mask, or decal). Optional red accent on the engine exhausts (`EDF 2 L/R`).
  - ⚪ **White** — everything else (nose, mid fuselage, wings, flaps/ailerons, horizontal tailplane, gondolas).
  - Click any card's **colour swatch** to cycle white → red → two-tone and tune it to your own plan.

The red/white split is a best-effort read of the reference photo — the exact fuselage
segment where the sweep falls should be confirmed against the build manual.

## Notes

This repo is **public** and contains only the tracker (a single `index.html`). The
proprietary STL part files and build manual live in a separate **private** repo and are
not published here.
