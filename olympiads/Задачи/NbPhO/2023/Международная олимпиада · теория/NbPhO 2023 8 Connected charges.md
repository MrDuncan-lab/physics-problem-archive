---
id: nbpho-2023-intl-theory-8
olympiad: NbPhO
year: 2023
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "8"
title: "Connected charges"
points: 8
authors: ["Jaan Kalda"]
aliases: ["Connected charges"]
topics: ["[[3.4 Работа электрического поля]]", "[[1.13 Кинематические связи (и динамика)]]", "[[1.17 Законы сохранения энергии и импульса]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: true
source_damaged: false
summary: "Исследовать движение двух связанных заряженных шариков при прохождении области однородного электрического поля."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 8. Connected charges (8 points) — Jaan Kalda.

**NbPhO 2023** · Международная олимпиада · теория · 10–12 класс · задача 8  
Источник: [[_pdf/NbPhO/nbpho-2023.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2023.pdf#page=9|решение, стр. 9–10]]

Темы: [[3.4 Работа электрического поля]], [[1.13 Кинематические связи (и динамика)]], [[1.17 Законы сохранения энергии и импульса]]

> [!abstract] Кратко (составлено моделью)
> Исследовать движение двух связанных заряженных шариков при прохождении области однородного электрического поля.

In the region $0<x<L$, there is an electric field $\vec E=E_0\hat x$, where $\hat x$ denotes the unit vector parallel to the $x$-axis. Two small balls, each of mass $m$ and carrying charge $q$ ($qE_0>0$) are connected with a weightless non-stretchable string of length $l$. Initially, at the moment of time $t=0$, the string is taut, the velocity of the both balls is $\vec v=v_0\hat x$, one of the balls, the ball $A$, is at $x=0$ while the other ball, the ball $B$ is at $x<0$. The electric field created by the balls can be neglected, and it can be assumed that $v_0$ is very small (much smaller than $\sqrt{ELq/m}$).

**i)** (2 points) Consider the case when the string is parallel to the $x$-axis, and $l=L$. Sketch the dependence of the velocity of the both balls as a function of time. Will the balls collide? If yes then when?

**ii)** (2 points) Now, at $t=0$, the string forms an angle of $45^\circ$ with the $x$-axis, $l=1.2291L$. By this string length, at the moment $t=T$ when the ball $A$ reaches $x=L$, the string is parallel to the $x$-axis. Find $T$.

**iii)** (2 points) Under the assumptions of the previous task, what is the speed of the ball $A$ at the moment $t=T$?

**iv)** (2 points) Now, at $t=0$, the string forms a very small angle $\phi$ with the $x$-axis. Similarly to the previous two tasks, at the moment $t=T'$ when the ball $A$ reaches $x=L$, the string is parallel to the $x$-axis. Find the string length $l$ assuming that $l>L$. The answer to this point should contain only $L$ and numerical constants.

> [!answer]- Ответ
> **i** — $t=t_1+t_2+t_3=\sqrt{Lm/qE}(\sqrt3+2)$.
>
> **ii** — $T=1.811\sqrt{\frac{mL}{qE}}$.
>
> **iii** — $v=\sqrt{\frac{qEL}{m}}$.
>
> **iii** — $v=\sqrt{v_x^2+v_y^2}=\sqrt{\frac{qEL}{m}}$.
>
> **iv** — $l=L/\lambda=1.6211L$.

