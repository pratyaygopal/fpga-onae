# One Night at ECEB - An FPGA Video Game

**FPGA Video Game inspired by Five Nights at Freddy’s**  
A playable game implemented on FPGA hardware using VHDL/Verilog.

---

## Overview

One Night at ECEB is an FPGA-based video game project developed using **Vivado**, **Vitis**, and HDL languages. The game runs on an FPGA board, using switch inputs for gameplay mechanics and on-board BRAM to store sprite imagery.

The gameplay simulates randomized animatronic spawns based on a user-selected seed — similar in spirit to classic survival horror mechanics. This repository contains the full project source for hardware design, simulations, and game assets.

---

## Demos

- **YouTube Playthrough:** https://www.youtube.com/watch?v=f_VWFFdSquA  
- **Showcase Demo:** https://www.youtube.com/watch?v=XwT2aaFxlOU

---

## Features

- FPGA implementation of a video game  
- Pseudo-randomized gameplay using hardware switches  
- Optional visual effects toggle (rainbow flash mode)  
- Complete Vivado & Vitis project source included

---

## Methodology

-  **BRAM Initialization**  
   Before running the game, you must generate and initialize BRAMs with COE files for all sprites/images.

-  **Gameplay Inputs**
   - Set the **five leftmost switches** on your FPGA board to choose a seed value.  
   - Set the **rightmost switch** to enable/disable the camera popup (affects difficulty and visual effects).

-  **Launch Environment**
   - Open the project in **Vivado** and **Vitis**.
   - Program and run on the target FPGA board.

---

## Documentation 

- For more docs: [report] (./fnaf.pdf)
