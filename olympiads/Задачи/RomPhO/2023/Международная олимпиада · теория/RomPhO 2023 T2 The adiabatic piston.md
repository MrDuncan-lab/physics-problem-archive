---
id: rompho-2023-intl-theory-t2
olympiad: RomPhO
year: 2023
stage: "Международная олимпиада"
round: теория
grade: ""
number: "T2"
title: "The adiabatic piston"
aliases: ["The adiabatic piston"]
topics: ["[[2.2 Уравнение состояния идеального газа]]", "[[2.5 Первое начало термодинамики]]", "[[2.12 Молекулярно-кинетическая теория]]", "[[1.20 Колебания]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Исследовать состояние идеального газа и движение адиабатического поршня при малых возмущениях, включая затухание и изменение энтропии."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# Theoretical problem 2: The adiabatic piston

**RomPhO 2023** · Международная олимпиада · теория · задача T2  
Источник: [[_pdf/RomPhO/RomPhO-2023-T2.pdf#page=1|условие, стр. 1–2]] · [[_pdf/RomPhO/RomPhO-2023-T2-solutions.pdf#page=1|решение, стр. 1–9]]

Темы: [[2.2 Уравнение состояния идеального газа]], [[2.5 Первое начало термодинамики]], [[2.12 Молекулярно-кинетическая теория]], [[1.20 Колебания]]

> [!abstract] Кратко (составлено моделью)
> Исследовать состояние идеального газа и движение адиабатического поршня при малых возмущениях, включая затухание и изменение энтропии.

A vertical cylinder with adiabatic walls contains argon, considered as an ideal gas (the molar mass of argon is $\mu=40$ g/mol). The gas is contained in the cylinder with the help of an adiabatic piston, the mass of which is $m=0.64$ kg. The cross-section area of the piston is $A=80$ cm$^2$. The piston can move without friction inside the cylinder and does not let the gas escape. The air surrounding the cylinder – piston system is evacuated. Initially, the gas temperature is $T_i=293$ K and the height at which the piston is in static equilibrium, measured as the height of the gas column in the cylinder, is $y_i=1.0$ m. The gravitational acceleration is $g=9.81$ m/s$^2$ and the universal constant of ideal gases is $R=8.315$ J mol$^{-1}$ K$^{-1}$.

## A. Gas parameters in the initial state [0.8 points]

**A** Derive the mathematical expressions and calculate the numerical values for the gas pressure in the initial equilibrium state and for the mass of argon in the cylinder. **0.8 points**

## B. Very small perturbations [2.3 points]

The purpose of this problem is to find out what happens with the gas and the piston after perturbing the piston. To do this, the piston is suddenly pushed, such that its initial speed $u_i$ is so much smaller than the thermal speed $v_{T_i}$ of the gas in the initial state that their ratio can be neglected.

**B1** Derive the mathematical dependence of the gas temperature $T$ of $y$. **0.4 points**

**B2** Derive the equation describing the position of the piston, with respect to the bottom of the cylinder, as a function of time, $y(t)$. **1.6 points**

**B3** Calculate the entropy variation of the gas in this process. **0.3 points**

## C. Small perturbations [6.9 points]

The speed $u$ of the piston is at least one order of magnitude higher than in the previous part of the problem, but still much smaller than the thermal speed of the gas. Due to the smallness of the piston’s speed, there is no turbulence inside the gas. Furthermore, it is found that the pressure is not the same everywhere in the gas volume. When the piston moves upwards, for example, a rarefaction thin layer will appear immediately under the piston. To make a simple model, we will divide the gas volume in two hydrodynamic regions:

- the rarefaction thin layer, situated immediately under the piston, having the following properties:
  - its volume ($\delta V$) is negligible when compared to the entire gas volume;
  - the pressure is uniform in the layer, but slightly smaller than in the rest of the gas;
  - the temperature is the same as in the rest of the gas;
- the rest of the gas in which the pressure and the temperature are those of equilibrium.

During the piston movement, its interaction with the gas, mediated by the hydrodynamic layer beneath it, has a macroscopic effect: the appearance of a drag force acting on the piston. In this way the mechanical energy of the piston is degraded into thermal energy and the piston will eventually stop moving.

**C1** Derive the expression for the final position of the piston ($y_f$), measured with respect to the bottom of the cylinder, as well as for the final temperature of the gas ($T_f$). Calculate their numerical values considering $u_i=5.0$ m/s. **1.6 points**

**C2** Evaluate the variation of entropy in this process $\Delta S$ and calculate its numerical value. **0.8 points**

The strong inequality $u\ll v_T$ means that the integer powers greater than one of the ratio $u/v_T$ can be neglected.

**C3** Evaluate the actual pressure $p^*$ in the gas layer beneath the piston during its movement upwards. **1.6 points**

An exact analysis of the gas and the piston dynamics involves the simultaneous solution of two coupled nonlinear differential equations, a task possible only with the help of a computer. However, the problem can be solved analytically in the asymptotic approximation, that is by analyzing the final stage of the piston movement, when $y=y_f+z$, $z\ll y_f$. The physical significance of $y$ and $y_f$ are those from above. Also, in the final stage of the dynamics, $\frac{mu^2}{m_{Ar}v_{T_f}^2}$ can be neglected because $u\ll u_i$, even if initially, $u_i\lesssim\sqrt{\frac{m_{Ar}}m}v_{T_i}$.

**C4** Prove that, in the final stage, the movement of the piston is an oscillatory one with damping. Derive the mathematical expression and calculate the numerical value of these oscillations’ pseudoperiod. **2.4 points**

**C5** How long does it take for the piston to stop moving? For this evaluation, express the relaxation time for the piston’s oscillations and calculate the numerical value of damped oscillations lifetime, $\tau_{tot}$, knowing that it is considered to be five times the relaxation time. Also, calculate the number $N$ of oscillations effectuated by the piston in this time. **0.5 points**

**Notes:**

1. For an ideal gas, the mean values for the gas speed $v$, respectively $v^2$, in the direction of the piston velocity, are

$$
\langle v\rangle=\sqrt{\frac{2RT}{\pi\mu}},\quad\text{respectively }\langle v^2\rangle=\frac{RT}{\mu}.
$$

2. If needed, the following approximation formula can be used:

$$
(1+x)^n\cong1+nx,\quad\text{if }|x|\ll1.
$$

problem proposed by  
Assoc. Prof. Sebastian POPESCU, PhD  
Faculty of Physics, Alexandru Ioan Cuza University of Iasi, Romania

> [!answer]- Ответ
> **A**
>
> $$
> p_i=\frac{mg}{A},\qquad [0.2\ \mathrm p]
> $$
>
> **A**
>
> $$
> p_i=785\ \mathrm{Pa}\cong7.9\cdot10^2\ \mathrm{Pa}.\qquad [0.1\ \mathrm p]
> $$
>
> **A**
>
> $$
> m_{Ar}=\frac{mgy_i\mu}{RT_i},\qquad [0.1\ \mathrm p]
> $$
>
> **A**
>
> $$
> m_{Ar}=1{,}03\cdot10^{-4}\ \mathrm{kg}\cong1{,}0\cdot10^{-4}\ \mathrm{kg}.\qquad [0.1\ \mathrm p]
> $$
>
> **B1**
>
> $$
> T=T_i\left(\frac{y_i}{y}\right)^{2/3},\qquad [0.1\ \mathrm p]
> $$
>
> **B2**
>
> $$
> y=y_i\left[1+\frac{u_i}{\sqrt{\gamma gy_i}}\sin\left(\sqrt{\frac{\gamma g}{y_i}}t\right)\right].\qquad [0.1\ \mathrm p]
> $$
>
> **B3**
>
> $$
> \Delta S=0.\qquad [0.3\ \mathrm p]
> $$
>
> **C1**
>
> $$
> y_f=y_i\left[1+\frac{u_i^2}{5gy_i}\right].\qquad [0.1\ \mathrm p]
> $$
>
> **C1**
>
> $$
> y_f=1.51\ \mathrm m\cong1.5\ \mathrm m.\qquad [0.1\ \mathrm p]
> $$
>
> **C1**
>
> $$
> T_f=T_i\left[1+\frac{u_i^2}{5gy_i}\right].\qquad [0.1\ \mathrm p]
> $$
>
> **C1**
>
> $$
> T_f=442\ \mathrm K\cong440\ \mathrm K.\qquad [0.1\ \mathrm p]
> $$
>
> **C2**
>
> $$
> \Delta S=\frac52\frac{mgy_i}{T_i}\ln\left[1+\frac{u_i^2}{5gy_i}\right].\qquad [0.1\ \mathrm p]
> $$
>
> **C2**
>
> $$
> \Delta S=2.2\cdot10^{-2}\ \mathrm{J/K}.\qquad [0.1\ \mathrm p]
> $$
>
> **C3**
>
> $$
> p^*=p\left(1-2u\sqrt{\frac{2\mu}{\pi RT}}\right)=p\left(1-2\sqrt{\frac6\pi}\frac{u}{v_T}\right).\qquad [0.1\ \mathrm p]
> $$
>
> **C4**
>
> $$
> T'_1=2\pi\sqrt{\frac{y_f}{g\left(\gamma-\frac{2m_{Ar}}{\pi m}\right)}},\qquad [0.2\ \mathrm p]
> $$
>
> **C4**
>
> $$
> T'_1=1.91\ \mathrm s\cong1.9\ \mathrm s.\qquad [0.1\ \mathrm p]
> $$
>
> **C5**
>
> $$
> \tau=\frac1\delta=\sqrt{\frac{\pi my_f}{2m_{Ar}g}},\qquad [0.2\ \mathrm p]
> $$
>
> **C5**
>
> $$
> \tau_{tot}=5\tau=194\ \mathrm s\cong190\ \mathrm s.\qquad [0.1\ \mathrm p]
> $$
>
> **C5**
>
> $$
> N=\frac{\tau_{tot}}{T'_1}=101\cong100.\qquad [2\times0.1\ \mathrm p]
> $$

> [!solution]- Решение
> **A. Solution:** The initial pressure of the gas is
>
> $$p_i=\frac{mg}{A},\qquad [0.2\ \mathrm p]$$
> having the numerical value
>
> $$p_i=785\ \mathrm{Pa}\cong7.9\cdot10^2\ \mathrm{Pa}.\qquad [0.1\ \mathrm p]$$
> The amount of substance, according to Clapeyron-Mendeleev eq., has the expression
> $$m_{Ar}=\frac{p_iV_i\mu}{RT_i}.\qquad [0.2\ \mathrm p]$$
> Since
> $$V_i=Ay_i,\qquad [0.1\ \mathrm p]$$
> then
>
> $$m_{Ar}=\frac{mgy_i\mu}{RT_i},\qquad [0.1\ \mathrm p]$$
> having the numerical value
>
> $$m_{Ar}=1{,}03\cdot10^{-4}\ \mathrm{kg}\cong1{,}0\cdot10^{-4}\ \mathrm{kg}.\qquad [0.1\ \mathrm p]$$
>
> **B1. Solution:**
>
> Let’s suppose, for fixing the ideas, that the piston moves upwards. The piston moves so slowly that the gas expansion is quasistatic, so each state the gas passes through is an equilibrium state. For the quasistatic adiabatic expansion, the Poisson equation is valid:
> $$T_iV_i^{\gamma-1}=TV^{\gamma-1},\qquad [0.2\ \mathrm p]$$
> or
> $$T_iy_i^{\gamma-1}=Ty^{\gamma-1}.\qquad [0.1\ \mathrm p]$$
> Hence
>
> $$T=T_i\left(\frac{y_i}{y}\right)^{2/3},\qquad [0.1\ \mathrm p]$$
> because the argon is a monoatomic gas ($\gamma=5/3$).
>
> **Note:** To prove that the gas obeys the Poisson law under the adopted assumption, let’s write the eq. of motion for the piston and the 1st law of thermodynamics:
> $$m\frac{du}{dt}=pA-mg=\frac{pV}{y}-mg=\frac{nRT}{y}-mg\tag{*}$$
> and
> $$\frac m2(u^2-u_i^2)+nC_V(T-T_i)=-mg(y-y_i),$$
> which, differentiated, gives
> $$mudu+\frac{1}{\gamma-1}nR\,dT=-mg\,dy,$$
> or
> $$m\frac{du}{dt}=-\frac{1}{\gamma-1}nR\frac{dT}{dy}-mg.\tag{**}$$
> From (*) and (**), it follows that
> $$\frac{nRT}{y}+\frac{1}{\gamma-1}nR\frac{dT}{dy}=0,$$
> or
> $$(\gamma-1)\frac{dy}{y}+\frac{dT}{T}=0,$$
> which, by integration, gives
> $$Ty^{\gamma-1}=const.$$
>
> **B2. Solution:** Considering that the piston move upwards, from the eq. of motion of the piston
> $$ma=pA-mg,\qquad [0.2\ \mathrm p]$$
> where
>
> $$mg=p_iA\qquad [0.1\ \mathrm p]$$
> and from Poisson eq.
> $$p=p_i\left(\frac{y_i}{y}\right)^\gamma=p_i\left(\frac{y_i}{y_i+\Delta y}\right)^\gamma=p_i\left(1+\frac{\Delta y}{y_i}\right)^{-\gamma}\cong p_i\left(1-\gamma\frac{\Delta y}{y_i}\right),\qquad [0.4\ \mathrm p]$$
> because the perturbation is very small. So,
> $$a=-\frac{\gamma g}{y_i}\Delta y,\qquad [0.1\ \mathrm p]$$
> meaning that the movement of the piston is a harmonic oscillatory one, described by the eq.
> $$y=y_i+B\cos(\omega_0t+\varphi_0),\qquad [0.2\ \mathrm p]$$
> where
> $$\omega_0=\sqrt{\frac{\gamma g}{y_i}},\qquad [0.1\ \mathrm p]$$
> which means that the oscillations frequency is $f_0=\frac1{2\pi}\sqrt{\frac{\gamma g}{y_i}}=0.64\ \mathrm{Hz}$.
> For finding $B$ and $\varphi_0$, the initial conditions must be used:
> $$y(0)=y_i\quad\text{and}\quad u(0)=u_i\qquad [2\times0.1\ \mathrm p]$$
> The results are:
> $$\varphi_0=\frac\pi2\quad\text{and}\quad A=-\frac{u_i}{\omega_0}=-u_i\sqrt{\frac{y_i}{\gamma g}}.\qquad [2\times0.1\ \mathrm p]$$
> So,
>
> $$y=y_i\left[1+\frac{u_i}{\sqrt{\gamma gy_i}}\sin\left(\sqrt{\frac{\gamma g}{y_i}}t\right)\right].\qquad [0.1\ \mathrm p]$$
> **Note:** The ratio $\frac{u_i}{\sqrt{\gamma gy_i}}$ cannot be neglected because
> $$\frac1{\sqrt{\gamma gy_i}}\cong0.25\ \frac{\mathrm s}{\mathrm m}.$$
>
> **B3. Solution:** For any quasistatic adiabatic process
>
> $$\Delta S=0.\qquad [0.3\ \mathrm p]$$
>
> **C1. Solution:** The 1st law of Thermodynamics has the form
> $$\frac m2(u_f^2-u_i^2)+\Delta U=L_{ext},\qquad [0.2\ \mathrm p]$$
> where
> $$L_{ext}=-mg(y_f-y_i)\qquad [0.1\ \mathrm p]$$
> and
> $$\Delta U=nC_V(T_f-T_i)=\frac32nR(T_f-T_i)=\frac32(p_fV_f-p_iV_i).\qquad [0.3\ \mathrm p]$$
> In the final state
> $$u_f=0\qquad [0.1\ \mathrm p]$$
> and
> $$p_f=p_i=\frac{mg}{A},\qquad [0.1\ \mathrm p]$$
> so
> $$\Delta U=\frac32\frac{mg}{A}(Ay_f-Ay_i)=\frac32mg(y_f-y_i).\qquad [0.2\ \mathrm p]$$
> As a result,
>
> $$y_f=y_i\left[1+\frac{u_i^2}{5gy_i}\right].\qquad [0.1\ \mathrm p]$$
> Numerically,
>
> $$y_f=1.51\ \mathrm m\cong1.5\ \mathrm m.\qquad [0.1\ \mathrm p]$$
> Because
>
> $$\frac{nRT_f}{V_f}=\frac{nRT_i}{V_i}\to T_f=T_i\frac{y_f}{y_i},\qquad [0.2\ \mathrm p]$$
> then
>
> $$T_f=T_i\left[1+\frac{u_i^2}{5gy_i}\right].\qquad [0.1\ \mathrm p]$$
> Numerically,
>
> $$T_f=442\ \mathrm K\cong440\ \mathrm K.\qquad [0.1\ \mathrm p]$$
>
> **C2. Solution:**
> $$\Delta S=nC_V\ln\frac{T_f}{T_i}+nR\ln\frac{V_f}{V_i}=\frac32nR\ln\frac{y_f}{y_i}+nR\ln\frac{y_f}{y_i}=\frac52nR\ln\frac{y_f}{y_i}.\qquad [0.4\ \mathrm p]$$
> Taking into account that
> $$nR=\frac{p_iV_i}{T_i}=\frac{\frac{mg}{A}Ay_i}{T_i}=\frac{mgy_i}{T_i}\qquad [0.2\ \mathrm p]$$
> and that
> $$\frac{y_f}{y_i}=1+\frac{u_i^2}{5gy_i},$$
> then
>
> $$\Delta S=\frac52\frac{mgy_i}{T_i}\ln\left[1+\frac{u_i^2}{5gy_i}\right].\qquad [0.1\ \mathrm p]$$
> Numerically,
>
> $$\Delta S=2.2\cdot10^{-2}\ \mathrm{J/K}.\qquad [0.1\ \mathrm p]$$
>
> **C3. Solution:** The requested pressure is
> $$p^*=\frac{\langle F\rangle}{A},\qquad [0.1\ \mathrm p]$$
> where the average force with which the atoms act on the piston is
> $$\langle F\rangle=\frac{\delta N\cdot\Delta p}{\delta t}.\qquad [0.1\ \mathrm p]$$
> Here, $\delta t$ is a very short time interval, such that the speed $u$ of the piston keeps its value, $\Delta p$ is the momentum variation of one atom during one elastic collision with the piston, and $\delta N$ is the number of collisions with the piston in the above time interval.
>
> To evaluate $\delta N$, we should consider that half of the atoms move in the same direction with the piston (Joule’s hypothesis) and that the relative speed of an atom with respect to the piston is $v-u$, where it was supposed that $u$ and $v$ have the same direction. So,
> $$\delta N=\frac12\frac NV A(v-u)\delta t.\qquad [0.3\ \mathrm p]$$
> Since the atom’s speed after the collision with the piston is
> $$v'=v-2u,$$
> With respect to the cylinder, then, its momentum variation is
> $$\Delta p=2m_0(v-u),\qquad [0.1\ \mathrm p]$$
> where $m_0$ is the mass of one atom.
> Under these conditions,
> $$\begin{aligned}\langle F\rangle&=\left\langle\frac12\frac NV A(v-u)2m_0(v-u)\right\rangle=m_0\frac NV A\langle(v-u)^2\rangle=m_0\frac NV A\left\langle v^2\left(1-\frac uv\right)^2\right\rangle\cong\\&\cong m_0\frac NV A\left\langle v^2\left(1-2\frac uv\right)\right\rangle=m_0\frac NV A(\langle v^2\rangle-2u\langle v\rangle),\end{aligned}\qquad [0.2\ \mathrm p]$$
> Since $\langle v^2\rangle=\frac{RT}{\mu}$ and $\langle v\rangle=\sqrt{\frac{2RT}{\pi\mu}}$, then
> $$p^*=m_0\frac NV\left(\frac{RT}{\mu}-2u\sqrt{\frac{2RT}{\pi\mu}}\right)=m_0\frac NV\frac{RT}{\mu}\left(1-2u\sqrt{\frac{2\mu}{\pi RT}}\right)=\frac{m_{Ar}}\mu\frac{RT}{V}\left(1-2u\sqrt{\frac{2\mu}{\pi RT}}\right).\quad [0.2\ \mathrm p]$$
> Because
> $$\frac{m_{Ar}}\mu RT=p^*\delta V+p(V-\delta V)=pV-(p-p^*)\delta V=pV-\delta p\delta V\cong pV,\qquad [0.5\ \mathrm p]$$
> then
>
> $$p^*=p\left(1-2u\sqrt{\frac{2\mu}{\pi RT}}\right)=p\left(1-2\sqrt{\frac6\pi}\frac{u}{v_T}\right).\qquad [0.1\ \mathrm p]$$
>
> **C4. Solution:** The equation of motion for the piston is
> $$ma=p^*A-mg=\frac{p^*V}{y}-mg=\frac{m_{Ar}RT}{\mu y}\left(1-2u\sqrt{\frac{2\mu}{\pi RT}}\right)-mg,\qquad [0.2\ \mathrm p]$$
> or
> $$a=\frac{m_{Ar}RT}{\mu my}\left(1-2u\sqrt{\frac{2\mu}{\pi RT}}\right)-g.\qquad [0.1\ \mathrm p]$$
>
> The motion of the piston is damped because the gas pressure in the adjacent layer and, consequently, the force acting on the piston, has a drag component proportional with the piston’s speed (and also with the gas temperature, making the force a little more complicated)!
>
> The gas temperature close to the final state of the system can be found from the energy balance:
> $$\frac m2(\underbrace{u_f^2}_{=0}-u^2)+nC_V(T_f-T)=-mg(y_f-y),\qquad [0.1\ \mathrm p]$$
> or, because $C_V=3R/2$,
> $$T=T_f\left(1-\frac{mu^2}{3nRT_f}-\frac{2mgz}{3nRT_f}\right)=T_f\left(1-\frac{mu^2}{m_{Ar}v_{Tf}^2}-\frac{2p_fAz}{3p_fV_f}\right).\qquad [0.2\ \mathrm p]$$
> Neglecting the ratio $\frac{mu^2}{m_{Ar}v_{Tf}^2}$ as was stated in the text,
> $$T\cong T_f\left(1-\frac23\frac z{y_f}\right).\qquad [0.1\ \mathrm p]$$
> Because
> $$u\sqrt{\frac{2\mu}{\pi RT}}=u\sqrt{\frac{2\mu}{\pi RT_f}}\left(1-\frac23\frac z{y_f}\right)^{-\frac12}\cong\sqrt{\frac6\pi}\frac u{v_{Tf}}\left(1+\frac13\frac z{y_f}\right)=\sqrt{\frac6\pi}\left(\frac u{v_{Tf}}+\frac13\frac u{v_{Tf}}\frac z{y_f}\right)\cong\sqrt{\frac6\pi}\frac u{v_{Tf}},$$
> or
> $$u\sqrt{\frac{2\mu}{\pi RT}}\cong\sqrt{\frac6\pi}\frac u{v_{Tf}},\qquad [0.4\ \mathrm p]$$
> then
> $$\begin{aligned}a&\cong\frac{m_{Ar}RT_f\left(1-\frac23\frac z{y_f}\right)}{\mu my_f\left(1+\frac z{y_f}\right)}\left(1-2\sqrt{\frac6\pi}\frac u{v_{Tf}}\right)-g=\\&=g\left(1-\frac23\frac z{y_f}\right)\left(1+\frac z{y_f}\right)^{-1}\left(1-2\sqrt{\frac6\pi}\frac u{v_{Tf}}\right)-g,\end{aligned}\qquad [0.2\ \mathrm p]$$
> or
> $$\begin{aligned}a&\cong g\left(1-\frac23\frac z{y_f}\right)\left(1-\frac z{y_f}\right)\left(1-2\sqrt{\frac6\pi}\frac u{v_{Tf}}\right)-g\cong g\left(1-\frac53\frac z{y_f}\right)\left(1-2\sqrt{\frac6\pi}\frac u{v_{Tf}}\right)-g\cong\\&\cong g\left(1-\gamma\frac z{y_f}-2\sqrt{\frac6\pi}\frac u{v_{Tf}}\right)-g=-g\gamma\frac z{y_f}-2g\sqrt{\frac6\pi}\frac u{v_{Tf}}=-\omega_1^2z-2\delta u.\end{aligned}\quad [0.4\ \mathrm p]$$
> This is the eq. of a damped oscillator, with the natural angular frequency
> $$\omega_1=\sqrt{\frac{\gamma g}{y_f}}\qquad [0.1\ \mathrm p]$$
> and the damping coefficient
> $$\delta=\sqrt{\frac6\pi}\frac g{v_{Tf}}=g\sqrt{\frac{2\mu}{\pi RT_f}}=\sqrt{\frac{2m_{Ar}g}{\pi my_f}}.\qquad [0.1\ \mathrm p]$$
>
> In conclusion, the oscillation natural frequency of the piston in its final stage of movement is
> $$f_1=\frac1{2\pi}\sqrt{\frac{\gamma g}{y_f}},$$
> having the numerical value
> $$f_1=0.524\ \mathrm{Hz}\cong0.52\ \mathrm{Hz},$$
> while that of the damping coefficient is
> $$\delta=2.58\cdot10^{-2}\ \mathrm{s}^{-1}\cong2.6\cdot10^{-2}\ \mathrm{s}^{-1}.$$
> The angular pseudofrequency is
> $$\omega'_1=\sqrt{\omega_1^2-\delta^2}=\sqrt{\frac g{y_f}\left(\gamma-\frac{2m_{Ar}}{\pi m}\right)},\qquad [0.2\ \mathrm p]$$
> so, the pseudoperiod is
>
> $$T'_1=2\pi\sqrt{\frac{y_f}{g\left(\gamma-\frac{2m_{Ar}}{\pi m}\right)}},\qquad [0.2\ \mathrm p]$$
> having the numerical value
>
> $$T'_1=1.91\ \mathrm s\cong1.9\ \mathrm s.\qquad [0.1\ \mathrm p]$$
>
> **C5. Solution:** Since
>
> $$\tau=\frac1\delta=\sqrt{\frac{\pi my_f}{2m_{Ar}g}},\qquad [0.2\ \mathrm p]$$
> Then the oscillations lifetime is
>
> $$\tau_{tot}=5\tau=194\ \mathrm s\cong190\ \mathrm s.\qquad [0.1\ \mathrm p]$$
> The number of oscillations is
>
> $$N=\frac{\tau_{tot}}{T'_1}=101\cong100.\qquad [2\times0.1\ \mathrm p]$$
>
> **Notes:**
> 1. For an ideal gas, the mean values for the gas speed $v$, respectively $v^2$, in the direction of the piston velocity, are
> $$\langle v\rangle=\sqrt{\frac{2RT}{\pi\mu}},\quad\text{respectively}\quad\langle v^2\rangle=\frac{RT}{\mu}.$$
> 2. If needed, the following approximation formula can be used:
> $$(1+x)^n\cong1+nx,\quad\text{if }|x|\ll1.$$
>
> problem proposed by
>
> **Assoc. Prof. Sebastian POPESCU, PhD**
>
> Faculty of Physics, Alexandru Ioan Cuza University of Iasi, Romania
