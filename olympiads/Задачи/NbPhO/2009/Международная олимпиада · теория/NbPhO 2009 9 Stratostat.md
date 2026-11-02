---
id: nbpho-2009-intl-theory-9
olympiad: NbPhO
year: 2009
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "9"
title: "Stratostat"
points: 5
aliases: ["Stratostat"]
topics: ["[[2.2 Уравнение состояния идеального газа]]", "[[1.18 Гидростатика]]"]
difficulty: 3
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Вывести барометрическую формулу и найти высоту полного наполнения стратостата гелием."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 9. Stratostat (5 points)

**NbPhO 2009** · Международная олимпиада · теория · 10–12 класс · задача 9  
Источник: [[_pdf/NbPhO/nbpho-2009.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2009.pdf#page=4|решение, стр. 4]]

Темы: [[2.2 Уравнение состояния идеального газа]], [[1.18 Гидростатика]]

> [!abstract] Кратко (составлено моделью)
> Вывести барометрическую формулу и найти высоту полного наполнения стратостата гелием.

**i)** Show that the pressure of an isothermal gas of molar mass $\mu$ follows the law $p=p_0e^{-\alpha z}$, where $p_0$ is the pressure at the origin, and $z$ is the height. Find the constant $\alpha$. The temperature is $T$, the free fall acceleration is $g$.

**ii)** Consider a stratostat, the envelope of which (a freely deformable non-elastic sack) is filled at the Earth’s surface by helium to the volume fraction of $\beta=10\%$. At which height $h$ does the helium expand so that it fills the entire volume of the stratostat? The molar masses of the air and helium are $\mu_a=29\,\mathrm{g/mol}$ and $\mu_{He}=4\,\mathrm{g/mol}$, respectively. You may neglect the temperature variations of the atmosphere, and use the value $T=250\,\mathrm K$.

> [!answer]- Ответ
> **i** — $\alpha=\frac{\mu g}{RT}$.
>
> **ii** — $h=\frac{RT}{\mu_a g}\ln\frac1\beta$, $h=17\,\mathrm{km}$.

> [!solution]- Решение
> # 9. Stratostat (5 points)
>
> **i)** Consider the pressure difference at heights $z+dz$ and $z$: $dp=-\rho gdz$ (the difference is simply due to the weight of the layer $dz$). The density can be found using the state equation of ideal gas: $pV=\frac m\mu RT$, $\rho=\frac mV=\frac{\mu p}{RT}$. Therefore $\frac1p\frac{dp}{dz}=-\frac{\mu g}{RT}$. Note that we have a derivative of a logarithm: $\frac1p\frac{dp}{dz}=\frac{d\ln p(z)}{dz}$. Therefore $\ln(p/p_0)=-\alpha z$, $p=p_0e^{-\alpha z}$, where
> $\alpha=\frac{\mu g}{RT}$.
>
> Alternatively, we can derive this law from the Boltzmann distribution for the particle density $n=n_0e^{-U/kT}$, where $U$ is the potential energy of a molecule. Bearing in mind that for a constant temperature, the pressure is proportional to the density, we obtain $p=p_0e^{-U/kT}$. Substituting $U=mgz=\frac\mu{N_A}gz$ and $R=kN_A$, we obtain the same result as above.
>
> **ii)** Clearly, the pressures inside and outside of the stratostat are equal and depending on the height as $p=p_0e^{-\alpha z}$, where $\alpha=\frac{\mu_a g}{RT}$. For helium inside the sack $pV=const$. Let the volume of the stratostat be $V_S$, therefore $p_0\beta V_S=pV_S$, where $p$ is the pressure at the height, where helium has filled the entire volume. Since $p=\beta p_0$, we obtain $\frac{\mu_a g}{RT}h=-\ln\beta$,
> $h=\frac{RT}{\mu_a g}\ln\frac1\beta$, $h=17\,\mathrm{km}$.
