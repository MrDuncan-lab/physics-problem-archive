---
id: rompho-2017-intl-theory-t3
olympiad: RomPhO
year: 2017
stage: "Международная олимпиада"
round: теория
grade: ""
number: "T3"
title: "On the propagation and generation of gravitational waves"
aliases: ["On the propagation and generation of gravitational waves"]
topics: ["[[6.5 Волновая оптика]]", "[[4 Магнетизм]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: true
source_damaged: false
summary: "Исследовать распространение и поляризацию гравитационных волн по аналогии с электромагнитными и оценить энергию волн от слияния чёрных дыр."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# Theoretical problem 3: On the propagation and generation of gravitational waves

**RomPhO 2017** · Международная олимпиада · теория · задача T3  
Источник: [[_pdf/RomPhO/RomPhO-2018-T3.pdf#page=1|условие, стр. 1–3]] · [[_pdf/RomPhO/RomPhO-2018-T3-solution.pdf#page=5|решение, стр. 5–8]] · [[_pdf/RomPhO/RomPhO-2018-T3-solution.pdf#page=10|критерии, стр. 10]]

> [!info] Год
> Год исправлен по самим листам: в архиве файл подписан 2018, но это RMPh 2017 — на листах «Theoretical/Experimental Exam — October 27/28, 2017» (7-я RMPh, 25–30 октября 2017).

Темы: [[6.5 Волновая оптика]], [[4 Магнетизм]]

> [!abstract] Кратко (составлено моделью)
> Исследовать распространение и поляризацию гравитационных волн по аналогии с электромагнитными и оценить энергию волн от слияния чёрных дыр.

The scope of this problem is to help you understand the properties of gravitational waves, whose discovery has recently been rewarded with the 2017 Nobel Prize in Physics. Part I of the problem will analyze the propagation of gravitational waves in close analogy with electromagnetic waves, while Part II will be concerned with estimating the amount of energy gravitational waves carry from the merger of two black holes.

**Part I. [6 pts.]** Numerous phenomena that occur when studying gravitational waves closely resemble those in the world of electromagnetism. This is due to the similarity between solutions to the Maxwell equations in vacuum,

$$\nabla\cdot\vec E=\frac{\partial E_x}{\partial x}+\frac{\partial E_y}{\partial y}+\frac{\partial E_z}{\partial z}=0,\tag{1}$$
$$\nabla\cdot\vec B=\frac{\partial B_x}{\partial x}+\frac{\partial B_y}{\partial y}+\frac{\partial B_z}{\partial z}=0,\tag{2}$$
$$\nabla\times\vec E=\left(\frac{\partial E_z}{\partial y}-\frac{\partial E_y}{\partial z}\right)\hat x+\left(\frac{\partial E_x}{\partial z}-\frac{\partial E_z}{\partial x}\right)\hat y+\left(\frac{\partial E_y}{\partial x}-\frac{\partial E_x}{\partial y}\right)\hat z=-\frac{\partial\vec B}{\partial t},\tag{3}$$
$$\nabla\times\vec B=\left(\frac{\partial B_z}{\partial y}-\frac{\partial B_y}{\partial z}\right)\hat x+\left(\frac{\partial B_x}{\partial z}-\frac{\partial B_z}{\partial x}\right)\hat y+\left(\frac{\partial B_y}{\partial x}-\frac{\partial B_x}{\partial y}\right)\hat z=\frac1{c^2}\frac{\partial\vec E}{\partial t},\tag{4}$$

which describe electromagnetic waves propagating freely, and solutions to the equation for gravitational waves propagating in vacuum,

$$-\frac1{c^2}\frac{\partial^2}{\partial t^2}h_{ij}+\nabla^2h_{ij}=-\frac1{c^2}\frac{\partial^2}{\partial t^2}h_{ij}+\left(\frac{\partial^2h_{ij}}{\partial x^2}+\frac{\partial^2h_{ij}}{\partial y^2}+\frac{\partial^2h_{ij}}{\partial z^2}\right)=0\tag{5}$$

Above, $c$ is the speed of light and $\vec E$ and $\vec B$ are the electric and magnetic field, respectively, $h$ can be understood as a $3\times3$ matrix whose elements represent perturbations in the “fabric” of space. The matrix needs to be symmetric ($h_{ij}=h_{ji}$), with each line and column representing a direction in space: specifically, $i,j=\overline{1,3}$, and 1 corresponds to x, 2 to y and 3 to z. Thus, for instance, the element $h_{11}$ is associated to the xx component of the wave, $h_{12}$ is associated to the xy component of the wave etc. The gravitational wave equation (5) thus applies independently to every element of the matrix $h$.

**a)** [2 pts.] Show that for an electromagnetic wave propagating in the z-direction, $\vec E(\vec r,t)=E_0e^{i(\omega t-kz)}\hat x$ is a solution to Maxwell’s equations in vacuum (1–4), where $\hat x$ is the unit vector in the x-direction, and find the associated magnetic field $\vec B(\vec r,t)$. Along the way, prove that $\vec B(\vec r,t)$ needs to be pointing in the y-direction. Furthermore, show that $\vec k\times\vec E(\vec r,t)=\omega\vec B(\vec r,t)$.

**b)** [1 pt.] Prove that the equation for gravitational waves also has a similar oscillating solution propagating in the z-direction, $h=h_0e^{i(\omega t-kz)}$, where $h_0$ is a $3\times3$ matrix of constants.

**c)** [0.5 pts.] Show that in vacuum both electromagnetic waves and gravitational waves propagate at the speed of light.

