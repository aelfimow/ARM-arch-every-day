# Day 26

Notes reading [Doc 1](../Doc001.md).

* p.208
  - `MRS` instruction
  - `MSR` instruction
  - Special-purpose register
    - `NZCV`
    - `DAIF`
    - `SVCR`
    - `SSBS`
    - `DIT`
    - `TCO`

* p.209
  - `SMSTART` and `SMSTOP` instructions
    - change more efficiently `PSTATE.{SM, ZA}`

* p.210
  - `SVE` scalable vector registers: `Z0` to `Z31`
    - smallest architecturally defined maximum length is 128 bits
    - largest architecturally defined maximum length is 2048 bits
  - `SVL`: Effective Streaming SVE vector length
    - all powers of two from 128 to 2048 bits
  - `NSVL`: Effective Non-streaming SVE vector length

* p.211
  - `NSVL` set is all powers of two from 128 to 2048 bits
  - `VL`: Effective `SVE` vector length

* p.212
