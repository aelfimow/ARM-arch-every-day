# Day 56

Notes reading [Doc 1](../Doc001.md).

* p.380
  - Load/store non-temporal pair
    - Base plus a scaled 7-bit signed immediate offset
  - `LDNP`: Load Non-temporal Pair
  - `STNP`: Store Non-temporal Pair
  - `LDTNP`: Load Non-temporal Pair
  - `STTNP`: Store Non-temporal Pair

* p.381
  - Load/store unprivileged
    - Base plus an unscaled 9-bit signed immediate offset
  - Single-copy atomic 64-byte load/store

* p.383
  - Load-Exclusive/Store-Exclusive instructions

* p.384
  - Load-Exclusive/Store-Exclusive unprivileged

* p.385
  - Non-exclusive Load-Acquire and Store-Release instructions

* p.386
  - Load-Acquire/Store-Release unprivileged
  - LoadLOAcquire/StoreLORelease instructions

* p.387
  - Load/store scalar `SIMD` and floating-point register
    - Base plus a scaled 12-bit unsigned immediate offset
    - Base plus unscaled 9-bit signed immediate offset
    - Base plus 64-bit register offset, optionally scaled
    - Base plus 32-bit extended register offset, optionally scaled
    - Pre-indexed by an unscaled 9-bit signed immediate offset
    - Post-indexed by an unscaled 9-bit signed immediate offset
    - `PC`-relative literal for loads of 32 bits or more

* p.388
  - Load/store scalar `SIMD` and floating-point register
  - Load/store `SIMD` and floating-point register pair

* p.389
  - Load/store unprivileged `SIMD` and floating-point register pair
  - Load/store `SIMD` and floating-point non-temporal pair

* p.390
  - Load/store unprivileged `SIMD` and floating-point non-temporal pair

* p.392
  - Prefetch memory instructions
    - Base register with no offset
    - Base plus a scaled 12-bit unsigned immediate offset or base plus an unscaled 9-bit signed immediate offset
    - Base plus a 64-bit register offset (can be optionally scaled by 8-bits)
    - Base plus a 32-bit extended register offset (can be optionally scaled by 8-bits)
    - `PC`-relative literal

* p.393
  - `PRFM`:
    - Prefetch memory (register offset)
    - Prefetch memory (immediate offset)
    - Prefetch memory (PC-relative offset)
  - `PRFUM`: Prefetch memory (unscaled offset)
  - `RPRFM`: Range prefetch memory

* p.394
  - Atomic integer memory operations

* p.395
  - Atomic floating-point memory operations

* p.396
  - Unprivileged atomic memory operations

* p.397
  - Swap operations
    - `SWP`: Swap SWP
    - `SWPB`: Swap byte
    - `SWPH`: Swap halfword
    - `SWPP`: Swap quadword

* p.398
  - Compare and Swap operations
  - `CAS`: Compare and swap
  - `CASB`: Compare and swap byte
  - `CASH`: Compare and swap halfword
  - `CASP`: Compare and swap pair
  - Read-Check-Write instructions

* p.399
  - Memory Tagging Extension Tag load instructions

* p.400
