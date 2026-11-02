---
id: rompho-2014-intl-theory-t2
olympiad: RomPhO
year: 2014
stage: "Международная олимпиада"
round: теория
grade: ""
number: "T2"
title: "Terrestrial climate modeling"
points: 10
aliases: ["Terrestrial climate modeling"]
topics: ["[[2.1 Уравнение теплового баланса. 8-ой класс]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: true
source_damaged: false
summary: "Моделирование радиационного теплового баланса Земли с учётом альбедо и свойств атмосферы; определить среднюю температуру поверхности."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# Theoretical Problem no. 2 (10 points)

**RomPhO 2014** · Международная олимпиада · теория · задача T2  
Источник: [[_pdf/RomPhO/RomPhO-2014-T2.pdf#page=1|условие, стр. 1–3]] · [[_pdf/RomPhO/RomPhO-2014-T2-solution.pdf#page=4|критерии, стр. 4]]

Темы: [[2.1 Уравнение теплового баланса. 8-ой класс]]

> [!abstract] Кратко (составлено моделью)
> Моделирование радиационного теплового баланса Земли с учётом альбедо и свойств атмосферы; определить среднюю температуру поверхности.

## Terrestrial climate modeling

Climate change and global warming, the life of humans in new climatic conditions becomes topics of public interest in recent decades.

On a cosmic scale, the only phenomena occurring in Earth's energy balance are absorption and emission of radiation. One can say that the earth's climate condition depends on delicate balance between the energy that our planet receives for the formidable energy source that is the sun and the energy that Earth radiates into space. Consider that solar constant for the radiation coming from the Sun towards the Earth is $w_S=1370\;W\cdot m^{-2}$.

A body that absorbs electromagnetic radiation reaching the surface, regardless of the wavelength of the radiation and emits electromagnetic radiation according to the temperature of its surface is called a blackbody. A black body emits energy with a specific spectral distribution, depending on its own temperature. Solid smooth lines, in the graph in Figure 1 show the spectral distribution of the emission energy of the Sun, equivalent to a black body.

![[rompho-2014-t2-problems-p1-f1.png]]
*Figure 1 (not for calculations purposes)*

If $\varepsilon(T)$ represents the total energy (in the whole spectrum) emitted by unit area of a black body in unit time, and $T$ is the absolute temperature of the black body, then the Stefan - Boltzmann states that $\varepsilon(T)=\sigma\cdot T^4$. In the expression $\sigma=5{,}67\cdot10^{-8}\;W\cdot m^{-2}\cdot K^{-4}$ is Stefan – Boltzmann constant.

Problem proposes you to use different modeling in different workloads and to determine the average temperature the Earth would have at the surface for each of the models used. Express the answers as function of symbols of quantities or numerical values marked in blue color in the problem statement. Express obtained numerical results in the form of integers.

**Task no. 1**

In the task no. 1 uses simple modeling. Suppose that the energy is taken from the Sun and that the Earth loses energy as a black body.

**1.a.** Determine the expression of average temperature $T_P$ that the Earth's surface should have, in accordance with simple modeling used. (0,70p)

**1.b.** Calculate the numerical value $T_P$ of the average temperature that the Earth's surface should have, according to this model. (0,30p)

**Task no. 2**

Simple modeling of the task no. 1 one assumes that the Earth is a black body. Assumption is unrealistic, because all images taken from space show the Earth as a luminous body.

Earth's atmosphere (especially clouds) reflects approximately $24\%$ of the energy coming from the Sun and the Earth's surface (especially ice areas) still reflects $6\%$ of the incident energy. Feature called albedo measures the ratio of reflected radiant flux and incident radiant flux. Considers that terrestrial albedo is $A=30\%$.

**2.a.** Determine the expression of average temperature $T'_P$ that the Earth's surface should have, in accordance with simple modeling used in these workload. (0,70p)

**2.b.** Calculate the numerical value $T'_P$ of the average temperature that the Earth's surface should have, according to the model in workload 2a. (0,30p)

**Task no. 3**

While the Sun emits energy mostly in the visible, relatively low temperature of the Earth's land surface causes its emission to be localized in the infrared spectrum. A careful modeling of climate takes account of the atmosphere. The atmospheric gas is a mixture having specific absorbent properties. The Spectrum illustrated in Figure 1 shows that the different atmospheric gases absorb radiation in different spectral domains. Characterization of the spectral absorption can be achieved by introduction of transmission coefficients in the visible $\alpha_{vis}$ and infrared $\alpha_{ir}$, respectively, representing the ratio of the energy passing through the air (in the visible or infrared), and the energy that enters the atmosphere. If radiation in a specified spectral range is completely absorbed, then the corresponding transmission coefficient is zero, and if radiation is not absorbed at all, then the transmission coefficient is one.

Task no. 3 proposes to determine the Earth's temperature $T''_P$ using a modeling that takes into account the partial reflection of light coming from the sun (albedo $A$) and absorptive properties of the atmosphere (transmission coefficients $\alpha_{vis}$ and $\alpha_{ir}$).

**3.a.** Determine the expression of average temperature $T''_P$ that the Earth's surface should have, in accordance with modeling used in these workload. (2,50p)

**3.b.** Calculate the numerical value $T''_P$ of the average temperature that the Earth's surface should have when $A=0{,}3$, $\alpha_{vis}=0{,}8$ and $\alpha_{ir}=0{,}1$. (0,30p)

**3.c.** Using modeling proposed in this workload, calculate the average temperature on the Earth surface, where albedo and transmission coefficients have the values given in Table 1 (1,20p)

*Table 1*

| Case | I | II | III | IV |
|---|---|---|---|---|
| $\alpha_{vis}$ | 1 | 1 | 1 | 1 |
| $\alpha_{ir}$ | 1 | 1 | 0 | 0 |
| $A$ | 0,3 | 0,0 | 0,0 | 0,3 |
| $T''_P$ (K) | | | | |
| $t''_P$ ($^\circ$C) | | | | |

**Task no. 4**

Use modeling proposed in the task no. 3 and assume that the distance between Earth and the Sun would rise by $f=1\%$.

**4.a.** Determine the expression of average temperature $T'''_P$ that the Earth's surface should have, if $A=0{,}3$, $\alpha_{ir}=0{,}3$ and $\alpha_{vis}=0{,}6$. (1,00p)

**Task no. 5**

Assume that some of the sand found in the Sahara desert would be "transformed" into a "mirror glass".

**5.a.** Using the modeling proposed in task no. 3 estimates the surface that "mirror glass" should have so that the average temperature at the Earth's surface to fall $1^\circ C$ against the value determined in the task 3.b. Consider that the radius of the Earth is $R_P=6400\,km$. (3,00p)

> [!answer]- Ответ
> **1.a** — $T_P=\sqrt[4]{\frac{w_S}{4\cdot\sigma}}$
>
> **1.b** — $T_P\cong279K$, $t_P\cong6^\circ C$
>
> **2.a** — $T'_P=\sqrt[4]{\frac{(1-A)\cdot w_S}{4\cdot\sigma}}$
>
> **2.b** — $T'_P\cong255K$, $t'_P\cong-18^\circ C$
>
> **3.a** — $T''_P=\sqrt[4]{\frac{w_s\cdot(1-A)\cdot(\alpha_{vis}+1)}{4\cdot\sigma\cdot(\alpha_{ir}+1)}}$
>
> **3.b** — $T''_P\cong288K$, $t''_P\cong15^\circ C$
>
> **4.a** — $T'''_P\cong267K$, $t'''_P\cong-6^\circ C$
>
> **5.a** — $x=0{,}0544$, $s\cong7\cdot10^6\,km^2$

> [!solution]- Решение (схема оценивания)
> Barem de evaluare şi de notare
>
> Se punctează în mod corespunzător oricare altă modalitate de rezolvare corectă a problemei
>
> Problema teoretică nr. 2 — Modelarea climei terestre
>
> | Nr. item | Sarcina de lucru nr. 1 | | Punctaj |
> |---|---|---|---|
> | 1.a. | Pentru: | | 0,70p |
> | | $w_S\cdot\pi\cdot R_P^2=\sigma\cdot T_P^4\cdot4\cdot\pi\cdot R_P^2$ | 0,50p | |
> | | expresia temperaturii medii la suprafaţa Pământului $T_P=\sqrt[4]{\frac{w_S}{4\cdot\sigma}}$ | 0,20p | |
> | 1.b. | Pentru: $T_P\cong279K$, $t_P\cong6^\circ C$ | 0,30p | 0,30p |
> | Nr. item | Sarcina de lucru nr. 2 | | Punctaj |
> | 2.a. | Pentru: | | 0,70p |
> | | $(1-A)\cdot w_S\cdot\pi\cdot R_P^2=\sigma\cdot T_P'^4\cdot4\cdot\pi\cdot R_P^2$ | 0,50p | |
> | | expresia temperaturii medii la suprafaţa Pământului $T'_P=\sqrt[4]{\frac{(1-A)\cdot w_S}{4\cdot\sigma}}$ | 0,20p | |
> | 2.b. | Pentru: $\begin{cases}T'_P\cong255K\\t'_P\cong-18^\circ C\end{cases}$ | 0,30p | 0,30p |
> | Nr. item | Sarcina de lucru nr. 3 | | Punctaj |
> | 3.a. | Pentru: | | 2,50p |
> | | expresia energiei care ajunge la suprafaţa Pământului în unitatea de timp, venind de la Soare $E_S=\pi\cdot R_P^2\cdot w_s\cdot(1-A)\cdot\alpha_{vis}$ | 0,30p | |
> | | bilanţul puterilor la suprafaţa Pământului $(1-A)\cdot w_s\cdot\pi\cdot R_P^2\cdot\alpha_{vis}+E_A=\sigma\cdot T_P''^4\cdot4\cdot\pi\cdot R_P^2$, unde $E_A$ este puterea radiantă, datorată atmosferei | 1,00p | |
> | | bilanţul puterilor în partea superioară a atmosferei $(1-A)\cdot w_s\cdot\pi\cdot R_P^2=\sigma\cdot T_P''^4\cdot4\cdot\pi\cdot R_P^2\cdot\alpha_{ir}+E_A$ | 1,00p | |
> | | expresia temperaturii medii la suprafaţa Pământului $T''_P=\sqrt[4]{\frac{w_s\cdot(1-A)\cdot(\alpha_{vis}+1)}{4\cdot\sigma\cdot(\alpha_{ir}+1)}}$ | 0,20p | |
> | 3.b. | Pentru: $\begin{cases}T''_P\cong288K\\t''_P\cong15^\circ C\end{cases}$ | 0,30p | 0,30p |
> | 3.c. | Pentru: | 4x 0,30p | 1,20p |
>
> | Caz | I | II | III | IV |
> |---|---|---|---|---|
> | $w_s$ | 1370 | 1370 | 1370 | 1370 |
> | $\alpha_{vis}$ | 1 | 1 | 1 | 1 |
> | $\alpha_{ir}$ | 1 | 1 | 0 | 0 |
> | $A$ | 0,3 | 0,0 | 0,0 | 0,3 |
> | $T''_P$ (K) | 255 | 279 | 332 | 303 |
> | $t''_P$ ($^\circ$C) | -18 | 6 | 59 | 30 |
>
> | Nr. item | Sarcina de lucru nr. 4 | | Punctaj |
> |---|---|---|---|
> | 4.a. | Pentru: | | 1,00p |
> | | $w'_s=\frac{w_s}{(1{,}01)^2}$ | 0,50p | |
> | | expresia temperaturii medii la suprafaţa Pământului $T'''_P=\sqrt[4]{\frac{w'_s\cdot(1-A)\cdot(\alpha_{vis}+1)}{4\cdot\sigma\cdot(\alpha_{ir}+1)}}$ | 0,20p | |
> | | $\begin{cases}T'''_P\cong267K\\t'''_P\cong-6^\circ C\end{cases}$ | 0,30p | |
> | Nr. item | Sarcina de lucru nr. 5 | | Punctaj |
> | 5.a. | Pentru: | | 3,00p |
> | | expresia ariei suprafeţei „oglinzii de sticlă” din deşertul Sahara $s=x\cdot\pi\cdot R_P^2$ | 0,10p | |
> | | expresia ariei suprafeţei „de captură” a energiei solare $\begin{cases}S_{captura}=\pi\cdot R_P^2-\frac{x}{2}\cdot\pi\cdot R_P^2\\S_{captura}=\pi\cdot R_P^2\cdot(1-\frac{x}{2})\end{cases}$ | 0,20p | |
> | | expresia ariei suprafeţei emiţătoare $\begin{cases}S_{emitator,P}=4\cdot\pi\cdot R_P^2-x\cdot\pi\cdot R_P^2\\S_{emitator,P}=\pi\cdot R_P^2\cdot(4-x)\end{cases}$ | 0,20p | |
> | | bilanţul puterilor la suprafaţa Pământului $(1-A)\cdot w_s\cdot\pi\cdot R_P^2\cdot(1-\frac{x}{2})\cdot\alpha_{vis}+E_A=\sigma\cdot(T'''_{P,Sahara})^4\cdot\pi\cdot R_P^2\cdot(4-x)$ | 0,70p | |
> | | bilanţul puterilor în partea superioară a atmosferei $(1-A)\cdot w_s\cdot\pi\cdot R_P^2\cdot(1-\frac{x}{2})=\sigma\cdot(T'''_{P,Sahara})^4\cdot\pi\cdot R_P^2\cdot(4-x)\cdot\alpha_{ir}+E_A$ | 0,70p | |
> | | $T'''_{P,Sahara}=\sqrt[4]{\frac{w_s\cdot(1-A)}{\sigma}\cdot\frac{\alpha_{vis}+1}{\alpha_{ir}+1}\cdot\frac{1-\frac{x}{2}}{4-x}}$ | 0,20p | |
> | | $\frac{T'''_{P,Sahara}}{T''_P}=\sqrt[4]{\frac{1-\frac{x}{2}}{1-\frac{x}{4}}}$ | 0,20p | |
> | | $\frac{1-\frac{x}{2}}{1-\frac{x}{4}}=\left(\frac{T'''_{P,Sahara}}{T''_P}\right)^4=k$, unde $k=0{,}9862$ | 0,30p | |
> | | $\begin{cases}x=\frac{4\cdot(1-k)}{2-k}\\x=0{,}0544\end{cases}$ | 0,20p | |
> | | aria suprafeţei „oglinzii de sticlă” din Sahara $s\cong7\cdot10^6\,km^2$. Observaţie: Aria suprafeţei Saharei este de $9\cdot10^6\,km^2$. | 0,20p | |
> | TOTAL | | | 10p |
