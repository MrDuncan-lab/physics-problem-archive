---
id: nbpho-2025-intl-theory-8
olympiad: NbPhO
year: 2025
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "8"
title: "Phase Spiral"
points: 9
authors: ["Taavet Kalda"]
aliases: ["Phase Spiral"]
topics: ["[[1.20 Колебания]]", "[[1.21 Фазовые диаграммы колебательных систем]]", "[[1.17 Законы сохранения энергии и импульса]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: true
source_damaged: false
summary: "По фазовой спирали звёзд оценить гравитационный потенциал, плотность вещества и время возмущения Галактики."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 8. Phase Spiral (9 points) — Taavet Kalda.

**NbPhO 2025** · Международная олимпиада · теория · 10–12 класс · задача 8  
Источник: [[_pdf/NbPhO/nbpho-2025.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2025.pdf#page=9|решение, стр. 9–10]]

Темы: [[1.20 Колебания]], [[1.21 Фазовые диаграммы колебательных систем]], [[1.17 Законы сохранения энергии и импульса]]

> [!abstract] Кратко (составлено моделью)
> По фазовой спирали звёзд оценить гравитационный потенциал, плотность вещества и время возмущения Галактики.

Here we shall study the motion of Milky Way stars in the Solar neighbourhood in the direction of the $z$-axis, i.e. perpendicular to the galactic plane. For our purposes, we can model the galactic gravity field as being created by a continuous mass density $\rho$ (that accounts for the masses of stars, dark matter, gas, interstellar dust, etc), and assume that this mass forms an infinite mirror-symmetric plate, i.e. $\rho \equiv \rho(z)$ and $\rho(z) = \rho(-z)$ is independent of $x$ and $y$. Throughout the problem, you may assume that each star’s total energy is conserved over the entire considered time period. Gravitational constant $G = 6.67 \times 10^{-11}\,\mathrm{m^3\,kg^{-1}\,s^{-2}} = 4.30 \times 10^{-3}\,\mathrm{pc}\,\mathrm M_\odot^{-1}(\mathrm{km/s})^2$.

**i)** (1 point) Assuming that the mass density is constant over the plate’s thickness, i.e. $\rho(z) = \rho_0$, what is the acceleration $a_z$ of a star at a distance $z$ from the mid-plane?

**ii)** (0.5 points) Consider a star that starts with zero velocity at a distance of $z = a$ from the mid-plane. With what period does it start oscillating around the mid-plane?

In reality, density decreases with growing $|z|$. Measuring density has been a great challenge because of contributions from dark and other difficult-to-see matter. Here, we consider a breakthrough method of doing it. Consider the distributions of the stars in our neighbourhood on the $z$–$v_z$ phase plane, where each star is a dot with coordinates $(v_z,z)$; $v_z$ denotes the $z$-component the star’s velocity, and $z$ – the vertical coordinate. Initially, these dots were distributed nearly homogeneously, but some time ago, the Milky Way was perturbed externally, probably by a passing-by dwarf galaxy; this shuffled the positions and velocities of stars, creating a bar-shaped overdensity region. When moving within that bar-shaped region from the centre to the periphery, the total energy per mass of stars increased monotonously. Over time, this overdensity region started “winding up”, due to the oscillation periods of stars in the vertical plane depending on their oscillation amplitude $z_m$, and evolved into a spiral pictured below (Antoja et al. 2018, Nature 561, 360). An observation that you need to exploit below is that the ordering of stars by energies along the spiral today remains the same as it was at the time of perturbation.

The oscillation period of stars depends on the amplitude $z_m$ because the gravitational potential (the potential energy per mass) $\Phi(z)$ is not parabolic. In such a case, the period can be approximately found by substituting the real $\Phi(z)$ with a $kz^2$ matching $\Phi(z)$ at $z = z_m$, i.e. with $k = \Phi(z_m)/z_m^2$.

![[nbpho-2025-p2-c5047.png]]

**iii)** (2.5 points) At the intersection points of the spiral with $v_z = 0$, calculate $\Phi(z)$ by interpolating data linearly where appropriate; plot your results (this follows the analysis of Guo et al. 2024, ApJ, 960, 133).

