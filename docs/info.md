<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This is a Game Of Life Remake using verilog code and VGA displays. This has a new spin as it will have presets as well as new rules. The base game of life rules are 
1. Any live cell with fewer than two live neighbours dies, as if by underpopulation.
2. Any live cell with two or three live neighbours lives on to the next generation.
3. Any live cell with more than three live neighbours dies, as if by overpopulation.
4. Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction

For my bonus rules,
5.Sick cells infect other live cells, this is in pinout 2 setting
6.

## How to test

connect the chip to vga and watch the magic roll baby

## External hardware

List external hardware used in your project (e.g. PMOD, LED display, etc), if any
