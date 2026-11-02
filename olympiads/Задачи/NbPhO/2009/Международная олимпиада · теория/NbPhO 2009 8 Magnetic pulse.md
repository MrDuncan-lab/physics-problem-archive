---
id: nbpho-2009-intl-theory-8
olympiad: NbPhO
year: 2009
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "8"
title: "Magnetic pulse"
points: 7
aliases: ["Magnetic pulse"]
topics: ["[[4.3 Индуктивность. Взаимоиндукция]]", "[[5.1 RC-цепи]]", "[[5.2 RL-цепи]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Найти токи и прошедший заряд в цепи при импульсе магнитного поля."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 8. Magnetic pulse (7 points)

**NbPhO 2009** · Международная олимпиада · теория · 10–12 класс · задача 8  
Источник: [[_pdf/NbPhO/nbpho-2009.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2009.pdf#page=4|решение, стр. 4]]

Темы: [[4.3 Индуктивность. Взаимоиндукция]], [[5.1 RC-цепи]], [[5.2 RL-цепи]]

> [!abstract] Кратко (составлено моделью)
> Найти токи и прошедший заряд в цепи при импульсе магнитного поля.

Consider an electric circuit consisting of a coil of negligibly small inductance, consisting of $N=10$ turns and with the surface area of a single loop $S=10\,\mathrm{cm^2}$), resistors $R_1=R_2=3\,\Omega$, capacitor $C=0.2\,\mathrm F$, and an inductance $L=1\,H$, connected as shown in Fig. At the moment of time $t=0$, a magnetic field, parallel to the axis of the coil is switched on. The inductance of the magnetic field starts growing linearly, starting from $B=0$ until the maximal value $B=1\,\mathrm T$ is achieved at $t=10\,\mathrm{ms}$. Further, the inductance of the magnetic field remains constant (and equal to $1\mathrm T$).

![[nbpho-2009-p2-c0274.png]]

**i)** Find the current through the resistors $R_1$ and $R_2$ at the moment of time $t_1=5\,\mathrm{ms}$.

**ii)** Find the current through the resistors $R_1$ and $R_2$ at the moment of time $t_2=15\,\mathrm{ms}$.

**iii)** What is the net charge passing through the resistor $R_2$?

> [!answer]- Ответ
> **i** — $I_1=U/R_1\approx0.33\,\mathrm A$. As for $I_2$, it starts growing from $0\,\mathrm A$ at $t=0$ at a rate, given by $L\frac{dI}{dt}=U$, i.e.
>
> **i** — $I_2=Ut_1/L=5\,\mathrm{mA}$.
>
> **ii** — $I'_1=Q/R_1C=U\tau/R_1^2C\approx5.6\,\mathrm{mA}$. As for the inductance, it will retain (almost completely, because $t_2-\tau\ll L/R_2$) the current it has acquired during the first $10\,\mathrm{ms}$,
>
> **ii** — $I'_2=U\tau/L=10\,\mathrm{mA}$.
>
> **iii** — $\Delta q=LI'_2/R_2=3.3\,\mathrm{mC}$.

> [!solution]- Решение
> # 8. Magnetic pulse (7 points)
>
> Since we can neglect the inductance of the coil, it performs as a voltage source, which outputs $U=NSB/\tau=1\,\mathrm V$ during the time period between $t=0\,\mathrm{ms}$ and $10\,\mathrm{ms}$, and $0\,\mathrm V$ otherwise. The characteristic time scales of the $RC$ and $LC$ circuits are $\tau_1=R_1C=0.6\,\mathrm s$ and $\tau_2=L/R_2\approx0.3\,\mathrm s$. So, for both circuits, the processes are very fast, i.e. the capacitor is effectively short-circuited, and almost all the voltage falls on the inductance.
>
> **i)** According to the considerations given above,
> $I_1=U/R_1\approx0.33\,\mathrm A$. As for $I_2$, it starts growing from $0\,\mathrm A$ at $t=0$ at a rate, given by $L\frac{dI}{dt}=U$, i.e.
> $I_2=Ut_1/L=5\,\mathrm{mA}$.
>
> **ii)** When the voltage $U$ is switched off (at $t=\tau=10\,\mathrm{ms}$), the capacitor will (almost completely, because $t_2-\tau\ll R_1C$) retain the charge it has accumulated, $Q=I_1\tau$. All the voltage of the capacitor ($Q/C$) will fall on the resistor $R_1$, so that
> $I'_1=Q/R_1C=U\tau/R_1^2C\approx5.6\,\mathrm{mA}$. As for the inductance, it will retain (almost completely, because $t_2-\tau\ll L/R_2$) the current it has acquired during the first $10\,\mathrm{ms}$,
> $I'_2=U\tau/L=10\,\mathrm{mA}$.
>
> **iii)** Since the current in $R_2$ will decay very slowly, as compared to its growth during the first $10\,\mathrm{ms}$, we can neglect the charge passing through it during $t<\tau$. Then we can write the Kirhoff’s law in the form $L\frac{dI}{dt}+R_2\frac{dq}{dt}=0$, from where $LdI+R_2dq=0$, and $L\Delta I=-R_2\Delta q$. Since $\Delta I=-I'_2$, we obtain
> $\Delta q=LI'_2/R_2=3.3\,\mathrm{mC}$.
