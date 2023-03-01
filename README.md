![Verified Software Toolchain](chain.jpg)

anonymous version, available online at https://github.com/anonymous-submissions-VST/VST-Iris-ICFP-2023.

## How to install:

To build parts relevant to "Updating a Verifier with Iris’s Concurrency Logic", run `make -j atomics`. Requires Iris v4.0.0 or greater.

See the following files for details on each section of the paper:

| Section | File |
| ----- | ---- |
| 2, 3.5 | veric/bi.v |
| 3.2 | veric/rmaps.v |
| 3.3 | msl/ghost_seplog.v, veric/own.v |
| 3.4 | veric/juicy_extspec.v, veric/SeparationLogicSoundness.v |
| 4.1 | veric/invariants.v |
| 4.2 | veric/fupd.v, veric/juicy_extspec.v, veric/SequentialClight.v |
| 5.1 | msl/sepalg.v |
| 5.2 | msl/predicates_sl.v, msl/knot_full_sa.v |
| 6.1 | atomics/SC_atomics_base.v, atomics/SC_atomics.v |
| 6.2 | atomics/general_atomics.v |
| 6.3 | atomics/verif_hashtable_atomic.v |
