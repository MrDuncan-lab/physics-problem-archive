---
id: belpho-2002-final-theory-11-3
olympiad: BelPhO
year: 2002
stage: "Заключительный этап"
round: теория
grade: 11
number: "11-3"
title: "Задача 11-3"
aliases: ["Задача 11-3"]
topics: ["[[6.5 Волновая оптика]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Найти групповую скорость огибающей амплитудно-модулированного радиосигнала в диспергирующей среде."
status: "проверено: сверка"
lang: ru
tags: [задача]
---

# 3.

**BelPhO 2002** · Заключительный этап · теория · 11 класс · задача 11-3  
Источник: [[_pdf/BelPhO/2002-final-theoretical-problems.pdf#page=5|условие, стр. 5]] · [[_pdf/BelPhO/2002-final-theoretical-solutions.pdf#page=14|решение, стр. 14–15]]

Темы: [[6.5 Волновая оптика]]

> [!abstract] Кратко (составлено моделью)
> Найти групповую скорость огибающей амплитудно-модулированного радиосигнала в диспергирующей среде.

Простейший модулированный радиосигнал может быть описан функцией $E=E_0\cos\omega_0t(1+a\cos\omega_1t)$, где $\omega_0$ — несущая частота, $\omega_1$ — частота модуляции (частота полезного сигнала), причем $\omega_0\gg\omega_1$, $a,E_0$ — постоянные величины, определяющие амплитуду и глубину модуляции сигнала. Скорость распространения электромагнитной волны $c$ зависит от ее частоты (из-за дисперсии) по приближенному закону $c(\omega)=c_0-\gamma(\omega-\omega_0)$, где $c_0$ — скорость распространения волны с частотой $\omega_0$, $\gamma$ — известная малая постоянная $(c_0\gg\gamma\omega_0)$. Определите скорость распространения полезного сигнала (скорость распространения огибающей) в данных условиях.

*Подсказки*

$$
\cos A+\cos B=2\cos\frac{A+B}{2}\cos\frac{A-B}{2};
$$

$$
2\cos A\cos B=\cos(A+B)+\cos(A-B).
$$

> [!answer]- Ответ
> $$
> c=\frac xt=\frac{\omega_1}{\dfrac{\omega_0}{c_0}\left(\dfrac{\omega_1}{\omega_0}+\gamma\dfrac{\omega_1}{c_0}\right)}=\frac{c_0}{1+\gamma\dfrac{\omega_0}{c_0}}\approx c_0\left(1-\gamma\frac{\omega_0}{c_0}\right).
> $$

> [!solution]- Решение
> # 3.
>
> Представим сигнал в виде суммы трех гармонических составляющих
>
> $$
> \begin{aligned}
> E&=E_0\cos\omega_0t(1+a\cos\omega_1t)=\\
> &=E_0\cos\omega_0t+\frac{aE_0}{2}\cos(\omega_0-\omega_1)t+\frac{aE_0}{2}\cos(\omega_0+\omega_1)t.
> \end{aligned}
> \tag{1}
> $$
>
> Распространение монохроматической волны в пространстве вдоль оси $x$ описывается функцией
>
> $$
> E(t,x)=E_0\cos\left(\omega t-\frac{2\pi}{\lambda}x\right)=E_0\cos\left(\omega t-\frac{\omega}{c}x\right),
> \tag{2}
> $$
>
> где $c$ — скорость распространения волны с частотой $\omega$. Применим эту формулу к сигналу (1), учитывая формулу для скорости распространения волн
>
> $$
> \begin{aligned}
> E(t,x)&=E_0\cos\left(\omega_0t-\frac{\omega_0}{c_0}x\right)\omega_0t+\\
> &+\frac{aE_0}{2}\cos\left((\omega_0-\omega_1)t-\frac{(\omega_0-\omega_1)x}{c_0+\gamma\omega_1}\right)+\frac{aE_0}{2}\cos\left((\omega_0+\omega_1)t-\frac{(\omega_0+\omega_1)x}{c_0-\gamma\omega_1}\right)
> \end{aligned}
> $$
>
> Далее упростим это выражение, используя малость величин $\dfrac{\omega_1}{\omega_0},\dfrac{\gamma\omega_1}{c_0}\ll1$. Тогда
>
> $$
> \frac{(\omega_0-\omega_1)x}{c_0+\gamma\omega_1}=\frac{x\omega_0}{c_0}\cdot\frac{1-\dfrac{\omega_1}{\omega_0}}{1+\gamma\dfrac{\omega_1}{c_0}}\approx\frac{x\omega_0}{c_0}\left(1-\frac{\omega_1}{\omega_0}-\gamma\frac{\omega_1}{c_0}\right);
> $$
>
> $$
> \frac{(\omega_0+\omega_1)x}{c_0-\gamma\omega_1}\approx\frac{x\omega_0}{c_0}\left(1+\frac{\omega_1}{\omega_0}+\gamma\frac{\omega_1}{c_0}\right);
> $$
>
> Воспользуемся теперь обратным преобразованием от суммы косинусов к их произведению
>
> $$
> E(t,x)=E_0\cos\left(\omega_0t-\frac{\omega_0}{c_0}x\right)\left(1+a\cos\left(\omega_1t-\frac{\omega_0}{c_0}x\left(\frac{\omega_1}{\omega_0}+\gamma\frac{\omega_1}{c_0}\right)\right)\right).
> $$
>
> Скорость распространения сигнала можно найти из условия постоянства фазы (полагая ее равной, например, нулю). Окончательно получаем, что искомая скорость распространения огибающей (полезного сигнала)
>
> $$
> c=\frac xt=\frac{\omega_1}{\dfrac{\omega_0}{c_0}\left(\dfrac{\omega_1}{\omega_0}+\gamma\dfrac{\omega_1}{c_0}\right)}=\frac{c_0}{1+\gamma\dfrac{\omega_0}{c_0}}\approx c_0\left(1-\gamma\frac{\omega_0}{c_0}\right).
> $$
