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
```
Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
Developed by: D.DEVIKA
RegisterNumber:24002534
```
```
module exp2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```


**RTL realization**
![exp2 (2)](https://github.com/user-attachments/assets/85e167bd-d1ee-41e9-946a-50e1345f25ef)

**Output:**

**RTL**

**Timing Diagram**

![exp2](https://github.com/user-attachments/assets/ec4fa345-a456-4484-95a0-19ba37014fd2)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

