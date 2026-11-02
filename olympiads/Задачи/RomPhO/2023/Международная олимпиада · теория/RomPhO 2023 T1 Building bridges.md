---
id: rompho-2023-intl-theory-t1
olympiad: RomPhO
year: 2023
stage: "Международная олимпиада"
round: теория
grade: ""
number: "T1"
title: "Building bridges"
aliases: ["Building bridges"]
topics: ["[[1.10 Статика]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Найти форму троса подвесного моста и максимальное натяжение, исследовать его зависимость от высоты башен и учесть вес подвесок."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# Problem 1. Building bridges

**RomPhO 2023** · Международная олимпиада · теория · задача T1  
Источник: [[_pdf/RomPhO/RomPhO-2023-T1.pdf#page=1|условие, стр. 1]] · [[_pdf/RomPhO/RomPhO-2023-T1-solutions.pdf#page=2|решение, стр. 2–3]]

Темы: [[1.10 Статика]]

> [!abstract] Кратко (составлено моделью)
> Найти форму троса подвесного моста и максимальное натяжение, исследовать его зависимость от высоты башен и учесть вес подвесок.

The goal of this problem is to analyze a variety of properties in suspension bridges, a type of bridge in which the deck is hung below a curved suspension cable using vertical suspenders.

![[rompho-2023-t1-problems-p1-f1.png]]

To model the bridge, assume the following:

- There are two suspension cables, and the tension is distributed equally between the two. The weight of the suspension cables is much smaller than that of the deck, whose density per unit length is $\lambda$.
- In parts a) - c), assume that the weight of the vertical suspenders is negligible. Do not assume that in part d).
- The weight of the deck is uniformly supported by a large number of vertical suspenders for which the distance between consecutive suspenders is much smaller than the length of the bridge.
- The deck is perfectly horizontal.
- The suspension cable spans the length between two towers.
- The lowest point on the suspension cable is at the same vertical position as the deck.

Your task is to find the following:

**a)** Find an equation, $y(x)$, that describes the shape of the suspension cable. Your final result can depend on three constants that, in this part of the problem, can be left undetermined.

**b)** Assume that the two towers of the bridge have the same height $h$ (above the suspension deck), and that the length of the deck in between the two towers is $L$. Assuming that $y=0$ is the level of the deck and that $x=0$ is the middle of the deck, find the shape of the suspension cable $y(x)$ solely in terms of $L$ and $h$.

**c)** Find the maximum tension in the suspension cable in terms of the height of the bridge $h$, the length of the bridge $L$, the density per unit length $\lambda$, and the gravitational acceleration $g$. Where is the maximum tension achieved? Sketch this maximum tension for fixed $L$, in terms of the height $h$. What is the height of the towers $h_{\max}$ where the tension is maximized, and what is their height $h_{\min}$ when the tension is minimized?

**d)** The total weight of the vertical suspenders is initially much smaller than that of the deck. However, after a reconstruction project, the suspenders are reinforced, and their weight can no longer be neglected. Since the new suspenders are solid metal rods, you can assume that the shape of the suspension cable does not change. Assume that the total number of suspenders per unit length is $n$ and that the mass per unit length of the suspenders is $w$, with $w\ll\lambda$. What is the new maximum tension in the suspension line? What height $h_{\min}^{\mathrm{new}}$ do the two towers need to be such that the maximum tension in the suspension cable is minimized?

Proposed by Luca Victor Iliesiu, Stanford University

> [!answer]- Ответ
> **a**
>
> $$
> y(x)=A(x-x_0)^2+B,
> $$
>
> **b**
>
> $$
> y(x)=\frac{4h}{L^2}x^2.
> $$
>
> **c**
>
> $$
> T_{\max}=\frac{\lambda gL}{4}\sqrt{\left(\frac L{4h}\right)^2+1}.
> $$
>
> **d**
>
> $$
> T_{\max}=\frac{\lambda gL}{4}\sqrt{\left(\frac L{4h}\right)^2+1}\left(1+\frac{hwn}{3\lambda}\right).
> $$
>
> **d**
>
> $$
> h_{\min}^{\mathrm{new}}=\frac12\left(\frac{3\lambda L^2}{2nw}\right)^{1/3}.
> $$

