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
module deexp2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```
Developed by: ASWIKA.B
REF NO:24001099


**RTL realization**

**Output:**

**RTL**
![Screenshot 2024-12-05 190047](https://github.com/user-attachments/assets/934d20a1-19e9-4b7a-b170-8f009b588860)
**Timing Diagram**
![Screenshot 2024-12-05 185943](https://github.com/user-attachments/assets/b2c1ed7a-6f1d-498f-9a9e-00a16071862d)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

