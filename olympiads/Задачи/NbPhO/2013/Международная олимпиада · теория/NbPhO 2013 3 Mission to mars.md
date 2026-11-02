---
id: nbpho-2013-intl-theory-3
olympiad: NbPhO
year: 2013
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "3"
title: "Mission to mars"
points: 7
aliases: ["Mission to mars"]
topics: ["[[1.17 Законы сохранения энергии и импульса]]", "[[1.3 Равноускоренное криволинейное движение]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Рассчитать длительность перелёта Земля — Марс и необходимые изменения скорости на переходной орбите."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 3. MISSION TO MARS (7 points)

**NbPhO 2013** · Международная олимпиада · теория · 10–12 класс · задача 3  
Источник: [[_pdf/NbPhO/nbpho-2013.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2013.pdf#page=3|решение, стр. 3–4]]

Темы: [[1.17 Законы сохранения энергии и импульса]], [[1.3 Равноускоренное криволинейное движение]]

> [!abstract] Кратко (составлено моделью)
> Рассчитать длительность перелёта Земля — Марс и необходимые изменения скорости на переходной орбите.

A crew of astronauts is going to be sent to explore the polar region of Mars and search for buried water ice. Their spaceship will travel from Earth to Mars along an elliptic transfer orbit tangential to the orbits of both planets. Despite its shortcomings, this orbit is commonly used in space travel due to its relatively good fuel economy. Future manned missions to Mars are very likely based on this kind of transfer. In this problem you will examine some aspects of this orbit.

The mean orbital radius of Mars is $R_a=1.52\mathrm{AU}$. The mean orbital radius of Earth is $R_g=1\mathrm{AU}=149600000\mathrm{km}$. Mars has a mean radius of $r_a=3397\mathrm{km}$ and surface gravity $g_a=3.71\mathrm{m/s^2}$. Earth has a mean radius of $r_g=6371\mathrm{km}$.

**i)** (1 point) Find the orbital period $T_a$ of Mars, i.e. find the length of Martian “year” in Earth years.

**ii)** (1.5 points) How long ($t_t$) does a one-way trip to Mars take?

**iii)** (1.5 points) The spaceship is put into this orbit by using a powerful rocket. It is more efficient to burn fuel as a short burst when the spaceship is still near Earth. How much additional speed ($\Delta v_1$) does the booster have to be able to give to the spaceship to enter the transfer orbit, starting from the north pole? Neglect the air resistance.

**iv)** (1.5 points) Estimate the $\Delta v_2$ needed to enter a circular orbit close to Mars.

**v)** (1.5 points) What is the minimal duration of the trip to Mars and back?

> [!answer]- Ответ
> **i** — $t_t\approx1.87\,\mathrm{yr}$.
>
> **ii**
>
> $$
> t_t=\frac{T_g}{2}\frac{(R_a+R_g)^{3/2}}{(2R_g)^{3/2}}\approx0.707\,\mathrm{yr}.
> $$
>
> **iii** — $\Delta v_1\approx11.2\mathrm{km/s}$.
>
> **iv** — $\Delta v_2\approx2.43\mathrm{km/s}$.
>
> **v** — $2.67\mathrm{yr}$.

> [!solution]- Решение
> # 3. MISSION TO MARS (7 points)
>
> **i)** (1 point) We can find the orbital period of Mars from Kepler’s third law $R_a^3/R_g^3=T_a^2/T_g^2$, giving
> $t_t\approx1.87\,\mathrm{yr}$.
>
> **ii)** (1.5 points) Again, we can use Kepler’s third law to calculate half of the orbital period,
>
> $$t_t=\frac{T_g}{2}\frac{(R_a+R_g)^{3/2}}{(2R_g)^{3/2}}\approx0.707\,\mathrm{yr}.$$
>
> **iii)** (1.5 points) *Background.* $\Delta v$ is important, because the sum of all $\Delta v$ determines how much fuel is needed for a given mission. The fuel needed is exponential of total $\Delta v$ and is described by Tsiolkovsky rocket equation.
>
> Kinetic energy per unit mass of such a transfer orbit where it intersects the Earth’s orbit is $-\frac{GM_s}{R_g+R_a}+\frac{GM_s}{R_g}$. Using the orbital angular speed of Earth we can substitute $GM_s=\frac{4\pi^2R_g^3}{T_g^2}$. The speed at the beginning of the transfer orbit becomes
>
> $$v_{t0}=\sqrt{2GM_s\left(\frac1{R_g}-\frac1{R_g+R_a}\right)}\approx32.7\mathrm{km/s}.$$
>
> The speed in Earth’s inertial frame is $v'_{t0}=v_{t0}-v_g\approx2.94\mathrm{km/h}$. To achieve that, we first need to escape Earth’s gravity, so
>
> $$\Delta v_1=\sqrt{2\left(\frac{v_{t0}'^2}{2}+\frac{GM_g}{r_g}\right)}.$$
>
> Using the surface gravity of Earth we can substitute $\frac{GM_g}{r_g}=g_gr_g$ so
> $\Delta v_1\approx11.2\mathrm{km/s}$.
>
> **iv)** (1.5 points) We can calculate the speed of the transfer orbit where it intersects the orbit of Mars from Kepler’s second law $v_{t1}=v_{t0}/1.52\approx21.5\mathrm{km/s}$. The speed of the spacecraft relative to Mars is $v'_{t1}\approx3.25\mathrm{km/s}$. The speed of the spacecraft once near Mars surface is
>
> $$v_{tm}=\sqrt{2\left(\frac{v_{t1}'^2}{2}+r_ag_a\right)}\approx5.98\mathrm{km/s}$$
>
> Since the speed of low Mars orbit is $v_{ea}=\sqrt{r_ag_a}\approx3.55\mathrm{km/s}$, we need to brake for
> $\Delta v_2\approx2.43\mathrm{km/s}$.
>
> **v)** (1.5 points) The Earth–Sun–Mars angle $\alpha$ at the launch of the mission needs to be $\alpha=\pi-w_at_t\approx0.77$ for the spacecraft to reach Mars. Likewise for the return trip $\beta=\pi-w_gt_t\approx-1.301$. If we go to the corotating frame of reference with earth, we can see that the minimal time between those two angles is $\frac{2\pi-\alpha+\beta}{w_a-w_g}\approx1.96\mathrm{yr}$. The minimal duration of the trip is therefore longer by $t_t$, giving
> $2.67\mathrm{yr}$.
