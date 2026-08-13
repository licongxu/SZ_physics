---
tags:
  - SZ
  - kSZ
  - literature
aliases:
  - kSZ literature
  - kSZ
---

# kSZ literature

**Hub:** [SZ Literature Map](../SZ%20Literature%20Map.md) · **Physics:** [Unified SZ Derivation](../Unified%20SZ%20Derivation.md#9-ksz-is-m-k-1-0)

**Moment:** $`(m,k)=(1,0)`$ → $`\int n_e v_\parallel\,dl`$. Spectrum: **blackbody** $`\Delta T/T=-\tau\beta\mu`$. Same SED as primary CMB.

---

## Background

Sunyaev & Zeldovich (1980): coherent bulk motion Doppler-shifts CMB photons. Typical $`\beta\sim 10^{-3}`$ ($`300\,\mathrm{km\,s^{-1}}`$), so $`y_{\mathrm{kSZ}}\sim 10^{-5}`$, about **10× fainter** than tSZ in a massive cluster, and frequency-independent in $`\Delta T`$. Isolation requires (i) a velocity tracer, (ii) the tSZ null near $`217\,\mathrm{GHz}`$, or (iii) pairwise/odd-parity statistics that tSZ (even in $`v`$) cancels.

Relativistic corrections to this term are [rkSZ and higher kinematic](rkSZ%20and%20higher%20kinematic.md), not kSZ itself.

---

## The kSZ power spectrum — three components

The late-time kSZ signal is not one thing. The total kSZ power spectrum is canonically split into three physically distinct contributions:

| Component | Physics | Era | $`\ell`$ |
| --- | --- | --- | --- |
| **Ostriker–Vishniac (OV)** | linear velocity field integrated over ionized gas | post-recombination, $`z\lesssim 10`$ | smooth, peaks $`\ell\sim 1000`$–$`3000`$ |
| **Patchy reionization kSZ** | ionized bubbles growing into neutral IGM | EoR, $`z\sim 6`$–$`10`$ | bump at $`\ell\sim 2000`$–$`4000`$ |
| **Late-time (nonlinear) kSZ** | nonlinear peculiar velocities in $`z\lesssim 2`$ halos / filaments | low $`z`$ | broad, non-Gaussian |

Ostriker & Vishniac (1986); Vishniac (1987) computed the linear OV term. The split matters because high-$`\ell`$ kSZ power is *detected* as a residual, but attributing it between OV + late-time (both $`z<10`$) and patchy reionization ($`z\sim 6`$–$`10`$) is **prior-dependent** — see [Patchy kSZ and reionization](Patchy%20kSZ%20and%20reionization.md). The OV effect is the linear-theory floor that any reionization model sits on top of.

---

## What people have done

Four estimator families (all still in use):

| Method | Idea | Landmark |
| --- | --- | --- |
| **Pairwise** | approaching pairs: increment + decrement | Hand+2012 ACT+SDSS (**first detection**) |
| **Velocity-weighted stack** | reconstruct $`v_\parallel`$ from galaxies (continuity), stack $`\Delta T\times v`$ | Schaan+; ACT+DESI **$`13\sigma`$** |
| **Projected-field / bispectrum** | $`T\times \delta_g\times \delta_g`$ without per-object $`v`$ | Hill, Ferraro, Smith, … |
| **Quadratic velocity reconstruction** | reconstruct large-scale $`v`$ from $`T`$ and $`\delta_g`$ | Deutsch/Cayuso/Johnson; ACT DR6 **$`3.8\sigma`$** |

Plus **resolved** kSZ in mergers: only **MACS J0717.5+3745** (Mroczkowski+2012 hint; Sayers+2013 **$`4.2\sigma`$** on subcluster B, $`v_z=+3450\pm 900\,\mathrm{km\,s^{-1}}`$; Adam+2017 NIKA **first resolved kSZ map**, dipole $`-5.1\sigma`$ / $`+3.4\sigma`$). Still the only individual cluster with a published kSZ detection (PITSZI 2025 restates this).

### Statistical detections, roughly in order
- Hand et al. (2012) — pairwise, ACT + SDSS DR9
- Planck 2014/2016 — pairwise on SDSS CGC; also $`v`$–$`T`$ correlation $`\sim 3\sigma`$
- De Bernardis+ / Schaan+ ACT+BOSS stacking
- Soergel et al. DES+SPT pairwise (photometric)
- Li, Calafut, Amodeo, Schaan, … ACT DR4/DR5 + BOSS (optical depth profiles, feedback)
- **Hadzhiyska et al. (2025)** ACT + DESI photometric LRGs: stacked kSZ **$`13\sigma`$**, gas more extended than DM, disfavours low-feedback TNG vs high-feedback Illustris
- **Pairwise DESI DR1 + ACT DR6 + Planck (2025)**: **$`9.3\sigma`$**, 913k LRGs — highest-significance *pairwise* kSZ
- ACT DR6 kSZ velocity reconstruction × BOSS $`v`$: **$`3.8\sigma`$** (JCAP 2025)
- DESI DR2 + ACT DR6 precision kSZ vs mass and $`z`$ (2026, arXiv:2604.19744)

### Theory of the kSZ power spectrum
- Ostriker & Vishniac (1986); Vishniac (1987) — **OV effect**, the linear post-recombination contribution
- Hu (2000); Zhang, Pen, Trac (2004) — nonlinear late-time kSZ
- McQuinn, Zahn, Battaglia, Park, Gorce — patchy reionization kSZ (see [Patchy kSZ and reionization](Patchy%20kSZ%20and%20reionization.md))

### Science targets
- **Missing baryons / CGM** — kSZ traces all ionized gas, not only $`T_e\gtrsim 1\,\mathrm{keV}`$
- **Feedback** — stacked $`p_{\mathrm{e}}(r)`$ from tSZ vs $`n_e(r)`$ from kSZ
- **Growth / $`f\sigma_8`$** — pairwise velocity; still $`\tau`$–$`v`$ degenerate without an optical-depth prior
- **Reionization** — [Patchy kSZ and reionization](Patchy%20kSZ%20and%20reionization.md) (different redshift, same SED)

---

## Detection significance

Statistical kSZ is **real and high-S/N** in 2025–2026 (9–13$`\sigma`$ stacked/pairwise). It is **not** a per-cluster velocity catalog. Optical depth $`\tau`$ is the limiting systematic for cosmology: kSZ measures $`\tau v`$, not $`v`$.

---

## Open issues
$`\tau`$ from tSZ/$`Y`$ vs kSZ (temperature structure); photo-$`z`$ vs spec-$`z`$; ILC CMB maps still contain tSZ/CIB residuals; only one resolved cluster; rkSZ bias on hot mergers.

**Key papers:** SZ80 · Hand+2012 · Sayers+2013 · Adam+2017 · Schaan+ · Hadzhiyska+2025 · DESI pairwise 2025. [SZ Paper Index](../SZ%20Paper%20Index.md)
