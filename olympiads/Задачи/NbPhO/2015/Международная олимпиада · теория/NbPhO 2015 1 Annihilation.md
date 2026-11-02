---
id: nbpho-2015-intl-theory-1
olympiad: NbPhO
year: 2015
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "1"
title: "Annihilation"
points: 6
aliases: ["Annihilation"]
topics: ["[[1.17 Законы сохранения энергии и импульса]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Рассчитать энергию, импульс и направления фотонов при аннигиляции электрона и позитрона."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 1. ANNIHILATION (6 points)

**NbPhO 2015** · Международная олимпиада · теория · 10–12 класс · задача 1  
Источник: [[_pdf/NbPhO/nbpho-2015.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2015.pdf#page=6|решение, стр. 6]]

Темы: [[1.17 Законы сохранения энергии и импульса]]

> [!abstract] Кратко (составлено моделью)
> Рассчитать энергию, импульс и направления фотонов при аннигиляции электрона и позитрона.

*(by L. Franti)*

An electron with kinetic energy $1\mathrm{MeV}$ travels along the $z$-axis and collides with a positron at rest. The particles annihilate producing a pair of two photons A and B with equal energies.

**i)** (1.5 points) Find the speed of the electron $v_e$ in the lab frame.

**ii)** (0.5 points) Find the energy $E_\gamma$ of photon A in the lab frame.

**iii)** (1 point) Find the momentum $p_\gamma$ of photon A in the lab frame.

**iv)** (2 points) Find the angle $\alpha$ between the $z$-axis and the momentum of photon A in the lab frame.

**v)** (1 point) Why is it not possible for a collision process to produce just one single photon?

The rest mass of electron $m_e=511\mathrm{keV}/c^2$. You can express your results in electron volts and related units.

> [!answer]- Ответ
> **i** — $v_e\approx 0.941c$.
>
> **ii** — $E_\gamma=\frac12(T+2m_ec^2)\approx 1.01\mathrm{MeV}$.
>
> **iii** — $p_\gamma=E_\gamma/c=1.01\mathrm{MeV}/c$.
>
> **iv** — $\alpha=\arccos\frac{p_e}{2p_\gamma}=\arccos\frac1{\sqrt{1+2m_ec^2/T}}=\arctan\sqrt{\frac{2m_ec^2}{T}}\approx45.3^\circ$.

> [!solution]- Решение
> # 1. ANNIHILATION
>
> **i)** Electron’s total energy $E=\gamma m_ec^2\implies\gamma=\frac{E}{m_ec^2}$, where $E=T+m_ec^2$ (here, $T=1\mathrm{MeV}$ is the given kinetic energy). Now, $\gamma=1/\sqrt{1-v_e^2/c^2}\implies v_e=c\sqrt{1-1/\gamma^2}=c\sqrt{1-m_e^2c^4/E^2}=\frac{c\sqrt{T^2+2Tm_ec^2}}{T+m_ec^2}$. Numerically,
> $v_e\approx 0.941c$.
>
> **ii)** The photons fly away symmetrically with respect to the electron’s trajectory: in the zero-total-momentum frame, momentum conservation implies that the photons have equal momenta and, thus, equal energies, and fly in exactly opposite directions; their energies can be equal also in the positron’s frame only if they are flying totally symmetrically. Each photon gets a half of the total energy in the system:
> $E_\gamma=\frac12(T+2m_ec^2)\approx 1.01\mathrm{MeV}$.
>
> **iii)** $E_\gamma=p_\gamma c\implies$
> $p_\gamma=E_\gamma/c=1.01\mathrm{MeV}/c$.
>
> **iv)** From $E=p_e^2c^2+m_e^2c^4$, the electron’s momentum is $p_e=\sqrt{\frac{E^2}{c^2}-m_e^2c^2}=\frac1c\sqrt{T^2+2Tm_ec^2}$. (Equivalent result can be derived from $p_e=\gamma m_ev_e$.) Momentum conservation in the $z$-direction then implies that $p_e=2p_\gamma\cos\alpha\implies$
> $\alpha=\arccos\frac{p_e}{2p_\gamma}=\arccos\frac1{\sqrt{1+2m_ec^2/T}}=\arctan\sqrt{\frac{2m_ec^2}{T}}\approx45.3^\circ$.
>
> **v)** In the center-of-mass frame, the total momentum of any system is zero. This means that if the outcome of a collision is only a single particle, then the particle’s momentum must be zero in the center-of-mass frame. However, a photon’s momentum can never be zero, because otherwise it would have zero energy and an infinite wavelength.
