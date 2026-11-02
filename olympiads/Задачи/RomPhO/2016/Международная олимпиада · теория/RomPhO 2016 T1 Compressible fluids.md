---
id: rompho-2016-intl-theory-t1
olympiad: RomPhO
year: 2016
stage: "Международная олимпиада"
round: теория
grade: ""
number: "T1"
title: "Compressible fluids"
aliases: ["Compressible fluids"]
topics: ["[[2.5 Первое начало термодинамики]]", "[[2.2 Уравнение состояния идеального газа]]", "[[1 Механика]]"]
difficulty: 5
has_solution: false
has_hints: false
has_grading: false
source_damaged: false
summary: "Вывести уравнение Бернулли для адиабатического течения идеального газа и исследовать скорость возмущений, звука и зависимость параметров потока от числа Маха."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# Q1. Compressible fluids

**RomPhO 2016** · Международная олимпиада · теория · задача T1  
Источник: [[_pdf/RomPhO/RomPhO-2016-T1.pdf#page=1|условие, стр. 1–4]]

Темы: [[2.5 Первое начало термодинамики]], [[2.2 Уравнение состояния идеального газа]], [[1 Механика]]

> [!abstract] Кратко (составлено моделью)
> Вывести уравнение Бернулли для адиабатического течения идеального газа и исследовать скорость возмущений, звука и зависимость параметров потока от числа Маха.

The study of gases flow uncovers many interesting phenomena which have a myriad of applications, starting from boilers to airplanes and rockets. To simplify the calculations, in this problem the following assumptions will be adopted:

- The gas is ideal;
- The gas flow is steady and non-turbulent;
- The processes taking place in the flowing gas are adiabatic;
- The gas flow speed is much less than the speed of light;
- The gas flow is uniform and one-dimensional (axisymmetric);
- The effect of gravity is negligible.

The constants useful in this problem are:
- the molar mass of air, $\mu=29.0\,g/mol$;
- the ideal gas constant, $R=8.32\,J/(mol\cdot K)$.

**A. Bernoulli’s equation**

Bernoulli’s equation is the mathematical form of the law of conservation and transformation of energy for a flowing ideal gas. It bears the name of the Swiss physicist Daniel Bernoulli (1700 - 1782), who derived it in 1738. The easiest way to obtain this equation is to follow a fluid particle (a volume element of the fluid) in its way on a streamline.

**A** Perform the energy balance between two points in the flowing gas, knowing the parameters $(p_1,\rho_1,v_1)$ and $(p_2,\rho_2,v_2)$, and derive the equation that connects these variables. The adiabatic exponent $\gamma$ of the gas is also known. The parameter $p$ is the gas pressure, $\rho$ its density, and $v$ its speed. 1.5 p

**B. Propagation of a perturbation in a flowing gas**

If the pressure in a layer of a macroscopically motionless gas system suddenly increases (by heating or rapid compression), the layer will begin to expand, compressing the adjacent layers. This pressure disturbance will be thus transmitted by contiguity as an elastic wave through the gas.

**B1. Speed of the perturbation**

The speed $c$ of this wave is the speed of its wavefront (the most advanced surface, the points of which oscillate in phase and the thermodynamic parameters of which have the same value). If in the reference frame of the unperturbed gas the process of the wave propagation is nonsteady (the gas parameters in any point vary with time), in the reference frame of the wavefront the process will be steady, so the simple equations for a steady state can be applied.

**B1** Derive the mathematical expression for the speed $c$ of the wavefront, taking into account that the thermodynamic parameters of the unperturbed gas are $(p,\rho)$, while those “behind” the wavefront are $(p_1,\rho_1)=(p+\Delta p,\rho+\Delta\rho)$. 1.5 p

**B.2 Sound waves**

Sound waves are waves of weak disturbances ($\Delta p\ll p$ and $\Delta\rho\ll\rho$) that travel fast enough, their speed being of the order of hundreds of meters per second. Due to this, the gas compressions and rarefactions can be considered as adiabatic, the adiabatic exponent being $\gamma$.

**B2** Using the result from B1, obtain the mathematical expression for the sound speed in the gas and, using Bernoulli’s eq., derive the relation between the flow speed at a given point in the gas and the local sound speed. 0.5 p

**B.3 Mach’s number**

For classifying the speed performances of bodies in a fluid (e.g. aircrafts), as well as the flow regimes of fluids, the Swiss aeronautical engineer Jakob Ackeret (1898 – 1981) – one of the leading authorities in the 20th century aeronautics – proposed in 1929 that the ratio of the body or of the fluid’s speed $v$ and the local sound speed $c$ in that fluid to be called Mach’s number

$$M=\frac vc,$$

after the name of the great Czech (then in the Austrian empire) physicist and philosopher Ernst Mach (1838 – 1916). Primarily, the value of this non-dimensional quantity delimitates the incompressible from the compressible behavior of a flowing fluid, in aeronautics this limit being settled to $M=0.3$.

**B3.1** Find the relative variation of the gas density as a function of Mach’s number, when its motion is slowed down to a stop, its initial velocity being $v<c$, and calculate its maximum value for a flow to be considered incompressible. 0.5 p

**B3.2** The pressure at the nose of an aircraft in flight was found to be $1.92\cdot10^5\,Pa$ and the speed of air relative to the aircraft was zero at this point. The pressure and temperature of the undisturbed air were $1.01\cdot10^5\,Pa$ and $21.1^\circ C$ respectively. The adiabatic exponent for this temperature is $\gamma=1.40$. Find the speed and the Mach number of the aircraft. 0.5 p

**B3.3** When a gas is flowing through a pipe, it exerts a friction force on the fluid, which is not always negligible. If at the entrance of such a pipe the static pressure in the flowing fluid is $p_1=6.90\cdot10^5\,Pa$ and the Mach number is $M_1=0.700$, while at the exit $M_2=1.00$, find the expression and the numerical value of the force with which the fluid is acting on the pipe. The adiabatic exponent is $\gamma=1.40$, the constant cross section of the pipe is $S=9.29\cdot10^{-2}\,m^2$, and the relative increase of the gas temperature through the pipe is $5.00\cdot10^{-3}$. 1.0 p

**C. Shock waves**

There are two types of acoustic waves in a gas: sound waves and shock waves. The latter appear when a body moves in a gas with a supersonic speed (i.e. the relative speed of the body with respect to that of the gas is greater than the sound speed). At supersonic speeds, in front of the body appears a very thin layer of gas with a higher pressure, called compression shock. This kind of special acoustic waves were studied by Mach, so the envelope of such a wave is known as Mach’s cone, having the body in its apex. Passing through the compression shock, the thermodynamic parameters of the gas change abruptly. The Mach’s cone is an example of an oblique shock, but we are interested here mainly in normal shocks, for which the shock wavefront is perpendicular on the body or fluid velocity.

For shock waves the pressure/density differences between the two sides of the wavefront can reach very high values. Passing through the wavefront, the thermodynamic parameters vary abruptly, with a sudden jump. This is another reason for which a shock wavefront is called a pressure or a compression shock.

**C.1 The shock adiabat**

The gas compressed by the shock wave undergoes an irreversible adiabatic process which cannot be described by Poisson’s equation. However, an equation for the shock adiabat was deduced towards the end of the XIXth century by the Scottish physicist William Rankine (1820 – 1872) and, independently by him, by the French engineer Pierre Henri Hugoniot (1851 – 1887), using the mass and energy conservation, as well as the momentum equation. The Rankine – Hugoniot equation, or the shock adiabat, relates the pressure and the density of the gas compressed by a shock wave.

**C1** Denoting with $p_s$ and $\rho_s$ the gas pressure and density in front of the compression shock (which are known), and with $p_1$ and $\rho_1$ the same parameters behind the shock (which are unknown), show that the pressure ratio $p_1/p_s=y_1$ is related with the density ratio $\rho_1/\rho_s=x_1$ by a relation of the form

$$y_1=\frac{\alpha x_1-\beta}{\tau-\sigma x_1}.$$

Find the explicit form of the coefficients $\alpha$, $\beta$, $\tau$ and $\sigma$. The adiabatic exponent $\gamma$ of the gas is known.

Note: For simplicity, use a stream tube with a constant cross section, crossing perpendicularly the wavefront of the normal shock. 1.5 p

**C.2 A shockwave created by an explosion**

An explosion creates a spherically shockwave propagating radially into still air at $p_s=1.01\cdot10^5\,Pa$ and $t_s=20.0^\circ C$. A recording instrument registers a maximum pressure of $p_1=1.48\cdot10^6\,Pa$ as the shock wavefront passes by. The adiabatic coefficient of air for this compression shock is $\gamma=1.38$, the molar mass of air is $\mu=29.0\,g/mol$ and the ideal gas constant is $R=8.32\,J/(mol\cdot K)$.

**C2.1** Determine the air temperature increase $T_1/T_s$ under the action of the compression shock. 0.5 p

**C2.2** Determine the Mach’s number corresponding to the speed of the shockwave. 0.5 p

**C2.3** Determine the wind’s speed $v_1$ following the shock wavefront, with respect to a fixed observer. 0.5 p

During the compression shock the gas temperature and pressure sharply increase, much more than in a quasistatic adiabatic compression. After the shock, the gas expands adiabatically, but because the slope of the adiabatic process is smaller than that of the adiabatic shock, when the gas density reaches again the initial value, its pressure $p_2$ is still higher than that of the unperturbed gas, $p_s$.

**C2.4** Derive the ratios $p_2/p_s$ and $T_2/T_s$ at the end of the expansion process and calculate the numerical values of $p_2$ and $T_2$. 0.5 p

**C2.5** From this point the gas is cooling until it reaches the initial state. Assuming that for the entire cyclic process the adiabatic exponent has the same value, derive an expression for the entropy variation of the mass unit of air during the compression shock and calculate its numerical value. 1.0 p

© Assoc. Prof. Sebastian POPESCU, PhD
Faculty of Physics, Alexandru Ioan Cuza University of Iasi, ROMANIA
