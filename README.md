# Portable-Phone-Charger-2.0
A complete re-design of the original portable phone charger I was in the process of designing two years ago.

The original phone charger was incorrectly designed, using an LED driver as battery indication as opposed to transistor circuitry, along with the boost converter circuitry not being properly layed out or implemented properly in the schematic. This re-design of the original project not only fixes the original issues with the design, but make several enhacements to the size, routing, and component placement as well. 

The IP5306 is the main chargining IC used to charge a 3.6V Lithium Ion Battery with a current capacity of 3.25aH, with the IC mains feature being 2.1A synchronous charging with a boost converter efficiency of 92%. TVS diodes were added at the input and output of the IC for proper ESD protection, along with an AP9101C protection IC so that the battery doesn't overcharge or reach the minimun voltage threshold. The PCB was designed with a cylindrical enclosure in mind, where the PCB would sit inbetween the slits and the lithium ion battery would be soldered onto the solder pads and go underneath. 

The board itself is a two layer PCB with a top and bottom ground pour filling the front and back copper. Trace width was kept at 0.5mm for power and 0.3mm for the LED power status indication and ON/OFF switch. BOM consolidation was considered with capacitors being chosen with the same values at 22uF to reduce cost and the entire board consists of surfacemount components. 
