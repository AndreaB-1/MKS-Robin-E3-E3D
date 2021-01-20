# MKS-Robin-E3-E3D
This fork of the original repo contains only the modified firmware compiled to run on a MKS Robin E3 V1.0. 

The firmware is modified to used a BLtouch (or clone) which also acts as a Z-probe (removed Z endstop).

The Bltouch is connected to the allocated pin connector on the board, however, the trigger line (usualy the black and white cables) are connected directly to the Z-axis endstop on the board).

Also, the firmware is configured to work with the standard Ender-3 LCD.