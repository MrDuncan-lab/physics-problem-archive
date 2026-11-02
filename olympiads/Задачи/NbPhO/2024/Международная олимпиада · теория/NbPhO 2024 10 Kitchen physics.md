---
id: nbpho-2024-intl-theory-10
olympiad: NbPhO
year: 2024
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "10"
title: "Kitchen physics"
points: 12
authors: ["Eero Uustalu", "Jaan Kalda"]
aliases: ["Kitchen physics"]
topics: ["[[3.8 Сложный конденсатор]]", "[[5 Цепи]]", "[[7 Эксперименты]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: true
source_damaged: false
summary: "Измерить толщину алюминиевого покрытия по сопротивлению и диэлектрическую проницаемость плёнки по ёмкости."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 10. Kitchen physics (12 points) — Eero Uustalu, Jaan Kalda.

**NbPhO 2024** · Международная олимпиада · теория · 10–12 класс · задача 10  
Источник: [[_pdf/NbPhO/nbpho-2024.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2024.pdf#page=10|решение, стр. 10]]

Темы: [[3.8 Сложный конденсатор]], [[5 Цепи]], [[7 Эксперименты]]

> [!abstract] Кратко (составлено моделью)
> Измерить толщину алюминиевого покрытия по сопротивлению и диэлектрическую проницаемость плёнки по ёмкости.

Tools: aluminum foil laminated brown paper bag*; a kitchen sponge with abrasive green side (for removing the varnish from the aluminum surface of the aluminum laminated bag to achieve good electrical contact), two sheets of aluminum foil*, two sheets of cushioning foam*, a square-shaped piece of wooden laminated plate, a sheet of kitchen plastic wrap*, permanent marker, scissors, micrometer, ruler, multimeter with crocodile clips. You can ask for a replacement if items marked with a star become damaged. The resistivity of aluminum $\rho = 2.7 \times 10^{-8}\,\Omega\cdot\mathrm{m}$; permittivity of vacuum $\varepsilon_0 = 8.854 \times 10^{-12}\,\mathrm{F\,m^{-1}}$.

**i)** (6 points) Find the thickness of the aluminium foil coating of the brown paper bag.

**ii)** (6 points) Find the relative permittivity of the plastic wrap.

> [!answer]- Ответ
> **i**
>
> $$
> t=\frac{\rho l}{Rw}\approx6.3\,\mu\mathrm m.
> $$
>
> **ii**
>
> $$
> C=\frac{\varepsilon\varepsilon_0 S}{d}\quad\Longrightarrow\quad\varepsilon=\frac{Cd}{\varepsilon_0 S}\approx5
> $$

> [!solution]- Решение
> # 10. Kitchen physics (12 points) — Solution by Tudor Plopeanu, grading schemes by Eero Uustalu, Mihhail Olentšenko and Uku Andreas Reigo.
>
> **i)** (6 points) The multimeter given is not precise enough to measure the resistance of the aluminium foil coating as-is. To increase the resistance, we cut it in a long, thin band of approximately the same width. We also scrape the ends of the band (with a sponge) in order to improve the contact with the crocodile clips. We plug the multimeter into a circuit with the aluminium band, and measure the resistance $R=\frac{\rho l}{S}$, where $S$ is the cross-section area and $l$ is the length of our band. As $S$ is the product of thickness $t$ and the width $w$ of our band, we find
>
> $$t=\frac{\rho l}{Rw}\approx6.3\,\mu\mathrm m.$$
>
> Note: directly measuring the width of the aluminium foil (for example by folding it a few times first) would yield an inaccurate result due to the paper component of the material.
>
> **ii)** (6 points) First, we measure the thickness of our plastic wrap by folding it enough times to reach our equipment’s precision: $t\approx13.5\,\mu\mathrm m$.
>
> Then, we set the wrap between two aluminium foils, such that a measured surface $S$ of film is sandwiched between the aluminium foils (and, of course, the aluminium foils do not touch or, otherwise, a short-circuit is formed). Thus we have created a capacitor. Its design is imperfect, as there are air gaps in between the layers. In order to minimize the airgaps, we will physically press on the set-up using the wooden laminated plate (while adding some padding, for the pressure to be distributed closer to uniformly).
>
> All that is left is to connect the multimeter to the capacitor, by connecting each crocodile clip to a different aluminium foil. While the readings can be rather chaotic, we shall consider the highest value displayed on the multimeter, as it corresponds to the lowest amount of air inside the setup.
>
> $$C=\frac{\varepsilon\varepsilon_0 S}{d}\quad\Longrightarrow\quad\varepsilon=\frac{Cd}{\varepsilon_0 S}\approx5$$
>
> We repeat the experiment, perhaps also considering different surface areas for our capacitor.

