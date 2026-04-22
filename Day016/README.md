# Day 16

Notes reading [Doc 1](../Doc001.md).

* p.137
  - `FEAT_AFP`, Alternate floating-point behavior
  - `FEAT_EBF16`, `AArch64` Extended `BFloat16` behaviors
  - `FEAT_HCX`, Support for the `HCRX_EL2` register

* p.138
  - `FEAT_LPA2`, Larger physical address for 4KB and 16KB translation granules
  - `FEAT_LS64`, Support for 64-byte loads and stores without status

* p.139
  - `FEAT_LS64_ACCDATA`, Support for 64-byte `EL0` stores with status
  - Note: The meaning of any status being returned by the `ST64BV0`, `ST64BV` instructions is defined by the peripheral providing the response
  - `FEAT_LS64_V`, Support for 64-byte stores with status
  - `FEAT_MTE3`, `MTE` Asymmetric Fault Handling

* p.140
  - `FEAT_MTE_ASYM_FAULT`, Memory tagging asymmetric faults
  - `FEAT_PAN3`, Support for `SCTLR_ELx.EPAN`
  - `FEAT_PMUv3p7`, `Armv8.7` `PMU` extensions

* p.141
  - `FEAT_RPRES`, Increased precision of `FRECPE` and `FRSQRTE`
  - `FEAT_SPE_FnE`, Statistical Profiling inverse event filter
  - `FEAT_SPE_PBT`, Statistical Profiling previous branch target
  - `FEAT_SPEv1p2`, Statistical Profiling Extensions version 1.2

* p.142
  - `FEAT_WFxT`, `WFE` and `WFI` instructions with timeout
  - `FEAT_XS`, `XS` attribute

* p.143
