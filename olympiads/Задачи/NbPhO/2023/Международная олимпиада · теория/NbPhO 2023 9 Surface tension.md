---
id: nbpho-2023-intl-theory-9
olympiad: NbPhO
year: 2023
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "9"
title: "Surface tension"
points: 10
authors: ["Jaan Kalda", "Eero Uustalu"]
aliases: ["Surface tension"]
topics: ["[[2.11 Поверхностное натяжение]]", "[[6.3 Линзы]]", "[[7 Эксперименты]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: true
source_damaged: false
summary: "По оптическим и геометрическим измерениям капли определить контактный угол и поверхностное натяжение воды."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 9. Surface tension (10 points) — Jaan Kalda, Eero Uustalu.

**NbPhO 2023** · Международная олимпиада · теория · 10–12 класс · задача 9  
Источник: [[_pdf/NbPhO/nbpho-2023.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2023.pdf#page=10|решение, стр. 10–11]]

Темы: [[2.11 Поверхностное натяжение]], [[6.3 Линзы]], [[7 Эксперименты]]

> [!abstract] Кратко (составлено моделью)
> По оптическим и геометрическим измерениям капли определить контактный угол и поверхностное натяжение воды.

Tools: a syringe, a small glass plate, a support for holding the glass plate horizontally at an adjustable height, a cup with water (coefficient of refraction of water $n_w=1.33$), a caliper, a sheet of graph paper. Your working room has ceiling lights at an approximate height of $3\,\mathrm m$. The glass plate holder is a short piece of plastic pipe with a nut; put the glass plate on top of the nut and turn the nut to adjust the height. By turning the nut, one can change the holder height only by the thickness of the nut; there are also spare nuts that can be stacked to increase the total height of the pipe-nuts system, and a cap that fits into the pipe — use it if there is a need to make the distance between the glass plate and the surface beneath it smaller than the height of the pipe. NB! Hold the glass plate only from its matte part and do not touch the glossy (transparent) part as fingerprints will affect the value of the contact angle. If you accidentally do touch, ask organisers to clean the glass surface.

**i)** (3 points) Put a small drop of water onto the glass plate; this will form a plano-convex lens. Determine the focal length of this lens and measure its diameter.

**ii)** (2 points) Calculate the curvature radius of the water surface and the water-glass contact angle $\alpha$. The contact angle is defined as the angle under which the water surface (the air-water interface) meets the surface of the glass plate.

**iii)** (3 points) Now increase the amount of water on the glass plate so that it covers a big part of the glass plate so that its top surface becomes almost flat. Determine the thickness of the water layer.

**iv)** (2 points) Calculate the surface tension of water $\sigma$. Hint: a given amount of water takes a shape which minimises its total potential energy. Use reasonable approximations. Keep in mind that the glass-water interface makes also a certain contribution $U_{gw}$ to the full surface energy, the magnitude of which is related to the contact angle: $U_{gw}=-\sigma\cos\alpha A$, where $A$ denotes the surface area of the glass-water interface.

> [!answer]- Ответ
> **i** — $f=15.9\,\mathrm{mm}$ and
>
> **i** — $d=5.8\,\mathrm{mm}$.
>
> **ii**
>
> $$
> \frac1f=\frac{n-1}{R}\implies R=f(n-1)\approx5.3\,\mathrm{mm}.
> $$
>
> **ii**
>
> $$
> \alpha=90^\circ-\mathrm{acos}\frac d{2R}\approx33.2^\circ
> $$
>
> **iii** — $t=V/A\approx1.57\,\mathrm{mm}$.
>
> **iv**
>
> $$
> \sigma=\frac{\rho gh^2}{2(1-\cos\alpha)}\approx0.077\,\mathrm{N/m}.
> $$

