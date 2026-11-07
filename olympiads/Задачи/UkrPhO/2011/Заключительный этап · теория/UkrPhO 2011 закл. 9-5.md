---
id: ukrpho-2011-final-theory-9-5
olympiad: UkrPhO
year: 2011
stage: "Заключительный этап"
round: теория
grade: 9
number: "9-5"
title: "Задача 9-5"
aliases: ["Задача 9-5"]
topics: ["[[5 Цепи]]"]
difficulty: 3
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "По напряжению на одной группе батареек в замкнутой последовательной цепи найти напряжения на другой группе и батарейках каждого типа."
status: "проверено: сверка"
lang: ru
lang_orig: uk
translated: "GPT Pro, ukrpho_tr01_p7_RESULT"
tags: [задача]
---

# 5.

**UkrPhO 2011** · Заключительный этап · теория · 9 класс · задача 9-5  
Источник: [[_pdf/UkrPhO/2011-final-theory-09-combined.pdf#page=1|условие, стр. 1]] · [[_pdf/UkrPhO/2011-final-theory-09-combined.pdf#page=8|решение, стр. 8–10]]

Темы: [[5 Цепи]]

> [!abstract] Кратко (составлено моделью)
> По напряжению на одной группе батареек в замкнутой последовательной цепи найти напряжения на другой группе и батарейках каждого типа.

Неопытный лаборант спаял замкнутую цепь из десяти батареек «Альфа» и четырнадцати батареек «Бета». Батарейки он брал в произвольном порядке, но всегда соединял «плюс» с «минусом». Верхний вольтметр, подключённый к группе «Бета»-«Альфа»-«Бета» (рис.3), показывает напряжение 1,5 В. Какое напряжение показывает нижний вольтметр, подключённый к группе «Альфа»-«Бета»-«Альфа»? Какое напряжение покажет вольтметр, если его подключить к батарейке «Бета»? К батарейке «Альфа»?

![[ukrpho-2011-theory-9-combined-p1-f3.png]]

Задачи предложили В.П.Сохацкий (1), Е.П.Соколов (2, 5), С.У.Гончаренко (3), А.П.Федоренко (4).

> [!answer]- Ответ
> Отсюда первый ответ: $U_{\alpha\beta\alpha}=3\cdot U_{\beta\alpha\beta}=4{,}5\,\text{В}$
>
> Второй ответ: $U_\beta=\dfrac{5}{9}\cdot U_{\alpha\beta\alpha}=\dfrac{5}{3}\cdot U_{\beta\alpha\beta}=2{,}5\,\text{В}$.
>
> Третий ответ: $U_\alpha=\dfrac{7}{5}\cdot U_\beta=\dfrac{7}{9}\cdot U_{\alpha\beta\alpha}=\dfrac{7}{3}\cdot U_{\beta\alpha\beta}=3{,}5\,\text{В}$
>
> **1)** $U_{\alpha\beta\alpha}=3\cdot U_{\beta\alpha\beta}=4{,}5\,\text{В}$;
>
> **2)** $U_\beta=\dfrac{5}{3}\cdot U_{\beta\alpha\beta}=2{,}5\,\text{В}$;
>
> **3)** $U_\alpha=\dfrac{7}{3}\cdot U_{\beta\alpha\beta}=3{,}5\,\text{В}$.
>
> $$
> |U_\alpha|=\frac{7}{3}\cdot U_{\beta\alpha\beta}=3{,}5\ \text{В},
> $$
>
> $$
> |U_\beta|=\frac{5}{7}\cdot|U_\alpha|=2{,}5\ \text{В},
> $$
>
> $$
> U_{\alpha\beta\alpha}=\frac{9}{7}\cdot|U_\alpha|=4{,}5\ \text{В}.
> $$
>
> **1)** $U_{\alpha\beta\alpha}=3\cdot U_{\beta\alpha\beta}=4{,}5\ \text{В}$;
>
> **2)** $U_\beta=\frac{5}{3}\cdot U_{\beta\alpha\beta}=2{,}5\ \text{В}$;
>
> **3)** $U_\alpha=\frac{7}{3}\cdot U_{\beta\alpha\beta}=3{,}5\ \text{В}$.

