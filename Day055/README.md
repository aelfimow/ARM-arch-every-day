# Day 55

Notes reading [Doc 1](../Doc001.md).

* p.376
  - addressing modes
    - base plus a scaled 12-bit unsigned immediate offset
    - base plus an unscaled 9-bit signed immediate offset
    - base plus a 64-bit register offset, optionally scaled
    - base plus a 32-bit extended register offset, optionally scaled
    - pre-indexed by an unscaled 9-bit signed immediate offset
    - post-indexed by an unscaled 9-bit signed immediate offset
    - `PC`-relative literal for loads of 32 bits or more

* p.378
  - addressing modes of load/store pair instructions
    - Base plus a scaled 7-bit signed immediate offset
    - Pre-indexed by a scaled 7-bit signed immediate offset
    - Post-indexed by a scaled 7-bit signed immediate offset

* p.380