**iv)** (1 point) Assuming that the mass density is almost constant for $|z| \leq 0.3\,\mathrm{kpc}$, what is the mass density near $z = 0$?

**v)** (2 points) Dark matter is an “invisible” form of matter that only interacts by gravity. In general, it is found that dark matter forms halos that extend significantly farther than visible matter structures. By assuming that the dark matter density doesn’t vary significantly within the volume of interest and that it starts dominating far away from the galactic plane, from around $z = 0.7\,\mathrm{kpc}$, estimate the local dark matter density $\rho_\mathrm{DM}$.

**vi)** (2 points) How long ago did the perturbation occur?

> [!answer]- Ответ
> **i**
>
> $$
> a_z = -4\pi G\rho_0z.
> $$
>
> **ii**
>
> $$
> T = \frac{2\pi}{\sqrt{4\pi G\rho_0}} = \sqrt{\frac{\pi}{G\rho_0}}.
> $$
>
> **iv**
>
> $$
> \rho_0 = \frac{\Phi(z_1)}{2\pi Gz_1^2} = 6.1\times10^{-21}\,\mathrm{kg/m^3} = 0.090\,\mathrm M_\odot/\mathrm{pc^3}.
> $$
>
> **v**
>
> $$
> \rho_\mathrm{DM} \approx \frac1{2\pi G(z_6-z_5)}\left(\frac{\Phi(z_6)}{z_6}-\frac{\Phi(z_5)}{z_5}\right) = 7.7\times10^{-22}\,\mathrm{kg/m^3} = 0.011\,\mathrm M_\odot/\mathrm{pc^3}.
> $$
>
> **vi**
>
> $$
> T_0 = 2.5\frac{2\pi}{\omega(z_6)-\omega(z_5)} = 5\pi\left(\sqrt{2\Phi(z_1)/z_1^2}-\sqrt{2\Phi(z_6)/z_6^2}\right)^{-1} = 1.9\times10^{16}\,\mathrm s = 620\,\mathrm{Myr}.
> $$

