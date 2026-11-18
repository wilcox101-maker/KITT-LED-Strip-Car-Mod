# KITT LED Strip Car Mod

A Knight Rider "KITT"-style scanning LED strip mod for a car — the sweeping red
scanner bar, driven by a microcontroller with an addressable LED strip.

**Status: new — setup.** Hardware, controller and wiring are still to be chosen; this repo
starts with its rules and structure so work can begin cleanly.

## Scope (initial, to firm up)
- Addressable LED strip (e.g. WS2812B/SK6812 or APA102) running the classic KITT sweep,
  with brightness and pattern control.
- A microcontroller driver (Dale's usual ESP32/Arduino toolchain is the likely target).
- Clean, reversible install into the vehicle's 12 V electrical system — fused, no permanent
  changes without Dale's say-so.

## Layout (to grow)
| Path | What |
|---|---|
| `README.md` | This file |
| `AGENTS.md` / `CLAUDE.md` | Rules for AI collaborators and this project's place in the org |
| `firmware/` | Controller firmware (to be added) |
| `hardware/` | Wiring, power, strip selection, bill of materials (to be added) |
| `docs/` | Notes and decisions (to be added) |

## Place in the org
Part of Dale's project org under the **Claudius Maximus** overseer; a standalone project
(not under the Redux Manager). Shared support is available from the **Custom Hardware Design**
project. Roles to be defined.

## Licence
To be chosen by Dale.
