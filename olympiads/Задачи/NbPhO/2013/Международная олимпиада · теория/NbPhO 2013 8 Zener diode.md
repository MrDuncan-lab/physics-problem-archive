---
id: nbpho-2013-intl-theory-8
olympiad: NbPhO
year: 2013
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "8"
title: "Zener diode"
points: 7
aliases: ["Zener diode"]
topics: ["[[5.3 Электромагнитные колебания. RLC-цепи]]", "[[5.5 Нелинейные элементы в электрических цепях]]", "[[1.21 Фазовые диаграммы колебательных систем]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Построить фазовую диаграмму LC-контура со стабилитроном и определить затухание колебаний."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 8. ZENER DIODE (7 points)

**NbPhO 2013** · Международная олимпиада · теория · 10–12 класс · задача 8  
Источник: [[_pdf/NbPhO/nbpho-2013.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2013.pdf#page=5|решение, стр. 5]]

Темы: [[5.3 Электромагнитные колебания. RLC-цепи]], [[5.5 Нелинейные элементы в электрических цепях]], [[1.21 Фазовые диаграммы колебательных систем]]

> [!abstract] Кратко (составлено моделью)
> Построить фазовую диаграмму LC-контура со стабилитроном и определить затухание колебаний.

An inductance $L$ and a capacitor $C$ are connected in series with a switch. Initially the switch is open and the capacitor is given a charge $q_0$. Now the switch is closed.

**i)** (1 point) What are the charge $q$ on the capacitor and the current $I$ in the circuit as functions of time? Draw the phase diagram of the system — the evolution of the system on a $I-q$ graph — and note the curve’s parameters. Note the direction of the system’s evolution with arrow(s).

A Zener diode is a non-linear circuit element that acts as a bi-directional diode: it allows the current to flow in the positive direction when a forward voltage on it exceeds a certain threshold value, but it also allows a current to flow in the opposite direction when exposed to sufficiently large negative voltage. Normally the two voltage scales are quite different, but for our purposes we will take a Zener diode with the following volt-ampere characteristics: for forward currents, the voltage on the diode is $V_d$, for reverse currents, the voltage on the diode is $-V_d$, for zero current the voltage on the diode is $-V_d<V<V_d$.

Now we connect the inductance $L$, the capacitor $C$ all in series with a switch and a Zener diode. The switch is initially open. The capacitor is again given the charge $q_0>CV_d$ and the switch is then closed.

**ii)** (2 points) Make a drawing of the phase diagram for the system. Note the direction of the system’s evolution with arrow(s).

**iii)** (2 points) Does the evolution of the system only necessarily stop for $q=0$? Find the range of values of $q$ on the capacitor for which the evolution of the system will necessarily come to a halt.

**iv)** (2 points) Find the decrease $\Delta q$ in the maximum positive value of the capacitor’s charge $q$ after one full oscillation. How long does it take before oscillation halts?

> [!answer]- Ответ
> **i** — $q(t)=q_0\cos\omega t$, while
>
> **i** — $I(t)=\dot q(t)=-\omega q_0\sin\omega t$.
>
> **iii** — $\pm CV_d$ (for $I=0$). If a trajectory reaches any of the points in that segment, it will stay there forever. The extent of that region is $2CV_d$.
>
> **iv** — $\Delta q=-4CV_d$.
>
> **iv** — $t=N\frac T2=N\frac\pi\omega=N\pi\sqrt{LC}$.

