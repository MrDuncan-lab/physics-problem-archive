---
id: nbpho-2013-intl-theory-1
olympiad: NbPhO
year: 2013
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "1"
title: "Prism"
points: 8
aliases: ["Prism"]
topics: ["[[1.10 Статика]]", "[[1.11 Центр масс]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Найти предельную ширину щели для устойчивого положения треугольной призмы."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 1. PRISM (8 points)

**NbPhO 2013** · Международная олимпиада · теория · 10–12 класс · задача 1  
Источник: [[_pdf/NbPhO/nbpho-2013.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2013.pdf#page=3|решение, стр. 3]]

Темы: [[1.10 Статика]], [[1.11 Центр масс]]

> [!abstract] Кратко (составлено моделью)
> Найти предельную ширину щели для устойчивого положения треугольной призмы.

**i)** (4 points) A right prism that has an equilateral triangular base with length $a$ is placed in a horizontal slit between two tables, so that one of the side faces is vertical. How small can the width $d$ of the slit be made before the prism falls out of the slit? There is no friction between the prism and the tables and the prism is made of a homogeneous material. The edges of the slit are parallel.

**ii)** (4 points) Now the prism is placed in the slit so that one of its side faces is horizontal. How small can the width $l$ of the slit be made before that position becomes unstable?

![[nbpho-2013-p1-f1.svg]]

> [!answer]- Ответ
> **i** — $d=\frac14a\cos30^\circ=\frac{\sqrt3}{8}a$.
>
> **ii** — $l>\frac14a$.

> [!solution]- Решение
> # 1. PRISM (8 points)
>
> **i)** (4 points) The prism is acted on by three forces: reaction force $\vec R_l$ from the left-hand table, directed perpendicularly to the prism’s face; reaction force $\vec R_r$ from the right-hand table, directed horizontally (with its point of action to be determined yet); and gravitational force $mg$, directed vertically and applied at the triangle’s centre. (Considering a planar triangular cross-section of the prism is enough.)
>
> On the verge of falling out, the force $\vec R_r$ is applied at the lower corner of the triangle. If a body in equilibrium is acted on by three forces, then their lines of action must intersect at one point. This is because otherwise the torque of one of those forces would not be zero with respect to the intersection of the lines of action of the two other forces.
>
> As the distance between the triangle’s centre and its side is $\frac{\sqrt3}{6}a$, the distance between the points of action of $\vec R_l$ and $\vec R_r$ is $\frac{\sqrt3}{6}a\cos30^\circ=\frac14a$. Thus,
> $d=\frac14a\cos30^\circ=\frac{\sqrt3}{8}a$.
>
> ![[nbpho-2013-p3-c0164.png]]
>
> **ii)** (4 points) Let the corners be denoted by $A$ and $B$, and the tip of the prism (at its equilibrium position) by $C$. Let us consider a small rotation of the prism (assuming it remains in contact with the corners). The trajectory of the tip is a circle ascribed around the triangle $ABC$ (it follows from the property of the inscribed angles because the $\angle ACB$ remains equal to $60^\circ$). The radius of that circle $r=l/\sqrt3$; its centre will be denoted by $O$. Once the prism rotates by angle $\alpha$, so that the new position of the tip will be $D$, the central angle $\angle COD=2\alpha$. Hence, the tip is raised by $r-r\cos(2\alpha)\approx2r\alpha^2$. The height of the centre of mass $P$ of the prism is raised because the tip is raised, and lowered because the vertical projection of the segment $CP$ is reduced by $|CP|(1-\cos\alpha)\approx|CP|\alpha^2/2$. Here, $|CP|=a/\sqrt3$. So, the original position is stable if $\frac a{\sqrt3}\alpha^2/2<2\frac l{\sqrt3}\alpha^2$, hence
> $l>\frac14a$.
>
> ![[nbpho-2013-p3-c2648.png]]
