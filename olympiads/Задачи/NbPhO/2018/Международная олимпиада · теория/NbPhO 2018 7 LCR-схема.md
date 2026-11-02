---
id: nbpho-2018-intl-theory-7
olympiad: NbPhO
year: 2018
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "7"
title: "LCR-схема"
points: 5
authors: ["Jaan Kalda"]
aliases: ["LCR-схема"]
topics: ["[[5.3 Электромагнитные колебания. RLC-цепи]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Построить фазовую диаграмму LCR-схемы и найти входное напряжение по межузловым напряжениям."
status: "проверено: сверка, два чтения совпали"
lang: ru
tags: [задача]
---

# 7. LCR-схема (5 б) — Jaan Kalda.

**NbPhO 2018** · Международная олимпиада · теория · 10–12 класс · задача 7  
Источник: [[_pdf/NbPhO/nbpho-2018.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2018.pdf#page=8|решение, стр. 8–9]]

Темы: [[5.3 Электромагнитные колебания. RLC-цепи]]

> [!abstract] Кратко (составлено моделью)
> Построить фазовую диаграмму LCR-схемы и найти входное напряжение по межузловым напряжениям.

Рассмотрим электрическую схему показанную на рисунке.

![[nbpho-2018-p2-f1.svg]]

**i)** (2 б) Начертите фазовую диаграмму для этой схемы показывающую векторы напряжения между следующими узлами: $V_{AD}$, $V_{DB}$, $V_{AB}$, $V_{AE}$, $V_{EB}$, $V_{AF}$ и $V_{FB}$.

**ii)** (3 б) Напряжения между узлами $D$, $E$ и $F$ имеют следующие значения: $V_{DE}=7\,\mathrm V$, $V_{DF}=15\,\mathrm V$ и $V_{EF}=20\,\mathrm V$; каково значение напряжения на входящих клеммах $V_0$?

> [!answer]- Ответ
> **7** — With $a=7\mathrm V$, $b=15\mathrm V$ and $c=20\mathrm V$ we obtain $p=21\mathrm V$ and $V_{AB}=2R=25\mathrm V$.

> [!solution]- Решение
> # 7. LCR-CIRCUIT
>
> **i)** Let us consider first the upper branch of the circuit consisting of the capacitor $C$ and resistor $R_2$. There is the same current $I_1$ through the both elements so that the complex voltage amplitudes are $I_1/(i\omega C)$ and $I_1R_2$, respectively. Division by imaginary unit rotates a vector in complex plane clock-wise by $\pi/2$, hence the voltage vector on resistor is rotated with respect to the voltage on the capacitor counter-clock-wise by $\pi/2$. Similar analysis leads us to the conclusion that the voltage on the inductor $L_1$ is rotated with respect to the voltage on the resistor $R_0$ counter-clock-wise by $\pi/2$, and that the voltage on the resistor $R_1$ is rotated with respect to the voltage on the inductor $L_0$ clock-wise by $\pi/2$. The resulting phasor diagram is shown below.
>
> ![[nbpho-2018-p8-f1.svg]]
>
> **ii)** From Thales theorem we can conclude that the points $F$, $D$, and $E$ in the figure above lay on the circle drawn around the segment $AB$ as a diameter. Hence, the voltage $V_{AB}$ which we want to know equals by modulus to the diameter $AB$ of the circumcircle of the triangle $FDE$ for which we know the side lengths. By making use of the two formulas for the surface area of a triangle, the Heron formula $A=\sqrt{p(p-a)(p-b)(p-c)}$, with $p=\frac12(a+b+c)$, and $A=\frac{abc}{4R}$ with $R$ denoting the radius of the circumcircle, we conclude that the diameter of the circumcircle
>
> $$2R=\frac{abc}{2\sqrt{p(p-a)(p-b)(p-c)}}.$$
>
> With $a=7\mathrm V$, $b=15\mathrm V$ and $c=20\mathrm V$ we obtain $p=21\mathrm V$ and $V_{AB}=2R=25\mathrm V$.
