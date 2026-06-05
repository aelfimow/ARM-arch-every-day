# Day 60

Notes reading [Doc 1](../Doc001.md).

* p.439
  - three forms of SIMD instructions
    - `Wide`: suffix `W`
    - `Long`: suffix `L`
    - `Narrow`: suffix `N`

* p.440
  - Note: This is referred to as a lane set specifier
  - Floating-point move (register)
  - Floating-point move (immediate)

* p.442
  - Floating-point to integer or fixed-point conversion instructions

* p.443
  - Convert from integer or fixed-point to floating-point
  - Integer or fixed-point to floating-point conversion instructions
  - Floating-point round to integral value
  - Floating-point round to an integer of the same size as the register

* p.444
  - Floating-point round to 32-bit or 64-bit integer
  - Floating-point multiply-add

* p.445
  - Floating-point arithmetic (one source)
  - Floating-point arithmetic (two sources)
  - Floating-point minimum and maximum

* p.446
  - Floating-point comparison
  - Note:
    - The `NZCV` flags in the `FPSR` are associated with `AArch32` state.
    - The `A64` floating-point comparison instructions do not change the Condition flags in the `FPSR`.
  - Floating-point comparison instructions
  - Floating-point conditional select

* p.447
  - `SIMD` move instructions
  - `SIMD` arithmetic instructions

* p.450
  - `SIMD`compare instructions
  - `SIMD`widening and narrowing arithmetic

* p.451
  - `SIMD` unary arithmetic

* p.453
  - `SIMD` by element arithmetic instructions

* p.454
  - `SIMD` permute instructions
  - `SIMD` immediate instructions

* p.455
  - `SIMD` shift (immediate) instructions

* p.456
  - `SIMD` floating-point conversion instructions
  - `SIMD` integer conversion instructions

* p.457
