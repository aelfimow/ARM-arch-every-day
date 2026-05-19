# Day 43

Notes reading [Doc 1](../Doc001.md).

* p.315
  - All memory-mapped peripherals defined in the Arm architecture must be little-endian

* p.316
  - Normal memory
  - Note: Write speculation that is visible to other observers is prohibited for all memory types

* p.317
  - Inner and Outer Shareability domains

* p.319
  - two conceptual levels of cache:
    - inner cache
    - outer cache
  - Note: `L1` cache is the level closest to the `PE`

* p.320
  - Device memory
    - `G` or `nG`: Gathering
    - `R` or `nR`: Reordering
    - `E` or `nE`: Early Write Acknowledgement
  - `Armv8` Device memory types:
    - Device-`nGnRnE`
    - Device-`nGnRE`
    - Device-`nGRE`
    - Device-`GRE`

* p.322
  - Note: In general, making a translation table walk to any Device memory type is the result of a programming error

* p.323
