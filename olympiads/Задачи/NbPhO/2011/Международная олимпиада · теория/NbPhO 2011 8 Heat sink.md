---
id: nbpho-2011-intl-theory-8
olympiad: NbPhO
year: 2011
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "8"
title: "Heat sink"
points: 6
aliases: ["Heat sink"]
topics: ["[[2.4 Теплоёмкость процесса]]", "[[2.5 Первое начало термодинамики]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "По температурным измерениям определить теплоёмкость радиатора и полученное им количество теплоты."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 8. Heat sink (6 points)

**NbPhO 2011** · Международная олимпиада · теория · 10–12 класс · задача 8  
Источник: [[_pdf/NbPhO/nbpho-2011.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2011.pdf#page=4|решение, стр. 4–5]]

Темы: [[2.4 Теплоёмкость процесса]], [[2.5 Первое начало термодинамики]]

> [!abstract] Кратко (составлено моделью)
> По температурным измерениям определить теплоёмкость радиатора и полученное им количество теплоты.

Consider a heat sink in the form of a copper plate of a constant thickness (much smaller than the diameter $d$ of the plate). An electronic component is fixed to the plate, and a temperature sensor is fixed to the plate at some distance from that component. You may assume that the heat flux (i.e. power per unit area) from the plate to the surrounding air is proportional to the difference of the plate temperature at the given point (the coefficient of proportionality is constant over the entire plate, including the site of the electronic component).

**i)** (2 pts) The electronic component has been dissipating energy with a constant power of $P=35\mathrm{W}$ for a long time, and the average plate temperature has stabilized at the value $T_0=49^\circ\mathrm{C}$. Now, the component is switched off, and the average plate temperature starts dropping; it takes $\tau=10\mathrm{s}$ to reach the value $T_1=48^\circ\mathrm{C}$. Determine the heat capacity $C$ (units $\mathrm{J}/^\circ\mathrm{C}$) of the plate. The capacities of the electronic component and the temperature sensor are negligible.

**ii)** (4 pts) Now, the electronic component has been switched off for a long time; at the moment $t=0$, a certain amount of heat $Q$ is dissipated at it during a very short time. In the Figure and Table, the temperature is given as a function of time, as recorded by the sensor. Determine the dissipated heat amount $Q$.

![[nbpho-2011-p2-f1.svg]]

| $t$ (s) | 0 | 20 | 30 | 100 | 200 | 300 |
| --- | --- | --- | --- | --- | --- | --- |
| $T$ ($^\circ$C) | 20.0 | 20.0 | 20.4 | 32.9 | 41.6 | 42.2 |
| $t$ (s) | 400 | 600 | 800 | 1000 | 1200 | 1400 |
| $T$ ($^\circ$C) | 39.9 | 33.4 | 27.9 | 24.4 | 22.3 | 21.2 |

> [!answer]- Ответ
> **ii** — $Q=CT_c\approx46700\,\mathrm{J}$.

> [!solution]- Решение
> # 8. Heat sink (6 points)
>
> **i)** When the average temperature is stable at $T_0$, all the power dissipated at the electronic component is eventually given to the air: the air is being heated with power $P$. As the heat flux depends linearly on the temperature difference between a point on the plate and the air, the average heat flux and therefore the net power dissipated into the air depends linearly on the average temperature of the plate. The average temperature determines the radiated power.
>
> Now consider the situation after the heating has ended. The average temperature is initially the same, so the radiated heat power is initially still $P$. By the definition of heat capacity, an infinitesimal heat amount given to the surroundings is $dQ=-C\,dT_\mathrm{avg}$ with the minus sign encoding the direction of the heat flow. Thus, at the first moment, $P=\frac{dQ}{dt}=-C\frac{dT_\mathrm{avg}}{dt}$. Assuming that during $\tau$ the average temperature depends approximately linearly on time (because $T_0-T_1=1^\circ\mathrm{C}$ is much less than the usual ambient temperature), $\frac{dT_\mathrm{avg}}{dt}\approx\frac{T_1-T_0}{\tau}$ and
> $C\approx\frac{P\tau}{T_0-T_1}=350\,\mathrm{J}/^\circ\mathrm{C}$. Actually the graph of $T_\mathrm{avg}(t)$ is slightly curved downwards (as it is an exponential eventually stabilizing at the ambient temperature) and initially somewhat steeper, so $C$ is a bit smaller.
>
> **ii)** The average temperature of the heat sink falls off exponentially, therefore, if the “tail” of the given graph turns out to be exponential, we can presume the “tail” depicts the situation where the sensor is sensing the average temperature and the initial “bump”
>
> in the temperature distribution has evened out. Extrapolating the exponential to $t=0$ we get the initial average temperature $T_{\mathrm{avg},0}$ (immediately after the $Q$ has been dissipated into the sink) and, by $Q=C(T_{\mathrm{avg},0}-T_\mathrm{amb})$, the heat $Q$. The ambient temperature $T_\mathrm{amb}$ can be read off from the beginning of the given graph where the sensor’s surroundings have not yet heated up. This is furthermore a check for the assumption $T_0-T_1\ll T_\mathrm{amb}$ made in the first part of the solution. From the table, $T_\mathrm{amb}=20.0^\circ\mathrm{C}$.
>
> Let us analyse the (yet hypothetical) exponential $T_\mathrm{avg}-T_\mathrm{amb}$ ought to obey, so that eventually we expect $T\sim T_\mathrm{avg}=T_\mathrm{amb}+T_ce^{-\frac t{t_c}}$ where $T_c$ and $t_c$ are, respectively, a characteristic temperature and a characteristic time. (The “$\sim$” means “is asymptotical to” or “approaches”.) We plot $\ln(T-T_\mathrm{amb})$ using the data from the table. Then approximate the “tail” linearly (valuing the end of it most) to get $\ln[(T-T_\mathrm{amb})/^\circ\mathrm{C}]\sim4.89-\frac{t}{300\,\mathrm{s}}$. Therefore $T_c\approx e^{4.89}\,{}^\circ\mathrm{C}\approx133^\circ\mathrm{C}$. On the other hand, plugging $t=0$ into our exponential function shows that $T_{\mathrm{avg},0}-T_\mathrm{amb}=T_c$ and, finally,
> $Q=CT_c\approx46700\,\mathrm{J}$.
>
> ![[nbpho-2011-p5-f1.svg]]
>
> Actually, quite a good result can be obtained without re-plotting anything, by just considering the last three datapoints of the table. Denote $\Delta T_i\equiv T_i-T_\mathrm{amb}$. If the times $t_3-t_2=t_2-t_1$, then with an exponential we should observe that $\Delta T_3/\Delta T_2=\Delta T_2/\Delta T_1$. The last three timepoints are good indeed, so we check $\Delta T_1=4.4^\circ\mathrm{C}$, $\Delta T_2=2.3^\circ\mathrm{C}$ and $\Delta T_3=1.2^\circ\mathrm{C}$. Their ratios are $\Delta T_3/\Delta T_2\approx0.522$ and $\Delta T_2/\Delta T_1\approx0.523$, a splendid match. This confirms the exponential “tail”. As in every equal time interval the $\Delta T$ is multiplied by the same number (that is the essence of exponentials), $T_c=\Delta T_{\mathrm{avg},0}=\Delta T_3\times\left(\frac{\Delta T_2}{\Delta T_3}\right)^{\frac{t_3}{t_3-t_2}}\approx114^\circ\mathrm{C}$. From this,
> $Q\approx39900\,\mathrm{J}$. This is discrepant from our previous calculation, but not too much: $T_c$ is exponentially sensitive to the $T$-intercept of the straight line fitted to the “tail” (its crossing point with the $T$-axis) on the logarithmic plot. The bump has still not yet disappeared completely enough.
