# Profiles & Calibration

[← FAQ home](../README.md)

## Q022 — How do I create a custom filament preset?

Choose the closest compatible generic/material preset, edit it, then **Save As** a user preset. Apply manufacturer values first, then calibrate.

## Q029 — What plate is assumed in these examples?

Unless otherwise stated, the baseline in this FAQ is the **Textured PEI Plate**.

## Q034–Q035 — When should I calibrate?

Calibrate when changing important variables such as filament formulation/brand, nozzle/hotend type or diameter, or when print behavior indicates the stored calibration is no longer appropriate. You do not need to rerun every calibration before every print.

## Q036 — Basic calibration workflow

Load/select the intended filament preset, dry the filament when required, run the appropriate flow/pressure-dynamics calibration, review/save the result to the correct user preset, and test with representative geometry.

## Q037 — Where are profiles stored?

Bambu Studio user presets can be local and/or synchronized through the account/cloud depending on sign-in and sync configuration. Do not assume the printer itself is the master storage location for all custom Studio presets.

## Q038 — Which Process preset should I select for calibration?

The filament/nozzle/material combination is the key variable for filament calibration. A Process preset controls print geometry/speed choices but is not a substitute for selecting the correct filament and nozzle.

## Q039 — Auto Flow Dynamics

Use automatic calibration when the current printer/material/profile combination supports it. If the UI reports the filament as incompatible, diagnose compatibility rather than forcing the calibration.

## Q040/Q043 — Custom filament shows Unsupported/Incompatible

Bambu Studio versions can change custom-preset compatibility behavior. If a previously working custom filament suddenly becomes Unsupported or Incompatible, record the exact Studio version first and check current release notes/issues before repeatedly rebuilding the JSON.

## Q041–Q042 — Overture profiles

Overture publishes downloadable Bambu presets. Manufacturer presets are a useful source of baseline material properties, but printer/nozzle compatibility metadata may need adaptation for H2C and current Bambu Studio.

## Q045 — Manual Flow Rate calibration

After the first calibration pass, clear the plate before starting the next physical calibration print unless the workflow explicitly instructs otherwise.

## Q060 — Overture Silk reference values

Referenced Overture preset: 230°C nozzle, 55°C Textured PEI, 0.95 flow ratio, 20 mm³/s MVS, 1.34 density, 1.5 mm retraction; pressure-advance value 0.02 present but disabled.

## Q061 — Quality vs speed profiles

Keep material properties in the Filament preset and create Process presets for quality/speed/layer-height goals. Typical layer-height ranges depend on nozzle diameter and model requirements rather than filament branding alone.

## Q071 — Where can I see total print hours?

The printer's Device/maintenance information screens are the first place to look, but exact menu names can move between firmware versions. Use the current maintenance UI and firmware documentation if the counter is not where an older guide shows it.
