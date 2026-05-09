# Day 33

Notes reading [Doc 1](../Doc001.md).

* p.251
  - formal concurrency model

* p.252
  - Memory Location
  - Tag Location: 4-bit `MTE` Allocation Tag
  - Effects
    - Register Effects
    - Memory Effects
    - Explicit Memory Effects
    - Implicit Translation Table Descriptor (`TTD`) Memory Effects
    - Hardware Update Effects
    - Tag Memory Effects
    - Implicit Instruction Memory Read Effects
    - Barrier Effects
    - Instruction Fetch Barrier Effects
    - Conditional Branching, and Intrinsic Branching Effects
    - Fault Effects, Exception Entry, and Exception Return Effects
    - `TLBI` Effects, Completed `TLBI` Effects and Invalidation Scopes
    - `TLBUncacheable` Effects
    - `DC CVAU` Effects
    - `IC` Effects, Completed `IC` Effects
    - Empty Effects

* p.253
  - Note: Prefetch memory instructions do not generate any Explicit Memory Effects

* p.254
