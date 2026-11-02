---
id: nbpho-2015-intl-theory-7
olympiad: NbPhO
year: 2015
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "7"
title: "Bouncy ball"
points: 5
aliases: ["Bouncy ball"]
topics: ["[[1.17 Законы сохранения энергии и импульса]]", "[[1.7 Качение твёрдого тела]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Определить вращение шара и минимальное трение при упругом отскоке от стены."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 7. BOUNCY BALL (5 points)

**NbPhO 2015** · Международная олимпиада · теория · 10–12 класс · задача 7  
Источник: [[_pdf/NbPhO/nbpho-2015.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2015.pdf#page=7|решение, стр. 7]]

Темы: [[1.17 Законы сохранения энергии и импульса]], [[1.7 Качение твёрдого тела]]

> [!abstract] Кратко (составлено моделью)
> Определить вращение шара и минимальное трение при упругом отскоке от стены.

*(by J. Toots)*

A homogeneous elastic ball with radius $R$ bounces from a vertical wall in such a way that it rebounds back exactly in the same direction it came from. The ball’s speed before the bounce is $v$ at an angle $\alpha$ to the vertical; the ball also has an angular speed $\omega$. There was no slipping at the contact point, but do not assume that $\omega R=v\cos\alpha$. The bounce was completely elastic, ie no kinetic energy was lost; also, the horizontal components of incident and rebound velocities have the same magnitude. The moment of inertia for a homogeneous ball is $I=\frac25mR^2$.

**i)** (1 point) Find the angular speed $\omega_2$ of the ball after the bounce.

**ii)** (2 points) Find the initial angular speed $\omega$ in terms of $v$, $\alpha$ and $R$.

**iii)** (2 points) What is the minimum value for coefficient of friction $\mu$ that such bounce could happen?

> [!answer]- Ответ
> **i** — $\omega_2=-\omega$.
>
> **ii** — $\omega=\frac{mav}{I}=\frac{5v\cos\alpha}{2R}$.
>
> **iii** — $\mu\geq\cot\alpha$.

> [!solution]- Решение
> # 7. BOUNCY BALL
>
> **i)** Energy is conserved: $\frac{mv^2}{2}+\frac{I\omega^2}{2}=\frac{mv^2}{2}+\frac{I\omega_2^2}{2}\implies|\omega_2|=|\omega|$. As the ball receives some angular momentum from the wall (the net force from the wall is not directed through the ball’s centre), the angular velocity changes its sign — the rotation flips its direction and
> $\omega_2=-\omega$.
>
> **ii)** The angular momentum is conserved with respect to the contact point, because all the forces are directed through the point. Let $a=R\cos\alpha$ be the distance from the trajectory of the center of mass to the contact point. Then the aforementioned angular momentum conservation reads $I\omega-mav=I\omega_2+mav$. As $\omega_2=-\omega$, this gives
> $\omega=\frac{mav}{I}=\frac{5v\cos\alpha}{2R}$.
>
> **iii)** At the verge of slipping on a surface, the angle between the surface normal and the resultant of the reaction force and the friction force equals $\arctan\mu$. Here this angle is $\frac\pi2-\alpha$, thence
> $\mu\geq\cot\alpha$.
