# Vulcan Hardware

This includes all the Schematics, PCBs, 3D models and any documents used such as the BOM, Reference Designs and Datasheets.

## 3D models
The models are broken up into three subfolders of V1, V2, and Latte Panda. The f3z files are full stack models to reduce clutter. 

**V1** includes models from the original design without the IO board stack up and larger power boards. It also has the final 3D model of V1 that comprises; smaller powerboards with only 2 legs, the IO board stack up, and mechanical supports. Finally, there is a basic model used for the mechanical alignment of the boards and supports.

**V2** is a lot smaller and includes a much simpler design of the input and output face as well as the mainboard stack up is not as detailed. These are, however, still accurate and have been used to design and create the PCB layouts.

**Latte Panda** folder contains the full stack up with the slanted top as well as the original design of the screen laying flat. Within these files also include the stands to hold the input and output PCBs. There is also a BOM for the screws required.

## Schematics and PCBs
Within the 'Designs' folder contains the schematics and PCBs in JSON files. This includes the Analog and Digital Input, Digital Output, the Cutout Panels, Input and Output boards, Powerboards and Mainboard.

**Analog and Digital Input and Digital Output** are all the same as V1. No changes made.

The output panel from the **Cutout Panels** is very similar to V1, however was designed better to allow the input and output panels to be centered within the enclosure. Input panel had a major shift in design due to the removal of Ethernet and USB A. 

**Powerboard** mechanically the same as V1, but with a 6pin on one of the legs to allow for the enable pin of the new SMPS. PSU entirely different besides the logic and the current sensor. (PSU design copied from Adriaan's RS232 PSU design)

**Input** a lot of changes from V1. Notably, the reduction in USB A and Ethernet allowed for more space and an aesthetical placing of the components. 

**Output** added ESD protection for pins from V1.

**Main** completely redesigned from V1. Notable changes, no Ethernet or USB but with USB FTDI. PSU same as Powerboard 3V3 and NOR flash. On the PCB the document squares are locations of the powerboards and IO stack up. This allows for mechanical representation to make sure components will not clash. 2mm keep out on top and bot displayed with silk lines.
