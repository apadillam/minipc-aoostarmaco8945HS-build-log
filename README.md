# 🚀 High-Performance Mini PC Lab (AOOSTAR MACO 8945HS Precision Build & Thermal Optimization)

Detailed documentation of the construction, thermal optimization, and performance validation of the **AOOSTAR MACO** (Ryzen 9 8945HS).

## 🎯 Motivation and Purpose
The goal of this project is to architect a compact yet uncompromising development and sandbox environment for personal/professional projects and advanced technical experimentation.
* **High-Performance Storage:** Implementing a reliable dual-NVMe array to support multi-OS workflows and high-speed data processing.
* **Thermal Efficiency** Thermal Repasting of processor, and custom selection of heatsinks for ideal cooling in small-form-factor (SFF) environments.
* **System Stability:** Validating the Ryzen 9 8945HS performance under sustained workloads and verifying peak SSD read/write speeds.
* **Scalability:** Designing the system to remain relevant for several years, ensuring a clear path for hardware scalability as requirements evolve.
* **Documentation** Document my efforts and shortcomings being this my first major hardware enthusiast project in the year 2026 on an inflated global PC hardware market.

## 💻 Current System Configuration (summarized specs sheet)
*Summary of the hardware currently integrated and operational.*

| Component | Specification | Details / Cooling |
| :--- | :--- | :--- |
| **Processor** | AMD Ryzen 9 8945HS (8C/16T) | Integrated Radeon 780M and NPU / Liquid Metal (Factory) |
| **RAM** | 32GB DDR5 Kingston Fury 5600MT/s | Dual Channel (2x16GB) |
| **System Drive A (2TB)** | Kingston KC30000 NVMe Gen4 | DRAM - Dual Sided /Generic Aluminum Heatsink (included with MACO, underside doesn't allow for extra space) |
| **System Drive B (1TB)** | NVMe Gen4 | Be Quiet MC1 Pro M.2 |

**'Drive A'** has Windows 11 installed.
**'Drive B'** has Linux Mint installed. Planning to partition and install Linux Pop!_OS. 

## 📈 Next Steps & Scalability
* **Phase 1 (Hardware Thermal Optimization):**
    * Upgrade generic heatsink on **KC3000 ("Drive A")** for a 4mm solid copper heatsink and high-performance thermal pads to mitigate the identified **72°C thermal peak**.
    * Evaluate optimal slot placement for airflow; if swapping with **"Drive B"**, assess clearance for **BeQuiet** vs. **Thermalright** heatsinks due to chassis restrictions.
    * Determine the feasibility of repasting the processor with **Noctua NT-H1**.

* **Phase 2 (Validation & Benchmarking):**
    * Execute post-installation stress tests (**Cinebench R23 / CrystalDiskMark**) to verify if temperatures stabilize below 60°C under load.
    * Document the **Delta-T** (temperature difference) across both NVMe drives to measure cooling efficiency.

* **Phase 3 (Partitioning & Pop!_OS Deployment):**
    * Partition **"Drive B"** to allocate dedicated space for a third environment.
    * Install **Pop!_OS** and configure the bootloader for a seamless triple-boot workflow.

* **Phase 4 (System Optimization):**
    * Fine-tune BIOS fan curves to achieve the ideal balance between acoustic comfort and thermal performance.

* **Future Scalability:**
    * Potential RAM upgrade to **64GB DDR5** for intensive virtualization or datasets.
    * Research external **eGPU** integration via the **OCuLink** interface for advanced graphical/AI workloads.

---
*Maintained by apadillam | Last updated: May 8th 2026*
---

