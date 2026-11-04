---
id: 9PH0-jun19-3-q5
exam: "A Level"
board: "Pearson Edexcel"
qualification: "A level"
spec_code: "9PH0"
specification: "Physics (2015)"
subject: Physics
year: 2019
session: "June 2019"
session_code: "Jun19"
paper: 3
paper_name: "General and Practical Principles in Physics"
kind: structured
number: 5
points: 9
parts: ["a", "b", "c"]
topics: ["[[5.3 Intensity, refraction and total internal reflection]]", "[[10.1 Black-body radiation, luminosity, Stefan–Boltzmann and Wien's laws]]"]
level: "A2"
summary: "Пульсоксиметр: экспоненциальное ослабление красного и ИК-излучения в крови, влияние галогенной лампы"
has_mark_scheme: true
has_examiner_report: true
options_in: ""
status: "скрипт + Claude"
flags: []
lang: en
aliases: ["9PH0/03 June 2019 Q5"]
tags: [задача, alevel]
---

# Question 5 (9 marks)

**Pearson Edexcel A level Physics (9PH0)** · June 2019 · Paper 3 — General and Practical Principles in Physics · вопрос 5  
Источник: [[_pdf/2019/9PH0_03_qp_jun19.pdf#page=12|условие, стр. 12–13]] · [[_pdf/2019/9PH0_03_ms_jun19.pdf#page=10|схема оценивания, стр. 10]] · [[_pdf/2019/9PH0_03_er_jun19.pdf#page=25|отчёт экзаменаторов]]  
Работа: [[9PH0 Jun19 P3]]  
Темы: [[5.3 Intensity, refraction and total internal reflection]], [[10.1 Black-body radiation, luminosity, Stefan–Boltzmann and Wien's laws]]

> [!abstract] Кратко (составлено моделью)
> Пульсоксиметр: экспоненциальное ослабление красного и ИК-излучения в крови, влияние галогенной лампы

An oximeter is a device used in hospitals to monitor the oxygen level in a patient’s blood.

In an oximeter, two light-emitting diodes (LEDs) are mounted opposite light sensors in a clip and attached to the patient’s finger. One of the LEDs produces red light and the other produces infrared.

![[9PH0-jun19-3-p12-f1.png]]

The intensity *I* of electromagnetic radiation received by the detector, after passing through a thickness *x* of blood, is given by

$I = I_{0}e^{-\mu x}$

where *I*$_{0}$ is the intensity that would have been received if the blood were not present and *μ* is the attenuation coefficient of blood.

The red LED emits visible light of wavelength 650 nm and the infrared LED emits infrared of wavelength 950 nm.

The graph shows how *μ* varies with wavelength *λ* for oxygenated blood and deoxygenated blood.

![[9PH0-jun19-3-p12-f2.svg]]

**(a)** *I*$_{0}$ for the infrared LED is 1.8 W m$^{-2}$.

Calculate *I* for the infrared after passing through 1.4 mm of oxygenated blood. **[3]**

*I* =  \_\_\_\_\_\_

**(b)** The oximeter determines *I* / *I*$_{0}$ the fraction of radiation transmitted at each wavelength.

Deduce whether *I* / *I*$_{0}$ will be smaller for the red or the infrared radiation if the blood is deoxygenated. **[3]**

It is suggested that ambient light could affect the readings produced by the oximeter.

Halogen lamps have a filament temperature of 3200 K.

**(c)** Deduce whether the light from such a lamp would have a significant effect on the oximeter readings. **[3]**

> [!grading]- Схема оценивания (mark scheme)
> | Пункт | Ответ (acceptable answers) | Указания (additional guidance) | Баллы |
> |---|---|---|---|
> | (a) | • *μ* read from graph **(1)**<br>• Use of $I = I_{0}e^{-\mu x}$ **(1)**<br>• *I* = 1.5 W m$^{-2}$ **(1)** | Accept *μ* in the range 140 (m$^{-1}$) - 160 (m$^{-1}$)<br>Accept answers that round to 1.4 W m$^{-2}$ or 1.5 W m$^{-2}$ dependent upon value of *μ* for MP3<br><u>Example of calculation:</u><br>$I = 1.8\ \text{W m}^{-2}\times\text{e}^{-150\ \text{m}^{-1}\times1.4\times10^{-3}\ \text{m}} = 1.46\ \text{W m}^{-2}$ | 3 |
> | (b) | • (for deoxygenated blood) *μ* is greater for red **(1)**<br>• hence more red is absorbed<br>**Or** intensity is smaller for red<br>**Or** $\text{e}^{-\mu x}$ is smaller for red **(1)**<br>• So $I/I_{0}$ is smaller for red [dependent upon MP2] **(1)** | Accept values for μ which show $\mu_{\text{red}} > \mu_{\text{IR}}$ for MP1<br>Allow numerical substitutions for MP2 and MP3<br>Accept converse argument leading to same conclusion | 3 |
> | (c) | • Use of $\lambda_{\text{max}}T = 2.898\times10^{-3}$ m K **(1)**<br>• $\lambda_{\text{max}}$ = 910 nm **(1)**<br>• Yes, because peak emission occurs at a wavelength close to 950 nm **(1)** | Ignore references to the wavelength of red light<br><u>Example of calculation:</u><br>$\lambda_{\text{max}} = \dfrac{2.898\times10^{-3}\ \text{m K}}{3200\ \text{K}} = 9.06\times10^{-7}\ \text{m}$ | 3 |

> [!report]- Отчёт экзаменаторов
> **(a)**
>
> Candidates quite often had problems interpreting the logarithmic scale and so they used an incorrect of μ from the graph. A significant number of candidates gave their answer with an incorrect unit (even though it was given in the question), and so they did not gain mark point 3.
>
> This response gains all 3 marks. Although the candidate hasn't substituted into the exponential equation, logs have been taken before substituting values and then an inverse log function has been carried out to calculate a value for I that is within range. Correct units are included.
>
> **(b)**
>
> Too many compared deoxygenated blood to oxygenated blood instead of answering the question.
>
> Some candidates had difficulty reading the μ values, sometimes using the wrong graph, but most were awarded mark point 1. Many then jumped straight to the answer without giving any acceptable working.
>
> This response uses qualitative data from the graph to give a clear deduction, so all 3 marks are awarded.
>
> In this response, numerical data is used from the graph to calculate values for I for deoxygenated blood at the two wavelengths. A correct deduction is made, and so all 3 marks are awarded.
>
> **(c)**
>
> Most candidates realised they could calculate the peak wavelength of the emission at 3200K, but not all knew what to do with their answer. Rarely did candidates make an adequate comparison to the wavelength of the infra-red radiation to gain mark point 3.
>
> Although a correct calculation has been carried out, the deduction made is invalid, and so the response only gains credit for mark point 1 and mark point 2. The candidate has realised that the wavelength is similar to that of the infra-red radiation, but concludes that this will not have a significant effect as the values of μ for these two wavelength will be similar.
>
> A correct calculation and associated deduction, so this response gains all 3 marks.
