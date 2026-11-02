---
id: nbpho-2011-intl-theory-5
olympiad: NbPhO
year: 2011
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "5"
title: "Plutonium decay"
points: 3
aliases: ["Plutonium decay"]
topics: ["[[2.12 Молекулярно-кинетическая теория]]"]
difficulty: 3
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Определить плотность потока альфа-частиц у поверхности пластины плутония по периоду полураспада."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 5. Plutonium decay (3 points)

**NbPhO 2011** · Международная олимпиада · теория · 10–12 класс · задача 5  
Источник: [[_pdf/NbPhO/nbpho-2011.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2011.pdf#page=4|решение, стр. 4]]

Темы: [[2.12 Молекулярно-кинетическая теория]]

> [!abstract] Кратко (составлено моделью)
> Определить плотность потока альфа-частиц у поверхности пластины плутония по периоду полураспада.

Plutonium is an unstable element, a $\mathrm{Pu}^{239}$ atom decays with a half-life of $\tau_{1/2}=24000$ years by creating smaller nuclei, including an $\alpha$-particle. Find the $\alpha$-particle flux density (i.e the number of passing nuclei per unit time and per unit cross-sectional area) near the surface of a plate of $\mathrm{Pu}^{239}$. The plate has thickness $d=1\mathrm{mm}$; its width and length are much larger than that. The density of plutonium $\rho=19800\mathrm{kg/m^3}$. *Remark:* half-life is the period of time it takes for a substance undergoing decay to decrease in size (in the number of particles) by half. The mass of an atom of $\mathrm{Pu}^{239}$ is $m_0=3.84\times10^{-25}\mathrm{kg}$.

> [!answer]- Ответ
> $$
> \Phi=\frac{\rho d\ln2}{2\tau_{1/2}m_0}\approx2.36\times10^{13}\,\mathrm{m}^{-2}\cdot\mathrm{s}^{-1}.
> $$

> [!solution]- Решение
> # 5. Plutonium decay (3 points)
>
> Let the number of $\mathrm{Pu}^{239}$-atoms be reduced during time interval $t=1\,\mathrm{s}$ by a factor of $1-\lambda$ (with $\lambda\ll1$). Then, during the time period of $\tau_{1/2}$, it is reduced by a factor of $(1-\lambda)^{\tau_{1/2}/t}\approx e^{-\lambda\tau_{1/2}/t}=\frac12\Rightarrow\lambda=t\ln2/\tau_{1/2}$. Therefore, the number of atom decay events is $N_d=Nt\ln2/\tau_{1/2}$, where $N=\rho dS/m_0$ is the number of atoms, i.e. the $\alpha$-particle flux is $\Phi=N_d/2St$ (where the factor 2 accounts for the fact that the particles are emitted towards the both sides of the plate). Upon bringing all the expressions together, we obtain
>
> $$\Phi=\frac{\rho d\ln2}{2\tau_{1/2}m_0}\approx2.36\times10^{13}\,\mathrm{m}^{-2}\cdot\mathrm{s}^{-1}.$$
