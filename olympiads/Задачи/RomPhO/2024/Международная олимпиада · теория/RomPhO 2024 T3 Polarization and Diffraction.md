---
id: rompho-2024-intl-theory-t3
olympiad: RomPhO
year: 2024
stage: "Международная олимпиада"
round: теория
grade: ""
number: "T3"
title: "Polarization and Diffraction"
points: 10
aliases: ["Polarization and Diffraction"]
topics: ["[[6.5 Волновая оптика]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Определить интенсивность и поляризацию света после поляроидов и интенсивность дифрагировавшего света для различных сочетаний прозрачных областей, поляроидов и полуволновых пластинок."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# Q3. Polarization and Diffraction (10 points)

**RomPhO 2024** · Международная олимпиада · теория · задача T3  
Источник: [[_pdf/RomPhO/RomPhO-2024-T3.pdf#page=1|условие, стр. 1–2]] · [[_pdf/RomPhO/RomPhO-2024-T3-solution.pdf#page=3|решение, стр. 3]]

Темы: [[6.5 Волновая оптика]]

> [!abstract] Кратко (составлено моделью)
> Определить интенсивность и поляризацию света после поляроидов и интенсивность дифрагировавшего света для различных сочетаний прозрачных областей, поляроидов и полуволновых пластинок.

**A.** A beam of natural (unpolarized) light, with an intensity $I_o$, passes through two identical polaroids, placed one after the other one.

**a.** If the polaroids are ideal and the angle between their transmission axes is $\theta=60^\circ$, calculate the intensity of the emergent beam. **1 p** **b.** If the two polaroids are non-ideal and the transmission axis of one is rotated with respect to the other, the ratio of the maximum emergent intensity to the minimum emergent intensity is $I_{\max}/I_{\min}=n$. Calculate the degree of polarization of the light passing through the two polaroids when their transmission axes are parallel. **2 p**

**B.** A diffraction aperture is formed by two semi-infinite planes, $Z_1$ and $Z_2$, that have different optical properties. A parallel, coherent beam of monochromatic light falls at normal incidence on this aperture. If the intensity of this beam is $I_o$, calculate the intensity at point P on the screen (see figure 1) for the following configurations.

![[rompho-2024-t3-problems-p1-f2.png]]
*Figure 1*

The beam is unpolrazied for the following:

**c.** $Z_1$ transparent, $Z_2$ opaque; **1 p** **d.** $Z_1$ ideal polaroid, $Z_2$ opaque; **1 p**

**e.** $Z_1$, $Z_2$ ideal polaroids with transmission axis with mutually perpendicular axes; **1 p** **f.** $Z_1$ transparent, $Z_2$ ideal polaroid; **1 p**

**g.** $Z_1$, $Z_2$ non-ideal polaroids with transmission axis with mutually perpendicular axes (The polaroids are identical and have the amplitude transmission coefficients: 1. parallel to the transmission axis, $\alpha_{\parallel}=0.9$; and 2. perpendicular to the transmission axis, $\alpha_{\perp}=0.1$. **1 p**

**C.** A retarder plate is an optical device used to alter the polarization state of light beams. These plates are typically made from anisotropic materials such as calcite or quartz crystals, which possess an axis of high symmetry called the optic axis. When an incoming light wave enters the retarder plate, it splits into two waves at the entrance: the o-wave (ordinary), with the electric field perpendicular to the optic axis, and the e-wave (extraordinary), with the electric field parallel to the optic axis. Due to their different refractive indices, the plate introduces a phase difference between these waves. If the phase difference is $\pi$ (or an odd multiple of $\pi$), the plate functions as a half-wave plate. When a linearly polarized wave enters a half-wave plate, the emerging wave becomes linearly polarized symmetrically about the optic axis of the plate (crystal axis). See Figure 2 for a visual representation.

![[rompho-2024-t3-problems-p2-f1.png]]
*Figure 2*

The beam is polarized for the following:

**h.** $Z_1$ transparent, $Z_2$ half-wave plate, the angle between the polarization direction and optical axis of half-waveplate is $\theta=30^\circ$; **1 p** **i.** $Z_1$ half-wave plate, $Z_2$ half-wave plate, the optical axes of the two half-waveplates perpendicular to each other. **1 p**

**Note:** Any optical path difference due to the optical thickness of the two adjacent areas can be neglected (it is considered that they are compensated in the device).

Lecturer Marian Cornel BAZAVAN, PhD  
University of Bucharest  
Faculty of Physics

> [!answer]- Ответ
> **a** — $I=(I_o/2)\cos^2\theta=I_o/8$ — 0.5 pt
>
> **b**
>
> $$
> P_{\parallel}=\frac{T_{\parallel}^2-T_{\perp}^2}{T_{\parallel}^2+T_{\perp}^2}=\frac{T_{\parallel}-T_{\perp}}{T_{\parallel}+T_{\perp}}\frac{(T_{\parallel}+T_{\perp})^2}{T_{\parallel}^2+T_{\perp}^2}=\frac{T_{\parallel}-T_{\perp}}{T_{\parallel}+T_{\perp}}\left(1+\frac{2T_{\parallel}T_{\perp}}{T_{\parallel}^2+T_{\perp}^2}\right)=\frac{\sqrt{n^2-1}}{n}\qquad 0.5\text{ pt}
> $$
>
> **d** — $I(P)=E(P)E^*(P)=I_o/4$ — 0.5 pt
>
> **e** — $I(P)=E(P)E^*(P)=I_o/8$ — 0.5 pt
>
> **f** — $I(P)=E_{\parallel}(P)E_{\parallel}^*(P)+E_{\perp}(P)E_{\perp}^*(P)=I_o/8+I_o/8=I_o/4$ — 0.5 pt
>
> **g** — $I(P)=E_{\parallel}(P)E_{\parallel}^*(P)+E_{\perp}(P)E_{\perp}^*(P)=I_o/2+I_o/8=5I_o/8$ — 0.5 pt
>
> **h** — $I(P)=E_{\parallel}(P)E_{\parallel}^*(P)+E_{\perp}(P)E_{\perp}^*(P)=(\alpha_{\parallel}+\alpha_{\perp})^2I_o/4=I_o/4$ — 0.5 pt
>
> **i**
>
> $$
> I(P)=\left(\frac{E_o}{2}\right)^2+\left(\frac{E_o}{2}\right)^2+2\frac{E_o}{2}\frac{E_o}{2}\cos2\theta=\frac{3E_o^2}{4}=\frac{3I_o}{4}\qquad 0.5\text{ pt}
> $$
>
> **j** — $I(P)=0$. — 0.5 pt

> [!solution]- Решение
> Q3
>
> **a.** $I=I_{inc}\cos^2\theta$ (Malus law) — 0.5 pt
>
> $I=(I_o/2)\cos^2\theta=I_o/8$ — 0.5 pt **b.** Let $T_{\parallel}$ and $T_{\perp}$ represent the energetic transmission coefficients of the polaroids parallel and perpendicular, respectively, to the transmission axis.
>
> Paralel polaroids $I_{\max}=(T_{\parallel}^2+T_{\perp}^2)I_o/2$ — 0.5 pt
>
> Perpendicular polaroids $I_{\min}=2T_{\parallel}T_{\perp}I_o/2$ — 0.5 pt
>
> $$
> n=\frac{I_{max}}{I_{min}}=\frac{T_{\parallel}^2+T_{\perp}^2}{2T_{\parallel}T_{\perp}}
> $$
>
> The degree of polarization after a single polaroid:
>
> $$
> P=\frac{T_{\parallel}-T_{\perp}}{T_{\parallel}+T_{\perp}}=\sqrt{\left(\frac{T_{\parallel}-T_{\perp}}{T_{\parallel}+T_{\perp}}\right)^2}=\sqrt{\frac{n-1}{n+1}} \qquad 0.5\text{ pt}
> $$
>
> The degree of polarization after two paralel polaroids:
>
> $$
> P_{\parallel}=\frac{T_{\parallel}^2-T_{\perp}^2}{T_{\parallel}^2+T_{\perp}^2}=\frac{T_{\parallel}-T_{\perp}}{T_{\parallel}+T_{\perp}}\frac{(T_{\parallel}+T_{\perp})^2}{T_{\parallel}^2+T_{\perp}^2}=\frac{T_{\parallel}-T_{\perp}}{T_{\parallel}+T_{\perp}}\left(1+\frac{2T_{\parallel}T_{\perp}}{T_{\parallel}^2+T_{\perp}^2}\right)=\frac{\sqrt{n^2-1}}{n}\qquad 0.5\text{ pt}
> $$
>
> **c.** $E(P)=E_o/2$ — 0.5 pt
>
> **d.** $I(P)=E(P)E^*(P)=I_o/4$ — 0.5 pt **e.** $E(P)=\frac12\frac{E_o}{\sqrt2}$ — 0.5 pt
>
> $I(P)=E(P)E^*(P)=I_o/8$ — 0.5 pt **f.** $E_{\parallel}(P)=\frac12\frac{E_o}{\sqrt2};\ E_{\perp}(P)=\frac12\frac{E_o}{\sqrt2}$ — 0.5 pt
>
> $I(P)=E_{\parallel}(P)E_{\parallel}^*(P)+E_{\perp}(P)E_{\perp}^*(P)=I_o/8+I_o/8=I_o/4$ — 0.5 pt **g.** $E_{\parallel}(P)=\frac{E_o}{\sqrt2};\ E_{\perp}(P)=\frac12\frac{E_o}{\sqrt2}$ — 0.5 pt
>
> $I(P)=E_{\parallel}(P)E_{\parallel}^*(P)+E_{\perp}(P)E_{\perp}^*(P)=I_o/2+I_o/8=5I_o/8$ — 0.5 pt **h.** $E_{\parallel}(P)=\frac12\alpha_{\parallel}\frac{E_o}{\sqrt2}+\frac12\alpha_{\perp}\frac{E_o}{\sqrt2};\ E_{\perp}(P)=\frac12\alpha_{\parallel}\frac{E_o}{\sqrt2}+\frac12\alpha_{\perp}\frac{E_o}{\sqrt2}$ — 0.5 pt
>
> $I(P)=E_{\parallel}(P)E_{\parallel}^*(P)+E_{\perp}(P)E_{\perp}^*(P)=(\alpha_{\parallel}+\alpha_{\perp})^2I_o/4=I_o/4$ — 0.5 pt **i.** After the linearly polarized light goes through the half-wave plate, the light is still linearly polarised in a direction symmetrical to the optical axis of the half-wave plate. The contributions of the two areas will be in phase, but the angle between the two polarization directions at P will be $2\theta$: — 0.5 pt
>
> $$
> I(P)=\left(\frac{E_o}{2}\right)^2+\left(\frac{E_o}{2}\right)^2+2\frac{E_o}{2}\frac{E_o}{2}\cos2\theta=\frac{3E_o^2}{4}=\frac{3I_o}{4}\qquad 0.5\text{ pt}
> $$
>
> **j.** After the light goes through the two areas we have two beams that will be “out of phase”. (the angle between the two components at P will be $180^\circ$): — 0.5 pt
>
> $I(P)=0$. — 0.5 pt
