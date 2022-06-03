# Attach the lower drive mounts and rear extrusion

**Parts needed:**
* 8 M3x10 BHCS
* 1 Extrusion B  

**Printed parts:**
* 1 A_Drive_Frame_Lower
* 1 B_Drive_Frame_Lower

**Steps:**
1. Attach the B_Drive_Frame_Lower to the left rear corner of the frame using 2 M3x10 BHCS
2. Attach the A_Drive_Frame_Lower to the right rear corner of the frame using 2 M3x10 BHCS
![](images/lower_motor_mounts_attached.png)
3. Center the extrusion B on the mounts and attach it with 2 M3x10 BHCS on each mount. The extrusion B will not sit flush with the extrusion C on the frame, this is intentional
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
* 1 M3x8 BHCS
* 2 M3x25 BHCS
* 3 M3x25 SHCS
* 1 B motor assembly from previous step


**Printed parts:**
* 1 B_Drive_Frame_Upper

**Steps:**

1. Attach the motor assembly to the B_drive_Frame_lower using 1 M3x8 BHCS in the position shown. Orient the stepper so that the wires are on the left side ![](images/b_drive_m3_x8.png)
2. Using 3 M3x25 SHCS, attach the B_Drive_Frame_Upper ![](images/b_drive_top_attached.png)
3. Add 4 M3x10 BHCS screws to attach the upper drive frame to the extrusions ![](images/b_drive_upper_mounted_extrusion.png)
4. Use a M3x25 BHCS to mount a bearing stack in place. A bearing stack is a M3 washer, 2 F623 bearings, and another M3 washer ![Bearing stack side view](images/bearing_stack_side_view.png) ![](images/b_drive_first_bearing_stack.png)
5. Use another M3x25 BHCS to mount two more bearing stacks ![](images/b_motor_second_bearing_stack.png)

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
2. Attach the switch to the upper motor mount using M2x10 self tapping screws.  ![](images/a_drive_upper_d2f_added.png)


# Assemble the A motor mount

**Parts needed:**
* 6 F623 bearings
* 6 M3 washers
* 4 M3x10 BHCS
* 1 M3x8 BHCS
* 2 M3x25 BHCS
* 3 M3x25 SHCS
* 1 B motor assembly from previous step


**Printed parts:**
* 1 A_Drive_Frame_Upper

**Steps:**

1. Attach the motor assembly to the A_drive_Frame_lower using 1 M3x8 BHCS in the position shown. Orient the stepper so that the wires are on the right side ![](images/a_drive_stepper_attached.png)
2. Using 3 M3x25 SHCS, attach the A_Drive_Frame_Upper ![](images/A_drive_top_attached.png)
3. Add 4 M3x10 BHCS screws to attach the upper drive frame to the extrusions ![](images/a_drive_upper_mounted_extrusion.png)
4. Use a M3x25 BHCS to mount a bearing stack in place. A bearing stack is a M3 washer, 2 F623 bearings, and another M3 washer ![Bearing stack side view](images/bearing_stack_side_view.png) ![](images/a_drive_first_bearing_stack.png)
5. Use another M3x25 BHCS to mount two more bearing stacks ![](images/a_motor_second_stack.png)

![](images/a_motor_rear_view.png)

