---
id: nbpho-2015-intl-theory-e2
olympiad: NbPhO
year: 2015
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "E2"
title: "Vapour pressure"
points: 8
aliases: ["Vapour pressure"]
topics: ["[[7 Эксперименты]]", "[[2.10 Насыщенный пар]]", "[[2.2 Уравнение состояния идеального газа]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Измерить давление насыщенного пара неизвестной жидкости и оценить погрешность."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 10. VAPOUR PRESSURE (8 points)

**NbPhO 2015** · Международная олимпиада · теория · 10–12 класс · задача E2  
Источник: [[_pdf/NbPhO/nbpho-2015.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2015.pdf#page=8|решение, стр. 8]]

Темы: [[7 Эксперименты]], [[2.10 Насыщенный пар]], [[2.2 Уравнение состояния идеального газа]]

> [!abstract] Кратко (составлено моделью)
> Измерить давление насыщенного пара неизвестной жидкости и оценить погрешность.

*(by J. Kalda, M. Heidelberg, E. Uustalu)*

Measure the room temperature saturated vapour pressure of the unknown fluid in the syringe. The volume of the bottle is $V=0.50\ell$, the inner diameter of the pipe is $d=6.0\mathrm{mm}$. Current air pressure $p_0$ and room temperature $T_0$ are written on the blackboard. There is no need to repeat the measurement after a successful attempt as getting the bottle free from vapours is time consuming. Estimate the uncertainty of the result.

*Equipment:* syringe with an unknown fluid, syringe with water, bottle, flexible pipe, ruler, plug, stand, tape.

> [!answer]- Ответ
> $p_x=(p_0+\Delta p)\frac{n_n}{1+n_n}$.
>
> $p_x=6.52\mathrm{kPa}$ at $21.6^\circ\mathrm{C}$. However, the grading scheme was not insistent on the exact value as it proved technically quite difficult to get it correct.

> [!solution]- Решение
> # 10. VAPOUR PRESSURE
>
> We construct a manometer by fixing the pipe into a “U” shape using the stand, and filling the tube partially with water. With a small trouble we should get the water to the bottom of “U” shape and then we can measure the pressure difference from differences of depth $\Delta p=\rho g\Delta h$. After we attach a bottle to one end, we should let the pressures equalise through a needle hole in the bottle. We then squirt the unknown liquid to the bottle and close the needle hole with tape as fast as possible. We then shake the bottle to hasten the vaporisation and write down the difference of depths $\Delta h$ after it has reached a stable value. During all this we should be careful to heat the bottle with our body as little as possible.
>
> If the volume would have been fixed we would get the vapour pressure directly from the manometer reading as according to Dalton’s law. But since the diameter of the pipe was not that small we should take the relative volume increase to account.
>
> If the depth difference is $\Delta h$, we have a relative increase of pressure $n_p=\frac{\rho g\Delta h}{p_0}$ and a relative increase of volume $n_V=\frac{S\Delta h}{2V_0}$. Assuming an ideal gas, this gives us relative molar increase $n_n=\frac{(1+n_p)(1+n_V)p_0V_0-p_0V_0}{p_0V_0}\approx n_p+n_V$. Substituting in the given values we get $n_n\approx0.0987\mathrm{m}^{-1}\times h+0.00471\mathrm{m}^{-1}\times h\approx0.1034\mathrm{m}^{-1}\times h$.
>
> Since all the molar increase is due to the vapour, we can get the vapour pressure (partial pressure exerted by vapour) by multiplying the pressure with the molar fraction of vapour
> $p_x=(p_0+\Delta p)\frac{n_n}{1+n_n}$.
>
> The unknown liquid was ethanol with vapour pressure of
> $p_x=6.52\mathrm{kPa}$ at $21.6^\circ\mathrm{C}$. However, the grading scheme was not insistent on the exact value as it proved technically quite difficult to get it correct.
