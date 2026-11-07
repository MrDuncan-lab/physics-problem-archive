---
id: ukrpho-2018-final-theory-9-1
olympiad: UkrPhO
year: 2018
stage: "Заключительный этап"
round: теория
grade: 9
number: "9-1"
title: "Задача 9-1"
aliases: ["Задача 9-1"]
topics: ["[[1.13 Кинематические связи (и динамика)]]", "[[1.6 Векторная кинематика]]"]
difficulty: 3
has_solution: true
has_hints: false
has_grading: false
source_damaged: true
summary: "Найти скорости двух узлов шарнирных ножниц при заданной скорости другого узла и угле между стержнями."
status: "проверено: сверка"
lang: ru
lang_orig: uk
translated: "GPT Pro, ukrpho_tr01_p5_RESULT"
tags: [задача]
---

# 1.

**UkrPhO 2018** · Заключительный этап · теория · 9 класс · задача 9-1  
Источник: [[_pdf/UkrPhO/2018-final-theory-09-combined.pdf#page=1|условие, стр. 1]] · [[_pdf/UkrPhO/2018-final-theory-09-combined.pdf#page=2|решение, стр. 2]]

Темы: [[1.13 Кинематические связи (и динамика)]], [[1.6 Векторная кинематика]]

> [!abstract] Кратко (составлено моделью)
> Найти скорости двух узлов шарнирных ножниц при заданной скорости другого узла и угле между стержнями.

> [!warning] Часть текста утрачена в исходном PDF
> - вместо подстрочного символа горизонтальной составляющей скорости напечатаны квадраты; утраченный символ передан как [?]

На рис. 1 изображён шарнирный механизм - «Нюрнбергские ножницы». Точка С движется с постоянной скоростью $V_0=60\text{ см}/\text{с}$. **1)** Найти скорость точки А. **2)** Найти скорость точки В в тот момент, когда угол $\alpha=30^\circ$.

![[ukrpho-2018-theory-9-combined-p1-f2.png]]

*Рис. 1*

> [!answer]- Ответ
> **а** — $\upsilon_A=\frac25\upsilon_C=\frac25\upsilon_0=24\text{ см}/\text{с}$.
>
> **в**
>
> $$
> \upsilon_B=\sqrt{\upsilon_{[?]}^2+\upsilon_\perp^2}=\sqrt{\frac{\upsilon_0^2}{4}+\frac{3\upsilon_0^2}{100}}=\frac{\sqrt7}{5}\upsilon_0\approx31{,}7\text{см}/\text{с}.
> $$

> [!solution]- Решение
> **Задача 9.1.**
>
> **а)** Отрезок АО всегда составляет 2/5 от отрезка ОС, поэтому скорость точки А составляет 2/5 от скорости точки С:
>
> $\upsilon_A=\frac25\upsilon_C=\frac25\upsilon_0=24\text{ см}/\text{с}$.
>
> ![[ukrpho-2018-theory-9-combined-p2-f1.svg]]
>
> **б)** Скорость точки В можно разложить на две составляющие: горизонтальную $\upsilon_{[?]}$ и вертикальную $\upsilon_\perp$ ($\upsilon_B=\sqrt{\upsilon_{[?]}^2+\upsilon_\perp^2}$). Поскольку точка В всегда находится посередине механизма горизонтальная составляющая её скорости составляет $\upsilon_{[?]}=\frac{\upsilon_0}{2}=30\text{ см}/\text{с}$.
>
> **в)** Во время движения длина отрезка АВ не изменяется, тогда разность проекций скоростей точек А и В на направление вдоль отрезка АВ равна нулю.
>
> $$
> \upsilon_{[?]x}+\upsilon_{\perp x}-\upsilon_{Ax}=\upsilon_{[?]}\cos\alpha-\upsilon_\perp\sin\alpha-\upsilon_A\cos\alpha=0
> \Rightarrow\upsilon_\perp=(\upsilon_{[?]}-\upsilon_A)\operatorname{ctg}\alpha=\frac{\sqrt3}{10}\upsilon_0
> $$
>
> $$
> \upsilon_B=\sqrt{\upsilon_{[?]}^2+\upsilon_\perp^2}=\sqrt{\frac{\upsilon_0^2}{4}+\frac{3\upsilon_0^2}{100}}=\frac{\sqrt7}{5}\upsilon_0\approx31{,}7\text{см}/\text{с}.
> $$

> [!original]- Оригинал (украинский)
> На рис. 1 зображений шарнірний механізм - «Нюрнберзькі ножиці». Точка С рухається зі сталою швидкістю $V_0=60\text{ см}/\text{с}$. **1)** Знайти швидкість точки А. **2)** Знайти швидкість точки В в той момент, коли кут $\alpha=30^\circ$.
>
> ![[ukrpho-2018-theory-9-combined-p1-f2.png]]
>
> *Рис. 1*
>
> > [!solution]- Розв’язання
> > **Задача 9.1.**
> >
> > **а)** Відрізок АО завжди складає 2/5 від відрізка ОС, тому швидкість точки А складає 2/5 від швидкості точки С:
> >
> > $\upsilon_A=\frac25\upsilon_C=\frac25\upsilon_0=24\text{ см}/\text{с}$.
> >
> > ![[ukrpho-2018-theory-9-combined-p2-f1.svg]]
> >
> > **б)** Швидкість точки В можна розкласти на дві складові: горизонтальну $\upsilon_{[?]}$ та вертикальну $\upsilon_\perp$ ($\upsilon_B=\sqrt{\upsilon_{[?]}^2+\upsilon_\perp^2}$). Тому що точка В завжди знаходиться посередині механізму горизонтальна складова її швидкості становить $\upsilon_{[?]}=\frac{\upsilon_0}{2}=30\text{ см}/\text{с}$.
> >
> > **в)** Підчас руху довжина відрізка АВ не змінюється, тоді різниця проекцій швидкостей точок А і В на напрям вздовж відрізка АВ дорівнює нулю.
> >
> > $$
> > \upsilon_{[?]x}+\upsilon_{\perp x}-\upsilon_{Ax}=\upsilon_{[?]}\cos\alpha-\upsilon_\perp\sin\alpha-\upsilon_A\cos\alpha=0
> > \Rightarrow\upsilon_\perp=(\upsilon_{[?]}-\upsilon_A)\operatorname{ctg}\alpha=\frac{\sqrt3}{10}\upsilon_0
> > $$
> >
> > $$
> > \upsilon_B=\sqrt{\upsilon_{[?]}^2+\upsilon_\perp^2}=\sqrt{\frac{\upsilon_0^2}{4}+\frac{3\upsilon_0^2}{100}}=\frac{\sqrt7}{5}\upsilon_0\approx31{,}7\text{см}/\text{с}.
> > $$
