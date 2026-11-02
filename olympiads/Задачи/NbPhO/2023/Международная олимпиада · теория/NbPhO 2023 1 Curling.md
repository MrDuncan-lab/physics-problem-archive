---
id: nbpho-2023-intl-theory-1
olympiad: NbPhO
year: 2023
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "1"
title: "Curling"
points: 8
authors: ["Oskar Vallhagen"]
aliases: ["Curling"]
topics: ["[[1.2 Равноускоренное прямолинейное движение]]", "[[1.17 Законы сохранения энергии и импульса]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: true
source_damaged: false
summary: "Исследовать трение, торможение и вращение скользящего камня для кёрлинга."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 1. Curling (8 points) — Oskar Vallhagen.

**NbPhO 2023** · Международная олимпиада · теория · 10–12 класс · задача 1  
Источник: [[_pdf/NbPhO/nbpho-2023.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2023.pdf#page=3|решение, стр. 3–4]]

Темы: [[1.2 Равноускоренное прямолинейное движение]], [[1.17 Законы сохранения энергии и импульса]]

> [!abstract] Кратко (составлено моделью)
> Исследовать трение, торможение и вращение скользящего камня для кёрлинга.

In the sport of curling, participants take turns sliding near-cylindrical stones across an ice court towards a target, trying to get their stones as close to the target as possible after using a set of stones. A vertical cross section of a stone is depicted below, showing that the stone is in contact with the ice on a thin ring of radius $r$. The full radius of the stone is $R$, the mass of the stone is $m$ and the coefficient of friction with the ice is $\mu$.

![[nbpho-2023-p1-c0227.png]]

Consider the case when the stone is released at a speed $v_0$ with the aim of knocking out an opponent’s stone at a distance $s$.

**i)** (1 point) Give an expression for the sliding speed $v_s$ as a function of the time $t$ since the stone was released until the stone hits the opponent’s stone.

**ii)** (1 point) What is the sliding speed $v_{hit}$ just before the stone hits the opponent’s stone?

Now the stone is given a small rotation at the initial angular speed $\omega_0$ (this can be done to alter the deflection angle of the stone when it hits the opponent’s stone). Assume that the rotation speed $\omega$ remains small throughout the sliding motion: $\omega r\ll v_s$. Keep only the main non-vanishing terms in your calculations, i.e. among the terms with a factor $(\omega r/v_s)^n$, keep only the term with the smallest $n$. Depending on your approach you may use the following approximations for $x\ll1$: $(1+x)^\alpha\approx1+\alpha x+\frac12\alpha(\alpha-1)x^2$, $\sin(\alpha+x)\approx\sin\alpha+x\cos\alpha$, $\cos x\approx1-x^2/2$. You may also need the integral $\int(at+b)^{-1}dt=a^{-1}\ln|at+b|+C$.

**iii)** (2 points) By how much does the friction force on the stone change due to its rotation? Express your answer in terms of the current angular speed $\omega$ and sliding speed $v_s$.

**iv)** (2 points) Give an expression for the torque $T$ exerted on the stone.

**v)** (2 points) What is the angular speed of the stone just before it hits the opponent’s stone?

> [!answer]- Ответ
> **i**
>
> $$
> \frac{dv_s}{dt}=-\mu g\Rightarrow v_s=v_0-\mu gt.
> $$
>
> **ii**
>
> $$
> \frac{mv_0^2}{2}=\frac{mv_{\mathrm{hit}}^2}{2}+\mu mgs\Rightarrow v_{\mathrm{hit}}=\sqrt{v_0^2-2\mu gs}.
> $$
>
> **ii**
>
> $$
> v_{\mathrm{hit}}=\sqrt{v_0^2-2\mu gs}.
> $$
>
> **iii**
>
> $$
> \Delta F_x=-\frac{\mu mg\omega^2r^2}{4v_s^2}.
> $$
>
> **iii**
>
> $$
> F_{fx}=\int_0^{2\pi}F'_{fx}rd\theta=\mu mg\left(1-\frac14\delta^2\right).
> $$
>
> **iv**
>
> $$
> \tau=-\frac{\mu mg\omega r^2}{2v_s}.
> $$
>
> **iv**
>
> $$
> \tau=\int_0^{2\pi}\tau'rd\theta=-\frac12\delta\mu mgr.
> $$
>
> **v**
>
> $$
> \omega_{\mathrm{hit}}=\omega_0\left(\frac{v_{\mathrm{hit}}}{v_0}\right)^{\frac{r^2}{R^2}}.
> $$

