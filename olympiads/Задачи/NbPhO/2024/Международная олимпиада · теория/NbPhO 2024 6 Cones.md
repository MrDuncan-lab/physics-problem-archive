---
id: nbpho-2024-intl-theory-6
olympiad: NbPhO
year: 2024
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "6"
title: "Cones"
points: 8
authors: ["Jaan Kalda", "Eppu Leinonen"]
aliases: ["Cones"]
topics: ["[[6.1 Отражение]]", "[[1.3 Равноускоренное криволинейное движение]]", "[[1.17 Законы сохранения энергии и импульса]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: true
source_damaged: false
summary: "Определить угол конического зеркала и исследовать движение шайбы по поверхности конуса."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 6. Cones (8 points) — Jaan Kalda, Eppu Leinonen.

**NbPhO 2024** · Международная олимпиада · теория · 10–12 класс · задача 6  
Источник: [[_pdf/NbPhO/nbpho-2024.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2024.pdf#page=7|решение, стр. 7–8]]

Темы: [[6.1 Отражение]], [[1.3 Равноускоренное криволинейное движение]], [[1.17 Законы сохранения энергии и импульса]]

> [!abstract] Кратко (составлено моделью)
> Определить угол конического зеркала и исследовать движение шайбы по поверхности конуса.

**i)** (2 points) The photo below shows a self-anamorphic drawing — a red heart in green background. The reflection of the red heart in the conical mirror is a reduced green heart. What is the apex angle of the conical mirror? You can take measurements from the photo. The distance where the photo was taken was much larger than the diameter of the red heart.

![[nbpho-2024-p2-c0130.png]]

Photo by Erik Mahieu, cf. https://community.wolfram.com/groups/-/m/t/2027565.

**ii)** (1 point) A point-like puck of mass $m$ can slide frictionlessly along the internal surface of a cone of half apex angle $\theta$. The gravitational acceleration is $g$ and points along the symmetry axis of the cone at the apex. The puck starts sliding from a point $P$ on the surface of the cone with such a horizontal velocity that it will stay moving at the same fixed height while performing uniform circular motion of radius $R$. What is its speed $v$?

**iii)** (2.5 points) Now the puck starts sliding horizontally from the same point $P$ as before, but its initial speed is reduced to $v/2$. What is the smallest distance between the puck and the cone’s axis during the subsequent motion?

**iv)** (2.5 points) Now, the cone and the puck are moved to weightlessness. The puck starts again from the point $P$ with the same velocity as in part ii). By how many degrees will the radius vector drawn from the cone’s axis to the puck rotate during the subsequent motion? Assume that the cone is infinitely long.

> [!answer]- Ответ
> **i** — $2\theta\approx1.22$ radians, or 71 degrees.
>
> **ii** — $v=\sqrt{Rg\cot\theta}$.
>
> **iii** — $\frac{1+\sqrt{33}}{16}R\approx0.42R$.
>
> **iv** — $\frac\pi2\frac{2\pi}{2\pi\sin\theta}=\frac\pi{2\sin\theta}$.
>
> **iv** — $\phi_\infty=\frac\pi{2\sin\theta}$.
>
> **iv** — $\phi_\infty=\frac1{\sin\theta}\int_0^v\frac{dv_\parallel}{\sqrt{v^2-v_\parallel^2}}=\frac\pi{2\sin\theta}$. The integral can be calculated easily by recognising that it represents a quarter of the area of a unit circle.

