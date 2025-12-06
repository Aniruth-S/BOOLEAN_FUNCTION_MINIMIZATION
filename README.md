# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:25017728*/
module boolean_function_4var (
    input  wire A,
    input  wire B,
    input  wire C,
    input  wire D,
    output wire F
);

assign F = (~A & B) | (C & D) | (A & ~D);

endmodule

**RTL realization**

**Output:**
<img width="1040" height="565" alt="Screenshot 2025-12-06 133745" src="https://github.com/user-attachments/assets/72b864e6-054e-4bc7-9002-d9e917851538" />

**RTL**
<img width="1044" height="265" alt="Screenshot 2025-12-06 134047" src="https://github.com/user-attachments/assets/f1cbb7cd-b61f-46cd-ac46-a3af2012f9a9" />

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.
...
