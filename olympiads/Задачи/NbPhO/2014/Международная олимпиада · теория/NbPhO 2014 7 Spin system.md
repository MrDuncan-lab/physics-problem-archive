---
id: nbpho-2014-intl-theory-7
olympiad: NbPhO
year: 2014
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "7"
title: "Spin system"
points: 8
aliases: ["Spin system"]
topics: ["[[2.12 Молекулярно-кинетическая теория]]", "[[2.4 Теплоёмкость процесса]]", "[[4 Магнетизм]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Найти вероятности, среднюю энергию и теплоёмкость системы магнитных диполей при высокой температуре."
status: "проверено: сверка, два чтения + арбитр"
lang: en
tags: [задача]
---

# 7. SPIN SYSTEM (8 points)

**NbPhO 2014** · Международная олимпиада · теория · 10–12 класс · задача 7  
Источник: [[_pdf/NbPhO/nbpho-2014.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2014.pdf#page=4|решение, стр. 4]]

Темы: [[2.12 Молекулярно-кинетическая теория]], [[2.4 Теплоёмкость процесса]], [[4 Магнетизм]]

> [!abstract] Кратко (составлено моделью)
> Найти вероятности, среднюю энергию и теплоёмкость системы магнитных диполей при высокой температуре.

Let us consider a system of $N$ independent magnetic dipoles (spins) in a magnetic field $B$ and temperature $T$. Our goal is to determine some properties of this system by using statistical physics. It is known that the energy of a single spin is $E=\varepsilon m$, where $m=\pm\frac{1}{2}$ and $\varepsilon=\alpha B$.

**i)** (2 points) What is the probability $p_\uparrow$ for a spin to be in excited state, i.e. have positive energy?

**ii)** (2 points) What is the average value of the total energy $E_s$ of the spin system as a function of $B$ and $T$?

**iii)** (2 points) Using high temperature approximation $T\gg\frac{\alpha Bm}{k}$, simplify the expression of $E_s$.

**iv)** (2 points) Using high temperature approximation $T\gg\frac{\alpha Bm}{k}$, find the heat capacity $C$ of the spin system.

> [!answer]- Ответ
> **7.1**
>
> $$
> p_\uparrow=\frac{e^{-\epsilon/2kT}}{e^{-\epsilon/2kT}+e^{\epsilon/2kT}}.
> $$
>
> **7.2**
>
> $$
> E=\frac{N\epsilon}{2}\frac{e^{-\epsilon/2kT}-e^{\epsilon/2kT}}{e^{-\epsilon/2kT}+e^{\epsilon/2kT}}=-\frac{N\epsilon}{2}\tanh(\epsilon/2kT).
> $$
>
> **7.3** — $E\approx-N\epsilon^2/4kT$.
>
> **7.4** — $C=\frac{dE}{dT}=N\epsilon^2/4kT^2$.

> [!solution]- Решение
> # 7. Spin system
>
> **1)** According to Boltzmann’s distribution, $p_\uparrow=A\cdot e^{-\epsilon m}$, where the constant $A$ can be found from the condition that the probability of having either up or down orientation is one: $A\cdot e^{-\epsilon/2}+A\cdot e^{\epsilon/2}=1$, hence
>
> $$A=\frac{1}{e^{-\epsilon/2kT}+e^{\epsilon/2kT}}=\frac{1}{2\cosh(\epsilon/2kT)}.$$
>
> Thus,
>
> $$p_\uparrow=\frac{e^{-\epsilon/2kT}}{e^{-\epsilon/2kT}+e^{\epsilon/2kT}}.$$
>
> **2)** The average energy is the weighted average of up- and down-state energies for a single spin, multiplied by the number of spins:
>
> $$E=\frac{N\epsilon}{2}\frac{e^{-\epsilon/2kT}-e^{\epsilon/2kT}}{e^{-\epsilon/2kT}+e^{\epsilon/2kT}}=-\frac{N\epsilon}{2}\tanh(\epsilon/2kT).$$
>
> **3)** For small values of the argument of the hyperbolic tangent, the last expression can be approximated as
> $E\approx-N\epsilon^2/4kT$.
>
> **4)** According to the definition of the heat capacity,
> $C=\frac{dE}{dT}=N\epsilon^2/4kT^2$.