**d)** [1 pt.] Similar to how Maxwell’s equations impose a constraint that relates the electric field, $\vec E$, to the magnetic field $\vec B$, there are supplementary constrains that can be imposed for the matrix $h$. Specifically, for a wave propagating in the z-direction one can impose that any component of the matrix related to the z-direction has to vanish ($h_{i3}=h_{3i}=0$ for $i=\overline{1,3}$), and that the matrix is traceless ($h_{11}+h_{22}+h_{33}=0$). Use these properties, together with the fact that the matrix is symmetric, to show that $h_0$ only has two independent components. Show that $h_0$ can be expressed as

$$h_0=h_+\epsilon_++h_\times\epsilon_\times,\tag{6}$$

where $h_+$ și $h_\times$ are two independent constants and $\epsilon_+$ and $\epsilon_\times$ are given by

$$\epsilon_+=\begin{pmatrix}1&0&0\\0&-1&0\\0&0&0\end{pmatrix},\qquad\epsilon_\times=\begin{pmatrix}0&1&0\\1&0&0\\0&0&0\end{pmatrix}.\tag{7}$$

**e)** [1.5 pts.] In quantum mechanics, the spin of a particle is given by a number $s$ that describes the symmetry of the wave solution associated with the propagation of this particle. Specifically, the spin is the maximum number, $s$, for which the wave solution is invariant under rotations of $360^\circ/s$ around the direction of propagation. The three-dimensional rotation matrix that performs a rotation of angle $\theta$ around the z-axis is given by,

$$U=\begin{pmatrix}\cos\theta&-\sin\theta&0\\\sin\theta&\cos\theta&0\\0&0&1\end{pmatrix},\tag{8}$$

and transforms the electric and magnetic fields as, $\vec E\to U\cdot\vec E$, and, $\vec B\to U\cdot\vec B$ respectively¹. The matrix $h$ transforms as, $h\to UhU^T$, where $U^T$ is the transpose² of $U$.

¹ Note that when taking the product between the matrix $U$ and a vector $\vec E$, each element of the resulting vector $\vec E'$ is given by, $(\vec E')_i=\sum_{j=1}^3 U_{ij}(\vec E)_j$.

² Note that when taking the transpose $(U^T)_{ij}=U_{ji}$ for all $i,j=\overline{1,3}$. When taking the product between two $3\times3$ matrices, A and B, $(AB)_{ij}=\sum_{l=1}^3 A_{il}B_{lj}$ for every $i,j=\overline{1,3}$.

Find the spin of the photon (the particle associated to electromagnetic waves) and that of the graviton (associated to gravitational waves).

**Part II. [4 pts.]** The black holes, whose merger was recently detected by the winners of the 2017 Nobel Prize in Physics, are extremely massive objects with strange physical properties.

The first detection of gravitational waves came from the merger of two black holes each with a mass equal to $M=30$ solar masses located $d=1.3\cdot10^9$ light-years from Earth (1 solar mass is $1.98\cdot10^{30}\,kg$ and 1 light year is $9.46\cdot10^{15}\,m$).

**a)** [1.5 pts.] Assuming that the merger of the two black holes occurs while the black holes are close to being at rest and generates only gravitational waves, and nothing else, use the mass-energy relation to express the energy passing through a detector with the opening of $1\,m^2$, situated on Earth from those gravitational waves. Express your answer both analytically (in terms of the mass $M$ of each black hole, the distance $d$ and the speed of light $c$) and numerically.

