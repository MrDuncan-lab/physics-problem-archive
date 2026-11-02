---
id: nbpho-2003-intl-theory-1
olympiad: NbPhO
year: 2003
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "1"
title: "Volleyball"
points: 8
aliases: ["Volleyball"]
topics: ["[[1.18 Гидростатика]]", "[[1.20 Колебания]]", "[[1.17 Законы сохранения энергии и импульса]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Найти силу сжатия, деформацию и время удара мяча с нерастяжимой оболочкой."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 1. Volleyball (8 points)

**NbPhO 2003** · Международная олимпиада · теория · 10–12 класс · задача 1  
Источник: [[_pdf/NbPhO/nbpho-2003.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2003.pdf#page=3|решение, стр. 3]]

Темы: [[1.18 Гидростатика]], [[1.20 Колебания]], [[1.17 Законы сохранения энергии и импульса]]

> [!abstract] Кратко (составлено моделью)
> Найти силу сжатия, деформацию и время удара мяча с нерастяжимой оболочкой.

Consider a simplified model of a volleyball: a thin spherical envelope filled with air. The envelope material is non-stretchable, easily foldable. The excess pressure inside the ball $\Delta p=20\,\mathrm{kPa}$, the ball radius $R=10\,\mathrm{cm}$ and mass $m=400\,\mathrm g$ (the air mass inside the ball is negligible). You can neglect the dependence of the excess pressure on the deformation of the ball.

**1)** The ball is pressed between two parallel rigid plates, the distance between of which is $2R-2h$ (so that the height of the deformed segments is $h=1\,\mathrm{cm}$). Find the force between the ball and a plate $N$.

**2)** Ball moves with velocity $v_0=2\,\mathrm{m/s}$ and hits a rigid wall. Find the maximal height of the deformed segment $h_m$ …

**3)** …and the collision time $\tau$.

**4)** For small excess pressures, the ball can lose its spherical shape even in those points, which are not in touch with the wall. Which condition between the quantities $\Delta p$, $R$, $m$ and $h$ has to be satisfied in order to ensure that such a loss of sphericity is negligible?

> [!answer]- Ответ
> **1** — $F=\Delta p\pi h(2R-h)\approx120\,\mathrm N$.
>
> **2** — $h=v\sqrt{m/2\pi R\Delta p}\approx11\,\mathrm{mm}$.
>
> **3** — $\tau=\pi\sqrt{m/2\pi R\Delta p}=\sqrt{\pi m/2R\Delta p}\approx18\,\mathrm{ms}$.

> [!solution]- Решение
> # 1. Volleyball (8 pts)
>
> **1)** $F=\Delta pS$, where $S=\pi r^2$ is the segment base surface. It is easy to see that $r^2=(2R-h)h$, hence
> $F=\Delta p\pi h(2R-h)\approx120\,\mathrm N$.
>
> **2)** During the collision the ball is deformed as shown in Figure: the envelope is not stretchable, hence it retains the spherical shape (except where in touch with the wall). Using the approximation $h\ll R$ we can neglect the term $h^2$ in the expression for the force. Then, the force is proportional to $h$, ie. the ball behaves as a spring of stiffness $k=2\pi R\Delta p$. According to the energy conservation law $mv^2=2\pi R\Delta p h^2$, hence
> $h=v\sqrt{m/2\pi R\Delta p}\approx11\,\mathrm{mm}$.
>
> ![[nbpho-2003-p3-c0142.png]]
>
> **3)** This is the half of the harmonic oscillations period,
> $\tau=\pi\sqrt{m/2\pi R\Delta p}=\sqrt{\pi m/2R\Delta p}\approx18\,\mathrm{ms}$.
>
> **4)** Let us use the ball’s system of reference. The envelope surface element $dS$ is exerted by the force of inertia $dF_i=amdS/4\pi R^2$, where $a=\Delta p\pi h(2R-h)/m$. Thus, $dF_i=\Delta p h(2R-h)dS/4R^2$. In order to keep the spherical shape, this force has to be compensated by the force due to the excess pressure $dF_r=\Delta p dS$, hence
> $h(2R-h)<4R^2$. This condition is always satisfied, no additional constraint is needed. Notice that we considered only the worst case requiring the largest compensating force when the force of inertia is normal to the surface. Remark: The case of stretchable envelope is completely different, sphericity disappears over all the surface (try to press a balloon against a glass!).
