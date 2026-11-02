---
id: nbpho-2010-intl-theory-9
olympiad: NbPhO
year: 2010
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "9"
title: "Power supply"
points: 6
aliases: ["Power supply"]
topics: ["[[5.2 RL-цепи]]", "[[5.5 Нелинейные элементы в электрических цепях]]", "[[5.1 RC-цепи]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Рассчитать токи и выходное напряжение импульсного источника питания с катушкой и диодом."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 9. Power supply (6 points)

**NbPhO 2010** · Международная олимпиада · теория · 10–12 класс · задача 9  
Источник: [[_pdf/NbPhO/nbpho-2010.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2010.pdf#page=5|решение, стр. 5]]

Темы: [[5.2 RL-цепи]], [[5.5 Нелинейные элементы в электрических цепях]], [[5.1 RC-цепи]]

> [!abstract] Кратко (составлено моделью)
> Рассчитать токи и выходное напряжение импульсного источника питания с катушкой и диодом.

![[nbpho-2010-p2-f1.svg]]

**i)** (2 pt) Consider the circuit given in Fig (a), where the diode can be assumed to be ideal (i.e. having zero resistance for forward current and infinite resistance for reverse current. The key is switched on for a time $\tau_c$ and then switched off, again. The input and output voltages are during the whole process constant and equal to $U_i$ and $U_o$, respectively ($2U_i<U_o$). Plot the graphs of input and output currents as functions of time.

**ii)** (2 pt) Now, the key is switched on and off periodically; each time, the key is kept closed for time interval $\tau_c$ and open — also for $\tau_c$. Find the average output current.

![[nbpho-2010-p2-f2.svg]]

**iii)** (2 pt) Now, circuit (a) is substituted by circuit (b); the switch is switched on and off as in part ii. What will be the voltage on the load $R$, when a stationary working regime has been reached? You may assume that $\tau_c\ll RC$, i.e. the voltage variation on the load (and capacitor) is negligible during the whole period (i.e. the charge on the capacitor has no time to change significantly).

> [!answer]- Ответ
> **ii**
>
> $$
> J=I_{\max}\frac14\frac{U_i}{U_0-U_i}=\frac{\tau_c}{4L}\frac{U_i^2}{U_0-U_i}.
> $$
>
> **iii**
>
> $$
> U_o=\frac{U_i}{2}\left(1+\sqrt{1+\frac{\tau_cR}{L}}\right),
> $$
>
> **iii**
>
> $$
> U_0=2U_i,\quad\text{if }\tau_cR<8L.
> $$

> [!solution]- Решение
> # Problem 9. Power supply (6 points)
>
> ![[nbpho-2010-p5-f1.svg]]
>
> **i. (2 pts)** When the key is closed, there is no current through the diode, because it has reverse voltage applied. Meanwhile, the voltage applied to the inductance is $U_i=L\dot I$, hence $I=I_0+U_it/L$. Since there was initially no current, $I_0=0$, and $I=U_it/L$. So, the maximal current achieved is $I_{\max}=U_i\tau_c/L$. The current through an inductance cannot change instantaneously; so, when the key is opened, all the current is redirected to the diode. The diode receives a forward current, hence it has no voltage drop. Thus, the inductance obtains the voltage $L\dot I=U_i-U_o$, (which is smaller than $-U_i$). Hence, $I=I_0-(U_0-U_i)t/L$, where $I_0$ is such as to match the current $I_{\max}$ at the moment when the key is opened. Once the current reaches zero, the diode is closed and no further current flows in the system. These findings allow us to sketch the Figure above.
>
> **ii. (2 pts)** For the first cycle, we can use the result of the question i. We notice that at the beginning of the second cycle, the system is exactly at the same state as at the beginning of the first cycle. So, the process starts to behave periodically, see Fig.
>
> ![[nbpho-2010-p5-f3.svg]]
>
> The average output current $J$ is the surface area under one period of the graph, divided by the period length. So, $J=\frac12 I_{\max}\tau_1/(2\tau_c)$, where $\tau=\tau_c\frac{U_i}{U_0-U_i}$ is the length of a time segment when $I_o>0$. So,
>
> $$J=I_{\max}\frac14\frac{U_i}{U_0-U_i}=\frac{\tau_c}{4L}\frac{U_i^2}{U_0-U_i}.$$
>
> **iii. (2 pts)** Now, we can use the result of the question ii, because the situation is exactly the same as it was, except that the output voltage will establish itself according to the value of average current $J$. Note that average current to the capacitor is 0 (because its upper plate is isolated from the lower one), therefore, all the current $J$ goes to the resistor. (The capacitor works as a buffer, redistributing the strongly fluctuating current of the previous graph over time, so that the current to the resistor is almost constant.) So, the output voltage $U_o=JR$, where the expression for $J$ can be found from the answer of the question ii. It is convenient to designate $U_o/U_i=\kappa$. Then we have
> $$\kappa(\kappa-1)=\frac{\tau_cR}{4L}\Rightarrow 2\kappa=1\pm\sqrt{1+\frac{\tau_cR}{L}}.$$
> We need $\kappa\geq 2$, so the “−” sign can be excluded, and we arrive at
>
> $$U_o=\frac{U_i}{2}\left(1+\sqrt{1+\frac{\tau_cR}{L}}\right),$$
> which is valid as long as $\tau_cR\geq 8L$. If this inequality is not satisfied, the assumption $U_o\geq 2U_i$ will not be satisfied, so that the expression for $J$ will fail.
>
> If $U_o<2U_i$, the ascending branch of the $I_i(t)$-graph is steeper than the descending one. So, the sawtooth profile of that graph starts “climbing up”. The higher it goes, the larger will be $J$ and hence the larger will be $U_o$. In its turn, larger $U_o$ results in a steeper the descending branch of the $I_i(t)$ graph; the process continues until reaching a state when the ascending and descending branches are equally steep; this corresponds to $U_0=2U_i$. So,
>
> $$U_0=2U_i,\quad\text{if }\tau_cR<8L.$$
