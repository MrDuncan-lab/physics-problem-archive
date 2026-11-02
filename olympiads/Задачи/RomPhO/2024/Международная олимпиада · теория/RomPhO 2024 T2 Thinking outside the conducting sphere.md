---
id: rompho-2024-intl-theory-t2
olympiad: RomPhO
year: 2024
stage: "Международная олимпиада"
round: теория
grade: ""
number: "T2"
title: "Thinking outside the conducting sphere"
aliases: ["Thinking outside the conducting sphere"]
topics: ["[[3.6 Проводники]]", "[[3.1 Закон Кулона. Напряжённость]]", "[[1.17 Законы сохранения энергии и импульса]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Найти силы и скорости заряженных частиц и диэлектрических шаров внутри и вне заземлённой проводящей сферы."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# Q2: Thinking outside the conducting sphere

**RomPhO 2024** · Международная олимпиада · теория · задача T2  
Источник: [[_pdf/RomPhO/RomPhO-2024-T2.pdf#page=1|условие, стр. 1–2]] · [[_pdf/RomPhO/RomPhO-2024-T2-solution.pdf#page=3|решение, стр. 3–4]]

Темы: [[3.6 Проводники]], [[3.1 Закон Кулона. Напряжённость]], [[1.17 Законы сохранения энергии и импульса]]

> [!abstract] Кратко (составлено моделью)
> Найти силы и скорости заряженных частиц и диэлектрических шаров внутри и вне заземлённой проводящей сферы.

Consider a conducting sphere that is grounded (i.e., has zero electric potential) that has a radius $R$. There are two charged point-like particles, one inside the sphere at a location $\vec r$ ($|\vec r|<R$), of charge $q$, and one outside the sphere, at a location $\vec r'$ ($|\vec r'|>R$), of charge $q'$, as in the figure below.

![[rompho-2024-t2-problems-p1-f1.png]]

**a)** Find the electric force that acts on the particle of charge $q$ and on the particle of charge $q'$, respectively. **3.5 p**

Consider a similar setup as in point **a)** by replacing the point-like particles with two dielectric spheres of finite radius:

![[rompho-2024-t2-problems-p1-f3.png]]

One sphere, of radius $a$, has a homogenous charge density $\rho$, is centered at $\vec r$ and lies fully within the conducting grounded sphere ($|\vec r|+a<R$). The other sphere, of radius $a'$, with a homogenous charge density $\rho'$, is centered at $\vec r'$ and lies fully outside the conducting grounded sphere ($|\vec r'|+a>R$).

**b)** Find the electric force that acts on the sphere with charge density $\rho$ and on the sphere with charge density $\rho'$, respectively. **3.5 p**

The spheres have masses $m$ (for the sphere with charge density $\rho$) and $m'$ (for the sphere with charge density $\rho'$).

