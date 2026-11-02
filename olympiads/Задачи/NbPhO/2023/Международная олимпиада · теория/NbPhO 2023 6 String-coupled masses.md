---
id: nbpho-2023-intl-theory-6
olympiad: NbPhO
year: 2023
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "6"
title: "String-coupled masses"
points: 5
authors: ["Aleksi Kononen"]
aliases: ["String-coupled masses"]
topics: ["[[1.20 Колебания]]", "[[1.13 Кинематические связи (и динамика)]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: true
source_damaged: false
summary: "Найти частоты синфазных и противофазных колебаний двух грузов на нитях."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 6. String-coupled masses (5 points) — Aleksi Kononen.

**NbPhO 2023** · Международная олимпиада · теория · 10–12 класс · задача 6  
Источник: [[_pdf/NbPhO/nbpho-2023.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2023.pdf#page=8|решение, стр. 8–9]]

Темы: [[1.20 Колебания]], [[1.13 Кинематические связи (и динамика)]]

> [!abstract] Кратко (составлено моделью)
> Найти частоты синфазных и противофазных колебаний двух грузов на нитях.

Two small masses $m$ are connected and hung between walls by weightless strings as pictured below. The acceleration due to gravity is $g$. All oscillatory motion is assumed to have a small amplitude and the system is always in one of its normal modes (i.e. the oscillations are sinusoidal).

![[nbpho-2023-p2-f3.svg]]

**i)** (2 points) Find $\omega_1$, the angular frequency of in-phase oscillations (by which the oscillation phases of the both masses are always equal), perpendicular to the plane of the figure.

**ii)** (3 points) Find $\omega_2$, the angular frequency of anti-phase oscillations (by which the oscillation phases of the both masses are always opposite), in terms of $\omega_1$.

> [!answer]- Ответ
> **i**
>
> $$
> \omega_1=\sqrt{\frac{g}{r\sin\theta}}
> $$
>
> **ii**
>
> $$
> \omega_2=\sqrt{|\ddot y/y|}=\omega_1\sqrt{1+\cos\theta}.
> $$
>
> **ii**
>
> $$
> \omega_2=\sqrt{\frac{T'+T}{mr}}=\omega_1\sqrt{1+\cos\theta}.
> $$

> [!solution]- Решение
> # 6. String-coupled masses (5 points) — Solution by Aleksi Kononen and Jaan Kalda, grading schemes by Aleksi Kononen.
>
> **i)** (2 points) For in-phase oscillations, the string connecting the masses always remains parallel to the $x$-axis. In that case, the motion is confined to the $yz$-plane and is identical to a pendulum with length $r\sin\theta$ hung from the axis of rotation:
>
> $$\omega_1=\sqrt{\frac{g}{r\sin\theta}}$$
>
> **ii)** (3 points) Now suppose one of the balls moves along the $y$ axis to a distance $y\,\mathrm m$ and the other ball — by $-y$. The length of the horizontal string remains constant, hence $y^2+(r-x)^2=r^2$, where $x$ denotes the displacement of the ball in $x$-direction. For small displacements, we can neglect the smallest term $x^2$, hence $x=y^2/2r$. The length of the slanted string remains also constant, hence $(r\sin\theta-z)^2+(r\cos\theta+x)^2+y^2=r^2$, where $z$ denotes the vertical displacement. Neglecting here the smallest terms $z^2$ and $x^2$, we obtain $2rz\sin\theta=2rx\cos\theta+y^2=y^2(1+\cos\theta)$, hence
>
> $$z=\frac{y^2}{2r}\frac{1+\cos\theta}{\sin\theta}.$$
>
> Now we can write down energy conservation law: $\frac12\dot y^2+gz=const$, where dot denotes the time derivative. Differentiating this over time we obtain
>
> $$\ddot y=-\frac{gy}{r}\frac{1+\cos\theta}{\sin\theta}$$
>
> so that
>
> $$\omega_2=\sqrt{|\ddot y/y|}=\omega_1\sqrt{1+\cos\theta}.$$
>
> **Alternative solution:** Let one of the masses (mass A) be displaced by $y$ and the other by $-y$. Let $T'$ be the tension in the two outermost strings (equal magnitudes by symmetry) and $T$ in the connecting string. Newton’s law along the $y$-axis for mass A then yields
>
> $$-T'\frac yr-T\frac yr=m\ddot y,$$
>
> i.e.
>
> $$\ddot y=-\frac{T'+T}{mr}y.$$
>
> Without oscillations, $T'_0=mg/\sin\theta$ and $T_0=T'_0\cos\theta$. Let us write $T'=T'_0+\Delta T'$ and $T=T_0+\Delta T$, i.e.
>
> $$T'+T=mg\frac{1+\cos\theta}{\sin\theta}+\Delta T'+\Delta T.$$
>
> Let us make some estimates. Clearly, $|\Delta T|\sim|\Delta T'|$. The maximum of $\Delta T'$ occurs when the mass swings by its lowest point with velocity $\dot y$, where its trajectory has a radius of curvature $R\sim r\sin\theta$. Moreover, small normal mode oscillations imply $y=A\cos\omega_2t$ for some amplitude $A\ll r\sin\theta$, i.e. $|\dot y|\leq A\omega_2$. Finally, assume $\omega_2=k\omega_1$ holds for some $k\sim1$. We have
>
> $$|\Delta T'|\sim\frac{m\dot y^2}{R}\sim\frac{mk^2A^2g}{r^2\sin^2\theta}=k^2mg\left(\frac A{r\sin\theta}\right)^2,$$
>
> i.e. quadratically smaller in $(A/r\sin\theta)$ than $T'_0$. Thus, $T'+T\approx mg\frac{1+\cos\theta}{\sin\theta}$ and
>
> $$\omega_2=\sqrt{\frac{T'+T}{mr}}=\omega_1\sqrt{1+\cos\theta}.$$
>
> (The result shows $k\leq\sqrt2$, i.e. the assumption holds.)

> [!grading]- Критерии оценивания
> **Grading:**
> - Stating $\sum F_x=0$, or stating that the connecting string remains parallel to the $x$-axis **(0.6 pts)**
> - Realising the effective pendulum length is $r\sin\theta$, i.e. the axis of rotation is the line connecting the wall points **(0.8 pts)**
> - Correct expression for $\omega_1$ **(0.6 pts)**
>
> **ii)**
>
> **Grading:**
> - Equation for a cylinder surface **(0.4 pts)**
> - Equation for a sphere surface **(0.4 pts)**
> - Both surface equations correct and coordinates consistent **(0.2 pts)**
> - Realising $x^2$- and $z^2$-terms are negligible, and not discarding $y^2$ **(0.2 pts)**
> - Solving $z$ in terms of $y$ **(0.5 pts)**
> - Energy conservation between $z$ and $\dot y$ **(0.3 pts)**
> - Solving relation between $\ddot y$ and $y$ **(0.6 pts)**
> - Correct expression for $\omega_2$ **(0.3 pts)**
> - $\omega_2$ correctly in terms of $\omega_1$ **(0.1 pts)**
>
> **Grading:**
> - Force equation, either along $y$ or full vector form **(0.4 pts)**
> - Solving relation between $\ddot y$ and $y$ in terms of tension forces **(0.4 pts)**
> - Unperturbed values for $T'$ and $T$ **(0.4 pts)**
> - Reasonable estimate of $|\Delta T'|$ **(0.6 pts)**
> - Showing $|\Delta T'|$ is quadratically smaller than $T'$ **(0.8 pts)**
> - Correct expression for $\omega_2$ **(0.3 pts)**
> - $\omega_2$ correctly in terms of $\omega_1$ **(0.1 pts)**
> - **Remark:** Accept solution with assumption $\Delta T'/T'\ll1$ without estimates