> [!solution]- Решение
> # 6. Cones (8 points) — Solution by Tudor Plopeanu, grading schemes by Eppu Leinonen and Aleksi Kononen.
>
> **i)** (2 points) We will consider any extreme point on the red heart and its reflection. This may be easiest and most precise for the points furthest from the center of the picture, but any edge point of the red heart would suffice. Let $\theta$ be the cone’s half apex angle. Let $r$ be the measured ratio of the (angular) distance from the perceived image to the mirror and the perceived image to the original point. Then, $\frac{\tan\theta}{\tan2\theta}=r$, so $\theta=\arccos\frac1{\sqrt{2(1-r)}}$, or alternatively $\arctan\sqrt{1-2r}$. Of course, the apex angle is $2\theta$, which is double the above.
>
> For measured $r=0.25$, we have the answer
>
> $2\theta\approx1.22$ radians, or 71 degrees.
>
> ![[nbpho-2024-p7-f1.svg]]
>
> **ii)** (1 point) The contribution of gravity along the side of the cone has to be equal to the contribution of the centrifugal force. As such, $mg\cos\theta=\frac{mv^2}{R}\sin\theta$, so
>
> $v=\sqrt{Rg\cot\theta}$.
>
> **iii)** (2.5 points) The puck’s energy is the sum of its gravitational potential energy and its kinetic energy, so for a maximal vertical displacement $h_f$, and the speed $v_f$ at that moment, we have $E=\frac{v^2}{8}+gh_f=\frac{v_f^2}{2}$. From the conservation of angular momentum between the initial moment and the minimal distance to axis moment, when the velocity is horizontal, we can deduce that $\frac v2R=v_fR_f$, where $R_f$ is the minimal distance to the cone’s axis. We can relate $h_f$ and $R_f$ through $\frac{R-R_f}{h_f}=\tan\theta$. Then, $h_f=(R-R_f)\cot\theta$. Replacing $h_f$ and $v_f$ in the energy conservation, $\frac{v^2}{8}=\frac{v^2R^2}{8R_f^2}-g(R-R_f)\cot\theta$. Replacing $v^2=Rg\cot\theta$ and solving the third degree polynomial in $R_f$, $8R_f^3-9RR_f^2+R^3=0$, yields the roots $R$, $\frac{1+\sqrt{33}}{16}R$, and some negative value. Our minimal radius is, as such,
>
> $\frac{1+\sqrt{33}}{16}R\approx0.42R$.
>
> ![[nbpho-2024-p7-f3.svg]]
>
> **iv)** (2.5 points) Let us unfold the cone and repeat its pattern, as in the figure above. We note that the relation between the apex angle and the angle of the unfolded cone are related through the area of a cone $\pi L^2\sin\theta=\varphi L^2$ and as such $\varphi=\pi\sin\theta$.
>
> The puck’s trajectory is a straight line starting perpendicular to the edge of our unfolded cone. The radius vector will rotate, in our drawing, by $90^\circ=\pi/2$ over an infinite period of time. To match the rotation on our representation of the cone with the rotation of the radius vector, we remind ourselves that a $360=2\pi$ degree rotation of the radius vector matches a $2\varphi$ rotation on our drawing. As such, the number of radians of rotation will be
>
> $\frac\pi2\frac{2\pi}{2\pi\sin\theta}=\frac\pi{2\sin\theta}$.
>
> *Solution 2 by Eppu Leinonen*
>
> Let $\phi$ be the total rotation angle of the radius vector and $r$ its length. The speed related to $\dot\phi$ is $r\dot\phi$ and the speed related to $\dot r$ is $\dot r\csc\phi$, the projection of which to the radial axis is $\dot r$. Thus energy conservation states that $r^2\dot\phi^2+\dot r\csc\theta=v^2$. Also the projection of the angular momentum onto the symmetry axis is also conserved and as such $r^2\dot\phi=Rv$. From this we solve $\dot\phi$ and substitute to the energy conservation equation to get $\dot r=v\sqrt{1-(R/r)^2}\sin\theta$. Integrating both sides from time $t=0$ to $t=t$ ($r(0)=R$ and $r(t)=r$) yields $r^2=\sqrt{R^2+v^2t^2\sin^2\theta}$. Then $\dot\phi=\frac{Rv}{R^2+v^2t^2\sin^2\theta}$ which we can integrate from $t=0$ to $t=\infty$ by noticing that $\arctan' x=1/(1+x^2)$ which gives
>
> $\phi_\infty=\frac\pi{2\sin\theta}$.
>
> *Solution 3 by Eppu Leinonen*
>
> Split the velocity into two components: the velocity from changing angle of the radius vector $\phi$, $v_\perp$, and the velocity up along the cone $v_\parallel$. In cylindrical coordinates the radial force law now states $N\cos\theta=mv_\perp\dot\phi-m\dot v_\parallel\sin\theta$ and the vertical force law now states $N\sin\theta=m\dot v_\parallel\cos\theta$. From this we can solve for $\dot\phi=\dot v_\parallel/(v_\perp\sin\theta)$. From conservation of energy $v_\perp=\sqrt{v^2-v_\parallel}$ and thus
>
> $\phi_\infty=\frac1{\sin\theta}\int_0^v\frac{dv_\parallel}{\sqrt{v^2-v_\parallel^2}}=\frac\pi{2\sin\theta}$. The integral can be calculated easily by recognising that it represents a quarter of the area of a unit circle.
>
> *Solution 4 by Aleksi Kononen and Eppu Leinonen*
>
> Split the velocity into two components: the velocity from changing angle of the radius vector $\phi$, $v_\perp$, and the velocity up along the cone $v_\parallel$. Go to the frame corotating with puck. In this frame, there will be three inertial forces on the puck: centrifugal, Coriolis, and Euler. Both the Coriolis and Euler forces point perpendicularly to $v_\parallel$ and tangentially to the cone. However, as the frame is corotating $\dot v'_\perp=0$ in the frame, and thus the Coriolis and Euler forces must cancel. This means that the radial component of the normal force is $N_r=mv_\perp^2/r$. Thus back in the inertial frame we get $\dot v_\parallel=\frac{v_\perp^2}{r}\sin\theta$. On the other hand $\dot\phi=v_\perp/r=\frac1{\sin\theta}\dot v_\parallel/v_\perp$. From energy conservation $v_\perp=\sqrt{v^2-v_\parallel^2}$ and thus
>
> $\phi_\infty=\frac1{\sin\theta}\int_0^v\frac{dv_\parallel}{\sqrt{v^2-v_\parallel^2}}=\frac\pi{2\sin\theta}$. The integral can be calculated easily by recognising that it represents a quarter of the area of a unit circle.