**c)** Starting at rest in the configuration in point **b)** (with initial locations $\vec r_0$ and $\vec r_0'$ for the centers of the spheres), find the relationship between the velocity of each sphere and its position. Calculate their speeds when they touch the conducting sphere. Do not consider the spheres movement after they touch the conducting sphere. Furthermore, consider that the masses of the spheres are sufficiently large so that their velocities and accelerations are sufficiently small in order to neglect the induction of any magnetic fields. **3.0 p**

Proposed by  
Assist. Prof. Luca ILIEŞIU, PhD  
Department of Physics, University of California at Berkeley, USA

> [!answer]- Ответ
> **a**
>
> $$
> \vec F_{\mathrm{inside}}=\frac{1}{4\pi\epsilon_0}\frac{q^2R}{|\vec r|^3\left(\frac{R^2}{|\vec r|^2}-1\right)^2}\hat r,
> $$
>
> **a**
>
> $$
> \vec F_{\mathrm{outside}}=-\frac{1}{4\pi\epsilon_0}\frac{(q')^2R}{|\vec r'|^3\left(1-\frac{R^2}{|\vec r'|^2}\right)^2}\hat r'.
> $$
>
> **b**
>
> $$
> \vec F_{\mathrm{inside}}=\frac{1}{4\pi\epsilon_0}\frac{q^2R}{|\vec r|^3\left(\frac{R^2}{|\vec r|^2}-1\right)^2}\hat r,\qquad \vec F_{\mathrm{outside}}=-\frac{1}{4\pi\epsilon_0}\frac{(q')^2R}{|\vec r'|^3\left(1-\frac{R^2}{|\vec r'|^2}\right)^2}\hat r'.
> $$
>
> **c**
>
> $$
> \frac{m\dot r^2(t)}2=\int_{\vec r_0}^{\vec r}\vec F_{\mathrm{inside}}(\vec x)d\vec x=\frac{1}{8\pi\epsilon_0}\frac{q^2R}{R^2-r^2}-\frac{1}{8\pi\epsilon_0}\frac{q^2R}{R^2-r_0^2}\quad\Rightarrow\quad\dot r=\left[\frac{q^2R}{4\pi\epsilon_0 m}\left(\frac1{R^2-r^2}-\frac1{R^2-r_0^2}\right)\right]^{\frac12}.
> $$
>
> **c**
>
> $$
> \dot r_{\mathrm{sph.\ inside}}=\left[\frac{q^2R}{4\pi\epsilon_0 m}\left(\frac1{R^2-(R-a)^2}-\frac1{R^2-r_0^2}\right)\right]^{\frac12}.
> $$
>
> **c**
>
> $$
> \frac{m(\dot r'(t))^2}{2}=\int_{\vec r'_0}^{\vec r'}\vec F_{\mathrm{outside}}(\vec x)d\vec x=\frac1{8\pi\epsilon_0}\frac{q^2R}{(r')^2-R^2}-\frac1{8\pi\epsilon_0}\frac{q^2R}{(r'_0)^2-R^2}\quad\Rightarrow
> $$
>
> $$
> \Rightarrow\quad\dot r'=-\left[\frac{q^2R}{4\pi\epsilon_0 m}\left(\frac1{(r')^2-R^2}-\frac1{(r'_0)^2-R^2}\right)\right]^{\frac12}.
> $$
>
> **c**
>
> $$
> \dot r_{\mathrm{sph.\ outside}}=-\left[\frac{q^2R}{4\pi\epsilon_0 m}\left(\frac1{(R+a)^2-R^2}-\frac1{(r'_0)^2-R^2}\right)\right]^{\frac12}.
> $$

> [!solution]- Решение
> **Problem 2. Thinking outside the conducting sphere.** Solution.
>
> **a)** [3.5 points] Because the conducting sphere is grounded, we can treat the two-point particles as non-interacting. To compute the forces, we thus wish to compute the electric field inside and outside the conductor, and, for this, we will use the method of images. We wish to find the image charges for the inside and outside charges such that the electric potential vanishes on the surface of the sphere. This is achieved by placing the image charges between the center of the sphere and the inside/outside charges at a location $\vec p$ with a charge $\tilde q$ for the image of the inside charge and at a location $\vec p'$ with charge $\tilde q'$ for the outside charges. The potential on the inside of the sphere at a location $\vec x$ ($|\vec x|<R$) is given by
>
> $$
> V_{\mathrm{inside}}(\vec x)=\frac{1}{4\pi\epsilon_0}\left[\frac{q}{|\vec x-\vec r|}+\frac{\tilde q}{|\vec x-\vec p|}\right]. \tag{2.1}
> $$
>
> Imposing that this potential vanishes on the surface of the sphere, we find (1 point)
>
> $$
> \tilde q=-q\frac{R}{r},\qquad \vec p=\frac{R^2}{|\vec r|}\hat r,
> $$
>
> which thus lies outside the sphere. Similarly, on the outside, at a location $\vec x$ ($|\vec x|>R$), we have
>
> $$
> V_{\mathrm{outside}}(\vec x)=\frac{1}{4\pi\epsilon_0}\left[\frac{q'}{|\vec x-\vec r'|}+\frac{\tilde q'}{|\vec x-\vec p'|}\right]. \tag{2.2}
> $$
>
> Once again imposing that this vanishes on the surface of the sphere, we find (1 point)
>
> $$
> \tilde q'=-q'\frac{R}{r'},\qquad \vec p'=\frac{R^2}{|\vec r'|}\hat r'.
> $$
>
> which thus lies inside the sphere. The force on the particle inside is simply given by the attraction to the image charge outside, while the force on the particle outside is given by the attraction to the image charge inside. The former is given by (0.75 points)
>
> $$
> \vec F_{\mathrm{inside}}=\frac{1}{4\pi\epsilon_0}\frac{q^2R}{|\vec r|^3\left(\frac{R^2}{|\vec r|^2}-1\right)^2}\hat r,
> $$
>
> while the latter is (0.75 points)
>
> $$
> \vec F_{\mathrm{outside}}=-\frac{1}{4\pi\epsilon_0}\frac{(q')^2R}{|\vec r'|^3\left(1-\frac{R^2}{|\vec r'|^2}\right)^2}\hat r'.
> $$
>
> **b)** [3.5 points] One approach to generalize the solution above when we replace the point particles with spheres is to find the image charges for each charge element $dq$ that is part of the interior of the two homogeneously charged spheres. This is, however, unnecessarily complicated. Instead, we can notice that because the contribution to the electric potential from a homogeneously charged sphere is the same as that of a charged particle placed at the center of the sphere (with a charge $q=\frac43\pi a^3\rho$ for the inside and a charge $q'=\frac43\pi(a')^3\rho'$ for the outside) the same image charges studied in part a) make the potential vanish on the surface of the conductor! Thus, outside the volumes of the homogeneously charged spheres, the electric potentials (2.1) and (2.2) found in point a) are unchanged (2.0 points). The forces acting on the inside and outside spheres are, thus, again (1.5 points)
>
> $$
> \vec F_{\mathrm{inside}}=\frac{1}{4\pi\epsilon_0}\frac{q^2R}{|\vec r|^3\left(\frac{R^2}{|\vec r|^2}-1\right)^2}\hat r,\qquad \vec F_{\mathrm{outside}}=-\frac{1}{4\pi\epsilon_0}\frac{(q')^2R}{|\vec r'|^3\left(1-\frac{R^2}{|\vec r'|^2}\right)^2}\hat r'.
> $$
>
> where
>
> $$
> q=\frac43\pi a^3\rho,\qquad q'=\frac43\pi(a')^3\rho'. \tag{2.3}
> $$
>
> **c)** [3 points] Because the particles (or spheres) do not interact, we can use conservation of energy separately for the charged particles (or spheres) inside or outside the conductor. Since the force is always in the direction $\hat r_0$ for the particle or sphere inside (and in the direction $\hat r'_0$ for the particle or sphere outside) the only component of the velocity will be along the $\hat r_0$ direction (or the $\hat r'_0$ direction). For the particle or sphere inside, conservation of energy tells us that (1.0 points)
>
> $$
> \frac{m\dot r^2(t)}2=\int_{\vec r_0}^{\vec r}\vec F_{\mathrm{inside}}(\vec x)d\vec x=\frac{1}{8\pi\epsilon_0}\frac{q^2R}{R^2-r^2}-\frac{1}{8\pi\epsilon_0}\frac{q^2R}{R^2-r_0^2}\quad\Rightarrow\quad\dot r=\left[\frac{q^2R}{4\pi\epsilon_0 m}\left(\frac1{R^2-r^2}-\frac1{R^2-r_0^2}\right)\right]^{\frac12}. \tag{2.4}
> $$
>
> When the inside sphere hits the surface of the conductor, we have (0.5 point)
>
> $$
> \dot r_{\mathrm{sph.\ inside}}=\left[\frac{q^2R}{4\pi\epsilon_0 m}\left(\frac1{R^2-(R-a)^2}-\frac1{R^2-r_0^2}\right)\right]^{\frac12}. \tag{2.5}
> $$
>
> Note that if the point particle were to hit the conductor ($a\to0$) its velocity would be infinite and we could not neglect the effect of magnetic induction.
>
> For the particle or sphere outside, we similarly have (1.0 point)
>
> $$
> \frac{m(\dot r'(t))^2}{2}=\int_{\vec r'_0}^{\vec r'}\vec F_{\mathrm{outside}}(\vec x)d\vec x=\frac1{8\pi\epsilon_0}\frac{q^2R}{(r')^2-R^2}-\frac1{8\pi\epsilon_0}\frac{q^2R}{(r'_0)^2-R^2}\quad\Rightarrow
> $$
> $$
> \Rightarrow\quad\dot r'=-\left[\frac{q^2R}{4\pi\epsilon_0 m}\left(\frac1{(r')^2-R^2}-\frac1{(r'_0)^2-R^2}\right)\right]^{\frac12}. \tag{2.6}
> $$
>
> When the sphere touches the conductor (0.5 points), we have
>
> $$
> \dot r_{\mathrm{sph.\ outside}}=-\left[\frac{q^2R}{4\pi\epsilon_0 m}\left(\frac1{(R+a)^2-R^2}-\frac1{(r'_0)^2-R^2}\right)\right]^{\frac12}. \tag{2.7}
> $$
>
> The velocity would once again be infinite when the sphere would be replaced by a point particle.
