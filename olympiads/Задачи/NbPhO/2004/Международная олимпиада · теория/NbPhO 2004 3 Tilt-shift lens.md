---
id: nbpho-2004-intl-theory-3
olympiad: NbPhO
year: 2004
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "3"
title: "Tilt-shift lens"
points: 6
aliases: ["Tilt-shift lens"]
topics: ["[[6.3 Линзы]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Построить изображения прямой и определить положение объектива для резкой съёмки поля."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 3. Tilt-shift lens (6 pts)

**NbPhO 2004** · Международная олимпиада · теория · 10–12 класс · задача 3  
Источник: [[_pdf/NbPhO/nbpho-2004.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2004.pdf#page=3|решение, стр. 3]]

Темы: [[6.3 Линзы]]

> [!abstract] Кратко (составлено моделью)
> Построить изображения прямой и определить положение объектива для резкой съёмки поля.

**1)** Show that an image of a straight line created by a thin lens is also a straight line. Consider two-dimensional geometry only, i.e. assume that the main optical axis and the straight line lay in the same $(x,y)$ surface. Hint: use the coordinate system, where the origin coincides with the center of the lens and represent lines algebraically, e.g. $y=ax+b$. Make use of the formula of thin lens $f^{-1}=x^{-1}-x'^{-1}$ ($x>0$ and $x'$ are the $x$-coordinates of a point and its image, respectively) (2 pts).

**2)** In figure (a), draw the image of the given line and indicate, which parts of the image are virtual, and which are real (2 pts).

![[nbpho-2004-p1-f2.svg]]

**3)** Photographer wants to take a photo of a field of flowers. In order to get image where all the flowers (both the close and far ones) are sharp, he has to use a lens with tilt-shift (TS) capabilities (either an ordinary camera with TS lens, or a large-format camera, where the entire lens compartment can be freely positioned). The field of flowers (which extends effectively to infinity) and the image of its distant edge, together with the image plane are depicted in figure (b). Reconstruct the position of the lens, the focal length of which is provided as a scale (2 pts).

![[nbpho-2004-p1-c5368.png]]

> [!solution]- Решение
> # 3. Tilt-shift lens (6 pts)
>
> From $f^{-1}=x^{-1}-x'^{-1}$ we obtain $x=\frac{x'f}{x'+f}$. Since the ray passing through the centre of a lens without refraction, from similar triangles we obtain the relationship between the $y$-coordinates of the image: $y=y'\frac x{x'}=\frac{y'f}{x'+f}$. Substituting into $y=ax+b$ we result in $\frac{y'f}{x'+f}=a\frac{x'f}{x'+f}+b$, hence $y'=ax'+b(\frac{x'}f+1)=x'(a+\frac bf)+b$, which defines also a straight line.
>
> **1)** First we notice that the line, its image, and lens plane intersect in one point, because the image of that point of the line which lays at the lens plane, coincides with itself. Now, it is easy to construct the image, see the figure.
>
> ![[nbpho-2004-p3-f1.svg]]
>
> **2)** First we notice that the distance of the image of the far end of the field (let us designate it by $A$) from the focal plane equals to the focal length $f$. So, the lens plane must touch the circle of radius $f$, drawn around $A$, see figure. Next we notice that there is one such ray connecting far end of the field and its image, which does not refract — the one passing through the enter of the lens, see figure.
>
> ![[nbpho-2004-p3-f3.svg]]
