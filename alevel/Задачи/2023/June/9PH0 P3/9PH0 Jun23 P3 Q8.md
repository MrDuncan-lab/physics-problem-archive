---
id: 9PH0-jun23-3-q8
exam: "A Level"
board: "Pearson Edexcel"
qualification: "A level"
spec_code: "9PH0"
specification: "Physics (2015)"
subject: Physics
year: 2023
session: "June 2023"
session_code: "Jun23"
paper: 3
paper_name: "General and Practical Principles in Physics"
kind: structured
number: 8
points: 8
parts: ["a", "b"]
topics: ["[[7.2 Capacitors — capacitance, stored energy, charging and discharging]]", "[[1.2 Practical skills — measurement, uncertainties and graphs]]"]
level: "A2"
summary: "Разряд конденсатора: попадает ли ёмкость по графику в допуск ±20%, нужен ли регистратор данных"
has_mark_scheme: true
has_examiner_report: true
options_in: ""
status: "скрипт + Claude"
flags: []
lang: en
aliases: ["9PH0/03 June 2023 Q8"]
tags: [задача, alevel]
---

# Question 8 (8 marks)

**Pearson Edexcel A level Physics (9PH0)** · June 2023 · Paper 3 — General and Practical Principles in Physics · вопрос 8  
Источник: [[_pdf/2023/9PH0_03_qp_jun23.pdf#page=20|условие, стр. 20–21]] · [[_pdf/2023/9PH0_03_ms_jun23.pdf#page=18|схема оценивания, стр. 18]] · [[_pdf/2023/9PH0_03_er_jun23.pdf#page=40|отчёт экзаменаторов]]  
Работа: [[9PH0 Jun23 P3]]  
Темы: [[7.2 Capacitors — capacitance, stored energy, charging and discharging]], [[1.2 Practical skills — measurement, uncertainties and graphs]]

> [!abstract] Кратко (составлено моделью)
> Разряд конденсатора: попадает ли ёмкость по графику в допуск ±20%, нужен ли регистратор данных

A student investigated the discharge of a capacitor C through a resistor R using the circuit shown.

![[9PH0-jun23-3-p20-f1.svg]]

The student used the switch to connect C to X to charge the capacitor. She then connected C to Y to discharge the capacitor through R.

As the capacitor discharged, she recorded values of the potential difference *V* across C and corresponding values of time *t*. She used a stopwatch to measure *t*.

The student used her results to plot the following graph.

![[9PH0-jun23-3-p20-f2.svg]]

**(a)** The capacitor was marked 220 μF ± 20%.

Deduce whether the student’s data give a value of capacitance within the stated range.

*R* = 82 kΩ **[5]**

**(b)** The student suggested that her results would have been more accurate if she had used a data logger to record the data.

Assess the student’s suggestion. **[3]**

> [!grading]- Схема оценивания (mark scheme)
> | Пункт | Ответ (acceptable answers) | Указания (additional guidance) | Баллы |
> |---|---|---|---|
> | (a) | • A pair of corresponding *V* and *t* values read from graph **(1)**<br>• Use of $V = V_{0}e^{-\frac{t}{RC}}$<br>**Or** Use of time constant = *RC* **(1)**<br>• *C* = 270 μF **(1)**<br>• Use of ±20% with 220 μF<br>[Largest *C* = 264 μF, smallest *C* = 176 (μF)] **(1)**<br>• Comparison of 264 (μF) [176 (μF) if their calculated *C* is too low] with calculated value of C from graph and conclusion consistent with this **(1)** | [рисунок в схеме оценивания]<br>Allow use of tangent at *t* = 0 to determine intercept on *x*-axis and obtain value for time constant; then calculate *C* gives MP1, MP2 and MP3<br>MP3:Value should be correct and have units<br><u>Example of calculation</u><br>$1.0 = 6.0\text{e}^{-\frac{40\ \text{s}}{82\times10^{3}\ \Omega \times C}}$<br>$\therefore \ln\left(\dfrac{1.0\ \text{V}}{6.0\ \text{V}}\right) = -\dfrac{40\ \text{s}}{82 \times 10^{3}\ \Omega \times C}$<br>$\therefore C = \dfrac{-40\ \text{s}}{-1.79 \times 82 \times 10^{3}\ \Omega} = 2.72 \times 10^{-4}\ \text{C}$<br>Largest value of capacitance = 1.2 × 220 μF = 264 μF | 5 |
> | (b) | • The data has to be collected in a short time<br>**Or** Data logger has high sampling rate<br>Or Data logger enables readings to be taken more frequently **(1)**<br>• It would be difficult to read the voltmeter and stopwatch simultaneously **(1)**<br>• So the suggestion is correct<br>[dependent on MP1 or MP2] **(1)** | MP1: Data logger can take more readings in the time for capacitor to discharge | 3 |

> [!report]- Отчёт экзаменаторов
> **(a)**
>
> This was a well answered high mark calculation with most candidates scoring at least three marks for calculating the capacitance of the capacitor. Most candidates were comfortable with rearranging the equation to correctly determine C, with many using time constant = RC as an easier and more reliable route. Not all candidates were able to use the given tolerance to create a range (or in this case an upper bound) so that a conclusion could be made.
>
> This response scored full marks.
>
> The solution used in this response follows the first alternative given in the mark scheme (use of the exponential equation).
>
> This response scored full marks.
>
> The solution used in this response follows the second alternative given in the mark scheme (use of the time constant).
>
> **(b)**
>
> This question was poorly answered in general. The question demonstrated poor articulation by some candidates, who clearly had the idea that two values could not be taken at the same time but referred to reaction time instead of the idea of taking readings simultaneously.
>
> A significant minority of candidates recognised that a data logger has a high sample rate and so Mark Point 1 was probably scored more frequently than Mark Point 2. It was quite unusual to actually see responses that drew a conclusion as to whether the suggestion to use a data logger was correct or not.
