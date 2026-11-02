---
id: nbpho-2014-intl-theory-2
olympiad: NbPhO
year: 2014
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "2"
title: "Waste project"
points: 8
aliases: ["Waste project"]
topics: ["[[1.17 Законы сохранения энергии и импульса]]", "[[1.3 Равноускоренное криволинейное движение]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Определить траекторию и параметры полёта космического корабля с отходами от Земли к Солнцу."
status: "проверено: сверка, два чтения + арбитр"
lang: en
tags: [задача]
---

# 2. WASTE PROJECT (8 points)

**NbPhO 2014** · Международная олимпиада · теория · 10–12 класс · задача 2  
Источник: [[_pdf/NbPhO/nbpho-2014.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2014.pdf#page=3|решение, стр. 3]]

Темы: [[1.17 Законы сохранения энергии и импульса]], [[1.3 Равноускоренное криволинейное движение]]

> [!abstract] Кратко (составлено моделью)
> Определить траекторию и параметры полёта космического корабля с отходами от Земли к Солнцу.

In 2114, Europarliament decided that all radioactive wastes need to be sent to the Sun, so as to avoid contamination of Earth and orbital space. In what follows, you can use the following numerical data: duration of one year $T=365.25\,\mathrm{days}$, orbital speed on Earth $v_0=29.8\,\mathrm{km/s}$, angular diameter of Sun as seen from the Earth $\alpha=0.5^\circ$, radius of the Earth $R=6400\,\mathrm{km}$, free fall acceleration at the Earth’s surface $g=9.81\,\mathrm{m/s^2}$.

According to the project, the waste is sent to the Sun using ballistic spaceships: the engine operates only during a short period of time during which the displacement of the spaceship remains much shorter than the radius of Earth. In the Earth’s frame of reference, the spaceship obtains a velocity opposite to the orbital velocity of Earth in the Sun’s frame of reference. Further, the ship moves along a ballistic trajectory until it hits the Sun. The trajectory is such as to minimize the consumption of fuel.

**i)** (1 point) Sketch the trajectory of the spaceship.

As a first approximation, calculations can be done when neglecting the angular size of the Sun (i.e. by putting $\alpha\approx0^\circ$); you can use this approach for the next two questions.

**ii)** (1.5 points) How long will it take for the spaceship to travel from the Earth to the Sun?

**iii)** (1.5 points) What is the speed of the spaceship in the Earth’s frame of reference when the distance from the Earth is much larger than the Earth’s radius, but still much shorter than the distance to the Sun?

**iv)** (2.5 points) Answer the previous question without making the approximation $\alpha\approx0^\circ$.

**v)** (1.5 points) What is the speed of the spaceship in the Earth’s frame of reference when the distance from the Earth is much smaller than the Earth’s radius?

> [!answer]- Ответ
> **2.2** — $t=2^{-5/2}T\approx64.6\,\mathrm{days}$.
>
> **2.3** — $v_0=29.8\,\mathrm{km/s}$.
>
> **2.4**
>
> $$
> v_S=v_0\sqrt{\frac{2r_S}{R_E+r_S}}=v_0\sqrt{2\sin\left(\frac{\alpha}{2}\right)}\approx v_0\sqrt{\alpha}.
> $$
>
> **2.4** — $v_S\approx2.8\,\mathrm{km/s}$; the speed in the Earth’s frame of reference
>
> **2.4** — $v_E=v_0-v_S\approx27.0\,\mathrm{km/s}$.
>
> **2.5**
>
> $$
> u=\sqrt{v_E^2+2gR}\approx29.2\,\mathrm{km/s}.
> $$

> [!solution]- Решение
> # 2. Waste project
>
> **1)** The trajectory is a very elliptical ellipse, perihelion of which is within the Sun. In order to minimize the fuel consumption, the speed near the Earth’s orbit needs to be as large as possible (we need to decelerate the ship to bring it to the elliptical orbit), hence the full orbital energy of the ship $E=-\frac{GMm}{2a}$ needs to be as small as possible. Here, $M$ is the mass of the Sun, $m$ — the mass of the space ship, and $a$ — the longer semiaxis. So, $a$ needs to be as large as possible, which means that the perihelion needs to lie at the surface of the Sun, in which case $2a=R_E+r_S$, where $R_E$ is the orbital radius of the Earth and $r_S$ — the radius of the Sun. The resulting trajectory is depicted below.
>
> ![[nbpho-2014-p3a-c5581.png]]
>
> **2)** If we neglect the radius of the Sun, the space ship needs to “fall” directly to the Sun, which means that its initial orbital speed must be zero, hence its trajectory is an ellips with longer semiaxis equal to $R_E/2$. According to the Kepler’s III law, the period on such an orbit is $2^{3/2}$ times shorter than the Earth’s orbital period $T$. The travel time $t$ is half of the period, so that
> $t=2^{-5/2}T\approx64.6\,\mathrm{days}$.
>
> **3)** In the Sun’s frame of reference, the speed needs to be zero; hence, in the Earth’s frame of reference, it is opposite to the orbital velocity of the Earth and by modulus equal to
> $v_0=29.8\,\mathrm{km/s}$.
>
> **4)** The speed $v_S$ in the Sun’s frame of reference is found from the expression for the total energy,
>
> $$-\frac{GMm}{2a}=-\frac{GMm}{R_E+r_S}=-\frac{GMm}{R_e}+\frac{mv_S^2}{2},$$
>
> hence
>
> $$v_S=\sqrt{\frac{GM}{R_E}\frac{2r_S}{R_E+r_S}}.$$
>
> This expression can be rewritten by using equality $v_0^2=\frac{GM}{R_E}$ as
>
> $$v_S=v_0\sqrt{\frac{2r_S}{R_E+r_S}}=v_0\sqrt{2\sin\left(\frac{\alpha}{2}\right)}\approx v_0\sqrt{\alpha}.$$
>
> Numerically this yields
> $v_S\approx2.8\,\mathrm{km/s}$; the speed in the Earth’s frame of reference
> $v_E=v_0-v_S\approx27.0\,\mathrm{km/s}$.
>
> **5)** Part of the initial kinetic energy in the Earth’s frame of reference goes to the change of the potential energy due to the gravitational pull of the Earth, $\Delta\Pi=\frac{GM_Em}{R}=gmR$ hence $gR+\frac{v_E^2}{2}=\frac{u^2}{2}$. Here, $M_E$ is the Earth’s mass and $u$ is the launching speed. So,
>
> $$u=\sqrt{v_E^2+2gR}\approx29.2\,\mathrm{km/s}.$$