> [!solution]- Решение
> # 8. ZENER DIODE (7 points)
>
> **i)** (1 point) Kirchoff’s 2nd law gives $L\dot I+q/C=0$ or $\ddot q+\frac1{LC}q=0$. This is the equation of a simple harmonic oscillator with the frequency $\omega=\frac1{\sqrt{LC}}$ and we can immediately write
> $q(t)=q_0\cos\omega t$, while
> $I(t)=\dot q(t)=-\omega q_0\sin\omega t$.
>
> Note that
>
> $$q^2+\frac1{\omega^2}I^2=q_0^2(\sin^2\omega t+\cos^2\omega t)=q_0^2,$$
>
> and therefore the phase diagram of the system is an ellipse centred at the origin, with semi-axes $q_0$ and $\omega q_0$. Alternatively, this relation comes directly from the conservation of energy:
>
> $$\frac{LI^2}{2}+\frac{q^2}{2C}=E_0=\frac{q_0^2}{2C}.$$
>
> By looking at $q$ and $I$ a quarter-period later from $t=0$, say, it’s not hard to see that the system must evolve in a clockwise sense on the phase diagram. Note that in this instance, only $q=0$ is an equilibrium point: for all non-zero $q$ there will be never-ending oscillations in the circuit.
>
> ![[nbpho-2013-p5-c2655.png]]
>
> **ii)** (2 points) Now the sign of the voltage on the diode depends on the direction of the current, giving either of $L\ddot q+\frac qC\pm V_d=0$. We can summarize the equations as follows:
>
> $$\begin{cases}L\ddot q+\frac qC=V_d&\text{if }\dot q<0\\L\ddot q+\frac qC=-V_d&\text{if }\dot q>0\end{cases}$$
>
> Let us introduce the new variables $q_{1,2}$ such that $q_1=q-CV_d$ and $q_2=q+CV_d$. Then we can rewrite the two equations above in a more familiar form:
>
> $$\begin{cases}L\ddot q_1+\frac{q_1}{C}=0&\text{if }\dot q<0\\L\ddot q_2+\frac{q_2}{C}=0&\text{if }\dot q>0\end{cases}$$
>
> Thus the introduction of the diode only serves to shift the equilibrium points for the otherwise simple harmonic orbits. For $\dot q>0$, the equilibrium point is $q_2=0$ or $q=-CV_d$, while for $\dot q<0$ it is $q=CV_d$. So the orbit will consist of half-ellipses in the upper and the lower parts of the $I-q$ diagram, centred at $q=-CV_d$ for the upper half and at $q=CV_d$ for the lower half. As the evolution is continuous, these half-ellipses will join up at $I=0$.
>
> ![[nbpho-2013-p5-c5056.png]]
>
> **iii)** (2 points) We can see on the diagram that there is a “dead zone” between
> $\pm CV_d$ (for $I=0$). If a trajectory reaches any of the points in that segment, it will stay there forever. The extent of that region is $2CV_d$.
>
> **iv)** (2 points) Let’s use the phase diagram to figure this out. Suppose the capacitor initially has the charge $q_0\gg CV_d$. Then the charge will first swing to the other way of $CV_d$ and will become $q_{T/2}=CV_d-(q_0-CV_d)=2CV_d-q_0$. Then it will perform the other half-oscillation around $-CV_d$ and the charge at the end of that is $q_T=-CV_d+(-CV_d-(2CV_d-q_0))=q_0-4CV_d$, and therefore
> $\Delta q=-4CV_d$.
>
> Note that we have the right to talk about half- and full periods because the oscillations still happen at the immutable frequency $\omega=\frac1{\sqrt{LC}}$. Therefore the time between the two maxima is just a full period of oscillation, $T=\frac{2\pi}{\omega}$.
>
> Once $q(t)$ has a zero derivative inside the region bounded by $\pm CV_d$, it will remain at that particular value forever. For a large initial $q_0$, we expect there to be approximately $\left|\frac{q_0}{\Delta q}\right|=\frac{|q_0|}{4CV_d}$ total oscillations.
>
> More exactly, the distance from the “dead zone” is initially $|q_0|-CV_d$ and decreases during each half-oscillation by $2CV_d$. The total number of half-oscillations is $N=\left\lfloor\frac{|q_0|-CV_d}{2CV_d}\right\rfloor$ and the total time
> $t=N\frac T2=N\frac\pi\omega=N\pi\sqrt{LC}$.
