---
id: rompho-2021-intl-theory-t2
olympiad: RomPhO
year: 2021
stage: "Международная олимпиада"
round: теория
grade: ""
number: "T2"
title: "Coffee - Flavored Physics"
aliases: ["Coffee - Flavored Physics"]
topics: ["[[2.2 Уравнение состояния идеального газа]]", "[[2.10 Насыщенный пар]]", "[[1.18 Гидростатика]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Исследовать нагрев воды, давление воздуха и насыщенного пара и перенос воды через кофейный слой в гейзерной кофеварке."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# Problem 2: Coffee - Flavored Physics

**RomPhO 2021** · Международная олимпиада · теория · задача T2  
Источник: [[_pdf/RomPhO/RomPhO-2021-T2.pdf#page=1|условие, стр. 1–4]] · [[_pdf/RomPhO/RomPhO-2021-T2-soltuion.pdf#page=2|решение, стр. 2–9]]

Темы: [[2.2 Уравнение состояния идеального газа]], [[2.10 Насыщенный пар]], [[1.18 Гидростатика]]

> [!abstract] Кратко (составлено моделью)
> Исследовать нагрев воды, давление воздуха и насыщенного пара и перенос воды через кофейный слой в гейзерной кофеварке.

The most popular coffee making device in Italy is the so-called moka pot (Fig. 1) and the purpose of this problem is to analyze some of the physical processes and phenomena taking place during the coffee brewing process.

![[rompho-2021-t2-problems-p1-c7612.png]]
*Fig. 1*

The moka pot has three independent structural elements, all made of aluminum:

- the kettle (the lower part of the pot) in which the water is heated; the kettle has a safety pressure valve at its upper part (Figs. 1 and 2);
- the funnel, which contains the ground coffee container (Fig. 2). Its tube is submerged into the water but does not touch the base of the kettle. The coffee container has a cylindrical shape with the inner diameter $d=4.3$ cm and the depth $h=1.4$ cm. The base of the container is a filter (a perforated Al disc, as can be seen in Figs. 2 and 3). When the container is filled with coffee, the coffee forms a plug acting as a porous filter for water;
- the collector (the upper vessel of the pot) in which the water passing the coffee plug is collected (the liquid coffee). At its bottom there is a similar filter as in the funnel (a perforated Al plate), which touches the upper surface of the coffee plug (Fig.3). This filter is surrounded by a rubber gasket which seals the air pocket trapped above the water in the kettle, between the funnel and the kettle walls (Figs. 3 and 4).

![[rompho-2021-t2-problems-p1-c7930.png]]
*Fig. 2*

![[rompho-2021-t2-problems-p1-c6056.png]]
*Fig. 3*

![[rompho-2021-t2-problems-p1-c6172.png]]
*Fig. 4*

The moka pot is used as follows (Fig. 2):

- water is poured into the kettle (not surpassing the safety valve);
- the funnel is lowered into the kettle, closing its opening;
- the funnel’s container is loaded with ground coffee;
- the collector is screwed onto the kettle;
- the pot is placed on a slow heater.

One functioning cycle of the moka pot can be divided into two stages:

A. The rise of the water temperature;
B. The water transfer from the kettle to the collector, through the funnel. This stage ends with a gurgling sound made by the residual steam during its evacuation from the kettle.

## A. Stage one: the rise of the water temperature (4.2 p)

During this stage, no water flows from the kettle to the collector. This heating process can also be divided into two parts:

**a)** as its temperature increases from $\theta_1=17.3\ {}^\circ$C to $\theta_2=72.0\ {}^\circ$C, the water rises in the funnel and at $\theta_2=72.0\ {}^\circ$C the water touches the perforated disc at the bottom of the coffee plug from the funnel;

**b)** as its temperature increases from $\theta_2=72.0\ {}^\circ$C to $\theta_3=99.5\ {}^\circ$C, the water floods the coffee plug. At $\theta_3=99.5\ {}^\circ$C the water fills completely the ground coffee container. Some quantities of interest for water (density, pressure of saturated vapors, and dynamic viscosity coefficient) for the above temperatures are given in the adjacent table.

| $\theta$/°C | $\rho_w$/kg/m$^3$ | $p_{sv}$/kPa | $\eta/10^{-4}$ Pa · s |
|---|---|---|---|
| 17.3 | 999 | 1.98 | 10.7 |
| 72.0 | 977 | 34.0 | 3.92 |
| 99.5 | 959 | 99.6 | 2.83 |

The useful volume of the kettle (obtained from its total inner volume by subtracting the volume displaced by the walls of the funnel and the volume of the funnel’s container) is $V_0=84.2$ ml. If this volume of water is poured into the kettle, the water touches the perforated disc of the funnel and there is no air pocket above the water (see Fig. 4). However, the water level in the kettle should be lower than the safety valve. In this problem, the water mass used for making coffee was $m_w=60.0$ g, which satisfies the above restriction. Also, during the coffee brewing process, for the specific data given in this problem, the safety pressure valve does not open.

The atmospheric pressure when the experimental data were collected was $p_0=96.4$ kPa. The air and the water vapors existent above the water in the kettle are considered ideal gases and the thermal dilatation of the pot is neglected throughout this problem. The water is considered permanently in dynamical equilibrium with its vapors because the heating process is a slow one.

**A.1 Water vapors (0.9 p)**

Above the water in the kettle, trapped between the wall of the funnel and that of the kettle, there is a fixed amount of air and a variable quantity of saturated water vapors – the so-called ”air pocket” in Fig. 4. Knowing that the mass of water vaporized during the heating process is negligible compared with the total mass of water, derive an expression for the mass of saturated water vapors ($m_{sv,2}$) in the air pocket at the temperature $\theta_2=72.0\ {}^\circ$C and calculate its numerical value. The molar mass for water is $\mu_w=18.0$ g/mol, the ideal gas constant is $R=8.32$ J/(mol · K).

**A.2 The initial volume of the air pocket (0.8 p)**

When the water temperature reaches $\theta_2=72.0\ {}^\circ$C, the level difference between the water in the funnel and that in the kettle is $\Delta h=12.1$ mm. Derive an expression for the volume of the air pocket ($V_{air,1}$) in the initial state (at $\theta=\theta_1$) and calculate its numerical value. The gravitational acceleration is $g=9.81$ m/s$^2$.

**A.3 The internal energy variation (1.4 p)**

Determine a mathematical expression for the internal energy variation of the air trapped in the air pocket ($\Delta U_{air/air\ pocket}$), as well as for that of the air in the collector ($\Delta U_{air/collector}$), during the $\theta_1\to\theta_2$ heating process, and calculate their numerical values. The average specific heat of air at constant volume for the temperature range of interest is $c_V=719$ J/(kg · K) and the molar mass of air is $\mu_{air}=29.0$ g/mol.

**A.4 The pressure in the air pocket at the end of stage one (1.1 p)**

As the temperature rises from $\theta_2=72.0\ {}^\circ$C to $\theta_3=99.5\ {}^\circ$C, the water is flooding the coffee plug which fills the container of the funnel. The coffee plug has the mass $m_c=6.0$ g and the density of compacted coffee is $\rho_c=1190$ kg/m$^3$. At $\theta_3=99.5\ {}^\circ$C the water fills completely the container and this is the end of stage one of coffee brewing. Derive an expression for the pressure $p_3$ above the water in the kettle at $\theta_3=99.5\ {}^\circ$C and calculate its numerical value. For the purpose of this task, neglect the solubility of any coffee component in water, as well as the mass of the water vapors with respect to the total mass of water.

## B. Stage two: the rise of the water in the collector (5.8 p)

This process takes place at the constant temperature $\theta=\theta_3$. The water starts flowing through the filter once the container of the funnel is filled with water and the driver of this process is the pressure difference at the ends of the filter. After the water is transferred to the collector, this second stage of functioning of the moka pot is over. The well-known gurgling sound signals that the coffee brewing is finished.

**B.1 The filtration law (0.7 p)**

When the container of the funnel is loaded with ground coffee, the coffee plug (together with the bordering perforated Al discs) will act as a cylindrical filter, the properties of which will depend on the dimensions of the coffee grains and the compactness of the coffee plug. The filtration law gives the relationship between the volume flow rate $Q$ of water through the filter and the pressure difference $\Delta p$ on its faces and is similar with Ohm’s law in electricity. The hydrodynamic resistance of the filter $\mathcal R_h$, similarly to its counterpart in electricity, depends on the area $S$ of the plug’s transversal section, its height $h$, but it also depends on the dynamic viscosity coefficient $\eta$ of water and on the so-called filtration coefficient, $k$, also known as the permeability of the filter. Knowing that the filtration coefficient has the dimension of an area and that the measurement unit for $\eta$ in SI is Pa · s, derive an expression for $\mathcal R_h$, as a function of $S,h,k$ and $\eta$, using dimensional analysis. Consider any numeric coefficient equal to one.

**B.2 Time evolution of air pressure in the air pocket (1.4 p)**

Derive the variation law for the pressure of the air in the air pocket during the second stage of the functioning cycle of the moka pot, as a function of time, $p_{air}(t)$. For simplicity, consider that the hydrodynamic resistance of the filter is constant during this stage.

**B.3 The hydrodynamic resistance of the filter filled with coffee (0.7 p)**

When the container is filled with ground coffee, the water passage through the filter takes the time $\tau_c=54$ s. Derive an expression for the hydrodynamic resistance of the filter filled with ground coffee ($\mathcal R_h$) and calculate its numerical value.

**B.4 The filtration coefficient of the coffee plug (1.2 p)**

When the funnel’s container is empty, the passage time of the same quantity of water through this filter is $\tau_0=17$ s and the water transfer through the funnel takes place at the same temperature as in the presence of the coffee plug. Derive an expression for the filtration coefficient of coffee ($k$) and calculate its numerical value. Assume that the water reaches the base of the funnel’s container at the same temperature as above, even if the coffee plug is absent. When the coffee plug is in the container, consider that all the water passing the filter goes through coffee.

**B.5 The work done by the air pocket during the coffee filtration process (0.8 p)**

Derive an expression for the work done by the air ($\mathcal W_{air}$) from the air pocket, as well as for the work done by the water saturated vapors ($\mathcal W_{sv}$) from the air pocket, respectively, on the water inside the kettle during the filtration process and calculate their numerical values.

**B.6 The work done for circulating the water through the filter to produce coffee infusion (1.0 p)**

Derive an expression for the work done to pass the water from the kettle through the filter ($\mathcal W_w$) and calculate its numerical value.

*Note:* If needed, you can use one of the following pieces of information:

$$
\ln(1+x)\cong x-\frac{x^2}{2}
$$

The relative error made for the above approximation is below 1% for $x<0.177$.

$$
\int\frac{dx}{x^2(x+a)}=\frac1{a^2}\left[\ln\left(1+\frac ax\right)-\frac ax\right]+\mathcal C
$$
$$
\int\frac{dx}{\sqrt{1+ax}}=\frac2a\sqrt{1+ax}+\mathcal C
$$
$$
\int\frac{dx}{1+ax}=\frac1a\ln(1+ax)+\mathcal C
$$

Assoc. Prof. Sebastian POPESCU, PhD  
Faculty of Physics, Alexandru Ioan Cuza University of Iasi, ROMANIA

> [!answer]- Ответ
> **A.1**
>
> $$
> m_{sv,2}=\frac{p_{sv,2}\mu_w}{RT_2}\left(V_0-\frac{m_w}{\rho_{w2}}\right),\qquad 0.2\text{ p}
> $$
>
> **A.1**
>
> $$
> m_{sv,2}=4.86\cdot10^{-3}\ \mathrm g,\qquad 0.2\text{ p}
> $$
>
> **A.2**
>
> $$
> V_{air,1}=\frac{p_0+\rho_{w2}g\Delta h-p_{sv,2}}{p_0-p_{sv,1}}\frac{T_1}{T_2}\left(V_0-\frac{m_w}{\rho_{w2}}\right)\qquad 0.2\text{ p}
> $$
>
> **A.2**
>
> $$
> V_{air,1}=\frac{62.5}{94.4}\times\frac{290.45}{345.15}\times22.8\ \mathrm{cm^3}=12.7\ \mathrm{cm^3}.\qquad 0.2\text{ p}
> $$
>
> **A.3**
>
> $$
> \Delta U_{air/airpocket}=m_{air}c_V(T_2-T_1),\qquad 0.2\text{ p}
> $$
>
> **A.3**
>
> $$
> \Delta U_{air/airpocket}=0.566\ \mathrm J.\qquad 0.2\text{ p}
> $$
>
> **A.3**
>
> $$
> \Delta U_{air/collector}=C_V(n_2T_2-n_1T_1),\qquad 0.2\text{ p}
> $$
>
> **A.3**
>
> $$
> \Delta U_{air/collector}=0\ \mathrm J.\qquad 0.1\text{ p}
> $$
>
> **A.4**
>
> $$
> p_3=\frac{T_3}{T_2}\frac{V_0-\frac{m_w}{\rho_{w2}}}{V_0-\frac{m_w}{\rho_{w3}}+\frac{\pi d^2h}{4}-\frac{m_c}{\rho_c}}(p_0+\rho_{w2}g\Delta h-p_{sv,2})+p_{sv,3},\qquad 0.2\text{ p}
> $$
>
> **A.4**
>
> $$
> p_3=42\ \mathrm{kPa}+99.6\ \mathrm{kPa}=141.6\ \mathrm{kPa}\cong1.4\cdot10^2\ \mathrm{kPa}.\qquad 0.2\text{ p}
> $$
>
> **B.1**
>
> $$
> \mathcal R_h=\frac{\eta h}{kS}.\qquad 0.2\text{ p}
> $$
>
> **B.2**
>
> $$
> p_{air}(t)=p_{air3}\left(1+\frac{2p_{air3}t}{\mathcal R_hV_{air3}}\right)^{-1/2}.\qquad 0.2\text{ p}
> $$
>
> **B.3**
>
> $$
> \mathcal R_h=\frac{2p_{air3}\tau_c}{V_{air3}\left[\left(\frac{V_0}{V_{air3}}\right)^2-1\right]}.\qquad 0.2\text{ p}
> $$
>
> **B.3**
>
> $$
> \mathcal R_h=2.9\cdot10^{10}\ \mathrm{Pa\cdot s\cdot m^{-3}}.\qquad 0.2\text{ p}
> $$
>
> **B.4**
>
> $$
> k=\frac{\eta h}{R_{h,coffee}S}=\frac{4\eta h}{\pi d^2R_{h,coffee}},\qquad 0.2\text{ p}
> $$
>
> **B.4**
>
> $$
> k=1.4\cdot10^{-13}\ \mathrm{m^2}.\qquad 0.2\text{ p}
> $$
>
> **B.5**
>
> $$
> \mathcal W_{air}=p_{air3}V_{air3}\ln\frac{V_0}{V_{air3}},\qquad 0.2\text{ p}
> $$
>
> **B.5**
>
> $$
> \mathcal W_{air}=1.3\ \mathrm J.\qquad 0.2\text{ p}
> $$
>
> **B.5**
>
> $$
> \mathcal W_{sv}=p_{sv,3}\Delta V=p_{sv,3}(V_0-V_{air3}),\qquad 0.2\text{ p}
> $$
>
> **B.5**
>
> $$
> \mathcal W_{sv}=99.6\cdot10^3\ \mathrm{Pa}\times47\cdot10^{-6}\ \mathrm{m^3}=4.7\ \mathrm J.\qquad 0.2\text{ p}
> $$
>
> **B.6**
>
> $$
> \mathcal W_w=\frac{a^2}{\mathcal R_h}\tau_c+2aV_{air3}\left(\sqrt{1+\frac{2p_{air3}\tau_c}{\mathcal R_hV_{air3}}}-1\right)+\frac{p_{air3}V_{air3}}2\ln\left(1+\frac{2p_{air3}\tau_c}{\mathcal R_hV_{air3}}\right).\qquad 0.2\text{ p}
> $$
>
> **B.6**
>
> $$
> \mathcal W_w=1.9\cdot10^{-2}\ \mathrm J+0.30\ \mathrm J+1.3\ \mathrm J=1.6\ \mathrm J.\qquad 0.2\text{ p}
> $$

> [!solution]- Решение
> **A.1 Solution: 0.9 p**
>
> The mass of saturated water vapors in the air pocket at the temperature $\theta_2$ is
>
> $$
> m_{sv,2}=\rho_{sv,2}V_{air,2},\qquad 0.1\text{ p}
> $$
>
> where
>
> $$
> \rho_{sv,2}=\frac{p_{sv,2}\mu_w}{RT_2}\qquad 0.2\text{ p}
> $$
>
> ($\rho_{sv,2}=0.213\ \mathrm{kg/m^3}$) and the volume occupied by air at $\theta_2=72.0\ {}^\circ$C is
>
> $$
> V_{air,2}=V_0-V_{w2},\qquad 0.1\text{ p}
> $$
>
> where
>
> $$
> V_{w2}=\frac{m_w}{\rho_{w2}}\qquad 0.1\text{ p}
> $$
>
> ($V_{w2}=61.4\ \mathrm{cm^3}$ and $V_{air,2}=22.8\ \mathrm{cm^3}$), because the mass of water vaporized in this process is negligible compared with the total mass of water. Hence,
>
> $$
> m_{sv,2}=\frac{p_{sv,2}\mu_w}{RT_2}\left(V_0-\frac{m_w}{\rho_{w2}}\right),\qquad 0.2\text{ p}
> $$
>
> having the numerical value
>
> $$
> m_{sv,2}=4.86\cdot10^{-3}\ \mathrm g,\qquad 0.2\text{ p}
> $$
>
> which is, indeed, negligible compared to the mass of water.
>
> **A.2 Solution: 0.8 p**
>
> The air pocket volume at the beginning of the heating stage can be obtained from the general transformation equation of an ideal gas
>
> $$
> \frac{p_{air,1}V_{air,1}}{T_1}=\frac{p_{air,2}V_{air,2}}{T_2},
> $$
>
> hence
>
> $$
> V_{air,1}=\frac{p_{air,2}}{p_{air,1}}\frac{T_1}{T_2}V_{air,2}.\qquad 0.2\text{ p}
> $$
>
> Initially, the pressure in the air pocket (air and air vapor mixture) is the atmospheric pressure, so
>
> $$
> p_{air1}=p_{air}(T_1)=p_0-p_{sv,1}\qquad 0.1\text{ p}
> $$
>
> ($p_{air1}=96.4\ \mathrm{kPa}-1.98\ \mathrm{kPa}=94.4\ \mathrm{kPa}$).
>
> In the state 2,
>
> $$
> p_{air2}=p_{air}(T_2)=(p_0+\rho_{w2}g\Delta h)-p_{sv,2}\qquad 0.1\text{ p}
> $$
>
> ($p_{air2}=(96.4\ \mathrm{kPa}+116\ \mathrm{Pa})-34.0\ \mathrm{kPa}=62.5\ \mathrm{kPa}$). Hence
>
> $$
> V_{air,1}=\frac{p_0+\rho_{w2}g\Delta h-p_{sv,2}}{p_0-p_{sv,1}}\frac{T_1}{T_2}\left(V_0-\frac{m_w}{\rho_{w2}}\right)\qquad 0.2\text{ p}
> $$
>
> and its numerical value is
>
> $$
> V_{air,1}=\frac{62.5}{94.4}\times\frac{290.45}{345.15}\times22.8\ \mathrm{cm^3}=12.7\ \mathrm{cm^3}.\qquad 0.2\text{ p}
> $$
>
> **A.3 Solution: 1.4 p**
>
> *In the kettle:* The air pocket is a closed system. The mass of air is
>
> $$
> m_{air}=\frac{p_{air,1}V_{air,1}\mu_{air}}{RT_1}\qquad 0.2\text{ p}
> $$
>
> ($m_{air}=1.44\cdot10^{-5}$ kg), so, the internal energy variation is
>
> $$
> \Delta U_{air/airpocket}=m_{air}c_V(T_2-T_1),\qquad 0.2\text{ p}
> $$
>
> having the numerical value
>
> $$
> \Delta U_{air/airpocket}=0.566\ \mathrm J.\qquad 0.2\text{ p}
> $$
>
> *In the collector:* Because the collector is not sealed, the air volume is an open system, so, at any temperature, the Clapeyron-Mendeleev equation is $p_0V_{collector}=nRT$, because the air in the collector is permanently at atmospheric pressure. Since $V_{collector}$ is also constant, under the assumption that the thermal dilatation of the pot is neglected, then, at any temperature we will have $nT=const.$ (0.3 p)
>
> The internal energy variation of the air from the collector is
>
> $$
> \Delta U_{air/collector}=U_{air/collector,2}-U_{air/collector,1}=(n_2C_VT_2+U_0)-(n_1C_VT_1+U_0),\qquad 0.2\text{ p}
> $$
>
> so
>
> $$
> \Delta U_{air/collector}=C_V(n_2T_2-n_1T_1),\qquad 0.2\text{ p}
> $$
>
> having the numerical value
>
> $$
> \Delta U_{air/collector}=0\ \mathrm J.\qquad 0.1\text{ p}
> $$
>
> **A.4 Solution: 1.1 p**
>
> The pressure above the water in the kettle is $p_3=p_{air,3}+p_{sv,3}$, (0.1 p) where
>
> $$
> p_{air,3}=\frac{T_3}{T_2}\frac{V_{air,2}}{V_{air,3}}p_{air,2}.\qquad 0.2\text{ p}
> $$
>
> ($p_{air,3}=41.6\ \mathrm{kPa}\cong42\ \mathrm{kPa}$). The air volume trapped in the kettle at $T_3=372{,}65$ K is $V_{air,3}=V_0-(V_{w3}-V_f)$, (0.1 p) where the water volume is $V_{w3}=\frac{m_w}{\rho_{w3}}$ ($V_{w3}=62.6\ \mathrm{cm^3}$) (0.1 p) and the container volume flooded by water is (0.2 p)
>
> $$
> V_f=\frac{\pi d^2h}{4}-\frac{m_c}{\rho_c}.
> $$
>
> ($V_f=20\ \mathrm{cm^3}-5{,}0\ \mathrm{cm^3}=15.0\ \mathrm{cm^3}\cong15\ \mathrm{cm^3}$ and $V_{air,3}=36.6\ \mathrm{cm^3}\cong37\ \mathrm{cm^3}$). So,
>
> $$
> p_3=\frac{T_3}{T_2}\frac{V_0-\frac{m_w}{\rho_{w2}}}{V_0-\frac{m_w}{\rho_{w3}}+\frac{\pi d^2h}{4}-\frac{m_c}{\rho_c}}(p_0+\rho_{w2}g\Delta h-p_{sv,2})+p_{sv,3},\qquad 0.2\text{ p}
> $$
>
> its numerical value being
>
> $$
> p_3=42\ \mathrm{kPa}+99.6\ \mathrm{kPa}=141.6\ \mathrm{kPa}\cong1.4\cdot10^2\ \mathrm{kPa}.\qquad 0.2\text{ p}
> $$
>
> **B.1 Solution: 0.7 p**
>
> The filtration law is $\Delta p=Q\cdot\mathcal R_h$ (0.2 p) and $\mathcal R_h=f(\eta,k)\frac hS$, (0.2 p) because, in electricity, the electric resistance can be written as $R=\rho\frac lS$, where $\rho$ is the electric resistivity of the given resistor. Then, using dimensional analysis, it follows that $\mathcal R_h=C\eta^\alpha k^\beta hS^{-1}$, (0.1 p) with $C=1$, as stated in the text. According to the details in the following table, giving the physical quantities, their measurement units in SI and their dimensions
>
> | $X$ | $\mathcal R_h$ | $S$ | $h$ | $\eta$ | $k$ |
> |---|---|---|---|---|---|
> | $\langle X\rangle_{SI}$ | $\mathrm{Pa\cdot s/m^3=kg/(m^4s)}$ | $\mathrm{m^2}$ | $\mathrm m$ | $\mathrm{Pa\cdot s=kg/(m\cdot s)}$ | $\mathrm{m^2}$ |
> | $[X]$ | $L^{-4}MT^{-1}$ | $L^2$ | $L$ | $L^{-1}MT^{-1}$ | $L^2$ |
>
> the dimensional equation will be:
>
> $$
> L^{-4}MT^{-1}=(L^{-1}MT^{-1})^\alpha L^{2\beta}L\cdot L^{-2},
> $$
>
> or, equating the exponents, $\begin{cases}\alpha=1\\\beta=-1\end{cases}$, hence
>
> $$
> \mathcal R_h=\frac{\eta h}{kS}.\qquad 0.2\text{ p}
> $$
>
> **B.2 Solution: 1.4 p**
>
> The water flowing equation is $p_{air}+p_{sv,3}-p_0=\mathcal R_hQ$. (0.1 p) Denoting $a=p_{sv,3}-p_0=3.2$ kPa, the above equation can be written as $p_{air}+a=-\mathcal R_h\frac{dV}{dt}$, (0.2 p) because the water volume in the kettle decreases in time.
>
> The second stage is, essentially, an isothermal process at $T_3=372.65$ K, for which the air volume is
>
> $$
> V_0-V=\frac{p_{air3}V_{air3}}{p_{air}},\qquad 0.2\text{ p}
> $$
>
> where $V$ is the volume occupied by water at that instant. Hence
>
> $$
> -\frac{dV}{dt}=-\frac{p_{air3}V_{air3}}{p_{air}^2}\frac{dp_{air}}{dt},\qquad 0.1\text{ p}
> $$
>
> which gives
>
> $$
> p_{air}+a=-\mathcal R_h\frac{p_{air3}V_{air3}}{p_{air}^2}\frac{dp_{air}}{dt}.\qquad 0.2\text{ p}
> $$
>
> After separating the variables, we get
>
> $$
> \frac{dp_{air}}{p_{air}^2(p_{air}+a)}=-\frac{dt}{\mathcal R_hp_{air3}V_{air3}}.
> $$
>
> Using the integral given at the end of the text, it follows that
>
> $$
> \frac1{a^2}\left[\ln\left(1+\frac a{p_{air}}\right)-\frac a{p_{air}}\right]=-\frac{t}{\mathcal R_hp_{air3}V_{air3}}+\mathcal C.\qquad 0.2\text{ p}
> $$
>
> Since $a=3.2$ kPa and $p_{air}$ varies between $p_{air3}=42$ kPa and $p_{air4}=\frac{p_{air3}V_{air3}}{V_0}=18.5$ kPa $\cong19$ kPa, this means that the ratio $a/p_{air}$ varies between 0.076 and 0.17. Consequently, the logarithm function can be approximated as suggested at the end of the text $\ln(1+x)\cong x-x^2/2$, for $x<0.177$, so, the above equation can be written as
>
> $$
> \frac1{2p_{air}^2}=\frac{t}{\mathcal R_hp_{air3}V_{air3}}-\mathcal C.\qquad 0.1\text{ p}
> $$
>
> The integration constant can be determined considering that at $t=0\to p_{air}=p_{air3}$, so $\mathcal C=-\frac1{2p_{air3}^2}$. (0.1 p) As a result,
>
> $$
> p_{air}(t)=p_{air3}\left(1+\frac{2p_{air3}t}{\mathcal R_hV_{air3}}\right)^{-1/2}.\qquad 0.2\text{ p}
> $$
>
> **B.3 Solution: 0.7 p**
>
> At the end of the stage two, the air pressure in the kettle is $p_{air4}$ (with the numerical value given above), so
>
> $$
> \mathcal R_h=\frac{2p_{air3}\tau_c}{V_{air3}\left[\left(\frac{p_{air3}}{p_{air4}}\right)^2-1\right]}.\qquad 0.1\text{ p}
> $$
>
> Since $p_{air4}=\frac{p_{air3}V_{air3}}{V_0}$, (0.2 p) then
>
> $$
> \mathcal R_h=\frac{2p_{air3}\tau_c}{V_{air3}\left[\left(\frac{V_0}{V_{air3}}\right)^2-1\right]}.\qquad 0.2\text{ p}
> $$
>
> Its numerical value is
>
> $$
> \mathcal R_h=2.9\cdot10^{10}\ \mathrm{Pa\cdot s\cdot m^{-3}}.\qquad 0.2\text{ p}
> $$
>
> **B.4 Solution: 1.2 p**
>
> From the text, states 1 and 2 are the same, while the state 3 becomes 3’, characterized by
>
> $$
> V'_{air,3}=V_0-(V_{w3}-V_{container})=84.2\ \mathrm{ml}-62.5\ \mathrm{ml}+20\ \mathrm{ml}=41.7\ \mathrm{ml}\cong42\ \mathrm{ml}.\qquad 0.1\text{ p}
> $$
>
> and $p'_3=p'_{air,3}+p_{sv,3}$, where
>
> $$
> p'_{air,3}=\frac{T_3}{T_2}\frac{V_{air,2}}{V'_{air,3}}p_{air,2}=37\ \mathrm{kPa}.\qquad 0.2\text{ p}
> $$
>
> So $p'_3=37\ \mathrm{kPa}+99{,}6\ \mathrm{kPa}=136.6\ \mathrm{kPa}\cong1.4\cdot10^2\ \mathrm{kPa}$. Since the transformation $3\to4$, respectively $3'\to4'$ are isothermal, for the same quantity of air, at the same temperature, and with the same final volume, it means that $p'_{air4}=p_{air4}=19$ kPa.
>
> Then
>
> $$
> \mathcal R_{h0}=\frac{2p'_{air3}\tau_0}{V'_{air,3}\left[\left(\frac{V_0}{V'_{air,3}}\right)^2-1\right]},\qquad 0.1\text{ p}
> $$
>
> having the numerical value $\mathcal R_{h0}=9.9\cdot10^9\ \mathrm{Pa\cdot s\cdot m^{-3}}$. (0.1 p) Because $R_h=R_{h0}+R_{h,coffee}$, (0.2 p) then $R_{h,coffee}=1.9\cdot10^{10}\ \mathrm{Pa\cdot s\cdot m^{-3}}$. (0.1 p) Finally, the filtration coefficient of the used coffee is
>
> $$
> k=\frac{\eta h}{R_{h,coffee}S}=\frac{4\eta h}{\pi d^2R_{h,coffee}},\qquad 0.2\text{ p}
> $$
>
> with the numerical value
>
> $$
> k=1.4\cdot10^{-13}\ \mathrm{m^2}.\qquad 0.2\text{ p}
> $$
>
> **B.5 Solution: 0.8 p**
>
> The work done by the air during its isothermal expansion is
>
> $$
> \mathcal W_{air}=p_{air3}V_{air3}\ln\frac{V_0}{V_{air3}},\qquad 0.2\text{ p}
> $$
>
> having the numerical value
>
> $$
> \mathcal W_{air}=1.3\ \mathrm J.\qquad 0.2\text{ p}
> $$
>
> The work done by the saturated vapors is
>
> $$
> \mathcal W_{sv}=p_{sv,3}\Delta V=p_{sv,3}(V_0-V_{air3}),\qquad 0.2\text{ p}
> $$
>
> with the numerical value
>
> $$
> \mathcal W_{sv}=99.6\cdot10^3\ \mathrm{Pa}\times47\cdot10^{-6}\ \mathrm{m^3}=4.7\ \mathrm J.\qquad 0.2\text{ p}
> $$
>
> **B.6 Solution: 1.0 p**
>
> The work done on the water to make it pass through the filter is
>
> $$
> \mathcal W_w=\int_0^{\tau_c}Pdt,\qquad 0.2\text{ p}
> $$
>
> where $P$ is the power needed for passing the water through the filter
>
> $$
> P=\frac{(\Delta p)^2}{\mathcal R_h}=\frac{(p_{air}+a)^2}{\mathcal R_h}=\frac{a^2}{\mathcal R_h}+2a\frac{p_{air}}{\mathcal R_h}+\frac{p_{air}^2}{\mathcal R_h}.\qquad 0.2\text{ p}
> $$
>
> Consequently,
>
> $$
> \mathcal W_w=\frac{a^2}{\mathcal R_h}\tau_c+\frac{2a}{\mathcal R_h}\int_0^{\tau_c}p_{air}dt+\frac1{\mathcal R_h}\int_0^{\tau_c}p_{air}^2dt\qquad 0.1\text{ p}
> $$
>
> and using the time evolution law for $p_{air}$, derived at B2, the work is
>
> $$
> \mathcal W_w=\frac{a^2}{\mathcal R_h}\tau_c+\frac{2ap_{air3}}{\mathcal R_h}\int_0^{\tau_c}\left(1+\frac{2p_{air3}t}{\mathcal R_hV_{air3}}\right)^{-1/2}dt+\frac{p_{air3}^2}{\mathcal R_h}\int_0^{\tau_c}\frac{dt}{1+\frac{2p_{air3}t}{\mathcal R_hV_{air3}}}.\qquad 0.1\text{ p}
> $$
>
> Finally, using the integrals given at the end of the text, the work becomes
>
> $$
> \mathcal W_w=\frac{a^2}{\mathcal R_h}\tau_c+2aV_{air3}\left(\sqrt{1+\frac{2p_{air3}\tau_c}{\mathcal R_hV_{air3}}}-1\right)+\frac{p_{air3}V_{air3}}2\ln\left(1+\frac{2p_{air3}\tau_c}{\mathcal R_hV_{air3}}\right).\qquad 0.2\text{ p}
> $$
>
> Numerically,
>
> $$
> \mathcal W_w=1.9\cdot10^{-2}\ \mathrm J+0.30\ \mathrm J+1.3\ \mathrm J=1.6\ \mathrm J.\qquad 0.2\text{ p}
> $$
