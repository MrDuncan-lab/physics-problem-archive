---
id: nbpho-2024-intl-theory-2
olympiad: NbPhO
year: 2024
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "2"
title: "Oklo fission reactor"
points: 7
authors: ["Topi Löytäinen", "Jaan Kalda"]
aliases: ["Oklo fission reactor"]
topics: ["[[2.1 Уравнение теплового баланса. 8-ой класс]]", "[[2.10 Насыщенный пар]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: true
source_damaged: false
summary: "Оценить содержание урана, мощность и расход воды природного ядерного реактора Окло."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 2. Oklo fission reactor (7 points) — Topi Löytäinen, Jaan Kalda.

**NbPhO 2024** · Международная олимпиада · теория · 10–12 класс · задача 2  
Источник: [[_pdf/NbPhO/nbpho-2024.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2024.pdf#page=4|решение, стр. 4]]

Темы: [[2.1 Уравнение теплового баланса. 8-ой класс]], [[2.10 Насыщенный пар]]

> [!abstract] Кратко (составлено моделью)
> Оценить содержание урана, мощность и расход воды природного ядерного реактора Окло.

Based on the ratio of the uranium isotopes $^{235}\mathrm{U}$ and $^{238}\mathrm{U}$, as well as the abundances of the isotopes produced by nuclear reactors, researchers have established that self-sustaining natural nuclear reactors operated in Oklo ca $T_0 = 1.8 \times 10^9$ years ago in Gabon, central Africa. For such reactors to exist, two conditions must be met: (a) presence of deposits with high enough concentration of uranium; (b) sufficiently high abundance of $^{235}\mathrm{U}$ in natural uranium. Rich uranium ores were created by floods: scattered uranium was dissolved in oxygen-rich water and transported by it to underground pools. Significant concentration of oxygen appeared in the atmosphere only around 2.5 billion years ago, so the first condition was not met earlier than that. You will learn below that the abundance of $^{235}\mathrm{U}$ decreases relatively fast in time, so the second condition ceased to be satisfied soon after the operation of Oklo’s reactor.

What made the operation of Oklo’s reactor possible was a stable influx of ground water that kept the uranium deposits sufficiently wet. Water is the so-called moderator for the fission reactor: it slows down neutrons emerging from fission reactions, dramatically enhancing the chances of a neutron triggering the fission of a next $^{235}\mathrm{U}$ nucleus.

In what follows, in addition to $T_0$, you can use the following numerical values.

Energy released by the fission of a single $^{235}\mathrm{U}$ nucleus: $E_0 = 200\,\mathrm{MeV}$.

Half-life of $^{235}\mathrm{U}$: $\tau_5 \approx 7 \times 10^8$ years.

Half-life of $^{238}\mathrm{U}$: $\tau_8 \approx 4.5 \times 10^9$ years.

Latent heat of evaporation of water: $L = 2260\,\mathrm{kJ\,kg^{-1}}$.

Specific heat of water $c = 4200\,\mathrm{J\,kg^{-1}\,K^{-1}}$.

Abundance of $^{235}\mathrm{U}$ in natural uranium today: $R = 0.72\%$. We define abundance as the number of atoms of the isotope, normalized to the number of atoms of the given element.

Average abundance of $^{235}\mathrm{U}$ in the uranium from Oklo’s uranium ore today: $R_O = 0.62\%$.

The total amount of uranium in Oklo’s mine today: $M = 5 \times 10^8\,\mathrm{kg}$.

The duration of the time period over which Oklo’s reactor operated: $T \approx 1 \times 10^5$ year.

Elementary charge: $e = 1.6 \times 10^{-19}\,\mathrm{C}$.

Atomic mass unit: $u = 1.66 \times 10^{-27}\,\mathrm{kg}$.

Avogadro’s number: $N_A = 6.02 \times 10^{23}\,\mathrm{mol^{-1}}$.

Note that: (a) the abundance of other isotopes of uranium besides $^{235}\mathrm{U}$ and $^{238}\mathrm{U}$ is negligibly small; (b) $^{235}\mathrm{U}$ is not among the decay products of $^{238}\mathrm{U}$; and (c) fission channels other than the fission of $^{235}\mathrm{U}$ (e.g., synthesis and fission of plutonium) can be neglected.

**i)** (1.5 points) What was the abundance of $^{235}\mathrm{U}$ in natural uranium when the Oklo’s reactor operated?

**ii)** (2 points) What was the average power of the Oklo’s reactor?

**iii)** (1.5 points) Qualitatively explain why was Oklo’s reactor operating in a stable regime and did not blow up. Water inflow rate varied over time; what happened to the reactor when the water inflow rate increased two times?

