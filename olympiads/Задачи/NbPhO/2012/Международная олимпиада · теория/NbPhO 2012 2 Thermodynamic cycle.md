---
id: nbpho-2012-intl-theory-2
olympiad: NbPhO
year: 2012
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "2"
title: "Thermodynamic cycle"
points: 5
aliases: ["Thermodynamic cycle"]
topics: ["[[2.8 Тепловые двигатели]]", "[[2.5 Первое начало термодинамики]]"]
difficulty: 3
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Найти КПД газового цикла с изотермами, изохорами и регенерацией теплоты."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# Problem 2. Thermodynamic cycle (5 points)

**NbPhO 2012** · Международная олимпиада · теория · 10–12 класс · задача 2  
Источник: [[_pdf/NbPhO/nbpho-2012.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2012.pdf#page=3|решение, стр. 3]]

Темы: [[2.8 Тепловые двигатели]], [[2.5 Первое начало термодинамики]]

> [!abstract] Кратко (составлено моделью)
> Найти КПД газового цикла с изотермами, изохорами и регенерацией теплоты.

Calculate the thermal efficiency of an ideal-gas cycle consisting of two isotherms at temperatures $T_1$ and $T_2$, and two isochores joining them. (An isochore is a constant-volume process.) The engine is constructed so that the heat released during the cooling isochore is used for feeding the heating isochore.

> [!answer]- Ответ
> **2** — $(T_1-T_2)/T_1$.
>
> **2** — $\eta=\frac{Q_{12}(T_2)-Q_{12}(T_1)}{Q_{12}(T_2)}=\frac{T_2-T_1}{T_2}$.

> [!solution]- Решение
> # Problem 2. Thermodynamic cycle (5 points)
>
> ![[nbpho-2012-p3-f1.png]]
>
> It is possible to realise the described process as a reversible cycle between two reservoirs at $T_1$ and $T_2$ (in this case it is called the Stirling cycle). A thermodynamic process is reversible if and only if there is never any heat flux between regions having non-infinitesimally different temperatures. During either isotherm we may keep the system in contact with a reservoir. The isochores can be connected with a heat exchanger in such a way that the heat emitted at any specific temperature on one isochore is later reused at the same temperature on the other isochore. A corollary of Carnot’s theorem (which says that the Carnot cycle is the most efficient one possible between to reservoirs) is that any reversible cycle between two reservoirs has the same efficiency as Carnot’s. Assuming $T_1>T_2$, the efficiency is
> $(T_1-T_2)/T_1$.
>
> Alternatively: for an isotherm, $p\propto T/V$, therefore the work done during compression from $V_1$ to $V_2$ is $Q_{12}(T)=\int_{V_1}^{V_2}p\,dV\propto T\int_{V_1}^{V_2}\frac{dV}{V}=T\int_{V_1}^{V_2}d\ln V=T\ln\frac{V_2}{V_1}$. During isochores there is no displacement and thus no work done. The efficiency
> $\eta=\frac{Q_{12}(T_2)-Q_{12}(T_1)}{Q_{12}(T_2)}=\frac{T_2-T_1}{T_2}$.
