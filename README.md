# Didgeridoo Practice Mute

> [!IMPORTANT]
>
> ## Design concept / pre-prototype
>
> **This repository currently describes a design idea and preliminary construction concept.**
>
> No physical prototype of this exact design has been fully tested or acoustically characterized yet. Dimensions, materials and construction details are therefore **preliminary design values** and may change after practical testing.
>
> The next stage of the project will include:
>
> * construction of one or more prototypes
> * subjective evaluation of playing feel and back pressure
> * sound-level measurements with and without the mute
> * comparison of different outlet diameters
> * testing of different absorber materials
> * frequency-spectrum measurements where possible
> * optimization of dimensions based on the results
>
> **Experimental results and revised blueprints will be published in this repository.**
>
> This should currently be considered **Version 0.x — Concept / Pre-Prototype**, not a finished or validated design.

A simple DIY acoustic mute concept for quieter didgeridoo practice.

The goal of this project is to reduce the perceived volume of a didgeridoo while keeping airflow and back pressure as natural as reasonably possible.

Instead of simply closing the bell end of the instrument, the proposed design uses an **expansion chamber, a perforated inner tube and acoustic absorption material**.

The design is intended for quiet practice at home, especially when normal didgeridoo volume would disturb neighbours or other people nearby.

> This is an experimental DIY acoustic concept. It will not make a didgeridoo completely silent.

---

## Current Project Status

**Status: Design Idea / Pre-Prototype**

Current version:

**v0.1-concept**

The present construction plan is based on acoustic principles and engineering estimates.

It has **not yet been experimentally validated**.

Practical tests will follow.

Measured values will replace estimates as soon as prototype data becomes available.

---

## Features Intended by the Design

* Passive acoustic construction
* No electronics required
* Low-cost materials
* Standard plumbing pipe components
* Replaceable bell adapter
* Adjustable exhaust diameter
* Relatively low additional back pressure
* Reduction of higher harmonics and buzzing noise
* Adaptation to different didgeridoo bell diameters
* Easy modification for experimental testing

---

## How It Is Intended to Work

A didgeridoo produces strong low-frequency sound together with many harmonics.

Simply blocking the bell reduces volume, but also greatly increases back pressure and changes the behaviour of the instrument.

The proposed design therefore uses three acoustic stages:

1. **Expansion chamber**

   Air leaving the didgeridoo first enters a larger chamber.

2. **Perforated inner tube**

   The airflow then continues through a perforated tube.

   Acoustic energy can pass through the holes into the surrounding absorber material.

3. **Acoustic absorber**

   Open-cell acoustic foam or PET felt is intended to absorb part of the acoustic energy, especially at higher frequencies.

The exhaust remains open so that airflow can continue through the system.

This operating principle is plausible, but its effectiveness in this exact configuration still needs to be experimentally verified.

---

# Preliminary Blueprint

## Proposed Main Dimensions

| Part                       | Preliminary specification |
| -------------------------- | ------------------------- |
| Main housing               | DN125 PP/PVC/HT pipe      |
| Housing length             | 400 mm                    |
| Typical outside diameter   | approx. 125 mm            |
| Bell adapter               | approx. 70–105 mm         |
| Didgeridoo insertion depth | approx. 40 mm             |
| Free expansion chamber     | approx. 80 mm             |
| Absorber section           | approx. 230 mm            |
| Outlet section             | approx. 50 mm             |
| Inner tube                 | approx. Ø50 mm            |
| Inner tube length          | approx. 250 mm            |
| Perforation                | Ø6 mm                     |
| Hole spacing               | approx. 15 mm             |
| Absorber thickness         | approx. 20–25 mm          |
| Initial test outlet        | Ø50 / Ø40 / Ø32 mm        |
| Total length               | approx. 440 mm            |

**Important:** These dimensions are preliminary starting values for prototype construction. They are not yet experimentally optimized.

---

## Proposed Cross Section

```text
 DIDGERIDOO                         PRACTICE MUTE

       Bell
        /\
       /  \         80 mm          230 mm               50 mm
======/    \====================================================
      \    / |                  ___________________
       \__/  |                 /                   \
             |                |   Acoustic foam     |
      EVA    |                |  ################   |
      ring   |                |  # ............ #   |
             |                |  # : Ø50 tube  : #---+----> OUT
             |                |  # :perforated : #   |
             |                |  # ............ #   |
             |                |  ################   |
             |                 \___________________/
===============================================================
             <----------- DN125 / 400 mm -------------------->
```

---

# Proposed Materials

| Part            | Description                                        |
| --------------- | -------------------------------------------------- |
| Main tube       | DN125 HT/PP/PVC pipe                               |
| Rear cap        | DN125 end cap                                      |
| Inner tube      | Ø50 mm PP/PVC pipe                                 |
| Bell adapter    | EVA foam, EPDM or similar                          |
| Absorber        | PET acoustic felt or open-cell acoustic foam       |
| Protective mesh | Nylon or stainless steel mesh                      |
| Sealant         | Neutral silicone, polyurethane adhesive or similar |
| Outlet insert   | PVC/PP disc or pipe reducer                        |

Loose glass wool or mineral wool should not be used because fibres could potentially enter the airflow.

---

# Bell Adapter Concept

The didgeridoo should not be clamped directly against hard plastic.

A flexible EVA or EPDM adapter is proposed to provide:

* sealing
* mechanical isolation
* protection of the instrument
* adaptation to different bell sizes

Preliminary adapter dimensions:

| Didgeridoo Bell | Proposed Adapter Hole |
| --------------: | --------------------: |
|           70 mm |              66–68 mm |
|           80 mm |              76–78 mm |
|           90 mm |              86–88 mm |
|          100 mm |              96–98 mm |

