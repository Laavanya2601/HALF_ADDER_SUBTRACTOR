**NAME: LAAVANYA.R**

**REG NO: 24005572**

**EXPERIMENT NO:3  HALF_ADDER_SUBTRACTOR**

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**EQUIPMENTS REQUIRED:** 

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**HALF ADDER:**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**HALF SUBTRACTOR:**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**TRUTH TABLE:**

![Screenshot 2024-12-12 192838](https://github.com/user-attachments/assets/52880f65-f6ef-4896-ba33-7f75603e5ab2)

![Screenshot 2024-12-12 192847](https://github.com/user-attachments/assets/86342808-17b2-4fc0-afdc-07e0d2da7532)

**PROCEDURE:**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**PROGRAM:**

![Screenshot 2024-12-12 194301](https://github.com/user-attachments/assets/afacf9a2-4603-433f-a561-493d62821cf1)




**RTL SCHEMATIC DIAGRAM:**

![Screenshot 2024-12-12 194240](https://github.com/user-attachments/assets/e571639c-9fec-41bd-876f-cdd4dbfd691c)


**OUTPUY/TIMING WAVEFORM:**

![Screenshot 2024-12-12 192901](https://github.com/user-attachments/assets/cfa6ba95-26cd-49c3-adb7-86e9c95dcc9b)


**RESULT:**

Successfully designed a half adder and half subtractor circuit and verified its truth table in QUARTUS using Verilog programming.
