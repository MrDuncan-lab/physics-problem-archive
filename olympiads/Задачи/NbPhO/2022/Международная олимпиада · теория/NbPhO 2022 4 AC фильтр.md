---
id: nbpho-2022-intl-theory-4
olympiad: NbPhO
year: 2022
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "4"
title: "AC фильтр"
points: 5
authors: ["Jaan Kalda"]
aliases: ["AC фильтр"]
topics: ["[[5.3 Электромагнитные колебания. RLC-цепи]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: true
source_damaged: false
summary: "Определить резонансную частоту и максимальный фазовый сдвиг в фильтре переменного тока."
status: "проверено: сверка"
lang: ru
tags: [задача]
---

# 4. AC фильтр (5 p) — Jaan Kalda.

**NbPhO 2022** · Международная олимпиада · теория · 10–12 класс · задача 4  
Источник: [[_pdf/NbPhO/nbpho-2022.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2022.pdf#page=7|решение, стр. 7]]

Темы: [[5.3 Электромагнитные колебания. RLC-цепи]]

> [!abstract] Кратко (составлено моделью)
> Определить резонансную частоту и максимальный фазовый сдвиг в фильтре переменного тока.

Переменное напряжение амплитуды $V_0$ и угловой скорости $\omega_0$ приложено в схеме, показанной ниже.

**i)** (2 p) Для какой угловой скорости $\omega_0$ напряжение на выходе было бы бесконечным?

**ii)** (3 p) Теперь пусть угловая скорость $\omega$ будет в два раза больше найденной в предыдущей части, $\omega = 2\omega_0$. Ёмкость $C_1$ выбрана так, что разность фаз $\varphi$ между напряжением на выходе и на входе максимальная (параметры $C_0$, $L$ и $R$ не меняют). Найдите сдвиг фазы $\varphi$ и напряжение на выходе $V_\mathrm{out}$.

![[nbpho-2022-p1-f1.svg]]

> [!answer]- Ответ
> **i** — hence $\omega_0=1/\sqrt{LC_0}$.
>
> **ii**
>
> $$
> \varphi=\arcsin\frac{V_0/2}{V_L-V_0/2}=\frac35,
> $$
>
> **ii**
>
> $$
> V_{\text{out}}=\frac{V_0/2}{\tan\varphi}=\frac23V_0.
> $$

> [!solution]- Решение
> # 4. AC filter (5 points) — Solution by Jaan Kalda.
>
> **i)** (2 points) The output voltage $V_{\text{out}}$ is the difference of the voltages on the capacitors. Hence, for $V_{\text{out}}$ to become infinite, one of the currents must become infinite. This is possible only if the impedance of the lower branch becomes zero:
>
> $$\frac{1}{i\omega_0C_0}+i\omega_0L=0,$$
>
> hence $\omega_0=1/\sqrt{LC_0}$.
>
> **ii)** (3 points) Let us draw a phasor for this circuit. As compared with $\omega=\omega_0$, the ratio of the impedances on the inductor and on a capacitor is increased four-fold. For the lower branch, these two impedances were equal previously, hence now the impedance of the inductor is four times bigger than the impedance of the capacitor; the same applies to the corresponding voltages: $V_L=4V_{C0}$. The two voltage vectors are antiparallel and must add up to the input voltage $V_0$, hence $V_L-V_{C0}=V_0$, hence $V_{C0}=V_0/3$ and $V_L=\frac43V_0$. The voltage vectors on $C_1$ and $R$ are perpendicular to each other and must add up also to the input voltage $V_0$, hence these three voltage vectors form a right triangle. According to the Thales theorem, the right angle must lie on a circle, with the input voltage being a diameter of this circle. This is depicted in the figure below where the voltage vectors are color-coded as follows: output — black; capacitor $C_1$ — cyan; capacitor $C_0$ — blue; inductor — red; resistor — green. Radius of the circle is shown in purple.
>
> ![[nbpho-2022-p7-f1.svg]]
>
> From this figure, it becomes obvious that the phase shift $\varphi$ is maximal when the output voltage vector is tangent to the circle, hence
>
> $$\varphi=\arcsin\frac{V_0/2}{V_L-V_0/2}=\frac35,$$
>
> and
>
> $$V_{\text{out}}=\frac{V_0/2}{\tan\varphi}=\frac23V_0.$$
>
> Alternatively, the problem can be solved using the standard impedance-based approach, but this will be mathematically significantly more technical.

> [!grading]- Критерии оценивания
> **Grading:** Concluding that the impedance of the lower branch must be zero: 0.8 pts; expressing this impedance: 1 pt; finding the final answer: 0.2 pts.
>
> **ii)**
>
> **Grading:** Concluding that $V_{C0}=V_0/3$ and $V_L=\frac43V_0$: 0.5 pts; concluding that the potential of the upper output node draws a circle (applying the Thales theorem): 1 pt; noting that phase shift is maximal when the output voltage vector is tangent to the circle: 1 pt; finding the phase shift: 0.2 pts; finding $V_{\text{out}}$: 0.3 pts.
