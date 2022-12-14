# Mini-MIPS-Machine
Description: 
Design a simplified version of a MIPS machine and write Verilog programs that describe its structure and simulate its functioning. Use gate-level modeling for all components unless otherwise specified. The machine should include the following components:  

General purpose registers (register file): 4 registers, 16-bit long, numbered 0 - 3. Register $0 must contain 0 (read-only). Implemented in behavioral modeling. 

Other registers: 16-bit program counter, pipeline registers. Implemented by reg vectors in Verilog. 

Istruction Memory. 

Word size: 16 bits, word addressed, size: 1024 bytes. Implemented by reg array in Verilog. 

Data Memory. 

Word size: 16 bits, byte addressed, size: 1024 bytes. Implemented by reg array in Verilog.. 

ALU: 16-bit data, 4-bit control. 

Functions: and, or, nor, nand, add, sub, slt, Zero. Implemented at gate-level. 

Main Control unit: Behavioral model. 

Branch Control unit: Gate-level model. 

Other components necessary to connect the main components: multiplexes implemented at gate-level.
