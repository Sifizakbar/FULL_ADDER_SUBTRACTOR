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

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**

**Procedure**

Write the detailed procedure here

**Program:**

Developed by: Sifiz.A
RegisterNumber: 25010152
<img width="994" height="287" alt="Screenshot (109)" src="https://github.com/user-attachments/assets/e2f536d8-8114-4473-9ad1-2d93c38e4b77" />
<img width="809" height="274" alt="Screenshot (110)" src="https://github.com/user-attachments/assets/2789256b-caf6-4bf3-87f9-a271e0aab1c7" />


**RTL Schematic**
<img width="1138" height="665" alt="Screenshot (111)" src="https://github.com/user-attachments/assets/bdb3ad01-98c0-467c-8698-c197cc6a6517" />
<img width="1131" height="440" alt="Screenshot (113)" src="https://github.com/user-attachments/assets/fd11da1f-b012-43f9-a904-9fba54a90da8" />


**Output Timing Waveform**
<img width="1037" height="432" alt="Screenshot (112)" src="https://github.com/user-attachments/assets/f31f2e2b-cdcd-4467-bd8c-b5e2ea0154f5" />
<img width="1194" height="442" alt="Screenshot (114)" src="https://github.com/user-attachments/assets/6ddbadac-c335-4214-835a-8c678f77c1e5" />

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



