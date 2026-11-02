---
id: belpho-2014-final-theory-11-3
olympiad: BelPhO
year: 2014
stage: "Заключительный этап"
round: теория
grade: 11
number: "11-3"
title: "Переменная диэлектрическая проницаемость · Переменная проводимость"
aliases: ["Переменная диэлектрическая проницаемость · Переменная проводимость"]
topics: ["[[3.8 Сложный конденсатор]]", "[[3.7 Дифференциальный закон Ома]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Найти ёмкость, сопротивление и распределения зарядов в слоистых материалах с переменной диэлектрической проницаемостью и проводимостью."
status: "проверено: сверка, два чтения + арбитр; решение — проверено: сверка, два чтения совпали, два чтения + арбитр"
lang: ru
tags: [задача]
---

# Задача 11-3

**BelPhO 2014** · Заключительный этап · теория · 11 класс · задача 11-3  
Источник: [[_pdf/BelPhO/2014-final-theoretical-problems.pdf#page=16|условие, стр. 16–17]] · [[_pdf/BelPhO/2014-final-theoretical-solutions.pdf#page=30|решение, стр. 30–34]]

Темы: [[3.8 Сложный конденсатор]], [[3.7 Дифференциальный закон Ома]]

> [!abstract] Кратко (составлено моделью)
> Найти ёмкость, сопротивление и распределения зарядов в слоистых материалах с переменной диэлектрической проницаемостью и проводимостью.

С развитием технологий появляются все новые материалы с удивительными свойствами. Два таких метаматериала рассматриваются в данной задаче.

**Часть 1. Переменная диэлектрическая проницаемость.**

**1.1.1** Плоский конденсатор состоит из двух металлических параллельных пластин площади $S$, находящимися на расстоянии $h$ друг от друга. Пространство между пластинами заполнено двумя слоями диэлектрика (толщины этих слоев одинаковы) с диэлектрическими проницаемостями $\varepsilon_1$ и $\varepsilon_2$. Найдите емкость такого конденсатора.

![[belpho-2014-final-theory-problems-p16-f1.png]]

**1.1.2** На внешние металлические пластины подают постоянное напряжение $U_0$. Найдите поверхностные плотности зарядов на пластинах $\sigma_0$ и на границе раздела диэлектриков $\sigma'$

**1.2** Плоский конденсатор состоит из двух металлических параллельных пластин площади $S$, находящимися на расстоянии $h$ друг от друга. Пространство между пластинами заполнено диэлектриком, проницаемость которого плавно изменяется от $\varepsilon_1$ у левой пластины до $\varepsilon_2$ у правой. Закон изменения проницаемости от координаты $x$ имеет вид

$$\varepsilon=(ax+b)^{-1}.$$

![[belpho-2014-final-theory-problems-p17-f1.png]]

**1.2.1** Выразите параметры этой зависимости через значения $\varepsilon_1$ и $\varepsilon_2$.

**1.2.2** Найдите емкость этого конденсатора.

**1.2.3** На внешние металлические пластины подают постоянное напряжение $U_0$. При этом внутри диэлектрика возникают объемные поляризационные заряды. Найдите их объемную плотность как функцию координаты $x$ $\rho(x)$

**Часть 2. Переменная проводимость.**

**2.1.1** Плоский резистор состоит из двух металлических параллельных пластин площади $S$, находящимися на расстоянии $h$ друг от друга. Пространство между пластинами заполнено двумя слоями слабо проводящих веществ (толщины этих слоев одинаковы) с удельными сопротивлениями $\rho_1$ и $\rho_2$. Найдите сопротивление такого резистора.

![[belpho-2014-final-theory-problems-p17-f2.png]]

**2.1.2** На внешние металлические пластины подают постоянное напряжение $U_0$. Найдите поверхностную плотность заряда $\sigma'$ на границе раздела слоев. Поляризационными зарядами пренебречь.

**2.2.1** Плоский резистор состоит из двух металлических параллельных пластин площади $S$, находящимися на расстоянии $h$ друг от друга. Пространство между пластинами заполнено веществом, удельное сопротивление которого плавно изменяется от $\rho_1$ у левой пластины до $\rho_2$ у правой по линейному закону.

**1.2.1** Запишите формулу, описывающую изменение удельного сопротивления вещества.

**1.2.2** Найдите сопротивление этого резистора.

**1.2.3** На внешние металлические пластины подают постоянное напряжение $U_0$. При этом внутри вещества возникают объемные заряды. Найдите их объемную плотность как функцию координаты $x$.

> [!answer]- Ответ
> **1.1.1**
>
> $$
> \frac1C=\frac{h}{2\varepsilon_1\varepsilon_0 S}+\frac{h}{2\varepsilon_2\varepsilon_0 S}=\frac{h}{2\varepsilon_0 S}\frac{\varepsilon_1+\varepsilon_2}{\varepsilon_1\varepsilon_2}\quad\Rightarrow\quad C=\frac{2\varepsilon_0 S}{h}\frac{\varepsilon_1\varepsilon_2}{\varepsilon_1+\varepsilon_2}.
> $$
>
> **1.1.2**
>
> $$
> \sigma_0=\varepsilon_0 U_0\frac2h\frac{\varepsilon_1\varepsilon_2}{\varepsilon_1+\varepsilon_2}.
> $$
>
> **1.1.2**
>
> $$
> \frac{E_0}{\varepsilon_2}-\frac{E_0}{\varepsilon_1}=\frac{\sigma'}{\varepsilon_0}\quad\Rightarrow\quad\sigma'=\frac{\varepsilon_1-\varepsilon_2}{\varepsilon_1+\varepsilon_2}\frac{2\varepsilon_0}{h}U_0
> $$
>
> **1.2.1**
>
> $$
> \begin{cases}\dfrac1{\varepsilon_1}=b\\\dfrac1{\varepsilon_2}=ah+b\end{cases}\quad\Rightarrow\quad\begin{cases}b=\dfrac1{\varepsilon_1}\\a=\dfrac1h\dfrac{\varepsilon_1-\varepsilon_2}{\varepsilon_1\varepsilon_2}\end{cases}
> $$
>
> **1.2.2**
>
> $$
> C=2\frac{\varepsilon_0 S}{h}\frac{\varepsilon_1\varepsilon_2}{\varepsilon_1+\varepsilon_2}.
> $$
>
> **1.2.3**
>
> $$
> \rho(x)=\varepsilon_0\frac{\Delta E}{\Delta x}=2\varepsilon_0\frac{U_0}{h}\frac{\varepsilon_1\varepsilon_2}{\varepsilon_1+\varepsilon_2}\frac{\Delta\varepsilon^{-1}(x)}{\Delta x}=2\varepsilon_0\frac{U_0}{h^2}\frac{\varepsilon_1-\varepsilon_2}{\varepsilon_1+\varepsilon_2}.
> $$
>
> **2.1.1**
>
> $$
> R=\rho_1\frac{h}{2S}+\rho_2\frac{h}{2S}=\frac{\rho_1+\rho_2}{2}\frac hS.
> $$
>
> **2.1.2**
>
> $$
> \sigma'=2\varepsilon_0 E\frac{U_0}{h}\frac{\rho_2-\rho_1}{\rho_2+\rho_1}.
> $$
>
> **2.2.1**
>
> $$
> \rho(x)=\rho_1+\frac{\rho_2-\rho_1}{h}x.
> $$
>
> **2.2.3**
>
> $$
> \gamma(x)=\varepsilon_0\frac{\Delta E}{\Delta x}=\varepsilon_0j\frac{\Delta\rho}{\Delta x}=\varepsilon_0\frac{2U_0}{h(\rho_1+\rho_2)}\frac{\rho_2-\rho_1}{h}=\frac{2\varepsilon_0 U_0}{h^2}\frac{\rho_2-\rho_1}{\rho_1+\rho_2}.
> $$

> [!solution]- Решение
> **Задача 11-3**
>
> **Часть 1. Переменная диэлектрическая проницаемость.**
>
> **1.1.1** Описанную систему можно рассматривать как два конденсатора, соединенных последовательно. Используя формулу для электроемкости плоского конденсатора, запишем емкость составного конденсатора
>
> $$\frac1C=\frac{h}{2\varepsilon_1\varepsilon_0 S}+\frac{h}{2\varepsilon_2\varepsilon_0 S}=\frac{h}{2\varepsilon_0 S}\frac{\varepsilon_1+\varepsilon_2}{\varepsilon_1\varepsilon_2}\quad\Rightarrow\quad C=\frac{2\varepsilon_0 S}{h}\frac{\varepsilon_1\varepsilon_2}{\varepsilon_1+\varepsilon_2}. \tag{1}$$
>
> **1.1.2** При помещении диэлектрика во внешнее поле на нем возникают поляризационные заряды, которые изменяют поле внутри диэлектрика. Если силовые линии поля перпендикулярны границам диэлектрика, то напряженность поля внутри диэлектрика оказывается в $\varepsilon$ раз меньше.
>
> ![[belpho-2014-final-theory-solutions-p30-f2.png]]
>
> Обозначим напряженность поля, создаваемого только зарядами на пластинах $\vec E_0$, модуль которой связан с поверхностной плотностью зарядов на пластинах соотношением
>
> $$\sigma_0=\varepsilon_0 E_0. \tag{2}$$
>
> Тогда напряженности полей внутри диэлектриков будут равны $\vec E_1=\frac{\vec E_0}{\varepsilon_1}$, $\vec E_2=\frac{\vec E_0}{\varepsilon_2}$. Разность потенциалов между пластинами (напряжение) может быть выражена через напряженности полей следующим образом
>
> $$U_0=E_1\frac h2+E_2\frac h2=\frac{E_0}{\varepsilon_1}\frac h2+\frac{E_0}{\varepsilon_2}\frac h2=E_0\frac h2\frac{\varepsilon_1+\varepsilon_2}{\varepsilon_1\varepsilon_2}. \tag{3}$$
>
> Откуда следует, что
>
> $$E_0=U_0\frac2h\frac{\varepsilon_1\varepsilon_2}{\varepsilon_1+\varepsilon_2}. \tag{4}$$
>
> А поверхностная плотность зарядов на пластинах
>
> $$\sigma_0=\varepsilon_0 U_0\frac2h\frac{\varepsilon_1\varepsilon_2}{\varepsilon_1+\varepsilon_2}. \tag{5}$$
>
> *Впрочем, эта формула может быть получена непосредственно из формулы (1), как $q=CU_0$.*
>
> Поверхностная плотность поляризационных зарядов на границе диэлектриков $\sigma'$ может быть найдена различными способами.
>
> **Способ 1.** Представим поля внутри диэлектриков как суперпозицию поля $E'=\frac{\sigma'}{2\varepsilon_0}$, создаваемого зарядами $\sigma'$ и поля $\vec E_e$, создаваемого всеми остальными зарядами (на пластинах и поляризационных зарядов на границах диэлектриков, примыкающих к пластинам). В этом случае напряженности полей внутри диэлектриков описываются формулами
>
> ![[belpho-2014-final-theory-solutions-p31-f1.png]]
>
> $$\begin{aligned}E_1&=\frac{E_0}{\varepsilon_1}=E_e-\frac{\sigma'}{2\varepsilon_0}\\ E_2&=\frac{E_0}{\varepsilon_2}=E_e+\frac{\sigma'}{2\varepsilon_0}.\end{aligned} \tag{6}$$
>
> Из этих формул следует
>
> $$\frac{E_0}{\varepsilon_2}-\frac{E_0}{\varepsilon_1}=\frac{\sigma'}{2\varepsilon_0}\quad\Rightarrow\quad\sigma'=\varepsilon_0\frac{\varepsilon_1-\varepsilon_2}{\varepsilon_1\varepsilon_2}E_0 \tag{7}$$
>
> Подставляя выражение (4), окончательно получим
>
> $$\frac{E_0}{\varepsilon_2}-\frac{E_0}{\varepsilon_1}=\frac{\sigma'}{\varepsilon_0}\quad\Rightarrow\quad\sigma'=\frac{\varepsilon_1-\varepsilon_2}{\varepsilon_1+\varepsilon_2}\frac{2\varepsilon_0}{h}U_0 \tag{8}$$
>
> **Способ 2.** Поле внутри диэлектрика $\vec E_1=\frac{\vec E_0}{\varepsilon_1}$ может быть представлено как сумма внешнего поля $\vec E_0$ и поля $E'_1=\frac{\sigma'_1}{\varepsilon_0}$, создаваемого поляризационными зарядами:
>
> ![[belpho-2014-final-theory-solutions-p31-f2.png]]
>
> $$\frac{E_0}{\varepsilon_1}=E_0-\frac{\sigma'_1}{\varepsilon_0}. \tag{9}$$
>
> Откуда находим
>
> $$\sigma'_1=\varepsilon_0\frac{\varepsilon_1-1}{\varepsilon_1}E_0. \tag{10}$$
>
> Поверхностная плотность зарядов на втором диэлектрике описывается аналогичной формулой. Суммарная плотность заряда на границе равна $\sigma'=\sigma'_1-\sigma'_2=\varepsilon_0 E_0\frac{\varepsilon_1-\varepsilon_2}{\varepsilon_1\varepsilon_2}$, что совпадает с формулой (7).
>
> **Способ 3.** Используем теорему Гаусса для поверхности изображенной на рисунке.
>
> ![[belpho-2014-final-theory-solutions-p32-f1.png]]
>
> $$E_2s-E_2s=\frac{\sigma's}{\varepsilon_0}.$$
>
> Из этой формулы следует $\sigma'=\varepsilon_0\left(\frac{E_0}{\varepsilon_2}-\frac{E_0}{\varepsilon_1}\right)$, что приводит, как это не странно, к тому же результату (10).
>
> **1.2** Решение этой части задачи, в принципе, аналогично решению предыдущей части.
>
> **1.2.1** Сначала выразим параметры зависимости диэлектрической проницаемости от координаты
>
> $$\varepsilon(x)=\frac1{ax+b} \tag{11}$$
>
> через граничные значения. Для этого запишем и решим систему уравнений
>
> ![[belpho-2014-final-theory-solutions-p32-f2.png]]
>
> $$\begin{cases}\dfrac1{\varepsilon_1}=b\\\dfrac1{\varepsilon_2}=ah+b\end{cases}\quad\Rightarrow\quad\begin{cases}b=\dfrac1{\varepsilon_1}\\a=\dfrac1h\dfrac{\varepsilon_1-\varepsilon_2}{\varepsilon_1\varepsilon_2}\end{cases} \tag{12}$$
>
> **1.2.2** Для расчета емкости конденсатора представим его как совокупность последовательно соединенных конденсаторов малой толщины $\Delta x_i$, емкости которых равны
>
> ![[belpho-2014-final-theory-solutions-p32-f3.png]]
>
> $$C_i=\frac{\varepsilon(x)\varepsilon_0 S}{\Delta x_i}. \tag{13}$$
>
> При последовательном соединении суммарная емкость рассчитывается по формуле
>
> $$\frac1C=\sum_i\frac1{C_i}=\sum_i\frac1{\varepsilon(x)\varepsilon_0 S}\Delta x_i=\frac1{\varepsilon_0 S}\sum_i\frac{\Delta x_i}{\varepsilon(x)}. \tag{14}$$
>
> При малых $\Delta x_i$ сумма в выражении (14) равна площади под графиком зависимости $\varepsilon^{-1}(x)$. Так как эта зависимость линейна, то в результате суммирования получим
>
> $$\frac1C=\frac1{\varepsilon_0 S}\sum_i\frac{\Delta x_i}{\varepsilon(x)}=\frac1{\varepsilon_0 S}\frac h2(\varepsilon_1^{-1}+\varepsilon_2^{-1})=\frac1{\varepsilon_0 S}\frac h2\frac{\varepsilon_1+\varepsilon_2}{\varepsilon_1\varepsilon_2}.$$
>
> Тогда емкость конденсатора оказывается равной
>
> $$C=2\frac{\varepsilon_0 S}{h}\frac{\varepsilon_1\varepsilon_2}{\varepsilon_1+\varepsilon_2}. \tag{15}$$
>
> Для расчета объемной плотности поляризационных зарядов запишем выражение для напряженности электрического поля
>
> $$E(x)=\varepsilon^{-1}(x)E_0, \tag{16}$$
>
> где $E_0$ - как и ранее напряженность поля создаваемого только зарядами на пластинах. Разность потенциалов между пластинами в данном случае определяется формулой
>
> $$U_0=\sum_i E(x)\Delta x_i=E_0\sum_i\varepsilon^{-1}(x)\Delta x_i. \tag{17}$$
>
> Эту сумму мы уже вычисляли, поэтому сразу запишем
>
> $$U_0=E_0\sum_i\varepsilon^{-1}(x)\Delta x_i=E_0\frac h2\frac{\varepsilon_1+\varepsilon_2}{\varepsilon_1\varepsilon_2}\quad\Rightarrow\quad E_0=2\frac{U_0}{h}\frac{\varepsilon_1\varepsilon_2}{\varepsilon_1+\varepsilon_2}. \tag{18}$$
>
> Таким образом, зависимость напряженности от координаты имеет вид
>
> $$E(x)=\frac{E_0}{\varepsilon(x)}=2\frac{U_0}{h}\frac{\varepsilon_1\varepsilon_2}{\varepsilon_1+\varepsilon_2}\varepsilon^{-1}(x). \tag{19}$$
>
> Для расчета зависимости плотности заряда от координаты воспользуемся самым коротким способом, основанном на теореме Гаусса (хотя приемлем и любой из ранее рассмотренных). Так для тонкого цилиндра толщиной $\Delta x$, основания которого параллельны пластинам, имеем:
>
> ![[belpho-2014-final-theory-solutions-p33-f1.png]]
>
> $$E(x+\Delta x)s-E(x)s=\frac{\rho(x)\Delta x}{\varepsilon_0}. \tag{20}$$
>
> Из этой формулы следует, что
>
> $$\rho(x)=\varepsilon_0\frac{\Delta E}{\Delta x}=2\varepsilon_0\frac{U_0}{h}\frac{\varepsilon_1\varepsilon_2}{\varepsilon_1+\varepsilon_2}\frac{\Delta\varepsilon^{-1}(x)}{\Delta x}=2\varepsilon_0\frac{U_0}{h}\frac{\varepsilon_1\varepsilon_2}{\varepsilon_1+\varepsilon_2}a,$$
>
> где $a$ - коэффициент, найденный ранее (формула (12)). С учетом этой формулы получим
>
> $$\rho(x)=\varepsilon_0\frac{\Delta E}{\Delta x}=2\varepsilon_0\frac{U_0}{h}\frac{\varepsilon_1\varepsilon_2}{\varepsilon_1+\varepsilon_2}\frac{\Delta\varepsilon^{-1}(x)}{\Delta x}=2\varepsilon_0\frac{U_0}{h^2}\frac{\varepsilon_1-\varepsilon_2}{\varepsilon_1+\varepsilon_2}. \tag{21}$$
>
> Отметим, что объемная плотность поляризационных зарядов постоянна по объему диэлектрика.
>
> **Часть 2. Переменная проводимость.**
>
> **2.1.1** Сопротивление резистора найдем как сумму двух последовательно соединенных резисторов
>
> $$R=\rho_1\frac{h}{2S}+\rho_2\frac{h}{2S}=\frac{\rho_1+\rho_2}{2}\frac hS. \tag{22}$$
>
> **2.1.2** Поясним причину возникновения заряда в этом случае. При включении внешнего поля плотности токов будут различными, что приведет к накоплению зарядов на границе раздела. Эти заряды будут изменять плотности токов в разных материалах до тех пор, пока плотности токов не сравняются. Итак, в установившемся режиме будет выполняться условие
>
> ![[belpho-2014-final-theory-solutions-p33-f2.png]]
>
> $$j_1=j_2\quad\Rightarrow\quad\frac{E_1}{\rho_1}=\frac{E_2}{\rho_2} \tag{23}$$
>
> Как уже было отмечено, различия в напряженностях полей обусловлены полем, создаваемым зарядами на границе, поэтому
>
> $$E_1=E_0-\frac{\sigma'}{2\varepsilon_0},\quad E_2=E_0+\frac{\sigma'}{2\varepsilon_0}.$$
>
> Здесь $E_0$ - напряженность поля, создаваемого всеми зарядами, кроме зарядов на границе. Из уравнений (23)-(24) найдем
>
> $$\frac1{\rho_1}\left(E_0-\frac{\sigma'}{2\varepsilon_0}\right)=\frac1{\rho_2}\left(E_0+\frac{\sigma'}{2\varepsilon_0}\right)\quad\Rightarrow\quad\sigma'=2\varepsilon_0 E_0\frac{\rho_2-\rho_1}{\rho_2+\rho_1} \tag{24}$$
>
> Из формул (24) и определения напряжения следует, что величина $E_0$ может быть легко найдена
>
> $$U_0=E_1\frac h2+E_1\frac h2=E_0h\quad\Rightarrow\quad E_0=\frac{U_0}{h} \tag{25}$$
>
> Поэтому поверхностная плотность зарядов на границе равна
>
> $$\sigma'=2\varepsilon_0 E\frac{U_0}{h}\frac{\rho_2-\rho_1}{\rho_2+\rho_1}. \tag{26}$$
>
> **2.2** Основная идея решения этой части заключается в постоянстве плотности тока, т.е.
>
> $$j=\frac E\rho=const. \tag{27}$$
>
> Поэтому напряженность поля внутри проводника изменяется по закону
>
> $$E(x)=j\rho(x) \tag{28}$$
>
> Зависимость удельного сопротивления от координаты линейна, с учетом значений на границе эта зависимость имеет вид
>
> $$\rho(x)=\rho_1+\frac{\rho_2-\rho_1}{h}x. \tag{29}$$
>
> Для определения плотности тока запишем выражение для напряжения между пластинами резистора
>
> $$U_0=\sum_i E(x)\Delta x=\sum_i j\rho(x)\Delta x=j\frac{\rho_1+\rho_2}{2}h. \tag{30}$$
>
> из которого выразим
>
> $$j=\frac{2U_0}{h(\rho_1+\rho_2)}. \tag{31}$$
>
> Ранее было получено, что плотность² заряда определяется формулой $\gamma(x)=\varepsilon_0\frac{\Delta E}{\Delta x}$. Используя эту формулу, а также выражения (28), (29), (31), найдем
>
> $$\gamma(x)=\varepsilon_0\frac{\Delta E}{\Delta x}=\varepsilon_0j\frac{\Delta\rho}{\Delta x}=\varepsilon_0\frac{2U_0}{h(\rho_1+\rho_2)}\frac{\rho_2-\rho_1}{h}=\frac{2\varepsilon_0 U_0}{h^2}\frac{\rho_2-\rho_1}{\rho_1+\rho_2}. \tag{32}$$
>
> Как и в первой части, объемная плотность заряда оказалась постоянной.
>
> **Последнее замечание.** Вторую часть задачи можно было и не решать! В первой части расчет электрического поля сводился к решению системы уравнений
>
> $$E(x)=\varepsilon^{-1}(x)E_0=(ax+b)E_0,\qquad \sum_i E(x)\Delta x=U_0,$$
>
> А во второй
>
> $$E(x)=\rho(x)j=(ax+b)j,\qquad \sum_i E(x)\Delta x=U_0,$$
>
> Эти системы уравнений полностью совпадают, если $E_0$ заменить на $j$, $\varepsilon^{-1}$ заменить на $\rho$. Достаточно было просто переписать формулы с учетом этих замен!
>
> ² Чтобы не путать с удельным электрическим сопротивлением, обозначим плотность заряда $\gamma$.