> [!solution]- Решение
> # 8. Connected charges (8 points) — Solution by Jaan Kalda, grading schemes by Jānis Cīmurs.
>
> **i)** (2 points) As the ball $A$ enters the electric field, the force $qE$ is exerted on it, hence the acceleration of the system of two balls is $a_1=qE/2m$; the acceleration remains constant until the ball $A$ exits the field. This will happen when $L=a_1t_1^2/2$, hence $t_1=\sqrt{2L/a}=2\sqrt{Lm/qE}$. At that moment, the acceleration of the ball $A$ becomes zero, but at the very same moment, ball $B$ enters the field. The force $qE$ exerted on it will give it twice as big an acceleration as before, $a_2=qE/m$, and the string becomes loose. So, the speed of the ball $B$ is now bigger than that of the ball $A$, and so they will eventually collide. The time $t_2$ spent by the ball $B$ in the field can be expressed as $t_2=(v_f-v_i)/a_2$, where $v_i=\sqrt{qEL/m}$ is its initial speed, and $v_f=\sqrt{3qEL/m}$ — the final speed. So, $t_2=\sqrt{Lm/qE}(\sqrt3-1)$. At the moment when the ball $B$ exits the field, the distance between the balls is $s=L-(v_f-v_i)t_2/2=v_it_2=L(\sqrt3-1)$, and the difference between the velocities of the balls is $\Delta v=v_f-v_i=\sqrt{qEL/m}(\sqrt3-1)$, hence the time remaining until the collision $t_3=s/\Delta v=\sqrt{Lm/qE}$. Thus, the moment of collision
>
> $t=t_1+t_2+t_3=\sqrt{Lm/qE}(\sqrt3+2)$.
>
> **ii)** (2 points) **First solution:** The centre of mass moves with constant acceleration $a_1=qE/2m$, and has travelled distance $s_{CM}=L-l/2+l/(2\sqrt2)=0.8200L=a_1T^2/2$, hence
>
> $T=1.811\sqrt{\frac{mL}{qE}}$.
>
> **iii)** (2 points) **First solution:** Due to the conservation of $y$-directional momentum, the $y$-components of the balls are always equal. At $t=T$, the string is parallel to the $x$-axis; since it is not stretchable, $x$-components of the balls are equal, too, at that moment. Hence, the speeds are equal, and energy conservation law states $EqL=mv^2$ so that
>
> $v=\sqrt{\frac{qEL}{m}}$.
>
> **Alternative solution:** The time period $0<t<T$ is most conveniently analysed in the centre-of-mass frame. In that frame, there is a force of inertia equal to $F_i=-ma_1=-qE/2$. Hence, both balls perform non-linear oscillations around the centre of mass (it is nonlinear because the amplitude is not small). The speed of the ball at $t=T$ can be found from the energy conservation law. At $t=0$, the speed is zero so that the full energy is due to the potential energy in the homogeneous force field $qE/2$: $\Delta U=\frac{qE}{2}(\frac l2-\frac{l}{2\sqrt2})=\frac{qEL}{8}(2-\sqrt2)=\frac{mv_y^2}{2}$, hence $v_y^2=\frac{qEl}{4m}(2-\sqrt2)=0.1800\frac{qEL}{m}$. This gives us the velocity component in the $y$-direction; once we return to the laboratory frame, we need to add the $x$-component of the frame’s velocity $v_x=a_1T=\frac{qE}{2m}1.811\sqrt{\frac{mL}{qE}}=0.9055\sqrt{\frac{qEL}{m}}$ so that
>
> $v=\sqrt{v_x^2+v_y^2}=\sqrt{\frac{qEL}{m}}$.
>
> **iv)** (2 points) For the string to be parallel to the $x$-axis, the system must perform $n+\frac12$ half-periods, where $n$ is an integer. Since now the amplitude is small, the oscillations are harmonic, and the circular frequency $\omega=\sqrt{qE/ml}$ (we can use the formula for a pendulum of length $l/2$ and equivalent gravity field $g=qE/2m$). So, the travel time must be $\tau=\pi\sqrt{ml/qE}(n+\frac12)$. On the other hand, we can use the result from task ii: $\tau=\sqrt{ml/qE}\sqrt{4\lambda-2+2\cos\phi}$, where $\lambda=L/l<1$ and $\cos\phi\approx1$. So, $\pi(n+\frac12)=\sqrt{4\lambda}$. Since $\lambda<1$, this equality can only be satisfied with $n=0$, hence $\lambda=\frac{\pi^2}{16}=0.6169$ so that
>
> $l=L/\lambda=1.6211L$.

> [!grading]- Критерии оценивания
> **Grading:**
> - Initially both charges move with the same acceleration **(0.2 pts)**
> - When A escapes the field region A moves with constant speed, B moves with higher acceleration **(0.2 pts)**
> - When B escapes, both move with constant speed **(0.1 pts)**
> - Correct $a_1$ **(0.2 pts)**
> - Correct $t_1$ **(0.2 pts)**
> - Correct $a_2$ **(0.1 pts)**
> - Correct $v_i$ **(0.2 pts)**
> - Correct $v_f$ **(0.2 pts)**
> - Correct $t_2$ **(0.2 pts)**
> - Correct $s$ **(0.2 pts)**
> - Correct $t_3$ and $t$ **(0.2 pts)**
>
> **ii)**
>
> **Grading:**
> - Use $s_{CM}=a_1T^2/2$ for centre of mass **(0.5 pts)**
> - Correct $a_1$ **(0.5 pts)**
> - Correct $s_{CM}$ **(0.6 pts)**
> - Correct $T$ **(0.4 pts)**
> - If you assume small angle oscillation to calculate time necessary for the string to align with the $x$-axis. **(up to 1.4 pts)**
>
> **iii)**
>
> **Grading:**
> - Using energy conservation law **(1.0 pts)**
> - Kinetic energy of both masses **(0.6 pts)**
> - Work done by electric field **(0.2 pts)**
> - Correct $v$ **(0.2 pts)**
>
> **Grading:**
> - Horizontal speed $v_x$ **(0.4 pts)**
> - Use energy balance or something similar to find rotational speed $v_y$ **(0.4 pts)**
> - Correct distance travelled **(0.6 pts)**
> - Rotational speed $v_y$ **(0.4 pts)**
> - Pythagorean theorem **(0.2 pts)**
>
> **iv)**
>
> **Grading:**
> - Correct circular frequency **(0.6 pts)**
> - If circular frequency deviates from the right by factor $\sqrt2$ **(0.2 pts)**
> - Correct rotation time with $n$ **(0.6 pts)**
> - Correct rotation time without $n$ **(0.2 pts)**
> - Correct travel time from ii **(0.4 pts)**
> - Derivation of $l$ **(0.4 pts)**
