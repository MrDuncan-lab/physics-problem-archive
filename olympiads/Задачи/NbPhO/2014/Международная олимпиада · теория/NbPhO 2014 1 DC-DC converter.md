---
id: nbpho-2014-intl-theory-1
olympiad: NbPhO
year: 2014
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "1"
title: "DC-DC converter"
points: 8
aliases: ["DC-DC converter"]
topics: ["[[5.2 RL-цепи]]", "[[5.3 Электромагнитные колебания. RLC-цепи]]", "[[5.5 Нелинейные элементы в электрических цепях]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: true
summary: "Исследовать ток, напряжение и потери в импульсном преобразователе с катушкой, диодом и конденсатором."
status: "проверено: сверка, два чтения + арбитр"
lang: en
tags: [задача]
---

# 1. DC-DC CONVERTER (8 points)

**NbPhO 2014** · Международная олимпиада · теория · 10–12 класс · задача 1  
Источник: [[_pdf/NbPhO/nbpho-2014.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2014.pdf#page=3|решение, стр. 3]]

Темы: [[5.2 RL-цепи]], [[5.3 Электромагнитные колебания. RLC-цепи]], [[5.5 Нелинейные элементы в электрических цепях]]

> [!abstract] Кратко (составлено моделью)
> Исследовать ток, напряжение и потери в импульсном преобразователе с катушкой, диодом и конденсатором.

> [!warning] Часть текста утрачена в исходном PDF
> - подписи осей на графике отображаются повреждёнными символами

In order to obtain high voltage supply using a battery, the following circuit is used.

![[nbpho-2014-p1-f1.svg]]

An electromagnetic switch $K_1$ connects a battery of electromotive force $\mathcal{E}$ to an inductor of inductance $L$: it is closed if there is no current in the inductor (a spring keeps it closed), but if the inductor current reaches a critical value $I_0$, magnetic field created by the inductor pulls it open. Due to inertia, once the key is open, it takes a certain time $\tau_K$ to close again even if the current falls to zero.

For the diode $D$ you may assume that its current is zero for any reverse voltage ($V_D<0$), and also for any forward voltage smaller than the opening voltage $V_0$ (i.e. for $0<V_D<V_0$). For any non-zero forward current, the diode voltage $V_D$ remains equal to $V_0$.

You may express your answers in terms of $L$, $\mathcal{E}$, $I_0$, $V_0$, and the capacitance $C$ (see figure).

**i)** (1 point) At first, let the key $K_2$ be open. If the initial inductor current is zero, how long time $\tau_L$ will it take to open the key $K_1$?

**ii)** (1 point) Assuming (here and in what follows) that $L/R\ll\tau_K\ll\tau_L$, plot the inductor current as a function of time $t$ (for $0\leq t<3\tau_L$).

**iii)** (1 point) What is the maximal voltage $V_\mathrm{max}$ on the resistor $R$?

**iv)** (2 points) Assuming that $V_\mathrm{max}\gg V_0$, what is the average power dissipation on the diode?

**v)** (2 points) Now, let the key $K_2$ be closed, and let us assume simplifyingly that $V_0=0$; also, $RC\gg\tau_L$ and $\tau_K>\pi\sqrt{LC}$. Suppose that the circuit has been operated for a very long time. Find the average voltage on the resistor.

**vi)** (1 point) Find the amplitude of voltage variations on the resistor.

> [!answer]- Ответ
> **1.1**
>
> $$
> \tau_L=LI_0/\mathcal E.
> $$
>
> **1.3** — $V_\mathrm{max}=RI_0$.
>
> **1.4**
>
> $$
> P=\frac{A}{\tau_L}=\frac{V_0I_0L}{R\tau_L}=\frac{V_0\mathcal E}{R}.
> $$
>
> **1.5**
>
> $$
> \frac{V_{av}^2\tau_L}{R}=\frac12 LI_0^2\Rightarrow V_{av}=I_0\sqrt{\frac{LR}{2\tau_L}}=\sqrt{\frac{\mathcal E I_0R}{2}}.
> $$
>
> **1.6**
>
> $$
> U_0=\frac{\Delta V}{2}=\frac{\tau_LV_{av}}{2RC}=\frac{I_0L}{2C}\sqrt{\frac{I_0}{2R\mathcal E}}.
> $$

