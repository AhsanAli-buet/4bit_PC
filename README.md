# 4bit_PC

4bit PC is Digital System Design LAB Project of BUET CSE Level-4 term-1.

This the proteus simulation of 4bit PC which used 8bit BUS and executes 28 instructions. Full Details of this project is 
described in **4bit_PC_Final_Report.pdf**. The operation codes of 28 instructions and theirs hex values are in **4bit_PC_OpCODE.xlsx**
file and the signal bits for instructions (4 ROM output of control unit) are in **4bit_PC_final_ROM_Hex.xlsx** file.

Configuring ROM(opcode input,ASCHEX) stored in RAM of design file is mandotory to run the 4bit_PC simulation in Proteus.
The main design file of 4bit_PC is in [**4bitPC_083_Final/4bit_PC_83.DSN**](https://github.com/AhsanAli-buet/4bit_PC/blob/main/4bitPC_083_Final/4bit_PC_83.DSN) (proteus design file). Component of RAM,ALU in this
design file are implemented in child sheet. In [**4bitPC_083_Final/rom**](https://github.com/AhsanAli-buet/4bit_PC/tree/main/4bitPC_083_Final/rom) or [**rom_TEST**](https://github.com/AhsanAli-buet/4bit_PC/tree/main/4bitPC_083_Final/rom_TEST) folder [**OPCODE.bin**](https://github.com/AhsanAli-buet/4bit_PC/tree/main/4bitPC_083_Final/rom) and [**test.bin**](https://github.com/AhsanAli-buet/4bit_PC/tree/main/4bitPC_083_Final/rom_TEST) are 
input binary file and [**ROM1-ROM4.bin**](https://github.com/AhsanAli-buet/4bit_PC/tree/main/4bitPC_083_Final/rom) are for Control Unit. 

# 4bit_PC Block Diagram

![alt text](https://github.com/AhsanAli-buet/4bit_PC/blob/main/Screenshots/Block_Diagram.png?raw=true)

# 4bit_PC Circuit Diagram
![alt text](https://github.com/AhsanAli-buet/4bit_PC/blob/main/Screenshots/Circuit_Diagram.png?raw=true)

# How to execute 4bit_PC 
![alt text](https://github.com/AhsanAli-buet/4bit_PC/blob/main/Screenshots/ExecuteProcess.png?raw=true)
![alt text](https://github.com/AhsanAli-buet/4bit_PC/blob/main/Screenshots/ExecuteProcess2.png?raw=true)
