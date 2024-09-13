# Sherpa *Crew* Mini v1.1 [Issue #6](https://github.com/VoronDesign/Voron-Afterburner/issues/6) Slayer (made by knight_rad.iant in Discord)

## Product Info

The Sherpa Crew Mini is a 3d printer extruder that uses two sets of Bondtech (or any other clone) 5mm gears.  It is designed to allow for smooth layer stacking (provided no other motion parts on your printer have any issues), slaying the pesky [Voron Issue #6](https://github.com/VoronDesign/Voron-Afterburner/issues/6) and [Prusa3d Issue #602](https://github.com/prusa3d/Prusa-Firmware/issues/602).  It is compact and it uses a single thumbscrew for even pressure on both the upper and power gears.
The extruder provides extreme performance at the cost of increased weight and cost.  If cost or weight are of a concern, one might try using the [Sherpa Zero](https://github.com/jrlomas/Sherpa-Zero), instead. It uses a single additional screw to remove the backlash from the front involute gears.

![Sherpa Crew Headshot Left](Images/left_side_v1.1.PNG)
![Sherpa Crew Headshot Right](Images/right_side_v1.1.PNG)

## Mechanics
The extruder uses an upper and lower 50T gears meshed with one another.  Notice that the backlash for these two gears is **not** adjustable.  If you are pushing a lot of current through the motor (i.e. more than 0.8A RMS, this might be a problem); otherwise, practically, the mechanism seems to work fine.  The motor backlash to the lower 50T is adjustable, and should work with 8T, and 10T gears.

![Sherpa Double Gears](Images/mechanism.png)

Notice also that the lower gearset guilder is meant to run with a bushing to replace the idler drive gear on the original bondtech set. It is [5mm ID x 8mm OD and 10mm in length](https://www.amazon.com/dp/B09CD8QSG3?psc=1&ref=ppx_yo2ov_dt_b_product_details).   The upper gearset uses the standard configuration.

![Lower Gearset](Images/lower_guilder.jpg)
![Lower Gearset Render](Images/bushing.PNG)

## Standing on the shoulder of giants: the many who made this extruder possible
The sherpa crew mini is a derivative work from [Churls Double Sherpa](https://github.com/Annex-Engineering/Annex-Engineering_User_Mods/tree/main/Extruders/Sherpa_Mini/Extruder_Mods/Churls-Double_Sherpa_Mini) and the work by the Voron and the 3d printer community at large on helping with creative ways to slay [Issue #6](https://github.com/VoronDesign/Voron-Afterburner/issues/6) (i.e. inconsistent extrusion).  As a derivate work from Annex Engineering, the product [license](https://github.com/Annex-Engineering/ANNEX-Engineering-License-Agreement) is the same as the original [Sherpa Mini](https://github.com/Annex-Engineering/Sherpa_Mini-Extruder/).

Thanks to: [Aneex Engineering](https://store.annex.engineering/) for the original design; to Meelis on discord for his tiredlessly, obsessive characterization and testing of different extruders, and the grandfather of double gear sets extruder designs (along with Churls who created the original Double Sherpa); and to the Voron community for all of the support.

Happy printing!

## Changelog
### v1.1
* Corrected alignment between several of the parts
* Styling changes to rear, front, and main housing
* Included alternative options for PTFE tube connections to the main housing, including:
  * ECAS04 
  * PC4-M6
* Only STP files are now included to stream publishing

### v1.0
* Initial Release
