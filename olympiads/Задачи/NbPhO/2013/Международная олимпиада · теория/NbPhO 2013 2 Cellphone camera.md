---
id: nbpho-2013-intl-theory-2
olympiad: NbPhO
year: 2013
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "2"
title: "Cellphone camera"
points: 6
aliases: ["Cellphone camera"]
topics: ["[[6.3 Линзы]]"]
difficulty: 3
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Определить расстояния резкой съёмки камеры по размерам объектива и пикселя."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 2. CELLPHONE CAMERA (6 points)

**NbPhO 2013** · Международная олимпиада · теория · 10–12 класс · задача 2  
Источник: [[_pdf/NbPhO/nbpho-2013.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2013.pdf#page=3|решение, стр. 3]]

Темы: [[6.3 Линзы]]

> [!abstract] Кратко (составлено моделью)
> Определить расстояния резкой съёмки камеры по размерам объектива и пикселя.

A photographer focussed his camera to distance $L$ and took a photo. On the photo, all farther objects (up to infinity) turned also out to be sharp. Additionally, all closer objects down to distance $s$ were sharp.

**i)** (4 points) What is the minimum possible $L$?

**ii)** (2 points) Find the corresponding $s$.

*Background.* We consider the image of a pointlike object to be sharp if its image is smaller than one pixel on the sensor. Otherwise the image is blurry. The lens of the camera may be viewed as a convex lens. The camera is focussed by changing the distance between the sensor and the lens.

*Parameters.* Calculate the answer for a cellphone made by a well-known company. The focal length of its camera $f=4.3\mathrm{mm}$ and the diameter of the lens $D=1.8\mathrm{mm}$. The sensor is $w=4.6\mathrm{mm}$ wide corresponding to $N=3264$ pixels.

> [!answer]- Ответ
> **i** — $L=Df/\eta=DfN/w\approx5.5\,\mathrm{m}$.
>
> **ii** — $s=\frac12Df/\eta=L/2\approx2.75\,\mathrm{m}$.

> [!solution]- Решение
> # 2. CELLPHONE CAMERA (6 points)
>
> The distance $L$ is often called hyperfocal distance in photography and it was calculated more than one hundred years ago by Louis Derr (the figure is taken from his book *Photography for students of physics and chemistry*, published in 1906).
>
> ![[nbpho-2013-p3-f1.png]]
>
> Let’s consider that the camera is focused to distance $L$ and the image is formed exactly on the sensor’s plane. The object’s distance $L$ and its image’s distance $a$ (corresponds to $p'$ on the figure) are related by the lens formula $\frac1L+\frac1a=\frac1f$, thus
>
> $$a=\frac{Lf}{L-f}=\frac{Lf}{L(1-f/L)}\approx\frac{Lf}{L}\left(1+\frac fL\right)=f+\frac{f^2}{L},$$
>
> where the approximation $(1+x)^{-1}\approx1-x$ (for small $x$) was used. Image’s distance exceeds the focal length by $\Delta a=a-f=f^2/L$.
>
> **i)** (4 points) The light coming from an infinitely far away object will pass the focal point $F$ and form a cone which is cut by the sensor’s plane. The diameter $d$ of the cut on the sensor’s plane can be found from similar triangles $d/D=\Delta a/f$, thus $d=Df/L$. Taking into account the sharpness condition $d\leq\eta$, where $\eta=w/N$ is the size of a single element of the sensor, we find that the limiting value of $L$ is
> $L=Df/\eta=DfN/w\approx5.5\,\mathrm{m}$.
>
> **ii)** (2 points) We’ll now find the shortest distance $s$ satisfying the sharpness condition. Object at distance $s$ will have an image at distance $b=f+f^2/s$ and the light passing the lens will converge behind the sensor’s plane forming a cone. The diameter $d_2$ of the cone’s cut with the sensor’s plane can be calculated from similar triangles: $d_2/D=(b-a)/b$. Accounting for sharpness condition $d_2=\eta$, we can express $b=a/(1-\eta/D)$, and substituting the values of $a$ and $b$ gives
>
> $$f+\frac{f^2}{s}=\frac{f+\frac{f^2}{L}}{1-\eta/D}=f\frac{1+\eta/D}{1-\eta/D}\approx f\left(1+\frac\eta D\right)^2\approx f\left(1+\frac{2\eta}{D}\right).$$
>
> Finally, $f^2/s=2f\eta/D$, or
> $s=\frac12Df/\eta=L/2\approx2.75\,\mathrm{m}$.
