##  Description
This project implements a simple C-to-Assembly transpiler that converts
basic C-like statements into x86 assembly instructions.

The goal is to understand how high-level constructs map to low-level
assembly operations, including register usage, arithmetic, logic,
control flow, and loops.

##  Features

###  Register Mapping
- A → `eax`
- B → `ebx`
- C → `ecx`
- D → `edx`
- All values are treated as 4-byte integers.

###  Supported Instructions
- Data movement: `MOV`
- Arithmetic: `ADD`, `SUB`, `MUL`, `DIV`
- Logical: `AND`, `OR`, `XOR`
- Bitwise shifts: `SHL`, `SHR`
- Comparisons: `CMP`
- Jumps: `JMP`, `JE`, `JNE`, `JG`, `JGE`, `JL`, `JLE`

###  Control Flow
- `if-else` statements
- `for` loops
- `while` loops

##  Implementation Details
- Translates simple C assignments and expressions into assembly mnemonics.
- Handles multiplication and division using `EAX` and `EDX` conventions.
- Generates labels for conditional branches and loops.
- Output executable: `transpiler`
