---
id: nbpho-2015-intl-theory-2
olympiad: NbPhO
year: 2015
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "2"
title: "Holographic lens"
points: 7
aliases: ["Holographic lens"]
topics: ["[[6.5 Волновая оптика]]", "[[6.2 Преломление]]", "[[6.3 Линзы]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Исследовать зонную пластинку и стеклянную линзу, фокусирующие световые импульсы."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 2. HOLOGRAPHIC LENS (7 points)

**NbPhO 2015** · Международная олимпиада · теория · 10–12 класс · задача 2  
Источник: [[_pdf/NbPhO/nbpho-2015.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2015.pdf#page=6|решение, стр. 6]]

Темы: [[6.5 Волновая оптика]], [[6.2 Преломление]], [[6.3 Линзы]]

> [!abstract] Кратко (составлено моделью)
> Исследовать зонную пластинку и стеклянную линзу, фокусирующие световые импульсы.

*(by J. Kalda)*

Monochromatic light can be focused into a point using an holographic lens (better known as a Fresnel zone plate). This is a thin film which has a system of opaque and transparent concentric rings: the opaque rings obstruct those light waves which would arrive at the focus in the opposite phase (as compared with the light from the transparent rings). In what follows, let us assume that the diameter and focal length of such a lens $d=f=10\mathrm{cm}$; the wavelength of the monochromatic incident light radiation is $\lambda=5\times10^{-7}\mathrm m$.

**i)** (1.5 points) Starting enumeration from the (opaque) centre of the lens, what is the radius of the $m$-th transparent ring (more precisely, the circle at the middle of the ring)?

**ii)** (1.5 points) Let us consider also a glass lens of the same focal length $f$ and diameter $d$, such that a parallel incident beam is collected perfectly into the focus (has aspheric surfaces). What is the minimal possible thickness of such a lens if the coefficient of refraction of the glass is $n=1.5$?

**iii)** (2 points) If a short light pulse falls onto a lens, the behaviour of the holographic lens is very different from that of the glass lens. Indeed, if we ignore the dispersion of the glass (the dependence of $n$ on the wavelength), the pulse duration at the focus of the glass lens is the same as that of the incident beam. Meanwhile, in the case of a short pulse ($\tau=3\times10^{-14}\mathrm s$), the pulse duration at the focus of the holographic lens becomes significantly dilated. Sketch qualitatively the light intensity $I$ at the focus of the holographic lens as a function of time. A scale is required for time $t$, but not for $I$. The speed of light $c=3\times10^8\mathrm{m/s}$.

**iv)** (1 point) Even if the light source is an ideal laser providing a perfectly monochromatic radiation, the short pulse is no longer strictly monochromatic. Estimate the width of the range of wavelengths in the pulse of duration $\tau$.

**v)** (1 point) Estimate the duration of this light pulse in the focus of the glass lens. Assume that in the glass, the light wave group velocity $v_g$ depends on the wavelength at the rate $\frac{\mathrm dv_g}{\mathrm d\lambda}=0.02\times\frac{v_g}{\lambda}$ and that for the wavelength $\lambda$, group speed is equal to the phase speed.

> [!answer]- Ответ
> **i** — $r_{2m+1}=\sqrt{\left(m+\frac12\right)^2\lambda^2+(2m+1)\lambda f}$.
>
> **ii** — $x=\frac1{n-1}\left[\sqrt{\left(\frac d2\right)^2+f^2}-f\right]\approx2.4\mathrm{cm}$.
>
> **iii** — $\tau_\mathrm{hol}=N_{\max}\frac\lambda c=\frac2c\left[\sqrt{\left(\frac d2\right)^2+f^2}-f\right]\approx7.9\times10^{-9}\,\mathrm{s}$.
>
> **iv** — $\Delta\lambda\approx\left|\frac d{dp}\frac hp\right|\Delta p=\frac{h\Delta p}{p^2}=\frac{h\frac\hbar{c\tau}}{\left(\frac h\lambda\right)^2}=\frac{\lambda^2}{2\pi c\tau}\approx4.4\times10^{-9}\,\mathrm{m}$.
>
> **v** — $\tau_\mathrm{gl}=\tau+\Delta t=5.1\times10^{-14}\,\mathrm{s}$.

