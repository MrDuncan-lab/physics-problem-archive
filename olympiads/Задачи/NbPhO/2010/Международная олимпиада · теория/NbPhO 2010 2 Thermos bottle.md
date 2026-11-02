---
id: nbpho-2010-intl-theory-2
olympiad: NbPhO
year: 2010
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "2"
title: "Thermos bottle"
points: 6
aliases: ["Thermos bottle"]
topics: ["[[2.10 Насыщенный пар]]", "[[2.1 Уравнение теплового баланса. 8-ой класс]]", "[[6 Оптика]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Оценить тепловой поток излучения в сферическом термосе и время испарения жидкого азота."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 2. Thermos bottle (6 points)

**NbPhO 2010** · Международная олимпиада · теория · 10–12 класс · задача 2  
Источник: [[_pdf/NbPhO/nbpho-2010.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2010.pdf#page=3|решение, стр. 3]]

Темы: [[2.10 Насыщенный пар]], [[2.1 Уравнение теплового баланса. 8-ой класс]], [[6 Оптика]]

> [!abstract] Кратко (составлено моделью)
> Оценить тепловой поток излучения в сферическом термосе и время испарения жидкого азота.

In order to study the thermal properties of a thermos bottle, let us model it as two concentric spherical vessels, with radii $R_1=7\mathrm{cm}$ and $R_2=10\mathrm{cm}$. The gap between the walls of the vessels contains vacuum (hence, the heat conductivity can be neglected).

**i)** (3,5 pt) Find the radiative heat flux (i.e. transmitted heat per unit time) between the walls of the bottle, assuming that the ambient temperature is $T_2=293\mathrm{K}$ and the inner sphere is filled with liquid nitrogen at the boiling temperature $T_1=77\mathrm{K}$. The emissivities of all the surfaces are equal to that of stainless steel: $\varepsilon=0.1$. *Remark:* The emitted heat flux per unit area is given Stefan-Boltzmann’s law $P=\varepsilon\sigma T^4$, where $\sigma=5.67\times10^{-8}\mathrm{W/m^2K^4}$ (assuming that $\varepsilon$ is independent of the wavelength.

**ii)** (2,5 pt) Estimate, how long time does it take for a full evaporization of the liquid nitrogen (the vapor escapes through an over pressure valve). For the liquid nitrogen, density $\rho=810\mathrm{g/l}$ and latent heat for vaporization $\lambda=5.580\mathrm{kJ/mol})$. *NB! If you were unable to find $P$ (for question i), express the evaporization time symbolically (i.e. using the symbol $P$).*

> [!answer]- Ответ
> **i**
>
> $$
> P=Q_{di}-Q_{do}=\frac{\varepsilon\sigma4\pi R_1^2(T_2^4-T_1^4)}{1+(1-\varepsilon)R_1^2/R_2^2}\approx1.78\,\mathrm{W}.
> $$
>
> **ii**
>
> $$
> \tau=\frac43\pi\rho R^3\lambda\mu/P\approx36\,\mathrm{h}.
> $$

> [!solution]- Решение
> # Problem 2. Thermos bottle (6 points)
>
> **i.** (3.5 pts) *Remark: this problem technically rather challenging. Therefore, reasonable estimates like $P\approx\sigma\varepsilon S_1(T_2^4-T_1^4)\approx2.6\,\mathrm{W}$ or $P\approx\frac12\sigma\varepsilon S_1(T_2^4-T_1^4)\approx1.3\,\mathrm{W}$ will be graded by 2–2.5 pts.*
>
> The heat flux radiated from one wall is partially reflected back by other wall, which is also partially reflected back, etc. Besides, the flux from the outer wall can hit itself, if it misses the inner wall. So, near the surface of the outer wall, we can split the heat flux into inwards flux $Q_i$ and outwards flux $Q_o$. Then, upon designating the flux radiated by the outer wall by $Q=\varepsilon\sigma S_2T_2^4$, we have equalities
>
> $$Q_i=Q+Q_o(1-\varepsilon),$$
>
> i.e. the inward flux consists of (a) initial radiation, and of (b) the back-reflected part of the outwards flux. Similarly we have
>
> $$Q_o=Q_i\kappa(1-\varepsilon)+Q_i(1-\kappa)=Q_i(1-\kappa\varepsilon),$$
>
> i.e. the outward flux consists of (a) the part $\kappa$ of itself, which hits the inner wall and is reflected back, and of (b) the part $1-\kappa$ of itself, which misses the inner wall hence reaches again the outer wall as an outwards flux. Upon substituting $Q_o$ from the second equation into the first one, we obtain
>
> $$Q=Q_i[1-(1-\kappa\varepsilon)(1-\varepsilon)]=Q_i\varepsilon(1+\kappa-\kappa\varepsilon),$$
>
> hence $Q_i=Q/\varepsilon(1+\kappa-\varepsilon)$. From that inwards flux, the part which hits the inner wall is $\kappa$; in order to get the dissipated part, we need further to multiply the result by $\varepsilon$. So, the dissipated flux is
>
> $$Q_{di}=\varepsilon\sigma S_2T_2^4\kappa/(1+\kappa-\kappa\varepsilon).$$
>
> In order to obtain the flux $Q_{do}$, which is radiated from the inner wall and is dissipated in the outer wall, we proceed in the same way. Now, let $Q=\varepsilon\sigma S_1T_1^4$; then,
>
> $$Q_o=Q+Q_i(1-\kappa\varepsilon),$$
>
> and
>
> $$Q_i=Q_o(1-\varepsilon),$$
>
> so that $Q_o=Q/[\varepsilon(1+\kappa-\kappa\varepsilon)]$ and
>
> $$Q_{do}=\varepsilon\sigma S_1T_1^4/(1+\kappa-\kappa\varepsilon).$$
>
> Now, let us consider (an imaginary) situation, when $T_1=T_2$. This is thermal equilibrium, when the heat flux $Q_{do}$ given by the inner wall to the outer one must be equal to the flux $Q_{di}$, which is given by the outer wall to the inner one. Using our expressions we see that $\kappa S_2=S_1$, i.e. $\kappa=S_1/S_2$. Now we can finally write down the expression for the net flux given to the nitrogen,
>
> $$P=Q_{di}-Q_{do}=\frac{\varepsilon\sigma4\pi R_1^2(T_2^4-T_1^4)}{1+(1-\varepsilon)R_1^2/R_2^2}\approx1.78\,\mathrm{W}.$$
>
> **ii.** (2.5 pts) The net heat received by the inner wall is spent on evaporating the nitrogen, i.e. $\tau P=\lambda m$, where $m=\frac43\pi\rho R^3$. So,
>
> $$\tau=\frac43\pi\rho R^3\lambda\mu/P\approx36\,\mathrm{h}.$$
