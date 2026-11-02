---
id: belpho-2001-final-theory-9-4
olympiad: BelPhO
year: 2001
stage: "Заключительный этап"
round: теория
grade: 9
number: "9-4"
title: "Задача 9-4"
points: 7
aliases: ["Задача 9-4"]
topics: ["[[1.3 Равноускоренное криволинейное движение]]", "[[1.6 Векторная кинематика]]"]
difficulty: 3
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Найти расстояние между баскетболистами по времени и высоте столкновения одновременно брошенных под разными углами мячей."
status: "проверено: сверка"
lang: ru
tags: [задача]
---

# 4. (7 баллов).

**BelPhO 2001** · Заключительный этап · теория · 9 класс · задача 9-4  
Источник: [[_pdf/BelPhO/2001-final-theoretical-problems.pdf#page=2|условие, стр. 2]] · [[_pdf/BelPhO/2001-final-theoretical-solutions.pdf#page=3|решение, стр. 3–4]]

Темы: [[1.3 Равноускоренное криволинейное движение]], [[1.6 Векторная кинематика]]

> [!abstract] Кратко (составлено моделью)
> Найти расстояние между баскетболистами по времени и высоте столкновения одновременно брошенных под разными углами мячей.

Два баскетболиста ростом $h=2{,}0\,\text{м}$ каждый бросили одновременно два мяча, один под углом $\alpha_1=30^\circ$, а второй под углом $\alpha_2=60^\circ$ к горизонту. Найдите расстояние между баскетболистами в момент броска, если известно, что брошенные мячи столкнулись в воздухе на высоте $H=5{,}0\,\text{м}$ над уровнем пола через время $\tau=1{,}0\,\text{с}$ после броска. Ускорение свободного падения $g=9{,}8\dfrac{\text{м}}{\text{с}^2}$. Сопротивлением воздуха пренебречь

> [!answer]- Ответ
> $$
> S=\left(H-h+\frac{g\tau^2}{2}\right)\cdot\left(\frac{\cos\alpha_1}{\sin\alpha_1}+\frac{\cos\alpha_2}{\sin\alpha_2}\right)\approx18\,\text{м}.
> $$
>
> $$
> S=|AC|=\frac{|AB|}{\cos\alpha_1}=\frac{1}{\cos\alpha_1}\cdot\frac{|BD|}{\sin\alpha_1}=\frac{H-h+\dfrac{g\tau^2}{2}}{\cos\alpha_1\sin\alpha_1},
> $$

> [!solution]- Решение
> **9.4** Из кинематических законов равноускоренного движения можно записать следующие уравнения
>
> ![[belpho-2001-final-theory-solutions-p3-f2.png]]
>
> $$
> \begin{cases}
> H-h=v_1\tau\sin\alpha_1-\dfrac{g\tau^2}{2}\\
> H-h=v_1\tau\sin\alpha_1-\dfrac{g\tau^2}{2}\\
> S=v_1\tau\cos\alpha_1+v_1\tau\cos\alpha_1
> \end{cases};\tag{1}
> $$
> Из первых двух уравнений следует выразить значения $v_1\tau$ и $v_2\tau$ и подставить их в третье уравнение системы (1)
>
> $$
> S=\left(H-h+\frac{g\tau^2}{2}\right)\cdot\left(\frac{\cos\alpha_1}{\sin\alpha_1}+\frac{\cos\alpha_2}{\sin\alpha_2}\right)\approx18\,\text{м}.\tag{2}
> $$
>
> *Данная задача допускает также более простое «геометрическое» решение. Представим закон движения каждого мяча в векторной форме $\vec{r}=\vec{v}\tau-\dfrac{\vec{g}\tau^2}{2}$ и изобразим его графически. Можно заметить, что треугольники $ABC$ и $ABD$ прямоугольные (т.к. $\alpha_1+\alpha_2=90^\circ$) поэтому*
>
> ![[belpho-2001-final-theory-solutions-p4-c5033.png]]
>
> $$
> S=|AC|=\frac{|AB|}{\cos\alpha_1}=\frac{1}{\cos\alpha_1}\cdot\frac{|BD|}{\sin\alpha_1}=\frac{H-h+\dfrac{g\tau^2}{2}}{\cos\alpha_1\sin\alpha_1},
> $$
> *что приводит к тому же численному результату.*
