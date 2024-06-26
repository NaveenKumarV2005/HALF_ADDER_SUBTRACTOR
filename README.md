# HALF_ADDER_SUBTRACTOR
# Developed by:Naveenkumar.v
# RegisterNumber:212223220068

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

![Screenshot 2024-04-03 203447](https://github.com/NaveenKumarV2005/HALF_ADDER_SUBTRACTOR/assets/151476286/ad9763b7-b10f-41aa-af2e-3f1b6188eb9b)




![Screenshot 2024-04-03 203454](https://github.com/NaveenKumarV2005/HALF_ADDER_SUBTRACTOR/assets/151476286/607f9f2a-9046-4b4a-969e-735393cb356f)




**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**



![Screenshot 2024-04-03 212113](https://github.com/NaveenKumarV2005/HALF_ADDER_SUBTRACTOR/assets/151476286/f9717b23-c022-4d5a-9ff8-06bfeca9d850)



**RTL Schematic**

![Screenshot 2024-04-03 203522](https://github.com/NaveenKumarV2005/HALF_ADDER_SUBTRACTOR/assets/151476286/4f54b220-1217-4f52-a21e-ef07125368aa)










**Output/TIMING Waveform**

![Screenshot 2024-04-03 203533](https://github.com/NaveenKumarV2005/HALF_ADDER_SUBTRACTOR/assets/151476286/05fd547a-1e02-45fe-9cc6-7dc81acbd036)







**Result:**

   half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.
