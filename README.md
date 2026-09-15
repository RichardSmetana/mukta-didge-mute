<p align="center">
  <img src="docs/logo.png" alt="Didgeridoo Practice Mute" width="380">
</p>

<h1 align="center">Didgeridoo Practice Mute</h1>

<p align="center"><strong>Quieter practice. More music.</strong></p>

<p align="center">Project Version 0.1 · DIY · Open Hardware · Experimental</p>

<p align="center">
  <a href="./README.md">English</a> ·
  <a href="./README_DE.md">Deutsch</a>
</p>

An experimental DIY acoustic mute for quieter didgeridoo practice.

The proposed designs use an **expansion / absorption volume, a perforated inner tube and acoustic absorber** instead of simply closing the bell. Air still leaves through an open outlet.

> This is an experimental practice mute. **It will not make a didgeridoo completely silent.** The crossed-speaker mark on the logo is a “quieter / muted” symbol, not a claim of silence.

> [!IMPORTANT]
>
> ## Design concept / pre-prototype
>
> **NOT YET TESTED.**
>
> This repository describes experimental design ideas. No physical prototype of these exact drawings has been measured here. Dimensions and materials are **preliminary** and may change after practical testing.
>
> Future work includes:
>
> * building physical prototypes
> * measuring sound level
> * measuring or evaluating back pressure
> * comparing outlet sizes
> * testing absorber materials
> * analysing frequency spectra
> * updating dimensions from real tests
>
> **Do not treat any qualitative loudness wording as a measured result.**

---

## Variant overview

This project contains **two separate experimental variants**. They are not translations of each other.

| Variant | Status | Housing | Body length | Assembled length | Purpose |
| ------- | ------ | ------- | ----------- | ---------------- | ------- |
| **DN125 v0.1** | Primary pre-prototype · not yet tested | DN125 | 400 mm | approx. 440 mm | Main low-back-pressure experiment |
| **DN75 Compact v0.1** | Experimental compact draft · not yet tested | DN75 | 180 mm **body** | greater than 180 mm (end cap + outlet; exact total unmeasured) | Smaller experimental alternative |

**DN125-v0.1 is the main project design.** DN75-Compact-v0.1 is a compact draft, not a finished Version 1.0 product.

---

# Primary design — DN125 v0.1

**Name:** DN125 Practice Mute  
**Status:** Version 0.1 · Design concept / pre-prototype · **not yet tested**

## Construction plan

<p align="center">
  <img src="docs/construction-plan-dn125.svg" alt="DN125 v0.1 construction plan">
</p>

<p align="center"><em>DN125-v0.1 · drawing not to scale — use stated millimetre dimensions · CERN-OHL-P-2.0</em></p>

## Working principle (DN125)

1. **Front / insertion section (40 mm)**  
   A flexible **bell adapter / seal** (EVA or EPDM) couples the didgeridoo. This is a seal, not the acoustic absorber.

2. **Expansion chamber (80 mm)**  
   Air enters a larger chamber before the perforated tube.

3. **Absorber section (230 mm housing length)**  
   A Ø50 mm inner tube sits in this section. **200 mm of the tube is perforated**; the tube’s **total length is 250 mm**. Those two numbers are not the same as the 230 mm housing absorber length.

4. **Rear / outlet section (50 mm) and outlet projection (approx. 40 mm)**  
   An interchangeable insert (Ø50 / Ø40 / Ø32 mm) keeps the airflow path open.

## DN125 dimensions (preliminary)

Housing chain:

**40 + 80 + 230 + 50 = 400 mm** housing body.

| Item | Preliminary value |
| ---- | ----------------- |
| Main housing | DN125 PP/PVC/HT pipe |
| Housing body length | **400 mm** |
| Housing outside diameter | approx. **125 mm** |
| Outlet projection outside housing | approx. **40 mm** |
| Approximate assembled total length | **440 mm** |
| Front / insertion section | **40 mm** |
| Expansion chamber | **80 mm** |
| Absorber section (housing) | **230 mm** |
| Rear / outlet section (housing) | **50 mm** |
| Inner tube | **Ø50 mm**, **250 mm** total length |
| Perforated length of inner tube | **200 mm** |
| Perforation | Ø6 mm holes, approx. 15 mm spacing, staggered, approx. 80–120 holes |
| Acoustic absorber | 20–25 mm **open-cell acoustic foam or PET acoustic felt** |
| Test outlets | **Ø50 / Ø40 / Ø32 mm** |

