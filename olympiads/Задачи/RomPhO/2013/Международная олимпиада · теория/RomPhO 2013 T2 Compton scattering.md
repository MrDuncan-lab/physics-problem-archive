---
id: rompho-2013-intl-theory-t2
olympiad: RomPhO
year: 2013
stage: "Международная олимпиада"
round: теория
grade: ""
number: "T2"
title: "Compton scattering"
points: 10
aliases: ["Compton scattering"]
topics: ["[[1.17 Законы сохранения энергии и импульса]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: true
source_damaged: false
summary: "Исследовать два последовательных комптоновских рассеяния фотона на электронах и определить энергии, импульсы и длины волн частиц."
status: "проверено: сверка; решение — проверено: сверка, два чтения + арбитр"
lang: en
tags: [задача]
---

# Theoretical Problem No. 2 (10 points)

**RomPhO 2013** · Международная олимпиада · теория · задача T2  
Источник: [[_pdf/RomPhO/RomPhO-2013-T2.pdf#page=1|условие, стр. 1–2]] · [[_pdf/RomPhO/RomPhO-2013-T2-solution.pdf#page=2|решение, стр. 2–8]] · [[_pdf/RomPhO/RomPhO-2013-T2-solution.pdf#page=9|критерии, стр. 9]]

Темы: [[1.17 Законы сохранения энергии и импульса]]

> [!abstract] Кратко (составлено моделью)
> Исследовать два последовательных комптоновских рассеяния фотона на электронах и определить энергии, импульсы и длины волн частиц.

## Compton scattering

An electron storage ring contains circulating electrons with high energy produced by an accelerator and rotating in an appropriate magnetic field. X - ray photons are directed so as to collide with electrons stored in storage ring. Phenomenon that occurs is known as Inverse Compton Scattering.

A photon of wavelength $\lambda_i$ is scattered by a moving, free electron. As a result the electron stops and the resulting photon of wavelength $\lambda_0$ is scattered at an angle $\theta=60^\circ$ with respect to the direction of the incident photon; this photon is again scattered by a second free electron at rest. In this second scattering process a photon with wavelength of $\lambda_f=1{,}25\times10^{-10}m$ emerges at an angle $\theta=60^\circ$ with respect to the direction of the photon of wavelength $\lambda_0$.

To characterize the photons and the electrons during the processes use the following notation:

| | initial photon | photon – after the first scattering | final photon | | first electron before collision | first electron after collision | second electron before collision | Second electron after collision |
|---|---|---|---|---|---|---|---|---|
| moment | $\vec p_i$ | $\vec p_0$ | $\vec p_f$ | moment | $\vec p_{1e}$ | 0 | 0 | $\vec p_{2e}$ |
| energy | $E_i$ | $E_0$ | $E_f$ | energy | $E_{1e}$ | $E_{0e}$ | $E_{0e}$ | $E_{2e}$ |
| wavelength | $\lambda_i$ | $\lambda_0$ | $\lambda_f$ | speed | $\vec v_{1e}$ | 0 | 0 | $\vec v_{2e}$ |

The following constants are known:

$h=6{,}6\times10^{-34}\,J\cdot s$ - Planck’s constant

$m_0=9{,}1\times10^{-31}\,kg$ - rest mass of the electron

$c=3{,}0\times10^8\,m/s$ - speed of light in vacuum

**Task No. 1 - First collision**

**1.a.** Draw simple sketches marking the moments of the electron and photon before and after the first collision. Clearly specify the coordinate system used.

**1.b.** Express the energy and moment of the electron implied in the first collision as a function of the initial speed of the electron $\vec v_{1e}$ and its rest mass $m_0$.

**1.c.** Express the energy and wavelength of the photon after the first collision as a function of the wavelength of the initial photon $\lambda_i$, the scattering angle $\theta$ and $\Lambda=h/(m_0\cdot c)$.

**Task No. 2 - Second collision**

**2.a.** Draw simple sketches marking moment of the electron and photon before and after the second collision. Clearly specify the coordinate system used.

**2.b.** Express the energy and wavelength of the photon after the second collision as a function of the wavelength of the photon before the collision $\lambda_0$, the scattering angle $\theta$ and $\Lambda=h/(m_0\cdot c)$.

**2.c.** Express the kinetic energy $(T_2=E_{2e}-E_{0e})$ and momentum $p_{2e}$ of the electron after the second collision as a function of the photon wavelengths after the collision $\lambda_f$, $m_0$, $c$ and $h$.

**Task No. 3 - Quantitative description of processes**

Using the values of the given physical constants and numerical values of $\lambda_f$ and $\theta$ determine the expressions and numerical values for:

**3.a.** the De Broglie wavelength of the initial electron;

**3.b.** the energy and frequency of the initial photon;

**3.c.** the speed of the second electron after collision;

**3.d.** the variation of the photon wavelength after each collision process.

> [!answer]- Ответ
> **1.b**
>
> $$
> \begin{cases}\vec p_{1e}=m\cdot\vec v_{1e}=\frac{m_0\cdot\vec v_{1e}}{\sqrt{1-\beta^2}}\\E_{1e}=m\cdot c^2=\frac{m_0\cdot c^2}{\sqrt{1-\beta^2}}\end{cases}
> $$
>
> **1.c**
>
> $$
> \lambda_0=\lambda_i-\Lambda\cdot(1-\cos\theta)
> $$
>
> **2.b**
>
> $$
> \begin{cases}\frac h{m_0\cdot c}\cdot(1-\cos\theta)=\lambda_f-\lambda_0\\\lambda_f-\lambda_0=\Lambda\cdot(1-\cos\theta)\end{cases}
> $$
>
> **2.c**
>
> $$
> p_{2e}=h\sqrt{\frac1{\lambda_f^2}+\frac1{(\lambda_f-\Lambda(1-\cos\theta))^2}-\frac{2\cdot\cos\theta}{\lambda_f\cdot(\lambda_f-\Lambda(1-\cos\theta))}}
> $$
>
> **2.c**
>
> $$
> T_2=h\cdot c\cdot\left(\frac1{\lambda_0}-\frac1{\lambda_f}\right)
> $$
>
> **3.a**
>
> $$
> \lambda_{1e}=1/\left(\sqrt{\frac1{\lambda_f^2}+\frac1{(\lambda_f-\Lambda(1-\cos\theta))^2}-\frac{2\cdot\cos\theta}{\lambda_f\cdot(\lambda_f-\Lambda(1-\cos\theta))}}\right)
> $$
>
> **3.a**
>
> $$
> \lambda_{1e}=10^{-10}/\left(\sqrt{\frac1{1{,}25^2}+\frac1{1{,}24^2}-\frac1{1{,}25\times1{,}24}}\right)m\cong1{,}25\times10^{-10}m
> $$
>
> **3.b**
>
> $$
> E_i=\frac{h\cdot c}{\lambda_i}=\frac{6{,}6\times10^{-34}\cdot3{,}0\times10^8}{1{,}25\times10^{-10}}\cong1{,}58\times10^{-15}J=9{,}9KeV
> $$
>
> **3.b**
>
> $$
> f_i=\frac{3\times10^8}{1{,}25\times10^{-10}}\cong2{,}4\times10^{18}Hz
> $$
>
> **3.c**
>
> $$
> m\cong m_0
> $$
>
> **3.c**
>
> $$
> v_{2e}\approx5{,}8\times10^6\,m/s=0{,}019\cdot c
> $$
>
> **3.d**
>
> $$
> \frac\Lambda2\cong0{,}01\times10^{-10}\,m
> $$

> [!solution]- Решение
> # Compton scattering - Solution
>
> **Task 1 - First collision**
>
> **1.a.** Figure 1 presents the situation before the first scattering of the photon.
>
> ![[rompho-2013-t2-solutions-p2-f1.png]]
> *Figure 1 Photon and electron before the first collision. The collision occurs in the point M*
>
> ![[rompho-2013-t2-solutions-p2-f2.png]]
> *Figure 2. Photon and electron after the first collision. The collision took place in point M*
>
> **1.b.** The angle between the directions of the electron and photon moments before collision is denoted by $\alpha$.
>
> To characterize the initial photon we will use its moment $\vec p_i$ and its energy $E_i$
> $$\begin{cases}|\vec p_i|=\frac h{\lambda_i}=\frac{h\cdot f_i}{c}\\E_i=h\cdot f_i\end{cases}\tag{1}$$
>
> $$f_i=\frac c{\lambda_i}\tag{2}$$
> is the frequency of the initial photon.
>
> For the initial free electron in motion scenario, the moment $\vec p_{1e}$ and the energy $E_{oe}$ are
>
> $$\begin{cases}\vec p_{1e}=m\cdot\vec v_{1e}=\frac{m_0\cdot\vec v_{1e}}{\sqrt{1-\beta^2}}\\E_{1e}=m\cdot c^2=\frac{m_0\cdot c^2}{\sqrt{1-\beta^2}}\end{cases}\tag{3}$$
> where $m_0$ is the rest mass of the electron and $m$ is the mass of the moving electron. As usual $\beta=v_{1e}/c$. De Broglie wavelength of the first electron is
> $$\lambda_{1e}=\frac h{p_{1e}}=\frac{h}{m_0\cdot v_{1e}}\sqrt{1-\beta^2}\tag{4}$$
>
> **1.c.** The situation after the scattering of photon is described in the figure 2. To characterize the scattered photon we will use its moment $\vec p_0$ and its energy $E_0$
> $$\begin{cases}|\vec p_o|=\frac h{\lambda_o}=\frac{h\cdot f_o}{c}\\E_o=h\cdot f_o\end{cases}\tag{5}$$
> where
> $$f_o=\frac c{\lambda_0}\tag{6}$$
> is the frequency of the scattered photon.
>
> The magnitude of the moment of the electron (that remains at rest) after the scattering is zero; its energy is $E_{0e}$. The mass of the electron after collision is $m_0$ - the mass of electron at rest state. So,
> $$E_{0e}=m_0\cdot c^2\tag{7}$$
> To determine the moment of the first moving electron, one can write the principles of conservation of moments and energy. That is
> $$\vec p_i+\vec p_{1e}=\vec p_0\tag{8}$$
> and
> $$E_i+E_{1e}=E_0+E_{0e}\tag{9}$$
> Using the referential in figures 1 and 2, the conservation of the moment in collision along the $Ox$ direction is written as
> $$\frac{h\cdot f_i}{c}+m\cdot v_{1e}\cdot\cos\alpha=\frac{h\cdot f_0}{c}\cos\theta\tag{10}$$
> and the conservation of moment along $Oy$ direction is
> $$m\cdot v_{1e}\cdot\sin\alpha=\frac{h\cdot f_0}{c}\sin\theta\tag{11}$$
> To eliminate $\alpha$, the last two equations must be written again as
> $$\begin{cases}(m\cdot v_{1e}\cdot\cos\alpha)^2=\frac{h^2}{c^2}\cdot(f_0\cdot\cos\theta-f_i)^2\\(m\cdot v_{1e}\cdot\sin\alpha)^2=\left(\frac{h\cdot f_0}{c}\sin\theta\right)^2\end{cases}\tag{12}$$
>
> and then added. The result is
> $$m^2\cdot v_{1e}^2=\frac{h^2}{c^2}\cdot(f_0^2+f_i^2-2f_0\cdot f_i\cdot\cos\theta)\tag{13}$$
> or
> $$\frac{m_0^2\cdot c^2}{1-(v_{1e}/c)^2}\cdot v_{1e}^2=h^2\cdot(f_0^2+f_i^2-2f_0\cdot f_i\cdot\cos\theta)\tag{14}$$
> The conservation of energy (9) can be written again as
> $$m\cdot c^2+h\cdot f_i=m_0\cdot c^2+h\cdot f_0\tag{15}$$
> or
> $$\frac{m_0\cdot c^2}{\sqrt{1-(v_{1e}/c)^2}}=m_0\cdot c^2+h\cdot(f_0-f_i)\tag{16}$$
> Squaring the last relation results in the following
> $$\frac{m_0^2\cdot c^4}{1-(v_{1e}/c)^2}=m_0^2\cdot c^4+h^2\cdot(f_0-f_i)^2+2m_0\cdot h\cdot c^2\cdot(f_0-f_i)\tag{17}$$
> Subtracting (14) from (17) the result is
> $$2m_0\cdot c^2\cdot h\cdot(f_0-f_i)+2h^2\cdot f_i\cdot f_0\cdot\cos\theta-2h^2\cdot f_i\cdot f_0=0\tag{18}$$
> or
> $$\frac h{m_0\cdot c}(1-\cos\theta)=\frac c{f_i}-\frac c{f_0}\tag{19}$$
> Using
> $$\Lambda=\frac h{m_0\cdot c}\tag{20}$$
> the relation (19) becomes
> $$\Lambda\cdot(1-\cos\theta)=\lambda_i-\lambda_0\tag{21}$$
> The wavelength of scattered photon is
>
> $$\lambda_0=\lambda_i-\Lambda\cdot(1-\cos\theta)\tag{22}$$
> Equation (22) show that the scattered photon wavelength is shorter than the wavelength of the initial photon. Consequently the energy of the scattered photon is greater that the energy of the initial photon.
> $$\begin{cases}\lambda_0<\lambda_i\\E_0>E_i\end{cases}\tag{23}$$
>
> **Task 2 - Second collision**
>
> **2.a.** Let’s analyze now the second collision process that occurs at point $N$. To study that, let’s consider a new referential having the $Ox$ axis along the direction of the photon scattered after the first collision.
>
> ![[rompho-2013-t2-solutions-p5-f1.png]]
> *Figure 3 Photon and electron before the second collision. The collision occur at the point N*
>
> ![[rompho-2013-t2-solutions-p5-f2.png]]
> *Figure 4 Photon and electron after the second collision. The collision took place at the point N. The scattering angle for electron is denoted by $\beta$.*
>
> Figure 3 presents the situation before the second collision and Figure 4 presents the situation after this scattering process.
>
> **2.b.** The conservation law for moments in the scattering process gives
> $$\begin{cases}\frac h{\lambda_0}=\frac h{\lambda_f}\cos\theta+m\cdot v_{2e}\cdot\cos\beta\\\frac h{\lambda_f}\sin\theta-m\cdot v_{2e}\cdot\sin\beta=0\end{cases}\tag{24}$$
> To eliminate the unknown angle $\beta$, one must square and then add equations (24). That is
> $$\begin{cases}\left(\frac h{\lambda_0}-\frac h{\lambda_f}\cos\theta\right)^2=(m\cdot v_{2e}\cdot\cos\beta)^2\\\left(\frac h{\lambda_f}\sin\theta\right)^2=(m\cdot v_{2e}\cdot\sin\beta)^2\end{cases}\tag{25}$$
> and
> $$\left(\frac h{\lambda_f}\right)^2+\left(\frac h{\lambda_0}\right)^2-\frac{2\cdot h^2}{\lambda_0\cdot\lambda_f}\cos\theta=(m\cdot v_{2e})^2\tag{26}$$
> or
> $$\frac{h^2\cdot c^2}{\lambda_f^2}+\frac{h^2\cdot c^2}{\lambda_0^2}-\frac{2\cdot h^2\cdot c^2}{\lambda_0\cdot\lambda_f}\cos\theta=m^2\cdot c^2\cdot v_{2e}^2\tag{27}$$
> The conservation law for energies in the second scattering process gives
>
> $$\frac{h\cdot c}{\lambda_0}+m_0\cdot c^2=\frac{h\cdot c}{\lambda_f}+m\cdot c^2\tag{28}$$
> or
> $$h^2\cdot c^2\cdot\left(\frac1{\lambda_f}-\frac1{\lambda_0}\right)^2+m_0^2\cdot c^4+2h\cdot c^3\cdot m_0\cdot\left(\frac1{\lambda_f}-\frac1{\lambda_0}\right)=\frac{m_0^2\cdot c^4}{1-(v_{2e}/c)^2}\tag{29}$$
> Subtracting (27) from (29), one obtains
> $$+\frac{2\cdot h^2\cdot c^2}{\lambda_0\cdot\lambda_f}\cos\theta-\frac{2\cdot h^2\cdot c^2}{\lambda_0\cdot\lambda_f}+2h\cdot c^3\cdot m_0\cdot\left(\frac1{\lambda_f}-\frac1{\lambda_0}\right)=0\tag{30}$$
> that is
>
> $$\begin{cases}\frac h{m_0\cdot c}\cdot(1-\cos\theta)=\lambda_f-\lambda_0\\\lambda_f-\lambda_0=\Lambda\cdot(1-\cos\theta)\end{cases}\tag{31}$$
> Concluding
> $$\begin{cases}\lambda_f>\lambda_0\\E_f<E_0\end{cases}\tag{32}$$
> Comparing (31) written as
> $$\lambda_f=\lambda_0+\Lambda\cdot(1-\cos\theta)\tag{33}$$
> and (22) written as
> $$\lambda_i=\lambda_0+\Lambda\cdot(1-\cos\theta)\tag{34}$$
> results in
> $$\lambda_i=\lambda_f\tag{35}$$
>
> **2.c.** Taking into account (26), the moment of the electron after the second collision is
> $$p_{2e}=h\sqrt{\frac1{\lambda_f^2}+\frac1{\lambda_0^2}-\frac{2\cdot\cos\theta}{\lambda_f\cdot\lambda_0}}\tag{36}$$
> Or, considering (33), the moment can be rewritten as
>
> $$p_{2e}=h\sqrt{\frac1{\lambda_f^2}+\frac1{(\lambda_f-\Lambda(1-\cos\theta))^2}-\frac{2\cdot\cos\theta}{\lambda_f\cdot(\lambda_f-\Lambda(1-\cos\theta))}}\tag{37}$$
> The expression of the de Broglie wavelength of the second electron after scattering is
> $$\lambda_{2e}=1/\left(\sqrt{\frac1{\lambda_f^2}+\frac1{(\lambda_f-\Lambda(1-\cos\theta))^2}-\frac{2\cdot\cos\theta}{\lambda_f\cdot(\lambda_f-\Lambda(1-\cos\theta))}}\right)\tag{38}$$
> From (28) results
> $$\frac{h\cdot c}{\lambda_0}=\frac{h\cdot c}{\lambda_f}+T_2\tag{39}$$
> that is
>
> $$T_2=h\cdot c\cdot\left(\frac1{\lambda_0}-\frac1{\lambda_f}\right)\tag{40}$$
>
> **Task 3 - Quantitative description of processes**
>
> **3.a.** The relation (13) can be written as
> $$p_{1e}=h\sqrt{\frac1{\lambda_i^2}+\frac1{\lambda_0^2}-\frac{2\cdot\cos\theta}{\lambda_i\cdot\lambda_0}}\tag{41}$$
> or, considering (34) and (35)
>
> $$p_{1e}=h\sqrt{\frac1{\lambda_f^2}+\frac1{(\lambda_f-\Lambda(1-\cos\theta))^2}-\frac{2\cdot\cos\theta}{\lambda_f\cdot(\lambda_f-\Lambda(1-\cos\theta))}}\tag{42}$$
> so that the expression of the de Broglie wavelength of the first electron before scattering is
>
> $$\lambda_{1e}=1/\left(\sqrt{\frac1{\lambda_f^2}+\frac1{(\lambda_f-\Lambda(1-\cos\theta))^2}-\frac{2\cdot\cos\theta}{\lambda_f\cdot(\lambda_f-\Lambda(1-\cos\theta))}}\right)\tag{43}$$
> In the condition of the problem (43) becomes
> $$\lambda_{1e}=1/\left(\sqrt{\frac1{\lambda_f^2}+\frac1{(\lambda_f-\Lambda/2)^2}-\frac1{\lambda_f\cdot(\lambda_f-\Lambda/2)}}\right)\tag{44}$$
> Because the value of $\lambda_f$ and $\Lambda$ are known as
> $$\begin{cases}\lambda_f=\lambda_i=1{,}25\times10^{-10}m\\\Lambda=\frac{6{,}6\times10^{-34}}{9{,}1\times10^{-31}\cdot3{,}0\times10^8}m=2{,}41\times10^{-12}m=0{,}02\times10^{-10}m\end{cases}\tag{45}$$
> From (33) results that
> $$\lambda_0=\lambda_f-\Lambda\cdot(1-\cos\theta)=\lambda_f-\frac\Lambda2\tag{46}$$
> or
> $$\lambda_0=1{,}24\times10^{-10}m\tag{47}$$
> The numerical value of the de Broglie wavelength of the first electron before scattering is
>
> $$\lambda_{1e}=10^{-10}/\left(\sqrt{\frac1{1{,}25^2}+\frac1{1{,}24^2}-\frac1{1{,}25\times1{,}24}}\right)m\cong1{,}25\times10^{-10}m\tag{48}$$
> Evidently the de Broglie wavelength $\lambda_{2e}$ for the second electron after the scattering is the same
> $$\lambda_{1e}=\lambda_{2e}\tag{49}$$
>
> **3.b.** Because $\lambda_f=\lambda_i$ the energy of the first photon before the first scattering has the following expression
> $$E_i=\frac{h\cdot c}{\lambda_i}=\frac{h\cdot c}{\lambda_f}\tag{50}$$
> Its numerical value is
>
> $$E_i=\frac{h\cdot c}{\lambda_i}=\frac{6{,}6\times10^{-34}\cdot3{,}0\times10^8}{1{,}25\times10^{-10}}\cong1{,}58\times10^{-15}J=9{,}9KeV\tag{51}$$
> The frequency $f_i$ of the first photon before the first scattering has the following expression
> $$f_i=\frac c{\lambda_i}=\frac c{\lambda_f}\tag{52}$$
> Its numerical value is
>
> $$f_i=\frac{3\times10^8}{1{,}25\times10^{-10}}\cong2{,}4\times10^{18}Hz\tag{53}$$
>
> **3.c.** From (40) written as
> $$T_2=T_1=m\cdot c^2-m_0\cdot c^2=h\cdot c\cdot\left(\frac1{\lambda_0}-\frac1{\lambda_f}\right)\tag{54}$$
> results
> $$m=m_0+\frac hc\cdot\left(\frac1{\lambda_f-(\Lambda/2)}-\frac1{\lambda_f}\right)\cong m_0+\frac hc\cdot\frac\Lambda{2\lambda_f^2}=m_0\cdot\left(1+\frac12\left(\frac h{m_0\cdot c\cdot\lambda_f}\right)^2\right)\tag{55}$$
> Its numerical value is
>
> $$m\cong m_0\tag{56}$$
> Consequently, the speed of the second electron after the collision $v_{2e}$ has the following expression
> $$v_{2e}=\frac h{\lambda_f\cdot m}\approx\frac h{\lambda_f\cdot m_0}\tag{57}$$
> Its numerical value is
>
> $$v_{2e}\approx5{,}8\times10^6\,m/s=0{,}019\cdot c\tag{58}$$
> **3.d.** As results from (46)
> $$\lambda_i-\lambda_0=\lambda_f-\lambda_0=\frac\Lambda2\tag{59}$$
> The numerical value of the variation of wavelength is
>
> $$\frac\Lambda2\cong0{,}01\times10^{-10}\,m\tag{60}$$
>
> © Solution proposed by  
> Delia DAVIDESCU, PhD  
> Adrian DAFINEI, PhD

> [!grading]- Критерии оценивания
> Barem de evaluare și de notare  
> Se punctează oricare altă modalitate de rezolvare corectă a problemei
>
> Problema teoretică nr. 2 – Împrăștiere Compton
>
> | Nr. item | Sarcina de lucru nr. 1 – Prima ciocnire | | Punctaj |
> |---|---|---|---|
> | 1.a. | Pentru: ![[rompho-2013-t2-solutions-p9-c1325.png]] ![[rompho-2013-t2-solutions-p9-f3.png]] | 0,50p | 0,50p |
> | 1.b. | Pentru: expresia energiei electronului implicat în prima ciocnire $E_{1e}=m\cdot c^2=\dfrac{m_0\cdot c^2}{\sqrt{1-\beta^2}}$ | 0,40p | 0,80p |
> | | expresia impulsului electronului implicat în prima ciocnire $\vec p_{1e}=m\cdot\vec v_{1e}=\dfrac{m_0\cdot\vec v_{1e}}{\sqrt{1-\beta^2}}$ | 0,40p | |
> | 1.c. | Pentru: $\begin{cases}\lvert\vec p_o\rvert=\dfrac h{\lambda_o}=\dfrac{h\cdot f_o}{c},\ \text{unde }f_o=\dfrac c{\lambda_0}\\ E_o=h\cdot f_o\end{cases}$ | 0,20p | 1,20p |
> | | legile de conservare ale impulsului și energiei $\vec p_i+\vec p_{1e}=\vec p_0$, $E_i+E_{1e}=E_0+E_{0e}$ | 0,40p | |
> | | expresia lungimii de undă a fotonului după prima împrăștiere $\lambda_0=\lambda_i-\Lambda\cdot(1-\cos\theta)$, unde $\Lambda=\dfrac h{m_0\cdot c}$ | 0,40p | |
> | | expresia energiei fotonului după prima împrăștiere $E_o=\dfrac{h\cdot c}{\lambda_i-\Lambda\cdot(1-\cos\theta)}$ | 0,20p | |
>
> | Nr. item | Sarcina de lucru nr. 2 – A doua ciocnire | | Punctaj |
> |---|---|---|---|
> | 2.a. | Pentru: ![[rompho-2013-t2-solutions-p10-c1108.png]] | 0,50p | 0,50p |
> | 2.b. | Pentru: legea de conservare a impulsului $\begin{cases}\dfrac h{\lambda_0}=\dfrac h{\lambda_f}\cos\theta+m\cdot v_{2e}\cdot\cos\beta\\\dfrac h{\lambda_f}\sin\theta-m\cdot v_{2e}\cdot\sin\beta=0\end{cases}$ | 0,40p | 1,20p |
> | | legea de conservare a energiei $\dfrac{h\cdot c}{\lambda_0}+m_0\cdot c^2=\dfrac{h\cdot c}{\lambda_f}+m\cdot c^2$ | 0,20p | |
> | | expresia lungimii de undă a fotonului după a doua împrăștiere $\lambda_f=\lambda_0+\Lambda\cdot(1-\cos\theta)$ | 0,40p | |
> | | expresia energiei fotonului după a doua împrăștiere $E_f=\dfrac{h\cdot c}{\lambda_0+\Lambda\cdot(1-\cos\theta)}$ | 0,20p | |
> | 2.c. | Pentru: expresia impulsului electronului după a doua ciocnire $\lambda_{2e}=1/\left(\sqrt{\dfrac1{\lambda_f^2}+\dfrac1{(\lambda_f-\Lambda(1-\cos\theta))^2}-\dfrac{2\cdot\cos\theta}{\lambda_f\cdot(\lambda_f-\Lambda(1-\cos\theta))}}\right)$, unde $\Lambda=\dfrac h{m_0\cdot c}$ | 0,40p | 0,80p |
> | | expresia energiei cinetice a electronului după a doua ciocnire $\begin{cases}T_2=h\cdot c\cdot\left(\dfrac1{\lambda_0}-\dfrac1{\lambda_f}\right)\\T_2=h\cdot c\cdot\left(\dfrac1{\lambda_f-\Lambda\cdot(1-\cos\theta)}-\dfrac1{\lambda_f}\right)\end{cases}$ | 0,40p | |
>
> | Nr. item | Sarcina de lucru nr. 3 – O descriere cantitativă a proceselor | | Punctaj |
> |---|---|---|---|
> | 3.a. | Pentru: expresia pentru lungimea de undă de Broglie a electronului inițial $\lambda_{1e}=\left(\dfrac1{\lambda_f^2}+\dfrac1{\left(\lambda_f-\dfrac\Lambda2\right)^2}-\dfrac1{\lambda_f\cdot\left(\lambda_f-\dfrac\Lambda2\right)}\right)^{-\frac12}$ | 1,00p | 2,00p |
> | | valoarea numerică pentru lungimea de undă de Broglie a electronului inițial $\lambda_{1e}\cong1{,}25\cdot10^{-10}\,m$ | 1,00p | |
> | 3.b. | Pentru: expresia energiei fotonului inițial $E_i=\dfrac{h\cdot c}{\lambda_i}=\dfrac{h\cdot c}{\lambda_f}$ | 0,30p | 1,00p |
> | | expresia frecvenței fotonului inițial $f_i=\dfrac c{\lambda_i}=\dfrac c{\lambda_f}$ | 0,20p | |
> | | valoarea energiei fotonului inițial $\begin{cases}E_i\cong1{,}58\times10^{-15}\,J\\E_i\cong9{,}9\,KeV\end{cases}$ | 0,30p | |
> | | valoarea frecvenței fotonului inițial $f_i\cong2{,}4\times10^{18}\,Hz$ | 0,20p | |
> | 3.c. | Pentru: expresia vitezei celui de al doilea electron după ciocnire $v_{2e}=\dfrac h{\lambda_f\cdot m}\approx\dfrac h{\lambda_f\cdot m_0}$ | 0,50p | 1,00p |
> | | valoarea vitezei celui de al doilea electron după ciocnire $\begin{cases}v_{2e}\cong5{,}8\times10^6\,m/s\\v_{2e}\cong0{,}019\cdot c\end{cases}$ | 0,50p | |
> | 3.d. | Pentru: expresia pentru variația lungimii de undă a fotonului, după fiecare dintre ciocniri $\lambda_i-\lambda_0=\lambda_f-\lambda_0=\dfrac\Lambda2$ | 0,50p | 1,00p |
> | | valoarea numerică pentru variația lungimii de undă a fotonului, după fiecare dintre ciocniri $\dfrac\Lambda2\cong0{,}01\times10^{-10}\,m$ | 0,50p | |
> | Punctaj total - Problema teoretică nr. 2 | | | 10p |
>
> © Barem de evaluare și de notare propus de:  
> Prof. Dr. Delia DAVIDESCU  
> Conf. univ. dr. Adrian DAFINEI
