# The Silis Foundation

The Silis Foundation is an open-source hardware and digital design research organization behind **Silis**, an Integrated Development Environment (IDE) engineered for the complete RTL-to-GDSII ASIC silicon design flow. 

Beyond EDA toolchain unification, the foundation conducts empirical digital design research, microarchitectural benchmarks, and hardware/software co-design—exploring spatial compute fabrics (such as systolic tensor arrays), custom RISC-V coprocessor extensions (GEMMrv32), and bare-metal runtime infrastructures for their own open silicon.

---

### Core Research & Silicon Projects

- **[Silis IDE](https://github.com/The-Silis-Foundation/silis)** ([Latest Release](https://github.com/The-Silis-Foundation/silis/releases)) — Flagship modular open-source RTL-to-GDSII ASIC design environment integrating Yosys, OpenROAD, OpenSTA, and Magic VLSI with native C++ layout parsing engines bound via pybind11. Standalone Linux AppImage binaries available.
- **[GEMMrv32](https://github.com/The-Silis-Foundation/GEMMrv32)** — Spatial 8×8 systolic-array coprocessor integrated into the NEORV32 RISC-V Custom Functions Subsystem (CFS) for accelerated matrix compute with ping-pong tiling registers.
- **[PulseGEMM](https://github.com/JeromeAntonyRobin/PulseGEMM)** — 16×16 INT8 systolic compute accelerator on Microchip PolarFire SoC with 64-bit AXI4-DMA and Linux UIO drivers (256 MACs/cycle).
- **[DOOM on GEMMrv32](https://github.com/JeromeAntonyRobin/DOOM-on-GEMMrv32)** — Bare-metal OS-less port of DOOM offloading 3D transformation matrices directly to systolic hardware coprocessors.
- **[GEMMrvStudio](https://github.com/The-Silis-Foundation/GEMMrvStudio)** — Telemetry, simulation profiling, and verification environment for custom RISC-V coprocessors.

---

### Research Focus & Competencies
- **Physical Design Automation**: Sub-millisecond DEF layout decoding, interactive clock-tree visualization, and automated tapeout pipelines.
- **Custom Silicon Architectures**: Domain-specific ISA coprocessor extensions, custom execution units, and spatial PE grids.
- **Hardware/Software Co-Design**: Bare-metal runtimes, userspace DMA interfaces, and zero-overhead memory streaming for edge silicon.
