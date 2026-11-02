---
id: nbpho-2015-intl-theory-e1
olympiad: NbPhO
year: 2015
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "E1"
title: "Radiator"
points: 8
aliases: ["Radiator"]
topics: ["[[7 Эксперименты]]", "[[2.5 Первое начало термодинамики]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Измерить коэффициент теплообмена алюминиевого профиля с окружающим воздухом."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 5. RADIATOR (8 points)

**NbPhO 2015** · Международная олимпиада · теория · 10–12 класс · задача E1  
Источник: [[_pdf/NbPhO/nbpho-2015.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2015.pdf#page=7|решение, стр. 7]]

Темы: [[7 Эксперименты]], [[2.5 Первое начало термодинамики]]

> [!abstract] Кратко (составлено моделью)
> Измерить коэффициент теплообмена алюминиевого профиля с окружающим воздухом.

*(by M. Heidelberg)*

Measure the heat transfer coefficient $h$ between the environment and an aluminium profile. $h=\frac{p}{T-T_0}$, where $p$ is the heat flux from the aluminium profile to air per unit of length; $T$ and $T_0$ are the temperatures of aluminium and the environment, respectively. For measurements, keep the aluminium profile flat on your table surface, to limit nonlinear effects from turbulence. Thermal conductivity of aluminium is $k=205\mathrm{W/(K\cdot m)}$ and the cross-section of the profile is $A=36\mathrm{mm}^2$.

*Hint:* to describe the stationary temperature distribution along the profile we can derive a one-dimensional Helmholtz equation $T''(x)=\frac{h(T(x)-T_0)}{kA}$, the general solution of which is

$$T(x)=T_0+C_1e^{x\sqrt{\frac h{kA}}}+C_2e^{-x\sqrt{\frac h{kA}}},$$

where $C_1$ and $C_2$ are integration constants.

*Equipment:* Aluminium profile, wire (for heating), DC power source, infrared thermometer, ruler.

**Keep the temperature of the wire below 150°C as both the wire insulation and the table surface will start to emit smoke after that point!**

> [!solution]- Решение
> # 5. RADIATOR
>
> We wind the wire around one end of the aluminium profile and supply current to it for heating. In most cases it was OK to supply up to $5\mathrm{A}$ (the maximum possible) through the wire, only when it was wound very compact it could get too hot. This should give us good $100^\circ\mathrm{C}$ to measure on the profile, but the experiment also worked if smaller currents/temperatures were used. Now we wait until the temperature in the profile stabilises, this takes about five to ten minutes and we can check if it has stabilised with the thermometer.
>
> When the temperature has stabilised we measure and write down the temperature values along the part of the profile that is not covered with wire using a reasonable distance interval. We can see that that the other end of the profile is still at room temperature (the difference is below or near the resolution of this thermometer). This means that in the given solution for Helmholtz equation,
>
> $$T(x)=T_0+C_1e^{x\sqrt{\frac h{kA}}}+C_2e^{-x\sqrt{\frac h{kA}}},$$
>
> the integration constant $C_1=0$.
>
> Now one way is to use $T(0)$ to express $C_2=T(0)-T_0$ and use any other temperature measurement to calculate $h$. A better way is to plot the temperature difference in a logarithmic scale: $\log(T(x)-T_0)=-\sqrt{\frac h{kA}}x+C_2$, and use the slope of the graph $a=-\sqrt{\frac h{kA}}$ to calculate $h$. This gives a more accurate value for $h$ and allows us to better estimate the uncertainty by finding the range of slopes that can reasonably be drawn on the graph.
>
> The correct answer is in the range
> $h=0.3\mathrm{W/K\cdot m}$ to $h=0.5\mathrm{W/K\cdot m}$, it depends slightly on how the profile is placed on the table. The heat transfer coefficient is higher when the profile is on the edge of the table or slightly raised due to the wiring.
