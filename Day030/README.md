# Day 30

Notes reading [Doc 1](../Doc001.md).

* p.240
  - `BRK`: Breakpoint Instruction exception
  - `HLT`: `PE` halts execution and enters Debug state
  - Note: In `AArch32` state, previous versions of the architecture defined the `DBG` instruction, which could provide a hint to the debug system. This instruction executes as a `NOP`. Arm deprecates the use of the `DBG` instruction.
  - data-independent-time resource
  - Note: The collections of `PSTATE.NZCV` and `SPSR_ELx.NZCV` are each considered a single data-independent-time resource
  - data-independent-time instruction
  - data-independent-time value

* p.243
