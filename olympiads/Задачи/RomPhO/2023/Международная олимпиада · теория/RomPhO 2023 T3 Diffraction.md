---
id: rompho-2023-intl-theory-t3
olympiad: RomPhO
year: 2023
stage: "Международная олимпиада"
round: теория
grade: ""
number: "T3"
title: "Diffraction"
aliases: ["Diffraction"]
topics: ["[[6.5 Волновая оптика]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Исследовать интенсивность дифракции щелей и решёток, а также спектральную ширину, длину когерентности и разрешение монохроматора."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# Problem 3: Diffraction

**RomPhO 2023** · Международная олимпиада · теория · задача T3  
Источник: [[_pdf/RomPhO/RomPhO-2023-T3.pdf#page=1|условие, стр. 1]] · [[_pdf/RomPhO/RomPhO-2023-T3-solutions.pdf#page=2|решение, стр. 2–3]]

Темы: [[6.5 Волновая оптика]]

> [!abstract] Кратко (составлено моделью)
> Исследовать интенсивность дифракции щелей и решёток, а также спектральную ширину, длину когерентности и разрешение монохроматора.

**a.** Determine the ratio between the intensities of the central maxima in the diffraction patterns for two slits of width $a$ and $b$ respectively if they are illuminated with the same beam of coherent monochromatic light. **1 point**

Consider a diffraction grating made up of a sequence of identical equidistant slits.

**b.** What relationship exists between the intensities of the main maxima of the 1st order obtained with the help of two complementary diffraction gratings (both having the same constant $l$, the distance between the center of one slit and the center of the adjacent slit), and slit widths $a$ and respectively $l-a$)? It is considered that the diffraction gratings are illuminated with the same beam of coherent monochromatic light. **1 point** **c.** Prove that in the case of a diffraction grating made up of a sequence of identical and equidistant slits, the intensity of the diffracted light, $I_{dif}$, is not more than a quarter of the intensity of the light incident on the grating. What is the condition for $I_{dif}=I_{inc}/4$, such that the brightness of the grating is maximized? (where $I_{dif}$ is the intensity of the diffracted light in all maxima, except the maximum of order zero). **2.5 points**

The gratings with a better brightness, i.e. $I_{dif}>I_{inc}/4$, are the blazed (reflection) gratings, in which the plane of the individual grooves makes an angle $\alpha$ with the grating plane $P_1P_2$. (see figure).

![[rompho-2023-t3-problems-p1-f1.png]]

**d.** Determine this angle for a grating with $n=2000$ grooves/mm which forms the 1st order maximum in the direction of the incident beam for the wavelength $\lambda_0=500$ nm and this maximum is the brightest from the diffraction pattern. **1 point**

The grating from (d) is used in a monochromator in which the diffraction spectrum is projected onto the exit slit with a concave mirror having the radius of curvature $R=1$ m.

**e.** Determine the spectral width $\Delta\lambda$ and the coherence length of the beam that comes out of the monochromator if it is illuminated with white light, the slit has the width $d=20$ μm, and the central wavelength is $\lambda_0=500$ nm. Calculate their numerical values. **3 points** **f.** What is the minimum spectral range between two monochromatic radiations that can still be resolved using the grating from (d). The grating is 10 cm long and the spectrum is projected with the mirror from point (e). onto a CCD detector having 200 pixels/mm. **1.5 points**

*Note.* The normal incidence on the slits and gratings is considered only for a., b., c. Diffraction in parallel light is considered.

Problem proposed by  
Dr. Marian Băzăvan, Faculty of Physics, University of Bucharest, Romania

> [!answer]- Ответ
> **a**
>
> $$
> \frac{I_{0a}}{I_{0b}}=\frac{a^2}{b^2}\qquad (0.4\text{pt})
> $$
>
> **b**
>
> $$
> I_{a(1)}=E_{a(1)}E_{a(1)}^*=E_{l-a(1)}E_{l-a(1)}^*=I_{l-a(1)}\qquad (0.3\text{pt})
> $$
>
> **c** — The maximum occurs for $a=l/2$ which leads to $I_{dif\ max}=1/4*I_{incident}$. (0.2+0.3pt)
>
> **d** — $\alpha=30^\circ$. (0.2pt)
>
> **e** — $\Delta\lambda=0.17$ Å. (0.2pt)
>
> **e** — $L_c=1.5$ cm (0.2pt)
>
> **f** — Therefore, the minimum spectral range resolved by the spectrometer is 0.043 Å. (0.3pt)

> [!solution]- Решение
> **Solution:**
>
> **a.** The distribution of the electric field intensity, depending on the diffraction angle $\theta$, is given by the relation (Fraunhofer type diffraction):
>
> $$
> E(\theta)=\int_0^a Ce^{i(\omega t-kx\sin\theta)}dx \qquad (0.2\text{pt})
> $$
>
> where $k$ is the modulus of the wave vector. The light intensity distribution is in this case:
>
> $$
> I(\theta)=E(\theta)E^*(\theta)=CC^*a^2\left[\frac{\sin(ka\sin\theta/2)}{ka\sin\theta/2}\right]^2 \qquad (0.4\text{pt})
> $$
>
> which results in:
>
> $$
> \frac{I_{0a}}{I_{0b}}=\frac{a^2}{b^2}\qquad (0.4\text{pt})
> $$
>
> **b.** The diffraction patterns, given as the electric field, for the two gratings are:
>
> $$
> E_a(\theta)=\sum_m\int_{ml}^{ml+a}Ce^{i(\omega t-kx\sin\theta)}dx
> $$
>
> and
>
> $$
> E_{l-a}(\theta)=\sum_m\int_{ml+a}^{ml+l}Ce^{i(\omega t-kx\sin\theta)}dx\qquad (0.2\text{pt})
> $$
>
> respectively. Adding the two field distributions, we get the field distribution as if there was no aperture:
>
> $$
> E_a(\theta)+E_{l-a}(\theta)=E_{incident}(\theta)=\begin{cases}0&\text{geometric shadow}\\E_o&\text{incident direction}\end{cases}\qquad (0.2\text{pt})
> $$
>
> The main maxima of the 1st order are formed in the geometric shadow and therefore:
>
> $$
> E_{a(1)}+E_{l-a(1)}=0\quad\Rightarrow\quad E_{a(1)}=-E_{l-a(1)}\qquad (0.3\text{pt})
> $$
>
> and
>
> $$
> I_{a(1)}=E_{a(1)}E_{a(1)}^*=E_{l-a(1)}E_{l-a(1)}^*=I_{l-a(1)}\qquad (0.3\text{pt})
> $$
>
> The two gratings with slits of width $a$ and $l-a$ will have $I_{dif\ a}=I_{dif\ l-a}$ and therefore the main maxima of the 1st order will have equal intensity (This follows from the Babinet principle. i.e. According to the Babinet principle for complementary apertures, the light intensity distribution in the geometric shadow is the same.)
>
> **c.** We also consider the complementary grating (see point b,) illuminated with the same incident beam. In this situation we have the following relationships:
>
> 1. $I_{dif\ a}=I_{dif\ l-a}$ given the Babinet principle. (0.4pt)
> 2. $I_{0a}/a^2=I_{0l-a}/(l-a)^2$ for the in the intensity in the 0th order. (0.4pt)
> 3. $I_{dif\ a}+I_{0a}=\frac al I_{incident}$; $I_{dif\ l-a}+I_{0l-a}=\frac{l-a}{l}I_{incident}$. (0.6pt)
>
> From 1., 2., 3., we get:
>
> $$
> I_{dif\ a}=\frac{a(l-a)}{l^2}I_{incident}\qquad (0.6\text{pt})
> $$
>
> The maximum occurs for $a=l/2$ which leads to $I_{dif\ max}=1/4*I_{incident}$. (0.2+0.3pt)
>
> This grating is a pure amplitude grating, which causes the diffraction maximum corresponding to a slit to overlap with the main maximum of order 0.
>
> **d.** To avoid this problem, the grating must cause a periodic variation of the phase of the incident wave (phase gratings). In practice, reflection gratings are mainly used, the surface of their features is inclined to the plane of the grating, i.e. "blazed gratings".
>
> $\sin i+\sin\alpha=nm\lambda_o$ (0.4pt)
>
> For $m=1$ and $i=\alpha$ (maximum intensity) we obtain:
>
> $2\sin\alpha=n\lambda_o$ (0.4pt)
>
> $\alpha=30^\circ$. (0.2pt)
>
> **e.** The width of the spectral range $\Delta\lambda$ is:
>
> $\Delta\lambda=\frac{d}{(D_\alpha R/2)}=2d\cos\alpha/Rn$ (0.4pt)
>
> $\Delta\lambda=0.17$ Å. (0.2pt)
>
> Coherence length=optical path difference for which the interference fringes are no longer observed:
>
> Intensity distribution in a two-beam interferometer illuminated with radiation from the spectral range $[\lambda_o-\Delta\lambda/2;\lambda_o+\Delta\lambda/2]$ and $[\nu_o-\Delta\nu/2;\nu_o+\Delta\nu/2]$ respectively is:
>
> $$
> I=\int_{\nu_o-\Delta\nu/2}^{\nu_o+\Delta\nu/2}2\frac{I_o}{\Delta\nu}\left(1+\cos\frac{2\pi\nu}{c}L\right)d\nu=2\frac{I_o}{\Delta\nu}\left(\nu+\frac{\sin\frac{2\pi\nu}{c}L}{\frac{2\pi}{c}L}\right)\bigg|_{\nu_o-\Delta\nu/2}^{\nu_o+\Delta\nu/2}
> $$
>
> $$
> I=2I_o\left(1+\frac{\sin\frac{\pi\Delta\nu}{c}L}{\frac{\pi\Delta\nu}{c}L}\cos\frac{2\pi\nu_o}{c}L\right)\qquad (1\text{pt})
> $$
>
> Finge visibility:
>
> $$
> V=\frac{I_{max}-I_{min}}{I_{max}+I_{min}}=\frac{|\sin\frac{\pi\Delta\nu}{c}L|}{\frac{\pi\Delta\nu}{c}L}\qquad (0.6\text{pt})
> $$
>
> Where $L$ is the optical path difference corresponding to the interfering waves. The first disappearance of the fringes is obtained given the following condition:
>
> $$
> V=0\quad\longrightarrow\quad\frac{\pi\Delta\nu}{c}L_c=\pi\quad\longrightarrow\quad L_c=\frac c{\Delta\nu}\qquad (0.4\text{pt})
> $$
>
> $L_c=\frac{\lambda_o^2}{\Delta\lambda}$ (0.2pt)
>
> $L_c=1.5$ cm (0.2pt)
>
> **f.** The resolution power for the 1st order:
>
> $P=\frac\lambda{\delta\lambda}=N=nL=200000$ (0.4pt)
>
> The smallest range that could be resolved by the grating is then $\delta\lambda=0.025$ Å. (0.2pt)
>
> From the point of view of the matrix detector, the minimum spectral range is limited by the distance between two consecutive pixels 1 mm/200 pixels =5 μm
>
> $\delta\lambda'=2*5\mu m*\frac{\cos\alpha}{Rn}=0.043$ Å (0.4pt)
>
> $\delta\lambda'=0.043$ Å (0.2pt)
>
> Therefore, the minimum spectral range resolved by the spectrometer is 0.043 Å. (0.3pt)
