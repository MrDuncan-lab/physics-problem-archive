---
id: nbpho-2003-intl-theory-6
olympiad: NbPhO
year: 2003
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "6"
title: "Charged particle"
points: 12
aliases: ["Charged particle"]
topics: ["[[4.1 Сила Лоренца]]", "[[1.21 Фазовые диаграммы колебательных систем]]", "[[3.4 Работа электрического поля]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Построить траектории и найти среднюю скорость заряженной частицы при импульсах электрического поля в магнитном поле."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 6. Charged particle (12 points)

**NbPhO 2003** · Международная олимпиада · теория · 10–12 класс · задача 6  
Источник: [[_pdf/NbPhO/nbpho-2003.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2003.pdf#page=3|решение, стр. 3–4]]

Темы: [[4.1 Сила Лоренца]], [[1.21 Фазовые диаграммы колебательных систем]], [[3.4 Работа электрического поля]]

> [!abstract] Кратко (составлено моделью)
> Построить траектории и найти среднюю скорость заряженной частицы при импульсах электрического поля в магнитном поле.

A particle of mass $m$ and charge $q$ is in a homogeneous magnetic field with induction $B$ (the vector is parallel to the $z$-axis). The characteristic time of the system is the cyclotron period of the particle $T_B=2\pi m/Bq$. The system is situated in between two parallel electrodes, which can be used to create an homogeneous, parallel to the $x$-axis electric field $E$.

**1)** The particle is at rest. At the moment of time $t=0$, the electric field $E$ is switched on; after a short time interval $\tau$ ($\tau\ll T_B$), it is switched off, again. What will be the trajectory of the particle?

**2)** Let $p_x$ and $p_y$ denote the $x$- and $y$ components of the momentum of the particle. Sketch the trajectory of the particle in $(p_x,p_y)$-plane and depict the vectors of the momentum for the moments of time $t_n=nT_B/4$ ($n=1,2,3$ and $4$).

**3)** Consider the situation when the on-off switching of the electric field is done periodically, starting with $t=0$, after equal time intervals $\Delta t=T_B/4$. Sketch the particle trajectories in $(p_x,p_y)$- and $(x,y)$-planes.

**4)** Let the period be short, $\Delta t\ll T_B$ (but still much longer than the duration of pulse, $\Delta t\gg\tau$). Show that after the $n$-th pulse (at the time moment $t_n=n\Delta t$), the momentum of the particle can be represented as the sum of $n$ vectors $\vec p_i$, where all the component-vectors are equal in modulus (the modulus being independent of $n$), and the neighboring vectors ($\vec p_i$ and $\vec p_{i+1}$, $i=1,2,\ldots$) have equal angles between them.

**5)** Consider the limit case $\Delta t\to0$, so that $E\tau/\Delta t\to E_k$ ($E_k$ denotes the time-average of the electric field). Sketch the particles trajectory in $(p_x,p_y)$-plane and express the particles mean velocity (vectorially; averaged over the cyclotron period) via the quantities $E_k$ and $B$.

**6)** Let us return to the non-zero (but still small, $\Delta t\ll T_B$) time-intervals. Let us consider the case when the pulses are of variable polarity: for the $2n$-th pulse, the electric field is $+E$, and for the $2n+1$st pulse $-E$. Find the particles average velocity, (vectorially) averaged over the cyclotron period.

> [!answer]- Ответ
> **1** — $R=E\tau/B$.
>
> **4** — $P=Eq\tau$ is added; the angle between the lastly added vector, and the previously added vector is
>
> **4** — $\alpha=\Delta tBq/m$.
>
> **5** — $v_y=-\mathcal R/m=E_k/B$, $v_x=0$.
>
> **6** — $v_x=v_y=0$.

> [!solution]- Решение
> # 6. Charged particle (12 pts)
>
> **1)** The particle acquires the velocity $v=Eq\tau/m$ and starts moving along a circle of radius $R$, with $mv^2/R=Bvq$, hence
> $R=E\tau/B$.
>
> **2)**
>
> ![[nbpho-2003-p4-c0204.png]]
>
> **3)**
>
> ![[nbpho-2003-p4-c0220.png]]
>
> **4)** Let us consider the vectorial sum of the momenta given to the particle in different moments of time. During the time interval $\Delta t$, all the component-vectors are rotated by the angle $2\pi\Delta t/T_B=\tau Bq/m$. Thus, with each impulse, a vector $\vec P$ with modulus
> $P=Eq\tau$ is added; the angle between the lastly added vector, and the previously added vector is
> $\alpha=\Delta tBq/m$.
>
> **5)** All these vectors, when added according to the triangle rule, form a circle of radius $\mathcal R=P/\sin\alpha\to P/\alpha=E_km/B$.
>
> ![[nbpho-2003-p4-f4.svg]]
>
> Hence, the average velocity
> $v_y=-\mathcal R/m=E_k/B$, $v_x=0$.
>
> **6)** Two subsequent momenta along $x$-axes result in net moment along $y$-axes $\mathcal P_y=P\alpha$. The sequence of such moment pairs form a (nearly) circle (actually, regular equilateral polygon), composed of vectors (with modulus $\mathcal P_y$), the angle between of which is $2\alpha$ (see Fig.). The radius of the circle is $\mathcal P_y/2\alpha=P/2=\frac12Eq\tau$, and its center coordinates are $mv_x=-Eq\tau/2$, $mv_y=0$. After an even number of impulses, the endpoint of the particles momentum lies on that circle. Thus, averaged over the moments of time $2n\Delta t$, the average velocity is $v_x=-Eq\tau/2m$. For odd number of impulses, one has to add the lastly given momentum $\vec P=(Eq\tau,0)$; hence, a similar circle is formed, except that the center is shifted by $\vec P$: the center coordinates are $mv_x=Eq\tau/2$, $mv_y=0$. Correspondingly, averaged over the moments of time $2n\Delta t$, the average velocity is $v_x=+Eq\tau/2m$. Averaged over all the moments of time, the final result is
> $v_x=v_y=0$.
>
> ![[nbpho-2003-p4-f2.svg]]
>
> The figure represents the net moment $P_{res}$ after $2n$-th impulse, and also the net impulse $P'_{res}$ for another time moment $2n'\Delta t$. For an odd number of impulses, the pattern is exactly the same, except that all the vectors have opposite direction (because the lastly added component, the vertical vector, has opposite direction).
