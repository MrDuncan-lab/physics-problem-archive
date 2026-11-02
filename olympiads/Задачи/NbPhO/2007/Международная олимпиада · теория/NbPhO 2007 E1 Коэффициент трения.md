---
id: nbpho-2007-intl-theory-e1
olympiad: NbPhO
year: 2007
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "E1"
title: "Коэффициент трения"
points: 12
aliases: ["Коэффициент трения"]
topics: ["[[7 Эксперименты]]", "[[1.10 Статика]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Экспериментально определить коэффициенты трения между доской, бруском и шариком."
status: "проверено: сверка"
lang: ru
tags: [задача]
---

# 4 Коэффициент трения (12 баллов)

**NbPhO 2007** · Международная олимпиада · теория · 10–12 класс · задача E1  
Источник: [[_pdf/NbPhO/nbpho-2007.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2007.pdf#page=3|решение, стр. 3]]

Темы: [[7 Эксперименты]], [[1.10 Статика]]

> [!abstract] Кратко (составлено моделью)
> Экспериментально определить коэффициенты трения между доской, бруском и шариком.

*Оборудование:* деревянный брусок, сферический шарик, доска и линейка (отношение масс бруска и шарика дано).

**1)** Определить коэффициент трения покоя между доской и бруском.

**2)** Определить коэффициент трения покоя между шариком и бруском.

> [!answer]- Ответ
> **1** — $\mu_1\approx0.24$.
>
> **2**
>
> $$
> \mu=\frac{\frac mM+1-\mu_2\cot\beta}{\mu_2(\cot\beta+\frac mM)-1}.
> $$
>
> **2** — $\mu\approx0.2$.

> [!solution]- Решение
> # 4. Coefficient of friction (12 pts)
>
> **1)** This is a straightforward question: we measure the tangent of the slope of the board, when the brick starts sliding, $\mu_1=\tan\alpha_1$, for the given setup,
> $\mu_1\approx0.24$.
>
> **2)** We put the ball and brick together on the slope, the ball touching both the brick and board and being upwards on the slope. So, the ball pushes the brick down and the sliding is expected to take place for somewhat smaller sloping angles. For the given setup, that critical angle turns out to give $\tan\beta\approx0.12$.
>
> Now we need to express $\mu$ knowing $\mu_2\approx0.24$ and $\beta=\arctan0.12$. First we write the torque balance for the ball with respect to the touching point with the board: $mgR\sin\beta=\mu NR+NR$, where $N$ is the pressure force between the ball and the brick. Hence, $N=\frac{mg}{\mu+1}\sin\beta$.
>
> Now, we use the normal (to the board) force balance for the brick, to find the pressure force between the board and the brick: $N_2=Mg\cos\beta+\frac{\mu mg}{\mu+1}\sin\beta$. Finally, we have the tangential force balance for the brick:
> $$\frac{mg}{\mu+1}\sin\beta+Mg\sin\beta=\mu_2g\left(M\cos\beta+\frac{\mu m}{\mu+1}\sin\beta\right).$$
> This equation can be simplified to
> $$\frac mM+\mu+1=\mu_2\left[(\mu+1)\cot\beta+\mu\frac mM\right],$$
> from where
>
> $$\mu=\frac{\frac mM+1-\mu_2\cot\beta}{\mu_2(\cot\beta+\frac mM)-1}.$$
> Using the measured values we get
> $\mu\approx0.2$.
