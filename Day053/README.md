# Day 53

Notes reading [Doc 1](../Doc001.md).

* p.369
  - System instructions
    - `SYS`: System instruction
    - `SYSL`: System instruction with result
    - `SYSP`: 128-bit System instruction
    - `IC`: Instruction cache maintenance
    - `DC`: Data cache maintenance
    - `AT`: Address translation
    - `TLBI`: `TLB` Invalidate
  - Hint instructions
    - `NOP`: No operation
    - `YIELD`: Yield hint
    - `WFE`: Wait for event
    - `WFET`: Wait for event with timeout
    - `WFI`: Wait for interrupt
    - `WFIT`: Wait for interrupt with timeout
    - `SEV`: Send event
    - `SEVL`: Send event local
    - `HINT`: Unallocated hint
    - `DGH`: Data Gathering Hint
    - `CLRBHB`: Clear Branch History
    - `CHKFEAT`: Check Feature
    - `STSHH`: Store Shared Hint

* p.370
  - Barriers and `CLREX` instructions
    - `CLREX`: Clear Exclusives monitor
    - `DMB`: Data memory barrier
    - `DSB`: Data synchronization barrier
    - `ISB`: Instruction synchronization barrier
  - Speculation and synchronization barriers
    - `CSDB`: Consumption of Speculative Data Barrier
    - `ESB`: Error synchronization barrier
    - `PSB`: Profiling synchronization barrier
    - `PSSBB`: Physical Speculative Store Bypass Barrier
    - `SB`: Speculation Barrier
    - `SSBB`: Speculative Store Bypass Barrier
    - `TSB`: Trace Synchronization Barrier
    - `GCSB`: Guarded Control Stack Barrier

* p.371
