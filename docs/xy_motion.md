# Attach the lower drive mounts and rear extrusion

**Parts needed:**
* 8 M3x10 BHCS
* 1 Extrusion B  
* 16 M3 nuts
  
**Printed parts:**
* 1 A_Drive_Frame_Lower
* 1 B_Drive_Frame_Lower

**Steps:**
1. Attach the B_Drive_Frame_Lower to the left rear corner of the frame using 2 M3x10 BHCS
2. Attach the A_Drive_Frame_Lower to the right rear corner of the frame using 2 M3x10 BHCS

![](images/lower_motor_mounts_attached.png)

3. Preload 6 M3 nuts onto the top and 6 M3 nuts onto the bottom of extrusion B.
4. Preload 2 M3 nuts into the front of extrusion B
5. Preload 1 M3 nut into the left and 1 M3 nut into the right side of extrusion C (the one with the rear Z rail attached)
6. Center the extrusion B on the mounts and attach it with 2 M3x10 BHCS on each mount. The extrusion B will not sit flush with the extrusion C on the frame, this is intentional
7. Make sure the extrusion B is parallel with the corner extrusions. You can use a straightedge across the back of the printer to align it
8. Now you can gently tighten the screws on the rear Z carriage to hold extrusion B in it's proper orientation

![](images/extrusion_b_added.png)

# Prepare the B drive stepper

**Parts needed:**
* 1 NEMA14 stepper motor
* 1 GT2 16T pulley

**Steps:**
1. Attach a GT2 16T to the stepper drive shaft. Align it as shown, with approx 1.2mm clearance from the stepper. This will be adjusted later when the belts are added
   
![](images/B_drive_pulley_detail.png)




# Assemble the B motor mount

**Parts needed:**
* 6 F623 bearings
* 6 M3 washers
* 4 M3x10 BHCS
* 1 M3x6 BHCS
* 2 M3x25 BHCS
* 3 M3x25 SHCS
* 1 B motor assembly from previous step


**Printed parts:**
* 1 B_Drive_Frame_Upper

**Steps:**

1. Attach the motor assembly to the B_drive_Frame_lower using 1 M3x6 BHCS in the position shown. Orient the stepper so that the wires are on the left side 

![](images/b_drive_m3_x8.png)

2. Using 3 M3x25 SHCS, attach the B_Drive_Frame_Upper 

![](images/b_drive_top_attached.png)

3. Add 4 M3x10 BHCS screws to attach the upper drive frame to the extrusions 

![](images/b_drive_upper_mounted_extrusion.png)

4. Use a M3x25 BHCS to mount a bearing stack in place. A bearing stack is a M3 washer, 2 F623 bearings, and another M3 washer 

![Bearing stack side view](images/bearing_stack_side_view.png) 
![](images/b_drive_first_bearing_stack.png)

5. Use another M3x25 BHCS to mount two more bearing stacks 

![](images/b_motor_second_bearing_stack.png)

![](images/b_motor_rear_view.png)



# Prepare the A drive stepper

**Parts needed:**
* 1 NEMA14 stepper motor
* 1 GT2 16T pulley

**Steps:**
1. Attach a GT2 16T to the stepper drive shaft. Align it as shown, with approx 4.8mm clearance from the stepper. This will be adjusted later when the belts are added
   
![](images/A_drive_pulley_detail.png)


# Add the Y endstop switch 

**Parts needed:**
* 1 D2F switch
* 2 M2x10 self tapping screws
* 24 AWG wire (2 pieces of 60mm length)

**Printed parts:**
* 1 A_Drive_Frame_Upper

**Steps:**
1. Solder wire to the two outside contacts of the switch, these are normally labeled "NC" for "Normally closed". Using the NC pins is a safety measure to prevent printer damage in the event of a broken wire. 
2. Attach the switch to the upper motor mount using M2x10 self tapping screws.  

![](images/a_drive_upper_d2f_added.png)


# Assemble the A motor mount

**Parts needed:**
* 6 F623 bearings
* 6 M3 washers
* 4 M3x10 BHCS
* 1 M3x6 BHCS
* 2 M3x25 BHCS
* 3 M3x25 SHCS
* 1 A motor assembly from previous step


**Printed parts:**
* 1 A_Drive_Frame_Upper

**Steps:**

