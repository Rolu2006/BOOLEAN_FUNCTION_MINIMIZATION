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

Developed by:somalaraju rohini RegisterNumber:*/212224240156
(ii).module exp_2(w,x,y,z,f1);
input w,x,y,z;
output f1;
assign f1=((~y&z)|(x&y)|(w&y));
endmodule

**RTL realization**

**Output:**

![Screenshot 2025-03-07 140223](https://github.com/user-attachments/assets/b365ba3c-8a00-4a8d-ac30-2e96108109f1)



![Screenshot 2025-03-14 144016](https://github.com/user-attachments/assets/a3255f3f-cc55-4ef0-98a1-3ab4d9a58565)







**RTL**

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