> [!solution]- Решение
> # 2. HOLOGRAPHIC LENS
>
> **i)** Let $N=0,1,\ldots$ number the zones (both opaque and transparent). The optical path difference between two neighbouring zones must be $\lambda/2$ (opposite phase is demanded). The path difference between the $N$th zone and the 0th zone, on the other hand, is $\Delta_N=\sqrt{r_N^2+f^2}-f$. Therefore, $\frac{N\lambda}{2}=\sqrt{r_N^2+f^2}-f$ and $r_N=\sqrt{\left(\frac{N\lambda}{2}\right)^2+N\lambda f}$. Only odd-numbered zones are transparent, thus we need
> $r_{2m+1}=\sqrt{\left(m+\frac12\right)^2\lambda^2+(2m+1)\lambda f}$.
>
> **ii)** A perfectly focussing glass lens is such that all the possible light rays that go to the focus have an equal optical path length. The optical path length inside a refracting medium is $n$ times longer than the corresponding geometric length (the phase velocity is slowed down by a factor of $n$). Denote the sought-after thickness by $x$. Equate the optical path lengths of a ray through the edge of the lens and of a ray through its centre: $\sqrt{\left(\frac d2\right)^2+f^2}=f-x+nx\implies$
> $x=\frac1{n-1}\left[\sqrt{\left(\frac d2\right)^2+f^2}-f\right]\approx2.4\mathrm{cm}$.
>
> **iii)** Firstly, note that the given pulse is short enough that the whole lens never illuminates the focus — the pulse is only $\frac{\tau c}{\lambda}=18$ periods long, but $r_{2\times18}\approx1.3\mathrm{mm}\ll5\mathrm{cm}$. This implies that only a thin strip of the lens is illuminating the focus at a time. The intensity, when the $N$th period is being observed, is proportional to the area of the $N$th zone. This is $A_N=\pi(r_{N+1}^2-r_N^2)=\pi\left(\frac{N\lambda^2}{2}+\frac{\lambda^2}{4}+\lambda f\right)$.
>
> As $N$ is proportional to time (the period of the wave is constant), the intensity will also grow linearly in time. The linear part starts at $N=1$ with a jump and ends at $N_{\max}\frac\lambda2=\sqrt{\left(\frac d2\right)^2+f^2}-f$ with a jump back into darkness, when the light from the edge of the lens arrives. The total duration of illumination is (approximately)
> $\tau_\mathrm{hol}=N_{\max}\frac\lambda c=\frac2c\left[\sqrt{\left(\frac d2\right)^2+f^2}-f\right]\approx7.9\times10^{-9}\,\mathrm{s}$.
>
> **iv)** The pulse is localized into a region of space with a width $\Delta x=c\tau$. Because of the Heisenberg’s uncertainty principle, the pulse is composed of photons with a range of momenta (if we take the picture that the properties of the individual photons are classical) or, from a different viewpoint, is a single photon with a somewhat uncertain momentum; either way, the characteristic width in the momentum space is $\Delta p=\frac\hbar{\Delta x}=\frac\hbar{c\tau}$. The wavelength of a photon, whose momentum $p$ is known, is $\lambda=\frac hp$ (this is the de Broglie relation: the photon’s energy is $pc$ and also $h\nu=\frac{hc}{\lambda}$). Thus,
> $\Delta\lambda\approx\left|\frac d{dp}\frac hp\right|\Delta p=\frac{h\Delta p}{p^2}=\frac{h\frac\hbar{c\tau}}{\left(\frac h\lambda\right)^2}=\frac{\lambda^2}{2\pi c\tau}\approx4.4\times10^{-9}\,\mathrm{m}$.
>
> **v)** The spread of the arrival times of waves with different wavelengths is the largest for the waves that spend the longest time inside the lens. Therefore it is enough to consider only the waves that go through the thickest part of the lens — its centre. The spread in the arrival times is $\Delta t=\Delta\frac{x}{v_g}=\frac{x\Delta v_g}{v_g^2}=\frac{x\Delta\lambda}{v_g^2}\frac{dv_g}{d\lambda}$. To find the group velocity $v_g$ itself, we can use the hint (given during the examination) that in this question we may assume the group velocity and the phase velocity to be equal (in reality it would be an unusual coincidence): $v_g=v_p$ and the phase velocity $v_p=c/n$. Therefore, $\Delta t=\frac{x\Delta\lambda}{v_g^2}\times0.02\frac{v_g}{\lambda}=0.02\frac{xn\Delta\lambda}{c\lambda}\approx2.1\times10^{-14}\,\mathrm{s}$. The total observed pulse length behind the glass lens is
> $\tau_\mathrm{gl}=\tau+\Delta t=5.1\times10^{-14}\,\mathrm{s}$.
