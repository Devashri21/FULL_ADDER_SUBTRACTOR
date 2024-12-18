**NAME: DEVASHRI S**

**REF NO: 24001806**


# EXPERIMENT NO: 4 
# FULL ADDER SUBTRACTOR

IMPLEMENTATION OF FULL ADDER AND FULL SUBTRACTOR CIRCUIT

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**EQUIPMENT REQUIRED:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**FULL ADDER AND FULL SUBTRACTOR:**

**FULL ADDER:**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**FULL SUBTRACTOR:**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

**Figure -2 FULL SUBTRACTOR**

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**TRUTH TABLE:**

**FULL SUBTRACTOR:**

![Screenshot 2024-12-18 134346](https://github.com/user-attachments/assets/b4598b15-f820-41b2-abca-bcfc48bdf355)

**FULL ADDER:**

![Screenshot 2024-12-18 134336](https://github.com/user-attachments/assets/42daca05-24b0-4c5e-9319-f3cb83f3601e)



**PROCEDURE:**

Full Adder

1.Open Quartus II and create a new project.

2.Use schematic design entry to draw the full adder circuit.

3.The circuit consists of XOR, AND, and OR gates.

4.Compile the design, verify its functionality through simulation.

5.Implement the design on the target device and program it

Full Subtractor

1.Follow the same steps as for the full adder.

2.Draw the full subtractor circuit using schematic design.

3.The circuit includes XOR, AND, OR gates to perform subtraction.

4.Compile, simulate, implement, and program the design similarly to the full adder.

**PROGRAM:**
![Screenshot 2024-12-18 133920](https://github.com/user-attachments/assets/3c60d1b8-aee9-447e-b292-08537b552413)


**RTL VIEWER:**

![Screenshot 2024-12-18 133944](https://github.com/user-attachments/assets/7bb531ea-4afd-4d6d-b0af-5c3e9b714177)

**TIMING WAVEFORM:**

![Screenshot 2024-12-18 133959](https://github.com/user-attachments/assets/933076d1-5d31-43db-91ba-ec0d4668e5af)

**RESULT:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



