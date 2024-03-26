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

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by:Salini A RegisterNumber:*/23008741
**CODE**
**HALF ADDER**
![Screenshot 2024-03-26 082127](https://github.com/salinianbzhgan/HALF_ADDER_SUBTRACTOR/assets/145742862/5638d669-04ae-4859-b757-01b8106b6c44)

**HALF SUBTRACTOR**
![Screenshot 2024-03-26 082138](https://github.com/salinianbzhgan/HALF_ADDER_SUBTRACTOR/assets/145742862/7aacbc45-8263-404e-8814-687b53932d10)

**RTL Schematic**
**HALF ADDER**
![Screenshot 2024-03-26 082151](https://github.com/salinianbzhgan/HALF_ADDER_SUBTRACTOR/assets/145742862/e476e975-3b7f-4c8b-b15a-53fbdf7995ac)


**HALF SUBTRACTOR**
![Screenshot 2024-03-26 082200](https://github.com/salinianbzhgan/HALF_ADDER_SUBTRACTOR/assets/145742862/bda3b200-7d98-4242-90f6-e40f82ce2b9d)

**Output/TIMING Waveform**
**HALF ADDER**
![Screenshot 2024-03-26 082210](https://github.com/salinianbzhgan/HALF_ADDER_SUBTRACTOR/assets/145742862/f801f509-8f13-4a3a-8e16-66cc1b54903b)
**HALF SUBTRACTOR**
![Screenshot 2024-03-26 082221](https://github.com/salinianbzhgan/HALF_ADDER_SUBTRACTOR/assets/145742862/74728dfb-e30d-467e-bb3a-42027f734252)

**Result:**
Thus, a half adder and half subtractor circuit is designed to verify its truth table in Quartus using Verilog programming.
