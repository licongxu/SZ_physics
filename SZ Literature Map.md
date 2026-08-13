---
tags:
  - SZ
  - literature
  - MOC
aliases:
  - SZ literature
  - SZ knowledge graph
  - SZ periodic table literature
---

# SZ literature map

**Derivation:** [Unified SZ Derivation](Unified%20SZ%20Derivation.md) · **Paper list:** [SZ Paper Index](SZ%20Paper%20Index.md) · **Canvas:** [SZ Periodic Table](SZ%20Periodic%20Table.md)

This is the hub for an Obsidian graph of **all SZ physics**, not only tSZ/kSZ. Every named effect is one cell of the same Compton/Thomson expansion in $`(\theta_e,\beta)`$, plus a few extras that sit outside that table (non-thermal electrons, multiple scattering, reionization, WHIM).

Open this folder in Obsidian graph view: markdown links between notes are graph edges. Notes such as *The Physics of tSZ* and *FLAMINGO Overview* live in the parent `PhD_notebook` vault; they resolve if that folder is the vault root.

> **Note:** Honest scope
> Nobody has a complete bibliography of this field (thousands of papers). This map is a **structured census**: what each probe *is*, whether it has been *detected*, who did the *canonical work*, and what is still *open*. Landmark reviews: Birkinshaw (1999), Carlstrom et al. (2002), [Mroczkowski et al. 2019](https://arxiv.org/abs/1811.02310).

**Contents:** [Detection dashboard](#detection-dashboard) · [Periodic table](#periodic-table) · [Beyond the table](#beyond-the-table) · [How the field actually works](#how-the-field-actually-works) · [What is still missing](#what-is-still-missing)

---

## Detection dashboard

Status as of mid-2026. “Detected” means a published measurement of *that* spectral/spatial signature, not merely that the physics is in a forward model.

| Probe | Moment | Status | Best current handle | Note |
| --- | --- | --- | --- | --- |
| **tSZ** clusters | $`n_e T_e`$ | **Mature** | Planck PSZ2 1653 sources / 1203 confirmed; ACT/SPT thousands | Survey science |
| **tSZ** $`C_\ell^{yy}`$ | $`n_e T_e`$ | **Detected** | Planck+ACT+SPT shape; SPT-3G+SPIRE $`9.3\sigma`$ full shape (2026) | CIB is the enemy |
| **tSZ** stacking / cross | $`n_e T_e`$ | **Mature** | galaxies, lensing, CIB, X-ray | Feedback + missing baryons |
| **kSZ** pairwise | $`n_e v_\parallel`$ | **Detected** | DESI DR1 + ACT DR6 **$`9.3\sigma`$** (2025) | First: Hand+2012 |
| **kSZ** velocity-weighted stack | $`n_e v_\parallel`$ | **Detected** | ACT + DESI photo-z **$`13\sigma`$** | Highest S/N kSZ |
| **kSZ** velocity reconstruction | $`n_e v_\parallel`$ | **Emerging** | ACT DR6 + DESI LRGs **$`3.8\sigma`$** | Quadratic estimators |
| **kSZ** one cluster | $`n_e v_\parallel`$ | **One object** | MACS J0717, $`\sim 3`$–$`5\sigma`$ | Still unique |
| **rSZ** stacked $`T_e`$ | $`n_e T_e^{2}`$ | **Emerging** | ACT+Planck $`8.5\pm 2.4\,\mathrm{keV}`$; Planck $`\simeq 5\,\mathrm{keV}`$ | Systematics ~ statistical |
| **rSZ** one cluster | $`n_e T_e^{2}`$ | **Tentative** | RX J1347 (Butler+2022) | Not routine |
| **rkSZ** | $`n_e v_\parallel T_e`$ | **Not detected** | theory + MACS J0717 modelling | few % of kSZ at $`10\,\mathrm{keV}`$ |
| **$`\beta^2`$ SZ** | $`n_e v^2`$ | **Not detected** | theory / forecasts | monopole + quadrupole |
| **$`\beta^3`$ SZ** | $`n_e v^3`$ | **Not detected** | boost-operator papers 2026 | negligible for typical $`v`$ |
| **pSZ** (remote quadrupole) | $`\tau a_{2m}`$ | **Not detected** | limits / bispectrum forecasts | 2026 constraint papers |
| **kpSZ** | $`\tau\beta_\perp^2`$ | **Not detected** | forecasts (SO / CMB-S4 / CMB-HD) | |
| **ntSZ** | non-Maxwellian $`f(p)`$ | **Not detected** | cavities / radio cocoons, tentative | CR pressure $`\lesssim 1\%`$ |
| **multiple scattering** | $`\tau^2`$, $`y\tau`$ | **Not detected** | $`\sim 0.1\%`$ of tSZ | |
| **observer-motion SZ** | boost of SZ | **Not a separate detection** | dipole modulation of counts | must be modelled |
| **patchy kSZ** (EoR) | $`n_e v`$ at $`z\sim 6`$–$`10`$ | **Power seen, origin mixed** | high-$`\ell`$ kSZ $`C_\ell`$ | late-time vs EoR split is model-dependent |
| **WHIM / filaments** | $`n_e T_e`$ (warm) | **Stacked** | Tanimura+2019 **$`5.3\sigma`$**; tSZ+lensing **$`7.8\sigma`$** (2025) | not typical individual filaments |
| **CGM / missing baryons** | $`n_e`$, $`n_e T_e`$ | **Stacked** | kSZ + tSZ around galaxies | gas more extended than DM |
| **proto-cluster tSZ** | $`n_e T_e`$ at $`z\sim 2`$–$`4`$ | **A few objects** | Spiderweb $`z=2.16`$ ($`\sim 6\sigma`$); SPT2349−56 $`z=4.3`$ ($`8.4\sigma`$) | ICM assembly, not survey science |
| **mean $`\langle y\rangle`$** | sky-averaged $`P_e`$ | **Upper limit** | FIRAS; 2026 reanalysis $`\langle y\rangle=(1.2\pm 2.0)\times 10^{-6}`$ | not a $`y`$-map detection |
| **moving lens** | $`\nabla_\perp\Psi\cdot v_\perp`$ | **Claimed $`4.8\sigma`$** | ACT DR6 × DESI LS (2026 preprint) | **gravitational**, not Compton SZ |
| **kSZ projected-field** | $`T\times\delta_g\times\delta_g`$ | **Detected** | Hill+2016 Planck+WISE **$`3.8`$–$`4.5\sigma`$** | no spec-$`z`$ needed |
| **kSZ “dark flow”** | Gpc bulk $`v`$ | **Ruled out** | Planck Int. XIII: dipole $`<254\,\mathrm{km\,s^{-1}}`$ (95% CL) | Kashlinsky claim not confirmed |

---

## Periodic table

Physics derivation: [Unified SZ Derivation](Unified%20SZ%20Derivation.md#18-sz-periodic-table). Literature notes:

|  | $`\theta_e^0`$ | $`\theta_e^1`$ | $`\theta_e^{2+}`$ |
| --- | --- | --- | --- |
| $`\beta^0`$ | $`0`$ (cold static) | [tSZ literature](literature/tSZ%20literature.md) | [rSZ literature](literature/rSZ%20literature.md) |
| $`\beta^1`$ | [kSZ literature](literature/kSZ%20literature.md) | [rkSZ and higher kinematic](literature/rkSZ%20and%20higher%20kinematic.md) | higher rkSZ |
| $`\beta^2`$ | [rkSZ and higher kinematic](literature/rkSZ%20and%20higher%20kinematic.md) ($`\beta^2`$) | $`\beta^2`$ rSZ | … |
| $`\beta^3`$ | $`\beta^3`$-SZ | … | … |
| pol. | [Polarized SZ literature](literature/Polarized%20SZ%20literature.md) | thermal pol. | … |

Each cell $`\beta^m\theta_e^k \leftrightarrow \int n_e v^m T_e^k P_\ell(\mu)\,dl`$.

---

## Beyond the table

These are still SZ, but they are not a single $`(m,k)`$ Maxwellian cell.

- [Non-thermal SZ literature](literature/Non-thermal%20SZ%20literature.md) — power-law / cosmic-ray electrons, AGN bubbles; anisotropic $`f(p)`$
- [Multiple scattering and observer motion](literature/Multiple%20scattering%20and%20observer%20motion.md) — $`\tau^2`$ and Solar-System boost
- [Patchy kSZ and reionization](literature/Patchy%20kSZ%20and%20reionization.md) — ionized bubbles at high $`z`$; OV vs patchy vs late-time
- [WHIM CGM and cosmic web](literature/WHIM%20CGM%20and%20cosmic%20web.md) — groups, filaments, missing baryons; A399–A401
- [Resolved SZ astrophysics](literature/Resolved%20SZ%20astrophysics.md) — shocks, turbulence, mergers, MACS J0717, **proto-clusters**, NIKA2 LPSZ
- [SZ cosmology observables](literature/SZ%20cosmology%20observables.md) — cluster counts, $`C_\ell^{yy}`$, $`Y`$–$`M`$, $`T_{\mathrm{CMB}}(z)`$, CIB
- [Global Compton y and spectral distortions](literature/Global%20Compton%20y%20and%20spectral%20distortions.md) — monopole $`\langle y\rangle`$, FIRAS, PIXIE; not a $`y`$-map

Theory machinery that organises all of the above: [Unified SZ Derivation](Unified%20SZ%20Derivation.md) · Chluba et al. 2013 moments · SZpack · Hoey, Long & Chluba 2026 boost operator.

---

## How the field actually works

People do not observe “a cell of the periodic table”. They observe **mm maps** and then isolate a moment with frequency, spatial filtering, and a tracer.

1. **Photometry / ILC / constrained ILC** — separate tSZ ($`y`$-spectrum) from CMB/kSZ (blackbody) from CIB/radio. rSZ is a *residual* after a non-relativistic $`y`$ is deprojected.
2. **Surveys** — find clusters from tSZ: Planck, ACT, SPT. Cosmology from counts and $`C_\ell^{yy}`$.
3. **Cross-correlations** — kSZ needs a velocity or galaxy tracer because it is a blackbody. Pairwise, stacking, projected fields, quadratic estimators.
4. **Resolved imaging** — MUSTANG-2, NIKA2, ALMA, Bolocam: shocks, mergers, one kSZ map.
5. **Simulations** — FLAMINGO, BAHAMAS, IllustrisTNG, Magneticum: forward-model $`n_e T_e^k v^m`$. See *FLAMINGO Overview*, *Pressure Profiles and tSZ PS*.

---

## What is still missing

The interesting PhD-level gaps are **not** “detect tSZ”. They are:

- Which $`(k,m,\ell)`$ moments can multifrequency CMB actually *separate*?
- rSZ $`T_e`$ as a mass proxy vs X-ray, with systematics under control (passbands already limit ACT)
- kSZ $`\tau`$ vs tSZ $`y`$ on the **same** DESI sample (optical depth vs pressure)
- rkSZ as a contaminant of kSZ velocities in hot mergers
- $`\beta^2`$ monopole vs tSZ / rSZ at the null
- Polarized SZ: first detection (remote quadrupole or $`\beta_\perp^2`$)
- ntSZ in AGN bubbles with submm spectroscopy
- Late-time vs patchy-reionization split of $`C_\ell^{\mathrm{kSZ}}`$
- Feedback: kSZ says gas is more extended than TNG-like models; tSZ $`C_\ell`$ is low vs fiducial FLAMINGO — same physics?
- Proto-cluster ICM: Spiderweb is *under*-pressured vs virial expectations; SPT2349−56 at $`z=4.3`$ is *over*-pressured — simulations do not yet do both
- Mean $`\langle y\rangle`$: FIRAS still an upper limit; 2026 reanalysis is approaching Hill+2015’s prediction
- Moving lens vs kSZ: claimed $`4.8\sigma`$ transverse-velocity detection is gravitational, not a Compton cell

---

## Suggested reading order

1. [Unified SZ Derivation](Unified%20SZ%20Derivation.md) — what the cells *are*
2. This map — what has been *seen*
3. [tSZ literature](literature/tSZ%20literature.md) then [kSZ literature](literature/kSZ%20literature.md) then [rSZ literature](literature/rSZ%20literature.md)
4. [SZ cosmology observables](literature/SZ%20cosmology%20observables.md) if you care about $`\sigma_8`$ / feedback
5. [rkSZ and higher kinematic](literature/rkSZ%20and%20higher%20kinematic.md) + [Polarized SZ literature](literature/Polarized%20SZ%20literature.md) if you care about the unexplored cells
6. [Mroczkowski et al. 2019](https://arxiv.org/abs/1811.02310) as the 50-page backbone
7. [SZ Paper Index](SZ%20Paper%20Index.md) when you need a citation

---

## Literature search (2026-08-13)

Mode: lit-review against this vault. Databases: web + arXiv abs pages (API SSL failed; IDs checked on `arxiv.org/abs/`). Inclusion: named SZ physics or landmark papers missing from the census, with a verifiable bibliographic record.

Added after that search: monopole $`\langle y\rangle`$; proto-cluster tSZ (Spiderweb, SPT2349−56); moving lens as a *gravitational* secondary (and a 2026 claimed detection); kSZ dark-flow vs Planck; projected-field kSZ S/N; A399–A401 and newer filament stacks; $`T_{\mathrm{CMB}}(z)`$ ACT/SPT; Lee & Chluba 2024 anisotropic kernels; NIKA2 LPSZ; Battaglia 2012 profile.

---

*Census compiled 2026-08-13, updated after an online literature pass the same day. Detection significances are from the cited papers, not a meta-analysis.*
