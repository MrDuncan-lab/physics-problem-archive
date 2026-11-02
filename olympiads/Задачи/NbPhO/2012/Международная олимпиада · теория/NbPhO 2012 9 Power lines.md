---
id: nbpho-2012-intl-theory-9
olympiad: NbPhO
year: 2012
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "9"
title: "Power lines"
points: 7
aliases: ["Power lines"]
topics: ["[[1.15 Упругость. Весомая пружина]]", "[[1.20 Колебания]]", "[[1.10 Статика]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Определить скорость волн, натяжение и основную частоту колебаний провисающего провода."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# Problem 9. Power lines (7 points)

**NbPhO 2012** · Международная олимпиада · теория · 10–12 класс · задача 9  
Источник: [[_pdf/NbPhO/nbpho-2012.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2012.pdf#page=5|решение, стр. 5]]

Темы: [[1.15 Упругость. Весомая пружина]], [[1.20 Колебания]], [[1.10 Статика]]

> [!abstract] Кратко (составлено моделью)
> Определить скорость волн, натяжение и основную частоту колебаний провисающего провода.

**i.** (2 pts) Consider a rope of linear density $\sigma$ (mass per unit length), which is stretched so as to maintain a mechanical tension $T$ in the rope. Show that along such a rope, perturbations (eg. waves) will travel with the speed $k\sqrt{T/\sigma}$, and find the coefficient $k$.

**ii.** (2 pts) Now, consider a power line between two poles, the distance between of which is $L$; the linear density of the wire is $\sigma$, and the middle point of the wire hangs below the horizontal level at which the wire is fixed to the poles by a distance $d$. Find the tension $T$ in the wires assuming that $d\ll L$. *Hint:* make use of the torque balance for a half of the wire.

**iii.** (3 pts) Find the lowest frequency $f_0$ of free oscillations of such a power line (the amplitude of the oscillations is so small that the tension in the wire remains essentially constant).

> [!answer]- Ответ
> **9.i** — $k=1$.
>
> **9.ii**
>
> $$
> Td=\frac L4\sigma g\frac L2\Rightarrow T=\frac{L^2\sigma g}{8d}.
> $$
>
> **9.iii** — $f_0=v/2L=\frac1{2L}\sqrt{\frac T\sigma}$.

> [!solution]- Решение
> # Problem 9. Power lines (7 points)
>
> **i.** (2 pts) Let us use a frame where the moving perturbations are at rest. There, the centripetal acceleration required for the motion along a trajectory of curvature radius $R$ is given by the mechanical tension of the rope, for a small piece of rope (of length $l$)
>
> $$T\frac{l}{R}=\frac{v^2}{R}\sigma l\Rightarrow v=\sqrt{\frac{T}{\sigma}},$$
>
> ie.
> $k=1$.
>
> **ii.** (2 pts) We consider the torque balance for one half of the wire, with respect to the point where it is fixed to the pole. Then, the centre of mass lays approximately at the distance $\frac L4$ (since the shape of the wire is not far from a straight line), and the equation can be written as
>
> $$Td=\frac L4\sigma g\frac L2\Rightarrow T=\frac{L^2\sigma g}{8d}.$$
>
> **iii.** (3 pts) For the natural oscillation modes, there will be standing waves with nodes at the fixing points; the lowest frequency corresponds to the longest wavelength, which is $2L$, so that
> $f_0=v/2L=\frac1{2L}\sqrt{\frac T\sigma}$.
