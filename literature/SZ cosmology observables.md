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

The tSZ/kSZ spectral shape fixes the CMB temperature *at the cluster redshift*, giving a direct, model-independent test of $T(z)=T_0(1+z)$ from adiabatic expansion. Unlike distances, this needs no cosmological model. Proposed by Fabbri et al. (1978) and Rephaeli (1980). Parametrize deviations as $T(z)=T_0(1+z)^{1-\alpha}$ (sometimes $\beta$ for the same exponent).

- Battistelli et al. (2002); de Petris et al. (2007); Luzzi et al. (2009)
- **Saro et al. (2014)** — SPT clusters
- **Hurier et al. (2014)** — Planck, $\beta=0.009\pm 0.017$
- Luzzi et al. (2015); de Martino et al. (2015)
- **Li et al. (2021)**, ApJ — ACT, 370 clusters $0.07<z<1.4$, $\alpha=0.017^{+0.029}_{-0.032}$; combined with independent data $\alpha=-0.001\pm 0.012$
- Khatri & Sunyaev (2012) — rSZ as a thermometer ($T_e$ vs $T_{\mathrm{CMB}}$), a related but different use of the spectrum

All published SZ $T(z)$ constraints are consistent with adiabatic expansion ($\alpha=0$).

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

## Moving lens — transverse velocity, **not Compton**

A gravitational potential moving across the line of sight produces a time-varying Weyl potential. CMB photons traversing it pick up a temperature dipole $\propto \nabla_\perp\Psi\cdot v_\perp$ (Birkinshaw & Gull 1983; Aghanim, de Luca, Bouchet, Gispert & Silk; Hotinli et al. 2019, PRL 123, 061301). In the lens rest frame this is lensing of the CMB kinematic dipole.

This is **not** the Compton $\beta^2$ quadrupole (that *is* Thomson scattering; see [rkSZ and higher kinematic](rkSZ%20and%20higher%20kinematic.md)). It is a nonlinear ISW / moving-lens secondary. Science case: $v_\perp$ without the kSZ $\tau$–$v$ degeneracy (Hotinli, Smith, Madhavacheril & Kamionkowski 2021).

**Status:** [arXiv:2605.18938](https://arxiv.org/abs/2605.18938) (2026 preprint) reports the **first detection** with ACT DR6 × DESI Legacy Imaging Surveys: $b_{\mathrm{ML}}=1.24\pm 0.26$ (**$4.8\sigma$**) on the extended LRG sample in the NILC map ($3.7\sigma$ on the main sample). Treat as a preprint until journal refereeing is complete; CIB/tSZ dipoles aligned with $v_\perp$ remain the main systematic (Beheshti, Schaan & Kosowsky; Hotinli & Pierpaoli).

---

## Open cosmology questions
Is the tSZ $S_8$ problem **feedback** or **cosmology**? kSZ feedback vs tSZ $C_\ell$ vs WL baryon suppression — one consistent $f_{\mathrm{gas}}(M)$? Does rSZ bias $Y$ enough to matter for CNC?

**Key papers:** Planck SZ cosmology · Bocquet SPT · Arnaud+2010 · Efstathiou & McCarthy 2025 · CLASS_SZ · McCarthy+2024. [SZ Paper Index](../SZ%20Paper%20Index.md)
