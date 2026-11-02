---
id: nbpho-2023-intl-theory-3
olympiad: NbPhO
year: 2023
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "3"
title: "Wobble"
points: 8
authors: ["Taavet Kalda"]
aliases: ["Wobble"]
topics: ["[[1.11 Центр масс]]", "[[1.3 Равноускоренное криволинейное движение]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: true
source_damaged: false
summary: "По астрометрическим траекториям звёзд определить периоды и массы планет и их звёзд."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 3. Wobble (8 points) — Taavet Kalda.

**NbPhO 2023** · Международная олимпиада · теория · 10–12 класс · задача 3  
Источник: [[_pdf/NbPhO/nbpho-2023.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2023.pdf#page=5|решение, стр. 5]]

Темы: [[1.11 Центр масс]], [[1.3 Равноускоренное криволинейное движение]]

> [!abstract] Кратко (составлено моделью)
> По астрометрическим траекториям звёзд определить периоды и массы планет и их звёзд.

We investigate the so-called astrometric wobble method for detecting exoplanets. The method relies on the ability to measure the change in position in the sky that the host star experiences due to the gravitational influence of its orbiting planets. This method has become feasible in recent years due to the availability of more precise instruments.

**i)** (2.5 points) Consider a system consisting of a host star, an inner planet $A$, and an outer planet $B$. Below is a measurement of the trajectory of the centre of the star in the plane perpendicular to the line of sight, measured over a period of $t=10\,\mathrm{yr}$. In all of the subsequent parts, you may assume that both planets orbit in circular orbits in the plane of the diagram. What are the orbital periods $T_A$ and $T_B$ of the two planets?

![[nbpho-2023-p1-f4.svg]]

**ii)** (2.5 points) Based on direct imaging of planet $A$ in the infrared, the orbital radius of planet $A$ is measured to be $a_A=1.5\,\mathrm{AU}=2.2\times10^8\,\mathrm{km}$. What is the mass $M$ of the host star, and the mass $m_A$ of planet $A$? The gravitational constant is $G=6.67\times10^{-11}\,\mathrm{m^3\,kg^{-1}\,s^{-2}}$.

**iii)** (1 point) What is the mass $m_B$ of planet $B$?

**iv)** (2 points) Now consider a similar $t=10\,\mathrm{yr}$ measurement of a different system shown below, also consisting of a host star and two planets $A$ and $B$ (where $A$ is the inner planet). Similarly to before, find the mass $M$ of the host star, and the masses $m_A$, $m_B$ of the planets in the new system. As before, direct imaging yields that the orbital radius of planet $A$ is $a_A=1.3\,\mathrm{AU}=2.0\times10^8\,\mathrm{km}$.

![[nbpho-2023-p1-f1.svg]]

> [!answer]- Ответ
> **i**
>
> $$
> T_B=\frac{2\pi}{\omega_B}=\frac{2\pi t}{\alpha}=12.4\,\mathrm{yr},
> $$
>
> **i**
>
> $$
> T_A=\frac{2\pi}{\omega_A}=\frac{1}{\frac1{T_B}+\frac{7.5}{t}}=1.20\,\mathrm{yr}.
> $$
>
> **ii**
>
> $$
> M=\frac{4\pi^2a_A^3}{GT_A^2}=4.4\times10^{30}\,\mathrm{kg}.
> $$
>
> **ii**
>
> $$
> m_A=M\frac{x_A}{a_A}=1.2\times10^{27}\,\mathrm{kg}.
> $$
>
> **iii**
>
> $$
> m_B=M\frac{x_B}{a_B}=9.3\times10^{26}\,\mathrm{kg}.
> $$
>
> **iv**
>
> $$
> M=\frac{4\pi^2a_A^3}{GT_A^2}=6.8\times10^{29}\,\mathrm{kg},
> $$
>
> **iv**
>
> $$
> m_A=M\frac{x_A}{a_A}=5.1\times10^{26}\,\mathrm{kg},
> $$
>
> **iv**
>
> $$
> m_B=Mx_B\sqrt[3]{\frac{4\pi^2}{T_B^2GM}}=3.9\times10^{25}\,\mathrm{kg}.
> $$

