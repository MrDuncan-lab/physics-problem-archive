---
id: nbpho-2024-intl-theory-9
olympiad: NbPhO
year: 2024
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "9"
title: "Triangle"
points: 5
authors: ["Jaan Kalda"]
aliases: ["Triangle"]
topics: ["[[1.11 Центр масс]]", "[[1.6 Векторная кинематика]]", "[[1.13 Кинематические связи (и динамика)]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: true
source_damaged: false
summary: "По положению трёх шариков после разрыва нитей восстановить угол и направление вращения оставшейся нити."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 9. Triangle (5 points) — Jaan Kalda.

**NbPhO 2024** · Международная олимпиада · теория · 10–12 класс · задача 9  
Источник: [[_pdf/NbPhO/nbpho-2024.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2024.pdf#page=9|решение, стр. 9]]

Темы: [[1.11 Центр масс]], [[1.6 Векторная кинематика]], [[1.13 Кинематические связи (и динамика)]]

> [!abstract] Кратко (составлено моделью)
> По положению трёх шариков после разрыва нитей восстановить угол и направление вращения оставшейся нити.

Three identical small iron balls were initially arranged in an equilateral triangle formation, connected by massless non-stretchable threads. Upon being thrown into the air, the system experienced the following conditions: (a) all threads were taut initially; (b) all balls possessed different velocities; (c) all velocities were confined to the plane of the triangle as the system underwent free fall within Earth’s gravitational field. At a certain moment $t = 0$, two threads ruptured, leaving two balls tethered together while the third ball separated from the rest of the system. The accompanying diagram depicts the positions of all three balls and the remaining thread within the plane of their initial arrangement at a later moment of time $t = T$ when all the balls were still continuing their free fall. To answer the questions below, you can take measurements from the figure.

**i)** (4 points) By how many degrees did the remaining thread rotate during the time period from $t = 0$ to $t = T$?

**ii)** (1 point) Was the rotation clockwise or counterclockwise?

![[nbpho-2024-p2-c7529.png]]

> [!answer]- Ответ
> **i** — $\theta=\frac{\sqrt3v}{l}T=\frac{\sqrt{3AG^2-l^2}}{l}=\sqrt{\frac43(\frac{AM}{l})^2-1}$. For a measured value of $\frac{AM}{L}\approx4.8$, $\theta\approx5.5$ radians.

> [!solution]- Решение
> # 9. Triangle (5 points) — Solution by Tudor Plopeanu.
>
> ![[nbpho-2024-p9-c5046.png]]
>
> Let us consider points $A$, where the detached ball is, and $M$, the middle point of the remaining string. Let $G$ be the center of mass of the three balls, lying on the segment $[AM]$ such that $GA=2GM$.
>
> As the same gravity force acted on all the balls, we can consider their free-falling frame and note that our lab-frame picture is simply a translation of a similar picture taken in the free-falling frame. As such, we can work in the free-falling frame, and assume that both the detached ball and the center of mass of the other two balls have moved in a straight line ($A$ and $M$ have moved linearly in time). The overall center of mass, $G$, has not moved at all.
>
> One can easily find the length of the rope from the picture, let us denote it as $l$. Before the ropes snapped, the balls were rotating around $G$, their trajectories being tangential to the circle of center $G$ and radius $\frac{\sqrt3}{3}l$. The ball which detached continued in this trajectory until it reached point $A$. As such, we know that the length the ball has traveled is equal to the length of its tangent to $\mathcal C(G,\frac{\sqrt3}{3}l)$. This length is $\sqrt{AG^2-\frac{l^2}{3}}=vT$, where $v$ is the speed of the detached ball.
>
> For the two balls that are still attached, the angular momentum they had with respect to their center of mass is preserved, and as such they have been rotating around it with speed $\frac{\sqrt3}{2}v$. The angle by which they have rotated is
>
> $\theta=\frac{\sqrt3v}{l}T=\frac{\sqrt{3AG^2-l^2}}{l}=\sqrt{\frac43(\frac{AM}{l})^2-1}$. For a measured value of $\frac{AM}{L}\approx4.8$, $\theta\approx5.5$ radians.
>
> We can discover the same angle geometrically: let us consider the tangents from $M$ to $\mathcal C(G,\frac{\sqrt3}{6}l)$. Each line represents a case, whether the rotation was clockwise or counterclockwise. The string that remained attached went alongside each of these lines, respectively, when the other two strings snapped. The ”top” line represents clockwise rotation and the ”bottom” line represents counterclockwise rotation. As such, the angle should be measured clockwise and counterclockwise respectively. The one most fitting is for the counterclockwise rotation.

> [!grading]- Критерии оценивания
> Grading: (preliminary)
>
> | Criterion | Points |
> |---|---|
> | Student displays knowledge of the situation (rotating in a plane perpendicular to the ground etc.) | 0.5 pts |
> | Determines COM | 0.5 pts |
> | Draws (or detailed describes) trajectory after separation and does so correctly (parallel but not colinear lines of COM-travels etc.). | 0.5 pts |
> | Showing that $\omega_1=\omega_2$ (triangle and two-connected balls) | 1 pts |
> | For each formula: $v_1=\omega_i r$, $s_1=v_1T$, $\alpha=\omega_2T$ | 0.2 pts |
> | Correct final expression $\alpha=\frac{s_1}{r}$ | 0.4 pts |
> | Correct final value $\alpha=5.6\,\mathrm{rad}$ (with some tolerance for measurement errors) | 0.5 pts |
> | For (ii): full marks if correct. Requires (i) to be correct. Answer is counter-clockwise. In exceptionally well motivated cases, half marks are awarded for correct reasoning even from incorrect answers in part (i). | 1 pts |
