# ROOMS — Visual Design Spec v1
**Date locked:** 2026-04-23
**Status:** FINAL — do not change without explicit approval
**Codename:** ROOMS

---

## Overview

ROOMS is the visual layer for the TOWPATH fleet dashboard. Each node gets a room. Each room is alive and responds to live TOWPATH data. The design was finalized in a session with Everly as co-art-director.

---

## Room Map

| Node | Room Theme | Palette |
|---|---|---|
| M4 | Control room | Pastel pink / deep pink |
| M1 | Workshop | Dark purple / light purple |
| JEEP | Car cockpit | Dark green / grey / black |

---

## Room Specs

### M4 — Control Room

**Palette:**
- Background: `#F9A8D4`
- Wall: `#FCE7F3` (pastel pink)
- Floor: `#EC4899` (deep pink)
- Floor edge: `#DB2777`
- Surfaces: `#BE185D`, `#9D174D`
- Screen dark: `#1a0a12`

**Props:**
- 3 wall-mounted monitors, equal size, on shared rail — NO stands
- Monitor content: bar chart (left), progress bars (center), progress bars (right)
- Console panel with colored buttons and readout bars
- Big desk with keyboard, mouse, notepad
- Boba tea (taro purple, pearl, striped pink straw, dome lid)
- Empty chair

**Cats:** Black cat and/or white cat appear randomly on desk or floor. Never in JEEP.

---

### M1 — Workshop

**Palette:**
- Background: `#4C1D95`
- Wall: `#EDE9FE` (light purple)
- Floor: `#4C1D95` (dark purple)
- Floor edge: `#3B0764`
- Surfaces: `#6D28D9`, `#2e1065`
- Screen dark: `#1E1033`

**Props:**
- Orange pipes left and right wall — orange only, no green circles
- 3 wall-mounted monitors, equal size, on shared rail — NO stands
- Monitor content: waveform (left), progress bars (center), progress bars (right)
- NO multicolored bottom bar on any monitor
- Machine button panel with equal-size colored circles
- Wood workbench with wood grain — `#92400E` top, `#78350F` legs
- Wrench, keyboard, mouse
- Coffee cup with steam
- Two red Red Bull cans on floor
- Empty stool

**Cats:** Black cat and/or white cat appear randomly on workbench or floor. Never in JEEP.

---

### JEEP — Cockpit

**Palette:**
- Background: `#1C2B1C`
- Pillars: `#1A271A`
- Header: `#2D3B2D`
- Windshield frame: `#4B6B4B`
- Dashboard: `#2D3B2D`, `#1A271A`
- Accent: `#6EE7B7`

**Props:**
- Tinted windshield — dark green overlay `#0A1A0A` at 40% opacity
- Weather scene behind tint — 5 states: evening (default), sunny, deep night, rain, snow
- Each weather state has textured multi-layer trees (overlapping circles)
- Left gauge (km/h, teal needle)
- Right gauge (rpm, orange needle)
- Center nav screen with map, route line, destination dot
- Vents left and right
- Chunky 3-spoke steering wheel with `#6EE7B7` horn center
- Empty seat
- NO cup holders
- NO drinks
- Signal bars top right

**Weather states:**
- `evening` — dusk blue sky, deep green trees, dark road
- `sunny` — bright blue sky, sun with rays, fluffy clouds, bright grass, vibrant multi-layer green trees
- `deep night` — near-black sky, stars, crescent moon, headlight glow, dark trees
- `rain` — grey clouds, blue rain streaks, wet road, dark moody trees
- `snow` — light grey sky, snowflakes, snow drifts, white-capped trees

**Cats:** NONE. No cats in the JEEP. Ever.

---

## Character Spec — LOCKED

All three characters share the same base construction. Do not change without explicit approval.

### Base construction

**Head:**
- Shape: oblong ellipse, taller than wide — `rx=44 ry=54`
- Fill: `#FFDAB8`
- Stroke: `#111` (black), `stroke-width="5"`
- Sits directly on vest body — NO neck element

**Hat — Carhartt watch cap:**
- Crown: tapered path (wider base, narrower top like a real beanie)
- Crown fill: `#7A4A1A`
- Crown stroke: `#111`
- Cuff: wide rounded rect at base of crown, pulled down over forehead
- Cuff fill: `#5C3210`
- Cuff stroke: `#111`
- Patch: centered on cuff — white border rect `#F5F0E8`, amber fill `#C8860A`
- NO text on patch

**Vest — Carhartt:**
- Shape: oblong ellipse, skinnier than old version — `rx=36 ry=42`
- Fill: `#7A4A1A`
- Two front panels: lighter brown `#8B5520`
- Center seam line
- Lapel curves at top
- NO chest pocket

