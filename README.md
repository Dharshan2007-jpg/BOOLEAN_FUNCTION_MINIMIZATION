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
module ex2 (a,b,c,d,w,x,y,z,f1,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1 = ~a&~b&~c&~d | a&~c&~d | ~b&c&~d | ~a&b&c&d | b&~c&d;
assign f2 = x&~y&z | ~x&~y&z | ~w&x&y | w&~x&y | w&x&y;
endmodule

```
Developed by:Dharshan Babu A
RegisterNumber:25008132


**RTL realization Output:**
<img width="1919" height="1022" alt="Screenshot 2025-11-19 213601" src="https://github.com/user-attachments/assets/4b1ab44a-6232-4152-aad5-1632b7da33df" />


**RTL:**
<img width="1916" height="1019" alt="Screenshot 2025-11-20 142120" src="https://github.com/user-attachments/assets/693e9938-921f-4522-a425-be18862e6c77" />


**Timing Diagram:**
<img width="327" height="527" alt="Screenshot 2025-11-20 180211" src="https://github.com/user-attachments/assets/6745fd01-b2c2-44d4-b591-67541da5bd2b" />


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