**b)** [2.5 pts.] The assumption that all the energy from the merger is converted only to gravitational waves can be easily refined using the laws of thermodynamics. Gravitational waves hold only negligible entropy while black holes carry huge amounts of entropy. The entropy of a single black hole of mass $M$ is given by, $S_{BH}=sM^2$, where $s$ is related to fundamental constants. Argue that if two black holes violently collide to make one bigger black hole, then at most 29% of their initial rest energy can be radiated in gravitational waves. Thus, assuming that the two black holes are almost static during the collision, give a numerical upper bound for the energy flux determined on Earth from the black hole collision. Note that the assumption that the two black holes are static should only apply to the numerical result and no to the rest of the problem.

> [!answer]- Ответ
> **I.a**
>
> $$
> \vec B(\vec r,t)=\left(\frac{k}{\omega}E_0e^{i(\omega t-kz)}\right)\hat y+\vec C(\vec r)
> $$
>
> **II.a** — $\Phi=2Mc^2/d^2$. Numerically, the answer is
>
> **II.a** — $\Phi=0.07J/m^2$.
>
> **II.b**
>
> $$
> f\geq\frac{2-\sqrt2}{2}\approx0.29],
> $$
>
> **II.b**
>
> $$
> \Phi\geq0.2J/m^2
> $$

> [!solution]- Решение
> **Solution:** Inserting $\vec E(\vec r,t)=E_0e^{i(\omega t-kz)}\hat x$ into Maxwell’s first equation we find that the equation in satisfied trivially since the only non-vanishing spatial derivative is in the z direction, which is orthogonal to the direction of the electric field. Plugging the solution into the third equation we find that,
>
> $$-\frac{\partial\vec B}{\partial t}=-ikE_0e^{i(\omega t-kz)}\hat y\tag{6}$$
>
> whose solution, gives,
>
> $$\vec B(\vec r,t)=\left(\frac{k}{\omega}E_0e^{i(\omega t-kz)}\right)\hat y+\vec C(\vec r)\tag{7}$$
>
> where $\vec C(\vec r)$ is an arbitrary function. Thus, we have proven that $\vec B(\vec r,t)$ points in the $\vec y$ direction. Plugging this solution into the second and fourth Maxwell equation we find that both equations are satisfied if $C(\vec r)=\vec C$, and if $k^2/\omega^2=1/c^2$. For $|\vec C|=0$ (which is given by choosing appropriate boundary conditions at infinity for the electric current) we indeed find that for $\vec k=k\hat x$, $\vec k\times\vec E(\vec r,t)=\omega\vec B(\vec r,t)$.
>
> To prepare the ground for dealing with gravitational waves, one can notice that, by applying the curl to the third and fourth of Maxwell’s equations, the electric and magnetic fields both have to obey a very similar equation to the equation for the propagation of gravitational waves,
>
> $$-\frac1{c^2}\frac{\partial^2}{\partial t^2}\vec E+\nabla^2\vec E=0,\qquad-\frac1{c^2}\frac{\partial^2}{\partial t^2}\vec B+\nabla^2\vec B=0,\tag{8}$$
>
> **Solution:** By plugging in the suggested solution into the equation for gravitational waves we find that, for each element of the matrix $h$,
>
> $$\nabla^2h_{ij}=-k^2(h_0)_{ij}e^{i(\omega t-kz)}\tag{9}$$
>
> and,
>
> $$\frac1{c^2}\frac{\partial^2}{\partial t^2}h_{ij}=-\frac{\omega^2}{c^2}(h_0)_{ij}e^{i(\omega t-kz)}\tag{10}$$
>
> which together, prove that the ansatz is indeed a propagating wave solution if $\omega/k=c$.
>
> **Solution:** Both the solution in part a. and part b. require that the wave velocity, $\omega/k=c$. Thus, both types of waves have to propagate with the speed of light.
>
> **Solution:** A general symmetric matrix has 6 independent elements. The condition that all elements of the matrix related to the z-direction vanish reduces the number of independent elements to 3. The trace condition further reduces the number of elements from 3 to 2. Furthermore, the matrix has to satisfy $h_{12}=h_{21}$ by symmetry and $h_{11}=-h_{22}$ by the trace condition. Identifying $h_{12}=h_{21}=h_+$ and $h_{11}=-h_{22}=h_\times$ yields the required expression.
>
> **Solution:** Transforming the vector $\vec E$ yields,
>
> $$U\vec E=E_0e^{i(\omega t-kz)}(\cos\theta\vec x+\sin\theta\vec y)\tag{14}$$
>
> The only way for the vector $\vec E$ to return to the same position is to take $\theta=2\pi$. This shows that the spin of the photon is 1.
>
> Transforming the matrix $h$, using the form (??), yields,
>
> $$UhU^T=\begin{pmatrix}h_+\cos(2\theta)-h_\times\sin(2\theta)&h_+\cos(2\theta)+h_\times\sin(2\theta)&0\\h_+\cos(2\theta)+h_\times\sin(2\theta)&-h_+\cos(2\theta)+h_\times\sin(2\theta)&0\\0&0&0\end{pmatrix}e^{i(\omega t-kz)}.\tag{15}$$
>
> Thus, $UhU^T=h$ if $\theta=\pi$, which implies that the graviton has spin 2.
>
> **Solution:** The energy that would be transferred into gravitational waves is $E=2Mc^2$.
>
> Thus, the flux will be
>
> $\Phi=2Mc^2/d^2$. Numerically, the answer is
>
> $\Phi=0.07J/m^2$.
>
> **Solution:** The estimate simply requires the use of the second law of thermodynamics (that the entropy of the entire system increases with time). The initial entropy is given by,
>
> $$S_{before}=2sM^2\tag{16}$$
>
> Requiring that the entropy of the system after the collision, $S_{after}$, increases ($S_{after}>S_{before}$) and that the entropy of the gravitational waves is negligible
>
> $$S_{after}=sM_{after}^2\geq2sM^2\tag{17}$$
>
> which implies that $M_{after}\geq\sqrt2M$. Thus, the maximum ration between the energy transferred into gravitational waves and the initial energy of the black hole is given by,
>
> $$f\geq\frac{2-\sqrt2}{2}\approx0.29],\tag{18}$$
>
> Thus, an upper bound for the energy flux assuming that the collision occurs when the two black holes are almost at rest,
>
> $$\Phi\geq0.2J/m^2\tag{19}$$