> [!solution]- Решение
> # 1. Curling (8 points)
>
> — Solution by Jaan Kalda, Oskar Vallhagen, grading schemes by Oskar Vallhagen.
>
> **i)** (1 point) As the stone is gliding over the ice everywhere on the contact surface, the friction force is $F_{fx}=\mu mg$, i.e. the acceleration is $\mu g$, directed in the negative $x$-direction (with the $x$-direction pointing towards the target stone). Thus, we get
>
> $$\frac{dv_s}{dt}=-\mu g\Rightarrow v_s=v_0-\mu gt.$$
>
> **ii)** (1 point) The simplest way to obtain the final velocity is to use energy conservation, noting that the friction force does a work $W_f=\mu mgs$. Thus, we get
>
> $$\frac{mv_0^2}{2}=\frac{mv_{\mathrm{hit}}^2}{2}+\mu mgs\Rightarrow v_{\mathrm{hit}}=\sqrt{v_0^2-2\mu gs}.$$
>
> Alternatively, one can first calculate the time $t_{\mathrm{hit}}$ before the stone hits the opponents stone. Integrating the expression for $v_s$ up to this time gives
>
> $$s=v_0t_{\mathrm{hit}}-\mu g\frac{t_{\mathrm{hit}}^2}{2}.$$
>
> Solving for $t_{\mathrm{hit}}$, we get
>
> $$t_{\mathrm{hit}}=\frac{v_0}{\mu g}-\sqrt{\frac{v_0^2}{\mu^2g^2}-\frac{2s}{\mu g}}$$
>
> (the solution with the plus sign gives a negative velocity). Inserting back into the expression for $v_s$ and simplifying gives
>
> $$v_{\mathrm{hit}}=\sqrt{v_0^2-2\mu gs}.$$
>
> **iii)** (2 points) Consider the motion of a point at the ring in contact with the ice at an angle $\theta$ from the $x$-axis, moving at a velocity $v$ as depicted in the figure below. The components of this motion along the $x$ and $y$ axes can be seen to be $v_x=v_s-\omega r\sin\theta$ and $v_y=\omega r\cos\theta$, respectively.
>
> ![[nbpho-2023-p3-f1.svg]]
>
> The friction force per unit length has the magnitude
>
> $$F'_f=\frac{\mu mg}{2\pi r}$$
>
> everywhere on the circle in contact with the ice, as before, but is now directed opposite to the local velocity $v$ rather than the sliding velocity $v_s$. The component of the force density in the $x$-direction thus becomes
>
> $$F'_{fx}=-F'_f\cos\varphi=-F'_f\frac{v_x}{v}.$$
>
> From this point on, there are two ways to work out the mathematical calculations. **First**, consider an infinitesimal arc of the contact ring of central angle $d\theta$; the friction force exerted on it has magnitude $dF_f=\frac{\mu mg}{2\pi}d\theta$. The total force is obviously directed antiparallel to the velocity of the stone as $y$-directional components of the acting on arcs at $\theta$ and $\pi-\theta$ cancel pairwise out. The projection of the friction force acting on our arc is given by
>
> $$dF_x=\frac{\mu mg}{2\pi}\cos\varphi d\theta$$
>
> Using the small parameter $\delta\equiv\omega r/v_s\approx\omega r/v\ll1$, we conclude that $\varphi\ll1$, hence we can use approximation
>
> $$dF_x\approx\frac{\mu mg}{2\pi}\left(1-\frac12\varphi^2\right)d\theta.$$
>
> The angle $\varphi$ can be found from the sine theorem assuming $\sin\varphi\approx\varphi$: $\varphi\approx\sin(\frac\pi2-\theta)\frac{\omega r}{v}\approx\cos\theta\frac{\omega r}{v_s}\equiv\delta\cos\theta$. Alternatively, a similarly accurate expression can be found by noting that
>
> $$\varphi\approx\tan\varphi=\frac{v_y}{v_x}\approx\frac{v_y}{v_s}=\frac{\omega r\cos\theta}{v_s}.$$
>
> Thus,
>
> $$dF_x=\frac{\mu mg}{2\pi}\left(1-\frac{\delta^2}{2}\cos^2\theta\right)d\theta.$$
>
> Recognising that $\int_0^{2\pi}\cos^2\theta d\theta=\pi$, this can be integrated to obtain
>
> $$F_x=\mu mg\left(1-\frac{\omega^2r^2}{4v_s^2}\right)$$
>
> so that the final answer is
>
> $$\Delta F_x=-\frac{\mu mg\omega^2r^2}{4v_s^2}.$$
>
> **The second way** is by continuing
>
> $$\begin{aligned}F'_{fx}&=F'_f\frac{v_x}{v}\\&=F'_f\frac{v_s-\omega r\sin\theta}{\sqrt{v_s^2-2v_s\omega r\sin\theta+\omega^2r^2}}\\&=F'_f\frac{1-\delta\sin\theta}{\sqrt{1-2\delta\sin\theta+\delta^2}}.\end{aligned}$$
>
> To second order in $\delta$, we get, using the approximation suggested in the problem text for $x=-2\delta\sin\theta+\delta^2$ and doing some elementary algebra,
>
> $$F'_{fx}\approx F'_f(1-\tfrac12\delta^2\cos^2\theta).$$
>
> The total friction force can now be obtained by integrating over the length element of size $rd\theta$ along the ring in contact with the ice, yielding, after simplifying and re-inserting the expression for $F'_f$,
>
> $$F_{fx}=\int_0^{2\pi}F'_{fx}rd\theta=\mu mg\left(1-\frac14\delta^2\right).$$
>
> **iv)** (2 points) For the torque $\tau'$ per unit length (around the central axis of the stone), we see from the figure that the angle between the local force per unit length and the radius is $\theta-\varphi$, yielding
>
> $$\tau'=F'_fr\sin(\theta-\varphi).$$
>
> From here on, there are again two ways to continue. **First**, we can use Taylor series and keep only the linear term: $\sin(\theta-\varphi)\approx\sin\theta-\varphi\cos\theta$; by using the previously obtained expression $\varphi\approx\delta\cos\theta$, we can express
>
> $$d\tau=\mu mgr(\sin\theta-\delta\cos^2\theta)\frac{d\theta}{2\pi}$$
>
> integration of which yields
>
> $$\tau=-\frac{\mu mg\omega r^2}{2v_s}.$$
>
> **The second way** is to write
>
> $$\begin{aligned}\tau'&=F'_fr\sin(\theta-\varphi)\\&=F'_fr(\sin\theta\cos\varphi-\cos\theta\sin\varphi)\\&=F'_fr(\sin\theta\frac{v_x}{v}-\cos\theta\frac{v_y}{v}),\end{aligned}$$
>
> which, using the above expressions for $v_x$ and $v_y$, can be simplified to
>
> $$\tau'=F'_fr\frac{\sin\theta-\delta}{\sqrt{1-2\delta\sin\theta+\delta^2}}.$$
>
> Applying the same approximation as in the previous part and keeping only the first, now leading, order terms in $\delta$, we get
>
> $$\tau'\approx F'_fr(\sin\theta-\delta\cos^2\theta).$$
>
> Integrating to find the total torque, we get
>
> $$\tau=\int_0^{2\pi}\tau'rd\theta=-\frac12\delta\mu mgr.$$
>
> **v)** (2 points) The equation describing the rotation is, now expressed in terms of $\omega$ and $v_s$ rather than $\delta$,
>
> $$I\frac{d\omega}{dt}=\tau=-\frac12\mu mgr^2\frac{\omega}{v_s},$$
>
> where the moment of inertia is $I\approx\frac12mR^2$. As the correction to $F_{fx}$ is only of second order in $\delta$, to the first, leading order approximation, we may neglect the effect of rotation on $F_{fx}$. Thus, the sliding speed $v_s$ has the same time dependence as in part i). The equation above can then be separated as
>
> $$\int_{\omega_0}^{\omega_{\mathrm{hit}}}\frac{d\omega}{\omega}=\int_0^{t_{\mathrm{hit}}}-\mu g\frac{r^2}{R^2}\frac{dt}{v_0-\mu gt}\Rightarrow$$
> $$\ln\frac{\omega_{\mathrm{hit}}}{\omega_0}=\frac{r^2}{R^2}\ln\frac{v_0-\mu gt_{\mathrm{hit}}}{v_0},$$
>
> which, recognising that $v_0-\mu gt_{\mathrm{hit}}=v_{\mathrm{hit}}$, yields
>
> $$\omega_{\mathrm{hit}}=\omega_0\left(\frac{v_{\mathrm{hit}}}{v_0}\right)^{\frac{r^2}{R^2}}.$$

