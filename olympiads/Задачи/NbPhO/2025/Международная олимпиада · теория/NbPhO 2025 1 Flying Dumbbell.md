---
id: nbpho-2025-intl-theory-1
olympiad: NbPhO
year: 2025
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "1"
title: "Flying Dumbbell"
points: 10
authors: ["Jaan Kalda"]
aliases: ["Flying Dumbbell"]
topics: ["[[1.15 Упругость. Весомая пружина]]", "[[1.20 Колебания]]", "[[1.17 Законы сохранения энергии и импульса]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: true
source_damaged: false
summary: "Колебания и столкновения упругой гантели со стеной при разных углах её движения."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 1. Flying Dumbbell (10 points) — Jaan Kalda.

**NbPhO 2025** · Международная олимпиада · теория · 10–12 класс · задача 1  
Источник: [[_pdf/NbPhO/nbpho-2025.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2025.pdf#page=3|решение, стр. 3]]

Темы: [[1.15 Упругость. Весомая пружина]], [[1.20 Колебания]], [[1.17 Законы сохранения энергии и импульса]]

> [!abstract] Кратко (составлено моделью)
> Колебания и столкновения упругой гантели со стеной при разных углах её движения.

In this problem, we shall study the dynamics of a dumbbell consisting of two steel balls, each with radius $r = 1\,\mathrm{cm}$, connected by a steel rod with diameter $d = 1\,\mathrm{mm}$ and length $l = 10\,\mathrm{cm}$, in the absence of gravity. Unless instructed otherwise, assume steel is perfectly elastic. You may simplify your calculations by assuming $l \gg r$.

**i)** (2 points) Given that the Young’s modulus of steel is $Y = 2 \times 10^{11}\,\mathrm{Pa}$ and the density of steel is $\rho = 7800\,\mathrm{kg\,m^{-3}}$, determine the period $T$ of free longitudinal oscillations of the dumbbell. (Do not consider oscillations with standing waves in the rod where the balls remain almost at rest.) Young’s modulus is the ratio of a material’s stress (force per unit area) to its strain (relative deformation).

**ii)** (2 points) Estimate the impact time $\tau$ when a steel ball bounces off a steel wall.

**iii)** (2 points) The dumbbell moves toward a steel wall with velocity $\vec v = -v\hat x$, with its axis perpendicular to the wall, and bounces back. Here, $\hat x$ denotes a unit vector along the axis perpendicular to the wall. Sketch how the $x$-component $v_x$ of the front ball’s velocity (the ball that collides with the wall) depends on time.

**iv)** (2 points) Now, the dumbbell moves toward a steel wall with velocity $\vec v = -v\hat x$ as before, but its axis forms an angle $\alpha$ with the $x$-axis. The interaction of the front ball with the wall depends qualitatively on the angle $\alpha$, with a transition from one type of interaction to another occurring at $\alpha = \alpha_0$. Determine the value of $\alpha_0$. Hint: $\min\left(\frac{\sin x}{x}\right) \approx -0.217$.

**v)** (2 points) Under the assumptions of the previous task, let $\alpha > \alpha_0$. Additionally, assume that while steel is highly elastic, it is not infinitely so: any oscillations excited in the rod will decay by the time the rear ball collides with the wall. Determine the speed with which the centre of mass of the dumbbell departs from the wall.

> [!answer]- Ответ
> **i**
>
> $$
> T = 2\pi\sqrt{\frac{m}{k}} = 4\pi\frac{r}{d}\sqrt{\frac{2\rho rl}{3Y}} \approx 0.64\,\mathrm{ms}.
> $$
>
> **ii** — $\tau \sim 2r/c_s = 2r\sqrt{\rho/Y} = 4\,\mu\mathrm{s}$.
>
> **ii** — $\tau \sim 2\pi\sqrt{m/\kappa}$.
>
> **iv**
>
> $$
> \alpha_0 = \arctan\sqrt{0.217}\approx 25^\circ.
> $$

