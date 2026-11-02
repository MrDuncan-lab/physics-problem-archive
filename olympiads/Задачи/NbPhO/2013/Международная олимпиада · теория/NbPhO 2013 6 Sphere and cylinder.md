---
id: nbpho-2013-intl-theory-6
olympiad: NbPhO
year: 2013
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "6"
title: "Sphere and cylinder"
points: 7
aliases: ["Sphere and cylinder"]
topics: ["[[1.7 Качение твёрдого тела]]", "[[1.17 Законы сохранения энергии и импульса]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Сравнить движение шара и цилиндра по наклонной плоскости при качении и проскальзывании."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 6. SPHERE AND CYLINDER (7 points)

**NbPhO 2013** · Международная олимпиада · теория · 10–12 класс · задача 6  
Источник: [[_pdf/NbPhO/nbpho-2013.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2013.pdf#page=4|решение, стр. 4–5]]

Темы: [[1.7 Качение твёрдого тела]], [[1.17 Законы сохранения энергии и импульса]]

> [!abstract] Кратко (составлено моделью)
> Сравнить движение шара и цилиндра по наклонной плоскости при качении и проскальзывании.

A sphere and a cylinder are lying on an inclined surface with inclination angle $\alpha$. Both have mass $m$ and radius $r$. The bodies are released from equal initial heights $H$. The moments of inertia of the sphere and the cylinder are, respectively, $I_\mathrm{sph}=\frac25mr^2$ and $I_\mathrm{cyl}=\frac12mr^2$. The coefficient of friction between the surface and the bodies is $\mu$.

**i)** (2 points) Which of the bodies comes down faster? What was the relative lag of the slower body $\gamma=(t_2-t_1)/t_1$? The times $t_1$ and $t_2$, respectively, denote the traveling times of the faster or the slower body. Assume that the rolling occurs without slipping.

**ii)** (2.5 points) Find the minimal angle of inclination $\alpha_0$ for which the cylinder starts to slide in addition to rolling.

**iii)** (2.5 points) If $\alpha\to90^\circ$, the bodies obviously lose contact with the surface and fall down in free fall with equal times. What is the minimal angle of inclination $\alpha_m$, for which both the sphere and the cylinder come down with equal times?

> [!answer]- Ответ
> **i**
>
> $$
> \gamma=\sqrt{\frac{1+k_c}{1+k_s}}-1=\sqrt{\frac{15}{14}}-1\approx0.035.
> $$
>
> **ii** — $\alpha_0=\arctan(3\mu)$.
>
> **iii** — $\alpha_m=\alpha_\mathrm{sph}$ both bodies are in the slipping mode and thus have equal accelerations and arrival times.

> [!solution]- Решение
> # 6. SPHERE AND CYLINDER (7 points)
>
> **i)** (2 points) Since no energy is lost due to friction on sliding, the change in potential energy $\Delta E_p=mgH$ is transformed to kinetic energy consisting of both translational and rotational motion. Taking into account the rolling condition $v=\omega r$, we have
>
> $$\Delta E_p=E_k=\frac12mv^2+\frac12I\omega^2=\frac12mv^2+\frac12kmv^2=\frac12(1+k)mv^2,$$
>
> where general expression $I=kmr^2$ for moment of inertia is used. Therefore, $v^2=2gH/(1+k)$.
>
> On the other hand, the bodies travel distance $x=H/\sin\alpha$ along the slope with a constant acceleration $a_\parallel$ directed parallel to the surface. Let’s express $a_\parallel$ from the equation $v^2=2a_\parallel x$:
>
> $$a_\parallel=g\sin\alpha/(1+k).$$
>
> The times are now easy to calculate as $t=v/a_\parallel$, giving
>
> $$t=\sqrt{1+k}\left(\frac{2H}{g\sin^2\alpha}\right)^{\frac12}.$$
>
> Replacing $k_s=\frac25$ for sphere and $k_c=\frac12$ for cylinder, we find that the sphere is faster by a relative factor
>
> $$\gamma=\sqrt{\frac{1+k_c}{1+k_s}}-1=\sqrt{\frac{15}{14}}-1\approx0.035.$$
>
> **ii)** (2.5 points) As found in previous subpart, the acceleration’s parallel component to the slope $a_\parallel$ is smaller than the contribution by gravity $g\sin\alpha$. The difference is contributed by the friction force $F_f=mg\sin\alpha-ma_\parallel$. Sliding starts, if the necessary friction reaches the maximal value $F_{\max}=\mu N=\mu mg\cos\alpha$. Equating the two expressions gives
>
> $$mg\sin\alpha-mg\sin\alpha/(1+k)=\mu mg\cos\alpha,$$
>
> $$\tan\alpha=\mu\frac{1+k}{k}.$$
>
> For the cylinder the limiting angle is
> $\alpha_0=\arctan(3\mu)$.
>
> **iii)** (2.5 points) When the maximal friction force is reached, the motion goes into rolling and sliding mode, where the total force component along the surface is given by the difference of gravity and friction:
>
> $$F_\parallel=mg\sin\alpha-F_{\max}=mg\sin\alpha-\mu mg\cos\alpha.$$
>
> We note that the acceleration in this mode does not depend on the moment of inertia any more.
>
> Calculating the limiting angle of slipping mode also for the sphere $\alpha_\mathrm{sph}=\arctan(\frac72\mu)>$
>
> $\alpha_0$ shows that for all angles larger than
> $\alpha_m=\alpha_\mathrm{sph}$ both bodies are in the slipping mode and thus have equal accelerations and arrival times.
