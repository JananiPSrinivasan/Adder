<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

The Full Adder circuit uses two Half Adders.
The first Half Adder takes inputs A and B, producing a sum (S1) and an intermediate carry (C1).
The second Half Adder takes the sum from the first Half Adder (S1) and the Carry-in (Cin), producing the final sum S and an intermediate carry C2.
The final Carry-out (Cout) is the OR of the two carries: 
C1∨C2.

## How to test

Full Adder Logic Equations:

Sum (S): S = A ⊕ B ⊕ Cin
Carry-out (Cout): Cout = (A∧B) ∨ (Cin ∧ (A⊕B))



Full Adder Truth Table
The truth table for a Full Adder is as follows:

A	B	Cin	Sum (S)	Carry-out (Cout)
0	0	 0	 0 	        0
0	0	 1	 1	        0
0	1	 0	 1	        0
0	1	 1	 0	        1
1	0	 0	 1	        0
1	0	 1	 0	        1
1	1	 0	 0	        1
1	1	 1	 1	        1



## External hardware

Three LED bulbs are connected at the output of sum and carry
The LED will blink when the respective values are high




