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




![WhatsApp Image 2025-03-26 at 3 09 04 PM](https://github.com/user-attachments/assets/383c04c7-5802-46c0-b682-4542c5d87b0b)








**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
(i).
```
module exp_1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
endmodule
```
(ii).
```
module exp_2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y&z)|(w&y)|(x&y));
endmodule
```
Developed by:somalaraju rohini RegisterNumber:*/212224240156

**RTL realization**

(i).

![Screenshot 2025-03-16 212130](https://github.com/user-attachments/assets/a5d2cd41-898c-4984-8747-ed4f00fe5224)

(ii).





![Screenshot 2025-03-14 143418](https://github.com/user-attachments/assets/4a17f862-82c0-403e-9d75-e986c9dd74f4)




**Output:**


(i).

![Screenshot 2025-03-16 212621](https://github.com/user-attachments/assets/f32db8cb-b491-4dc4-ac08-7cda873faab7)


(ii).


![Screenshot 2025-03-14 144016](https://github.com/user-attachments/assets/7ae20e67-1bbf-4604-91d4-f1fa988667ac)



**RTL**

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

