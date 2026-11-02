---
id: belpho-1997-final-theory-9-4
olympiad: BelPhO
year: 1997
stage: "Заключительный этап"
round: теория
grade: 9
number: "9-4"
title: "Задача 9-4"
aliases: ["Задача 9-4"]
topics: ["[[1.3 Равноускоренное криволинейное движение]]", "[[1.6 Векторная кинематика]]"]
difficulty: 3
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Найти минимальное расстояние и момент наибольшего сближения двух камней, брошенных с башни с задержкой."
status: "проверено: сверка"
lang: ru
tags: [задача]
---

# 9-4.

**BelPhO 1997** · Заключительный этап · теория · 9 класс · задача 9-4  
Источник: [[_pdf/BelPhO/1997-final-theoretical-problems.pdf#page=1|условие, стр. 1]] · [[_pdf/BelPhO/1997-final-theoretical-solutions.pdf#page=3|решение, стр. 3–4]]

Темы: [[1.3 Равноускоренное криволинейное движение]], [[1.6 Векторная кинематика]]

> [!abstract] Кратко (составлено моделью)
> Найти минимальное расстояние и момент наибольшего сближения двух камней, брошенных с башни с задержкой.

Два камешка брошены с высокой башни под углом $\alpha>0$ к горизонту со скоростью $v_0$ с интервалом времени $\Delta t$ один за другим. Определите наименьшее расстояние между ними в течение полета и момент времени, когда это произойдет. Сопротивлением воздуха пренебречь.

> [!answer]- Ответ
> **1**
>
> $$
> CB_1=(\Delta\vec r_0)_x=\left(\vec v_0\Delta t+\vec g\frac{\Delta t^2}{2}\right)_x=v_0\cos\alpha\Delta t.
> $$
>
> **1**
>
> $$
> t=\frac{v_0\sin\alpha}{g}-\frac{\Delta t}{2}.
> $$
>
> **2**
>
> $$
> OA_2=|\Delta\vec r_0|=\sqrt{(v_0\cos\alpha\Delta t)^2+\left(v_0\sin\alpha\Delta t-g\frac{\Delta t^2}{2}\right)^2},
> $$
>
> **2**
>
> $$
> t=0.
> $$

> [!solution]- Решение
> ## 9-4.
>
> Выберем начало системы отсчета на башне, задачу будем решать в векторном виде. К моменту вылета второго камешка первый совершит перемещение
>
> $$
> \Delta\vec r_0=\vec v_0\Delta t+\vec g\frac{\Delta t^2}{2}
> $$
>
> и будет двигаться со скоростью
>
> $$
> \vec v=\vec v_0+\vec g\Delta t.
> $$
>
> Перемещения камешков после бросания второго камешка запишутся следующим образом
>
> $$
> \Delta\vec r_1(t)=\vec v_0(t+\Delta t)+\vec g\frac{(t+\Delta t)^2}{2},
> $$
>
> $$
> \Delta\vec r_2(t)=\vec v_0t+\frac{\vec gt^2}{2}.
> $$
>
> Перейдем в систему отсчета, связанную со вторым камешком. Тогда относительное положение первого камешка задается вектором
>
> $$
> \vec S=\Delta\vec r_1(t)-\Delta\vec r_2(t)=\vec v_0\Delta t+\vec g\frac{\Delta t^2}{2}+\vec g\Delta t\cdot t=\Delta\vec r_0+\vec g\Delta t\cdot t,
> $$
>
> т.е. это движение вертикально вниз со скоростью $\vec g\Delta t$. Поэтому
>
> **1)** если $\Delta t$ таково, что первый камушек не успел опуститься ниже горизонта точки бросания (точка $A_1$), тогда наименьшее расстояние будет равно
>
> ![[belpho-1997-final-theory-solutions-p4-c6807.png]]
>
> $$
> CB_1=(\Delta\vec r_0)_x=\left(\vec v_0\Delta t+\vec g\frac{\Delta t^2}{2}\right)_x=v_0\cos\alpha\Delta t.\tag{1}
> $$
>
> Оно будет достигнуто в момент, когда оба шарика будут на одной высоте, т.е.
>
> $$
> S_y=0=(\Delta\vec r_0)_y-g\Delta t\cdot t=v_0\sin\alpha\Delta t-g\frac{\Delta t^2}{2}-g\Delta t\cdot t,
> $$
>
> $$
> t=\frac{v_0\sin\alpha}{g}-\frac{\Delta t}{2}.\tag{2}
> $$
>
> **2)** если $\Delta t$ таково, что первый камушек опустился ниже горизонта бросания ($A_2$), наименьшим расстоянием будет начальное, т.е.
>
> $$
> OA_2=|\Delta\vec r_0|=\sqrt{(v_0\cos\alpha\Delta t)^2+\left(v_0\sin\alpha\Delta t-g\frac{\Delta t^2}{2}\right)^2},\tag{3}
> $$
>
> а момент времени
>
> $$
> t=0.\tag{4}
> $$
>
> Условие выбора ответа следует из (2): если $\Delta t>\dfrac{2v_0\sin\alpha}{g}$, то ответ — (3), (4), если $\Delta t<\dfrac{2v_0\sin\alpha}{g}$, то — (1), (2).
