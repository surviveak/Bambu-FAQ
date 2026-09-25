# Bambu Studio & Model Editing

[← FAQ home](../README.md)

## Q001 — Where do I change bed temperature?

Edit the **Filament preset**. Bed temperatures are material/plate settings rather than general Process speed settings.

## Q002–Q003 — How do multiple plates work?

Multiple virtual plates can be prepared in one project, but they are separate print jobs. The H2C cannot print two physical plates simultaneously, and a finished plate normally has to be cleared before the next job.

## Q023–Q024 — Where are print and wall speeds?

Open the **Process** preset and go to **Speed**. Outer wall, inner wall, infill, top surface, first layer and travel-related speeds are controlled there.

## Q025 — What are X, Y and Z?

X and Y locate the model across the build plate. Z is height above the plate.

## Q052 — How do I rotate one piece?

Select that object/part and use the Rotate tool rather than selecting the entire plate or multipart parent.

## Q053–Q055 — Can I edit text already on an STL?

If the lettering is baked into the mesh, it is no longer editable as text. You can add new text or modify/remove the geometry, but cannot simply edit the original characters as though they were a text field.

## Q056 — Can only certain parts get a brim?

Yes. Use per-object settings/modifiers where appropriate rather than forcing the same brim behavior on every object.

## Q057 — What should I choose in Send Print Job?

Automatic mapping is generally the starting point. Always verify plate, filament and hotend assignments before sending a complex multicolor/material job.

## Q058 — What are non-manifold edges?

They indicate invalid or ambiguous mesh topology, such as holes, overlapping surfaces or edges shared incorrectly. Repairing the mesh can prevent slicing errors.

## Q080–Q081 — How do I position one model on another?

For multipart work, keep pieces as parts of a common object when you need independent Z positioning. A tiny intentional overlap can help ensure the slicer produces continuous geometry.

## Q083 — Will the printer compensate if an object physically moves?

No. Once printing begins, the machine continues using the coordinates in the sliced job.

## Q088 — Can I queue several independent jobs?

You can prepare multiple plates, but normal printing still requires removing the finished part/resetting the plate between jobs. **Print by Object** can sequentially print multiple objects on one plate when toolhead-clearance rules permit it.

## Q094 — Can I stack copies vertically?

Only with deliberate separation/support/interface design. Simply touching identical-material models usually fuses them. A deliberately incompatible support-interface material or modeled breakaway connection can be used for specialized stacking.

## Q097 — How do I add surface texture?

Use **Fuzzy Skin** for built-in stochastic texture. For designed patterns, use modeled geometry, emboss/deboss features, SVGs, modifiers or CAD/mesh tools.

## Q100 — How do I make only the middle of a container taller?

Do not scale the whole model if the base and threaded top must remain exact. Cut/isolate the straight middle section, extend or insert geometry there, and move the unchanged threaded top upward.

## Q101–Q103 — How do I reassemble cut pieces and move them above the plate?

A key distinction is **objects versus parts**. Independent objects are normally dropped to the build plate. For vertical assembly, retain/convert the cut sections as **parts of the same multipart object**, then position the individual parts. Do not rely on Merge after positioning as a universal workflow; Bambu Studio version behavior and available commands can differ.
