---
Last Updated: 2026-04-25
Status: Seed – awaiting first research run
---

# AMD Ryzen AI Max+ 395 (Strix Halo)

> **How to update this file**
> Run the Copilot prompt `.github/prompts/research-amd-ryzen-ai-max-395.prompt.md`
> in VS Code / Codespace to automatically search the web and propose additions here.
> Commit every update with message: `research: <short description>`.

---

## Overview

The **AMD Ryzen AI Max+ 395** is AMD's flagship mobile APU in the **Strix Halo**
family, designed to bring workstation-class CPU and GPU performance — plus on-device
AI compute — to a single mobile chip package.

| Attribute | Value |
|-----------|-------|
| Codename | Strix Halo *(unverified; confirm in first research run)* |
| Architecture | Zen 5 (CPU) + RDNA 3.5 (iGPU) *(unverified; confirm in first research run)* |
| CPU Cores / Threads | 16 cores / 32 threads *(unverified; confirm in first research run)* |
| CPU Base / Boost | ~2.0 GHz base / up to 5.1 GHz boost[^1] |
| iGPU | Radeon 890M – 40 CUs (RDNA 3.5)[^1] |
| AI Engine (NPU) | XDNA 2 – up to 50 TOPS[^1] |
| Memory | LPDDR5X, up to 128 GB unified[^1] |
| Memory Bandwidth | Up to 256 GB/s[^1] |
| TDP Range | 45 W – 120 W (cTDP configurable) *(unverified; confirm in first research run)* |
| Process Node | TSMC 4 nm *(unverified; confirm in first research run)* |
| Announced | CES 2025 (January 2025)[^2] |
| General Availability | Early–Mid 2025 (OEM laptop launches)[^2] |

---

## AI Performance

| Metric | Value |
|--------|-------|
| NPU (XDNA 2) | 50 TOPS[^1] |
| Combined (CPU + GPU + NPU) | Not yet verified / no sourced figure captured |
| Microsoft Copilot+ PC | ✅ Eligible based on 50 TOPS NPU spec[^1] |

---

## Availability – Known Laptops

> This section will be expanded by the research agent as new products launch.

| OEM | Model | Expected / Launched |
|-----|-------|---------------------|
| ASUS | ROG Zephyrus G16 (2025) | Q1 2025[^2] |
| Lenovo | ThinkPad X1 Extreme (rumoured) | TBC |
| HP | Unknown | TBC |

---

## Benchmarks & Performance

> No verified benchmarks captured yet. Run the research prompt to populate this section.

---

## Open Questions

- [ ] Has AMD released a Ryzen AI Max 395 (non-plus) alongside the Max+ 395?
- [ ] What is the confirmed shipping TDP for specific OEM configurations?
- [ ] Are there any independent GPU benchmark comparisons vs. NVIDIA RTX 4070?
- [ ] Has AMD announced a refresh / successor to the Strix Halo line?

---

## Sources

[^1]: AMD official product page / specifications – https://www.amd.com/en/products/processors/laptop/ryzen-ai-max *(to be verified by research agent)*
[^2]: CES 2025 AMD press announcement – https://www.amd.com/en/newsroom *(to be verified by research agent)*

---

## Research History

| Date | Summary | Researcher |
|------|---------|-----------|
| 2026-04-25 | Seed file created with known-good baseline specs | Copilot Agent |
