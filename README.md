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
```
module EXP2 (
    input  wire A,
    input  wire B,
    input  wire C,
    input  wire D,
    output wire F
);

assign F = (~A & B) | (C & D) | (A & ~D);

endmodule

```

Developed by: SAMEEHA S

RegisterNumber:25004324


**RTL realization**

**Output:** 

**Output:<img width="813" height="420" alt="image" src="https://github.com/user-attachments/assets/ed52c563-2217-4099-9128-455382bc08d1" />
**

**Timing Diagram**

<img width="1231" height="798" alt="image" src="https://github.com/user-attachments/assets/2be6dacd-1c0e-4332-a082-0184f1543f7f" />

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

