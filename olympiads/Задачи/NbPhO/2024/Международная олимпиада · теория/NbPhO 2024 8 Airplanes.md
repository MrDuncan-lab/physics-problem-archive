---
id: nbpho-2024-intl-theory-8
olympiad: NbPhO
year: 2024
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "8"
title: "Airplanes"
points: 7
authors: ["Janis Huns", "Jaan Kalda"]
aliases: ["Airplanes"]
topics: ["[[1.6 Векторная кинематика]]", "[[1.1 Равномерное прямолинейное движение]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: true
source_damaged: false
summary: "По путевым скоростям самолётов найти минимальные возможные воздушную скорость и скорость ветра."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 8. Airplanes (7 points) — Janis Huns, Jaan Kalda.

**NbPhO 2024** · Международная олимпиада · теория · 10–12 класс · задача 8  
Источник: [[_pdf/NbPhO/nbpho-2024.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2024.pdf#page=8|решение, стр. 8–9]]

Темы: [[1.6 Векторная кинематика]], [[1.1 Равномерное прямолинейное движение]]

> [!abstract] Кратко (составлено моделью)
> По путевым скоростям самолётов найти минимальные возможные воздушную скорость и скорость ветра.

Two airplanes pass each other while flying at a constant altitudes. While they have identical airspeeds, their ground speeds are $v_1$ and $v_2$, respectively, and the angle between the velocity vectors is $\alpha$. Based on this knowledge, what is the minimal possible value **i)** (1 point) of the airspeed of the planes;

**ii)** (3 points) of the wind speed at the altitudes of the planes?

**iii)** (3 points) Answer the question ii) if now $v_1 = v_2 = v$, but it is known that the airspeed of one of the planes is two times bigger than that of the other.

> [!answer]- Ответ
> **i**
>
> $$
> |   |   |   |   |
> |---|---|---|---|
> |\vec u_1|_{\min}=|\vec v_1-\vec v_2|/2=\frac12\sqrt{v_1^2+v_2^2-2v_1v_2\cos\alpha}.
> $$
>
> **ii**
>
> $$
> |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
> |---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
> |\vec w|_{\min}=\frac{|(\vec v_1+\vec v_2)\cdot(\vec v_1-\vec v_2)|}{2|\vec v_1-\vec v_2|}=\frac{||\vec v_1|^2-|\vec v_2|^2|}{2|\vec v_1-\vec v_2|}=\frac{|v_1^2-v_2^2|}{2\sqrt{v_1^2+v_2^2-2v_1v_2\cos\alpha}}.
> $$
>
> **iii**
>
> $$
> |   |   |   |   |   |   |
> |---|---|---|---|---|---|
> |\vec w|_{\min}=\left|\frac43\vec v_2-\frac13\vec v_1\right|-\frac23|\vec v_2-\vec v_1|=\frac{\sqrt{17-8\cos\alpha}-4\sin\frac\alpha2}{3}v.
> $$

