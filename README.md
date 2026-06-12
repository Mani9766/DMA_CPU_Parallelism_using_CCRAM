# DMA_CPU_Parallelism_using_CCRAM
Minimal STM32F407 project demonstrating DMA and CPU parallelism using CCMRAM for non‑blocking execution.

This repository contains a stripped‑down STM32F407 project created to investigate real‑time debugging challenges where interrupts stall under CubeIDE. The focus is on leveraging CCRAM (Core‑Coupled RAM) to enable parallel execution between DMA transfers and CPU tasks, ensuring non‑blocking performance.

Key highlights:
* Configures DMA and CPU to operate concurrently using CCMRAM.
* Provides a reproducible setup for debugging interrupt behavior in CubeIDE.
* Serves as a minimal test case, separate from larger projects, for sharing with peers and ST support.
* Useful for engineers exploring STM32F4 debugging, DMA concurrency, and memory optimization.
