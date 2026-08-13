---
tags:
  - SZ
  - rkSZ
  - literature
aliases:
  - rkSZ literature
  - beta2 SZ
---

# rkSZ and higher kinematic terms

**Hub:** [SZ Literature Map](../SZ%20Literature%20Map.md) · **Physics:** [Unified SZ Derivation](../Unified%20SZ%20Derivation.md#10-rksz-is-m-k-1-1) · [Unified SZ Derivation](../Unified%20SZ%20Derivation.md#11-n_e-v2-is-not-rksz)

This note covers every $\beta^{m}\theta_e^{k}$ cell with $m\ge 1$ except leading kSZ: **rkSZ**, **$\beta^2$**, **$\beta^3$**, mixed $\beta^2\theta_e$.

---

## rkSZ — $\beta\theta_e$

**Moment:** $\int n_e v_\parallel T_e\,dl$. Spectrum: not a pure blackbody; Nozawa et al. (1998) $C_1(x)$. Operator (Hoey+2026):
$\hat{\mathcal{R}}_{11}=\frac15[\hat{\mathcal{D}}_{\nu}(7\hat{\mathcal{O}}_{\nu}-1)+2\hat{\mathcal{O}}_{\nu}]$.

At $T_e\sim 10\,\mathrm{keV}$ this is **a few percent of kSZ**. For MACS J0717 ($T\sim 20\,\mathrm{keV}$, $v\sim 3000\,\mathrm{km\,s^{-1}}$) it is a relevant systematic on the velocity.

**Literature:** Nozawa, Itoh & Kohyama (1998); Sazonov & Sunyaev (1998); Challinor & Lasenby (1999); Chluba+2012 (SZpack); Chluba & Rosenberg (2026); Hoey, Long & Chluba (2026) recover $C_1$.

**Detection:** **none.** It is included in forward models of hot mergers, not measured as its own spectrum.

---

## $\beta^2$-SZ — second-order kinematic

**Moment:** $\int n_e v^2\,dl$ and $\int n_e v^2 P_2(\mu)\,dl$. Angular structure: **monopole + quadrupole**, not a dipole.

A bulk boost of a blackbody:
$\Delta T/T\sim -\beta\mu+\beta^2(\mu^2-1/2)+\cdots$.

Hoey+2026:
$$
\frac{\beta^2}{3}\left[\hat{\mathcal{D}}_{\nu}+P_2(\mu)\left(\frac{12}{5}\hat{\mathcal{O}}_{\nu}+\frac{11}{10}\hat{\mathcal{D}}_{\nu}\right)\right].
$$
The monopole piece looks Kompaneets-like (can leak into tSZ/rSZ at the null). The quadrupole is a distinct anisotropy.

Nozawa+1998 already argued $\mathcal{O}(\beta^2)$ is “very small and can be safely neglected” for typical clusters. Forecasts: Lee/Chluba-style and [Forecasts and Simulations for Relativistic Corrections (arXiv:2504.18637)](https://arxiv.org/abs/2504.18637).

**This is not rkSZ.** $n_e v^2$ is $\beta^2$; $n_e v_\parallel T_e$ is rkSZ.

**Detection:** **none.**

---

## $\beta^3$ and mixed $\beta^2\theta_e$

$\beta^3$ produces $P_1$ and $P_3$. First obtained systematically with boost operators (Chluba & Rosenberg 2026; Hoey+2026). Negligible at $v\sim 300\,\mathrm{km\,s^{-1}}$; conceivably relevant in $3000\,\mathrm{km\,s^{-1}}$ mergers if spectra are measured at the 0.1% level.

$\beta^2\theta_e$: relativistic correction to the second-order kinematic term. Theory only.

---

## Observer motion

A separate boost: the Solar System moves at $\beta_{\odot}\simeq 1.2\times 10^{-3}$. Chluba, Hütsi & Sunyaev (2005); Nozawa+2005. Dipolar modulation of SZ cluster counts; distortion of the CMB dipole spectrum (Balashev+2015). Must be in the model; not a cluster probe.

---

## Detection significance

| Term | Status |
| --- | --- |
| rkSZ | not detected; few-% systematic on kSZ in hot systems |
| $\beta^2$ monopole/quadrupole | not detected |
| $\beta^3$ | not detected |
| observer boost | modelled, not a detection |

**Open:** can AtLAST / CMB-HD separate $\beta^2$ monopole from rSZ at the null? Can rkSZ be seen as a $T_e$-dependent residual in stacked kSZ spectra?

**Key papers:** Nozawa+1998 · Chluba+2005 · Chluba+2012 · Chluba & Rosenberg 2026 · Hoey+2026 · arXiv:2504.18637. [SZ Paper Index](../SZ%20Paper%20Index.md)