> [!grading]- Критерии оценивания
> | Item | Points |
> |---|---|
> | a) | Showing that $\vec E(\vec r,t)=E_0e^{i(\omega t-kz)}\hat x$ satisfies Maxwell’s first equation [0.4pts]. Finding the associated magnetic field, $\vec B(\vec r,t)=\left(\frac{k}{\omega}E_0e^{i(\omega t-kz)}\right)\hat y+\vec C$ (6) is worth [0.5 pts]. Dealing with the constant vector $\vec C$ correctly will be worth [0.1 pts] of the [0.5 pts]. Checking that all other Maxwell equations are satisfied is worth [0.6 pts] ([0.2 pts] per remaining Maxwell equation). Proving that the magnetic field points in the $\hat y$ direction is worth [0.2pts]. Proving that $\vec k\times\vec E(\vec r,t)=\omega\vec B(\vec r,t)$ is worth [0.3pts]. |
> | b) | Obtaining $\partial^2h/\partial^2t$ correctly is worth [0.4 pts]. Obtaining $\nabla^2h$ correctly is worth [0.4 pts]. Arriving to the correct conclusion is worth another [0.2 pts]. |
> | c) | Interpreting $\omega/k$ as the wave velocity gives [0.3pts]. Arriving to the correct conclusions for electromagnetic and gravitational waves are worth [0.1 pts] each. |
> | d) | Counting the number of degrees of freedom correctly is worth [0.6 pts] ([0.2 pts] for each step of the three steps in the solution). Identifying the correct form of the matrix is worth [0.4 pts]. |
> | e) | Computing $U\cdot\vec E$ correctly for general $\theta$ is worth [0.4 pts]. Computing $UhU^T$ correctly for general $\theta$ is worth [0.8 pts]. Arriving to the right conclusion, that the spin of the photon is 1 and that of the graviton is 2 is worth [0.3pts]. If one only shows that there is a symmetry for $\theta=2\pi$ for electromagnetic waves and $\theta=\pi$ for gravitational waves but does not study the symmetries for general $\theta$ the solution will only receive [1 pt]. |
> | II.a) | Using the mass energy formula correctly is worth [0.6 pts]. Obtaining the flux correctly is worth another [0.6 pts]. Finally obtaining the numerical answer correctly is worth [0.3 pts] of which [0.1 pts] are accorded for giving the correct units. |
> | II.b) | Using the second law of thermodynamics correctly is worth [1.2 pts]. Using the mass energy relation together with the second law to obtain an inequality is worth [0.8 pts]. Arriving to the right conclusion about the energy percentage of gravitational waves is worth another [0.2 pts]. Obtaining the correct numerical bounds is worth [0.3 pts] of which [0.1 pts] are accorded for giving the correct units. |
