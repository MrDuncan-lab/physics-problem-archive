---
id: nbpho-2014-intl-theory-4
olympiad: NbPhO
year: 2014
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "4"
title: "Superballs"
points: 5
aliases: ["Superballs"]
topics: ["[[1.17 Законы сохранения энергии и импульса]]", "[[1.16 Закон сохранения импульса]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Найти скорости и высоту верхнего шара после последовательных упругих столкновений в стопке."
status: "проверено: сверка, два чтения + арбитр"
lang: en
tags: [задача]
---

# 4. SUPERBALLS (5 points)

**NbPhO 2014** · Международная олимпиада · теория · 10–12 класс · задача 4  
Источник: [[_pdf/NbPhO/nbpho-2014.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2014.pdf#page=3|решение, стр. 3]]

Темы: [[1.17 Законы сохранения энергии и импульса]], [[1.16 Закон сохранения импульса]]

> [!abstract] Кратко (составлено моделью)
> Найти скорости и высоту верхнего шара после последовательных упругих столкновений в стопке.

$n+1$ elastic balls are dropped so that they are exactly above each other, with a very small gap between each. Bottom ball has a mass of $m_0$, the one above has a mass of $fm_0$, next $f^2m_0$ and so on, until the topmost ball with mass $f^nm_0$, where $f<1$. At the moment when the bottom ball touches the ground, all the balls are moving with the speed $v$.

**i)** (1 point) After the collision between the two bottommost balls, what is the speed $v_1$ of the second ball from the bottom?

**ii)** (3 points) What is the speed of the topmost ball $v_n$ after all collisions?

**iii)** (1 point) How many times higher would that ball fly compared to the initial drop height $h$? Take $f=0.5$ and $n=10$.

It maybe useful that that sequence $a_0=1$, $a_{k+1}=a_k\alpha+\beta$ has a general term $a_n=\alpha^n+\beta\frac{\alpha^n-1}{\alpha-1}$, where $\alpha$ and $\beta$ are constants.

> [!answer]- Ответ
> **4.1** — $v_1=\frac{3-f}{1+f}v=\left(\frac{4}{1+f}-1\right)v$.
>
> **4.2** — $v_n=\left(2\left(\frac{2}{1+f}\right)^n-1\right)v$.
>
> **4.3**
>
> $$
> h_n/h_0=\sqrt{v_n/v_0}=\sqrt{2\left(\frac{2}{1+f}\right)^n-1}.
> $$

> [!solution]- Решение
> # 4. Superballs
>
> **1)** During the collision with the floor, the bottom-most ball will retain its speed and change the direction of the velocity; its upwards speed $v_0=v$. Let the $k$-th ball move up with a velocity $v_k$; we’ll consider the collision between this and $(k+1)$-st ball, which moves down with the velocity $v$. In the frame of reference of the centre of mass, $u=\frac{v_k-fv}{1+f}$; hence, after the collision the upwards velocity equals to $v_{k+1}=v+2\frac{v_k-fv}{1+f}=\frac{2}{1+f}v_k+\frac{1-f}{1+f}v$. With $v_0=v$, we can conclude that
> $v_1=\frac{3-f}{1+f}v=\left(\frac{4}{1+f}-1\right)v$.
>
> **2)** One can see that if we apply the recurrent formula repetitively, the result at the $n$-th step will be
> $v_n=\left(2\left(\frac{2}{1+f}\right)^n-1\right)v$.
>
> **3)** Now we need to relate the speeds to the jumping heights via $v^2=2gh_0$ and $v_n^2=2gh_n$; hence,
>
> $$h_n/h_0=\sqrt{v_n/v_0}=\sqrt{2\left(\frac{2}{1+f}\right)^n-1}.$$
>
> For $f=0.5$ and $n=10$ we obtain that the final height will be $ca\ 1200$ larger than the initial one.
