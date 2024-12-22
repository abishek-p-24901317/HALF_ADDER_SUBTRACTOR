# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers

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
![397930368-6917253e-4b99-4d73-99d4-ca83a8835326](https://github.com/user-attachments/assets/18b5ce40-b30e-4fde-bebe-b57c96613d6e)
![397930376-db04186a-6e78-4da3-bbf2-98ef7c5896e6](https://github.com/user-attachments/assets/287ddd85-99f2-47b8-b5dc-774c5097fd42)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by: Abishek P 24901317

![image](https://github.com/user-attachments/assets/1cdb70bf-2c13-4cbf-8771-3c26ffd48d5d)


**RTL Schematic**
![392862436-5cfd481f-8664-49de-aecf-4cc69f1ca977](https://github.com/user-attachments/assets/e27a3002-f8c8-45b4-adda-94ed84b5d0d9)
![392862581-b8ce1e3f-106a-46b1-b182-cc30227a4b46](https://github.com/user-attachments/assets/ed14a7e6-5830-4369-8900-45311416390b)

**Output/TIMING Waveform**
![392862681-4f0a4ecc-62d8-4c2b-8e90-b291698d5940](https://github.com/user-attachments/assets/9509180c-a595-449a-aadf-a409c18c4314)
![392862720-76da6dd6-e373-4956-b355-0659a42b3597](https://github.com/user-attachments/assets/3fb364b1-8aea-41a1-80d8-2e88aa3b1805)

**Result:**
Thus the truth table of half adder and half subtractor in Quartus II using Verilog programming is verified
