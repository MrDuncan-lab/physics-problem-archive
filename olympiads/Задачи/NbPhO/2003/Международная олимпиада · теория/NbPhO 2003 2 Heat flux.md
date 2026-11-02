---
id: nbpho-2003-intl-theory-2
olympiad: NbPhO
year: 2003
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "2"
title: "Heat flux"
points: 4
aliases: ["Heat flux"]
topics: ["[[2.5 Первое начало термодинамики]]"]
difficulty: 3
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Определить тепловой поток через пластину и проволоку с переменным тепловым сопротивлением."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 2. Heat flux (4 points)

**NbPhO 2003** · Международная олимпиада · теория · 10–12 класс · задача 2  
Источник: [[_pdf/NbPhO/nbpho-2003.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2003.pdf#page=3|решение, стр. 3]]

Темы: [[2.5 Первое начало термодинамики]]

> [!abstract] Кратко (составлено моделью)
> Определить тепловой поток через пластину и проволоку с переменным тепловым сопротивлением.

Heat resistivity is equal to the ratio of the temperature difference between the end-points of a wire of unit cross-section and unit length, and the heat flux (unit: W) through this wire.

**1)** Microprocessor of power $P=90\,\mathrm W$ has a water-cooling system. The chip and flowing water are separated by a copper plate of thickness $d=5\,\mathrm{mm}$ and cross-section area $s=100\,\mathrm{mm^2}$. What is the temperature difference between the processor and water? The copper heat resistivity is $\rho=2{,}6\,\mathrm{mm\cdot K/W}$.

**2)** A wire is made of different alloys, its heat resistivity $\rho$ as a function of the coordinate along the wire is given in the attached graph. The cross-section area of the wire is $S=1\,\mathrm{mm^2}$, its length $l=4\,\mathrm{cm}$. Find the heat flux through the wire, if one end of the wire is kept at the temperature $100^\circ\mathrm C$, and the other end — at $0^\circ\mathrm C$.

![[nbpho-2003-p1-c2621.png]]

> [!answer]- Ответ
> **1** — $\Delta T=P\rho d/s\approx12\,\mathrm K$.
>
> **2** — $P\approx20\,\mathrm{mW}$.

> [!solution]- Решение
> # 2. Heat flux (4 pts)
>
> **1)** The heat flux $P=\Delta Ts/\rho d$, hence
> $\Delta T=P\rho d/s\approx12\,\mathrm K$.
>
> **2)** By a constant heat flux $P$, the temperature change along the wire $\Delta T=P\rho\Delta x/S$, where $\Delta x$ is a displacement along the wire. Hence the temperature drop $t_1-t_2=P\mathcal S/S$, where $\mathcal S$ is the surface under the graph. Thus, $P=(t_1-t_2)S/\mathcal S$. Using the graph we find $\mathcal S\approx50\,\mathrm{Kcm^2/W}$ and
> $P\approx20\,\mathrm{mW}$.
