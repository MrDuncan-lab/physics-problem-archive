---
id: nbpho-2011-intl-theory-1
olympiad: NbPhO
year: 2011
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "1"
title: "Spool"
points: 12
aliases: ["Spool"]
topics: ["[[1.7 Качение твёрдого тела]]", "[[1.13 Кинематические связи (и динамика)]]", "[[1.17 Законы сохранения энергии и импульса]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Исследовать движение катушки под действием нити и её удар о порог."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 1. Spool (12 points)

**NbPhO 2011** · Международная олимпиада · теория · 10–12 класс · задача 1  
Источник: [[_pdf/NbPhO/nbpho-2011.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2011.pdf#page=3|решение, стр. 3]]

Темы: [[1.7 Качение твёрдого тела]], [[1.13 Кинематические связи (и динамика)]], [[1.17 Законы сохранения энергии и импульса]]

> [!abstract] Кратко (составлено моделью)
> Исследовать движение катушки под действием нити и её удар о порог.

A spool with inner radius $r$ and outer radius $R$ lies on a horizontal table; the axis of the spool is horizontal. A weightless rope is wound around the inner part as shown in the picture. The loose end of the rope makes an angle $\alpha$ with the horizont (the angle $\alpha$ can be also negative). The moment of inertia of the spool is $J$ and mass — $M$. In what follows you may assume that the spool rolls on the table without slipping.

**i)** (2 pts) We pull the loose end of the rope with velocity $u$ (parallel to the loose part of the rope; that loose part can be thought to be very long). What is the velocity of the spool?

**ii)** (3 pts) Suppose now that the spool is at rest, and we apply force $F$ to the loose end of the rope (parallel to the loose part of the rope). What is the acceleration of axis of the spool?

**iii)** (2 pts) How large does the coefficient of friction $\mu$ need to be (as a function of $\alpha$) to ensure that there is no slipping between the spool and the table?

**iv)** (1.5 pts) Now the spool rolls, again, with velocity $u$; however there is no rope. The spool hits a threshold of height $H$ (see Figure); the impact is perfectly inelastic. What is the speed $v$ of the spool immediately after the impact?

**v)** (1.5 pts) What is the speed $w$ of the spool after rolling over the threshold? Assume that $u$ is such that the spool will roll over the threshold without losing contact with its edge.

**vi)** (2 pts) If the speed $u$ is too large, $u>u_0$, the spool will jump up and lose contact with the edge of the threshold. Determine $u_0$.

![[nbpho-2011-p1-f2.svg]]

> [!answer]- Ответ
> **i**
>
> $$
> u'=\frac{uR}{\sqrt{R^2\cos^2\alpha+r^2+2Rr\cos\alpha}}=\frac{uR}{|R\cos\alpha+r|}.
> $$
>
> **i**
>
> $$
> v=\frac{u_r}{\sin\alpha}=\frac{uR}{R\cos\alpha+r}.
> $$
>
> **ii**
>
> $$
> a=\frac{dv}{dt}=\frac{Fu}{Mv\left(1+\frac J{MR^2}\right)}=\frac FM\cdot\frac{\cos\alpha+\frac rR}{1+\frac J{MR^2}}.
> $$
>
> **iii**
>
> $$
> \mu_{\mathrm{min}}=\frac{\left|\frac rR-\frac J{MR^2}\cos\alpha\right|}{\left(1+\frac J{MR^2}\right)\left|\frac{Mg}{F}-\sin\alpha\right|}.
> $$
>
> **iv**
>
> $$
> v=u\left(1-\frac{H/R}{1+\frac J{MR^2}}\right).
> $$
>
> **v**
>
> $$
> w=\sqrt{v^2-\frac{2gH}{1+\frac J{MR^2}}}.
> $$
>
> **vi**
>
> $$
> u_0=\sqrt{\frac gM(R-H)}\frac{1+\frac J{MR^2}}{1+\frac J{MR^2}-\frac HR}.
> $$

