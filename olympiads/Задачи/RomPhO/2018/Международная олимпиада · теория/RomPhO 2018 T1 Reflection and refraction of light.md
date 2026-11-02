---
id: rompho-2018-intl-theory-t1
olympiad: RomPhO
year: 2018
stage: "Международная олимпиада"
round: теория
grade: ""
number: "T1"
title: "Reflection and refraction of light"
aliases: ["Reflection and refraction of light"]
topics: ["[[6.1 Отражение]]", "[[6.2 Преломление]]", "[[6.5 Волновая оптика]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Исследовать прохождение и дисперсию света в ромбической призме, полное внутреннее отражение и возникающую при нём затухающую волну."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# Reflection and refraction of light

**RomPhO 2018** · Международная олимпиада · теория · задача T1  
Источник: [[_pdf/RomPhO/RomPhO-2017-T1.pdf#page=1|условие, стр. 1–5]] · [[_pdf/RomPhO/RomPhO-2017-T1-solution.pdf#page=1|решение, стр. 1–9]]

> [!info] Год
> Год исправлен: в архиве файл подписан 2017, и на шапке листов стоит «Romanian Master of Physics 2017», но RMPh 2017 — октябрьский тур 2017 года с другими задачами; этот комплект в архиве олимпиады числится как RMPh 2018.

Темы: [[6.1 Отражение]], [[6.2 Преломление]], [[6.5 Волновая оптика]]

> [!abstract] Кратко (составлено моделью)
> Исследовать прохождение и дисперсию света в ромбической призме, полное внутреннее отражение и возникающую при нём затухающую волну.

**A. An interesting prism**

The main section of a glass prism, situated in air ($n'=1.00$), has the form of a rhomb with $\angle BAD=\angle BCD=\theta$. A thin yellow beam of monochromatic light, propagating towards the prism, parallel with the diagonal AC of the rhomb, is incident on the face AB (Fig. 1). The beam is totally reflected on the faces AD and DC, then emerges through its face BC. For the yellow radiation, the refraction index of the glass is $n=1.60$.

![[rompho-2017-t1-problems-p1-f1.png]]
*Fig. 1*

**A1** Derive the mathematical expression for the angle $\theta$ as a function of the refraction index $n$ of the prism, such that the total deviation of the beam that exits the prism to be zero. Under the above condition, calculate the numerical value of $\theta$ in degrees and minutes, if $n=1.60$. 2.25 p

The prism with $\theta$ determined above and the direction of the incident beam remain fixed, but the nature of the light radiation changes, being formed now of the yellow doublet of the mercury. The two wavelengths have the values 579.1 nm, respectively 577 nm. The refraction indices of the glass for these wavelengths are $n=1.60$, respectively $n+\Delta n$, where $\Delta n=1.3\cdot10^{-4}$. The light rays that exit the prism enter longitudinally into an astronomical telescope adjusted for infinite distance.

**A2** Derive the mathematical expression for „the angular distance” $\varepsilon$ between the two images seen through the telescope (first as a function of $\theta$ and $\Delta n$, then as a function of $n$ and $\Delta n$) and calculate its numerical value. 2.00 p

**A3** If the focal distance of the telescope’s objective is $f_{ob}=0.40\,m$, derive the linear distance $y$ between the two images, seen in the focal plane of the objective and calculate its numerical value. 0.50 p

**B. Refraction, but…mostly reflection**

**B1. Total reflection in geometrical optics**

Total reflection occurs when light travels from a medium with refractive index $n_1$ to another one, with the refractive index $n_2<n_1$, at an incidence angle $\theta_1\geq l$, where $l$ is the critical value of the incidence angle, called limit angle, beyond which there will be no refracted light. At total reflection, the entire energy of the incident light beam goes to the reflected beam.

**B1** Derive the mathematical expression for the limit angle. 0.25 p

**B2. Total reflection in electromagnetic optics**

Electromagnetic optics proves that, besides being totally reflected, the incident light beam also penetrates the less refringent medium as an evanescent wave.

![[rompho-2017-t1-problems-p2-f2.png]]
*Fig. 2*

The characteristics of the reflected and the refracted light beams depend on the angle of incidence, as well as on the orientation of the electric field of the light wave (called polarization). For simplicity, let us consider that the electric field intensity is perpendicular on the incidence plane, as represented in Fig. 2. The indices $i$, $r$, and $t$ refer to the incident, reflected and transmitted properties of light waves while $\vec k$ is the wave vector, giving the light propagation orientation. Moreover, $\hat x$, $\hat y$ and $\hat z$ are the unit vectors of the chosen Cartesian reference frame.

**Physical note:** The perturbation produced by a plane, monochromatic wave in a point in space at a certain moment of time can be written as $\vec E(\vec r,t)=\vec E_0\cos(\omega t-\vec k\cdot\vec r)$, or, to simplify calculations, in the complex form $\vec e(\vec r,t)=\vec E_0e^{i(\omega t-\vec k\cdot\vec r)}$, where $i=\sqrt{-1}$, and then taking only the real part of the result.

**Mathematical note:** For the complex number $z=a\pm ib$, $a$ is the real part and $b$ is the imaginary part. It can be written as

$$z=\underbrace{\sqrt{a^2+b^2}}_{=|z|}\left(\underbrace{\frac a{\sqrt{a^2+b^2}}}_{=\cos\varphi}\pm i\underbrace{\frac b{\sqrt{a^2+b^2}}}_{=\sin\varphi}\right)=|z|e^{\pm i\varphi},$$

where $|z|$ is the modulus of the complex number $z$ and $\tan\varphi=b/a$.

**B2.1. Evanescent wave**

**B2.1** Knowing that the incident wave is a plane and monochromatic one, characterized by the equation $\vec e_i(\vec r,t)=\vec E_{0i}e^{i(\omega t-\vec k_i\cdot\vec r)}$, prove that the mathematical expression for the evanescent wave is $\vec e_t(\vec r,t)=\vec E_{0t}e^{-\alpha z}e^{i\varphi}$ and derive the exact expression for the attenuation coefficient $\alpha$ as a function of the incidence angle $\theta_1$, the limit angle $l$, and the wavelength $\lambda$ of the incident wave. Also, derive the exact expression for the phase $\varphi$ of the evanescent wave. 1.50 p

**B2.2. Penetration depth**

**B2.2** Derive the mathematical expression of the distance $\Delta z$ from the interface at which the amplitude of the evanescent wave is $e$ times smaller than at the interface, as a function of the incident wavelength $\lambda$ and calculate its numerical value. The first medium is glass ($n_1=1.6$), the second is air ($n_2=1.0$), and the incidence angle of light is $\theta_1=40^\circ$. 0.50 p

**B2.3. The phase speed of the evanescent wave**

**B2.3** Derive the mathematical expression for the ratio $v_e/v_1$, where $v_e$ is the phase speed of the evanescent wave and $v_1$ - the phase speed of the incident wave, and compute its numerical value for the case of the incidence angle of light of $\theta_1=40^\circ$. 0.75 p

**B2.4. The energy transferred from the incident wave to the totally reflected wave**

For any value of the incidence angle, the relationship between the amplitude of the field of the reflected wave and that of the incident wave was derived by the French physicist Augustin Fresnel (1788 – 1829):

$$E_{0r}=\frac{n_1\cos\theta_1-n_2\cos\theta_2}{n_1\cos\theta_1+n_2\cos\theta_2}E_{0i}.$$

**Physical note:** If the perturbation produced by a wave in a point in space at a given moment is expressed using complex numbers, then the wave intensity has the mathematical expression $I=\frac12\varepsilon_0cE_0^*E_0=\frac12\varepsilon_0c|E_0|^2$, where $E_0^*=a-ib$ is the complex conjugate of the complex number $E_0=a+ib$. Here $\varepsilon_0$ is the vacuum permittivity and $c$ is the speed of light in vacuum.

**B2.4** Prove that the totally reflected wave has the same intensity as the incident wave. 0.50 p

**B2.5. The Goos – Hänchen effect**

When an incident wave beam with a finite cross section undergoes total reflection at an interface between two media, the totally reflected wave beam is laterally displaced, on a distance $D$ (see Fig. 3), that was measured for the first time by Goos and Hänchen in 1947. In Fig. 3, the displacement along the surface is $s$, and the Goos – Hänchen shift is the lateral shift $D$ indicated in the diagram. This is the Goos – Hänchen effect. The explanation of this lateral shift is based on the appearance of the evanescent wave at the interface and its propagation parallel to the interface.

![[rompho-2017-t1-problems-p4-f1.png]]
*Fig. 3*

**B2.5.1. The lateral shift**

**B2.5.1** Derive the mathematical expression for the Goos – Hänchen lateral shift $D$, admitting that the phase difference between the totally reflected wave and the incident one is zero at the interface. Consequently, compute the numerical value of the displacement $s$ along the interface as a function of the wavelength $\lambda$ of the incident light, if the first medium is glass ($n_1=1.6$), the second is air ($n_2=1.0$), and the incidence angle of light is $\theta_1=40^\circ$. 1.00 p

**B2.5.2. Time needed for the total reflection**

An alternative explanation of the Goos – Hänchen shift can be given in terms of the time delay associated with the scattering of a radiation pulse at the interface. The incident radiation pulse is not scattered instantaneously by the surface, but reemerges into medium 1 after a time delay $\tau$, during which the pulse propagates parallel to the surface and is displaced by the distance $s$.

**B2.5.2.** Derive the mathematical expression for the time delay $\tau$ and calculate its value if the first medium is glass ($n_1=1.6$), the second is air ($n_2=1.0$), the incidence angle of light is $\theta_1=40^\circ$, and the monochromatic radiation has the wavelength $\lambda=579.1\,nm$. The light speed in vacuum is $c=3.0\cdot10^8\,m/s$. 0.75 p

> [!answer]- Ответ
> **A1**
>
> $$
> \cos(\theta/2)=\sqrt{\frac{3n+1}{4n}}=0.952,\qquad (0.75p)
> $$
>
> **A1**
>
> $$
> \theta=35^\circ40',\qquad (0.25\ p)
> $$
>
> **A2**
>
> $$
> \varepsilon=2\frac{\sin r}{\cos i}dn=2\left[\frac{\cos(3\theta/2)}{\sin(\theta/2)}\right]dn.\qquad (0,50\ p)
> $$
>
> **A2**
>
> $$
> \varepsilon=2\frac{dn}{n}\sqrt{\frac{3n+1}{n-1}}\qquad (0,50\ p)
> $$
>
> **A2**
>
> $$
> \varepsilon=5.1\cdot10^{-4}\,rad\quad(\text{or }1.7')\qquad (0.25\ p)
> $$
>
> **A3**
>
> $$
> y=f_{ob}\operatorname{tg}\varepsilon\approx\varepsilon f_{ob}=2\left(\frac{dn}{n}\right)f_{ob}\sqrt{\frac{3n+1}{n-1}}.
> $$
>
> **A3**
>
> $$
> y=0.20\,mm\qquad (0.50\ p)
> $$
>
> **B1**
>
> $$
> l=\arcsin\frac{n_2}{n_1}.
> $$
>
> **B2.1**
>
> $$
> \varphi=\omega t-k_ty\frac{n_1}{n_2}\sin\theta_1
> $$
>
> **B2.1**
>
> $$
> \alpha=k_i\sqrt{\sin^2\theta_1-\frac{n_2^2}{n_1^2}}=\frac{2\pi}{\lambda}\sqrt{\sin^2\theta_1-\frac{n_2^2}{n_1^2}}=\frac{2\pi}{\lambda}\sqrt{\sin^2\theta_1-\sin^2 l}.
> $$
>
> **B2.2**
>
> $$
> \Delta z=\frac1\alpha=1.1\lambda.
> $$
>
> **B2.3**
>
> $$
> \frac{v_e}{v_1}=\frac1{\sin\theta_1}=1.6.
> $$
>
> **B2.4**
>
> $$
> I_r=\frac12\varepsilon_0c|E_{0r}|^2=\frac12\varepsilon_0c|E_{0i}|^2=I_i.
> $$
>
> **B2.5.1**
>
> $$
> D=\frac\lambda\pi\frac{\tan^{-1}\left(\frac{\sqrt{\sin^2\theta_1-\sin^2l}}{\cos\theta_1}\right)}{\tan\theta_1}.
> $$
>
> **B2.5.1**
>
> $$
> s=5.5\lambda.
> $$
>
> **B2.5.2**
>
> $$
> \tau=\frac{s}{v_{1y}}=\frac{s}{v_1\sin\theta_1}=\frac{sn_1}{c\sin\theta_1}=\frac{\lambda n_1}{\pi c}\frac1{\sin^2\theta_1}\tan^{-1}\left(\frac{\sqrt{\sin^2\theta_1-\sin^2l}}{\cos\theta_1}\right)=2.6\cdot10^{-14}\,s.
> $$

> [!solution]- Решение
> **Solution:** The total deviation is zero only if I’R ∥ SI. This means that $i'=i$ and $r'=r$ (symmetrical path inside of the rhombic prism). Therefore $JJ'\parallel AC\parallel SI\parallel I'R$ (0.25 p)
>
> From the figure below, $m(\widehat{JJ'D})=m(\widehat{J'JD})=\theta/2$ and $m(\widehat{AJI})=m(\widehat{CJ'I'})=\theta/2$.
>
> In the $\triangle AIJ$: $\theta+\pi/2+r+\theta/2=\pi$, so that $r=\pi/2-3\theta/2$ (0.25 p)
>
> ![[rompho-2017-t1-solutions-p1-c2173.png]]
>
> On the other hand, $i=\pi/2-\theta/2$ (0,25 p)
>
> The refraction law (Snell-Descartes) is $\sin(\pi/2-\theta/2)=n\sin(\pi/2-3\theta/2)$, or $\cos(\theta/2)=n\cos(3\theta/2)$. (0,50 p)
>
> Since
>
> $$\cos(3\theta/2)=\cos(\theta+\theta/2)=\cos\theta\cos(\theta/2)-\sin\theta\sin(\theta/2)$$
> $$=[2\cos^2(\theta/2)-1]\cos(\theta/2)-2\sin^2(\theta/2)\cos(\theta/2)=\ldots=4\cos^3(\theta/2)-3\cos(\theta/2),$$
>
> the refraction law becomes $\cos(\theta/2)[1-n[4\cos^2(\theta/2)-3]]=0$. The solution $\theta=\pi$ (i.e. $180^\circ$) cannot be accepted as unphysical, so, the physical solution is
>
> $$\cos(\theta/2)=\sqrt{\frac{3n+1}{4n}}=0.952,\qquad (0.75p)$$
>
> i.e.,
>
> $$\theta=35^\circ40',\qquad (0.25\ p)$$
>
> **Solution:** We have a fixed angle of incidence ($i=$ constant) and two angles of refraction $r$ and $r-dr$, corresponding to $n$ and $n+dn$. From $\sin i=n\sin r$ we can write $0=dn\sin r+n\cos r\,dr$. On the other hand, from $\sin i'=n\sin r'$, we can write $\cos i'\,di'=dn\sin r'+n\cos r'\,dr'$. Because $dn$ (or $\Delta n$, as in the text of the question) is a very small (infinitesimal) quantity, we can approximate $i'=i$ and $r'=r$, but with $di'\ne di$ ($=0$) and $dr'\ne dr$ ($\ne0$). (0.50 p)
>
> We will demonstrate later (see Note below) that $dr'=-dr$. Now, let us determine the angle between the two emergent rays of light, namely $\varepsilon\equiv di'$, obtaining
>
> $$\varepsilon=\frac{\sin r}{\cos i}dn+n\frac{\cos r}{\cos i}(-dr)\quad\text{with }dr=-\operatorname{tg}r\frac{dn}{n}.$$
>
> The final result is
>
> $$\varepsilon=2\frac{\sin r}{\cos i}dn=2\left[\frac{\cos(3\theta/2)}{\sin(\theta/2)}\right]dn.\qquad (0,50\ p)$$
>
> We know the mathematical expression of $\cos(\theta/2)$ and, after a little algebra, $\varepsilon$ can be expressed in another form, namely
>
> $$\varepsilon=2\frac{dn}{n}\sqrt{\frac{3n+1}{n-1}}\qquad (0,50\ p)$$
>
> Numerically:
>
> $$\varepsilon=5.1\cdot10^{-4}\,rad\quad(\text{or }1.7')\qquad (0.25\ p)$$
>
> **Note:** In the triangle JDJ’ we write that the sum of inner angles is $\pi$ (radians), namely $(\pi/2-\alpha)+(\pi-\theta)+(\pi/2-\beta)=\pi$, i.e. $\alpha+\beta=\pi-\theta=$ constant (for a given rhombic prism, with fixed $\theta$). Therefore $d\alpha=-d\beta$, where $\alpha=\theta+r$ (see the triangle AIJ) and $\beta=\theta+r'$ (see the triangle CI’J’). Since $\theta$ is fixed (our situation) $d\alpha=dr$ and $d\beta=dr'$ so that $dr=-dr'$. (0.25 p)
>
> **Solution:**
>
> $$y=f_{ob}\operatorname{tg}\varepsilon\approx\varepsilon f_{ob}=2\left(\frac{dn}{n}\right)f_{ob}\sqrt{\frac{3n+1}{n-1}}.$$
>
> Numerically:
>
> $$y=0.20\,mm\qquad (0.50\ p)$$
>
> **Solution:** When the incidence angle $\theta_1$ reaches the limit angle $l$, the refraction angle will be $\theta_2=90^\circ$. In this case, the second Snell’s refraction law gives $n_1\sin l=n_2$, so
>
> $$l=\arcsin\frac{n_2}{n_1}.$$
>
> **Solution:** For the transmitted wave
>
> $$\vec e_t(\vec r,t)=\vec E_{0t}e^{i(\omega t-\vec k_t\cdot\vec r)},$$
>
> where
>
> $$\vec k_t\cdot\vec r=(\hat yk_t\sin\theta_2+\hat zk_t\cos\theta_2)\cdot(\hat y y+\hat z z)=k_t(y\sin\theta_2+z\cos\theta_2).$$
>
> Since $n_1\sin\theta_1=n_2\sin\theta_2$, then
>
> $$\cos\theta_2=\pm\sqrt{1-\sin^2\theta_2}=\pm\sqrt{1-\frac{n_1^2}{n_2^2}\sin^2\theta_1}=\pm i\sqrt{\frac{n_1^2}{n_2^2}\sin^2\theta_1-1},$$
>
> because $\theta_1>l$. Under these conditions the electric field of the transmitted wave can be written as
>
> $$\vec e_t(\vec r,t)=\vec E_{0t}e^{\pm k_tz\sqrt{\frac{n_1^2}{n_2^2}\sin^2\theta_1-1}}e^{i\left(\omega t-k_ty\frac{n_1}{n_2}\sin\theta_1\right)}.$$
>
> The + sign in the first exponential has no physical significance because there is no wave at appreciable distances from the interface. In conclusion, the electric field of the transmitted (evanescent) wave has the form $\vec e_t(\vec r,t)=\vec E_{0t}e^{-\alpha z}e^{i\varphi}$, where $\alpha=k_t\sqrt{\frac{n_1^2}{n_2^2}\sin^2\theta_1-1}$ is the attenuation coefficient of the evanescent wave and
>
> $$\varphi=\omega t-k_ty\frac{n_1}{n_2}\sin\theta_1$$
>
> is the wave’s phase. This result shows that the wave travels along the interface (along y direction) and that it is attenuated in the z direction (perpendicular on the interface). Because
>
> $$k_t=\frac\omega{v_2}=\frac\omega{v_1}\frac{v_1}{v_2}=k_i\frac{c/n_1}{c/n_2}=k_i\frac{n_2}{n_1},$$
>
> then
>
> $$\alpha=k_i\sqrt{\sin^2\theta_1-\frac{n_2^2}{n_1^2}}=\frac{2\pi}{\lambda}\sqrt{\sin^2\theta_1-\frac{n_2^2}{n_1^2}}=\frac{2\pi}{\lambda}\sqrt{\sin^2\theta_1-\sin^2 l}.$$
>
> **Solution:**
>
> $$\Delta z=\frac1\alpha=1.1\lambda.$$
>
> **Solution:** Considering the phase of the evanescent wave, $\varphi=\omega t-k_ty\frac{n_1}{n_2}\sin\theta_1$ its phase speed is
>
> $$v_e=\frac\omega{k_t\frac{n_1}{n_2}\sin\theta_1}=\frac\omega{k_i\sin\theta_1}=\frac{v_1}{\sin\theta_1},$$
>
> so, the requested ratio is
>
> $$\frac{v_e}{v_1}=\frac1{\sin\theta_1}=1.6.$$
>
> **Solution:** Since
>
> $$n_2\cos\theta_2=-n_2\sqrt{1-\sin^2\theta_2}=-n_2\sqrt{1-\frac{n_1^2}{n_2^2}\sin^2\theta_1}=-in_2\sqrt{\frac{n_1^2}{n_2^2}\sin^2\theta_1-1}=-i\frac{n_1\alpha}{k_i},$$
>
> then
>
> $$E_{0r}=\frac{n_1\cos\theta_1+i\frac{n_1\alpha}{k_i}}{n_1\cos\theta_1-i\frac{n_1\alpha}{k_i}}E_{0i}=\frac{\cos\theta_1+i\frac\alpha{k_i}}{\cos\theta_1-i\frac\alpha{k_i}}E_{0i}.$$
>
> For any complex number of the same form we can write
>
> $$\frac{a+ib}{a-ib}=\frac{\sqrt{a^2+b^2}e^{i\varphi_0}}{\sqrt{a^2+b^2}e^{-i\varphi_0}}=e^{2i\varphi_0},$$
>
> where $\tan\varphi_0=b/a$. In conclusion $E_{0r}=e^{2i\varphi_0}E_{0i}$, where
>
> $$\tan\varphi_0=\frac\alpha{k_i\cos\theta_1}=\frac1{\cos\theta_1}\sqrt{\sin^2\theta_1-\sin^2l}.$$
>
> Under these conditions, the intensity of the totally reflected wave will be
>
> $$I_r=\frac12\varepsilon_0c|E_{0r}|^2=\frac12\varepsilon_0c|E_{0i}|^2=I_i.$$
>
> **Solution:** From Fig. 3, it follows that $D=s\cos\theta_1$. If in the incidence point for the incident wave, on the interface, the phase of its electric field is $\Phi_i$, then, at the starting point, for the totally reflected wave its phase is $\Phi_r=\Phi_i-k_{iy}s+2\varphi_0$. With $\Phi_r=\Phi_i$, and knowing that $k_{iy}=k_i\sin\theta_1$, we obtain
>
> $$s=\frac{2\varphi}{k_i\sin\theta_1}=\frac\lambda\pi\frac1{\sin\theta_1}\tan^{-1}\left(\frac{\sqrt{\sin^2\theta_1-\sin^2l}}{\cos\theta_1}\right).$$
>
> Finally,
>
> $$D=\frac\lambda\pi\frac{\tan^{-1}\left(\frac{\sqrt{\sin^2\theta_1-\sin^2l}}{\cos\theta_1}\right)}{\tan\theta_1}.$$
>
> The numerical value of $s$ is
>
> $$s=5.5\lambda.$$
>
> **Solution:**
>
> $$\tau=\frac{s}{v_{1y}}=\frac{s}{v_1\sin\theta_1}=\frac{sn_1}{c\sin\theta_1}=\frac{\lambda n_1}{\pi c}\frac1{\sin^2\theta_1}\tan^{-1}\left(\frac{\sqrt{\sin^2\theta_1-\sin^2l}}{\cos\theta_1}\right)=2.6\cdot10^{-14}\,s.$$
