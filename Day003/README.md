# Day 3

Notes reading [Doc 1](../Doc001.md).

* p.41
  - 64-bit Execution state: `AArch64`
  - 32-bit Execution state: `AArch32`
  - Note: The Base instruction set comprises the supported instructions other than the floating-point instructions
  - Application profile:
    - `A`
    - Virtual Memory System Architecture: `VMSA`
    - Memory Management Unit: `MMU`
  - Real-time profile
    - `R`
    - Protected Memory System Architecture: `PMSA`
    - Memory Protection Unit: `MPU`
    - optional `VMSA` based on an `MMU`
  - Microcontroller profile
    - `M`
    - `PMSA` based on an `MPU`
    - variant of the `T32` instruction set
  - instruction sets
    - `A64`
    - `A32`
    - `T32`

* p.42
  - Exception Link Registers: `ELR`
  - Process state: `PSTATE`
  - Link Register: `LR`
  - Application Program Status Register: `APSR`
  - Current Program Status Register: `CPSR`

* p.43
  - interprocessing: transfer control between the `AArch64` and `AArch32` Execution states
