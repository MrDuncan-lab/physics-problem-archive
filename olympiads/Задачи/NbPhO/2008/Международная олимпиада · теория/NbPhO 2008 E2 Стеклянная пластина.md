---
id: nbpho-2008-intl-theory-e2
olympiad: NbPhO
year: 2008
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "E2"
title: "Стеклянная пластина"
points: 10
aliases: ["Стеклянная пластина"]
topics: ["[[7 Эксперименты]]", "[[6.5 Волновая оптика]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Измерить толщину стеклянной пластины с помощью лазера и оценить погрешность."
status: "проверено: сверка, два чтения + арбитр"
lang: ru
tags: [задача]
---

# 10. Стеклянная пластина (10 баллов)

**NbPhO 2008** · Международная олимпиада · теория · 10–12 класс · задача E2  
Источник: [[_pdf/NbPhO/nbpho-2008.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2008.pdf#page=4|решение, стр. 4]]

Темы: [[7 Эксперименты]], [[6.5 Волновая оптика]]

> [!abstract] Кратко (составлено моделью)
> Измерить толщину стеклянной пластины с помощью лазера и оценить погрешность.

*Оборудование:* лазер (длина волны $\lambda=650\,\text{нм}$), тонкая стеклянная пластина, линза, линейка. NB! Стеклянная пластина прикреплена к подставке; избегайте прикасания к стеклу (так как оно острое и может легко поломаться).

Найдите толщину стеклянной пластины и оцените погрешность. Нарисуйте схему своего опыта.

> [!answer]- Ответ
> $d=2L\lambda/a$. Numerically, the thickness was
>
> $d\approx0.20\,\mathrm{mm}$.

> [!solution]- Решение
> # 10. Glass plate (10 points)
>
> ![[nbpho-2008-p4b-c3406.png]]
>
> There are two possible setups. First, we consider the interference of the beams, reflected from the upper and lower surfaces of the glass plate, see Figure, upper drawing. Second, we direct the beam on the edge of the plate. As a result, on the screen, there will be almost the same diffraction pattern, as from a single slit (lower drawing in the Figure).
>
> ![[nbpho-2008-p4b-c7323.png]]
>
> In the first case, we need to calculate the optical path difference, see Figure. $\Delta l=2(n|CD|-|AB|)=2(nd/\cos\beta-d\sin\beta\sin\alpha)=2d(n/\cos\beta-\sin^2\alpha/n)$; we keep in mind that $\sin\beta=\sin\alpha/n$. We need to find such a change in $\alpha$, which gives rise to the change of $\Delta l$ by $\lambda$ (this corresponds to a transition from one diffraction minimum to another one): $\Delta\alpha\cdot\frac{d(\Delta l)}{d\alpha}=\lambda$. Then, we can relate the measured quantity, the distance between the minima on the screen $a=L\Delta\alpha$ (where $L$ is the path length $|AB|+|BC|$) to the plate thickness. $\frac{d(\Delta l)}{d\alpha}=2d(\sin\alpha/\cos^2\beta-\sin2\alpha/n)=2d\sin\alpha(\cos^{-2}\beta-2\cos\alpha/n)$. So, $L\lambda=2ad\sin\alpha(\cos^{-2}\beta-2\cos\alpha/n)$; hence,
> $d=L\lambda/2a\sin\alpha(\cos^{-2}\beta-2\cos\alpha/n)$. We can easily measure $\alpha$ and calculate $\beta$; for $n$, we can use typical value $n\approx1.4$, or use the Brewster angle $\alpha_B$ measurement to find $n=\tan\alpha_B$. For the precise measurement of $a$, we count several, e.g. 10, inter-minima intervals, and divide the distance between the farthest minima by 10.
>
> In the second case, the angular distance between the minima is given by $\Delta\alpha=2\lambda/d$, so that $a=2L\lambda/d$ and
> $d=2L\lambda/a$. Numerically, the thickness was
> $d\approx0.20\,\mathrm{mm}$.
