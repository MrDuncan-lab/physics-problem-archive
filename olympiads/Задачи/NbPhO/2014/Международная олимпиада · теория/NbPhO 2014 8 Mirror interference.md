---
id: nbpho-2014-intl-theory-8
olympiad: NbPhO
year: 2014
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "8"
title: "Mirror interference"
points: 5
aliases: ["Mirror interference"]
topics: ["[[6.5 Волновая оптика]]", "[[6.1 Отражение]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Определить положение и форму интерференционных максимумов света, отражённого от зеркала."
status: "проверено: сверка, два чтения + арбитр"
lang: en
tags: [задача]
---

# 8. MIRROR INTERFERENCE (5 points)

**NbPhO 2014** · Международная олимпиада · теория · 10–12 класс · задача 8  
Источник: [[_pdf/NbPhO/nbpho-2014.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2014.pdf#page=4|решение, стр. 4]]

Темы: [[6.5 Волновая оптика]], [[6.1 Отражение]]

> [!abstract] Кратко (составлено моделью)
> Определить положение и форму интерференционных максимумов света, отражённого от зеркала.

A point source $S$ emits coherent light of wavelength $\lambda$ isotropically in all directions; thus, the wavefronts are concentric spheres. The waves reflect from a dielectric surface placed at a distance $l=N\lambda$ (where $N$ is a large integer) from the point source, and the interference pattern is observed on a screen which is placed to a distance $L\gg l$ from the point source (see figure).

![[nbpho-2014-p2-f2.png]]

In what follows we use the $x$, $y$, and $z$ coordinates as defined in the figure. The screen is parallel to the mirror and lies in the $y-z$-plane.

**i)** (2 points) At which values of the $y$-coordinate (for $z=0$) are the interference maxima observed on the screen? You may assume that $y\ll L$.

**ii)** (1 point) Sketch the shape of few smallest-sized interference maxima on the screen (in $y-z$-plane).

**iii)** (2 points) Now the flat screen is replaced with a spherical screen of radius $L$, centred around the point source. How many interference maxima can be observed?

> [!answer]- Ответ
> **8.1**
>
> $$
> \alpha=\sqrt{\frac{n+0.5}{N}}\Rightarrow y_n=L\sqrt{\frac{n+0.5}{N}},
> $$
>
> **8.3**
>
> $$
> m=(\varphi_\mathrm{max}-\varphi_\mathrm{min})/2\pi=2N.
> $$

> [!solution]- Решение
> # 8. Mirror interference
>
> **1)** For a position $y$, the arriving rays form an angle $\alpha=y/L$ (we use the small-angle approximation; the angle is in radians). Then, the optical path difference between the reflected and direct rays is $\Delta=2l\cos\alpha\approx2N\lambda-N\lambda\alpha^2$. Since there is an additional phase shift for the reflected rays at the reflection from optically denser dielectric material, the total phase shift is $\varphi=2\pi\Delta/\lambda=4\pi N-\pi(2N\alpha^2-1)$. At the maxima, this equals to $2\pi(2N-n)$, where $n$ is an integer. Therefore, the condition for the maxima is written as
>
> $$\alpha=\sqrt{\frac{n+0.5}{N}}\Rightarrow y_n=L\sqrt{\frac{n+0.5}{N}},$$
>
> where $n=0,1,\ldots\ll N$.
>
> **2)** Since the rays of a given order number $n$ form a fixed angle with the $x$-axis, the maxima form on the screen concentric circles; the pitch between the neighbouring circles becomes smaller as the order number $n$ grows (using the length unit defined by the smallest radius, the radii form a sequence $\sqrt1=1$, $\sqrt3\approx1.73$, $\sqrt5\approx2.23$, etc).
>
> **3)** Since the reflected rays can reach the screen only within a hemisphere, the phase shift varies between $\varphi_\mathrm{max}=4\pi N+\pi$ and $\varphi_\mathrm{min}=\pi$. The number of maxima
>
> $$m=(\varphi_\mathrm{max}-\varphi_\mathrm{min})/2\pi=2N.$$
