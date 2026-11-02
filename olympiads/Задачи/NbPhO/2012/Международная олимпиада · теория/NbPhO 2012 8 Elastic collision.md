---
id: nbpho-2012-intl-theory-8
olympiad: NbPhO
year: 2012
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "8"
title: "Elastic collision"
points: 7
aliases: ["Elastic collision"]
topics: ["[[1.17 Законы сохранения энергии и импульса]]", "[[1.12 Теорема о движении центра масс]]", "[[1.6 Векторная кинематика]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Исследовать упругое нецентральное столкновение шаров и максимальный угол отклонения."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# Problem 8. Elastic collision (7 points)

**NbPhO 2012** · Международная олимпиада · теория · 10–12 класс · задача 8  
Источник: [[_pdf/NbPhO/nbpho-2012.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2012.pdf#page=5|решение, стр. 5]]

Темы: [[1.17 Законы сохранения энергии и импульса]], [[1.12 Теорема о движении центра масс]], [[1.6 Векторная кинематика]]

> [!abstract] Кратко (составлено моделью)
> Исследовать упругое нецентральное столкновение шаров и максимальный угол отклонения.

Consider a perfectly elastic collision of two balls, one of which has mass $M$ and is moving with velocity $v$. The other has mass $m\leq M$ and stays initially at rest. The collision is not necessarily central. The surface of the balls is slippery, so the balls will not rotate.

**i.** (1 pt) What are the momenta of the balls before the collision in the frame of reference where the centre of mass of the whole system stays at rest?

**ii.** (3 pts) What are the momenta of the balls (by moduli) after the collision in the mass centre’s frame of reference?

**iii.** (3 pts) What is the maximal angle $\alpha$ by which the trajectory of the initially moving ball can be inclined as a result of the collision?

> [!answer]- Ответ
> **8.i** — $\vec p=-m\vec u=-\frac{Mm}{M+m}\vec v$. Since in this frame, the centre of mass is at rest, the large ball needs to have equal by modulus and opposite momentum.
>
> **8.ii**
>
> $$
> \frac{\vec{p}^2}{2m}+\frac{\vec{p}^2}{2M}=\frac{\vec{p}'^2}{2m}+\frac{\vec{p}'^2}{2M}\Rightarrow|\vec p|=|\vec{p}'|,
> $$
>
> **8.iii**
>
> $$
> \alpha=\arcsin\frac{|\vec{p}'|}{|M\vec u|}=\arcsin\frac{m}{M}.
> $$

> [!solution]- Решение
> # Problem 8. Elastic collision (7 points)
>
> **i.** (1 pt) The centre of mass moves with the velocity $\vec u=\frac{M}{M+m}\vec v$, and that will be the speed of the small ball in new reference frame, hence its momentum
> $\vec p=-m\vec u=-\frac{Mm}{M+m}\vec v$. Since in this frame, the centre of mass is at rest, the large ball needs to have equal by modulus and opposite momentum.
>
> **ii.** (3 pts) Let the balls change a momentum $\vec q$. The small ball will have momentum $\vec{p}'=\vec p+\vec q$, and as the centre of mass remains at rest, the large ball will have momentum $-\vec{p}'$. The energy conservation law can be written now as follows:
>
> $$\frac{\vec{p}^2}{2m}+\frac{\vec{p}^2}{2M}=\frac{\vec{p}'^2}{2m}+\frac{\vec{p}'^2}{2M}\Rightarrow|\vec p|=|\vec{p}'|,$$
>
> ie. the moduli of the momenta will remain unchanged.
>
> **iii.** (3 pts) In the laboratory frame, the momentum of the large ball will be
>
> $$\vec{p}''=M\vec u-\vec{p}';$$
>
> since $|\vec{p}'|$ remains constant, the angle $\alpha$ between $\vec{p}''$ and $\vec u$ will be maximal when $\vec{p}''\perp\vec{p}'$, with
>
> $$\alpha=\arcsin\frac{|\vec{p}'|}{|M\vec u|}=\arcsin\frac{m}{M}.$$
