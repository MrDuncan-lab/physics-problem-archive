---
id: nbpho-2010-intl-theory-4
olympiad: NbPhO
year: 2010
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "4"
title: "Ball"
points: 6
aliases: ["Ball"]
topics: ["[[1.10 Статика]]", "[[1.7 Качение твёрдого тела]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Найти минимальную силу и точку её приложения для подъёма шара вдоль стены."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 4. Ball (6 points)

**NbPhO 2010** · Международная олимпиада · теория · 10–12 класс · задача 4  
Источник: [[_pdf/NbPhO/nbpho-2010.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2010.pdf#page=4|решение, стр. 4]]

Темы: [[1.10 Статика]], [[1.7 Качение твёрдого тела]]

> [!abstract] Кратко (составлено моделью)
> Найти минимальную силу и точку её приложения для подъёма шара вдоль стены.

Massive spherical ball has a mass $M=100\mathrm{kg}$; an attempt is made to roll the ball upwards, along a vertical wall, by applying a force $F$ to some point $P$ on the ball. The coefficient of friction between the wall and the ball is $\mu=0.7$.

**i)** (5 pt) What is the minimal force $F_{\min}$ required to achieve this goal?

**ii)** (1 pt) On a side view of the ball and the wall, construct geometrically the point $P$, where the force has to be applied to, together with the direction of the applied force.

> [!answer]- Ответ
> **i** — $F_{\mathrm{min}}=mgR/OA=mg/\sqrt{1+\mu^2}\approx800\,\mathrm{N}$.

> [!solution]- Решение
> # Problem 4. Ball (6 points)
>
> ![[nbpho-2010-p4-f1.svg]]
>
> The friction force $F_f$ cannot exceed $\mu N$, where $N$ is the normal force. Hence, the resultant vector $\vec T$ of those two forces must point to some point $Q$ on the segment $AB$, the length of which is $2\mu R$, and $R$ stands for the radius of the ball (so that $AC=\mu R$, where $C$ is the ball’s center).
>
> The ball has three forces applied: the force applied by the wall ($\vec T$), the gravity force $m\vec g$, and the external force $\vec F$. All the lines defined by these vectors must intersect in a single point. Indeed, suppose that the line defined by the force $\vec F$ intersects the vertical axis of the ball in a point, different from $Q$. Then it would have a non-zero torque with respect to the point $Q$ — unlike the other two forces, causing imbalance of torques.
>
> Now let us consider the torque balance with respect to $O$. The torque of the gravity force $mgR$ is balanced by the torque of $F$; so, in order to have as small as possible force $F$, its lever arm must be as long as possible. Hence, $Q$ must be as far away as possible from $O$, i.e. coincide with $A$, and $PA$ must be perpendicular to $OA$ (this answers the question ii). Finally,
> $F_{\mathrm{min}}=mgR/OA=mg/\sqrt{1+\mu^2}\approx800\,\mathrm{N}$.