> [!solution]- Решение
> # 1. Flying Dumbbell (10 points) — Solution by Jaan Kalda, grading schemes by Author 2.
>
> **i)** (2 points) Free oscillations of the dumbbell take place around the centre of mass, i.e. the centre of the rod. Therefore, we need the stiffness of a half of the rod. This stiffness is expressed as $k = Y\frac{\pi}{2}d^2/l$. We also need the mass of the ball $m = \frac43\pi r^3\rho$. The oscillation angular frequency $\omega = \sqrt{k/m}$, hence the period
>
> $$T = 2\pi\sqrt{\frac{m}{k}} = 4\pi\frac{r}{d}\sqrt{\frac{2\rho rl}{3Y}} \approx 0.64\,\mathrm{ms}.$$
>
> **ii)** (2 points) The easiest way to estimate is to notice that a compressed ball is essentially a compression wave in steel, so the period is on the order of a wave with wave length $2r$. Knowing that the sound speed $c_s = \sqrt{Y/\rho}$, we obtain
>
> $\tau \sim 2r/c_s = 2r\sqrt{\rho/Y} = 4\,\mu\mathrm{s}$.
>
> Alternatively, one can approximate the ball as a spring of stiffness $\kappa \sim Yr$ and mass $\sim m$, and obtain a similar result with
>
> $\tau \sim 2\pi\sqrt{m/\kappa}$.
>
> **iii)** (2 points) When the dumbbell with axis perpendicular to the wall approaches with velocity $\vec v = -v\hat x$, the front ball impacts the wall first. Since the impact time ($\tau \approx 4\,\mu\mathrm{s}$) is much shorter than the oscillation period ($T \approx 0.64\,\mathrm{ms}$), the front ball’s velocity changes almost instantaneously from $-v$ to $+v$, while the rear ball continues with velocity $-v$. Since the balls have equal masses, the centre of mass remains stationary. The dumbbell then oscillates about this stationary centre of mass, with the front ball’s velocity following a half-period sinusoidal oscillation, changing from $+v$ to $-v$ over a time interval of $T/2$. When the velocity reaches $-v$, the front ball impacts the wall again, and its velocity changes instantaneously from $-v$ to $+v$. After this second impact, both balls move away from the wall, with the same velocity $+v$, so the dumbbell as a whole departs with velocity $+v$.
>
> ![[nbpho-2025-p3-f1.svg]]
>
> **iv)** (2 points) During the impact, the front ball velocity becomes opposite, so the centre of mass stops (as the rear ball moves still with its old speed). After the collision, the front ball obtains a component $v\cos\alpha$ along its axis, and $v\sin\alpha$ perpendicular to it. The former initiates oscillations of period $T$, and the latter — a rotation at angular speed
>
> $$\Omega = v\sin\alpha/(l/2) = 2v\sin\alpha/l$$
>
> . The ball will hit the wall twice if the rotation is slow, and only once if the rotation is fast enough; let us study this in more details. By time $t \ll 1/\Omega$, the rotation angle is $\Omega t$, and the distance of the farthest point of the ball from the rotation centre is $l/2-a\sin(\omega t)$, where the oscillation amplitude can be obtained from the energy conservation law, $a = v\cos\alpha\sqrt{m/k} = v\cos\alpha/\omega$. So, the distance from the wall of the closest point of the ball is
>
> $$\frac l2\cos\alpha-\left[\frac l2-a\sin(\omega t)\right]\cos(\alpha+\Omega t)\approx
> \frac l2\Omega t\sin\alpha+a\cos\alpha\sin\omega t =
> vt\sin^2\alpha+\frac v\omega\cos^2\alpha\sin\omega t =
> \frac v\omega s\sin^2\alpha+\frac v\omega\cos^2\alpha\sin s,\quad s\equiv\omega t.$$
>
> If this expression becomes negative, there will be a second collision. So, the cross-over value of $α = α_0$ is such that the expression becomes never negative, hence
>
> $$\tan^2\alpha_0 = -\min\frac{\sin s}{s}\approx 0.217,$$
>
> hence
>
> $$\alpha_0 = \arctan\sqrt{0.217}\approx 25^\circ.$$
>
> If we divide this expression by corresponding **v)** (2 points) Using the results of the previous task, the angular speed after the initial collision is $\Omega = 2v\sin\alpha/l$. The dumbbell rotates around its centre of mass, longitudinal oscillations decay by the time of the second collision. It rotates until the other ball will hit the wall. At the moment of the second collision, the velocity of the ball is $v\sin\alpha$, and its projection to the surface normal of the wall is $-v\sin^2\alpha$.
> During the second collision, that components reverses sign, and as a result, both balls have now $x$-directional velocity component $v\sin^2\alpha$. Hence, this is also the speed of the centre of mass — the speed with which the dumbbell departs from the wall.

