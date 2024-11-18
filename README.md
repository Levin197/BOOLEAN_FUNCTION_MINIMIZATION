# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
module Exp3(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d) | (~a & d) | (a & b & ~c));
endmodule 

module exp3(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z) | (x & y) | (w & y));
endmodule
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:24009890*/


**RTL realization**
![WhatsApp Image 2024-11-11 at 14 25 35](https://github.com/user-attachments/assets/ed6e5cb0-89f3-4d86-b6f4-b81001c9fc2a)
![Screenshot 2024-10-14 143320 (2)](https://github.com/user-attachments/assets/af2c691c-32fd-46d7-a66a-754d55517525)

**Timing Diagram**
![WhatsApp Image 2024-11-11 at 14 22 56](https://github.com/user-attachments/assets/184f2775-f0c9-4ee5-81b2-e6a808181776)
![WhatsApp Image 2024-11-11 at 14 22 55](https://github.com/user-attachments/assets/f9583b36-638b-441a-953f-abd3d26d7e50)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

