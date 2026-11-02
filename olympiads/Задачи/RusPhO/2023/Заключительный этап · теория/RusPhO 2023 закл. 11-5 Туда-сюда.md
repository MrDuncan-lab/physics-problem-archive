---
id: ruspho-2023-final-theory-11-5
olympiad: RusPhO
year: 2023
stage: "Заключительный этап"
round: теория
grade: 11
number: "11-5"
title: "Туда-сюда"
aliases: ["Туда-сюда"]
topics: ["[[1 Механика]]", "[[1.6 Векторная кинематика]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Для шайбы с трением на наклонной доске определить ускорения, скорости в характерных точках и время возвращения к основанию."
status: "проверено: сверка, два чтения + арбитр"
lang: ru
tags: [задача]
---

# Задача №5. Туда-сюда

**RusPhO 2023** · Заключительный этап · теория · 11 класс · задача 11-5  
Источник: [[_pdf/RusPhO/2023-final-theor.pdf#page=12|условие, стр. 12–13]] · [[_pdf/RusPhO/2023-final-theor.pdf#page=54|решение, стр. 54–58]]

Темы: [[1 Механика]], [[1.6 Векторная кинематика]]

> [!abstract] Кратко (составлено моделью)
> Для шайбы с трением на наклонной доске определить ускорения, скорости в характерных точках и время возвращения к основанию.

На плоской доске, образующей с горизонтом угол $\alpha=30{,}0^\circ$, находится маленькая шайба. Коэффициент трения между шайбой и доской равен $\mu=\operatorname{tg}\alpha$. Вблизи основания доски шайбе сообщают скорость $v_0=8{,}00\ \text{м/с}$, и она движется по доске, пока снова не достигнет основания. Основание доски горизонтально. Известно, что в моменты старта и повторного достижения основания доски вектор скорости шайбы образовывал углы $\varphi_0=60{,}0^\circ$ и

![[ruspho-2023-final-theory-p12-f2.svg]]

$\varphi_1=159{,}3^\circ$ соответственно с положительным направлением оси $y$, направленной вверх по доске (см. рис). Ускорение свободного падения $g=9{,}80\ \text{м/с}^2$. Шайба не вращается.

*Примечание:* Ответ на каждый из вопросов задачи должен быть как рассчитан, так и выражен аналитически через заданные в условии величины!

**1.** Определите ускорения шайбы $a_0$ и $a_1$ в момент старта и прямо перед повторным достижением основания доски соответственно.

**2.** Определите скорости шайбы $u$ и $v_1$ в верхней точке траектории и прямо перед повторным достижением основания доски соответственно.

**3.** Определите время $t$, через которое шайба повторно достигает основания доски.

> [!answer]- Ответ
> **1**
>
> $$
> a_0=2g\sin\alpha\cos(\varphi_0/2)\approx8.49\text{ м/с}^2,
> $$
>
> **1**
>
> $$
> a_1=2g\sin\alpha\cos(\varphi_1/2)\approx1.76\text{ м/с}^2.
> $$
>
> **2**
>
> $$
> u=v_0(1-\cos\varphi_0)\approx4{,}00\text{ м/с},
> $$
>
> **2**
>
> $$
> v_1=\frac{v_0(1-\cos\varphi_0)}{1-\cos\varphi_1}\approx2{,}07\text{ м/с}.
> $$
>
> **3**
>
> $$
> t=\frac{v_0}{2g\sin\alpha(1-\cos\varphi_0)}\left(1-\left(\frac{1-\cos\varphi_0}{1-\cos\varphi_1}\right)^2\right)\approx1{,}52\text{ с}
> $$
>
> **3**
>
> $$
> t=\frac{v_0(1-\cos\varphi_0)}{2g\sin\alpha}\left(\frac1{1-\cos\varphi_0}-\frac1{1-\cos\varphi_1}+\ln\left(\frac{\tan(\varphi_1/2)}{\tan(\varphi_1/2)}\right)\right)\approx1{,}52\text{ с}.
> $$

> [!solution]- Решение
> # Задача №11-Т5. Туда-сюда
>
> **1.** Пусть $m$ – масса шайбы. В плоскости доски на шайбу действуют компонента силы тяжести $mg\sin\alpha$, а также сила трения $F_\text{тр}=\mu mg\cos\alpha$, причём поскольку $\mu=\tan\alpha$:
>
> $$
> F_\text{тр}=mg\sin\alpha.
> $$
>
> ![[ruspho-2023-final-theory-p54-c5242.png]]
>
> Изобразим на рисунке компоненту силы тяжести и силу трения, соответствующие углу $\varphi$ между направлением скорости шайбы и осью $y$. Из него следует, что равнодействующая $R$ компоненты силы тяжести и силы трения равна:
>
> $$
> R=2mg\sin\alpha\cos(\varphi/2).
> $$
>
> Тогда для ускорений $a_0$ и $a_1$ имеем:
>
> $$
> a_0=2g\sin\alpha\cos(\varphi_0/2)\approx8.49\text{ м/с}^2,
> $$
>
> $$
> a_1=2g\sin\alpha\cos(\varphi_1/2)\approx1.76\text{ м/с}^2.
> $$
>
> **2. Первое решение:**
>
> Равнодействующая компоненты силы тяжести и силы трения направлена вдоль биссектрисы угла $\varphi$ между направлением скорости и осью $y$ – тангенциальное ускорение шайбы и проекция её ускорения на ось $y$ равны друг другу, $a_\tau=a_y$, поэтому:
>
> $$
> v-v_y=v(1-\cos\varphi)=const=v_0(1-\cos\varphi_0).
> $$
>
> **Второе решение:**
>
> Запишем выражение для тангенциальной и нормальной компонент ускорения:
>
> $$
> a_\tau=\dot v=-g\sin\alpha(1+\cos\varphi),\qquad a_n=v\dot\varphi=g\sin\alpha\sin\varphi.
> $$
>
> Отсюда:
>
> $$
> \frac{\dot v}{v\dot\varphi}=-\frac{1+\cos\varphi}{\sin\varphi}=-\frac1{\tan(\varphi/2)}.
> $$
>
> Разделим переменные и получим:
>
> $$
> \frac{dv}{v}=-\frac{d\varphi}{\tan(\varphi/2)}.
> $$
>
> Проинтегрируем полученное выражение ($\theta=\varphi/2$):
>
> $$
> \int_{v_0}^v\frac{dv}{v}=\ln\left(\frac v{v_0}\right)=-\int_{\varphi_0}^\varphi\frac{d\varphi}{\tan(\varphi/2)}=-2\int_{\varphi_0/2}^{\varphi/2}\frac{\cos\theta\,d\theta}{\sin\theta}=-2\ln\left(\frac{\sin(\varphi/2)}{\sin(\varphi_0/2)}\right).
> $$
>
> Избавляясь от логарифма, получим:
>
> $$
> \frac v{v_0}=\frac{\sin^2(\varphi_0/2)}{\sin^2(\varphi/2)},\qquad v(\varphi)=\frac{v_0(1-\cos\varphi_0)}{1-\cos\varphi}.
> $$
>
> Поскольку в верхней точке траектории $\varphi=90^\circ$, для скоростей $u$ и $v_1$ имеем:
>
> $$
> u=v_0(1-\cos\varphi_0)\approx4{,}00\text{ м/с},
> $$
>
> $$
> v_1=\frac{v_0(1-\cos\varphi_0)}{1-\cos\varphi_1}\approx2{,}07\text{ м/с}.
> $$
>
> **3. Первое решение:**
>
> Обратим внимание, что из найденного во втором пункте инварианта следует:
>
> $$
> v-v_y=v_0(1-\cos\varphi_0).
> $$
>
> Интегрируя по времени, получим
>
> $$
> S-\Delta y=v_0(1-\cos\varphi_0)t,
> $$
>
> где $\Delta y$ и $S$ – изменение координаты $y$ мела и пройденный им путь соответственно. К моменту достижения шайбой основания доски $\Delta y=0$, поэтому:
>
> $$
> S=v_0(1-\cos\varphi_0)t.
> $$
>
> Для определения пути $S$ воспользуемся законом изменения кинетической энергии:
>
> $$
> \Delta E_k=\frac{mv^2}{2}-\frac{mv_0^2}{2}=A_\text{тяж}+A_\text{тр}=-mg\sin\alpha\Delta y-mg\sin\alpha S.
> $$
>
> Поскольку при достижении основания доски $\Delta y=0$:
>
> $$
> v_0^2-v_1^2=2g\sin\alpha S=2g\sin\alpha v_0(1-\cos\varphi_0)t,
> $$
>
> откуда:
>
> $$
> t=\frac{v_0}{2g\sin\alpha(1-\cos\varphi_0)}\left(1-\left(\frac{1-\cos\varphi_0}{1-\cos\varphi_1}\right)^2\right)\approx1{,}52\text{ с}
> $$
>
> **Второе решение:**
>
> С учётом полученной зависимости $v(\varphi)$, время $t$ можно определить, например, из уравнения для нормальной компоненты ускорения шайбы:
>
> $$
> v\dot\varphi=g\sin\alpha\sin\varphi\Rightarrow dt=\frac{v\,d\varphi}{g\sin\alpha\sin\varphi}=\frac{v_0(1-\cos\varphi_0)}{g\sin\alpha}\cdot\frac{d\varphi}{(1-\cos\varphi)\sin\varphi}.
> $$
>
> Перейдём к переменной половинного угла:
>
> $$
> dt=\frac{v_0(1-\cos\varphi_0)}{g\sin\alpha}\cdot\frac{d\varphi}{4\sin^3(\varphi/2)\cos(\varphi/2)}.
> $$
>
> Воспользуемся стандартной тригонометрической подстановкой $z=\tan(\varphi/2)$. Тогда получим:
>
> $$
> \sin(\varphi/2)=\frac z{\sqrt{1+z^2}},\qquad\cos(\varphi/2)=\frac1{\sqrt{1+z^2}}.
> $$
>
> Свяжем $d\varphi$ и $dz$:
>
> $$
> dz=d\tan(\varphi/2)=\frac1{\cos^2(\varphi/2)}\cdot\frac{d\varphi}{2}=(1+\tan^2(\varphi/2))\cdot\frac{d\varphi}{2},\qquad d\varphi=\frac{2\,dz}{1+z^2}.
> $$
>
> Отсюда имеем:
>
> $$
> dt=\frac{v_0(1-\cos\varphi_0)}{g\sin\alpha}\cdot\frac{(1+z^2)^2}{4z^3}\cdot\frac{2\,dz}{1+z^2}.
> $$
>
> Вводя переменные $z_0=\tan(\varphi_0/2)$ и $z_1=\tan(\varphi_1/2)$, для времени $t$ получим:
>
> $$
> t=\frac{v_0(1-\cos\varphi_0)}{2g\sin\alpha}\int_{z_0}^{z_1}\frac{1+z^2}{z^3}\,dz=\frac{v_0(1-\cos\varphi_0)}{2g\sin\alpha}\left(\int_{z_0}^{z_1}\frac{dz}{z^3}+\int_{z_0}^{z_1}\frac{dz}{z}\right).
> $$
>
> Интегрируя, находим:
>
> $$
> t=\frac{v_0(1-\cos\varphi_0)}{2g\sin\alpha}\left(\frac1{2z_0^2}-\frac1{2z_1^2}+\ln\left(\frac{z_1}{z_0}\right)\right).
> $$
>
> Возвращаясь к исходным переменным, для времени $t$ находим:
>
> $$
> t=\frac{v_0(1-\cos\varphi_0)}{2g\sin\alpha}\left(\frac1{1-\cos\varphi_0}-\frac1{1-\cos\varphi_1}+\ln\left(\frac{\tan(\varphi_1/2)}{\tan(\varphi_1/2)}\right)\right)\approx1{,}52\text{ с}.
> $$
>
> *Примечание 1:* Вообще говоря, задача является переопределённой, поскольку значение $\varphi_1$ однозначно определяется значением $\varphi_0$, однако в такой формулировке задача становится слишком сложной. Участникам олимпиады было достаточно получить лишь одно уравнение, связывающее $\varphi_1$ и $t$. Без заданного значения $\varphi_1$ решение третьего пункта задачи требует комбинации первого и второго изложенных решений. Численное значение $\varphi_1=159.3^\circ$ можно найти, приравняв два выражения для $t$ и численно решив полученное уравнение:
>
> $$
> \frac1{(1-\cos\varphi_0)^2}-\frac1{(1-\cos\varphi_1)^2}=\frac1{1-\cos\varphi_0}-\frac1{1-\cos\varphi_1}+\ln\left(\frac{\tan(\varphi_1/2)}{\tan(\varphi_0/2)}\right).
> $$
>
> *Примечание 2:* Из комбинации двух решений также получаются явные зависимости перемещения $\Delta y$ и пути $S$ от угла $\varphi$:
>
> $$
> \Delta y(\varphi)=\frac{v_0^2(1-\cos\varphi_0)^2}{4g\sin^2\alpha}\left(\frac{\cos\varphi_0}{(1-\cos\varphi_0)^2}-\frac{\cos\varphi}{(1-\cos\varphi)^2}-\ln\left(\frac{\tan(\varphi/2)}{\tan(\varphi_0/2)}\right)\right),
> $$
>
> $$
> S(\varphi)=\frac{v_0^2(1-\cos\varphi_0)^2}{4g\sin^2\alpha}\left(\frac{2-\cos\varphi_0}{(1-\cos\varphi_0)^2}-\frac{2-\cos\varphi}{(1-\cos\varphi)^2}+\ln\left(\frac{\tan(\varphi/2)}{\tan(\varphi_0/2)}\right)\right).
> $$
>
> Помимо этого, мы можем определить зависимость перемещения вдоль оси $x$, направленной вдоль основания наклонной плоскости, от угла $\varphi$:
>
> $$
> dx=v\sin\varphi\,dt=v\sin\varphi\cdot\frac{d\varphi}{\dot\varphi}=\frac{v^2\,d\varphi}{g\sin\alpha}=\frac{v_0^2(1-\cos\varphi_0)^2}{g\sin\alpha}\cdot\frac{d\varphi}{(1-\cos\varphi)^2}.
> $$
>
> Вновь переходя к переменной $z=\tan(\varphi/2)$, получим:
>
> $$
> \Delta x(z)=\frac{v_0^2(1-\cos\varphi_0)^2}{2g\sin\alpha}\int_{z_0}^z\frac{(1+z^2)^2}{z^4}\cdot\frac{dz}{1+z^2}=\frac{v_0^2(1-\cos\varphi_0)^2}{2g\sin\alpha}\left(\int_{z_0}^z\frac{dz}{z^4}+\int_{z_0}^z\frac{dz}{z^2}\right).
> $$
>
> Интегрируя, находим:
>
> $$
> \Delta x(z)=\frac{v_0^2(1-\cos\varphi_0)^2}{2g\sin\alpha}\left(\frac1{3z_0^3}-\frac1{3z^3}+\frac1{z_0}-\frac1z\right).
> $$
>
> Возвращаясь к переменной $\varphi$:
>
> $$
> \Delta x(\varphi)=\frac{v_0^2(1-\cos\varphi_0)^2}{2g\sin\alpha}\left(\frac1{3\tan^3(\varphi_0/2)}-\frac1{3\tan^3(\varphi/2)}+\frac1{\tan(\varphi_0/2)}-\frac1{\tan(\varphi/2)}\right).
> $$
>
> Таким образом, траектория шайбы может быть получена аналитически в параметрической форме, поскольку $\Delta y(\varphi)$ и $\Delta x(\varphi)$ являются известными аналитическими функциями.
>
> Траектория для заданных значений $v_0$, $\varphi_0$, $\alpha$ и $g$ представлена на рисунке ниже.
>
> ![[ruspho-2023-final-theory-p58-c1065.png]]
