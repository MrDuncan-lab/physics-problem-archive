---
id: ukrpho-2016-final-theory-8-5
olympiad: UkrPhO
year: 2016
stage: "Заключительный этап"
round: теория
grade: 8
number: "8-5"
title: "Задача 8-5"
aliases: ["Задача 8-5"]
topics: ["[[2.1 Уравнение теплового баланса. 8-ой класс]]"]
difficulty: 3
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "По температурам выходящей охлаждающей смеси при разных скоростях прокачки найти объёмную долю льда и минимальный расход без кипения."
status: "проверено: сверка, два чтения + арбитр"
lang: ru
lang_orig: uk
translated: "GPT Pro, ukrpho_tr02_p3_RESULT"
tags: [задача]
---

# 5.

**UkrPhO 2016** · Заключительный этап · теория · 8 класс · задача 8-5  
Источник: [[_pdf/UkrPhO/2016-final-theory-08-combined.pdf#page=1|условие, стр. 1]] · [[_pdf/UkrPhO/2016-final-theory-08-combined.pdf#page=10|решение, стр. 10]]

Темы: [[2.1 Уравнение теплового баланса. 8-ой класс]]

> [!abstract] Кратко (составлено моделью)
> По температурам выходящей охлаждающей смеси при разных скоростях прокачки найти объёмную долю льда и минимальный расход без кипения.

Для охлаждения химического оборудования было предложено использовать в качестве охлаждающей жидкости смесь холодной воды ($t_0=0^\circ C$) с мелко перетертым льдом. При тестировании установки выяснилось, что при закачивании в систему охлаждающей жидкости со скоростью $V_1=0{,}2\text{ м/с}$ на выходе получалась вода с температурой $t_1=30^\circ C$, а при закачивании охлаждающей жидкости со скоростью $V_2=0{,}1\text{ м/с}$ — вода с температурой $t_2=80^\circ C$.

**1)** Какую объемную часть составляет лед в охлаждающей жидкости?

**2)** При какой минимальной скорости прокачки система охлаждения еще будет нормально работать (т.е. жидкость не будет закипать внутри системы)?

Для расчетов принять: удельная теплоемкость воды равна $c=4200\text{ Дж}/(\text{кг}\cdot\text{град})$, удельная теплота плавления льда $\lambda=3{,}3\cdot10^5\text{ Дж/кг}$, отношение плотности льда к плотности воды $\rho_\text{л}/\rho_\text{в}=0{,}9$

***Примечание:*** *под термином «объемная часть льда» следует понимать долю объема льда в объеме охлаждающей жидкости, т.е. отношение объема льда к объему охлаждающей жидкости.*

> [!answer]- Ответ
> **1**
>
> $$
> \alpha=\left[\frac{\rho_\text{в}-\rho_\text{л}}{\rho_\text{в}}+\frac{\lambda\cdot\rho_\text{л}}{c\cdot\rho_\text{в}}\cdot\frac{V_1-V_2}{V_2\Delta t_2-V_1\Delta t_2}\right]^{-1}=\left[\varepsilon+\frac{\lambda\cdot\rho_\text{л}}{c\cdot\rho_\text{в}}\cdot\frac{V_1-V_2}{V_2\Delta t_2-V_1\Delta t_2}\right]^{-1}=0{,}275
> $$
>
> **2**
>
> $$
> V_3=\frac{\alpha\cdot\rho_\text{л}(\lambda+c\Delta t_1)+(1-\alpha)\cdot\rho_\text{в}\cdot c\Delta t_1}{\alpha\cdot\rho_\text{л}(\lambda+c\Delta t_3)+(1-\alpha)\cdot\rho_\text{в}\cdot c\Delta t_3}\cdot V_1=\frac{\Delta t_1+\Theta}{\Delta t_3+\Theta}\cdot V_1=0{,}083\text{ м/с}
> $$
>
> **3)** — **1)** $\alpha=\left[\frac{\rho_\text{в}-\rho_\text{л}}{\rho_\text{в}}+\frac{\lambda\cdot\rho_\text{л}}{c\cdot\rho_\text{в}}\cdot\frac{V_1-V_2}{V_2\Delta t_2-V_1\Delta t_2}\right]^{-1}=0{,}275$; **2)** $V_3=0{,}083\text{ м/с}$.

