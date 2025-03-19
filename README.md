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

Developed by:Dhanashree A RegisterNumber:212224040065
~~~
First program:
module EXP2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b&~d|a&b&~c|~a&b&d));
endmodule

Second program:
module EXP2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y&z|x&y|w&y));
endmodule
~~~
Truth table & symbol


![Screenshot 2025-03-19 085024](https://github.com/user-attachments/assets/a3724a9c-9ce9-40fe-bd19-9a112b97650a)


![Screenshot 2025-03-19 085015](https://github.com/user-attachments/assets/562bb0fd-20b5-4297-ba0f-9d9c166b2aa5)

**RTL**

![Screenshot 2025-03-19 084933](https://github.com/user-attachments/assets/d379134a-2cfc-476a-a603-24bb0389159c)
![Screenshot 2025-03-19 084927](https://github.com/user-attachments/assets/3379a739-6075-4c82-9874-982dc4cd18b5)


**Timing Diagram**

![Screenshot 2025-03-19 085106](https://github.com/user-attachments/assets/71c77d89-5e36-46ce-8d0a-f45f86b55457)
![Screenshot 2025-03-19 085053](https://github.com/user-attachments/assets/860df4f2-5ce2-4474-85da-ff1ecbddce98)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

