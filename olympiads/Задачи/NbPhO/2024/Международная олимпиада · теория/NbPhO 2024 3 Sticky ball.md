---
id: nbpho-2024-intl-theory-3
olympiad: NbPhO
year: 2024
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "3"
title: "Sticky ball"
points: 4
authors: ["Jaan Kalda"]
aliases: ["Sticky ball"]
topics: ["[[2.11 Поверхностное натяжение]]", "[[1.10 Статика]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: true
source_damaged: false
summary: "Определить силу притяжения стеклянного шарика к пластине за счёт тонкой водяной перемычки."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 3. Sticky ball (4 points) — Jaan Kalda.

**NbPhO 2024** · Международная олимпиада · теория · 10–12 класс · задача 3  
Источник: [[_pdf/NbPhO/nbpho-2024.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2024.pdf#page=4|решение, стр. 4–5]]

Темы: [[2.11 Поверхностное натяжение]], [[1.10 Статика]]

> [!abstract] Кратко (составлено моделью)
> Определить силу притяжения стеклянного шарика к пластине за счёт тонкой водяной перемычки.

A glass ball of radius $R$ rests on a flat glass plate. A tiny droplet of water (of surface tension $\sigma$) is injected with a syringe so that water forms a small thin neck between the ball and the plate. Both the ball and the plate are perfectly hydrophilic, i.e. the contact angle of water is $0^\circ$. Find the increase of the normal force between the plate and the ball caused by the presence of the neck of water.

> [!answer]- Ответ
> $\Delta F\approx\sigma\pi\rho^2/r=4\pi\sigma R$.
>
> $\Delta F=\Delta F_p+\Delta F_\sigma\approx\Delta F_p\approx4\pi\sigma R$.

> [!solution]- Решение
> # 3. Sticky ball (4 points) — Solution by Jaan Kalda, Tudor Plopeanu, grading schemes by Eppu Leinonen.
>
> ![[nbpho-2024-p5-f1.svg]]
>
> Let the radius of the neck be $\rho\ll R$ thus the force from surface tension at the contact of the sphere is negligible (angle to the horizontal $\approx 0$). Then, the curvature radius of the meniscus $r\ll\rho$ can be found from the intersecting secants theorem applied on a point $C$ on the bottom edge of the neck relative to the ball and approximating that the point $T$ is (near) the intersection of $CD$ and the circle: $2r\cdot2R\approx\rho^2$. On the drawing, $AC^2\approx CT\cdot CD$ and we approximate $CT$ as $2r$, $R+r$ as $R$, and $AC$ as $\rho$. The pressure difference between the water and the surrounding air is $\Delta p=\sigma/r$. Its total vertical component is equal to its amplitude times the vertical cross-section $S=\pi\rho^2$. As such, the total vertical force on the ball difference between the two cases (with and without water) is
>
> $\Delta F\approx\sigma\pi\rho^2/r=4\pi\sigma R$.
>
> *Solution 2 by Eppu Leinonen*
>
> The position of the meniscus can be parameterised using the angle $\theta=\angle TOA$. The meniscus is small as the amount of water is small. Thus $|\theta|\ll1$ and the radii can be approximated as $\rho=R\sin\theta\approx R\theta$ and $2r\approx R(1-\cos\theta)\approx R\theta^2/2$. The change in normal force due to surface tension is $\Delta F_\sigma=2\pi\sigma\rho\sin\theta\approx2\pi\sigma R\theta^2\approx0$. Using the Young-Laplace equation $\Delta p=\sigma(1/\rho-1/r)\approx\sigma(1/\theta-4/\theta^2)$. Thus the total change in normal force due to pressure difference is $\Delta F_p=-S\Delta P=-\pi\rho^2\Delta P\approx\pi\sigma R(4-\theta)\approx4\pi\sigma R^2$. I.e.
>
> $\Delta F=\Delta F_p+\Delta F_\sigma\approx\Delta F_p\approx4\pi\sigma R$.
>
> *Note:* A common approach was to use the method of virtual displacement to solve for the force caused by the meniscus. However, it turns out that $\delta A_{lg}\propto\sqrt r\delta r$ (the area of the meniscus-air interface is roughly half of a spherical toroid with radii $\rho$ and $r$) which means that the change in potential energy due to the change in surface area is negligible ($r\ll R$). Thus the virtual work done by lifting the sphere only counteracts the virtual work done by the pressure, which reduces the problem back to either solution 1 or solution 2. Thus no points are granted for just mentioning this approach and telling that $\delta U=\sigma\delta A_{lg}$.
>
> *Solution 3 using virtual displacement (by Jaan Kalda).* Let us denote the contact area of water and plate with $A=\pi\rho^2$; then, the contact area of water and ball is also approximately $A$. Let the ball touch initially the plate, and then be raised by $dx$. Since the volume of water is conserved, no work is made by atmospheric pressure, and $2r\,dA=A\,dx$, where $dA$ is the change of the contact area; hence, $\frac{dA}{dx}=A/2r$. Meanwhile, for zero contact angle, the difference of surface energies at the air-solid interface, and at the water-solid interface equals to the surface energy of the water-air interface. This fact can be expressed in terms of the three surface tension coefficients denoted with $\sigma_1$, $\sigma_2$, and $\sigma$, respectively: $\sigma_1-\sigma_2=\sigma\cos\alpha=\sigma$. During our virtual displacement, the air-water interface remains almost constant; meanwhile, air-solid interface is increased by $2dA$ (contributed equally by the ball and plate surfaces). Therefore, the surface energy is increased by $dU=(\sigma_1-\sigma_2)2dA=2\sigma dA$. Now we can find force as $F=\frac{dU}{dx}=2\sigma\frac{dA}{dx}=\sigma A/r$. This is the same expression we obtained from Young-Laplace equation. From this point on, the solution follows the steps made above.

> [!grading]- Критерии оценивания
> Grading: (preliminary) Note that differing sign conventions are tolerated
>
> | Criterion | Points |
> |---|---|
> | Stating that the meniscus is (roughly) inverse spherical or usage of constant $r$ to characterise the meniscus as inverse spherical | 0.5 pts |
> | $r\ll\rho\ll R$ | 0.1 pts |
> | Stating that surface tension from from contact is negligible or $\Delta F$ comes from the pressure difference (either explicitly or implicitly) | 0.5 pts |
> | $2r\cdot2R\approx\rho^2$ (if not found, partial points can be earned as below) | 0.7 pts |
> | $CT\approx2r$ | 0.1 pts |
> | $R+r\approx R$ | 0.1 pts |
> | $AC\approx\rho$ | 0.2 pts |
> | $AC^2\approx CT\cdot CD$ or statement of intersecting secants theorems | 0.3 pts |
> | $\Delta p=\sigma/r$ (if not found, partial points can be earned as below) | 1 pts |
> | $\Delta p=\sigma(1/r_1+1/r_2)$ or any attempt to use a form of the Laplace-Young equation | 0.2 pts |
> | $\Delta p=\sigma(1/\rho-1/r)$ | 0.3 pts |
> | $S=\pi\rho^2$ (correct effective area for pressure) | 0.5 pts |
> | $\Delta F=S\Delta p$ | 0.5 pts |
> | $\Delta F\approx4\pi\sigma R$ (0.1 pts for each of the following) | 0.2 pts |
> | $\Delta F>0$ or noting that the contact force increases | |
> | Correct dimensionless factor of $4\pi$ and correct dimensions (only if approach is correct) | |
>
> Grading: (preliminary) Note that differing sign conventions are tolerated
>
> | Criterion | Points |
> |---|---|
> | Stating that the meniscus is (roughly) inverse spherical or usage of constant $r$ to characterise the meniscus as inverse spherical | 0.5 pts |
> | $\lvert\theta\rvert\ll1$ | 0.1 pts |
> | $\rho\approx R\theta$ | 0.2 pts |
> | $AC\approx\rho$ | 0.2 pts |
> | $r\approx R\theta^2/4$ | 0.3 pts |
> | $\Delta F_\sigma\propto\theta^2\ll\Delta F_p$ or any statement that the force from surface tension is negligible or $\Delta F=\Delta F_p$ | 0.5 pts |
> | $\Delta p=\sigma/r$ (if not found, partial points can be earned as below) | 1 pts |
> | $\Delta p=\sigma(1/r_1+1/r_2)$ or any attempt to use a form of the Laplace-Young equation | 0.2 pts |
> | $\Delta p=\sigma(1/\rho-1/r)$ | 0.3 pts |
> | $S=\pi\rho^2$ (correct effective area for pressure) | 0.5 pts |
> | $\Delta F_p=-S\Delta p$ | 0.5 pts |
> | $\Delta F\approx4\pi\sigma R$ (0.1 pts for each of the following) | 0.2 pts |
> | $\Delta F>0$ or noting that the contact force increases | |
> | Correct dimensionless factor of $4\pi$ and correct dimensions (only if approach is correct) | |
>
> Grading: (preliminary) Note that differing sign conventions are tolerated.
>
> | Criterion | Points |
> |---|---|
> | Only the contact area between the solid and the liquid changes notably | 0.5 pts |
> | $\frac{dA}{dx}=A/2r$ | 0.5 pts |
> | $\sigma_1-\sigma_2=\sigma$ | 0.2 pts |
> | $dU=2(\sigma_1-\sigma_2)dA$ | 0.3 pts |
> | $F=\frac{dU}{dx}$ (only if $A$ has been identified correctly) | 0.3 pts |
> | $F=\sigma A/r$ | 0.2 pts |
>
> These replace noting that $\Delta F_\sigma\approx0$, $\Delta p=\sigma/r$ and $\Delta F=S\Delta p$ from the other solutions.
