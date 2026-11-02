---
id: nbpho-2023-intl-theory-5
olympiad: NbPhO
year: 2023
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "5"
title: "Force sensor"
points: 5
authors: ["Päivo Simson"]
aliases: ["Force sensor"]
topics: ["[[1.15 Упругость. Весомая пружина]]", "[[1.10 Статика]]", "[[5.4 Симметрии электрических цепей. Перемычки]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: true
source_damaged: false
summary: "Связать изгиб упругой балки и сопротивления тензодатчиков с выходным напряжением моста."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 5. Force sensor (5 points) — Päivo Simson.

**NbPhO 2023** · Международная олимпиада · теория · 10–12 класс · задача 5  
Источник: [[_pdf/NbPhO/nbpho-2023.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2023.pdf#page=8|решение, стр. 8]]

Темы: [[1.15 Упругость. Весомая пружина]], [[1.10 Статика]], [[5.4 Симметрии электрических цепей. Перемычки]]

> [!abstract] Кратко (составлено моделью)
> Связать изгиб упругой балки и сопротивления тензодатчиков с выходным напряжением моста.

A force sensor is constructed from a flexible beam of working length $L$ and height $h$ to which four identical electrically resistive wires of length $l\ll L$ are attached, as shown in the figure below. If a force $F$ is applied to the end of the beam, it will bend the beam and stretch the upper wires and compress the lower ones, causing changes in the electrical resistance. Using the Wheatstone bridge method, these changes can be converted into a voltmeter reading, allowing for the measurement of the applied force $F$.

![[nbpho-2023-p2-c0129.png]]

In what follows, assume that the deflection of the beam is very small.

**i)** (2 points) The bending moment $M(x)$ (i.e. the torque with which one fictitious half of the beam affects the other) is inversely proportional to the curvature radius $r(x)$ of the center line of the beam: $M=EI/r$, where $E$ is Young’s modulus and $I$ is a constant depending on the geometry of the of the beam’s cross-section (both are known). Find the elongation $\Delta l$ of the upper wire when a force $F$ is applied to the sensor. Assume that the wires are placed in the middle of the beam.

**ii)** (1 point) Find the resistances $R_1$ and $R_2$ when $\Delta l$ from the previous section is known and the initial resistance of the wires is $R_0$. Assume that the volume of the wire remains constant during the deformation.

**iii)** (2 points) The resistors are arranged in a Wheatstone bridge configuration shown in the figure below, where $U$ is the known battery voltage. Find the relationship between the measured voltage $V$ and the force $F$.

![[nbpho-2023-p2-f1.svg]]

> [!answer]- Ответ
> **i**
>
> $$
> \Delta l=\frac{FLlh}{4EI}.
> $$
>
> **ii**
>
> $$
> R_1=\frac{\rho(l+\Delta l)^2}{lS}\approx\frac{\rho l(1+2\Delta l/l)}{S}=R_0+\Delta R,
> $$
>
> **ii**
>
> $$
> R_2=\frac{\rho(l-\Delta l)^2}{lS}\approx\frac{\rho l(1-2\Delta l/l)}{S}=R_0-\Delta R,
> $$
>
> **ii**
>
> $$
> \Delta R=\frac{2\rho\Delta l}{S}=2R_0\frac{\Delta l}{l}=R_0\frac{FLh}{2EI}.
> $$
>
> **iii**
>
> $$
> F=\frac{2EIV}{LhU}.
> $$

> [!solution]- Решение
> # 5. Force sensor (5 points) — Solution by Päivo Simson, grading schemes by ....
>
> **i)** (2 points) To find the elongation $\Delta l$, we need to know the curvature radius $r$ of the beam at $x=L/2$. The torque created by the force $F$ at an arbitrary point $x$ is $F\cdot(L-x)$. This must be balanced by the bending moment $M(x)$ of the beam. In the middle of the beam we have
>
> $$M=\frac{EI}{r}=F\frac L2\implies r=\frac{2EI}{FL}.$$
>
> It is easy to see that if the upper wires elongate by $\Delta l$, the lower ones shorten by the same amount. Now we need to relate the curvature radius $r$ with the elongation $\Delta l$.
>
> ![[nbpho-2023-p8-f1.svg]]
>
> The arc length of a circle is $\Delta s=r\Delta\phi$. Knowing this, we have from the above figure
>
> $$l+\Delta l=\left(r+\frac h2\right)\Delta\phi,$$
> $$l-\Delta l=\left(r-\frac h2\right)\Delta\phi.$$
>
> By dividing the above equations, we get an equation for $\Delta l$ that is easily solved:
>
> $$\frac{l+\Delta l}{l-\Delta l}=\frac{2r+h}{2r-h}\implies\Delta l=\frac{lh}{2r}.$$
>
> Combining this with the expression for $r$ we have
>
> $$\Delta l=\frac{FLlh}{4EI}.$$
>
> **ii)** (1 point) Let $\rho$ and $S$ be the resistivity and the cross-sectional area of the wires, respectively. The initial resistance $R_0$ of all the wires is
>
> $$R_0=\frac{\rho l}{S}=\frac{\rho l^2}{lS},$$
>
> where $lS$ is the volume of the wire that remains constant during the deformation. Assuming $\Delta l\ll l$ we have
>
> $$R_1=\frac{\rho(l+\Delta l)^2}{lS}\approx\frac{\rho l(1+2\Delta l/l)}{S}=R_0+\Delta R,$$
>
> $$R_2=\frac{\rho(l-\Delta l)^2}{lS}\approx\frac{\rho l(1-2\Delta l/l)}{S}=R_0-\Delta R,$$
>
> where
>
> $$\Delta R=\frac{2\rho\Delta l}{S}=2R_0\frac{\Delta l}{l}=R_0\frac{FLh}{2EI}.$$
>
> **iii)** (2 points) The total resistance $R$ of the circuit is
>
> $$R=\frac{(R_1+R_2)(R_1+R_2)}{2R_1+2R_2}=\frac{R_1+R_2}{2}$$
>
> Since both sides of the circuit have the same total resistance $R_1+R_2$, the current is also the same. The voltmeter reading is therefore
>
> $$V=\frac I2R_2-\frac I2R_1=\frac U{2R}(R_1-R_2)=$$
> $$=U\frac{R_1-R_2}{R_1+R_2}=U\frac{\Delta R}{R_0}=U\frac{FLh}{2EI}.$$
>
> From this, we finally have
>
> $$F=\frac{2EIV}{LhU}.$$

> [!grading]- Критерии оценивания
> **Grading:**
> - Correct moment equation $EI/r=FL/2$ at the center of the beam **(0.6 pts)**
> - Correct geometric relations for $l\pm\Delta l$ based on $\Delta s=r\Delta\phi$ **(0.6 pts)**
> - correctly solving for $\Delta l$ **(0.6 pts)**
> - correctly expressing the final answer **(0.2 pts)**
>
> **ii)**
>
> **Grading:**
> - $R=\rho l/S$ **(0.3 pts)**
> - Correct approximations **(0.3 pts)**
> - Correctly calculating the resistances and the change in resistance using the above relations **(0.4 pts)**
>
> **iii)**
>
> **Grading:**
> - Correct total resistance of the Wheatstone circuit **(0.5 pts)**
> - Assumes that the resistance of the Voltmeter is infinite **(0.5 pts)**
> - Correctly calculating the potential difference $V$ as a function of the change in the resistance **(0.5 pts)**
> - Expressing the final answer in the form given in the solution **(0.5 pts)**
