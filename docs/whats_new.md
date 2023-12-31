---
title: Known issues with the LUMI software stacks
hide:
- navigation
---

# What's new in the LUMI software stack

## Release 20231215

-   [rocm/5.6.1](r/rocm/index.md) and [amd/5.6.1](a/amd/index.md) 
    modules installed in `CrayEnv` and `LUMI/23.09 partition/G`.
-   Updated user-installable recipes for Java, including [Java/21](j/Java/index.md).
-   User-installable recipe for the [UNICORE UFTP client](u/unicore-uftp/index.md).
-   User-installable recipe for the installation of [SIESTA (CPU version)](s/Siesta/index.md)


## Release 20231208

-   [GROMACS](g/GROMACS/index.md) with [hipSYCL](h/hipSYCL/index.md) and dependencies, including a version with heFFT.
-   [nvtop](n/nvtop/index.md)
-   Extra user-installable version of [SCOTCH](s/SCOTCH/index.md) (64-bit integers)
-   Update of the [aws-ofi-rccl plugin](a/aws-ofi-rccl/index.md)
-   Fix for [ELPA](e/ELPA/index.md)
-   Improved [Open MPI](o/OpenMPI/index.md) with [OSU micro-benchmarks](o/OSU-Micro-Benchmarks/index.md)
    as test code and user-installable adapted versions of [lumi-CPEtools](l/lumi-CPEtools/index.md)
    for checking task and thread distribution and pinning.


## Release 20231121

-   Bug fixes for the module view
-   More container recipes


## Release 20231116

-   Initial release of the `LUMI/23.09` central software stack, including a first
    selection of user-installable build recipes
-   Initial support for creating modules that ease working with containers
    provided on LUMI.
-   New version of the [cotainr](c/cotainr/index.md) module
-   Bug fix for the `lumi-ldap-projectinfo` command.
