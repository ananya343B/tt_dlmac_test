<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

The project aims to implement a 16 bit floating point MAC unit for the DL float data type. The two operands will be taken from the input and bidirectional pins over two clock cyccles. The multiplication and addition units take one clock cycle each. The result is given out throught the output pins across two clock cycles, first the 8 msb bits of the result will be given out followed by the 8 lsb bits in the next clock.

## How to test

The project will be used to perform mac operations on 16 bit DL floating point numbers. DL float data type is used majorly in ML operations where speed of operation is of more importance than the accuracy of the operation. The design in this projects offers an accuracy upto 3 decimal points.

## External hardware

No external hardware required. For ease of verifying the working, a unit to combine the output (msb+lsb) could be used.
