
# Umbilical ties


**Printed parts:**
* 2 cable_tie_down_misumi or cable_tie_down_makerbeam depending on your extrusion type


**Steps:**
1. Add 2 cable_tie_down_misumi to the right side of extrusion C. Exact position is not important, these are used to secure the toolhead umbilical wires 

![](images/cable_tie_downs.png)


# Wiring

For now, follow standard Trident wiring instructions, with some small differences for the Salad Fork. 

* There is no 5v power supply, you should power your pi (if relevant) from your mcu to pins 2/4 (5v) and 6 (gnd) on the pi GPIO
* Instead of an inductive probe, the klicky can be used instead, so no BAT85 diode required
* If using the Boop, you can skip the klicky and the Z endstop.
* Instead of cable chains, Salad Fork uses an umbilical routed up extrusion C
  
**Notes**

Motor wires can run under the MCU/PSU, there is clearance.

Motors should have diag disabled (by jumper, or by removing the diag pin) for all axis which are not using sensorless homing.  Failure to do so will disable that endstop.

Motors plug in as follows:
* 0: motor b
* 1: motor a
* 2: motor z (front left)
* 3: motor z (rear center)
* 4: motor z (front right)
* 5: empty
* 6: empty
* 7: motor extruder

Endstops plug in as follows:
- X endstop plugs into X endstop plug (if not using sensorless)
- Y endstop plugs into Y endstop plug (if not using sensorless)
- Z endstop plugs into Z endstop plug (if used)
- Klicky plugs into Z probe plug (otherwise boop plugs in to z probe)