> [!solution]- Решение
> # 3. Wobble (8 points)
>
> — Solution by Taavet Kalda, grading schemes by ....
>
> **i)** (2.5 points) The farther away a planet is from the host star, the bigger its orbital period. In a fixed period, we then expect planet A to make more rotations around the star than planet B. The wobble effect comes from both the star and the planets orbiting around their common barycentre (centre of mass). The effect of one planet makes the star undergo a circular motion with some radius $x$ and frequency $\omega$. The effect of two planets is additive, so the overall motion is the sum of two circular motions with radius’ $x_A$ and $x_B$ with different angular frequencies $\omega_A$ and $\omega_B$.
>
> In the figure, we find the centre of circular motion of the star from the centre of the envelope (by for example using a ruler to find the diameter and then the centre-point). From there, we measure that lower frequency component covers an angle of $\alpha=290^\circ$ within the measurement period $t=10\,\mathrm{yr}$. The higher frequency component, in the meantime, undergoes 7.5 full rotations with respect to the lower frequency component. Hence, $\omega_Bt=\alpha$ and $(\omega_A-\omega_B)t/(2\pi)=7.5$. This yields
>
> $$T_B=\frac{2\pi}{\omega_B}=\frac{2\pi t}{\alpha}=12.4\,\mathrm{yr},$$
>
> $$T_A=\frac{2\pi}{\omega_A}=\frac{1}{\frac1{T_B}+\frac{7.5}{t}}=1.20\,\mathrm{yr}.$$
>
> **ii)** (2.5 points) From the figure, we measure the extrema of the distance of the star from the origin as $l_1=1.6\times10^5\,\mathrm{km}$ and $l_2=2.8\times10^5\,\mathrm{km}$. The extrema corresponds to when the two circular motions are pointing in the same direction or the opposite direction. In other words, the distances are $l_1=x_B-x_A$ and $l_2=x_B+x_A$. Rearranging, $x_A=(l_2-l_1)/2=6\times10^4\,\mathrm{km}$ and $x_B=2.2\times10^5\,\mathrm{km}$. To infer the masses, we need to study the dynamics of the system.
>
> First, we can assume that the semi-major axis of the planets are much bigger than $x$. Indeed, $a_A/x_A=4000\gg1$. Either from force balance between gravity and centrifugal force, or through Kepler’s Third Law, we have $4\pi^2/(GM)=T_A^2/a_A^3$ so the star’s mass is
>
> $$M=\frac{4\pi^2a_A^3}{GT_A^2}=4.4\times10^{30}\,\mathrm{kg}.$$
>
> The planet’s mass can be inferred from the property that planet and star rotate around their common centre of mass: $Mx_A=m_Aa_A$. Hence,
>
> $$m_A=M\frac{x_A}{a_A}=1.2\times10^{27}\,\mathrm{kg}.$$
>
> **iii)** (1 point) Once again, from Kepler’s Third law, we get the semi-major axis of planet $B$ to be
>
> $$a_B=\sqrt[3]{\frac{T_B^2GM}{4\pi^2}}=1.0\times10^9\,\mathrm{km}.$$
>
> Similarly to before, we get the mass as
>
> $$m_B=M\frac{x_B}{a_B}=9.3\times10^{26}\,\mathrm{kg}.$$
>
> Both of the planets are gas giants, similar to Jupiter (0.63 and 0.50 Jupiter masses respectively). This makes sense, as this method is more sensitive to higher mass exoplanets with bigger orbits.
>
> **iv)** (2 points) The equations describing the system still hold, but reading off the frequencies is trickier. Nevertheless, we can still locate the origin and measure the extreme distances $l_1=1.20\times10^5\,\mathrm{km}$ and $l_2=1.85\times10^5\,\mathrm{km}$. We also note that the higher frequency component (corresponding to planet $A$) has a bigger radius than the lower frequency one (planet $B$). Hence, $l_1=x_A-x_B$ and $l_2=x_A+x_B$, and so $x_A=(l_1+l_2)/2=1.5\times10^5\,\mathrm{km}$, $x_B=(l_2-l_1)/2=3.3\times10^4\,\mathrm{km}$.
>
> The higher frequency component does 3 full turns and, measuring from the figure, an extra $280^\circ$ on top of it. This gives $T_A=t/(3+280^\circ/360^\circ)=2.65\,\mathrm{yr}$. The lower frequency component, meanwhile, starts and ends from the farthest away point, and oscillates through the closest point 3 times. Hence it goes through 3 full rotations. Thus,
>
> $$\left(\frac{2\pi}{T_A}-\frac{2\pi}{T_B}\right)t=6\pi,$$
>
> and so
>
> $$T_B=\frac1{\frac1{T_A}-\frac3t}=12.9\,\mathrm{yr}.$$
>
> By using the equations from the previous parts, we get
>
> $$M=\frac{4\pi^2a_A^3}{GT_A^2}=6.8\times10^{29}\,\mathrm{kg},$$
>
> $$m_A=M\frac{x_A}{a_A}=5.1\times10^{26}\,\mathrm{kg},$$
>
> $$m_B=Mx_B\sqrt[3]{\frac{4\pi^2}{T_B^2GM}}=3.9\times10^{25}\,\mathrm{kg}.$$
>
> The first planet is once again a gas giant (0.26 Jupiter masses) while the second one is a “Super-Earth” (6.4 Earth masses).

> [!grading]- Критерии оценивания
> Grading:
>
> | Criterion | Points |
> |---|---|
> | Realising that the higher frequency component is due to planet A and the lower frequency component is due to planet B | 0.5 pts |
> | The higher frequency component undergoes 7.5 full rotations | 0.4 pts |
> | The lower frequency component covers an angle of $290^\circ$, or alternatively, $\frac{7.5}{9}\cdot2\pi$ | 0.4 pts |
> | Finding $T_A$ | 0.8 pts |
> | Finding $T_B$ | 0.4 pts |
>
> **ii)**
>
> Grading:
>
> | Criterion | Points |
> |---|---|
> | Expressing $4\pi^2/(GM)=T_A^2/a_A^3$ | 0.6 pts |
> | Finding $M$ | 0.4 pts |
> | Realising that the position of the centre of mass of $A$ and $M$ is conserved (with respect to $B$) | 0.5 pts |
> | Inferring equation $Mx_A=m_Aa_A$ | 0.5 pts |
> | Finding $x_A$ from the trajectory | 0.3 pts |
> | Finding $m_A$ | 0.2 pts |
>
> ![[nbpho-2023-p5-f1.svg]]
>
> **iii)**
>
> Grading:
>
> | Criterion | Points |
> |---|---|
> | Finding $a_B$ | 0.5 pts |
> | Finding $m_B$ | 0.5 pts |
>
> **iv)**
>
> Grading:
>
> | Criterion | Points |
> |---|---|
> | Finding $T_A$ | 0.4 pts |
> | Finding $T_B$ | 0.4 pts |
> | Finding $M$ | 0.3 pts |
> | Finding $m_A$ | 0.4 pts |
> | Finding $m_B$ | 0.5 pts |
>
> ![[nbpho-2023-p6-c0104.png]]
