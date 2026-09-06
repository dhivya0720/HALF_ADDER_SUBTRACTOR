# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

Half Adder
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/74c12d48-0303-4760-9a57-27ae4de0fbc9" />
Half Subtractor
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/ebb66d71-1808-4580-be80-01f3fb7c4219" />



Developed by: DHIVYA DARSHNEE U Register Number:212225220027*/

**RTL Schematic**
Half Adder
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/6730b89b-3f6a-4e7f-8aea-33516a113736" />
Half Subtractor
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/fd5f63a4-3b33-41b3-a48d-514b71272578" />


**Output/TIMING Waveform**
<img width="1211" height="731" alt="image" src="https://github.com/user-attachments/assets/64758342-e99d-4ecb-a67b-611f050e6962" />
<img width="1210" height="737" alt="image" src="https://github.com/user-attachments/assets/58897572-a758-4465-8712-afaa7638a7a0" />


**Result:** Thus the Half Adder and Half Subtractor are studied and the truth tables are verified
