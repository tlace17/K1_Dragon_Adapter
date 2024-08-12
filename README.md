# Getting Started:

This mod is an intermediate mod for your K1 printer and requires the use of my Linear Rail Gantry for compatibility. It requires some additional parts and pieces to work but once complete you can achieve very high flowrates (50mm<sup>3</sup>/s) and have the ability to do single hand nozzle changes. There are two setups that can be utilized, but for most users I recommend the normal Volcano version over the MZE+V6 version as you can achieve up to 80% of the flowrates without special shrouds.


# What you need:

[BOM](https://docs.google.com/spreadsheets/d/1sPTMPV2eK_xJK3cMwCgg2oyzx_67ZIePCPmvhL2Yadw/)

You also need a new printed carriage that can be found under the usermods section of the K1 Linear Rail Gantry [here](https://github.com/tlace17/K1-Linear-Rail-Gantry/tree/main/user-mods/BootyCall%20Jones/Dragon%20ACE%20Mod).


# Installation:


## Prepare heatsink:

1.) Drill through the heatsink heatbreak hole with 15/64” or 6mm drill bit:
![image](https://github.com/user-attachments/assets/d860f72f-a0d8-4043-8d4f-35189edfe326)

2.) Using an M3x0.5mm tap, tap the holes circled below: 
![image](https://github.com/user-attachments/assets/902403b3-4d97-48bb-8f94-709a00dca0b1)

3.) Attach the adapter plate to the bottom of the heatsink with 2 short M3 BHCS (4-8mm):
![image](https://github.com/user-attachments/assets/f692548d-ad80-4e5d-9938-32c74468f7a1)

## Assemble hotend:

1.) Thread the heartbreak into the top of the hotend until ~1mm above flush:
![image](https://github.com/user-attachments/assets/713c94e0-8f18-4474-bb2b-78cf9d2d8f46)


2.) Insert the 4 ceramic standoffs into the hotend: 
![image](https://github.com/user-attachments/assets/249d4c61-a6b7-4f3a-ae1e-ee7f39f3add7)


3.) Apply Boron Nitride paste to the lower half of the smooth section of the heatbreak and insert it into the heatsink:
![image](https://github.com/user-attachments/assets/c1984e64-4905-481f-aec0-728cc18a6f98)


4.) Now while holding the assembly together carefully twist the top of the heatbreak with pliers or fingers to seat the threaded portion of the heartbreak as far into the hotend as possible until you cannot spin anymore this will ensure good seating of the ceramic standoffs. 

5.) Now tighten the grub screw on the back of the heatsink and this should now have your hotend fully assembled.

6.) Now fully thread and tighten your V6 Volcano or Volcano adapter+MZE+V6 into the hotend until it is fully seated, you will fully tighten this when hot.


## Wiring:

1.) Reterminate hotend and thermistor properly for the k1 toolhead and install your full hotend/heatsink assembly into the new printed carriage.


## Final Steps:

1.) Add the new length of PTFE between the heartbreak and the extruder and continue onto klipper to set up your new thermistor, tighten your nozzle while hot and run a new PID.

Happy printing
