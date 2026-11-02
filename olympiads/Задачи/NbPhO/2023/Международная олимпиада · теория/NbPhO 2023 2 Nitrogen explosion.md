---
id: nbpho-2023-intl-theory-2
olympiad: NbPhO
year: 2023
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "2"
title: "Nitrogen explosion"
points: 8
authors: ["Päivo Simson"]
aliases: ["Nitrogen explosion"]
topics: ["[[1.18 Гидростатика]]", "[[1.15 Упругость. Весомая пружина]]", "[[2.10 Насыщенный пар]]", "[[2.1 Уравнение теплового баланса. 8-ой класс]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: true
source_damaged: false
summary: "Оценить давление и время взрыва плавающей сферы с жидким азотом при нагревании."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 2. Nitrogen explosion (8 points) — Päivo Simson.

**NbPhO 2023** · Международная олимпиада · теория · 10–12 класс · задача 2  
Источник: [[_pdf/NbPhO/nbpho-2023.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2023.pdf#page=4|решение, стр. 4–5]]

Темы: [[1.18 Гидростатика]], [[1.15 Упругость. Весомая пружина]], [[2.10 Насыщенный пар]], [[2.1 Уравнение теплового баланса. 8-ой класс]]

> [!abstract] Кратко (составлено моделью)
> Оценить давление и время взрыва плавающей сферы с жидким азотом при нагревании.

A half-sphere of radius $r=0.1\,\mathrm m$ is filled with liquid nitrogen at the boiling point temperature of $T_1=77.4\,\mathrm K$ ($-195.8\,{}^\circ\mathrm C$). The other half is then firmly sealed onto the first, creating a sphere containing liquid nitrogen and nitrogen gas, each occupying one-half of the volume. The sphere is immediately thrown into $T_w=20\,{}^\circ\mathrm C$ temperature water, where it floats exactly as shown in the figure below. After some time, it explodes.

![[nbpho-2023-p1-f3.svg]]

The sphere is made of PCTFE plastic of density $\rho_p=2130\,\mathrm{kg\,m^{-3}}$, maximum tensile strength $\sigma=3.4\times10^7\,\mathrm{N\,m^{-2}}$ (above this stress, the plastic will break) and thermal conductivity $k=0.84\,\mathrm{W\,m^{-1}\,K^{-1}}$. For liquid nitrogen, under the conditions considered here, the latent heat of vaporization is $\lambda=2.0\times10^5\,\mathrm{J\,kg^{-1}}$, specific heat $c_v=2000\,\mathrm{J\,kg^{-1}\,K^{-1}}$ and density $\rho_n=808\,\mathrm{kg\,m^{-3}}$. Molar mass $\mathrm M(\mathrm N_2)=28\,\mathrm{g\,mol^{-1}}$. The ideal gas constant $R=8.31\,\mathrm{J\,K^{-1}\,mol^{-1}}$. Temperature dependence of saturated vapor pressure of nitrogen is shown below.

![[nbpho-2023-p1-f5.svg]]

**i)** (1.5 points) What is the wall thickness $d$ of the sphere?

**ii)** (1.5 points) What is the pressure $p_2$ inside the sphere right before it explodes? The outside pressure is $p_a=1.0\times10^5\,\mathrm{Pa}$.

**iii)** (1.5 points) What is the temperature $T_2$ of liquid nitrogen right before the explosion?

**iv)** (1.5 points) Calculate the mass of nitrogen that evaporates inside the sphere before the explosion.

**v)** (2 points) Estimate the time it will take for the sphere to explode. The heat capacity of the plastic and the heat flux through the upper half of the sphere can be neglected.

> [!answer]- Ответ
> **i**
>
> $$
> d=\frac r6\cdot\frac{\rho_w-\rho_n}{\rho_p}=1.5\,\mathrm{mm}.
> $$
>
> **ii**
>
> $$
> p_2=p_a+\frac{2\sigma d}{r}=1.1\cdot10^6\,\mathrm{Pa}.
> $$
>
> **iii**
>
> $$
> p_2=1.1\cdot10^6\,\mathrm{Pa}\quad\Longrightarrow\quad T_2=106\,\mathrm K.
> $$
>
> **iv**
>
> $$
> \Delta m=m_2-m_1=\frac{2\pi r^3M}{3R}\left(\frac{p_2}{T_2}-\frac{p_1}{T_1}\right)=0.065\,\mathrm{kg}.
> $$
>
> **v**
>
> $$
> \Delta t=\frac{d\cdot(Q_e+Q_l)}{2\pi r^2k\,(T_w-T_n)}=15.5\,\mathrm s.
> $$

