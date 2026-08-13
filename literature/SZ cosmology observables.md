---
tags:
  - SZ
  - cosmology
  - literature
aliases:
  - SZ cosmology
---

# SZ cosmology observables

**Hub:** [SZ Literature Map](../SZ%20Literature%20Map.md) · **tSZ:** [tSZ literature](tSZ%20literature.md) · **Your notes:** *Cluster Number Counts* · *Pressure Profiles and tSZ PS* · *Hydrostatic Bias*

How survey SZ is turned into cosmology and feedback constraints. These are *applications* of tSZ (and increasingly kSZ), not new Compton cells.

---

## Cluster number counts (CNC)

$dN/dz\,dM$ from SZ selection ($q=y_0/\sigma_{y_0}$ or $Y_{500}$). Needs: selection function, $Y$–$M$, mass bias $B=M_{\mathrm{true}}/M_{\mathrm{SZ}}$, HMF.

- Planck 2013–2016 SZ cosmology: lower $\sigma_8$ than primary CMB if $B\sim 1.4$
- SPT-SZ / SPTpol / SPT-3G: Bocquet et al. series
- ACT: Hilton, Madhavacheril, DR6 catalog cosmology in progress
- FLAMINGO: HMF and $Y$–$M$ from hydro (*Cluster Number Counts*, Kugel+)

Limiting systematics: **mass calibration**, not raw cluster finding.

---

## $Y$–$M$ and pressure profiles

Self-similar $Y\propto M^{5/3}E^{2/3}$ (*Compton Y parameter and self-similarity*). Arnaud+2010 GNFW. Stacked Planck, ACT, SPT, NIKA2 profiles. Hydrostatic bias from X-ray vs WL vs $T_y$ (*Hydrostatic Bias*).

---

## tSZ power spectrum $C_\ell^{yy}$

One-halo dominated at $\ell\gtrsim 300$; extremely sensitive to $\sigma_8$ *and* baryonic feedback.

- Planck $y$-maps: MILCA, NILC; Bolliet, Salvati, …
- ACT/SPT high-$\ell$ foreground fits (template at $\ell=3000$)
- Efstathiou & McCarthy (2025): CMB $TT$ spectra, CIB-robust, **lower/shallower** than fiducial FLAMINGO
- SPT-3G+SPIRE 2026: **$9.3\sigma$** full shape $\ell=500$–$5000$
- Halo model: CLASS_SZ II (Bolliet+2025)

---

## Cross-correlations

| Cross | What it weights |
| --- | --- |
| $y\times$ CMB lensing | massive halos, $\sigma_8$, feedback |
| $y\times$ galaxies / CIB | groups, redshift kernel, CIB leakage tests |
| $y\times$ X-ray | $P_e$ vs $n_e^2\Lambda$ |
| kSZ $\times$ galaxies | $n_e v$, CGM |
| tSZ–kSZ on same sample | $T_e\sim y/\tau$ |

McCarthy+2024 (FLAMINGO): kSZ + tSZ–WL. Hill & Spergel; Van Waerbeke; Koukoufilippas; ACT DR6 cross papers.

---

## Distances (historical)

tSZ + X-ray → angular diameter distance (Silk & White; Birkinshaw; Reese+2002; Bonamente+2006). Superseded by BAO/CMB for $H_0$, still a cross-check of ICM models.

---

## $T_{\mathrm{CMB}}(z)$ — testing adiabatic expansion

The tSZ/kSZ spectral shape fixes the CMB temperature *at the cluster redshift*, giving a direct, model-independent test of $T(z)=T_0(1+z)$ from adiabatic expansion. Unlike distances, this needs no cosmological model.

- Battistelli et al. (2002); de Petris et al. (2007) — early measurements
- Luzzi et al. (2009, ApJ) — 7 clusters, consistent with $T\propto(1+z)$
- Hurier et al. (2014) — combined tSZ + X-ray + kSZ, percent-level
- Khatri & Sunyaev (2012) — rSZ as a thermometer (relativistic corrections encode $T_e$ vs $T_{\mathrm{CMB}}$)

This is one of the few **direct** cosmological tests from the SZ spectral shape, distinct from cluster counts and $C_\ell^{yy}$.

---

## Foregrounds: SZ–CIB correlation

The cosmic infrared background is the dominant contaminant for tSZ cosmology. The $y\times\mathrm{CIB}$ correlation is positive and biases $C_\ell^{yy}$ and $Y$–$M$ if not modelled.

- Planck XXX; Addison et al. (2012); Dolag et al.; Manz et al.
- Mitigation: multi-frequency ILC / constrained ILC, CIB deprojection, cross-frequency cleaning
- The correlation is itself physical (same halos host hot gas and dusty star formation), so it cannot be fully removed — only modelled

| Cross | What it weights |
| --- | --- |
| $y\times$ CIB | dusty star-forming halos; dominant tSZ systematic |

---

## Open cosmology questions
Is the tSZ $S_8$ problem **feedback** or **cosmology**? kSZ feedback vs tSZ $C_\ell$ vs WL baryon suppression — one consistent $f_{\mathrm{gas}}(M)$? Does rSZ bias $Y$ enough to matter for CNC?

**Key papers:** Planck SZ cosmology · Bocquet SPT · Arnaud+2010 · Efstathiou & McCarthy 2025 · CLASS_SZ · McCarthy+2024. [SZ Paper Index](../SZ%20Paper%20Index.md)
