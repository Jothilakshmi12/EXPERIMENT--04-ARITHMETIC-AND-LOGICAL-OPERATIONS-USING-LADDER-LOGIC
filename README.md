# EXPERIMENT-04 ARITHMETIC AND LOGICAL OPERATIONS USING LADDER LOGIC.
# NAME: JOTHILAKSHMI PALANI
# REGISTER NUMBER: 212223110017
# DEPARTMENT: B.E.CSE(IOT)
# YEAR: III
# DATE: 23.02.2026

## Aim:
To understand and implement various arithmetic and logical operations in Programmable Logic Controller (PLC) ladder logic.

## Apparatus Required:
Programmable Logic Controller (PLC): A PLC that supports arithmetic and logical functions.
PLC Programming Software: Software such as RSLogix, TIA Portal, or CX-Programmer.
Computer System: For programming and simulating the PLC ladder logic.
Input Devices: Push buttons or switches to trigger arithmetic and logical operations.
Output Devices: LEDs or other indicators to visualize the results of operations.
Wires and Connectors: For interfacing input/output devices with the PLC.
Power Supply: Appropriate power supply for the PLC and peripherals.
## Theory:
Arithmetic and logical operations in PLC ladder logic are essential for handling complex decision-making and calculations within automation processes. Arithmetic operations (e.g., addition, subtraction, multiplication, division) and logical operations (e.g., AND, OR, NOT) allow PLCs to perform calculations, make comparisons, and control actions based on specific conditions.

## Types of Operations:
Arithmetic Operations:

Addition (ADD): Adds two values and stores the result in a specified memory location.
Subtraction (SUB): Subtracts one value from another.
Multiplication (MUL): Multiplies two values.
Division (DIV): Divides one value by another.
Logical Operations:

AND Operation: The output is TRUE only when all inputs are TRUE.
OR Operation: The output is TRUE when any input is TRUE.
NOT Operation: Inverts the input logic.
Procedure:
Setup the PLC Programming Environment:

Connect the PLC to the computer and launch the PLC programming software.
Ensure all input and output devices are connected to the PLC’s I/O modules.
Create Ladder Logic for Arithmetic Operations:

Addition (ADD):
Create a rung with an input (e.g., push button) linked to an ADD instruction.
Set the operands (e.g., two values) and the destination to store the result.
Subtraction (SUB):
Create a rung with an input linked to a SUB instruction.
Set the values and the destination to store the result.
Multiplication (MUL):
Create a rung with an input linked to a MUL instruction.
Set the values and the destination to store the result.
Division (DIV):
Create a rung with an input linked to a DIV instruction.
Set the values and the destination to store the result.
Create Ladder Logic for Logical Operations:

AND Operation:
Create a rung with two inputs connected in series to simulate an AND operation.
Assign an output to visualize when both inputs are TRUE.
OR Operation:
Create a rung with two inputs connected in parallel to simulate an OR operation.
Assign an output to visualize when any input is TRUE.
NOT Operation:
Create a rung with a single input connected to a NOT function.
Assign an output to visualize the inverted logic.
Simulate the Ladder Logic:

Arithmetic Operations:
Run the simulation in the PLC software. Trigger each operation by pressing the input button, and observe the output values.
Logical Operations:
Simulate the AND, OR, and NOT logic by toggling the inputs and observing the outputs.
Download and Execute:

Download the ladder logic program to the PLC if available and run it.
Test the arithmetic and logical operations with physical push buttons and observe the LEDs or other output devices.


## Outputs:

<img width="788" height="472" alt="Screenshot 2026-02-23 105723" src="https://github.com/user-attachments/assets/8517c4ab-f459-4e07-966e-9e9a6ab593ce" />

<img width="759" height="467" alt="Screenshot 2026-02-23 105740" src="https://github.com/user-attachments/assets/55e5da36-0d6d-47a8-88e7-406e2fe9af1c" />

<img width="760" height="464" alt="Screenshot 2026-02-23 105753" src="https://github.com/user-attachments/assets/ebb6547c-220d-4ee3-a1ae-5d5f6adb1017" />

<img width="758" height="420" alt="Screenshot 2026-02-23 105808" src="https://github.com/user-attachments/assets/6fbb95ef-3fc2-473c-b0a5-445e938d5ed6" />

<img width="674" height="400" alt="Screenshot 2026-02-23 105830" src="https://github.com/user-attachments/assets/6959f73e-4653-41f6-8499-93fd743a4604" />

##  Simulation Screenshots:

## ADDITION:
<img width="1513" height="368" alt="Screenshot 2026-02-23 105632" src="https://github.com/user-attachments/assets/8137cd98-5039-4cd2-878e-bf6a01d08ad2" />

## SUBTRACTION:
<img width="1504" height="356" alt="Screenshot 2026-02-23 105903" src="https://github.com/user-attachments/assets/427aa27b-01d0-4a78-8e9b-a00bf6ea86dc" />

## MULTIPLY:
<img width="1500" height="383" alt="Screenshot 2026-02-23 105951" src="https://github.com/user-attachments/assets/eeb9649c-37ba-4343-a461-06ec91aa781c" />

## DIVISION:
<img width="1504" height="365" alt="Screenshot 2026-02-23 110010" src="https://github.com/user-attachments/assets/ae514b6d-2989-4a21-b1f7-791a567b1726" />

## OR:
<img width="1510" height="365" alt="Screenshot 2026-02-23 110032" src="https://github.com/user-attachments/assets/fd921eed-3af7-4614-9845-14bbbc1032d9" />

## AND:
<img width="1512" height="362" alt="Screenshot 2026-02-23 110051" src="https://github.com/user-attachments/assets/f5a14f19-803a-4350-9129-501726c021ee" />

## XOR:
<img width="1502" height="364" alt="Screenshot 2026-02-23 110112" src="https://github.com/user-attachments/assets/db9e1a80-29c0-43fd-ba21-60797fef3547" />

## NEGATIVE(NOT):
<img width="1506" height="367" alt="Screenshot 2026-02-23 110131" src="https://github.com/user-attachments/assets/51c93641-2236-481c-b413-b70513f37350" />

## INCREMENT:
<img width="1505" height="360" alt="Screenshot 2026-02-23 110207" src="https://github.com/user-attachments/assets/ede17e9a-28ce-4deb-9b13-6e7bcebaa719" />

## DECREMENT:
<img width="1501" height="366" alt="Screenshot 2026-02-23 110305" src="https://github.com/user-attachments/assets/ff178b5c-845a-48a6-ab9c-e9ad821a964d" />

## Results:
The ladder logic programs for various arithmetic and logical operations were successfully implemented and tested. The outputs were as expected, demonstrating correct calculation and logical decision-making capabilities. This experiment illustrates the essential role of arithmetic and logical functions in automated processes.
