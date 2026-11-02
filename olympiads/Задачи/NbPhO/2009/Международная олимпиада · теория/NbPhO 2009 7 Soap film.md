---
id: nbpho-2009-intl-theory-7
olympiad: NbPhO
year: 2009
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "7"
title: "Soap film"
points: 6
aliases: ["Soap film"]
topics: ["[[2.11 Поверхностное натяжение]]", "[[1.16 Закон сохранения импульса]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Оценить время разрушения мыльной плёнки по её толщине и поверхностному натяжению."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 7. Soap film (6 points)

**NbPhO 2009** · Международная олимпиада · теория · 10–12 класс · задача 7  
Источник: [[_pdf/NbPhO/nbpho-2009.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2009.pdf#page=4|решение, стр. 4]]

Темы: [[2.11 Поверхностное натяжение]], [[1.16 Закон сохранения импульса]]

> [!abstract] Кратко (составлено моделью)
> Оценить время разрушения мыльной плёнки по её толщине и поверхностному натяжению.

Lord Rayleigh had in 1891 a lecture about taking photos of physical processes. Among others, he showed a photo of a soap film, which is falling apart (see Fig.). Instead of a flash, he used an electric spark (well, nowadays the flashes are also based on electric sparks). Estimate, how precise must have been the timing, i.e. estimate the time for a soap film to fall apart. Let the thickness of the soap film be $h=1\,\mu\mathrm m$, the ring diameter $D=10\,\mathrm{cm}$ and the surface tension $\sigma=0.025\,\mathrm{N/m}$.

![[nbpho-2009-p2-c1133.png]]

*Hint:* you may use a model, according to which the already broken part of the soap film gathers into a single front and moves all together towards the still preserved part of the film.

> [!answer]- Ответ
> $t=D/v=\frac1{100}\,\mathrm s$.

> [!solution]- Решение
> # 7. Soap film (6 points)
>
> Suppose the area of a broken part of the soap film is $S$. The corresponding surface energy is $E_S=2\sigma S$. The mass of the soap water that was previously located at the broken part is $m=Sh\rho$, where $\rho=10^3\,\mathrm{kg/m^3}$. Assuming that the surface energy is transformed to the kinetic energy of the moving front, we get an equation for the speed of the front: $2\sigma S=\frac12mv^2$, $4\sigma S=Sh\rho v^2$. Therefore $v=\sqrt{\frac{4\sigma}{h\rho}}=\sqrt{\frac{4\cdot0.025}{10^{-6}\cdot10^3}}\,\mathrm{m/s}=10\,\mathrm{m/s}$ and we can estimate the time of breakup of the soap film to be
> $t=D/v=\frac1{100}\,\mathrm s$.
