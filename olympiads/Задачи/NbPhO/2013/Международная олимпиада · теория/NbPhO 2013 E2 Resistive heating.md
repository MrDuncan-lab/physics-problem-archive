---
id: nbpho-2013-intl-theory-e2
olympiad: NbPhO
year: 2013
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "E2"
title: "Resistive heating"
points: 8
aliases: ["Resistive heating"]
topics: ["[[7 Эксперименты]]", "[[2.1 Уравнение теплового баланса. 8-ой класс]]", "[[5 Цепи]]"]
difficulty: 3
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Измерить сопротивление резистора калориметрическим методом при изменяющемся токе."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 10. RESISTIVE HEATING (8 points)

**NbPhO 2013** · Международная олимпиада · теория · 10–12 класс · задача E2  
Источник: [[_pdf/NbPhO/nbpho-2013.pdf#page=2|условие, стр. 2–3]] · [[_pdf/NbPhO/nbpho-2013.pdf#page=6|решение, стр. 6]]

Темы: [[7 Эксперименты]], [[2.1 Уравнение теплового баланса. 8-ой класс]], [[5 Цепи]]

> [!abstract] Кратко (составлено моделью)
> Измерить сопротивление резистора калориметрическим методом при изменяющемся токе.

Measure the resistor. You are not asked to estimate the uncertainty.

*Equipment:* resistor, voltage source (batteries), ammeter, calorimeter, thermometer, stopwatch.

The calorimeter has $V=0.80\mathrm{dl}$ of water and $m_a=27\mathrm{g}$ of aluminum, specific heat capacity of water $c_w=4.2\mathrm{J/(K\cdot g)}$ and of aluminum $c_a=0.90\mathrm{J/(K\cdot g)}$. Internal resistance of the batteries will vary. Your set of batteries may become depleted, spares are available.

Estonian-Finnish Olympiad 2013

> [!answer]- Ответ
> $$
> R=\frac{(c_am_a+c_wm_w)\Delta T}{\sum_n\Delta t(I_n/2+I_{n+1}/2)^2}.
> $$
>
> $R=0.47\Omega\pm5\%$. In the described circuit the batteries were depleted in 10 to 15 minutes and the temperature of the calorimeter rose by 7 to 10 degrees.

> [!solution]- Решение
> # 10. RESISTIVE HEATING (8 points)
>
> After noting the temperature of the calorimeter, connect the batteries, resistor (in the calorimeter) and ammeter in series. Choose a convenient time interval $\Delta t$ and note the ammeter reading until batteries are depleted. Measure the temperature at the end, after waiting a bit or stirring the calorimeter. We want to get maximum temperature difference for precise measurement. Since $P=RI^2$,
>
> $$\frac QR\approx\sum_n\Delta t(I_n/2+I_{n+1}/2)^2,$$
>
> $$R=\frac{(c_am_a+c_wm_w)\Delta T}{\sum_n\Delta t(I_n/2+I_{n+1}/2)^2}.$$
>
> The resistance used was
> $R=0.47\Omega\pm5\%$. In the described circuit the batteries were depleted in 10 to 15 minutes and the temperature of the calorimeter rose by 7 to 10 degrees.
