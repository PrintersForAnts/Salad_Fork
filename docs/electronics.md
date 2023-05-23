# Mains inlet


**Parts needed:**
* 1 AC inlet
* 2 M3x6 BHCS

**Printed parts:**
* 1 skirt_rear_ac_inlet


**Steps:**
1. Attach the skirt_rear_ac_inlet using the M3x6 BHCS to the right rear corner of the printer on extrusion G

![](images/skirt_ac_inlet.png)

2. Insert the AC inlet into the skirt, it should click into place securely

![](images/skirt_ac_inlet_inserted.png)

# Power rail
** THIS IS FOR 160 BUILD **

**Parts needed:**
* 1 DIN rail 
* 4 M3x10 BHCS
* 4 M3x6 BHCS
* 4 M3 heatsets 
  

**Printed parts:**
* 2 din_mount
* 2 uhp-350_din_rail_bracket

**Steps:**
1. Insert 2 heatsets into each uhp-350_din_rail_bracket

![](images/uhp-mount-heatsets.png)

2. Use the M3x6 BHCS to attach the din rail brackets to the power supply
3. Slide the din_mount parts onto the din rail
4. Use the M3x10 BHCS to attach the din_mount to the frame on the bottom H extrusions towards the rear of the printer

![](images/power_din_rail_mounted.png)

5. Clip the power supply on to the din rail, orient it so that the AC side of the power supply is close to the inlet to reduce wiring length

**Note:**
To keep the CAD simple, a dimensionally-accurate cube was substituted for the power supply in the images. 


# Control rail
** THIS IS FOR 160 BUILD **

**Parts needed:**
* 1 DIN rail 
* 4 M3x10 BHCS
* 14 M2x10 self tapping
* 4 M3x6 BHCS
  

**Printed parts:**
* 3 din_clip_for_pi_and_mcu
* 1 din_rpi_bracket
* 1 din_octopus_bracket or din_spider_bracket (use the correct one for your MCU)

**Steps:**
1. Attach the MCU brackets to the din_clip_for_pi_and_mcu using M2x10 self-tapping screws. This image shows a Spider MCU, but it is the same process for the Octopus.

![](images/mcu_brackets.png)

2. Use M3x6 BHCS to attach the MCU to the brackets
3. Use M2x10 self-tapping screws to assemble the din_rpi_bracket and the din_clip_for_pi_and_mcu

![](images/rpi_brackets.png)

4. Use M2x10 self-tapping screws to mount the RPi to the printed brackets

![](images/rpi_mounted_on_bracket.png)

5. Slide the din_mount parts onto the din rail
6. Use the M3x10 BHCS to attach the din_mount to the frame on the bottom H extrusions towards the front of the printer
7. Clip the RPi and MCU to the rail

![](images/electonics_bay.png)

**Note:**

You may need/want to reverse the power supply and mcu locations, depending on the length of your cables.
