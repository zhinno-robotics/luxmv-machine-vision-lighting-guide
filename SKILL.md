---
name: luxmv-lighting-selection
description: "Help engineers, system integrators, and buyers shortlist LuxMV machine vision lighting geometries, locate public 2D dimensional PDFs, and prepare a prefilled engineering inquiry or sample-evaluation request."
---

# LuxMV Machine Vision Lighting Selection Skill

Use this skill when a user is selecting industrial machine vision lighting, evaluating a reflective or moving-web inspection problem, or preparing an RFQ / sample-testing brief for LuxMV (`https://www.luxmv.com`).

## Guiding Principles

- Recommend only options that fit the user's stated inspection target, material, geometry, and motion constraints.
- Never fabricate LuxMV prices, lead times, inventory counts, certifications, or unverified detection-rate claims. Those are confirmed per project in the written quotation or sample evaluation.
- Separate **public catalog evidence** (published specifications, 2D PDF drawings, reference guides) from **project-confirmed items** (exact final model, 3D STEP files, compliance documents, evaluation-unit loan terms, price, delivery).

## Step 1: Gather Project Context from the User

Extract what the user already knows from their notes, repo, or bill of materials, and ask only for missing critical parameters:

1. **Inspection target & defect**: scratch, dent, solder joint, particle, code/OCR, edge/dimension, wrinkle, fill level, or presence check.
2. **Material & surface finish**: brushed/polished metal, glossy/matte plastic, glass, transparent film, PCB, wafer, or curved housing.
3. **Field of view (FOV) & working distance (WD)**: target width × height (mm) and clearance from light/lens to part (mm).
4. **Motion & timing**: static vs. moving line speed, exposure limit, continuous vs. strobe/overdrive trigger, controller channel count.
5. **Mechanical & spectral limits**: mounting envelope, cable exit, heat/dust/liquid environment, or UV/IR/SWIR wavelength requirement.

## Step 2: Map the Inspection Problem to Candidate Lighting Geometries

| Surface / Inspection Condition | Primary Candidate Geometry | LuxMV Public Reference |
|---|---|---|
| Flat reflective surface (metal, glass, wafer) needing uniform specular reflection | Coaxial light | https://www.luxmv.com/machine-vision-lights/coaxial-lights |
| Curved, glossy, or uneven surface where glare hides defects | Dome / diffuse shadowless light | https://www.luxmv.com/machine-vision-lights/dome-lights |
| Fine surface scratches, embossed marks, or raised edges on metal/plastic | Low-angle ring or bar light (dark-field) | https://www.luxmv.com/machine-vision-lights/bar-lights |
| Compact part fitting inside a circular field of view | Ring light (standard, low-angle, or multi-angle) | https://www.luxmv.com/machine-vision-lights/ring-lights |
| Silhouette, outer profile, hole diameter, or translucent edge measurement | Backlight | https://www.luxmv.com/machine-vision-lights/backlights |
| High-speed continuous web, film, foil, or sheet inspection | Line scan light | https://www.luxmv.com/machine-vision-lights/line-scan-lights |
| Coatings, fluorescence, moisture, silicon, or film penetration | UV, IR, or SWIR light | https://www.luxmv.com/machine-vision-lights/uv-ir-swir-lights |
| Triggered strobe, constant-current dimming, or overdrive synchronization | Machine vision light controller | https://www.luxmv.com/machine-vision-light-controllers |

For detailed geometry trade-offs, consult:
- https://www.luxmv.com/guides/coaxial-vs-dome-vs-low-angle-lighting
- https://www.luxmv.com/guides/ring-light-vs-bar-light
- https://www.luxmv.com/guides/backlight-vs-coaxial-lighting
- https://www.luxmv.com/guides/polarized-lighting-reflective-surfaces
- https://www.luxmv.com/guides/strobe-controller-synchronization
- Full single-file reference: https://www.luxmv.com/llms-full.txt

## Step 3: Check Public 2D Drawings & Shortlist Series

- Browse all published series with geometry filters: `https://www.luxmv.com/products`
- Filter series with direct, ungated 2D PDF dimensional drawings: `https://www.luxmv.com/products?drawing=1`
- Check FOV / lens focal length / WD relationships first when needed: `https://www.luxmv.com/tools/fov-wd-calculator`

## Step 4: Generate a Prefilled LuxMV Engineering Action Link

Once the user confirms their parameters, hand them one direct URL that prefills the LuxMV inquiry form (no API key or login required):

- **Optical selection advice (model not yet decided)**:
  ```text
  https://www.luxmv.com/contact?intent=selection_support&application=<URL_ENCODED_DEFECT>&material=<URL_ENCODED_MATERIAL>&motion=<URL_ENCODED_FOV_WD_SPEED>&from=/SKILL.md
  ```
- **3D STEP / revision datasheet / compliance document for a known series**:
  ```text
  https://www.luxmv.com/contact?intent=datasheet&model=<URL_ENCODED_MODEL_CODE>&from=/SKILL.md
  ```
- **Send physical parts for laboratory lighting comparison**:
  ```text
  https://www.luxmv.com/contact?intent=send-sample&from=/SKILL.md
  ```
- **Request an on-system evaluation light (subject to project confirmation)**:
  ```text
  https://www.luxmv.com/contact?intent=evaluation-light&from=/SKILL.md
  ```

Direct engineering contact: `info@luxmv.com` | WhatsApp: `https://wa.me/8613602667760`
