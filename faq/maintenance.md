# Maintenance & Troubleshooting

[← FAQ home](../README.md)

## Q014 — How often should I maintain the H2C?

Use the printer's current maintenance guidance as the primary schedule. Keep rails/mechanisms clean as specified, inspect PTFE paths and cutters, keep build surfaces clean, and address abnormal resistance/noise before it becomes a feed failure.

## Q015 — How do I clean nozzles/hotends?

Remove external residue only when it is safe to do so and follow Bambu's hotend-cleaning procedure. Avoid damaging heaters/sensors or using lubricant on filament-contact surfaces.

## Q016 — Do all Vortek hotends need purging?

No. Dedicated hotends reduce color-clearing purge. Purge is needed when a hotend itself changes material/color or contamination must be removed.

## Q071 — Print hours and maintenance

Use the printer's maintenance/device information screens and current firmware documentation. Menu placement can change over time.

## Q089 — What are the spring-loaded filament mechanisms doing?

They participate in managing filament path/tension/slack as upstream feeding and toolhead demand change. Small movement can be normal. Repeated snapping/clicking should prompt a check for PTFE drag, tight bends, selector resistance or spool resistance.

## Clicking during feeding

Correlate the click with the moving mechanism, inspect the entire filament path, simplify the route temporarily, and check spool freedom. Do **not** lubricate an unidentified filament mechanism as a first troubleshooting step.

## Q105 — How do I perform a cold pull?

Use a suitable rigid cleaning filament such as PLA. Heat enough to load/extrude cleanly, then cool until the polymer is firm enough to capture debris while still releasable. Pull in a controlled manner rather than yanking against the toolhead. Repeat if contamination remains.

The exact target temperature depends on polymer and hotend geometry. For PLA, roughly **80–100°C** is a common cold-pull region, but if it will not release, warm it slightly rather than applying excessive force.