1. Attach the motor assembly to the A_drive_Frame_lower using 1 M3x6 BHCS in the position shown. Orient the stepper so that the wires are on the right side 

![](images/a_drive_stepper_attached.png)

2. Using 3 M3x25 SHCS, attach the A_Drive_Frame_Upper 

![](images/A_drive_top_attached.png)

3. Add 4 M3x10 BHCS screws to attach the upper drive frame to the extrusions 

![](images/a_drive_upper_mounted_extrusion.png)

4. Use a M3x25 BHCS to mount a bearing stack in place. A bearing stack is a M3 washer, 2 F623 bearings, and another M3 washer 

![Bearing stack side view](images/bearing_stack_side_view.png) 
![](images/a_drive_first_bearing_stack.png)

5. Use another M3x25 BHCS to mount two more bearing stacks 

![](images/a_motor_second_stack.png)

![](images/a_motor_rear_view.png)



# Prepare the idler tensioners

**Parts needed:**
* 4 M3 heatsets

**Printed parts:**
* 1 tensioner_a
* 1 tensioner_b

**Steps:**
1. Insert 2 heatsets into each tensioner part 

![](images/A_and_b_idler_tensioner_heatsets.png)



# Attach the B idler

**Parts needed:**
* 4 M3x10 BHCS
* 3 M3 washers
* 2 F623 bearings
* 1 M3x35 BHCS
* 1 M3x25 BHCS
  
**Printed parts:**
* 1 tensioner_top
* 1 tensioner_bottom
* 1 tensioner_b

**Steps:**
1. Attach the tensioner_top to the front left of the printer, on the underside of the extrusion as shown using 2 M3x10 BHCS 

![](images/b_idler_lower_mounted.png)

2. Assemble a bearing stack using 2 M3 washers and 2 F623 bearings, place it on the mounted tensioner_top piece and use a screw to align it with the cutout for later 

![](images/b_idler_bearing_stack.png)

3. Attach the tensioner_bottom to the frame using M3x8 BHCS. Be careful to not dislodge the bearing stack 

![](images/b_idler_bottom_attached.png)

4. Add the tensioner_b part to the assembly, aligning the hole with the bearing stack. Use a M3x35 BHCS to fasten it in place 

![](images/b_idler_tensioner_added.png)

5. Thread a M3 washer and a M3x25 BHCS into the tensioner to finalize the idler assembly 

![](images/b_idler_tension_screw.png)





# Attach the A idler

**Parts needed:**
* 4 M3x10 BHCS
* 3 M3 washers
* 2 F623 bearings
* 1 M3x35 BHCS
* 1 M3x25 BHCS
  
**Printed parts:**
* 1 tensioner_top
* 1 tensioner_bottom
* 1 tensioner_a

**Steps:**
1. Attach the tensioner_bottom to the front right of the printer, on the underside of the extrusion as shown using 2 M3x10 BHCS 

![](images/a_idler_bottom_mounted.png)

2. Assemble a bearing stack using 2 M3 washers and 2 F623 bearings, place it on the mounted tensioner_bottom piece and use a screw to align it with the cutout for later 

![](images/a_idler_bearing_stack.png)

3. Attach the tensioner_top to the frame using M3x8 BHCS. Be careful to not dislodge the bearing stack 

![](images/a_idler_top_attached.png)

4. Add the tensioner_a part to the assembly, aligning the hole with the bearing stack. Use a M3x35 BHCS to fasten it in place 

![](images/a_idler_tensioner.png)

5. Thread a M3 washer and a M3x25 BHCS into the tensioner to finalize the idler assembly 

![](images/a_idler_finished.png)



# Attach rear Z brackets and misc parts

**Parts needed:**
* 4 M3x6 BHCS
* 4 M3x6 SHCS

**Printed parts:**
* 1 z_spacer
* 1 z_bracket_left
* 1 z_bracket_right
* 1 bowden_mount
* 1 umbilical_mount

**Steps:**
1. Using 2 M3x6 BHCS, add the z_bracket_right between extrusions B and C 

![](images/z_bracket_right.png)

2. Repeat this process for z_bracket_left
3. With 2 M3x6 SHCS, mount the umbilical_mount on top of extrusion B, centered over extrusion C 

![](images/umbilical_mount.png)

4. Add the bowden_mount to the bottom of the top rear extrusion E, also centered over extrusion C 

![](images/bowden_mount.png) using 2 M3x6 SHCS