> [!grading]- Критерии оценивания
> Grading: (preliminary)
>
> | Criterion | Points |
> |---|---|
> | Stating that the image is formed by vertical rays as the camera is far away | 0.5 pts |
> | Correct explicit expression of $\theta$ with respect to $r$ (or some other measurable variable) (if not found, partial points can be earned as below) | 1 pts |
> | Correct geometrical figure | 0.2 pts |
> | $r=\tan\theta/\tan2\theta$ or equivalent or a correct implicit equation for $\theta$ | 0.5 pts |
> | Correct numerical answer $2\theta\in[65^\circ,76^\circ]$ (only if approach is correct) | 0.5 pts |
> | If only $\theta$ is given and not $2\theta$ | -0.2 pts |
>
> **ii)**
>
> Grading: (preliminary)
>
> | Criterion | Points |
> |---|---|
> | Correct force balance | 0.5 pts |
> | Correct expression for $v$ | 0.5 pts |
> | Mistakes in trigonometry | -0.1 pts |
>
> **iii)**
>
> Grading: (preliminary)
>
> | Criterion | Points |
> |---|---|
> | Idea of using energy and angular momentum conservation (0.1 pts for each) | 0.2 pts |
> | Correct energy conservation | 0.5 pts |
> | Correct angular momentum conservation | 0.5 pts |
> | Correct relation between $h_f$ and $R_f$ | 0.1 pts |
> | Correct third degree polynomial | 0.5 pts |
> | Picking the physically relevant solution | 0.5 pts |
> | Correct final answer | 0.2 pts |
>
> Grading: (preliminary)
>
> | Criterion | Points |
> |---|---|
> | Idea of folding out the cone | 0.2 pts |
> | Stating that the trajectory is a straight line in the folded plane | 1 pts |
> | Correct 90 degree rotation in the folded picture or a correct figure | 0.6 pts |
> | Correct relation between rotation in the folded plane and the rotation of the radial vector | 0.7 pts |
> | Using $\theta$ instead of $2\theta$ as the apex angle | -0.3 pts |
>
> Grading: (preliminary)
>
> | Criterion | Points |
> |---|---|
> | Idea of using energy and angular momentum (projection) (both required for points) | 0.1 pts |
> | Correct energy conservation with respect to $\phi$ and $r$ velocity components (can be named freely e.g. $v_r$ and $v_\phi$) | 0.4 pts |
> | Correct angular momentum (projection) conservation | 0.4 pts |
> | Equivalent form $\dot r=v\sqrt{1-(R/r)^2}$ | 0.5 pts |
> | Solving $r(t)$ (partials below) | 0.5 pts |
> | Correct integration boundaries | 0.1 pts |
> | Solving $\phi_\infty$ (partials below) | 0.6 pts |
> | Setting up integral of the form $\phi_\infty=\int Rv/r^2(t)dt$ | 0.1 pts |
> | Correct integration boundaries | 0.1 pts |
> | $1/\sin\theta$ dependence | 0.3 pts |
>
> Grading: (preliminary)
>
> | Criterion | Points |
> |---|---|
> | Correct radial and vertical equations of motion (0.2 for each) | 0.4 pts |
> | Representing them in $\phi,v_\parallel,v_\perp$ (0.2 for each) | 0.4 pts |
> | Correct relation between $\dot\phi$ and $v_\perp,\dot v_\parallel$ | 0.5 pts |
> | For wrong trigonometric dependence | -0.2 pts |
> | Using the energy conservation law to relate $\dot\phi$ to only $v_\perp$ or $v_\parallel$ and derivatives | 0.7 pts |
> | Solving the integral (partial points below) | 0.5 pts |
> | Correct integration boundaries | 0.1 pts |
> | Noticing the area of a circle | 0.2 pts |
>
> Grading: (preliminary)
>
> | Criterion | Points |
> |---|---|
> | Argument for why the radial component of the normal force is equal $mv_\perp^2/r$ (partials below for non-inertial frame method) | 0.7 pts |
> | Noting that in the inertial frame there are three inertial forces | 0.1 pts |
> | Noting that Coriolis and Euler forces are parallel to $v_\perp$ | 0.3 pts |
> | Noting that Coriolis and Euler forces must be equal as $\dot v'_\perp=0$ | 0.3 pts |
> | Noting that the radial component normal force is equal to $mv_\perp^2/r$ | 0.1 pts |
> | Correct relation between $\dot\phi$ and $v_\perp,\dot v_\parallel$ | 0.5 pts |
> | For wrong trigonometric dependence | -0.2 pts |
> | Using the energy conservation law to relate $\dot\phi$ to only $v_\perp$ or $v_\parallel$ and derivatives | 0.7 pts |
> | Solving the integral (partial points below) | 0.5 pts |
> | Correct integration boundaries | 0.1 pts |
> | Noticing the area of a circle | 0.2 pts |
