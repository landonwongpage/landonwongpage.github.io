---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
classes: wide

---
# Welcome

Songyue (Landon) Wang (王嵩岳) is now a B.S. candidate major in Computer Science (CS) at University of Chinese Academy of Science (UCAS). He is also a guest student researcher at Institute of Computing Technology, Chinese Academy of Sciences (ICT, CAS). He is supervised by [Prof. Ninghui Sun](https://dl.acm.org/profile/81100446659) and [Prof. Mingyu Chen](https://scholar.google.com/citations?user=_hZiQeUAAAAJ&hl=zh-CN) successively at ICT, CAS. His research interests including computer architecture, operating systems and applications of FPGA clouds.

## Research Experience

+ **Cooperative Operation of the Fleet in the Environment of the Internet of Vehicles** (Sept. 2019 – Aug. 2020)\
  *Research Leader, Department of Computer Sciences, UCAS*

+ **SERVE: An Agile Hardware Design and Evaluate Platform Based on CI/CD and Cloud FPGAs** (Jul. 2020 - Sept. 2021)\
  *Researcher, [State Key Laboratory of Computer Architecture (SKLCA), ICT, CAS](http://english.ict.cas.cn/rh/rd/200908/t20090820_33353.html)*
  
+ **RISC-V Async Memory Access Unit (AMU) with Message Interface Prototype System** (Jul. 2021-Jun. 2022)\
  *Researcher, SKLCA, ICT, CAS*

+ **ByteFPGA: FPGA Development Middle-Platform for AI Computing Acceleration** (Oct. 2021-Feb. 2022)\
  *Intern Researcher, [Data System Group, AI Laboratory, ByteDance Inc](https://ailab.bytedance.com/research)*
  
+ ****Software Defined Rack (SDR) for Resource Disaggregation in Cloud Computing**** (Feb. 2022-May.2022)\
  *Intern Researcher, [System and Network Research Group, Microsoft Research Asia (MSRA)](https://www.microsoft.com/en-us/research/group/systems-and-networking-research-group-asia/)*
 
## Selected Projects
+ **[7–Stage Sequential Single-Issued RISC-V CPU (RV64IMA)](./project/cpu-rv64ima)**
  + We built it with Chisel HDL and Verilog. It can boot Linux 4.18 on FPGA @250MHz. 
  + It integrated with Sv39 MMU, L1 I/D-Cache and complete CSR design.
  + We have a efficient diff-test and CI flow to evaluate our design.

+ **[UCAS-OS: A Unix-like OS based on Dual Core Rocket Chip (RV64GC)](./project/ucas-os)**
  + OS run on a programmed FPGA (Xilinx PYNQ) with dual core Rocket Chip’s bitstream. 
  + A NIC driver was integrated in OS. Processes can send/receive IP packets through NIC on FPGA board.
 
+ **Compiler from a C-like Language to RISC-V ASM (RV64GC)**\
  It can handle a series of data structures and grammars such as arrays, loops, recursion etc. with ANTLR tool. The process includes grammar analysis, grammar tree construction, target language generation, etc.
  
+ **7–Stage Sequential Dual-Issued MIPS CPU (MIPS R1)**
  + Supports 82 instructions of MIPS R1, integrates I/D-Cache and TLB, and it accesses memory through the AXI4 interface. Now it has entered the tape-out process at [SMIC@110nm](https://www.smics.com/en/site/mature_logic) sponsored by [OSCPU](https://github.com/OSCPU) plan.
  + Carried out back-end evaluation and timing optimization.
  + A few modern processor technologies are implemented (branch predictor and issue/commit queues).

## Teaching Experience
+ **Experiment on Computer Organization and Design (COD) (2021 Spring)**\
  *Teaching Assistant, Department of Computer Science, UCAS (Mar. 2021-Jul. 2021)*\
  Contributed to curriculum project design, maintained and improved the FPGA cloud platform (SERVE) used in course, lectured to students and graded the students’ RTL design. This class taught totaled 100+ undergraduates.
  
+ **Practice on Operating System (OS) (2021 Fall)**\
  *Teaching Assistant, Department of Computer Science, UCAS (Sept. 2021-Jan. 2022)*\
  Designed course projects, organized and participated in course Q&A sessions and wrote instruction manual to help
students’ debugging. Class taught totaled 100+ undergraduates major in CS.

## Patents
1. **Songyue Wang** at ICT, CAS. A Method of FPGA Cluster Management and Bitstream Deployment. *China Patent* 2021.

## Awards

+ Outstanding Student, UCAS (2019, 2020 and 2021)
+ 2nd Academic Scholarship, UCAS (2019, 2020 and 2021)
+ National College Student Scholarship, UCAS (2021)
+ 3rd Award of 5th National Student Computer System Capability Challenge 2021 (NSCSCC 2021): CPU Design Track (Loongson Cup), Ministry of Education of China (Co-Organizer: Xilinx Inc and Loongson Co., Ltd) 
+ 2nd Award of 1st Dream Cup Chinese Youth IC Technology Competition (CYICTC 2021): Open-source Chip Development and Performance Optimization Track, Ministry of Science and Technology of China (Organizer: Chinese Academy of Science)

## Relevant Skills
+ **Language:** English (fluent, TOEFL ITP Plus: 547), Chinese Mandarin (native)
+ **Software Skills:** Programming: C, C++, Python, ASM (x86, RISC-V), tcl and Linux bash Performance evaluation tools; Machine learning (PyTorch); Git and DevOps tools.
+ **Hardware Skills:** RTL Design (Verilog, Chisel); FPGA (Xilinx Vivado, verilator, SpyGlass)
+ **Other Knowledege:** Basic cloud computing technology and experience (virtualization, container, etc.) Familiar with CPU architecture, memory hierarchy, transmission bus (PCIe, AXI), etc. Familiar with hardware and software co-design: OS, hardware driver, etc.
