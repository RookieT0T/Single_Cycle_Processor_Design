# **Single_Cycle_Processor_Design**
This is a 16-bit processor, which supports 16 ISA instructions. It has the conventional procedure of running an instruction. i.e instruction fectch --> instruction decode --> execute --> accessing memory --> write back. And it is a single-cycle processor. i.e. it executes one instruction per clock cycle.

## WISC ISA ##
Based on MIPS ISA and customized by the school's CS/ECE department for teaching purposes, this ISA is what the processor is built on. This ISA includes sixteen 16-bit-long instructions as follows:

1. Compute Type Instructions: ADD, PADDSB, SUB, XOR, RED, SLL, SRA, ROR.
2. Memory Type Instructions:  LW, SW, LLB, LHB.
3. Control Type Instructions: B, BR, PCS, HLT.

## Main Internal Components ##
PC Register, Instruction Memory, Register File, Control Unit, ALU, Data Memory, Flag Register (used for branch).

## Simulation ##
All simulations are done in Modelsim.
