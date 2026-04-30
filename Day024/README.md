# Day 24

Notes reading [Doc 1](../Doc001.md).

* p.202
  - `EL0`, `EL1`, `EL2`, `EL3`: Exception levels
  - `EL0`: lowest privilege level, unprivileged

* p.203
  - `R0` to `R30`
    - `X0` to `X30`: 64-bit general-purpose registers
    - `W0` to `W30`: 32-bit general-purpose registers
    - `X30`: procedure call link register
    - `SP`, `WSP`: Stack Pointer
    - Note: Stack pointer alignment to a 16-byte boundary is configurable at `EL1`
    - `PC`
    - Note: Attempting to execute an `A64` instruction that is not word-aligned generates a `PC` alignment fault
    - `V0` to `V31`:
      - `Q0` to `Q31`: 128-bit registers
      - `D0` to `D31`: 64-bit registers
      - `S0` to `S31`: 32-bit registers
      - `H0` to `H31`: 16-bit registers
      - `B0` to `B31`: 8-bit registers

* p.204
  - `FPCR`: floating-point control register
  - `FPSR`: floating-point status register
  - `Z0` to `Z31`: `SVE` scalable vector registers
    - bit width: 128 bits to an `IMPLEMENTATION DEFINED` maximum no greater than 2048 bits
  - `P0` to `P15`: 16 `SVE` predicate registers
  - Note: The Maximum implemented `SVE` predicate length is the Maximum implemented `SVE` vector length divided by 8
