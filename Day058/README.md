# Day 58

Notes reading [Doc 1](../Doc001.md).

* p.408
  - Instruction suffix
    - `B`: Unsigned byte
    - `H`: Unsigned halfword or half-precision floating-point
    - `W`: Unsigned word or single-precision floating-point
    - `D`: Unsigned doubleword or double-precision floating-point
    - `SB`: Signed byte
    - `SH`: Signed halfword
    - `SW`: Signed word

* p.418
  - Array vector/table load and store

* p.423
  - Arithmetic (immediate) instructions accept a 12-bit unsigned immediate value, optionally shifted left by 12 bits

* p.425
  - `PC`-relative address calculation
  - `ADRP`: Compute address of 4KB page at a `PC`-relative offset
  - `ADR`: Compute address of label at a `PC`-relative offset

* p.426
  - Bitfield move
  - Bitfield insert and extract

* p.429
