---
id: nbpho-2025-intl-theory-3
olympiad: NbPhO
year: 2025
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "3"
title: "Nuclear Reactors"
points: 6
authors: ["Topi Lind"]
aliases: ["Nuclear Reactors"]
topics: ["[[1.17 Законы сохранения энергии и импульса]]", "[[2.12 Молекулярно-кинетическая теория]]", "[[2.2 Уравнение состояния идеального газа]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: true
source_damaged: false
summary: "Замедление нейтронов в реакторе и определение состава газа в топливном стержне."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 3. Nuclear Reactors (6 points) — Topi Lind.

**NbPhO 2025** · Международная олимпиада · теория · 10–12 класс · задача 3  
Источник: [[_pdf/NbPhO/nbpho-2025.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2025.pdf#page=4|решение, стр. 4–5]]

Темы: [[1.17 Законы сохранения энергии и импульса]], [[2.12 Молекулярно-кинетическая теория]], [[2.2 Уравнение состояния идеального газа]]

> [!abstract] Кратко (составлено моделью)
> Замедление нейтронов в реакторе и определение состава газа в топливном стержне.

In order to maintain a chain reaction in a modern thermal-neutron nuclear reactor one needs three things: 1. nuclear fuel (e.g. $\mathrm{U}^{235}$), 2. moderator (e.g. water) and 3. coolant. In most cases the moderator acts as the coolant as well. Neutrons released from a thermal fission of $\mathrm{U}^{235}$ have a mean kinetic energy of approximately $E_0 = 2\,\mathrm{MeV}$. However, neutrons which are that fast are inefficient in triggering fission of $\mathrm{U}^{235}$: neutrons need to be slowed down to an average kinetic energy of $E_f = 0.025\,\mathrm{eV}$. In what follows, justify why non-relativistic approximations can be used unless explicitly instructed otherwise.

**i)** (1 point) The rest energy of neutrons $m_n c^2 = 940\,\mathrm{MeV}$, the Boltzmann constant $k_\mathrm B = 1.38 \times 10^{-23}\,\mathrm{J\,K^{-1}}$, and the elementary charge $e = 1.602 \times 10^{-19}\,\mathrm C$. What is the required speed of neutrons, i.e. the speed of neutrons with kinetic energy $E_f$? What is the temperature $T_f$ of a neutron gas where the average kinetic energy of neutrons is $E_f$?

**ii)** (1 point) What is the initial speed of neutrons, i.e. the speed of neutrons with energy $E_0$?

**iii)** (2.5 points) From a completely non-relativistic point of view, what should be the mass of the moderator’s atoms to slow down the fast neutrons as efficiently as possible? If the mass of the moderator’s atoms were to be $M = 135m_n$, how many collisions with such atoms at a temperature much lower than $T_f$ would a fast neutron need to experience to slow down from $E_0$ to $E_f$? Assume that all collisions are elastic and central.

**iv)** (1.5 points) Nuclear fuel, i.e. $\mathrm{U}^{235}$, is placed inside metal rods and pressurized with helium gas to $p_0 = 2.5\,\mathrm{MPa}$. During operation, as $\mathrm{U}^{235}$ keeps on fissioning inside the fuel rods, there is a build up of gas inside the rods. With a non-invasive ultrasound measurement we can measure that the gas pressure inside the rod after it is finally picked out from the core is $p = 6.5\,\mathrm{MPa}$. Assuming that the gas released inside the rods is completely made of xenon isotope ${}^{135}_{54}\mathrm{Xe}$ and that the initial gas volume drops from $V_0 = 18\,\mathrm{cm^3}$ to $V = 9\,\mathrm{cm^3}$ due to the swelling of the fuel pellets, how many moles of xenon are released from fission? What is the ratio of helium to xenon inside the rod? The measurements are done at $T_0 = 20\,{}^\circ\mathrm{C}$; the universal gas constant $R = 8.31\,\mathrm{J\,mol^{-1}\,K^{-1}}$.

