---
id: nbpho-2015-intl-theory-3
olympiad: NbPhO
year: 2015
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "3"
title: "Gear shift"
points: 3
aliases: ["Gear shift"]
topics: ["[[1.3 Равноускоренное криволинейное движение]]", "[[1.13 Кинематические связи (и динамика)]]"]
difficulty: 3
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Определить оптимальную скорость переключения передач и ускорение автомобиля по графику момента двигателя."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 3. GEAR SHIFT (3 points)

**NbPhO 2015** · Международная олимпиада · теория · 10–12 класс · задача 3  
Источник: [[_pdf/NbPhO/nbpho-2015.pdf#page=1|условие, стр. 1–6]] · [[_pdf/NbPhO/nbpho-2015.pdf#page=6|решение, стр. 6]]

Темы: [[1.3 Равноускоренное криволинейное движение]], [[1.13 Кинематические связи (и динамика)]]

> [!abstract] Кратко (составлено моделью)
> Определить оптимальную скорость переключения передач и ускорение автомобиля по графику момента двигателя.

*(by K.A. Saar)*

The maximum torque of a car’s engine depends on the engine’s rotation speed (see the following figure, a larger copy is on an extra sheet).

![[nbpho-2015-p1-f1.svg]]

The rotations of the engine are transferred to the wheels through a transmission gearbox. When the car is in the first gear, then the gear ratio from the engine to the wheels is 14:1; in the second gear, the gear ratio is 7:1.

**i)** (2 points) At what speed of the car should the transmission be shifted from the first gear into the second, in order for the average acceleration of the car to be maximum?

**ii)** (1 point) What is the acceleration of the car immediately before and immediately after the gear change?

Neglect any drag force. The mass of the car $m=1400\mathrm{kg}$, the diameter of a wheel is $d=60\mathrm{cm}$.

![[nbpho-2015-p3-c0004.png]]

Estonian-Finnish Olympiad 2015

> [!answer]- Ответ
> **i** — $v\approx37\mathrm{km/h}$.
>
> **ii** — $a=\frac{28\tau_e}{md}\approx2.2\mathrm{m/s^2}$.

> [!solution]- Решение
> # 3. GEAR SHIFT
>
> **i)** The acceleration of the car is proportional to the torque applied to the wheels. Therefore we should keep the torque onto the wheels as big as possible, and shift gears when the torque applied onto the wheels in the second gear is bigger than the one obtained in the first gear. At the same car’s speed, the engine’s speed is $(14:1):(7:1)=2$ times bigger in the first gear than in the second gear. Correspondingly, at the same engine’s speed, the torque onto the wheels is two times smaller in the second gear than in the first gear. Therefore we can draw another graph where the engine’s torque is twice as small and the engine’s speed is two times bigger. The intersection of those graphs is the point where the gear should be changed.
>
> ![[nbpho-2015-p6-f1.svg]]
>
> From the graph we read that at that moment in the first gear, the engine’s torque is $\tau_e=66.5\mathrm{N\cdot m}$ and the engine’s speed is $\omega_e=4550\mathrm{rpm}$. The wheels’ angular speed is then $\omega_w=\frac1{14}\omega_e$ and the car’s speed is $v=\frac12\omega_wd=\frac1{28}\omega_ed$. Let’s convert $1\mathrm{rpm}=120\pi\,\mathrm{rad/h}$ and $d=6\times10^{-4}\,\mathrm{km}$. Thus,
> $v\approx37\mathrm{km/h}$.
>
> **ii)** At the optimum point, the acceleration before and after gear change is the same. From Newton’s second law, it equals $a=F/m=\frac{2\tau_w}{md}$, where the net torque applied to the wheels is $\tau_w=14\tau_e$. Hence,
> $a=\frac{28\tau_e}{md}\approx2.2\mathrm{m/s^2}$.
