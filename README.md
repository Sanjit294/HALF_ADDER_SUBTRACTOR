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

![Screenshot 2024-11-28 12160](https://github.com/user-attachments/assets/e86c9c91-f88e-4dad-a104-435d1689ec8e)


Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

![Screenshot 2024-11-28 121600](https://github.com/user-attachments/assets/3d98fa2b-011c-4cb2-9fd2-536576dbe1bd)


Figure -02 HALF Subtractor

**Truthtable**

![image](https://github.com/user-attachments/assets/f1678429-71b4-4f66-b7f9-75acd02d6676)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by: Sanjit A RegisterNumber: 24005054*/

![Screenshot 2024-11-28 121143](https://github.com/user-attachments/assets/444df6d4-4df4-4de2-a284-081d2b19ef85)


**RTL Schematic**

![Screenshot 2024-11-28 121151](https://github.com/user-attachments/assets/1b9ebc05-301e-4f24-b7a0-1acd306812c1)


**Output/TIMING Waveform**

![Screenshot 2024-11-28 121202](https://github.com/user-attachments/assets/cecaed15-38ad-40dc-86a6-bf5f387cc8af)


**Result:**

 Thus the Half Adder and Half Subtractor circuits are designed and the truth tables is
 verified using Quartus software.
