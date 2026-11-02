---
id: nbpho-2009-intl-theory-2
olympiad: NbPhO
year: 2009
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "2"
title: "Nanoclock"
points: 10
aliases: ["Nanoclock"]
topics: ["[[3.1 Закон Кулона. Напряжённость]]", "[[3.3 Потенциал системы. Подобие]]", "[[1.20 Колебания]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Исследовать электрическое поле заряженного кольца и колебания электрона вблизи его центра."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 2. Nanoclock (10 points)

**NbPhO 2009** · Международная олимпиада · теория · 10–12 класс · задача 2  
Источник: [[_pdf/NbPhO/nbpho-2009.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2009.pdf#page=3|решение, стр. 3]]

Темы: [[3.1 Закон Кулона. Напряжённость]], [[3.3 Потенциал системы. Подобие]], [[1.20 Колебания]]

> [!abstract] Кратко (составлено моделью)
> Исследовать электрическое поле заряженного кольца и колебания электрона вблизи его центра.

Nanotechnology allows controllable fabrication of very small structures. Let us consider a tiny homogeneously charged thin ring, having a radius $R$ and carrying a positive net charge $Q$.

**i)** Find the electric potential $\varphi$ at a point $P$, which is on the axes of the ring, at a distance $z$ from the centre of the ring.

**ii)** Find the electric field $E$ at the point $P$.

**iii)** Show that the force acting on an electron moving along the symmetry axes in the vicinity of the centre of the ring ($|z|\ll R$) is harmonic (i.e. depends linearly on $z$).

**iv)** Define the frequency of oscillations of such an electron. Use numerical values $R=1\,\mu\mathrm m$ and $Q=1.0\times10^{-13}\,\mathrm C$.

**v)** Now, let us assume that the electron can perform also off-axis movements. Is the position at the symmetry centre of the ring (on-axis, $z=0$) stable or unstable? Motivate your answer.

*Hint:* You may use the approximate formula
$$(1+x)^\alpha\approx1+\alpha x+\tfrac12\alpha(\alpha-1)x^2.$$

> [!answer]- Ответ
> **i**
>
> $$
> \varphi=kQ/\sqrt{R^2+z^2}.
> $$
>
> **ii** — $E=-\frac{d\varphi}{dz}=kQz/(R^2+z^2)^{3/2}$.
>
> **iii** — $E=\approx kQz/R^3$.
>
> **iv** — $f=\frac1{2\pi R}\sqrt{\frac{ekQ}{mR}}\approx5.6\times10^{12}\,\mathrm{Hz}$.

> [!solution]- Решение
> # 2. Nanoclock (10 points)
>
> **i)** All the charges of the ring are at the same distance from the point $P$, $l=\sqrt{R^2+z^2}$. So, according to the superposition principle, the potential is the sum of potential of all the charges,
>
> $$\varphi=kQ/\sqrt{R^2+z^2}.$$
>
> **ii)**
> $E=-\frac{d\varphi}{dz}=kQz/(R^2+z^2)^{3/2}$.
>
> **iii)** For $|z|\ll R$ we may approximate $(R^2+z^2)^{3/2}\approx R^3$, so that
> $E=\approx kQz/R^3$.
>
> **iv)** From the Newton II law, $m\ddot z=-ekQz/R^3$, i.e. $\omega^2=ekQ/mR^3$ and
> $f=\frac1{2\pi R}\sqrt{\frac{ekQ}{mR}}\approx5.6\times10^{12}\,\mathrm{Hz}$.
>
> **v)** At the origin, there are no charges; hence, the electric field lines cannot neither start nor end there. Consider a tiny coaxial cylinder embracing the origin. The field lines exit the cylinder through its bottom and top surfaces (because there is an electric field $E=\approx kQz/R^3$). Hence there must be field lines entering the cylinder through its side surface. This implies a radial repelling force for an electron situated at that surface, i.e. instability.
>
> *Remark:* In the same way, one can prove a theorem, electrostatic equilibria are always unstable.
