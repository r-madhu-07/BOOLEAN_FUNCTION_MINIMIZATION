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
![image](https://github.com/user-attachments/assets/ed8d3497-c670-47e0-9f8c-8c2e4ef2b073)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
~~~~
module ex2a(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~a&b&d)|(~b&~d)|(a&b&~c));
endmodule

module ex2b(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
~~~~
~~~
Developed by: Madhumitha R
RegisterNumber: 212224240082
*/

~~~~
**RTL realization**

![exp2ares](https://github.com/user-attachments/assets/83a77764-4c05-4099-94e1-ef10499bd97d)

![Screenshot 2025-04-16 113654](https://github.com/user-attachments/assets/41d932da-6d0b-4491-92ed-0586511e9ae3)


**Timing Diagram**
![Screenshot 2025-03-17 142521](https://github.com/user-attachments/assets/9740b3e5-110c-4c5a-80d3-7742e3c17850)

![Screenshot 2025-04-16 114245](https://github.com/user-attachments/assets/72cf370b-f087-4e7a-8bb9-f1e07887a3ac)


**Output:**

Hence we have implemented the given logic function and verified its operation in Quartus using Verilog programming.

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

