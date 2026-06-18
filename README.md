# Digital Calculator using Verilog on FPGA

A 4-bit digital calculator designed and implemented using Verilog HDL on a Xilinx FPGA platform. The calculator performs four basic arithmetic operations: Addition, Subtraction, Multiplication, and Division. Results are generated in binary, converted to BCD format, and displayed on a 7-segment display.

## Features

* 4-bit input operands
* Addition, Subtraction, Multiplication, and Division
* Binary-to-BCD conversion using the Double Dabble algorithm
* 7-segment display output
* Modular Verilog design
* Functional simulation and verification using Vivado
* FPGA hardware implementation

## Operation Selection

| Operation      | Opcode |
| -------------- | ------ |
| Addition       | 00     |
| Subtraction    | 01     |
| Multiplication | 10     |
| Division       | 11     |

## Hardware Inputs

| Input   | Description      |
| ------- | ---------------- |
| SW0–SW3 | Operand A        |
| SW4–SW7 | Operand B        |
| SW8–SW9 | Operation Select |

## Hardware Outputs

| Output            | Description                 |
| ----------------- | --------------------------- |
| 7-Segment Display | Decimal result (BCD format) |


## Tools Used

* Verilog HDL
* Xilinx Vivado
* FPGA Development Board

## Project Photos


<img width="160" height="90" alt="88539" src="https://github.com/user-attachments/assets/e430f43f-bc07-4287-ac16-3ff517289cfe" />


<img width="120" height="160" alt="88541" src="https://github.com/user-attachments/assets/bb5af496-80c9-488e-aaca-fb680bb69953" />


<img width="120" height="160" alt="88537" src="https://github.com/user-attachments/assets/1d260dfc-fd8e-4005-af58-632ec9da312c" />


## Team Members

* Prarthana Praveen
* Pavithra
* Rachna

## Results

The design was successfully simulated, synthesized, and tested on FPGA hardware. All arithmetic operations were verified with multiple test cases, and outputs were displayed correctly on the 7-segment display.
n-FPGA