> [!solution]- Решение
> # 2. Nitrogen explosion (8 points)
>
> — Solution by Päivo Simson, grading schemes by Päivo Simson and ....
>
> **i)** (1.5 points) As shown in the first figure of the problem, the sphere floats so that exactly half of it is submerged in water. When studying buoyancy, the mass of nitrogen gas can be considered negligibly small compared to the masses of liquid nitrogen and the plastic sphere. According to Archimedes’ principle, we have
>
> $$\rho_nV_n+\rho_pV_p=\rho_wV_w,$$
>
> where $V_n$, $V_p$, and $V_w$ are the volumes of liquid nitrogen, plastic, and displaced water, respectively. We have
>
> $$\frac12\cdot\frac{4\pi r^3\rho_n}{3}+d\cdot4\pi r^2\rho_p=\frac12\cdot\frac{4\pi r^3\rho_w}{3},$$
>
> and solving for $d$ we get
>
> $$d=\frac r6\cdot\frac{\rho_w-\rho_n}{\rho_p}=1.5\,\mathrm{mm}.$$
>
> **ii)** (1.5 points) The sphere will explode when the pressure difference $p_2-p_a$ is such that the maximum tensile strength of the plastic is reached. Let’s look at only one-half of the sphere and study the balance of the forces.
>
> ![[nbpho-2023-p4-f1.svg]]
>
> The resultant force due to pressure is $(p_2-p_a)\pi r^2$. This must always be balanced by the elastic forces in the plastic. Right before the explosion, we have the equality
>
> $$(p_2-p_a)\pi r^2=\sigma2\pi rd,$$
>
> where $2\pi rd$ is the cross-sectional area of the plastic. Now solving for $p_2$ we get
>
> $$p_2=p_a+\frac{2\sigma d}{r}=1.1\cdot10^6\,\mathrm{Pa}.$$
>
> **iii)** (1.5 points) During boiling at constant pressure, the temperature of the liquid does not change, even though the liquid is gaining energy all the time. If however the pressure changes, as we have in our problem, then so does the boiling point, following exactly the phase transition line on the phase diagram. Since we know the final pressure $p_2$, we can simply read the corresponding temperature of the diagram:
>
> $$p_2=1.1\cdot10^6\,\mathrm{Pa}\quad\Longrightarrow\quad T_2=106\,\mathrm K.$$
>
> **iv)** (1.5 points) If $p$, $V$, and $T$ are known, the mass of the nitrogen gas can be calculated using the ideal gas equation:
>
> $$pV=\frac mM RT\quad\Longrightarrow\quad m=\frac{pVM}{RT}.$$
>
> Since we know the initial and final states, the mass $\Delta m$ of nitrogen that evaporated between these states is
>
> $$\Delta m=m_2-m_1=\frac{2\pi r^3M}{3R}\left(\frac{p_2}{T_2}-\frac{p_1}{T_1}\right)=0.065\,\mathrm{kg}.$$
>
> **v)** (2 points) Neglecting the heat capacity of the plastic and the heat flux through the upper half of the sphere, we only need to consider the heat of evaporation:
>
> $$Q_e=\lambda\Delta m=1{,}31\cdot10^4\,\mathrm J,$$
>
> and the heat for raising the temperature of the liquid nitrogen:
>
> $$Q_l=c_vm_l(T_2-T_1)=\frac23\pi r^3\rho_nc_v(T_2-T_1)=9{,}7\cdot10^4\,\mathrm J.$$
>
> The heat for rising the temperature of the nitrogen gas can be neglected, as the mass of the gas is very small compared to the mass of liquid nitrogen ($\approx1.7\,\mathrm{kg}$). The total heat $Q_e+Q_l$ is taken from the water through the plastic. The average temperature of nitrogen is $T_n=(T_1+T_2)/2=91.7\,\mathrm K$, and the average temperature difference between water and nitrogen is $T_w-T_n=201.5\,\mathrm K$. The heat flux through the plastic is
>
> $$q=k\cdot\frac{T_w-T_n}{d}.$$
>
> The total amount of heat carried through the lower half of the sphere during time $\Delta t$ is
>
> $$\Delta Q=qA\Delta t=Q_e+Q_l,$$
>
> where $A=2\pi r^2$ is half of the surface area of the sphere. Finally, solving for $\Delta t$, we have the estimated time it takes for the sphere to explode:
>
> $$\Delta t=\frac{d\cdot(Q_e+Q_l)}{2\pi r^2k\,(T_w-T_n)}=15.5\,\mathrm s.$$

> [!grading]- Критерии оценивания
> Grading:
>
> | Criterion | Points |
> |---|---|
> | Archimedes’ principle | 0.3 pts |
> | Correct volumes of liquid nitrogen, plastic, and displaced water | 0.6 pts |
> | Correctly solving for $d$ | 0.3 pts |
> | Correct answer $d=1.5\,\mathrm{mm}$ | 0.3 pts |
>
> **ii)**
>
> Grading:
>
> | Criterion | Points |
> |---|---|
> | Qualitative understanding of the conditions for the sphere to explode - resultant pressure force equals the total tensile strength | 0.4 pts |
> | The idea of breaking the sphere in half and analysing the forces acting on only one side of the sphere | 0.4 pts |
> | Correct condition for the sphere to explode: $(p_2-p_a)\pi r^2=\sigma2\pi rd$ | 0.4 pts |
> | Correct final expression and answer | 0.3 pts |
>
> **iii)**
>
> Grading:
>
> | Criterion | Points |
> |---|---|
> | Correctly stating that the process $1-2$ follows the phase transition line. | 1.0 pts |
> | Reading the correct temperature from the graph | 0.5 pts |
>
> **iv)**
>
> Grading:
>
> | Criterion | Points |
> |---|---|
> | The idea of calculating the mass of nitrogen gas in the initial and final state | 0.3 pts |
> | Realizing that ideal gas law can be used to calculate the mass of nitrogen gas | 0.3 pts |
> | Correct ideal gas law | 0.3 pts |
> | Correctly using the molar mass | 0.3 pts |
> | Correct calculation and correct final answer | 0.3 pts |
>
> **v)**
>
> Grading:
>
> | Criterion | Points |
> |---|---|
> | Understanding that $Q_e+Q_l$ must be equal to the total heat received from the water | 0.3 pts |
> | Correct heat of evaporation | 0.2 pts |
> | Correct heat for rising the temperature of liquid nitrogen | 0.2 pts |
> | Correctly using the average temperature of nitrogen | 0.2 pts |
> | Correctly using the average temperature difference | 0.2 pts |
> | Correct expression for the heat flux $q$ though the plastic | 0.3 pts |
> | Correct expression for the total heat $\Delta Q$ received through the plastic | 0.3 pts |
> | Correct final expression for calculating the time till explosion | 0.3 pts |
>
> Give full points for this part if the final expression and the answer are correct.
