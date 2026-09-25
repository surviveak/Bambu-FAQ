# AMS, FTS & Filament Routing

[← FAQ home](../README.md)

## Q009 — How should TPU be routed?

Soft TPU benefits from the lowest-resistance path possible. Avoid unnecessary selectors, tight PTFE bends and long high-drag routes.

## Q010 — What does TPU Feed Assist do?

TPU Feed Assist is a powered helper for flexible filament. It reduces the force needed to pull soft TPU through a long feed path and helps prevent stretching, buckling and feed errors. It is not an AMS or filament selector.

## Q011 — Can I use more than one Filament Track Switch?

The intended H2C topology centers on the printer's FTS routing and appropriate adapters/mergers rather than simply chaining arbitrary FTS units. Verify the current Bambu-supported topology before expanding the system.

## Q012–Q013 — Can AMS 2 Pro, AMS HT and TPU Feed Assist coexist?

They can be part of the same overall installation, but rigid filament and soft TPU may use different routes. Keep normal AMS/FTS routing for compatible rigid materials and use the low-resistance TPU path where required.

## Q017 — Does AMS 2 Pro weigh the spool?

Do not treat the remaining-filament display as a precision scale. RFID/usage estimation can help with supported Bambu spools, but it is not the same as directly weighing the remaining filament.

## Q018 — How do multiple AMS units connect?

Multiple AMS-family devices are combined through the supported hub/merger/FTS topology for the H2C. Exact supported layouts can change with hardware and firmware, so use the current Bambu connection diagram for a specific combination.

## Q064–Q067 — Can TPU Feed Assist stay installed?

Yes, a TPU-assist path can remain installed while rigid filament uses the normal path. A merger can make permanent plumbing convenient, provided unused filament is fully retracted from the junction and the arrangement does not add excessive drag.

## Q070 — How can AMS switching be faster?

Keep PTFE paths short and smooth, reduce unnecessary material changes in the model, and use dedicated Vortek hotends for colors/materials that alternate most often. Avoid unsupported motor-speed or loading-G-code hacks.

## Q077 — How does AMS auto-refill work?

Load compatible backup spools, configure them as matching material/profile/color as required by the current software, and enable the filament-backup/auto-refill option. Eligibility depends on how the slots are identified and configured.

## Q078 — Can Filament Manager track exact remaining grams?

Not reliably as a general inventory scale, particularly for third-party spools. For a partial spool, weighing it and subtracting the empty-spool tare remains the most direct measurement.