> [!answer]- Ответ
> **i** — $v_f = 2.2 \times 10^3\,\mathrm{m\,s^{-1}}$.
>
> **i**
>
> $$
> T_f = \frac{0.025\cdot1.602\times10^{-19}}{1.38\times10^{-23}} = 290\,\mathrm K.
> $$
>
> **i** — $T_f \approx 193\,\mathrm K$.
>
> **ii** — $v_0 = 2.0\times10^7\,\mathrm{m\,s^{-1}}$.
>
> **iii**
>
> $$
> N = \frac{\ln(v_f/v_0)}{\ln[(m_1-m_2)/(m_1+m_2)]} = \frac12\frac{\ln(E_f/E_0)}{\ln[(m_1-m_2)/(m_1+m_2)]} = 614.
> $$
>
> **iv**
>
> $$
> n_\mathrm{Xe} = p_\mathrm{Xe}V/RT_0 = 5.5\times10^{-3}\,\mathrm{mol},
> $$
>
> **iv**
>
> $$
> \frac{n_\mathrm{He}}{n_\mathrm{Xe}} \approx 3.3.
> $$

> [!solution]- Решение
> # 3. Nuclear Reactors (6 points) — Solution and grading scheme by Topi Lind, Melvin Storbacka, Oleg Kosik, Aleksandr Sorokin and Ludmila Belogrudova.
>
> **i)** (1 point) If the speed of the particle is much less than the speed of light, we can use non-relativistic approach. For non-relativistic particles we know $v = \sqrt{2E_k/m}$. Substituting values gives us
>
> $v_f = 2.2 \times 10^3\,\mathrm{m\,s^{-1}}$.
>
> This is much less than the speed of light and thus justified. Another way to justify the applicability of the non-relativistic approach would be to say that kinetic energy is significantly less than the rest energy ($E_f \ll m_nc^2$).
>
> *Typo in problem description. $E_f = 0.025\,\mathrm{eV}$ is the mode of the Maxwell–Boltzmann distribution which gives $E = k_bT$. Average gives $E = (3/2)k_bT$.*
>
> Using the mode of the Maxwell–Boltzmann distribution, $E = k_BT$, and remembering to convert from eV to J correctly, we find
>
> $$T_f = \frac{0.025\cdot1.602\times10^{-19}}{1.38\times10^{-23}} = 290\,\mathrm K.$$
>
> With $E = (3/2)k_BT$ we find
>
> $T_f \approx 193\,\mathrm K$.
>
> **ii)** (1 point) The non-relativistic approach justified as in previous task. Same approach gives us
>
> $v_0 = 2.0\times10^7\,\mathrm{m\,s^{-1}}$.
>
> **iii)** (2.5 points) In a collision between particle 1 ($m_1$, $v_{1,i}$ and $v_{1,f}$) and particle 2 ($m_2$, $v_{2,i}$ and $v_{2,f}$) momentum is conserved,
>
> $$m_1(v_{1,f}-v_{1,i}) = m_2(v_{2,i}-v_{2,f})$$
>
> and since the collisions are elastic, kinetic energy is also conserved:
>
> $$m_1(v_{1,f}^2-v_{1,i}^2) = m_2(v_{2,i}^2-v_{2,f}^2).$$
>
> Dividing the latter by the former leads to
>
> $$v_{1,i}+v_{1,f} = v_{2,i}+v_{2,f}.$$
>
> Substituting this to the conservation of momentum gives for particle 1:
>
> $$v_{1,f} = \frac{m_1-m_2}{m_1+m_2}v_{1,i}+\frac{2m_2}{m_1+m_2}v_{2,i},$$
>
> and similarly for particle 2:
>
> $$v_{2,f} = \frac{2m_1}{m_1+m_2}v_{1,i}+\frac{m_1-m_2}{m_1+m_2}v_{2,i}.$$
>
> We see that with $m_1 = m_2$ there is a maximum transfer of momentum. Assuming that particle 1 is the neutron and particle 2 is the target, and that the target is at rest for all intents and purposes, the mass of the moderators atoms should be the same as the neutrons.
>
> In a single collision with a stationary atom of the moderator, the speed of the neutron decreases by the factor of $\frac{m_1-m_2}{m_1+m_2}$, so the speed of the neutron after $N$ head-on collisions with stationary atoms of moderator will be
>
> $$v_N = v\left(\frac{m_1-m_2}{m_1+m_2}\right)^N.$$
>
> Hence,
>
> $$N = \frac{\ln(v_f/v_0)}{\ln[(m_1-m_2)/(m_1+m_2)]} = \frac12\frac{\ln(E_f/E_0)}{\ln[(m_1-m_2)/(m_1+m_2)]} = 614.$$
>
> **iv)** (1.5 points) We can model the gas inside the rod as an ideal gas. Simply due to swelling the pressure inside the rod would increase from $2.5\,\mathrm{MPa}$ to $5\,\mathrm{MPa}$ as we know from Boyle’s law $P_1V_1 = P_2V_2 \rightsquigarrow P_2 = P_1V_1/V_2$. Thus, the release of xenon must contribute $1.5\,\mathrm{MPa}$’s worth of pressure due to Dalton’s law $p_\mathrm{tot} = p_\mathrm{He}+p_\mathrm{Xe}$. From ideal gas law we find the amount of xenon moles as
>
> $$n_\mathrm{Xe} = p_\mathrm{Xe}V/RT_0 = 5.5\times10^{-3}\,\mathrm{mol},$$
>
> where $p_\mathrm{Xe} = 1.5\,\mathrm{MPa}$, $V_2 = 9\,\mathrm{cm^3}$ and $T = 293\,\mathrm K$. In a similar manner we find that the amount of helium in the beginning was
>
> $$n_\mathrm{He} = p_\mathrm{He}V_0/RT_0 = 1.8\times10^{-2}\,\mathrm{mol},$$
>
> where $P_\mathrm{He} = 2.5\,\mathrm{MPa}$, $V_0 = 18\,\mathrm{cm^3}$ and $T_0 = 293\,\mathrm K$. The ratio of the two is
>
> $$\frac{n_\mathrm{He}}{n_\mathrm{Xe}} \approx 3.3.$$

