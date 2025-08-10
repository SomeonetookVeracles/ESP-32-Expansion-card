---
Title: "ESP-32 Expansion Card"
Author: "Veracles"
Description: "A ESP-32 based expansion card with a removable antenna and a wide range of features"
Created On: "8/8/2025"
---

## August 8th

### Setup
I started this project by downloading the template for expansion modules from the framework github, and opening the kicad file. For some reason it didn't load the schematic though, so I ended up recreating them in the schematic editor myself and reassigning the footpads in the PCB editor. I also assigned the netclasses, so I don't have to worry about it later.

<div style="display: flex; justify-content: center; gap: 1%;">
  <img src="https://github.com/user-attachments/assets/f60419fa-532f-420b-9f21-3a2dc3b3c1c3" 
       style="width: 33%; border: 1px solid #ccc; box-sizing: border-box; vertical-align: top;" />
  <img src="https://github.com/user-attachments/assets/1471957e-33e3-4402-8f05-bb05cd0298a4" 
       style="width: 33%; border: 1px solid #ccc; box-sizing: border-box; vertical-align: top;" />
  <img src="https://github.com/user-attachments/assets/ce38e2d0-ed3b-4564-82af-6dfeee21176e" 
       style="width: 33%; border: 1px solid #ccc; box-sizing: border-box; vertical-align: top;" />
</div>

I just wired up the main power structure, including decoupling capacitors, level shifter from 5v to 3.3v, and the ground plane.
<img width="732" height="700" alt="image" src="https://github.com/user-attachments/assets/a184a568-b95b-47b9-b752-3a2b74c8e5fe" />

Here's a wip 3d model with the ESP-32 module on it, it's gonna be a bit thicker than the standard expansion card, but with the rubber feet it won't impede usage.

<img width="1068" height="572" alt="ESP-32 Devboard" src="https://github.com/user-attachments/assets/689385d6-0c75-41bb-baf8-6d6971138759" />

**Total Time Spent: 3 Hours**

## August 9th

I spent some time redoing the schematic, trying to make it compliant with the DRC, adding a copper ground plane, and adding a different ESP-32 chip for more signal strength.
<img width="762" height="651" alt="image" src="https://github.com/user-attachments/assets/afb0862b-1145-47ab-a7a7-4a72971e12dc" />

It's mostly done now.
