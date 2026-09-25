# TPU & Flexible Filament

[← FAQ home](../README.md)

## Q064–Q069 — TPU routing and Feed Assist

Soft TPU benefits from a short, low-resistance path. TPU Feed Assist reduces upstream drag; it does not turn every AMS/FTS route into a suitable soft-TPU path. Use the dedicated/bypass TPU routing required by the current H2C hardware.

## Q076 — TPU on Textured PEI

Textured PEI is a useful TPU surface. A starting bed range around **35–45°C** can work depending on formulation. TPU can bond very strongly, so a thin glue layer may be useful as a release layer. Let the part cool before peeling it off.

## Q090 — Overture High-Speed TPU/TPU 2.0 volumetric speed

Overture's public linear-speed guidance does not directly provide a universal maximum volumetric speed. **6 mm³/s** was used as a conservative starting MVS for calibration, not as an official manufacturer maximum. With roughly 0.42 × 0.20 mm extrusion, 60–90 mm/s corresponds to about **5.0–7.6 mm³/s**.

## Q091 — Why might TPU be unavailable on a particular nozzle/path?

There is no universal rule that the left nozzle cannot melt TPU. Compatibility can depend on the selected TPU type, source/path, hotend/nozzle configuration and current Bambu Studio rules. Check the actual Send Print Job mapping/error rather than assuming a thermal limitation.

## TPU stringing / spider webs

If a TPU print is mechanically good but covered in fine strings between parts, investigate **moisture first**, then travel/retraction behavior and temperature. TPU can be wet enough to string heavily while still producing an otherwise recognizable print.

When starting from Generic TPU at **210°C**, dry the spool and repeat the same test before lowering temperature further. Change one variable at a time. High-speed TPU may ultimately need a higher temperature to sustain its intended flow rate.

## Drying

Drying requirements vary by TPU formulation. Follow the spool manufacturer's current temperature/time guidance and, for long jobs, print from a dry environment when practical.
