---
id: nbpho-2023-intl-theory-7
olympiad: NbPhO
year: 2023
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "7"
title: "A stack of papers"
points: 8
authors: ["Taavet Kalda", "Jaan Kalda"]
aliases: ["A stack of papers"]
topics: ["[[1.13 Кинематические связи (и динамика)]]", "[[1.17 Законы сохранения энергии и импульса]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: true
source_damaged: false
summary: "Исследовать движение стопки при вытягивании нижнего листа и найти условия полного извлечения."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 7. A stack of papers (8 points) — Taavet Kalda and Jaan Kalda.

**NbPhO 2023** · Международная олимпиада · теория · 10–12 класс · задача 7  
Источник: [[_pdf/NbPhO/nbpho-2023.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2023.pdf#page=9|решение, стр. 9]]

Темы: [[1.13 Кинематические связи (и динамика)]], [[1.17 Законы сохранения энергии и импульса]]

> [!abstract] Кратко (составлено моделью)
> Исследовать движение стопки при вытягивании нижнего листа и найти условия полного извлечения.

There is a pack of $N\gg1$ identical sheets of papers lying on an infinite horizontal table. The coefficient of friction between the surface of the table, and between two sheets of paper are both equal to $\mu$. Each sheet has dimensions $L\times W$, with $L>W$. Sandra is trying to fetch the bottom-most sheet by pulling from a shorter edge of it with a constant velocity $u$ (while all the sheets lie almost exactly on top of each other, she managed to get hold of an edge of the bottom-most sheet).

**i)** (2 points) Sketch a qualitative graph of how the acceleration $a$ of the pack (excluding the bottom-most sheet) depends on time when

(a) the speed $u$ is very small.

(b) the speed $u$ is very big.

**ii)** (3 points) What is the minimal speed $u_{min}$ by which it is possible to pull the bottom-most sheet out (i.e. separating it completely from the remaining pack)?

**iii)** (1 point) Assuming $u>u_{min}$, what is the speed of the remaining pack at the moment when the bottom-most sheet gets out of the pack (i.e. there is no longer overlapping areas)?

**iv)** (2 points) Considering still $u>u_{min}$, what is the minimal distance $l$ between the pack of papers and the edge of the table such that the pack would not slide over the edge of the table? ($l$ is the maximal allowed travel distance of the pack.)

> [!answer]- Ответ
> **ii**
>
> $$
> u_{\min}=\frac{\sqrt{k}L}{2}=\sqrt{\frac{g\mu L}{2}}.
> $$
>
> **iii** — Surprisingly, the final speed of the pack in the table frame is therefore 0.
>
> **iv**
>
> $$
> l=ut_1-L=\frac{2u}{\omega}\tanh^{-1}\left(\frac{L\omega}{2u}\right)-L
> $$
>
> $$
> =L\left(\frac{2u}{L\omega}\tanh^{-1}\left(\frac{L\omega}{2u}\right)-1\right).
> $$

