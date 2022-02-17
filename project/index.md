---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
classes: wide

---
# Selected Projects

## Architecture

### [7–Stage Sequential Single-Issued RISC-V CPU (RV64IMA)](../project/cpu-rv64ima)
  + We built it with Chisel HDL and Verilog. It can boot Linux 4.18 on FPGA @250MHz. 
  + It integrated with Sv39 MMU, L1 I/D-Cache and complete CSR design.
  + We have a efficient diff-test and CI flow to evaluate our design.

### 7–Stage Sequential Dual-Issued MIPS CPU (MIPS R1)
  + Supports 82 instructions of MIPS R1, integrates I/D-Cache and TLB, and it accesses memory through the AXI4 interface. Now it has entered the tape-out process at [SMIC@110nm](https://www.smics.com/en/site/mature_logic) sponsored by [OSCPU](https://github.com/OSCPU) plan.
  + Carried out back-end evaluation and timing optimization.
  + A few modern processor technologies are implemented (branch predictor and issue/commit queues).

## Software and System

### [UCAS-OS: A Unix-like OS based on Dual Core Rocket Chip (RV64GC)](../project/ucas-os)
  + OS run on a programmed FPGA (Xilinx PYNQ) with dual core Rocket Chip’s bitstream. 
  + A NIC driver was integrated in OS. Processes can send/receive IP packets through NIC on FPGA board.
 
### Compiler from a C-like Language to RISC-V ASM (RV64GC)
  It can handle a series of data structures and grammars such as arrays, loops, recursion etc. with ANTLR tool. The process includes grammar analysis, grammar tree construction, target language generation, etc.
