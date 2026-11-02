---
id: nbpho-2024-intl-theory-5
olympiad: NbPhO
year: 2024
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "5"
title: "String and pendulum"
points: 10
authors: ["Päivo Simson", "Jaan Kalda"]
aliases: ["String and pendulum"]
topics: ["[[1.20 Колебания]]", "[[1.10 Статика]]", "[[7 Эксперименты]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: true
source_damaged: false
summary: "Экспериментально найти поправку к периоду маятника и линейную плотность нити."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 5. String and pendulum (10 points) — Päivo Simson, Jaan Kalda.

**NbPhO 2024** · Международная олимпиада · теория · 10–12 класс · задача 5  
Источник: [[_pdf/NbPhO/nbpho-2024.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2024.pdf#page=6|решение, стр. 6–7]]

Темы: [[1.20 Колебания]], [[1.10 Статика]], [[7 Эксперименты]]

> [!abstract] Кратко (составлено моделью)
> Экспериментально найти поправку к периоду маятника и линейную плотность нити.

Tools: stand with a clamp; a thread bar that can be fixed horizontally to the stand; one piece of red string and two pieces of orange thread; two wooden blocks for fixing orange threads between the stand’s clamp; two steel nuts; tape measure, protractor, permanent marker, one staple of $m = 0.0889\,\mathrm{g}$.

**i)** (5 points) The formula for the oscillation period of a mathematical pendulum is $T = 2\pi\sqrt{l/g}$, where $l$ is the length of the pendulum and $g$ is the acceleration due to gravity, valid only for small oscillations. It is known that, in reality, the period $T$ also depends on the angular amplitude $\alpha$, which is the maximum deviation angle of the pendulum from the equilibrium position. For small angles $\alpha < \pi/2$, a good approximation is given by the formula $T = 2\pi\sqrt{l/g}(1 + A\alpha^2)$, where $\alpha$ is measured in radians and $A$ is a dimensionless constant. Find the value of the constant $A$ experimentally.

**ii)** (5 points) Find the mass of one meter’s worth of red string.

> [!answer]- Ответ
> **i**
>
> $$
> A=\frac{\sqrt{\frac{l_0}{l_1}}-1}{\alpha^2}=\frac{\sqrt{\frac{l_0}{l_1}}-1}{\left(\frac{\pi\phi}{180^\circ}\right)^2}.
> $$
>
> **i** — Thus generally, the larger the angle used in the measurement, the larger the value of $A$, which is why a value in the range $A\in[0.06,0.08]$ is to be expected.
>
> **ii**
>
> $$
> \frac Ml=\frac ml\frac{\tan\alpha_2-\cot\alpha_1}{\cot\alpha_1}=\frac ml(\tan\alpha_1\tan\alpha_2-1),
> $$
>
> **ii** — $M\approx0.12\,\mathrm g$.¹

> [!solution]- Решение
> # 5. String and pendulum (10 points) — Solution by Päivo Simson, Tudor Plopeanu.
>
> **i)** (5 points) We build two pendulums of different lengths and release them from different angles such that their periods are equal. We choose a small enough amplitude for the longer pendulum to be able to use the small angle formula, and a large amplitude for the short pendulum.
>
> We measure the lengths of the pendulums. Let $l_0$ be the length of the longer pendulum and $l_1$ be the length of the shorter pendulum. Additionally, we measure the angular amplitude $\phi$ (in degrees) of the shorter (larger-amplitude oscillating) pendulum with a protractor. From the equality of periods, we get
>
> $$\sqrt{l_0}=\sqrt{l_1}(1+A\alpha^2),$$
>
> from which
>
> $$A=\frac{\sqrt{\frac{l_0}{l_1}}-1}{\alpha^2}=\frac{\sqrt{\frac{l_0}{l_1}}-1}{\left(\frac{\pi\phi}{180^\circ}\right)^2}.$$
>
> We repeat the experiment with different lengths and finally find the average of the results. With the example values: $\phi=55^\circ$, $l_0=41.5\,\mathrm{cm}$ and $l_1=36.5\,\mathrm{cm}$ we get
>
> $A\approx0.07$. The theoretical true value is $A\approx0.063$, but the expected measured value is slightly larger, as higher order terms of the theoretical expansion $(1+A\alpha^2+B\alpha^4+\ldots)$ are “combined” in the value of $A$.
> Thus generally, the larger the angle used in the measurement, the larger the value of $A$, which is why a value in the range $A\in[0.06,0.08]$ is to be expected.
>
> *We note a common solution attempt of measuring the number of periods until two pendulums of equal length, but different initial angles, sync up again (i.e. one obtains a phase shift). However, the inaccuracy in this method is very large, in large part due to the amplitude drastically decreasing for large angles as an effect of energy dissipation. Even if a value of $A\approx0.07$ is obtained, this might therefore not get the “correct value” mark. However, if the amplitude decrease is taken into account, for example by averaging the angular amplitudes over the measurement time, it is possible to obtain a more accurate and correct result.*
>
> *Another common attempt of using a second pendulum as a “clock” results in a far too low time resolution, and therefore is not rewarded any points.*
>
> **ii)** (5 points)
>
> ![[nbpho-2024-p7-f2.svg]]
>
> We shall tie some red string to two fixture points on the same horizontal level and dangle the known mass staple from the middle point. We measure the angles the string makes with the horizontal plane at the middle points and next to the supports, averaging the latter for a more accurate value. Let $\alpha_1$ be the angle at the staple’s level, and $\alpha_2$ be the angle at the support’s level. Let $T_x$ be the (unknown) horizontal tension in the string. Along the string, between the staple and the support, $T_x$ is constant, as all acting forces are vertical.
>
> Equilibrium around the staple implies $2T_x\cot\alpha_1=mg$. Equilibrium on the string strictly between the staple and the support implies $2T_x(\tan\alpha_2-\cot\alpha_1)=Mg$, where $M$ is the mass of the string. We compute the mass of one meter’s worth of string as
>
> $$\frac Ml=\frac ml\frac{\tan\alpha_2-\cot\alpha_1}{\cot\alpha_1}=\frac ml(\tan\alpha_1\tan\alpha_2-1),$$
>
> where $l$ is the measured length of string.
>
> We repeat the experiment with different lengths and finally find the average of the results. With the example values $\alpha_1=70^\circ$, $\alpha_2=41^\circ$, we find
>
> $M\approx0.12\,\mathrm g$.¹
>
> ¹ Weighing the string on a scale, we found the true value to be $0.135\,\mathrm g$.