> [!solution]- Решение
> # 8. Phase Spiral (9 points) — Taavet Kalda.
>
> **i)** (1 point) Gravitational acceleration obeys Gauss’ law, i.e., the number of field lines passing through a closed surface is proportional to the enclosed mass. We can see from the example of a point mass $M$ that $\oint g\,dA = 4\pi GM$. Applied for the case of an infinite plane with constant density with a cuboid of area $A$ and half-thickness $z$, we get $-2a_zA = 4\pi G2Az\rho_0$ so
>
> $$a_z = -4\pi G\rho_0z.$$
>
> **ii)** (0.5 points) The acceleration is proportional to displacement and therefore corresponds to a harmonic oscillator. The period of oscillation is thus
>
> $$T = \frac{2\pi}{\sqrt{4\pi G\rho_0}} = \sqrt{\frac{\pi}{G\rho_0}}.$$
>
> **iii)** (2.5 points) If we follow the trajectory of a single star that lies on the spiral, we would find it oscillating around the mid-plane with some period $T(z)$ that decreases with increasing $z$. Over the course of an orbit, the energy per unit mass is conserved and is given by $E = v_z^2/2+\Phi(z)$. We know that near the mid-plane, the gravitational potential is minimal and equal to zero, so $v_z$ is maximal and the kinetic energy is equal to the total energy. Hence, we know the total energy of stars at the seven intersection points of the spiral with $z = 0$. Similarly, when $v_z = 0$, the kinetic energy is minimal and equal to zero, so the total energy is equal to $\Phi(z)$ at those points.
>
> As one traces the various intersection points with $v_z = 0$ and $z = 0$ along the spiral, the maximal extent of the orbit keeps increasing. To the first order, if we assume that the maximal extent increases linearly with each crossing, we can find the potential energy of the crossings of $v_z = 0$ as the average between the kinetic energies of the previous and subsequent crossing over $z = 0$. This allows us to determine the potential energy at all the crossings with $v_z = 0$, as tabulated and plotted below.
>
> | $i$ | $z_i$ (kpc) | $\Phi(z_i)$ ($\mathrm{km^2/s^2}$) |
> |---|---|---|
> | 1 | 0.27 | 180 |
> | 2 | 0.39 | 330 |
> | 3 | 0.54 | 530 |
> | 4 | 0.72 | 800 |
> | 5 | 0.97 | 1200 |
> | 6 | 1.34 | 1800 |
>
> ![[nbpho-2025-p9-c5116.png]]
>
> **iv)** (1 point) For a harmonic oscillator, the potential energy would grow as $z^2$. Based on the plot of potential energy we obtained, it seems to grow roughly quadratically in the beginning, and then transition into a more linear regime, implying that smaller values of $z$ have more uniform $\rho$. Taking the first value of $\Phi(z_1) = 180\,\mathrm{km^2/s^2}$ that we obtained, we can estimate the mid-plane density. From the first part, $\Phi(z) = \int a_z dz = 2\pi G\rho_0z^2$ and so
>
> $$\rho_0 = \frac{\Phi(z_1)}{2\pi Gz_1^2} = 6.1\times10^{-21}\,\mathrm{kg/m^3} = 0.090\,\mathrm M_\odot/\mathrm{pc^3}.$$
>
> **v)** (2 points) We can compute the enclosed surface density $\Sigma(z)$ between $0 < z$ by using the previous harmonic oscillator estimate. With the constant density approximation, the surface density is $\Sigma(z) = \rho_0z = \Phi(z)/(2\pi Gz)$.
>
> *Of course, here, $\rho_0$ is a placeholder variable while using the constant profile approximation to simplify the calculus. The final result is expected to deviate from the true value by a numerical factor that’s close to unity.*
>
> Assuming that dark matter density dominates far away, we can use the difference between the farthest two datapoints at $z_5$ and $z_6$ to estimate the dark matter density via
>
> $$\Sigma(z_6)-\Sigma(z_5) = \rho_\mathrm{DM}(z_6-z_5) = \frac1{2\pi G}\left(\frac{\Phi(z_6)}{z_6}-\frac{\Phi(z_5)}{z_5}\right).$$
>
> Thus,
>
> $$\rho_\mathrm{DM} \approx \frac1{2\pi G(z_6-z_5)}\left(\frac{\Phi(z_6)}{z_6}-\frac{\Phi(z_5)}{z_5}\right) = 7.7\times10^{-22}\,\mathrm{kg/m^3} = 0.011\,\mathrm M_\odot/\mathrm{pc^3}.$$
>
> Dark matter therefore makes up around $\rho_\mathrm{DM}/\rho_0 = 13\%$ of the total local matter budget.
>
> **vi)** (2 points) We can estimate the time of the perturbation by using the winding rate between two points on the spiral and how many full turns around the origin they have made relative to each other. Using the harmonic estimate, firstly, $\rho_0 = \Phi(z)/(2\pi Gz^2)$ and secondly the angular frequency is
>
> $$\omega(z) = \sqrt{4\pi G\rho_0} = \sqrt{2\Phi(z)/z^2}.$$
>
> By, for example, picking points $z_1$ and $z_6$ and seeing that they have 2.5 full turns between them, we can express how long ago the perturbation happened:
>
> $$T_0 = 2.5\frac{2\pi}{\omega(z_6)-\omega(z_5)} = 5\pi\left(\sqrt{2\Phi(z_1)/z_1^2}-\sqrt{2\Phi(z_6)/z_6^2}\right)^{-1} = 1.9\times10^{16}\,\mathrm s = 620\,\mathrm{Myr}.$$
>
> The timescale is relatively long, but compared to the lifespan of the Milky Way, which is around 13.6 billion years, it’s relatively recent.

