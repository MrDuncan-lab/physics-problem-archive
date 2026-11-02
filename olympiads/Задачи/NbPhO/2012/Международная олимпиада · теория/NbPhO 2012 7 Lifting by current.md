---
id: nbpho-2012-intl-theory-7
olympiad: NbPhO
year: 2012
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "7"
title: "Lifting by current"
points: 7
aliases: ["Lifting by current"]
topics: ["[[4.2 Сила Ампера]]", "[[1.10 Статика]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Найти форму гибкого проводника и высоту подъёма груза в магнитном поле."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# Problem 7. Lifting by current (7 points)

**NbPhO 2012** · Международная олимпиада · теория · 10–12 класс · задача 7  
Источник: [[_pdf/NbPhO/nbpho-2012.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2012.pdf#page=4|решение, стр. 4–5]]

Темы: [[4.2 Сила Ампера]], [[1.10 Статика]]

> [!abstract] Кратко (составлено моделью)
> Найти форму гибкого проводника и высоту подъёма груза в магнитном поле.

Consider a loop of freely deformable conducting wire with insulation of length $2l$, the two ends of which are fixed (permanently) to the ceiling. A load of mass $m$ is fixed to the middle of the wire (the mass of the wire is negligible). There is also a horizontal magnetic field of induction $B$; free fall acceleration is $g$. A current $I$ is lead through the wire. Neglect the field induced by the wires.

![[nbpho-2012-p2-f1.svg]]

**i.** (2 pts) Sketch the shape of the wire.

**ii.** (2 pts) What is the maximal height by which the load can be lifted in such a way (increasing the current, if necessary)?

**iii.** (2 pts) Write an equation from which it is possible to determine the lifting height $\Delta h$.

**iv.** (1 pt) How large current $I_0$ is needed to lift the load by $\Delta h_0=l(1-\frac3\pi)$?

> [!answer]- Ответ
> **7.ii** — $\Delta h=l(1-\frac2\pi)$.
>
> **7.iii**
>
> $$
> \alpha\frac{mg}{lIB}=\cos\alpha,
> $$
>
> **7.iii**
>
> $$
> \Delta h=l-2R\sin\alpha=l-\frac{2T}{lIB}\sin\alpha=l\left(1-\frac{\sin\alpha}{\alpha}\right).
> $$
>
> **7.iv**
>
> $$
> I=\frac{mg\alpha}{lB\cos\alpha}=\frac{mg\pi}{3\sqrt3lB}.
> $$

> [!solution]- Решение
> # Problem 7. Lifting by current (7 points)
>
> **i.** (2 pts) The Ampère force pulls the wires to the side so that the wires will take a curved shape. Since the Ampère force is perpendicular to the wire, the mechanical tension is constant along the wires. Let the tension be $T$ and the curvature of the wire at a certain point — $R$. Let us consider a short piece of the wire, of length $a\ll R$. Then the angle by which the tangent of the wire rotates while the tangent point moves over an arc of length $a$ is given by $\alpha=a/R$. Let us study the force balance in the perpendicular direction for that piece of wire: the Ampère’s force $IaB$ is balanced by the tension $T\alpha=Ta/R$. So, $R=T/IB$ which means that $R$ is constant, and the wire will take the form of a circle segment. To conclude, both halves of the wire will take the form of a circle segment, the convex sides of which are turned outside.
>
> **ii.** (2 pts) The maximal height is achieved when the circle segments form a perfect circle, in which case the lifting height is
> $\Delta h=l(1-\frac2\pi)$.
>
> **iii.** (2 pts) If the central angle of the circle segments is $2\alpha$, the tangents to the wires at the point where the load is fixed forms angle $\alpha$ with the vertical direction. So, the lifting force is $mg=2T\cos\alpha$. From the other hand, $R=l/2\alpha=T/IB$, ie.
>
> $$\alpha\frac{mg}{lIB}=\cos\alpha,$$
>
> which is the equation from where one can determine the angle $\alpha$. Then, the lifting height
>
> $$\Delta h=l-2R\sin\alpha=l-\frac{2T}{lIB}\sin\alpha=l\left(1-\frac{\sin\alpha}{\alpha}\right).$$
>
> **iv.** (1 pt) From the previous result it can be seen that we need to have $\frac{\sin\alpha}{\alpha}=\frac\pi3$, hence $\alpha=\frac\pi6$ and
>
> $$I=\frac{mg\alpha}{lB\cos\alpha}=\frac{mg\pi}{3\sqrt3lB}.$$
