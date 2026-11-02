---
id: nbpho-2003-intl-theory-4
olympiad: NbPhO
year: 2003
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "4"
title: "Tunnel diode"
points: 8
aliases: ["Tunnel diode"]
topics: ["[[5.5 Нелинейные элементы в электрических цепях]]"]
difficulty: 3
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "По вольт-амперной характеристике туннельного диода определить ток и выходной сигнал усилителя."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 4. Tunnel diode (8 points)

**NbPhO 2003** · Международная олимпиада · теория · 10–12 класс · задача 4  
Источник: [[_pdf/NbPhO/nbpho-2003.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2003.pdf#page=3|решение, стр. 3]]

Темы: [[5.5 Нелинейные элементы в электрических цепях]]

> [!abstract] Кратко (составлено моделью)
> По вольт-амперной характеристике туннельного диода определить ток и выходной сигнал усилителя.

Tunnel diode is a semi-conductor device, similar to the ordinary diode, the volt-amper characteristic of which is given in the attached graph. The circuit below describes a simple amplifier. The resistance $R=10\,\Omega$, battery voltage $\mathcal E=0{,}25\,\mathrm V$.

![[nbpho-2003-p1-f1.svg]]

**1)** Find the current in the circuit, if $U_{in}+\mathcal E=0{,}08\,\mathrm V$.

**2)** Find the output voltage $U_{out\,0}$ if $U_{in}=0\,\mathrm V$.

**3)** Find the output signal $U_{out}-U_{out\,0}$ if $U_{in}=1\,\mathrm{mV}$.

**4)** The input signal is given in the graph below. Sketch the output signal as a function of time.

![[nbpho-2003-p1-c5055.png]]

> [!answer]- Ответ
> **1** — $I=(U_{in}+\mathcal E)/(R+R_D)\approx4.5\,\mathrm{mA}$.
>
> **2** — $IR=60\,\mathrm{mV}$ (see the graph).
>
> **3** — 1.7 mV, and …

> [!solution]- Решение
> # 4. Tunnel diode (8 pts)
>
> **1)** For voltages below 0.08V, the graph is almost a straight line corresponding to a constant resistance $R_D=0.05\,\mathrm V/6.5\,\mathrm{mA}\approx7.7\,\Omega$. Hence
> $I=(U_{in}+\mathcal E)/(R+R_D)\approx4.5\,\mathrm{mA}$.
>
> **2)** The output voltage can be found graphically: the diode voltage $U(I)=\mathcal E-IR$, hence, the intersection point of the graph and the straight line $U=\mathcal E-IR$, gives us the diode current 6 mA; then, the output voltage
> $IR=60\,\mathrm{mV}$ (see the graph).
>
> ![[nbpho-2003-p3-f1.svg]]
>
> **3)** One millivolt input shifts the line intersecting the graph a little-bit sideward, but the shift is so small that the graph can be approximated by a straight line. The cotangent of the slope of that line gives us the differential resistance of the diode, $R_d=-16\,\Omega$. Then, a small change in the input voltage $\Delta U$ will lead to a current change $\Delta I$ given by the relationship $(R+R_d)\Delta I=\Delta U$; hence, $\Delta I=\Delta U/(R_d+R)$. The output voltage change $\Delta U_{out}=IR=R\Delta U/(R_d+R)$, and the amplification factor $\Delta U_{out}/\Delta U=R/(R_d+R)\approx1.7$. Consequently, the output voltage is
> 1.7 mV, and …
>
> **4)** the output graph is exactly the same as the input graph, except that it is vertically stretched by a factor of -1.7.
