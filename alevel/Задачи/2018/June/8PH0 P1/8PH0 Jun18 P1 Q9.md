---
id: 8PH0-jun18-1-q9
exam: "A Level"
board: "Pearson Edexcel"
qualification: "AS"
spec_code: "8PH0"
specification: "Physics (2015)"
subject: Physics
year: 2018
session: "June 2018"
session_code: "Jun18"
paper: 1
paper_name: "Core Physics I"
kind: structured
number: 9
points: 6
parts: ["a", "b"]
topics: ["[[3.3 Series and parallel circuits, Kirchhoff's laws]]", "[[3.4 Potential dividers, thermistors and LDRs]]"]
level: "AS"
summary: "Вывод сопротивления последовательной цепи; сопротивление вольтметра по его показанию в делителе"
has_mark_scheme: true
has_examiner_report: true
options_in: ""
status: "скрипт + Claude"
flags: ["источник (опечатка в PDF Pearson, оставлена как напечатано): в PDF у токов единица «Ω» вместо «A» (0.045 Ω, 0"]
lang: en
aliases: ["8PH0/01 June 2018 Q9"]
tags: [задача, alevel]
---

# Question 9 (6 marks)

**Pearson Edexcel AS Physics (8PH0)** · June 2018 · Paper 1 — Core Physics I · вопрос 9  
Источник: [[_pdf/2018/8PH0_01_qp_jun18.pdf#page=8|условие, стр. 8–9]] · [[_pdf/2018/8PH0_01_ms_jun18.pdf#page=8|схема оценивания, стр. 8]] · [[_pdf/2018/8PH0_01_er_jun18.pdf#page=6|отчёт экзаменаторов]]  
Работа: [[8PH0 Jun18 P1]]  
Темы: [[3.3 Series and parallel circuits, Kirchhoff's laws]], [[3.4 Potential dividers, thermistors and LDRs]]

> [!abstract] Кратко (составлено моделью)
> Вывод сопротивления последовательной цепи; сопротивление вольтметра по его показанию в делителе

**(a)** Three resistors, of resistance *R*$_{1}$, *R*$_{2}$ and *R*$_{3}$, are connected in series across a cell. The cell has electromotive force (e.m.f.) *ε* with negligible internal resistance. The current through the cell is *I*.

![[8PH0-jun18-1-p8-f1.svg]]

Derive the formula for the total resistance *R*$_{\text{T}}$ of the circuit in terms of *R*$_{1}$, *R*$_{2}$ and *R*$_{3}$. **[3]**

**(b)** The circuit diagram shows two resistors in series across a battery of e.m.f. 6.0 V and negligible internal resistance. A voltmeter with low resistance is connected across the 40 Ω resistor.

![[8PH0-jun18-1-p9-f1.svg]]

The reading on the voltmeter is 1.8 V.

Calculate the resistance of the voltmeter. **[3]**

Resistance of voltmeter =  \_\_\_\_\_\_

> [!grading]- Схема оценивания (mark scheme)
> | Пункт | Ответ (acceptable answers) | Указания (additional guidance) | Баллы |
> |---|---|---|---|
> | (a) | • A statement applying the conservation of energy to the circuit **(1)**<br>• Use of Ohm’s law for each term /individual pd leading to the cancelling of currents in the equation **(1)**<br>• $R_{\text{T}} = R_{1} + R_{2} + R_{3}$ **(1)** | <u>Example of calculation</u><br>$\varepsilon = V_{1} + V_{2} + V_{3}$<br>$\varepsilon = IR_{\text{T}} = IR_{1} + IR_{2} + IR_{3}$<br>$R_{\text{T}} = R_{1} + R_{2} + R_{3}$ | 3 |
> | (b) | **Either**<br>• Use of equation(s) to determine the total resistance of the voltmeter and 40 Ω resistor in parallel (34.3 Ω)<br>i.e. potential divider formula or Ohm’s law **(1)**<br>• Use of $\dfrac{1}{R_{T}} = \dfrac{1}{R_{1}} + \dfrac{1}{R_{2}}$ **(1)**<br>• $R_{\text{v}} = 240\ (\Omega)$ **(1)**<br>**Or**<br>• Use of Ohm’s law to determine the current through voltmeter (0.0075 A)<br>i.e. current in 40 Ω resistor calculated (0.045 Ω) **and** subtracted from current in 80 Ω resistor (0.0525 Ω) **(1)**<br>• Use of Ohm’s law with 1.8 V to calculate the resistance of the voltmeter **(1)**<br>• $R_{\text{v}} = 240\ (\Omega)$ **(1)** | <u>Example of calculation</u><br>$\left(\dfrac{R}{80\ \Omega + R}\right) 6\ \text{V} = 1.8\ \text{V}$<br>$R = 34.29\ \Omega$<br>$\dfrac{1}{34.29\ \Omega} = \dfrac{1}{40\ \Omega} + \dfrac{1}{R_{V}}$<br>$R_{\text{V}} = 240.2\ \Omega$ | 3 |

> [!report]- Отчёт экзаменаторов
> **(a)**
>
> Specification point 36 requires learners to be able to derive the equations for combining resistances in both series and parallel. While it was very clear that many centres had covered this in detail, some learners still omitted steps or tried to work backwards with most recalling the end point of this derivation, the equation for the total resistance. The start point for all should have been the conservation of energy and a statement that the EMF of the cell was equal to the sum of all the individual potential differences in the circuit. Applying Ohm’s law for each term should have led to a cancellation of the currents and a final expression for the total resistance in the circuit.
>
> The question stated that the internal resistance of the cell is negligible, but some learners chose to start their derivation using V = E - Ir, which did not lead anywhere so many accompanied their response with a statement of the total resistance, as the end point was clearly known.
>
> This response scored just 1 mark.
>
> The learner clearly knew the equation for the total resistance for resistors in series but did not know where to start the derivation for this equation as no attempt was made to derive it.
>
> To derive the total resistance for resistors in series, you need to start with a statement using the conservation of energy Vtotal = V1 + V2 + V3 and then use Ohm's law for each term.
>
> To deive the total resistance of resitors in parallel, you need to start with a statement using the conservation of charge, Itotal = I1 + I2 + I3 and then use Ohm's law for each term.
>
> This response scored 2 marks, MP1 and MP3.
>
> The learner started off correctly, using the conservation of energy to obtain a statement of the total potential difference across the components is equal to the EMF of the cell. They then divided the individual voltages by the currents rather than replace each potential difference using Ohm's law, therefore this method did not lead them to the correct statement.
>
> The learner, did however state the correct equation at the end which allowed MP3 to be awarded. There was no justification for this but the marking points were indepenedent.
>
> **(b)**
>
> Very few learners managed to answer this question successfully. Those who correctly calculated a resistance of 240 W usually used the potential divider formula to obtain the total resistance of the parallel branch. They then successfully used the formula for the total resistance in a parallel circuit to obtain the resistance of the voltmeter.
>
> Some learners did manage to score 1 mark for using Ohm’s law with the p.d. across the voltmeter and what they thought to be the current in the voltmeter. Less able learners ignored the 1.85 V and assumed that the voltage was split 2V and 4V across the resistors, ignoring any reduction in the resistance due to the resistance in parallel of the voltmeter. Many could not correctly determine the current through the voltmeter, assuming that the current through the 40 W resistor was 0.05 A (6/120).
>
> This response scored all 3 marks.
>
> The learner used a ratio of the resistance R across the parallel section compared to the total resistance, 80 + R, with the p.d. across the parallel section compared to the total p.d. (i.e. the potential divider equation) to determine the total resistance of the parallel circuit, leaving their answer as a fraction. This is fine for interim calcualtions but not for the final answer.
>
> They then used the equation for the total resistance of resistors in parallel to determine the resitance of the voltmeter.
>
> This was a more typical response scoring just 1 mark for MP2, using the alternative marking route (the 'Or') on the mark scheme.
>
> The learner has assumed that the total resistance of the parallel section of the circuit is 80 Ω and has ignored the fact that the voltmeter has its own resistance. They then used Ohm's law to calculate an incorrect value for the current in the circuit. They then assumed that this is also the current in the voltmeter and used Ohm's law again, this time with the correct p.d. across the voltmeter to determine what they think is the resistance of the voltmeter.
