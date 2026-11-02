---
id: nbpho-2009-intl-theory-1
olympiad: NbPhO
year: 2009
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "1"
title: "Boat"
points: 9
aliases: ["Boat"]
topics: ["[[1.14 Движение в вязкой среде]]", "[[1.16 Закон сохранения импульса]]", "[[1.12 Теорема о движении центра масс]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Найти перемещение лодки с вязким сопротивлением при движении и прыжках человека."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 1. Boat (9 points)

**NbPhO 2009** · Международная олимпиада · теория · 10–12 класс · задача 1  
Источник: [[_pdf/NbPhO/nbpho-2009.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2009.pdf#page=3|решение, стр. 3]]

Темы: [[1.14 Движение в вязкой среде]], [[1.16 Закон сохранения импульса]], [[1.12 Теорема о движении центра масс]]

> [!abstract] Кратко (составлено моделью)
> Найти перемещение лодки с вязким сопротивлением при движении и прыжках человека.

Consider a boat of effective mass $m$, which moves along the (horizontal) $x$-axes, and for which the friction force of the water is given by $F_f=-\alpha v$, where $v$ is the velocity of the boat. (Effective mass is somewhat larger than the real mass, because any change of the boat’s velocity incurs a velocity change of those regions of water, which are close to the boat; hence, the boat’s inertia is complemented by the inertia of the surrounding water.)

**i)** Prove that during this motion,
$$v+kx=\mathrm{Const},$$
and find the factor $k$.

**ii)** Now, a boy of mass $M$ moves inside the boat, back and forth, with velocity $u(t)$ (also, along the $x$-axis). What term must be added to the conservation law $v+kx=\mathrm{Const}$, to describe this situation?

**iii)** Now, let the boat rest initially close to the coast and ready to depart. The boy jumps from the coast into the boat, turns around and jumps back to the coast. The horizontal component of the boy’s velocity during the first jump was $u_1$, and during the second jump $-u_2$. What is the maximum distance $s$ travelled by the boat? Neglect the effect of a vertical motion on the horizontal friction force of the water.

> [!answer]- Ответ
> **i** — $k=\frac\alpha m$.
>
> **ii**
>
> $$
> v+\frac M m u(t)+\frac\alpha m x=\mathrm{Const}.
> $$
>
> **iii**
>
> $$
> s=\frac M\alpha(u_1+u_2),
> $$

> [!solution]- Решение
> # 1. Boat (9 points)
>
> **i)** From the Newton II law, $m\frac{dv}{dt}+\alpha\frac{dx}{dt}=0$. Multiplying this equation by $dt$, we obtain $dv+\frac\alpha m dx=0$. Integrating (i.e. summing over all the small increments $dx$ and $dv$) this equation leads us to
> $$v+\frac\alpha m x=\mathrm{Const},$$
> i.e.
> $k=\frac\alpha m$.
>
> **ii)** We proceed in the same way as before, but we need to add the interaction force between the boat and the boy: $m\frac{dv}{dt}+\alpha\frac{dx}{dt}=M\frac{du}{dt}$. [Note that since the right-hand-side of this equation is the interaction force, it goes to zero, if the boy leaves the boat. Therefore, if we want to keep this equation correct even after the boy leaves the boat at the moment of time $t=t_*$, we must assume $u(t)\equiv u(t_*)$ for $t>t_*$.] Similarly to the previous section, we obtain
>
> $$v+\frac M m u(t)+\frac\alpha m x=\mathrm{Const}.$$
>
> **iii)** We use the conservation law of the previous section, and compare the value of the left-hand-side immediately before the boy lands into the boat with its value after a very long time. Bearing in mind that we need to substitute $u(t\to\infty)=-u_2$ (see above), we obtain
> $$0+\frac M m u_1+0=0-\frac M m u_2+\frac\alpha m s.$$
> So,
>
> $$s=\frac M\alpha(u_1+u_2),$$
> i.e. the result is independent of how long time did the boy spend in the boat.
