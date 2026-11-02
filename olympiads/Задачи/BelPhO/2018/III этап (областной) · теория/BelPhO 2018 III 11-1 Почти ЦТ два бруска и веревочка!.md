---
id: belpho-2018-iii-theory-11-1
olympiad: BelPhO
year: 2018
stage: "III этап (областной)"
round: теория
grade: 11
number: "11-1"
title: "Почти ЦТ: два бруска и веревочка!"
aliases: ["Почти ЦТ: два бруска и веревочка!"]
topics: ["[[1.10 Статика]]"]
difficulty: 3
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Определить натяжение массивной верёвки между брусками и минимальные силы начала движения одного и обоих брусков."
status: "проверено: сверка"
lang: ru
tags: [задача]
---

# Задача 11-1 Почти ЦТ: два бруска и веревочка!

**BelPhO 2018** · III этап (областной) · теория · 11 класс · задача 11-1  
Источник: [[_pdf/BelPhO/2018-III-theoretical-problems.pdf#page=14|условие, стр. 14]] · [[_pdf/BelPhO/2018-III-theoretical-solutions.pdf#page=13|решение, стр. 13]]

Темы: [[1.10 Статика]]

> [!abstract] Кратко (составлено моделью)
> Определить натяжение массивной верёвки между брусками и минимальные силы начала движения одного и обоих брусков.

На горизонтальной поверхности покоятся два одинаковых бруска, масса каждого равна $m$. Коэффициент трения брусков о поверхность равен $\mu$. Бруски связаны «веревочкой», масса которой равна $m_0$ (и сравнима с массой брусков). Бруски находятся в состоянии покоя на максимально возможном расстоянии друг от друга.

![[belpho-2018-iii-theory-problems-p14-f1.png]]

**1.** Под каким углом $\alpha$ к горизонту направлена веревка в месте крепления ее к брускам?

**2.** Чему равна сила натяжения веревки в точке крепления?

**3.** К одному из брусков прикладывают постоянную горизонтально направленную силу $F$. Какую силу минимальную $F_1$ следует приложить, чтобы сдвинуть один брусок? Какую силу $F_2$ следует приложить, чтобы сдвинуть два бруска?

> [!answer]- Ответ
> **1, 2**
>
> $$
> \begin{cases}T\cos\alpha=\mu\left(mg+\frac{m_0g}{2}\right)\\T\sin\alpha=\frac{m_0g}{2}\end{cases}\quad\Rightarrow\quad\begin{cases}tg\alpha=\frac{m_0}{\mu(2m+m_0)}\\T=\sqrt{\mu^2\left(mg+\frac{m_0g}{2}\right)^2+\left(\frac{m_0g}{2}\right)^2}\end{cases}
> $$
>
> **3**
>
> $$
> F>T\cos\alpha+\mu\left(mg+\frac{m_0g}{2}\right)=\mu\left(mg+\frac{m_0g}{2}\right)+\mu\left(mg+\frac{m_0g}{2}\right)=\mu g(2m+m_0)
> $$

> [!solution]- Решение
> # Задача 11-1 Почти ЦТ: два бруска и веревочка!
>
> Условия равновесия веревки:
>
> $$2T\sin\alpha=m_0g \tag{1}$$
>
> Условия предельного положения грузов:
>
> $$T\cos\alpha=\mu(mg+T\sin\alpha). \tag{2}$$
>
> Из этих уравнений находим
>
> $$\begin{cases}T\cos\alpha=\mu\left(mg+\frac{m_0g}{2}\right)\\T\sin\alpha=\frac{m_0g}{2}\end{cases}\quad\Rightarrow\quad\begin{cases}tg\alpha=\frac{m_0}{\mu(2m+m_0)}\\T=\sqrt{\mu^2\left(mg+\frac{m_0g}{2}\right)^2+\left(\frac{m_0g}{2}\right)^2}\end{cases} \tag{3}$$
>
> Чтобы сдвинуть брусок
>
> $$\begin{cases}F>T\cos\alpha+\mu(mg+T\sin\alpha)\\2T\sin\alpha=m_0g\end{cases}$$
>
> ![[belpho-2018-iii-theory-solutions-p13-f1.png]]
>
> Решая с учетом (3), получаем
>
> $$F>T\cos\alpha+\mu\left(mg+\frac{m_0g}{2}\right)=\mu\left(mg+\frac{m_0g}{2}\right)+\mu\left(mg+\frac{m_0g}{2}\right)=\mu g(2m+m_0) \tag{4}$$
>
> Очевидный результат – приложенная сила должна быть больше, чем суммарная сила трения, действующая на систему. Чтобы сдвинуть второй
>
> $$T\cos\alpha>\mu\left(mg+\frac{m_0g}{2}\right) \tag{5}$$
>
> Но, $T\cos\alpha=F-\mu\left(mg+\frac{m_0g}{2}\right)$, подставляя в (5), получаем то же условие (4). Т.е. в данном случае сдвинуть один брусок нельзя – сразу сдвинуться оба.
