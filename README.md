# EXPERIMENT--04-ARITHMETIC-AND-LOGICAL-OPERATIONS-USING-LADDER-LOGIC
#  NAME:KEERTHANA T
# REGISTER NUMBER:212224100031
# DEPARTMENT:B.E-CSE(CYBER SECURITY)
# YEAR: 1st
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
Arithmetic Operations: Verify that the output shows correct results for addition, subtraction, multiplication, and division.
Logical Operations: Confirm that the output behaves as expected based on the logical conditions (AND, OR, NOT).
##  Simulation Screenshots:


ADDITION

![ADD 1](https://github.com/user-attachments/assets/8b33ae1d-ab99-40ce-afd8-df45e875563c)


![ADD 2](https://github.com/user-attachments/assets/644c028e-421c-4537-b60c-f127ce9d033c)


![ADD 3](https://github.com/user-attachments/assets/9eec9423-6dcb-45eb-b87e-acc871a55d0f)


![ADD 4](https://github.com/user-attachments/assets/02745b9c-91db-4547-9ded-183e5b67278d)


![ADD 5](https://github.com/user-attachments/assets/f93d0109-fc31-463f-b0b9-9283cb3282e5)


![ADD 6](https://github.com/user-attachments/assets/b44e5661-91e9-4007-9cc2-dde8998ce639)



SUBTRACTION

![SUB 1](https://github.com/user-attachments/assets/57c302d6-91f5-4826-a622-6285916503f3)


![SUB 2](https://github.com/user-attachments/assets/003e275d-bcb8-4fd9-a1f2-c5c05946b74c)


![SUB 3](https://github.com/user-attachments/assets/a1c37856-d240-40df-bb38-748981adce75)


![SUB 4](https://github.com/user-attachments/assets/dd8e94e8-8d97-43bd-be37-176294a6410f)


![SUB 5](https://github.com/user-attachments/assets/90039267-4a96-4966-9813-4618a94f10a9)


![SUB 6](https://github.com/user-attachments/assets/85e97503-6de2-4d51-9bab-d856ae55f227)



MULTIPILICATION

![MUL 1](https://github.com/user-attachments/assets/c02a3b04-b286-409f-b460-8133696a48f9)


![MUL 2](https://github.com/user-attachments/assets/472a598d-2ae4-4968-ab86-4ced61171bdb)


![MUL 3](https://github.com/user-attachments/assets/aa8cd108-37ed-462c-88e3-23a31ae4dc7a)


![MUL 4](https://github.com/user-attachments/assets/1c7a94f7-0af4-4b72-8af0-36188778c49f)


![MUL 5](https://github.com/user-attachments/assets/cd87a984-55a6-4af6-9835-971e628446ae)


![MUL 6](https://github.com/user-attachments/assets/e1479075-ebd5-4448-bf13-ab3f9a71a149)



DIVISION

![DIV 1](https://github.com/user-attachments/assets/40e79b7c-3ea4-4e39-b364-3862ebca97f9)


![DIV 2](https://github.com/user-attachments/assets/74807a96-624d-4950-8832-0b4ab6e6cb33)


![DIV 3](https://github.com/user-attachments/assets/a45e3d1b-f5ae-43d2-9958-a65975b9904d)


![DIV 4](https://github.com/user-attachments/assets/330ea624-f7ea-4aca-9fd9-19d24c6be23d)


![DIV 5](https://github.com/user-attachments/assets/9d63a632-84ad-401d-bca8-6b495196e289)


![DIV 6](https://github.com/user-attachments/assets/0af89661-3777-4bb1-8829-9cfb6746d6da)




## Results:
The ladder logic programs for various arithmetic and logical operations were successfully implemented and tested. The outputs were as expected, demonstrating correct calculation and logical decision-making capabilities. This experiment illustrates the essential role of arithmetic and logical functions in automated processes.
