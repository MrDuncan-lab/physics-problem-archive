---
id: nbpho-2009-intl-theory-3
olympiad: NbPhO
year: 2009
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "3"
title: "Ball"
points: 8
aliases: ["Ball"]
topics: ["[[1.7 Качение твёрдого тела]]", "[[1.17 Законы сохранения энергии и импульса]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Определить переход шара от скольжения к качению и потери энергии при разных силах трения."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 3. Ball (8 points)

**NbPhO 2009** · Международная олимпиада · теория · 10–12 класс · задача 3  
Источник: [[_pdf/NbPhO/nbpho-2009.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2009.pdf#page=3|решение, стр. 3]]

Темы: [[1.7 Качение твёрдого тела]], [[1.17 Законы сохранения энергии и импульса]]

> [!abstract] Кратко (составлено моделью)
> Определить переход шара от скольжения к качению и потери энергии при разных силах трения.

A homogeneous ball of radius $R$ and mass $m$ is thrown horizontally onto a table at the moment of time $t=0$. Its initial velocity before contact is purely horizontal and equal to $v$; it is non-rotating. Coefficient of kinetic friction between the table and the ball is $\mu$.

**i)** Find the moment of time $t$, when the ball stops sliding, i.e. starts rolling without sliding.

**ii)** Calculate the angular velocity of the ball $\omega_*$ and its total mechanical energy $E_*$ at the moment when it stops sliding. In the case of a hollow sphere, would the energy $E_*$ be larger or smaller than in the case of a homogeneous ball?

**iii)** Now, assume that the horizontal surface is treated so that the coefficient of kinetic friction depends on the horizontal coordinate $x$ as $\mu=a+b\cos x$ (with $a>b$). Find the expression for the terminal mechanical energy $E'_* $ in this new case.

**iv)** Now, let us return to the case of constant kinetic friction coefficient $\mu$. However, let us assume that the surface is not perfectly rigid (e.g. covered by a felt cloth). This gives rise to a second friction force — the rolling friction force $F_r=\mu_rmg$. Unlike the kinetic friction force, it is not tangential to the touching point of the ball and the surface. Instead, it can be interpreted as the horizontal component of the surface reaction force (the entire reaction force is, of course, normal to the surface), see Fig. Find the expression for the terminal mechanical energy $E''_*$ in this case. What is the most important (qualitative) difference between the expressions for $E'_*$ and $E''_*$?

![[nbpho-2009-p1-c6447.png]]

*Hint:* The moment of inertia of a ball is $I=\frac25MR^2$.

> [!answer]- Ответ
> **i** — $t=\frac{I\omega}{mg\mu r}=\frac{Iv}{g\mu(I+mr^2)}$.
>
> **ii** — $\omega_*=\frac{mvr}{I+mr^2}$ and
>
> **ii** — $E_*=\frac12(mv_*^2+I\omega_*^2)=\frac12(mr^2\omega_*^2+I\omega_*^2)=\frac{m^2v^2r^2}{2(I+mr^2)}$. If $I$ increases then $E_*$ decreases.
>
> **iv** — $E_*''=\frac12(I+mr^2)\omega_*^2$. Clearly, $E_*''<E_*$.

> [!solution]- Решение
> # 3. Ball (8 points)
>
> A straightforward way to solve parts i), ii), and iii) is to use conservation of angular momentum with respect to any axis laying on the surface (there is no torque with respect to these axes). Angular momentum at the beginning: $L_0=mvr$. Rolling ball is always rotating around the touching point with the ground (although the location of that point is constantly changing). From Steiner’s theorem we know that for a rotation axis that is located at the distance $r$ form the center of mass, the moment of inertia is $I'=I+mr^2$. Therefore the angular momentum for rotating ball is $L'=I'\omega$ and clearly $L_0=L'$, therefore $mvr=(I+mr^2)\omega$, $\omega=\frac{mvr}{I+mr^2}$.
>
> **i)** The torque with respect to center of mass: $M=mg\mu r$. Since $M\Delta t=I\Delta\omega$, and the sliding stops when angular speed has reached value $\omega$, we obtain the corresponding time:
> $t=\frac{I\omega}{mg\mu r}=\frac{Iv}{g\mu(I+mr^2)}$.
>
> **ii)** Clearly,
> $\omega_*=\frac{mvr}{I+mr^2}$ and
> $E_*=\frac12(mv_*^2+I\omega_*^2)=\frac12(mr^2\omega_*^2+I\omega_*^2)=\frac{m^2v^2r^2}{2(I+mr^2)}$. If $I$ increases then $E_*$ decreases.
>
> **iii)** Since we didn’t make any assumptions about the functional form of $\mu$ while deriving $w_*$, the results $w_*$ and $E_*$ of ii) are still valid.
>
> **iv)** The net force $F=F_\mu+F_r$ causes the decrease of translational velocity: $m\Delta v=F\Delta t$, $v'(t)=v-(\mu+\mu_r)gt$. The sliding stops when $\omega(t)=v'(t)/r$. Note that the torque with respect to center of mass is only caused by kinetic frictional force, therefore $\omega(t)=\frac{mg\mu r}{I}t$. We get an equation for the time of the termination of sliding: $\frac{mg\mu r^2}{I}t=v-(\mu+\mu_r)gt$, $t=\frac{Iv}{g\mu(I+mr^2)+g\mu_r I}$. The corresponding angular speed $\omega_*''=\frac{mvr}{I+mr^2+\frac{\mu_r}{\mu}I}$, and energy
> $E_*''=\frac12(I+mr^2)\omega_*^2$. Clearly, $E_*''<E_*$.