> [!solution]- Решение
> # Solution to problem 1. Building bridges
>
> **a)** [3 points] Let $T_0$ be the tension in the portion of the suspension wire where it goes horizontal and the coordinate of that point be $x_0$. Let $T$ be the tension in the wire at some position $x$ (wlog we will assume $x>x_0$), at which the angle formed between the wire and horizontal axis is $\phi$, with $\tan\phi=dy/dx$. The total weight of the deck between points $x_0$ and $x$ is $G=\lambda g(x-x_0)$. Equating the tensions and gravitational forces yields,
>
> $$
> 2T\cos\phi=2T_0,\qquad 2T\sin\phi=\lambda g(x-x_0).
> $$
>
> where the factors of 2 come from the fact that we have 2 parallel suspension cables. Taking the ratio between the two equations to eliminate $T$ yields
>
> $$
> \frac{dy}{dx}=\frac{\lambda g}{2T_0}(x-x_0),
> $$
>
> whose solution is given by
>
> $$
> y(x)=A(x-x_0)^2+B,
> $$
>
> with $A$ and $B$ unknown. Note that $A$ is given by
>
> $$
> A=\frac{\lambda g}{4T_0},
> $$
>
> while $B$ is an integration constant.
>
> **b)** [2 points] The above equation has $x_0=0$ and $y(x=0)=0$ from which we find $B=0$. At the top of the bridge towers, we have
>
> $$
> h=A\frac{L^2}{4},
> $$
>
> from which $A=\frac{4h}{L^2}$. Thus, we have
>
> $$
> y(x)=\frac{4h}{L^2}x^2.
> $$
>
> This also determines $T_0=\frac{\lambda gL^2}{16h}$.
>
> **c)** [2.5 points] We can square the first two equations above to write the magnitude of the tension at position $x$ as,
>
> $$
> T^2=T_0^2+\frac{(\lambda gx)^2}{4},
> $$
>
> which can be simplified to
>
> $$
> T=\frac{\lambda g}{2}\sqrt{\left(\frac{L^2}{8h}\right)^2+x^2}.
> $$
>
> This is a monotonically increasing function of $x$, and therefore the maximum tension is always achieved at the ends of the bridge, $x=\pm L/2$. The magnitude of the tension there is
>
> $$
> T_{\max}=\frac{\lambda gL}{4}\sqrt{\left(\frac L{4h}\right)^2+1}.
> $$
>
> This is again a monotonically decreasing function in $h$ (for $h>0$). Its maximum is therefore achieved at $h_{\max}=0$ where $T\to\infty$, while the minimum is achieved when $h_{\min}\to\infty$, where $T=\frac{\lambda gL}{4}$. When $h_{\min}\to\infty$, the suspension cables are almost vertical, and the sum of the tensions at the four ends is equal to the weight of the bridge – thus $4T=\lambda gL$, which provides a nice consistency check.
>
> **d)** [2.5 points] The additional gravitational force along the segment between $x=0$ and some point $x$ (once again, with $x>0$) is
>
> $$
> G_{\mathrm{corr}}=\int dx\ wngy=\frac{4wngh}{3L^2}x^3.
> $$
>
> From the previous result, we have seen that
>
> $$
> \cos\phi=\frac{L^2}{8h\sqrt{\left(\frac{L^2}{8h}\right)^2+x^2}},\qquad \sin\phi=\frac{8hx}{\sqrt{L^4+64h^2x^2}}.
> $$
>
> The balance of forces now dictates that
>
> $$
> T=\frac{\lambda g}{2}\sqrt{\left(\frac{L^2}{8h}\right)^2+x^2}\left(1+\frac{4hwn}{3\lambda L^2}x^2\right).
> $$
>
> Once again, the maximum is at $x=\pm L/2$, which implies
>
> $$
> T_{\max}=\frac{\lambda gL}{4}\sqrt{\left(\frac L{4h}\right)^2+1}\left(1+\frac{hwn}{3\lambda}\right).
> $$
>
> The function is no longer monotonically decreasing in $h$. Its minimum is given by $\partial T_{\max}/\partial h=0$ which results in
>
> $$
> h_{\min}^{\mathrm{new}}=\frac12\left(\frac{3\lambda L^2}{2nw}\right)^{1/3}.
> $$
>
> Note that as $w\to0$, $h_{\min}^{\mathrm{new}}\to\infty$, which is consistent with the previous result. Thus, in this more realistic bridge model, where we take into account the additional weight of the suspension cables, we see that the towers get corrected to a finite height.
