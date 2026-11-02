---
id: ruspho-2000-final-theory-10-5
olympiad: RusPhO
year: 2000
stage: "Заключительный этап"
round: теория
grade: 10
number: "10-5"
title: "Электрическая схема"
aliases: ["Электрическая схема"]
topics: ["[[5.1 RC-цепи]]", "[[3.5 Энергия системы]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: true
summary: "Найти начальные токи батарей, изменение энергии конденсаторов, работы источников и выделившуюся теплоту после замыкания схемы."
status: "проверено: сверка"
lang: ru
tags: [задача]
---

# Задача 5. Электрическая схема

**RusPhO 2000** · Заключительный этап · теория · 10 класс · задача 10-5  
Источник: [[_pdf/RusPhO/2000-final-theor.pdf#page=3|условие, стр. 3–4]] · [[_pdf/RusPhO/2000-final-theor.pdf#page=8|решение, стр. 8–9]]

Темы: [[5.1 RC-цепи]], [[3.5 Энергия системы]]

> [!abstract] Кратко (составлено моделью)
> Найти начальные токи батарей, изменение энергии конденсаторов, работы источников и выделившуюся теплоту после замыкания схемы.

> [!warning] Часть текста утрачена в исходном PDF
> - в пункте 4 решения 10-5 правая часть формулы изменения энергии обрезана после C/4(ℰ1+2ℰ2

В электрической цепи, представленной на рисунке, ключ $K$ разомкнут и токи не текут. Определите:

**1.** Токи через батареи $\mathcal E_1$ и $\mathcal E_2$ сразу после замыкания ключа $K$.

**2.** Изменение электростатической энергии $\Delta W$ системы после прекращения токов.

**3.** Работы $A_1$ и $A_2$ батарей $\mathcal E_1$ и $\mathcal E_2$ за все время процесса.

**4.** Количество теплоты $Q$, выделившееся на резисторах после замыкания ключа $K$.

![[ruspho-2000-final-theory-p3-c8412.png]]

*Рис. 9*

> [!answer]- Ответ
> **1**
>
> $$
> IR=\mathcal E_2+\mathcal E_1-U_0\Rightarrow I=\frac{\mathcal E_2+\mathcal E_1/2}{R}.
> $$
>
> **1** — $I_1=I=\frac{\mathcal{E}_2+\mathcal{E}_1/2}{R}$,
>
> **2**
>
> $$
> \Delta W=W-W_0=\frac{C\mathcal{E}_2^2}{2}+\frac{C\mathcal{E}_2^2}{2}+\frac{C\mathcal{E}_1^2}{2}+C\mathcal{E}_1\mathcal{E}_2-\frac{C\mathcal{E}_1^2}{4}=C\mathcal{E}_2^2+\frac{C\mathcal{E}_1^2}{4}+C\mathcal{E}_1\mathcal{E}_2=\frac{C}{4}(\mathcal{E}_1+2\mathcal{E}_2[?]
> $$
>
> **3**
>
> $$
> A_2=q\mathcal{E}_2=C\mathcal{E}_2(\mathcal{E}_1+2\mathcal{E}_2).
> $$
>
> **3**
>
> $$
> A_1=\Delta q\mathcal{E}_1=\frac{C\mathcal{E}_1(2\mathcal{E}_2+\mathcal{E}_1)}{2}.
> $$
>
> **4**
>
> $$
> Q=A-\Delta W=\frac{C(\mathcal{E}_1+2\mathcal{E}_2)^2}{4}.
> $$

> [!solution]- Решение
> # Задача 5. Электрическая схема
>
> **1.** До замыкания ключа $K$ на конденсаторах были одинаковые разности потенциалов $U_0=\mathcal E_1/2$ и заряды $q_0=C\mathcal E_1/2$. Полярность указана на рисунке (рис. 26).
>
> **2.** В момент замыкания заряды конденсаторов и напряжения на них не могут мгновенно измениться. В цепи появляются токи $I$, $I_1$, и $I_2$ (рис. 27). Согласно законам Кирхгофа:
>
> $$
> IR=\mathcal E_2+\mathcal E_1-U_0\Rightarrow I=\frac{\mathcal E_2+\mathcal E_1/2}{R}.
> $$
>
> Здесь $I$ — ток через $\mathcal E_2$. Далее
>
> $$
> I_2R+IR=\mathcal E_2+U_0,
> $$
>
> $$
> I_2=-I+\frac{\mathcal E_2+U_0}{R}=-\frac{\mathcal E_2+\mathcal E_1/2}{R}+\frac{\mathcal E_2+\mathcal E_1/2}{R}=0.
> $$
>
> Следовательно
>
> $I_1=I=\frac{\mathcal{E}_2+\mathcal{E}_1/2}{R}$, где $I_1$ — ток через $\mathcal{E}_1$.
>
> ![[ruspho-2000-final-theory-p9-c0112.png]]
> *Рис. 26*
>
> ![[ruspho-2000-final-theory-p9-c1710.png]]
> *Рис. 27*
>
> ![[ruspho-2000-final-theory-p9-c3212.png]]
> *Рис. 28*
>
> **3.** Начальная энергия системы $W_0=2CU_0^2/2=C\mathcal{E}_1^2/4$. В конечном состоянии (т. е. после затухания токов) напряжения на конденсаторах равны $U_1=\mathcal{E}_2+\mathcal{E}_1$ и $U_2=\mathcal{E}_2$. Полярность указана на рисунке (рис. 28). Энергия системы в конечном состоянии есть:
>
> $$
> W=\frac{C\mathcal{E}_2^2}{2}+\frac{C(\mathcal{E}_2+\mathcal{E}_1)^2}{2}.
> $$
>
> **4.** Изменение энергии
>
> $$
> \Delta W=W-W_0=\frac{C\mathcal{E}_2^2}{2}+\frac{C\mathcal{E}_2^2}{2}+\frac{C\mathcal{E}_1^2}{2}+C\mathcal{E}_1\mathcal{E}_2-\frac{C\mathcal{E}_1^2}{4}=C\mathcal{E}_2^2+\frac{C\mathcal{E}_1^2}{4}+C\mathcal{E}_1\mathcal{E}_2=\frac{C}{4}(\mathcal{E}_1+2\mathcal{E}_2[?]
> $$
>
> **5.** До замыкания ключа K суммарный заряд на левых обкладках конденсаторов был равен нулю. В конечном состоянии
>
> $$
> q_1=C(\mathcal{E}_1+\mathcal{E}_2)
> $$
>
> $$
> q_2=C\mathcal{E}_2
> $$
>
> Отсюда:
>
> $$
> q=q_1+q_2=C(\mathcal{E}_1+2\mathcal{E}_2).
> $$
>
> Это означает, что через батарею $\mathcal{E}_2$ протек заряд $q$ и батарея совершила работу
>
> $$
> A_2=q\mathcal{E}_2=C\mathcal{E}_2(\mathcal{E}_1+2\mathcal{E}_2).
> $$
>
> Через батарею $\mathcal{E}_1$ протек заряд
>
> $$
> \Delta q=q_1-q_0=C(\mathcal{E}_2+\mathcal{E}_1)-\frac{C\mathcal{E}_1}{2}=\frac{C(2\mathcal{E}_2+\mathcal{E}_1)}{2}.
> $$
>
> Батарея совершила работу
>
> $$
> A_1=\Delta q\mathcal{E}_1=\frac{C\mathcal{E}_1(2\mathcal{E}_2+\mathcal{E}_1)}{2}.
> $$
>
> Обе батареи совершили работу $A=A_1+A_2=C(\mathcal{E}_1+2\mathcal{E}_2)^2/2$.
>
> **6.** По закону сохранения энергии $A=\Delta W+Q$, где $Q$ — выделившееся тепло.
>
> $$
> Q=A-\Delta W=\frac{C(\mathcal{E}_1+2\mathcal{E}_2)^2}{4}.
> $$
