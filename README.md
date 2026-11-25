# Machine Vision Lighting Selection Guide & Evaluation Templates

[![Website](https://img.shields.io/badge/Website-luxmv.com-0f766e)](https://www.luxmv.com)
[![Agent Skill](https://img.shields.io/badge/Agent_Skill-SKILL.md-0f172a)](./SKILL.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](./LICENSE)

Open engineering reference, lighting geometry decision matrices, sample-evaluation worksheet, and AI buyer-agent selection skill (`SKILL.md`) maintained by **[LuxMV](https://www.luxmv.com)** for machine vision engineers, OEM machine builders, and system integrators.

> **Engineering boundary**: Public specifications, geometry comparisons, and worksheets in this repository are intended for candidate shortlisting and structured RFQ preparation. Final model code, wavelength, working distance, controller mode, documentation, price, and lead time must be confirmed through project-specific review and sample validation.

---

## 1. Lighting Geometry Selection Matrix

Choose illumination geometry from the **material, surface finish, defect orientation, and motion** rather than brightness alone:

| Inspection Condition / Surface | Primary Candidate Geometry | Public Reference & Model Series |
|---|---|---|
| Flat reflective surface (metal, glass, silicon wafer) requiring uniform specular reflection | **Coaxial Light** | [Coaxial Lights](https://www.luxmv.com/machine-vision-lights/coaxial-lights) |
| Curved, glossy, or uneven surface where glare hides defects | **Dome / Diffuse Shadowless Light** | [Dome Lights](https://www.luxmv.com/machine-vision-lights/dome-lights) |
| Fine surface scratches, embossed marks, or raised edges | **Low-Angle Ring or Bar Light (Dark-Field)** | [Bar Lights](https://www.luxmv.com/machine-vision-lights/bar-lights) · [Ring Lights](https://www.luxmv.com/machine-vision-lights/ring-lights) |
| Silhouette, outer contour, hole diameter, or translucent edge measurement | **Backlight** | [Backlights](https://www.luxmv.com/machine-vision-lights/backlights) |
| High-speed continuous web, plastic film, foil, or sheet inspection | **Line Scan Light** | [Line Scan Lights](https://www.luxmv.com/machine-vision-lights/line-scan-lights) |
| Fluorescence, coatings, moisture, silicon, or material penetration | **UV / IR / SWIR Light** | [UV, IR & SWIR Lights](https://www.luxmv.com/machine-vision-lights/uv-ir-swir-lights) |
| Trigger synchronization, constant-current dimming, or strobe overdrive | **Light Controller** | [Light Controllers](https://www.luxmv.com/machine-vision-light-controllers) |

### Key Comparison Guides

- [Lighting Selection Method](https://www.luxmv.com/guides/lighting-selection-method) — Geometry → Pattern → Wavelength → Filter order of evaluation.
- [Coaxial vs. Dome vs. Low-Angle Lighting](https://www.luxmv.com/guides/coaxial-vs-dome-vs-low-angle-lighting) — Trade-offs on reflective and curved surfaces.
- [Ring Light vs. Bar Light](https://www.luxmv.com/guides/ring-light-vs-bar-light) — Part-size envelope and directional contrast criteria.
- [Backlight vs. Coaxial Lighting](https://www.luxmv.com/guides/backlight-vs-coaxial-lighting) — Silhouette vs. specular surface inspection.
- [Polarized Lighting for Reflective Surfaces](https://www.luxmv.com/guides/polarized-lighting-reflective-surfaces) — Glare suppression boundaries.
- [Strobe Controller Synchronization](https://www.luxmv.com/guides/strobe-controller-synchronization) — Trigger timing, pulse width, and exposure alignment.

---

## 2. Included Engineering Assets

- **[`SKILL.md`](./SKILL.md)** — Ready-to-use Agent Skill for Claude Code, Cursor, and engineering assistants to shortlist candidate illumination geometries and build prefilled inquiry links.
- **[`docs/lighting-evaluation-record.md`](./docs/lighting-evaluation-record.md)** — Reproducible sample-evaluation record and RFQ input checklist.
- **[`docs/supplier-selection-checklist.md`](./docs/supplier-selection-checklist.md)** — Technical procurement checklist separating public catalog evidence from project-confirmed terms.
- **[`llms.txt`](./llms.txt)** — Machine-readable index of LuxMV public engineering resources.

---

## 3. Online Engineering Tools & Ungated 2D Drawings

- **Product Catalog & Geometry Filter**: https://www.luxmv.com/products
- **Ungated 2D Dimensional PDFs**: https://www.luxmv.com/products?drawing=1
- **FOV & Working-Distance Calculator**: https://www.luxmv.com/tools/fov-wd-calculator
- **RFQ Lighting Selection Brief Builder**: https://www.luxmv.com/tools/lighting-selection-brief
- **Application Reference Library (12 Industries/Tasks)**: https://www.luxmv.com/applications

---

## Contact

- Website: https://www.luxmv.com
- Engineering & RFQ Contact: https://www.luxmv.com/contact
- Email: info@luxmv.com
