---
tags:
  - SZ
  - tSZ
  - kSZ
  - rSZ
  - rkSZ
  - Compton
aliases:
  - Unified SZ
  - SZ moment hierarchy
  - boost operator SZ
cssclasses:
  - physics
---

# Unified SZ derivation: one collision operator, two expansions

**Related notes:** [SZ Literature Map](SZ%20Literature%20Map.md) · [SZ Paper Index](SZ%20Paper%20Index.md) · *The Physics of tSZ* · *Compton Y parameter and self-similarity* · *The Universal Pressure Profile and A10* · *Pressure Profiles and tSZ PS*

tSZ, kSZ, rSZ, rkSZ, and $\beta^2$-SZ are **not** different scattering processes. They are different orders of the **same** Thomson/Compton collision operator, expanded in thermal motion $\theta_e$ and coherent bulk motion $\beta$.

The 2026 boost-operator papers make this factorization explicit: **thermal-average in the cluster rest frame, then boost back to the CMB frame**.

**Contents:** [1. Only one process: Thomson scattering](#1-only-one-process-thomson-scattering) · [2. Single-electron frequency shift](#2-single-electron-frequency-shift) · [3. Universal single-scattering formula](#3-universal-single-scattering-formula) · [4. Split the electron velocity](#4-split-the-electron-velocity) · [5. The two-parameter expansion](#5-the-two-parameter-expansion) · [6. Differential operators](#6-differential-operators) · [7. tSZ is (m, k) = (0, 1)](#7-tsz-is-m-k-0-1) · [8. rSZ is the next thermal orders](#8-rsz-is-the-next-thermal-orders) · [9. kSZ is (m, k) = (1, 0)](#9-ksz-is-m-k-1-0) · [10. rkSZ is (m, k) = (1, 1)](#10-rksz-is-m-k-1-1) · [11. n_e v^2 is not rkSZ](#11-n_e-v2-is-not-rksz) · [12. Why beta^2 splits into monopole plus quadrupole](#12-why-beta2-splits-into-monopole-plus-quadrupole) · [13. LOS moment hierarchy](#13-los-moment-hierarchy) · [14. Astrophysical fields](#14-astrophysical-fields) · [15. All-orders boost-operator formula](#15-all-orders-boost-operator-formula) · [16. Three-frame picture](#16-three-frame-picture) · [17. Polarization](#17-polarization) · [18. SZ periodic table](#18-sz-periodic-table) · [Assumptions and caveats](#assumptions-and-caveats) · [Reading list](#reading-list)

---

## The claim to keep in mind

$$
\Delta n
=
\tau
\sum_{m=0}^{\infty}
\sum_{k=0}^{\infty}
\beta^{m}\theta_{e}^{k}\,
\mathcal{S}_{mk}(x,\mu),
\qquad
(m,k)=(0,0)\ \text{vanishes}.
$$

Each $(m,k)$ term is one named SZ effect, and each maps onto a line-of-sight moment of the electron phase-space distribution
$$
\int n_e\, T_e^{k}\, v^{m}\, P_{\ell}(\mu)\, dl.
$$

> **Important:** Cold, static electrons do nothing
> A cold electron at rest ($\theta_e=0$, $\beta=0$) Thomson-scattering an isotropic blackbody leaves the radiation field unchanged. That is why the $(0,0)$ cell is identically zero, and why tSZ starts at $\theta_e$, not at $\sqrt{\theta_e}$.

---

## 1. Only one process: Thomson scattering

A CMB photon $(\nu_i,\hat{\mathbf{n}}_i)$ hits an electron with velocity $\boldsymbol{\beta}_e=\mathbf{v}_e/c$.

For cluster SZ,
$$
\frac{h\nu}{m_e c^2}\ll 1.
$$
Even in relativistic SZ, the photon is **not** in the Klein–Nishina regime. Relativistic corrections come from **electron motion and Lorentz transformations**, not from a change of the microscopic cross section.

In the **electron rest frame** the differential cross section is Thomson,
$$
\frac{d\sigma}{d\Omega'}=\frac{3\sigma_T}{16\pi}\bigl(1+\cos^2\Theta'\bigr),
$$
and
$$
\nu'_{\mathrm{out}}=\nu'_{\mathrm{in}}.
$$
The photon energy does **not** change in that frame.

SZ appears only after boosting:
$$
\text{CMB frame}
\longrightarrow
\text{electron frame}
\longrightarrow
\text{Thomson scatter}
\longrightarrow
\text{CMB frame}.
$$
The two Lorentz boosts Doppler-redistribute frequency.

---

## 2. Single-electron frequency shift

Lorentz transform into the electron frame:
$$
\nu'_i=\gamma_e\nu_i\bigl(1-\boldsymbol{\beta}_e\cdot\hat{\mathbf{n}}_i\bigr).
$$
Thomson scatter: $\nu'_f=\nu'_i$. Boost back:
$$
\nu_f=\frac{\nu'_f}{\gamma_e\bigl(1-\boldsymbol{\beta}_e\cdot\hat{\mathbf{n}}_f\bigr)}.
$$
Therefore
$$
\frac{\nu_f}{\nu_i}
=
\frac{1-\boldsymbol{\beta}_e\cdot\hat{\mathbf{n}}_i}{1-\boldsymbol{\beta}_e\cdot\hat{\mathbf{n}}_f}.
$$
This one ratio already contains **every** SZ effect. (Aberration of $\hat{\mathbf{n}}_i,\hat{\mathbf{n}}_f$ is implicit: the scattering angle that enters the Thomson kernel is the electron-frame angle.)

Define the logarithmic shift
$$
s\equiv\ln\frac{\nu_f}{\nu_i}
=
\ln\frac{1-\boldsymbol{\beta}_e\cdot\hat{\mathbf{n}}_i}{1-\boldsymbol{\beta}_e\cdot\hat{\mathbf{n}}_f}.
$$
Expanding in electron speed,
$$
s=\mathcal{O}(\beta_e)+\mathcal{O}(\beta_e^2)+\mathcal{O}(\beta_e^3)+\cdots.
$$
At the microscopic level, SZ is a measurement of **electron velocity moments**.

---

## 3. Universal single-scattering formula

Photon occupation number (Lorentz invariant)
$$
n(x)=\frac{1}{e^{x}-1},\qquad
x\equiv\frac{h\nu}{k_B T_{\mathrm{CMB}}}.
$$
This is the **mean number of photons per mode** (one frequency, one direction, one polarisation), not a number density. Intensity is the same information: $I_{\nu}=(2h\nu^{3}/c^{2})n$. We use $n$ because it is Lorentz invariant, so the collision term is just photons entering/leaving a mode.

Averaging over scattering angles and the electron velocity distribution defines a frequency-redistribution kernel $P(s;\theta_e,\boldsymbol{\beta},\hat{\mathbf{n}})$. In the optically thin, single-scattering limit,
$$
\Delta n(x,\hat{\mathbf{n}})
=
\int d\tau\int ds\, P(s)
\bigl[n(xe^{-s})-n(x)\bigr],
\qquad
d\tau=\sigma_T n_e\, dl.
$$
The first term is gain (photons scattered **into** this frequency from $x e^{-s}$); the second is loss (photons scattered **out** of $x$). $d\tau=\sigma_T n_e dl$ is the scattering probability in a path $dl$: one electron has area $\sigma_T$, so a tube of area $A$ contains $n_e A dl$ electrons and the hit probability is $n_e\sigma_T dl$. $\tau$ is the expected number of scatterings; for a cluster $\tau\sim 10^{-2}$, so $P_{\mathrm{scatter}}\approx\tau$.

This is the most primitive **universal SZ equation**.

The dilation operator $D\equiv x\partial_x$ implements a multiplicative frequency shift:
$$
n(xe^{-s})=e^{-sD}n(x).
$$
Hence
$$
\Delta n
=
\int d\tau\,
\bigl\langle e^{-sD}-1\bigr\rangle n.
$$
Taylor expanding the exponential,
$$
\Delta n
=
\int d\tau
\left[
-\langle s\rangle D
+\frac12\langle s^2\rangle D^2
-\frac16\langle s^3\rangle D^3
+\cdots
\right]n.
$$
That is the physical content of a **generalized Kompaneets / moment expansion**.

Hoey, Long & Chluba (2026) use the opposite-sign energy-shift generator
$$
\hat{\mathcal{O}}_{\nu}\equiv -x\partial_x = -D,
$$
so $e^{-sD}=e^{s\hat{\mathcal{O}}_{\nu}}$. Same physics, opposite generator convention.

---

## 4. Split the electron velocity

Write
$$
\mathbf{v}_e=\mathbf{v}_{\mathrm{bulk}}+\mathbf{u},
\qquad
\langle\mathbf{u}\rangle=0.
$$
$\mathbf{u}$ is thermal (random); $\mathbf{v}_{\mathrm{bulk}}$ is the coherent peculiar velocity of the gas element.

Two small parameters:
$$
\theta_e\equiv\frac{k_B T_e}{m_e c^2},
\qquad
\boldsymbol{\beta}\equiv\frac{\mathbf{v}_{\mathrm{bulk}}}{c}.
$$
For Maxwellian electrons,
$$
\frac{\langle u^2\rangle}{c^2}\simeq 3\theta_e
\quad\Rightarrow\quad
\frac{u}{c}\sim\sqrt{\theta_e}.
$$
Isotropy kills odd thermal moments:
$$
\langle u_i\rangle=0,
\qquad
\langle u_i u_j\rangle\sim\theta_e.
$$
So the first non-vanishing **thermal** term is $\mathcal{O}(\theta_e)$, not $\mathcal{O}(\sqrt{\theta_e})$. Coherent velocity does **not** average to zero, so the first kinematic term is $\mathcal{O}(\beta)$.

| Named effect | Order | Why that order |
| --- | --- | --- |
| tSZ | $\theta_e$ | isotropic $\langle u\rangle=0$; first even moment |
| kSZ | $\beta$ | coherent $\langle v\rangle$ survives |
| rSZ | $\theta_e^2,\theta_e^3,\ldots$ | higher even thermal moments |
| rkSZ | $\beta\theta_e,\beta\theta_e^2,\ldots$ | thermal–kinematic cross terms |
| $\beta^2$-SZ | $\beta^2$ | second-order bulk boost (monopole + quadrupole) |

---

## 5. The two-parameter expansion

$$
\Delta n
=
\tau\sum_{m,k}\beta^{m}\theta_e^{k}\,\mathcal{S}_{mk}(x,\mu),
\qquad
\mu=\hat{\boldsymbol{\beta}}\cdot\hat{\mathbf{n}}.
$$

| Order             | Effect                            | Gas moment                |
| ----------------- | --------------------------------- | ------------------------- |
| $\theta_e$        | tSZ                               | $n_e T_e$                 |
| $\beta$           | kSZ                               | $n_e v_{\parallel}$       |
| $\theta_e^2$      | first rSZ                         | $n_e T_e^2$               |
| $\theta_e^3$      | higher rSZ                        | $n_e T_e^3$               |
| $\beta\theta_e$   | first rkSZ                        | $n_e v_{\parallel} T_e$   |
| $\beta\theta_e^2$ | higher rkSZ                       | $n_e v_{\parallel} T_e^2$ |
| $\beta^2$         | second-order kSZ                  | $n_e v^2$                 |
| $\beta^2\theta_e$ | relativistic $\beta^2$ correction | $n_e v^2 T_e$             |
| $\beta^3$         | third-order kSZ                   | $n_e v^3$                 |

Typical cluster numbers: $\theta_e\sim k_B T_e/(511\,\mathrm{keV})\sim 0.02$ at $10\,\mathrm{keV}$; $\beta\sim 10^{-3}$ at $300\,\mathrm{km\,s^{-1}}$. So $\theta_e\gg\beta$ for massive clusters, but $\beta\theta_e$ can still be a few-percent correction to kSZ in hot, fast systems (e.g. MACS J0717).

---

## 6. Differential operators

$$
\hat{\mathcal{O}}_{\nu}\equiv -x\partial_x,
\qquad
\hat{\mathcal{D}}_{\nu}
\equiv
\hat{\mathcal{O}}_{\nu}^{2}-3\hat{\mathcal{O}}_{\nu}
=
x^{-2}\partial_x\bigl(x^{4}\partial_x\bigr).
$$
$\hat{\mathcal{O}}_{\nu}$ generates a blackbody temperature shift. $\hat{\mathcal{D}}_{\nu}$ is the Kompaneets diffusion operator (energy redistribution at $\mathcal{O}(\theta_e)$).

Through $\mathcal{O}(\theta_e^2,\beta,\beta\theta_e,\beta^2)$, Hoey, Long & Chluba (2026) recover
$$
\begin{aligned}
\frac{\Delta n}{\tau}
&=
\underbrace{\theta_e\,\hat{\mathcal{D}}_{\nu}n_{\mathrm{Pl}}}_{\mathrm{tSZ}}
+
\underbrace{\theta_e^{2}\,\hat{\mathcal{R}}_{20}n_{\mathrm{Pl}}}_{\mathrm{rSZ}}
+
\underbrace{\beta\mu\,\hat{\mathcal{O}}_{\nu}n_{\mathrm{Pl}}}_{\mathrm{kSZ}}
\\
&\quad
+
\underbrace{\beta\mu\theta_e\,\hat{\mathcal{R}}_{11}n_{\mathrm{Pl}}}_{\mathrm{rkSZ}}
+
\underbrace{\frac{\beta^{2}}{3}
\left[
\hat{\mathcal{D}}_{\nu}
+P_2(\mu)\left(\frac{12}{5}\hat{\mathcal{O}}_{\nu}+\frac{11}{10}\hat{\mathcal{D}}_{\nu}\right)
\right]
n_{\mathrm{Pl}}}_{\text{second-order kSZ}}
+\cdots.
\end{aligned}
$$
The leading rkSZ operator is
$$
\hat{\mathcal{R}}_{11}
=
\frac15
\Bigl[
\hat{\mathcal{D}}_{\nu}\bigl(7\hat{\mathcal{O}}_{\nu}-1\bigr)
+2\hat{\mathcal{O}}_{\nu}
\Bigr].
$$
This is $\mathcal{O}(\beta\theta_e)$ and recovers the classical Nozawa et al. (1998) $C_1(x)$ correction.

---

## 7. tSZ is (m, k) = (0, 1)

$$
\Delta n_{\mathrm{tSZ}}
=
\tau\theta_e\,\hat{\mathcal{D}}_{\nu}n_{\mathrm{Pl}}.
$$
Acting on the Planck occupation $n_{\mathrm{Pl}}=(e^{x}-1)^{-1}$,
$$
\hat{\mathcal{D}}_{\nu}n_{\mathrm{Pl}}
=
\frac{xe^{x}}{(e^{x}-1)^{2}}
\left[x\coth\frac{x}{2}-4\right].
$$
Hence the textbook result
$$
\Delta n_{\mathrm{tSZ}}
=
y\,\frac{xe^{x}}{(e^{x}-1)^{2}}
\left[x\coth\frac{x}{2}-4\right],
$$
with Compton parameter
$$
y
=
\int d\tau\,\theta_e
=
\frac{\sigma_T}{m_e c^2}\int dl\, n_e k_B T_e.
$$
So
$$
\mathrm{tSZ}\quad\longleftrightarrow\quad\int n_e T_e\, dl
$$
is only the **first thermal moment** of the universal expansion. See *Compton Y parameter and self-similarity* for the integrated $Y$ and self-similar scaling.

Chluba & Rosenberg write the all-order thermal series as
$$
\Delta n_{\mathrm{th}}
=
\tau\theta_e\sum_{k=0}^{\infty}\theta_e^{k}Y_k(x),
$$
where $Y_0$ is classical tSZ.

---

## 8. rSZ is the next thermal orders

$$
\Delta n_{\mathrm{th}}
=
\tau\bigl[\theta_e Y_0(x)+\theta_e^{2}Y_1(x)+\theta_e^{3}Y_2(x)+\cdots\bigr].
$$
$\theta_e Y_0$ is ordinary tSZ. The rest are relativistic tSZ corrections (observational literature often just says **rSZ**). Itoh et al. (1998) computed high-order $\theta_e$ terms; SZpack / boost-operator methods generate them systematically.

Along the line of sight,
$$
\theta_e^{2}\,d\tau
=
\sigma_T n_e\left(\frac{k_B T_e}{m_e c^2}\right)^{2}dl,
$$
so
$$
\text{first rSZ}\propto\int n_e T_e^{2}\, dl,
\qquad
\mathrm{rSZ}^{(k)}\propto\int n_e T_e^{k+1}\, dl.
$$
rSZ therefore measures **temperature moments**, not just the pressure that ordinary tSZ sees. That is why $y$-weighted temperatures $T_y$ differ from X-ray spectroscopic temperatures — see *Hydrostatic Bias* and Kay et al. (2024).

> **Warning:** Asymptotic series
> The $\theta_e$ expansion is asymptotic. In the Wien tail, $n_{\mathrm{Pl}}\sim e^{-x}$, so high-order frequency derivatives over-correct and the series oscillates. For hot clusters one should use SZpack (or the exact boost-operator form) rather than truncating $Y_k$ by hand.

---

## 9. kSZ is (m, k) = (1, 0)

Set $\theta_e\to 0$ but $\beta\neq 0$. The leading term is
$$
\Delta n_{\mathrm{kSZ}}
=
\tau\beta\mu\,\hat{\mathcal{O}}_{\nu}n_{\mathrm{Pl}}.
$$
Since
$$
\hat{\mathcal{O}}_{\nu}n_{\mathrm{Pl}}
=
\frac{xe^{x}}{(e^{x}-1)^{2}},
$$
this is a pure blackbody temperature shift. With the convention that $\mu$ is the cosine between $\boldsymbol{\beta}$ and the photon direction, and $v_{\parallel}>0$ **away from the observer**,
$$
\frac{\Delta T}{T_{\mathrm{CMB}}}
=
-\int d\tau\,\frac{v_{\parallel}}{c}
=
-\frac{\sigma_T}{c}\int dl\, n_e v_{\parallel}.
$$
Hoey et al. write the same statement as $\Delta T/T_{\mathrm{CMB}}\simeq -\tau\beta_{\mathrm{p}}\mu_{\mathrm{p}}$.

So
$$
\mathrm{kSZ}\quad\longleftrightarrow\quad\int n_e v_{\parallel}\, dl.
$$
No thermal energy is exchanged. The microscopic process is still Thomson scattering.

---

## 10. rkSZ is (m, k) = (1, 1)

If $T_e\neq 0$ **and** $v_{\mathrm{bulk}}\neq 0$, a cross term $\beta\theta_e$ is required:
$$
\Delta n_{\mathrm{rkSZ}}
\sim
\int d\tau\,\beta_{\parallel}\theta_e\, C_1(x)
\quad\longleftrightarrow\quad
\int dl\, n_e v_{\parallel} T_e.
$$
The full kinematic series at finite temperature is
$$
\Delta n_{\mathrm{rkSZ}}
=
\int d\tau\,\beta_{\parallel}
\bigl[C_0(x)+\theta_e C_1(x)+\theta_e^{2}C_2(x)+\cdots\bigr],
$$
where $C_0$ is ordinary kSZ. Strictly,
$$
\mathrm{kSZ}=\beta\theta_e^{0},
\qquad
\mathrm{rkSZ}=\beta\theta_e+\beta\theta_e^{2}+\cdots.
$$
Nozawa, Itoh & Kohyama (1998) computed these mixed terms. For $T_e\sim 10\,\mathrm{keV}$, the $\beta\theta_e$ correction is typically a few percent of kSZ.

---

## 11. n_e v^2 is not rkSZ

A velocity-weighted kSZ moment $\sim n_e v^2$ is physically real, but it is **not** what the literature calls relativistic kSZ.

| Object | Order | Name |
| --- | --- | --- |
| $n_e v_{\parallel} T_e$ | $\beta\theta_e$ | **rkSZ** (leading) |
| $n_e v^2$ | $\beta^2$ | second-order **kinematic** SZ |

$\beta^2$-SZ is interesting because it is no longer a pure dipole.

---

## 12. Why beta^2 splits into monopole plus quadrupole

A bulk boost of an isotropic CMB gives
$$
T'(\mu)=\frac{T}{\gamma(1+\beta\mu)}.
$$
Expanding,
$$
\frac{\Delta T}{T}
\sim
-\beta\mu
+\beta^{2}\left(\mu^{2}-\frac12\right)
+\cdots.
$$
- $\mathcal{O}(\beta)$: dipole $\propto P_1(\mu)$
- $\mathcal{O}(\beta^2)$: $P_0(\mu)+P_2(\mu)$ (monopole + quadrupole)
- $\mathcal{O}(\beta^3)$: $P_1(\mu)+P_3(\mu)$

This is angular-momentum structure, not a coincidence. Hoey et al. (2026), Eq. (3.15):
$$
\begin{aligned}
\hat{\mathcal{S}}_{\mathrm{kin}}
&=
\beta\mu\,\hat{\mathcal{O}}_{\nu}
+\frac{\beta^{2}}{3}
\left[
\hat{\mathcal{D}}_{\nu}
+P_2(\mu)\left(\frac{12}{5}\hat{\mathcal{O}}_{\nu}+\frac{11}{10}\hat{\mathcal{D}}_{\nu}\right)
\right]
\\
&\quad
+\frac{\beta^{3}}{25}
\Bigg[
\mu\bigl(2\hat{\mathcal{O}}_{\nu}-5\hat{\mathcal{D}}_{\nu}+7\hat{\mathcal{O}}_{\nu}\hat{\mathcal{D}}_{\nu}\bigr)
+\frac{P_3(\mu)}{6}\bigl(128\hat{\mathcal{O}}_{\nu}+45\hat{\mathcal{D}}_{\nu}+13\hat{\mathcal{O}}_{\nu}\hat{\mathcal{D}}_{\nu}\bigr)
\Bigg]
+\cdots.
\end{aligned}
$$
The $\beta^3$ terms were first obtained with the boost-operator method (Chluba & Rosenberg 2026); they are usually negligible at typical cluster speeds.

---

## 13. LOS moment hierarchy

Define
$$
\mathcal{M}_{m\ell}^{(k)}
\equiv
\int d\tau\,\theta_e^{k}\beta^{m} P_{\ell}(\mu).
$$
Then
$$
\Delta I_{\nu}
=
\sum_{m,k,\ell}
\mathcal{M}_{m\ell}^{(k)}\, S_{m\ell}^{(k)}(\nu).
$$
For a pure velocity expansion the selection rule is
$$
\ell=m,\, m-2,\, m-4,\,\ldots
$$

| Moment | Integral | Named effect |
| --- | --- | --- |
| $\mathcal{M}_{00}^{(1)}$ | $\int d\tau\,\theta_e$ | tSZ |
| $\mathcal{M}_{00}^{(2)}$ | $\int d\tau\,\theta_e^{2}$ | rSZ |
| $\mathcal{M}_{11}^{(0)}$ | $\int d\tau\,\beta P_1(\mu)$ | kSZ |
| $\mathcal{M}_{11}^{(1)}$ | $\int d\tau\,\beta\theta_e P_1(\mu)$ | rkSZ |
| $\mathcal{M}_{20}^{(0)}$ | $\int d\tau\,\beta^{2}$ | $\beta^2$ monopole |
| $\mathcal{M}_{22}^{(0)}$ | $\int d\tau\,\beta^{2} P_2(\mu)$ | $\beta^2$ quadrupole |

Chluba et al. (2013) organised the same idea as generalized Compton moments $y^{(k)}$ and velocity moments $b^{(k)}$: the LOS-integrated SZ spectrum is completely determined by these moments.

---

## 14. Astrophysical fields

Since $d\tau=\sigma_T n_e\, dl$,
$$
\mathcal{M}_{m\ell}^{(k)}
=
\sigma_T
\int dl\,
n_e
\left(\frac{k_B T_e}{m_e c^2}\right)^{k}
\left(\frac{v}{c}\right)^{m}
P_{\ell}(\mu).
$$
SZ is tomography of electron phase space, $n_e T_e^{k} v^{m} P_{\ell}(\mu)$:

| Probe | Field |
| --- | --- |
| $\tau$ | $n_e$ |
| tSZ | $n_e T_e$ |
| rSZ | $n_e T_e^{2}$, $n_e T_e^{3}$, … |
| kSZ | $n_e v_{\parallel}$ |
| rkSZ | $n_e T_e v_{\parallel}$, $n_e T_e^{2} v_{\parallel}$, … |
| $\beta^2$ SZ | $n_e v^{2}$, $n_e v^{2} P_2(\mu)$ |
| $\beta^2$ rSZ | $n_e T_e v^{2}$, … |

The slogans “tSZ measures pressure, kSZ measures momentum” are the $(k,m)=(1,0)$ and $(0,1)$ corners of this hierarchy. The deeper statement is:

> **Tip:** One-line summary
> **The SZ spectrum measures moments of the electron phase-space distribution.**

---

## 15. All-orders boost-operator formula

Hoey, Long & Chluba (2026), Eq. (3.12), for single scattering of an unpolarized CMB monopole:
$$
\Delta n
=
\tau\,
\hat{\mathcal{S}}_{\mathrm{SZ}}(\nu,\hat{\boldsymbol{\gamma}},\theta_e,\boldsymbol{\beta}_{\mathrm{p}})\,
n^{\mathrm{Pl}},
$$
with Legendre decomposition
$$
\hat{\mathcal{S}}_{\mathrm{SZ}}
=
\sum_{\ell=0}^{\infty}
P_{\ell}(\hat{\boldsymbol{\gamma}}\cdot\hat{\boldsymbol{\beta}}_{\mathrm{p}})\,
\hat{\mathcal{S}}_{\ell}(\nu,\theta_e,\beta_{\mathrm{p}})
$$
and
$$
\hat{\mathcal{S}}_{\ell}
=
\sqrt{2\ell+1}
\sum_{\ell'}
\hat{\mathcal{D}}^{0}_{\ell\ell'0}(\nu,\beta_{\mathrm{p}})\,
\hat{\mathcal{S}}^{\mathrm{th}}_{\ell'}(\nu,\theta_e).
$$

The factorization is the whole point:
$$
\underbrace{\hat{\mathcal{S}}^{\mathrm{th}}_{\ell'}(\theta_e)}_{\text{thermal electron physics}}
\times
\underbrace{\hat{\mathcal{D}}_{\ell\ell'0}(\beta)}_{\text{bulk Lorentz boost}}.
$$
This is exact (single-scattering, unpolarized) to **all orders** in $\theta_e$ and $\beta$. The thermal operators depend only on $\theta_e$; the Doppler operators depend only on $\beta$. One may expand either independently.

In the CMB-frame calculation the electron distribution is an **anisotropic** relativistic Maxwellian, so $\theta_e$ and $\beta$ are entangled inside the integrals. Doing the thermal average in the cloud frame first removes that entanglement.

The thermal operators themselves are Doppler-operator averages over a relativistic Maxwellian (Hoey et al., Eq. 3.1b):
$$
\hat{\mathcal{S}}^{\mathrm{th}}_{\ell}(\nu,\theta_e)
=
\int_0^{\infty} p^{2} f(\gamma)\, dp
\left[
\frac{\hat{\mathcal{D}}_{\ell 0\ell}}{2\ell+1}
+\frac{1}{10}\frac{\hat{\mathcal{D}}_{\ell 2\ell}}{2\ell+1}
-1
\right],
$$
$$
f(\gamma)=\frac{e^{-\gamma/\theta_e}}{\theta_e K_2(1/\theta_e)}.
$$
The $1$ and $1/10$ weights are Thomson: monopole scattering plus the $\ell=2$ anisotropy of $1+\cos^2\Theta$.

---

## 16. Three-frame picture

```mermaid
flowchart LR
  CMB[CMB frame] --> Cluster[cluster frame]
  Cluster --> eRest[electron frame]
  eRest --> Out[observed Delta n]
```

$$
\text{CMB frame}
\overset{\beta_{\mathrm{bulk}}}{\longrightarrow}
\text{cluster frame}
\overset{u_{\mathrm{thermal}}}{\longrightarrow}
\text{electron frame}.
$$
In the individual electron frame: **just Thomson scattering**. Then reverse the boosts.

| Motion | Averages | Named series |
| --- | --- | --- |
| thermal, random | $\langle u\rangle=0$, $\langle u^2\rangle\neq 0$ | tSZ + rSZ |
| bulk, coherent | $\langle v\rangle\neq 0$ | kSZ + higher kSZ |
| both | mixed | rkSZ, $\beta^{2}\theta_e$, … |

Mathematically:
$$
\text{one collision operator}
\quad+\quad
\text{double expansion in }(\theta_e,\beta).
$$

---

## 17. Polarization

Polarized SZ is the same scattering/boost hierarchy, with the photon field extended from spin-$0$ intensity to spin-$\pm 2$.

Thomson scattering responds to an incident **quadrupole**. A bulk boost of the CMB monopole produces
$$
\mathcal{O}(\beta):\ \text{dipole},
\qquad
\mathcal{O}(\beta^2):\ \text{quadrupole}.
$$
That kinematic quadrupole Thomson-scatters into
$$
Q\pm iU\sim\tau\beta_{\perp}^{2}.
$$
A primordial CMB quadrupole gives
$$
Q\pm iU\sim\tau a_{2m}.
$$
Thermal corrections then supply $\theta_e\beta^2$, etc. Rosenberg & Chluba (2026) extend the boost-operator formalism to this case.

---

## 18. SZ periodic table

|  | $\theta_e^{0}$ | $\theta_e^{1}$ | $\theta_e^{2}$ | $\theta_e^{3}$ | $\cdots$ |
| --- | --- | --- | --- | --- | --- |
| $\beta^{0}$ | $0$ | **tSZ** | rSZ$_1$ | rSZ$_2$ | $\cdots$ |
| $\beta^{1}$ | **kSZ** | **rkSZ$_1$** | rkSZ$_2$ | rkSZ$_3$ | $\cdots$ |
| $\beta^{2}$ | kSZ$^{(2)}$ | rkSZ$^{(2,1)}$ | $\cdots$ |  |  |
| $\beta^{3}$ | kSZ$^{(3)}$ | $\cdots$ |  |  |  |

Each cell is one astrophysical moment,
$$
\beta^{m}\theta_e^{k}
\quad\Longleftrightarrow\quad
\int dl\, n_e\, v^{m}\, T_e^{k}\times\text{(angular moment)}.
$$
tSZ starts at $k=1$. The cold/static $(0,0)$ cell produces no distortion.

---

## Assumptions and caveats

Keep these in view while reviewing the derivation.

1. **Single scattering / optically thin.** Multiple scatterings exist (Chluba, Dai & Kamionkowski 2014) and are a separate expansion in $\tau$.
2. **Thomson limit.** Recoil $\propto h\nu/m_e c^2$ is dropped. That is excellent for CMB photons; it is not a statement about electron relativity.
3. **Unpolarized incoming radiation** in the Hoey (2026) all-orders formula. Polarization is an extension, not a different collision term.
4. **Lab frame = CMB rest frame.** Observer motion (Chluba, Hütsi & Sunyaev 2005) is another boost.
5. **Maxwellian electrons** in the cloud frame. Non-thermal tails change the thermal operators $\hat{\mathcal{S}}^{\mathrm{th}}_{\ell}$.
6. **Constant $\beta_{\mathrm{p}}$ along the LOS** in the operator derivation. Spatially varying velocity is restored by integrating $\mathcal{M}_{m\ell}^{(k)}$ along the ray.
7. **$\theta_e$ series is asymptotic.** High-$x$ / high-$T_e$ needs the exact operator or SZpack, not a truncated $Y_k$.

---

## Reading list

Read in this order if the goal is the **unified** viewpoint rather than separate tSZ/kSZ chapters.

| Priority | Paper | Why |
| --- | --- | --- |
| ★★★ | Hoey, Long & Chluba (2026) — [arXiv:2608.07404](https://arxiv.org/abs/2608.07404) | Thermal average in the cloud frame, then boost. All-orders $\hat{\mathcal{S}}_{\mathrm{SZ}}$. Recovers $C_1$ and $\beta^3$. **Start here.** |
| ★★★ | Chluba & Rosenberg (2026) — [arXiv:2508.20659](https://arxiv.org/abs/2508.20659), [MNRAS](https://academic.oup.com/mnras/article/547/1/stag240/8475325) | Full boost-operator machinery; generates arbitrary $(\theta_e,\beta)$ order. |
| ★★☆ | Chluba et al. (2012) — [arXiv:1205.5778](https://arxiv.org/abs/1205.5778) | SZpack: thermal, kinematic, dipole/quadrupole scattering. |
| ★★☆ | Chluba et al. (2013) — [arXiv:1211.3206](https://arxiv.org/abs/1211.3206) | Temperature–velocity **moment method**. Directly $\int d\tau\,\theta_e^{k}\beta^{m}$. |
| ★★☆ | Itoh, Kohyama & Nozawa (1998) — [arXiv:astro-ph/9712289](https://arxiv.org/abs/astro-ph/9712289) | Classical $\theta_e$ expansion (rSZ). |
| ★★☆ | Nozawa, Itoh & Kohyama (1998) — [arXiv:astro-ph/9804051](https://arxiv.org/abs/astro-ph/9804051) | Classical $\beta\theta_e^{k}$ relativistic-kSZ expansion. |
| ★☆☆ | Chluba & Ravenni (2025) — [arXiv:2505.02080](https://arxiv.org/abs/2505.02080) | Boost operator as a mathematical object (aberration kernel, recurrences). |
| ★☆☆ | Rosenberg & Chluba (2026) — polarized SZ, MNRAS `stag331` | Same hierarchy for $Q\pm iU$. |
| ★☆☆ | Sazonov & Sunyaev (1998/1999); Challinor & Lasenby (1998) | Independent early relativistic calculations. |

Mathematica notebooks for the 2026 operator expansions: [chluba.de/Mathematica](http://www.chluba.de/Mathematica).

---

## Why this matters for the rest of the notebook

If SZ is an electron phase-space moment expansion, then tSZ, rSZ, and kSZ are not three independent probes. They are a hierarchy
$$
\int n_e\, T_e^{k}\, v^{m}\, P_{\ell}(\mu)\, dl.
$$
The observational question for next-generation multifrequency CMB (SO, CMB-S4, AtLAST, CMB-HD) is: **which $(k,m,\ell)$ moments can actually be separated**, and which of those constrain feedback, temperature structure, bulk/turbulent velocity, and cosmology independently.

That is a sharper question than “measure kSZ” or “measure pressure”. It also clarifies why $n_e v^2$ (turbulent / second-order kinematic) and $n_e v_{\parallel} T_e$ (rkSZ) must not be conflated.

---

## Review checklist

- [ ] Reproduce $\nu_f/\nu_i$ from two Lorentz boosts plus Thomson ($\nu'_{\mathrm{out}}=\nu'_{\mathrm{in}}$)
- [ ] Show why $(m,k)=(0,0)$ vanishes for an isotropic blackbody
- [ ] Show why tSZ starts at $\theta_e$ rather than $\sqrt{\theta_e}$
- [ ] Derive $\hat{\mathcal{D}}_{\nu}n_{\mathrm{Pl}}$ and recover the classical $y$-distortion
- [ ] Derive $\hat{\mathcal{O}}_{\nu}n_{\mathrm{Pl}}$ and recover $\Delta T/T=-\tau\beta\mu$
- [ ] State the difference between $n_e v_{\parallel}T_e$ (rkSZ) and $n_e v^2$ ($\beta^2$-SZ)
- [ ] Explain why $\beta^2$ contains $P_0$ and $P_2$
- [ ] Write $\Delta n=\tau\hat{\mathcal{S}}_{\mathrm{SZ}}n^{\mathrm{Pl}}$ and identify the thermal vs Doppler factors
- [ ] List the assumptions (single scattering, Thomson, CMB frame, Maxwellian)

---

*Created 2026-08-13. Equations checked against Hoey, Long & Chluba, [arXiv:2608.07404](https://arxiv.org/abs/2608.07404).*
