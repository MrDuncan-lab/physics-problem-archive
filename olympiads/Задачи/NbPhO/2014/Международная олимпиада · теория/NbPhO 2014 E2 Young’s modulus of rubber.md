---
id: nbpho-2014-intl-theory-e2
olympiad: NbPhO
year: 2014
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "E2"
title: "Young’s modulus of rubber"
points: 12
aliases: ["Young’s modulus of rubber"]
topics: ["[[7 Эксперименты]]", "[[1.15 Упругость. Весомая пружина]]", "[[6.5 Волновая оптика]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Экспериментально определить зависимость напряжения от деформации и модуль Юнга резиновой нити."
status: "проверено: сверка, два чтения + арбитр"
lang: en
tags: [задача]
---

# 10. YOUNG’S MODULUS OF RUBBER (12 points)

**NbPhO 2014** · Международная олимпиада · теория · 10–12 класс · задача E2  
Источник: [[_pdf/NbPhO/nbpho-2014.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2014.pdf#page=4|решение, стр. 4]]

Темы: [[7 Эксперименты]], [[1.15 Упругость. Весомая пружина]], [[6.5 Волновая оптика]]

> [!abstract] Кратко (составлено моделью)
> Экспериментально определить зависимость напряжения от деформации и модуль Юнга резиновой нити.

The linear Hooke’s law for a rope made from an elastic material is supposed to held for small relative deformations $\varepsilon=x/L$ (which is also called “strain”), where $L$ is the undeformed length of the rope, and $x$ is the deformation. Once $\varepsilon$ becomes too large, the force-deformation relationship $F=kx$ is no longer linear; what is “too large” depends on the material. For very elastic materials which can reach relative deformations considerably large than one, it may happen that the linear Hooke’s law with a constant stiffness $k$ fails, but if we take into account the change of the cross-sectional area $S$ of the rope with $k=ES/L$, where $E$ is the Young’s modulus of the elastic material, such a non-linear Hooke’s law remains valid. In that case we can say that there is still a linear stress-strain relationship $\sigma=E\cdot\varepsilon$, where the stress $\sigma=F/S$.

**i)** (7 points) Measure the relationship between the stress $\sigma$ and strain $\varepsilon$ in a rubber string and plot it.

**ii)** (5 points) From your plot determine the Young’s modulus $E$ with its uncertainty, and the maximum strain $\varepsilon_m$ until which it applies.

*Note:* the diameter of the thread is to be measured using the diffraction of laser light.

*Equipment:* rubber thread, stand, measuring tape, 15 hex nuts with a known mass, a plastic bag for hanging a set of nuts to the thread, a green laser ($\lambda=532\,\mathrm{nm}$), a screen.

**WARNING: AVOID LOOKING INTO A LASER BEAM, THIS MAY DAMAGE YOUR EYES!**

> [!solution]- Решение
> # 10. Young’s modulus of rubber
>
> **1)** The setup is as follows. The rubber thread is fixed to the stand, and the plastic bag is fixed to the free end of the thread. The hex nuts are added, one-by-one, into the bag, starting with zero and ending with 15. The laser light is directed to the thread and the diffraction pattern is observed on the screen (which is a vertically fixed sheet of graphic paper on a support). The diffraction pattern from a wire is the same as from a single slit (the superposition of the Huygens sources from those two cases gives a full set of sources on a flat wave front, hence the electric fields from those two cases must provide equal and opposite wave amplitudes and equal intensities). So, if we measure on the screen the distance $a$ between such maxima which are separated by $n$ (e.g. $n=10$) periods of the diffraction pattern then using small-angle-approximation, $n\lambda/d=a/L$, where $L$ is the distance from the thread to the screen and $d$ — the thread diameter. So,
>
> $$d=nL\lambda/a.$$
>
> The strain is calculated by making markings on the thread and measuring the distance $b$ between these in a stretched state,
>
> $$\varepsilon=\frac{b-b_0}{b_0},$$
>
> where $b_0$ is the length in a non-strained state. The stress is calculated as
>
> $$\sigma=\frac{4Nmg}{\pi d^2},$$
>
> where $N$ is the number of hex nuts in the bag and $m$ — the mass of a single nut. The data are plotted in a graph; linear relationship corresponds to a straight line. The uncertainties are calculated using the rule of relative uncertainties, either using Pythagorean or simple addition, e.g.
>
> $$\Delta\varepsilon=\varepsilon\Delta b\left(\frac{2}{b-b_0}+\frac{1}{b_0}\right),$$
>
> where $\Delta b\approx0.5\,\mathrm{mm}$ is the length measurement uncertainty. Similarly,
>
> $$\Delta\sigma=2\sigma\frac{\Delta d}{d}.$$
>
> These uncertainties are marked in the graph as error bars.
>
> **2)** Using the plot, we need to determine such a value of $\varepsilon=\varepsilon_*$ that for $\varepsilon_1>\varepsilon_*$, it is impossible to draw a straight line intersecting the error bars of all the data points with $\varepsilon_1<\varepsilon_*$.