> [!solution]- Решение
> # 9. Surface tension (10 points) — Solution by Jaan Kalda, grading schemes by ....
>
> **i)** (3 points) The focal length can be found by adjusting the height of the plate holder; adjust the height so as to achieve a sharp image of the ceiling lights at the screen (either a sheet of paper beneath the holder, or the surface of the cap inside the holder. The height can be measured precisely by caliper. The diameter of the drop can be also measured by caliper, but it is more convenient to put the glass plate on top of the graph paper and take the diameter reading from the millimeter grid of the graph paper. A possible pair of data is
>
> $f=15.9\,\mathrm{mm}$ and
> $d=5.8\,\mathrm{mm}$.
>
> **ii)** (2 points) Lensmaker’s equation can be used to relate the focal length to the curvature radius:
>
> $$\frac1f=\frac{n-1}{R}\implies R=f(n-1)\approx5.3\,\mathrm{mm}.$$
>
> Those who don’t know the lensmaker’s formula can derive it easily from Snell’s law by considering a beam which falls onto the lens parallel to the optical axis, and by using small angle approximation, $\sin x\approx x$. The water-glass contact angle can be found using trigonometry:
>
> $$\alpha=90^\circ-\mathrm{acos}\frac d{2R}\approx33.2^\circ$$
>
> **iii)** (3 points) Increase the surface area of water covering the glass plate as much as possible — in that way the mistake in calculations introduced by the edge effects (the water surface is not flat near the edges of the water pool) is minimised. It is safe to let the water reach the edges of the glass plate as long as there is a small part of the perimeter where it does not reach the edge — this guarantees that the water surface at the edges forms with the horizon an angle equal to the contact angle. However, you shouldn’t let the water reach the edges of the plate over its entire perimeter as in that case, the angle formed by the water surface can become larger than the contact angle, due to the fact that at the edge, the direction of the glass plate’s surface normal changes discontinuously; this would result in a thicker water layer (this cannot happen if there is a part of the perimeter still not touching the edge as in that case, instead of increasing the depth, the water would spread to fill the unoccupied parts of the plate). It is also recommended to avoid water reaching the matte area as that part is not guaranteed to be clean and may have a different contact angle value. With water volume $V=2.00\,\mathrm{ml}$, the water fills almost the entire glossy part of the plate. By putting the glass plate on top of the graph paper, one can count the squares of the grid, resulting in $A=12.7\,\mathrm{cm}^2$. The thickness of water layer is found as
>
> $t=V/A\approx1.57\,\mathrm{mm}$.
>
> **iv)** (2 points) Total potential energy of the water is $U=\sigma A(1-\cos\alpha)+\frac12V\rho gt$. If we plug in $A=V/t$, we obtain
>
> $$U=V\left(\sigma\frac{1-\cos\alpha}{t}+\frac{\rho gt}{2}\right).$$
>
> Its minimum is easily found by equating $dU/dt=0$, resulting in
>
> $$\sigma=\frac{\rho gh^2}{2(1-\cos\alpha)}\approx0.077\,\mathrm{N/m}.$$

> [!grading]- Критерии оценивания
> **Grading:**
> - Correct idea of searching for the focal length by adjusting the height of the plate holder in order to achieve a sharp image of the ceiling lights **(0.7 pts)**
> - student takes into consideration that the light source is at a finite length or mentions in solution that it can be considered that the light source is at a very large distance away. **(0.3 pts)**
> - Correctly taken height measurements with a caliper **(0.5 pts)**
> - Correctly taken diameter measurements of the drop using the caliper or using the millimeter grid on the graphing paper **(0.5 pts)**
> - The results should be roughly $f=15.9\,\mathrm{mm}$ and $d=5.8\,\mathrm{mm}$, but should later give accurate $\alpha$ value. **(1 pts)**
>
> **ii)**
>
> **Grading:**
> - Correct idea of calculating the radius using the Lensmaker’s equation. Other methods (for example using direct thickness measurement) only gives max 0.3 pts. **(0.5 pts)**
> - The result should be around $R=5.3\,\mathrm{mm}$, but should later give accurate $\alpha$ value. **(0.5 pts)**
> - Correct idea for determining the water-glass contact angle using previously calculated values $d$ and $R$. **(0.5 pts)**
> - The result should be around $\alpha=33.2^\circ$. Give max points for $\alpha=28^\circ-38^\circ$. **(0.5 pts)**
>
> **iii)**
>
> **Grading:**
> - Student understands that it is necessary to maximize the surface area of the water. **(0.5 pts)**
> - Student understands that the area of the water should not extend to the edges of the glass plate. **(0.5 pts)**
> - If measurement of water volume $V<2.5\,\mathrm{ml}$. **(0.5 pts)**
> - If measurement of the surface area of the water. $A<13.5\,\mathrm{cm}^2$ **(0.5 pts)**
> - Correct formula to determine thickness of the water layer. **(0.5 pts)**
> - The result should be around $t=1.57\,\mathrm{mm}$. Give max points for $t=1.45\,\mathrm{mm}-1.70\,\mathrm{mm}$. **(0.5 pts)**
> - if the thickness is measured directly max receivable points are 0.5 for a reasonable result and 0.5 pts for a reasonable method if described as this has very poor precision because the caliper can not touch the water surface and the water surface has poor visibility.
>
> **iv)**
>
> **Grading:**
> - Surface energy is shown in the expression for total potential energy. **(0.3 pts)**
> - $U_{gw}$ is taken into consideration in the expression for total potential energy. **(0.4 pts)**
> - Potention energy is shown in the expression for total potential energy. **(0.3 pts)**
> - Minimum total potential energy is correctly found. **(0.6 pts)**
> - The result should be around $\sigma=0.077\,\mathrm{N\,m^{-1}}$. Give max points for $\sigma=0.060\,\mathrm{N\,m^{-1}}-0.094\,\mathrm{N\,m^{-1}}$. **(0.4 pts)**
