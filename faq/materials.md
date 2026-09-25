# Filaments & Materials

[← FAQ home](../README.md)

## Q019–Q021 — How should third-party filament be configured?

Start from the closest compatible generic/material preset, create a user filament preset, then apply the manufacturer's documented temperatures, flow ratio, maximum volumetric speed and cooling values. Calibration refines the manufacturer baseline.

## Q044 — PLA-CF vs PLA-Aero

**PLA-CF** is carbon-fiber-filled PLA: stiffer, matte-looking and abrasive. **PLA-Aero** is a lightweight/foaming PLA intended for low-density parts such as RC aircraft. They solve very different problems.

## Q048/Q059/Q060 — Overture Silk PLA baseline

From Overture's H2D preset used as a reference: nozzle **230°C**, Textured PEI **55°C**, flow ratio **0.95**, maximum volumetric speed **20 mm³/s**, density **1.34 g/cm³**, retraction **1.5 mm**, strong part cooling after the first layer, and pressure advance value 0.02 stored but disabled in the preset.

## Q061 — Do layer heights belong in the filament preset?

No. Material behavior belongs in the **Filament** preset; nozzle/layer-height/quality/speed choices belong primarily in the **Process** preset.

## Q068 — PETG vs PLA

PLA is generally easier to print, rigid and good for detail/prototypes. PETG is generally tougher, less brittle and more resistant to heat, moisture and outdoor use, but can string more.

## Q072 — Why can PLA+ print slower than PLA?

The product name does not guarantee higher flow. In Overture's referenced presets, standard PLA is **20 mm³/s**, PLA+ **16 mm³/s**, Super PLA+ **12 mm³/s**, and Silk PLA **20 mm³/s**. Maximum volumetric speed can cap actual print speed.

## Q086–Q087 — Can nominal 1.75 mm filament measure 1.80 mm?

Some 1.75 mm products specify tolerances that can reach 1.80 mm. Measure at multiple locations and orientations. Consistently oversized filament increases feed resistance and changes extrusion volume; do not assume a true 1.8 mm filament standard is compatible.

## Q092 — Is “food-safe PLA” automatically food-safe after FDM printing?

No. A marketing claim about resin/filament does not automatically establish that the finished printed article is appropriate for every food-contact condition. Consider resin/additive authorization, pigments, migration conditions, nozzle contamination, surface/layer-line cleanability and intended temperature/time of contact.

## Q093 — SUNLU PETG maximum volumetric speed

A conservative starting point previously discussed was around **12 mm³/s**, followed by calibration. This is a tuning starting point, not a manufacturer-certified universal maximum.

## Q095 — Overture PLA maximum volumetric speed

The referenced Overture standard PLA preset specifies **20 mm³/s**. Actual reliable flow still depends on temperature, nozzle/hotend and the individual spool.

## Q096 — What does a high-flow nozzle do?

It increases melt capacity, allowing higher volumetric extrusion when the filament and cooling system can keep up. It does not automatically improve every print and cannot overcome a filament formulation's own flow limit.

## Q098 — What humidity should filament storage target?

For a mixed collection, **≤20% RH** is a useful storage target; around **10–15% RH** is excellent for moisture-sensitive materials. Very hygroscopic materials such as nylon/PVA benefit most. Low-RH storage maintains dry filament; heat is normally required to actively remove significant absorbed moisture.

## Q099 — PA12-CF20 vs PA6-CF20

Both are carbon-fiber-reinforced nylons. PA6-CF20 commonly emphasizes strength/stiffness/thermal performance but absorbs more moisture. PA12-CF20 generally absorbs less moisture and offers better dimensional stability and easier environmental handling. Compare the actual manufacturer's TDS before choosing for a critical part.
