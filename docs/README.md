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
* 18 M3 nut
  
**Printed parts:**
* None

**Steps:**

1. Insert a M3x8 BHCS into each end of the extrusion, leaving about 2 mm clearance
2. Preload 2 M3 nuts into the top of the extrusion
3. Preload 7 M3 nuts into the bottom of the extrusion
4. Repeat for second extrusion

# Assemble front left corner of frame 

**Parts needed:**
* Front bottom X extrusion (E) from previous step
* 1 bottom Y extrusion (H) from previous step
* 1 Z extrusion with rail (I) from previous step