---
id: ruspho-2000-region-theory-t1-10-5
olympiad: RusPhO
year: 2000
stage: "Региональный этап, 1 тур"
round: теория
grade: 10
number: "10-5"
title: "Борьба за КПД"
aliases: ["Борьба за КПД"]
topics: ["[[2.8 Тепловые двигатели]]", "[[2.5 Первое начало термодинамики]]", "[[2.9 Прямая с отрицательным наклоном]]"]
difficulty: 3
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Найти максимально возможный КПД треугольного цикла одноатомного идеального газа с изохорным и изобарным участками."
status: "проверено: сверка"
lang: ru
tags: [задача]
---

# Задача 5. Борьба за КПД

**RusPhO 2000** · Региональный этап, 1 тур · теория · 10 класс · задача 10-5  
Источник: [[_pdf/RusPhO/2000-region-theor-1.pdf#page=3|условие, стр. 3–4]] · [[_pdf/RusPhO/2000-region-theor-1.pdf#page=6|решение, стр. 6–7]]

Темы: [[2.8 Тепловые двигатели]], [[2.5 Первое начало термодинамики]], [[2.9 Прямая с отрицательным наклоном]]

> [!abstract] Кратко (составлено моделью)
> Найти максимально возможный КПД треугольного цикла одноатомного идеального газа с изохорным и изобарным участками.

Найдите максимально возможное значение КПД $\eta$ цикла, в котором участвует идеальный одноатомный газ. В $PV$-координатах цикл имеет форму прямоугольного треугольника, левый катет которого — изохора, а верхний катет — изобара (рис. 5).

![[ruspho-2000-region-theory-1-p3-c6618.png]]

*Рис. 5*

> [!answer]- Ответ
> $$
> \eta_\text{max}=\frac{1}{2\dfrac{c_P}{R}\left(\dfrac{\Delta P}{\Delta P}\right)}=\frac{R}{2c_p}=\frac{1}{5}.
> $$

> [!solution]- Решение
> # Задача 5. Борьба за КПД
>
> Из рис. 14 видно, что
>
> $$
> \eta=\frac{A}{Q_V+Q_P},\tag{1}
> $$
>
> здесь
>
> $$
> A=\frac{1}{2}\Delta P\Delta V.\tag{2}
> $$
>
> Тепло, подводимое к газу на изобаре и изохоре, есть
>
> $$
> Q_V=\nu c_V\Delta T_1\tag{3}
> $$
>
> и
>
> $$
> Q_P=\nu c_P\Delta T_2.\tag{4}
> $$
>
> $\Delta T_1$ и $\Delta T_2$ найдем из уравнения состояния:
>
> $$
> PV=\nu RT,\ \Rightarrow\ V_1\Delta P=\nu R\Delta T_1,\tag{5}
> $$
>
> $$
> P_2\Delta V=\nu R\Delta T_2.\tag{6}
> $$
>
> Подставляя (2),(3) и (4) в (1), получим:
>
> $$
> \eta=\frac{1}{2}\frac{\Delta P\Delta V}{\nu c_V\dfrac{V_1\Delta P}{\nu R}+\nu c_P\dfrac{P_2\Delta V}{\nu R}},
> $$
>
> $$
> \eta=\frac{1}{2\left(\dfrac{c_V}{R}\dfrac{V_1}{\Delta V}+\dfrac{c_P}{R}\dfrac{P_2}{\Delta P}\right)}.\tag{7}
> $$
>
> Из (7) видно, что при уменьшении $V_1$ и $P_2$ КПД цикла возрастает. $\min V_1=0$, $\min P_2=\Delta P$. Отсюда,
>
> $$
> \eta_\text{max}=\frac{1}{2\dfrac{c_P}{R}\left(\dfrac{\Delta P}{\Delta P}\right)}=\frac{R}{2c_p}=\frac{1}{5}.
> $$
>
> ![[ruspho-2000-region-theory-1-p7-c1209.png]]
> *Рис. 14*
