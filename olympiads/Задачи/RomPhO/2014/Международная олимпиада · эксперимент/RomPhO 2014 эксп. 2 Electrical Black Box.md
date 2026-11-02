---
id: rompho-2014-intl-experiment-exp2
olympiad: RomPhO
year: 2014
stage: "Международная олимпиада"
round: эксперимент
grade: ""
number: "exp2"
title: "Electrical Black Box"
aliases: ["Electrical Black Box"]
topics: ["[[5 Цепи]]", "[[7 Эксперименты]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: true
source_damaged: false
summary: "По измеренным вольт-амперным характеристикам определить сопротивления, ЭДС и схему трёхполюсного электрического чёрного ящика."
status: "проверено: сверка; решение — проверено: сверка, два чтения + арбитр"
lang: en
tags: [задача]
---

# Electrical Black Box

**RomPhO 2014** · Международная олимпиада · эксперимент · задача 2  
Источник: [[_pdf/RomPhO/RomPhO-2014-exp2.pdf#page=1|условие, стр. 1–2]] · [[_pdf/RomPhO/RomPhO-2014-exp2-solution.pdf#page=3|критерии, стр. 3]]

Темы: [[5 Цепи]], [[7 Эксперименты]]

> [!abstract] Кратко (составлено моделью)
> По измеренным вольт-амперным характеристикам определить сопротивления, ЭДС и схему трёхполюсного электрического чёрного ящика.

**Experimental Problem no. 2 (10 points)**

This experimental problem propose an analysis for an electrical black box, which has three terminals - denoted by 1,2,3. To discover the elements that compose it, it is provided a measuring device comprising a voltage source variable (denoted by S), connected in series with an ammeter (denoted by A); the two terminals of the device are denoted by P and Q. To the same terminals P and Q is mounted a voltmeter (denoted by V). Ammeter and power supply have negligible internal resistance; internal resistance of the voltmeter can be considered as being infinite.

![[rompho-2014-exp2-problems-p1-f1.png]]

The terminals 1, 2 and P are placed in electrical contact. If terminals 3 and Q are also in electrical contact and the tension furnished by the source varies, pairs of values (indicated by the measuring instruments) are obtained. These data are given in the table 1. Current intensity is positive when the current passes through the ammeter from P to Q.

*Table 1*

| U(V) | -6 | -4 | -2 | 0 | 2 | 4 |
|---|---|---|---|---|---|---|
| I(A) | -0,2 | 1,2 | 2,6 | 4,0 | 5,4 | 6,8 |

Then, terminals 2, 3, P are putted in electrical contact. If and terminals 1, Q are also in electrical contact, the pairs of values indicated by the measuring instruments - where the voltage supplied by the source varies - are given in table 2.

*Table 2*

| U(V) | 0 | 2 | 4 | 6 | 8 | 10 |
|---|---|---|---|---|---|---|
| I(A) | -5,2 | -4,0 | -2,8 | -1,6 | -0,4 | +0,8 |

Finally, terminals 3, 1, P are putted in electrical contact. If terminals 2, Q are also in electrical contact, the pairs of values indicated by the measuring instruments - where the voltage supplied by the source varies - are given in table 3.

*Table 3*

| U(V) | -6 | -4 | -2 | 0 | 2 |
|---|---|---|---|---|---|
| I(A) | -0,6 | 0 | 0,6 | 1,2 | 1,8 |

Assume that all current-voltage dependencies are linear. In this problem, calculation of errors is NOT requested.

**Task 1**

**1.a.** Plot current - voltage dependence for the data set in Table 1.

**1.b.** Determine the numerical values of the intersections with coordinate axes of the graph. Determine also the slope of graph outlined in task 1.a. If applicable, write the result as a fraction.

**1.c.** Plot current - voltage dependence for the data set in Table 2.

**1.d.** Determine the numerical values of the intersections with coordinate axes of the graph. Determine also the slope of graph outlined in task 1.a. If applicable, write the result as a fraction.

**1.e.** Plot current - voltage dependence for the data set in Table 3.

**1.f.** Determine the numerical values of the intersections with coordinate axes of the graph outlined in task 1.e. Determine also the slope of graph outlined in task 1.e. If applicable, write the result as a fraction.

**Task 2**

**2.a.** Determine the values of the electrical resistance of the resistors and electromotive force (emf) of ideal voltage sources that form the simplest circuit (a circuit triangle, delta, $\Delta$), which has the behavior described by the above data. Keep in mind that the ideal voltage source connected in series with the resistor having the lowest electrical resistance, has an emf of 10V.

**2.b.** Draw the equivalent circuit diagram for black box. Write on diagram the values of electrical resistance and emf of the sources - as they results in the task 2.a.

**Task 3**

**3.a.** For the equivalent circuit that you have determined in the task no. 2, plot the current-voltage dependence, when the terminals P and Q are in electrical contact with terminals 1 and 2 respectively. Write numerical values of the intersections with the axes of coordinates of the graph plotted.

© Topic was proposed by:  
Prof. Dr. Delia DAVIDESCU  
Conf. Univ. Dr. Adrian DAFINEI

> [!solution]- Решение (схема оценивания)
> Barem de evaluare şi de notare
>
> Se punctează oricare altă modalitate de rezolvare corectă a problemei
>
> Problema experimentală nr. 2 – Cutie neagră electrică
>
> | Nr. item | Sarcina de lucru nr. 1 | | Punctaj |
> |---|---|---|---|
> | 1.a. | Pentru: trasarea caracteristicii curent-tensiune, corespunzătoare datelor din tabelul 1. ![[rompho-2014-exp2-solutions-p3-f1.png]] <br> Observaţii: - se acordă câte 0,10p pentru indicarea mărimii şi a unităţii de măsură corespunzătoare fiecăreia dintre axele de coordonate; - se acordă 0,50p pentru marcarea corectă pe grafic a punctelor corespunzătoare setului de date experimentale din tabelul 1. | 0,70p | 070p |
> | 1.b. | Pentru: determinarea valorilor pentru intersecţia cu axele de coordonate a caracteristicii curent-tensiune şi pentru panta graficului, corespunzător datelor din tabelul 1: $\begin{cases}(0,I_{sc,12})\equiv(0,4)\\(U_{cd,12},0)\equiv(-\frac{40}{7},0)\end{cases}$ şi $m_{12}=0{,}7\,\Omega^{-1}$ | 0,30p | 0,30p |
> | 1.c. | Pentru: trasarea caracteristicii curent-tensiune, corespunzătoare datelor din tabelul 2. ![[rompho-2014-exp2-solutions-p4-f1.png]] <br> Observaţii: - se acordă câte 0,10p pentru indicarea mărimii şi a unităţii de măsură corespunzătoare fiecăreia dintre axele de coordonate; - se acordă 0,50p pentru marcarea corectă pe grafic a punctelor corespunzătoare setului de date experimentale din tabelul 2. | 0,70p | 0,70p |
> | 1.d. | Pentru: determinarea valorilor pentru intersecţia cu axele de coordonate a caracteristicii curent-tensiune şi pentru panta graficului, corespunzător datelor din tabelul 2: $\begin{cases}(0,I_{sc,23})\equiv(0,-5{,}2)\\(U_{cd,23},0)\equiv(\frac{26}{3},0)\end{cases}$ şi $m_{23}=\frac{12}{20}\,\Omega^{-1}$ | 0,30p | 0,30p |
> | 1.e. | Pentru: trasarea caracteristicii curent-tensiune, corespunzătoare datelor din tabelul 3. ![[rompho-2014-exp2-solutions-p4-f3.png]] <br> Observaţii: - se acordă câte 0,10p pentru indicarea mărimii şi a unităţii de măsură corespunzătoare fiecăreia dintre axele de coordonate; - se acordă 0,50p pentru marcarea corectă pe grafic a punctelor | 0,70p | 0,70p |
>
> corespunzătoare setului de date experimentale din tabelul 3.
>
> |   |   |   |   |
> |---|---|---|---|
> | 1.f. | Pentru: determinarea valorilor pentru intersecţia cu axele de coordonate a caracteristicii curent-tensiune şi pentru panta graficului, corespunzător datelor din tabelul 3: $\begin{cases}(0,I_{sc,31})\equiv(0,1{,}2)\\(U_{cd,31},0)\equiv(-4,0)\end{cases}$ şi $m_{31}=0{,}3\,\Omega^{-1}$ | 0,30p | 0,30p |
> | Nr. item | Sarcina de lucru nr. 2 | | Punctaj |
> | 2.a. | Pentru: schema unui circuit triunghi echivalent cu cutia neagră. ![[rompho-2014-exp2-solutions-p5-f3.png]] | 0,40p | 4,60p |
> | | schema echivalentă a circuitului, pentru primul set de măsurări, în cursul cărora sunt legate împreună bornele 1, 2, P şi respectiv 3, Q. ![[rompho-2014-exp2-solutions-p5-f4.png]] | 0,40p | |
> | | expresia caracteristicii curent-tensiune a cutiei negre pentru legarea $(1,2,P)$, $(3,Q)$: $i=U\cdot(\frac1{R_{23}}+\frac1{R_{31}})+(-\frac{E_{23}}{R_{23}}+\frac{E_{31}}{R_{31}})$; expresia pantei $m_{12}=\frac1{R_{23}}+\frac1{R_{31}}$; expresia intercepţiei $n_{12}=-\frac{E_{23}}{R_{23}}+\frac{E_{31}}{R_{31}}$ | 0,40p | |
> | | expresiile pentru intersecţiile cu axele de coordonate: $\begin{cases}I_{sc,12}=-\frac{E_{23}}{R_{23}}+\frac{E_{31}}{R_{31}}\\ U_{cd,12}=\frac{\frac{E_{23}}{R_{23}}-\frac{E_{31}}{R_{31}}}{\frac1{R_{23}}+\frac1{R_{31}}}\end{cases}$ | 0,40p | |
> | | expresia caracteristicii curent-tensiune a cutiei negre, pentru legarea $(2,3,P)$, $(1,Q)$: $i=U\cdot(\frac1{R_{31}}+\frac1{R_{12}})+(-\frac{E_{31}}{R_{31}}+\frac{E_{12}}{R_{12}})$; expresia pantei $m_{23}=\frac1{R_{31}}+\frac1{R_{12}}$; expresia intercepţiei $n_{23}=-\frac{E_{31}}{R_{31}}+\frac{E_{12}}{R_{12}}$ | 0,40p | |
> | | expresiile pentru intersecţiile cu axele de coordonate: $\begin{cases}I_{sc,23}=-\frac{E_{31}}{R_{31}}+\frac{E_{12}}{R_{12}}\\ U_{cd,23}=\frac{\frac{E_{31}}{R_{31}}-\frac{E_{12}}{R_{12}}}{\frac1{R_{31}}+\frac1{R_{12}}}\end{cases}$ | 0,40p | |
> | | expresia caracteristicii curent-tensiune a cutiei negre, pentru legarea $(3,1,P)$, $(2,Q)$: $i=U\cdot(\frac1{R_{12}}+\frac1{R_{23}})+(-\frac{E_{12}}{R_{12}}+\frac{E_{23}}{R_{23}})$; expresia pantei $m_{31}=\frac1{R_{12}}+\frac1{R_{23}}$; expresia intercepţiei $n_{31}=-\frac{E_{12}}{R_{12}}+\frac{E_{23}}{R_{23}}$ | 0,40p | |
> | | expresiile pentru intersecţiile cu axele de coordonate: $\begin{cases}I_{sc,31}=-\frac{E_{12}}{R_{12}}+\frac{E_{23}}{R_{23}}\\ U_{cd,31}=\frac{\frac{E_{12}}{R_{12}}-\frac{E_{23}}{R_{23}}}{\frac1{R_{12}}+\frac1{R_{23}}}\end{cases}$ | 0,40p | |
> | | determinarea valorilor rezistenţelor electrice şi ale tensiunilor electromotoare ale surselor, care formează circuitul electric: $R_{12}=10\Omega$, $R_{23}=5\Omega$, $R_{31}=2\Omega$, $E_{31}=10V$, $E_{23}=5V$, $E_{12}=-2V$ | 1,40p | |
> | **2.b.** | Pentru: | | **0,40p** |
> | | desenarea schemei circuitului electric echivalent, cu indicarea valorilor elementelor constitutive<br>![[rompho-2014-exp2-solutions-p7-f2.png]] | 0,40p | |
> | Nr. item | Sarcina de lucru nr. 3 | | Punctaj |
> | **3.a.** | Pentru: | | **2,00p** |
> | | schema echivalentă a circuitului realizat prin legarea $(1,P)$ şi $(2,Q)$<br>![[rompho-2014-exp2-solutions-p7-f3.png]]<br>determinarea dependenţei curent – tensiune pentru circuitul specificat $i=\frac{17}{70}U+\frac{164}{70}$ | 1,00p | |
> | | trasarea graficului pentru dependenţa curent-tensiune, în cazul în care terminalele P şi Q se leagă respectiv la terminalele 1 şi 2<br>![[rompho-2014-exp2-solutions-p8-f1.png]] | 0,60p | |
> | | valoarea intensităţii curentului electric de scurtcircuit $i_{sc}=\frac{164}{70}A$; valoarea tensiunii de circuit deschis $U_{cd}=-\frac{164}{17}V$ | 0,40p | |
> | Punctaj total - Problema experimentală nr. 2 | | | **10p** |
>
> © Barem de evaluare şi de notare propus de:
> Prof. Dr. Delia DAVIDESCU
> Conf. Univ. Dr. Adrian DAFINEI
