---
id: nbpho-2014-intl-theory-e1
olympiad: NbPhO
year: 2014
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "E1"
title: "Planck’s constant"
points: 8
aliases: ["Planck’s constant"]
topics: ["[[7 Эксперименты]]", "[[5.5 Нелинейные элементы в электрических цепях]]", "[[6.5 Волновая оптика]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "По измерениям светодиодов определить длины волн и постоянную Планка с погрешностью."
status: "проверено: сверка, два чтения + арбитр"
lang: en
tags: [задача]
---

# 5. PLANCK’S CONSTANT (8 points)

**NbPhO 2014** · Международная олимпиада · теория · 10–12 класс · задача E1  
Источник: [[_pdf/NbPhO/nbpho-2014.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2014.pdf#page=3|решение, стр. 3–4]]

Темы: [[7 Эксперименты]], [[5.5 Нелинейные элементы в электрических цепях]], [[6.5 Волновая оптика]]

> [!abstract] Кратко (составлено моделью)
> По измерениям светодиодов определить длины волн и постоянную Планка с погрешностью.

In a simplistic model, light emitting diodes can be considered to only pass current when lit, and then they have a constant voltage drop $V_t=\frac{E}{e}$ across them. $E=hf$ is the energy of the light quanta emitted and $e=1.60\times10^{-19}\,\mathrm{C}$ is the elementary charge. Speed of light in vacuum $c=3.00\times10^8\,\mathrm{m/s}$.

You have a assorted light emitting diodes numbered 1–6, each with a $R=680\,\Omega$ series resistor. From the datasheets it is known for the peak wavelengths of the diodes to be 940 nm, 620 nm, 590 nm, 525 nm, 470 nm, and 450 nm.

**i)** (2 points) Find out which wavelength corresponds to which diode.

**ii)** (4 points) Measure the Planck’s constant $h$ that corresponds to our simplistic model. This does not have to correspond to real Planck’s constant.

**iii)** (2 points) Estimate the uncertainty.

*Equipment:* voltage source (batteries) with an unknown voltage, ammeter, assorted light emitting diodes with series resistor. Take care not to short the battery with the ammeter. You may ignore the internal resistances of the batteries and the ammeter.

> [!answer]- Ответ
> **E1.2** — $h=eA/c$.
>
> **E1.3** — $\Delta h=h\Delta A/A$.

> [!solution]- Решение
> # 5. Planck’s constant
>
> **1)** When we connect each of the diodes to the battery, we can observe the light of the emitted light; the mapping is as follows: 940 nm — invisible (infrared), 620 nm — red, 590 nm — orange, 525 nm — green; 470 nm — blue; 450 nm — violet.
>
> **2)** We can measure the current $I$ through the diode (which is also the current through the resistor $R$), so that the voltage on the diode would be $V_d=\mathcal E-IR$, but we don’t know the battery voltage. However, we do know that the diode’s voltage equals approximately to the photon’s energy $E_p$ expressed in electron volts, $E_p=hc/(\lambda e)$. Since we expect that $IR=\mathcal E-V_d$, if we plot $IR$ versus $1/\lambda$, we should obtain a straight line
>
> $$IR=\mathcal E-\frac{1}{\lambda}\frac{hc}{e}.$$
>
> We can measure the slope of the straight line $A=hc/e$, which allows us to calculate
> $h=eA/c$.
>
> **3)** The major source of the uncertainty is not the instrument uncertainties, but the departure of the real diode data from the simplistic model. Therefore we can try to fit the data points with different straight lines making the slope $A$ as steep as possible (while still keeping a reasonable fit with the data points, and also as flat as possible; the uncertainty of $A$ is found as $\Delta A=\frac12(A_\mathrm{max}-A_\mathrm{min})$, and
> $\Delta h=h\Delta A/A$.