> [!solution]- Решение
> # 1. Spool (12 points)
>
> **i)** **First solution.** The momentary rotation centre of the spool is the contact point $P$ with the floor (since this point is at rest). So, the velocity of the spool is $u'=R\omega$, where $\omega$ is the angular velocity. Consider triangle $POA$, where $A$ is defined as the point where the loose end of the rope meets the inner part of the spool at the current moment of time, but which is actually a point of the spool, i.e. it rolls together with the spool); $O$ is the centre of the spool. Let us denote $\angle PAO=\beta$; it is easy to see that $\angle AOP=\pi-\alpha$. The velocity $\vec v_A$ of the point $A$ is perpendicular to $PA$ and, hence, forms angle $\beta$ with the loose end of the rope. Its projection to the rope equals to $u$, therefore $v_A=u/\cos\beta$. Further, $\omega=v_A/l$, where $l=|AP|$ can be found from the cosine theorem: $l=\sqrt{R^2+r^2+2Rr\cos\alpha}$. The angle $\beta$ can be found using the sine theorem for the triangle $AOP$: $\sin\beta=\frac{R\sin\alpha}{l}$. Combining everything together we end up with
>
> $$u'=\frac{uR}{\sqrt{R^2\cos^2\alpha+r^2+2Rr\cos\alpha}}=\frac{uR}{|R\cos\alpha+r|}.$$
>
> **Second solution.** Let us decompose the velocity $\vec v_A$ into two components: the tangential component (parallel to the rope) equals (by modulus) to $u$; let us denote the radial component as $u_r$. Since the distance between $O$ and $A$ is constant, the projection of the velocities of $O$ and $A$ to the line $OA$ are equal:
>
> $$u_r=v\sin\alpha\Rightarrow v=u_r/\sin\alpha\Rightarrow\omega=u_r/R\sin\alpha.$$
>
> The vertical component of the velocity of the point $A$ remains unchanged if we switch the laboratory system of reference with the system associated with point $O$; hence,
>
> $$u\sin\alpha-u_r\cos\alpha=\omega r\sin\alpha=u_rr/R\Rightarrow$$
>
> $$v=\frac{u_r}{\sin\alpha}=\frac{uR}{R\cos\alpha+r}.$$
>
> **ii)** (2 pts) The easiest way to solve this part is to use the energy balance for infinitesimal displacement of the cylinder and apply the answer to the previous question:
>
> $$Fu\cdot dt=d\left[\frac M2v^2\left(1+\frac{J}{MR^2}\right)\right]=Mv\,dv\left(1+\frac{J}{MR^2}\right)\Rightarrow$$
>
> $$a=\frac{dv}{dt}=\frac{Fu}{Mv\left(1+\frac J{MR^2}\right)}=\frac FM\cdot\frac{\cos\alpha+\frac rR}{1+\frac J{MR^2}}.$$
>
> **iii)** Let us write the force balance projection to the horizontal axis assuming that the spool is at the edge of slipping, i.e. the friction force $F_f=\mu_{\mathrm{min}} N$, where $N=mg-F\sin\alpha$ is the normal force:
>
> $$Ma=F\cos\alpha+\mu_{\mathrm{min}} N=F\cos\alpha+\mu_{\mathrm{min}}(Mg-F\sin\alpha).$$
>
> Using the result of the previous task, we can use this equation directly to obtain an expression for the minimal allowed value of the coefficient of friction:
>
> $$\mu_{\mathrm{min}}=\frac{\left|\frac rR-\frac J{MR^2}\cos\alpha\right|}{\left(1+\frac J{MR^2}\right)\left|\frac{Mg}{F}-\sin\alpha\right|}.$$
>
> **iv)** The angular moment of the spool with respect to the edge of the threshold conserves during the impact (since the impact force has zero arm):
>
> $$Mu(R-H)+J\frac uR=(J+MR^2)\frac vR\Rightarrow$$
>
> $$v=u\left(1-\frac{H/R}{1+\frac J{MR^2}}\right).$$
>
> **v)** From the energy conservation law we obtain immediately
>
> $$(J+MR^2)\frac{v^2}{R^2}=(J+MR^2)\frac{w^2}{R^2}+2MgH\Rightarrow$$
>
> $$w=\sqrt{v^2-\frac{2gH}{1+\frac J{MR^2}}}.$$
>
> **vi)** The spool is the most prone to jumping immediately after the impact; the gravity force needs to be large enough to bind the centre of mass to the rotational motion around the edge of the threshold:
>
> $$\frac{Mv^2}{R}\leq g\frac{R-H}{R}\Rightarrow v^2\leq\frac gM(R-H)\Rightarrow$$
>
> $$u_0=\sqrt{\frac gM(R-H)}\frac{1+\frac J{MR^2}}{1+\frac J{MR^2}-\frac HR}.$$