These dimensions will need to be verified experimentally with different bell shapes and materials.

---

# Perforated Inner Tube Concept

Initial prototype specification:

* outside diameter: approximately 50 mm
* length: approximately 250 mm
* perforated length: approximately 200 mm
* hole diameter: 6 mm
* hole spacing: approximately 15 mm
* staggered rows

Example:

```text
   o     o     o
      o     o
   o     o     o
      o     o
   o     o     o
```

Approximately 80–120 holes are proposed.

For reference:

```text
Ø50 mm tube area ≈ 1960 mm²

100 × Ø6 mm holes ≈ 2830 mm²
```

This should keep the perforations from becoming a major airflow restriction, but actual pressure behaviour still needs to be measured.

---

# Adjustable Outlet — Experimental Values

Three outlet sizes are proposed for the first prototype tests:

| Test   | Outlet | Expected behaviour                            |
| ------ | -----: | --------------------------------------------- |
| OPEN   | Ø50 mm | lowest restriction                            |
| MEDIUM | Ø40 mm | intermediate                                  |
| QUIET  | Ø32 mm | more attenuation, probably more back pressure |

These descriptions are **expectations only**.

The actual relationship between attenuation and back pressure will be measured during prototype testing.

---

# Proposed Assembly

1. Cut the DN125 housing to approximately **400 mm**.
2. Prepare the front plate for the didgeridoo bell adapter.
3. Cut the Ø50 mm inner tube to approximately **250 mm**.
4. Drill Ø6 mm holes over approximately 200 mm.
5. Wrap the perforated section with thin protective mesh.
6. Install approximately 20–25 mm of acoustic absorber.
7. Mount the inner tube centrally inside the main housing.
8. Leave approximately **80 mm of free expansion space** behind the didgeridoo bell.
9. Install the rear cap.
10. Install a replaceable or adjustable outlet.
11. Ensure that absorber material cannot enter the airflow.
12. Begin experimental testing with the largest outlet.

---

# Planned Prototype Tests

The first practical tests should compare:

```text
Test A: no mute
Test B: Ø50 mm outlet
Test C: Ø40 mm outlet
Test D: Ø32 mm outlet
```

For each configuration the following should be documented:

* perceived volume
* playing comfort
* back pressure
* response of the fundamental note
* ease of circular breathing
* effect on vocalizations
* effect on harmonics
* condensation behaviour

---

# Planned Acoustic Measurements

Measurements should preferably be performed at a fixed distance, for example:

```text
Distance:       1 metre
Microphone:     same position
Room:           same room
Instrument:     same didgeridoo
Playing level:  as consistent as possible
```

Useful measurements include:

* average dBA
* maximum dBA
* frequency spectrum
* fundamental level
* harmonic levels
* difference with and without the mute

Results should be repeated several times where possible.

---

# Acoustic Expectations

At this stage **no specific noise-reduction figure is claimed**.

The design is expected to affect higher harmonics more easily than the very low fundamental frequency.

Possible reductions may occur in:

* buzzing
* higher harmonics
* attack noise
* breath noise
* perceived brightness
* overall subjective loudness

However, the effectiveness is currently hypothetical until prototype measurements are available.

Any future dB figures published here will be clearly identified as **measured results** rather than design estimates.

---

# Safety

This project is experimental.

Do not use the device if:

* airflow becomes severely restricted
* breathing feels uncomfortable
* excessive pressure develops
* parts become loose
* absorber material can enter the airflow

Only clean, non-toxic materials should be used near the airflow path.

The device must never form an airtight closure.

---

# Cleaning

The design should preferably remain serviceable and removable.

Because condensation is expected during didgeridoo playing:

* allow the device to dry after use
* use removable absorber material where practical
* clean the inner tube periodically
* inspect for mould or contamination
* replace contaminated absorber material

---

# Planned Development

Possible later versions may investigate:

* adjustable iris outlet
* interchangeable absorber cartridges
* 3D-printed bell adapters
* different expansion-chamber volumes
* different housing diameters
* Helmholtz resonators
* quarter-wave resonators
* multi-stage absorber chambers
* internal baffles
* condensation collection
* optimized low-back-pressure variants

---

# Development Stages

```text
v0.1  Design concept / preliminary blueprint
 ↓
v0.2  First physical prototype
 ↓
v0.3  Initial acoustic measurements
 ↓
v0.4  Geometry and absorber optimization
 ↓
v0.5  Second-generation prototype
 ↓
v1.0  Tested and documented design
```

This roadmap may change depending on experimental results.

---

# Contributing

Experiments and independent prototypes are very welcome.

Especially useful contributions include:

* photos of prototypes
* SPL measurements
* frequency-spectrum measurements
* back-pressure measurements
* tests with different absorber materials
* alternative dimensions
* 3D-printable components
* tests with different didgeridoos

Please clearly distinguish between:

**design assumptions**, **subjective observations** and **measured results**.

---

# Disclaimer

This repository currently contains an **experimental design concept**, not a validated finished product.

The design has not been certified as a medical, acoustic or safety device.

Use of any prototype is at your own risk.

No guarantee is provided regarding:

* acoustic attenuation
* mechanical safety
* breathing resistance
* playing characteristics
* compatibility with individual instruments

---

# License

For mechanical designs, drawings and CAD files, the **CERN Open Hardware Licence Version 2 – Permissive (CERN-OHL-P-2.0)** is a suitable option.

Software added later may use a separate software license.

See the repository `LICENSE` file for the license actually selected.

---

## Project Status

**v0.1 — Design Concept / Pre-Prototype**

**Practical prototype construction and measurements will follow.**

Results, failures, modifications and updated blueprints will be documented openly in this repository.
