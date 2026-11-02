---
id: nbpho-2003-intl-theory-5
olympiad: NbPhO
year: 2003
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "5"
title: "Vibration"
points: 10
aliases: ["Vibration"]
topics: ["[[1.2 Равноускоренное прямолинейное движение]]", "[[1.6 Векторная кинематика]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Исследовать среднюю силу трения и движение бруска на колеблющейся поверхности."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 5. Vibration (10 points)

**NbPhO 2003** · Международная олимпиада · теория · 10–12 класс · задача 5  
Источник: [[_pdf/NbPhO/nbpho-2003.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2003.pdf#page=3|решение, стр. 3]]

Темы: [[1.2 Равноускоренное прямолинейное движение]], [[1.6 Векторная кинематика]]

> [!abstract] Кратко (составлено моделью)
> Исследовать среднюю силу трения и движение бруска на колеблющейся поверхности.

Consider a smooth horizontal surface, which is moved periodically back and forth along the horizontal $x$-axis: during the first semi-period $\tau$, the surface velocity is $u$, during the second semi-period — $-u$. A brick of mass $m$ is put on that surface; the friction coefficient between the surface and brick is $\mu$, free falling acceleration is $g$.

**1)** The brick has initial $x$-directional velocity $v$. Which condition between the quantities $g$, $\mu$, $v$, and $\tau$ has to be satisfied in order to ensure that the brick velocity change during a semi-period is negligible? Further we assume that this condition is satisfied.

**2)** The brick is kept in motion along $x$-axis by a force $F_x$ in such a way that the mean brick velocity is $v$. Sketch graphically the dependance $F_x(v)$.

**3)** The brick is kept in motion along (horizontal) $y$-axis by a force $F_y$ in such a way that the mean brick velocity is $v$. Find the dependance $F_y(v)$.

**4)** Until now we have ignored the dependance of the friction coefficient on the sliding velocity. Further let us assume this dependance is given by the graph below. The brick is kept in motion along $x$-axis by a force $F_x$ in such a way that the mean brick velocity is $v$. Sketch graphically the dependance $F_x(v)$ taking $u=\frac34w_0$.

![[nbpho-2003-p1-c7544.png]]

**5)** The brick is put on the surface, there are no external forces. What is the brick’s terminal velocity $v$? Provide the answer as a function of $u$.

> [!answer]- Ответ
> **1** — $\mu mg\tau\ll v$.
>
> **2** — $F=0$, when $|v|<u$; $F=\mu mg$, when $|v|>u$.
>
> **3** — $F=\mu mgv/\sqrt{v^2+u^2}$.

> [!solution]- Решение
> # 5. Vibration (10 pts)
>
> **1)**
> $\mu mg\tau\ll v$.
>
> **2)**
> $F=0$, when $|v|<u$; $F=\mu mg$, when $|v|>u$.
>
> **3)** The $x$-component of the frictional force cancels in average out, the $y$-component is left:
> $F=\mu mgv/\sqrt{v^2+u^2}$.
>
> **4)** $F=[\mu(v+u)+\mu(v-u)]mg$, if $v>u$ and $F=[\mu(u+v)-\mu(u-v)]mg$, if $v<u$ ($F>0$ means that $F$ and $v$ are opposite to each other). It is easy to see that by small values of $v$, the force starts linearly decreasing [with $F(v=0)=0$] ($F<0$ implies that force and velocity are in the same direction). At $u=v$, the graph exerts a jump, $F$ becomes positive, and starts decreasing. The attached graph presents a sketch of the effective friction coefficient; the construction has been based on the lengths $\mu_{k1}=\mu(w_0/2)-\mu(w_0)$, $\mu_{k2}=\mu(w_0/4)-\mu(5w_0/4)$, and $\mu_{k3}=\mu(0)-\mu(3w_0/2)$.
>
> ![[nbpho-2003-p3-f3.svg]]
>
> **5)** The rest position is unstable, if $u<w_0$: the particle obtains the (stable) velocity $u$. If $u>w_0$, the rest position is stable, and the particle velocity remains 0.
