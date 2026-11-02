---
id: nbpho-2011-intl-theory-6
olympiad: NbPhO
year: 2011
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "6"
title: "Violin string"
points: 9
aliases: ["Violin string"]
topics: ["[[1.20 Колебания]]", "[[1.15 Упругость. Весомая пружина]]", "[[1.21 Фазовые диаграммы колебательных систем]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Исследовать колебания пружинного осциллятора при чередовании покоя и скольжения под движущейся пластиной."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 6. Violin string (9 points)

**NbPhO 2011** · Международная олимпиада · теория · 10–12 класс · задача 6  
Источник: [[_pdf/NbPhO/nbpho-2011.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2011.pdf#page=4|решение, стр. 4]]

Темы: [[1.20 Колебания]], [[1.15 Упругость. Весомая пружина]], [[1.21 Фазовые диаграммы колебательных систем]]

> [!abstract] Кратко (составлено моделью)
> Исследовать колебания пружинного осциллятора при чередовании покоя и скольжения под движущейся пластиной.

The motion of a bow puts a violin string into a periodic motion. Let us make a simplified model of this process. The string has elasticity and inertia, so we substitute it by a block of mass $m$, fixed via a spring of stiffness $k$ to a motionless wall and laying on a frictionless horizontal surface. The bow is substituted by a horizontal plate, which is pressed with constant force $N$ downwards, and which moves with a constant velocity $u$, parallel to the axis of the spring, see Figure. The static coefficient of friction between the plate and the block is $\mu_1$, and the kinetic coefficient of friction is $\mu_2<\mu_1$. So, as long as the plate does not slide with respect to the block, the coefficient of friction equals to $\mu_1$; as soon as there is some slip, it decreases down to $\mu_2$.

![[nbpho-2011-p2-f2.svg]]

**i)** (2 pts) For questions (i) and (ii), let us assume that the speed of the plate $u$ is very small as compared to the maximal velocity of the block. What is the maximal velocity of the block $v_{\max}$ (maximized over time)?

**ii)** (2 pts) Sketch qualitatively the graph of the displacement of the block as a function of time and indicate on the graph the durations of the prominent stages of the block motion (graph segments).

**iii)** (1,5 pts) Now, let us abandon the assumption about the smallness of $u$. Sketch qualitatively the graph of the velocity of the block as a function of time.

**iv)** (2,5 pts) Determine the amplitude $A$ of the block’s oscillations.

**v)** (1 pt) Which condition (strong inequality, $\gg$ or $\ll$) must be satisfied for $u$ in order to ensure that the oscillations will be almost harmonic?

> [!answer]- Ответ
> **i** — $v_{\mathrm{max}}=\xi_0\sqrt{k/m}$.
>
> **ii**
>
> $$
> T_1=2\xi_0/u=2(\mu_1-\mu_2)N/ku;
> $$
>
> **ii** — $T_2=\pi\sqrt{m/k}$.
>
> **iv**
>
> $$
> A=\frac1k\sqrt{(\mu_1-\mu_2)^2N^2+u^2mk}.
> $$
>
> **v** — $u\gg(\mu_1-\mu_2)N/\sqrt{mk}$.

> [!solution]- Решение
> # 6. Violin string (9 points)
>
> **i)** When the plate slides, there is a constant friction force $\mu_2N$ acting upon the block, which means that the equilibrium deformation of the spring is $x_0=\mu_2N/k$; the net force acting upon the block (due to spring and friction) is given by $F=-k\xi$, where we have defined $\xi=x-x_0$. Therefore, while sliding, the block oscillates harmonically around the point $\xi=0$. Slipping starts when the static friction will be unable to keep equilibrium, i.e. at $kx=\mu_1N$, which corresponds to $\xi_0=(\mu_1-\mu_2)N/k$. If the plate moves slowly, the block is released with essentially missing kinetic energy, and the energy conservation law yields $\frac12k\xi_0^2=\frac12mv_{\mathrm{max}}^2\Rightarrow$
> $v_{\mathrm{max}}=\xi_0\sqrt{k/m}$.
>
> **ii)** As mentioned, when the plate slides, the motion of the block is harmonic, i.e. the graph of $x(t)$ is a segment of a sinusoid; when there is no sliding, the block moves together with the plate, i.e. the graph of $x(t)$ is a straight line. At the moment when slipping starts or stops, the oscillatory speed is equal to the speed of plate, i.e. the straight line is tangent to the sinusoid. The length of a straight segment can be calculated as
>
> $$T_1=2\xi_0/u=2(\mu_1-\mu_2)N/ku;$$
>
> the sinusoidal segment corresponds to a half-period and therefore has a length of
> $T_2=\pi\sqrt{m/k}$.
>
> ![[nbpho-2011-p4-f1.svg]]
>
> **iii)** The speed $v(t)=\frac{dx}{dt}$ is the derivative of $x(t)$; therefore, the sinusoidal segment of $x(t)$ will correspond to a sinusoidal segment of $v(t)$, and a straight segment of $x(t)$ — to a horizontal segment of $v(t)$. The resulting graph is depicted below.
>
> ![[nbpho-2011-p4-f2.svg]]
>
> **iv)** Let the amplitude of the oscillations be $A$, i.e. the sinusoidal segments follow the law $\xi(t)=A\cos(\omega t)$, where $\omega=\sqrt{k/m}$. Correspondingly, $v(t)=A\omega\sin(\omega t)\Rightarrow A\sin(\omega t)=v(t)/\omega$; hence, for any point at a sinusoidal segment, $\xi^2+v^2/\omega^2=A^2$. At a point, where a sinusoid and a straight line meet, the straight line and sinusoid have equal values for $\xi=\xi_0=(\mu_1-\mu_2)N/k$ and $v=u$. Consequently, $(\mu_1-\mu_2)^2N^2/k^2+u^2/\omega^2=A^2\Rightarrow$
>
> $$A=\frac1k\sqrt{(\mu_1-\mu_2)^2N^2+u^2mk}.$$
>
> **v)** The oscillations will be almost harmonic when the straight segments are very short, i.e. when $u/\omega\gg(\mu_1-\mu_2)N/k\Rightarrow$
> $u\gg(\mu_1-\mu_2)N/\sqrt{mk}$.