> [!solution]- Решение
> # Решение 1 «Макроскопическое»
>
> **1)** Перегруппируем батарейки, не входящие в «зону действия вольтметров», так, чтобы образовалось шесть групп «Бета»-«Альфа»-«Бета» и две группы «Альфа»-«Бета»-«Альфа» (рис.2).
>
> ![[ukrpho-2011-theory-9-combined-p8-f2.svg]]
> *Рис.2*
>
> Серый и белый вольтметры, подключённые к точкам соединения групп, показывают одинаковое напряжение. При этом показания серого вольтметра равны $U_\text{с}=6\cdot U_{\beta\alpha\beta}$, а белого – $U_\text{б}=2\cdot U_{\alpha\beta\alpha}$. Получаем уравнение:
>
> $$
> 2\cdot U_{\alpha\beta\alpha}=6\cdot U_{\beta\alpha\beta}.
> $$
>
> Отсюда первый ответ: $U_{\alpha\beta\alpha}=3\cdot U_{\beta\alpha\beta}=4{,}5\,\text{В}$
>
> **2)** Расположим батарейки так, чтобы образовалось пять групп «Альфа»-«Бета»-«Альфа» и девять элементов «Бета» (рис.3).
>
> Показания серого и белого вольтметров одинаковы, - отсюда второе уравнение:
>
> $$
> 9\cdot U_\beta=5\cdot U_{\alpha\beta\alpha}.
> $$
>
> Второй ответ: $U_\beta=\dfrac{5}{9}\cdot U_{\alpha\beta\alpha}=\dfrac{5}{3}\cdot U_{\beta\alpha\beta}=2{,}5\,\text{В}$.
>
> ![[ukrpho-2011-theory-9-combined-p9-c1042.png]]
> *Рис.3*
>
> ![[ukrpho-2011-theory-9-combined-p9-f2.svg]]
>
> **3)** Расположим батарейки одну за другой: четырнадцать батареек «Бета» и десять батареек «Альфа» (рис.4).
>
> Показания серого и белого вольтметров одинаковы, отсюда уравнение:
>
> $$
> 10\cdot U_\alpha=14\cdot U_\beta.
> $$
>
> Третий ответ: $U_\alpha=\dfrac{7}{5}\cdot U_\beta=\dfrac{7}{9}\cdot U_{\alpha\beta\alpha}=\dfrac{7}{3}\cdot U_{\beta\alpha\beta}=3{,}5\,\text{В}$
>
> *Ответы:*
>
> **1)** $U_{\alpha\beta\alpha}=3\cdot U_{\beta\alpha\beta}=4{,}5\,\text{В}$;
>
> **2)** $U_\beta=\dfrac{5}{3}\cdot U_{\beta\alpha\beta}=2{,}5\,\text{В}$;
>
> **3)** $U_\alpha=\dfrac{7}{3}\cdot U_{\beta\alpha\beta}=3{,}5\,\text{В}$.
>
> # Решение 2 «Микроскопическое»
>
> Теперь нашим первым шагом будет третий шаг предыдущего решения:
>
> $$
> 14\cdot\left|U_\beta\right|=10\cdot\left|U_\alpha\right|.
> $$
>
> То есть напряжения на батарейках каждого вида связаны соотношением:
>
> $$
> |U_\beta|=\frac{5}{7}\cdot|U_\alpha|
> $$
>
> Следует учесть, что для того чтобы алгебраическая сумма напряжений в цикле была равна нулю, одно из напряжений имеет знак «+», а другое - «-».
>
> Для известного напряжения $U_{\beta\alpha\beta}$ получаем:
>
> $$
> U_{\beta\alpha\beta}=\left|2\cdot|U_\beta|-|U_\alpha|\right|=\frac{3}{7}\cdot|U_\alpha|.
> $$
>
> Для напряжения $U_{\alpha\beta\alpha}$ аналогично:
>
> $$
> U_{\alpha\beta\alpha}=\left|2\cdot|U_\alpha|-|U_\beta|\right|=\frac{9}{7}\cdot|U_\alpha|.
> $$
>
> Отсюда следуют все ответы:
>
> $$
> |U_\alpha|=\frac{7}{3}\cdot U_{\beta\alpha\beta}=3{,}5\ \text{В},
> $$
>
> $$
> |U_\beta|=\frac{5}{7}\cdot|U_\alpha|=2{,}5\ \text{В},
> $$
>
> $$
> U_{\alpha\beta\alpha}=\frac{9}{7}\cdot|U_\alpha|=4{,}5\ \text{В}.
> $$
>
> **Ответы:**
>
> **1)** $U_{\alpha\beta\alpha}=3\cdot U_{\beta\alpha\beta}=4{,}5\ \text{В}$;
>
> **2)** $U_\beta=\frac{5}{3}\cdot U_{\beta\alpha\beta}=2{,}5\ \text{В}$;
>
> **3)** $U_\alpha=\frac{7}{3}\cdot U_{\beta\alpha\beta}=3{,}5\ \text{В}$.

