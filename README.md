# **Single_Cycle_Processor_Design**
This is a 16-bit processor, which supports 16 ISA instructions. It has the conventional procedure of running an instruction. i.e instruction fectch --> instruction decode --> execute --> accessing memory --> write back. And it is single cycle. i.e. it executes one instruction per clock cycle.

## WISC-F23 ISA ##
Customized by the school's department for teaching purpose, this ISA is what the processor is built on. THis ISA include 16 16-bit-long instructions as following:

Compute Instructions: ADD, PADDSB, SUB, XOR, RED, SLL, SRA, ROR.
Memory Instructions:  LW, SW, LLB, LHB.
Control Instructions: B, BR, PCS, HLT.

## Main Internal Components ##
PC Register, Instruction Memory, Register File, Control Unit, ALU, Data Memory, Flag Register (used for branch).

## Simulation ##
All simulations are done in Modelsim.
