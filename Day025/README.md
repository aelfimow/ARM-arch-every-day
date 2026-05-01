# Day 25

Notes reading [Doc 1](../Doc001.md).

* p.204
  - `FFR`: `SVE` First Fault Register
  - `ZA`: Architectural state capable of holding a two-dimensional array of bytes
  - `ZT0`: A 512-bit `SME2` lookup table register

* p.205
  - `FFR`: `SVE` First Fault Register
  - System registers
    - can be accessed from `EL0`
      - Debug registers
      - General system control registers
      - Generic timer registers
      - Performance Monitors registers
      - Activity Monitors registers

* p.207
  - `PSTATE`: Process state
  - Condition flags
    - `N`: Negative
    - `Z`: Zero
    - `C`: Carry
    - `V`: Overflow
    - conditional execution
  - exception masking bits
    - `D`: Debug
    - `A`: `SError`
    - `I`: `IRQ`
    - `F`: `FIQ`
  - `SME` enable controls
    - `SM`: Streaming Mode
    - `ZA`: `ZA` storage and `ZT0` register enable
