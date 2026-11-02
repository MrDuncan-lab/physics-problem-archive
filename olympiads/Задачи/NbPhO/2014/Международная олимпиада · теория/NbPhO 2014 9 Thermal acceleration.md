---
id: nbpho-2014-intl-theory-9
olympiad: NbPhO
year: 2014
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "9"
title: "Thermal acceleration"
points: 9
aliases: ["Thermal acceleration"]
topics: ["[[2.4 Теплоёмкость процесса]]", "[[2.12 Молекулярно-кинетическая теория]]", "[[1.16 Закон сохранения импульса]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Оценить энергию и скорость охлаждающегося куба при тепловом излучении и столкновениях с газом."
status: "проверено: сверка, два чтения + арбитр"
lang: en
tags: [задача]
---

# 9. THERMAL ACCELERATION (9 points)

**NbPhO 2014** · Международная олимпиада · теория · 10–12 класс · задача 9  
Источник: [[_pdf/NbPhO/nbpho-2014.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2014.pdf#page=4|решение, стр. 4]]

Темы: [[2.4 Теплоёмкость процесса]], [[2.12 Молекулярно-кинетическая теория]], [[1.16 Закон сохранения импульса]]

> [!abstract] Кратко (составлено моделью)
> Оценить энергию и скорость охлаждающегося куба при тепловом излучении и столкновениях с газом.

Consider a cube of side length $a=1\,\mathrm{cm}$, made of aluminium (density $\rho=2.7\,\mathrm{g/cm^3}$, molar mass $M_A=23\,\mathrm{g/mol}$). The heat capacitance of one mole of aluminium is given as a function of temperature in the graph below. The speed of light $c=3\times10^8\,\mathrm{m/s}$, universal gas constant $R=8.31\,\mathrm{J/(kg\cdot K)}$. The initial temperature of the cube is $T_0=300\,\mathrm{K}$.

![[nbpho-2014-p2-f1.svg]]

**i)** (1 point) What is the total heat energy of such a cube at the initial temperature $T_0$?

**ii)** (3 points) Now, the cube has 5 faces painted in white (reflects all relevant wavelengths) and one face painted in black (absorbs all these waves). The cube is surrounded by vacuum at a very low temperature (near absolute zero); there is no gravity field. Initially, the cube is at rest; as it cools down due to heat radiation, it starts slowly moving. Estimate its terminal speed $v_1$.

**iii)** (2 points) At very low temperatures, the heat capacitance of aluminium is proportional to $T^3$, where $T$ is its temperature. Which functional dependance $f(t)$ describes the temperature as a function of time [$T=A\cdot f(Bt)$, where $A$ and $B$ are constants] for such very low temperatures under the assumptions of the previous question?

**iv)** (3 points) Now, the cube has 5 faces covered with a thermal insulation layer (you may neglect heat transfer through these faces). One face is left uncovered. The cube is surrounded by hydrogen atmosphere at a very low temperature (molar mass of hydrogen molecules $M_H=2\,\mathrm{g/mol}$). The cube starts cooling down due to heat transfer to the surrounding gas; you may neglect the heat radiation. Initially, the cube is at rest; as it cools down, it starts slowly moving. Estimate the order of magnitude of its terminal speed $v_2$. Assume that the surrounding gas is sparse, so that the mean free path of the molecules is much larger than $a$. Assume that $v_2\ll c_s$ where $c_s$ is the speed sound in the atmosphere surrounding the cube.

> [!answer]- Ответ
> **9.1** — $Q=q\nu\approx546\,\mathrm{J}$.
>
> **9.2**
>
> $$
> v\sim\frac{Q}{\rho a^3c}\approx0.67\,\mathrm{mm/s}.
> $$
>
> **9.2** — $v\approx0.22\,\mathrm{mm/s}$.
>
> **9.3**
>
> $$
> \frac{dT}{T}=-Bt\Rightarrow T=A\cdot e^{-Bt}.
> $$
>
> **9.4**
>
> $$
> v\sim\frac{Q}{\rho a^3}\sqrt{\frac{M_H}{RT}}\approx180\,\mathrm{m/s}.
> $$