Supported **didgeridoo bell diameter:** approximately **70–105 mm**.

That range is **not** the inner diameter of the adapter.

**Adapter opening:** approximately bell diameter minus **2–4 mm**. Exact size depends on foam or elastomer flexibility and must be tested.

| Didgeridoo bell Ø | Proposed adapter hole Ø |
| ----------------: | ----------------------: |
|            70 mm |                66–68 mm |
|            80 mm |                76–78 mm |
|            90 mm |                86–88 mm |
|           100 mm |                96–98 mm |

Do not use excessive force. Do not clamp the instrument against hard plastic.

### Inner-tube area reference (geometry only)

```text
Ø50 mm tube area  π × 25² ≈ 1963.5 mm²   (documented as ~1960 mm²)
100 × Ø6 mm holes 100 × π × 3² ≈ 2827.4 mm²  (documented as ~2830 mm²)
```

These figures only compare hole area with tube bore. They are **not** acoustic performance results.

## DN125 materials

| Part | Role | Proposed material |
| ---- | ---- | ----------------- |
| Bell adapter | **Seal / mechanical adapter** | EVA or EPDM |
| Main housing | Structure | DN125 HT/PP/PVC pipe, 400 mm |
| Inner tube | Air path + perforation | Ø50 mm PP/PVC pipe, 250 mm |
| Acoustic absorber | **Acoustic absorber** | open-cell acoustic foam or PET acoustic felt, 20–25 mm |
| Protective mesh | Keep absorber out of airflow | nylon or stainless mesh |
| End cap | Rear closure | DN125 cap |
| Outlet insert | Open exhaust | Ø50 / Ø40 / Ø32 mm |
| Sealant | Joints | neutral silicone or similar |

Do not use loose glass wool or mineral wool. Closed-cell PE foam is **not** an equivalent acoustic absorber.

## DN125 assembly (proposed)

1. Cut the DN125 housing to approximately **400 mm**.
2. Prepare the front for the EVA/EPDM bell adapter.
3. Cut the Ø50 mm inner tube to approximately **250 mm**.
4. Drill Ø6 mm holes over approximately **200 mm** (staggered).
5. Wrap the perforated section with thin protective mesh.
6. Install approximately **20–25 mm** of acoustic absorber in the **230 mm** absorber section.
7. Mount the inner tube centrally.
8. Leave approximately **80 mm** expansion chamber behind the bell.
9. Install the rear cap.
10. Fit a replaceable outlet insert.
11. Ensure absorber cannot enter the airflow.
12. Start testing with the **largest** outlet (**Ø50 mm**).

## DN125 planned tests

No results are recorded yet.

```text
A  no mute
B  Ø50 mm
C  Ø40 mm
D  Ø32 mm
```

For every test, propose recording:

* average sound level
* maximum sound level
* frequency spectrum
* fundamental level
* harmonic levels
* subjective back pressure
* playing comfort
* circular breathing
* vocalisations
* condensation behaviour

Outlet wording is **expected behaviour only, not measured**:

| Outlet | Expected restriction | Expected attenuation |
| -----: | -------------------- | -------------------- |
| Ø50 mm | lower | lower |
| Ø40 mm | intermediate | intermediate |
| Ø32 mm | higher | higher |

Never close the outlet completely.

---

# Compact design — DN75 Compact v0.1

**Name:** Compact DN75 Practice Mute  
**Status:** Version 0.1 · Experimental compact draft / pre-prototype · **not yet tested**

This is **not** a mature Version 1.0 product.

## Construction plan

<p align="center">
  <img src="docs/construction-plan-dn75-compact.svg" alt="DN75 Compact v0.1 construction plan">