> [!grading]- Критерии оценивания
> Grading:
>
> | Criterion | Points |
> |---|---|
> | Correct friction force | 0.5 pts |
> | Correct acceleration | 0.2 pts |
> | correct $v_s$ | 0.3 pts |
>
> **ii)**
>
> Grading:
>
> | Criterion | Points |
> |---|---|
> | Idea of using energy conservation | 0.2 pts |
> | Calculating the work done by the friction force | 0.3 pts |
> | Correct total energy conservation equation $v_s$ | 0.3 pts |
> | Correct $v_{\mathrm{hit}}$ | 0.2 pts |
>
> Grading:
>
> | Criterion | Points |
> |---|---|
> | Integration of the expression for $v_s$ | 0.4 pts |
> | Solving for $t_{\mathrm{hit}}$ | 0.4 pts |
> | Inserting into expression for $v_s$ and final answer | 0.2 pts |
>
> **iii)**
>
> Grading:
>
> | Criterion | Points |
> |---|---|
> | Understanding that the friction force is everywhere antiparallel with the local velocity | 0.4 pts |
> | Calculating the magnitude of the force per unit length | 0.3 pts |
> | Correct expression for the $x$ component | 0.2 pts |
> | **First solution:** Approximate expression for $F'_{fx}$ or $dF_{fx}$ for small $\varphi$ | 0.3 pts |
> | Expressing $\varphi$ in terms of $\delta$ and $\theta$ | 0.5 pts |
> | Correct integral and final answer | 0.3 pts |
> | **Second solution:** Expressing $F'_{fx}$ or $dF_{fx}$ in terms of $\delta$ and $\theta$ | 0.3 pts |
> | Approximate expression for $F'_{fx}$ or $dF_{fx}$ for small $\delta$ | 0.5 pts |
> | Correct integral and final answer | 0.3 pts |
>
> **iv)**
>
> Grading:
>
> | Criterion | Points |
> |---|---|
> | Finding the angle between the local force per unit length and the radius | 0.5 pts |
> | Correct expression for $\tau'$ | 0.4 pts |
> | **First solution:** Approximate expression for $\tau'$ or $d\tau$ for small $\varphi$ | 0.3 pts |
> | Expressing $\varphi$ in terms of $\delta$ and $\theta$ | 0.5 pts |
> | Correct integral and final answer | 0.3 pts |
> | **Second solution:** Expressing $\tau'$ or $d\tau$ in terms of $\delta$ and $\theta$ | 0.3 pts |
> | Approximate expression for $\tau'$ or $d\tau$ for small $\delta$ | 0.5 pts |
> | Correct integral and final answer | 0.3 pts |
>
> **v)**
>
> Grading:
>
> | Criterion | Points |
> |---|---|
> | Correct equation of motion for the rotation | 0.5 pts |
> | Realising that $v_s$ is unaffected by the rotation to leading order | 0.5 pts |
> | Using separation of variables | 0.5 pts |
> | Final answer | 0.5 pts |
