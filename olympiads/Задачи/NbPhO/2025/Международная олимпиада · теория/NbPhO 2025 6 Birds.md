---
id: nbpho-2025-intl-theory-6
olympiad: NbPhO
year: 2025
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "6"
title: "Birds"
points: 4
authors: ["Jaan Kalda"]
aliases: ["Birds"]
topics: ["[[1.18 Гидростатика]]", "[[1.10 Статика]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: true
source_damaged: false
summary: "Найти максимальное число птиц, удерживаемых плавающей балкой, по её наклону под одной птицей."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 6. Birds (4 points) — Jaan Kalda.

**NbPhO 2025** · Международная олимпиада · теория · 10–12 класс · задача 6  
Источник: [[_pdf/NbPhO/nbpho-2025.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2025.pdf#page=8|решение, стр. 8]]

Темы: [[1.18 Гидростатика]], [[1.10 Статика]]

> [!abstract] Кратко (составлено моделью)
> Найти максимальное число птиц, удерживаемых плавающей балкой, по её наклону под одной птицей.

A long and thin homogenous beam with uniform thickness and square cross-section floats horizontally in water with its top surface parallel to the water surface. A bird lands on one end of the beam, and as a result, the beam sinks so that the edge of the upper face on the bird’s side is exactly at the same height as the water surface, while at the other end of the beam the lower face does not rise above the water. What is the maximum number of such birds that this beam can hold above water?

> [!answer]- Ответ
> This means that additionally, the beam can support up to 3 more birds, i.e. 4 birds in total.

> [!solution]- Решение
> # 6. Birds (4 points) — Solution by Jaan Kalda.
>
> Let us consider the torque balance with respect to the beam’s centre of mass. Note that as the beam is long and thin and the other end of the beam doesn’t rise above the water, the beam will stay approximately horizontal, which we will use to calculate the moment arms. First, the beam’s weight acts at its centre of mass, creating zero torque. The second contribution comes from the buoyancy force that can be split into two components: the upward buoyancy force as if the entire beam were submerged (acts at the centre of mass, creating zero torque), and the downward ”missing” buoyancy force of the triangular section above water (creates a torque). This missing buoyancy force $F$ is what becomes a real buoyancy force once additional birds land and press the beam fully underwater; if the length of the beam is $L$ then the arm of this force is the distance from the centre of mass of the beam to the centre of mass of the triangle which is at the intersection point of medians, which are a distance $\frac23L$ away from the bird. Thus the moment arm of $F$ is $(\frac23-\frac12)L = \frac16L$. The arm of the bird’s weight $mg$ is $\frac12L$, hence $\frac12L\cdot mg = \frac16L\cdot F$, i.e. $F = 3mg$.
>
> This means that additionally, the beam can support up to 3 more birds, i.e. 4 birds in total.
>
> **Note:** according the official solution, the answer does not depend on how much of the beam is left in the water nor on any other unknown properties of the beam. As such, fixing any of these parameters does not create a maximum condition.

> [!grading]- Критерии оценивания
> Grading (preliminary)
>
> | Criterion | Points |
> |---|---|
> | Used any correct torque balance | 0.6 pts |
> | – Used any correct force balance with the bird present | 0.3 pts |
> | Moment arm for the force of the bird | 0.2 pts |
> | Explicitly stated or derived the center of mass of a triangle | 0.6 pts |
> | Moment arm for the buoyancy force | 0.3 pts |
> | Justified numerical answer (4) | 0.3 pts |
> | A final solution that does not depend on fixing any unknown parameters | 2 pts |
