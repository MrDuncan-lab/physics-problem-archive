---
id: nbpho-2011-intl-theory-e1
olympiad: NbPhO
year: 2011
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "E1"
title: "Black box"
points: 10
aliases: ["Black box"]
topics: ["[[7 Эксперименты]]", "[[5.1 RC-цепи]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Определить неизвестную ёмкость в чёрном ящике и оценить погрешность."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 4. Black box (10 points)

**NbPhO 2011** · Международная олимпиада · теория · 10–12 класс · задача E1  
Источник: [[_pdf/NbPhO/nbpho-2011.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2011.pdf#page=3|решение, стр. 3–4]]

Темы: [[7 Эксперименты]], [[5.1 RC-цепи]]

> [!abstract] Кратко (составлено моделью)
> Определить неизвестную ёмкость в чёрном ящике и оценить погрешность.

*Equipment:* a black box with three terminals, voltmeter, timer. Inside the black box, there are two capacitors and a battery, connected as shown in Figure. The capacitance $C_1=(3400+400)\mu\mathrm{F}$; you are asked to determine the capacitance $C_2$ and estimate the uncertainty. *Remark:* the terminal “+” is a wire, long enough to be connected to either terminal “A” or terminal “B”.

![[nbpho-2011-p1-f1.svg]]

> [!answer]- Ответ
> $C_2=C_1t_2/t_1$; the uncertainty is estimated as
>
> $\Delta C_1=C_1\left(\frac{\Delta t_1}{t_1}+\frac{\Delta t_2}{t_2}+\frac{\Delta C_1}{C_1}\right)$.
>
> $C_2=(\frac{\mathcal E}{U}-1)C_1$.

> [!solution]- Решение
> # 4. Black box (10 points)
>
> There are several ways to perform this task. First one can notice that if two capacitors discharge at the same resistor, starting with equal voltages and ending also with equal voltages, the ratio of the discharge times equals to the ratio of the capacitances (because for each given voltage, the discharge currents are the same, but larger capacitor has more charge — proportionally to the capacitance). Therefore we can first charge the known capacitor (using the battery), and let it discharge on the voltmeter (which has some finite resistance), measuring the time $t_1$ required for it to reach a pre-defined final voltage. Then we need to repeat the procedure with the other capacitor and measure the time $t_2$ and calculate
> $C_2=C_1t_2/t_1$; the uncertainty is estimated as
> $\Delta C_1=C_1\left(\frac{\Delta t_1}{t_1}+\frac{\Delta t_2}{t_2}+\frac{\Delta C_1}{C_1}\right)$.
>
> It is recommended to check the negligibility of the leak current across the plates of the capacitor. To this end, one can charge a capacitor, measure the voltage, remove the voltmeter and wait for some time (of the order $t_1$ and $t_2$), and check again the voltage.
>
> Another way is to discharge completely one capacitor by short-circuiting its terminals and charge the other capacitor up to the voltage of the battery. Further, we connect the terminals $A$ and $B$ so that the capacitors re-distribute the charge $Q=\mathcal EC_1$ and take the same voltage: $Q_1/C_1=(Q-Q_1)/C_2\Rightarrow Q_1=QC_1/(C_1+C_2)=\mathcal EC_1^2/(C_1+C_2)$. Consequently, the new voltage (which we measure) is $U=Q_1/C_1=\mathcal EC_1/(C_1+C_2)$, from where
> $C_2=(\frac{\mathcal E}{U}-1)C_1$.
