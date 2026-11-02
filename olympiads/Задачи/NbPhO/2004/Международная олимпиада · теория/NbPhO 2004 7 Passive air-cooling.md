---
id: nbpho-2004-intl-theory-7
olympiad: NbPhO
year: 2004
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "7"
title: "Passive air-cooling"
points: 9
aliases: ["Passive air-cooling"]
topics: ["[[2.2 Уравнение состояния идеального газа]]", "[[2.4 Теплоёмкость процесса]]", "[[1.18 Гидростатика]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Рассчитать температуру и скорость воздуха в системе пассивного охлаждения."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 7. Passive air-cooling (9 pts)

**NbPhO 2004** · Международная олимпиада · теория · 10–12 класс · задача 7  
Источник: [[_pdf/NbPhO/nbpho-2004.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2004.pdf#page=4|решение, стр. 4]]

Темы: [[2.2 Уравнение состояния идеального газа]], [[2.4 Теплоёмкость процесса]], [[1.18 Гидростатика]]

> [!abstract] Кратко (составлено моделью)
> Рассчитать температуру и скорость воздуха в системе пассивного охлаждения.

Consider a passive cooling system depicted in figure. Cold air (at normal conditions: $p_0=10^5\,\mathrm{Pa}$, $T_0=293\,\mathrm K$) flows over the heat sink of a chip of power dissipation $P=100\,\mathrm W$, into a vertical pipe of length $L=1\,\mathrm m$ and cross-sectional area $S=25\,\mathrm{cm^2}$. After passing the pipe, air enters the ambient room. Assume that the air inside the pipe becomes well mixed; neglect the viscous and turbulent friction of air inside the pipe and heat sink. Air can be considered as an ideal gas with adiabatic exponent $\gamma=1.4$ and molar mass $\mu=29\,\mathrm{g/mol}$.

![[nbpho-2004-p2-f2.svg]]

**1)** Express heat capacitance at constant pressure $c_p$ via quantities $\gamma$ and $R$ (1 pt).

**2)** Find a relationship between the outflowing air density $\rho$ and temperature $T$ (the relationship may contain also the parameters defined above) (2 pts).

**3)** Find a relationship between the air flow velocity in the pipe $v$ and outflowing air density $\rho$ (the relationship may contain also the parameters defined above) (2 pts).

**4)** Express the power dissipation $P$ in terms of the air flow velocity $v$, the outflowing air temperature $T$, and density $\rho$ (the relationship may contain also the parameters defined above) (2 pts).

**5)** What is the temperature $T$ of the outflowing air? In your calculations, you may use approximation $T-T_0\ll T_0$ (2 pts)?

> [!answer]- Ответ
> **1** — $c_p=\frac\gamma{\gamma-1}R$.
>
> **2** — $p_0=\frac\rho\mu RT$ (the process is by constant pressure, otherwise there would be huge acceleration due to pressure drop).
>
> **3** — $(\frac{p_0\mu}{RT_0}-\rho)gL=\rho v^2$.
>
> **4** — $P=\frac\gamma{\gamma-1}R(T-T_0)Sv\rho/\mu$.
>
> **5** — $T=T_0[1+(\frac\gamma{\gamma-1}\frac{gL}{S}\frac P{p_0})^{2/3}/gL]\approx322\,\mathrm K$.

> [!solution]- Решение
> # 7. Passive air-cooling (9 pts)
>
> **1)** Using $\gamma=c_p/c_V$ and $c_p=c_V+R$ we arrive at
> $c_p=\frac\gamma{\gamma-1}R$.
>
> **2)** From the ideal gas equation,
> $p_0=\frac\rho\mu RT$ (the process is by constant pressure, otherwise there would be huge acceleration due to pressure drop).
>
> **3)** Different air densities inside and outside the pipe give rise to small residual (as compared to the static pressure distribution inside the pipe) pressure difference between the open ends of the pipe, $\Delta p=-\Delta\rho gL$. This pressure difference is responsible for the acceleration of the air, from zero, up to the velocity of the air flow $v$. The momentum balance for small time interval $\tau$ yields $S\Delta p\tau=\rho(Sv\tau)v$, hence $(\rho_0-\rho)gL=\rho v^2$. Here, the cold air density $\rho_0=p_0\mu/RT_0$. Finally,
> $(\frac{p_0\mu}{RT_0}-\rho)gL=\rho v^2$.
>
> **4)** Heat flux:
> $P=\frac\gamma{\gamma-1}R(T-T_0)Sv\rho/\mu$.
>
> **5)** From the result of question 2, we obtain $\frac{\Delta\rho}{\rho}=-\frac{\Delta T}{T}$. From the result of question 3, $\frac{\Delta\rho}{\rho}=-\frac{v^2}{gL}$. Substituting these values into the equation obtained for question 4, $P=\frac\gamma{\gamma-1}R\frac{v^3}{gL}TS\rho/\mu$. Using the gas equation, this simplifies to $v^3=\frac\gamma{\gamma-1}\frac{gL}{S}\frac P{p_0}$. So,
> $T=T_0[1+(\frac\gamma{\gamma-1}\frac{gL}{S}\frac P{p_0})^{2/3}/gL]\approx322\,\mathrm K$.
