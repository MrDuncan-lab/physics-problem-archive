---
id: rompho-2012-intl-theory-t1
olympiad: RomPhO
year: 2012
stage: "Международная олимпиада"
round: теория
grade: ""
number: "T1"
title: "Магнитостатика"
aliases: ["Магнитостатика"]
topics: ["[[4 Магнетизм]]", "[[4.2 Сила Ампера]]", "[[1.20 Колебания]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Найти магнитные поля различных распределений тока, давление на проводящую плоскость и период колебаний стержня с током."
status: "проверено: сверка"
lang: ru
tags: [задача]
---

# 1. МАГНИТОСТАТИКА

**RomPhO 2012** · Международная олимпиада · теория · задача T1  
Источник: [[_pdf/RomPhO/RomPhO-2012-T1.pdf#page=1|условие, стр. 1–2]] · [[_pdf/RomPhO/RomPhO-2012-T1-solution.pdf#page=3|решение, стр. 3–5]]

Темы: [[4 Магнетизм]], [[4.2 Сила Ампера]], [[1.20 Колебания]]

> [!abstract] Кратко (составлено моделью)
> Найти магнитные поля различных распределений тока, давление на проводящую плоскость и период колебаний стержня с током.

Магнитодвижущую силу (МДС) можно определить как интеграл вдоль пути проекции вектора магнитной индукции $B$,
$$\int_{\text{curve}}\vec B\,d\vec l.$$
Согласно теореме о циркуляции МДС вдоль замкнутой кривой пропорциональна электрическому току сквозь любую поверхность, натянутую на данную кривую. Коэффициент пропорциональности называется магнитной постоянной ($\mu_0$).
$$\oint_{\text{loop}}\vec B\,d\vec l=\mu_0 I_{\text{across}}$$
Положительному направлению тока соответствует обход кривой *по часовой стрелке*.

**a.** Вдоль бесконечно длинного прямого проводника течёт ток $I$. Найдите величину и направление магнитной индукции $B$, создаваемой этим током в зависимости от расстояния $r$ от проводника. Выразите результат через $I$, $r$ и $\mu_0$.

**b.** Тонкий однородный стержень массой $m$ и длиной $L$ расположен параллельно проводнику на расстоянии $d$. Это стержень может вращаться только вокруг оси, перпендикулярной плоскости проходящей через проводник и середину стержня. Вдоль стержня течёт постоянный ток $I'$ в направлении, противоположном $I$. Стержень отклоняют на небольшой угол от положения равновесия и он начинает свободно колебаться. Определите период $T_{\text{slant}}$ малых колебаний и выразите его через $I$, $I'$, $m$, $L$, $d$ и $\mu_0$.

**c.** Система представляет собой полубесконечный прямолинейный провод, переходящий в бесконечную коническую поверхность, ось которой совпадает с осью проводника (см. рис.). По системе течёт постоянный ток $I$. Определите величину и направление магнитной индукции $B$ на расстоянии $r$ от оси как внутри ($B_{\mathrm{IN}}(r)$), так и вне ($B_{\mathrm{OUT}}(r)$) конической поверхности. Выразите результат через $I$, $r$ и $\mu_0$.

![[rompho-2012-t1-problems-p1-f1.svg]]

**d.** Система представляет собой полубесконечный прямолинейный провод, примыкающий к бесконечной проводящей плоскости, перпендикулярной проводу. По системе течёт постоянный ток $I$. Определите величину и направление магнитной индукции $B$ на расстоянии $r$ от оси провода по обе стороны от проводящей плоскости. Выразите результат через $I$, $r$ и $\mu_0$.

**e.** Определим линейную плотность тока $\vec J$, текущего по плоскости как:
$$J\overset{\mathrm{def}}=\frac{dI}{dl},$$
где $dl$ – элементарная длина, взятая вдоль направления перпендикулярного направлению элементарного тока $dI$.

Введём единичный вектор $\vec n$, перпендикулярный плоскости, чтобы задать положительное направление пересечения плоскости. Векторное произведение

$\vec J\times\vec n$ определяет положительное направление компоненты $B$, параллельной плоскости.

Покажите, что при пересечении плоскости разница значений компоненты $B$ (параллельной плоскости) пропорциональна значению $J$ в точке пересечения. Найдите этот коэффициент пропорциональности.

**f.** Бесконечная проводящая плоскость параллельна однородному магнитному полю. Магнитная индукция $B$ с обеих сторон плоскости имеет одинаковое направление, но разные значения $B_1$ и $B_2$. Определите давление, действующее на плоскость. Выразите результат через $B_1$, $B_2$ и $\mu_0$.

**g.** Проводящая полая сфера соединяется на своих полюсах с двумя полубесконечными прямыми проводниками, направленными вдоль полярной оси. По системе течёт постоянный ток $I$. Определите величину и направление магнитной индукции $B$ на расстоянии $r$ от полярной оси как внутри, так и вне сферы. Выразите результат через $I$, $r$ и $\mu_0$.

**h.** Полюса проводящей полой сферы соединены прямолинейным проводом, находящимся внутри сферы. Постоянный ток $I$ течёт по поверхности сферы от одного полюса к другому и затем назад по проводу. Определите величину и направление магнитной индукции $B$ на расстоянии $r$ от полярной оси как внутри, так и вне сферы. Выразите результат через $I$, $r$ и $\mu_0$.

По закону Био-Савара магнитная индукция, создаваемая током, текущим по элементарному пути длиной $dl$, определяется как:
$$d\vec B=\frac{\mu_0 I(d\vec l\times\vec r)}{4\pi r^3},$$
где $r$ – расстояние от элементарного тока до данной точки.

**i.** По прямому проводу длиной $L$ течёт постоянный ток $I$. Точка наблюдения находится в плоскости, проходящей через середину этого провода и перпендикулярной ему. Из этой точки провод виден под углом $2\alpha$. Определите величину магнитной индукции $B$ в этой точке. Выразите результат через $L$, $I$, $\alpha$ и $\mu_0$.

**j.** Постоянный ток $I$ течёт по поверхности проводящей сферы радиуса $R$ от одного полюса к другому. Определите величину и направление магнитной индукции $B$ в экваториальной плоскости сферы в точке на расстоянии $r$ от полярной оси как внутри, так и вне сферы. Выразите результат через $I$, $R$, $r$ и $\mu_0$.

> [!answer]- Ответ
> **a**
>
> $$
> \oint\vec B\,d\vec l=2\pi rB=\mu_0I\Rightarrow B=\frac{\mu_0I}{2\pi r}
> $$
>
> **b**
>
> $$
> M=\int_0^{L/2}-\frac{\mu_0II'\alpha x^2dx}{\pi d^2}=-\frac{\mu_0II'\alpha L^3}{24\pi d^2}=\frac{mL^2}{12}\ddot\alpha\Rightarrow T_{\mathrm{slant}}=2\pi d\sqrt{\frac{2\pi m}{\mu_0II'L}}
> $$
>
> **c**
>
> $$
> B_{\mathrm{IN}}=0
> $$
>
> **c**
>
> $$
> B_{\mathrm{OUT}}=\frac{\mu_0I}{2\pi r}
> $$
>
> **d**
>
> $$
> B_{\mathrm{WIRE\ SIDE}}=\frac{\mu_0I}{2\pi r}
> $$
>
> **d**
>
> $$
> B_{\mathrm{OTHER\ SIDE}}=0
> $$
>
> **e**
>
> $$
> \Delta B_{\parallel}=B_{\parallel\mathrm{OTHER\ SIDE}}-B_{\parallel\mathrm{WIRE\ SIDE}}=0-\left(-\frac{\mu_0I}{2\pi r}\right)=\mu_0J
> $$
>
> **f**
>
> $$
> dF=dI\cdot da\cdot B_0=J\cdot db\cdot da\frac{B_1+B_2}2=\frac{B_2-B_1}{\mu_0}dS\frac{B_1+B_2}2\Rightarrow p=\frac{dF}{dS}=\frac{B_2^2-B_1^2}{2\mu_0}
> $$
>
> **g**
>
> $$
> B_{\mathrm{IN}}=0
> $$
>
> **g**
>
> $$
> B_{\mathrm{OUT}}=\frac{\mu_0I}{2\pi r}
> $$
>
> **h**
>
> $$
> B_{\mathrm{IN}}=\frac{\mu_0I}{2\pi r}
> $$
>
> **h**
>
> $$
> B_{\mathrm{OUT}}=0
> $$
>
> **i**
>
> $$
> B=2\int_0^\alpha\frac{\mu_0I}{4\pi d}\cos\beta\,d\beta=\left.\frac{\mu_0I}{2\pi d}\sin\beta\right|_0^\alpha=\frac{\mu_0I}{\pi L}\frac{\sin^2\alpha}{\cos\alpha}
> $$
>
> **j**
>
> $$
> B_{\mathrm{OUT}}(r)=\frac{\mu_0I}{2\pi}\frac Rr\frac1{\sqrt{r^2+R^2}}
> $$
>
> **j**
>
> $$
> B_{\mathrm{IN}}(r)=\frac{\mu_0I}{2\pi r}\left(1-\frac R{\sqrt{r^2+R^2}}\right)
> $$

> [!solution]- Решение
> PROBLEM No. 1
>
> **a.** 1p
> From the symmetry of the situation we take the magnetomotive force along a circular path of radius r, centered on the wire.
> ![[rompho-2012-t1-solutions-p3-f1.svg]]
>
> $$\oint\vec B\,d\vec l=2\pi rB=\mu_0I\Rightarrow B=\frac{\mu_0I}{2\pi r}$$
>
> **b.** 1.5p
> Consider two elements $dx$ of the rod placed symmetrically at distances $x$ from its center. The corresponding forces acting on them are:
> ![[rompho-2012-t1-solutions-p3-f2.svg]]
> $$dF'=\frac{\mu_0II'\,dx}{2\pi(d-x\sin\alpha)}$$
> $$dF''=\frac{\mu_0II'\,dx}{2\pi(d+x\sin\alpha)}$$
> The sum of their torques is:
> $$dM=(dF''-dF')x=-\frac{2\mu_0II'x^2\sin\alpha\,dx}{2\pi(d^2-x^2\sin^2\alpha)}$$
> For very small angles, the total torque is:
>
> $$M=\int_0^{L/2}-\frac{\mu_0II'\alpha x^2dx}{\pi d^2}=-\frac{\mu_0II'\alpha L^3}{24\pi d^2}=\frac{mL^2}{12}\ddot\alpha\Rightarrow T_{\mathrm{slant}}=2\pi d\sqrt{\frac{2\pi m}{\mu_0II'L}}$$
>
> **c.** 1p
> Taking path integrals along circular field lines exactly like at the first point, we get:
> ![[rompho-2012-t1-solutions-p3-f3.svg]]
>
> $$B_{\mathrm{IN}}=0$$
>
> $$B_{\mathrm{OUT}}=\frac{\mu_0I}{2\pi r}$$
>
> **d.** 0.5p
> The above argument keeps holding, and the results are:
> ![[rompho-2012-t1-solutions-p3-f4.svg]]
>
> $$B_{\mathrm{WIRE\ SIDE}}=\frac{\mu_0I}{2\pi r}$$
>
> $$B_{\mathrm{OTHER\ SIDE}}=0$$
>
> **e.** 1p
> $$J(r)=\frac I{2\pi r}$$
>
> $$\Delta B_{\parallel}=B_{\parallel\mathrm{OTHER\ SIDE}}-B_{\parallel\mathrm{WIRE\ SIDE}}=0-\left(-\frac{\mu_0I}{2\pi r}\right)=\mu_0J$$
>
> **f.** 1.5p
> Consider a small region of the plane having dimensions $da$ along $J$ and $db$ across $J$.
>
> ![[rompho-2012-t1-solutions-p4-c6012.png]]
> $$J=\frac{B_2-B_1}{\mu_0}$$
> Let $B_0$ be the external magnetic field and $B'$ the field generated by the conducting plane.
> $$\left.\begin{aligned}B_1&=B_0-B'\\B_2&=B_0+B'\end{aligned}\right\}\Rightarrow B_0=\frac{B_1+B_2}2$$
>
> $$dF=dI\cdot da\cdot B_0=J\cdot db\cdot da\frac{B_1+B_2}2=\frac{B_2-B_1}{\mu_0}dS\frac{B_1+B_2}2\Rightarrow p=\frac{dF}{dS}=\frac{B_2^2-B_1^2}{2\mu_0}$$
>
> **g.** 0.5p
> Just as before,
>
> $$B_{\mathrm{IN}}=0$$
>
> $$B_{\mathrm{OUT}}=\frac{\mu_0I}{2\pi r}$$
>
> **h.** 1p
> This time the path integrals go the other way around.
>
> $$B_{\mathrm{IN}}=\frac{\mu_0I}{2\pi r}$$
>
> $$B_{\mathrm{OUT}}=0$$
>
> **i.** 1p
> Consider two elements $dl$ of the wire, placed symmetrically at a distance $l$ from the center of the wire. Their contributions to the magnetic field in the mediator plane are equal:
>
> ![[rompho-2012-t1-solutions-p4-c6257.png]]
> $$|d\vec B|=\frac{\mu_0I\,dl\sin(90^\circ-\beta)}{4\pi r^2}=\frac{\mu_0I\,dl}{4\pi d^2}\cos^3\beta$$
> $$l=d\tan\beta\Rightarrow dl=\frac d{\cos^2\beta}d\beta\Rightarrow|d\vec B|=\frac{\mu_0I}{4\pi d}\cos\beta\,d\beta$$
>
> $$B=2\int_0^\alpha\frac{\mu_0I}{4\pi d}\cos\beta\,d\beta=\left.\frac{\mu_0I}{2\pi d}\sin\beta\right|_0^\alpha=\frac{\mu_0I}{\pi L}\frac{\sin^2\alpha}{\cos\alpha}$$
>
> **j.** 1p
> From a point in the equatorial plane, the axis of the poles of the sphere is seen under an angle $2\alpha$, with $\tan\alpha=R/r$.
> ![[rompho-2012-t1-solutions-p4-f3.svg]]
> Outside, the sphere behaves similarly to an electric current flowing directly from one pole to the other through a wire connecting the poles directly:
>
> $$B_{\mathrm{OUT}}(r)=\frac{\mu_0I}{2\pi}\frac Rr\frac1{\sqrt{r^2+R^2}}$$
> Inside, the sphere behaves similarly to two semi-infinite straight conductors connecting the two poles of the sphere and carrying the current $I$ in the opposite direction:
>
> $$B_{\mathrm{IN}}(r)=\frac{\mu_0I}{2\pi r}\left(1-\frac R{\sqrt{r^2+R^2}}\right)$$
