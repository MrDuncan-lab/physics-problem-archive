---
id: rompho-2021-intl-theory-t3
olympiad: RomPhO
year: 2021
stage: "Международная олимпиада"
round: теория
grade: ""
number: "T3"
title: "Water world"
aliases: ["Water world"]
topics: ["[[2.11 Поверхностное натяжение]]", "[[1.18 Гидростатика]]", "[[3.6 Проводники]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: true
source_damaged: false
summary: "Исследовать форму и отрыв капель воды с учётом поверхностного натяжения, гидростатического давления и электрического заряда."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# Water world

**RomPhO 2021** · Международная олимпиада · теория · задача T3  
Источник: [[_pdf/RomPhO/RomPhO-2021-T3.pdf#page=1|условие, стр. 1–3]] · [[_pdf/RomPhO/RomPhO-2021-T3-solution.pdf#page=4|критерии, стр. 4]]

Темы: [[2.11 Поверхностное натяжение]], [[1.18 Гидростатика]], [[3.6 Проводники]]

> [!abstract] Кратко (составлено моделью)
> Исследовать форму и отрыв капель воды с учётом поверхностного натяжения, гидростатического давления и электрического заряда.

All the situations studied in the problem take place in an enclosure thermostated at where there is air and saturated water vapor. The pressure in the enclosure is constant and has value $p_0=1{,}0\times10^5\,N\cdot m^{-2}$.

Write all the numerical results obtained using **two** significant digits.

In solving the problem, you can use the following physical constants:

$$g=9{,}8\,m\cdot s^{-2}$$
$$\mu_0=4\pi\times10^{-7}\,H\cdot m^{-1}$$
$$\varepsilon_0=8{,}9\times10^{-12}\,F\cdot m^{-1}$$

as well as the following data on the physical properties of water.

**Data Table**

| | |
|---|---|
| Density | $\rho=1{,}0\times10^3\,kg\cdot m^{-3}$ |
| Saturated vapor pressure at 70 °C | $p_s=3{,}1\times10^4\,N\cdot m^{-2}$ |
| Surface tension coefficient at 70 °C | $\sigma=6{,}5\times10^{-2}\,N\cdot m^{-1}$ |
| Magnetic susceptibility ($\chi=\mu_r-1$) | $\chi=-9{,}0\times10^{-6}$ |

**Part A. Falling droplets**

For the first, part of the problem, you will study the falling with a constant speed of water droplets. An ultra-fast, enlarged, photograph shows that the falling water droplet remains approximately spherical, retains its symmetry of rotation around the vertical axis but undergoes a slight elongation along this axis, reaching a length $2h=2{,}0\times10^{-3}\,m$ (measured by along the axis of vertical symmetry). At the ends of the longitudinal axis of symmetry of the droplet, the radii of curvature of its surface are respectively $R_1=h-\delta$ and $R_2=h+\delta$ with $\delta=7{,}5\times10^{-5}\,m$.

**A.1.** Using the data obtained from the ultrafast photo and physical quantities indicated in the statement, determines the value of $\sigma$ - the surface tension coefficient of water. (0.5p)

**Part B. Stalagmometer**

A stalagmometer is a device used for investigating the surface tension of liquids. The device is a glass tube whose middle section is widened. The lower end of the tube is narrowed and continues with a metallic capillary tube (like a needle), to force the fluid to fall out of the tube as a droplet. The fluid flows slowly from the tube in a vertical direction. Denote with $R$ the radius of the drop hanging below the nozzle, which grows slowly in time until the drop separates from the nozzle due to the gravitation. When the droplet separates from the tube, the liquid surface forms in the vicinity of the nozzle a “neck”, which has vertical tangent.

![[rompho-2021-t3-problems-p1-f1.png]]

There is water in a vertically positioned stalagmometer. The metal capillary has an inside diameter $d=1{,}0\times10^{-4}\,m$ and negligible wall thickness. The level difference between the upper surface of the water in the stalagmometer and the lower end of the capillary is constant and equal to $H=5{,}0\times10^{-2}\,m$. In the calculations, use the value of the surface tension that you obtained in the previous part of the problem. If you did not solve the previous part, use the value indicated in the data table.

**B.1.** Determine the expression of radius $R$ of the spherical droplet that detaches from the end of the capillary tube, neglecting the contribution due to the hydrostatic pressure of the water in the stalagmometer tube. Calculate the value of radius $R$. (0.5p)

**B.2.** Determine the expression of radius $R_H$ of the spherical drop that detaches from the end of the capillary tube, considering the contribution due to the hydrostatic pressure of the water in the stalagmometer. Calculate the value of radius $R_H$. (0.5p)

**Part C. Electrically charged droplets**

The metallic capillary of the stalagmometer described in part B is put in contact with an electric source and acquires the increasing electric potential $\phi$. The water in the stalagmometer is electrically conductive.

**C.1.** Determine the expression of the pressure $p_\varepsilon$, determined by the electrostatic charge, inside the spherical water drop having the radius $R$ at the end of the tube, as a function of the electric potential $\phi$. Neglects the electrostatic interaction between the drop and the rest of the system. (2.0p)

When the increasing electrostatic potential of the tube reaches the value $\phi_{max}$ for which the pressure determined by the surface tension is equal in the module of the electrostatic pressure, the water drop having the radius $R$ breaks and its content is sprayed.

**C.2.** Determine the expression $\phi_{max}$ of the potential of the metal tube for which the water droplet is sprayed. Express the result as a function of $R,\sigma$ and physical constants. Calculate the numerical value of this potential for the water droplet having radius $R=1{,}0\times10^{-3}\,m$. (1.0p)

Assume that when spraying the water droplet separates into $n=64$ identical spherical droplets.

**C.3.** Determine the expression of $p_\pi$ - the pressure leading to the spherical shape of the droplets formed by spraying. Express the result as a function of $R,\sigma$ and physical constants. Calculate the numerical value of the pressure $p_\pi$. (1.0p)

**Part D. Water in magnetic field**

Water is a diamagnetic substance. Its introduction into a magnetic field leads to the appearance of magnetic dipoles that are equivalent to magnets having the opposite polarity to that of the applied magnetic field. As a result, when in an inhomogeneous magnetic field, water tends to leave the place with a more intense magnetic field.

A region of the vacuum is situated in the magnetic field with induction $\vec B$. The density of energy in that region has the value $w_0$. When there is water in that region, the density of energy is $w_w$.

**D.1.** Write the expression $\Delta w=w_w-w_0$ for the difference in energy densities as a function of $\vec B$, $\mu_0$, $\mu_r$. (0.3p)

The water in a glass vessel is subjected to the action of a non-uniform magnetic field with a vertical direction. The point $M$ is on the same vertical as the point $N$, below it. The induction of the magnetic field has the modulus $|\vec B|$ at the point $M$ and the modulus 0 at the point $N$. Imagine that a small volume of water $v$ is moved from point $M$ to point $N$ and then brought back from point $N$ to point $M$.

**D.2.** Comparing the magnetic potential energy for the initial and final states of the water volume $v$ determines the expression of the pressure difference (due to the existence of the inhomogeneous magnetic field) between the points $N$ and $M$. (1.5p)

A vertical graduated cylinder of glass (a mensure) $\mathbb V$ with length $\mathbb L=4{,}0\times10^{-1}\,m$ is filled in three quarters with water. A solenoid is wound on its lower half. The solenoid generates inside it a uniformly vertical magnetic field having the induction modulus $B=K\cdot I$. In expression $I$ is the intensity of the electric current flowing through the solenoid and $K=5{,}0\times10^{-2}\,T\cdot A^{-1}$ is a constant of device. It assumes that due to the scattering of field lines the magnetic field outside the solenoid is negligible.

**D.3.** Determine the expression of intensity of the electrical current through the solenoid so that the water in the vessel $\mathbb V$ would start to boil. Calculate the value of this intensity of the electrical current (1.5p)

**Part E. Rising bubbles**

The gas bubbles that appear during boiling rise to the free surface of the water. Consider that there are only water-saturated vapors in the bubbles and that the radius of a bubble remains constant as it rises. Consider a vapor bubble with a constant radius $R_{bubble}=1{,}0\times10^{-3}\,m$, which rises on the distance $h_0=1{,}0\cdot10^{-1}\,m$, with a constant speed $v_{bubble}$.

**E.1.** Determine the expression of the mechanical work $L_{bubble}$ done by the vapor bubble on the water in the vessel $\mathbb V$, during its lifting. Express the result as function of $R_{bubble}$, $h_0$ and $v_{bubble}$. (0.4p)

**E.2.** Determine the value of time interval $t_{up}$, in which the bubble reaches the free surface of the water in the vessel $\mathbb V$. (0.8p)

> [!answer]- Ответ
> **A.1** — $\sigma\cong\frac{\rho\cdot g\cdot h^3}{2\delta}$; $\sigma=6.5\times10^{-2}\,N\cdot m^{-1}$
>
> **B.1** — $R=\sqrt[3]{\frac{3\cdot d\cdot\sigma}{4\cdot g\cdot\rho}}$; $R=7.9\times10^{-4}\,m$
>
> **B.2** — $R_H=R\cdot\sqrt[3]{1-\frac{d\cdot H\cdot\rho\cdot g}{4\sigma}}$; $R_H=7.4\times10^{-4}\,m$
>
> **C.1** — $p_\varepsilon=\frac{\varepsilon_0\cdot\phi^2}{2R^2}$
>
> **C.2** — $\phi_{max}=2\cdot\sqrt{\frac{\sigma\cdot R}{\varepsilon_0}}$; $\phi_{max}=5.4\times10^3\,V$
>
> **C.3** — $p_\pi=\frac{2\sigma}{R}\cdot(n^{1/3}-n^{-2/3})$; $p_\pi=5.1\times10^2\,N\cdot m^{-2}$
>
> **D.1** — $\Delta w=w_w-w_0=\frac{B^2}{2\mu_0}\cdot\left(\frac1{\mu_r}-1\right)$
>
> **D.2** — $p_N-p_M=\frac{B^2}{2\mu_0}\cdot\left(\frac1{\mu_r}-1\right)$
>
> **D.3** — $I=\sqrt{-\frac{2\mu_0\cdot(1+\chi)\cdot(p_0-p_s)}{K^2\cdot\chi}}$; $I=2.7\times10^3\,A$
>
> **E.1** — $L_{bubble}=\pi\cdot R_{bubble}^2\cdot h_0\cdot\rho\cdot\frac{v_{bubble}^2}{2}$
>
> **E.2** — $t_{up}=\frac{h_0}{\sqrt{\frac{8g\cdot R_{bubble}}3}}$; $t_{up}=6.2\times10^{-1}\,s$

> [!solution]- Решение (схема оценивания)
> Any other solution that leads to correct results will be scored accordingly.
>
> Theoretical Problem nr. 3 - Water world
>
> | A. | Part A. Falling droplets | | Points |
> |---|---|---|---|
> | **A.1.** | $p_{up}+p_{hidro}=p_{down}$; $\sigma=\frac{\rho\cdot g\cdot h\cdot(h^2-\delta^2)}{2\delta}$; $\sigma\cong\frac{\rho\cdot g\cdot h^3}{2\delta}$ | 0.3p | 0.5p |
> | | $\sigma=6.5\times10^{-2}\,N\cdot m^{-1}$ | 0.2p | |
> | B. | Part B. Stalagmometer | | Points |
> | **B.1.** | $G=F_\sigma$; $R=\sqrt[3]{\frac{3\cdot d\cdot\sigma}{4\cdot g\cdot\rho}}$ | 0.3p | 0.5p |
> | | $R=7.9\times10^{-4}\,m$ | 0.2p | |
> | **B.2.** | $G+F_H=F_\sigma$; $\begin{cases}R_H=\sqrt[3]{\frac34\left(\frac{d\cdot\sigma}{\rho\cdot g}-\frac{d^2\cdot H}{4}\right)}\\R_H=R\cdot\sqrt[3]{1-\frac{d\cdot H\cdot\rho\cdot g}{4\sigma}}\end{cases}$ | 0.3p | 0.5p |
> | | $R_H=7.4\times10^{-4}\,m$ | 0.2p | |
> | C. | Part C. Electrically charged droplets | | Points |
> | **C.1** | The variation of the volume of the conductive drop, if its radius increases with the infinitely small amount $\Delta R$: $\Delta V=\frac{4\pi}{3}\cdot[(R+\Delta R)^3-R^3]\cong4\pi\cdot R^2\cdot\Delta R$ | 0.3p | 2.0p |
> | | Variation of the capacitance of the spherical capacitor represented by the drop: $\Delta C=4\pi\cdot\varepsilon_0\cdot\Delta R$ | 0.3p | |
> | | The variation of the electrostatic energy, accumulated in the drop at the constant potential: $\Delta W_\varepsilon=2\pi\cdot\varepsilon_0\cdot\phi^2\cdot\Delta R$ | 0.4p | |
> | | Mechanical work $L_\varepsilon$ of electrostatic pressure $p_\varepsilon$, when increasing the volume with $\Delta V$: $\begin{cases}L_\varepsilon=p_\varepsilon\cdot\Delta V\\L_\varepsilon=p_\varepsilon\cdot4\pi\cdot R^2\cdot\Delta R\end{cases}$ | 0.4p | |
> | | $\Delta W_\varepsilon=L_\varepsilon$ | 0.3p | |
> | | $p_\varepsilon=\frac{\varepsilon_0\cdot\phi^2}{2R^2}$ | 0.3p | |
> | **C.2.** | The expression of the pressure exerted towards the outside of the drop, just before the moment of its spraying: $p_\varepsilon=\frac{\varepsilon_0\cdot\phi_{max}^2}{2R^2}$ | 0.2p | 1.0p |
> | | The expression of the pressure exerted towards the inside of the drop $p_\sigma=\frac{2\sigma}{R}$ | 0.2p | |
> | | $p_\sigma=p_\varepsilon$ | 0.2p | |
> | | $\phi_{max}=2\cdot\sqrt{\frac{\sigma\cdot R}{\varepsilon_0}}$ | 0.2p | |
> | | $\phi_{max}=5.4\times10^3\,V$ | 0.2p | |
> | **C.3.** | The pressure due to the surface tension in each of the n small drops: $p_{\sigma\pi}=\frac{2\sigma}{r}$; $p_{\sigma\pi}=\frac{2\sigma}{R}\cdot\sqrt[3]{n}$ | 0.2p | 1.0p |
> | | The electrostatic potential of each small drop $\frac Rn\cdot\phi_{max}=r\cdot\phi_\pi$; $\phi_\pi=\frac1{\sqrt[3]{n^2}}\cdot2\cdot\sqrt{\frac{\sigma\cdot R}{\varepsilon_0}}$; $\phi_\pi=2\cdot\sigma^{1/2}\cdot\varepsilon_0^{-1/2}\cdot R^{1/2}\cdot n^{-2/3}$ | 0.2p | |
> | | The outward pressure determined by the electric charges on each small drop: $p_{\varepsilon\pi}=\frac{\varepsilon_0\cdot\phi_\pi^2}{2r^2}$; $p_{\varepsilon\pi}=\frac{2\sigma}{R}\cdot n^{-2/3}$ | 0.2p | |
> | | Expression of the pressure leading to the spherical shape of the droplets resulting from the spray: $p_\pi=\frac{2\sigma}{R}\cdot(n^{1/3}-n^{-2/3})$ | 0.2p | |
> | | $p_\pi=5.1\times10^2\,N\cdot m^{-2}$ | 0.2p | |
> | D. | Part D. Water in magnetic field | | Points |
> | **D.1.** | $\Delta w=w_w-w_0=\frac{B^2}{2\mu_0}\cdot\left(\frac1{\mu_r}-1\right)$ | 0.3p | 0.3p |
> | **D.2.** | $\Delta W=v\cdot\frac{B^2}{2\mu_0}\cdot\left(\frac1{\mu_r}-1\right)$ | 0.4p | 1.5p |
> | | $L=v\cdot(p_N-p_M)$ | 0.4p | |
> | | $v\cdot(p_N-p_M)=v\cdot\frac{B^2}{2\mu_0}\cdot\left(\frac1{\mu_r}-1\right)$ | 0.5p | |
> | | $p_N-p_M=\frac{B^2}{2\mu_0}\cdot\left(\frac1{\mu_r}-1\right)$ | 0.2p | |
> | **D.3.** | $p_N=p_0+\rho\cdot g\cdot\frac{\mathbb L}{4}\cong p_0$ | 0.3p | 1.5p |
> | | $p_M=p_0-\frac{B^2}{2\mu_0}\cdot\left(\frac1{\mu_r}-1\right)$ | 0.4p | |
> | | $p_M=p_s$; $p_s=p_s(70^\circ C)$ | 0.3p | |
> | | $I=\sqrt{-\frac{2\mu_0\cdot(1+\chi)\cdot(p_0-p_s)}{K^2\cdot\chi}}$ | 0.3p | |
> | | $I=2.7\times10^3\,A$ | 0.2p | |
> | E. | Part E. Rising bubbles | | Points |
> | **E.1.** | $L_{bubble}=\pi\cdot R_{bubble}^2\cdot h_0\cdot\rho\cdot\frac{v_{bubble}^2}{2}$ | 0.4p | 0.4p |
> | **E.2.** | $F_{asc}=\frac{4\pi}{3}\cdot R_{bubble}^3\cdot g\cdot\rho$ Note: the weight of the vapor is negligible; $F_{dis}=\pi\cdot R_{bubble}^2\cdot\rho\cdot\frac{v_{bubble}^2}{2}$ | 0.2p | 0.8p |
> | | $\vec F_{asc}+\vec F_{dis}=0$; $v_{bubble}=\sqrt{\frac{8g\cdot R_{bubble}}3}$ | 0.2p | |
> | | $t_{up}=\frac{h_0}{\sqrt{\frac{8g\cdot R_{bubble}}3}}$ | 0.2p | |
> | | $t_{up}=6.2\times10^{-1}\,s$ | 0.2p | |
> | | Total points | | 10p |
