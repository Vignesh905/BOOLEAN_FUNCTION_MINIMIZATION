# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

 Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:PALLADI VENKATESH VIGNESH ; RegisterNumber: 24001645

     module exp2(a,b,c,d,f1,f2,w,x,y,z);
     
     input a,b,c,d,w,x,y,z;
     
     output f1;
     
     output f2;
     
     assign f1 =((~b & ~d)|(~a&b&d)|(a&b&~c));
     
     assign f2 =((~y&z)|(x&y)|(w&y));
     
     endmodule


**RTL realization**
![Screenshot 2024-12-03 143619](https://github.com/user-attachments/assets/c6575a20-37de-464d-9a56-ea29c8603b97)



**Timing Diagram**
![Screenshot 2024-12-03 143957](https://github.com/user-attachments/assets/d2d98194-cd43-4caf-b343-463f1706961b)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

