---
id: nbpho-2025-intl-theory-7
olympiad: NbPhO
year: 2025
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "7"
title: "Charged Rod"
points: 6
authors: ["Jaan Kalda"]
aliases: ["Charged Rod"]
topics: ["[[4.1 Сила Лоренца]]", "[[1.11 Центр масс]]", "[[1.3 Равноускоренное криволинейное движение]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: true
source_damaged: false
summary: "Движение и вращение равномерно заряженного стержня в однородном магнитном поле."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 7. Charged Rod (6 points) — Jaan Kalda.

**NbPhO 2025** · Международная олимпиада · теория · 10–12 класс · задача 7  
Источник: [[_pdf/NbPhO/nbpho-2025.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2025.pdf#page=8|решение, стр. 8]]

Темы: [[4.1 Сила Лоренца]], [[1.11 Центр масс]], [[1.3 Равноускоренное криволинейное движение]]

> [!abstract] Кратко (составлено моделью)
> Движение и вращение равномерно заряженного стержня в однородном магнитном поле.

A rod of mass $m$ carries a charge $q$; both the charge and the mass are homogeneously distributed over its entire length $l$. The system is in homogeneous magnetic field of strength $B$, parallel to the $z$-axis whereas the rod is in the $x$–$y$-plane. Neglect any forces except for the Lorentz force. One end of the rod is painted red, and the other — blue.

**i)** (2 points) Consider the case when the rod rotates around its centre of mass. What should be the angular speed $\omega$ for the mechanical tension force at the centre of the rod to be zero?

**ii)** (4 points) Consider now a case when initially the blue end of the rod is at the origin ($x = y = 0$), and the red end at $x = l$. The blue end’s initial speed is zero while the red end’s speed is $v$, parallel to the $y$-axis. It turns out that after a certain time $t$, the red end passes through the origin. Find the smallest possible value for $t$ and express the corresponding value of $v$ in terms of $m$, $q$ and $l$.

> [!answer]- Ответ
> **i** — $\omega = \frac{Bq}{m}$.
>
> **ii** — $v = \pi l/T = \frac{lBq}{2m}$.

> [!solution]- Решение
> # 7. Charged Rod (6 points) — Solution by Jaan Kalda, grading schemes by....
>
> **i)** (2 points) Notice that all particles with the same charge-to-mass ratio orbit in a homogeneous magnetic field $B$ with the same frequency $\omega_B = \frac{Bq}{m}$; the orbit is a circle of radius $r = \frac{v}{\omega_B}$. Indeed, the Lorentz force must provide the centripetal acceleration, hence $Bqv = mv\omega_B \Rightarrow \omega_B = \frac{Bq}{m}$.
>
> Since the mass-to-charge ratio is the same for all the fictitious pieces of the rod, if the rod rotates with angular speed $\omega = \frac{Bq}{m}$, then the Lorentz force provides exactly the needed acceleration to all these pieces, and the tension force is zero everywhere.
>
> On the other hand, if the angular speed were smaller or larger, we would have either $Bqv < mv\omega$ or $Bqv > mv\omega$ for all the pieces, resulting in either stretching or compressive tension force at the centre of the rod, respectively. Therefore, the answer is
>
> $\omega = \frac{Bq}{m}$.
>
> **ii)** (4 points) To begin with, let us notice that if a system of charges with the same charge-to-mass ratio $\alpha = q/m$ moves in a homogeneous magnetic field, the centre of mass will move along a circle with cyclotron frequency $\omega_B$. Indeed, the total Lorentz force acting on the system is
>
> $$\sum_i q_i\frac{d\vec r_i}{dt}\times\vec B = \alpha\sum_i m_i\frac{d\vec r_i}{dt}\times\vec B = \alpha\frac{d\vec r_C}{dt}\times\vec B\sum_i m_i.$$
>
> So, Newton’s second law reads
>
> $$\frac{d^2\vec r_C}{dt^2}\sum_i m_i = \frac qm\frac{d\vec r_C}{dt}\times\vec B\sum_i m_i.$$
>
> The total mass of the system cancels out from this equation, and we can see that the centre of mass $\vec r_C$ moves in the same way as a point charge $q$ with mass $m$.
>
> *Alternatively*, the same can be achieved through integration. From Newton’s second law $m\vec a_C = \int dq\,\vec v\times\vec B$, where $\vec v$ is the velocity of the charge element $dq$. But since the mass and charge distributions are homogenous, $dq = \frac qm dm$ and $\vec B$ is constant so it can be taken out from the integral to achieve $m\vec a_C = \frac qm(\int\vec v\,dm)\times\vec B$. But now the integral is just $m\vec v_C$ (can be seen directly or through the definition of centre of mass $\int\frac{d\vec r}{dt}\,dm = \frac d{dt}\int\vec r\,dm = m\vec r_C$. Thus we get $m\vec a_C = q\vec v_C\times\vec B$.
>
> Additionally, the rod can (and will) rotate with a constant speed. The fact that the angular speed must be constant follows from the conservation of kinetic energy of the rod, which is the sum of the kinetic energy of its centre of mass and the rotational energy around the centre of mass. The former is constant, so the latter must be as well.
>
> The centre of mass moves with speed $v/2$ and draws a circle of radius $R = \frac{mv}{2Bq}$ that passes through the point $(\frac l2,0)$ and for which the $x$-axis is a symmetry axis. The red end can reach the origin only when the centre of mass is at a distance $\frac l2$ from the origin.
> This can happen either after a full cyclotron period $T = 2\pi/\omega_B$, or at any moment assuming $R = \frac l2$ and the circle is centred around the origin.
>
> To determine if this can happen earlier than after time $T$, let us assume that $R = \frac{mv}{2Bq} = \frac l2$. In that case, the angular speed of the rod’s rotation is $\Omega = \frac vl$, and we get $v = \frac{Bql}{m}$. This means $\Omega = \frac{Bq}{m} = \omega_B$, i.e., the rod’s rotational angular speed is the same as the centre of mass’ angular speed in its orbit, which would cause the blue end to remain at the origin.
>
> Next, we examine if the red end can reach the origin after time $T$. For this to happen, the condition is that $\Omega T = (2\pi n+\pi)$, where $n$ is an integer. Since $\Omega = v/l$ and we need to minimize $v$, we take $n = 0$ to obtain
>
> $v = \pi l/T = \frac{lBq}{2m}$.

> [!grading]- Критерии оценивания
> Grading: (preliminary)
>
> | Criterion | Points |
> |---|---|
> | Considers forces on an infinitesimal part of the rod | 0.4 pts |
> | Equates, with justification, Lorentz and centrifugal forces $dqvB = dm\omega^2r$ | 0.4 pts |
> | Uses $\omega = \frac vr$ | 0.4 pts |
> | Uses $\frac{dq}{dm} = \frac qm$ | 0.4 pts |
> | Expresses $\omega = \frac{qB}{m}$ | 0.4 pts |
>
> **ii)**
>
> Grading: (preliminary)
>
> | Criterion | Points |
> |---|---|
> | Deduces, with justification, that the net force on the rod $\vec F = q\vec v_C\times\vec B$ | 0.5 pts |
> | Uses $v_C = v/2$ | 0.2 pts |
> | Justifies that the COM moves on a circular path | 0.3 pts |
> | Expresses the radius of the path traced by the COM $R = \frac{mv}{2qB}$ | 0.3 pts |
> | Concludes that the angular velocity of the COM is $\omega = \frac{qB}{m}$ | 0.2 pts |
> | Expresses the angular velocity of the rotation around the COM $\Omega = \frac vl$ | 0.2 pts |
> | Justifies that $\Omega$ is conserved | 0.3 pts |
> | Argues that $t < \frac{2\pi}{\omega}$ is possible only if $R = l/2$ | 0.5 pts |
> | Justifies that in this case, the red end will never end up at the origin | 0.5 pts |
> | Justifies that $\Omega t = \pi+2\pi k$ with $k \in \mathbb Z_{\geq 0}$ | 0.4 pts |
> | Expresses $v = \frac{qBl}{m}(\frac12+k)$ | 0.6 pts |
