---
id: nbpho-2015-intl-theory-8
olympiad: NbPhO
year: 2015
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "8"
title: "Electric field"
points: 6
aliases: ["Electric field"]
topics: ["[[4.1 Сила Лоренца]]", "[[4 Магнетизм]]", "[[3.1 Закон Кулона. Напряжённость]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Найти магнитное поле токового кольца и электрическое поле в системе движущегося наблюдателя."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 8. ELECTRIC FIELD (6 points)

**NbPhO 2015** · Международная олимпиада · теория · 10–12 класс · задача 8  
Источник: [[_pdf/NbPhO/nbpho-2015.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2015.pdf#page=7|решение, стр. 7]]

Темы: [[4.1 Сила Лоренца]], [[4 Магнетизм]], [[3.1 Закон Кулона. Напряжённость]]

> [!abstract] Кратко (составлено моделью)
> Найти магнитное поле токового кольца и электрическое поле в системе движущегося наблюдателя.

*(by L. Franti)*

A conducting ring with radius $R$ carries a large current $I$. The ring lies stationary in the $xy$-plane with its centerpoint at $(0,0,0)$. An observer approaches the ring parallel to the $z$-axis with velocity $v$ and measures the electric field at distance $r$ from the axis. Assume that $v\ll c$ and $r\ll R$.

**i)** (2 points) Find the direction and magnitude of the magnetic field $B(z)$ on $z$ axis in stationary reference frame.

**ii)** (4 points) Estimate the magnitude and direction of electric field $E(z,r)$ measured by the observer when he is at a distance $z$ from the ring’s plane.

> [!answer]- Ответ
> **i** — $B(z)=\frac{\mu_0 I\times2\pi R\sin\alpha}{4\pi(z^2+R^2)}=\frac{\mu_0IR^2}{2(z^2+R^2)^{3/2}}$. The field is along the $z$-axis.
>
> **ii** — $E(z,r)=-\frac{rv}{2}B'(z)=\frac{3\mu_0IrR^2vz}{4(z^2+R^2)^{5/2}}$.

> [!solution]- Решение
> # 8. ELECTRIC FIELD
>
> **i)** By the Biot-Savart law, every piece of the ring with length and direction $d\vec l$ creates a magnetic field $d\vec B=\frac{\mu_0I d\vec l\times\hat a}{4\pi a^2}$, where $\vec a$ is the displacement vector from the piece to the point where we are calculating $\vec B$, and $\hat a=\vec a/a$. By symmetry, the magnetic field on the $z$-axis adds up to being exactly along the $z$-axis, because the perpendicular components cancel out. $dB_z$ is proportional to $dl$ and $d\vec l\perp\hat a$. The vector $d\vec l\times\hat a$ is at an angle $\alpha=\arctan\frac rz$ from the horizontal. Therefore we can add up the contributions and write
> $B(z)=\frac{\mu_0 I\times2\pi R\sin\alpha}{4\pi(z^2+R^2)}=\frac{\mu_0IR^2}{2(z^2+R^2)^{3/2}}$. The field is along the $z$-axis.
>
> **ii)** The electric field measured by a charged observer must be in the same direction as the Lorentz force acting on the observer in the laboratory frame of reference. Therefore the electric fieldlines are circles around the $z$-axis. Now we may apply Faraday’s induction law to such a circle, as it approaches the ring: the total electromotive force $E(z,r)\times2\pi r=\dot\Phi=-\frac{d\Phi}{dz}v\approx-\frac d{dz}B(z)\times\pi r^2\times v\implies$
> $E(z,r)=-\frac{rv}{2}B'(z)=\frac{3\mu_0IrR^2vz}{4(z^2+R^2)^{5/2}}$.
