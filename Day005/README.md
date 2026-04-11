# Day 5

Notes reading [Doc 1](../Doc001.md).

* p.47
  - `.F`: Floating-point number (of n bits)
  - `.I`: Signed or unsigned integer (of n bits)
  - `.P`: Polynomial over {0, 1} (of degree less than n)
  - `.S`: Signed integer (of n bits)
  - `.U`: Unsigned integer (of n bits)

* p.48
  - Note for `AArch32` state: a pair of even and following odd numbered doubleword registers can be concatenated and treated as a single quadword register

* p.49
  - Effective `SVE` vector length

* p.50
  - `B`: 8 bits
  - `H`: 16 bits
  - `S`: 32 bits
  - `D`: 64 bits
  - `Q`: 128 bits

* p.51
  - Arm alternative half-precision format
  - Note: `BFloat16` is not a half-precision floating-point format

* p.52ff
  - quiet `NaN`
  - signaling `NaN`
  - default `NaN`

* p.56
  - `BFloat16` format

* p.57
  - `FP8` formats
    - `OFP8 E4M3` format
    - `OFP8 E5M2` format

* p.60
  - Note: An out of range fixed-point result is saturated to the destination size

* p.61
  - see Procedure Call Standard for the Arm 64-bit Architecture
  - Default `NaN` behavior

* p.62
  - `FPCR`: Floating-point Control Register
  - `FPSCR`: Floating-Point Status and Control Register
  - `FPSR`: Floating-point Status Register
  - Note: Single elements are also referred to as scalar elements