**Arms:**
- Thick stroke path: `stroke-width="13"` to `stroke-width="14"`
- Color: `#111`
- Ends in filled circle hands: `#FFDAB8`

**Mouth:**
- O shape — open oval, no teeth
- Outer ellipse: `#111`
- Inner ellipse: `#c0605a`

**Cheeks:** Not currently shown — flagged to add back later.

---

### M4 — Operator (eyes)

**Eyes — googly:**
- White sclera ellipse: `rx=16 ry=17`, stroke `#111`
- Iris: `rx=11 ry=11`, fill `#7C3AED` (purple)
- Pupil: `rx=6 ry=6`, fill `#111`
- Large catchlight: `r=4`, fill white
- Small catchlight: `r=2`, fill white

**Brows:** Worried — angled down toward center, stroke `#111`

**Seat color:** `#7C3AED`

---

### M1 — Worker (eyes)

**Eyes:** Same construction as M4, iris `#7C3AED` (purple — same as M4)

**Brows:** Same worried brows as M4

**Extras:** Sweat drop removed. No green circles on hat.

**Seat color:** `#0F766E`

---

### JEEP — Driver (sunglasses)

**Sunglasses:**
- Two large round lens ellipses: `rx=18 ry=16`, fill `#1A271A`, stroke `#111 stroke-width="3.5"`
- Bridge: line connecting lenses, `stroke-width="4"`
- Arms: lines from outer lens edges, `stroke-width="3.5"`
- Glare: curved white arc top-left of each lens + small white dot — `opacity="0.85"`

**Brows:** NONE — no eyebrows on the driver

**Seat color:** `#2D3B2D`

**One hand on wheel:** Right arm curves toward steering wheel

---

## Cat Spec

### Black cat
- Body: loaf ellipse, fill `#111`, stroke `#222`
- Head: circle, fill `#111`
- Ears: triangle polygons with pink inner `#F9A8D4`
- Eyes: green `#4ADE80` with black pupil and white catchlight
- Nose: `#F9A8D4` ellipse
- Whiskers: light grey lines
- Tail: curved stroke path, `stroke-width="5-6"`, fill `#111`

### White cat
- Same construction
- Fill: `#F0F0F0`, stroke `#DDD`
- Eyes: blue `#60A5FA`
- Inner ears: `#F9A8D4`
- Whiskers: `#CCC`

### Cat placement rules
- M4: desk surface or floor
- M1: workbench surface or floor
- JEEP: **NEVER**
- Cats appear randomly — driven by idle state animation
- Both cats can appear simultaneously in the same room
- Cat spawn is a GSAP idle animation trigger

---

## Monitor Standard

All monitors across M4 and M1 follow this spec:

| Property | Value |
|---|---|
| Size | `width=108 height=82` |
| Corner radius | `rx=10` |
| Wall rail | shared horizontal bar, same y position |
| NO stands | wall mounted only |
| Screen inset | `8px` padding, `rx=6` |
| Screen bg | dark fill matching room palette |

### Screen content by slot:
| Position | Content | Animation target |
|---|---|---|
| Left | Waveform (polyline) | Line drift, scroll |
| Center | Progress bars (3 rows) | Bar width change |
| Right | Progress bars (3 rows) | Bar width change |

---

## GSAP State → Room Behavior

| State | M4 | M1 | JEEP |
|---|---|---|---|
| idle | Dim lights, boba straw sway, cat may appear | Dim lights, coffee steam, cat may appear | Evening weather, needle rests |
| active | Monitors brighten, buttons pulse | Waveform animates, progress bars fill | Nav route animates |
| receiving | Console lights flash, character looks up | Button row flashes, character looks up | Signal bars pulse |
| working | Bar charts update, character types | Progress bars cycle, waveform active | Speedo needle rises |
| down | Lights off, monitors dark, cobwebs | Lights off, pipes dim, cobwebs | Windshield darkens, gauges drop |

---

## SVG Contract (unchanged from spec v1)

```
room-{node}       → root SVG id
agent-{name}      → character group
light-{node}      → lighting layer
activity-{node}   → animation trigger zone
status-{node}     → status dot
layer-{n}         → top-level groups
{type}-{node}-{n} → named elements
```

viewBox: `0 0 360 320` (rooms) / `0 0 200 280` (characters)
No inline transforms on root.
No clip-path, filter, mask, linearGradient.
All strokes: `#111` (black) — not purple, not dark-color-matched.

---

## What is NOT in scope for v1

- Everly's final character art (Phase 2)
- inkscape-mcp production pass (Phase 3)
- Supabase realtime (polling only for now)
- Room navigation / click-to-zoom (Phase 4+)
- Agent nicknames (Everly names them in design session)

---

*Locked 2026-04-23 — design session with Everly*
*Do not modify characters, palettes, or cat rules without Everly's sign-off*
