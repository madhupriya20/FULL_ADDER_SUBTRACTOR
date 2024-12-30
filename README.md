### NAME : MADHUPRIYA.R
### REFERENCE NO : 24900083
# EXPERIMENT NO .4: FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

# AIM:

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

# EQUIPMENTS REQUIRED:

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

# FULL ADDER and FULL SUBTRACTOR:

# FULL ADDER:

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

# Figure -1 FULL ADDER:

# FULL SUBTRACTOR:

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

# TRUTH TABLE:


![TT 4 EX](https://github.com/user-attachments/assets/8e03d675-961d-48e9-9488-a7311e751748)

# PROCEDURE:

Implementing BOOLEAN functions in Verilog HDL (Hardware Description Language) involves translating the simplified Boolean expressions into Verilog code to describe the behavior of digital circuits. The basic building blocks in Verilog is module. The module represent a combinational circuit. Use logical operators (&, |, ~, ^) to implement Boolean functions directly. Use built-in gate primitives for basic functions. Use University program VWF to verify the functionality of your Verilog modules. Create waveform and check outputs against expected results.

# PROGRAM:


![EX 4](https://github.com/user-attachments/assets/9e7f0243-43d9-452c-824b-62963166b008)

# RTL SYSTEMATIC:

![logic gate diagram 4](https://github.com/user-attachments/assets/fb36aa01-0bc2-4188-a894-81d7d2d40b70)


# OUTPUT WAVEFORM:

![4 waveform](https://github.com/user-attachments/assets/49cd36eb-1428-43f9-b6d0-8f5579d7c1ed)

# RESULT:

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



