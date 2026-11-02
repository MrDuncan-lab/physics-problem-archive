---
id: rompho-2012-intl-theory-t2
olympiad: RomPhO
year: 2012
stage: "Международная олимпиада"
round: теория
grade: ""
number: "T2"
title: "Колебания упругих тел"
aliases: ["Колебания упругих тел"]
topics: ["[[1.15 Упругость. Весомая пружина]]", "[[1.20 Колебания]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Исследовать малые продольные, радиальные, сдвиговые и крутильные колебания упругих тел и определить их периоды и моды."
status: "проверено: сверка"
lang: ru
tags: [задача]
---

# 2. КОЛЕБАНИЯ УПРУГИХ ТЕЛ

**RomPhO 2012** · Международная олимпиада · теория · задача T2  
Источник: [[_pdf/RomPhO/RomPhO-2012-T2.pdf#page=1|условие, стр. 1–2]] · [[_pdf/RomPhO/RomPhO-2012-T2-solution.pdf#page=3|решение, стр. 3–6]]

Темы: [[1.15 Упругость. Весомая пружина]], [[1.20 Колебания]]

> [!abstract] Кратко (составлено моделью)
> Исследовать малые продольные, радиальные, сдвиговые и крутильные колебания упругих тел и определить их периоды и моды.

При решении данной задачи гравитационными эффектами следует пренебречь. Все объекты считайте однородными и изотропными, если не указано иное.

**A.** Тонкий упругий стержень защищён от изгиба. Его длина $L$, плотность $\rho$, и модуль Юнга $E$. Стержень слегка растянули за концы и отпустили. После этого в нём возникли свободные колебания.

**a.** Запишите выражение для кинетической энергии стержня как функцию времени, выразив её через массу $m$ стержня, длину $L$ и скорость изменения $\varepsilon$ (здесь $\varepsilon$ - относительное удлинение).

**b.** Запишите выражение для потенциальной упругой энергии как функцию времени, выразив её через $m$, $\rho$, $E$ и $\varepsilon$.

**c.** Покажите, что для стержня закон сохранения механической энергии приводит к характеристическому дифференциальному уравнению для незатухающих гармонических колебаний. Переходя к аналогии с точечной массой $m$, находящейся под действием силы $\sigma S$ ($\sigma$ – это напряжение, а $S$ – площадь поперечного сечения), укажите величину, которая играет роль координаты.

**d.** Запишите выражение для периода малых продольных колебаний стержня, выразив его через $L$, $\rho$ и $E$.

**B.** Рассмотрите упругую сферу радиуса $R$, изготовленную из того же материала, что и стержень, о котором шла речь выше. Пусть $\varepsilon$ – относительная деформация $\Delta R/R$. Сферу слегка радиально сжали и предоставили ей свободно колебаться.

**e.** Запишите выражение для механической энергии сферы как функцию времени, выразив её через $m$, $R$, $\rho$, $E$, $\varepsilon$ и скорость изменения $\varepsilon$ (здесь $\varepsilon$ - относительное удлинение).

**f.** Запишите выражение для периода малых радиальных колебаний сферы, выразив его через $R$, $\rho$ и $E$.

**C.** Рассмотрите тонкую упругую прямоугольную пластину, защищённую от изгиба. Пусть размеры пластины $L$ и $l$. Толщину пластины считайте постоянной. Результаты воздействия напряжений $\sigma_x$ и $\sigma_y$ на пластину не являются независимыми, в том смысле, что деформация в одном направлении приводит к деформации в другом направлении. В пределах применимости закона Гука это можно записать, как:
$$\begin{cases}\varepsilon_x=-\mu\frac{\sigma_y}{E}\\\varepsilon_y=-\mu\frac{\sigma_x}{E}\end{cases},$$
где безразмерный параметр $\mu$ (коэффициент Пуассона) примерно равен 0,3.

**g.** Выразите $\sigma_x$ и $\sigma_y$ через $\varepsilon_x$, $\varepsilon_y$, $E$ и $\mu$.

**h.** Запишите систему дифференциальных уравнений, описывающую движение точки массой $m$ в двух взаимно перпендикулярных направлениях, используя в качестве координат эквивалентные величины, определённые в пункте c.

**i.** Найдите возможные значения $\omega$ для которых решениями вышеупомянутой системы являются незатухающие гармонические колебания (моды):

$$\begin{cases}\varepsilon_x=A\sin\omega t\\\varepsilon_y=B\sin\omega t\end{cases}.$$
Выразите результаты в терминах $L$, $l$, $\rho$, $E$ и $\mu$.

**j.** В общем случае, решение вышеупомянутой системы уравнений является суперпозицией двух найденных мод. Для квадратной пластины ($L=l$) и малого коэффициента Пуассона ($\mu^2\ll1$), выразите период биений через $\mu$ и период $T_{long}$ продольных колебаний стержня той же длины.

**D.** Теперь, вместо сжатия, пластина испытывает деформацию сдвига вдоль одной из сторон под действием напряжения сдвига $\tau$ (см. рис.). Сдвиг определяется как $\tan\gamma\approx\gamma$, и законом Гука в виде:
$$\gamma=\frac1G\tau;\quad[\tau]_{SI}=[G]_{SI}=N/m^2,$$
где $G$ – *модуль сдвига*.

![[rompho-2012-t2-problems-p2-f1.svg]]

**k.** Выразите $G$ через $E$ и $\mu$.

**l.** Определите период малых сдвиговых колебаний пластины, выразив его через $L$, $\rho$ и $G$. Выразите тот же период через $\mu$ и период колебаний стержня той же длины, испытывающего продольные колебания $T_{long}$.

**E.** Стержень радиусом $R$ и длиной $L$, изготовленный из того же материала, подвергли небольшому скручиванию и предоставили совершать свободные крутильные колебания. Угол закручивания $\theta$ определяется как угол, на который скрутился стержень под действием приложенного крутильного напряжения. В этом случае закон Гука примет вид:
$$\theta=\frac1C M;\quad[C]_{SI}=[M]_{SI}=Nm,$$
где $C$ – *модуль скручивания*.

**m.** Определите период малых крутильных колебаний стержня, выразив его через $L$, $\rho$ и $G$.

**n.** Выразите модуль скручивания через $R$, $L$, $E$ и $\mu$.

> [!answer]- Ответ
> **a**
>
> $$
> E_{kin}=2\int_0^{L/2}\frac{dm\,v^2(x)}2=\int_0^{L/2}x^2\dot\varepsilon^2\frac{m\,dx}{L}=\left.\frac{m\dot\varepsilon^2}{L}\frac{x^3}{3}\right|_0^{L/2}=\frac{mL^2\dot\varepsilon^2}{24}
> $$
>
> **b**
>
> $$
> E_{pot}=\frac{mE\varepsilon^2}{2\rho}
> $$
>
> **c**
>
> $$
> m\left(\frac{L\varepsilon}{12}\right)^{\cdot\cdot}=-\sigma S\Rightarrow\ddot x_{equivalent}=\left(\frac{L\varepsilon}{12}\right)^{\cdot\cdot}
> $$
>
> **d**
>
> $$
> \frac{L^2}{12}\ddot\varepsilon+\frac E\rho\varepsilon=0\Rightarrow\omega^2=\frac{12E}{\rho L^2}\Rightarrow T_{long}=\pi L\sqrt{\frac\rho{3E}}
> $$
>
> **e**
>
> $$
> E_{mech}=\frac{3m}{2}\left(\frac{R^2\dot\varepsilon^2}{5}+\frac{E\varepsilon^2}{\rho}\right)=\text{constant}
> $$
>
> **f**
>
> $$
> \dot E=0\Rightarrow\frac{R^2\ddot\varepsilon\dot\varepsilon}{5}+\frac{E\varepsilon\dot\varepsilon}{\rho}=0\Rightarrow\omega^2=\frac{5E}{\rho R^2}\Rightarrow T_{radial}=2\pi R\sqrt{\frac\rho{5E}}
> $$
>
> **g**
>
> $$
> \begin{cases}\varepsilon_x=\frac{\sigma_x}{E}-\mu\frac{\sigma_y}{E}\\\varepsilon_y=\frac{\sigma_y}{E}-\mu\frac{\sigma_x}{E}\end{cases}\Rightarrow\begin{cases}\sigma_x=\frac{E(\varepsilon_x+\mu\varepsilon_y)}{1-\mu^2}\\\sigma_y=\frac{E(\varepsilon_y+\mu\varepsilon_x)}{1-\mu^2}\end{cases}
> $$
>
> **h**
>
> $$
> \begin{cases}m\ddot x_{equivalent}=-\sigma_x\frac VL\\m\ddot y_{equivalent}=-\sigma_y\frac Vl\end{cases}\Rightarrow\begin{cases}\frac{mL\ddot\varepsilon_x}{12}+\frac{E(\varepsilon_x+\mu\varepsilon_y)}{1-\mu^2}\frac VL=0\\\frac{ml\ddot\varepsilon_y}{12}+\frac{E(\varepsilon_y+\mu\varepsilon_x)}{1-\mu^2}\frac Vl=0\end{cases}
> $$
>
> **i**
>
> $$
> \omega_{1;2}=\sqrt{\frac{6E\left[L^2+l^2\pm\mu\sqrt{(L^2-l^2)^2+(2\mu Ll)^2}\right]}{\rho L^2l^2(1-\mu^2)}}
> $$
>
> **j**
>
> $$
> \Delta\omega=\sqrt{\frac{12E}{\rho L^2}}\left(\sqrt{\frac{1+\mu^2}{1-\mu^2}}-1\right)\approx\mu^2\sqrt{\frac{12E}{\rho L^2}}\Rightarrow T_{beats}=\frac{T_{long}}{\mu^2}
> $$
>
> **k**
>
> $$
> G=\frac E{2(1+\mu)}
> $$
>
> **l**
>
> $$
> T_{slant}=\pi L\sqrt{\frac\rho{3G}}=T_{long}\sqrt{2(1+\mu)}
> $$
>
> **m**
>
> $$
> T_{twist}=\pi L\sqrt{\frac\rho{3G}}
> $$
>
> **n**
>
> $$
> M=\frac{2\pi G\alpha}{L}\int_0^R x^3\,dx=\frac{2\pi GR^4\alpha}{4L}\Rightarrow C=\frac{\pi GR^4}{2L}=\frac{\pi ER^4}{4L(1+\mu)}
> $$

> [!solution]- Решение
> # PROBLEM No. 2
>
> **a.** 1p
>
> Consider an element $dx$ of the rod, placed at distance $x$ from the center of the rod. Its mass is $dm=mdx/L$ each. Let $2l$ be the length of the rod at some moment, and let $y$ be the corresponding length of the region $x$.
>
> Since the object is homogenous at all times,
> $$\frac yx=\frac l{L/2}$$
> Let $v$ be the velocity of the two ends of the rod at some moment.
> $$v=\frac{dl}{dt}=\frac{d(2l-L)}{2dt}=\frac{d\left(\frac{2l-L}{L}\right)}{\frac{2dt}{L}}=\frac{L\,d\varepsilon}{2dt}=\frac L2\dot\varepsilon$$
> The velocity of the element considered is
> $$v(x)=\frac{dy}{dt}=\frac{d\left(\frac{lx}{L/2}\right)}{dt}=\frac{x}{L/2}\frac{dl}{dt}=\frac{xv}{L/2}=\frac{2x}{L}\frac{L\dot\varepsilon}{2}=x\dot\varepsilon$$
> The kinetic energy of the rod is
>
> $$E_{kin}=2\int_0^{L/2}\frac{dm\,v^2(x)}2=\int_0^{L/2}x^2\dot\varepsilon^2\frac{m\,dx}{L}=\left.\frac{m\dot\varepsilon^2}{L}\frac{x^3}{3}\right|_0^{L/2}=\frac{mL^2\dot\varepsilon^2}{24}$$
>
> **b.** 0.5p
>
> Let $S$ be the cross section of the rod, and $V$ its volume. The elementary work done by the tensile force $\sigma S$ equals the increase in elastic potential energy.
> $$dE_{pot}=dW=F\,d(2l)=\sigma S\,d(2l-L)=E\varepsilon\frac VLd(2l-L)=\frac{mE}{\rho}\varepsilon\,d\varepsilon=d\left(\frac{mE}{2\rho}\varepsilon^2\right)\Rightarrow$$
>
> $$E_{pot}=\frac{mE\varepsilon^2}{2\rho}$$
>
> **c.** 0.5p
> $$E_{mech}=E_{kin}+E_{pot}=\frac{mL^2\dot\varepsilon^2}{24}+\frac{mE\varepsilon^2}{2\rho}=\text{constant}\Rightarrow\dot E_{mech}=\frac{mL^2\ddot\varepsilon\dot\varepsilon}{12}+\frac{mE\varepsilon\dot\varepsilon}{\rho}=0\Rightarrow$$
> $$\frac{mL^2\ddot\varepsilon}{12}+V\sigma=0$$
> Dividing by $L$ we get:
>
> $$m\left(\frac{L\varepsilon}{12}\right)^{\cdot\cdot}=-\sigma S\Rightarrow\ddot x_{equivalent}=\left(\frac{L\varepsilon}{12}\right)^{\cdot\cdot}$$
>
> **d.** 0.5p
>
> Dividing also by $m$ we get:
>
> $$\frac{L^2}{12}\ddot\varepsilon+\frac E\rho\varepsilon=0\Rightarrow\omega^2=\frac{12E}{\rho L^2}\Rightarrow T_{long}=\pi L\sqrt{\frac\rho{3E}}$$
>
> **e.** 0.5p
>
> Consider very thin spherical layers of radius $x$ and thickness $dx$. Their masses are:
> $$dm=m\frac{4\pi x^2dx}{\frac{4\pi R^3}{3}}=\frac{3m}{R^3}x^2\,dx$$
> Let $r$ be the radius of the sphere and $v$ the velocity of its surface at some moment. The argument goes similarly as in section A.
> $$v=R\dot\varepsilon\Rightarrow v(x)=x\dot\varepsilon\Rightarrow dE_{kin}=\frac{dm\,v^2(x)}2=\frac{3mx^2\,dx}{R^3}\frac{x^2\dot\varepsilon^2}{2}\Rightarrow E_{kin}=\frac{3mR^2\dot\varepsilon^2}{10}$$
> $$dE_{pot}=dW=\sigma S\,dr=\varepsilon E4\pi R^2R\,d\varepsilon=\frac{3EV\,d(\varepsilon^2)}2=d\left(\frac{3mE}{2\rho}\varepsilon^2\right)$$
>
> $$E_{mech}=\frac{3m}{2}\left(\frac{R^2\dot\varepsilon^2}{5}+\frac{E\varepsilon^2}{\rho}\right)=\text{constant}$$
>
> **f.** 0.5p
>
> $$\dot E=0\Rightarrow\frac{R^2\ddot\varepsilon\dot\varepsilon}{5}+\frac{E\varepsilon\dot\varepsilon}{\rho}=0\Rightarrow\omega^2=\frac{5E}{\rho R^2}\Rightarrow T_{radial}=2\pi R\sqrt{\frac\rho{5E}}$$
>
> **g.** 0.5p
>
> $$\begin{cases}\varepsilon_x=\frac{\sigma_x}{E}-\mu\frac{\sigma_y}{E}\\\varepsilon_y=\frac{\sigma_y}{E}-\mu\frac{\sigma_x}{E}\end{cases}\Rightarrow\begin{cases}\sigma_x=\frac{E(\varepsilon_x+\mu\varepsilon_y)}{1-\mu^2}\\\sigma_y=\frac{E(\varepsilon_y+\mu\varepsilon_x)}{1-\mu^2}\end{cases}$$
>
> **h.** 0.5p
>
> $$\begin{cases}m\ddot x_{equivalent}=-\sigma_x\frac VL\\m\ddot y_{equivalent}=-\sigma_y\frac Vl\end{cases}\Rightarrow\begin{cases}\frac{mL\ddot\varepsilon_x}{12}+\frac{E(\varepsilon_x+\mu\varepsilon_y)}{1-\mu^2}\frac VL=0\\\frac{ml\ddot\varepsilon_y}{12}+\frac{E(\varepsilon_y+\mu\varepsilon_x)}{1-\mu^2}\frac Vl=0\end{cases}$$
>
> **i.** 1.5p
>
> By replacing the sought solutions into the system of equations we get
> $$\begin{cases}-\frac{\omega^2AL^2}{12}+\frac{E(A+\mu B)}{\rho(1-\mu^2)}=0\\-\frac{\omega^2Bl^2}{12}+\frac{E(B+\mu A)}{\rho(1-\mu^2)}=0\end{cases}$$
> By dividing the two equations term by term we get a simpler one:
> $$\frac{AL^2}{Bl^2}=\frac{A+\mu B}{B+\mu A}$$
> Let us denote the ratio of the two amplitudes by $r$.
>
> $$r\frac{L^2}{l^2}=\frac{r+\mu}{1+r\mu}\Rightarrow\mu L^2r^2+(L^2-l^2)r-\mu l^2=0\Rightarrow$$
> $$r_{1;2}=\frac{-(L^2-l^2)\pm\sqrt{(L^2-l^2)^2+4\mu^2L^2l^2}}{2\mu L^2}$$
> Returning $r$ in the second equation we get:
>
> $$\omega^2=\frac{12E}{\rho l^2(1-\mu^2)}\left[1+\mu\frac{-(L^2-l^2)\pm\sqrt{(L^2-l^2)^2+4\mu^2L^2l^2}}{2\mu L^2}\right]\Rightarrow$$
>
> $$\omega_{1;2}=\sqrt{\frac{6E\left[L^2+l^2\pm\mu\sqrt{(L^2-l^2)^2+(2\mu Ll)^2}\right]}{\rho L^2l^2(1-\mu^2)}}$$
>
> **j.** 0.5p
>
> $$L=l\Rightarrow\omega_{1;2}=\sqrt{\frac{6E(2L^2\pm2\mu^2L^2)}{\rho L^4(1-\mu^2)}}=\sqrt{\frac{12E(1\pm\mu^2)}{\rho L^2(1-\mu^2)}}$$
>
> $$\Delta\omega=\sqrt{\frac{12E}{\rho L^2}}\left(\sqrt{\frac{1+\mu^2}{1-\mu^2}}-1\right)\approx\mu^2\sqrt{\frac{12E}{\rho L^2}}\Rightarrow T_{beats}=\frac{T_{long}}{\mu^2}$$
>
> **k.** 1.5p
>
> Let $d$ be the thickness of the plate. The shear force $\tau ld$ can be decomposed into a stretching component along $L$ (x-axis) and a shrinking component along $l$ (y-axis).
>
> ![[rompho-2012-t2-solutions-p5-c5553.png]]
> $$\sigma_x=\frac{\tau ld\sin\gamma}{ld};\quad\sigma_y=\frac{\tau ld\cos\gamma}{(L/\cos\gamma)d}\Rightarrow$$
> $$\varepsilon_x=\frac{\tau\sin\gamma}{E}-\mu\left(-\frac{\tau l\cos^2\gamma}{LE}\right)$$
> $$\varepsilon_y=-\frac{\tau l\cos^2\gamma}{LE}-\mu\frac{\tau\sin\gamma}{E}$$
> But
> $$\varepsilon_x=\frac{\frac L{\cos\gamma}-L}{L}=\frac{1-\cos\gamma}{\cos\gamma};\quad\varepsilon_y=\frac{l\cos\gamma-l}{l}=-(1-\cos\gamma)\Rightarrow$$
> $$\begin{cases}\frac E\tau\frac{1-\cos\gamma}{\cos\gamma}=\sin\gamma+\mu\frac lL\cos^2\gamma\\\frac E\tau(1-\cos\gamma)=\frac lL\cos^2\gamma+\mu\sin\gamma\end{cases}$$
> Multiplying the second equation by $\mu$ and subtracting it from the first one we get:
> $$\frac E\tau(1-\cos\gamma)\left(\frac1{\cos\gamma}-\mu\right)=\sin\gamma(1-\mu^2)\Rightarrow\frac{E\gamma^2}{2\tau}(1-\mu)\approx\gamma(1-\mu^2)\Rightarrow\gamma=\frac{2\tau(1+\mu)}E$$
>
> $$G=\frac E{2(1+\mu)}$$
>
> **l.** 0.5p
>
> The quantities involved in the shear deformation are absolutely analogous to those describing the longitudinal deformation.
>
> $$T_{slant}=\pi L\sqrt{\frac\rho{3G}}=T_{long}\sqrt{2(1+\mu)}$$
>
> **m.** 0.5p
>
> Consider very thin cylindrical layers of radius $x$ and thickness $dx$. When the cylinder is twisting, each one of them is subject to a very small shear.
>
> $$T_{twist}=\pi L\sqrt{\frac\rho{3G}}$$
>
> **n.** 1p
>
> Let $\alpha$ be a very small angle with which one cap of the cylinder rotates with respect to the other. Then the slanting angle of a cylindrical layer is:
> $$x\alpha=L\gamma\Rightarrow\gamma=\frac xL\alpha$$
> The corresponding shear stress is
> $$\tau=G\frac xL\alpha$$
> The elementary shear force acting on the cap is
> $$dF=\tau\,dS=G\frac xL\alpha2\pi x\,dx$$
> The corresponding elementary torque is
> $$dM=dF\cdot x=\frac{2\pi G\alpha x^3\,dx}{L}$$
>
> $$M=\frac{2\pi G\alpha}{L}\int_0^R x^3\,dx=\frac{2\pi GR^4\alpha}{4L}\Rightarrow C=\frac{\pi GR^4}{2L}=\frac{\pi ER^4}{4L(1+\mu)}$$
