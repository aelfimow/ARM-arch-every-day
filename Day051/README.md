# Day 51

Notes reading [Doc 1](../Doc001.md).

* p.363
  - perform a nested subroutine call
    - `BLR`
    - `BL`
  - perform a control transfer
    - `BR`
    - `B`
  - Conditional branch instructions

* p.365
  - `B`: Branch unconditionally, ±128MB
  - `BL`: Branch with link, ±128MB

* p.366
  - `BLR`: Branch with link to register
  - `BR`: Branch to register
  - `RET`: Return from subroutine
  - Direct branch instructions
  - Indirect branch instructions
    - Branch with link to register, with pointer authentication

* p.367
  - `BRK`: Breakpoint Instruction
  - `HLT`: Halt Instruction
  - `HVC`: Generate exception targeting Exception level 2
  - `SMC`: Generate exception targeting Exception level 3
  - `SVC`: Generate exception targeting Exception level 1
  - `ERET`: Exception return using current `ELR` and `SPSR`

* p.368
  - `ERETAA`, `ERETAB`: Exception return, with pointer authentication
