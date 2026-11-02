---
id: nbpho-2009-intl-theory-10
olympiad: NbPhO
year: 2009
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "10"
title: "Wedge"
points: 5
aliases: ["Wedge"]
topics: ["[[1.13 Кинематические связи (и динамика)]]", "[[1.12 Теорема о движении центра масс]]"]
difficulty: 3
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Найти время соскальзывания бруска по свободно движущемуся клину."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 10. Wedge (5 points)

**NbPhO 2009** · Международная олимпиада · теория · 10–12 класс · задача 10  
Источник: [[_pdf/NbPhO/nbpho-2009.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2009.pdf#page=4|решение, стр. 4]]

Темы: [[1.13 Кинематические связи (и динамика)]], [[1.12 Теорема о движении центра масс]]

> [!abstract] Кратко (составлено моделью)
> Найти время соскальзывания бруска по свободно движущемуся клину.

A wedge of mass $M$ is kept at rest on an horizontal surface, and a block of mass $m$ is kept on the wedge at the height $h$ from the surface. The angle of the wedge is $\alpha$, see Fig. There is no friction neither between the block and wedge nor between the surface and the wedge. The system is released into a free motion. Find the time $t$ needed for the block to reach the surface.

![[nbpho-2009-p2-c5754.png]]

> [!answer]- Ответ
> $$
> t=\sqrt{\frac{2\beta h}{g}}=\sqrt{\frac{2h}{g}\left(\frac M{M+m}\cot^2\alpha+1\right)}.
> $$

> [!solution]- Решение
> # 10. Wedge (5 points)
>
> The center of mass of the system doesn’t move, therefore $Mu=mv_h$, where $u$ and $v_h$ are the horizontal components of the velocities of the wedge and block in the lab frame at some instant of time. In the wedge’s frame, the block has horizontal velocity $v'=v_h+u=v_h(1+\frac mM)$. Since the block is sliding down the wedge, the vertical component of the block has to be $v_\downarrow=v'\tan\alpha$. The total kinetic energy in the lab frame $E_K=\frac12(Mu^2+mv_h^2+mv_\downarrow^2)$. Substituting the relevant quantities and simplifying, we obtain
> $$E_k=\frac m2v_\downarrow^2\beta,\quad\text{where }\beta\equiv\frac M{M+m}\cot^2\alpha+1.$$
> The kinetic energy equals to the change in potential energy: $\frac m2\beta v_\downarrow^2=\Delta E_P=mg(h-h')$. By differentiating and noting that $dh=dt\cdot v_\downarrow$, we get $\beta dv_\downarrow=gdt$, $t=\frac\beta g v_{\downarrow\max}$. From the above written energy conservation law we get $v_{\downarrow\max}=\sqrt{\frac{2gh}{\beta}}$; so we finally have
>
> $$t=\sqrt{\frac{2\beta h}{g}}=\sqrt{\frac{2h}{g}\left(\frac M{M+m}\cot^2\alpha+1\right)}.$$