</p>

<p align="center"><em>DN75-Compact-v0.1 · drawing not to scale — use stated millimetre dimensions · CERN-OHL-P-2.0</em></p>

## Compact construction (no dedicated empty expansion chamber)

The compact drawing does **not** define a separate 40 mm empty expansion chamber. Describe it as:

* front bell adapter / foam section
* perforated DN50 inner tube
* absorber around / adjacent to the inner tube
* rear foam section
* open outlet

Any remaining free volume around the perforated inner tube **may** act as an expansion / absorption volume. That is a preliminary description, not a measured chamber.

## DN75 dimensions (preliminary)

| Item | Preliminary value |
| ---- | ----------------- |
| Main housing | HT **DN75** |
| Housing **body** length | **180 mm** |
| Typical housing OD | approx. **78 mm** |
| Typical housing ID | approx. **74 mm** |
| Outlet projection | approx. **20 mm** |
| Overall assembled length | **depends on the selected DN75 end cap; greater than 180 mm** |
| Inner tube | HT DN50, approx. Ø50 mm OD, **80 mm** long |
| Inner-tube holes | Ø8 mm, approx. 15 mm pitch, 3 staggered rows, 6 holes/row, **18 holes** |
| Front foam ring | approx. Ø74 mm outside, 40 mm thick, inner hole **approx. Ø48–50 mm** |
| Rear foam block | approx. Ø74 mm outside, 40 mm thick, central hole **approx. Ø26 mm** |
| Outlet | DN25, approx. Ø20 mm inside / Ø26 mm outside, 20 mm projection |

**Do not call the complete assembled device 180 mm long.** 180 mm is the main DN75 **housing body**.

The front foam inner hole must pass over the DN50 tube. A Ø40 mm hole is **not** compatible with an approx. Ø50 mm tube. Use **approx. Ø48–50 mm**; the exact diameter depends on foam compressibility and must be tested.

The rear foam hole **approx. Ø26 mm** matches the DN25 outlet outside diameter.

### Compact bell connection

A hose clamp **alone** cannot bridge a roughly Ø60 mm bell to a roughly Ø74 mm housing ID.

Add an explicit flexible **bell adapter / sealing sleeve** (EVA / EPDM / neoprene).

Example (preliminary): Ø60 mm bell and approx. Ø74 mm housing ID → about **7 mm radial adapter thickness**.

The hose clamp **secures** the assembly. It is not the part that fills the diameter difference.

Adapter geometry remains experimental.

## DN75 materials

| Part | Role | Proposed material |
| ---- | ---- | ----------------- |
| Bell adapter / sleeve | **Seal / mechanical adapter** | EVA, EPDM or neoprene |
| Hose clamp | Secures the joint | stainless, size to suit |
| Main housing | Structure | HT DN75, **180 mm body** |
| Front foam ring | **Acoustic absorber** at the front | open-cell acoustic foam or PET felt |
| Inner tube | Air path + perforation | HT DN50, 80 mm |
| Rear foam block | **Acoustic absorber** at the rear | open-cell acoustic foam or PET felt |
| End cap | Rear closure | HT DN75 cap |
| Outlet | Open exhaust | HT DN25, 20 mm projection |

## DN75 assembly (proposed)

1. Cut the DN75 housing body to **180 mm**.
2. Fit the EVA/EPDM/neoprene bell adapter / sealing sleeve.
3. Cut the DN50 inner tube to **80 mm** and drill Ø8 mm holes (3 × 6).
4. Open the **front foam** to approx. **Ø48–50 mm** and slide it onto the inner tube.
5. Insert the inner tube with front foam into the housing.
6. Install the **rear foam** with approx. **Ø26 mm** hole.
7. Glue or seal the DN75 end cap.
8. Fit the **20 mm** DN25 outlet.
9. Fit the hose clamp around the adapter/housing — to secure, not to span the bell gap alone.
10. Start testing with the **largest** recommended outlet (**Ø25 mm**).

## DN75 planned tests

No results are recorded yet.

