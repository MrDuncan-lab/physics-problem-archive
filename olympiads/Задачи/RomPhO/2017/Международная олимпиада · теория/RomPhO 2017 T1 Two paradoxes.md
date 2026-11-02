---
id: rompho-2017-intl-theory-t1
olympiad: RomPhO
year: 2017
stage: "Международная олимпиада"
round: теория
grade: ""
number: "T1"
title: "Two paradoxes"
aliases: ["Two paradoxes"]
topics: ["[[1.17 Законы сохранения энергии и импульса]]", "[[4 Магнетизм]]", "[[6.5 Волновая оптика]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Разобрать сохранение энергии в движущейся системе отсчёта и момент импульса электромагнитного поля и заряженных вращающихся цилиндров."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# Theoretical problem 1: Two paradoxes

**RomPhO 2017** · Международная олимпиада · теория · задача T1  
Источник: [[_pdf/RomPhO/RomPhO-2018-T1.pdf#page=1|условие, стр. 1–2]] · [[_pdf/RomPhO/RomPhO-2018-T1-solution.pdf#page=1|решение, стр. 1–8]]

> [!info] Год
> Год исправлен по самим листам: в архиве файл подписан 2018, но это RMPh 2017 — на листах «Theoretical/Experimental Exam — October 27/28, 2017» (7-я RMPh, 25–30 октября 2017).

Темы: [[1.17 Законы сохранения энергии и импульса]], [[4 Магнетизм]], [[6.5 Волновая оптика]]

> [!abstract] Кратко (составлено моделью)
> Разобрать сохранение энергии в движущейся системе отсчёта и момент импульса электромагнитного поля и заряженных вращающихся цилиндров.

A paradox is a statement that is apparently false or unveils its contradictory nature when analyzed in two different ways.

**A. Where is the missing energy?** (4 points)

A body (treated as a material point) with the mass $m$ is kept at rest on a slope (Fig. 1) with a constant inclination on its whole length. When released, the body starts to slide towards the base of the slope and continues to move to the right on the horizontal plane. The connection region between the slope and the horizontal plane is smooth, such that the speed of the body does not change, only the direction of its velocity. The starting point is at a height $h$ above the horizontal plane and the value of the gravitational acceleration is constant and known, $g$. Friction is neglected everywhere.

![[rompho-2018-t1-problems-p1-f1.png]]
*Fig. 1*

**A1** Derive the mathematical expression for the speed $v_0$ of the body on the horizontal plane. 0.30 p

Consider now the same process, but seen from a reference system moving to the right with the constant speed $v_0$ relative to the ground (the slope and the horizontal plane). In this reference system the final energy of the body is zero, while its initial energy is positive.

**A2** Where did the energy “disappeared”? Give a detailed quantitative analysis of the missing energy. 3.70 p

**B. Where is the missing angular momentum?** (6 points)

**B1. Momentum of electromagnetic waves**

The energy transferred by an electromagnetic wave per unit of time per unit of surface is called Poynting vector and has the mathematical form

$$\vec S=\frac1{\mu_0}\vec E\times\vec B,$$

where $\mu_0$ is the magnetic permeability of vacuum. The electric permittivity of vacuum, $\varepsilon_0$, is also known.

**B1** Derive the volume density of the linear momentum of an electromagnetic wave, $p_V$. Express your result in vector form ($\vec p_V$). 0.90 p

**B2. Feynman paradox**

In Fig. 2 there are two long, coaxial cylindrical shells of length $l$. The inner one has the radius $a$ and the electric charge $+Q$, uniformly distributed over its surface. The outer cylinder has the radius $b$ ($b\ll l$) and the electric charge $-Q$, uniformly distributed over its surface. The cylinders are made of the same material, having the mass per unit of area equal to $\sigma$. Coaxial with them there is a long solenoid with the radius $R$ ($a<R<b$), with $n$ turns per unit length, and carrying an electric current $i$. The solenoid is fixed, but the cylindrical shells can freely and independently rotate around their common axis. Initially all the parts of this system are at rest.

![[rompho-2018-t1-problems-p2-f1.png]]
*Fig. 2*

**B2.1. Angular velocities**

**B2.1** When the current in the solenoid is gradually reduced to zero, the cylinders begin to rotate. Derive the mathematical expressions of the final angular velocities (magnitude and orientation) of the cylinders. 2.60 p

Note: The cylindrical shells are heavy enough to neglect any magnetic field due to their rotation!

**B2.2. Feynman paradox**

**B2.2** Since no external force acted on the system, its angular momentum should be conserved. From where did the angular momentum “appeared”? Give a detailed quantitative analysis of this paradox. 1.30 p

**B2.3. Radial spoke**

**B2.3** Instead of decreasing the current through the solenoid, the cylinders are rigidly connected with a radial spoke with negligible mass (the practical method of doing this is not of interest here). The spoke is a weak conductor in order to neglect the displacement current. Determine the total angular momentum of the cylinders in this case, as well as their angular velocity. 1.20 p

> [!answer]- Ответ
> **A1**
>
> $$
> v_0=\sqrt{2gh}.\qquad (0.10\ p)
> $$
>
> **A2**
>
> $$
> L_N=L_{1N}+L_{2N}=-2mgh,\qquad (0.20\ p)
> $$
>
> **B1**
>
> $$
> \vec p_V=\frac1{c^2\mu_0}\vec E\times\vec B=\varepsilon_0\vec E\times\vec B.\qquad (0.20\ p)
> $$
>
> **B2.1**
>
> $$
> \vec\omega_a=\frac{\mu_0nQi}{4\pi l\sigma a}\hat z,\qquad (0.10\ p)
> $$
>
> **B2.1**
>
> $$
> \vec\omega_b=-\frac{\mu_0nQiR^2}{4\pi l\sigma b^3}\hat z,\qquad (0.10\ p)
> $$
>
> **B2.2**
>
> $$
> \vec L_{em}=\vec l_{em}\times\pi(R^2-a^2)l=-\frac12\mu_0niQ(R^2-a^2)\hat z.\qquad (0.30\ p)
> $$
>
> **1**
>
> $$
> \vec\omega=\frac{\vec L}{I_{tot}}=-\frac{\mu_0niQ(R^2-a^2)}{4\pi\sigma l(a^3+b^3)}\hat z.\qquad (0.30\ p)
> $$

> [!solution]- Решение
> **Solution:**
>
> In the absence of friction, mechanical energy is conserved. Taking the zero level for the gravitational potential energy on the horizontal plane, at the starting point the body has only potential energy, $mgh$, and on the horizontal plane only kinetic energy, $\frac{mv_0^2}{2}$. So,
>
> $$mgh=\frac{mv_0^2}{2},\qquad (0.20\ p)$$
>
> leading to
>
> $$v_0=\sqrt{2gh}.\qquad (0.10\ p)$$
>
> **Solution:**
>
> Taking into account the free body diagram from Fig. 1R(a),
>
> ![[rompho-2018-t1-solutions-p2-c4226.png]]
> *Fig. 1R(a)*
>
> the theorem of variation for the kinetic energy is
>
> $$\Delta E_c=L_{mg}+L_N.\qquad (0.50\ p)$$
>
> Since the initial speed of the body is $v_0$ and its final speed is zero, the variation of its kinetic energy is
>
> $$\Delta E_c=0-\frac{mv_0^2}{2}=-\frac{mv_0^2}{2}=-mgh,\qquad (0.20\ p)$$
>
> while the work done by the body’s weight is
>
> $$L_{mg}=mgh.\qquad (0.10\ p)$$
>
> ![[rompho-2018-t1-solutions-p2-c4060.png]]
> *Fig. 1R(b)*
>
> Since $\vec v_r$ is not perpendicular on $\vec N$ [Fig. 1R(b)], then the work done by
>
> $$N=mg\cos\alpha\qquad (0.10\ p)$$
>
> on the descending part of the slope, which makes an angle $\alpha$ with the horizontal plane, is
>
> $$dL_{1N}=\vec N\cdot\vec v_rdt=-Nv_0dt\sin\alpha=-mgv_0dt\sin\alpha\cos\alpha,\qquad (0.40\ p)$$
>
> or,
>
> $$L_{1N}=-mgv_0\tau_1\sin\alpha\cos\alpha,\qquad (0.20\ p)$$
>
> where $\tau_1$ is the descending time, found from projecting the equation of motion for the body on the vertical axis
>
> $$ma_y=mg-N\cos\alpha=mg-mg\cos^2\alpha=mg\sin^2\alpha.\qquad (0.30\ p)$$
>
> So,
>
> $$a_y=g\sin^2\alpha,\qquad (0.10\ p)$$
>
> hence
>
> $$\tau_1=\sqrt{\frac{2h}{a_y}}=\frac1{\sin\alpha}\sqrt{\frac{2h}{g}}.\qquad (0.10\ p)$$
>
> Consequently,
>
> $$L_{1N}=-mgv_0\sqrt{\frac{2h}{g}}\cos\alpha=-mg\sqrt{2gh}\sqrt{\frac{2h}{g}}\cos\alpha=-2mgh\cos\alpha.\qquad (0.10\ p)$$
>
> ![[rompho-2018-t1-solutions-p3-c3532.png]]
> *Fig. 1R(b)*
>
> On the connection region between the slope and the horizontal plane the body’s speed is $v_0$, constant in magnitude, but not in orientation. As a result [Fig. 1R(c)], the work done by $\vec N$ on this part of the trajectory is
>
> $$dL_{2N}=\vec N\cdot\vec v_rdt=-Nv_0dt\sin\beta.\qquad (0.30\ p)$$
>
> Projecting on the horizontal axis the mathematical expression of the theorem of momentum variation,
>
> $$dp_x=N_xdt=Ndt\sin\beta.\qquad (0.30\ p)$$
>
> So,
>
> $$dL_{2N}=-v_0dp_x.\qquad (0.10\ p)$$
>
> For the entire connection region,
>
> $$L_{2N}=-v_0\Delta p_x=-v_0m(v_0-v_0\cos\alpha)=-mv_0^2(1-\cos\alpha)=-2mgh(1-\cos\alpha).\qquad (0.50\ p)$$
>
> In conclusion,
>
> $$L_N=L_{1N}+L_{2N}=-2mgh,\qquad (0.20\ p)$$
>
> so, the theorem of kinetic energy variation also holds in the moving inertial system. (0.20 p)
>
> **Solution:**
>
> Since an electromagnetic wave may be considered to be made of photons, then their momentum is
>
> $$\delta p=\frac{\delta W}{c}=\frac{S\delta A\delta t}{c},\qquad (0.30\ p)$$
>
> where $c$ is light speed in vacuum. In these conditions, the volume density of the linear momentum is
>
> $$p_V=\frac{\delta p}{\delta V}=\frac{S\delta A\delta t}{c\delta A\delta l}=\frac{S}{c\frac{\delta l}{\delta t}}=\frac{S}{c^2}.\qquad (0.40\ p)$$
>
> In vector form,
>
> $$\vec p_V=\frac1{c^2\mu_0}\vec E\times\vec B=\varepsilon_0\vec E\times\vec B.\qquad (0.20\ p)$$
>
> **Solution:**
>
> The current through the solenoid produces inside it a magnetic field given by
>
> $$\vec B=\mu_0ni\hat z,\ \text{for }r<R.\qquad (0.10\ p)$$
>
> When the current decreases, the magnetic field strength decreases, inducing an electric field (with the circular field lines), in accord with Faraday’s law
>
> $$\vec E\cdot2\pi r\hat\phi=-\frac{d}{dt}(\vec B\cdot\vec S).\qquad (0.30\ p)$$
>
> If $r<R$, then $\vec S=\pi r^2\hat z$ and (0.10 p)
>
> $$\vec E=-\frac12\mu_0n\frac{di}{dt}r\hat\phi,\qquad (0.10\ p)$$
>
> while if $r>R$, then $\vec S=\pi R^2\hat z$ and (0.10 p)
>
> $$\vec E=-\frac12\mu_0n\frac{di}{dt}\frac{R^2}{r}\hat\phi.\qquad (0.10\ p)$$
>
> The torque on the inner cylinder is
>
> $$\vec\tau_a=\vec r\times Q\vec E=-\frac12\mu_0nQa^2\frac{di}{dt}\hat r\times\hat\phi=-\frac12\mu_0nQa^2\frac{di}{dt}\hat z.\qquad (0.40\ p)$$
>
> In accord with the theorem for the variation of the angular momentum,
>
> $$\vec\tau_a=\frac{d\vec L_a}{dt},\qquad (0.20\ p)$$
>
> so
>
> $$\Delta\vec L_a=-\frac12\mu_0nQa^2\Delta i\hat z,\qquad (0.10\ p)$$
>
> or
>
> $$\vec L_a=\frac12\mu_0nQa^2i\hat z.\qquad (0.10\ p)$$
>
> Because
>
> $$\vec L_a=I\vec\omega_a=m_a a^2\vec\omega_a=2\pi l\sigma a^3\vec\omega_a,\qquad (0.30\ p)$$
>
> then
>
> $$\vec\omega_a=\frac{\mu_0nQi}{4\pi l\sigma a}\hat z,\qquad (0.10\ p)$$
>
> For the outer cylinder, the torque is
>
> $$\vec\tau_b=\vec r\times(-Q)\vec E=\frac12\mu_0nQR^2\frac{di}{dt}\hat r\times\hat\phi=\frac12\mu_0nQR^2\frac{di}{dt}\hat z.\qquad (0.10\ p)$$
>
> Using the theorem for the variation of the angular momentum,
>
> $$\vec\tau_b=\frac{d\vec L_b}{dt},\qquad (0.10\ p)$$
>
> the variation of the angular momentum is
>
> $$\Delta\vec L_b=\frac12\mu_0nQR^2\Delta i\hat z,\qquad (0.10\ p)$$
>
> or
>
> $$\vec L_b=-\frac12\mu_0nQR^2i\hat z.\qquad (0.10\ p)$$
>
> Because
>
> $$\vec L_b=I\vec\omega_b=m_b b^2\vec\omega_b=2\pi l\sigma b^3\vec\omega_b,\qquad (0.10\ p)$$
>
> then
>
> $$\vec\omega_b=-\frac{\mu_0nQiR^2}{4\pi l\sigma b^3}\hat z,\qquad (0.10\ p)$$
>
> which means that the outer cylinder rotates clockwise, when seen from above.
>
> **Solution:**
>
> In the region between the cylinders ($a<r<b$) there is an electric field, given by Gauss theorem
>
> $$\vec E=\frac{Q}{2\pi\varepsilon_0l}\frac1r\hat r.\qquad (0.30\ p)$$
>
> While there is a current through the solenoid, there will be a magnetic field inside it, so, the linear momentum density of the fields is
>
> $$\vec p_V=\varepsilon_0\vec E\times\vec B=\frac Q{2\pi l}\frac1r\hat r\times\mu_0ni\hat z=-\frac{\mu_0niQ}{2\pi l}\frac1r\hat\phi.\qquad (0.20\ p)$$
>
> The angular momentum density of the fields will be
>
> $$\vec l_{em}=\vec r\times\vec p_V=-\frac{\mu_0niQ}{2\pi l}\hat r\times\hat\phi=-\frac{\mu_0niQ}{2\pi l}\hat z.\qquad (0.30\ p)$$
>
> The total angular momentum of the fields will be
>
> $$\vec L_{em}=\vec l_{em}\times\pi(R^2-a^2)l=-\frac12\mu_0niQ(R^2-a^2)\hat z.\qquad (0.30\ p)$$
>
> Checking the above results, it immediately follows that
>
> $$\vec L_{em}=\vec L_a+\vec L_b,\qquad (0.20\ p)$$
>
> or that the fields angular momentum is totally transformed into mechanical angular momentum of the cylinders.
>
> **Solution:**
>
> In this case the electric field is turned off and the mechanism of transforming the angular momentum is based on the Lorentz force. So, the force acting on a segment
>
> $$d\vec r=dr\hat r$$
>
> of the spoke is
>
> $$d\vec F=i_1d\vec r\times\vec B=i_1Bdr\hat r\times\hat z=i_1Bdr(-\hat\phi)=-i_1Bdr\hat\phi,\qquad (0.20\ p)$$
>
> where
>
> $$i_1=\frac{dQ}{dt}\qquad (0.10\ p)$$
>
> is the current discharging the cylinders and
>
> $$\vec B=\begin{cases}\mu_0ni\hat z, & \text{for }a<r<R\\ \vec 0, & \text{for }r>R\end{cases}$$
>
> is the magnetic field produced by the solenoid. The torque on the spoke will be
>
> $$\vec\tau=\int_a^b\vec r\times d\vec F=-\mu_0nii_1\left(\int_a^R r\,dr\right)\hat r\times\hat\phi=-\frac12\mu_0nii_1(R^2-a^2)\hat z.\qquad (0.30\ p)$$
>
> Since
>
> $$\vec\tau=\frac{d\vec L}{dt},\qquad (0.10\ p)$$
>
> then
>
> $$\frac{d\vec L}{dt}=-\frac12\mu_0ni\frac{dQ}{dt}(R^2-a^2)\hat z,$$
>
> or
>
> $$\Delta\vec L=-\frac12\mu_0ni\Delta Q(R^2-a^2)\hat z.$$
>
> From here, because
>
> $$\Delta\vec L=\vec L-\vec 0=\vec L\quad\text{and}\quad\Delta Q=Q-0=Q,\qquad (0.10\ p)$$
>
> it follows that
>
> $$\vec L=-\frac12\mu_0niQ(R^2-a^2)\hat z,\qquad (0.10\ p)$$
>
> in agreement with the above result for the angular momentum of the fields. Finally, the angular velocity of the cylinders is
>
> $$\vec\omega=\frac{\vec L}{I_{tot}}=-\frac{\mu_0niQ(R^2-a^2)}{4\pi\sigma l(a^3+b^3)}\hat z.\qquad (0.30\ p)$$
>
> proposed by
>
> Assoc. Prof. Sebastian POPESCU, PhD  
> Faculty of Physics, Alexandru Ioan Cuza University of Iași, ROMANIA
