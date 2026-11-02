---
id: nbpho-2013-intl-theory-7
olympiad: NbPhO
year: 2013
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "7"
title: "Burning with a lens"
points: 7
aliases: ["Burning with a lens"]
topics: ["[[6.3 Линзы]]", "[[2.5 Первое начало термодинамики]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Оценить температуру пластинки, нагреваемой солнечным светом через линзу, и предельный размер линзы."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 7. BURNING WITH A LENS (7 points)

**NbPhO 2013** · Международная олимпиада · теория · 10–12 класс · задача 7  
Источник: [[_pdf/NbPhO/nbpho-2013.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2013.pdf#page=5|решение, стр. 5]]

Темы: [[6.3 Линзы]], [[2.5 Первое начало термодинамики]]

> [!abstract] Кратко (составлено моделью)
> Оценить температуру пластинки, нагреваемой солнечным светом через линзу, и предельный размер линзы.

Sunrays are focused with a lens of diameter $d=10\mathrm{cm}$ and focal length of $f=7\mathrm{cm}$ to a black thin plate. Behind the plate is a mirror. Angular diameter of the Sun is $\alpha=32'$ and its intensity on the surface of the Earth is $I=1000\mathrm{W/m^2}$, Stefan-Boltzmann constant $\sigma=5.670\times10^{-8}\,\mathrm{W/(m^2K^4)}$.

**i)** (4 points) Find the temperature of the heated point of the plate.

**ii)** (3 points) Using thermodynamic arguments, estimate the maximal diameter of the lens for which this model can be used.

> [!answer]- Ответ
> **i**
>
> $$
> T=\sqrt{\frac d{\alpha f}\sqrt{\frac I\sigma}}\approx4500\mathrm{K}.
> $$
>
> **ii** — $d\leq2f$.

> [!solution]- Решение
> # 7. BURNING WITH A LENS (7 points)
>
> The solar energy flux which is focused by the lens to the image of the Sun can be calculated as $P=\frac\pi4d^2I$; the image of the Sun radiates according to the Stefan-Boltzmann law with the total power $P=\frac\pi4(\alpha f)^2\sigma T^4$. From the heat balance we obtain $\frac\pi4d^2I=\frac\pi4(\alpha f)^2\sigma T^4$, hence
>
> $$T=\sqrt{\frac d{\alpha f}\sqrt{\frac I\sigma}}\approx4500\mathrm{K}.$$
>
> Due to the second law of thermodynamics, it is impossible to direct heat energy from a lower temperature body to a higher temperature body. Hence, the image temperature cannot exceed the temperature of the Sun. Now we can use the known temperature of Sun $T_0=6000\mathrm{K}$, but it is better to use the Stefan-Boltzmann law for solar radiation flux density: near the Sun’s surface, $I_0=\sigma T_0^4$, with the total flux of $P_t=4\pi R_s^2I_0$. Near the Earth, the total flux $P_t=4\pi L^2I$; here, $R_s$ is the Sun’s radius, and $L$ — the orbital radius of the Earth. From here we obtain $I=I_0R_s^2/L^2=\sigma T_0^4R_s^2/L^2$; using the previous result,
>
> $$T=T_0\sqrt{\frac d{\alpha f}\frac{R_s}{L}}.$$
>
> Let us note that $\alpha L=2R_s$, hence
>
> $$T=T_0\sqrt{\frac d{2f}}\leq T_0,$$
>
> which means that
> $d\leq2f$.