> [!grading]- Критерии оценивания
> Grading i)+ii): (preliminary)
>
> | Criterion | Points |
> |---|---|
> | Expresses $v_f = \sqrt{2E_f/m}$ and/or $v_0 = \sqrt{2E_0/m}$ | 0.3 pts |
> | Calculates $v_f = 2.2\times10^3\,\mathrm{m\,s^{-1}}$ and/or $v_0 = 2.0\times10^7\,\mathrm{m\,s^{-1}}$ for two correct numerical values; 0.5 pts; if only one value is correct | 0.3 pts |
> | Uses $E_f = \frac32 k_BT$ | 0.3 pts |
> | Using this formula calculates $T = 193\,\mathrm K$ | 0.3 pts |
> | Justifies the validity of the classical approach in both cases | 0.3 + 0.3 pts |
>
> Remark. Using $E_f = k_BT$ without justification and finding $T = 290\,\mathrm K$ gives 0 pts for the formula and 0.3 pts for the numerical calculation.
>
> **iii)**
>
> Grading: (preliminary)
>
> | Criterion | Points |
> |---|---|
> | $T \ll T_f$, so moderator atoms are essentially at rest | 0.3 pts |
> | Justifies that maximum momentum transfer is when $m_n = M$ | 0.4 pts |
> | Applies energy and momentum conservation | 0.3 pts + 0.3 pts |
> | Expresses $u = v\frac{m_1-m_2}{m_1+m_2}$ | 0.4 pts |
> | Expresses $v_f = v_0\left(\frac{m_1-m_2}{m_1+m_2}\right)^N$ | 0.5 pts |
> | Calculates $N = 614$ | 0.3 pts |
>
> **iv)**
>
> Grading: (preliminary)
>
> | Criterion | Points |
> |---|---|
> | Applies Boyle’s law | 0.3 pts |
> | Applies Dalton’s law | 0.4 pts |
> | Expresses $n_\mathrm{Xe} = p_\mathrm{Xe}V/RT_0$ | 0.2 pts |
> | Calculates $n_\mathrm{Xe} = 5.5\times10^{-3}\,\mathrm{mol}$ | 0.2 pts |
> | Expresses $n_\mathrm{He} = p_\mathrm{He}V_0/RT_0$ | 0.2 pts |
> | Calculates $\frac{n_\mathrm{He}}{n_\mathrm{Xe}} = 3.3$ | 0.2 pts |
