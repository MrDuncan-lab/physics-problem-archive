---
id: rompho-2014-intl-theory-t1
olympiad: RomPhO
year: 2014
stage: "Международная олимпиада"
round: теория
grade: ""
number: "T1"
title: "Circles all the way"
aliases: ["Circles all the way"]
topics: ["[[1.9 Кривизна траектории]]", "[[1.20 Колебания]]", "[[1.15 Упругость. Весомая пружина]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Вывести радиус кривизны траектории и исследовать колебания бусины и движение тела, соединённого с пружинами на окружности."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# PROBLEM 1: CIRCLES ALL THE WAY

**RomPhO 2014** · Международная олимпиада · теория · задача T1  
Источник: [[_pdf/RomPhO/RomPhO-2014-T1.pdf#page=1|условие, стр. 1–2]] · [[_pdf/RomPhO/RomPhO-2014-T1-solution.pdf#page=3|решение, стр. 3–8]]

Темы: [[1.9 Кривизна траектории]], [[1.20 Колебания]], [[1.15 Упругость. Весомая пружина]]

> [!abstract] Кратко (составлено моделью)
> Вывести радиус кривизны траектории и исследовать колебания бусины и движение тела, соединённого с пружинами на окружности.

*This problem has two parts.*

**A. Determining the radius of curvature of a planar curve by means of Mechanics**

Each infinitesimal length element of a curve can be thought as belonging to a circle with a certain radius (see Figure 1). This radius is called the *radius of curvature*. In order to determine the radius of curvature at some point of a planar curve, one can consider that the curve is the trajectory of a point-like object, and that the given point is the very object.

![[rompho-2014-t1-problems-p1-f1.svg]]
*Figure 1*

Let $y=f(x)$ be the equation of the curve, where $x$ and $y$ are the coordinates of the object.

**a.** Express the components $v_x$ and $v_y$ of the velocity of the object in terms of $x$ and its time derivatives, and $f(x)$ and its derivatives.

**b.** Let $a_t$ be the component of the acceleration vector parallel to the velocity. Express vector $\vec{a}_t$ in terms of $v_x$, $v_y$, the components $a_x$ and $a_y$ of the acceleration, and the unit vectors $\vec{i}$ and $\vec{j}$ of the $Ox$ and $Oy$ axes.

**c.** Express the magnitude (i.e. the absolute value) of the component $\vec{a}_n$ of the acceleration perpendicular to the velocity, in terms of $v_x$, $v_y$, $a_x$ and $a_y$.

**d.** Express the radius of curvature in terms of $f(x)$ and its derivatives.

**e.** Find the radius of curvature of the parabola $y=Ax^2$ ($A>0$) at a point having coordinate $x=x_0$.

**f.** Find the period of small oscillations performed by a bead on the bottom of a smooth surface of equation $y=\sin 2x$ [m]. You may use $g\approx\pi^2$ [m/s$^2$], where $g$ is the gravitational acceleration.

**B. Springs on a circle**

In this problem we will investigate the motion of a point-like object of mass $m$ connected to $N+1$ springs of stiffness $k$. The springs are attached to a circle of radius $R$ (see Figure 2) and have negligible natural length. The points to which the springs are attached are arranged uniformly on the circle such that, when the object is at the center of the circle, the angle between two adjacent springs is equal to $2\pi/(N+1)$. We label the springs 0 through $N$.

![[rompho-2014-t1-problems-p1-f3.png]]
*Figure 2*

Let angle $\alpha$ and the radial coordinate $r$ of the object be defined as in Figure 3. The object can move in the plane of the circle and we ignore the effects of gravity throughout the problem.

![[rompho-2014-t1-problems-p2-f1.png]]
*Figure 3*

**g.** Compute the length $l_n$ of the $n$-th spring for arbitrary $r$ and $\alpha$.

**h.** Write down the kinetic energy $E_{\mathrm{kin}}$ and the potential energy $E_{\mathrm{pot}}$ of the object in terms of $r$, $\alpha$, and their time derivatives. (Do not evaluate the sum in the potential energy just yet.)

**i.** Compute the sums

$$\sum_{n=0}^{N}\cos\left(\frac{2n\pi}{N+1}\right)\quad\text{and}\quad\sum_{n=0}^{N}\sin\left(\frac{2n\pi}{N+1}\right)$$

and use the results to evaluate $E_{\mathrm{pot}}$ for arbitrary $N$.

**j.** Show that the angular momentum $L$ is conserved.

**k.** Write down the implicit equation for $r$ in terms of $\mathcal{L}\equiv L/m$ and $\omega^2\equiv(N+1)k/m$.

**l.** Perform the substitution

$$r(t)=\sqrt{z^2(t)+K},$$

with $K$ an unspecified parameter, and obtain the equation “of motion” for $z(t)$.

Perhaps surprisingly, this equation admits oscillatory solutions $z(t)=A\cos(\omega t+\phi_0)$.

**m.** Show this, and determine $A$ in terms of $\mathcal{L}$, $K$, and $\omega$.

$K$ and $\phi_0$ can be thought of as integration constants to be specified by the initial conditions. Since the equation of motion is second order, and we have two integration constants, it means that this is the most general function describing the distance $r(t)$. On the other hand, one can notice that the equation for $r(t)$ remains unchanged on substituting $r$ with $-r$. Physically this is the same as substituting $\alpha$ with $\alpha+\pi$, which means that the distance from the center of the circle to the object is the same in any two opposing directions.

**n.** Write down $r(t)$ in terms of $\mathcal{L}$, $\omega$, $K$ and $\phi_0$. Is $r(t)$ periodic? Is the motion periodic? Do they both have the same period?

**o.** Describe the motion of the object when $L=0$.

**p.** Find out the possible value of $r$ at which the object could perform circular uniform motion.

Suppose now we remove the springs labeled $0$, $d$, $2d$, …, where $d$ divides $N+1$.

**q.** Argue that $r(t)$ derived in part **n.** continues to hold, but for a different value of $\omega$. What is this new value $\omega'$ in terms of $\omega$, $N$, and $d$?

> [!answer]- Ответ
> **a**
>
> $$
> v_x=\frac{\mathrm{d}x}{\mathrm{d}t}=\dot{x}
> $$
>
> **a**
>
> $$
> v_y=\frac{\mathrm{d}y}{\mathrm{d}t}=\frac{\mathrm{d}y}{\mathrm{d}x}\frac{\mathrm{d}x}{\mathrm{d}t}=f'(x)\cdot\dot{x}
> $$
>
> **b**
>
> $$
> \vec{a}_t=\frac{\vec{a}\vec{v}}{v}\cdot\frac{\vec{v}}{v}=\frac{a_xv_x+a_yv_y}{\sqrt{v_x^2+v_y^2}}\cdot\frac{v_x\vec{i}+v_y\vec{j}}{\sqrt{v_x^2+v_y^2}}=\frac{v_x(a_xv_x+a_yv_y)\vec{i}+v_y(a_xv_x+a_yv_y)\vec{j}}{v_x^2+v_y^2}
> $$
>
> **c**
>
> $$
> |   |   |   |   |
> |---|---|---|---|
> |\vec{a}_n|=\frac{|a_xv_y-a_yv_x|}{\sqrt{v_x^2+v_y^2}}
> $$
>
> **d**
>
> $$
> \begin{aligned}R&=\frac{v^2}{a_n}=\frac{\sqrt{v_x^2+v_y^2}^{\,3}}{|a_xv_y-a_yv_x|}\\ &=\frac{[\dot{x}^2+(f'(x)\cdot\dot{x})^2]^{3/2}}{|\ddot{x}\cdot f'(x)\cdot\dot{x}-(f''(x)\cdot\dot{x}^2+f'(x)\cdot\ddot{x})\cdot\dot{x}|}\\ &=\frac{|\dot{x}|^3[1+f'^2(x)]^{3/2}}{|\dot{x}^3\cdot f''(x)|}=\frac{[1+f'^2(x)]^{3/2}}{|f''(x)|}\end{aligned}
> $$
>
> **e**
>
> $$
> \left.\begin{aligned}f'(x_0)&=2Ax_0\\f''(x_0)&=2A\end{aligned}\right\}\Rightarrow R=\frac{(1+4A^2x_0^2)^{3/2}}{2A}
> $$
>
> **f**
>
> $$
> T=2\pi\sqrt{\frac{R}{g}}\approx1\,\mathrm{s}
> $$
>
> **g**
>
> $$
> l_n^2=R^2+r^2-2Rr\cos\left(\frac{2n\pi}{N+1}-\alpha\right)
> $$
>
> **h**
>
> $$
> E_{\mathrm{kin}}=\frac{m(\dot r^2+r^2\dot\alpha^2)}2
> $$
>
> **h**
>
> $$
> E_{\mathrm{pot}}=\sum_{n=0}^N\frac{kl_n^2}2=\frac{k}{2}\sum_{n=0}^N\left[R^2+r^2-2Rr\cos\left(\frac{2n\pi}{N+1}-\alpha\right)\right]
> $$
>
> **i**
>
> $$
> \sum_{n=0}^N\cos\left(\frac{2n\pi}{N+1}\right)=\sum_{n=0}^N\sin\left(\frac{2n\pi}{N+1}\right)=0
> $$
>
> **i**
>
> $$
> E_{\mathrm{pot}}=\frac{k}{2}\left[\sum_{n=0}^N(R^2+r^2)-2Rr\sum_{n=0}^N\cos\left(\frac{2n\pi}{N+1}-\alpha\right)\right]=\frac{N+1}{2}k(R^2+r^2)
> $$
>
> **k**
>
> $$
> \ddot r-\mathcal L^2r^{-3}+\omega^2r=0
> $$
>
> **l**
>
> $$
> (\ddot z+\omega^2z)z^3+K\ddot z z+K\dot z^2+2K\omega^2z^2+K^2\omega^2-\mathcal L^2=0
> $$
>
> **m**
>
> $$
> K\omega^2A^2+K^2\omega^2-\mathcal L^2=0\Rightarrow A^2=\frac{\mathcal L^2}{K\omega^2}-K
> $$
>
> **n**
>
> $$
> \begin{aligned}r(t)&=\sqrt{\frac{\mathcal L^2-K^2\omega^2}{K\omega^2}\cos^2(\omega t+\phi_0)+K}\\&=\frac1\omega\sqrt{\frac{\mathcal L^2\cos^2(\omega t+\phi_0)+K^2\omega^2\sin^2(\omega t+\phi_0)}{K}}\\&=\frac1{\omega\sqrt{2K}}\sqrt{\mathcal L^2[1+\cos(2\omega t+2\phi_0)]+K^2\omega^2[1-\cos(2\omega t+2\phi_0)]}\\&=\frac1{\omega\sqrt{2K}}\sqrt{(\mathcal L^2+K^2\omega^2)+(\mathcal L^2-K^2\omega^2)\cos(2\omega t+2\phi_0)}\end{aligned}
> $$
>
> **n**
>
> $$
> T_r=\frac{2\pi}{2\omega}
> $$
>
> **n**
>
> $$
> T=2\pi\sqrt{\frac1{N+1}\frac{m}{k}}
> $$
>
> **p**
>
> $$
> r=\mathrm{constant}=\sqrt K\Rightarrow\mathcal L^2-K^2\omega^2=0\Rightarrow\left|\frac Lm\right|=K\sqrt{\frac{k}{m}}(N+1)\Rightarrow r=\sqrt{\frac{|L|}{\sqrt{(N+1)mk}}}
> $$
>
> **q**
>
> $$
> \omega'^2=\left[N+1-\frac{N+1}{d}\right]\frac{k}{m}\Rightarrow\omega'=\omega\sqrt{1-\frac1d}
> $$

> [!solution]- Решение
> # PROBLEM 1: MECHANICS
>
> **A. Determining the radius of curvature of a planar curve by means of Mechanics**
>
> **a. 1.0 point**
>
> $$v_x=\frac{\mathrm{d}x}{\mathrm{d}t}=\dot{x}$$
>
> $$v_y=\frac{\mathrm{d}y}{\mathrm{d}t}=\frac{\mathrm{d}y}{\mathrm{d}x}\frac{\mathrm{d}x}{\mathrm{d}t}=f'(x)\cdot\dot{x}$$
>
> **b. 1.0 point**
>
> $$a_x=\frac{\mathrm{d}v_x}{\mathrm{d}t}=\dot{v}_x=\ddot{x}$$
> $$a_y=\frac{\mathrm{d}v_y}{\mathrm{d}t}=\frac{\mathrm{d}}{\mathrm{d}t}[f'(x)\cdot\dot{x}]=f''(x)\cdot\dot{x}^2+f'(x)\cdot\ddot{x}$$
>
> $$\vec{a}_t=\frac{\vec{a}\vec{v}}{v}\cdot\frac{\vec{v}}{v}=\frac{a_xv_x+a_yv_y}{\sqrt{v_x^2+v_y^2}}\cdot\frac{v_x\vec{i}+v_y\vec{j}}{\sqrt{v_x^2+v_y^2}}=\frac{v_x(a_xv_x+a_yv_y)\vec{i}+v_y(a_xv_x+a_yv_y)\vec{j}}{v_x^2+v_y^2}$$
>
> **c. 1.0 point**
>
> $$\begin{aligned}\vec{a}_n&=\vec{a}-\vec{a}_t\\ &=a_x\vec{i}+a_y\vec{j}-\frac{v_x(a_xv_x+a_yv_y)\vec{i}+v_y(a_xv_x+a_yv_y)\vec{j}}{v_x^2+v_y^2}\\ &=\frac{[a_x(v_x^2+v_y^2)-v_x(a_xv_x+a_yv_y)]\vec{i}+[a_y(v_x^2+v_y^2)-v_y(a_xv_x+a_yv_y)]\vec{j}}{v_x^2+v_y^2}\\ &=\frac{(a_xv_y^2-a_yv_xv_y)\vec{i}+(a_yv_x^2-a_xv_xv_y)\vec{j}}{v_x^2+v_y^2}\\ &=\frac{(a_xv_y-a_yv_x)(v_y\vec{i}-v_x\vec{j})}{v_x^2+v_y^2}\end{aligned}$$
>
> $$|\vec{a}_n|=\frac{|a_xv_y-a_yv_x|}{\sqrt{v_x^2+v_y^2}}$$
>
> **d. 0.5 point**
>
> $$\begin{aligned}R&=\frac{v^2}{a_n}=\frac{\sqrt{v_x^2+v_y^2}^{\,3}}{|a_xv_y-a_yv_x|}\\ &=\frac{[\dot{x}^2+(f'(x)\cdot\dot{x})^2]^{3/2}}{|\ddot{x}\cdot f'(x)\cdot\dot{x}-(f''(x)\cdot\dot{x}^2+f'(x)\cdot\ddot{x})\cdot\dot{x}|}\\ &=\frac{|\dot{x}|^3[1+f'^2(x)]^{3/2}}{|\dot{x}^3\cdot f''(x)|}=\frac{[1+f'^2(x)]^{3/2}}{|f''(x)|}\end{aligned}$$
>
> **e. 0.5 point**
>
> $$\left.\begin{aligned}f'(x_0)&=2Ax_0\\f''(x_0)&=2A\end{aligned}\right\}\Rightarrow R=\frac{(1+4A^2x_0^2)^{3/2}}{2A}$$
>
> **f. 0.5 point**
>
> $$f(x_0)=-1\Rightarrow\sin 2x_0=-1\Rightarrow x_0=\frac34\pi$$
> $$\left.\begin{aligned}f'(x_0)&=2\cos\left(2\cdot\frac34\pi\right)=0\\f''(x_0)&=-4\sin\left(2\cdot\frac34\pi\right)=4\end{aligned}\right\}\Rightarrow R=\frac14=0.25\,\mathrm{m}$$
>
> $$T=2\pi\sqrt{\frac{R}{g}}\approx1\,\mathrm{s}$$
>
> **B. Springs on a circle**
>
> ![[rompho-2014-t1-solutions-p5-c3812.png]]
>
> **g. 0.5 point**
>
> According to the cosine rule:
>
> $$l_n^2=R^2+r^2-2Rr\cos\left(\frac{2n\pi}{N+1}-\alpha\right)$$
>
> **h. 0.25 point + 0.25 point**
>
> $$E_{\mathrm{kin}}=\frac{m(\dot r^2+r^2\dot\alpha^2)}2$$
>
> $$E_{\mathrm{pot}}=\sum_{n=0}^N\frac{kl_n^2}2=\frac{k}{2}\sum_{n=0}^N\left[R^2+r^2-2Rr\cos\left(\frac{2n\pi}{N+1}-\alpha\right)\right]$$
>
> **i. 0.25 point + 0.25 point**
>
> One can use the sum of a geometric progression having complex terms.
>
> $$\begin{aligned}\sum_{n=0}^N\left[\cos\left(\frac{2n\pi}{N+1}\right)+i\sin\left(\frac{2n\pi}{N+1}\right)\right]&=\sum_{n=0}^N e^{i\frac{2n\pi}{N+1}}\\&=\frac{(e^{i\frac{2\pi}{N+1}})^{N+1}-1}{e^{i\frac{2\pi}{N+1}}-1}\\&=\frac{\cos 2\pi+i\sin 2\pi-1}{\cos\left(\frac{2\pi}{N+1}\right)+i\sin\left(\frac{2\pi}{N+1}\right)-1}=0\end{aligned}$$
>
> So
>
> $$\sum_{n=0}^N\cos\left(\frac{2n\pi}{N+1}\right)=\sum_{n=0}^N\sin\left(\frac{2n\pi}{N+1}\right)=0$$
>
> $$E_{\mathrm{pot}}=\frac{k}{2}\left[\sum_{n=0}^N(R^2+r^2)-2Rr\sum_{n=0}^N\cos\left(\frac{2n\pi}{N+1}-\alpha\right)\right]=\frac{N+1}{2}k(R^2+r^2)$$
>
> **j. 0.5 point**
>
> ![[rompho-2014-t1-solutions-p6-c3514.png]]
>
> The force with which the $n$-th spring is acting on the object is
> $$F_n=kl_n$$
> According to the sine rule,
> $$\frac{\sin(\pi-\gamma)}{R}=\frac{\sin\left(\frac{2n\pi}{N+1}-\alpha\right)}{l_n}$$
> The torque of $F_n$ equals
> $$M_n=r\cdot F_n\sin\gamma=r\cdot kl_n\cdot\frac{R\sin\left(\frac{2n\pi}{N+1}-\alpha\right)}{l_n}=kRr\sin\left(\frac{2n\pi}{N+1}-\alpha\right)$$
> The total torque equals
> $$M=\sum_{n=0}^N M_n=\sum_{n=0}^N kRr\sin\left(\frac{2n\pi}{N+1}-\alpha\right)=0$$
> So the angular momentum is indeed constant.
> $$L=mr^2\dot\alpha$$
>
> **k. 0.5 point**
>
> $$E=E_{\mathrm{kin}}+E_{\mathrm{pot}}=\frac12m\left(\dot r^2+\frac{L^2}{m^2r^2}\right)+\frac12k(N+1)(R^2+r^2)=\mathrm{constant}\Rightarrow$$
> $$\dot E=m\left(\dot r\ddot r-\frac{L^2}{m^2}r^{-3}\dot r\right)+k(N+1)r\dot r=0\Rightarrow$$
>
> $$\ddot r-\mathcal L^2r^{-3}+\omega^2r=0$$
>
> **l. 0.5 point**
>
> $$\dot r=\frac{2z\dot z}{2\sqrt{z^2+K}}=\frac{z\dot z}{r}\Rightarrow$$
> $$\ddot r=\frac{(\dot z^2+z\ddot z)r-z\dot z\dot r}{r^2}=\frac{\dot z^2+z\ddot z}{r}-\frac{z\dot z}{r^2}\cdot\frac{z\dot z}{r}\Rightarrow$$
>
> $$\frac{\dot z^2+z\ddot z}{r}-\frac{z^2\dot z^2}{r^3}-\frac{\mathcal L^2}{r^3}+\omega^2r=0$$
> $$(\dot z^2+z\ddot z)(z^2+K)-z^2\dot z^2-\mathcal L^2+\omega^2(z^2+K)^2=0$$
>
> $$(\ddot z+\omega^2z)z^3+K\ddot z z+K\dot z^2+2K\omega^2z^2+K^2\omega^2-\mathcal L^2=0$$
>
> **m. 0.5 point**
>
> The first term of the equation cancels anyway.
> $$-K\omega^2A^2\cos^2(\omega t+\phi_0)+K\omega^2A^2\sin^2(\omega t+\phi_0)+2K\omega^2A^2\cos^2(\omega t+\phi_0)+K^2\omega^2-\mathcal L^2=0$$
>
> $$K\omega^2A^2+K^2\omega^2-\mathcal L^2=0\Rightarrow A^2=\frac{\mathcal L^2}{K\omega^2}-K$$
>
> **n. 0.5 point**
>
> $$\begin{aligned}r(t)&=\sqrt{\frac{\mathcal L^2-K^2\omega^2}{K\omega^2}\cos^2(\omega t+\phi_0)+K}\\&=\frac1\omega\sqrt{\frac{\mathcal L^2\cos^2(\omega t+\phi_0)+K^2\omega^2\sin^2(\omega t+\phi_0)}{K}}\\&=\frac1{\omega\sqrt{2K}}\sqrt{\mathcal L^2[1+\cos(2\omega t+2\phi_0)]+K^2\omega^2[1-\cos(2\omega t+2\phi_0)]}\\&=\frac1{\omega\sqrt{2K}}\sqrt{(\mathcal L^2+K^2\omega^2)+(\mathcal L^2-K^2\omega^2)\cos(2\omega t+2\phi_0)}\end{aligned}$$
>
> $$T_r=\frac{2\pi}{2\omega}$$
> But since the values of $r$ repeat after every rotation by $\pi$, it means that the period of the motion is
>
> $$T=2\pi\sqrt{\frac1{N+1}\frac{m}{k}}$$
>
> **o. 0.5 point**
>
> $$L=0\Rightarrow\mathcal L=0\Rightarrow r(t)=\sqrt K|\sin(\omega t+\phi_0)|$$
> $$L=0\Rightarrow\dot\alpha=0\Rightarrow\alpha=\mathrm{constant}$$
> According to the previous part, except for the moments when $r=0$ and $\alpha$ is not defined, there will be two constant values for $\alpha$, corresponding to two opposing directions. So in this case the object will perform simple harmonic motion with amplitude $\sqrt K$.
>
> **p. 0.5 point**
>
> $$r=\mathrm{constant}=\sqrt K\Rightarrow\mathcal L^2-K^2\omega^2=0\Rightarrow\left|\frac Lm\right|=K\sqrt{\frac{k}{m}}(N+1)\Rightarrow r=\sqrt{\frac{|L|}{\sqrt{(N+1)mk}}}$$
>
> **q. 0.5 point**
>
> We can think of this situation as having $N+1$ springs of positive constant $k$ and another $(N+1)/d$ springs of “negative” stiffness $-k$. The potential energy $E_{\mathrm{pot}}$ derived in **i.** holds for both ensembles (with appropriate $N$ and $k$) and angular momentum is still conserved. Thus all the results from part **j.** onwards continue to hold if we replace $(N+1)$ by $(N+1)+[-(N+1)/d]$. Thus
>
> $$\omega'^2=\left[N+1-\frac{N+1}{d}\right]\frac{k}{m}\Rightarrow\omega'=\omega\sqrt{1-\frac1d}$$
