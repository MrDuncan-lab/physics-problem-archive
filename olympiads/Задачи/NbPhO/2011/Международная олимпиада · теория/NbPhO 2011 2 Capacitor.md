---
id: nbpho-2011-intl-theory-2
olympiad: NbPhO
year: 2011
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "2"
title: "Capacitor"
points: 6
aliases: ["Capacitor"]
topics: ["[[3.5 Энергия системы]]", "[[3.8 Сложный конденсатор]]", "[[1.18 Гидростатика]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Найти энергию и силу между пластинами конденсатора, а также давление воды между ними."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 2. Capacitor (6 points)

**NbPhO 2011** · Международная олимпиада · теория · 10–12 класс · задача 2  
Источник: [[_pdf/NbPhO/nbpho-2011.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2011.pdf#page=3|решение, стр. 3]]

Темы: [[3.5 Энергия системы]], [[3.8 Сложный конденсатор]], [[1.18 Гидростатика]]

> [!abstract] Кратко (составлено моделью)
> Найти энергию и силу между пластинами конденсатора, а также давление воды между ними.

An ideal plate capacitor has plates with area $A$ and separation $d$ and is charged so that the electric field between the plates equals to $E$.

**i)** (2 pts) Find the energy density of the electric field inside the capacitor and the total energy of the field.

**ii)** (1.5 pts) What is the force required to keep the plates separated?

**iii)** (2.5 pts) Now, this capacitor is submerged into distilled water of dielectric permittivity $\varepsilon=80$; the electric field between the plates equals still to $E$. What is the hydrostatic pressure between the plates if the atmospheric pressure is $p_0$ and the pressure of the water column can be neglected?

> [!answer]- Ответ
> **i** — $W=CU^2/2=\frac12\varepsilon_0\frac Ad E^2d^2=\frac12\varepsilon_0AdE^2$; hence, the energy density
>
> **i** — $w=W/Ad=\frac12\varepsilon_0E^2$.
>
> **ii** — $F=Q\langle E\rangle=CEd\langle E\rangle=\frac12\varepsilon_0AE^2$.
>
> **ii** — $F=\frac12\varepsilon_0AE^2$.
>
> **iii**
>
> $$
> \Delta p=\frac12\varepsilon_0E^2(\varepsilon-1)\Rightarrow p=p_0+\frac12\varepsilon_0E^2(\varepsilon-1).
> $$

> [!solution]- Решение
> # 2. Capacitor (6 points)
>
> **i)** The energy is
> $W=CU^2/2=\frac12\varepsilon_0\frac Ad E^2d^2=\frac12\varepsilon_0AdE^2$; hence, the energy density
> $w=W/Ad=\frac12\varepsilon_0E^2$.
>
> **ii)** There are two ways to calculate the force. First, we notice that the innermost charges $q$ at the capacitor plates are affected by the electric field $E$, therefore there is a force $qE$ acting upon these. The outermost charges, however, have no electric field around them (because outside the inter-plate space, there is no electric field). Due to the Gauss law, the electric field decreases linearly with the net charge left below the level of the current point (i.e. towards the inter-plate space). Therefore, the electric field averaged over the charges is just half of the maximal value $E$: $\langle E\rangle=\frac12E$, and the net force acting on the plate is
> $F=Q\langle E\rangle=CEd\langle E\rangle=\frac12\varepsilon_0AE^2$.
>
> The second way includes writing the energy balance for a small displacement of a plate: $F\cdot\delta d=\delta(Q^2/2C)=\frac{Q^2}{2\varepsilon_0 A}\delta d=\frac12C^2E^2d\cdot\delta d\Rightarrow$
> $F=\frac12\varepsilon_0AE^2$.
>
> **iii)** Let us push away part of the water from the inter-plate space so that there will be a small region of plate area $dA$, where there is no water between the plates (here, $\Delta p$ is the pressure difference between the inter-plate space and the outside regions). By doing so, we perform work $d\cdot\delta A\cdot\Delta p$, and increase the capacitor’s energy:
>
> $$\delta W=\delta(Q^2/2C)=\frac{Q^2d}{2\varepsilon_0}\left[\frac1{\varepsilon A}-\frac1{\varepsilon(A-\delta A)+\delta A}\right].$$
>
> So,
>
> $$\delta W=\frac{Q^2d(\varepsilon-1)\cdot\delta A}{2\varepsilon_0\varepsilon^2A^2}=\frac12\varepsilon_0E^2d(\varepsilon-1)\cdot\delta A;$$
>
> comparing this with the pressure work $d\cdot\delta A\cdot\Delta p$ we conclude that
>
> $$\Delta p=\frac12\varepsilon_0E^2(\varepsilon-1)\Rightarrow p=p_0+\frac12\varepsilon_0E^2(\varepsilon-1).$$
