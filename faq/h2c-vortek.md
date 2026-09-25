# H2C & Vortek

[← FAQ home](../README.md)

## Q004–Q007 — How does H2C multicolor printing work?

The H2C can use separate hotends for different colors/materials through Vortek. This can avoid repeatedly flushing one nozzle when frequently alternating materials. It does **not** perform true molten color mixing inside a nozzle.

## Q016 — Should I purge every Vortek hotend?

Not routinely. A dedicated hotend does not need color-clearing purge every time another Vortek hotend is selected. Repriming/stabilization can still be required.

## Q050 — Is two-color printing faster with dedicated hotends?

Usually when colors alternate frequently. Keeping a color/material assigned to its own hotend avoids much of the unload/load/color-clearing work of conventional single-nozzle AMS switching.

## Q051 — Is a prime tower still useful with Vortek?

It can be. Separate hotends eliminate much of the need to purge one color out of another, but the newly selected hotend may still need to reprime and stabilize before printing.

## Q073 — What is the Vision Encoder?

It is a precision motion-calibration system that uses optical measurement and a patterned calibration surface to measure commanded versus actual XY motion. It is not the normal monitoring camera and does not replace extrusion calibration or bed leveling.

## Q083 — Does the H2C track a model if the sheet or print moves?

No. The printer follows the sliced coordinates. If the part slips or the build sheet physically shifts during printing, it does not continuously re-register the model's new XY position.

## Q084–Q085 — How long does a Vortek material change take?

The total time depends on routing, heating, reprime behavior and whether a nozzle must be purged. Dedicated-hotend changes can be much faster than a full shared-nozzle material change. Treat fixed time estimates as approximate rather than guaranteed.

## Q106 — How many Vortek hotends can the right side use?

The Vortek system supports **six interchangeable hotends total**. In normal operation that can mean five parked in the rack and one mounted on the right toolhead. The separate left hotend is additional.

## Q107 — Can colors be assigned to hotends?

Bambu Studio/the printer maps job filaments to available hotends. The H2C can use its hotend/material history and automatic assignment, with job mapping depending on the current Studio/firmware workflow.

## Q108 — What if the job has more than six right-side colors?

More than six filaments can still be used through the material system, but only six Vortek hotends are available. Additional colors therefore have to share hotends at some point, which reintroduces unload/load and color-clearing purge for those shared-nozzle transitions. The left hotend can also participate in suitable jobs.
