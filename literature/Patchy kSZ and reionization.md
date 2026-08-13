---
tags:
  - SZ
  - kSZ
  - reionization
  - literature
aliases:
  - patchy kSZ
---

# Patchy kSZ and reionization

**Hub:** [SZ Literature Map](../SZ%20Literature%20Map.md) · **Late-time kSZ:** [kSZ literature](kSZ%20literature.md)

Same SED as late-time kSZ (blackbody), but the electrons are in **patchy reionization bubbles** at $`z\sim 6`$–$`10`$, not in $`z\lesssim 1`$ clusters. The science is the **duration and morphology of reionization**, not ICM physics.

---

## Background

Inhomogeneous ionization → a kSZ power spectrum “bump” at $`\ell\sim 2000`$–$`4000`$ (Gruzinov & Hu; Knox, Scoccimarro, Dodelson; McQuinn+; Zahn+; Battaglia+; Park+). Amplitude scales with the duration of reionization; shape with bubble size.

This is one of three components of the total kSZ power spectrum (see [kSZ literature](kSZ%20literature.md#the-ksz-power-spectrum--three-components)):

```math
C_\ell^{\mathrm{kSZ}} = \underbrace{C_\ell^{\mathrm{OV}}}_{\text{linear, post-recomb}} + \underbrace{C_\ell^{\mathrm{patchy}}}_{\text{reionization}} + \underbrace{C_\ell^{\mathrm{late}}}_{\text{nonlinear, }z\lesssim 2}.
```

The patchy term carries the reionization science. The **Ostriker–Vishniac** (OV) term is the linear floor from post-recombination ionized gas; the late-time nonlinear term comes from low-$`z`$ halos and filaments. All three share the **same blackbody SED**, so they are separated only by $`\ell`$-dependence, non-Gaussianity, and cross-correlations — never by frequency.

Observational problem: **late-time (homogeneous + patchy-group) kSZ** has the same spectrum. Separation uses:
- $`\ell`$-dependence (reionization is smoother, late-time more non-Gaussian / 4-point)
- cross-correlation with 21cm, Lyman-$`\alpha`$ emitters, galaxies (late-time)
- tSZ deprojection (does not remove kSZ)

---

## What people have done

- **Theory / sims:** McQuinn, Zahn, Battaglia, Park, Gorce, Chen, … reionization kSZ $`C_\ell`$ and trispectrum.
- **CMB power-spectrum constraints:** SPT (Reichardt+2021 and successors), ACT: high-$`\ell`$ kSZ amplitude after tSZ/CIB modelling. Typical limits on patchy kSZ $`\lesssim`$ few $`\mu\mathrm{K}^2`$ at $`\ell=3000`$, translated into reionization duration. The split late-time vs EoR is **prior-dependent**.
- **kSZ 4-point / non-Gaussian estimators** to isolate patchy reionization (Smith & Ferraro, Alvarez, …).
- **Forecasts:** CMB-S4, SO, LiteBIRD polarisation $`\tau`$ + kSZ duration.

This is *not* the DESI stacked kSZ, which is low-$`z`$ galaxies.

---

## Detection significance

High-$`\ell`$ **kSZ power is detected as a residual** in ACT/SPT foreground fits. A clean, unique **patchy-reionization kSZ detection** (separated from $`z<2`$ gas) is **not** in hand.

**Open:** 4-point vs 2-point split; joint 21cm; confusion with residual tSZ/CIB in the same $`\ell`$ range.

**Key papers:** Gruzinov & Hu · McQuinn+ · Zahn+ · Battaglia+ · Reichardt+2021 · Smith & Ferraro. [SZ Paper Index](../SZ%20Paper%20Index.md)
