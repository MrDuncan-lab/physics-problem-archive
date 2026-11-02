---
id: nbpho-2004-intl-theory-5
olympiad: NbPhO
year: 2004
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "5"
title: "4th order ellipse"
points: 6
aliases: ["4th order ellipse"]
topics: ["[[1.10 Статика]]", "[[1.11 Центр масс]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Найти положения равновесия цилиндра с сечением в виде эллипса четвёртого порядка и исследовать их устойчивость."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 5. 4th order ellipse (6 pts)

**NbPhO 2004** · Международная олимпиада · теория · 10–12 класс · задача 5  
Источник: [[_pdf/NbPhO/nbpho-2004.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2004.pdf#page=3|решение, стр. 3]]

Темы: [[1.10 Статика]], [[1.11 Центр масс]]

> [!abstract] Кратко (составлено моделью)
> Найти положения равновесия цилиндра с сечением в виде эллипса четвёртого порядка и исследовать их устойчивость.

4th order ellipse is defined by equation $\frac{x^4}{a^4}+\frac{y^4}{b^4}=1$, where $a$ and $b$ are the lengths of the half-axes. Consider an homogeneous cylinder, the cross-section of which is 4th order ellipse. The position of the cylinder is measured by the angle $0\leq\varphi\leq\pi/2$ between the vertical direction and a longer half-axes, see figure.

![[nbpho-2004-p1-f4.svg]]

**1)** What are the equilibrium positions of the cylinder laying on an horizontal surface (3.5 pts)?

**2)** Sketch on graph the net torque of gravity and surface reaction forces with respect to the contact point of the cylinder and surface as a function of $\varphi$ ($0\leq\varphi\leq\pi/2$). For the axis of torque, you do not need to indicate any quantitative scale (1.3 pts).

**3)** Which equilibrium positions are stable and which are not? Motivate your answer (1.2 pts).

> [!answer]- Ответ
> **1** — $\frac yx=(\frac ba)^2=\varphi=\arctan\frac yx=(\frac ba)^2$.

> [!solution]- Решение
> # 5. 4th order ellipse (6 pts)
>
> **1)** There are trivial positions
> $\varphi=0$ and $\varphi=\pi/2$. Besides, there is a position between these two. At the equilibrium, the vector from the origin to the touching point $\vec r=(x,y)$ has to be perpendicular to the tangent at that point. In order to find the tangent, let us differentiate the ellipse formula: $4\frac{x^3}{a^4}dx+4\frac{y^3}{b^4}dy=0$, hence, with $dx=1$, $dy=-\frac{x^3}{y^3}\frac{b^4}{a^4}$, a tangent vector is $\vec\tau=[1,-(\frac xy)^3(\frac ba)^4]$. The vectors are perpendicular, if the scalar product is zero: $x-y(\frac xy)^3(\frac ba)^4$, i.e.
> $\frac yx=(\frac ba)^2=\varphi=\arctan\frac yx=(\frac ba)^2$.
>
> **2)** Around each zero $\varphi$ changes sign. At $\varphi=0$, small increase in $\varphi$ will result in a torque trying to return to the initial position, i.e. the torque becomes negative. So, the graph looks like the one below.
>
> ![[nbpho-2004-p3-f2.svg]]
>
> **3)** If the derivative of the graph at equilibrium point is negative, the position is stable; otherwise it is unstable. $\varphi=0$ and $\varphi=\pi/2$ are stable, $\varphi=(\frac ba)^2$ is unstable.
