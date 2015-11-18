Interface used: LOGISIM

Final Instructions:

i. INPUT
The input is in the upper right corner of the CPU, it is composed of 10 input pins which remain activated throughout the run. Simply choose one to enable.

ii. OPERAND
The operand for multiplication can be found in the ROM section. It it the rightmost value (constant) labeled “operand”. Must be set to desired value

iii.	ROM
The ROM consists of a mega-BUS connected directly to the RAM (16 x 8bits). It is set using hexadecimal values for each ram slot. Once all the values are set (operand), turn ON the enabler pin (right below the ROM), tick the clock once, and then turn the enabler OFF. This will copy all the different constants into the RAM registers to input the program. After that, let the CPU run normally to execute.


Original instructions: 

A two bus executable classical computer using Logisim. This computer will have a system bus and a CPU bus.
The system bus has the following machines connected to it: a numeric key pad (digits 0 to 9), a 3 digit display, a 16 byte RAM, the MAR and MBR of the CPU. RAM has the AR, DR, and Mode.

The CPU bus has the following machines connected to it: two general purpose registers, the ALU, the MAR, and the MBR. The MAR is, at the same time, connected to the PC. The PC is connected to an adder. The MBR is, at the same time, connected to the IR. The IR is connected to the CU.

The ALU is made of the following machines: the L and R input registers, the A and STATUS output registers. The STATUS register flags the following conditions: overflow, negative result, and zero result. The L, R and A registers are connected to the CPU bus. The STATUS register is connected to the ALU and various CPU gates, as needed. Only the L register is connected to a 2's complement machine.

The PC increments by 1 at each new instruction. The PC is connected to the MAR.
The CU is constructed as you see fit. It must control the operation of the entire computer, both in CPU and on System Board. This will make things simpler for you. 

Register, Register1, Register2, R1, R2 means: Any general-purpose register, but not the same register in both parameters.

**Valid instructions are indicated in the pdf file**
