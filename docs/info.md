<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works
This project generates VGA synchronization signals to drive a VGA display. 
It uses horizontal and vertical counters to produce the HSYNC and VSYNC signals 
according to the VGA timing specification. Based on the current pixel position, 
the design outputs simple RGB values to display a pattern on the screen.

## How to test
1. Connect the VGA signals from the design to a VGA monitor.
2. Provide a clock signal to the circuit.
3. Program the design and observe the VGA output.
4. The monitor should display the generated pattern if the sync signals are correct.

## External hardware

VGA monitor connected to the VGA output signals.
