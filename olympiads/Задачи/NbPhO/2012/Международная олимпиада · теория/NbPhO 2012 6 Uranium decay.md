---
id: nbpho-2012-intl-theory-6
olympiad: NbPhO
year: 2012
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "6"
title: "Uranium decay"
points: 7
aliases: ["Uranium decay"]
topics: ["[[2.5 Первое начало термодинамики]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Рассчитать состав урана, тепловыделение при распаде и радиус плавления уранового шара."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# Problem 6. Uranium decay (7 points)

**NbPhO 2012** · Международная олимпиада · теория · 10–12 класс · задача 6  
Источник: [[_pdf/NbPhO/nbpho-2012.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2012.pdf#page=4|решение, стр. 4]]

Темы: [[2.5 Первое начало термодинамики]]

> [!abstract] Кратко (составлено моделью)
> Рассчитать состав урана, тепловыделение при распаде и радиус плавления уранового шара.

Natural uranium consists of 99.3% $\mathrm{U}^{238}$, and in this problem we can ignore the presence of other isotopes. $\mathrm{U}^{238}$ decays according to the table at the bottom of the page, where an isotope decays into the isotope indicated in its neighbouring cell (to the right), the decay energy is given in the cell below in megaelectronvolts (MeV), $1\,\mathrm{MeV}=1.6\times10^{-13}\,\mathrm{J}$, and the last row indicates the logarithm of the respective half-life in seconds, $\log_{10}\tau_{\frac12}$ (so that 17.15 below $\mathrm{U}^{238}$ means that the half-life of $\mathrm{U}^{238}$ is $10^{17.15}\,\mathrm{s}\approx1.41\times10^{17}\,\mathrm{s}$.

You may also use the value of the Avogadro number $N_A=6.02\times10^{23}\,\mathrm{mol^{-1}}$, and the following physical properties of uranium: melting point $T_0=1408\,\mathrm{K}$, density $\rho=1.89\times10^4\,\mathrm{kg/m^3}$, thermal conductivity $\kappa=27.5\,\mathrm{W/m\cdot K}$, molar mass $\mu=0.238\,\mathrm{kg/mol}$. It can be assumed that the radon which appears in the chain of nuclear decays does not escape the bulk of uranium. *Remark:* thermal conductivity is the coefficient of proportionality between the heat flux density ($\mathrm{W/m^2}$) and $dT/dx$ (temperature drop per unit distance).

**i.** (2 pts) Assuming that the only source of natural $\mathrm{U}^{234}$ is the decay chain of $\mathrm{U}^{238}$, what is the percentage of $\mathrm{U}^{234}$ in the natural uranium ore?

**ii.** (2 pts) Determine the heat production volume rate of natural uranium $w$ (in watts per cubic meter) due to nuclear decay.

**iii.** (3 pts) If the radius of a uranium ball is large enough, it will melt inside. How large radius $R_0$ is needed for such a melting, if ambient temperature is $T_a=300\,\mathrm{K}$?

| $\mathrm{U}^{238}$ | $\mathrm{Th}^{234}$ | $\mathrm{Pa}^{234}$ | $\mathrm{U}^{234}$ | $\mathrm{Th}^{230}$ | $\mathrm{Ra}^{226}$ | $\mathrm{Rn}^{222}$ | $\mathrm{Po}^{218}$ | $\mathrm{Pb}^{214}$ | $\mathrm{Bi}^{214}$ | $\mathrm{Po}^{214}$ | $\mathrm{Pb}^{210}$ | $\mathrm{Bi}^{210}$ | $\mathrm{Po}^{210}$ | $\mathrm{Pb}^{206}$ |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 4.27 | 0.27 | 2.27 | 4.86 | 4.77 | 4.87 | 5.59 | 6.12 | 1.02 | 3.27 | 7.88 | 0.06 | 1.43 | 5.41 | – |
| 17.15 | 6.32 | 4.38 | 12.89 | 12.38 | 10.70 | 5.52 | 2.27 | 3.21 | 3.08 | -3.78 | 8.85 | 5.64 | 7.08 | stable |

> [!answer]- Ответ
> **6.i**
>
> $$
> \frac{N_{234}}{N}=\frac{\tau_{234}}{0{,}993\tau_{238}}\approx5.53\times10^{-5}.
> $$
>
> **6.ii** — $w=N_A\frac{\rho}{\mu}E_\mathrm{dec}\frac{\ln2}{\tau_{238}}\approx2.0\,\mathrm{W/m^3}$.
>
> **6.iii**
>
> $$
> R=\sqrt{6\frac{\kappa}{w}(T_0-T_a)}\approx305\,\mathrm{m}.
> $$

> [!solution]- Решение
> # Problem 6. Uranium decay (7 points)
>
> **i.** (2 pts) It can be seen from the table that the first half-life is much longer than all the others. This means that as soon as something is produced by the decay of $\mathrm U^{238}$, all the other decay steps in the chain take place almost immediately, and for the other isotopes, a quasi-stationary concentration level is achieved — such that the number of decays per unit time of the isotope equals to that of $\mathrm U^{238}$. Let us apply this to $\mathrm U^{234}$. If the number of $\mathrm U^{238}$ atoms is $N_{238}$ then the number of decays per unit time is $\frac{dN}{dt}=N_0\ln2/\tau_{238}=N_{234}\ln2/\tau_{234}$, hence $N_{234}/N_{238}=\tau_{234}/\tau_{238}$. The total number of uranium atoms equals to $N=N_{238}/0.993$, so
>
> $$\frac{N_{234}}{N}=\frac{\tau_{234}}{0{,}993\tau_{238}}\approx5.53\times10^{-5}.$$
>
> **ii.** (2 pts) Since the uranium ore has reached a quasi-stationary composition of isotopes, per each decay of $\mathrm U^{238}$, there is one decay event for each of the isotopes. So we need to sum up all the decay energies in the second row of the table, this gives us $E_\mathrm{dec}=52.1\,\mathrm{MeV}$. Then the heat production rate is given by
> $w=N_A\frac{\rho}{\mu}E_\mathrm{dec}\frac{\ln2}{\tau_{238}}\approx2.0\,\mathrm{W/m^3}$.
>
> **iii.** (3 pts) The heat released will escape owing to the thermal conductance. Inside a sphere of radius $r$, the heat released equals to $\frac43\pi wr^3=4\pi r^2\kappa\frac{dT}{dr}$ (the right-hand-side gives the thermal flux due to conductance). From this equation we obtain $rdr=3\frac{\kappa}{w}dT$, which yields after integration
>
> $$R=\sqrt{6\frac{\kappa}{w}(T_0-T_a)}\approx305\,\mathrm{m}.$$
