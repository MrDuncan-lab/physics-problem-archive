---
id: nbpho-2009-intl-theory-e1
olympiad: NbPhO
year: 2009
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "E1"
title: "Black box"
points: 9
aliases: ["Black box"]
topics: ["[[7 Эксперименты]]", "[[5 Цепи]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Определить сопротивления в электрическом чёрном ящике по измерениям напряжения."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 4. Black box (9 points)

**NbPhO 2009** · Международная олимпиада · теория · 10–12 класс · задача E1  
Источник: [[_pdf/NbPhO/nbpho-2009.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2009.pdf#page=3|решение, стр. 3]]

Темы: [[7 Эксперименты]], [[5 Цепи]]

> [!abstract] Кратко (составлено моделью)
> Определить сопротивления в электрическом чёрном ящике по измерениям напряжения.

*Equipment:* electrical black box with three outlets, battery, voltmeter.

It is known that inside the black box, there are three resistors (connected with wires in an unknown manner), the smallest of which is $R_1=100\,\Omega$. Find the value of the largest resistor $R_3$. What can be said about the middle-valued resistor $R_2$? Estimate the uncertainties of your results.

> [!answer]- Ответ
> the largest resistance is $470\,\Omega$, and
>
> the middle-valued resistance is either $330\,\Omega$ or $140\,\Omega$.

> [!solution]- Решение
> # 4. Black box (9 points)
>
> Independently of whether there is a triangular or a star connection, one can measure the ratio of the resistances a pair of resistors by connecting the battery to two outlets — let these be the outlets 1 and 3, and measuring the voltages between the outlets 1 and 2, and between the outlets 2 and 3. For a star connection,
> $$\frac{R_3}{R_1}=\frac{V_{23}}{V_{12}},$$
> where $R_i$ denotes the resistor closest to the $i$-th outlet; for a triangular connection,
> $$\frac{R_3}{R_1}=\frac{V_{12}}{V_{23}},$$
> where $R_i$ denotes the resistor farthest away from the $i$-th outlet; for a triangular connection,
>
> In such a way we find
> $$\frac{R_3}{R_1}\approx4{,}7,\quad\frac{R_3}{R_2}\approx3{,}3,\text{ and }\frac{R_2}{R_1}\approx1{,}4,$$
> implying $R_1=100\,\Omega$, $R_2=140\,\Omega$ and $R_3=470\,\Omega$; or
> $$\frac{R_1}{R_3}\approx4{,}7,\quad\frac{R_2}{R_3}\approx3{,}3,\text{ and }\frac{R_1}{R_2}\approx1{,}4,$$
> $R_3=100\,\Omega$, $R_2=330\,\Omega$ and $R_1=470\,\Omega$. So, we can conclude that
> the largest resistance is $470\,\Omega$, and
> the middle-valued resistance is either $330\,\Omega$ or $140\,\Omega$.
