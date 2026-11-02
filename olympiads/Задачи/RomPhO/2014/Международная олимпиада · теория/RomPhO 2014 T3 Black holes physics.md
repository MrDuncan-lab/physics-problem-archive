---
id: rompho-2014-intl-theory-t3
olympiad: RomPhO
year: 2014
stage: "Международная олимпиада"
round: теория
grade: ""
number: "T3"
title: "Black holes physics"
aliases: ["Black holes physics"]
topics: ["[[1 Механика]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Исследовать радиальное падение наблюдателя к чёрной дыре и определить ускорение, скорость и времена достижения горизонта событий."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# PROBLEM 3: BLACK HOLES PHYSICS

**RomPhO 2014** · Международная олимпиада · теория · задача T3  
Источник: [[_pdf/RomPhO/RomPhO-2014-T3.pdf#page=1|условие, стр. 1–3]] · [[_pdf/RomPhO/RomPhO-2014-T3-solution.pdf#page=4|решение, стр. 4–8]]

Темы: [[1 Механика]]

> [!abstract] Кратко (составлено моделью)
> Исследовать радиальное падение наблюдателя к чёрной дыре и определить ускорение, скорость и времена достижения горизонта событий.

*In this problem we will explore the physics of black holes – astrophysical objects so massive that no object, not even a photon, can escape from if it gets sufficiently close. Because black holes are extremely massive, in their vicinity Newton’s theory of gravity breaks down and one is forced to use Einstein’s general theory of relativity to obtain a correct description of their physics.*

Any black hole in the physical universe is uniquely specified by exactly three quantities: its mass $M$, angular momentum $J$, and charge $Q$. In addition to these, a black hole also has a *space-time singularity* and an *event horizon*, which is the surface surrounding the central singularity which can only be crossed “going in”. Any photon or object which falls through the event horizon will not be able to exit back out and will eventually hit the central singularity.

It is convenient to describe the spacetime of non-rotating black holes by four coordinates: $t$, $r$, $\theta$ and $\phi$, with $0\leq\theta\leq\pi$ and $0\leq\phi\leq2\pi$. These can be thought of as the usual spherical coordinates plus time. Because the geometry is no longer flat, the infinitesimal spacetime interval is given by

$$(ds)^2=-c^2f(dt)^2+\frac{(dr)^2}{g}+r^2(d\theta)^2+r^2\sin^2\theta(d\phi)^2\tag{1}$$

with $f$ and $g$ functions of the four coordinates. For spherically symmetric uncharged black holes (known as *Schwarzschild black holes*), $f$ and $g$ are functions of the radial coordinate $r$ only, and are given by

$$f(r)=g(r)=1-\frac{r_S}{r},\tag{2}$$

where $r_S$, the *Schwarzschild radius*, is the radial coordinate of the event horizon.

**a.** Write down the infinitesimal spacetime interval $(ds)^2$ for Minkowski spacetime in spherical coordinates, using the signature given above ($-$, $+$, $+$, $+$).

Suppose an observer is initially at rest ($dr/dt=0$, $d\theta/dt=d\phi/dt=0$) at radial coordinate $r_0>r_S$. Under the gravitational pull of the black hole he will start falling towards the event horizon, moving only along the radial direction (and thus keeping $\theta$ and $\phi$ constant at all times). Let $t'$ be the proper time measured by the observer’s clock. The correct general relativistic relation between elapsed proper time $dt'$, elapsed coordinate time $dt$ and radial coordinate change $dr$ is (you don’t have to show this)

$$\frac{d^2r}{dt'^2}+\frac{r_Sc^2}{2r^2}\left(1-\frac{r_S}{r}\right)\left(\frac{dt}{dt'}\right)^2-\frac{r_S}{2r^2}\frac1{1-\frac{r_S}{r}}\left(\frac{dr}{dt'}\right)^2=0.\tag{3}$$

**b.** From equations (1) - (3) compute the proper acceleration $a\equiv d^2r/dt'^2$ in terms of $c$, the speed of light in empty space, $r$, and $r_S$.

**Hint:** The spacetime interval $(ds)^2$ is the same in all reference frames.

**c.** Even without resorting to any calculation, it should be expected that the Newtonian expression for $a$ can be recovered in the large $r$ (i.e. small $M$) limit of the relativistic expression. However, now that you have done the calculation, can you make a stronger statement? Determine $r_S$ in terms of $M$, the black hole’s mass, $c$, and $G$, the gravitational constant.

**d.** Compute the proper velocity $v\equiv dr/dt'$ as a function of $r$, in terms of $M$ and $r_0$ and $G$.

**e.** Using that

$$\int\sqrt{\frac{x}{1-x}}\,dx=-\sqrt{x(1-x)}-\arccos(\sqrt{x})+C,\tag{4}$$

compute the proper time $t'$ after which the observer reaches the event horizon. Write the result in terms of $r_0$, $M$, $G$ and $c$.

The results of parts **a. - c.** may lead one to speculate that general relativity is not that different from Newtonian mechanics after all. This is a misleading interpretation, as the two theories differ significantly in many aspects.

**f.** To highlight one such aspect, calculate the coordinate time $t$ it takes for the observer to reach the event horizon. Are you surprised?

**Hint:** You do not need to determine the antiderivative in order to compute what the integral equals.

We now turn towards the thermodynamical properties of black holes. If only classical physics is taken into account, black holes do not emit any form of radiation and can thus be considered to have zero temperature. However, in 1974 physicist Stephen Hawking proved that once quantum corrections are considered, black holes emit radiation according to the blackbody spectrum (you do not need to show this). The corresponding blackbody temperature is known as the *Hawking temperature*, $T_H$, and can be thought of as the temperature of the black hole. For a Schwarzschild black hole of mass $M$, the Hawking temperature is equal to

$$T_H=\frac{\hbar c^3}{8\pi Gk_BM},\tag{5}$$

where $\hbar$ is the Planck constant and $k_B$ is the Boltzmann constant.

**g.** Using equation (5) compute the entropy $S$ of a Schwarzschild black hole. Express it in terms of $c$, $G$, $\hbar$, $k_B$, and the *horizon area*, $A=4\pi r_S^2$.

**Hint:** Think of Einstein’s famous formula.

The result from part **g.** suggests that at the classical level (i.e. ignoring quantum corrections) the total area of black holes involved in any physical process can never decrease. This is indeed true and has been formalized into a theorem by Hawking in 1971.

**h.** Using the above theorem compute the maximum amount of energy that can be radiated as gravitational waves in the merger of two Schwarzschild black holes of masses $M_1$ and $M_2$, assuming the black holes were initially at rest when far away.

We now return to the subject of Hawking temperature. While Hawking’s 1974 derivation of $T_H$ was somewhat technical, in parts **i. - k.** we will rederive his result using a much simpler argument. Take an infinitesimal spacetime interval of the form (1) with the functions depending only on the radial coordinate $r$,

$$(ds)^2=-c^2F(r)(dt)^2+\frac{(dr)^2}{G(r)}+r^2(d\theta)^2+r^2\sin^2\theta(d\phi)^2,\tag{6}$$

and suppose that $F(r)$ and $G(r)$ have a first order zero at $r_h$, that is $F(r_h)=G(r_h)=0$, but $F'(r_h)\ne0$ and $G'(r_h)\ne0$. Consider only the $(t,r)$ part of $(ds)^2$ and analytically continue the coordinate time $t$ to “imaginary time” $\tau$ via $t\to i\tau$, so that the signature of the spacetime interval becomes Euclidean and the infinitesimal spacetime element $ds$ becomes an infinitesimal element of ordinary length,

$$(ds)^2=\frac{(dr)^2}{G(r)}+c^2F(r)(d\tau)^2\tag{7}$$

The length element $ds$ now describes how distances are measured on an ordinary 2-dimensional plane, with the origin corresponding to $r=r_h$ and $r\geq r_h$ for any point on the plane. This coordinate system is an analogue of polar coordinates, in that $r$ can be thought of as a radial coordinate, and $\tau$ as an angular coordinate that must be periodic with some period $P$.

**i.** Write down the distance $R$ from the origin to a point of coordinate $r=r_h+\varepsilon$ that is infinitesimally close to the origin. Express your answer in terms of $\varepsilon$ and $G'(r_h)$.

**j.** Write down the circumference $L$ of a circle of radial coordinate $r_h+\varepsilon$ around the origin, with $\varepsilon$ infinitesimal. Express your answer in terms of $P$, $\varepsilon$ and $F'(r_h)$.

**k.** By imposing the condition that the plane is not singular at the origin, that is that $L=2\pi R$, determine the period $P$ of the $\tau$ coordinate. From field-theoretic arguments this period must be equal to $\hbar c/k_BT_H$. Solve for the Hawking temperature and recover equation (5) for $F(r)=G(r)=1-2GM/(c^2r)$.

**l.** Compute the black hole’s heat capacity $C$ in terms of $G$, $c$, $\hbar$, $k_B$ and $T_H$.

We now consider black hole evaporation. Assuming no infalling matter or energy, a black hole will slowly radiate away its mass via *Hawking radiation photons*. Although a correct treatment of the evaporation process at high energy scales requires a theory of quantum gravity, as long as $T_H$ is below the Planck scale the semi-classical approach we’ve been using so far suffices. In what follows we will obtain an estimate of the black hole evaporation timescale, ignoring Planck regime complications. Since at the semi-classical level the black hole spends most of its life below the Planck scale, this will be a lower bound on the estimate of the evaporation process duration.

**m.** Assuming black holes obey the blackbody law, compute the power $W$ emitted by a black hole of mass $M$. Use that the Stefan-Boltzmann constant is

$$\sigma=\frac{\pi^2k_B^4}{60\hbar^3c^2},\tag{8}$$

and express your result in terms of $G$, $c$, $\hbar$ and $M$.

**n.** Compute the evaporation time $\tau$ in terms of $M$, assuming the result from the previous part holds at all energy scales. Compare with the age of the universe for a black hole of mass $10M_\odot=2\cdot10^{31}\,\mathrm{kg}$. Use that $G=6.67\cdot10^{-11}\,\mathrm{m^3/(s^2kg)}$, $\hbar=1.05\cdot10^{-34}\,\mathrm{m^2kg/s}$, $c=3\cdot10^8\,\mathrm{m/s}$.

> [!answer]- Ответ
> **a**
>
> $$
> (ds)^2=-c^2(dt)^2+(dr)^2+r^2(d\theta)^2+r^2\sin^2\theta(d\phi)^2
> $$
>
> **b**
>
> $$
> a=\frac{d^2r}{dt'^2}=-\frac{r_Sc^2}{2r^2}
> $$
>
> **c**
>
> $$
> a=-\frac{GM}{r^2}\Rightarrow r_S=\frac{2GM}{c^2}
> $$
>
> **d**
>
> $$
> v=-c\sqrt{r_S\left(\frac1r-\frac1{r_0}\right)}=-\sqrt{\frac{2GM}{r_0}\left(\frac{r_0}{r}-1\right)}
> $$
>
> **e**
>
> $$
> \begin{aligned}t'&=\int_{r_0}^{r_S}\left(-\frac1c\right)\sqrt{\frac{r_0}{r_S}\frac{r/r_0}{1-r/r_0}}\,dr\\&=\frac{r_0}{c}\sqrt{\frac{r_0}{r_S}}\left[-\left.\sqrt{x(1-x)}\right|_{r_S/r_0}^{1}-\left.\arccos(\sqrt x)\right|_{r_S/r_0}^{1}\right]\\&=\frac{r_0}{c}\sqrt{\frac{r_0}{r_S}}\left[\sqrt{\frac{r_S}{r_0}\left(1-\frac{r_S}{r_0}\right)}+\arccos\left(\sqrt{\frac{r_S}{r_0}}\right)\right]\\&=\frac{r_0}{c}\left[\sqrt{\left(1-\frac{2GM}{c^2r_0}\right)}+\sqrt{\frac{c^2r_0}{2GM}}\arccos\left(\sqrt{\frac{2GM}{c^2r_0}}\right)\right]\end{aligned}
> $$
>
> **f**
>
> $$
> \int_{r=r_0}^{r=r_S}dt>\int_{r_S}^{r_0}\frac{r_S}{c}\cdot\frac1{r-r_S}\,dr=\infty
> $$
>
> **g**
>
> $$
> S=\frac{4\pi Gk_BM^2}{\hbar c}=\frac{4\pi Gk_B}{\hbar c}\cdot\frac{r_S^2c^4}{4G^2}=\frac{k_Bc^3}{4G\hbar}A
> $$
>
> **h**
>
> $$
> E_{\max}=(M_1+M_2-\sqrt{M_1^2+M_2^2})c^2
> $$
>
> **i**
>
> $$
> R=\int_{r_h}^{r_h+\varepsilon}ds=\frac1{\sqrt{G'(r_h)}}\cdot\left.2\sqrt{r-r_h}\right|_{r_h}^{r_h+\varepsilon}=\frac{2\sqrt\varepsilon}{\sqrt{G'(r_h)}}
> $$
>
> **j**
>
> $$
> L=\int_0^P ds=\sqrt{F'(r_h)\cdot\varepsilon}\cdot P
> $$
>
> **k**
>
> $$
> \sqrt{F'(r_h)\cdot\varepsilon}\cdot P=2\pi\frac{2\sqrt\varepsilon}{\sqrt{G'(r_h)}}\Rightarrow P=\frac{4\pi}{\sqrt{F'(r_h)\cdot G'(r_h)}}=4\pi r_S
> $$
>
> **k**
>
> $$
> 4\pi\frac{2GM}{c^2}=\frac{\hbar c}{k_BT_H}\Rightarrow T_H=\frac{\hbar c^3}{8\pi Gk_BM}
> $$
>
> **l**
>
> $$
> C=\frac{dU}{dT_H}=\frac{d(Mc^2)}{dT_H}=c^2\frac{d\left(\frac{\hbar c^3}{8\pi Gk_BT_H}\right)}{dT_H}=-\frac{\hbar c^5}{8\pi Gk_BT_H^2}
> $$
>
> **m**
>
> $$
> W=\sigma T_H^4A=\frac{\pi^2k_B^4}{60\hbar^3c^2}\cdot\frac{\hbar^4c^{12}}{8^4\pi^4G^4k_B^4M^4}\cdot4\pi\cdot\frac{4G^2M^2}{c^4}=\frac{\hbar c^6}{15360\pi G^2M^2}
> $$
>
> **n**
>
> $$
> \tau=\int_0^\tau dt=-\frac{15360\pi G^2}{\hbar c^4}\int_M^0 M^2dM=\frac{5120\pi G^2M^3}{\hbar c^4}
> $$

> [!solution]- Решение
> Barem de evaluare şi de notare
>
> Se punctează în mod corespunzător oricare altă modalitate de rezolvare corectă a problemei
>
> # PROBLEM 3: BLACK HOLES PHYSICS
>
> **a. 1.0 point**
>
> For Minkovski (flat) spacetime $f(r)=g(r)=1$.
>
> $$(ds)^2=-c^2(dt)^2+(dr)^2+r^2(d\theta)^2+r^2\sin^2\theta(d\phi)^2$$
>
> **b. 1.0 point**
>
> $$(ds)^2=-c^2\left(1-\frac{r_S}{r}\right)(dt)^2+\frac{(dr)^2}{1-\frac{r_S}{r}}=-c^2(dt')^2\Rightarrow$$
> $$\left(1-\frac{r_S}{r}\right)\left(\frac{dt}{dt'}\right)^2-\frac{\left(\frac{dr}{dt'}\right)^2}{c^2\left(1-\frac{r_S}{r}\right)}=1\Rightarrow$$
> $$\frac{d^2r}{dt'^2}+\frac{r_Sc^2}{2r^2}\left[1+\frac{\left(\frac{dr}{dt'}\right)^2}{c^2\left(1-\frac{r_S}{r}\right)}\right]-\frac{r_S}{2r^2}\frac1{1-\frac{r_S}{r}}\left(\frac{dr}{dt'}\right)^2=0\Rightarrow$$
>
> $$a=\frac{d^2r}{dt'^2}=-\frac{r_Sc^2}{2r^2}$$
>
> **c. 0.5 point**
>
> The observer will always experience the same acceleration as in the classical case.
>
> $$a=-\frac{GM}{r^2}\Rightarrow r_S=\frac{2GM}{c^2}$$
>
> **d. 1.0 point**
>
> $$a=\frac{dv}{dt'}=\frac{dv}{dr}\frac{dr}{dt'}=\frac12\frac{d(v^2)}{dr}=-\frac{r_Sc^2}{2r^2}\Rightarrow$$
> $$d(v^2)=r_Sc^2\frac1{r^2}dr\Rightarrow v^2=r_Sc^2\frac1r+C$$
> From the initial conditions, $C=-r_Sc^2/r_0$, so
>
> $$v=-c\sqrt{r_S\left(\frac1r-\frac1{r_0}\right)}=-\sqrt{\frac{2GM}{r_0}\left(\frac{r_0}{r}-1\right)}$$
> Again, from the standpoint of the observer this is just the classical result.
>
> **e. 0.5 point**
>
> $$dt'=\frac{dr}{v}=-\frac1c\sqrt{\frac{r_0r}{r_S(r-r_0)}}dr\Rightarrow$$
>
> $$\begin{aligned}t'&=\int_{r_0}^{r_S}\left(-\frac1c\right)\sqrt{\frac{r_0}{r_S}\frac{r/r_0}{1-r/r_0}}\,dr\\&=\frac{r_0}{c}\sqrt{\frac{r_0}{r_S}}\left[-\left.\sqrt{x(1-x)}\right|_{r_S/r_0}^{1}-\left.\arccos(\sqrt x)\right|_{r_S/r_0}^{1}\right]\\&=\frac{r_0}{c}\sqrt{\frac{r_0}{r_S}}\left[\sqrt{\frac{r_S}{r_0}\left(1-\frac{r_S}{r_0}\right)}+\arccos\left(\sqrt{\frac{r_S}{r_0}}\right)\right]\\&=\frac{r_0}{c}\left[\sqrt{\left(1-\frac{2GM}{c^2r_0}\right)}+\sqrt{\frac{c^2r_0}{2GM}}\arccos\left(\sqrt{\frac{2GM}{c^2r_0}}\right)\right]\end{aligned}$$
> And once again this is just the classic result for a falling body.
>
> **f. 0.5 point**
> $$\left(1-\frac{r_S}{r}\right)\left(\frac{dt}{dt'}\right)^2-\frac{v^2}{c^2\left(1-\frac{r_S}{r}\right)}=1\Rightarrow$$
>
> $$\frac{r-r_S}{r}\left(\frac{dt}{dt'}\right)^2=1+\frac{c^2\frac{r_S(r_0-r)}{r_0r}}{c^2\frac{r-r_S}{r}}\Rightarrow$$
> $$\left(\frac{dt}{dt'}\right)^2=\frac{r}{r-r_S}\cdot\frac{r_0r-r_Sr}{r_0(r-r_S)}\Rightarrow$$
>
> $$dt=dt'\cdot\frac{r}{r-r_S}\sqrt{\frac{r_0-r_S}{r_0}}=-\frac{dr}{c}\cdot\frac{r}{r-r_S}\sqrt{\frac{r_0-r_S}{r_0}}\sqrt{\frac{r_0r}{r_S(r_0-r)}}=\frac{|dr|}{c}\cdot\frac{r}{r-r_S}\sqrt{\frac{r}{r_S}\cdot\frac{r_0-r_S}{r_0-r}}$$
> But
> $$\left.\begin{aligned}\frac r{r_S}&>1\\\frac{r_0-r_S}{r_0-r}&>1\\\frac r{r-r_S}&>\frac r{r-r_S}\end{aligned}\right\}\Rightarrow dt>\frac{|dr|}{c}\cdot\frac{r_S}{r-r_S}\Rightarrow$$
>
> $$\int_{r=r_0}^{r=r_S}dt>\int_{r_S}^{r_0}\frac{r_S}{c}\cdot\frac1{r-r_S}\,dr=\infty$$
> So from the point of view of someone outside the black hole, the falling observer remains frozen just outside the black hole’s rim for an eternity, never crossing the event horizon!! Of course, this result is just an approximation, valid in the idealized regime in which the falling observer’s effect on the gravitational field (spacetime) can be ignored.
>
> **g. 1.0 point**
> $$dS=\frac{dU}{T}=\frac{d(Mc^2)}{\frac{\hbar c^3}{8\pi Gk_BM}}=\frac{8\pi Gk_B}{\hbar c}MdM$$
> By definition and common sense, no black hole, no entropy. So
>
> $$S=\frac{4\pi Gk_BM^2}{\hbar c}=\frac{4\pi Gk_B}{\hbar c}\cdot\frac{r_S^2c^4}{4G^2}=\frac{k_Bc^3}{4G\hbar}A$$
>
> **h. 0.5 point**
> $$E_{\mathrm{radiated}}=(M_1+M_2-M_{1+2})c^2$$
> $$S_{1+2}\geq S_1+S_2\Rightarrow A_{1+2}\geq A_1+A_2\Rightarrow M_{1+2}^2\geq M_1^2+M_2^2\Rightarrow$$
>
> $$E_{\max}=(M_1+M_2-\sqrt{M_1^2+M_2^2})c^2$$
>
> **i. 0.5 point**
> $$ds=\frac{dr}{\sqrt{G(r)}}\approx\frac{dr}{\sqrt{G'(r_h)\cdot(r-r_h)}}\Rightarrow$$
>
> $$R=\int_{r_h}^{r_h+\varepsilon}ds=\frac1{\sqrt{G'(r_h)}}\cdot\left.2\sqrt{r-r_h}\right|_{r_h}^{r_h+\varepsilon}=\frac{2\sqrt\varepsilon}{\sqrt{G'(r_h)}}$$
>
> **j. 0.5 point**
> $$F(r)\approx F'(r_h)\cdot(r-r_h)$$
> $$ds=c\sqrt{F(r_h+\varepsilon)}d\tau\approx\sqrt{F'(r_h)\cdot\varepsilon}\cdot d(c\tau)$$
>
> $$L=\int_0^P ds=\sqrt{F'(r_h)\cdot\varepsilon}\cdot P$$
>
> **k. 1.0 point**
>
> $$F(r_h)=G(r_h)=0\Rightarrow1-\frac{2GM}{c^2r_h}=0\Rightarrow r_h=r_S$$
> $$F'(r_h)=G'(r_h)=\frac1{r_S}$$
>
> $$\sqrt{F'(r_h)\cdot\varepsilon}\cdot P=2\pi\frac{2\sqrt\varepsilon}{\sqrt{G'(r_h)}}\Rightarrow P=\frac{4\pi}{\sqrt{F'(r_h)\cdot G'(r_h)}}=4\pi r_S$$
>
> $$4\pi\frac{2GM}{c^2}=\frac{\hbar c}{k_BT_H}\Rightarrow T_H=\frac{\hbar c^3}{8\pi Gk_BM}$$
>
> **l. 1.0 point**
>
> $$C=\frac{dU}{dT_H}=\frac{d(Mc^2)}{dT_H}=c^2\frac{d\left(\frac{\hbar c^3}{8\pi Gk_BT_H}\right)}{dT_H}=-\frac{\hbar c^5}{8\pi Gk_BT_H^2}$$
>
> **m. 0.5 point**
>
> $$W=\sigma T_H^4A=\frac{\pi^2k_B^4}{60\hbar^3c^2}\cdot\frac{\hbar^4c^{12}}{8^4\pi^4G^4k_B^4M^4}\cdot4\pi\cdot\frac{4G^2M^2}{c^4}=\frac{\hbar c^6}{15360\pi G^2M^2}$$
>
> **n. 0.5 point**
> $$W=-\frac{dU}{dt}\Rightarrow\frac{\hbar c^6}{15360\pi G^2M^2}=-\frac{c^2dM}{dt}\Rightarrow$$
>
> $$\tau=\int_0^\tau dt=-\frac{15360\pi G^2}{\hbar c^4}\int_M^0 M^2dM=\frac{5120\pi G^2M^3}{\hbar c^4}$$
> For the given values, $\tau$ is of the order of $10^{77}$ s, which is approximately $10^{60}$ times greater than the age of the universe!!
