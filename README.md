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

![Screenshot 2024-12-05 203200](https://github.com/user-attachments/assets/cf99f445-604b-4163-86f0-b1fd658acbd0)


Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

![Screenshot 2024-12-05 205021](https://github.com/user-attachments/assets/8a47c7ed-6420-45bd-89ce-f0458d98db03)


Figure -02 HALF Subtractor

**Truthtable**
![Screenshot 2024-12-08 203022](https://github.com/user-attachments/assets/ae32c20f-2a78-4445-a72d-9ad1b5244736)


![Screenshot 2024-12-08 202536](https://github.com/user-attachments/assets/485d11d0-3769-462f-aa34-0bc153cb661c)




**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by:Sarankumar.V   RegisterNumber:24010668

![Screenshot 2024-12-05 203224](https://github.com/user-attachments/assets/136ebab5-a1ac-496a-8d10-f632b9f825b2)

![Screenshot 2024-12-05 204402](https://github.com/user-attachments/assets/dfd3c468-0d18-4999-bbee-cf107cce7ab1)

**RTL Schematic**

**Output/TIMING Waveform**
![Screenshot 2024-12-05 203433](https://github.com/user-attachments/assets/8c2e8f86-b87b-426b-97d4-b246172a5c08)


![Screenshot 2024-12-05 204648](https://github.com/user-attachments/assets/74d77a0c-82f3-47ca-a2a5-f0e54c083bb9)

**Result:**
Thus the truth table of Half adder_subractor in Quartus || using verilog programming are studied,verified and executed successfully.