> [!original]- Оригинал (украинский)
> Недосвідчений лаборант спаяв замкнуте коло з десяти батарейок «Альфа» і чотирнадцяти батарейок «Бета». Батарейки він брав у довільному порядку, але завжди з'єднував «плюс» з «мінусом». Верхній вольтметр, підключений до групи «Бета»-«Альфа»-«Бета» (мал.3), показує напругу 1,5 В. Яку напругу показує нижній вольтметр, підключений до групи «Альфа»-«Бета»-«Альфа»? Яку напругу покаже вольтметр, якщо його підключити до батарейки «Бета»? До батарейки «Альфа»?
>
> ![[ukrpho-2011-theory-9-combined-p1-f3.png]]
>
> Задачі запропонували В.П.Сохацький (1), Є.П.Соколов (2, 5), С.У.Гончаренко (3), А.П.Федоренко (4).
>
> > [!answer]- Відповідь
> > Звідси перша відповідь: $U_{\alpha\beta\alpha}=3\cdot U_{\beta\alpha\beta}=4{,}5\,\text{В}$
> >
> > Друга відповідь: $U_\beta=\dfrac{5}{9}\cdot U_{\alpha\beta\alpha}=\dfrac{5}{3}\cdot U_{\beta\alpha\beta}=2{,}5\,\text{В}$.
> >
> > Третя відповідь: $U_\alpha=\dfrac{7}{5}\cdot U_\beta=\dfrac{7}{9}\cdot U_{\alpha\beta\alpha}=\dfrac{7}{3}\cdot U_{\beta\alpha\beta}=3{,}5\,\text{В}$
> >
> > **1)** $U_{\alpha\beta\alpha}=3\cdot U_{\beta\alpha\beta}=4{,}5\,\text{В}$;
> >
> > **2)** $U_\beta=\dfrac{5}{3}\cdot U_{\beta\alpha\beta}=2{,}5\,\text{В}$;
> >
> > **3)** $U_\alpha=\dfrac{7}{3}\cdot U_{\beta\alpha\beta}=3{,}5\,\text{В}$.
> >
> > $$
> > |U_\alpha|=\frac{7}{3}\cdot U_{\beta\alpha\beta}=3{,}5\ \text{В},
> > $$
> >
> > $$
> > |U_\beta|=\frac{5}{7}\cdot|U_\alpha|=2{,}5\ \text{В},
> > $$
> >
> > $$
> > U_{\alpha\beta\alpha}=\frac{9}{7}\cdot|U_\alpha|=4{,}5\ \text{В}.
> > $$
> >
> > **1)** $U_{\alpha\beta\alpha}=3\cdot U_{\beta\alpha\beta}=4{,}5\ \text{В}$;
> >
> > **2)** $U_\beta=\frac{5}{3}\cdot U_{\beta\alpha\beta}=2{,}5\ \text{В}$;
> >
> > **3)** $U_\alpha=\frac{7}{3}\cdot U_{\beta\alpha\beta}=3{,}5\ \text{В}$.
>
> > [!solution]- Розв’язання
> > # Розв'язання 1 «Макроскопічне»
> >
> > **1)** Перегрупуємо батарейки, що не входять в «зону дії вольтметрів», так, щоб утворилося шість груп «Бета»-«Альфа»-«Бета» і дві групи «Альфа»-«Бета»-«Альфа» (мал.2).
> >
> > ![[ukrpho-2011-theory-9-combined-p8-f2.svg]]
> > *Мал.2*
> >
> > Сірий і білий вольтметри, що підключені до точок з'єднання груп, показують однакову напругу. При цьому показання сірого вольтметра рівні $U_\text{с}=6\cdot U_{\beta\alpha\beta}$, а білого – $U_\text{б}=2\cdot U_{\alpha\beta\alpha}$. Отримуємо рівняння:
> >
> > $$
> > 2\cdot U_{\alpha\beta\alpha}=6\cdot U_{\beta\alpha\beta}.
> > $$
> >
> > Звідси перша відповідь: $U_{\alpha\beta\alpha}=3\cdot U_{\beta\alpha\beta}=4{,}5\,\text{В}$
> >
> > **2)** Розташуємо батарейки так, щоб утворилося п'ять груп «Альфа»-«Бета»-«Альфа» і дев'ять елементів «Бета» (мал.3).
> >
> > Показання сірого й білого вольтметрів однакові, - звідси друге рівняння:
> >
> > $$
> > 9\cdot U_\beta=5\cdot U_{\alpha\beta\alpha}.
> > $$
> >
> > Друга відповідь: $U_\beta=\dfrac{5}{9}\cdot U_{\alpha\beta\alpha}=\dfrac{5}{3}\cdot U_{\beta\alpha\beta}=2{,}5\,\text{В}$.
> >
> > ![[ukrpho-2011-theory-9-combined-p9-c1042.png]]
> > *Мал.3*
> >
> > ![[ukrpho-2011-theory-9-combined-p9-f2.svg]]
> >
> > **3)** Розташуємо батарейки один по одному: чотирнадцять батарейок «Бета» і десять батарейок «Альфа» (мал.4).
> >
> > Показання сірого й білого вольтметрів однакові, звідси рівняння:
> >
> > $$
> > 10\cdot U_\alpha=14\cdot U_\beta.
> > $$
> >
> > Третя відповідь: $U_\alpha=\dfrac{7}{5}\cdot U_\beta=\dfrac{7}{9}\cdot U_{\alpha\beta\alpha}=\dfrac{7}{3}\cdot U_{\beta\alpha\beta}=3{,}5\,\text{В}$
> >
> > *Відповіді:*
> >
> > **1)** $U_{\alpha\beta\alpha}=3\cdot U_{\beta\alpha\beta}=4{,}5\,\text{В}$;
> >
> > **2)** $U_\beta=\dfrac{5}{3}\cdot U_{\beta\alpha\beta}=2{,}5\,\text{В}$;
> >
> > **3)** $U_\alpha=\dfrac{7}{3}\cdot U_{\beta\alpha\beta}=3{,}5\,\text{В}$.
> >
> > # Розв'язання 2 «Мікроскопічне»
> >
> > Тепер нашим першим кроком буде третій крок попереднього розв'язання:
> >
> > $$
> > 14\cdot\left|U_\beta\right|=10\cdot\left|U_\alpha\right|.
> > $$
> >
> > Тобто напруги на батарейках кожного виду зв'язані співвідношенням:
> >
> > $$
> > |U_\beta|=\frac{5}{7}\cdot|U_\alpha|
> > $$
> >
> > Варто врахувати, що для того щоб алгебраїчна сума напруг у циклі була б рівною нулю, одне з напруг має знак «+», а інше - «-».
> >
> > Для відомої напруги $U_{\beta\alpha\beta}$ отримуємо:
> >
> > $$
> > U_{\beta\alpha\beta}=\left|2\cdot|U_\beta|-|U_\alpha|\right|=\frac{3}{7}\cdot|U_\alpha|.
> > $$
> >
> > Для напруги $U_{\alpha\beta\alpha}$ аналогічно:
> >
> > $$
> > U_{\alpha\beta\alpha}=\left|2\cdot|U_\alpha|-|U_\beta|\right|=\frac{9}{7}\cdot|U_\alpha|.
> > $$
> >
> > Звідси випливають всі відповіді:
> >
> > $$
> > |U_\alpha|=\frac{7}{3}\cdot U_{\beta\alpha\beta}=3{,}5\ \text{В},
> > $$
> >
> > $$
> > |U_\beta|=\frac{5}{7}\cdot|U_\alpha|=2{,}5\ \text{В},
> > $$
> >
> > $$
> > U_{\alpha\beta\alpha}=\frac{9}{7}\cdot|U_\alpha|=4{,}5\ \text{В}.
> > $$
> >
> > **Відповіді:**
> >
> > **1)** $U_{\alpha\beta\alpha}=3\cdot U_{\beta\alpha\beta}=4{,}5\ \text{В}$;
> >
> > **2)** $U_\beta=\frac{5}{3}\cdot U_{\beta\alpha\beta}=2{,}5\ \text{В}$;
> >
> > **3)** $U_\alpha=\frac{7}{3}\cdot U_{\beta\alpha\beta}=3{,}5\ \text{В}$.
