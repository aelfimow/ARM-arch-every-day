# Day 62

Notes reading [Doc 1](../Doc001.md).

* p.465
  - `FEAT_SHA512`
  - Note:
    - Implementation of `FEAT_SHA512` does not require the implementation of the `AES` instructions and the 64-bit
    - Implementation of `FEAT_SHA512` does not require the implementation of the 64-bit polynomial variants of the `PMULL` instructions
  - `SHA512H`: `SHA512` Hash update part 1
  - `SHA512H2`: `SHA512` Hash update part 2
  - `SHA512SU0`: `SHA512` Schedule Update 0
  - `SHA512SU1`: `SHA512` Schedule Update 1
  - `FEAT_SHA3`

* p.466
  - `FEAT_SM3`
  - `SM3` hash algorithm, the standard Chinese hash algorithm
  - Note:
    - The `SM3` instruction names refer to intermediate variables defined as part of the `SM3` Cryptographic Hash Algorithm specification
  - `M3SS1`: `SM3` `SS1` calculation
  - `M3TT1A`: `SM3` `TT1` calculation
  - `M3TT1B`: `SM3` `TT1` calculation
  - `M3TT2A`: `SM3` `TT2` calculation
  - `M3TT2B`: `SM3` `TT2` calculation
  - `M3PARTW1`: `SM3` `PARTW` calculation
  - `M3PARTW2`: `SM3` `PARTW` calculation
