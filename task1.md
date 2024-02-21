# Let's explore various types of RISC-V instructions

<p align="justify">The Instruction set is a collection of instructions that define the operations a processor can perform. 
These instructions are designed to be simple, efficient, and easily extensible, allowing for a high degree of customization and optimization.
The instruction set is organized into a base integer instruction set and a set of optional extensions, which provide specialized functionality for specific applications or domains.</p>

<details open>
<summary><b>Base Integer Instruction Set</b></summary></summary>
<br>
<p align="justify">The base integer instruction set, also known as the "RV32I" or "RV64I" instruction set, depending on the address space size, provides the core functionality required for general-purpose computing. It includes instructions for <ol><li>arithmetic</li><li>logical and</li><li>control operations as well as</li><li>memory access and manipulation</li></ol>. The base integer instruction set is designed to be minimal and efficient, adhering to the principles of reduced instruction set computing (RISC).</p>
</details>
<details open>
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
 
