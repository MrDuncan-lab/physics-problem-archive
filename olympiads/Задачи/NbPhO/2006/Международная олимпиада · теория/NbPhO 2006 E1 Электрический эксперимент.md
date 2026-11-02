---
id: nbpho-2006-intl-theory-e1
olympiad: NbPhO
year: 2006
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "E1"
title: "Электрический эксперимент"
points: 12
aliases: ["Электрический эксперимент"]
topics: ["[[7 Эксперименты]]", "[[5.1 RC-цепи]]", "[[5.5 Нелинейные элементы в электрических цепях]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Измерить неизвестную ёмкость с помощью светодиода, резисторов и секундомера."
status: "проверено: сверка"
lang: ru
tags: [задача]
---

# 4 Электрический эксперимент (12 баллов)

**NbPhO 2006** · Международная олимпиада · теория · 10–12 класс · задача E1  
Источник: [[_pdf/NbPhO/nbpho-2006.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2006.pdf#page=3|решение, стр. 3]]

Темы: [[7 Эксперименты]], [[5.1 RC-цепи]], [[5.5 Нелинейные элементы в электрических цепях]]

> [!abstract] Кратко (составлено моделью)
> Измерить неизвестную ёмкость с помощью светодиода, резисторов и секундомера.

Найти ёмкость неизвестного конденсатора и оценить погрешность. Оборудование: красный световой диод, три резистора, сопротивление одного из которых $R_1=1.5\,\text{кОм}$, другого $R_1=2.6\,\text{кОм}$, а сопротивление ещё одного неизвестно, источник постоянного напряжения с неизвестным эдс (внутреннее сопротивление менее $500\,\text{Ом}$), соединительные провода, секундомер, конденсатор неизвестной ёмкости.

*Примечания:* На графике приведена типичная вольт-амперная характеристика светового диода; при планировании данного опыта можете считать световой диод идеальным, см. график. Значение порогового напряжения $U_c$ диода неизвестно. Диод светится тогда, когда через него идёт ток.

![[nbpho-2006-p1-c6729.png]]

Если конденсатор ёмкостью $C$, резистор $R$ и электродвижущая сила $E$ соединены последовательно в замкнутый контур, то приближение напряжения конденсатора к равновесному значению происходит экспоненциально: $U=E\pm U_0e^{-t/RC}$.

> [!answer]- Ответ
> $$
> C=(\tau_2/R_2-\tau_1/R_1)/\ln\frac{R_1}{R_2}.
> $$
>
> $C\approx13\,\mu\mathrm F$.

> [!solution]- Решение
> # 4. Electrical experiment
>
> We start with charging the capacitor (waiting long enough, to allow equalizing the voltages of the source and the capacitor, of the order of the discharge time below). The capacitor will be discharge on the diode and two resistances (the unknown one $r$ is parallel to the diode), using the scheme in the figure. We perform two experiments using for the sequentially connected resistor $R$ the both supplied resistors with known resistance, $R=R_1$ and $R=R_2$.
>
> ![[nbpho-2006-p3-c5658.png]]
>
> Initial voltage of the capacitor $U_0=\mathcal E$; the voltage drop on the diode is constant (while emitting light) — exactly as on a voltage source. Therefore, the voltage on the capacitor approaches that value exponentially:
> $$U-U_c=(\mathcal E-U_c)e^{-t/RC}.$$
> Diode stops burning, when all the current $I=(U-U_c)/R$ goes through the unknown resistor, $I=U_c/r$. Thus, at the fading moment ($t=\tau$):
> $$r(\mathcal E-U_c)e^{-\tau/RC}=RU_c.$$
> Rewriting the latter equality for the both experiments,
> $$r(\mathcal E-U_c)e^{-\tau_1/R_1C}=R_1U_c.$$
> $$r(\mathcal E-U_c)e^{-\tau_2/R_2C}=R_2U_c.$$
> Dividing these and taking the logarithm results in
>
> $$C=(\tau_2/R_2-\tau_1/R_1)/\ln\frac{R_1}{R_2}.$$
> Performing for both cases 3–5 measurements and finding the average ($\tau_1\approx37\,\mathrm s$, $\tau_2\approx32{,}4\,\mathrm s$), we find
> $C\approx13\,\mu\mathrm F$.
