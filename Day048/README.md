# Day 48

Notes reading [Doc 1](../Doc001.md).

* p.347
  - SVE alias:
    - `EQ`: `NONE`
    - `NE`: `ANY`
    - `CS` or `HS`: `NLAST`
    - `CC` or `LO`: `LAST`
    - `MI`: `FIRST`
    - `PL`: `NFRST`
    - `VS`: `-`
    - `VC`: `-`
    - `HI`:
    - `LS`: `PLAST`
    - `GE`: `TCONT`
    - `LT`: `TSTOP`

* p.348
  - `Wn`: 32 bits, General-purpose register
  - `Xn`: 64 bits, General-purpose register
  - `WZR`: 32 bits, Zero register
  - `XZR`: 64 bits, Zero register
  - `WSP`: 32 bits, Current stack pointer
  - `SP`: 64 bits, Current stack pointer
  - no register named `W31` or `X31`
  - Procedure Call Standard for the `Arm` 64-bit Architecture

* p.349
  - Advanced `SIMD` and floating-point scalar register names
    - 8 bits: `Bn`
    - 16 bits: `Hn`
    - 32 bits: `Sn`
    - 64 bits: `Dn`
    - 128 bits: `Qn`
  - `SIMD` vector register names
    - 8 bits × 8 lanes: `Vn.8B`
    - 8 bits × 16 lanes: `Vn.16B`
    - 16 bits × 4 lanes: `Vn.4H`
    - 16 bits × 8 lanes: `Vn.8H`
    - 32 bits × 2 lanes: `Vn.2S`
    - 32 bits × 4 lanes: `Vn.4S`
    - 64 bits × 1 lane: `Vn.1D`
    - 64 bits × 2 lanes: `Vn.2D`
  - Vector register names with element index
    - 8 bits: `Vn.B[i]`
    - 16 bits: `Vn.H[i]`
    - 32 bits: `Vn.S[i]`
    - 64 bits: `Vn.D[i]`

* p.351
