---
id: nbpho-2015-intl-theory-9
olympiad: NbPhO
year: 2015
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "9"
title: "Solenoids"
points: 8
aliases: ["Solenoids"]
topics: ["[[4.3 Индуктивность. Взаимоиндукция]]", "[[4.2 Сила Ампера]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Определить энергию поля, ЭДС и силу при взаимном перемещении двух соленоидов."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 9. SOLENOIDS (8 points)

**NbPhO 2015** · Международная олимпиада · теория · 10–12 класс · задача 9  
Источник: [[_pdf/NbPhO/nbpho-2015.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2015.pdf#page=7|решение, стр. 7–8]]

Темы: [[4.3 Индуктивность. Взаимоиндукция]], [[4.2 Сила Ампера]]

> [!abstract] Кратко (составлено моделью)
> Определить энергию поля, ЭДС и силу при взаимном перемещении двух соленоидов.

*(by S. Ainsaar).* A tightly-wound rigid solenoid coil has been partly inserted into another. They are connected to a constant current source so that the same current $I$ flows through them; both generate a magnetic field in the same direction. The solenoids have $N$ turns both, their length is $l$, their cross-sectional areas are $A_1$ and $A_2$. It may be assumed that $A_1,A_2\ll l^2$. You may find it useful to know that the magnetic field at the centre of one solenoid taken separately is $B=\mu_0IN/l$, where $\mu_0$ is the permeability of vacuum.

**i)** (2 points) The centres of the coils are at a distance $x<l$ along their common axis [$A_1,A_2\ll(x-l)^2,x^2$]. Find the total energy $E_m$ of the magnetic field in the system.

**ii)** (4 points) Find the electromotive forces $\mathcal E_1$ and $\mathcal E_2$ generated on the coils when one is pulled out with a speed $v$.

**iii)** (2 points) Find the force $F$ needed to pull one coil outwards.

> [!answer]- Ответ
> **i** — $E_m=\frac{B^2}{2\mu_0}(A_1l-A_2(l-x)+A_2x)+\frac{(2B)^2}{2\mu_0}A_2(l-x)=\frac{B^2}{2\mu_0}[A_1l+A_2(3l-2x)]=\frac{\mu_0I^2N^2}{2l^2}[A_1l+A_2(3l-2x)]$.
>
> **ii** — $\mathcal E_1=\dot\Phi_1=BA_2Nv/l=\mu_0A_2IN^2v/l^2$. The inner coil is also intersected by the flux $BA_2$, thus
>
> **ii** — $\mathcal E_2=\mathcal E_1$; those electromotive forces are in the same direction.
>
> **iii** — $F=-\frac{B^2A_2}{\mu_0}+\frac{2IBA_2N}{l}=\frac{\mu_0I^2N^2A_2}{l^2}$.

> [!solution]- Решение
> # 9. SOLENOIDS
>
> **i)** The overlapping region has magnetic field $2B$, rest of the coils’ insides has $B$. Let the inner coil have an area of $A_2$. Energy density, where the magnetic field is $B$, is $\frac{B^2}{2\mu_0}$. Therefore
> $E_m=\frac{B^2}{2\mu_0}(A_1l-A_2(l-x)+A_2x)+\frac{(2B)^2}{2\mu_0}A_2(l-x)=\frac{B^2}{2\mu_0}[A_1l+A_2(3l-2x)]=\frac{\mu_0I^2N^2}{2l^2}[A_1l+A_2(3l-2x)]$.
>
> **ii)** The outer coil is intersected by all the internal coil’s magnetic flux $BA_2$. After time $dt$ this flux is enclosed by fewer turns of the outer coil — by the $Nv\,dt/l$ turns that are on the length $v\,dt$. Thus the flux enclosed by the outer coil changes with a rate
> $\mathcal E_1=\dot\Phi_1=BA_2Nv/l=\mu_0A_2IN^2v/l^2$. The inner coil is also intersected by the flux $BA_2$, thus
> $\mathcal E_2=\mathcal E_1$; those electromotive forces are in the same direction.
>
> **iii)** The work done when pulling a coil out is balanced in two places: the magnetic field energy decreases and our constant current source dissipates some energy (because our electromotive forces work against it). In total, the applied mechanical power $Fv=\frac{dE_m}{dx}v+I(\mathcal E_1+\mathcal E_2)$, from where
> $F=-\frac{B^2A_2}{\mu_0}+\frac{2IBA_2N}{l}=\frac{\mu_0I^2N^2A_2}{l^2}$.
