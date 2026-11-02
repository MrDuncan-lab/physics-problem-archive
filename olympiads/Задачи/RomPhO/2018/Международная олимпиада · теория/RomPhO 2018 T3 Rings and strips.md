---
id: rompho-2018-intl-theory-t3
olympiad: RomPhO
year: 2018
stage: "Международная олимпиада"
round: теория
grade: ""
number: "T3"
title: "Rings and strips"
aliases: ["Rings and strips"]
topics: ["[[4.2 Сила Ампера]]", "[[4.3 Индуктивность. Взаимоиндукция]]", "[[5.2 RL-цепи]]", "[[1.20 Колебания]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: true
source_damaged: false
summary: "Исследовать индукцию и движение проводящих колец, магнитное поле и индуктивность системы проводящих полос."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# Rings and strips

**RomPhO 2018** · Международная олимпиада · теория · задача T3  
Источник: [[_pdf/RomPhO/RomPhO-2017-T3.pdf#page=1|условие, стр. 1–2]] · [[_pdf/RomPhO/RomPhO-2017-T3-solution.pdf#page=3|критерии, стр. 3]]

> [!info] Год
> Год исправлен: в архиве файл подписан 2017, и на шапке листов стоит «Romanian Master of Physics 2017», но RMPh 2017 — октябрьский тур 2017 года с другими задачами; этот комплект в архиве олимпиады числится как RMPh 2018.

Темы: [[4.2 Сила Ампера]], [[4.3 Индуктивность. Взаимоиндукция]], [[5.2 RL-цепи]], [[1.20 Колебания]]

> [!abstract] Кратко (составлено моделью)
> Исследовать индукцию и движение проводящих колец, магнитное поле и индуктивность системы проводящих полос.

Problem III (10 points)

**Task no. 1 - The rotating ring**

A metal ring of radius $R$ is made out of a wire of cross section aria $s$; the resistivity of the wire’s material is given by $\rho$. The ring is place in a vertical plane. A small magnetic needle is placed in the center of the ring. The magnetic needle can rotate freely around the vertical axis which passes through the center of the ring. Due to mechanical inertia, the needle points in the direction of the average horizontal magnetic field at the center of the ring. When the ring is motionless in the reference frame of the Earth, the magnetic needle indicates the direction of the horizontal component of Earth’s magnetic field. When the ring is rotating around its vertical axis with a constant angular velocity, $\omega$, the magnetic needle deviates, in horizontal plane, from this direction by an angle $\alpha$.

**1.a.** Find the expression of angle of deviation, $\alpha$ of the magnetic needle. Write your expression for $\alpha$ as a function of $s,\omega,\rho$ and of the magnetic permeability $\mu_0$.

**Task no. 2 - The superconducting ring**

A thin ring of mass $m$, radius $r_0$ and inductance $L$ is maintained in a horizontal plane above a cylindrical magnetic bar which is placed vertically (see figure). The vertical axis of symmetry of the cylindrical magnetic bar is aligned with the center of the ring. The magnetic field due to the cylindrical magnet is shown in the right figure and each of its components are given by: the radial component is given by $B_r=B_0\cdot\beta\cdot r$, while the vertical component is given by $B_z=B_0\cdot(1-\alpha\cdot z)$. $B_0$, $\alpha$, $\beta$ are all positive constant with appropriate dimensions, while $z$ and $r$ denotes the vertical and, respectively, the radial coordinate of the system. Initially, there is no electric current passing through the ring and it is kept fixed above the magnet. It is then allowed to fall due to the gravitational pull of the Earth, given by the gravitational acceleration, $g$. During the fall the ring will still be in a horizontal plane and will have the same vertical axis.

![[rompho-2017-t3-problems-p1-f1.png]]

Answer the following questions and write your results as a function of the variables specified above.

**2.a.** Derive the equations of motion for the ring in the reference frame specified in figure.

**2.b.** Find the expression of current $I=I(t)$ which flows through the ring at time t.

**Task no. 3 - Conducting strips**

For this task you are asked to determine a number of physical quantities for systems that contain one or two conducting strips which have an electric current flowing through them. These systems are placed in air ($\mu_{aer}\cong\mu_0$).

Answer the following questions and write your results as a function of the variables specified below.

Through a conducting strip of width $b$ and length $D$, $D\gg b$ there is an electric current $I$ flowing along its length. Assume that close to the strip the magnetic field lines are rectangles which surround the strip and are in planes orthogonal to it.

**3.a.** Find an expression which relates the induced magnetic field close to the strip to the intensity of electric current $I$.

We now add a second strip with the same length width $D$ and width $b$ and place it parallel, right above the first strip, at a distance $a$, ($a\ll b\ll D$). The strips now both have a current $I$ flowing along their length, but in opposite directions.

**3.b.** Find an expression which relates the induced magnetic field, $\vec B$, between the two strips to the electric current $I$.

**3.c.** Determine the inductance $L$ of the two strip ensemble.

The two strips have negligible electric resistance and are incorporated in the circuit presented in the figure on the right. The capacitance of the whole ensemble is also negligible. The right side of the strips are connected by a wire with negligible resistivity while the sides on the left are connected to an ideal source, generating a voltage $V$. Neglect all effects due to the finite speed propagation of the electric field.

![[rompho-2017-t3-problems-p2-f1.png]]

**3.d.** Find the time dependence of the electric current $I$ from the circuit characterized only by the inductance $L$, found in 3.c. Assume the initial moment (t=0) is the moment at which the circuit is closed.

**3.e.** Denote the distance between a point on one of the strips and the right side of the strips by $x$. Determine the potential between this point and the point placed identically on the other strip as a function of $x$.

In an infinitesimal time interval $dt$ the energy provided by the source is given by $dW=V\cdot I\cdot dt$. This amount of energy is partially stored in the magnetic field to the section x; the remaining energy „flows” from section to shorted ends of strips.

**3.f.** Find the expression of energy flux $dW(x)/dt$ as a function of the distance $x$ between a point on the strip and the right end of the strip.

© Problems written by:

Prof. dr. Delia DAVIDESCU

Conf. univ. dr. Adrian DAFINEI

> [!answer]- Ответ
> **1.a** — $\alpha=\operatorname{arctg}\frac{\mu_0\cdot s\cdot\omega}{8\cdot\rho}$
>
> **2.a** — $z(t)=\frac{m\cdot g\cdot L}{2\pi^2\cdot\alpha\cdot\beta\cdot B_0^2\cdot r_0^4}\cdot\cos[\pi\cdot B_0\cdot r_0^2\cdot\sqrt{\frac{2\cdot\alpha\cdot\beta}{L\cdot m}}\cdot t-1]$
>
> **2.b** — $I(t)=\frac{g\cdot m}{2\pi\cdot\beta\cdot B_0\cdot r_0^2}\cdot(\cos[\pi\cdot B_0\cdot r_0^2\cdot\sqrt{\frac{2\cdot\alpha\cdot\beta}{L\cdot m}}\cdot t-1])$
>
> **3.a** — $B_1=B_2=\mu_0\cdot\frac I{2b}$
>
> **3.b** — $B=\mu_0\cdot\frac I b$
>
> **3.c** — $L=\frac{\mu_0\cdot D\cdot a}{b}$
>
> **3.d** — $I(t)=\frac{V\cdot b}{\mu_0\cdot D\cdot a}\cdot t$
>
> **3.e** — $U_{AA'}=V\cdot\frac xD$
>
> **3.f** — $\frac{dW}{dt}=\frac{V^2\cdot b\cdot x}{\mu_0\cdot D^2\cdot a}\cdot t$

> [!solution]- Решение (схема оценивания)
> Points are given for any correct solution
>
> Problem III — Rings and strips
>
> | Nr. item | Task no. 1 – Rotating ring | | Points |
> |---|---|---|---|
> | 1.a. | For: $\vec B_{Earth}=B_h\cdot\hat e_x+B_v\cdot\hat e_z$. $B_h$ - horizontal component of Earth’s magnetic field; $B_v$ - vertical component of Earth’s magnetic field | 0.20p | 2.60p |
> | | formula of surface vector $\vec S$ for the ring $\vec S=\pi\cdot R^2\cdot(\cos(\omega\cdot t)\cdot\hat e_x+\sin(\omega\cdot t)\cdot\hat e_y)$ | 0.20p | |
> | | expression of magnetic flux $\phi$ of Earth’s magnetic field through ring’s surface: $\begin{cases}\phi=\vec B_{Earth}\bullet\vec S=(B_h\cdot\hat e_x+B_v\cdot\hat e_z)\bullet(\pi\cdot R^2\cdot(\cos(\omega\cdot t)\cdot\hat e_x+\sin(\omega\cdot t)\cdot\hat e_y))\\\phi=B_h\cdot\pi\cdot R^2\cdot\cos(\omega\cdot t)\end{cases}$ | 0.40p | |
> | | expression of electromotive force induced in the ring: $\begin{cases}E=-\frac{d\phi}{dt}\\E(t)=B_h\cdot\pi\cdot R^2\cdot\omega\cdot\sin(\omega\cdot t)\end{cases}$ | 0.20p | |
> | | intensity of electrical current through the ring $i(t)=\frac{B_h\cdot s\cdot R\cdot\omega}{2\cdot\rho}\cdot\sin(\omega\cdot t)$ | 0.20p | |
> | | modulus of induced magnetic field in center of ring $B_i(t)=\frac{\mu_0\cdot B_h\cdot s\cdot R\cdot\omega}{4R\cdot\rho}\cdot\sin(\omega\cdot t)$ | 0.20p | |
> | | $\vec B_i=B_i\cdot(\hat e_x\cdot\cos(\omega\cdot t)+\hat e_y\cdot\sin(\omega\cdot t))$; $\vec B_i=\frac{\mu_0\cdot B_h\cdot s\cdot\omega}{4\cdot\rho}\cdot[\hat e_x\cdot\frac12\cdot\sin(2\omega\cdot t)+\hat e_y\cdot\frac12\cdot(1-\cos(2\omega\cdot t))]$ | 0.60p | |
> | | average value per time of induced magnetic field $\langle\vec B_i\rangle=\frac{\mu_0\cdot B_h\cdot s\cdot R\cdot\omega}{8R\cdot\rho}\cdot\hat e_y$ | 0.20p | |
> | | $\operatorname{tg}\alpha=\frac{|\langle\vec B_i\rangle|}{B_h}$ | 0.20p | |
> | | $\alpha=\operatorname{arctg}\frac{\mu_0\cdot s\cdot\omega}{8\cdot\rho}$ | 0.20p | |
> | Nr. item | Task no. 2 – The superconducting ring | | Poins |
> | 2.a. | For: expression of magnetic flux through ring’s surface $\Phi=B_z\cdot\pi\cdot r_0^2+L\cdot I$ | 0.40p | 4.00p |
> | | $0=R\cdot I=\frac{d\Phi}{dt}$ <br> - voltage drop on superconducting ring is zero <br> - magnetic flux inside the ring is constant | 0.20p | |
> | | $\Phi=B_0\cdot(1-\alpha\cdot z)\cdot\pi\cdot r_0^2+L\cdot I=constant$ <br> Initial conditions $\begin{cases}z(t=0)=0\\I(t=0)=0\end{cases}$; $constant=B_0\cdot\pi\cdot r_0^2$ | 0.40p | |
> | | expression of the intensity of electric current through the ring $I=\frac{B_0}{L}\cdot\alpha\cdot\pi\cdot r_0^2\cdot z$ | 0.40p | |
> | | radial component of the force of interaction is zero - because of symmetry vertical component of the force of interaction $F_z=-\frac{2\pi^2\cdot\alpha\cdot\beta\cdot B_0^2\cdot r_0^4}{L}\cdot z$ | 0.60p | |
> | | elastic constant $k=\frac{2\pi^2\cdot\alpha\cdot\beta\cdot B_0^2\cdot r_0^4}{L}$ | 0.20p | |
> | | equations of motion for the ring $m\cdot\frac{d^2z}{dt^2}+k\cdot z=-m\cdot g$ | 0.60p | |
> | | general solution of the equations of motion for the ring $z(t)=A\cdot\cos(\omega\cdot t+\psi)-\frac{m\cdot g}{k}$ | 0.40p | |
> | | initial conditions $\begin{cases}z(0)=0\\\dot z(0)=v_z(0)=0\end{cases}$ | 0.20p | |
> | | $\begin{cases}z(t)=\frac{m\cdot g\cdot L}{2\pi^2\cdot\alpha\cdot\beta\cdot B_0^2\cdot r_0^4}\cdot\cos[\sqrt{\frac{2\pi^2\cdot\alpha\cdot\beta\cdot B_0^2\cdot r_0^4}{L\cdot m}}\cdot t-1]\\z(t)=\frac{m\cdot g\cdot L}{2\pi^2\cdot\alpha\cdot\beta\cdot B_0^2\cdot r_0^4}\cdot\cos[\pi\cdot B_0\cdot r_0^2\cdot\sqrt{\frac{2\cdot\alpha\cdot\beta}{L\cdot m}}\cdot t-1]\end{cases}$ <br> Observations: 1. Vertical coordinate is $z\leq0$. 2. Electric current passes all the time in the same direction through the ring and has a minimum value $(I=0)$ in the upper point $(z=0)$ of oscillation. 3. The electromagnetic force is always upward with a minimum value $(F_m=0)$ in the upper point of oscillation | 0.60p | |
> | 2.b. | For: expression of time dependence of electric current $\begin{cases}I(t)=\frac{g\cdot m}{2\pi\cdot\beta\cdot B_0\cdot r_0^2}\cdot(\cos\sqrt{\frac{2\pi^2\cdot\alpha\cdot\beta\cdot B_0^2\cdot r_0^4}{L\cdot m}}\cdot t-1)\\I(t)=\frac{g\cdot m}{2\pi\cdot\beta\cdot B_0\cdot r_0^2}\cdot(\cos[\pi\cdot B_0\cdot r_0^2\cdot\sqrt{\frac{2\cdot\alpha\cdot\beta}{L\cdot m}}\cdot t-1])\end{cases}$ | 0.40p | 0.40p |
> | Nr. item | Task no. 3 – Conducting strips | | Points |
> | 3.a. | For: ![[rompho-2017-t3-solutions-p5-c0834.png]] <br> Ampere law $\oint_\Gamma\vec B\cdot d\vec r=\mu_0\cdot\frac{I\cdot\ell}{b}$; $\begin{cases}B_1\cdot\ell+B_2\cdot\ell=\mu_0\cdot\frac{I\cdot\ell}{b}\\B_1+B_2=\mu_0\cdot\frac I b\end{cases}$ | 0.30p | 0.50p |
> | | $B_1=B_2=\mu_0\cdot\frac I{2b}$ | 0.20p | |
> | 3.b. | For: ![[rompho-2017-t3-solutions-p5-c2665.png]] <br> $\begin{cases}B=B_1+B_2\\B=\mu_0\cdot\frac I b\end{cases}$ | 0.50p | 0.50p |
> | 3.c. | For: $\begin{cases}U=-\frac{d\varphi}{dt}\\U=-L\cdot\frac{dI}{dt}\end{cases}$ or $\varphi=L\cdot I$ | 0.30p | 0.50p |
> | | $L=\frac{\mu_0\cdot D\cdot a}{b}$ | 0.20p | |
> | 3.d. | For: the second II Kirchhoff law $V=L\cdot\frac{dI}{dt}$ (R=0, C=0) | 0.30p | 0.50p |
> | | $I(t)=\frac{V\cdot b}{\mu_0\cdot D\cdot a}\cdot t$ | 0.20p | |
> | 3.e. | For: ![[rompho-2017-t3-solutions-p6-c2838.png]] <br> Voltage difference $U_{AA'}$ between two mirroring points of the two bands is due to self-induced voltage corresponding to the portion starting at $x$ to the end of the assembly strip $U_{AA'}=L(x)\cdot\frac{dI}{dt}$ <br> $L(x)$ - the inductance linked with of the magnetic flux through ending portion (of length $x$) of the strip assembly $\begin{cases}L(x)=\frac{\Phi(x)}I\\L(x)=\frac{B\cdot x\cdot a}{I}\end{cases}$; $L(x)=\frac{\mu_0\cdot x\cdot a}{b}$ | 0.30p | 0.50p |
> | | $U_{AA'}=V\cdot\frac xD$ | 0.20p | |
> | 3.f. | For: $\begin{cases}\frac{dW}{dt}=I\cdot U_{AA'}\\\frac{dW}{dt}=\frac{V^2\cdot b\cdot x}{\mu_0\cdot D^2\cdot a}\cdot t\end{cases}$ | 0.50p | 0.50p |
> | TOTAL Problem III | | | 10p |
>
> © Marking scheme written by:  
> Prof. dr. Delia DAVIDESCU  
> Conf. univ. dr. Adrian DAFINEI
