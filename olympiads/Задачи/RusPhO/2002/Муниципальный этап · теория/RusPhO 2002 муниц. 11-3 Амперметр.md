---
id: ruspho-2002-municipal-theory-11-3
olympiad: RusPhO
year: 2002
stage: "Муниципальный этап"
round: теория
grade: 11
number: "11-3"
title: "Амперметр"
aliases: ["Амперметр"]
topics: ["[[5 Цепи]]"]
difficulty: 2
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Найти показание идеального амперметра в резисторной цепи с несколькими идеальными источниками напряжения."
status: "проверено: сверка"
lang: ru
tags: [задача]
---

# Задача 3. Амперметр

**RusPhO 2002** · Муниципальный этап · теория · 11 класс · задача 11-3  
Источник: [[_pdf/RusPhO/2002-municipal.pdf#page=4|условие, стр. 4]] · [[_pdf/RusPhO/2002-municipal.pdf#page=9|решение, стр. 9]]

Темы: [[5 Цепи]]

> [!abstract] Кратко (составлено моделью)
> Найти показание идеального амперметра в резисторной цепи с несколькими идеальными источниками напряжения.

Найдите показания $I$ идеального амперметра в цепи (рис. 11). Параметры элементов схемы известны: $\mathcal{E}_1=1$ В, $\mathcal{E}_2=2$ В, $\mathcal{E}_3=4$ В, $R=3$ Ом. Внутренним сопротивлением источников пренебречь.

![[ruspho-2002-municipal-theory-p4-c8447.png]]
*Рис. 11*

> [!answer]- Ответ
> $$
> I=I_1+I_2=\frac{\mathcal{E}_1+2\mathcal{E}_2+\mathcal{E}_3}{R}=3\text{ А}.
> $$

> [!solution]- Решение
> # Задача 3. Амперметр
>
> Выберем направления токов $I$, $I_1$, $I_2$ (рис. 19) и запишем второй закон Кирхгофа для двух контуров (левого и правого):
>
> $$
> \mathcal{E}_1+\mathcal{E}_2=I_1R,\qquad\mathcal{E}_2+\mathcal{E}_3=I_2R.
> $$
>
> Искомый ток через амперметр
>
> $$
> I=I_1+I_2=\frac{\mathcal{E}_1+2\mathcal{E}_2+\mathcal{E}_3}{R}=3\text{ А}.
> $$
>
> ![[ruspho-2002-municipal-theory-p9-f1.svg]]
