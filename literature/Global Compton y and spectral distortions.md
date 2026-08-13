---
tags:
  - SZ
  - tSZ
  - spectral-distortions
  - literature
aliases:
  - Global Compton y
  - monopole y
  - CMB spectral distortions SZ
---

# Global Compton $`y`$ and CMB spectral distortions

**Hub:** [SZ Literature Map](../SZ%20Literature%20Map.md) · **Cluster tSZ:** [tSZ literature](tSZ%20literature.md) · **Physics:** [Unified SZ Derivation](../Unified%20SZ%20Derivation.md)

Same Compton operator as cluster tSZ, but **sky-averaged** (the monopole of $`y`$). This is absolute spectrophotometry, not a $`y`$-map. Cluster counts and $`C_\ell^{yy}`$ measure *fluctuations* of $`y`$; $`\langle y\rangle`$ measures the **total thermal energy in electrons** in the observable Universe.

```math
\langle y\rangle
=
\frac{\sigma_T}{m_e c^2}
\int\frac{d^{2}\hat{\mathbf{n}}}{4\pi}
\int dl\, P_e
\propto
E_e^{\mathrm{th,total}}.
```

---

## Physics split: $`\mu`$ vs $`y`$ vs cluster tSZ

| Distortion | When | Photon number | What it is |
| --- | --- | --- | --- |
| $`\mu`$ | $`5\times 10^4\lesssim z\lesssim 2\times 10^6`$ | conserved; Bose–Einstein | early energy injection (Silk damping, decaying particles) |
| primordial / reionization $`y`$ | $`z\lesssim 5\times 10^4`$ | conserved; Kompaneets $`y`$ | homogeneous Comptonization after thermalization fails |
| **cluster/group tSZ** | $`z\lesssim 2`$ halos | same $`y`$ spectrum | **dominant** contribution to $`\langle y\rangle`$ today |
| IGM / WHIM $`y`$ | filaments | same | $`\sim 5\%`$ of $`\langle y\rangle`$ |
| reionization $`y`$ | $`z\sim 6`$–$`10`$ | same | $`\sim 5\%`$ of $`\langle y\rangle`$ |

Hill, Battaglia, Chluba, Ferraro, Schaan & Spergel (2015, PRL 115, 261301; [arXiv:1507.01583](https://arxiv.org/abs/1507.01583)):
$`\langle y\rangle_{\mathrm{ICM}}\simeq 1.58\times 10^{-6}`$,
$`\langle y\rangle_{\mathrm{IGM}}\simeq 8.9\times 10^{-8}`$,
$`\langle y\rangle_{\mathrm{reion}}\simeq 9.8\times 10^{-8}`$.
Total $`\langle y\rangle\sim 1.8\times 10^{-6}`$, about **10× below** the original FIRAS bound. Primordial $`y`$ (Silk damping) is **2–3 orders of magnitude smaller** than structure-formation $`y`$.

This is why “detect tSZ” in maps is not the same as “detect the mean $`y`$ distortion”. Maps are zero-mean after component separation; $`\langle y\rangle`$ needs an **absolutely calibrated** spectrometer.

---

## What people have done

- **COBE-FIRAS** (Fixsen et al. 1996): $`|\langle y\rangle|<1.5\times 10^{-5}`$ (95% CL). Still the reference bound for three decades.
- **Hill et al. (2015)**: halo-model + hydro prediction that groups/clusters dominate $`\langle y\rangle`$; relativistic corrections $`\sim 1\%`$ below $`500\,\mathrm{GHz}`$.
- **PIXIE / PRISM / BISOU / FOSSIL** concepts: forecast $`\sigma(y)\sim 10^{-8}`$–$`10^{-9}`$ and a relativistic $`T_e`$ moment of the monopole (Abitbol, Chluba, Hill & Johnson 2017; Kogut et al. PIXIE [arXiv:2405.20403](https://arxiv.org/abs/2405.20403)).
- **Fabbian, Bianchini, Sabyr, Hill et al. (2026)** [arXiv:2512.03038](https://arxiv.org/abs/2512.03038): FIRAS reanalysis with pixel-by-pixel foreground cleaning,
  $`\langle y\rangle=(1.2\pm 2.0)\times 10^{-6}`$ ($`\langle y\rangle\lesssim 5.2\times 10^{-6}`$ at 95% CL) — about **3× tighter** than Fixsen+1996. Claims to rule out several strong-feedback hydro models at $`M\lesssim 10^{14}M_\odot`$. Complementary method paper: [arXiv:2508.04593](https://arxiv.org/abs/2508.04593).

---

## Detection significance

**The mean $`y`$ distortion is not a detection.** FIRAS is an upper limit. The 2026 reanalysis is consistent with Hill+2015’s $`\sim 1.8\times 10^{-6}`$ prediction but does **not** claim a positive detection (the central value sits inside a $`2\times 10^{-6}`$ error bar). Cluster $`y`$-**maps** are detections of *anisotropy*, not of the monopole.

**Open:** a true $`\langle y\rangle`$ detection (PIXIE-class); subtracting the cluster/group contribution to isolate reionization $`y`$; using $`\langle y\rangle`$ as a feedback prior for cosmic shear and kSZ (the 2026 FIRAS paper’s stated science case).

**Key papers:** Fixsen+1996 · Hill+2015 · Abitbol+2017 · Chluba spectral-distortion reviews · Fabbian+2026. [SZ Paper Index](../SZ%20Paper%20Index.md)
