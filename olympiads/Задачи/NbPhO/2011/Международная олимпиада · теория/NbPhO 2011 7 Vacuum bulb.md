---
id: nbpho-2011-intl-theory-7
olympiad: NbPhO
year: 2011
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "7"
title: "Vacuum bulb"
points: 8
aliases: ["Vacuum bulb"]
topics: ["[[2.2 Уравнение состояния идеального газа]]", "[[2.3 Работа газа]]", "[[2.5 Первое начало термодинамики]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Определить число циклов, работу и температуру газа при откачке сосуда поршневым насосом."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 7. Vacuum bulb (8 points)

**NbPhO 2011** · Международная олимпиада · теория · 10–12 класс · задача 7  
Источник: [[_pdf/NbPhO/nbpho-2011.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2011.pdf#page=4|решение, стр. 4]]

Темы: [[2.2 Уравнение состояния идеального газа]], [[2.3 Работа газа]], [[2.5 Первое начало термодинамики]]

> [!abstract] Кратко (составлено моделью)
> Определить число циклов, работу и температуру газа при откачке сосуда поршневым насосом.

Let us study how a vacuum can be created inside a bulb by pumping. Let the volume of the bulb be $V$, and the pump consist in a piston moving inside a cylinder of volume $\alpha V$, where $\alpha\ll1$. The pumping cycle starts with piston being pulled up; when the pressure inside the cylinder becomes smaller than inside the bulb, a valve $V_A$ (connecting the cylinder and the bulb) opens and remains open as long as the piston moves up. When piston is released, it starts moving down, at that moment, the valve $V_A$ closes. As long as the valve $V_A$ is open, the pressures of the bulb and the cylinder can be considered as equal to each other. When the piston moves down, the pressure in the cylinder increases adiabatically until becoming equal to the outside pressure $p_0=10^5\,\mathrm{Pa}$; at that moment, another valve $V_B$ opens letting the gas out of the cylinder. When the piston reaches the bottommost position, there is no residual air left inside the cylinder. Now, the piston is ready for being lift up: the valve $V_B$ closes and $V_A$ opens, marking the beginning of the next pumping cycle. The air inside the bulb can be considered isothermal, with the temperature being equal to the surrounding temperature $T_0$. The adiabatic exponent of air $\gamma=c_p/c_V=1.4$.

**i)** (2 pts) How many pumping cycles $N$ needs to be done to reduce the pressure inside bulb from $p=p_0$ down to $p=\beta p_0$, where $\beta\ll1$?

**ii)** (2 pts) What is the net mechanical work done during such a pumping (covering all the $N$ cycles)?

**iii)** (2 pts) What is the temperature of the air released from the cylinder to the surroundings at the end of the pumping process (when the pressure inside the bulb has become equal to $\beta p_0$)?

**iv)** (2 pts) According to the above described pumping scheme, there is a considerable loss of mechanical work during the period when the piston is released and moves down. Such a loss can be avoided if there is another pump, which moves in an opposite phase: the force due to outside air pressure pushing the piston down can be transmitted to the other pump for lifting the piston up. What is the net mechanical work done when such a pumping scheme is used?

> [!answer]- Ответ
> **i**
>
> $$
> N=-\frac{\ln\beta}{\alpha}.
> $$
>
> **ii** — $A\approx Np_0V\alpha=p_0V|\ln\beta|$.
>
> **iii** — $T=T_0\beta^{\frac1\gamma-1}$.
>
> **iv** — $A=2p_0V$.

> [!solution]- Решение
> # 7. Vacuum bulb (8 points)
>
> **i)** Each pumping cycle reduces the number of molecules inside the bulb by a factor of $(1-\alpha)$; therefore, after $N$ cycles, the number of molecules (and hence, the pressure) by a factor of $\beta=(1-\alpha)^N\approx e^{-N\alpha}\Rightarrow$
>
> $$N=-\frac{\ln\beta}{\alpha}.$$
>
> **ii)** Majority of the pumping cycles are done when the pressure inside the bulb is negligible as compared to the outside pressure. During such a cycle, a work equal to $p_0V\alpha$ is done. Therefore,
> $A\approx Np_0V\alpha=p_0V|\ln\beta|$.
>
> **iii)** Due to adiabatic law, $pV^\gamma=\mathrm{Const}$; when combined with the gas law $pV\propto T$ we obtain $p^{\gamma-1}\propto T^\gamma$. During the last downwards motion of the piston, the pressure inside the cylinder is increased by a factor of $1/\beta$; thus,
> $T=T_0\beta^{\frac1\gamma-1}$.
>
> **iv)** According to the modified pumping scheme, the work/energy loss is only due to the release of the hot air. Note that if we had a cylinder of volume $V$, we could be able to create vacuum inside there using only one pumping motion, i.e. by performing work $A=p_0V$ and without any energy loss. Now, we perform an excess work, which is converted into internal energy of the released hot air, which needs to be calculated. Let $\xi=\frac p{p_0}$ be an intermediate rarefaction factor; then, we can apply the previous result to calculate the internal energy of released air, if its quantity is $d\nu$ moles: $dU=T_0(\xi^{\frac1\gamma-1}-1)c_V\,d\nu$. Let us note that the number of moles inside the bulb is $\nu=\frac{p_0\xi V}{RT_0}\Rightarrow d\nu=\frac{p_0V}{RT_0}d\xi$. So, $U=p_0V\frac{c_V}R\int_0^1(\xi^{\frac1\gamma-1}-1)d\xi=(\gamma-1)p_0V\frac{c_V}R$. Now, recall that $\gamma=c_p/c_V=1+\frac R{c_V}$, hence $\frac{c_V}R=\frac1{\gamma-1}$ and $U=p_0V$. This gives us the energy loss due to heating the released air; another $p_0V$ is required for loss-free creation of the vacuum. Hence, the total required work is
> $A=2p_0V$.
