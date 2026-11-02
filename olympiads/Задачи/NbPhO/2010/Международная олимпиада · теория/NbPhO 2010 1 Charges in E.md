---
id: nbpho-2010-intl-theory-1
olympiad: NbPhO
year: 2010
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "1"
title: "Charges in E"
points: 8
aliases: ["Charges in E"]
topics: ["[[1.20 Колебания]]", "[[1.12 Теорема о движении центра масс]]", "[[3.4 Работа электрического поля]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Исследовать отражение двух связанных пружиной частиц от области электрического поля."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 1. Charges in E (8 points)

**NbPhO 2010** · Международная олимпиада · теория · 10–12 класс · задача 1  
Источник: [[_pdf/NbPhO/nbpho-2010.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2010.pdf#page=3|решение, стр. 3]]

Темы: [[1.20 Колебания]], [[1.12 Теорема о движении центра масс]], [[3.4 Работа электрического поля]]

> [!abstract] Кратко (составлено моделью)
> Исследовать отражение двух связанных пружиной частиц от области электрического поля.

Two particles (the blue and the red) of mass $m$ are connected with a spring, the stress-free length of which is $L$ and stiffness $k$; the blue carries charge $q$ ($q>0$) and the red is chargeless. In the region $x>0$, there is an homogeneous electric field $E$, antiparallel to the $x$-axis; In the region $x<0$, there is no electric field. Initially, the “dumbbell” of charges moves in region $x<0$ with velocity $v$, parallel to the $x$-axis; the dumbbell’s axis is also parallel to the $x$-axis and the spring is stress-free. It is known that after a while, the dumbbell moves in the region $x<0$ with velocity $-v$, and that the red particle never enters the region $x>0$. Also, the spring’s length achieves minimum only once.

**i)** (2.5 pt) How long time $\tau$ does the blue particle spend in the region $x>0$?

The process takes place exactly as described, if one equality and one inequality are satisfied for the quantities $m$, $v$, $k$, $q$, $E$ and $L$.

**ii)** (3 pt) Which equality must be satisfied?

**iii)** (2.5 pt) Which inequality must be satisfied?

> [!answer]- Ответ
> **i** — $\tau=4mv/Eq$.
>
> **ii**
>
> $$
> \sqrt{\frac{2k}{m}}\frac{4mv}{Eq}=\pi.
> $$
>
> **iii**
>
> $$
> \frac L2>s+2x=mv^2/Eq+Eq/2k.
> $$

> [!solution]- Решение
> # Problem 1. Charges in E (8 points)
>
> **i.** (2.5 pts) The initial and final momentum of the dumbbell differ by $4mv$. The only external force acting on the dumbbell is the electrostatic force $Eq$, applied to the blue particle. So, the duration of that force must satisfy condition $Eq\tau=4mv$, hence
> $\tau=4mv/Eq$.
>
> **ii.** (3 pts) Once the blue particle enters the electric field, the dumbbell’s center of mass $C$ obtains acceleration $a=Eq/2m$. Let us consider the motion in the system, where $C$ is at rest. Red and blue particles move symmetrically in that system; let us consider the red particle. Due to the inertial force $F_i=ma=Eq/2$, the equilibrium position of the red particle is shifted (the half-spring is to be deformed by $x=F_i/2k=Eq/4k$ to achieve the equilibrium); the particle starts from rest, apart from the equilibrium. So, it starts oscillations, the circular frequency being given by $\omega=\sqrt{2k/m}$ (the factor 2 accounts for the fact that oscillations take place around the center of the spring and half-spring has twice larger stiffness). For the dumbbell to return with the same velocity as it approached, the residual oscillations must be absent (otherwise, some part of the initial kinetic energy would be turned into the oscillations energy, so that the center of mass velocity would be decreased). So, the oscillations phase needs to be $\omega\tau=2n\pi$, where $n$ is an integer. Since the spring’s length achieves minimum only once, $n=1$. So, $\omega\tau=2\pi$, and the equality can be written as
>
> $$\sqrt{\frac{2k}{m}}\frac{4mv}{Eq}=\pi.$$
>
> **iii.** (2.5 pts) There is a requirement that the red particle never enters the region $x>0$. The most critical moment is $t=\tau/2$ ($t=0$ corresponds to the blue particle entering the electric field), when the spring is maximally compressed. The center of mass has displaced by $s=at^2/2=(Eq/2m)\cdot\tau^2/8=mv^2/Eq$, and the spring half-length has decreased by $2x$ ($x$ is the difference between lengths of the initial and equilibrium states; we need the difference between the lengths of the initial, i.e maximally stretched state, and maximally compressed state). So,
>
> $$\frac L2>s+2x=mv^2/Eq+Eq/2k.$$
