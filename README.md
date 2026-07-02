# 8-bit CPU in Logisim Evolution

## Features
- 8-bit ALU
- Registe File
- Program Counter
- ROM-based Instruction Memory
- Hardwired Control Unit
- Custom ISA
- LOADI
- ADD
- SUB
- HALT

## Instruction Format
Opcode (4) | Rd (3) | Rs (3) | Immediate (6)

## Opcode for different Operations:
1. LOADI - 0000
2. ADDITION - 0001
3. SUBTRACTION - 0010
4. OR OPERATION 0011
5. AND OPERATION 0100
6. XOR OPERATION 0101

## Components
- ALU
- Register File
- Program Counter
- ROM
- Control Unit
- CPU Datapath

## Sample Program
LOADI R1,5
LOADI R2,3
ADD R1,R2
HALT
