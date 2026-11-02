---
id: nbpho-2010-intl-theory-6
olympiad: NbPhO
year: 2010
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "6"
title: "Charges in B"
points: 5
aliases: ["Charges in B"]
topics: ["[[4.1 Сила Лоренца]]", "[[1.6 Векторная кинематика]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Построить траектории двух заряженных частиц в ограниченном магнитном поле и найти минимальное расстояние между ними."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 6. Charges in B (5 points)

**NbPhO 2010** · Международная олимпиада · теория · 10–12 класс · задача 6  
Источник: [[_pdf/NbPhO/nbpho-2010.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2010.pdf#page=4|решение, стр. 4]]

Темы: [[4.1 Сила Лоренца]], [[1.6 Векторная кинематика]]

> [!abstract] Кратко (составлено моделью)
> Построить траектории двух заряженных частиц в ограниченном магнитном поле и найти минимальное расстояние между ними.

There is an homogeneous, parallel to the $z$-axis magnetic field of inductance $B$ in region $x>0$. In region $x<0$, there is no field. There are two particles of mass $m$ and charge $q$. Initially, the particles have coordinates $y=z=0$, and respectively $x=-L_0$ and $x=-2L_0$ (with $L_0>0$). Initial velocity of both particles is $v$, along the $x$-axis, towards the magnetic field. Neglect the electrostatic repulsion force of the two charges.

**i)** (1,5 pt) Sketch the trajectory of the first particle, and the dependence of its $y$-coordinate on time.

**ii)** (3,5 pt) Sketch the distance $L$ between the particles as a function of time $t$, assuming that $\pi mv/Bq>L$. What is the minimal distance $L_{\min}$?

> [!answer]- Ответ
> **ii**
>
> $$
> L_{\mathrm{min}}=\frac{2mv}{qB}\sin\frac{L_0qB}{2mv}.
> $$

> [!solution]- Решение
> # Problem 6. Charges in B (5 points)
>
> ![[nbpho-2010-p4-f3.svg]]
>
> **i.** (1.5 pts) In the magnetic field, the particle moves along a circle of radius $R$, such that the Lorentz force $qvB=mv^2/R$, hence $R=mv/qB$. Outside the magnetic field, the trajectory is a straight line, see Fig. For the period of circular motion, $y=R-R\cos(\omega t)$, for the rest of the time, $y=0$ or $y=2R$.
>
> **ii.** (3.5 pts) The second particle follows the first one by being delayed along the trajectory by the same distance as it was originally. Once the first particle enters the magnetic field, the geometrical distance starts decreasing and achieves a minimum, when the distance changing rate swaps sign, i.e. reaches zero (at least for a single moment). In that state, they move as if being a part of a rigid body, i.e. the distance to the instantaneous rotation center (which would be the intersection point of the perpendiculars to the velocity vectors) must be equal for both particles (because the velocities are equal). It is easy to see that this equality of distances is achieved precisely when the second particle also enters the field and remains satisfied as long as both particles stay there. When the first particle exits the field, the distance starts increasing symmetrically to how it decreased before. The resulting graph is sketched in Fig; note that the curve is smooth: indeed, non-smooth joints of segments would imply infinite second time-derivative of the distance, i.e. infinite acceleration and force.
>
> ![[nbpho-2010-p4-f2.svg]]
>
> Once both particles are in the field, they are on a end-points of circle segment of arclength $L_0$. So, the distance $L_{\mathrm{min}}=2R\sin\frac\alpha2$, where the angle in radians $\alpha=L_0/R$. So,
>
> $$L_{\mathrm{min}}=\frac{2mv}{qB}\sin\frac{L_0qB}{2mv}.$$
