🔢 BCD to 7-Segment Display Decoder (Gate-Level Design)
📌 Project Overview

This project implements a BCD (Binary Coded Decimal) to 7-Segment Display Decoder using fundamental logic gates in Multisim.

Instead of using a dedicated decoder IC (like 7447), the circuit is designed from scratch using AND, OR, and NOT gates to generate the required Boolean expressions for each segment (a–g).

The circuit successfully displays decimal digits (0–9) based on 4-bit BCD input.

🧠 Objective

To design a combinational logic circuit for BCD to 7-segment decoding
To implement Boolean expressions using basic logic gates
To verify the design using Multisim simulation
To understand practical display interfacing concepts

🔌 Inputs and Outputs
Inputs:

A (MSB)
B
C
D (LSB)
These represent a 4-bit BCD number.
Outputs:
Seven segment outputs: a, b, c, d, e, f, g
Each output controls one segment of the 7-segment display.


⚙️ Working Principle

The 4-bit BCD input is applied to the logic network.
Each segment output is generated using minimized Boolean expressions.
AND, OR, and NOT gates are used to realize these expressions.
Current-limiting resistors (260Ω) are connected in series with each segment to prevent excessive current.
For valid BCD inputs (0000–1001), the corresponding decimal digit is displayed.
Invalid BCD inputs (1010–1111) are not considered in the design.


🛠 Components Used

AND gates
OR gates
NOT gates
7-segment display
260Ω resistors
DC logic input source

💻 Software Used
NI Multisim
