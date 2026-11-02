---
id: nbpho-2003-intl-theory-3
olympiad: NbPhO
year: 2003
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "3"
title: "Gravitation"
points: 6
aliases: ["Gravitation"]
topics: ["[[1 Механика]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Исследовать зависимость ускорения свободного падения от формы планеты и найти оптимальную форму."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 3. Gravitation (6 points)

**NbPhO 2003** · Международная олимпиада · теория · 10–12 класс · задача 3  
Источник: [[_pdf/NbPhO/nbpho-2003.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2003.pdf#page=3|решение, стр. 3]]

Темы: [[1 Механика]]

> [!abstract] Кратко (составлено моделью)
> Исследовать зависимость ускорения свободного падения от формы планеты и найти оптимальную форму.

**1)** Find the free falling acceleration $g_0$ at the surface of such a spherical planet, which has mass $M$ and material density $\rho$ (in what follows, $M$ and $\rho$ are assumed to be constant).

**2)** Is it possible that at the surface of a non-spherical planet, there is a point with free falling acceleration $g>g_0$? Motivate your answer.

**3)** For which planet shape the maximum of the free falling acceleration is achieved? Answer can be given in polar coordinates, the expression can contain one unspecified constant.

> [!answer]- Ответ
> **1**
>
> $$
> g_0=\gamma M\left(\frac{4\pi\rho}{3M}\right)^{2/3}.
> $$
>
> **3** — $l=l_0\sqrt{\cos\phi}$.

> [!solution]- Решение
> # 3. Gravitation (6 pts)
>
> **1)** $g_0=\gamma M/R^2$, where $R$ can be found from the relationship $\frac43\pi R^3\rho=M$. Hence,
>
> $$g_0=\gamma M\left(\frac{4\pi\rho}{3M}\right)^{2/3}.$$
>
> **2)** Taking a piece of ground from a certain point of the planet surface and carrying it into another point, the free fall acceleration can be changed (the sign of the change depends on the direction of the transport).
>
> **3)** Let use the polar coordinates with the origin at the point where the free fall acceleration is to be maximized. Let the axis $\phi=0$ be given by the direction of the acceleration. Carrying a small piece of ground from a point $(r_1,\phi_1)$ to another point $(r_2,\phi_2)$ must keep the modulus of the acceleration vector $\vec g$ constant, i.e. the vector of the small change must be perpendicular to the vector $\vec g$. Consequently, $\cos\phi_1/l_1^2=\cos\phi_2/l_2^2$, hence
> $l=l_0\sqrt{\cos\phi}$.
