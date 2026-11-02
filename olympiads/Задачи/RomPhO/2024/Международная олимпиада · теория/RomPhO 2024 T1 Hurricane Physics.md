---
id: rompho-2024-intl-theory-t1
olympiad: RomPhO
year: 2024
stage: "Международная олимпиада"
round: теория
grade: ""
number: "T1"
title: "Hurricane Physics"
aliases: ["Hurricane Physics"]
topics: ["[[1.3 Равноускоренное криволинейное движение]]", "[[1.6 Векторная кинематика]]", "[[1.18 Гидростатика]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Исследуется движение воздуха в урагане: поле скоростей, траектории частиц и действие силы Кориолиса."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# Q1: Hurricane Physics

**RomPhO 2024** · Международная олимпиада · теория · задача T1  
Источник: [[_pdf/RomPhO/RomPhO-2024-T1.pdf#page=1|условие, стр. 1–3]] · [[_pdf/RomPhO/RomPhO-2024-T1-solution.pdf#page=1|решение, стр. 1–7]]

Темы: [[1.3 Равноускоренное криволинейное движение]], [[1.6 Векторная кинематика]], [[1.18 Гидростатика]]

> [!abstract] Кратко (составлено моделью)
> Исследуется движение воздуха в урагане: поле скоростей, траектории частиц и действие силы Кориолиса.

A hurricane is a strong tropical storm having a low-pressure center (the eye of the hurricane) around which the air masses rotate with high speed. The general name for this type of extreme weather condition is that of cyclone. In the Western hemisphere it is called hurricane, while in Asia it is called typhoon. Regardless of the name, the hurricane forms above the warm sea water.

## Task 1: Hurricane Mechanics (4.40 points)

To understand more about the mechanics of air movement towards the hurricane’s eye, let us consider an idealized vortex – the cylindrical one. For simplicity, consider that the eye wall is cylindrical and vertical, taking its symmetry axis as the axis $Oz$ of a cylindrical coordinate system (having $\hat r$, $\hat\varphi$ and $\hat z$ as unit vectors). The air flows horizontally, towards the eye wall, so the velocity of any fluid particle outside the eye wall is $\vec v=\hat r v_r+\hat\varphi v_\varphi+\hat z0$ (see the adjacent figure).

![[rompho-2024-t1-problems-p1-f1.png]]

*Note:* In Fluid Mechanics, a fluid particle is a fluid volume, much smaller than the entire fluid volume to be considered as a particle and much bigger than a fluid molecule to encompass all the macroscopic properties of the fluid.

**1.a.** Determine a mathematical expression for the velocity of a fluid particle at a distance $r$ form the axis, in the outer region of the vortex. The fluid particle enters the outer region at a distance $r_0$ from the axis, with the radial speed $v_0$. In the outer region of the vortex the air flow is not rotational. **0.60 p**

Between the outer region and the eyewall there is an annulus (a cylindrical layer) in which the velocity of the fluid particle has an azimuthal component ($v_\varphi=\frac{C}{r}$), also keeping the same radial dependence of $v_r$, as in the outer region. $C$ is a positive, known constant.

**1.b.** Derive the equation for the fluid particle trajectory in the annulus. The transition of the fluid particle from the outer region to the annulus takes place at $r=r_1<r_0$. **1.70 p**

Usually, a difference in temperature in the atmosphere will produce a pressure difference, and the pressure force will move the atmospheric air, creating what we commonly call winds. We witness this air circulation from the Earth, which is a non-inertial reference frame due to its diurnal rotation (with an angular speed $\omega=7{,}29\cdot10^{-5}$ rad/s). In such a reference frame, to formally write Newton’s second law of motion, some inertia forces should be added to the ones resulting from interactions. Among them, the Coriolis force is of interest here. Its expression is $\vec F_{Cor}=-2m\vec\omega\times\vec v_{rel}$, where $\vec v_{rel}$ is the relative velocity of a body with respect to the non-inertial reference frame. Although the Earth’s angular speed is rather small, the value of the Coriolis force becomes noticeable as the speed of the body increases.

In the adjacent sketch you can see a crude representation of a low pression region, some isobars (the dashed curves) and a few arrows representing the wind directions. The representation does not consider the Earth rotation around its own axis. Imagine that this sketch describes a real situation somewhere in Romania (for simplicity, consider the North latitude as $\lambda=45^\circ$)

![[rompho-2024-t1-problems-p1-f2.png]]

**1.c.** Redraw the above sketch and on each arrow draw the direction of Coriolis force; as a result, redraw the air currents (arrows) affected by the Coriolis force. **0.50 p**

When the wind speed increases, its direction is more and more modified by the Coriolis force, until the fluid particles spiral around a closed loop where the Coriolis force has values comparable with the pressure force. This type of circular flow is observed in the annulus, close to the eyewall of the hurricane.

Consider a fluid particle with a small volume $\delta V$ at a distance $r$ from the eye axis, moving around it (the air density is $\rho=1.29$ kg/m$^3$) with constant speed.

**1.d.** Derive the equation of motion for the fluid particle, neglecting the viscosity of air, and obtain a mathematical expression for the wind speed as a function of the pressure gradient $\frac{\delta p}{\delta r}$, the distance $r$, air density $\rho$, the geographic latitude $\lambda$, and the angular speed of the Earth $\omega$. **1.30 p**

The table below gives the so-called Saffir-Simpson intensity scale for hurricanes.

| Category | Minimum central sea-level pressure/kPa | Maximum wind speed/(m/s) | Damage |
|---|---|---|---|
| 1 | $\geq 98.0$ | 33 – 42 | minimal |
| 2 | 97.9 – 96.5 | 43 – 49 | moderate |
| 3 | 96.4 – 94.5 | 50 – 59 | extensive |
| 4 | 94.4 – 92.0 | 60 – 69 | extreme |
| 5 | $<92.0$ | $\geq 70$ | catastrophic |

**1.e.** Calculate the minimal value of the air pressure gradient at 25 km from the center of the low-pressure region to qualify a wind as a hurricane. **0.30 p**

## Task 2: Hurricane Thermodynamics (5.60 points)

A hurricane path is not very difficult to forecast, but until recently, its intensity was. A new model, which is thermodynamical in nature, is able to offer accurate results¹. In essence, a hurricane operates as a heat engine, transforming a part of the heat absorbed at the ocean surface to mechanical energy of the hurricane wind. The succession of steps can be, briefly, outlined as follows:

![[rompho-2024-t1-problems-p2-f3.png]]

1. As the air currents (wind) spiral towards the eye of the hurricane, they absorb heat from the ocean’s surface (water from the surface of the ocean vaporizes and is carried by the wind together with its latent heat of evaporation); the segment A – B is essentially an isothermal process at the temperature $T_1\cong300$ K.
2. Reaching the eye wall, the moist air will rise quickly up to about 17 km (segment B – C).
3. A short, isothermal segment (C – D) during which the wind transfers heat to the outer space and the air dries up (the temperature is $T_2\cong200$ K).
4. The dry air quickly descends towards the ocean surface (segment D – A).

¹ The author of the thermodynamic model is dr. Kerry Emanuel, from MIT.

**2.a.** Using the above information, determine the maximum rate of energy transferred from the ocean to the kinetic energy of the wind, considering that the absorbed heat rate from the ocean surface is $\frac{dQ_1}{dt}>0$. **0.80 p**

In a hurricane, the mechanical energy of the wind is converted into heat due to wind friction, almost all of it at the ocean surface. This heat, in turn, contributes to the rate at which heat is absorbed by the wind at the ocean surface.

The entire air circulation takes place inside a cylindrical volume, having the hurricane eye axis as its symmetry axis, the height of 17 km, and the radius of its circular base $R=100$ km.

**2.b.** If $dQ_{10}/dt$ is the rate at which the heat is released from the ocean’s surface by evaporation, write an expression for $\frac{dQ_{10}}{dt}$, relating it to the given temperatures, the air density, and the wind speed. Any non-dimensional proportionality coefficient being of the order of unity, should be taken as equal to one. **1.60 p**

Let us denote by $h$ the specific enthalpy (the enthalpy per mass unit) of the inflowing dry air (at constant pressure, the enthalpy variation is the heat exchanged by the system with its environment) and with $h^*$ the specific enthalpy of the wet air immediately above the ocean surface (the latent heat of evaporation is, in fact, the evaporation enthalpy).

**2.c.** Derive a mathematical expression for $\frac{dQ_{10}}{dt}$, relating it to the given specific enthalpies. Any non-dimensional proportionality coefficient being of the order of unity, should be taken as equal to one. **1.20 p**

Under stationary conditions (constant local pressure and temperature in any given point on the surface of the ocean’s water), the specific enthalpy of water vapors at $0\ {}^\circ$C is $h_{w0}=2437$ kJ/kg, and the specific heat of water is $c_{p,w}=4.18\ \frac{\mathrm{kJ}}{\mathrm{kgK}}$. The air above the water surface is saturated with water vapors. The molar mass of air is $M_a=28.97$ g/mol, saturated vapor pressure of water at 300 K is $p_s=3.561$ kPa and the atmospheric pressure is 101.3 kPa. The water vapors can be considered an ideal gas.

**2.d.** Assuming that both expressions derived for $\frac{dQ_{10}}{dt}$ are valid for any value of the radius $R$ greater than the radius of the eye, derive an expression for the maximum wind speed and calculate its numerical value. **2.00 p**

Proposed by  
Assoc. Prof. Sebastian POPESCU, PhD  
Faculty of Physics, Alexandru Ioan Cuza University of Iasi, ROMANIA

> [!answer]- Ответ
> **1.a**
>
> $$
> \vec v = -\hat r\frac{v_0r_0}{r},
> $$
>
> **1.b**
>
> $$
> r=r_1e^{-\frac{v_0r_0}{C}\varphi},
> $$
>
> **1.d**
>
> $$
> \frac{v^2}{r}=\frac{1}{\rho}\frac{\delta p}{\delta r}-2\omega v\sin\lambda.
> $$
>
> **1.d**
>
> $$
> v=r\omega\sin\lambda\left(\sqrt{1+\frac{\frac{\delta p}{\delta r}}{\rho\omega^2r\sin^2\lambda}}-1\right).
> $$
>
> **1.e**
>
> $$
> \frac{\delta p}{\delta r}=5{,}62\cdot10^{-2}\frac{\mathrm{Pa}}{\mathrm m}+4{,}39\cdot10^{-3}\frac{\mathrm{Pa}}{\mathrm m}=6{,}06\cdot10^{-2}\frac{\mathrm{Pa}}{\mathrm m}\cong6{,}1\cdot10^{-2}\frac{\mathrm{Pa}}{\mathrm m}.
> $$
>
> **2.a**
>
> $$
> \frac{dW}{dt}\leq\left(1-\frac{T_2}{T_1}\right)\frac{dQ_1}{dt}.
> $$
>
> **2.b**
>
> $$
> \frac{dQ_{10}}{dt}\geq2\pi\frac{T_2}{T_1-T_2}\int_0^R\rho v^3r\,dr.
> $$
>
> **2.c**
>
> $$
> \frac{dQ_{10}}{dt}=2\pi\int_0^R\rho(h^*-h)v\,r\,dr.
> $$
>
> **2.d**
>
> $$
> v_{max}=\sqrt{\frac{T_1-T_2}{T_2}(h^*-h)}=170\,\frac{\mathrm m}{\mathrm s}.
> $$

> [!solution]- Решение
> **1.a. Solution:**
>
> Using a cylindrical surface with an arbitrary height $h$, the continuity equation is
>
> (0.4 p)
> $$v_r\cdot 2\pi rh = v_0\cdot 2\pi r_0h,$$
> so
>
> (0.1 p)
> $$v_r = \frac{v_0r_0}{r},$$
> Or, vectorially
>
> (0.1 p)
>
> $$\vec v = -\hat r\frac{v_0r_0}{r},$$
> because $v_\varphi = 0$ everywhere in the outer region, the flow being irrotational.
>
> **1.b. Solution:**
>
> Since the velocity of the fluid particle is tangent to the trajectory and taking an elementary displacement $d\vec s$, then
>
> (0.3 p)
> $$\vec v\times d\vec s = \vec 0.$$
> Because
>
> (0.3 p)
> $$d\vec s = \hat r\,dr+\hat\varphi r\,d\varphi,$$
> Then the above vectorial equation becomes
>
> (0.2 p)
> $$\hat z\left(-v_0r_0d\varphi-C\frac{dr}{r}\right)=\vec 0.$$
> This gives
>
> (0.3 p)
> $$d(v_0r_0\varphi+C\ln r)=0,$$
> or
>
> (0.2 p)
> $$v_0r_0\varphi+C\ln r=C_1.$$
> By choosing $\varphi=0$ when $r=r_1$ (0.1 p), the integration constant is
>
> (0.1 p)
> $$C_1=C\ln r_1.$$
> As a result,
>
> (0.2 p)
>
> $$r=r_1e^{-\frac{v_0r_0}{C}\varphi},$$
> meaning that the trajectory is a logarithmic spiral in the annulus.
>
> **1.c. Solution:**
>
> (0.3+0.2)
>
> ![[rompho-2024-t1-solutions-p2-c3883.png]]
>
> **1.d. Solution:**
>
> For a fluid particle with the mass
>
> (0.1+0.1)
> $$\delta m=\rho\delta V=\rho A\delta r,$$
>
> (0.3)
> ![[rompho-2024-t1-solutions-p3-c4534.png]]
>
> lex secunda has the form:
>
> (0.3 p)
> $$(p+\delta p)A=pA+2\delta m\omega v\sin\lambda+\delta m\frac{v^2}{r},$$
> or
>
> (0.2 p)
>
> $$\frac{v^2}{r}=\frac{1}{\rho}\frac{\delta p}{\delta r}-2\omega v\sin\lambda.$$
> Rearranging the eq. of motion
>
> (0.1 p)
> $$v^2+2(r\omega\sin\lambda)v-\frac{r}{\rho}\frac{\delta p}{\delta r}=0,$$
> its solution is
>
> (0.2 p)
>
> $$v=r\omega\sin\lambda\left(\sqrt{1+\frac{\frac{\delta p}{\delta r}}{\rho\omega^2r\sin^2\lambda}}-1\right).$$
>
> **1.e. Solution:**
>
> From the eq. of motion, it follows that
>
> (0.2 p)
> $$\frac{\delta p}{\delta r}=\frac{\rho v^2}{r}+2\rho\omega v\sin\lambda.$$
> With $v=33\,\frac{\mathrm m}{\mathrm s}$, the pressure gradient value is
>
> (0.1 p)
>
> $$\frac{\delta p}{\delta r}=5{,}62\cdot10^{-2}\frac{\mathrm{Pa}}{\mathrm m}+4{,}39\cdot10^{-3}\frac{\mathrm{Pa}}{\mathrm m}=6{,}06\cdot10^{-2}\frac{\mathrm{Pa}}{\mathrm m}\cong6{,}1\cdot10^{-2}\frac{\mathrm{Pa}}{\mathrm m}.$$
>
> **2.a. Solution:**
>
> 1. The segment A – B: isothermal process (at $T_1\cong300\,\mathrm K$) during which the wind absorbs heat from the ocean with the rate $\frac{dQ_1}{dt}$.
> 2. The segment B – C: essentially an adiabatic process, being a fast one (the wind speed is the highest at the eye wall of the hurricane). Since the pressure decreases with altitude, the air expands adiabatically and cools down.
> 3. The segment C – D: isothermal process (at $T_2\cong200\,\mathrm K$) As the moist air’s temperature dropped, the water vapors in it condense as rain, releasing the enthalpy of vaporization (latent heat), most of which being radiated into outer space. The rate of the released heat is $\frac{|dQ_2|}{dt}$.
> 4. The segment D – A: adiabatic compression of dry air.
>
> During the cycle, a part of the enthalpy absorbed from the ocean is converted into mechanical energy of the hurricane wind, with the rate $\frac{dW}{dt}$. Thus, according to the First Law of Thermodynamics,
>
> (0.3 p)
> $$\frac{dQ_1}{dt}=\frac{dW}{dt}+\frac{|dQ_2|}{dt}.$$
> From Carnot’s theorem:
>
> (0.3 p)
> $$\frac{|dQ_2|}{T_2}\geq\frac{dQ_1}{T_1},$$
> so
>
> (0.2 p)
>
> $$\frac{dW}{dt}\leq\left(1-\frac{T_2}{T_1}\right)\frac{dQ_1}{dt}.$$
>
> **2.b. Solution:**
>
> According to the information given in the text:
>
> (0.2 p)
> $$\frac{dQ_1}{dt}=\frac{dW}{dt}+\frac{dQ_{10}}{dt},$$
> so
>
> (0.2 p)
> $$\frac{dQ_{10}}{dt}\geq\frac{T_2}{T_1-T_2}\frac{dW}{dt}.$$
> Since
>
> (0.2 p)
> $$\frac{dW}{dt}=F_rv$$
> and
>
> (0.4+0.1)
> $$\delta F_r=C_1\cdot\delta S\cdot\frac{\rho v^2}{2}\cong\rho v^2\delta S.$$
> [Alternatively, at the ocean surface, the wind loses its vertical component of the velocity, which means that
>
> (0.1+0.1+0.1)
> $$F_r=\left|\frac{dm(0-v)}{dt}\right|=\left(\frac{dm}{dt}\right)v,$$
> while
>
> (0.1+0.1)
> $$\delta\left(\frac{dm}{dt}\right)=\rho\delta\left(\frac{dV}{dt}\right)=\rho v\cdot\delta S].$$
> As a result
>
> (0.2+0.1)
> $$\frac{dW}{dt}=\int_S\rho v^3dS=2\pi\int_0^R\rho v^3r\,dr$$
> and
>
> (0.2 p)
>
> $$\frac{dQ_{10}}{dt}\geq2\pi\frac{T_2}{T_1-T_2}\int_0^R\rho v^3r\,dr.$$
>
> *Note: From the above reasoning we obtain $dQ_{10}/dt=|dQ_2|/dt$, which implies that the heat of vaporization absorbed by the hurricane wind at the ocean surface is released at higher altitudes where the water condenses. This heat is radiated out of Earth’s atmosphere. Thus, the vaporization and condensation of water vapor is a mechanism that transfers heat from the oceans to higher altitudes where it is released into the outer space. Otherwise, the heat would be transferred back to the wind, making it extremely strong!*
>
> **2.c. Solution:**
>
> According to the information in the text
>
> (0.2 p)
> $$\delta Q_{10}=(h^*-h)\delta m,$$
> where
>
> (0.1 p)
> $$\delta m=\rho\delta V$$
> and
>
> (0.2+0.2+0.2+0.1)
> $$\delta V=\delta A\delta z=2\pi r\delta r\cdot C_2v\delta t\cong2\pi r\delta r\cdot v\delta t.$$
> So,
>
> (0.2 p)
>
> $$\frac{dQ_{10}}{dt}=2\pi\int_0^R\rho(h^*-h)v\,r\,dr.$$
>
> **2.d. Solution:**
>
> From both expressions found for $\frac{dQ_{10}}{dt}$, it follows that
>
> (0.2 p)
> $$2\pi\int_0^R\rho\left[(h^*-h)-\frac{T_2}{T_1-T_2}v^2\right]v\,r\,dr\geq0,$$
> or
>
> (0.2 p)
> $$v\leq\sqrt{\frac{T_1-T_2}{T_2}(h^*-h)}=v_{max}.$$
> If $h$ is the specific enthalpy for dry air and $h^*_w$ that for water vapors, then, the specific enthalpy for the humid air is
>
> (0.2 p)
> $$h^*=h+xh^*_w,$$
> so
>
> (0.1 p)
> $$h^*-h=xh^*_w,$$
>
> where $x$ (kg/kg) is the humidity ratio, i.e. the ratio of the mass of water vapors present in wet air to the mass of dry air, present in the same volume of wet air:
>
> (0.2+0.2+0.2+0.1 p)
> $$x=\frac{m_w}{m_a}=\frac{M_w\frac{p_sV}{RT}}{M_a\frac{(p-p_s)V}{RT}}=\frac{M_w}{M_a}\frac{p_s}{p-p_s}$$
> and
>
> (0.2 p)
> $$h^*_w=h_{w0}+c_{p,w}(T_1-T_0).$$
> Numerically,
>
> (0.1 p)
> $$x=\frac{18\,\frac{\mathrm g}{\mathrm{mol}}}{28.97\,\frac{\mathrm g}{\mathrm{mol}}}\times\frac{3.561\,\mathrm{kPa}}{101.3\,\mathrm{kPa}-3.561\,\mathrm{kPa}}=22.64\,\frac{\mathrm g}{\mathrm{kg}}$$
> and
>
> (0.1 p)
> $$h^*_w=2437\,\frac{\mathrm{kJ}}{\mathrm{kg}}+4.18\,\frac{\mathrm{kJ}}{\mathrm{kgK}}\times27\,\mathrm K=2550\,\frac{\mathrm{kJ}}{\mathrm{kg}},$$
> such that
>
> (0.1 p)
> $$h^*-h=57.73\,\frac{\mathrm{kJ}}{\mathrm{kg}}.$$
> As a result,
>
> (0.1 p)
>
> $$v_{max}=\sqrt{\frac{T_1-T_2}{T_2}(h^*-h)}=170\,\frac{\mathrm m}{\mathrm s}.$$
>
> Proposed by
>
> **Assoc. Prof. Sebastian POPESCU, PhD**
>
> Faculty of Physics, Alexandru Ioan Cuza University of Iasi, ROMANIA