> [!grading]- Критерии оценивания
> Grading: (preliminary)
>
> | Part | Criterion | Points |
> |---|---|---|
> | i) | explaining that oscillation is symmetric around centre of the rod (invoking Newton’s third law suffices as well) | 0.5 pts |
> | | expressing stiffness of half-rod | 0.5 pts |
> | | minor mistake made in stiffness expression | −0.2 pts |
> | | mass of the ball $m = \frac43\pi r^3\rho$ | 0.2 pts |
> | | Realising that the system can be treated as a spring | 0.3 pts |
> | | oscillation period $T = 2\pi\sqrt{m/k}$ | 0.3 pts |
> | | final answer | 0.2 pts |
> | ii) | Solution 1: | |
> | | Realise compressed ball is essentially a compression wave | 0.5 pts |
> | | Formula for speed of sound | 0.5 pts |
> | | Relation between time, radius and speed | 0.5 pts |
> | | Final answer | 0.5 pts |
> | | Solution 2: | |
> | | Realise the ball can be thought of as a spring | 0.5 pts |
> | | Estimate spring constant | 0.5 pts |
> | | Relation between spring constant and time or frequency | 0.5 pts |
> | | Final answer | 0.5 pts |
> | iii) | 2 hits | 0.4 pts |
> | | velocity of front ball flips almost instantaneously | 0.4 pts |
> | | centre of mass stays at rest | 0.4 pts |
> | | sinusoidal movement of front ball | 0.4 pts |
> | | constant velocity $-v$ of front ball after second hit | 0.4 pts |
> | iv) | Realise it behaves as in previous question (balls at velocity -v and v, CM at rest), but it now also rotates and oscillates around centre of mass | 0.5 pts |
> | | Expression for the angular speed of rotation | 0.3 pts |
> | | Expression of the amplitude of oscillations | 0.2 pts |
> | | Realise the difference in interaction is that if the first ball bounces once or twice | 0.2 pts |
> | | Formula for the distance of the front ball to the wall over time | 0.3 pts |
> | | Realise that if the distance is over 0 for all $t > 0$ the first ball does not hit the wall twice | 0.2 pts |
> | | Finding the critical angle given this condition | 0.3 pts |
> | v) | Realise that the dumbbell rotates around its centre of mass (after first collision) | 0.2 pts |
> | | Realise that the longitudinal oscillations have decayed by the time of the second collision | 0.4 pts |
> | | Expression for velocity of ball $v\sin\alpha$ | 0.5 pts |
> | | Expression for the component of velocity of ball in direction of surface normal $v\sin^2\alpha$ | 0.5 pts |
> | | Realise the component of velocity of second ball in direction of surface normal is also $v\sin^2\alpha$ | 0.2 pts |
> | | Realise the speed of the centre of mass $v\sin^2\alpha$ | 0.2 pts |
