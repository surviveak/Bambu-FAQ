# Speed & Optimization

[← FAQ home](../README.md)

## Q026 — Why doesn't increasing mm/s always make the printer faster?

Actual extrusion speed can be limited by maximum volumetric flow, acceleration, cooling, overhang rules, minimum layer time and geometry. The commanded wall speed is only one constraint.

## Q047 — How do I see how much filament each color uses?

Slice the plate and review the filament usage breakdown in the sliced results/preview. Multicolor jobs can include model material plus purge/prime/support consumption.

## Q050 — Dedicated hotends vs AMS switching

When two colors alternate frequently, assigning them to separate hotends can substantially reduce unload/load/purge overhead compared with repeatedly changing both through one nozzle.

## Q051 — Reducing prime-tower overhead

Dedicated hotends can reduce color-clearing purge, but reprime/stabilization may still be necessary. Optimize the tower only after verifying that transitions remain reliable.

## Q070 — Faster material changes

Prioritize dedicated hotends for frequently alternating colors, minimize PTFE drag, reduce unnecessary color transitions through model orientation/design, and keep filament paths straightforward.

## Q072/Q082/Q095 — Linear speed vs volumetric speed

Maximum volumetric speed is:

**flow (mm³/s) = line width × layer height × linear speed**

Example: 0.42 mm × 0.20 mm × 300 mm/s = **25.2 mm³/s**. A filament capped at 20 mm³/s cannot sustain that extrusion geometry at 300 mm/s; the practical linear cap would be about **238 mm/s**.

## Q096 — When is high-flow useful?

High-flow hotends are most useful when melt capacity is the bottleneck: larger nozzles, thick layers, wide lines and fast rigid-material printing. They provide little benefit when cooling, motion or the filament itself is the limiting factor.

## Matte appearance without matte filament

Gloss can change with temperature and actual surface speed. If outer walls are already very fast, increasing speed further just for appearance is not a good strategy. Check Preview for speed/flow changes, overhang slowdowns and cooling behavior; mild Fuzzy Skin can produce a more consistently matte-looking surface.