> [!solution]- Решение
> **Решение.** Обозначим объемную часть льда буквой $\alpha$, а сечение подводящих труб буквой $S$.
>
> С какой бы скоростью не прокачивали бы охлаждающую жидкость, она всегда выносит из установки за единицу времени одно и то же количества тепла. Найдем эту тепловую мощность. Для этого учтем, что за время $t$ в систему попадает:
>
> **1)** объем охлаждающей жидкости равный $V_\text{об}=V\cdot S\cdot t$;
>
> **2)** масса льда в нем равна $m_\text{л}=\alpha VSt\cdot\rho_\text{л}$ и масса воды — $m_\text{в}=(1-\alpha)VSt\cdot\rho_\text{в}$;
>
> **3)** на плавление льда идет количества тепла равное $Q_1=\lambda m_\text{л}=\alpha\cdot\lambda\cdot V\cdot S\cdot t\cdot\rho_\text{л}$, на нагрев всей воды (в том числе получившейся из растопленного льда) идет количество тепла равное $Q_2=c(m_\text{л}+m_\text{в})\Delta t=c\cdot[\alpha\cdot\rho_\text{л}+(1-\alpha)\cdot\rho_\text{в}]\cdot\Delta t\cdot V\cdot S\cdot t$.
>
> Таким образом, тепловая мощность, которую уносит охлаждающая жидкость, равна
>
> $$
> P=\frac{Q_1+Q_2}{t}=\left[\alpha\cdot\rho_\text{л}(\lambda+c\Delta t)+(1-\alpha)\cdot\rho_\text{в}\cdot c\Delta t\right]\cdot V\cdot S
> $$
>
> **2)** Приравнивая два этих выражения для случаев, описанных в задаче, получаем уравнение:
>
> $$
> \left[\alpha\cdot\rho_\text{л}(\lambda+c\Delta t_1)+(1-\alpha)\cdot\rho_\text{в}\cdot c\Delta t_1\right]\cdot V_1\cdot S=\left[\alpha\cdot\rho_\text{л}(\lambda+c\Delta t_2)+(1-\alpha)\cdot\rho_\text{в}\cdot c\Delta t_2\right]\cdot V_2\cdot S
> $$
>
> Откуда вытекает ответ для объемной части льда в охлаждающей жидкости (обозначим $\varepsilon=(\rho_\text{в}-\rho_\text{л})/\rho_\text{в}=0{,}1$):
>
> $$
> \alpha=\left[\frac{\rho_\text{в}-\rho_\text{л}}{\rho_\text{в}}+\frac{\lambda\cdot\rho_\text{л}}{c\cdot\rho_\text{в}}\cdot\frac{V_1-V_2}{V_2\Delta t_2-V_1\Delta t_2}\right]^{-1}=\left[\varepsilon+\frac{\lambda\cdot\rho_\text{л}}{c\cdot\rho_\text{в}}\cdot\frac{V_1-V_2}{V_2\Delta t_2-V_1\Delta t_2}\right]^{-1}=0{,}275
> $$
>
> **3)** Для предельно малой скорости охлаждающей жидкости $V_3$ на выходе будет выходить вода при температуре $t_3=100^\circ C$. Связывая это течение с первым, получаем уравнение:
>
> $$
> \left[\alpha\cdot\rho_\text{л}(\lambda+c\Delta t_1)+(1-\alpha)\cdot\rho_\text{в}\cdot c\Delta t_1\right]\cdot V_1\cdot S=\left[\alpha\cdot\rho_\text{л}(\lambda+c\Delta t_3)+(1-\alpha)\cdot\rho_\text{в}\cdot c\Delta t_3\right]\cdot V_3\cdot S
> $$
>
> Откуда второй ответ (введем обозначение $\Theta=\frac{\lambda\cdot\rho_\text{л}}{c\cdot\rho_\text{в}}\cdot\frac{\alpha}{(1-\alpha\cdot\varepsilon)}\approx20^\circ C$):
>
> $$
> V_3=\frac{\alpha\cdot\rho_\text{л}(\lambda+c\Delta t_1)+(1-\alpha)\cdot\rho_\text{в}\cdot c\Delta t_1}{\alpha\cdot\rho_\text{л}(\lambda+c\Delta t_3)+(1-\alpha)\cdot\rho_\text{в}\cdot c\Delta t_3}\cdot V_1=\frac{\Delta t_1+\Theta}{\Delta t_3+\Theta}\cdot V_1=0{,}083\text{ м/с}
> $$
>
> **Ответ:** **1)** $\alpha=\left[\frac{\rho_\text{в}-\rho_\text{л}}{\rho_\text{в}}+\frac{\lambda\cdot\rho_\text{л}}{c\cdot\rho_\text{в}}\cdot\frac{V_1-V_2}{V_2\Delta t_2-V_1\Delta t_2}\right]^{-1}=0{,}275$; **2)** $V_3=0{,}083\text{ м/с}$.

> [!original]- Оригинал (украинский)
> Для охолодження хімічного обладнання було запропоновано використати як охолоджувальну рідину суміш холодної води ($t_0=0^\circ C$) з дрібно перетертим льодом. При тестуванні установки з’ясувалося, що при закачуванні до системи охолоджувальної рідини зі швидкістю $v_1=0{,}2$ м/с на виході отримувалася вода з температурою $t_1=30^\circ C$, а при закачуванні охолоджувальної рідини зі швидкістю $v_2=0{,}1$ м/с – вода з температурою $t_2=80^\circ C$.
>
> **1)** Яку об’ємну частину складає крига в охолоджувальній рідині?
>
> **2)** При якій мінімальній швидкості прокачування система охолодження ще буде нормально працювати (тобто рідина не буде закипати усередині системи)?
>
> Для розрахунків прийняти: питома теплоємність води дорівнює $C=4200\ \text{Дж/(кг}\cdot\text{К)}$, питома теплота плавлення льоду $\lambda=3{,}3\cdot10^5\ \text{Дж/кг}$, відношення густини льоду до густини води $\rho_\text{л}/\rho_\text{в}=0{,}9$. Під терміном «об’ємна частина льоду» слід розуміти частку об’єму льоду в об’ємі охолоджувальної рідини, тобто відношення об’єму льоду до об’єму охолоджувальної рідини.