> [!solution]- Решение
> # 9. Thermal acceleration
>
> **1)** For the heat energy of one mole of material $dq=C_vdT$. There is no heat energy by $T=0$, hence $q=\int_0^T C_vdT$. Using the graph we find this as the area under the curve, $q\approx R\cdot560\,\mathrm{J/K}$. The number of moles $\nu=a^3\rho/M_A\approx0.117\,\mathrm{mol}$, hence the total heat energy
> $Q=q\nu\approx546\,\mathrm{J}$.
>
> **2)** Each photon of frequency $\nu$ radiated by the cube carries away heat energy equal to $E=h\nu$, and carries momentum $p=h/\lambda=h\nu/c=E/c$. If the photon departs at the angle $\alpha$ with respect to the surface normal then the component parallel to the surface normal $p_\parallel=\frac{E}{c}\cos\alpha$. The total momentum given by the photons to the cube equals by modulus to the total momentum carried by the photons; when averaged over all the photons, the perpendicular to the surface normal components cancel out (photons go to all the directions). The average value of the parallel component can be estimated just as $p_\parallel\sim\frac{E}{c}$.
>
> If we want to obtain an exact result, we need to integrate over all the directions while keeping in mind that the light intensity is proportional to $\cos\alpha$. So, the momentum averaged over all the directions $\bar p_\parallel=\frac{E}{c}\frac{1}{2\pi}\int\cos^2\alpha\,d\Omega$, where the solid angle differential $d\Omega=2\pi\sin\alpha\,d\alpha$. Therefore, $\bar p_\parallel=\frac{E}{c}\int_0^{\pi/2}\sin\alpha\cos^2\alpha\,d\alpha=\frac{E}{c}\int_0^{\pi/2}\cos^2\alpha\,d\cos\alpha=\frac{E}{3c}$.
>
> Since the momentum-energy ratio is the same for all the photons, equal to $1/c$, the overall momentum equals to $Q/c$. Thus, $a^3\rho v\sim Q/c$, hence
>
> $$v\sim\frac{Q}{\rho a^3c}\approx0.67\,\mathrm{mm/s}.$$
>
> If we apply the exact factor $\frac13$ (obtained above via integration), we end up with
> $v\approx0.22\,\mathrm{mm/s}$.
>
> **3)** The heat balance at very low temperatures can be written as $AT^3dT=-\sigma ST^4dt$, where $A$ is a constant, $\sigma$ is the Stefan-Boltzmann constant, and $S$ — the radiating area. This simplifies to
>
> $$\frac{dT}{T}=-Bt\Rightarrow T=A\cdot e^{-Bt}.$$
>
> **4)** In the case of a hydrogen atmosphere, the momentum is given to the cube due to the fact that the molecules colliding with the coated faces bounce back with the same speed as the they came, but uncoated face gives away heat energy, and the molecules leave at higher temperature. If we assume that the departing molecules have the same temperature as the cube (which serves us only as an estimate — when particles of different masses collide, only a part of the energy is transferred), then the momentum-to-heat ratio is estimated as $1/v_T$, where $v_T=\sqrt{RT/M_H}$ is the thermal speed of the molecules after the collision with the cube for the motion along the surface normal. So we estimate $a^3\rho v\sim Q/v_T$, hence
>
> $$v\sim\frac{Q}{\rho a^3}\sqrt{\frac{M_H}{RT}}\approx180\,\mathrm{m/s}.$$
>
> It should be noted that in fact, one should have been careful with such an estimate, because the thermal speed is at the denominator. This will increase the relative contribution of the heat radiated at low temperatures. However, the remaining heat at low temperatures is proportional to $T^4$, and therefore the contribution of those molecules which collide with the cube at low temperatures to the overall momentum remains still small.