> [!grading]- Критерии оценивания
> Grading: (preliminary)
>
> | Criterion | Points |
> |---|---|
> | Idea of using Gauss’ law | 0.3 pts |
> | Formula relating the mass inside with gravitational flux | 0.3 pts |
> | Application of Gauss’ law on a cuboid | 0.2 pts |
> | Final result | 0.2 pts |
>
> *Alternative solution:*
>
> | Criterion | Points |
> |---|---|
> | Finding the acceleration of a thin disk by integrating over its surface, of which: | 0.5 pts |
> | – Writing down the integral | 0.3 pts |
> | – Correct evaluation, including finding that the acceleration is independent of the displacement from the surface | 0.2 pts |
> | Inferring that only the surface density inside $-a < z < a$ contributes to the final acceleration | 0.3 pts |
> | Final result | 0.2 pts |
>
> **ii)**
>
> Grading: (preliminary)
>
> | Criterion | Points |
> |---|---|
> | Noticing that the movement is that of a harmonic oscillator | 0.3 pts |
> | Expression for the oscillation period | 0.2 pts |
>
> **iii)**
>
> Grading: (preliminary)
>
> | Criterion | Points |
> |---|---|
> | Making use of the total energy at $z = 0$ intersection points being known (either explicitly or implicitly) | 0.7 pts |
> | Interpolating the values at $v_z = 0$ from neighbouring $z = 0$ crossovers. This should be explicitly mentioned | 0.8 pts |
> | Tabulating the potential, of which: | 0.7 pts |
> | – using six points | 0.7/0.7 pts |
> | – using four to five points | 0.4/0.7 pts |
> | – using one to three points | 0.1/0.7 pts |
> | $\Phi(z)$ vs $z$ correctly plotted | 0.3 pts |
>
> Grading: (preliminary)
>
> | Criterion | Points |
> |---|---|
> | Connecting $\Phi(z_1)$ with $\rho_0$ by assuming constant mass density. | 0.8 pts |
> | If the first data point is not used | −0.2 pts |
> | Final expression for $\rho_0$ | 0.1 pts |
> | Numerical value within 10 % | 0.1 pts |
>
> **v)**
>
> Grading: (preliminary)
>
> | Criterion | Points |
> |---|---|
> | Obtaining an expression for the total mass contained within $z$ | 0.7 pts |
> | Taking the difference between the total mass within $z_6$ and $z_5$ for calculating the dark matter content | 0.9 pts |
> | Final expression for $\rho_\mathrm{DM}$ based on $z_6$ and $z_5$ | 0.3 pts |
> | Numerical value within 10 % | 0.1 pts |
>
> *Alternative scheme:*
>
> | Criterion | Points |
> |---|---|
> | Using the previous expression for $\rho$ based on $\Phi(z)$ to express $(z_6-z_5)\rho_\mathrm{DM} = z_6\rho(z_6)-z_5\rho(z_5)$ | 1.6 pts |
> | Final expression for $\rho_\mathrm{DM}$ based on $z_6$ and $z_5$ | 0.3 pts |
> | Numerical value within 10 % | 0.1 pts |
>
> **vi)**
>
> Grading: (preliminary)
>
> | Criterion | Points |
> |---|---|
> | Idea of using differences in the winding rate between two points on the spiral | 1.0 pts |
> | Expression for angular frequency $\omega$ in terms of $\Phi(z)$ by assuming a harmonic oscillator | 0.5 pts |
> | Picking two points and connecting the age of the spiral, $\omega$ and the winding amount | 0.3 pts |
> | Numerical value within 10 % of the solution value | 0.2 pts |
