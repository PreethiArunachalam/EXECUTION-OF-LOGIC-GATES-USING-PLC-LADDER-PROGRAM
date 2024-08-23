# EXECUTION-OF-LOGIC-GATES-USING-PLC-LADDER-PROGRAM


 # NAME :Preethi A A
 # REGISTER NUMBER :212222110035
 # DEPARTMENT: CSE(IoT)
 # YEAR: 3

 
# Aim:
To implement and verify the functioning of basic logic gates (AND, OR, NOT, NAND, NOR, XOR) using a PLC ladder program and simulate the outputs.

# Apparatus Required:
Programmable Logic Controller (PLC) - A PLC with support for ladder logic programming.
PLC Programming Software - Software like RSLogix, TIA Portal, or CX-Programmer.
Computer System - To run the PLC programming software and perform simulations.
Input Devices - Push buttons or switches to simulate inputs (I/O modules).
Output Devices - LEDs or any indicator to visualize the output of logic gates (I/O modules).
Wires and Connectors - For connecting input/output devices to the PLC.
Power Supply - Appropriate power supply for PLC and peripherals.


# Theory:
Logic gates are the fundamental building blocks of digital circuits, and they process binary inputs to produce a binary output. In PLC programming, these logic gates can be implemented using ladder logic, which is a graphical programming language resembling electrical relay logic.

# Basic Logic Gates:
AND Gate:

Function: Outputs HIGH only when all inputs are HIGH.
Ladder Logic: Represented by two or more normally open contacts in series.
OR Gate:

Function: Outputs HIGH when at least one input is HIGH.
Ladder Logic: Represented by two or more normally open contacts in parallel.
NOT Gate:

Function: Outputs the inverse of the input signal.
Ladder Logic: Represented by a normally closed contact.
NAND Gate:

Function: Outputs LOW only when all inputs are HIGH.
Ladder Logic: An AND gate followed by a NOT gate.
NOR Gate:

Function: Outputs LOW when at least one input is HIGH.
Ladder Logic: An OR gate followed by a NOT gate.
XOR Gate:

Function: Outputs HIGH when an odd number of inputs are HIGH.
Ladder Logic: Represented by a combination of AND, OR, and NOT gates.
# Truth Tables:

# AND GATE:

![Screenshot 2024-08-23 090957](https://github.com/user-attachments/assets/213227f3-5665-4ba8-8017-71bfdb574cc6)

# OR GATE:

![Screenshot 2024-08-23 091017](https://github.com/user-attachments/assets/9f3ce48b-8ad3-4225-b316-b8fa830b68c5)

# NOT GATE:

![Screenshot 2024-08-23 092203](https://github.com/user-attachments/assets/fa09ca64-ddb5-4ad1-bbfd-c9d726b0a75c)

# NAND GATE:

![Screenshot 2024-08-23 091012](https://github.com/user-attachments/assets/af603459-6cd0-4098-b392-67e780d19b22)

# NOR GATE:

![Screenshot 2024-08-23 091024](https://github.com/user-attachments/assets/cb68b70e-6c0e-44f4-a6f2-1a4712e7a7e5)

# X-OR GATE:

![Screenshot 2024-08-23 091028](https://github.com/user-attachments/assets/15efe1d5-be40-4646-b5d2-8f9984b74d84)

# Procedure:
Setup the PLC Programming Environment:

Connect the PLC to the computer system and launch the PLC programming software.
Ensure all input and output devices are correctly connected to the PLC’s I/O modules.
Create Ladder Logic Programs:

For each logic gate, create a ladder logic rung that corresponds to the truth table of the gate.
Use normally open (NO) and normally closed (NC) contacts to implement AND, OR, and NOT logic.
For NAND, NOR, and XOR gates, combine the basic gates appropriately in the ladder diagram.
Simulate the Ladder Logic:

Simulate the ladder logic programs in the PLC software.
Toggle the input states and observe the output corresponding to each gate’s truth table.
# Download and Execute:

If available, download the ladder logic program to the PLC and run it.
Verify the outputs by changing the input states using the connected switches and observing the LEDs or output indicators.
Output of Simulation:
For each logic gate, when the inputs are changed according to the truth tables, the corresponding outputs should be observed as follows:
AND Gate: The output LED or indicator should light up only when both inputs are HIGH.
OR Gate: The output should light up when any one or both inputs are HIGH.
NOT Gate: The output should be the inverse of the input state.
NAND Gate: The output should be HIGH except when both inputs are HIGH.
NOR Gate: The output should be HIGH only when both inputs are LOW.
XOR Gate: The output should light up when exactly one input is HIGH.


# SIMULATION RESULTS 

# AND GATE:

![and gate](https://github.com/user-attachments/assets/78597d53-91ad-40d0-b803-a0368d2edb6e)

# OR GATE:

![or gate](https://github.com/user-attachments/assets/6c72de35-0e50-44de-94a1-d098b2cf1d05)

# NOT GATE:

![not gate](https://github.com/user-attachments/assets/4b0eeb81-d9c7-4f89-8d9f-924e0777792d)

# NAND GATE:

![nand gate](https://github.com/user-attachments/assets/d4df218d-2d19-4bbd-a202-4fed1e120f99)

# NOR GATE:

![nor gate](https://github.com/user-attachments/assets/0bf22183-bd47-4b27-a3c4-1e765abb8069)

# X-OR GATE:

![xor](https://github.com/user-attachments/assets/2f3a92bb-820a-47eb-b6b3-5ff6c51c4ddb)

# Results:
The ladder logic programs for each logic gate were successfully implemented and simulated.
The outputs observed matched the expected results as per the truth tables of the respective logic gates.
This experiment demonstrates the effective use of PLCs in executing digital logic operations, which are fundamental to industrial control systems.
