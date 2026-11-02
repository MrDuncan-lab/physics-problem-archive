---
id: belpho-1995-final-theory-10-4
olympiad: BelPhO
year: 1995
stage: "Заключительный этап"
round: теория
grade: 10
number: "10-4"
title: "Задача 10-4"
aliases: ["Задача 10-4"]
topics: ["[[3.8 Сложный конденсатор]]", "[[1.15 Упругость. Весомая пружина]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Найти напряжение, при котором электрические силы разорвут диэлектрическую пластинку внутри плоского конденсатора."
status: "проверено: сверка"
lang: ru
tags: [задача]
---

# 10-4.

**BelPhO 1995** · Заключительный этап · теория · 10 класс · задача 10-4  
Источник: [[_pdf/BelPhO/1995-final-theoretical-problems.pdf#page=3|условие, стр. 3]] · [[_pdf/BelPhO/1995-final-theoretical-solutions.pdf#page=6|решение, стр. 6–7]]

Темы: [[3.8 Сложный конденсатор]], [[1.15 Упругость. Весомая пружина]]

> [!abstract] Кратко (составлено моделью)
> Найти напряжение, при котором электрические силы разорвут диэлектрическую пластинку внутри плоского конденсатора.

Внутрь плоского конденсатора, расстояние между пластинами которого $D$, вставили пластину из диэлектрика с проницаемостью $\varepsilon$ и толщиной $d$ ($d<D$). Грани пластины параллельны обкладкам конденсатора. Какое напряжение нужно подать на обкладки конденсатора, чтобы пластина разорвалась? Предел прочности материала пластины $\sigma_0$.

> [!answer]- Ответ
> $$
> U=\frac{\sigma}{\varepsilon_0}\left(D-d+\frac{d}{\varepsilon}\right)
> =\frac{D-\frac{\varepsilon-1}{\varepsilon}d}{\varepsilon_0}\sqrt{\frac{2\varepsilon^2\varepsilon_0}{\varepsilon^2-1}P_\text{пр}}
> =(D\varepsilon-(\varepsilon-1)d)\sqrt{\frac{2P_\text{пр}}{\varepsilon_0(\varepsilon^2-1)}}.
> $$

> [!solution]- Решение
> **10-4.** Пусть поверхностная плотность заряда на обкладках конденсатора равна $\sigma$. Тогда на поверхности диэлектрика:
>
> $$
> \sigma'=-\frac{\varepsilon-1}{\varepsilon}\sigma. \tag{1}
> $$
>
> ![[belpho-1995-final-theory-solutions-p6-c7762.png]]
>
> Эту формулу легко получить, если учесть, что суммарное электрическое поле, создаваемое зарядами на обкладках и поляризационными зарядами, в $\varepsilon$ раз меньше поля, создаваемого только свободными зарядами на обкладках, иными словами $(\sigma+\sigma')=\sigma/\varepsilon$.
>
> Тогда сила, действующая на единицу площади диэлектрика:
>
> $$
> P=\left(\frac{\sigma}{\varepsilon_0}+\frac{\sigma'}{2\varepsilon_0}\right)\sigma'=\frac{\varepsilon^2-1}{2\varepsilon^2\varepsilon_0}\sigma^2. \tag{2}
> $$
>
> Если предел прочности материала диэлектрика $P_\text{пр.}$, то он будет разорван кулоновскими силами при поверхностной плотности:
>
> $$
> \sigma=\sqrt{\frac{2\varepsilon^2\varepsilon_0}{\varepsilon^2-1}P_\text{пр}}. \tag{3}
> $$
>
> Тогда искомое напряжение:
>
> $$
> U=\frac{\sigma}{\varepsilon_0}\left(D-d+\frac{d}{\varepsilon}\right)
> =\frac{D-\frac{\varepsilon-1}{\varepsilon}d}{\varepsilon_0}\sqrt{\frac{2\varepsilon^2\varepsilon_0}{\varepsilon^2-1}P_\text{пр}}
> =(D\varepsilon-(\varepsilon-1)d)\sqrt{\frac{2P_\text{пр}}{\varepsilon_0(\varepsilon^2-1)}}.
> $$
