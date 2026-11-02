---
id: nbpho-2012-intl-theory-4
olympiad: NbPhO
year: 2012
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "4"
title: "RLC-circuit"
points: 5
aliases: ["RLC-circuit"]
topics: ["[[5.3 Электромагнитные колебания. RLC-цепи]]", "[[5.1 RC-цепи]]", "[[5.2 RL-цепи]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Найти показания вольтметра и тепловыделение в RLC-цепи после размыкания ключа."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# Problem 4. RLC-circuit (5 points)

**NbPhO 2012** · Международная олимпиада · теория · 10–12 класс · задача 4  
Источник: [[_pdf/NbPhO/nbpho-2012.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2012.pdf#page=4|решение, стр. 4]]

Темы: [[5.3 Электромагнитные колебания. RLC-цепи]], [[5.1 RC-цепи]], [[5.2 RL-цепи]]

> [!abstract] Кратко (составлено моделью)
> Найти показания вольтметра и тепловыделение в RLC-цепи после размыкания ключа.

For the circuit shown in Figure, $R_1=3R$, $R_2=R$, $C_1=C_2=C$, and $L_1=L_2=L$. The electromotive force of the battery is $\mathcal E$. Initially the switch is closed and the system is operating in a stationary regime.

![[nbpho-2012-p1-f2.svg]]

**i.** (1 pt) Find the reading of the voltmeter in the stationary regime.

**ii.** (2 pts) Now, the switch is opened. Find the reading of the voltmeter immediately after the opening.

**iii.** (2 pts) Find the total amount of heat which will be dissipated on each of the resistors after opening the switch, and until a new equilibrium state is achieved.

> [!answer]- Ответ
> **4.i** — $\mathcal E$.
>
> **4.ii** — $-2\mathcal E$.
>
> **4.iii** — $L\mathcal E^2/(2R^2)$. This is the energy dissipated from $R_1$. The corresponding expressions for the right-hand circuit (giving the energy dissipated from $R_2$) are
>
> **4.iii** — $C_2\mathcal E^2/2+L_2\mathcal E^2/(2R_2^2)$ and $C\mathcal E^2/2+L\mathcal E^2/(2R^2)$.

> [!solution]- Решение
> # Problem 4. RLC-circuit (5 points)
>
> **i.** (1 pt) In the stationary regime, the capacitors can be effectively disconnected (they conduct no direct current) and the inductors can be substituted by wires. If the voltmeter is ideal, there is therefore no current through $R_1$ and the voltmeter shows the voltage on $R_2$ equalling
> $\mathcal E$.
>
> **ii.** (2 pts) Capacitors cannot immediately change their voltage and inductors cannot instantaneously change their current. $L_1$ and $L_2$ had both been carrying all the current that had been flowing through the circuit, hence, after opening the switch, they still carry a current of $\mathcal E/R_2$ and act as such current sources. As the current from $L_2$ flows also through $R_2$, the voltage on $R_2$ is $\mathcal E$ (with the “+”-side at the centre of the circuit). The current through $L_1$ flows also through $R_1$ (it is the current charging $C_1$); therefore the voltage on $R_1$ is $\mathcal E R_1/R_2$ (with the “+”-side at the centre). The reading of the voltmeter has changed its sign and is $\mathcal E(1-R_1/R_2)$ or, plugging in the data,
> $-2\mathcal E$.
>
> **iii.** (2 pts) Immediately after opening the switch, capacitor $C_1$ was uncharged (it had been parallel to $R_1$ that was carrying no current) and $C_2$ had a voltage of $\mathcal E$ (it had been directly parallel to the battery). $L_1$ and $L_2$ were both carrying a current of $\mathcal E/R_2$. The voltmeter can be effectively disconnected (its resistance is huge), giving us two separate circuits, $R_1L_1C_1$ and $R_2L_2C_2$. Therefore (by the potential energy formulae $CU^2/2$ and $LI^2/2$) the energy stored in the left-hand circuit was $L_1\mathcal E^2/(2R_2^2)$ or, with the given data,
> $L\mathcal E^2/(2R^2)$. This is the energy dissipated from $R_1$. The corresponding expressions for the right-hand circuit (giving the energy dissipated from $R_2$) are
> $C_2\mathcal E^2/2+L_2\mathcal E^2/(2R_2^2)$ and $C\mathcal E^2/2+L\mathcal E^2/(2R^2)$.
