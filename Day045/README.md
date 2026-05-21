# Day 45

Notes reading [Doc 1](../Doc001.md).

* p.328
  - mismatched attributes
  - Note: the terms location and memory location refer to any byte within the current coherency granule and are used interchangeably

* p.331
  - Note: Use of the `Armv8` synchronization primitives scales for multiprocessing system designs
  - Load-Exclusive
  - Store-Exclusive

* p.332
  - local Exclusives monitor
    - or: local monitor

* p.333
  - Local monitor state machine diagram
  - local monitor

* p.334
  - global monitor
  - Note: Lamport’s Bakery algorithm

* p.335
  - Note: The global monitor supports only a single outstanding exclusive access to shareable memory per `PE`

* p.336
  - Global monitor state machine diagram for `PE(n)` in a multiprocessor system

* p.337
