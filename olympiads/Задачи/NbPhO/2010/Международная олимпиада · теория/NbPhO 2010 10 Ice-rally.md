---
id: nbpho-2010-intl-theory-10
olympiad: NbPhO
year: 2010
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "10"
title: "Ice-rally"
points: 7
aliases: ["Ice-rally"]
topics: ["[[1.2 Равноускоренное прямолинейное движение]]", "[[1.1 Равномерное прямолинейное движение]]"]
difficulty: 3
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "По графику ускорения автомобиля определить трение и потерю пути при переключении передачи."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 10. Ice-rally (7 points)

**NbPhO 2010** · Международная олимпиада · теория · 10–12 класс · задача 10  
Источник: [[_pdf/NbPhO/nbpho-2010.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2010.pdf#page=5|решение, стр. 5–6]]

Темы: [[1.2 Равноускоренное прямолинейное движение]], [[1.1 Равномерное прямолинейное движение]]

> [!abstract] Кратко (составлено моделью)
> По графику ускорения автомобиля определить трение и потерю пути при переключении передачи.

The car accelerates on a slippery ground so that the wheels are always at the limit of slipping (e.g. via using an electronic traction control). Such an acceleration would result in the velocity vs time graph as given in the Figure.

![[nbpho-2010-p2-f3.svg]]

**i)** (2 pt) What is the coefficient of friction, assuming a four-wheel drive?

Because of a manual gear change, there is time period of $\tau_1=0.5\,\mathrm{s}$, during which there is no driving force (so that the car decelerates due to air friction). Except for that period, the acceleration follows the law given by the graph. As a result, the terminal velocity $v_t=40\mathrm{m/s}$ is reached $\tau_2=1.0\,\mathrm{s}$ later than it would have been reached, if there were no delay caused by the gear change. Upon reaching the terminal velocity, the car continues moving at constant speed. In your calculations, you can assume that the air friction was constant during the gear change period.

**ii)** (2,5 pt) At which speed the gear was changed?

**iii)** (2,5 pt) How many meters shorter distance will be covered during the first 100 seconds, as compared to ideal acceleration (i.e. without the delay due to the gear change)?

> [!answer]- Ответ
> **i** — $\mu=0.1$.
>
> **ii** — $v_0\approx25\,\mathrm{m/s}$.
>
> **iii** — $S=\tau_2(v_t-v_0)\approx15\,\mathrm{m}$.

> [!solution]- Решение
> # Problem 10. Ice-rally (7 points)
>
> **i. (2 pts)** Since at the very beginning, the effect of the air friction is negligible, the acceleration (i.e. the tangent of the graph) gives us the ratio of the friction force $F_f$ and the mass $m$, i.e. $\mu g$. From the graph, this tangent is $\mu g=1.0\,\mathrm{m/s^2}$, hence
> $\mu=0.1$.
>
> ![[nbpho-2010-p5-f2.svg]]
>
> **ii. (2.5 pts)** When the driving force stops, the acceleration is reduced by $F_f/m=\mu g$, i.e. from the slope at the current point of the graph we need to subtract the slope of it at the origin. A close-up sketch of the graph around the period of gear change is given in Fig. After the gear change, the new graph follows the ideal graph, but is shifted rightwards by $\tau_2$, this shift is marked also in Fig. Since $2\tau_1=\tau_2$, the ascending and descending slopes in that close-up sketch must be of equal steepness, i.e. $a=\mu g/2$. So, the gear change takes place at that speed, when the acceleration is twice smaller than at zero-speed. From the graph we can find that
> $v_0\approx25\,\mathrm{m/s}$.
>
> **iii. (2.5 pts)** The distance difference is the surface area $S$ between the actual $v(t)$ graph, and the ideal one. These graphs coincide for $v<v_0$ and upon achieving the value $v=v_t$. So, the area $S$ is enclosed into the range $v_t>v>v_0$, where the actual graph is, in fact, just the ideal graph, but shifted rightwards by $\tau_2$. This area has a shape of a narrow curved stripe, the horizontal width of which is at every value of $v$ equal to $\tau_2$. One can divide this stripe into tiny horizontal layers of height $\delta$ and width $\tau_2$. If we sum up the surface areas of these layers, we can bring $\tau_2$ before the braces; then, the sum of the layer widths goes into the braces and yields $v_t-v_0$. So, the surface area
> $S=\tau_2(v_t-v_0)\approx15\,\mathrm{m}$.
