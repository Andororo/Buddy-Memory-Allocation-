1. Objective
- You’ll understand the following concepts at the ARM assembly language level through this final project that implements memory/time-related C standard library functions in Thumb-2.
  - CPU operating modes: user and supervisor modes
  - System-call and interrupt handling procedures
  - C to assembler argument passing (APCS: ARM Procedure Call Standard)
  - Stack operations to implement recursions at the assembly language level
  - Buddy memory allocation
2. Project Overview
- Using the Thumb-2 assembly language, you will implement several functions of the C standard library that will be invoked from a C program named driver.c. See Table 1. These functions must be code in the Thumb-2 assembly language. Some of them can be implemented in stdlib.s running in the unprivileged thread mode (=user mode), whereas the others need to be implemented as supervisor calls, (i.e., in the handler mode = supervisor mode). For more details, log in one of the CSS Linux servers and type from the Linux shell:
  - man 3 function		where function is either bezro, strncpy, malloc, free, signal, or alarm
 
