---
id: iepho-2013-intl-experiment-10-t2-1
olympiad: IEPhO
year: 2013
stage: "Международная олимпиада"
round: эксперимент
grade: 10
number: "10-T2-1"
title: "Определите силу трения между поршнем и цилиндром шприца"
aliases: ["Определите силу трения между поршнем и цилиндром шприца"]
topics: ["[[1.10 Статика]]", "[[7 Эксперименты]]"]
difficulty: 3
has_solution: true
has_hints: false
has_grading: true
source_damaged: false
summary: "Определить силу трения между поршнем и цилиндром шприца."
status: "проверено: сверка"
lang: ru
tags: [задача]
---

# Определите силу трения между поршнем и цилиндром шприца.

**IEPhO 2013** · Международная олимпиада · эксперимент · 10 класс · задача 10-T2-1  
Источник: [[_pdf/IEPhO/2013/2013-IEPhO-10-2tour_1-problem.pdf#page=1|условие, стр. 1]] · [[_pdf/IEPhO/2013/2013-IEPhO-10-2tour_1-solution.pdf#page=2|решение, стр. 2]] · [[_pdf/IEPhO/2013/2013-IEPhO-10-2tour_1-solution.pdf#page=3|критерии, стр. 3]]

Темы: [[1.10 Статика]], [[7 Эксперименты]]

> [!abstract] Кратко (составлено моделью)
> Определить силу трения между поршнем и цилиндром шприца.

Оцените погрешность измерения.

Оборудование: Линейка, шприц.

Температура на улице 0 °C, влажность 93%, давление воздуха 98,4 кПа, температура в комнате 20 °C.

> [!answer]- Ответ
> $$
> F_\mu=(0{,}95\pm0{,}17)N
> $$

> [!solution]- Решение
> After the syringes end is closed by the finger then:
>
> ![[iepho-2013-10-t2-1-solutions-p2-f1.png]]
>
> When the syringe is pressed an then released it will not return to the initial position but stays in:
>
> ![[iepho-2013-10-t2-1-solutions-p2-f2.png]]
>
> Where the friction force $F_\mu$ is equal to force from the pressure difference $F_{\Delta p}$:
>
> $$|F_\mu|=|F_{\Delta p}|=S\Delta p=S(p_1-p_0)=\frac{V_0}{l_0}p_0\frac{V_0-V_1}{V_1}$$
>
> as $S=V_0/l_0$ and when $T=\mathrm{const.}$ (moves have to be slow enough tor the isotherm)
>
> $$pV=\frac{m}{\mu}RT=const$$
>
> and therefore
>
> $$p_0V_0=p_1V_1\quad\text{and}\quad p_1=p_0\frac{V_0}{V_1}$$
>
> so one sets the initial volume to $V_0=(100{,}0\pm0{,}5)\cdot10^{-2}ml=(100{,}0\pm0{,}5)\cdot10^{-8}m^3$ (to be exact you have to choose the maximum value)
>
> what gives the value $l_0=(56{,}5\pm0{,}5)mm=(0{,}0565\pm0.0005)m$
>
> The value $p_0=98{,}4\,kPa$ is given.
>
> For the $V_1$ one repeats the measurements for the 11 times and finds the mean $V_1$ and the standard deviation $\sigma V_1$
>
> $$V_1\in(65;63;65;65;64;65;67;65;67;61;64)\cdot10^{-8}m^3$$
>
> $$\overline{V_1}=64{,}6\cdot10^{-8}m^3\quad\text{and}\quad\Delta V_1\approx2\sigma V_1=3{,}4\cdot10^{-8}m^3$$
>
> $$F_\mu=\frac{V_0}{l_0}p_0\frac{V_0-V_1}{V_1}=0{,}95\,N$$
>
> for the error values the error formula gives
>
> $$\frac{\Delta F_\mu}{F_\mu}=\frac{\Delta V_0+\Delta V_1}{V_0-V_1}+\frac{\Delta V_1}{V_1}+\frac{\Delta V_0}{V_0}+\frac{\Delta l_0}{l_0}=0{,}176$$
>
> and therefore
>
> $$\Delta F_\mu=0{,}176*0{,}95N=0{,}17N$$
>
> $$F_\mu=(0{,}95\pm0{,}17)N$$

> [!grading]- Критерии оценивания
> **КРИТЕРИИ**
>
> | код работы | | | |
> |---|---|---|---|
> | идея затыкать шприц пальцем | | | 0,2 |
> | замечен гистерезис сил | | | 0,3 |
> | измерение величины гистерезиса | | | 1,2 |
> | применяет полную шкалу шприца | | | 0,6 |
> | правильно находит S | | | 1,2 |
> | учитывает изотермичность процесса | | | 0,8 |
> | повторы и усреднение | 3 | 0,4 | 1 |
> | | 5 | 0,6 | |
> | | 10 | 0,8 | |
> | | усреднение | 0,2 | |
> | вывод формулы | $F_\mu=...$ | 0,8 | 2 |
> | | T=const | 0,4 | |
> | | PV=const | 0,4 | |
> | | $F_\mu=F_{\Delta p}$ | 0,4 | |
> | ответ правильный для данного шприца по измерениям | 0,3 – 1,5 N | 1 | 1,2 |
> | | единица | 0,2 | |
> | погрешность | $\Delta V_0$ | 0,2 | 1,5 |
> | | $\Delta l_0$ | 0,2 | |
> | | $\Delta V_1$ | 0,5 | |
> | | $\Delta F_\mu$ | 0,6 | |
> | | | | 10 |
