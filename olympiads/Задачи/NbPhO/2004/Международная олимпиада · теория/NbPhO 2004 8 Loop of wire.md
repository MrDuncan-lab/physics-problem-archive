---
id: nbpho-2004-intl-theory-8
olympiad: NbPhO
year: 2004
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "8"
title: "Loop of wire"
points: 7
aliases: ["Loop of wire"]
topics: ["[[4.3 Индуктивность. Взаимоиндукция]]", "[[4.2 Сила Ампера]]", "[[1.16 Закон сохранения импульса]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Определить магнитный поток, заряд и импульс проволочной рамки при выключении тока в прямом проводе."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 8. Loop of wire (7 pts)

**NbPhO 2004** · Международная олимпиада · теория · 10–12 класс · задача 8  
Источник: [[_pdf/NbPhO/nbpho-2004.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2004.pdf#page=4|решение, стр. 4]]

Темы: [[4.3 Индуктивность. Взаимоиндукция]], [[4.2 Сила Ампера]], [[1.16 Закон сохранения импульса]]

> [!abstract] Кратко (составлено моделью)
> Определить магнитный поток, заряд и импульс проволочной рамки при выключении тока в прямом проводе.

Consider a rectangular loop of wire with dimensions $a=0.03\,\mathrm m$ and $b=1.0\,\mathrm m$, one side of which is parallel to another long straight wire carrying current $I_0=1000\,\mathrm A$, at distance $l=0{,}01\,\mathrm m$, see figure. The magnetic inductance of such current is plotted as a function of the distance from the wire in attached graph. The Ohmic resistance of the loop is $R=1{,}0\,\Omega$, the inductance is negligible.

![[nbpho-2004-p2-f4.svg]]

![[nbpho-2004-p2-f1.svg]]

**1)** Calculate the magnetic flux $\Phi$ through the loop (2 pts).

**2)** At a certain moment of time, the current in the long wire is switched off. What is the net charge $Q$ flowing through a fixed cross-section of the wire of the loop (3 pts)?

**3)** What is the net momentum $p$ given to the loop during the switch-off of the current (express it in terms of $Q$ and the given quantities, if you were unable to calculate $Q$) (2 pts)?

> [!answer]- Ответ
> **1** — $\Phi=\int_l^{l+a}Bbdx=\int_l^{l+a}\frac{b\mu_0I_0}{2\pi x}dx=\frac{b\mu_0I_0}{2\pi}\ln\frac{a+l}{l}$.
>
> **1** — $\Phi=Sb=280\,\mu\mathrm{Wb}$.
>
> **2** — $Q=\Phi/R=280\,\mu\mathrm C$.
>
> **3** — $p=\frac{a(b\mu_0I_0)^2}{8\pi^2Rl(l+a)}\ln\frac{a+l}{l}\approx2.08\cdot10^{-6}\,\mathrm{kg\cdot m/s^2}$.

> [!solution]- Решение
> # 8. Loop of wire (7 pts)
>
> **1)** At the distance $r$ from the current $I_0$, the magnetic induction $B=\frac{\mu_0I_0}{2\pi r}$. Then, the flux through the contour
> $\Phi=\int_l^{l+a}Bbdx=\int_l^{l+a}\frac{b\mu_0I_0}{2\pi x}dx=\frac{b\mu_0I_0}{2\pi}\ln\frac{a+l}{l}$.
>
> Alternatively, we can find it using the graph by determining the area $S$ under the curve, from $r=r_1=0{,}01\,\mathrm m$ to $r=r_2=0{,}04\,\mathrm m$: $S\approx0{,}28\,\mathrm{mT\cdot m}$, further,
> $\Phi=Sb=280\,\mu\mathrm{Wb}$.
>
> **2)** After switching off the current, the flux through the tends to zero. From the Ohm’s law $R\frac{dq}{dt}=\frac{d\Phi}{dt}$, hence $Rdq=d\Phi$, i.e. $RQ=\Delta\Phi=\Phi$. Finally,
> $Q=\Phi/R=280\,\mu\mathrm C$.
>
> **3)** We calculate the force as difference between the forces at the two loop segments parallel to the straight line: $F_1=biB_1$ and $F_2=biB_2$, where $i=R^{-1}\frac{d\Phi}{dt}$. So, $dp=(F_1-F_2)dt=bR^{-1}(B_1-B_2)d\Phi$. Using $B_1=\mu_0I/2\pi l$ and $B_1=\mu_0I/2\pi(l+a)$, we end up with $dp=\frac bR\frac{\mu_0I}{2\pi}\frac a{l(l+a)}d\Phi$. Using the result of first question, $d\Phi=\frac{b\mu_0}{2\pi}\ln\frac{a+l}{l}dI$, i.e. $dp=(\frac{b\mu_0}{2\pi})^2\frac a{Rl(l+a)}\ln\frac{a+l}{l}IdI$. Finally,
> $p=\frac{a(b\mu_0I_0)^2}{8\pi^2Rl(l+a)}\ln\frac{a+l}{l}\approx2.08\cdot10^{-6}\,\mathrm{kg\cdot m/s^2}$.
>
> The same result could have been obtained using the graph and approach used in the alternative solution of the question 1.
