---
id: nbpho-2010-intl-theory-7
olympiad: NbPhO
year: 2010
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "7"
title: "Satellite"
points: 5
aliases: ["Satellite"]
topics: ["[[1.17 Законы сохранения энергии и импульса]]", "[[1.5 Удары в кинематике]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Исследовать последовательность упругих ударов шаров и оценить возможность запуска спутника."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 7. Satellite (5 points)

**NbPhO 2010** · Международная олимпиада · теория · 10–12 класс · задача 7  
Источник: [[_pdf/NbPhO/nbpho-2010.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2010.pdf#page=4|решение, стр. 4]]

Темы: [[1.17 Законы сохранения энергии и импульса]], [[1.5 Удары в кинематике]]

> [!abstract] Кратко (составлено моделью)
> Исследовать последовательность упругих ударов шаров и оценить возможность запуска спутника.

**i)** (3 pt) A large ball of mass $m_1$ is kept at the height $h$ from the floor (so that the center of the ball is at the height $h+d/2$, where $d$ is its diameter). A small ball of mass $m_2$ is placed upon the large one, and the system is released (so that it starts falling). To which height (from the floor) will the small ball rise, assuming that the collision between the lower ball and ground, and the collision between the balls are absolutely elastic, and $m_1\gg m_2$?

**ii)** (2 pt) Consider the following satellite launching project. There are $N$ absolutely elastic balls of masses $m_1\gg m_2\gg\ldots\gg m_N$: the first ball (the heaviest) is the lowest; the second ball is placed on top of the first; the third — on top of the second etc. The upmost ball is supposed to become a satellite, i.e. to obtain the velocity $v_N=7.8\mathrm{km/s})$. The lowest ball is at the height $h=1\mathrm{m}$ from the floor, and the system is released. What should be the number of balls $N$? What should be the mass of the lowest ball, if $m_i/m_{i+1}=10$, and the mass of the satellite $M_N=1\mathrm{kg}$?

> [!answer]- Ответ
> **ii**
>
> $$
> N=\left\lceil\log_2\left(1+\frac{v_N}{2gh}\right)\right\rceil=11.
> $$
>
> **ii** — $M_N\cdot10^{N-1}=1\times10^{10}\,\mathrm{kg}$.

> [!solution]- Решение
> # Problem 7. Satellite (5 points)
>
> **i.** (3 pts) Before the collisions, the balls achieve the velocity $u=\sqrt{2gh}$. The first collision is between the large ball and ground; the velocity of the large ball reverses direction. Let us consider the second collision in the system of the center of mass, which is approximately the same as the large ball’s system of reference. In that system, the small ball approaches with velocity $u+u=2u$, and after the collisions, departs with the same velocity. In the laboratory system, the velocity is $2u+u=3u=3\sqrt{2gh}$.
>
> **ii.** (2 pts) We use the same method as previously. Let designate the velocity of the $i$-th ball before the $i+1$-st collision by $v_i$. Then, in the system of the $i$-th ball, the $i+1$-st ball approaches and departs (after the collision) with the velocity $v_i+u$; in the laboratory system, the departing velocity is
>
> $$v_{i+1}=(v_i+u)+v_i=2v_i+u.$$
>
> Bearing in mind that $v_1=u$, we find that $v_2=3u$, $v_3=7u$, $v_4=15u$ etc, $v_N=(2^N-1)u$. So, $v_N=(2^N-1)\sqrt{2gh}$, hence
>
> $$N=\left\lceil\log_2\left(1+\frac{v_N}{2gh}\right)\right\rceil=11.$$
>
> Here, $\lceil\ldots\rceil$ denotes the ceiling function, i.e. rounding up. Each next ball is 10 times less massive than the previous one, so that the lowest ball must have a mass equal to
> $M_N\cdot10^{N-1}=1\times10^{10}\,\mathrm{kg}$.