**iv)** (2 points) Estimate the total mass of water that flowed into the Oklo’s reactor during its operation period.

> [!answer]- Ответ
> **i**
>
> $$
> R_1\approx\frac{\frac{\nu_5}{\nu_8}2^{T_0/\tau_5}}{\frac{\nu_5}{\nu_8}2^{T_0/\tau_5}+2^{T_0/\tau_8}}\approx3.16\%,
> $$
>
> **ii** — $\nu E_0/T\approx7.73\times10^7\,\mathrm W$.
>
> **iv** — $\nu E_0/E_w=9.09\times10^{13}\,\mathrm{kg}$.

> [!solution]- Решение
> # 2. Oklo fission reactor (7 points) — Solution by Tudor Plopeanu, Jaan Kalda and Topi Löytäinen.
>
> **i)** (1.5 points) The rate of natural decay is proportional to the amount of decaying material. If $\nu$ is the amount of $^{235}\mathrm U$ at some point in time, then $\frac{d\nu}{dt}=-k\nu$ for some positive constant $k$. Then, $\frac{\nu_b}{\nu_a}=e^{-k(t_b-t_a)}$ for some moments $t_b>t_a$. The half-time is defined as the time until the amount of material is halved, so $k\tau_5=\ln2$, $k=\frac{\ln2}{\tau_5}$, $\frac{\nu_b}{\nu_a}=(e^{\ln2})^{\frac{t_b-t_a}{\tau_5}}=2^{\frac{t_b-t_a}{\tau_5}}$. Therefore, the amount of $^{235}\mathrm U$ in natural uranium when the Oklo’s reactor operated was $2^{T_0/\tau_5}$ times higher. Similarly, the amount of $^{238}\mathrm U$ was $2^{T_0/\tau_8}$ higher. The natural abundance of $^{235}\mathrm U$ $T_0$ years ago was
>
> $$R_1\approx\frac{\frac{\nu_5}{\nu_8}2^{T_0/\tau_5}}{\frac{\nu_5}{\nu_8}2^{T_0/\tau_5}+2^{T_0/\tau_8}}\approx3.16\%,$$
>
> where $\nu_5$ and $\nu_8$ represent the number of isotopes of uranium. Keep in mind that $R=\nu_5/(\nu_5+\nu_8)$, so $\nu_5/\nu_8=R/(1-R)$.
>
> **ii)** (2 points) From here on we shall assume that before the Oklo reactor started operating, its abundance of uranium isotopes matched the natural abundance. After it finished operating, the $^{235}\mathrm U$ isotopes kept decaying at the normal rate, reaching the value we see today.
>
> The mass of $^{235}\mathrm U$ after the reactor finished operating was $M_1\approx2^{T_0/\tau_5}MR_O\approx1.84\times10^7\,\mathrm{kg}$.
>
> The $^{238}\mathrm U$ isotopes underwent normal decay, and we shall use them to compute the mass of $^{235}\mathrm U$ before the reactor started. The mass of $^{238}\mathrm U$ was approximately $M(1-R)2^{T_0/\tau_8}$. The mass of $^{235}\mathrm U$ before the reactor operated can, as such, be estimated as
>
> $$M_0=\frac{R_1}{1-R_1}M(1-R)2^{T_0/\tau_8}\approx2.14\times10^7\,\mathrm{kg}.$$
>
> The number of $^{235}\mathrm U$ nuclei which reacted is $\nu=[(M_0-M_1)/0.235]\cdot N_A\approx7.61\times10^{30}$. The amount of energy generated through fission is the above value multiplied by $E_0$. The average power of the reactor is
>
> $\nu E_0/T\approx7.73\times10^7\,\mathrm W$.
>
> **iii)** (1.5 points) Neutrons released from fission tend to have a high kinetic energy which have a low probability to cause further fissions. We need to slow them down to increase this probability. Water is relatively good for slowing down neutrons. This slowing down is called ”moderation”. The reactor could not explode since the water necessary for moderation would vapourize if the power increased too much. This would prevent an uncontrolled chain reactor from happening. The reactor’s power depends on water being present and thus the operation was self-regulating.
>
> When the water intake doubled, the amount of power doubled.
>
> **iv)** (2 points) The amount of energy generated by the reactor was $\nu E_0$. We shall consider the vast majority of it to have gone into heating up and vaporizing water. Let us consider water flowing in at $0^\circ C$ and leaving at $100^\circ C$. Then, the amount of energy absorbed by $1\,\mathrm{kg}$ of water is $(100^\circ K)c+L=E_w=2.68\times10^6\,\mathrm J$. The total mass of water that flowed into Oklo’s reactor is
>
> $\nu E_0/E_w=9.09\times10^{13}\,\mathrm{kg}$.

