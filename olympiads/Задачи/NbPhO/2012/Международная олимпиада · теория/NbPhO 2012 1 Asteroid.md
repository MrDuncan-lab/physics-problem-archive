---
id: nbpho-2012-intl-theory-1
olympiad: NbPhO
year: 2012
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "1"
title: "Asteroid"
points: 14
aliases: ["Asteroid"]
topics: ["[[1.17 Законы сохранения энергии и импульса]]", "[[1.16 Закон сохранения импульса]]", "[[6 Оптика]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Исследовать столкновение астероида с Землёй и возможность его предотвращения давлением солнечного света."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# Problem 1. Asteroid (14 points)

**NbPhO 2012** · Международная олимпиада · теория · 10–12 класс · задача 1  
Источник: [[_pdf/NbPhO/nbpho-2012.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2012.pdf#page=3|решение, стр. 3]]

Темы: [[1.17 Законы сохранения энергии и импульса]], [[1.16 Закон сохранения импульса]], [[6 Оптика]]

> [!abstract] Кратко (составлено моделью)
> Исследовать столкновение астероида с Землёй и возможность его предотвращения давлением солнечного света.

Consider a hypothetical asteroid of mass $m_a$ and radius $r_a$, which moves along an elliptical orbit around the Sun (of mass $M_s$) in the same direction as Earth. Let us assume that the Earth’s orbit is a circle of radius $R_e$ (neglecting thus its eccentricity) and that the two orbits lay in the same plane. The asteroid’s shortest distance to the Sun (at its perihelion) $R_\mathrm{min}=\frac12 R_e$ and the longest distance (at the apohelion) $R_\mathrm{max}=1.51R_e\approx1.5R_e$ (you may use the approximate value to simplify your calculations). The orbital velocity of the Earth $v_0=30\,\mathrm{km/s}$. You can also use the following numerical values: the radius of the Earth $r_e=6400\,\mathrm{km}$, free fall acceleration at the Earth’s surface $g=9.81\,\mathrm{m/s^2}$, angular diameter of the Sun as seen from the Earth $\alpha=0.5^\circ$, duration of one year $T_0=365\,\mathrm{days}$, the temperature of the Sun’s surface $T_s=6000\,\mathrm{K}$, free fall acceleration at the Sun’s surface $g_s=275\,\mathrm{m/s^2}$, Stefan Boltzmann constant $\sigma=5.6704\times10^{-8}\,\mathrm{kg\cdot s^{-3}\cdot K^{-4}}$, the speed of light $c=3\times10^8\,\mathrm{m/s}$. The asteroid is of a spherical shape, its radius $r_a=10\,\mathrm{m}$ and mass $m_a=1\times10^7\,\mathrm{kg}$; both the Sun and the asteroid can be considered as perfectly black bodies.

**Part A. Collision with Earth (5 points)**

**i.** (2 pts) Suppose that the asteroid will collide with the Earth and is already very close, at a distance $l\ll R_e$ from the Earth’s surface; what is the velocity of the asteroid with respect to the Earth assuming that (a) $l\gg r_e$; (b) $l\ll r_e$.

**ii.** (2 pts) Impact parameter $b$ is defined in the Earth’s reference frame as the distance between the Earth and a line, tangent to the asteroid’s trajectory at a point which is far enough (at a distance $l$, $r_e\ll l\ll R_e$). Determine the maximal value of the impact parameter $b_\mathrm{max}$ for which the asteroid will still collide with the Earth.

**iii.** (1 pt) According to calculations, the asteroid is going to hit the Earth centrally after $N=10$ orbital periods. In order to avert the collision, the period of the asteroid needs to be changed; by how many seconds? (Assume simplifyingly that the intersection point of the two orbits remains at rest.)

**Part B. Changing the solar pull (9 points)**

Theoretically, it is possible to change the asteroid’s period by making use of the pressure of the solar radiation. Let us study, how realistic is such a project. The Sun pulls the asteroid with the gravitational force equal to $F_0=GM_sm_a/R^2$, where $G$ is the gravitational constant and $R$ is the distance between the Sun and the asteroid at the given moment of time. Let us denote $GM_s=\gamma_0$, so that

$$F=\gamma_0m_a/R^2.$$

Suppose that when the asteroid is at its perihelion, the constant $\gamma_0$ is decreased instantaneously, down to a new value $\gamma_1$, which remains constant during the subsequent motion.

**i.** (2 pts) Find the new apohelion distance $R'_\mathrm{max}$ of the asteroid; express it in terms of $\kappa=(\gamma_0-\gamma_1)/\gamma_0$.

**ii.** (2 pts) Find the change of the asteroid’s orbital period assuming that $\kappa\ll1$ (express it in terms of $\kappa$).

**iii.** (4 pts) Suppose that at its perihelion, the asteroid is coated with a perfectly retro-reflective paint (which directs all the incident light directly back, towards the source). Such a painting will result in a change of the effective pull of the asteroid towards the Sun; find the respective value of $\kappa$ (provide also a numerical estimate).

**iv.** (1 pt) Estimate, is it realistic to avert the collision with this asteroid using the retroreflective paint.

> [!answer]- Ответ
> **1.A.i** — $v_a=2v_0\sin15^\circ\approx15.5\,\mathrm{km/s}$. When accelerated further by the Earth’s gravity field, the respective gravitational energy will be added to the kinetic one,
>
> **1.A.i** — $v_b=\sqrt{v_a^2+2gr_e}=19.1\,\mathrm{km/s}$.
>
> **1.A.ii** — $b=r_ev_b/v_a=7900\,\mathrm{km}$.
>
> **1.A.iii** — $\tau/10=27\,\mathrm{s}$.
>
> **1.B.i**
>
> $$
> a'=R_e\frac{1-\kappa}{1-4\kappa},\quad R'_\mathrm{max}=\frac{R_e}{2}\frac{3}{1-4\kappa}.
> $$
>
> **1.B.ii** — $\Delta T=5T_0\kappa$.
>
> **1.B.iii**
>
> $$
> \kappa=\Delta F/g_Sm_a=\pi r_a^2\sigma T_s^4/cg_Sm_a\approx2.8\times10^{-8}.
> $$

> [!solution]- Решение
> # Problem 1. Asteroid (14 points)
>
> **Part A. Collision with Earth (5 points)**
>
> **i.** (2 pts) The longer axis of the asteroid $2a=R_\mathrm{max}+R_\mathrm{min}=2R_e$ equals to that of Earth, so the full energies, when reduced to the unit mass, are equal. Immediately before the collision, the Earth and the asteroid are at the same distance from the Sun, so the gravitational potentials are equal, too. Hence, the speeds are also equal. The distance between the Sun and the asteroid equals to the longer semiaxis, hence it is situated at the shorter semiaxis of the orbit. The velocity of the asteroid is perpendicular to the shorter semiaxis, and the velocity of the Earth — to the radius vector drawn from the Sun. So, the angle between those two vectors is the angle between the radius vector and the shorter semiaxis, $\sin\alpha=\frac12(R_\mathrm{max}-R_\mathrm{min})/R_e=\frac12$, hence $\alpha=30^\circ$. The relative velocity of the asteroid is the vector difference of the two vectors, so its modulus equals to
> $v_a=2v_0\sin15^\circ\approx15.5\,\mathrm{km/s}$. When accelerated further by the Earth’s gravity field, the respective gravitational energy will be added to the kinetic one,
> $v_b=\sqrt{v_a^2+2gr_e}=19.1\,\mathrm{km/s}$.
>
> **ii.** (2 pts) At the limit case of impact, the trajectory of the asteroid is tangent to the surface of the Earth. So, we can apply the conservation of angular momentum for the point where the trajectory touches the Earth, $v_ab=v_br_e$, hence
> $b=r_ev_b/v_a=7900\,\mathrm{km}$.
>
> **iii.** (1 pt) Suppose that the asteroid is delayed by $\tau$; at that moment when the asteroid is at the Earth’s orbit, the Earth is at the distance $l=v_0\tau$ from the asteroid. The relative velocity of the asteroid forms with this displacement vector an angle equal to $90^\circ-15^\circ=75^\circ$, hence the impact parameter $b=v_0\tau\sin75^\circ$, from where $\tau=b/v_0\sin75^\circ\approx270\,\mathrm{s}$. Since this time delay is accumulated over 10 periods, the delay need for a single period is
> $\tau/10=27\,\mathrm{s}$.
>
> **Part B. Changing the solar pull (9 points)**
>
> **i.** (2 pts) When $\gamma$ changes, the kinetic energy remains constant:
>
> $$-\frac{\gamma_0}{2a}+\frac{\gamma_0}{0.5R_e}=-\frac{\gamma_1}{2a'}+\frac{\gamma_1}{0.5R_e}$$
>
> where $a=R_e$ and $2a'=0.5R_e+R'_\mathrm{max}$. So,
>
> $$\frac{\gamma_1}{2a'}=\frac{\gamma_0}{2R_e}\left(4\frac{\gamma_1}{\gamma_0}-3\right)\Rightarrow(1-\kappa)R_e=a'(1-4\kappa),$$
>
> $$a'=R_e\frac{1-\kappa}{1-4\kappa},\quad R'_\mathrm{max}=\frac{R_e}{2}\frac{3}{1-4\kappa}.$$
>
> **ii.** (2 pts) At the limit of small $\kappa$, we can simplify the previous result,
>
> $$\frac{a'}{R_e}\approx1+3\kappa.$$
>
> From the Kepler’s third law, $T/T_0=(a'/a)^{3/2}\sqrt{\gamma_0/\gamma_1}$, from where $\frac{\Delta T}{T_0}\approx\frac32\frac{a'-a}{a}+\frac{\kappa}{2}=5\kappa$. So,
> $\Delta T=5T_0\kappa$.
>
> **iii.** (4 pts) For photons, the energy-to-mass ratio is $c$. Therefore, at the Sun’s surface, the momentum carried by photons per unit time across a surface area $S$ is given by $dp/dt=S\sigma T_s^4/c$. As the result of the coating, the photons are reflected back by the asteroid, instead of being absorbed. So, before coating, each photon gave to the asteroid a momentum equal to its own; no it will double. Hence, the change in the force due to photons is given by $\Delta F=\pi r_a^2\sigma T_s^4/c$ (assuming that the asteroid is at the Sun’s surface). Both the pressure of photons and gravity force are inversely proportional to the distance from the Sun, so the force due to photons can be, indeed, considered as a correction to the gravity constant. $\kappa$ is the relative change of that constant and can be calculated for the Sun’s surface as
>
> $$\kappa=\Delta F/g_Sm_a=\pi r_a^2\sigma T_s^4/cg_Sm_a\approx2.8\times10^{-8}.$$
>
> **iv.** (1 pt) We need to have $\Delta T=27\,\mathrm{s}$, hence $\kappa=\frac15\frac{\Delta T}{T_0}\approx1.7\times10^{-7}$. This exceeds by an order of magnitude the effect provided by the coating. $\kappa$ provided by the coating is inversely proportional to the diameter of the asteroid; the required $\kappa$ is inversely proportional to $N$. So, it would be possible to avert collision for $r_a=2\,\mathrm{m}$, or for $r_a=10\,\mathrm{m}$ with $N=60$. In the first case, the asteroid may not be large enough to warrant attention; in the second case, 60 years is too long time. So, the answer is “no”.
