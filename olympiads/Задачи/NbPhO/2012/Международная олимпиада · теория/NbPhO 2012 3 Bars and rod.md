---
id: nbpho-2012-intl-theory-3
olympiad: NbPhO
year: 2012
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "3"
title: "Bars and rod"
points: 5
aliases: ["Bars and rod"]
topics: ["[[1.10 Статика]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Определить минимальную длину стержня, удерживаемого трением между двумя перекладинами."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# Problem 3. Bars and rod (5 points)

**NbPhO 2012** · Международная олимпиада · теория · 10–12 класс · задача 3  
Источник: [[_pdf/NbPhO/nbpho-2012.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2012.pdf#page=4|решение, стр. 4]]

Темы: [[1.10 Статика]]

> [!abstract] Кратко (составлено моделью)
> Определить минимальную длину стержня, удерживаемого трением между двумя перекладинами.

Two cylindrical horizontal bars are fixed one above the other; the distance between the axes of the bars is $4d$, where $d$ is the diameter of the rod. Between the bars, a cylindrical rod of diameter $d$ is placed as shown in Figure (this is a vertical cross-section of the system). The coefficient of friction between the rod and the bars is $\mu=\frac12$. If the rod is long enough, it will remain in equilibrium in such a position. What is the minimal length $L$ of the rod required for such an equilibrium?

![[nbpho-2012-p1-f1.svg]]

> [!answer]- Ответ
> **3**
>
> $$
> L=2AC=(11{,}5+2\sqrt3)d\approx14.96d.
> $$

> [!solution]- Решение
> # Problem 3. Bars and rod (5 points)
>
> With $\mu=\frac12$, the resultant force of the normal force and friction force forms an angle $\arctan\frac12$ with the surface normal (assuming that the rod is as short as possible and hence, at the threshold of slipping). There are three forces applied to the rod — the gravity force $mg$ applied to the centre of mass $C$, and the two forces due to the bars. At equilibrium, the three lines $s_1$, $s_2$, and $s_3$, defined by these three forces need to intersect at a single point $Q$ (otherwise, with respect to the intersection point of two lines, the torque of the third force would cause a rotation of the rod). This configuration is depicted in Figure.
>
> ![[nbpho-2012-p4-f1.svg]]
>
> Since the friction force forms angle $\arctan\frac12$ with the surface normal, hence $\angle DPQ=\angle DRQ=\arctan2$, hence $AP=RS=\frac14d$ (see Figure). From the geometry of the blue triangle, $AS=2\sqrt3d$; due to $AP=RS$, $PR=AS=2\sqrt3d$ and $PD=\sqrt3d$. Now, let us recall that $\tan\angle DPQ=2$, hence $DQ=PR=2\sqrt3d$. From the geometry of the blue triangle, $\angle DCQ=30^\circ$, so that $DC=DQ/\tan30^\circ=6d$. Now we can finally express
>
> $$AC=CD+DP-PA=5\frac34d+\sqrt3d\Rightarrow$$
>
> $$L=2AC=(11{,}5+2\sqrt3)d\approx14.96d.$$
