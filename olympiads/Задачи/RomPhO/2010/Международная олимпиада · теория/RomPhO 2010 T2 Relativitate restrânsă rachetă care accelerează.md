---
id: rompho-2010-intl-theory-t2
olympiad: RomPhO
year: 2010
stage: "Международная олимпиада"
round: теория
grade: ""
number: "T2"
title: "Relativitate restrânsă: rachetă care accelerează"
aliases: ["Relativitate restrânsă: rachetă care accelerează"]
topics: ["[[1 Механика]]", "[[6 Оптика]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Исследовать релятивистское движение ускоряющейся ракеты и обмен отражёнными световыми сигналами между ней и Землёй."
status: "проверено: сверка"
lang: ro
tags: [задача]
---

# RELATIVITATE RESTRÂNSĂ: RACHETĂ CARE ACCELEREAZĂ

**RomPhO 2010** · Международная олимпиада · теория · задача T2  
Источник: [[_pdf/RomPhO/RomPhO-2010-T2.pdf#page=1|условие, стр. 1]] · [[_pdf/RomPhO/RomPhO-2010-T2-solution.pdf#page=2|решение, стр. 2–4]]

Темы: [[1 Механика]], [[6 Оптика]]

> [!abstract] Кратко (составлено моделью)
> Исследовать релятивистское движение ускоряющейся ракеты и обмен отражёнными световыми сигналами между ней и Землёй.

La momentul de timp $t=0$ în sistemul de referință al Pământului, o rachetă aflată inițial în repaus pornește de pe Pământ într-o călătorie prin spațiu, pe o traiectorie rectilinie. Oriunde nu se va menționa altceva, racheta va fi considerată punctiformă. Presupuneți ipoteza simplificatoare că forța de tracțiune a motoarelor și masa de repaus a rachetei sunt constante în timp în sistemul de referință al Pământului. Neglijați orice influență gravitațională și/sau atmosferică. Fie $c$ viteza de propagare a luminii în vid, și $a$ accelerația inițială a rachetei.

**a.** Desenați schematic graficul vitezei rachetei în funcție de timp în sistemul de referință al Pământului.

**b.** Cât „cântărește“ un astronaut cu masa de repaus $m$ la bordul navei?

**c.** Exprimați coordonata $x$ a rachetei pe axa de mișcare, ca funcție de timpul de pe Pământ $t$, în funcție de $t$, $c$, și $a$. (Pământul se consideră ca fiind originea axei.)

**d.** Desenați pe o diagramă spațiu-timp linia de univers a rachetei, reprezentând doar coordonatele de interes, $x$ și $ct$.

**e.** Determinați ultimul moment de timp $t_0$ la care ar mai putea fi emis de pe Pământ un semnal luminos, astfel încât el să mai poată ajunge din urmă racheta.

La momentul de timp $c/2a$ în sistemul Pământului, o stație radio de pe Pământ inițiază un proces recurent de comunicare cu racheta: stația emite un flux monocromatic de fotoni care, atunci când sunt recepționați de rachetă, sunt reflectați imediat înapoi către Pământ. Fotonii ajung la stația radio și sunt reflectați imediat înapoi către rachetă, iar procesul se repetă. Atunci când sunt emiși prima dată, fotonii au frecvența $\nu_0$ în sistemul de referință al Pământului.

**f.** Determinați momentul de timp $T'$ în sistemul de referință al rachetei, la care ea recepționează prima dată un semnal de pe Pământ. (La lansare, ceasurile de pe rachetă sunt perfect sincronizate cu cele de pe Pământ.)

**g.** Adăugați pe graficul de la punctul d linia de univers a unui foton din momentul când este emis de pe Pământ și până când este recepționat prima dată de navă.

**h.** Determinați frecvența ultimului flux de fotoni recepționați de rachetă.

**i.** Determinați frecvența ultimului flux de fotoni recepționați de stația radio.

> [!answer]- Ответ
> **b**
>
> $$
> a'_x(t)=\frac{a_x}{\left(1-\frac{v_x^2}{c^2}\right)^{3/2}}=a\Rightarrow W=ma.
> $$
>
> **c**
>
> $$
> v_x=\frac{dx}{dt}\Rightarrow dx=c\frac{\frac{at}c}{\sqrt{1+\left(\frac{at}c\right)^2}}dt\Rightarrow x(t)=\frac{c^2}{a}\left[\sqrt{1+\left(\frac{at}c\right)^2}-1\right].
> $$
>
> **f**
>
> $$
> dt'=dt\sqrt{1-\frac{v_x^2}{c^2}}=\frac{dt}{\sqrt{1+\left(\frac{at}c\right)^2}}\Rightarrow T'=\int_0^{\frac34\frac ca}dt'=\frac ca\ln2\approx0.7\frac ca.
> $$
>
> **h**
>
> $$
> \nu'=\nu_0\sqrt{\frac{c-v_x}{c+v_x}}=\frac12\nu_0.
> $$
>
> **i**
>
> $$
> \nu=\frac14\nu_0.
> $$

> [!solution]- Решение
> # SPECIAL RELATIVITY: ACCELERATING SPACESHIP
>
> All quantities in the rocket’s reference frame will be denoted with a prime (’).
>
> **a.** 1p
>
> ![[rompho-2010-t2-solutions-p2-f2.svg]]
>
> **b.** 2p
>
> The momentum of the rocket increases uniformly with time.
> $$\frac{dp_x}{dt}=\text{const}\Rightarrow\frac{v_x}{\sqrt{1-\left(\frac{v_x}{c}\right)^2}}=at\Rightarrow v_x(t)=c\frac{\frac{at}c}{\sqrt{1+\left(\frac{at}c\right)^2}}.$$
> (We took into account the fact that $v_x(0)=0$.) The rocket’s acceleration in the Earth’s reference frame is
> $$a_x(t)=\frac{dv_x}{dt}=\frac a{\left(1+\left(\frac{at}c\right)^2\right)^{3/2}}.$$
> The Lorentz transformation for the accelerations on the $x$-axis is
> $$a_x=a'_x\left(\frac{\sqrt{1-\frac{V^2}{c^2}}}{1+\frac V{c^2}v'_x}\right)^3.$$
> For $V=v_x$, we get $v_x'=0$, so the astronaut’s “weight” will be given by
>
> $$a'_x(t)=\frac{a_x}{\left(1-\frac{v_x^2}{c^2}\right)^{3/2}}=a\Rightarrow W=ma.$$
>
> **c.** 1p
>
> $$v_x=\frac{dx}{dt}\Rightarrow dx=c\frac{\frac{at}c}{\sqrt{1+\left(\frac{at}c\right)^2}}dt\Rightarrow x(t)=\frac{c^2}{a}\left[\sqrt{1+\left(\frac{at}c\right)^2}-1\right].$$
>
> **d.** 1p
>
> The distance increases asymptotically with time:
> $$\lim_{t\to\infty}\frac{x(t)}t=c;\quad\lim_{t\to\infty}(x(t)-ct)=-\frac{c^2}a.$$
> The asymptote’s equation is
> $$x(t)=ct-\frac{c^2}a=c\left(t-\frac ca\right).$$
> For the drawing, see **g**.
>
> **e.** 1p
>
> As seen on the diagram, in the long run the spaceship’s motion gets infinitely close to the motion of a light signal emitted from Earth at Earth time $c/a$.
>
> **f.** 1.5p
>
> The Earth time when the first signal reaches the rocket is given by
> $$x(t)=c\left(t-\frac c{2a}\right)\Rightarrow t=\frac34\frac ca.$$
> The position and the velocity of the rocket at that moment are
> $$x\left(\frac34\frac ca\right)=\frac{c^2}{4a}\quad\text{and}\quad v_x\left(\frac34\frac ca\right)=\frac35c$$
> respectively. In order to find $T'$, for each infinitely small time interval $dt$ in Earth’s reference frame we will have to add up the corresponding time interval $dt'$ in the rocket’s reference frame.
>
> $$dt'=dt\sqrt{1-\frac{v_x^2}{c^2}}=\frac{dt}{\sqrt{1+\left(\frac{at}c\right)^2}}\Rightarrow T'=\int_0^{\frac34\frac ca}dt'=\frac ca\ln2\approx0.7\frac ca.$$
>
> **g.** 0.5p
>
> ![[rompho-2010-t2-solutions-p3-f1.svg]]
>
> **h.** 1p
>
> From the Doppler Effect formula it follows that
>
> $$\nu'=\nu_0\sqrt{\frac{c-v_x}{c+v_x}}=\frac12\nu_0.$$
>
> **i.** 1p
>
> Applying once again the Doppler Effect formula, we get
>
> $$\nu=\frac14\nu_0.$$
