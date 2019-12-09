# 8-bit-CPU
This 8 bit cpu was simulated on Logisim-generic and assembler program is written in Java. 

Its architecture is based on the design SAP as mentioned in the book "Digital computer electronics" by Albert P. Malvino".

it has a 16 byte memory (RAM) onto which programs can be loaded.

Instruction set:

it currently supports 13 instructions.

1)NOP: no operation.

2)LDA <address>: loads 8 bit value stored at given address to accumulator.

3)ADD <address>: adds the value stored at given address to accumulator and stores the result in accumulator.

4)SUB <address>: subtracts the value stored at given address from accumulator and stores the result in accumulator.

5)STA <address>: stores value in accumulater at the address provided in memory.

6)LDI <value>: loads an immidiate value to accumulator.

7)JMP <address>: unconditional jump to specified address.

8)JC  <address>: jumps to provided address if carry flag is set.

9)JZ  <address>: jumps to provided address if zero flag is set.

10)MOVAB: moves contents of accumulator to register B .

11)MOVBA: moves contents of register B to accumulator .

12)OUT: displays value stored in accumlator on the display.

13)HLT: haults the system by suspending clock.
