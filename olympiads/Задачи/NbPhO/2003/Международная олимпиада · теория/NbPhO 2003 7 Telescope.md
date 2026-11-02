---
id: nbpho-2003-intl-theory-7
olympiad: NbPhO
year: 2003
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "7"
title: "Telescope"
points: 12
aliases: ["Telescope"]
topics: ["[[6.3 Линзы]]", "[[6.5 Волновая оптика]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Оценить яркость изображения звезды на фоне дневного неба для телескопа и глаза."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 7. Telescope (12 points)

**NbPhO 2003** · Международная олимпиада · теория · 10–12 класс · задача 7  
Источник: [[_pdf/NbPhO/nbpho-2003.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2003.pdf#page=4|решение, стр. 4]]

Темы: [[6.3 Линзы]], [[6.5 Волновая оптика]]

> [!abstract] Кратко (составлено моделью)
> Оценить яркость изображения звезды на фоне дневного неба для телескопа и глаза.

As it is well known, a telescope makes it possible to see the stars in daylight. Let us study the problem in more details. Consider a simplified model of the eye: a single lens with focal length $f=4\,\mathrm{cm}$ and diameter $d=3\,\mathrm{mm}$ creating an image on screen (retina). The model of a telescope is similar: a lens of focal length $F=2\,\mathrm m$ and diameter $D=20\,\mathrm{cm}$ creating an image in focal plane (where eg. a film can be put). In your calculations, the following quantities can be used: the density of the light energy radiated from a unit Solar surface in unit time $w_0$ (the light power surface density); the ratio of the star and Sun distances $q=4\cdot10^5$ (we assume that the star is identical to the Sun); Solar angular diameter $\phi\approx9\,\mathrm{mrad}$. Remark: If the answer contains $w_0$ then numerical answer is not required.

**1)** Consider a sheet of paper, the normal of which is directed towards the Sun. What is the surface density of the light power $w_1$ arriving to the sheet from the Sun?

**2)** Find the net power $P_2$ of the light, which is focused by the telescope into the image of the star.

**3)** Assume that blue sky is as bright as a sheet of gray paper illuminated by Sun. You may assume that in the direction, perpendicular to the sheet, the ratio of the light power scattered by the paper into a 1-steradian space angle, to the net light power arriving to the sheet, is $\alpha\approx0{,}1$ (this corresponds to the dissipation of ca 70 % light energy in the gray paper). What is the surface density of the light power in the focal plane of the telescope $w_3$, due to the blue sky?

**4)** While studying the star image, let us ignore all the effects other than diffraction. Estimate the surface density of the light power in the center of the star image $w_2$ (in the focal plane of the telescope), due to the light arriving from the star.

**5)** Provide an expression for the ratio of the surface densities of the light powers $k$ in the middle of the star image, and in a point farther away from it.

**6)** Is it possible to see a star in daylight using a telescope? Plain eye? Motivate yourself.

> [!answer]- Ответ
> **1** — $w_1=w_0\phi^2/4$.
>
> **2** — $P_2=\frac14\pi D^2w_1q^{-2}=w_0\pi(\phi D/4q)^2$.
>
> **3** — $w_3=P_3/s=w_1\alpha(\frac\pi4D^2/F^2)=w_0\alpha\pi(\phi D/4F)^2$.
>
> **4** — $w_2=P_2/\pi\delta^2=w_0(\phi D^2/4qF\lambda)^2$.
>
> **5** — $k=(w_2+w_3)/w_3=1+(\alpha\pi)^{-1}(D/\lambda q)^2\approx4$ (assuming $\lambda\approx500\,\mathrm{nm}$).

> [!solution]- Решение
> # 7. Telescope (12 pts)
>
> **1)** The light flux density decreases inversely proportionally to the square of the distance, therefore $w_1=w_0R_p^2/L_p^2$, where $R_p$ is the solar radius, and $L_p$ — the solar distance. Due to $\phi=2R_p/L_p$, we obtain
> $w_1=w_0\phi^2/4$.
>
> **2)** The previous result can be applied to the star flux density, which is $q^{-2}w_1$; hence
> $P_2=\frac14\pi D^2w_1q^{-2}=w_0\pi(\phi D/4q)^2$.
>
> **3)** The paper surface area $S$ radiates towards the lens of the telescope the power $P_3=w_1\alpha S(\frac\pi4D^2/L^2)$, where $L$ is the telescope distance. The image of this piece of paper has size $s=SF^2/L^2$; thus,
> $w_3=P_3/s=w_1\alpha(\frac\pi4D^2/F^2)=w_0\alpha\pi(\phi D/4F)^2$.
>
> **4)** The angular distance of the first diffraction minimum (using the single slit approximation — circle is actually not a slit) is $\lambda/D$. Hence, the bright circle radius can be estimated as $\delta=F\lambda/D$. Consequently,
> $w_2=P_2/\pi\delta^2=w_0(\phi D^2/4qF\lambda)^2$.
>
> **5)**
> $k=(w_2+w_3)/w_3=1+(\alpha\pi)^{-1}(D/\lambda q)^2\approx4$ (assuming $\lambda\approx500\,\mathrm{nm}$).
>
> **6)** $k-1\sim1$ (or $k-1>1$) means that the star can be easily seen (as is the case for the telescope); $k-1\ll1$ means that the star cannot be seen (for the eye, $k-1\approx1\cdot10^{-4}$).
