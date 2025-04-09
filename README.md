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
~~~~
module ha_dataflow(a, b, s, ca); 
    input a; 
    input b; 
    output s; 
    output ca; 
  assign#2 s=a^b; 
  assign#2 ca=a&b;
  endmodule
~~~~
~~~
Developed by: Madhumitha R
RegisterNumber: 2122242400873
*/

~~~~
**RTL realization**
![WhatsApp Image 2025-04-09 at 09 14 23_cd85ab0c](https://github.com/user-attachments/assets/be1331f9-df50-40bd-9761-98818d525abe)

**Timing Diagram**
![WhatsApp Image 2025-04-09 at 09 14 34_631ec5ce](https://github.com/user-attachments/assets/bab44268-730d-4c9b-bff3-118ad5f4bbb8)

**Output:**

Hence we have implemented the given logic function and verified its operation in Quartus using Verilog programming.

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

