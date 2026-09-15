<p align="center">
  <img src="docs/logo.png" alt="Didgeridoo Practice Mute" width="380">
</p>

<h1 align="center">Didgeridoo Practice Mute</h1>

<p align="center"><strong>Quieter practice. More music.</strong></p>

<p align="center">DIY · Open Hardware · Experimental</p>

<p align="center">
  <a href="./README.md">English</a> ·
  <a href="./README_DE.md">Deutsch</a>
</p>

A compact DIY acoustic mute for quieter didgeridoo practice at home.

The design uses an **expansion space, a perforated inner tube and open-cell acoustic foam** instead of simply blocking the bell. Air can still leave through a small outlet, so the instrument should keep more of its normal playing feel than a closed plug.

> This is an experimental DIY practice mute. It will not make a didgeridoo completely silent.

> [!IMPORTANT]
>
> ## Experimental open-hardware design
>
> This repository documents a **compact DN75 construction plan** (plan version 1.0).
>
> It is a DIY practice device, not a certified acoustic, medical or stage product. Dimensions, materials and the loudness figures on the drawing are **guide values**. They can change after independent prototype tests.
>
> Planned next steps:
>
> * build one or more prototypes from this plan
> * judge playing feel and back pressure
> * measure sound level with and without the mute
> * compare outlet diameters
> * try different absorber foams
> * publish measured results and revised drawings here
>
> Treat the current status as **construction plan v1.0 — experimental**, not as a finished, lab-validated product.

---

## Current project status

**Status:** Experimental DIY construction plan  
**Plan version:** 1.0  
**Canonical design:** compact HT DN75 mute, overall length 180 mm

The construction drawing is the source of truth for parts and dimensions. Text in this README is aligned with that drawing.

A larger DN125 / ~400 mm concept was sketched earlier in this repository. That geometry is **not** the current build. Longer or larger housings remain optional later variants.

---

## Features intended by the design

* Passive construction — no electronics
* Low-cost standard HT plumbing parts
* Open-cell acoustic foam (replaceable)
* Perforated inner tube
* Hose-clamp bell coupling for typical practice didgeridoos
* Interchangeable / drillable outlet insert
* Relatively low extra back pressure with the larger outlets
* Intended to reduce higher harmonics and buzzing more than the fundamental
* Easy to modify for experiments

---

## How it is intended to work

A didgeridoo produces a strong low fundamental plus many harmonics.

Simply blocking the bell lowers volume, but it also raises back pressure and changes the instrument a lot.

This mute uses three stages:

1. **Front coupling and expansion space**  
   The bell is sealed with a hose clamp around the DN75 housing. Behind the bell there is free volume before the perforated tube.

2. **Perforated inner tube**  
   Air continues through a short DN50 tube with staggered holes. Acoustic energy can pass through those holes into the surrounding foam.

3. **Acoustic foam and open outlet**  
   Open-cell foam absorbs part of the energy, especially at higher frequencies. A DN25 outlet keeps the airflow path open.

The operating principle is plausible. How well this exact compact layout works still needs to be measured independently and documented in this repository.

---

# Construction plan

The German original drawing is the current blueprint:

<p align="center">
  <img src="docs/construction-plan.png" alt="Didgeridoo mute construction plan">
</p>

<p align="center"><em>Construction plan v1.0 — compact DN75 design. All dimensions in millimetres. Scale on the drawing is 1:2 unless noted otherwise.</em></p>

