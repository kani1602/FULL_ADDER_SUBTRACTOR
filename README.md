# **EXP4:FULL ADDER AND SUBTRACTOR**

Implementation-of-Full-Adder-and-Full-subtractor-circuit

Developed by:kanishka.v   RegisterNumber:24003362

# **AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

# **Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

# **Full Adder and Full Subtractor**

# **Full Adder:**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

# **Figure -1 FULL ADDER**

# **Full Subtractor:**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

# **Truthtable:**

![image](https://github.com/user-attachments/assets/bbfb76c1-f5b7-4883-869c-878426691da5)

![image](https://github.com/user-attachments/assets/21d352cf-6288-4275-8b2b-12df52c1fb21)



# **Procedure:**

1.Type the program in Quartus software.

2.Compile and run the program.

3.Generate the RTL schematic and save the logic diagram.

4.Create nodes for inputs and outputs to generate the timing diagram.

5.For different input combinations generate the timing diagram.




# **Program:**
![Screenshot (26)](https://github.com/user-attachments/assets/bff4f866-d090-491e-8a7c-38fe7ed22844)
![Screenshot (27)](https://github.com/user-attachments/assets/58aadb71-f359-41c1-950f-257b2676f29a)
 

# **RTL Schematic:**


![Screenshot (28)](https://github.com/user-attachments/assets/0de190fc-1df9-4952-a5d8-0c3ea172f0d7)
![Screenshot (24)](https://github.com/user-attachments/assets/ec452fb3-4802-4862-ad1e-6ae318d2caa4)



# **Output Timing Waveform:**

![full adder](https://github.com/user-attachments/assets/2c30ca4d-64c8-4025-95e3-3f36aef66cbe)
![Screenshot (25)](https://github.com/user-attachments/assets/47769ace-8cd1-4dff-8079-cbaf757ab18f)



# **Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



