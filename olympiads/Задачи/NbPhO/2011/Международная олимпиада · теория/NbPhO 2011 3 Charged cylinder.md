---
id: nbpho-2011-intl-theory-3
olympiad: NbPhO
year: 2011
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "3"
title: "Charged cylinder"
points: 8
aliases: ["Charged cylinder"]
topics: ["[[4.1 Сила Лоренца]]", "[[4.3 Индуктивность. Взаимоиндукция]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Найти магнитное поле вращающегося заряженного цилиндра и ЭДС в соединяющем проводе."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 3. Charged cylinder (8 points)

**NbPhO 2011** · Международная олимпиада · теория · 10–12 класс · задача 3  
Источник: [[_pdf/NbPhO/nbpho-2011.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2011.pdf#page=3|решение, стр. 3]]

Темы: [[4.1 Сила Лоренца]], [[4.3 Индуктивность. Взаимоиндукция]]

> [!abstract] Кратко (составлено моделью)
> Найти магнитное поле вращающегося заряженного цилиндра и ЭДС в соединяющем проводе.

Dielectric cylinder of radius $r$ carries a charge of surface density $\sigma$ on its cylindrical surface and rotates with angular velocity $\omega$.

**i)** (3 pts) Determine the magnetic induction $B$ inside the cylinder. *Remark:* if you wish, you can use the expression for the inductance $L=\mu_0N^2S/l$ of a solenoidal coil of radius $r$, length $l\gg r$, area of cross-section $S$ and number of loops $N$.

**ii)** (3 pts) A radial conducting wire connects the axis of the cylinder with the cylindrical surface (it rotates together with the cylinder). Find the electromotive force (voltage) $\mathcal E$ between the ends of the wire.

**iii)** (2 pts) Suppose that the wire connecting the axis of the cylinder with the cylindrical surface is not radial and has an arbitrary shape (still, there are no segments protruding outside the cylinder). Show that $\mathcal E$ does not depend on the shape of the wire.

> [!answer]- Ответ
> **i** — $B=\mu_0j=\mu_0\sigma\omega r$.
>
> **ii**
>
> $$
> \mathcal E=\mu_0\sigma\omega^2r^3/2.
> $$

> [!solution]- Решение
> # 3. Charged cylinder (8 points)
>
> **i)** Moving surface charge creates a solenoidal surface current with the surface density $j=\sigma v=\sigma\omega r$. From the circulation theorem for a rectangular loop embracing a segment of surface current we obtain $\frac{Bl}{\mu_0}=jl$, where $l$ is the length of the surface current segment (so that $jl$ gives the current flowing through the loop). Hence,
> $B=\mu_0j=\mu_0\sigma\omega r$.
>
> **ii)** Using formula $\mathcal E=\frac{d\Phi}{dt}=B\frac{dS}{dt}$, where $S$ is the area covered by the wire, we obtain $\mathcal E=B\omega r^2/2$. Indeed, during a small time interval $dt$, the wire covers an equilateral triangle of side lengths $r$, $r$, and $r\omega dt$; its area is apparently $r^2\omega dt/2$. By using the earlier obtained expression for $B$ we end up with
>
> $$\mathcal E=\mu_0\sigma\omega^2r^3/2.$$
>
> **iii)** We need to show that from the previous task, $\frac{dS}{dt}$ is independent of the wire shape. First we note that due to rotational symmetry, $\frac{dS}{dt}$ cannot depend on the rotation angle, i.e. $\frac{dS}{dt}\equiv\dot S=\mathrm{Const}$. Further we note that regardless of the wire shape, during the entire rotation period $2\pi/\omega$, the whole circle area is covered: $\dot S\cdot2\pi/\omega=\pi r^2\Rightarrow\dot S=r^2\omega/2$.
