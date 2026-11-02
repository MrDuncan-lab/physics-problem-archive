---
id: rompho-2010-intl-theory-t1
olympiad: RomPhO
year: 2010
stage: "Международная олимпиада"
round: теория
grade: ""
number: "T1"
title: "Fizică clasică"
aliases: ["Fizică clasică"]
topics: ["[[5.2 RL-цепи]]", "[[6.5 Волновая оптика]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Исследовать токи в цепи с индуктивностями и предохранителем и дифракционные максимумы спектрального прибора Михельсона."
status: "проверено: сверка"
lang: ro
tags: [задача]
---

# FIZICĂ CLASICĂ

**RomPhO 2010** · Международная олимпиада · теория · задача T1  
Источник: [[_pdf/RomPhO/RomPhO-2010-T1.pdf#page=1|условие, стр. 1–2]] · [[_pdf/RomPhO/RomPhO-2010-T1-solution.pdf#page=3|решение, стр. 3–4]]

Темы: [[5.2 RL-цепи]], [[6.5 Волновая оптика]]

> [!abstract] Кратко (составлено моделью)
> Исследовать токи в цепи с индуктивностями и предохранителем и дифракционные максимумы спектрального прибора Михельсона.

## A. ELECTRICITATE

În circuitul din figură sursa este ideală (rezistența internă este nulă) iar rezistențele celor două bobine se pot neglija. F este o siguranță fuzibilă (de rezistență nulă) ce se arde instantaneu atunci când curentul ajunge exact la valoarea $I_F=200\ \mathrm{mA}$. La momentul $t=0$ curenții în circuit sunt nuli, iar întrerupătorul S închide circuitul.

![[rompho-2010-t1-problems-p1-f2.svg]]

**a.** Calculați și reprezentați grafic dependențele de timp pentru curenții din circuit până la momentul arderii siguranței. Calculați la ce moment de timp se arde siguranța.

**b.** Determinați valorile și vitezele de variație ale tuturor curenților, imediat după arderea siguranței.

**c.** Calculați valorile curenților pentru $t\to\infty$.

Aplicație numerică: $V=10\ \mathrm V$; $L_1=10\ \mathrm{mH}$; $L_2=5\ \mathrm{mH}$; $I_F=0{,}2\ \mathrm A$; $R_1=1\ \mathrm{k\Omega}$; $R_2=200\ \Omega$.

(conf. dr. Petrică Cristea, conf. dr. Mihai Dincă, Facultatea de Fizică, Universitatea București)

## B. „SCARA“ LUI MICHELSON

Rețeaua de difracție “scara” lui Michelson este un aparat spectral interferențial compus dintr-un număr de lame de sticlă cu o foarte bună omogenitate, având fiecare grosimea $h$ și indicele de refracție $n$, Lărgimea unei trăsături se notează cu $a$.

Un fascicul monocromatic de lumină cu lungimea de undă $\lambda$ cade normal pe suprafața celei mai mari lame, așa ca în figură. Difracția se produce în punctul ultim comun a două lame vecine.

![[rompho-2010-t1-problems-p1-c6668.png]]

**a.** Deduceți condiția de obținere a maximelor principale de difracție, în funcție de $a$, $h$, $n$, $\lambda$, și unghiul $\alpha$ făcut de razele difractate cu direcția inițială.

**b.** Câte maxime principale sunt observabile practic? (Se consideră maxime observabile cele conținute în maximul principal de difracție corespunzător unei trăsături.)

**c.** Deduceți domeniul de dispersie $\Delta\lambda$ (lărgimea maximă a domeniului spectral cu care poate fi iluminat aparatul pentru a nu exista suprapuneri între ordine).

Aplicație numerică: $h=a=1\mathrm{cm}$; $n=1{,}5$; $\lambda=500\ \mathrm{nm}$.

(lect. dr. Marian Băzăvan, Facultatea de Fizică, Universitatea București)

> [!answer]- Ответ
> **A.a** — The fuse F acts as a short-circuit, and the voltage across it vanishes. No electric current $I_1$ flows in $R_1$, $I_1=0$.
>
> **A.a** — No electric current flows in $L_2$ for $t=0$, the voltage across the fuse is zero, the electric current $I_2$ is zero, $I_2=0$.
>
> **A.a** — Across the inductance $L_1$ a constant voltage $V$ causes $I$ to increase at a constant rate $V/L_1=1000\ \mathrm{A/s}$.
>
> **A.a** — All electrical current $I$ flows in the fuse, $I_F=I$.
>
> **A.a**
>
> $$
> t=L_1I_F/V=0.2\ \mathrm{ms}
> $$
>
> **A.b** — Once the fuse melts, the current $I_F$ vanishes, $I_F=0$.
>
> **A.b** — Right after the fuse melts, the electric current $I$ conserves its value before melting, $I=200\mathrm{mA}$.
>
> **A.b** — The current flowing in $L_2$ is free of jumps (discontinuities). Then, right after melting the fuse $I_2=0$.
>
> **A.b** — the current $I_1$ flowing in $R_1$ is 200 mA, causing a voltage drop across $R_1$ of 200 V, with the “+” pole in the right hand side.
>
> **A.b** — $(V-R_1I_F)/L_1=19000\mathrm{A/s}$.
>
> **A.b** — immediately after melting the fuse, $I_2$ raises at a rate of **40000 A/s**.
>
> **A.b** — From the first Kirchhoff law, it follows that immediately after the fuse melts, the current $I_1$ falls at a rate of **59000 A/s**.
>
> **A.c**
>
> $$
> I_1=10\ \mathrm{mA}
> $$
>
> **A.c**
>
> $$
> I_2=50\ \mathrm{mA}
> $$
>
> **A.c**
>
> $$
> I=60\ \mathrm{mA}
> $$
>
> **B.a**
>
> $$
> \delta=k\lambda,\quad k\in\mathbb N.
> $$
>
> **B.a**
>
> $$
> a\sin\alpha+h(1-\cos\alpha)=p\lambda,\quad p=k-k_0>0.
> $$
>
> **B.b**
>
> $$
> \sin\alpha<\frac\lambda a\Rightarrow p<1\Rightarrow p=0\Rightarrow k=k_0.
> $$
>
> **B.c**
>
> $$
> k_0\lambda=(k_0-1)(\lambda+\Delta\lambda)\Rightarrow\Delta\lambda\approx\frac\lambda{k_0}=0.5\mathrm A.
> $$

> [!solution]- Решение
> ## A. ELECTRICITY
>
> **a)** $I_F<200\ \mathrm{mA}$ (the fuse is intact):
>
> The fuse F acts as a short-circuit, and the voltage across it vanishes. No electric current $I_1$ flows in $R_1$, $I_1=0$.  
> 0.25 p
>
> No electric current flows in $L_2$ for $t=0$, the voltage across the fuse is zero, the electric current $I_2$ is zero, $I_2=0$.  
> 0.25 p
>
> Across the inductance $L_1$ a constant voltage $V$ causes $I$ to increase at a constant rate $V/L_1=1000\ \mathrm{A/s}$.  
> 0.25 p
>
> All electrical current $I$ flows in the fuse, $I_F=I$.  
> 0.25 p
>
> The melting condition is realized for
>
> $$t=L_1I_F/V=0.2\ \mathrm{ms}$$
> 0.5 p **total a) 1.5 p**
>
> **b)**
>
> Once the fuse melts, the current $I_F$ vanishes, $I_F=0$.  
> 0.25 p
>
> Right after the fuse melts, the electric current $I$ conserves its value before melting, $I=200\mathrm{mA}$.  
> 0.25 p
>
> The current flowing in $L_2$ is free of jumps (discontinuities). Then, right after melting the fuse $I_2=0$.  
> 0.25 p
>
> As a consequence of Kirchhoff’s first law, right after melting the fuse,
> the current $I_1$ flowing in $R_1$ is 200 mA, causing a voltage drop across $R_1$ of 200 V, with the “+” pole in the right hand side.  
> 0.25 p
>
> As a consequence, a voltage across $L_1$ develops $V-R_1I_F=200\mathrm V-10\mathrm V=190\mathrm V$, causing the variation of $I$ at a rate $\Delta I/\Delta t$ given by 
> $(V-R_1I_F)/L_1=19000\mathrm{A/s}$.
>
> Right after the fuse melts, the voltage polarity causes $I$ to decrease at the rate above.  
> 0.5 p
>
> The 200 V voltage drop across $R_1$ produces an increase of $I_2$. Right after the fuse melts, the voltage drop across $R_2$ is zero, therefore,
> immediately after melting the fuse, $I_2$ raises at a rate of **40000 A/s**.  
> 0.25 p
>
> From the first Kirchhoff law, it follows that immediately after the fuse melts, the current $I_1$ falls at a rate of **59000 A/s**.  
> 0.5 p **total b) 2.25 p**
>
> **c)** For $t$ approaching infinity:
>
> $$I_1=10\ \mathrm{mA}$$
> 0.25 p
>
> $$I_2=50\ \mathrm{mA}$$
> 0.25 p
>
> $$I=60\ \mathrm{mA}$$
> 0.25 p  
> **total c) 0.75 p**
>
> ## B. MICHELSON’S “LADDER”
>
> **a.** 1.5p
>
> ![[rompho-2010-t1-solutions-p4-f1.svg]]
>
> It is obvious that for $\alpha=0$, the path length difference $\delta$ between two neighboring light rays is $(n-1)h$. This difference increases with $\alpha$.
> $$\delta=nh+a\sin\alpha-h\cos\alpha=(n-1)h+a\sin\alpha+h(1-\cos\alpha).$$
>
> $$\delta=k\lambda,\quad k\in\mathbb N.$$
> One can see that in our specific example we get a diffraction maximum for $\alpha=0$ and $k_0=10{,}000$. So the condition for the principal maxima can be written:
>
> $$a\sin\alpha+h(1-\cos\alpha)=p\lambda,\quad p=k-k_0>0.$$
>
> **b.** 1.5p
>
> One knows that the intensity of the light diffracted by a slit with aperture $a$ depends on the deflecting angle according to:
> $$I(\alpha)=I_0\left[\frac{\sin\left(\frac{\pi a\sin\alpha}{\lambda}\right)}{\frac{\pi a\sin\alpha}{\lambda}}\right]^2.$$
> The first diffraction minimum occurs for
> $$\frac{\pi a\sin\alpha}{\lambda}=\pi\Rightarrow\sin\alpha=\frac\lambda a=5\cdot10^{-5}.$$
> For such a small angle,
> $$\delta\approx a\alpha+h\frac{\alpha^2}{2}\approx a\alpha\approx a\sin\alpha=p\lambda.$$
>
> $$\sin\alpha<\frac\lambda a\Rightarrow p<1\Rightarrow p=0\Rightarrow k=k_0.$$
> So the only principal maximum that can be seen is the “central” one.
>
> **c.** 1.5p
>
> Increasing the wavelength of the light stream by $\Delta\lambda$ can lead to the overlapping of two such central maxima.
>
> $$k_0\lambda=(k_0-1)(\lambda+\Delta\lambda)\Rightarrow\Delta\lambda\approx\frac\lambda{k_0}=0.5\mathrm A.$$
