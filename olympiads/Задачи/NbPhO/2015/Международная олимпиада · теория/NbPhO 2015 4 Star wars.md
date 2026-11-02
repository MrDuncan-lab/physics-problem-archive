---
id: nbpho-2015-intl-theory-4
olympiad: NbPhO
year: 2015
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "4"
title: "Star wars"
points: 8
aliases: ["Star wars"]
topics: ["[[1.17 Законы сохранения энергии и импульса]]", "[[1.3 Равноускоренное криволинейное движение]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Найти период орбиты и границу области поражения баллистической ракеты в поле звезды."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 4. STAR WARS (8 points)

**NbPhO 2015** · Международная олимпиада · теория · 10–12 класс · задача 4  
Источник: [[_pdf/NbPhO/nbpho-2015.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2015.pdf#page=6|решение, стр. 6–7]]

Темы: [[1.17 Законы сохранения энергии и импульса]], [[1.3 Равноускоренное криволинейное движение]]

> [!abstract] Кратко (составлено моделью)
> Найти период орбиты и границу области поражения баллистической ракеты в поле звезды.

*(by J. Kalda)*

Here we’ll study, in which region of space targets can be hit with an interplanetary ballistic missile. The launching point $P$ is motionless in the inertial frame of reference of a gravitationally attracting star centred at $S$. The launching speed of the missile is fixed throughout this problem and equal to $v_0$, the same applies to the distance to launching point $|SP|=R$. The mass of the star is $M$, and the gravity constant is $G$. *Hint:* the total energy of a missile of mass $m$ moving on an elliptical orbit is $E=-GMm/(2a)$, where $a$ is the longer semiaxis of its orbit.

**i)** (2 points) The missile is launched as described above in an arbitrary direction. What is the period of the missile on its elliptic orbit?

**ii)** (2 points) According to the Kepler’s I law, the missile’s orbit is an ellipse, with one of the foci being at $S$. The position of the other focus $F$ depends on the launching angle. While the launching angle is changed, the focus $F$ moves along a certain curve; what curve is it? Also, determine the geometric dimensions of that curve.

**iii)** (1 point) Let us consider such a point $Q$ on the missile’s trajectory, the distance of which from the star equals to $|SQ|=r$. Determine the distance $|QF|$.

**iv)** (1 point) The position of point $Q$ (as defined above) depends on the launching angle of the missile, and so does the distance $|PQ|$. Among all the possible positions of the point $Q$, what is the largest possible distance $|PQ|$?

**v)** (2 points) For questions iii and iv, we assumed that the distance $r$ had a fixed value. Now, if we consider $r$ as a free parameter, the position of the point $Q$ is a function of both $r$ and of the launching angle. What is the boundary of that region of space to which the point $Q$ can belong?

> [!answer]- Ответ
> **i** — $T=\frac{2\pi a^{3/2}}{\sqrt{GM}}$.
>
> **ii** — $|PF|=l_2=2a-R$ around $P$.
>
> **iii** — $|QF|=2a-r$.
>
> **iv** — $|QP|_{\max}=4a-R-r$.

> [!solution]- Решение
> # 4. STAR WARS
>
> **i)** The period of a Keplerian orbit having major semi-axis $a$ can be expressed using relation $T^2=\frac{4\pi^2a^3}{GM}$. However, if we didn’t know the formula, we should recall Kepler’s 3rd law $T^2\sim a^3$ and simply express the period for a circular orbit with $a=r$. Therefore, $T^2=\frac{4\pi^2r^2}{v^2}$, were we need to insert $v$ from $\frac{v^2}{r}=\frac{GM}{r^2}$.
>
> For finding the period, we can get the major semi-axis from the expression for orbit’s total energy $-\frac{GMm}{2a}=\frac{mv^2}{2}-\frac{GMm}{R}$, equivalently $a=\frac{GM}{2\frac{GM}{R}-v^2}=\frac1{\frac2R-\frac{v^2}{GM}}$. Finally
> $T=\frac{2\pi a^{3/2}}{\sqrt{GM}}$.
>
> **ii)** According to the properties of an ellipse, the distances $l_1$ and $l_2$ drawn from any point on the ellipse to its two foci add up to constant value $l_1+l_2=2a$. Since $l_1=R$, the other focus must be at distance $l_2=2a-R$, so the other focus $F$ lies on a circle with radius
> $|PF|=l_2=2a-R$ around $P$.
>
> **iii)** This is the previous part in reverse. Since we have distance to one focus given $|QS|=r$, we can express the distance to the other focus
> $|QF|=2a-r$.
>
> **iv)** The points P, Q, and F form a triangle, for which we have expressed two of its side lengths: $|PF|$ and $|QF|$. The third side QP must satisfy $|QP|\leq|PF|+|QF|$. The $|QP|_{\max}$ is obtained for a degenerated triangle (all the three points lying along a common line). Therefore,
> $|QP|_{\max}=4a-R-r$.
>
> **v)** It turns out that for all the maximal distance points $Q$ the sum of $|SQ|+|PQ|$ is constant and equal to $4a-R$. That means it also defines an ellipse with focal points $S$ and $P$ and major semi-axis $2a-R/2$. This ellipse is the area that we can hit.