> [!grading]- Критерии оценивания
> Grading: (preliminary)
>
> Note: The “sync up method” can be rewarded up to 1.5pts (0.5pts for measurements, 1pts for multiple datapoints).
>
> | Criterion | Points |
> |---|---|
> | Recognize that we may use two pendulums with different lengths and angular amplitudes with equal periods | 0.5 pts |
> | Presented measurement data of relevant quantities | 0.5 pts |
> | Good choice of measurements (i.e. large enough angles, correct measured angle, long enough pendulum for reasonably large period etc.) | 0.5 pts |
> | Using two or more datapoints (e.g. different lengths etc.) | 1 pts |
> | Obtaining a correct expression for $A$ in terms of measurable quantities | 1 pts |
> | Correct value $A\in[0.06,0.08]$ | 1.5 pts |
>
> **ii)**
>
> Grading: (preliminary) Easy to by chance get close to the correct answer using other methods, e.g. scales, balancing, other pendulums, ... Also the method of physical vs mathematical pendulum does not work, likely due to air resistance.
>
> | Criterion | Points |
> |---|---|
> | Recognize the method (banana) | 1 pts |
> | Recognize that the system is in equilibrium, and we may balance the forces | 1 pts |
> | Correct equation | 1 pts |
> | (Conditional on correct method being used) Correct answer $[0.11,0.15]$ | 2 pts |
