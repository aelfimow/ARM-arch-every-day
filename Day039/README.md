# Day 39

Notes reading [Doc 1](../Doc001.md).

* p.300
  - `DMB` and `DSB` instructions domains:
    - Full system
    - Outer Shareable
    - Inner Shareable
    - Non-shareable
  - Note: The distinction between Full system and Outer Shareable is applicable only for Normal Non-cacheable memory accesses and Device memory accesses
  - Note: This form of a `DMB` or `DSB` instruction can be described as a load-load/store barrier

* p.301
  - `RCsc`: Release Consistency sequentially consistent model
  - `RCpc`: Release Consistency processor consistent model

* p.303
  - Note: The LoadLOAcquire/StoreLORelease instructions can remove the requirement to use the explicit `DMB` instruction
  - `GCSB`: Guarded Control Stack Barrier
      - instruction
      - generates a `GCSB` event

* p.304
  - tag: main memory address information
  - cache line
  - cache hit
  - cache misses
  - potential problems
    - memory accesses can occur at times other than when the programmer would expect them
    - a data item can be held in multiple physical locations

* p.305
