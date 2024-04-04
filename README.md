# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Logic Diagram**
![WhatsApp Image 2024-04-04 at 14 06 42_29947507](https://github.com/ThakshaRishi/BOOLEAN_FUNCTION_MINIMIZATION/assets/144870423/24f7b33f-5bee-492a-a201-193f8954edb0)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
```
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:Thaksha Rishi RegisterNumber:212223100058*/
module experiment2(E,F,A,B,C,D);
output E,F;
input A,B,C,D;
assign E=A||(B&&C)||((!B)&&D);
assign F=((!B)&&C)||(B&&(!C)&&(!D));
endmodule
```
**Truth Table**
![WhatsApp Image 2024-04-04 at 14 56 15_0bb07d40](https://github.com/ThakshaRishi/BOOLEAN_FUNCTION_MINIMIZATION/assets/144870423/d922b8a7-a380-4f10-9130-3a179df1a467)

**RTL**
![WhatsApp Image 2024-04-04 at 14 06 42_64f68b0e](https://github.com/ThakshaRishi/BOOLEAN_FUNCTION_MINIMIZATION/assets/144870423/89bf336e-6302-4261-80b1-de74f82d0bc8)

**Output**
![WhatsApp Image 2024-04-04 at 14 06 56_d2878c58](https://github.com/ThakshaRishi/BOOLEAN_FUNCTION_MINIMIZATION/assets/144870423/97494255-23a0-4396-be84-fa2d9cf3f9f1)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

