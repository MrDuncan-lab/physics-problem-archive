---
id: nbpho-2004-intl-theory-2
olympiad: NbPhO
year: 2004
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "2"
title: "Planets"
points: 6
aliases: ["Planets"]
topics: ["[[1.3 Равноускоренное криволинейное движение]]", "[[1.6 Векторная кинематика]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Определить радиусы орбит планет по графику их видимого углового расстояния от звезды."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 2. Planets (6 pts)

**NbPhO 2004** · Международная олимпиада · теория · 10–12 класс · задача 2  
Источник: [[_pdf/NbPhO/nbpho-2004.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2004.pdf#page=3|решение, стр. 3]]

Темы: [[1.3 Равноускоренное криволинейное движение]], [[1.6 Векторная кинематика]]

> [!abstract] Кратко (составлено моделью)
> Определить радиусы орбит планет по графику их видимого углового расстояния от звезды.

Two planets move along circular orbits around a star of mass $M=2.0\cdot10^{30}\,\mathrm{kg}$; gravitational constant $G=6.67\cdot10^{-11}\,\mathrm{m^3/kg\cdot s^2}$. The dependence of the angular distance between a planet and the star on time, as seen from the other planet, is depicted in figure.

![[nbpho-2004-p1-f3.svg]]

**1)** What is the ratio of the radii of the planets $k$ (2 pts)?

**2)** Determine the value of the unit on the vertical axis (or express it in terms of $k$, if you were unable to find it) (2 pts).

**3)** What are the orbital radii of the planets, if the unit on the horizontal axis equals to one year (2 pts)?

> [!answer]- Ответ
> **1** — $k=\frac{1-\varepsilon}{1+\varepsilon}\approx1.4$.
>
> **1** — $k=\sin[(\frac12-\mu)\pi]\approx1.47\approx1.5$.
>
> **2** — $\varphi_m/(\frac12-\mu)\pi\approx4.8$.
>
> **3** — $r_1\approx2.5\cdot10^{11}\,\mathrm m$; correspondingly,
>
> **3** — $r_2=kr_1\approx3.7\cdot10^{11}\,\mathrm m$.

> [!solution]- Решение
> # 2. Planets (6 pts)
>
> **1)** First method: determine the tangents to the graph at the points where the curve crosses the horizontal axis, $a_1\approx-2.8$ and $a_2\approx16$ (in graph units), respectively. Then, $a_2=\omega\frac{-k}{1+k}$ and $a_2=\omega\frac{k}{1-k}$. The graph units will cancel out from the ratio of these to tangents, $\varepsilon=-\frac{a_2}{a_1}=\frac{1+k}{1-k}\approx5.7$, hence
> $k=\frac{1-\varepsilon}{1+\varepsilon}\approx1.4$.
>
> Second method (more precise): determine the distances between neighbouring minimum and maximum, $t_1\approx1.2$, and between neighbouring minima $t_2\approx4.6$ (in graph units), respectively. $\mu=\frac{t_1}{t_2}=\frac{\pi-2\arcsin k}{2\pi}\approx0.261$, hence
> $k=\sin[(\frac12-\mu)\pi]\approx1.47\approx1.5$.
>
> **2)** For the maximal angular displacement $\varphi_m$, $\sin\varphi_m=k=\sin[(\frac12-\mu)\pi]$, hence $\varphi_m=(\frac12-\mu)\pi=0.75\,\mathrm{rad}\approx3.6$ units. Therefore, the unit is
> $\varphi_m/(\frac12-\mu)\pi\approx4.8$.
>
> **3)** If the angular velocities of the planets are $\omega_1$ and $\omega_2$, the seeming angular velocity (as seen from the system, where both star and the observer planet are at rest) is $\omega=\omega_1-\omega_2$. From the Newton II law, $GMr_i^{-2}=\omega_i^2r_i$, where $i=1,2$ and $r_i$ is the planet’s orbital radius. So, $\omega_i=\sqrt{GMr_i^{-3}}$ and $\omega=\sqrt{GM}(r_2^{-1.5}-r_1^{-1.5})=\sqrt{GM}r_1^{-1.5}(1-k^{-1.5})$. Finally, the square of the observed period $T^2=(2\pi/\omega)^2=4\pi^2r_1^3/GM(1-k^{-1.5})^2$ and $r_1=[T^2GM(1-k^{-1.5})^2/4\pi^2]^{1/3}$. Using $T\approx4.6$ years $\approx1.45\cdot10^8\,\mathrm s$, we arrive at
> $r_1\approx2.5\cdot10^{11}\,\mathrm m$; correspondingly,
> $r_2=kr_1\approx3.7\cdot10^{11}\,\mathrm m$.
