<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

The circuit is a 1-bit full adder. It adds inputs A, B and Cin (carry in) and produces Sum and Cout (carry out). Sum is A XOR B XOR Cin. Cout is 1 when at least two of the three inputs are 1

## How to test

Set A, B and Cin with the input switches and check the Sum and Cout LEDs against the full adder truth table. For example, A=1, B=1, Cin=0 gives Sum=0 and Cout=1

## External hardware

Two LEDs, one on the Sum output pin and one on the Cout output pin. No other external hardware is needed