> [!grading]- Критерии оценивания
> Grading: (preliminary)
>
> For the first part, solution through resistance is graded.
>
> | Criterion | Points |
> |---|---|
> | The idea that resistance of foil strip can be used to calculate thickness of the foil | 0.4 pts |
> | The idea (or implication by specifying length) that length has to be maximized to achieve reasonably precise multimeter measurements by cutting the material into long strips | 0.8 pts |
> | The idea (or implication by specifying width) that width has to be minimized to achieve reasonably precise multimeter measurements by cutting the material into thin strips | 0.8 pts |
> | Width is large enough to be cut by hand precisely and consistently: $w\ge8\,\mathrm{mm}$ | 1.3 pts |
> | $6\,\mathrm{mm}\le w<8\,\mathrm{mm}$ | 0.9 pts |
> | $3\,\mathrm{mm}\le w<6\,\mathrm{mm}$ | 0.5 pts |
> | Length is large enough to give sufficient resistance, bag height is not enough: $l\ge2\,\mathrm m$ | 1.0 pts |
> | $1.4\,\mathrm m\le l<2\,\mathrm m$ | 0.6 pts |
> | $0.8\,\mathrm m\le l<1.4\,\mathrm m$ | 0.3 pts |
> | $0.34\,\mathrm m\le l<0.8\,\mathrm m$ | 0.1 pts |
> | Correct formulae are used for resistance and cross-section area | 0.2 pts |
> | Correct thickness value $t$ is calculated: $5\,\mu\mathrm m\le t\le7.5\,\mu\mathrm m$ | 1.5 pts |
> | $4\,\mu\mathrm m\le t\le9\,\mu\mathrm m$ | 1.0 pts |
> | $3\,\mu\mathrm m\le t\le12\,\mu\mathrm m$ | 0.5 pts |
>
> If aluminium foil has not been properly cleaned (can be seen from too high resistance), points are halved and rounded up if need be.
>
> Through direct measurement, no correct value of aluminium foil thickness $t$ can be achieved due to paper layer, which makes $\approx90\%$ of the foil total thickness. No points are given, unless idea of separating the layers is proposed (0.4 pts); if folding of multiple layers is mentioned, additionally give (0.8 pts).
>
> For the second part, one solution can be graded.
>
> | Criterion | Points |
> |---|---|
> | Idea to use capacitor (it is not enough to simply mention capacitance) | 0.8 pts |
> | If no follow up ideas (why is the capacitor used) is provided, or described capacitor is inadequate for the task, give | 0.4 pts |
> | Idea to fold plastic wrap (at least 8 layers required for maximum points) | 0.6 pts |
> | Thickness of plastic wrap $t$ is measured correctly: $12\,\mu\mathrm m\le t\le15\,\mu\mathrm m$ | 0.6 pts |
> | $11\,\mu\mathrm m\le t\le17\,\mu\mathrm m$ | 0.3 pts |
> | Clean aluminium foil is used as plates of the capacitor | 0.4 pts |
> | If laminated foil is used and lamination is mentioned as a factor, give | 0.2 pts |
> | Idea that air between plates will decrease capacitance due to increased distanced between plates and decreased average permittivity | 0.6 pts |
> | The correct execution of pressure application to the capacitor to push out air bubbles and straighten out the material | 0.4 pts |
> | If done imperfectly, give | 0.2 pts |
> | If maximum surface area is desired and used (larger than wooden plate) and application of pressure is impossible, give | 0.4 pts |
> | Cushioning foam is used to equally distribute pressure and avoid damage to the materials | 0.8 pts |
> | If done imperfectly or placed between the capacitor plates, give | 0.4 pts |
> | Correct formulae are used | 0.3 pts |
> | Correct answer is given in case of clean foil: $4\le\varepsilon\le5.5$ | 1.5 pts |
> | $3\le\varepsilon\le6$ | 0.9 pts |
> | $2\le\varepsilon\le6.5$ | 0.3 pts |
> | In case if laminated foil is used: $2\le\varepsilon\le2.5$ | 1.0 pts |
> | $1.5\le\varepsilon\le3$ | 0.4 pts |
>
> Note: if answer is guessed or acquired from wrongful idea, no points are given.
