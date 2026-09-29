# Python API

This reference covers the `tirx_harness` Python application programming
interface (API). Signatures, defaults, and docstrings are generated from this
repository's source at documentation build time. Match the documentation
revision to your installed package.

Start with [Installation](../installation.md) and the runnable
[compiler analysis examples](../components/tools.md). Use the reference when
integrating checks, simulation, or generated-code inspection into your own loop.

| Task | Reference |
| --- | --- |
| Check synchronization and memory-access ordering | [Checkers and reports](checkers.md) |
| Execute a kernel on the CPU and compare outputs | [Numerical simulation](numsim.md) |
| Describe inputs, tensor maps, and comparisons | [Simulation inputs](inputs.md) |
| Extract generated code and compiler resource information | [Generated-code inspection](inspection.md) |

The reference focuses on callable tools and the objects their callers supply
or receive. Kernel authoring belongs to
[TIRx-lite](../components/TIRx-lite.md), remote execution to
[kcoral](../components/kcoral.md), and run preparation to
[Optimization Runs](../optimization-runs.md).

```{toctree}
:maxdepth: 1

checkers
numsim
inputs
inspection
```
