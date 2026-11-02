---
id: nbpho-2024-intl-theory-7
olympiad: NbPhO
year: 2024
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "7"
title: "Waves"
points: 4
authors: ["Janis Huns", "Jaan Kalda"]
aliases: ["Waves"]
topics: ["[[2.11 Поверхностное натяжение]]", "[[1.20 Колебания]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: true
source_damaged: false
summary: "По дисперсионному соотношению и фотографии следа определить параметры капиллярно-гравитационных волн и поверхностное натяжение."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 7. Waves (4 points) — Janis Huns, Jaan Kalda.

**NbPhO 2024** · Международная олимпиада · теория · 10–12 класс · задача 7  
Источник: [[_pdf/NbPhO/nbpho-2024.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2024.pdf#page=8|решение, стр. 8]]

Темы: [[2.11 Поверхностное натяжение]], [[1.20 Колебания]]

> [!abstract] Кратко (составлено моделью)
> По дисперсионному соотношению и фотографии следа определить параметры капиллярно-гравитационных волн и поверхностное натяжение.

The dispersion relation (i.e. the dependence of the circular frequency $\omega$ on the wave vector $k = \frac{2\pi}{\lambda}$) of capillary-gravity waves is

$$\omega^2 = gk^\alpha + \frac{\sigma}{\rho}k^\beta,$$

where $\sigma$ denotes the surface tension, $g = 9.81\,\mathrm{m\,s^{-2}}$, and $\rho = 1000\,\mathrm{kg\,m^{-3}}$.

**i)** (1 point) determine the values of the exponents $\alpha$ and $\beta$.

![[nbpho-2024-p2-c2646.png]]

F. Moisy, M. Rabaud, PRE 90, 023009 (2014)

**ii)** (3 points) In the image above, we can see how an object moving with a constant speed $U = 60\,\mathrm{cm\,s^{-1}}$ generates a wake — a set of waves of different wavelengths. Pay attention to the short-wavelength waves whose wave crest extends from the object almost up to the edges of the photo: the presence of a very long wavefront testifies that for these particular waves, the phase and group velocities are equal. Determine the surface tension of water. You can take measurements from the photo. Note that while phase speed is the speed of a constant phase of the wave, the group speed $v_g = \frac{d\omega}{dk}$ is the speed of a wave packet (a train of waves).

> [!answer]- Ответ
> **i** — $\alpha=1$ and
>
> **i** — $\beta=3$.
>
> **ii**
>
> $$
> \sigma=\frac{\rho U^4\sin^4\mu}{4g}\approx60\,\mathrm{g\,s^{-2}}.
> $$

> [!solution]- Решение
> # 7. Waves (4 points) — Solution by Tudor Plopeanu.
>
> **i)** (1 point) Both $gk^\alpha$ and $\frac\sigma\rho k^\beta$’s dimensionalities are $\mathrm{s^{-2}}$, while $k$’s dimensionality is $\mathrm{m^{-1}}$. The surface tension’s dimensionality is $\mathrm{kg/s^2}$. As such,
>
> $\alpha=1$ and
>
> $\beta=3$.
>
> **ii)** (3 points)
>
> The phase and group velocities of the wake are equal, i.e. $\frac{d\omega}{dk}=\frac\omega k$. We can find $\frac\omega k$ from the Mach angle formed by the wave front in the picture: $\sin\mu=\frac\omega{Uk}$. Differentiating the dispersion relation,
>
> $$2\omega\frac{d\omega}{dk}=\left(g+3\frac\sigma\rho k^2\right)\quad\Longrightarrow\quad2\omega^2=k\left(g+3\frac\sigma\rho k^2\right).$$
>
> Substituting our dispersion relation, we obtain $g=\frac\sigma\rho k^2$ and $\omega^2=2gk$. Substituting $g^{1/2}=(\frac\sigma\rho)^{1/2}k$, we reach $\frac{\omega^2}{k^2}=2(\frac{g\sigma}{\rho})^{1/2}$. Thus, we can find
>
> $$\sigma=\frac{\rho U^4\sin^4\mu}{4g}\approx60\,\mathrm{g\,s^{-2}}.$$
>
> for measured $\mu\approx21.5^\circ$.

> [!grading]- Критерии оценивания
> Grading: (preliminary)
>
> | Criterion | Points |
> |---|---|
> | Dimensional analysis (or similar technique). | 0.2 pts |
> | Units of $\sigma$ | 0.2 pts |
> | $\alpha=1$. | 0.3 pts |
> | $\beta=3$. | 0.3 pts |
>
> **ii)**
>
> Grading: (preliminary)
>
> | Criterion | Points |
> |---|---|
> | Identifying $d\omega/dk=\omega/k$. | 0.6 pts |
> | Correct angle i.e. $\sin(\mu)=\omega/(Uk)$ | 0.6 pts |
> | Measuring $\mu$ from the picture | 0.4 pts |
> | Value $\mu\in[20^\circ,30^\circ]$ | 0.3 pts |
> | Calculate the derivative $d\omega/dk$ | 0.4 pts |
> | Correct expression for $\sigma$ | 0.4 pts |
> | Value $\sigma\approx60\,\mathrm{g\,s^{-2}}$ | 0.3 pts |
