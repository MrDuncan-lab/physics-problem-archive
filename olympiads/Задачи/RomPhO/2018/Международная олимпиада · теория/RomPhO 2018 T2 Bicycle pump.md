---
id: rompho-2018-intl-theory-t2
olympiad: RomPhO
year: 2018
stage: "Международная олимпиада"
round: теория
grade: ""
number: "T2"
title: "Bicycle pump"
aliases: ["Bicycle pump"]
topics: ["[[2.2 Уравнение состояния идеального газа]]", "[[2.3 Работа газа]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: true
source_damaged: false
summary: "Найти давление и количество воздуха в велосипедной шине, зависимость давления в насосе от положения поршня и работу накачивания."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# Bicycle pump

**RomPhO 2018** · Международная олимпиада · теория · задача T2  
Источник: [[_pdf/RomPhO/RomPhO-2017-T2.pdf#page=1|условие, стр. 1–3]] · [[_pdf/RomPhO/RomPhO-2017-T2-solution.pdf#page=4|критерии, стр. 4]]

> [!info] Год
> Год исправлен: в архиве файл подписан 2017, и на шапке листов стоит «Romanian Master of Physics 2017», но RMPh 2017 — октябрьский тур 2017 года с другими задачами; этот комплект в архиве олимпиады числится как RMPh 2018.

Темы: [[2.2 Уравнение состояния идеального газа]], [[2.3 Работа газа]]

> [!abstract] Кратко (составлено моделью)
> Найти давление и количество воздуха в велосипедной шине, зависимость давления в насосе от положения поршня и работу накачивания.

**Problem II (10 points)**

A student is inflating one of his bike’s tires by using a bicycle pump which functions via a hand-operated piston. Before inflating it, the pressure inside the tire was the atmospheric pressure $p_0$ and the temperature was $T_0$. In order to be inflated, the tire is fitted with a valve which opens when the pressure just outside the valve is equal to the pressure within the tire. Assume that the volume of the tire, $V_r$ does not change as the tire is inflated.

![[rompho-2017-t2-problems-p1-f1.png]]

Each inflation cycle starts with the piston in the top position. Each time the piston is in its top position, the piston’s cylinder is filled with air at the atmospheric pressure $p_0$ and temperature $T_0$. When in the top position the volume of the air in pump is $V_p$, with $V_p=V_r/N$, where $N$ is a given number. When the piston is pushed to its bottom position all of the air that was within the cylinder is pushed in the tire. The distance by which the piston moves between its top and bottom positions is given by $\ell$.

Assume that the walls of the piston’s cylinder as well as the walls of the tire itself are perfectly diathermal (allows heat but not matter to pass across it) and that their temperature as well as that of the air inside is given by the atmospheric temperature $T_0$. Assume that the universal gas constant is known and is denoted by $R$.

**Task no. 1**

Task number 1 asks you to analyze some of the parameters of the entire system, and to write your results in terms of the thermodynamical parameters $p_0$, $V_r$, $T_0$, $R$, the number $N$, the number of pumping cycles $k$, and the distances $\ell$ and $x$.

**1.a.** Find the number of moles of air, $\nu_k$ that are within the tire after the student pumped air $k$ times using the pump with the hand operated piston.

**1.b.** Find the air pressure $p_k$ within the tire, after the student pumped air $k$ times.

**1.c.** During the $(k+1)$th pumping cycle, the valve opens when the piston is at the distance $x_{k+1}$ from the top position of the piston. Determine expression of $x_{k+1}$.

**1.d.** Find the pressure $p=p(x)$ of air within the pump’s cylinder, during the $(k+1)$th pumping cycle, as a function of the distance $x$ between the top position and the current position of the piston.

**1.e.** Plot the previously determined pressure, during the $(k+1)$th pumping cycle as a function of $x$.

**Task no. 2**

In task number 2 you are asked to find the work that the student needs to do in order to inflate the tire up to a given pressure. Write your results in terms of $N$, $k$ and $n$, the pressure $p_0$ and the volume $V_r$.

**2.a.** During the $k_0$th inflation cycle, the air pressure within the tire reaches the value $n\cdot p_0$, where $n>1$. Find the expression of $k_0$.

**2.b.** Find the work that the student needs to do between the moment when he starts pumping to the moment where the air pressure within the tire reaches $n\cdot p_0$. Assume that $N\cdot(n-1)$ is an integer and that the friction between the piston and the cylinder walls is negligible.

**Task no. 3**

In task number 3 you are asked to compute the numerical values for some of the quantities which you were previously determined in task number 1 or 2.

Assume the following numerical values for the physical constants and parameters that have been previously mentioned: $R=8.31\,J\cdot mol^{-1}\cdot K^{-1}$, $T_0=300\,K$, $V_r=7.00\,dm^3$, $N=20$, $p_0=1.01\cdot 10^5\,N\cdot m^{-2}$ and $n=2.51$.

**3.a.** Compute the number of air moles within the tire after 10 pumping cycles.

**3.b.** Compute the value of the air pressure within the tire after 10 pumping cycles.

**3.c.** Compute the number of cycles needed for the air pressure within the tire to reach the value $n\cdot p_0$.

**3.d.** Compute the value of the work that the student has to do during the 10th pumping cycle.

**Task no. 4**

For task number 4 you are asked to analyze the evolution of the air pressure in two different scenarios (I and II) which will be described below. The atmospheric pressure is once again given by $p_0=1.01\cdot 10^5\,N\cdot m^{-2}$, and the volume of the bicycle tire is $V_r=7.00\,dm^3$.

**I.** You will consider that the inflating of the bicycle tire at pressure $p=2.51\cdot p_0$ takes place at a temperature $T_0=300\,K$, on a rainy day, and that the saturated water vapor pressure is $p_{s,0}=3.30\cdot10^{-2}\cdot p_0$. Then, the inflated wheel is reinstalled to the bike and the bike is ride at a temperature $0.90\cdot T_0$. The saturated water vapor pressure at temperature $0.90\cdot T_0$ is $p_{s,1}=6.00\cdot10^{-3}\cdot p_0$.

**4.a.** Find the air pressure $p_1$ within the tire under the above set of circumstances.

**II.** For the second scenario, assume that the student is trying to inflate the tire up to the same pressure, $p=2.51\cdot p_0$, at the same temperature, $T_0=300\,K$, however, instead of inflating the tire with air he uses nitrogen. Furthermore, assume that the bicycle tire is kept in a large room which is also filled with nitrogen at temperature $T_0=300\,K$ and pressure $p_0=1.01\cdot10^5\,N\cdot m^{-2}$. The molar mass of nitrogen is given by $\mu_{azot}=28.0\,kg\cdot kmol^{-1}$. On the other hand, this tire has a small defect, a very small orifice, of area $S=0.01\,mm^2$.

Assume that the average speed for particles in a gas with molar mass $\mu$, at a temperature $T$ is given by $\bar v=\sqrt{\frac{8R\cdot T}{\pi\cdot\mu}}$. Consider that for the given scenario, the number of gas particles that collide unit surface area of the wall per unit time is given by, $N^*=\frac14 n^*\cdot\bar v$.

**4.b.** Determine the number of nitrogen molecules per unit time, $N_i$, which collide with the small orifice from the interior of the tire, and find the number of nitrogen molecules per unit time, $N_e$, which collide with the small orifice from the exterior of the tire.

**4.c.** Find that time that it takes for the nitrogen pressure within the tire to decrease from the initial value $p=2.51\cdot p_0$ to a final value $p_f=1.10\cdot p_0$.

© Problem written by:  
Prof. dr. Delia DAVIDESCU  
Conf. univ. dr. Adrian DAFINEI

> [!answer]- Ответ
> **1.a** — $\nu_k=\frac{p_0V_r}{RT_0}(1+\frac{k}{N})$
>
> **1.b** — $p_k=p_0\frac{N+k}{N}$
>
> **1.c** — $x_{k+1}=\ell\frac{k}{N+k}$
>
> **1.d** — $p(x)=\begin{cases}\frac{p_0}{1-x/\ell},&0\leq x\leq\frac{k\ell}{N+k}\\\frac{p_0(N+k+1)}{(N+1)-x/\ell},&\frac{k\ell}{N+k}<x\leq\ell\end{cases}$
>
> **2.a** — $k_0=N\cdot(n-1)$, if $N\cdot(n-1)$ is a natural number or $k_0=[N\cdot(n-1)]+1$, if $N\cdot(n-1)$ is not a natural number
>
> **2.b** — $L_{total}=\frac{p_0V_r}{N}\sum_{k=1}^{N(n-1)}[\ln\frac{N+k-1}{N}+(N+k)\ln\frac{N+k}{N+k-1}]$
>
> **3.a** — $\nu_{10}=0{,}43\,moli$
>
> **3.b** — $p_{10}=1{,}52\cdot10^5\,\frac{N}{m^2}$
>
> **3.c** — $k_0=31$
>
> **3.d** — $L_{10,total}\cong49{,}1J$
>
> **4.a** — $p_1=2{,}257\times10^5\,N\cdot m^{-2}$
>
> **4.c** — $t_f=\frac{4\cdot V_r}{\bar v\cdot S}\cdot\ln15{,}1$; $t_f=1{,}59\times10^4\,s$, $t_f\cong4{,}4\,ore$

> [!solution]- Решение (схема оценивания)
> Points are given for any correct solution
>
> Problem II — Bicycle pump
>
> | Nr. item | Task No. 1 | | Point |
> |---|---|---|---|
> | 1.a. | For: expression of number of moles of air, initially found in the tire at atmospheric pressure $p_0$ and at $T_0$: $\nu_{initial}=\frac{p_0V_r}{RT_0}$ | 0.20p | 0.80p |
> | | expression of number of moles of air pumped inside the tire at each pumping cycle: $\begin{cases}\nu_0=\frac{p_0V_p}{RT_0}\\\nu_0=\frac{p_0V_r}{RT_0N}\end{cases}$ | 0.20p | |
> | | expression of the number of moles of air, $\nu_k$ that are within the tire after the student pumped air $k$ times using the pump with the hand operated piston: $\nu_k=\nu_{initial}+k\nu_0$ | 0.20p | |
> | | $\nu_k=\frac{p_0V_r}{RT_0}(1+\frac{k}{N})$ | 0.20p | |
> | 1.b. | For: expression of the air pressure $p_k$ within the tire, after the student pumped air $k$ times: $p_kV_r=\nu_kRT_0$ | 0.20p | 0.40p |
> | | $p_k=p_0\frac{N+k}{N}$ | 0.20p | |
> | 1.c. | For: isothermal transformation law applied to the air found in the bicycle pump $p_0\frac{V_r}{N}=p_kS(\ell-x_{k+1})$ | 0.20p | 0.40p |
> | | $x_{k+1}=\ell\frac{k}{N+k}$ | 0.20p | |
> | 1.d. | For: $p_0\cdot\frac{V_r}{N}=p(x)\cdot\frac{V_r}{N\cdot\ell}\cdot(\ell-x)$, for $0\leq x\leq\frac{k\cdot\ell}{N+k}$ | 0.20p | 0.60p |
> | | $p(x)\cdot[V_r+(\ell-x)\cdot\frac{V_r}{N\cdot\ell}]=p_{k+1}\cdot V_r$, for $\frac{k\cdot\ell}{N+k}<x\leq\ell$ | 0.20p | |
> | | $p(x)=\begin{cases}\frac{p_0}{1-x/\ell},&0\leq x\leq\frac{k\ell}{N+k}\\\frac{p_0(N+k+1)}{(N+1)-x/\ell},&\frac{k\ell}{N+k}<x\leq\ell\end{cases}$ | 0.20p | |
> | 1.e. | For: $p'(x)=\begin{cases}\frac{p_0/\ell}{(1-x/\ell)^2},&0\leq x<\frac{k\ell}{N+k}\\\frac{p_0(N+k+1)/\ell}{[(N+1)-x/\ell]^2},&\frac{k\ell}{N+k}<x\leq\ell\end{cases}$ <br> Observation: First-order derivative of the function $p(x)$ is positive over the entire range of definition | 0.20p | 0.80p |
> | | $\begin{cases}p_s'(x_k)=\frac{p_0/\ell}{(1-\frac{k}{N+k})^2}=\frac{p_0(N+k)^2}{\ell N^2}\\p_d'(x_k)=\frac{p_0(N+k+1)/\ell}{[(N+1)-x/\ell]^2}=\frac{p_0(N+k)^2}{\ell N^2(N+k+1)}\end{cases}$ <br> Observation: Left and right of the point where the valve opens, the pressure shows an angular point. | 0.20p | |
> | | $p''(x)=\begin{cases}\frac{2p_0/\ell^2}{(1-x/\ell)^3},&0\leq x<\frac{k\ell}{N+k}\\\frac{2p_0(N+k+1)/\ell^2}{[(N+1)-x/\ell]^3},&\frac{k\ell}{N+k}<x\leq\ell\end{cases}$ <br> Observation: Second-order derivative is also positive on the whole range of definition. | 0.20p | |
> | | ![[rompho-2017-t2-solutions-p6-f1.png]] <br> Observation: Graphic representation refers to the 11-th pumping cycle for N = 20 | 0.20p | |
> | Nr. item | Task No. 2 | | Points |
> | 2.a. | For: $p_{k_0-1}<n\cdot p_0\leq p_{k_0}$ | 0.20p | 1.20p |
> | | $p_{k_0}=p_0\cdot\frac{N+k_0}{N}$ | 0.20p | |
> | | $k_0\geq N\cdot(n-1)$, $k_0$ number of pumping cycle is a natural number | 0.20p | |
> | | $k_0=N\cdot(n-1)$, if $N\cdot(n-1)$ is a natural number or $k_0=[N\cdot(n-1)]+1$, if $N\cdot(n-1)$ is not a natural number | 0.60p | |
> | 2.b. | For: find the work that the student needs to do on the $\nu_1$ mole of air, evolving isothermally from pressure $p_0$ to pressure $p_{k-1}$: $L_{K,I}=\nu_1\cdot R\cdot T_0\cdot\ln\frac{p_{k-1}}{p_0}$ | 0.20p | 1.20p |
> | | $L_{K,I}=\frac{p_0\cdot V_r}{N}\cdot\ln\frac{N+k-1}{N}$ | 0.20p | |
> | | expression of the work that the student needs to do on the $\nu_k$ mole of air, evolving isothermally from pressure $p_{k-1}$ to pressure $p_k$: $L_{K,II}=\nu_k\cdot R\cdot T_0\cdot\ln\frac{p_k}{p_{k-1}}$ | 0.20p | |
> | | $L_{K,II}=\frac{p_0\cdot V_r\cdot(N+k)}{N}\cdot\ln\frac{N+k}{N+k-1}$ | 0.20p | |
> | | expression of the total work that the student needs to do, during the $k$ pumping cycle: $\begin{cases}L_{K,total}=L_{K,I}+L_{K,II}\\L_{K,total}=\frac{p_0V_r}{N}\ln\frac{N+k-1}{N}+\frac{p_0V_r(N+k)}{N}\ln\frac{N+k}{N+k-1}\\L_{K,total}=\frac{p_0V_r}{N}[\ln\frac{N+k-1}{N}+(N+k)\ln\frac{N+k}{N+k-1}]\end{cases}$ | 0.20p | |
> | | expression of the total work that the student do from the moment he starts pumping till the moment when the pressure inside tire is $n\cdot p_0$: $L_{total}=\frac{p_0V_r}{N}\sum_{k=1}^{N(n-1)}[\ln\frac{N+k-1}{N}+(N+k)\ln\frac{N+k}{N+k-1}]$ | 0.20p | |
> | Nr. item | Task No. 3 | | Points |
> | 3.a. | For: number of air moles within the tire after $k=10$ pumping cycles $\nu_{10}=0{,}43\,moli$ | 0.20p | 0.20p |
> | 3.b. | For: value of the air pressure within the tire after 10 pumping cycles $p_{10}=1{,}52\cdot10^5\,\frac{N}{m^2}$ | 0.20p | 0.20p |
> | 3.c. | For: For number of cycles needed for the air pressure within the tire to reach the value $n\cdot p_0$: $\begin{cases}k_0=[20\cdot(2{,}51-1)]+1\\k_0=31\end{cases}$ | 0.20p | 0.20p |
> | 3.d. | For: value of the work that the student has to do during the 10th pumping cycle $\begin{cases}L_{10,total}=\frac{(1{,}01\cdot10^5\frac N{m^2})\cdot(7{,}00\cdot10^{-3}m^3)}{20}\cdot[\ln\frac{29}{20}+30\cdot\ln\frac{30}{29}]\\L_{10,total}\cong49{,}1J\end{cases}$ | 0.20p | 0.20p |
> | Nr. item | Task No. 4 | | Points |
> | 4.a. | For: expression of partial pressure $p_{aer}(T_0)$ of air inside the tire: $\begin{cases}p_{aer}(T_0)=p-p_{s,0}\\p_{aer}(T_0)=2{,}477\cdot p_0\end{cases}$ | 0.20p | 0.80p |
> | | $\begin{cases}p_{aer}(T_1)=p_{aer}(T_0)\cdot\frac{T_1}{T_0}\\p_{aer}(T_1)=2{,}229\cdot p_0\end{cases}$ | 0.20p | |
> | | $\begin{cases}p_1=p_{aer}(T_1)+p_{s,1}\\p_1=2{,}235\cdot p_0\end{cases}$ | 0.20p | |
> | | The value of the pressure inside the tire in specified conditions of use $p_1=2{,}257\times10^5\,N\cdot m^{-2}$ | 0.20p | |
> | 4.b. | For: expression of the concentration $n_e^*$ of nitrogen molecules in the room where the tire is kept: $\begin{cases}n_e^*=\frac{p_0}{T_0}\cdot\frac1{k_B}\\n_e^*=\frac{p_0}{T_0}\cdot\frac{N_A}{R}\end{cases}$ | 0.20p | 1.20p |
> | | expression of the concentration $n_i^*$ of nitrogen molecules in the tire: $\begin{cases}n_i^*=2{,}51\cdot\frac{p_0}{T_0}\cdot\frac{N_A}{R}\\n_i^*=2{,}51\cdot\frac{p_0}{T_0}\cdot\frac1{k_B}\end{cases}$ | 0.20p | |
> | | expression of the density of the flux of molecules $N_e^*$ coming from all directions, from outside the tire: $\begin{cases}N_e^*=\frac14\cdot n_e^*\cdot\bar v\\N_e^*=\frac14\cdot\frac{p_0}{T_0}\cdot\frac{N_A}{R}\cdot\sqrt{\frac{8R\cdot T_0}{\pi\cdot\mu_{azot}}}\end{cases}$ | 0.20p | |
> | | expression of the density of the flux of molecules $N_i^*$ coming from all directions, from inside the tire: $\begin{cases}N_i^*=2{,}51\cdot\frac14\cdot n_i^*\cdot\bar v\\N_i^*=2{,}51\cdot\frac14\cdot\frac{p_0}{T_0}\cdot\frac{N_A}{R}\cdot\sqrt{\frac{8R\cdot T_0}{\pi\cdot\mu_{azot}}}\end{cases}$ | 0.20p | |
> | | expression of the number $N_i$ of nitrogen molecules falling onto the surface of pinhole in unit of time coming from all directions, from inside the tire: $N_i=2{,}51\cdot\frac14\cdot\frac{p_0}{T_0}\cdot\frac{N_A}{R}\cdot S\cdot\sqrt{\frac{8R\cdot T_0}{\pi\cdot\mu_{azot}}}$; $N_i=2{,}51\cdot p_0\cdot N_A\cdot S\cdot\sqrt{\frac1{2\pi\cdot\mu_{azot}\cdot R\cdot T_0}}$ | 0.20p | |
> | | expression of the number $N_e$ of nitrogen molecules falling onto the surface of pinhole in unit of time coming from all directions, from outside the tire: $N_e=\frac14\cdot\frac{p_0}{T_0}\cdot\frac{N_A}{R}\cdot S\cdot\sqrt{\frac{8R\cdot T_0}{\pi\cdot\mu_{azot}}}$; $N_e=p_0\cdot N_A\cdot S\cdot\sqrt{\frac1{2\pi\cdot\mu_{azot}\cdot R\cdot T_0}}$ | 0.20p | |
> | 4.c. | For: expression of the number of nitrogen molecules falling onto the surface $S$ of the small orifice in time $dt$ coming from outside the tire: $\begin{cases}\aleph_e=S\cdot N_e^*\cdot dt\\\aleph_e=\frac14\cdot\frac{p_0}{T_0}\cdot\frac{N_A}{R}\cdot\bar v\cdot S\cdot dt\end{cases}$ | 0.20p | 1.80p |
> | | expression of the number of nitrogen molecules falling onto the surface $S$ of the small orifice in time $dt$ coming from inside the tire depends on pressure: $\begin{cases}\aleph_i=\frac14\cdot n^*(p)\cdot\bar v\cdot S\cdot dt\\\aleph_i=\frac14\cdot\frac p{T_0}\cdot\frac{N_A}{R}\cdot\bar v\cdot S\cdot dt\end{cases}$ | 0.20p | |
> | | number of molecules inside the tire $\aleph=\frac{p\cdot V_r}{R\cdot T_0}\cdot N_A$ | 0.20p | |
> | | expression of the variation of numbers of molecules inside the tire: $\begin{cases}d\aleph=\aleph(t+dt)-\aleph(t)\\d\aleph=\frac{V_r\cdot N_A}{R\cdot T_0}\cdot(p(t+dt)-p(t))\\d\aleph=\frac{V_r\cdot N_A}{R\cdot T_0}\cdot dp\end{cases}$ | 0.20p | |
> | | $d\aleph=\aleph_e-\aleph_i$ | 0.20p | |
> | | $\frac{V_r\cdot N_A}{R\cdot T_0}\cdot dp=\frac14\cdot\frac{p_0}{T_0}\cdot\frac{N_A}{R}\cdot\bar v\cdot S\cdot dt-\frac14\cdot\frac p{T_0}\cdot\frac{N_A}{R}\cdot\bar v\cdot S\cdot dt$ | 0.20p | |
> | | $\frac{dp}{p-p_0}=-\frac14\cdot\frac{\bar v\cdot S}{V_r}\cdot dt$ | 0.20p | |
> | | $\int_{2{,}51p_0}^{1{,}10p_0}\frac{dp}{p-p_0}=-\frac14\cdot\frac{\bar v\cdot S}{V_r}\cdot\int_0^{t_f}dt$; $t_f=\frac{4\cdot V_r}{\bar v\cdot S}\cdot\ln15{,}1$ | 0.20p | |
> | | $\begin{cases}t_f=1{,}59\times10^4\,s\\t_f\cong4{,}4\,ore\end{cases}$ | 0.20p | |
> | TOTAL Problem II | | | 10p |
>
> © Marking scheme written by:  
> Prof. dr. Delia DAVIDESCU  
> Conf. univ. dr. Adrian DAFINEI
