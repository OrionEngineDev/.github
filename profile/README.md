<div align="center">

# Orion Engine

**High-Performance, Data-Oriented 2D/3D Game Architecture**

![.NET 10](https://img.shields.io/badge/.NET-10.0-purple.svg)
![Graphics API](https://img.shields.io/badge/Graphics-Vulkan%201.4-red.svg)
![Architecture](https://img.shields.io/badge/Architecture-ECS%20%2F%20DOD-green.svg)
![Zero Alloc](https://img.shields.io/badge/GC-0_bytes%2Fframe-brightgreen.svg)

---

###  About the Organization

Orion Engine is an open-source development ecosystem building low-level, high-performance game engine technology in modern C# (.NET 10) and Vulkan 1.4. We focus on strict Data-Oriented Design (DOD), zero-allocation runtimes, and GPU-driven rendering pipelines.

</div>

---

### Core Architectural Pillars

| Technology | Highlight Features |
| :--- | :--- |
| **Vulkan 1.4 Graphics** | GPU-driven compute culling, Multi-Draw Indirect, Dynamic Rendering, and Synchronization2. |
| **Dual-Storage ECS** | Generational indexing, Roslyn source-generated SoA buffers, and explicit SIMD vectorization. |
| **Physics Subsystem** | End-to-end Jolt Physics integration with mesh-derived static colliders and deferred execution. |
| **Zero-Allocation Core** | Value-type design using `Span<T>`, `ref struct`, and memory-mapped custom binary formats. |
| **Native Input** | Low-latency Raw HID transport layer with native haptics and adaptive triggers. |

---

### Ecosystem & Repositories

* **Orion Cook** – Offline asset compilation CLI for textures (`.ortex`), meshes (`.ormesh`), and materials (`.ormat`).
