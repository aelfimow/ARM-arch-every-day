# Day 4

Notes reading [Doc 1](../Doc001.md).

* p.43
  - `AArch64`:
    - single instruction set: `A64`
  - `FEAT_SVE`
  - `FEAT_SME`
  - `AArch32`
    - `A32`
    - `T32`
    - in previous documents: ARM and Thumb® instruction sets
  - lowest Exception level that can access the register:
    - `<register_name>_EL0`
    - `<register_name>_EL1`
    - `<register_name>_EL2`
    - `<register_name>_EL3`

* p.44
  - Generic Interrupt Controller: `GIC`
  - Self-hosted debug
  - External debug

* p.45
  - Byte, Halfword, Word, Doubleword, Quadword
  - floating point data types:
    - Half-precision, Single-precision, Double-precision, BFloat16, 8-bit floating-point
  - IMPLEMENTATION DEFINED

* p.46
  - Note: Two consecutive 64-bit registers can be used as a 128-bit register
  - vector: one-dimensional array of elements of the data type specified in the instruction
  - `SIMD&FP` registers: `Vn` (n from 0 to 31)
  - B: 8 bits
  - H: 16 bits
  - S: 32 bits
  - D: 64 bits
  - 128-bit vector: `Vn.{2D, 4S, 8H, 16B}`
  - 64-bit vector: `Vn.{1D, 2S, 4H, 8B}`

* p.47
