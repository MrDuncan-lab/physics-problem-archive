---
id: rompho-2013-intl-theory-t3
olympiad: RomPhO
year: 2013
stage: "Международная олимпиада"
round: теория
grade: ""
number: "T3"
title: "Star Trek Watching"
points: 10
aliases: ["Star Trek Watching"]
topics: ["[[1.1 Равномерное прямолинейное движение]]", "[[6 Оптика]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: true
source_damaged: false
summary: "Определить видимые положения и длину линии маяков движущегося космического корабля с учётом времени распространения света и релятивистского сокращения."
status: "проверено: сверка; решение — проверено: сверка, два чтения + арбитр"
lang: en
tags: [задача]
---

# Theoretical Problem No. 3 - Star Trek Watching (10 points)

**RomPhO 2013** · Международная олимпиада · теория · задача T3  
Источник: [[_pdf/RomPhO/RomPhO-2013-T3.pdf#page=1|условие, стр. 1–2]] · [[_pdf/RomPhO/RomPhO-2013-T3-solution.pdf#page=2|решение, стр. 2–11]] · [[_pdf/RomPhO/RomPhO-2013-T3-solution.pdf#page=12|критерии, стр. 12]]

Темы: [[1.1 Равномерное прямолинейное движение]], [[6 Оптика]]

> [!abstract] Кратко (составлено моделью)
> Определить видимые положения и длину линии маяков движущегося космического корабля с учётом времени распространения света и релятивистского сокращения.

## Description of the situation

![[rompho-2013-t3-problems-p1-f1.png]]

Star Ship Enterprise has on each of the two warp engines a succession of five collinear, equidistant, numbered, beacons as shown in the figure (for the propeller on right side). When traveling, SS Enterprise moves with constant speed $\vec v$ so that, for the questions that follow, beacons located on a propeller are always on the same line that is $Ox$ axis of the coordinate system. In the situation room of another spacecraft which is at rest and which oversees the SS Enterprise, are analyzed the images of line of beacons. The images are taken by a camera with the aperture located at the point $(0,d)$ - in the orthogonal coordinate system shown in the inset in figure above. An image of line of beacons is produced by light rays that arrive simultaneously at camera aperture that opens for a short time. On a picture of SS Enterprise at rest, the length of line of beacons is $L$. In the problem, the beacons can be considered as points.

The speed of light is $c=3{,}00\times10^8\,m\cdot s^{-1}$.

Employ the quantities $\beta=v/c$ and $\gamma=1/\sqrt{1-\beta^2}$, if they help to simplify your result.

## Task No. 1 - The link between image and the actual position

The actual position is the position in the frame in which the camera is at rest.

Next, the camera remains stationary in the point $(0,d)$ and the SS Enterprise is moving at velocity $\vec v$ on $Ox$ direction. In an image provided by the camera described above is observed that one of the bright beacons is placed in the position $x_i$.

**1.a.** Determine the expression for the actual position of the bright beacon when the image is formed in the camera.

**1.b.** Find also the corresponding inverse relation, that is the expression of $x_i$ in terms of $x,d,L,v$ and $c$.

## Task No. 2 - Apparent length of the beacons line

The camera takes a picture of the instant when the actual position of the center of beacons line is at some $x_0$ point.

**2.a.** Determine the expression for the apparent length of the beacons line on this picture.

**2.b.** Indicate – using a mathematical expression – how the apparent length of beacons line changes with time, when SS Enterprise moves along the Ox axe. The space ship comes from far away, passes through the origin of the system and then receding far away.

## Task No. 3 - Symmetrical image

One of the pictures taken by the camera shows both ends of beacons line at the same distance from the aperture of camera.

**3.a.** Determine the expression for the apparent length of beacons line on this picture.

**3.b.** Determine the expression for the actual position of the middle beacons at the time when this picture is taken.

**3.c.** Determine where will be situated on the picture the image of the middle beacons.

## Task No. 4 - Pictures of SS Enterprise, being far away and approaching or being far away and receding

Camera takes a picture when SS Enterprise is approaching from far away and another image when the ship (and the beacons line) is far away and receding. On one of these images the apparent length of the line of beacons is $160\,m$ and the other is $600\,m$.

**4.a.** Decide which of the following statements is correct.

**i.** Apparent length is $200\,m$ on the image of „approaching” ship and $600\,m$ on the image of „receding” ship.

**ii.** Apparent length is $600\,m$ on the image of „approaching” ship and $200\,m$ on the image of „receding” ship.

*Write in the appropriate box in the answer sheet the letter corresponding to the answer you think is correct. Briefly justify your choice.*

**4.b.** Determine the speed $v$ of the ship.

**4.c.** Calculate the value of length of the beacons line at rest.

**4.d.** Calculate the value of length of the beacons line on the symmetric picture, described at task no. 3.a.

© The Problem is proposed by:  
Delia DAVIDESCU, PhD  
Adrian DAFINEI, PhD

> [!answer]- Ответ
> **1.a**
>
> $$
> x=x_i+v\cdot T=x_i+\frac vc\sqrt{d^2+x_i^2}=x_i+\beta\cdot\sqrt{d^2+x_i^2}
> $$
>
> **1.b**
>
> $$
> x_i=\gamma\left(\gamma\cdot x-\beta\cdot\sqrt{d^2+\gamma^2\cdot x^2}\right)
> $$
>
> **2.a**
>
> $$
> L_i(x_0)=\gamma\cdot L-\beta\cdot\gamma\sqrt{d^2+\left(\gamma\cdot x_0+\frac L2\right)^2}+\beta\cdot\gamma\sqrt{d^2+\left(\gamma\cdot x_0-\frac L2\right)^2}
> $$
>
> **3.a**
>
> $$
> L_{i,simetric}=\frac L\gamma
> $$
>
> **3.b**
>
> $$
> x_0=\beta\sqrt{\frac{L^2}{4\gamma^2}+d^2}\tag*{(42)$^{*}$}
> $$
>
> **3.c**
>
> $$
> x_{i,0}=\gamma\cdot\beta\left(\sqrt{(\gamma\cdot d)^2+\left(\frac L2\right)^2}-\sqrt{(d\cdot\gamma)^2+\left(\frac{L\cdot\beta}2\right)^2}\right)
> $$
>
> **3.c**
>
> $$
> \ell=x_{i,+}-x_{i,0}=\frac L{2\gamma}-x_{i,0}=\frac L{2\gamma}-\gamma\cdot\beta\left(\sqrt{(\gamma\cdot d)^2+\left(\frac L2\right)^2}-\sqrt{(d\cdot\gamma)^2+\left(\frac{L\cdot\beta}2\right)^2}\right)
> $$
>
> **4.a**
>
> $$
> L_{i,apropiere}=L\sqrt{\frac{1+\beta}{1-\beta}}>L_{i,indepartare}=L\sqrt{\frac{1-\beta}{1+\beta}}
> $$
>
> **4.b**
>
> $$
> \begin{cases}v=\frac c2\\v=1{,}50\cdot10^8\,m\cdot s^{-1}\end{cases}
> $$
>
> **4.c**
>
> $$
> L=200\sqrt3\,m\cong346\,m
> $$
>
> **4.d**
>
> $$
> \begin{cases}L_i=\frac L\gamma=200\sqrt3\frac{\sqrt3}2\\L_i=300\,m\end{cases}
> $$

> [!solution]- Решение
> ## Problema teoretică nr. 3 - Soluție
> ## Sarcina de lucru nr. 1 - Legătura dintre imagine și poziția reală
>
> **1.a.** Imaginea apărută în cameră se datorează razelor de lumină care *ajung* în același moment și nu razelor de lumină care *pleacă* simultan. Din acest motiv apare diferența dintre imaginea aparentă a unui punct de pe linia de balize și poziția actuală, la momentul în care se formează imaginea, punctului de pe linia de balize.
>
> O baliză, aflată în poziția notată cu $x_i$ apare pe imaginea din camera obscură dacă lumina provenită de la ea a plecat înainte de momentul luării imaginii cu timpul $T$ având expresia
>
> $$T=\frac{\sqrt{d^2+x_i^2}}c\tag{1}$$
>
> ![[rompho-2013-t3-solutions-p3-f2.png]]
> *Figura 1*
>
> În timpul necesar luminii să ajungă de la baliză la camera obscură, baliza s-a deplasat pe distanța $v\cdot T$ astfel că „poziția actuală” a balizei la momentul la care este luată imaginea sa este
>
> $$x=x_i+v\cdot T=x_i+\frac vc\sqrt{d^2+x_i^2}=x_i+\beta\cdot\sqrt{d^2+x_i^2}\tag{2*}$$
> Baliza care se afla în poziția $x_i$ apare pe imagine atunci când este în poziția $x$.
>
> *Expresia din relația (2)⁎ reprezintă răspunsul la sarcina de lucru 1.a.*
>
> **1.b.** Prin ridicarea la pătrat a relației de mai sus rezultă succesiv
> $$\begin{cases}x^2-2x\cdot x_i+x_i^2=\beta^2\cdot d^2+\beta^2\cdot x_i^2\\(1-\beta^2)x_i^2-2x\cdot x_i+(x^2-\beta^2\cdot d^2)=0\\(1-\beta^2)x_i^2-2x\cdot x_i+(x^2-d^2+(1-\beta^2)\cdot d^2)=0\\\frac{x_i^2}{\gamma^2}-2x\cdot x_i+\left(x^2-d^2+\frac{d^2}{\gamma^2}\right)=0\end{cases}\tag{3}$$
> Corespunzător,
> $$\begin{cases}x_i=\gamma^2\left(x\pm\sqrt{x^2-\frac1{\gamma^2}(x^2-\beta^2\cdot d^2)}\right)\\x_i=\gamma^2\left(x\pm\frac1\gamma\sqrt{\beta^2\cdot d^2-(1-\gamma^2)\cdot x^2}\right)\end{cases}\tag{4}$$
> Deoarece
> $$1-\gamma^2=1-\frac1{1-\beta^2}=\frac{-\beta^2}{1-\beta^2}=-\beta^2\cdot\gamma^2\tag{5}$$
> din ultima relație din (5) rezultă
> $$\begin{cases}x_i=\gamma^2\left(x\pm\frac\beta\gamma\sqrt{d^2+\gamma^2\cdot x^2}\right)\\x_i=\gamma\left(\gamma\cdot x\pm\beta\sqrt{d^2+\gamma^2\cdot x^2}\right)\end{cases}\tag{6}$$
>
> Deoarece se apropie de proiecția originea axei pe care se deplasează, selectarea firească a semnului în expresiile de mai sus, conduce la
>
> $$x_i=\gamma\left(\gamma\cdot x-\beta\cdot\sqrt{d^2+\gamma^2\cdot x^2}\right)\tag{7*}$$
> Baliza a cărei imaginea apare în poziția $x_i$ se află în momentul formării imaginii în poziția $x$.
>
> *Expresia din relația (7)⁎ reprezintă răspunsul la sarcina de lucru 1.b.*
>
> ## Sarcina de lucru nr. 2. - Lungimea aparentă a liniei de balize
>
> **2.a.** Deoarece balizele se deplasează cu viteza $\vec v$ lungimea sa este – datorită contracției Lorentz - $L/\gamma$.
>
> În momentul în care camera obscură formează imaginea liniei de balize având centrul în punctul $x_0$, balizele din capete au respectiv pozițiile
> $$x_{fața}=x_+=x_0+\frac L{2\gamma}\tag{8}$$
> și
> $$x_{spate}=x_-=x_0-\frac L{2\gamma}\tag{9}$$
> Imaginile capetelor $x_{i,\pm}$ vor fi formate de camera obscură „ca și cum” s-ar fi aflat în pozițiile
> $$x_{i,\pm}=\gamma\left(\gamma\cdot x_0\pm\frac L2\right)-\beta\cdot\gamma\sqrt{d^2+\left(\gamma\cdot x_0\pm\frac L2\right)^2}\tag{10}$$
> În relația de mai sus s-a ținut seama de expresiile pozițiilor capetelor liniei de balize și de relația (8).
>
> Lungimea aparentă a liniei de balize, $L_i$, este diferența pozițiilor aparente ale capetelor adică
>
> $$L_i(x_0)=x_{i,+}-x_{i,-}\tag{11}$$
>
> $$L_i(x_0)=\gamma\cdot L-\beta\cdot\gamma\sqrt{d^2+\left(\gamma\cdot x_0+\frac L2\right)^2}+\beta\cdot\gamma\sqrt{d^2+\left(\gamma\cdot x_0-\frac L2\right)^2}\tag{12*}$$
> *Expresia din relația (12)⁎ reprezintă răspunsul la sarcina de lucru 2.a.*
>
> **2.b.** Văzută ca funcție de $x_0$, expresia polinomială de gradul 2
> $$F_1=\left(\gamma\cdot x_0+\frac L2\right)^2+d^2\tag{13}$$
> are un minim cu valoarea $d^2$ pentru
> $$x_0=-\frac L{2\gamma}\tag{14}$$
> Pentru valori ale variabilei $x_0$, $x_0\geq-\frac L{2\gamma}$ funcția $F_1$ este monoton crescătoare.
>
> Corespunzător, expresia
> $$E_1=-\beta\cdot\gamma\sqrt{F_1}\tag{15}$$
> este monoton crescătoare până la $x_0=-\frac L{2\gamma}$, apoi monoton descrescătoare și are un maxim în valoare de
> $$E_{1,max}=E_1\left(x_0=-\frac L{2\gamma}\right)=-\beta\gamma d\tag{16}$$
>
> Pentru
> $$x_0=\frac L{2\gamma}\tag{17}$$
> $$E_1\left(x_0=\frac L{2\gamma}\right)=-\beta\cdot\gamma\sqrt{d^2+L^2}\tag{18}$$
> Grafic, dependența $E_1(x_0)$ are aspectul prezentat în figura 2
>
> ![[rompho-2013-t3-solutions-p5-f2.png]]
> *Figura 2 - Reprezentarea grafică a funcțiilor $E_1$, $E_2$ și $E_1+E_2$*
>
> Analog, văzută ca funcție de $x_0$ expresia polinomială de gradul 2
> $$F_2=\left(\gamma\cdot x_0-\frac L2\right)^2+d^2\tag{19}$$
> are un minim cu valoarea $d^2$ pentru
> $$x_0=\frac L{2\gamma}\tag{20}$$
> Pentru valori ale variabilei $x_0$, $x_0\geq\frac L{2\gamma}$ funcția $F_2$ este monoton crescătoare.
>
> Corespunzător, expresia
> $$E_2=\beta\cdot\gamma\sqrt{F_2}\tag{21}$$
> este monoton descrescătoare până la $x_0=\frac L{2\gamma}$, apoi monoton crescătoare și are un minim în valoare de
> $$E_{2,minim}=E_2\left(x_0=\frac L{2\gamma}\right)=\beta\gamma d\tag{22}$$
> Pentru
> $$x_0=-\frac L{2\gamma}\tag{23}$$
>
> $$E_2\left(x_0=-\frac L{2\gamma}\right)=\beta\cdot\gamma\sqrt{d^2+L^2}\tag{24}$$
>
> Grafic, dependența $E_2(x_0)$ are aspectul prezentat în figura 2.
> Expresia
>
> $$\begin{cases}
> E=E_1+E_2=\gamma\beta(\sqrt{F_2}-\sqrt{F_1})\\
> E=\gamma\beta\left(\dfrac{F_2-F_1}{\sqrt{F_2}+\sqrt{F_1}}\right)=\dfrac{\left(\gamma\cdot x_0-\dfrac L2\right)^2+d^2-\left(\left(\gamma\cdot x_0+\dfrac L2\right)^2+d^2\right)}{\sqrt{\left(\gamma\cdot x_0-\dfrac L2\right)^2+d^2}+\sqrt{\left(\gamma\cdot x_0+\dfrac L2\right)^2+d^2}}\\
> E=\gamma\beta\dfrac{-2}{\sqrt{\left(\gamma\cdot x_0-\dfrac L2\right)^2+d^2}+\sqrt{\left(\gamma\cdot x_0+\dfrac L2\right)^2+d^2}}\gamma\cdot x_0 L
> \end{cases}\tag{25}$$
> este monoton descrescătoare – așa cum se vede în imaginea din figura 2.
> Ultima relație din ansamblul de mai sus se poate scrie și sub forma
> $$E=\frac{-2\gamma^2\cdot\beta\cdot L}{\sqrt{\left(\gamma-\frac L{2x_0}\right)^2+\left(\frac d{x_0}\right)^2}+\sqrt{\left(\gamma+\frac L{2x_0}\right)^2+\left(\frac d{x_0}\right)^2}}\cdot\frac{x_0}{|x_0|}\tag{26}$$
> Pentru valori negative ale variabilei $x_0$, expresia de mai sus se scrie
> $$E_-=\frac{2\gamma^2\cdot\beta\cdot L}{\sqrt{\left(\gamma-\frac L{2x_0}\right)^2+\left(\frac d{x_0}\right)^2}+\sqrt{\left(\gamma+\frac L{2x_0}\right)^2+\left(\frac d{x_0}\right)^2}}\tag{27}$$
> Evident, dacă $x_0$ evoluează monoton crescător între $-\infty$ și $0$ adică pentru $-\infty<x_0<0$, expresia din (27) evoluează de asemenea monoton dar descrescător între valorile
> $$E_-(-\infty)=\frac{\gamma^2\cdot\beta\cdot L}{\sqrt{\gamma^2}}=\gamma\cdot\beta\cdot L\tag{28}$$
> și
> $$E_-(0)=0\tag{29}$$
> Pentru valori pozitive ale variabilei $x_0$, expresia (26) se scrie
> $$E_+=\frac{-2\gamma^2\cdot\beta\cdot L}{\sqrt{\left(\gamma-\frac L{2x_0}\right)^2+\left(\frac d{x_0}\right)^2}+\sqrt{\left(\gamma+\frac L{2x_0}\right)^2+\left(\frac d{x_0}\right)^2}}\tag{30}$$
> Dacă $x_0$ evoluează monoton crescător între $0$ și $\infty$ adică dacă $0<x_0<\infty$, expresia din (30) evoluează de asemenea monoton, dar descrescător între
> $$E_+(0)=0\tag{31}$$
> și
> $$E_+(\infty)=-\gamma\cdot\beta\cdot L\tag{32}$$
> Studiul analitic al lungimii aparente
>
> $$L_i(x_0)=\gamma\cdot L+E\tag{33}$$
> arată – de asemenea – că aceasta evoluează monoton descrescător atunci când $x_0$ crește.
>
> Prin urmare, lungimea aparentă a liniei de balize descrește tot timpul.
>
> *Precizarea de mai sus reprezintă răspunsul la sarcina de lucru 2.b.*
>
> ### Sarcina de lucru nr. 3 - Imagine simetrică
>
> **3.a.** Dacă în imaginea luată de camera obscură capetele liniei de balize se află la aceeași distanță de diafragma camerei obscure, înseamnă că lumina provenită de la ambele capete ale liniei de balize parcurge drumuri egale pentru a ajunge în intervale de timp egale la diafragma camerei. Lumina care formează imaginea a plecat *simultan* din capetele liniei de balize. Lungimea aparentă a liniei de balize este în aceste condiții lungimea liniei de balize în mișcare – adică $\frac L\gamma$.
>
> Răspunsul la întrebarea **3.a.** referitoare la lungimea aparentă a liniei de balize care apare în imaginea simetrică este deci
>
> $$L_{i,simetric}=\frac L\gamma\tag{34*}$$
> *Expresia din relația (34)* $^*$ *reprezintă răspunsul la sarcina de lucru 3.a.*
>
> **3.b.** Imaginile capetelor sunt – conform enunțului – simetrice. Aceasta revine la
> $$x_{i,+}=-x_{i,-}\tag{35}$$
> adică
> $$x_{i,+}+x_{i,-}=0$$
> Ținând seama de (10) relația de mai sus devine
> $$0=x_{i,+}+x_{i,-}=2\gamma^2\cdot x_0-\beta\cdot\gamma\sqrt{d^2+\left(\gamma\cdot x_0+\frac L2\right)^2}-\beta\cdot\gamma\sqrt{d^2+\left(\gamma\cdot x_0-\frac L2\right)^2}\tag{36}$$
> Scriind și lungimea aparentă a liniei de balize pentru situația analizată
> $$\begin{cases}\dfrac L\gamma=x_{i,+}-x_{i,-}=L_i(x_0)\\\dfrac L\gamma=\gamma\cdot L-\beta\cdot\gamma\sqrt{d^2+\left(\gamma\cdot x_0+\dfrac L2\right)^2}+\beta\cdot\gamma\sqrt{d^2+\left(\gamma\cdot x_0-\dfrac L2\right)^2}\end{cases}\tag{37}$$
> și adunând relațiile de mai sus rezultă
>
> $$\begin{cases}\dfrac L\gamma=2\gamma^2\cdot x_0+\gamma\cdot L-2\beta\cdot\gamma\sqrt{d^2+\left(\gamma\cdot x_0+\dfrac L2\right)^2}\\\dfrac{2\gamma^2\cdot x_0+\gamma\cdot L-\dfrac L\gamma}{2\beta\cdot\gamma}=\sqrt{d^2+\left(\gamma\cdot x_0+\dfrac L2\right)^2}\\\sqrt{d^2+\left(\gamma\cdot x_0+\dfrac L2\right)^2}=\dfrac{x_0\cdot\gamma}{\beta}+\dfrac{L(\gamma^2-1)}{2\beta\cdot\gamma^2}=\dfrac{x_0\cdot\gamma}{\beta}+\dfrac{L\cdot\beta}{2}\end{cases}\tag{38}$$
> Prin urmare
>
> $$\sqrt{d^2+\left(\gamma\cdot x_0+\frac L2\right)^2}=\frac{x_0\cdot\gamma}{\beta}+\frac{L\cdot\beta}2\tag{39}$$
> Scăzând (36) din (37) rezultă
> $$\sqrt{d^2+\left(\gamma\cdot x_0-\frac L2\right)^2}=\frac{x_0\cdot\gamma}{\beta}-\frac{L\cdot\beta}2\tag{40}$$
> Din oricare dintre ultimele două relații se poate extrage valoarea poziției mijlocului liniei de balize.
> Din (40) rezultă succesiv
> $$\begin{cases}d^2+\left(\gamma\cdot x_0+\dfrac L2\right)^2=\left(\dfrac{x_0\cdot\gamma}{\beta}+\dfrac{L\cdot\beta}2\right)^2\\d^2+\gamma^2\cdot x_0^2+\dfrac{L^2}4+\gamma\cdot x_0\cdot L=\dfrac{x_0^2\cdot\gamma^2}{\beta^2}+\dfrac{L^2\cdot\beta^2}4+\gamma\cdot x_0\cdot L\\\gamma^2\cdot x_0^2\cdot\left(1-\dfrac1{\beta^2}\right)=\dfrac{L^2}4(\beta^2-1)-d^2\\\dfrac1{1-\beta^2}\cdot x_0^2\cdot\left(1-\dfrac1{\beta^2}\right)=\dfrac{L^2}4(\beta^2-1)-d^2\end{cases}\tag{41}$$
> și deci
>
> $$x_0=\beta\sqrt{\frac{L^2}{4\gamma^2}+d^2}\tag*{(42)$^{*}$}$$
> *Expresia din relația (43)* $^*$ *reprezintă răspunsul la sarcina de lucru 3.b.*
>
> O alternativă a metodei de determinare a poziției centrului liniei de balize, pleacă de la ipoteza „capetelor dispuse simetric”, relația (36) - scrisă sub forma
> $$2\gamma^2\cdot x_0-\beta\cdot\gamma\sqrt{d^2+\left(\gamma\cdot x_0+\frac L2\right)^2}=\beta\cdot\gamma\sqrt{d^2+\left(\gamma\cdot x_0-\frac L2\right)^2}\tag{43}$$
> din care rezultă succesiv prin două ridicări la pătrat și alte prelucrări algebrice
>
> $$\begin{cases}4\gamma^4\cdot x_0^2+2\beta^2\cdot\gamma^3\cdot x_0\cdot L=4\beta\cdot\gamma^3\cdot x_0\cdot\sqrt{d^2+\left(\gamma\cdot x_0+\dfrac L2\right)^2}\\4\gamma^2\cdot x_0^4(1-\beta^2)+\beta^2\cdot x_0^2\cdot L^2(\beta^2-1)-4\beta^2\cdot x_0^2\cdot d^2=0\\4\cdot x_0^4-\dfrac{\beta^2\cdot x_0^2\cdot L^2}{\gamma^2}-4\beta^2\cdot x_0^2\cdot d^2=0\end{cases}\tag{44}$$
> Din ultima relație se poate regăsi relația (42).
>
> **3.c.** Poziția mijlocului liniei de balize în imagine poate fi determinată folosind relația dintre pozițiile aparentă și actuală (7)
> $$\begin{cases}x_{i,0}=\gamma\left(\gamma\cdot x_0-\beta\cdot\sqrt{d^2+\gamma^2\cdot x_0^2}\right)\\x_{i,0}=\gamma\left(\gamma\cdot\beta\sqrt{d^2+\left(\dfrac L{2\gamma}\right)^2}-\beta\cdot\sqrt{d^2+\gamma^2\cdot\beta^2\left(d^2+\left(\dfrac L{2\gamma}\right)^2\right)}\right)\end{cases}\tag{45}$$
> Expresia poziției mijlocului liniei de balize *în imagine* este
>
> $$x_{i,0}=\gamma\cdot\beta\left(\sqrt{(\gamma\cdot d)^2+\left(\frac L2\right)^2}-\sqrt{(d\cdot\gamma)^2+\left(\frac{L\cdot\beta}2\right)^2}\right)\tag{46}$$
>
> Capătul din față al liniei de balize are imaginea la $x_{i,+}$. Distanța dintre imaginea capătului și imaginea centrului este
>
> $$\ell=x_{i,+}-x_{i,0}=\frac L{2\gamma}-x_{i,0}=\frac L{2\gamma}-\gamma\cdot\beta\left(\sqrt{(\gamma\cdot d)^2+\left(\frac L2\right)^2}-\sqrt{(d\cdot\gamma)^2+\left(\frac{L\cdot\beta}2\right)^2}\right)\tag{47*}$$
> *Expresia din relația (47)⁎ reprezintă răspunsul la sarcina de lucru 3.c.*
>
> ## Sarcina de lucru nr. 4 - Imagini ale SS Enterprise aflată foarte departe
>
> **4.a.** Relațiile (28) și (33) permit să se scrie pentru lungimea aparentă a liniei de balize în imaginea „cu apropiere de departe” expresia
> $$\begin{cases}L_{i,apropiere}=L_i(x_0\to-\infty)=\gamma\cdot L+E_-=\gamma\cdot L+\gamma\cdot\beta\cdot L\\L_{i,apropiere}=\gamma\cdot L\cdot(1+\beta)=L\frac{1+\beta}{\sqrt{1-\beta^2}}\\L_{i,apropiere}=L\sqrt{\frac{1+\beta}{1-\beta}}\end{cases}\tag{48}$$
> Analog, relațiile (32) și (33) permit să se scrie pentru lungimea aparentă a liniei de balize în imaginea „cu îndepărtare” expresia
> $$\begin{cases}L_{i,indepartare}=L_i(x_0\to\infty)=\gamma\cdot L+E_+=\gamma\cdot L-\gamma\cdot\beta\cdot L\\L_{i,indepartare}=\gamma\cdot L\cdot(1-\beta)=L\frac{1-\beta}{\sqrt{1-\beta^2}}\\L_{i,indepartare}=L\sqrt{\frac{1-\beta}{1+\beta}}\end{cases}\tag{49}$$
> Deoarece – evident –
>
> $$L_{i,apropiere}=L\sqrt{\frac{1+\beta}{1-\beta}}>L_{i,indepartare}=L\sqrt{\frac{1-\beta}{1+\beta}}\tag{50*}$$
> Se poate deci afirma că răspunsul corect la sarcina de lucru 4.a este ii. Lungimea aparentă este de $600\,m$ pe imaginea navei care vine și de $200\,m$ pe imaginea navei care pleacă.
>
> *Expresia din relația (50)⁎ și precizarea de mai sus reprezintă răspunsul la sarcina de lucru 4.a.*
>
> **4.b.** Raportul lungimilor imaginilor timpurie și târzie este
> $$\frac{L_{i,apropiere}}{L_{i,indepartare}}=\frac{L\sqrt{\frac{1+\beta}{1-\beta}}}{L\sqrt{\frac{1-\beta}{1+\beta}}}=\frac{1+\beta}{1-\beta}=\frac31.\tag{51}$$
> Din această relație rezultă
> $$\begin{cases}1+\beta=3-3\beta\\\beta=\frac12\end{cases}\tag{52}$$
> În consecință
>
> $$\begin{cases}v=\frac c2\\v=1{,}50\cdot10^8\,m\cdot s^{-1}\end{cases}\tag{53*}$$
> *Valoarea numerică din relația (53)⁎ reprezintă răspunsul la sarcina de lucru 4.b.*
>
> **4.c.** Din expresia lungimii imaginii timpurii rezultă – ținând seama de viteza liniei de balize
> $$600m=L_{i,apropiere}=L\sqrt{\frac{1+1/2}{1-1/2}}=L\sqrt3\tag{54}$$
> Prin urmare
>
> $$L=200\sqrt3\,m\cong346\,m\tag{55*}$$
> *Valoarea numerică din relația (55)⁎ reprezintă răspunsul la sarcina de lucru 4.c.*
>
> **4.d.** Deoarece valoarea parametrului $\gamma$ corespunzătoare valorii $\beta=\frac12$ este
> $$\gamma=\frac1{\sqrt{1-\beta^2}}=\frac1{\sqrt{1-\frac14}}=\frac2{\sqrt3}\tag{56}$$
> lungimea aparentă a imaginii simetrice este – conform relației
>
> $$\begin{cases}L_i=\frac L\gamma=200\sqrt3\frac{\sqrt3}2\\L_i=300\,m\end{cases}\tag{57*}$$
> *Valoarea lungimii aparente a imaginii simetrice din relația (57)⁎ reprezintă răspunsul la sarcina de lucru 4.d.*
>
> © Soluție propusă de:  
> Prof. Dr. Delia DAVIDESCU  
> Conf. univ. dr. Adrian DAFINEI

> [!grading]- Критерии оценивания
> Barem de evaluare și de notare  
> Se punctează oricare altă modalitate de rezolvare corectă a problemei
>
> Problema teoretică nr. 3 – Supraveghere Star Trek
>
> | Nr. item | Sarcina de lucru nr. 1 – Legătura dintre imagine și poziția reală | | Punctaj |
> |---|---|---|---|
> | 1.a. | Pentru: | | 1,00p |
> | | ![[rompho-2013-t3-solutions-p12-c1625.png]] $T=\frac{\sqrt{d^2+x_i^2}}c$ | 0,50p | |
> | | $\begin{cases}x=x_i+v\cdot T\\x=x_i+\beta\cdot\sqrt{d^2+x_i^2}\end{cases}$ | 0,50p | |
> | 1.b. | Pentru: | | 1,00p |
> | | $x_i=\gamma\left(\gamma\cdot x\pm\beta\sqrt{d^2+\gamma^2\cdot x^2}\right)$ | 0,80p | |
> | | alegerea corectă a semnului $x_i=\gamma\left(\gamma\cdot x-\beta\cdot\sqrt{d^2+\gamma^2\cdot x^2}\right)$ | 0,20p | |
> | Nr. item | Sarcina de lucru nr. 2 – Lungimea aparentă a liniei de balize | | Punctaj |
> | 2.a. | Pentru: | | 1,00p |
> | | expresia pozițiilor balizelor din capete $\begin{cases}x_{fața}=x_+=x_0+\frac L{2\gamma}\\x_{spate}=x_-=x_0-\frac L{2\gamma}\end{cases}$ | 0,20p | |
> | | expresia imaginilor din capetelor $x_{i,\pm}=\gamma\left(\gamma\cdot x_0\pm\frac L2\right)-\beta\cdot\gamma\sqrt{d^2+\left(\gamma\cdot x_0\pm\frac L2\right)^2}$ | 0,40p | |
> | | lungimea aparentă a liniei de balize $L_i(x_0)=x_{i,+}-x_{i,-}$; $L_i(x_0)=\gamma\cdot L-\beta\cdot\gamma\sqrt{d^2+\left(\gamma\cdot x_0+\frac L2\right)^2}+\beta\cdot\gamma\sqrt{d^2+\left(\gamma\cdot x_0-\frac L2\right)^2}$ | 0,40p | |
> | 2.b. | Pentru: | | 1,00p |
> | | $\begin{cases}L_i(x_0)=\gamma\cdot L+E\\L_i(x_0)=\gamma\cdot L+E_1+E_2\end{cases}$, unde $\begin{cases}E_1=-\beta\cdot\gamma\sqrt{d^2+\left(\gamma\cdot x_0+\frac L2\right)^2}\\E_2=\beta\cdot\gamma\sqrt{d^2+\left(\gamma\cdot x_0-\frac L2\right)^2}\end{cases}$ | 0,20p | |
> | | ![[rompho-2013-t3-solutions-p13-c1618.png]] | 0,60p | |
> | | expresia $L_i(x_0)=\gamma\cdot L+E$ evoluează monoton descrescător atunci când $x_0$ crește; lungimea aparentă a liniei de balize descrește tot timpul | 0,20p | |
> | Nr. item | Sarcina de lucru nr. 3 – Imagine simetrică | | Punctaj |
> | 3.a. | Pentru: | | 1,00p |
> | | expresia pentru lungimea aparentă a liniei de balize care apare în imaginea simetrică $L_{i,simetric}=\frac L\gamma$ | 1,00p | |
> | 3.b. | Pentru: | | 1,00p |
> | | condiția ca imaginile capetelor să fie simetrice $x_{i,+}=-x_{i,-}$ | 0,20p | |
> | | $0=x_{i,+}+x_{i,-}=2\gamma^2\cdot x_0-\beta\cdot\gamma\sqrt{d^2+\left(\gamma\cdot x_0+\frac L2\right)^2}-\beta\cdot\gamma\sqrt{d^2+\left(\gamma\cdot x_0-\frac L2\right)^2}$ | 0,20p | |
> | | $\frac L\gamma=x_{i,+}-x_{i,-}=L_i(x_0)$ | 0,20p | |
> | | $x_0=\beta\sqrt{\frac{L^2}{4\gamma^2}+d^2}$ | 0,40p | |
> | 3.c. | expresia poziției mijlocului liniei de balize în imagine $x_{i,0}=\gamma\cdot\beta\left(\sqrt{(\gamma\cdot d)^2+\left(\frac L2\right)^2}-\sqrt{(d\cdot\gamma)^2+\left(\frac{L\cdot\beta}2\right)^2}\right)$ | 0,60p | |
> | | distanța dintre imaginea capătului și imaginea centrului $\begin{cases}\ell=x_{i,+}-x_{i,0}\\\ell=\frac L{2\gamma}-\gamma\cdot\beta\left(\sqrt{(\gamma\cdot d)^2+\left(\frac L2\right)^2}-\sqrt{(d\cdot\gamma)^2+\left(\frac{L\cdot\beta}2\right)^2}\right)\end{cases}$ | 0,40p | |
> | Nr. item | Sarcina de lucru nr. 4 – Imagini ale SS Enterprise aflată foarte departe | | Punctaj |
> | 4.a. | Pentru: | | 1,00p |
> | | $\begin{cases}L_{i,apropiere}=L_i(x_0\to-\infty)=\gamma\cdot L+E_-=\gamma\cdot L+\gamma\cdot\beta\cdot L\\L_{i,apropiere}=L\sqrt{\frac{1+\beta}{1-\beta}}\end{cases}$ | 0,40p | |
> | | $\begin{cases}L_{i,indepartare}=L_i(x_0\to\infty)=\gamma\cdot L+E_+=\gamma\cdot L-\gamma\cdot\beta\cdot L\\L_{i,indepartare}=L\sqrt{\frac{1-\beta}{1+\beta}}\end{cases}$ | 0,40p | |
> | | $L_{i,apropiere}>L_{i,indepartare}$; răspuns corect: ii. *Lungimea aparentă este de $600\,m$ pe imaginea navei care vine și de $200\,m$ pe imaginea navei care pleacă.* | 0,20p | |
> | 4.b. | Pentru: | | 1,00p |
> | | $\frac{L_{i,apropiere}}{L_{i,indepartare}}=\frac{1+\beta}{1-\beta}$; $\frac{L_{i,apropiere}}{L_{i,indepartare}}=\frac31$ | 0,60p | |
> | | $\beta=\frac12$ | 0,20p | |
> | | $v=1{,}50\cdot10^8\,m\cdot s^{-1}$ | 0,20p | |
> | 4.c. | Pentru: | | 0,50p |
> | | $L_{i,apropiere}=L\sqrt3$; $L_{i,apropiere}=600m$ | 0,30p | |
> | | $L\cong346m$ | 0,20p | |
> | 4.d. | Pentru: | | 0,50p |
> | | valoarea lungimii aparente a imaginii simetrice $L_i=300\,m$ | 0,50p | |
> | Punctaj total - Problema teoretică nr. 3 | | | 10p |
>
> © Barem de evaluare și de notare propus de:  
> Prof. Dr. Delia DAVIDESCU  
> Conf. univ. dr. Adrian DAFINEI