> [!solution]- Решение
> # 7. A pack of papers (8 points) — Solution by Taavet Kalda, grading schemes by Martin Rahe, Isak Fleig and Joonas Kalda.
>
> **i)** (2 points) Clearly, when $u$ is very small, the pack gets dragged along with the bottom-most sheet, so the speed $v$ of the pack starts from 0, and ends up with $u$. Further, there is almost no slippage between the pack and the bottom sheet. The acceleration of the top sheet is then $g\mu$ as long as its being accelerated, and 0 otherwise. The acceleration lasts for a duration of $u/(g\mu)$.
>
> ![[nbpho-2023-p9-f2.svg]]
>
> Conversely at very large $v$, the bottom-most sheet gets pulled out so fast that the pack ends with very little speed. As the sheets gets pulled from under, the acceleration of the pack drops from $u/(g\mu)$ to $-u/(g\mu)$ over a duration of $L/u$.
>
> ![[nbpho-2023-p9-c2604.png]]
>
> **ii)** (3 points) The problem is most conveniently analysed in a frame moving with the bottom-most sheet with speed $u$. In the new frame, $v'=v-u$ and $x'=x-ut$. Let the centre-point of the bottom-most sheet be $x'=0$ and let’s track the movement of the pack using its right-most edge which will start at $x'=L/2$ with a speed of $v'=-u$ and lose contact with the bottom sheet at $x'=-L/2$.
>
> When the pack is in contact with the bottom-most sheet and in the process of slipping, the pack has a normal force of $N_1=mg(L/2+x')/L$ with the bottom-most sheet, and $N_2=mg(L/2-x')/L$ with the table. Friction force will then result in a net force of $F=N_1\mu-N_2\mu=2mg\mu x'/L$. The acceleration of the pack is thus $a'=2g\mu x'/L$. Note that this equation is that of a spring with a negative spring coefficient $k=2g\mu/L$ (which we will still denote with a positive $k$ value, only that the force repels from the equilibrium). Nevertheless, conservation of energy still holds, $v'^2/2-kx'^2/2=\mathrm{const}$. The most critical point to overcome is at $x'=0$ (after that the force starts helping the pack), which makes sense because then most of the bottom-most paper is out from underneath the pack, and the friction force from the table is dominant. The condition for this is simply $v'^2-kx'^2>0$ or in other words, $u^2-kL^2/4>0$. This gives
>
> $$u_{\min}=\frac{\sqrt{k}L}{2}=\sqrt{\frac{g\mu L}{2}}.$$
>
> **iii)** (1 point) As before, conservation of energy holds. This means that when the bottom sheet is separated at $x'=-L/2$, the potential energy is the same as when $x'=L/2$ so the speed of the pack is still $-u$.
> Surprisingly, the final speed of the pack in the table frame is therefore 0.
>
> **iv)** (2 points) The goal is to find the overall distance by which the pack slides in the table frame. Equivalently, we can find the duration $t_1$ for which it slides, because then it will have shifted by $-L$ in the paper frame, and the paper frame has shifted by $ut_1$ with respect to the table frame. The overall shift is then $l=ut_1-L$.
>
> The equation of motion for the pack was $a'=kx'$ with $k=2g\mu/L$. The solution for this is, instead of sine and cosine, hyperbolic sine and cosine. Seeing from the initial conditions, a possible solution could be $x'=x_0\sinh(\omega(t-\Delta t))$. This indeed gives $v'=\omega x_0\sinh(\omega(t-\Delta t))$ and $a'=\omega^2x'$ such that $\omega=\sqrt{k}$ satisfies the equation of motion. We find the values for $x_0$ and $\Delta t$ from the initial conditions at $t=0$ so that $x'=-x_0\sinh(\omega\Delta t)=L/2$ and $v'=x_0\omega\cosh(\omega\Delta t)=-u$. From here, we get
>
> $$\Delta t=\frac1\omega\tanh^{-1}\left(\frac{L\omega}{2u}\right),$$
> $$x_0=-\frac{L_0}{2\sinh(\omega\Delta t)}.$$
>
> Now, from the form of $x'$, it’s clear that it will pass $x'=0$ at $t=\Delta t$, and reach $x'=-L/2$ at $t=2\Delta t$. Therefore, $t_1=2\Delta t$ and the minimal distance between the paper pack and the edge has to be
>
> $$l=ut_1-L=\frac{2u}{\omega}\tanh^{-1}\left(\frac{L\omega}{2u}\right)-L$$
> $$=L\left(\frac{2u}{L\omega}\tanh^{-1}\left(\frac{L\omega}{2u}\right)-1\right).$$

> [!grading]- Критерии оценивания
> **Grading:**
> - Correct initial accelerations **(0.2 pts)**
> - Correct final accelerations **(0.2 pts)**
> - Correct durations of acceleration **(0.4 pts)**
> - Correct graph shapes **(0.6 pts)**
> - Physical explanations for the graph shapes **(0.6 pts)**
>
> (half of the points in each subsection are given for part (a) and half for part (b))
>
> **ii)**
>
> **Grading:**
> - switching to the reference frame of the bottom-most sheet **(0.4 pts)**
> - Correct normal forces with bottom-most sheet and table **(0.6 pts)**
> - Correct net force on pack **(0.2 pts)**
> - Identifying the spring coefficient **(0.3 pts)**
> - Conservation of energy equation **(0.5 pts)**
> - Identifying critical point $x=0$ **(0.6 pts)**
> - Deriving $u_{min}$ **(0.4 pts)**
>
> **iii)**
>
> **Grading:**
> - Potential energy when the sheet is separated is the same as when Sandra starts pulling **(0.6 pts)**
> - Correct final speed in the bottom-most sheet reference frame **(0.2 pts)**
> - Correct final speed in the table reference frame **(0.2 pts)**
>
> **iv)**
>
> **Grading:**
> - Stating the formula $l=ut_1-L$ **(0.2 pts)**
> - Stating the equation of motion $a'=kx'$ **(0.2 pts)**
> - Solution for the equation of motion **(0.4 pts)**
> - Correct values for $x_0$ and $\Delta t$ **(0.6 pts)**
> - Justification for $t_1=2\Delta t$ **(0.3 pts)**
> - Correct result for the minimal distance $l$ **(0.3 pts)**
