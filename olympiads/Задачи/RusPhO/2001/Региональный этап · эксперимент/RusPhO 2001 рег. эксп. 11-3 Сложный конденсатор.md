---
id: ruspho-2001-region-experiment-11-3
olympiad: RusPhO
year: 2001
stage: "Региональный этап"
round: эксперимент
grade: 11
number: "11-3"
title: "Сложный конденсатор"
aliases: ["Сложный конденсатор"]
topics: ["[[3.8 Сложный конденсатор]]", "[[3.5 Энергия системы]]", "[[5.1 RC-цепи]]"]
difficulty: 3
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Найти теплоту на резисторах при подключении дополнительной батареи к трёхпластинчатому конденсатору."
status: "проверено: сверка"
lang: ru
tags: [задача]
---

# Задача 3. Сложный конденсатор

**RusPhO 2001** · Региональный этап · эксперимент · 11 класс · задача 11-3  
Источник: [[_pdf/RusPhO/2001-region-exp.pdf#page=3|условие, стр. 3]] · [[_pdf/RusPhO/2001-region-exp.pdf#page=5|решение, стр. 5]]

Темы: [[3.8 Сложный конденсатор]], [[3.5 Энергия системы]], [[5.1 RC-цепи]]

> [!abstract] Кратко (составлено моделью)
> Найти теплоту на резисторах при подключении дополнительной батареи к трёхпластинчатому конденсатору.

В сложном конденсаторе, состоящем из трех пластин (рис. 6), пластины 2 и 3 подсоединены к батарее с ЭДС $\mathcal E_2$. Пластины 1 и 3 подсоединены к батарее с ЭДС $\mathcal E_1$ с помощью ключа $K$. Какое количество тепла выделится на резисторах после замыкания ключа $K$, если площади пластин равны $S$, а расстояние между ними — $d$? Считайте, что $d^2\ll S$.

![[ruspho-2001-region-experiment-p3-c3341.png]]

> [!answer]- Ответ
> $$
> Q=\frac{S\varepsilon_0}{d}(\mathcal E_1-\mathcal E_2)^2-\frac{S\varepsilon_0}{2d}(\mathcal E_1-\mathcal E_2)^2=\frac{S\varepsilon_0}{2d}(\mathcal E_1-\mathcal E_2)^2.
> $$

> [!solution]- Решение
> # Задача 3. Сложный конденсатор
>
> Пусть после замыкания ключа заряд каждой из пластин равен $q_1$, $q_2$ и $q_3$. Из закона сохранения заряда следует, что $q_1+q_2+q_3=0$. Разность потенциалов между пластинами 2 и 3 равна $\mathcal E_2$. Следовательно,
>
> $$
> q_3-q_2-q_1=\frac{2S\varepsilon_0}{d}\mathcal E_2.
> $$
>
> Аналогично,
>
> $$
> q_3+q_2-q_1=\frac{2S\varepsilon_0}{d}(\mathcal E_1-\mathcal E_2).
> $$
>
> Решая систему уравнений, находим заряды на каждой из пластин:
>
> $$
> q_1=\frac{S\varepsilon_0}{d}(\mathcal E_2-\mathcal E_1),
> $$
>
> $$
> q_2=\frac{S\varepsilon_0}{d}(\mathcal E_1-2\mathcal E_2),
> $$
>
> $$
> q_3=\frac{S\varepsilon_0}{d}\mathcal E_2.
> $$
>
> Начальная энергия системы $W_0=\frac{S\varepsilon_0}{2d}\mathcal E_2^2$. Конечная энергия системы $W_1=\frac{S\varepsilon_0}{2d}[\mathcal E_2^2+(\mathcal E_1-\mathcal E_2)^2]$. Изменение энергии системы $\Delta W=\frac{S\varepsilon_0}{2d}(\mathcal E_1-\mathcal E_2)^2$.
>
> По закону сохранения энергии работа батарей пошла на изменение энергии конденсаторов плюс выделившееся тепло: $A=\Delta W+Q$. Начальный заряд пластины 1 равен нулю. Значит, работа батареи $\mathcal E_1$ равна $A_1=-\mathcal E_1\Delta q_1=-{}-\mathcal E_1q_1=\frac{S\varepsilon_0}{d}(\mathcal E_1-\mathcal E_2)\mathcal E_1$. Работа второй батареи $A_2=-\mathcal E_2\Delta q_2=-\mathcal E_2(q_2+{}+q_3)=\frac{S\varepsilon_0}{d}(\mathcal E_2-\mathcal E_1)\mathcal E_2$. Отсюда
>
> $$
> Q=\frac{S\varepsilon_0}{d}(\mathcal E_1-\mathcal E_2)^2-\frac{S\varepsilon_0}{2d}(\mathcal E_1-\mathcal E_2)^2=\frac{S\varepsilon_0}{2d}(\mathcal E_1-\mathcal E_2)^2.
> $$