> [!solution]- Решение
> # 8. Airplanes (7 points) — Solution by Tudor Plopeanu.
>
> ![[nbpho-2024-p8-c7582.png]]
>
> **i)** (1 point) Let $\vec w$ be the speed of the wind at the airplanes’ altitude, and let $\vec u_1$ and $\vec u_2$ be the planes’ respective speeds in absence of wind. $\vec v_1=\vec w+\vec u_1$, $\vec v_2=\vec w+\vec u_2$. Let $O'$ be the point such that $\overrightarrow{OO'}=\vec w$, $A$ the point such that $\overrightarrow{OA}=\vec v_1$, and $B$ the point such that $\overrightarrow{OB}=\vec v_2$. As $|\vec w-\vec v_1|=|\vec w-\vec v_2|$, we know that $O'$ lies on the perpendicular bisector of $(AB)$, which we shall denote as $l$. A quick check also yields that all points on this line are valid selections for $\vec w$. $|\vec u_1|=|AO'|$. We can find the minimal airspeed as the length of the perpendicular from $A$ to $l$, of length $|AB|/2$. For a vector result in terms of $\vec v_1$ and $\vec v_2$, we have
>
> $$|\vec u_1|_{\min}=|\vec v_1-\vec v_2|/2=\frac12\sqrt{v_1^2+v_2^2-2v_1v_2\cos\alpha}.$$
>
> **ii)** (3 points) The minimal wind speed is given by the length of the perpendicular from $O$ to $l$. This is the length of $(\vec v_1+\vec v_2)/2$ projected on $\vec v_1-\vec v_2$, and can be found as
>
> $$|\vec w|_{\min}=\frac{|(\vec v_1+\vec v_2)\cdot(\vec v_1-\vec v_2)|}{2|\vec v_1-\vec v_2|}=\frac{||\vec v_1|^2-|\vec v_2|^2|}{2|\vec v_1-\vec v_2|}=\frac{|v_1^2-v_2^2|}{2\sqrt{v_1^2+v_2^2-2v_1v_2\cos\alpha}}.$$
>
> ![[nbpho-2024-p9-f2.svg]]
>
> **iii)** (3 points) In this situation, $|\vec w-\vec v_1|=2|\vec w-\vec v_2|$, so $O'$ is on the Apollonius’s circle with respect to the points $A$ and $B$, such that the points on the circle are 2 times closer to $B$ than to $A$. Let its center be $O''$. Its radius is $R_A=2|\vec v_1-\vec v_2|/3$ (this can be found by considering the intersection points of the Apollonius circle with the line $AB$). We are tasked to find the shortest distance from $O$ to this circle, which is found as $|OO''|-R_A$. We note that $\overrightarrow{OO''}=(4/3)\vec v_2-(1/3)\vec v_1$. The minimal wind speed is thus
>
> $$|\vec w|_{\min}=\left|\frac43\vec v_2-\frac13\vec v_1\right|-\frac23|\vec v_2-\vec v_1|=\frac{\sqrt{17-8\cos\alpha}-4\sin\frac\alpha2}{3}v.$$

> [!grading]- Критерии оценивания
> Grading:
>
> This is relevant for all three subproblems. The solutions are mainly geometric, however several students have tried solving it in a more algebraic manner. If it yielded the correct answer or near correct answer, points were given, but otherwise partial points were not given.
>
> | Criterion | Points |
> |---|---|
> | Representing the problem with vectors and adding the velocities correctly | 0.2 pts |
> | Wrong order or sign | -0.1 pts |
> | The wind velocity vector $w$ on perpendicular bisector of $(AB)$ | 0.4 pts |
> | The minimum airspeed needs $w$ to lie on the intersection of $AB$ and the perpendicular bisector | 0.1 pts |
> | calculating correct answer | 0.3 pts |
> | Small error but reasonable answer with correct units, or not expanded answer that is simple to expand | -0.1 pts |
>
> **ii)**
>
> Grading:
>
> | Criterion | Points |
> |---|---|
> | Representing the problem with vectors and adding the velocities correctly | 0.5 pts |
> | The wind velocity vector $w$ on perpendicular bisector of $(AB)$ | 0.5 pts |
> | The wind velocity is smallest when it is perpendicular to $l$ | 0.5 pts |
> | Calculating the correct answer | 1.5 pts |
> | Small error but reasonable answer with correct units, or not expanded answer that is simple to expand | -0.5 pts |
>
> Grading:
>
> | Criterion | Points |
> |---|---|
> | Representing the problem with vectors and adding the velocities correctly | 0.2 pts |
> | The wind velocity vector $w$ needs to lie on the Apollonius circle (doesn’t need the name) | 1.3 pts |
> | if one realises it is a circle, but not the correct one is given | 0.5 pts |
> | Calculating the $R_A$ | 0.5 pts |
> | Calculating the correct answer | 1 pts |
> | Small error but reasonable answer with correct units, or not expanded answer that is simple to expand | -0.5 pts |
