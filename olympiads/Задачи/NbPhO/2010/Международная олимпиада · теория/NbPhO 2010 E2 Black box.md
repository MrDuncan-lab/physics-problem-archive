---
id: nbpho-2010-intl-theory-e2
olympiad: NbPhO
year: 2010
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "E2"
title: "Black box"
points: 10
aliases: ["Black box"]
topics: ["[[7 Эксперименты]]", "[[5.1 RC-цепи]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Определить схему и параметры компонентов электрического чёрного ящика по измерениям."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 11. Black box (10 points)

**NbPhO 2010** · Международная олимпиада · теория · 10–12 класс · задача E2  
Источник: [[_pdf/NbPhO/nbpho-2010.pdf#page=2|условие, стр. 2–3]] · [[_pdf/NbPhO/nbpho-2010.pdf#page=6|решение, стр. 6]]

Темы: [[7 Эксперименты]], [[5.1 RC-цепи]]

> [!abstract] Кратко (составлено моделью)
> Определить схему и параметры компонентов электрического чёрного ящика по измерениям.

*Equipment:* a black box, multimeter, battery, timer (on the screen).

Determine the electrical scheme inside the black box, and the values of all the resistors inside it. Estimate the characteristics of other electrical components. It is known that apart from the wires, the total number of components is three.

Estonian-Finnish Olympiad - 2010

> [!answer]- Ответ
> **iv** — $R_2=\mathcal E/I_{c0}\approx2.5\,\mathrm{k\Omega}$ and
>
> **iv** — $R_1=\mathcal E/I_{c\infty}-R_2\approx6.9\,\mathrm{k\Omega}$,
>
> **iv** — $R_1=\mathcal E/I_{c\infty}\approx9.1\,\mathrm{k\Omega}$ and
>
> **iv** — $R_2=\mathcal E/I_d\approx3.2\,\mathrm{k\Omega}$.
>
> **iv** — $C=\tau_2/\ln 2R_1\approx5.2\,\mathrm{mF}$. In the case (b), $\tau_2=\ln 2(R_1+R_2)C$, hence
>
> **iv** — $C=\tau_2/\ln 2(R_1+R_2)\approx2.9\,\mathrm{mF}$.

> [!solution]- Решение
> # Problem 11. Black box (10 points)
>
> There are several measurements, which can be made.
>
> **i. (2 pts)** We can measure the voltage of the battery $\mathcal E\approx3.2\,\mathrm V$.
>
> **ii. (2 pts)** Then, we can connect battery to the outlets of the box via ammeter and measure the current. It appears that at the first moment, $I_{c0}\approx1.3\,\mathrm{mA}$; however, the current starts to decrease (decreasing twice during $\tau_1\approx12\,\mathrm s$) and achieves at the long-time limit the final value $I_{c\infty}\approx0.35\,\mathrm{mA}$.
>
> **iii. (2 pts)** Further, we can measure voltage at the outlet after disconnecting the battery. At the first moment, $V_d\approx2.35\,\mathrm V$; it decreases twice per $\tau_2\approx25\,\mathrm s$ and vanishes at the long-time limit.
>
> **iv. (4 pts)** Finally, we can connect the ammeter to the outlet immediately after disconnecting the battery, and measure the current. Initially, it has value $I_d\approx1.0\,\mathrm{mA}$, and vanishes at the long-time limit.
>
> From iii and ii we can conclude that the box must contain a capacitor $C$ (if there were an inductance, the current $I_c$ would increase in time). Because of self-discharge (voltage vanishes for iii), there must be a resistance $R_1$ parallel to the capacitor. Because of a prolonged charging (for ii, $\tau_1>0$), there must be also a resistor $R_2$ in serial connection to the capacitor. So, there are two possible schemes, Fig (a) and Fig (b).
>
> ![[nbpho-2010-p6-f1.svg]]
> ![[nbpho-2010-p6-f2.svg]]
>
> In case (a):
> $$I_{c0}=\mathcal E/R_2,\qquad I_{c\infty}=\mathcal E/(R_1+R_2),$$
> $$I_d=\mathcal E R_1/R_2(R_1+R_2),\qquad U_d=\mathcal E R_1/(R_1+R_2).$$
> In case (b),
> $$I_{c0}=\mathcal E(R_2^{-1}+R_1^{-1}),\qquad I_{c\infty}=\mathcal E/R_1,$$
> $$I_d=\mathcal E/R_2,\qquad U_d=\mathcal E R_1/(R_1+R_2).$$
>
> In both cases, we have two unknown quantities ($R_1$ and $R_2$), and four equations. It appears (follows from these equations) that in both cases, two equalities should hold between the measured quantities: $U_d=\mathcal E I_{c\infty}/I_{c0}$, and $I_{c0}=I_{c\infty}+I_d$. So, the effective (independent) number of equations is reduced by two, which still leaves two — just sufficient for finding $R_1$ and $R_2$, but not enough to distinguish between the cases (a) and (b). In fact, it can be shown that these two cases cannot be distinguished even if we study the time-dependences of voltage and currents. So, we can say that we have either scheme (a) with
> $R_2=\mathcal E/I_{c0}\approx2.5\,\mathrm{k\Omega}$ and
> $R_1=\mathcal E/I_{c\infty}-R_2\approx6.9\,\mathrm{k\Omega}$,
> or scheme (b) with
> $R_1=\mathcal E/I_{c\infty}\approx9.1\,\mathrm{k\Omega}$ and
> $R_2=\mathcal E/I_d\approx3.2\,\mathrm{k\Omega}$.
>
> The value of the capacitor can be estimated from characteristic current decay times. For instance, using the characteristic time $\tau_2$, in the case (a) we have $\tau_2=\ln 2R_1C$, hence
> $C=\tau_2/\ln 2R_1\approx5.2\,\mathrm{mF}$. In the case (b), $\tau_2=\ln 2(R_1+R_2)C$, hence
> $C=\tau_2/\ln 2(R_1+R_2)\approx2.9\,\mathrm{mF}$.
