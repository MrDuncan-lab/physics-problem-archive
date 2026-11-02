---
id: nbpho-2010-intl-theory-8
olympiad: NbPhO
year: 2010
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "8"
title: "Sprinkler"
points: 3
aliases: ["Sprinkler"]
topics: ["[[1.3 Равноускоренное криволинейное движение]]", "[[1.6 Векторная кинематика]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Определить площадь полива и распределение интенсивности воды из полусферического разбрызгивателя."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 8. Sprinkler (3 points)

**NbPhO 2010** · Международная олимпиада · теория · 10–12 класс · задача 8  
Источник: [[_pdf/NbPhO/nbpho-2010.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2010.pdf#page=4|решение, стр. 4–5]]

Темы: [[1.3 Равноускоренное криволинейное движение]], [[1.6 Векторная кинематика]]

> [!abstract] Кратко (составлено моделью)
> Определить площадь полива и распределение интенсивности воды из полусферического разбрызгивателя.

A sprinkler has a shape of hemisphere, which has small holes drilled into the spherical part of its surface. From these small holes, water flows out with velocity $v=10\mathrm{m/s}$. Near the sprinkler, the water flow is distributed evenly over all the directions of the upper half-space. The sprinkler is installed at the ground level so that its axis is vertical. In what follows, the air resistance can be neglected, and the dimensions of the sprinkler can be assumed to be very small.

![[nbpho-2010-p2-f4.svg]]

**i)** (1.5 pt) Find the surface area of the ground watered by the sprinkler.

**ii)** (1.5 pt) At which distance from the sprinkler is the watering intensity (mm/h) the highest?

> [!answer]- Ответ
> **i** — $S=\pi s_{\max}^2=\pi v^4/g^2$.
>
> **i** — $s=s_{\max}$.

> [!solution]- Решение
> # Problem 8. Sprinkler (3 points)
>
> It is known that for a body thrown at some angle $\alpha$ to the horizon with a velocity $v$, the maximal flight length is achieved with $\alpha=45^\circ$ (this result can be also easily derived). That maximal flight length is found as $s_{\max}=vt/\sqrt{2}$, where the flight time $t$ is obtained from the condition $gt=2v/\sqrt{2}$. So, $s_{\max}=v^2/g$. This distance gives the radius of the circular region, watered by the sprinkler; its area is
> $S=\pi s_{\max}^2=\pi v^4/g^2$.
>
> **i. (1.5 pts)** Let us plot the flight distance $s$ as a function of the angle $\alpha$ at the outlet of the sprinkler. This is a smooth curve with one maximum. For a range of distances from $s$ to $s+\Delta s$, the amount of received water is (roughly speaking) proportional to the corresponding width of the angle range $\Delta\alpha$. So, the watering intensity is (roughly) proportional to $Q\propto\frac{\Delta\alpha}{\Delta s}=1/\frac{\Delta s}{\Delta\alpha}$. At the limit of small $\Delta\alpha$ and $\Delta s$, this transforms into a derivative: $Q\propto 1/\frac{ds}{d\alpha}$, i.e. $Q$ tends to infinity at the maximum of $s(\alpha)$. In other words, the best position is at the distance
> $s=s_{\max}$.
