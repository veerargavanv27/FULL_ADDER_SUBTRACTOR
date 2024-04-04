# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 
Carry = AB + ACin + BCin
![image](https://github.com/Yuvan291205/FULL_ADDER_SUBTRACTOR/assets/138849170/6f493555-e30b-4f28-b869-cf9b1ece707a)


![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin
![image](https://github.com/Yuvan291205/FULL_ADDER_SUBTRACTOR/assets/138849170/2eb9d4aa-c363-4a95-9d07-ec9ada8ca4e1)

**Truthtable**

**Procedure**

Write the detailed procedure here

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/

**RTL Schematic**
## Full adder:
![image](https://github.com/Yuvan291205/FULL_ADDER_SUBTRACTOR/assets/138849170/446f72c0-4990-4fa7-90de-465e266c40dd)
## Full subractor:
![image](https://github.com/Yuvan291205/FULL_ADDER_SUBTRACTOR/assets/138849170/0cd8f7ac-eb09-4c68-876a-f8ac03305753)


**Output Timing Waveform**
## Full adder:
![image](https://github.com/Yuvan291205/FULL_ADDER_SUBTRACTOR/assets/138849170/c80bc9e9-9c60-4a92-833b-f0a44c278301)
## Full subractor:
![image](https://github.com/Yuvan291205/FULL_ADDER_SUBTRACTOR/assets/138849170/6fa45ce7-1ec4-4a99-a8eb-fc30b2378249)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



