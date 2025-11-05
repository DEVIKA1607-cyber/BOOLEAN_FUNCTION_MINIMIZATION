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
 1. Type the program in Quartus software.
 2. Compile and run the program.
 3. Generate the RTL schematic and save the logic diagram.
 4. Create nodes for inputs and outputs to generate the timing diagram.
 5. For different input combinations generate the timing diagram.

1.	Type the program in Quartus software.
2.	

3.	Compile and run the program.

4.	Generate the RTL schematic and save the logic diagram.

5.	Create nodes for inputs and outputs to generate the timing diagram.

6.	For different input combinations generate the timing diagram.


**Program:**

~~~

Developed by: D DEVIKA 
RegisterNumber:212224100010
 i) module funct1(a,b,c,d,f1);
 input a,b,c,d;
 output f1;
 assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
 endmodule
 ii) module funct2(w,x,y,z,f2);
 input w,x,y,z;
 output f2;
 assign f2=((~y & z)|( w & y )|(x & y));
 endmodule

~~~
**RTL realization**
<img width="779" height="443" alt="image" src="https://github.com/user-attachments/assets/acc650c2-1fcd-4ae3-8c60-dbde71314d60" />
<img width="804" height="432" alt="image" src="https://github.com/user-attachments/assets/c0495507-aa1c-4440-bc24-e6b0c0e2978a" />




**Timing Diagram**
<img width="805" height="426" alt="image" src="https://github.com/user-attachments/assets/9a744f3f-f912-46bd-8876-6c085d56cec8" />
<img width="825" height="260" alt="image" src="https://github.com/user-attachments/assets/7750d4fa-5789-4b6a-ae8b-145c7fa94291" />


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

