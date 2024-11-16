EXPERIMENT 3: HALF ADDER AND SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

NAME: KIRUTHIGA.B


ROLL NUMBER:24900863


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



![ha tt](https://github.com/user-attachments/assets/585687e4-3feb-4c7c-84a0-24d332a00570)



![hs tt](https://github.com/user-attachments/assets/89078d58-6ba8-4430-8273-4fe2f5bd35d3)




**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.



**Program:**



program for half adder:


![de ex2 sc 3](https://github.com/user-attachments/assets/c7a6fcb9-c407-4941-805f-f7cb3e37ecae)


program for half subtractor:


![de ex3 sc3](https://github.com/user-attachments/assets/42a9cb6a-caf9-414e-9bfe-c72bc3d55c08)






**RTL Schematic**

half adder RTL schematic:


![de ex2 sc 1](https://github.com/user-attachments/assets/442a92af-6232-45e8-8a74-5099c500722f)

half subtractor RTL schematic:



![de ex3 sc2](https://github.com/user-attachments/assets/f23dbf8c-3af1-4a27-822c-d4f42ea725ca)



**Output/TIMING Waveform**

half adder:

![de ex2 sc 2](https://github.com/user-attachments/assets/905e3dcc-6cd6-4db7-b001-29c6953c01cd)


half subtractor:


![de ex3 sc1](https://github.com/user-attachments/assets/ac43d41a-139f-4947-80d2-f6b122ce2abc)



**Result:**

Thus the program to design a half adder and subtractor circuit and its truth table has been verified.
