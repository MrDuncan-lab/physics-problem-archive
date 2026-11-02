---
id: nbpho-2010-intl-theory-3
olympiad: NbPhO
year: 2010
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "3"
title: "Tyrannosaur (T. Rex)"
points: 6
aliases: ["Tyrannosaur (T. Rex)"]
topics: ["[[1.20 Колебания]]", "[[1.10 Статика]]"]
difficulty: 3
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Оценить длину ноги и скорость ходьбы тираннозавра по следам и размерам кости."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 3. Tyrannosaur (T. Rex) (6 points)

**NbPhO 2010** · Международная олимпиада · теория · 10–12 класс · задача 3  
Источник: [[_pdf/NbPhO/nbpho-2010.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2010.pdf#page=3|решение, стр. 3–4]]

Темы: [[1.20 Колебания]], [[1.10 Статика]]

> [!abstract] Кратко (составлено моделью)
> Оценить длину ноги и скорость ходьбы тираннозавра по следам и размерам кости.

Paleontologists have discovered tracks of a tyrannosaur where the footprints of the same leg are $A=4.0$ meters apart. They have also recovered a piece of a tyrannosaur leg bone that has bone cross-sectional area $N=10000$ times that of a chicken (which the tyrannosaur is related to).

**i)** (3 pt) Knowing that the chicken leg is approximately $l=15\mathrm{cm}$ tall, estimate the length of a tyrannosaur leg $L$. You may assume that the length of a leg scales as the length of the whole animal, and that the bone stress (force per area) is the same for both animals. Is your result consistent with the step length $A$?

**ii)** (3 pt) Estimate the natural walking speed of the tyrannosaur by approximating the walking motion of a leg with a freely oscillating pendulum motion. State clearly all the assumptions you make.

> [!answer]- Ответ
> **i** — $L=lN^{1/3}\approx3.23\,\mathrm{m}$. The step length is half of the distance between two traces of the same leg, i.e. $2\,\mathrm{m}$. This corresponds to the angle between the legs $\alpha=2\arcsin\frac1{3.2}\approx36^\circ$, which seems reasonable.
>
> **ii** — $v=A/T=A\omega/2\pi=\frac A{2\pi}\sqrt{\frac{3g}{2L}}\approx$

> [!solution]- Решение
> # Problem 3. Tyrannosaur (T. Rex) (6 points)
>
> **i.** (3 pts) Knowing that mass $m$ is proportional to volume, the relationship between mass and length scale is $L=l(M/m)^{1/3}$. The force F on animal bones is proportional to its mass and to the cross-sectional area of the bone; hence, the area is proportional to the mass. So, $\frac Mm=N$, from which
> $L=lN^{1/3}\approx3.23\,\mathrm{m}$. The step length is half of the distance between two traces of the same leg, i.e. $2\,\mathrm{m}$. This corresponds to the angle between the legs $\alpha=2\arcsin\frac1{3.2}\approx36^\circ$, which seems reasonable.
>
> **ii.** (3 pts) Let us model the leg with a physical pendulum. The leg can be approximated as a uniform rod attached from its upper end (the hip joint). Then its moment of inertia is $I=\frac13\mathcal ML^2$, where $\mathcal M$ is the leg mass.
>
> For small-angle swings of the pendulum, the only force acting on the leg is from the mass of the leg. Thus, the torque equation will be
>
> $$\frac13\mathcal ML^2\cdot\ddot\varphi=-\mathcal Mg\varphi\frac L2;$$
>
> here, $\varphi$ is the angle of the leg, so that the gravity force’s lever arm is equal to $\varphi\frac L2$. Hence, the circular frequency of the leg is $\omega=\sqrt{\frac{3g}{2L}}$. The displacement $A$ corresponds to the whole period, i.e. the walking speed
> $v=A/T=A\omega/2\pi=\frac A{2\pi}\sqrt{\frac{3g}{2L}}\approx$
>
> $1.2\,\mathrm{m/s}\approx5\,\mathrm{km/h}$. So, the walking speed is comparable to that of a human.
