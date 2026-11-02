---
id: belpho-1995-final-theory-10-1
olympiad: BelPhO
year: 1995
stage: "Заключительный этап"
round: теория
grade: 10
number: "10-1"
title: "Задача 10-1"
aliases: ["Задача 10-1"]
topics: ["[[1.15 Упругость. Весомая пружина]]", "[[1 Механика]]"]
difficulty: 3
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "По графику механического напряжения в ускоряемом стержне определить изменение плотности материала между двумя сечениями."
status: "проверено: сверка"
lang: ru
tags: [задача]
---

# 10-1.

**BelPhO 1995** · Заключительный этап · теория · 10 класс · задача 10-1  
Источник: [[_pdf/BelPhO/1995-final-theoretical-problems.pdf#page=2|условие, стр. 2]] · [[_pdf/BelPhO/1995-final-theoretical-solutions.pdf#page=4|решение, стр. 4]]

Темы: [[1.15 Упругость. Весомая пружина]], [[1 Механика]]

> [!abstract] Кратко (составлено моделью)
> По графику механического напряжения в ускоряемом стержне определить изменение плотности материала между двумя сечениями.

Стержень постоянного поперечного сечения движется поступательно с некоторым ускорением. График зависимости механического напряжения $\sigma(x)$ в стержне от расстояния $x$ до конца $B$ приведен на рисунке. Известно, что в сечении $1$ плотность материала стержня $\rho=3{,}0\text{ г/см}^3$. Пользуясь графиком, определите плотность материала стержня в сечении $2$.

![[belpho-1995-final-theory-problems-p2-c5737.png]]

> [!answer]- Ответ
> $$
> \frac{\operatorname{tg}\alpha_1}{\rho_1}=\frac{\operatorname{tg}\alpha_2}{\rho_2}\Rightarrow\rho_2=\rho_1\frac{\operatorname{tg}\alpha_2}{\operatorname{tg}\alpha_1}=3{,}0\frac{\operatorname{tg}37^\circ}{\operatorname{tg}56^\circ}=5{,}9\text{ г/см}^3.
> $$

> [!solution]- Решение
> **10-1.** Пусть зависимость силы натяжения в стержне от расстояния $T(x)$. Тогда $T(x)=\sigma(x)\cdot S$,, где $S$ — площадь поперечного сечения стержня. Рассмотрим движение малого участка стержня длиной $\Delta x_i$; согласно основному закону динамики имеем:
>
> $$
> \rho_iS\Delta x_i a=T(x+\Delta x)-T(x)=\Delta T(x)=\Delta\sigma(x)\cdot S
> $$
>
> ![[belpho-1995-final-theory-solutions-p4-c7041.png]]
>
> Отсюда:
>
> $$
> a=const=\frac{\Delta\sigma(x)}{\Delta x_i}\frac{1}{\rho_i}=\frac{\operatorname{tg}\alpha_i}{\rho_i},
> $$
>
> где $\operatorname{tg}\alpha_i$ — тангенс угла наклона касательной к графику в соответствующей точке. Тогда:
>
> $$
> \frac{\operatorname{tg}\alpha_1}{\rho_1}=\frac{\operatorname{tg}\alpha_2}{\rho_2}\Rightarrow\rho_2=\rho_1\frac{\operatorname{tg}\alpha_2}{\operatorname{tg}\alpha_1}=3{,}0\frac{\operatorname{tg}37^\circ}{\operatorname{tg}56^\circ}=5{,}9\text{ г/см}^3.
> $$
>
> $\alpha_1$ и $\alpha_2$ — углы наклона касательных к графику в сечениях 1 и 2.
