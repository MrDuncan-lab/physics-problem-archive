---
id: nbpho-2013-intl-theory-e1
olympiad: NbPhO
year: 2013
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "E1"
title: "Friction of a string"
points: 8
aliases: ["Friction of a string"]
topics: ["[[7 Эксперименты]]", "[[1.10 Статика]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Измерить коэффициент трения нити о ручку и оценить погрешность."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 5. FRICTION OF A STRING (8 points)

**NbPhO 2013** · Международная олимпиада · теория · 10–12 класс · задача E1  
Источник: [[_pdf/NbPhO/nbpho-2013.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2013.pdf#page=4|решение, стр. 4]]

Темы: [[7 Эксперименты]], [[1.10 Статика]]

> [!abstract] Кратко (составлено моделью)
> Измерить коэффициент трения нити о ручку и оценить погрешность.

Measure the dynamic coefficient of friction $\mu_1$ between the ballpoint pen and the string. Estimate the uncertainty. It might help that the dynamic coefficient of friction between the pencil and the same string was measured beforehand and $\mu_2=0.20\pm0.01$ was obtained.

*Equipment:* dynamometer, string, ballpoint pen, pencil and weight.

> [!solution]- Решение
> # 5. FRICTION OF A STRING (8 points)
>
> Let’s first calculate the difference of tension force $T$ between two ends of a sliding string arced over a cylinder by an angle $\alpha$. Furthermore, let’s look at a short piece of the arc that subtends an angle $d\alpha$. On one hand, $dT=\mu\,dR$ is the friction force acting on the piece, where $dR$ is the reaction force. On the other hand, $dR\approx T\,d\alpha$, because both ends of the piece are pulled by a force with a radial component of $T\frac{d\alpha}{2}$ (where $\alpha$ is measured in radians). Therefore, we get a differential equation: $dT=\mu T\,d\alpha$ or $d\ln T=\mu\,d\alpha$, whence $T=T_0e^{\mu\alpha}$.
>
> As a solution to the problem, we can measure the change of the tension force for different angles $\alpha$ (for example, $\frac\pi2$, $\pi$, $\frac{3\pi}2$, $2\pi$, $\frac{5\pi}2$ etc. for several turns; however, keeping the strings vertical offers better precision) and plot $\ln T$ with respect to $\alpha$. The slope of the graph is the $\mu$ to be measured.
>
> *Extra solution (not as exact).* Those who cannot derive the necessary formula can still do the experiment by doing the same measurements and noting from the plot that the relationship between $\alpha$ and $T$ looks exponential. Thus, we can make an ansatz that $T=T_0X^{\mu\alpha}$: as $\alpha=0$ must correspond to $T=T_0$, we cannot reasonably write the $\mu$ anywhere else without over-complicating the formula. Now, we can re-measure the given pencil (it may be reasonably enough approximated with a cylinder here; more exact approaches exist) and conclude that $X\approx2.7$. From there on, the calculation is the same.
