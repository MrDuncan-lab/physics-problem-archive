---
id: rompho-2010-intl-experiment-exp1
olympiad: RomPhO
year: 2010
stage: "Международная олимпиада"
round: эксперимент
grade: ""
number: "exp1"
title: "Determining the values of the parameters of a real diode by studying its current-voltage characteristic"
aliases: ["Determining the values of the parameters of a real diode by studying its current-voltage characteristic"]
topics: ["[[5.5 Нелинейные элементы в электрических цепях]]", "[[7 Эксперименты]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: true
source_damaged: false
summary: "По экспериментальной вольт-амперной характеристике определить параметры модели реального диода с последовательным и шунтирующим сопротивлениями."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 1. Determining the values of the parameters of a real diode by studying its current-voltage characteristic

**RomPhO 2010** · Международная олимпиада · эксперимент · задача 1  
Источник: [[_pdf/RomPhO/RomPhO-2010-exp1.pdf#page=1|условие, стр. 1–4]] · [[_pdf/RomPhO/RomPhO-2010-exp1-solution.pdf#page=5|критерии, стр. 5]]

Темы: [[5.5 Нелинейные элементы в электрических цепях]], [[7 Эксперименты]]

> [!abstract] Кратко (составлено моделью)
> По экспериментальной вольт-амперной характеристике определить параметры модели реального диода с последовательным и шунтирующим сопротивлениями.

A theoretical model is a number of mathematical equations which relate the quantities involved in a physical phenomenon. The validity of a model consists in the concordance between the measured data and the predicted values.

The simplest situation which can occur in a model is the case when two quantities $(y_{\mathrm{model}},x_{\mathrm{model}})$ are in a linear dependency. It is to be expected that the experimental pairs of measured values $(x_{\mathrm{measured}}^i,y_{\mathrm{measured}}^i)$, $i=\overline{1,N}$ are subject to imprecision. This is why the plotted pairs of coordinates form a “cloud” around the predicted straight line, called fitting line.

It is assumed that the best fit of the experimental data with the theoretical model is attained when the sum of the squared distances from these points to the predicted line has the smallest possible value. The slope $a$ and the slope-intercept $b$ for a linear model are given by
$$a=\frac{N\sum_{i=1}^N x_i\cdot y_i-\sum_{i=1}^N x_i\cdot\sum_{i=1}^N y_i}{N\cdot\sum_{i=1}^N x_i^2-\left(\sum_{i=1}^N x_i\right)^2}\tag{1}$$
$$b=\frac{\sum_{i=1}^N x_i^2\cdot\sum_{i=1}^N y_i-\sum_{i=1}^N x_i\cdot\sum_{i=1}^N x_i\cdot y_i}{N\cdot\sum_{i=1}^N x_i^2-\left(\sum_{i=1}^N x_i\right)^2}\tag{2}$$
Whether there really is a linear dependency between the two quantities is a matter described by the so-called correlation coefficient $G$.

$$G=\frac{N\cdot\sum_{i=1}^N x_i\cdot y_i-\sum_{i=1}^N x_i\cdot\sum_{i=1}^N y_i}{\sqrt{\left|N\cdot\sum_{i=1}^N x_i^2-\left(\sum_{i=1}^N x_i\right)^2\right|\cdot\left|N\cdot\sum_{i=1}^N y_i^2-\left(\sum_{i=1}^N y_i\right)^2\right|}}\tag{3}$$
$G=+1$ if there truly is a linear dependency with positive slope. $G=-1$ if there truly is a linear dependency with negative slope. In general, $-1\leq G\leq1$ and the more $G$ gets closer to 0, the less credible the linear dependency is.

Very few of the physical models imply a linear dependency, but often a suitable rearrangement of a mathematical function can lead to one. The relation between the current $I$ and the voltage $V$ for an ideal diode is given by

$$I=I_0\cdot\left(e^{\frac{qV}{\eta\cdot k_B\cdot T}}-1\right)\tag{4}$$
where $q=1.60\times10^{-19}\,C$ is the elementary electrical charge, and $k_B=1.38\times10^{-23}\,J\cdot K^{-1}$ is the Boltzmann constant. For ordinary experimental conditions, $T=300K$ and $q/(k_BT)=38.64\,V^{-1}$. The quantities which determine the non-linear dependency of $I$ with $V$ are the diode factor $\eta$ and the saturation current $I_0$. The curve $I$ versus $V$ looks something like in Figure 1. When subject to large enough positive voltages, the diode’s resistance can be considered zero. When subject to large enough negative voltages, the diode’s resistance can be considered infinite.

![[rompho-2010-exp1-problems-p2-f1.png]]
*Figure 1. Schematic curve for the I-V characteristic of an ideal diode*

Admitting that $0{,}5\leq\eta\leq3$, for $V<0$ we get $qV/(\eta\cdot k_B\cdot T)\ll0$ and thus $e^{\frac{qV}{\eta\cdot k_B\cdot T}}\cong0$. So, for reversed polarity, (4) reduces to
$$I=-I_0\tag{5}$$
Plotting the I-V characteristic for negative polarity we get a line parallel to the V-axis, which allows us to determine the value of $I_0$.

For $V>0$, $qV/(\eta\cdot k_B\cdot T)\gg0$ and thus $e^{\frac{qV}{\eta\cdot k_B\cdot T}}\gg1$. Consequently, (4) becomes
$$I=I_0\cdot e^{\frac{qV}{\eta\cdot k_B\cdot T}}\tag{6}$$
or
$$\ln(I)=\ln(I_0)+\frac{qV}{\eta k_BT}\tag{7}$$
As you can see, writing the I-V characteristic as $\ln(I)=f(V)$, we get a linear dependency. The slope allows us to determine the value of the diode factor, while the slope-intercept allows us to determine the value of the saturation current.

One can consider that a „real” diode consists of an ideal diode connected in parallel with a shunt with resistance $R$, and the whole connected in series with a resistor $r$. Typical values for the characteristic resistances of $r$ and $R$ are $0.01\Omega<r<10\Omega$, and $75k\Omega<R<1M\Omega$ respectively.

The I-V characteristic of a real diode is given by
$$I=I_0\cdot\left(e^{\frac{q(V-r\cdot I)}{\eta\cdot k_B\cdot T}}-1\right)+\frac{V-r\cdot I}{R}\tag{8}$$
Experimental problem 1 asks you to determine the values of the parameters $R,r,I_0,\eta$ of a diode, by using the data in the following two tables.

*Table 1. Pairs of experimental data current-voltage for a real diode with reversed polarity*

| No. | U(V) | I($\mu$A) | Nr. | U(V) | I($\mu$A) | Nr. | U(V) | I($\mu$A) | Nr. | U(V) | I($\mu$A) |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 1 | 0 | 0 | 9 | -0.5 | -11 | 16 | -1.2 | -12 | 24 | -2 | -14 |
| 2 | -0.05 | -6 | 10 | -0.6 | -11 | 17 | -1.3 | -13 | 25 | -2.05 | -14 |
| 3 | -0.1 | -9 | 11 | -0.7 | -11 | 18 | -1.4 | -13 | 26 | -2.1 | -14 |
| 4 | -0.15 | -10 | 12 | -0.8 | -12 | 19 | -1.5 | -13 | 27 | -2.2 | -14 |
| 5 | -0.2 | -10 | 13 | -0.9 | -12 | 20 | -1.6 | -13 | 28 | -2.3 | -15 |
| 6 | -0.25 | -10 | 14 | -1 | -12 | 21 | -1.7 | -13 | 29 | -2.4 | -15 |
| 7 | -0.3 | -11 | 15 | -1.1 | -12 | 22 | -1.8 | -14 | 30 | -2.5 | -15 |
| 8 | -0.4 | -11 | | | | 23 | -1.9 | -14 | | | |

In order to determine the values of the parameters of the diode for reversed polarity follow the below procedure:

1. In the corresponding box on the answer sheet write down the expression of (6) for large values of the negative voltage $V\ll0$.
2. Using the experimental data, plot on the provided milimetric paper the I-V curve for reversed polarity.
3. In the corresponding box on the answer sheet write down the linear form of the I-V characteristic for reversed polarity and indicate the expressions of the slope $a$ and of the slope-intercept $b$.
4. Neglect from the experimental data the entries corresponding to small values of the negative voltage, and fill in Table 3 on the answer sheet.
5. Determine the parameters of the fitting line and fill in the corresponding boxes on the answer sheet.
6. Determine the correlation coefficient and write it down in the corresponding box on the answer sheet.
7. Determine the values of the parameters $R,I_0$ and write them down in the corresponding boxes on the answer sheet.

*Table 2. Pairs of experimental data current-voltage for a real diode with forward polarity*

| No. | Voltage (V) | Current (A) | No. | Voltage (V) | Current (A) |
|---|---|---|---|---|---|
| 1 | 0.345 | 0.007 | 11 | 0.491 | 0.082 |
| 2 | 0.383 | 0.015 | 12 | 0.498 | 0.090 |
| 3 | 0.406 | 0.022 | 13 | 0.504 | 0.097 |
| 4 | 0.423 | 0.030 | 14 | 0.511 | 0.105 |
| 5 | 0.437 | 0.037 | 15 | 0.516 | 0.112 |
| 6 | 0.449 | 0.045 | 16 | 0.522 | 0.120 |
| 7 | 0.459 | 0.052 | 17 | 0.527 | 0.127 |
| 8 | 0.468 | 0.060 | 18 | 0.533 | 0.135 |
| 9 | 0.477 | 0.067 | 19 | 0.538 | 0.142 |
| 10 | 0.484 | 0.075 | 20 | 0.543 | 0.150 |

In order to determine the values of the parameters of the diode for forward polarity follow the below procedure:

8. In the corresponding box on the answer sheet write down the expression of (6) for large values of the positive voltage, $V\gg0$.
9. Using the experimental data, plot on the provided milimetric paper the graph $\ln(I)=f(V)$ for forward polarity.
10. Fill in Table 4 on the answer sheet only with the experimental data corresponding to moderate values of the positive voltage.
11. Determine the parameters of the fitting line and fill in the corresponding boxes on the answer sheet.
12. Determine the correlation coefficient and write it down in the corresponding box on the answer sheet.
13. Draw on the graph plotted at point 9 the resulting fitting line.
14. Determine the values of the parameters $\eta,I_0$ and write them down in the corresponding boxes on the answer sheet.
15. The measured data for large positive voltages lay below the fitting line. Try to provide an explanation for this fact
16. Determine the value of the resistor $r$ and write it down in the corresponding box on the answer sheet.

Delia DAVIDESCU – National Centre for Assessment and Examination - MECTS  
Adrian DAFINEI, Ph.D. – Faculty of Physics – University of Bucharest

> [!solution]- Решение (схема оценивания)
> Evaluation Sheet
>
> Any other correct solution will be evaluated accordingly
>
> | No. | Experimental problem 1 | | Points |
> |---|---|---|---|
> | 1. | For: $I=-I_0\cdot+\dfrac VR$ | 0.4p | 0.4p |
> | 2. | For: ![[rompho-2010-exp1-solutions-p5-c1336.png]] | 0.6p | 0.6p |
> | 3. | For: Linear expression of the $I-V$ characteristic for reversed polarity $I=\dfrac VR-I_0$ | 0.2p | 0.6p |
> | | $a=1/R$ | 0.2p | |
> | | $b=-I_0$ | 0.2p | |
> | 4. | For: correctly filling in the Table 3 | 0.8p | 0.8p |
> | 5. | For: the slope of the fitting line $a=\dfrac{10\sum_{i=1}^{10}U_iI_i-\sum_{i=1}^{10}U_i\cdot\sum_{i=1}^{10}I_i}{10\cdot\sum_{i=1}^{10}U_i^2-\left(\sum_{i=1}^{10}U_i\right)^2}$; $a=\dfrac{10\cdot298.8-20.95\cdot142}{10\cdot44.49-(20.95)^2}=\dfrac{13.1}{5.99}\dfrac{\mu A}{V}=2.18\times10^{-6}\dfrac AV$ | 0.4p | 0.8p |
> | | the slope-intercept of the fitting line $b=\dfrac{\sum_{i=1}^{10}U_i^2\cdot\sum_{i=1}^{10}I_i-\sum_{i=1}^{10}U_i\cdot\sum_{i=1}^{10}U_iI_i}{10\cdot\sum_{i=1}^{N}U_i^2-\left(\sum_{i=1}^{N}U_i\right)^2}$; $b=\dfrac{44.49\cdot(-142)-(-20.95)\cdot298.8}{5.99}=\dfrac{-57.72}{5.99}\,\mu A=-9.6\mu A$ | 0.4p | |
> | 6. | For: the correlation coefficient for the presumed linear dependency $G=\dfrac{10\cdot\sum_{i=1}^{10}U_iI_i-\sum_{i=1}^{10}U_i\cdot\sum_{i=1}^{10}I_i}{\sqrt{\left|10\cdot\sum_{i=1}^{10}U_i^2-\left(\sum_{i=1}^{10}U_i\right)^2\right|\cdot\left|10\cdot\sum_{i=1}^{10}I_i^2-\left(\sum_{i=1}^{10}I_i\right)^2\right|}}$; $G=\dfrac{10\times298.8-20.95\times142}{\sqrt{5.99\times36}}=\dfrac{13.1}{14.6}\cong0.90$ | 0.4p | 0.4p |
> | 7. | For: $I_0=9.6\mu A$ | 0.4p | 0.8p |
> | | $R=\dfrac1a\cong460k\Omega$ | 0.4p | |
> | 8. | For: $I=I_0\cdot e^{\frac{q(V-r\cdot I)}{\eta\cdot k_B\cdot T}}$ | 0.4p | 0.4p |
> | 9. | For: $\ln(I)=\ln(I_0)+\dfrac{q(V-rI)}{\eta k_BT}$ | 0.2p | 1.0p |
> | | for experimental data within the range $V>rI$, $\ln(I)=\ln(I_0)+\dfrac{qV}{\eta k_BT}$ | 0.2p | |
> | | ![[rompho-2010-exp1-solutions-p7-f1.png]] | 0.6p | |
> | 10. | For: correctly filling in table 4 | 0.8p | 0.8p |
> | 11. | For: the slope of the fitting line $a=\dfrac{10\sum_{i=1}^{10}U_i\ln(I_i)-\sum_{i=1}^{10}U_i\cdot\sum_{i=1}^{10}\ln(I_i)}{10\cdot\sum_{i=1}^{10}U_i^2-\left(\sum_{i=1}^{10}U_i\right)^2}$; $a=\dfrac{10\cdot(-12.493)+(4.857)\cdot(25.849)}{10\cdot(2.363)-(4.857)^2}=\dfrac{0.6185}{0.0395}=15.66$ | 0.4p | 0.8p |
> | | the slope-intercept of the fitting line $b=\dfrac{\sum_{i=1}^{10}U_i^2\cdot\sum_{i=1}^{10}\ln(I_i)-\sum_{i=1}^{10}U_i\cdot\sum_{i=1}^{10}U_i\ln(I_i)}{10\cdot\sum_{i=1}^{N}U_i^2-\left(\sum_{i=1}^{N}U_i\right)^2}$; $b=\dfrac{(2.363)\cdot(-25.849)+(4.857)\cdot(12.493)}{0.0395}=\dfrac{-0.403}{0.0395}=-10.15$ | 0.4p | |
> | 12. | For: the correlation coefficient for the presumed linear dependency $G=\dfrac{10\cdot\sum_{i=1}^{10}U_i\ln(I_i)-\sum_{i=1}^{10}U_i\cdot\sum_{i=1}^{10}\ln(I_i)}{\sqrt{\left|10\cdot\sum_{i=1}^{10}U_i^2-\left(\sum_{i=1}^{10}U_i\right)^2\right|\cdot\left|10\cdot\sum_{i=1}^{10}(\ln(I_i))^2-\left(\sum_{i=1}^{10}\ln(I_i)\right)^2\right|}}$; $G=\dfrac{0.6185}{\sqrt{0.04\cdot8.4}}\cong1$ | 0.4p | 0.4p |
> | 13. | For: ![[rompho-2010-exp1-solutions-p8-c1310.png]] | 0.6p | 0,6p |
> | 14. | For: $\begin{cases}\eta=\dfrac q{a\cdot k_BT}\\I_0=e^b\end{cases}$ | 0.4p | 0.8p |
> | | $\begin{cases}\eta=\dfrac{38{,}64}{15{,}66}=2.4\\I_0=3.7\times10^{-5}A\cong30\mu A\end{cases}$ | 0,4p | |
> | 15. | For: ![[rompho-2010-exp1-solutions-p8-c1253.png]]; $\Delta V=rI$, $0.02=r\cdot0.15$ | 0.6p | 0.6p |
> | 16. | For: $r\cong0.2\Omega$ | 0.2p | 0.2p |
> | TOTAL | | | 10p |
