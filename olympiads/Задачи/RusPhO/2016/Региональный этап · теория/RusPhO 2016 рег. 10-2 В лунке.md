---
id: ruspho-2016-region-theory-10-2
olympiad: RusPhO
year: 2016
stage: "Региональный этап"
round: теория
grade: 10
number: "10-2"
title: "В лунке"
aliases: ["В лунке"]
topics: ["[[1.13 Кинематические связи (и динамика)]]", "[[1.6 Векторная кинематика]]"]
difficulty: 3
has_solution: true
has_hints: false
has_grading: true
source_damaged: false
summary: "Найти скорость свободного конца стержня в зависимости от наклона, когда другой конец равномерно движется по полусферической лунке."
status: "проверено: сверка"
lang: ru
tags: [задача]
---

# 2. В лунке

**RusPhO 2016** · Региональный этап · теория · 10 класс · задача 10-2  
Источник: [[_pdf/RusPhO/2016-region-theor.pdf#page=23|условие, стр. 23]] · [[_pdf/RusPhO/2016-region-theor.pdf#page=23|решение, стр. 23]] · [[_pdf/RusPhO/2016-region-theor.pdf#page=24|критерии, стр. 24]]

Темы: [[1.13 Кинематические связи (и динамика)]], [[1.6 Векторная кинематика]]

> [!abstract] Кратко (составлено моделью)
> Найти скорость свободного конца стержня в зависимости от наклона, когда другой конец равномерно движется по полусферической лунке.

Стержень $AB$ касается уступа $K$ полусферической лунки радиуса $R$. Точка $A$ движется равномерно со скоростью $\upsilon$ по поверхности лунки, начиная из нижней точки $N$, к точке $M$. Найти зависимость модуля скорости $u$ конца стержня $B$ от угла $\alpha$, который стержень составляет с горизонтом. Длина стержня $AB$ равна $2R$.

![[ruspho-2016-region-theory-p23-f1.png]]

> [!answer]- Ответ
> $$
> u = \sqrt{u_\parallel^2 + u_\perp^2} = \sqrt{\upsilon^2(\sin\alpha)^2 + \upsilon^2(1-\cos\alpha)^2} = \upsilon\sqrt{2(1-\cos\alpha)} = 2\upsilon\sin\left(\frac{\alpha}{2}\right).
> $$
>
> $$
> \begin{aligned}
> u &= \omega\cdot BL = \frac{\upsilon}{2R}\sqrt{(KL)^2+(BK)^2} = \frac{\upsilon}{2R}\sqrt{(2R\sin\alpha)^2+(2R-2R\cos\alpha)^2} = {}\\
> &= \upsilon\sqrt{2(1-\cos\alpha)} = 2\upsilon\sin\left(\frac{\alpha}{2}\right).
> \end{aligned}
> $$

> [!solution]- Решение
> ## Возможное решение 1
>
> **Бычков А.**
>
> Скорость точки стержня, касающейся уступа $K$, направлена вдоль стержня и, следовательно, она равна $\upsilon\sin\alpha$. Так как стержень жёсткий, то проекции скоростей остальных точек стержня на направление вдоль стержня также равны $\upsilon\sin\alpha$, значит, $u_\parallel = \upsilon\sin\alpha$.
>
> ![[ruspho-2016-region-theory-p23-f2.png]]
>
> Перпендикулярные составляющие скоростей линейно возрастают с расстоянием от точки $K$. Тогда
>
> $$
> \frac{u_\perp}{BK} = \frac{\upsilon\cos\alpha}{KA} \Rightarrow u_\perp = \upsilon\cos\alpha\frac{2R - 2R\cos\alpha}{2R\cos\alpha} = \upsilon(1 - \cos\alpha).
> $$
>
> Скорость точки $B$ стержня равна:
>
> $$
> u = \sqrt{u_\parallel^2 + u_\perp^2} = \sqrt{\upsilon^2(\sin\alpha)^2 + \upsilon^2(1-\cos\alpha)^2} = \upsilon\sqrt{2(1-\cos\alpha)} = 2\upsilon\sin\left(\frac{\alpha}{2}\right).
> $$
>
> ## Возможное решение 2.
>
> Мгновенный центр вращения (точка $L$) стержня находится на верхней полуокружности $KLM$, как показано на рисунке. При движении стержня точка $L$ перемещается по дуге этой полуокружности.
>
> ![[ruspho-2016-region-theory-p23-c5961.png]]
>
> Угловая скорость вращения стержня равна: $\omega = \upsilon/(2R)$. Тогда скорость конца стержня $B$ равна:
>
> $$
> \begin{aligned}
> u &= \omega\cdot BL = \frac{\upsilon}{2R}\sqrt{(KL)^2+(BK)^2} = \frac{\upsilon}{2R}\sqrt{(2R\sin\alpha)^2+(2R-2R\cos\alpha)^2} = {}\\
> &= \upsilon\sqrt{2(1-\cos\alpha)} = 2\upsilon\sin\left(\frac{\alpha}{2}\right).
> \end{aligned}
> $$

> [!grading]- Критерии оценивания
> | Пункт | Содержание | Баллы |
> | --- | --- | --- |
> | 1. | Указано, что в силу недеформируемости стержня проекции скоростей $u$ и $\upsilon$ на направление вдоль стержня одинаковы $(u_\parallel = \upsilon_\parallel)$ **или** найдено положение мгновенного центра вращения | 3 балла |
> | 2. | Указано, что угол $BAL$ равен $\alpha$ | 1 балл |
> | 3. | Найдена связь между проекциями скоростей $u$ и $\upsilon$ на направление перпендикулярно стержню $(u_\perp/BK = \upsilon_\perp AK)$ **или** найдена угловая скорость $\omega$ | 2 балла |
> | 4. | Выражены длины $AK$ и $KB$ через угол $\alpha$ и радиус | (1+1) балла |
> | 5. | Получен ответ | 2 балла |