```text
A  no mute
B  Ø25 mm
C  Ø20 mm
D  Ø15 mm
E  Ø10 mm   extreme restriction experiment only
```

Recommend **25 / 20 / 15 mm** for first practical tests.

**Ø10 mm** is an extreme experimental restriction. It is **not** recommended as the first test because of expected high back pressure.

**EXPECTED BEHAVIOUR — NOT MEASURED**

| Outlet | Expected restriction | Expected attenuation |
| -----: | -------------------- | -------------------- |
| 25 mm | low | lower |
| 20 mm | moderate | higher |
| 15 mm | significant | higher |
| 10 mm | very high | experimental only |

Do not present this table as verified fact.

Record the same observations as for DN125 (sound level, spectrum, back pressure, comfort, circular breathing, vocalisations, condensation).

---

# Measurement methodology (both variants)

Prefer constant conditions, for example:

```text
Distance:       1 metre
Microphone:     same position
Room:           same room
Instrument:     same didgeridoo
Playing level:  as consistent as possible
```

Repeat measurements where possible. Publish numbers in this repository only after they have actually been measured, and label them as measured results.

---

# Safety

Keep safety wording conservative. The design is **not** medically certified and is **not** “safe” just because the theory looks plausible.

* Never completely block the outlet.
* Stop testing if breathing becomes uncomfortable.
* Stop if excessive back pressure is perceived.
* Keep loose fibres out of the airflow.
* Do not use loose glass wool or mineral wool.
* Use clean, non-toxic materials near the airflow.
* Inspect for condensation and mould.
* Allow absorber material to dry after use.

---

# Cleaning

Keep the construction serviceable.

* dry after use
* use removable absorber where practical
* clean the inner tube periodically
* inspect for mould
* replace contaminated absorber

---

# Planned development

Possible later experiments (not current claims):

* other outlet diameters
* 3D-printed bell adapters
* interchangeable absorber cartridges
* longer or multi-chamber housings
* condensation collection
* low-back-pressure variants

Roadmap (repository-level, may change):

```text
v0.1  Design concept / pre-prototype          ← current
 ↓
v0.2  First physical prototypes
 ↓
v0.3  Initial acoustic measurements
 ↓
v0.4  Geometry and absorber revision
 ↓
v1.0  Only after tested and documented builds
```

---

# Contributing

Prototypes, photos and measurements are welcome.

Please distinguish **design assumptions**, **subjective observations** and **measured results**.

Do not add dB figures unless they come from documented measurements.

---

# License

Hardware design, drawings, CAD files and project documentation are licensed under the CERN Open Hardware Licence Version 2 – Permissive (CERN-OHL-P-2.0), unless a file explicitly states otherwise.

Software added later may use a separate software licence.

See [`LICENSE`](./LICENSE).

### Artwork

Unless explicitly stated otherwise, project artwork and logos included in this repository follow the repository licensing notice.

<!-- TODO(owner): Confirm whether CERN-OHL-P-2.0 should also cover logo artwork, or whether a separate artwork licence is preferred. Do not invent another licence here. -->

---

# Files

| File | Role |
| ---- | ---- |
| [`docs/logo.png`](./docs/logo.png) | Project logo (transparent disc) |
| [`docs/logo.jpg`](./docs/logo.jpg) | Project logo (original artwork, same identity) |
| [`docs/construction-plan-dn125.svg`](./docs/construction-plan-dn125.svg) | Current DN125-v0.1 plan |
| [`docs/construction-plan-dn75-compact.svg`](./docs/construction-plan-dn75-compact.svg) | Current DN75-Compact-v0.1 plan |
| [`docs/archive/`](./docs/archive/) | **OUTDATED / SUPERSEDED** rasters — do not build from these |
| [`CHANGELOG.md`](./CHANGELOG.md) | Documentation history |
| [`LICENSE`](./LICENSE) | CERN-OHL-P-2.0 |

The logo wording is: **DIDGERIDOO PRACTICE MUTE** · **QUIETER PRACTICE. MORE MUSIC.** · DIY · OPEN HARDWARE · EXPERIMENTAL.
