---
id: nbpho-2014-intl-theory-3
olympiad: NbPhO
year: 2014
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "3"
title: "Magnets"
points: 6
aliases: ["Magnets"]
topics: ["[[1.10 Статика]]", "[[4 Магнетизм]]"]
difficulty: 3
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "По потере равновесия подвешенного магнита найти показатель степени зависимости силы от расстояния."
status: "проверено: сверка, два чтения + арбитр"
lang: en
tags: [задача]
---

# 3. MAGNETS (6 points)

**NbPhO 2014** · Международная олимпиада · теория · 10–12 класс · задача 3  
Источник: [[_pdf/NbPhO/nbpho-2014.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2014.pdf#page=3|решение, стр. 3]]

Темы: [[1.10 Статика]], [[4 Магнетизм]]

> [!abstract] Кратко (составлено моделью)
> По потере равновесия подвешенного магнита найти показатель степени зависимости силы от расстояния.

To explore the force between two small magnets, the following experiment is performed. One of the magnets is hanged from a thread with length $l=1\,\mathrm{m}$. Other magnet is moved slowly closer while keeping the axes of the magnets always on the same horizontal line. At the moment when the distance between the magnets is $d_1=4\,\mathrm{cm}$ and the hanged magnet has moved $x_1=1\,\mathrm{cm}$ from initial position, balance is lost and the magnets pull together. By making the assumption that the pulling force between the magnets $F_m$ depends on the distance $d$ according to the relation $F_m\propto d^{-n}$, find the value of the exponent $n$.

> [!answer]- Ответ
> **3**
>
> $$
> n=d/x=4.
> $$

> [!solution]- Решение
> # 3. Magnets
>
> There three forces acting on the hanging magnet: the downwards directed gravity force $m\vec g$, the tension force $\vec T$, which is directed along the thread, and the horizontal magnetic force $\vec F_{\mathrm m}$. Since the thread’s angle is very small, the modulus of $\vec T$ is almost equal to $mg$, so that its horizontal projection is expressed as $-(x/l)mg$, where $l$ is the length of the thread and $x=1\,\mathrm{cm}$ (the displacement from the initial position). The net horizontal force $F=F_{\mathrm m}-(x/l)mg$. At the equilibrium point $F=0$. The equilibrium point is stable if a small (virtual) displacement $\Delta x$ gives rise to a returning force
>
> $$\Delta F=\Delta F_{\mathrm m}-\frac{\Delta x}{l}mg$$
>
> which needs to push towards the equilibrium point. Let $F_{\mathrm m}=kd^{-n}$, where $k$ is an unknown proportionality coefficient. Then
>
> $$\Delta F_{\mathrm m}=F_{\mathrm m}'(d)\Delta d=\frac{kn}{d^{n+1}}\Delta x,$$
>
> because $\Delta d=-\Delta x$. Therefore
>
> $$\Delta F=\left(\frac{kn}{d^{n+1}}-\frac{mg}{l}\right)\Delta x.$$
>
> At the limit case of the loss of stability (which is described by this problem) $\Delta F=0$. Thus we have two equations with two unknowns ($n$ and $k$):
>
> $$\frac{k}{d^n}-\frac{xmg}{l}=0,\qquad\frac{kn}{d^{n+1}}-\frac{mg}{l}=0;$$
>
> this can be rewritten as
>
> $$\frac{k}{d^n}=\frac{xmg}{l},\qquad\frac{kn}{d^{n+1}}=\frac{mg}{l}.$$
>
> If we divide the corresponding sides of the two equations we obtain $d/n=x$, hence
>
> $$n=d/x=4.$$