> [!grading]- Критерии оценивания
> Grading: (preliminary)
>
> | Criterion | Points |
> |---|---|
> | Amount of $^{238}\mathrm U$ during operation $\nu'_8=\nu_8 2^{T_0/\tau_8}$. | 0.3 pts |
> | Amount of $^{235}\mathrm U$ during operation $\nu'_5=\nu_5 2^{T_0/\tau_5}$. | 0.3 pts |
> | Abundance of $^{235}\mathrm U$ during operation expressed in terms of $\nu_5$ and $\nu_8$. | 0.3 pts |
> | Ratio $\nu_5/\nu_8$ expressed in terms of $R$. | 0.3 pts |
> | Abundance of $^{235}\mathrm U$ expressed in terms of $R$ and numerical answer. | 0.3 pts |
>
> **ii)**
>
> Grading: (preliminary)
>
> | Criterion | Points |
> |---|---|
> | Mass of $^{235}\mathrm U$ by the end of operation $M'_5=2^{T_0/\tau_5}MR_0$. | 0.4 pts |
> | Mass of $^{238}\mathrm U$ by the end of operation $M'_8=2^{T_0/\tau_8}M(1-R)$. | 0.3 pts |
> | Mass of $^{235}\mathrm U$ at the beginning of operation $2^{T_0/\tau_8}M(1-R)\frac{R'}{1-R'}$. | 0.3 pts |
> | Number of atoms that have undergone fission $N=N_A\Delta M/0.235$. | 0.3 pts |
> | Energy $E=NE_0$. | 0.2 pts |
> | Units converted correctly. | 0.2 pts |
> | Power: expression and numerical value. | 0.3 pts |
>
> **iii)**
>
> Grading: (preliminary)
>
> | Criterion | Points |
> |---|---|
> | Idea that neutrons from fission unlikely to cause fission unless moderated: | 0.3 pts |
> | Idea of water as a moderator: | 0.2 pts |
> | Idea of self-regulating behavior: | 0.5 pts |
> | Observation that power doubles when flow doubles: | 0.5 pts |
>
> **iv)**
>
> Grading: (preliminary)
>
> | Criterion | Points |
> |---|---|
> | Approximation that all energy went into water | 0.5 p |
> | $\Delta T\approx100$ | 0.3 p |
> | Both heating and vaporization considered | 0.3 p |
> | $E_w=2.68\times10^6\,\mathrm J$ or similar idea | 0.3 p |
> | $\nu E_0/E_w=9.09\times10^{13}\,\mathrm{kg}$ | 0.6 p |
