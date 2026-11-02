---
id: nbpho-2004-intl-theory-1
olympiad: NbPhO
year: 2004
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "1"
title: "Rubber fiber"
points: 12
aliases: ["Rubber fiber"]
topics: ["[[1.15 Упругость. Весомая пружина]]", "[[1.20 Колебания]]", "[[1.17 Законы сохранения энергии и импульса]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Исследовать нелинейную упругость резинового волокна и малые колебания вращающегося тела."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 1. Rubber fiber (12 pts)

**NbPhO 2004** · Международная олимпиада · теория · 10–12 класс · задача 1  
Источник: [[_pdf/NbPhO/nbpho-2004.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2004.pdf#page=3|решение, стр. 3]]

Темы: [[1.15 Упругость. Весомая пружина]], [[1.20 Колебания]], [[1.17 Законы сохранения энергии и импульса]]

> [!abstract] Кратко (составлено моделью)
> Исследовать нелинейную упругость резинового волокна и малые колебания вращающегося тела.

Fibers made of elastic rubber can be stretched to lengths $l$, much longer than the length in undeformed state $l_0$. For such rubbers, the net volume of the fiber remains constant.

**1)** Express the cross-sectional area $S$ of such a fiber in a deformed state via its length $l$ and initial dimensions $l_0$, $S_0$ (1 pt).

**2)** For small deformations of an elastic material, the stretching force $F$ and deformation $x$ are related to each other by the Hooke’s law $F=k_0x$, where the stiffness $k_0=E_0S_0/l_0$ and $E_0$ is the Young’s modulus of the rubber. For non-small (possibly large, $l\gg l_0$) deformations of elastic rubber, however, the Hooke’s law is substituted by a non-linear law, $F(l)=a+\frac bl$ (breaking of this law at very large values of $l$ will not be studied here). Express the constants $a$ and $b$ in terms of $l_0$, $S_0$, and $E_0$ (2 pt).

**3)** Suppose such a fiber is stretched by some force up to the length $l$. A small change $\Delta F$ of the stretching force results in a small change in the length $\Delta l\ll l$. Express $\Delta F$ in terms of $l$, $l_0$, $S_0$, $E_0$, and $\Delta l$ (1 pt).

**4)** Suppose a small body is fixed to an one end of the fiber and the system is put into rotation around the other end of the fiber. In the case of a circular motion of the body, express the length of the fiber $l$ via $l_0$, $S_0$, $E_0$, and the kinetic energy of the body $K$ (the kinetic energy of the fiber and gravity can be neglected). (1.5 pts)

**5)** Let us analyse a slightly non-circular motion of the body. Let us describe the motion of the system by the length change of the fiber $r(t)=l(t)-l(0)$, the radial $v_r(t)$ and tangential $v_t(t)$ velocities of the body (the components respectively parallel and perpendicular to the fiber). The initial values of these quantities are designated as $L\equiv l(0)$, $V_r\equiv v_r(0)$, and $V_t\equiv v_t(0)$. The values $L$ and $V_t$ are chosen so that if the initial radial velocity were zero, the motion would be circular. Write down two independent equations relating $r(t)$, $v_r(t)$, and $v_t(t)$ to each other (using also the mass of the body $m$, together with the parameters $L$, $V_r$, $V_t$, $l_0$, $S_0$, $E_0$). (3.5 pts).

**6)** Find the relationship between $r(t)$ and $v_r(t)$ (containing also the parameters $m$, $L$, $V_r$, $V_t$, $l_0$, $S_0$, $E_0$) assuming that $|r|\ll L$, and find the period $T$ of small oscillations of $r(t)$. Simplify the expression of $T$ for $L\gg l_0$ (3 pts).

> [!answer]- Ответ
> **1** — $S=S_0l_0/l$.
>
> **2** — $b=-E_0S_0l_0$ (1 pt). Besides, at $l=l_0$, $F=0$ (0.5 pts), hence $a+\frac bl=0$ and
>
> **2** — $a=E_0S_0$ (1 pt).
>
> **3** — $\Delta F\approx\frac{dF}{dl}dl=E_0S_0\frac{l_0\delta l}{l^2}$.
>
> **4** — $l=l_0+\frac{2K}{E_0S_0}$.
>
> **5** — $v_t=V_t\frac L{L+r}$ (1.5 pts). Conservation of energy:
>
> **5** — $\frac m2(v_t^2+v_r^2)+E_0S_0(r-l_0\ln\frac{r+L}{L})=\frac m2(V_t^2+V_r^2)$ (2 pts).
>
> **6** — $T=2\pi L/\sqrt{3V_t^2+E_0S_0l_0m^{-1}}\approx2\pi L/\sqrt3V_t$ (0.3+0.2 pts).

> [!solution]- Решение
> # 1. Rubber fiber (12 pts)
>
> **1)** Volume conservation: $Sl=S_0l_0$, hence
> $S=S_0l_0/l$.
>
> **2)** At the limit of small deformations, $F(l)=a+\frac bl\approx a-bx/l_0^2=k_0x$, hence $E_0S_0/l_0=-b/l_0^2$, hence
> $b=-E_0S_0l_0$ (1 pt). Besides, at $l=l_0$, $F=0$ (0.5 pts), hence $a+\frac bl=0$ and
> $a=E_0S_0$ (1 pt).
>
> **3)**
> $\Delta F\approx\frac{dF}{dl}dl=E_0S_0\frac{l_0\delta l}{l^2}$.
>
> **4)** Newton II law: $E_0S_0(1-\frac{l_0}l)=2K/l$, hence
> $l=l_0+\frac{2K}{E_0S_0}$.
>
> **5)** Conservation of angular momentum: $lv_t=LV_t$, hence
> $v_t=V_t\frac L{L+r}$ (1.5 pts). Conservation of energy:
> $\frac m2(v_t^2+v_r^2)+E_0S_0(r-l_0\ln\frac{r+L}{L})=\frac m2(V_t^2+V_r^2)$ (2 pts).
>
> **6)** Substituting $v_t$ from the angular momentum conservation law into the energy equation we obtain $\frac m2[V_t^2(\frac L{L+r})^2+v_r^2]+E_0S_0(r-l_0\ln\frac{r+L}{L})=\frac m2(V_t^2+V_r^2)$ (0.4 pts). Further we make use of condition $|r|\ll L$ and substitute $(\frac L{L+r})^2\approx1-2\frac rL+3(\frac rL)^2$ (0.4 pts), $\ln\frac{r+L}{L}\approx\frac rL-\frac12(\frac rL)^2$ (0.4 pts). Linear in $r$ terms cancel out due to the condition $E_0S_0(1-\frac{l_0}L)=mV_t^2/L$ (0.4 pts). So, we arrive at
> $\frac m2[3V_t^2(\frac rL)^2+v_r^2]+\frac12E_0S_0l_0(\frac rL)^2=\frac m2V_r^2$ (0.4 pts). This is the energy conservation law for a pendulum consisting of a spring with effective stiffness $k_{eff}=(3mV_t^2+E_0S_0l_0)L^{-2}$ and of a body with effective mass $m_{eff}=m$ (0.5 pts). So,
> $T=2\pi L/\sqrt{3V_t^2+E_0S_0l_0m^{-1}}\approx2\pi L/\sqrt3V_t$ (0.3+0.2 pts).