> [!solution]- Решение
> # 1. DC-DC converter
>
> **1)** (1 pt) From the Kirchhoff’s voltage law for the loop consisting of $L$ and $\mathcal E$, $\mathcal E=L\frac{dI}{dt}$, hence $I=\mathcal E t/L$. From $I_0=\mathcal E\tau_L/L$ we obtain
>
> $$\tau_L=LI_0/\mathcal E.$$
>
> **2)** (1 pts) Once the current $I_0$ is reached, the key is opened; the current through $L$ cannot change instantaneously and therefore is forced to flow through the resistor $R$. Since the characteristic time of this current loop (consisting of $L$ and $R$) is very short ($L/R\ll\tau_K$), the current decays very fast and becomes essentially equal to zero while the key is still open. Now there is no current through the inductor, so that the key will close again and the process will start repeating from the beginning. As a result we’ll have a periodic graph as shown in figure.
>
> ![[nbpho-2014-p3a-c0435.png]]
>
> **3)** (1 pt) The voltage through the resistor is maximal when the current is maximal, which happens immediately after the switch is opened; the maximal current is $I_0$ so that
> $V_\mathrm{max}=RI_0$.
>
> **4)** (2 pts) Due to $V_\mathrm{max}\gg V_0$, we can neglect the effect of the diode; so we have the Kirchhoff’s voltage law $L\frac{dI}{dt}=RI=R\frac{dq}{dt}$ (here we expressed the current via the charge $q$ which flows through the resistor). Integration over a single cycle (when the inductor current drops from $I_0$ down to 0) yields $LI_0=R\Delta q$, hence the charge flown through the resistor (and through the diode) $\Delta q=I_0L/R$. During that cycle, the diode had a constant voltage $V_0$, so the electric field performed work $A=V_0\Delta q$ which was released as heat in the diode. So, the average power dissipation
>
> $$P=\frac{A}{\tau_L}=\frac{V_0I_0L}{R\tau_L}=\frac{V_0\mathcal E}{R}.$$
>
> **5)** (2 pts) Now, since the characteristic time of the $RC$-loop is very large, the capacitor maintains its charge (and voltage) during that period of time when the diode is closed. Once the key $K_1$ opens, the diode will open, and the capacitor is connected to the inductor so that a $LC$-loop is formed. That loop admits oscillations of period $T_{LC}=2\pi\sqrt{LC}$ and as the current to the resistor can be neglected (since $RC\gg T_{LC}$), we can neglect the presence of the resistor. During the time interval when the diode is open, we can also neglect the presence of the diode since $V_0\ll V_\mathrm{max}$. Hence, the current $i$ in the $LC$-loop changes in time sinusoidally, starting from $i=I_0$ and ending when $i=0$ (then the diode will close disconnecting the $LC$-loop). During that process, the magnetic energy of the inductor $\frac12 LI_0^2$ is converted into the electric field energy of the capacitor, which is later released as heat on the resistor. When the stationary regime is achieved, the energy lost by the capacitor during one period (of duration $\tau_L$) as the heat dissipation on the resistor $Q=V_{av}^2\tau_L/R$ must be equal to the energy received from the inductor; so,
>
> $$\frac{V_{av}^2\tau_L}{R}=\frac12 LI_0^2\Rightarrow V_{av}=I_0\sqrt{\frac{LR}{2\tau_L}}=\sqrt{\frac{\mathcal E I_0R}{2}}.$$
>
> **6)** (1 pt) The charge which flows away from the capacitor when the diode is closed can be found as $q_C=\tau_LV_{av}/R$ (owing to $RC\gg\tau_{LC}$, the relative change of the capacitor’s voltage is small). Hence, the voltage drop is found as $\Delta V=q_C/C=\tau_LV_{av}/(RC)$. The amplitude is half of the difference between the minimal and maximal values, so that the amplitude
>
> $$U_0=\frac{\Delta V}{2}=\frac{\tau_LV_{av}}{2RC}=\frac{I_0L}{2C}\sqrt{\frac{I_0}{2R\mathcal E}}.$$
