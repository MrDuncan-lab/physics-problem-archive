---
id: nbpho-2013-intl-theory-4
olympiad: NbPhO
year: 2013
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "4"
title: "Magnetic dipoles"
points: 7
aliases: ["Magnetic dipoles"]
topics: ["[[4.2 Сила Ампера]]", "[[2.12 Молекулярно-кинетическая теория]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Исследовать равновесие магнитного диполя и намагниченность системы электронных спинов."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 4. MAGNETIC DIPOLES (7 points)

**NbPhO 2013** · Международная олимпиада · теория · 10–12 класс · задача 4  
Источник: [[_pdf/NbPhO/nbpho-2013.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2013.pdf#page=4|решение, стр. 4]]

Темы: [[4.2 Сила Ампера]], [[2.12 Молекулярно-кинетическая теория]]

> [!abstract] Кратко (составлено моделью)
> Исследовать равновесие магнитного диполя и намагниченность системы электронных спинов.

Let us consider the following model for a magnetic dipole. Some wire with no resistance has been bent into the shape of a square with side length $a$. At some point on the wire is a small ideal current source that keeps current $I$ flowing in the circuit in all situations. The magnetic moment $m$ of a planar circuit is given by the relation $m=IA$, with vector $\vec m$ pointing in the normal direction of the circuit according to the right hand rule ($A$ is the area bounded by the circuit).

**i)** (3 points) The dipole is placed inside a homogeneous magnetic field $\vec B$, so that the angle between $\vec m$ and $\vec B$ is $\theta$. Find the angles $\theta_s$ and $\theta_u$ that correspond to stable and unstable equilibria, respectively. Calculate the amount of work ($w$) needed to rotate the dipole from $\theta_s$ to $\theta_u$. Give your answer in terms of $m$ and $B$.

We can use this model to calculate the magnetic properties of materials containing unpaired electrons that have negligibly weak interactions with one another. Let us consider a sample of material with $n$ such unpaired electrons per unit volume, placed inside a homogeneous magnetic field $\vec B$. Due to spin, each unpaired electron acts as a small magnetic dipole. However, owing to the quantum nature of the electron, the projection of its magnetic moment along $\vec B$ can only be $\mu_B$ or $-\mu_B$ ($\mu_B$ is called the Bohr magneton).

**ii)** (4 points) Calculate $M$, the magnetic moment per unit volume of the sample, if the temperature of the material is $T$ and the external magnetic field is $B$.

> [!answer]- Ответ
> **i** — $\theta_s=0$ and
>
> **i** — $w=2Bm$.
>
> **ii**
>
> $$
> M=\mu_BN\frac{1-\exp\left(\frac{2\mu_BB}{k_BT}\right)}{1+\exp\left(\frac{2\mu_BB}{k_BT}\right)}=\mu_Bn\tanh\left(\frac{\mu_BB}{k_BT}\right).
> $$

> [!solution]- Решение
> # 4. MAGNETIC DIPOLES (7 points)
>
> **i)** (3 points) There is no torque on the square if $\theta=0$ or $\theta=\pi$, so one of them is stable and the other unstable. If we start from $\theta=0$ and turn the square to some $\theta$, but keep two sides of the square perpendicular to $\vec B$, Lorentz forces on these two sides give a torque $\tau=-BIa\cdot a\sin\theta=-Bm\sin\theta$ towards decreasing $\theta$. By symmetry, we get the same result if we keep the other keep two sides of the square perpendicular to $\vec B$. It is possible to conclude that the torque depends only on $\theta$ (at least near $\theta=0$), not on the exact orientation of the square. Since torque acts to restore $\theta=0$, we find that
> $\theta_s=0$ and
> $\theta_u=\pi$. To find the work to get from $\theta_s$ to $\theta_u$, we can again keep two sides perpendicular to $\vec B$ - the answer cannot depend on the path, so we choose the simplest one. Integrating $\tau=Bm\sin\theta$ from $\theta=0$ to $\pi$ gives us
> $w=2Bm$.
>
> **ii)** (4 points) Let us denote the number of electrons (per unit volume) with magnetic moment projection $+\mu_B$ as $n_+$ and the ones with $-\mu_B$ as $n_-$. Their sum is always the same, $n_++n_-=n$. Also, in thermal equilibrium, their ratio is given by $\frac{n_-}{n_+}=\exp\left(-\frac{2\mu_BB}{k_BT}\right)$, where $k_B$ is Boltzmann’s constant. Solving the equations, we can find $n_+$ and $n_-$. The total magnetic moment per unit volume (in the direction of $\vec B$) is given by $M=\mu_B(n_+-n_-)$. After substituting,
>
> $$M=\mu_BN\frac{1-\exp\left(\frac{2\mu_BB}{k_BT}\right)}{1+\exp\left(\frac{2\mu_BB}{k_BT}\right)}=\mu_Bn\tanh\left(\frac{\mu_BB}{k_BT}\right).$$
>
> *Additional comments.* We see $B$ and $M$ always have the same sign, therefore $\vec M$ is parallel with $\vec B$. This makes sense, as we saw that $\theta=0$ ($\vec m$ parallel to $\vec B$) orientation had lowest energy. The graph of $M$ vs $B$ goes to $\mu_Bn$ for very large $B$ or to $-\mu_Bn$ for very small $B$ (all spins aligned with $\vec B$). At $B=0$, $M=0$ as well, since both spin orientations have the same energy. Around zero, the curve is linear, as $\tanh x\approx x$ for small $x$ gives us $M\approx\frac{\mu_B^2nB}{k_BT}$.
