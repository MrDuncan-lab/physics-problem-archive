---
id: rompho-2013-intl-theory-t1
olympiad: RomPhO
year: 2013
stage: "Международная олимпиада"
round: теория
grade: ""
number: "T1"
title: "Fred & Barney's car"
points: 10
aliases: ["Fred & Barney's car"]
topics: ["[[1.7 Качение твёрдого тела]]", "[[1.17 Законы сохранения энергии и импульса]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: true
source_damaged: false
summary: "Исследовать движение автомобиля с квадратными колёсами: форму дороги, энергию, допустимые скорости и столкновение с препятствием."
status: "проверено: сверка; решение — проверено: сверка, два чтения + арбитр"
lang: en
tags: [задача]
---

# Theoretical Problem No. 1 (10 points)

**RomPhO 2013** · Международная олимпиада · теория · задача T1  
Источник: [[_pdf/RomPhO/RomPhO-2013-T1.pdf#page=1|условие, стр. 1–2]] · [[_pdf/RomPhO/RomPhO-2013-T1-solution.pdf#page=2|решение, стр. 2–8]] · [[_pdf/RomPhO/RomPhO-2013-T1-solution.pdf#page=9|критерии, стр. 9]]

Темы: [[1.7 Качение твёрдого тела]], [[1.17 Законы сохранения энергии и импульса]]

> [!abstract] Кратко (составлено моделью)
> Исследовать движение автомобиля с квадратными колёсами: форму дороги, энергию, допустимые скорости и столкновение с препятствием.

## Fred & Barney's car

Fred and Barney built a car having as "wheels" two identical square prisms (figure 1). The wheels are perfectly suited to the road's shape (that is a periodical repetition of identical bumps), so that the center of mass of the car does not move vertically during the trip. The wheels never slip on the road. During the car's motion, the wheel's long edge always touches a „valley” of the road; road „heights” are reached by a line passing through the half of a rectangular face of the "wheels". The vehicle's movement starts in the tops of two road bumps. Initially, the horizontal translational velocity is $\vec v_0$.

![[rompho-2013-t1-problems-p1-f1.png]]
*Figure 1*

The total weight of the vehicle excluding its „wheels” is $M\cdot\vec g$, distributed equally on the two wheel axles. Further, assume that the only forces acting on car are gravity and normal force.

**Task No. 1 - Kinetic energy of the car**

**1.a.** Determine the expression of J - the moment of inertia of wheel reported at its own axles if its mass is $m$ and the length of its square side is $2a$. (1,00p)

**1.b.** Determine the expression of kinetic energy of the car and the expression of the angular velocity of its wheels:

**i.** when the car pass on the tops of the bumps; (1,00p)

**ii.** when the car pass with each wheel through a „valley”. (1,00p)

**Task No. 2 - Road's shape**

In the figure 2 is shown the motion of the lower side of the square cross-section of the wheel on a bump (the curve passing through the points $x_s,T,x_d$).

![[rompho-2013-t1-problems-p1-c1762.png]]
*Figure 2*

The road is a periodic repetition of such a bump.

The $Ox$ axis of the coordinate system passes through valleys of the relief and the $Oy$ axis passes through bump tip. *AB is wheels side, T is the contact point between wheel and road and G is wheel axis position – in initial position. A'B', T', G' have the same meaning – but for a certain position.* In cross-section the wheel axis is always on the same vertical line with the contact point between wheel and road.

**2.a.** Give an explanation for this finding. (0,50p)

**2.b.** Determine the analytical form $y=y(x)$ of cross-section of the road. (2,00p)

Hint: The derivative $y'(x)$ of the function $y=y(x)$ is the slope of the tangent to the graph of function in $x$. Consider known that $\int\frac{dx}{\sqrt{x^2-a^2}}=\ln|x+\sqrt{x^2-a^2}|+C$. We recommend to use the notation $ch(x)=\frac{e^x+e^{-x}}2$; $sh(x)=\frac{e^x-e^{-x}}2$ with property $ch^2(x)-sh^2(x)=1$

**2.c.** Determine the expression of the length (on horizontal) of a bump of road. (0,50p)

**2.d.** Determine the expression of minimum distance between wheel axles Fred's car. (0,50p)

**2.e.** Decide whether a machine wheeled regular hexagonal prism conveniently chosen could run on the road whose form was determined in 2.b., without vertical displacement of the center of mass of the wheel. Give a short explanation. (0,50p)

**Task No. 3 - Accident**

Assuming that analytical expression of road’s bumps is $y=k-h\cdot ch(x/a)$ where $k$ and $h$ are two constants.

**3.a.** Determine the domain of possible values of the horizontal velocity of the car, under the circumstances established in problem’s statement. (2,00p)

**3.b.** Determines how the amount of heat that can be released by plastic collision of Fred's car with an obstacle depends on position of obstacle on road. Immediately after the collision the car stops. Give a short explanation. (0,50p)

**3.c.** Determine the expression of heat released by collision. (0,50p)

© The Problem is proposed by:
Delia DAVIDESCU, PhD
Adrian DAFINEI, PhD

> [!answer]- Ответ
> **1.a**
>
> $$
> \begin{cases}J=\frac{m}{4a^2L}\cdot L\cdot\int_{-a}^{a}\left(\int_{-a}^{a}(x^2+y^2)dy\right)dx=\frac{m}{4a^2}\int_{-a}^a\left(\int_{-a}^a(x^2+y^2)dy\right)dx=\frac{m}{4a^2}\cdot\frac{8a^4}{3}\\J=\frac{2a^2\cdot m}{3}\end{cases}
> $$
>
> **1.b.i**
>
> $$
> \omega_T=\frac{v_0}{a}
> $$
>
> **1.b.i**
>
> $$
> T_0=v_0^2\cdot\left(\frac M2+m+\frac{2m}{3}\right)=v_0^2\cdot\frac{3M+10m}{6}
> $$
>
> **1.b.ii**
>
> $$
> \omega_v=\frac{v_0}{a}\cdot\sqrt{\frac{3M+10m}{6M+16m}}
> $$
>
> **2.b**
>
> $$
> y=a(\sqrt2-ch(x/a))
> $$
>
> **2.c**
>
> $$
> 2d=|x_d-x_s|=2a\cdot\ln(\sqrt2+1)
> $$
>
> **2.d**
>
> $$
> d_{min}=4a\cdot\ln(\sqrt2+1)
> $$
>
> **3.a**
>
> $$
> v_{G'}(d)=\frac{v_0\cdot\sqrt{3M+10m}}{\sqrt{3M+8m}}>v_0
> $$
>
> **3.c**
>
> $$
> Q=v_0^2\cdot\left(\frac{3M+10m}{6}\right)
> $$

> [!solution]- Решение
> **Sarcina de lucru nr. 1 - Energia cinetică a maşinii - Soluţie**
>
> **1.a.** Densitatea materialului roţii presupusă de lungime $L$ este
> $$\rho=\frac{m}{4a^2\cdot L}\tag{1}$$
> Considerând o prismă elementară cu laturile $(L,dx,dy)$, momentul de inerţie elementar, al acestei prisme faţă de axul propriu al „roţii” este
> $$dJ=\rho\iint r^2\cdot L\cdot dx\cdot dy\tag{2}$$
> cu
>
> $$r^2=x^2+y^2\tag{3}$$
>
> ![[rompho-2013-t1-solutions-p3-f2.png]]
> *Figura 3- Determinarea momentului de inerţie*
>
> Deoarece
> $$\int_{-a}^a(x^2+y^2)dy=\left.\left(x^2\cdot y+\frac{y^3}{3}\right)\right|_{-a}^a=2a\cdot x^2+2\frac{a^3}{3}\tag{4}$$
> rezultă
> $$\int_{-a}^a\left(2a\cdot x^2+2\frac{a^3}{3}\right)dx=\left.\left(2a\cdot\frac{x^3}{3}+2\frac{a^3}{3}\cdot x\right)\right|_{-a}^a=\frac{4a^4}{3}+\frac{4a^4}{3}=\frac{8a^4}{3}\tag{5}$$
> momentul de inerţie al roţii are expresia
>
> $$\begin{cases}J=\frac{m}{4a^2L}\cdot L\cdot\int_{-a}^{a}\left(\int_{-a}^{a}(x^2+y^2)dy\right)dx=\frac{m}{4a^2}\int_{-a}^a\left(\int_{-a}^a(x^2+y^2)dy\right)dx=\frac{m}{4a^2}\cdot\frac{8a^4}{3}\\J=\frac{2a^2\cdot m}{3}\end{cases}\tag{6}$$
> Expresia din relaţia (6) reprezintă răspunsul la sarcina de lucru 1.a.
>
> **1.b.** În momentele în care roata maşinii este „în vârf” sau „în vale” viteza de translaţie a axului de rotire $v(t)$ - (care este şi viteza de translaţie a automobilului) - şi raza instantanee de giraţie $r(t)$ sunt perpendiculare. Legătura cu viteza unghiulară instantanee $\omega(t)$ se face prin relaţia
> $$v(t)=r(t)\cdot\omega(t)\tag{7}$$
> **i.** Deoarece în punctul de plecare raza instantanee de giraţie este $a$, viteza unghiulară instantanee în acest punct, $\omega_T$, are expresia
>
> $$\omega_T=\frac{v_0}{a}\tag{8}$$
> Energia cinetică de translaţie $T_t$ este
> $$T_t=\frac{M+2m}{2}v^2\tag{9}$$
> iar energia cinetică de rotaţie $T_r$ în acelaşi punct are expresia
> $$T_r=2\frac J2\omega^2=J\omega^2=\frac{2a^2\cdot m}{3}\cdot\omega^2.\tag{10}$$
> Energia cinetică totală $T$ a maşinii este
>
> $$T=T_t+T_r=\frac{M+2m}{2}v^2+\frac{2a^2\cdot m}{3}\cdot\omega^2\tag{11}$$
> La momentul iniţial când $v=v_0$ şi $\omega_T=\frac{v_0}{a}$
>
> $$T_0=v_0^2\cdot\left(\frac M2+m+\frac{2m}{3}\right)=v_0^2\cdot\frac{3M+10m}{6}\tag{12}$$
> Expresiile din relaţiile (8) şi (12) reprezintă răspunsul la sarcina de lucru 1.b.i.
>
> **ii.** În vale, viteza de translaţie $v_v$ este legată cu viteza unghiulară instantanee prin relaţia
> $$\omega_v=\frac{v_v}{a\sqrt2};\quad v_v=\omega_v\cdot a\sqrt2\tag{13}$$
> Astfel, în punctul „din vale” energia cinetică totală are expresia
> $$T_v=\left(\frac{(M+2m)\cdot2a^2}{2}+\frac{2a^2\cdot m}{3}\right)\cdot\omega_v^2=\left(M+2m+\frac{2\cdot m}{3}\right)\cdot\omega_v^2\cdot a^2=\omega_v^2\cdot a^2\cdot\frac{3M+8m}{3}\tag{14}$$
> Energia potenţială a maşinii nu variază deoarece - conform enunţului - nu există deplasare pe verticală a centrului de masă. Întrucât nu există forţe exterioare, energia cinetică totală a automobilului trebuie să se conserve. Deoarece energia cinetică se conservă, din relaţiile (12) şi (14) rezultă
> $$\left(\frac{3M+8\cdot m}{3}\right)\cdot\omega_v^2\cdot a^2=v_0^2\cdot\left(\frac{3M+10m}{6}\right)\tag{15}$$
> Astfel
>
> $$\omega_v=\frac{v_0}{a}\cdot\sqrt{\frac{3M+10m}{6M+16m}}\tag{16}$$
> O analiză a rezultatului permite următorul set de comentarii.
>
> - Dacă $M\gg m$, din relaţia (16) rezultă
> $$\omega_v=\frac{v_0}{a\sqrt2};\quad v_v=v_0\tag{17}$$
> Rezultatul este firesc. Viteza de translaţie este constantă dacă roţile nu contează.
> - Dacă $M\ll m$, din relaţia (16) rezultă
> $$\omega_v=\frac{v_0}{a}\cdot\sqrt{\frac58}\tag{18}$$
> - Dacă $M=m$, din relaţia (16) rezultă
> $$\omega_v=\frac{v_0}{a}\cdot\sqrt{\frac{13}{22}}\tag{19}$$
> Expresiile din relaţiile (12) şi (16) reprezintă răspunsul la sarcina de lucru 1.b.ii.
>
> **Sarcina de lucru nr. 2 - Forma drumului - Soluţie**
>
> **2.a.** Dacă forţa de greutate ar avea un moment faţă de punctul de contact, s-ar produce un transfer de energie potenţială gravitaţională către energie cinetică sau invers - ceea ce ar contrazice ipoteza constanţei energiei potenţiale.
>
> **2.b.** În imaginea din figura 4 este prezentată mişcarea laturii de jos a secţiunii pătrate a roţii pe relieful elementar – curba care trece prin punctele $x_s,T,x_d$. Folosind indicaţia rezultă că
> $$tg\alpha=-y'(x)\tag{20}$$
>
> Deoarece
> $$\cos\alpha=\frac1{\sqrt{1+tg^2\alpha}}\tag{21}$$
> rezultă că
> $$\cos\alpha=\frac1{\sqrt{1+y'^2}}\tag{22}$$
> şi deci
> $$G'T'=\frac a{\cos\alpha}=a\cdot\sqrt{1+y'^2}\tag{23}$$
>
> ![[rompho-2013-t1-solutions-p5-c1228.png]]
> *Figura 4. Vederea în secţiune a deplasării roţii pe relieful elementar al drumului. Verticala centrului de greutate al roţii trece prin punctul de contact dintre roată şi drum. Roata nu alunecă niciodată pe drum.*
>
> Coliniaritatea pe verticală a punctelor $G'$ şi $T'$ revine la
> $$y+a\cdot\sqrt{1+y'^2}=a\sqrt2\tag{24}$$
> sau
> $$y'=\sqrt{\left(\sqrt2-\frac ya\right)^2-1}\tag{25}$$
> de unde
> $$\frac{dy}{\sqrt{\left(\sqrt2-\frac ya\right)^2-1}}=\pm dx\tag{26}$$
> Din integrarea relaţiei (26) se obţine că
> $$\pm\frac xa+\wp=\ln\left|\left(\sqrt2-y/a\right)+\sqrt{(\sqrt2-y/a)^2-1}\right|\tag{27}$$
> Deoarece pentru
> $$x=0,\quad y=a\cdot(\sqrt2-1),\tag{28}$$
>
> constanta de integrare este nulă,
> $$\wp=0\tag{29}$$
> şi deoarece
> $$y<a(\sqrt2-1)\tag{30}$$
> ceea ce conduce la concluzia că modulul este aplicat unei cantităţi pozitive, expresia (27) se poate rescrie succesiv că
> $$(\sqrt2-y/a)+\sqrt{(\sqrt2-y/a)^2-1}=e^{\pm x/a}\tag{31}$$
> $$(e^{\pm x/a}-(\sqrt2-y/a))^2=(\sqrt2-y/a)^2-1\tag{32}$$
> $$\frac{e^{\pm2x/a}+1}{e^{\pm x/a}}=2(\sqrt2-y/a);\quad\frac{e^{\pm2x/a}+e^{\mp2x/a}}2=\sqrt2-\frac ya\tag{33}$$
> sau
>
> $$y=a(\sqrt2-ch(x/a))\tag{34}$$
> Graficul funcţiei reprezentând „relieful elementar” al drumului este prezentat în figura 5.
>
> ![[rompho-2013-t1-solutions-p6-f1.png]]
> *Figura 5 Relieful elementar al drumului*
>
> Expresia din relaţia (34) reprezintă răspunsul la sarcina de lucru 2.b.
>
> **2.c.** Din forma (31) a funcţiei care descrie relieful drumului rezultă că pentru $y=0$
> $$\pm x=a\cdot\ln(\sqrt2+1)\tag{35}$$
> Punctele extreme ale reliefului elementar al funcţiei sunt deci
> $$\begin{cases}x_s=-a\cdot\ln(\sqrt2+1)\\x_d=a\cdot\ln(\sqrt2+1)\end{cases}\tag{36}$$
> Întinderea pe orizontală a unui element al drumului, notată $2d$, este
>
> $$2d=|x_d-x_s|=2a\cdot\ln(\sqrt2+1)\tag{37}$$
> Expresia din relaţia (37) reprezintă răspunsul la sarcina de lucru 2.c.
>
> **2.d.** Deoarece
> $$2a\cdot\ln(\sqrt2+1)\cong1{,}76a<2\sqrt2a\tag{38}$$
> cele două roţi nu s-ar putea roti dacă s-ar afla pe două elemente de drum succesive.
>
> Distanţa minimă dintre axe $d_{min}$ trebuie să acopere poziţionarea la distanţa dintre două elemente de drum separate de un al treilea, adică
>
> $$d_{min}=4a\cdot\ln(\sqrt2+1)\tag{39}$$
> Expresia din relaţia (39) reprezintă răspunsul la sarcina de lucru 2.d.
>
> **2.e.** Corespunzător expresiei funcţiei care dă forma drumului rezultă că,
> $$y'=-sh(x/a)\tag{40}$$
> În consecinţă
> $$\begin{cases}y'(x_d)=-1\\y'(x_s)=1\end{cases}\tag{41}$$
> Rezultatul, care înseamnă că unghiul dintre tangentele la relief pentru două „dealuri” succesive este de $\pi/2$ asigură „potrivirea” exactă a pătratului în valea dintre două reliefuri elementare şi trecerea de pe unul pe celălalt, dar nu permite folosirea de roţi cu secţiunea hexagonală – oricare ar fi dimensiunea acestora pentru că, în secţiune, unghiul dintre laturile prismei hexagonale este $2\pi/3$.
>
> Precizările de mai sus reprezintă răspunsul la sarcina de lucru 2.e.
>
> **Sarcina de lucru nr. 3 – Accident - Soluţie**
>
> **3.a.** Viteza de deplasare a centrului de greutate satisface relaţia
> $$v_{G'}=\frac d{dt}(GG')=\frac{dx}{dt}\tag{42}$$
> În cursul deplasării raza giraţiei $GC$ ajunge în poziţia $G'C'$ rotindu-se cu unghiul
> $$\beta=\frac\pi2-\alpha\tag{43}$$
> Deoarece conform enunţului
> $$\alpha=arctg(-y'(x))\tag{44}$$
> viteza unghiulară a roţii este
> $$\omega=\frac{d\beta}{dt}=-\frac{d\alpha}{dt}=-\frac d{dt}[arctg(-y')]=\frac d{dt}[arctg(y')]\tag{45}$$
> $$\omega=-\frac d{dt}(arctg(sh(x/a)))=-\frac{ch(x/a)}{1+(sh(x/a))^2}\cdot\frac1a\cdot\frac{dx}{dt}\tag{46}$$
> $$\omega=-\frac1{a\cdot ch(x/a)}\cdot\frac{dx}{dt}\tag{47}$$
> atunci când roata evoluează de-a lungul reliefului din deal în vale
> $$0<x<d=a\cdot\ln(\sqrt2-1)\tag{48}$$
> şi corespunzător
> $$1<ch(x/a)<\sqrt2\tag{49}$$
> Între viteza unghiulară şi viteza de translaţie a „roţii” există relaţia
> $$\omega=-\frac1{a\cdot ch(x/a)}\cdot v_{G'}\tag{50}$$
> În cursul deplasării maşinii energia potenţială a acesteia este invariabilă. Energia sa cinetică $T$ este suma dintre energia cinetică de translaţie - (9) $T_t=(M+2m)\cdot v_{G'}^2/2$ şi energia cinetică de rotaţie (10) - $T_r=J\cdot\omega^2$. Astfel,
>
> $$T=T_t+T_r=\frac{M+2m}{2}v_{G'}^2+J\cdot\omega^2\tag{51}$$
> $$T=\frac{M+2m}{2}v_{G'}^2+\frac{2a^2\cdot m}{3}\cdot\left(\frac1{a\cdot ch(x/a)}\cdot v_{G'}\right)^2\tag{52}$$
> $$T=v_{G'}^2\cdot\left(\frac{M+2m}{2}+\frac23m\cdot\frac1{ch^2(x/a)}\right)\tag{53}$$
> La momentul iniţial când $x=0$
> $$v_{G'}(0)=v_0;\quad ch(x/a)=1\tag{54}$$
> $$T_0=v_0^2\cdot\left(\frac M2+\frac{5m}{3}\right)\tag{55}$$
> ceea ce verifică relaţia (12). În general, dependenţa de poziţie a vitezei de translaţia a maşinii este dată de
> $$v_{G'}=\frac{v_0\cdot\sqrt{\left(\frac M2+\frac{5m}{3}\right)}}{\sqrt{\frac{M+2m}{2}+\frac23m\cdot\frac1{ch^2(x/a)}}}\tag{56}$$
> La deplasarea din deal în vale, $0<x<a\cdot\ln(\sqrt2+1)$ şi corespunzător $1<ch(x/a)<\sqrt2$.
>
> În domeniul considerat $ch(x/a)$ este o funcţie monoton crescătoare (derivata sa în acest domeniu, $sh(x/a)$, este pozitivă) şi valorile extreme sunt cele din capete.
> $$\frac12<\frac1{ch^2(x/a)}<1\tag{57}$$
> Valorile extreme ale acestei viteze sunt respectiv viteza iniţială $v_0$ şi viteza „în vale”
>
> $$v_{G'}(d)=\frac{v_0\cdot\sqrt{3M+10m}}{\sqrt{3M+8m}}>v_0\tag{58}$$
> Precizarea de mai sus şi expresia din relaţia (58) reprezintă răspunsul la sarcina de lucru 3.a.
>
> **3.b.** Cantitatea de căldură apărută NU depinde de poziţia punctului de ciocnire deoarece în proces toată energia cinetică (constantă) a automobilului se transformă în căldură.
>
> Precizarea de mai sus reprezintă răspunsul la sarcina de lucru 3.b.
>
> **3.c.** Cantitatea de căldură $Q$ degajată este egală cu energia cinetică totală iniţială a maşinii.
>
> $$Q=v_0^2\cdot\left(\frac{3M+10m}{6}\right)\tag{59}$$
> Expresia din relaţia (59) reprezintă răspunsul la sarcina de lucru 3.c.

> [!grading]- Критерии оценивания
> Barem de evaluare şi de notare
>
> Se punctează oricare altă modalitate de rezolvare corectă a problemei
>
> Problema teoretică nr. 1 – Maşina lui Fred şi Barney
>
> | Nr. item | Sarcina de lucru nr. 1 - Energia cinetică a maşinii | | Punctaj |
> |---|---|---|---|
> | 1.a. | Pentru: | | 1,00p |
> | | expresia densităţii materialului roţii (presupusă de lungime $L$) $\rho=\frac{m}{4a^2\cdot L}$ | 0,20p | |
> | | expresia momentul de inerţie al unei prisme elementare cu laturile $(L,dx,dy)$, faţă de axul propriu al „roţii” $dJ=\rho\iint r^2\cdot L\cdot dx\cdot dy$<br>![[rompho-2013-t1-solutions-p9-f2.png]] | 0,30p | |
> | | expresia momentului de inerţie al roţii $J=\frac{2a^2\cdot m}{3}$ | 0,50p | |
> | 1.b.i. | Pentru: | | 1,00p |
> | | expresia vitezei unghiulare instantanee în punctul de plecare, unde raza instantanee de giraţie este $a$: $\omega_T=\frac{v_0}{a}$ | 0,20p | |
> | | expresia energiei cinetice totale a maşinii, la orice moment de timp $T=T_t+T_r=\frac{M+2m}{2}v^2+\frac{2a^2\cdot m}{3}\cdot\omega^2$ | 0,40p | |
> | | expresia energiei cinetice totale a maşini, la momentul iniţial $T_0=v_0^2\cdot\frac{3M+10m}{6}$ | 0,40p | |
> | 1.b.ii. | Pentru: | | 1,00p |
> | | expresia vitezei de translaţie în vale $v_v=\omega_v\cdot a\sqrt2$ | 0,20p | |
> | | expresia energiei cinetice totale a maşini în punctul „din vale” $T_v=\omega_v^2\cdot a^2\cdot\frac{3M+8m}{3}$ | 0,20p | |
> | | condiţia de conservare a energiei cinetice $\left(\frac{3M+8\cdot m}{3}\right)\cdot\omega_v^2\cdot a^2=v_0^2\cdot\left(\frac{3M+10m}{6}\right)$ | 0,40p | |
> | | $\omega_v=\frac{v_0}{a}\cdot\sqrt{\frac{3M+10m}{6M+16m}}$ | 0,20p | |
> | Nr. item | Sarcina de lucru nr. 2 – Forma drumului | | Punctaj |
> | 2.a. | Pentru: | | 0,50p |
> | | Exemplu de răspuns: Dacă forţa de greutate ar avea un moment faţă de punctul de contact, s-ar produce un transfer de energie potenţială gravitaţională către energie cinetică sau invers - ceea ce ar contrazice ipoteza constanţei energiei potenţiale. | 0,50p | |
> | 2.b. | Pentru:<br>![[rompho-2013-t1-solutions-p10-c1942.png]] | | 2,00p |
> | | $tg\alpha=-y'(x)$ | 0,20p | |
> | | condiţia de coliniaritate pe verticală a punctelor $G'$ şi $T'$: $y+a\cdot\sqrt{1+y'^2}=a\sqrt2$ | 0,50p | |
> | | $\frac{dy}{\sqrt{(\sqrt2-y/a)^2-1}}=\pm dx$ | 0,50p | |
> | | $\frac{e^{\pm2x/a}+e^{\mp2x/a}}2=\sqrt2-\frac ya$ | 0,50p | |
> | | $y=a(\sqrt2-ch(x/a))$ | 0,30p | |
> | 2.c. | Pentru: | | 0,50p |
> | | expresia punctelor extreme ale reliefului elementar, pentru $y=0$: $\begin{cases}x_s=-a\cdot\ln(\sqrt2+1)\\x_d=a\cdot\ln(\sqrt2+1)\end{cases}$ | 0,30p | |
> | | expresia lungimii pe orizontală a unui relief elementar $2d=|x_d-x_s|=2a\cdot\ln(\sqrt2+1)$ | 0,20p | |
> | 2.d. | Pentru: | | 0,50p |
> | | $2a\cdot\ln(\sqrt2+1)\cong1{,}76a<2\sqrt2a$. Observaţie: cele două roţi nu s-ar putea roti dacă s-ar afla pe două elemente de drum succesive | 0,20p | |
> | | expresia distanţei minime dintre axe $d_{min}=4a\cdot\ln(\sqrt2+1)$ | 0,30p | |
> | 2.e. | Pentru: | | 0,50p |
> | | $\begin{cases}y'(x_d)=-1\\y'(x_s)=1\end{cases}$ | 0,20p | |
> | | Răspuns corect. Exemplu de răspuns: Unghiul dintre tangentele la relief pentru două „dealuri” succesive este de $\pi/2$. Acest unghi asigură „potrivirea” exactă a pătratului în valea dintre două reliefuri elementare şi trecerea de pe unul pe celălalt, dar nu permite folosirea de roţi cu secţiunea hexagonală – oricare ar fi dimensiunea acestora pentru că, în secţiune, unghiul dintre laturile prismei hexagonale este $2\pi/3$. | 0,30p | |
> | Nr. item | Sarcina de lucru nr. 3 – Accident | | Punctaj |
> | 3.a. | Pentru: | | 2,00p |
> | | viteza de deplasare a centrului de greutate $v_{G'}=\frac d{dt}(GG')=\frac{dx}{dt}$ | 0,20p | |
> | | expresia vitezei unghiulare a roţii $\omega=-\frac1{a\cdot ch(x/a)}\cdot\frac{dx}{dt}$ | 0,40p | |
> | | expresia energiei cinetice $T=v_{G'}^2\cdot\left(\frac{M+2m}{2}+\frac23m\cdot\frac1{ch^2(x/a)}\right)$ | 0,40p | |
> | | expresia energiei cinetice la momentul iniţial ($x=0$, $v_{G'}(0)=v_0$ şi $ch(x/a)=1$) $T_0=v_0^2\cdot\left(\frac M2+\frac{5m}{3}\right)$ | 0,20p | |
> | | $v_{G'}=\frac{v_0\cdot\sqrt{\left(\frac M2+\frac{5m}{3}\right)}}{\sqrt{\frac{M+2m}{2}+\frac23m\cdot\frac1{ch^2(x/a)}}}$ | 0,40p | |
> | | expresiile valorilor extreme ale vitezei: viteza iniţială $v_0$; viteza „în vale” $v_{G'}(d)=\frac{v_0\cdot\sqrt{3M+10m}}{\sqrt{3M+8m}}>v_0$ | 0,40p | |
> | 3.b. | Pentru: | | 0,50p |
> | | răspuns corect. Exemplu de răspuns: Cantitatea de căldură apărută NU depinde de poziţia punctului de ciocnire, deoarece în proces toată energia cinetică (constantă) a automobilului se transformă în căldură. | 0,50p | |
> | 3.c. | Pentru: | | 0,50p |
> | | expresia cantităţii de căldură degajată $Q=v_0^2\cdot\left(\frac{3M+10m}{6}\right)$ | 0,50p | |
> | Punctaj total - Problema teoretică nr. 1 | | | 10p |
>
> © Barem de evaluare și de notare propus de:
>
> Prof. Dr. Delia DAVIDESCU
>
> Conf. univ. dr. Adrian DAFINEI
