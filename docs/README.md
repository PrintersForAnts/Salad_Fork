# Introduction

![](/images/whole_printer_small.png)    


**This is a work in progress. It *will* change.** The plan is to first complete a basic end to end sequence to document the build order, and then come back to further document and simplify the build steps

A note to experienced builders: Because of the need to preload nuts instead of using roll-ins like on a 2020-based printer, the build order is important to avoid redoing work. While this document is in development things are not 100% set yet but the rough order should be correct


# Lay out the frame and label the extrusions

Lay out your extrusions like this and add a label to each. We'll be referring to these by their label througout the build process.

![](images/frame_labels.png)

To help visualize where these go in the printer, you can refer to this image to see where they go

![](images/extrusion_map.png)


# Add the front Z rails

**Parts needed:**
* 2 extrusions with the label I
* 2 Z rails (MGN7H-200)
* 14 M2 nuts
* 14 M2x6 BHCS
* 2 M3x8 BHCS
* 2 M3 nut
  
**Printed parts:**
* 2 Rail stops (z_rail_nut_holder)

**Steps:**

1. Put 7 M2 nuts in each z rail nut holder, skipping every other hole
2. Insert rail nut holder into extrusion
3. Attach MGN7H rail with M2 BHCS
4. Align bottom of rail 27mm from end before tightening screws. 
5. Using a M3x8 BHCS and M3 nut, attach the railstop to the top of the rail
6. Repeat for second extrusion
7. **Be careful to not let the rail carriage slide off the rail**

![](images/z_rail_to_front_extrusion.png)
![](images/z_rail_bottom_clearance.png)




# Add rear Z rail

**Parts needed:**
* 1 extrusion with the label C
* 1 Z rail (MGN7H-200)
* 7 M2 nuts
* 7 M2x6 BHCS
* 1 M3x8 BHCS
* 1 M3 nut
  
**Printed parts:**
* 1 Rail stops (z_rail_nut_holder)

**Steps:**

1. Put 7 M2 nuts in the z rail nut holder, skipping every other hole
2. Insert rail nut holder into extrusion
3. Attach MGN7H rail with M2 BHCS
4. Align bottom of rail 27mm from end before tightening screws. 
5. Using a M3x8 BHCS and M3 nut, attach the railstop to the top of the rail
7. **Be careful to not let the rail carriage slide off the rail**






# Set up front bottom X extrusion


**Parts needed:**
* 1 extrusions with the label E
* 2 M3x8 BHCS
* 12 M3 nut
  
**Printed parts:**
* None

**Steps:**

1. Insert a M3x8 BHCS into each end of the extrusion, leaving about 2 mm clearance
2. Preload 4 M3 nuts into the top of the extrusion
3. Preload 8 M3 nuts into the bottom of the extrusion
![](images/front_bottom_x_preloads.png)




# Set up bottom Y extrusions


**Parts needed:**
* 2 extrusions with the label H
* 4 M3x8 BHCS
* 34 M3 nut
  
**Printed parts:**
* None

**Steps:**

1. Insert a M3x8 BHCS into each end of the extrusion, leaving about 2 mm clearance
2. Preload 2 M3 nuts into the top of the extrusion
3. Preload 7 M3 nuts into the bottom of the extrusion
4. Preload 4 M3 nuts into each side of the extrusion
5. Repeat for second extrusion

TODO grab picture



# Assemble front left corner of frame 

**Parts needed:**
* Front bottom X extrusion (E) from previous step
* 1 bottom Y extrusion (H) from previous step
* 1 Z extrusion with rail (I) from previous step

**Steps:**
1. Attach extrusion E to extrusion I, and tighten the screw in the E extrusion
1. Attach extrusion H to extrusion I, and tighten the screw in the H extrusion

*Notes:*
* For all of the frame assembly steps, be sure to make all corners square, and use a flat surface to build on to ensure the extrusions are aligned

![](images/front_left_assembly.png)




# Assemble front right corner of frame 

**Parts needed:**
* Frame assembly from previous step
* 1 bottom Y extrusion (H) from previous step
* 1 Z extrusion with rail (I) from previous step

**Steps:**
1. Attach extrusion I to extrusion E in the frame, and tighten the screw in the E extrusion
1. Attach extrusion H to extrusion I, and tighten the screw in the H extrusion

![](images/front_right_assembly.png)



# Rear bottom Z assembly 

**Parts needed:**
* Frame assembly from previous step
* 1 extrusion G
* 1 extrusion C (with Z rail attached)
* 2 M3x8 BHCS
* 14 M3 nuts 
  
**Steps:**
1. Add one M3x8 BHCS into each end of the G extrusion, leaving about 2mm clearance 
2. Add 8 M3 nuts to the bottom of the G extrusion
3. Add 2 M3 nuts to the back of the G extrusion
4. Add 4 M3 nuts to the top of the G extrusion
5. Attach the C extrusion to the middle of the G extrusion
6. Attach the rear Z assembly to the frame assembly
   
![](images/rear_z_assembly.png)