The drawing still contains a printed “private, non-commercial use” note. That note is **superseded** by the open-hardware licence of this repository. See [License](#license).

---

## Main dimensions

Example in the drawing: didgeridoo **outside diameter 60 mm**.

| Part | Specification |
| ---- | ------------- |
| Main housing | HT pipe **DN75**, length **180 mm** |
| Typical outside diameter | approx. **78 mm** |
| Typical inside diameter | approx. **74 mm** |
| Front foam ring | Ø74 mm, thickness **40 mm**, centre hole **Ø40 mm** |
| Inner tube | HT pipe **DN50**, length **80 mm** |
| Perforation | **Ø8 mm**, pitch approx. **15 mm**, 3 staggered rows of 6 holes |
| Rear foam block | Ø74 mm, thickness **40 mm**, centre hole **Ø40 mm** |
| End cap | HT cap **DN75** |
| Outlet pipe | HT pipe **DN25**, length **20 mm** (inner approx. Ø20 mm, outer approx. Ø26 mm) |
| Hose clamp | stainless, **60–80 mm** |
| Total length | **180 mm** |

Axial layout of the 180 mm housing:

```text
 40 mm          80 mm           40 mm      20 mm
 front foam     inner tube      rear foam  outlet
<--------------------- 180 mm --------------------->
```

**These dimensions are the current starting values for prototype construction.** They are not yet independently optimised in this repository.

---

## Proposed cross section

```text
 DIDGERIDOO                    PRACTICE MUTE (DN75)

     Bell ~Ø60
       ||     40 mm     80 mm          40 mm    20 mm
=======||================================================
  hose ||   [ foam ] [ perforated DN50 ] [ foam ] | DN25 --> OUT
  clamp||   [ Ø40  ] [ holes Ø8 mm     ] [ Ø40  ] |
=======||================================================
              <------------- DN75 / 180 mm ------------>
```

---

# Materials / bill of materials

Example prices from the construction plan (EUR, approximate):

| No. | Part | Specification | Qty | Approx. EUR |
| --: | ---- | ------------- | --: | ----------: |
| 1 | Outer tube | HT pipe DN75, 180 mm | 1 | 3.00 |
| 2 | Front foam ring | open-cell acoustic foam, Ø74 × 40 mm, hole Ø40 mm | 1 | 2.00 |
| 3 | Inner tube | HT pipe DN50, 80 mm, Ø8 mm holes at 15 mm pitch | 1 | 1.50 |
| 4 | Rear foam block | open-cell acoustic foam, Ø74 × 40 mm, hole Ø40 mm | 1 | 2.00 |
| 5 | End cap | HT cap DN75 | 1 | 1.50 |
| 6 | Outlet pipe | HT pipe DN25, 20 mm | 1 | 0.50 |
| 7 | Hose clamp | stainless, 60–80 mm | 1 | 2.00 |
|  |  | **Estimated total** |  | **12.50** |

Use **open-cell acoustic foam** (for example 20–30 kg/m³). Closed-cell PE foam is not a substitute.

Do not use loose glass wool or mineral wool: fibres could enter the airflow.

---

# Bell coupling

The drawing uses a **hose clamp** around the DN75 housing and the didgeridoo, not a hard plastic bite on the instrument.

The example instrument is **Ø60 mm outside**. The specified clamp range is **60–80 mm**.

For other bell sizes:

* a smaller or larger clamp
* a thin foam or rubber sleeve between clamp and instrument
* later: 3D-printed or EVA/EPDM adapters

The didgeridoo should not be forced against sharp plastic edges.

---

# Perforated inner tube

From the construction plan:

* HT DN50, length **80 mm**
* hole diameter **8 mm**
* spacing along the tube: 10 / 15 / 15 / 15 / 15 / 10 mm
* **3 staggered rows, 6 holes per row** (18 holes)

```text
   o     o     o
      o     o
   o     o     o
```

The hole area is large compared with the tube bore, so the perforations themselves should not be the main airflow restriction. Actual back pressure still needs to be measured.

---

# Adjustable outlet — guide values

The default outlet on the drawing is **DN25 / 20 mm long**.

Smaller outlets are expected to be quieter and to add more back pressure:

| Outlet Ø | Loudness reduction (guide) | Back pressure (guide) |
| -------: | -------------------------- | --------------------- |
| 25 mm | −10 to −15 dB | low |
| 20 mm | −15 to −20 dB | moderate |
| 15 mm | −20 to −25 dB | noticeable |
| 10 mm | −25 to −30 dB | high |

These figures come from the construction plan and are marked there as **experience / guide values**. They can vary with the didgeridoo, foam, room and how hard you play.

They are **not** independent laboratory measurements published by this repository. Any later dB numbers measured here will be labelled as measured results.

Do not close the outlet completely. Free airflow matters for playing feel and safety.

---

# Assembly

1. Cut the DN75 housing to **180 mm**.
2. Cut the DN50 inner tube to **80 mm**.
3. Drill Ø8 mm holes as in the drawing (3 staggered rows).
4. Slide the **front foam ring** onto the inner tube.
5. Insert inner tube plus front foam into the housing, leaving about **40 mm** to the front edge for the bell.
6. Insert the **rear foam block**.
7. Glue the DN75 end cap (HT solvent weld or silicone; airtight on the cap joint).
8. Glue the **20 mm DN25** outlet into the end cap.
9. Fit the hose clamp. Optionally wrap the outside with tape, neoprene or felt.
10. Make sure foam cannot enter the airflow path, and start testing with the **largest** outlet.

The foam should stay removable for drying and cleaning.

---

# Planned prototype tests

Compare at least:

```text
Test A: no mute
Test B: Ø25 mm outlet
Test C: Ø20 mm outlet
Test D: Ø15 mm outlet
Test E: Ø10 mm outlet
```

For each configuration, note:

* perceived volume
* playing comfort
* back pressure
* response of the fundamental
* circular breathing
* vocalizations
* harmonics
* condensation

---

# Planned acoustic measurements

Prefer constant conditions, for example:

```text
Distance:       1 metre
Microphone:     same position
Room:           same room
Instrument:     same didgeridoo
Playing level:  as consistent as possible
```

Useful measurements:

* average dBA
* maximum dBA
* frequency spectrum
* fundamental level
* harmonic levels
* difference with and without the mute

Repeat measurements where possible.

---

# Acoustic expectations

No certified noise-reduction figure is claimed.

The compact mute is expected to affect **higher harmonics, buzz and brightness** more easily than the very low fundamental.

Possible effects:

* less buzzing
* darker / quieter practice sound
* less attack and breath noise
* lower perceived loudness
* some extra back pressure, especially with small outlets

How large those effects are in this exact build still needs to be measured.

---

# Safety

This project is experimental.

Do not use the device if:

* airflow becomes severely restricted
* breathing feels uncomfortable
* excessive pressure develops
* parts become loose
* absorber material can enter the airflow

Use only clean, non-toxic materials in the airflow path.

The mute must never form an airtight closure.

The construction plan marks the device as a **practice** mute, not as a stage mute for microphone use.

---

# Cleaning

Keep the design serviceable.

Condensation is expected:

* dry the mute after use
* use removable foam
* clean the inner tube periodically
* inspect for mould
* replace contaminated foam

---

# Planned development

Possible later versions:

* other outlet diameters (about 15–25 mm as on the drawing)
* longer housing (for example DN75 × 250 mm) or a second chamber
* 3D-printed bell adapters
* interchangeable foam cartridges
* different housing diameters, including a larger DN125 experiment
* Helmholtz or quarter-wave resonators
* condensation collection
* low-back-pressure variants

---

# Development stages

```text
v1.0-plan   Compact DN75 construction plan (current)
     ↓
v1.1        First physical prototype from this plan
     ↓
v1.2        Independent acoustic measurements
     ↓
v1.3        Geometry / foam / outlet optimisation
     ↓
v2.0        Tested and documented design
```

This roadmap may change with experimental results.

---

# Contributing

Independent prototypes are welcome.

Especially useful:

* photos of builds
* SPL measurements
* frequency spectra
* back-pressure notes
* other foams and dimensions
* 3D-printable adapters
* tests with different didgeridoos

Please distinguish **design assumptions**, **subjective observations** and **measured results**.

---

# Disclaimer

This repository contains an **experimental DIY construction plan**, not a certified product.

Use of any prototype is at your own risk.

No guarantee is provided regarding:

* acoustic attenuation
* mechanical safety
* breathing resistance
* playing characteristics
* compatibility with individual instruments

---

# License

Hardware design, drawings and documentation in this repository are licensed under the **CERN Open Hardware Licence Version 2 – Permissive (CERN-OHL-P-2.0)**.

That matches the **Open Hardware** mark on the project logo.

The construction drawing still shows an older “private, non-commercial use” line. The repository licence above is the binding one.

See the [`LICENSE`](./LICENSE) file.

Software added later may use a separate software licence.

---

## Files

| File | Role |
| ---- | ---- |
| [`docs/logo.png`](./docs/logo.png) | Project logo (transparent) |
| [`docs/logo.jpg`](./docs/logo.jpg) | Project logo (original artwork) |
| [`docs/construction-plan.png`](./docs/construction-plan.png) | Construction plan v1.0 (German original) |
| [`README.md`](./README.md) | English documentation |
| [`README_DE.md`](./README_DE.md) | German documentation |
| [`LICENSE`](./LICENSE) | CERN-OHL-P-2.0 |

**Build from the construction plan, measure openly, and treat the dB table as a starting guide until this repository has its own measurements.**
