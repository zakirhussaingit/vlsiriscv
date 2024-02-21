# Let's explore various types of RISC-V instructions

<p align="justify">The Instruction set is a collection of instructions that define the operations a processor can perform. 
These instructions are designed to be simple, efficient, and easily extensible, allowing for a high degree of customization and optimization.
The instruction set is organized into a base integer instruction set and a set of optional extensions, which provide specialized functionality for specific applications or domains.</p>

<details>
<summary><b>Base Integer Instruction Set</b></summary></summary>
<br>
<p align="justify">The base integer instruction set, also known as the "RV32I" or "RV64I" instruction set, depending on the address space size, provides the core functionality required for general-purpose computing. It includes instructions for <ol><li>arithmetic</li><li>logical and</li><li>control operations as well as</li><li>memory access and manipulation</li></ol>. The base integer instruction set is designed to be minimal and efficient, adhering to the principles of reduced instruction set computing (RISC).</p>
</details>
<details>
  <summary><b>The instruction formats and their six types</b></summary>
  <br>
<p align="justify">RISC-V instructions are encoded using a fixed-length 32-bit format, which simplifies decoding and execution. The instruction formats are categorized into six types: R, I, S, B, U, and J. Each format serves a specific purpose and has a unique encoding structure:</p>
<ul><li><b>R-type instructions:</b></li> Used for register-to-register operations, such as arithmetic and logical operations. They include three register operands: two source registers and one destination register. Eg:- add (Add 2 registers and store results in another)
<li><b>I-type instructions:</b></li> Used for immediate operations, such as arithmetic and logical operations with an immediate value. They include two register operands and a 12-bit immediate value. Eg:- li (Load immediate value)
<li><b>S-type instructions:</b></li> Used for store operations, which store data from a register to memory. They include two register operands and a 12-bit immediate value for the memory address offset. Eg:- sw (store the value in register)
<li><b>B-type instructions:</b></li> Used for conditional branch operations, which transfer control to a different instruction based on a condition. They include two register operands and a 12-bit immediate value for the branch target address. Eg:- beq (compare and label)
<li><b>U-type instructions:</b></li> Used for operations with a 20-bit immediate value, such as loading a 20-bit constant into a register or setting the upper 20 bits of a register. Eg:- lui (load upper immediate value)
<li><b>J-type instructions:</b></li> Used for unconditional jump operations, which transfer control to a different instruction unconditionally. They include one register operand and a 20-bit immediate value for the jump target address. Eg:- J (jump)</ul>
<br>
 
 [For more information read The RISC-V Instruction Set Manual](https://drive.google.com/file/d/1p2O-sJGlOw3o57nqzbgWeEMJ22KzKdrN/view?usp=sharing)
</details>

 <details>
<summary><b>RISC-V Register File</b></summary>
   <br>
<p align="justify">The RISC-V register file is a key component of the RISC-V architecture, providing a set of storage locations for holding data during the execution of instructions. The register file is organized into a set of integer registers and floating-point registers, depending on the extensions implemented in the processor. Registers play a crucial role in the RISC-V architecture, as they enable fast access to data and help improve the performance and efficiency of the processor.</p>

<details>
  <summary><b> <pre class="tab1">Integer Registers</pre></b></summary>
  <br>
<p align="justify">The integer registers in the RISC-V architecture are used for storing and manipulating integer values during the execution of instructions. You can perform operations such as addition, subtraction, multiplication, division, bit manipulation, and comparisons using these registers. There are 32 integer registers in the RV32I base integer instruction set, and 32 or 64 integer registers in the RV64I base integer instruction set, depending on the address space size. Each register is 32 bits wide in the RV32I ISA and 64 bits wide in the RV64I ISA.</p>

<p>The integer registers are named using a convention that indicates their intended usage, although they can be used for any purpose, as they are general-purpose registers. The naming convention is as follows:</p>

- x0: This register is hardwired to the value 0 and cannot be modified.
- x1-x31: These registers are general-purpose registers, with some having specific names to indicate their intended usage, such as:
  - ra (x1): Return address register, used for storing the return address in function calls.
  - sp (x2): Stack pointer register, used for managing the stack.
  - gp (x3): Global pointer register, used for accessing global data.
  - tp (x4): Thread pointer register, used for thread-local storage.
  - t0-t6 (x5-x11): Temporary registers, used for holding intermediate values during calculations.
  - a0-a7 (x10-x17): Argument registers, used for passing function arguments.
  - s0-s11 (x8, x9, x18-x27): Saved registers, used for preserving values across function calls.
  - t3-t6 (x28-x31): Additional temporary registers.
<p>By providing a set of integer registers with a well-defined naming convention, the RISC-V architecture enables efficient execution of integer operations and simplifies the development of compilers and other software tools that generate code for the processor.</p>

</details>

 </details>
