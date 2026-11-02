---
id: nbpho-2025-intl-theory-2
olympiad: NbPhO
year: 2025
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "2"
title: "Evaporation"
points: 7
authors: ["Jaan Kalda"]
aliases: ["Evaporation"]
topics: ["[[2.10 Насыщенный пар]]", "[[2.1 Уравнение теплового баланса. 8-ой класс]]", "[[2.2 Уравнение состояния идеального газа]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: true
source_damaged: false
summary: "Испарение воды под поршнем и охлаждение влажной кожи в горячем воздухе."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 2. Evaporation (7 points) — Jaan Kalda.

**NbPhO 2025** · Международная олимпиада · теория · 10–12 класс · задача 2  
Источник: [[_pdf/NbPhO/nbpho-2025.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2025.pdf#page=3|решение, стр. 3–4]]

Темы: [[2.10 Насыщенный пар]], [[2.1 Уравнение теплового баланса. 8-ой класс]], [[2.2 Уравнение состояния идеального газа]]

> [!abstract] Кратко (составлено моделью)
> Испарение воды под поршнем и охлаждение влажной кожи в горячем воздухе.

For the subsequent tasks, the graph shows how the density of saturated water vapour in $\mathrm{g\,m^{-3}}$ depends on the temperature in $^\circ\mathrm C$.

![[nbpho-2025-p1-f1.svg]]

You may also use the following characteristics of water. Specific heat capacity $c = 4200\,\mathrm{J\,kg^{-1}\,K^{-1}}$; latent heat of vaporization $L = 2260\,\mathrm{kJ\,kg^{-1}}$; density $\rho = 1000\,\mathrm{kg\,m^{-3}}$; molar mass of water $\mu = 18\,\mathrm{g\,mol^{-1}}$. You may also assume water vapour to behave as an ideal gas. The universal gas constant is $R = 8.31\,\mathrm{J\,mol^{-1}\,K^{-1}}$.

**i)** (2 points) A cylinder contains a certain amount of water at temperature $T_0 = 90\,{}^\circ\mathrm{C}$, see the figure. The cross-sectional area of the piston is $S = 1\,\mathrm{dm^2}$. What is the minimum pulling force required to move the piston? The pressure of the surrounding air is $p_0 = 100\,\mathrm{kPa}$.

![[nbpho-2025-p1-c3257.png]]

**ii)** (2 points) If the piston is pulled so that it shifts by $a = 3\,\mathrm{dm}$, the water cools to a temperature of $T_1 = 89\,{}^\circ\mathrm{C}$; what is the mass of the water under the piston?

Water evaporation has a cooling effect the intensity of which depends on the relative humidity and air convection intensity. It appears, however, that once a dynamical thermal equilibrium is reached, the equilibrium temperature of a wet surface depends only on the relative humidity and the temperature of air and does not depend on the convection speed (as long as the convection is not too weak). This is so because the two competing processes determining the equilibrium state both depend on the thickness of the laminar (non-turbulent) surface layer exactly in the same way. In what follows we shall use the following assumptions. (a) Atop a wet surface (such as a sweating bare skin), there is a layer with a laminar flow of a certain thickness $d$. (b) Atop the laminar layer, the surrounding turbulent flow keeps a constant temperature $T$ and relative humidity $r$, both equal to the respective values in the bulk of the surrounding air. (c) Heat flux from beneath the wet surface (e.g. through the skin) can be neglected. (d) The heat conductivity of air $\kappa = 30\,\mathrm{mW\,m^{-1}\,K^{-1}}$ at $T = 70\,{}^\circ\mathrm{C}$ (neglect the temperature dependence), and the diffusivity of water molecules in air $D = 26\,\mathrm{mm^2\,s^{-1}}$. Neglect the dependence of $D$ on the temperature. Note that the particle flux (net number of molecules passing a cross-section in $y$–$z$-plane per second and per cross-sectional area) can be found as $J = D\frac{dn}{dx}$, where $n$ denotes the number density (number of molecules per volume).

**iii)** (3 points) Determine the temperature of sweating human skin in a sauna if the air temperature $T = 110\,{}^\circ\mathrm{C}$ and $r = 3\%$.

> [!answer]- Ответ
> **i** — $S(p_0-p_1) = 300\,\mathrm N$.
>
> **ii**
>
> $$
> m = \frac{m_vL}{c(T_0-T_1)} = \frac{\rho_1SaL}{c(T_0-T_1)} = 650\,\mathrm g.
> $$
>
> **iii** — $T_s = 41.5\,{}^\circ\mathrm{C}$.

> [!solution]- Решение
> # 2. Evaporation (7 points) — Solution by Jaan Kalda, grading schemes by Mattias Bjerklöv, Marko Tsengov, Eppu Leinonen.
>
> **i)** (2 points) Water is in a good approximation incompressible; hence, when the piston starts moving, the growing volume must be filled by gas which can be only the water vapours. Thus, the water starts boiling: these vapours must be in equilibrium with water, hence the vapour pressure must be equal to the pressure inside the piston. We can read from the graph that at $T_0$, the vapour density is $\rho = 420\,\mathrm{g\,m^{-3}}$; this corresponds to the pressure $p_1 = \rho RT/\mu = 70\,\mathrm{kPa}$. With atmospheric pressure $p_0 = 100\,\mathrm{kPa}$, the force needed to pull the piston is
>
> $S(p_0-p_1) = 300\,\mathrm N$.
>
> **ii)** (2 points) When the piston is pulled by displacement $a$, creating new volume $V_\mathrm{new} = S \times a$, the water partially evaporates to fill this volume with vapour and the remaining liquid water cools from temperature $T_0$ to $T_1$. The mass of vapour $m_v$ needed to fill the new volume can be calculated using the vapour density $\rho_1 = 405\,\mathrm{g\,m^{-3}}$ as $m_v = Sa\rho_1$. For the heat balance, the energy needed for evaporation must come from the cooling of the remaining liquid water:
>
> $$m_vL = (m-m_v)\cdot c\cdot(T_0-T_1); \tag{1}$$
>
> here we have neglected the dependence of $L$ on temperature, and heat capacity of water vapours, because $\mu L \gg 4R(T_1-T_0)$ (but we have not neglected the work done by piston, because $L$ is actually the enthalpy of evaporation already includes $p\Delta V$). Similarly, since $L \gg c(T_1-T_0)$, we can neglect $m_v$ in the right-hand-side and express
>
> $$m = \frac{m_vL}{c(T_0-T_1)} = \frac{\rho_1SaL}{c(T_0-T_1)} = 650\,\mathrm g. \tag{2}$$
>
> **iii)** (3 points) At the thermal equilibrium, there is as much heat flux to the skin as there is heat loss due to evaporation. The former (per area) equals to $\kappa\frac{dT}{dx}$ and the latter (per area) — to $-LJm$ where $m$ is the mass of one molecule, which we find to be $m = \mu/N_A$ to get $J\mu L/N_A$. Note that the minus sign comes from the fact that the particles diffuse from higher density areas to lower density areas. Now from the ideal gas law $n = P/Tk_B = PN_A/TR$ to get $J = -D\frac d{dx}\frac{rp}{Tk_B} = -D\frac d{dx}\frac{PN_A}{RT}$. Now the pressure of the water vapour is related to $r$ through $P = rp$, where $p$ denotes the saturation pressure of vapour. So,
>
> $$\kappa\frac{dT}{dx} = -\frac{DL\mu}{R}\frac d{dx}\frac{rp}{T},$$
>
> where $p = p(T)$ denotes the water vapour saturation pressure at the local air temperature; hence by integrating over $x$ we obtain
>
> $$\kappa(T-T_s) = \frac{DL\mu}{R}\left[\frac{p(T_s)}{T_s}-\frac{rp(T)}{T}\right],$$
>
> where the index $s$ denotes quantities evaluated at the skin surface. Also, we have used the fact that $r_s = 1$, because at the skin surface, the air is in direct contact with water (due to sweating, skin is wet), so that $pr_s = p(T_s)$. Substituting $\rho = \frac{p\mu}{RT}$ we obtain
>
> $$\rho(T_s) = r\rho(T) + \frac{\kappa}{DL}(T-T_s).$$
>
> Here we evaluate from the graph $r\rho(T) = 24.3\,\mathrm{g\,m^{-3}}$ and $\frac{\kappa}{DL} = 0.51\,\mathrm{g\,m^{-3}\,K^{-1}}$. Now we can draw this straight line onto the graph provided to find the intersection point at
>
> $T_s = 41.5\,{}^\circ\mathrm{C}$.
>
> ![[nbpho-2025-p4-f1.svg]]
>
> If working with $\rho$ earlier on we can show that that the heat flux up magnitude is
>
> *Solution 2 by Eppu Leinonen:* One can also work directly with $\rho$ through the fact that $n = N/V = MN_A/\mu V = \rho N_A/\mu$. Then the heat flux magnitude will directly become $LJm = LmD\frac{dn}{dx} = LmD\frac{N_A}{\mu}\frac{d\rho}{dx} = LD\frac{d\rho_v}{dx}$, where $\rho_v$ is the density of the water vapour. Then with correct signs we get
>
> $$\kappa\frac{dT}{dx} = -LD\frac{d\rho_v}{dx}$$
>
> from which by integrating and using $\rho_v = r\rho$ we get
>
> $$\rho(T_s) = r\rho(T)+\frac\kappa{DL}(T-T_s)$$
>
> and the solution proceeds the same way as in solution 1.

> [!grading]- Критерии оценивания
> | Part | Criterion | Points |
> |---|---|---|
> | i) | Realize that the pressure inside the the cylinder equals the saturated vapour pressure of water at temperature $T_0$. | 0.8 pts |
> | | Read the density $\rho$ from the graph, in the range $[400,440]\,\mathrm{g\,m^{-3}}$. | 0.2 pts |
> | | Use the ideal gas law to find an expression for the pressure $p_1$ at temperature $T_0$. | 0.4 pts |
> | | Correct expression for the force: $S(p_0-p_1)$. | 0.4 pts |
> | | Correct numerical answer. | 0.2 pts |
>
> **ii)**
>
> | Part | Criterion | Points |
> |---|---|---|
> | ii) | Read the vapour density $\rho_1$ from the graph ($\rho_1 \in [390,420]\,\mathrm{g\,m^{-3}}$). | 0.2 pts |
> | | Correct expression for mass of water vapour. | 0.3 pts |
> | | Correct expression for the latent heat ($m_vL$). | 0.3 pts |
> | | Correct expression for heat lost by water ($(m-m_v)\cdot c\cdot(T_0-T_1)$.) | 0.3 pts |
> | | Expression for energy conservation. | 0.4 pts |
> | | Correct expression for mass of water $m$. | 0.3 pts |
> | | Correct numerical answer $m \in [630,680]\mathrm g$ (with correct dimension). | 0.2 pts |
>
> **iii)**
>
> Grading: (preliminary)
>
> NB! the $\rho = p\mu/RT$ substitution can be done earlier so the schemes below represent only the relevant observations which can be done with $\rho$ already. Also equivalent forms will give points (i.e. if using $k$ and $N_a$ instead of $R$ in the middle steps)
>
> | Criterion | Points |
> |---|---|
> | heat going away from skin (up) = heat going to skin (down) at the equilibrium | 0.4 pts |
> | Heat flux down $\kappa\frac{dT}{dx}$ | 0.2 pts |
> | Heat flux up magnitude $\frac{DL\mu}{R}\frac d{dx}\frac PT$ (partial points available for the equivalents to the steps below) | 0.5 pts |
> | – Magnitude of heat flux up is $LJm$ | 0.3 pts |
> | – $m = \mu/N_A$ | 0.1 pts |
> | – $n = P/Tk_B$ | 0.1 pts |
> | Deducing that the direction of the heat flow is opposite to $\frac{dn}{dx}$ (explicitly mentioned or with the existence of the minus sign in the equations) | 0.1 pts |
> | $P = rp$ | 0.1 pts |
> | $\kappa(T-T_s) = \frac{DL\mu}{R}\left[\frac{p(T_s)}{T_s}-\frac{rp(T)}{T}\right]$ (i.e. integrating correctly) | 0.4 pts |
> | – Or doing a change from d → Δ in the derivatives has to be motivated properly (i.e. for heat conductivity no need for any explicit explanation but for Fick’s law one must state that $J$ is constant (due to the amount of particles is conserved)). | |
> | $\rho = p\mu/RT$ | 0.1 pts |
> | Reading $\rho$ correctly ($\rho_1 \in [800,815]\mathrm{g\,m^{-3}}$) | 0.2p pts |
> | Graphical method | 0.8 pts |
> | – Noticing that $\rho(T_s) = r\rho(T)+\frac\kappa{DL}(T-T_s)$ defines a straight line in $(T,\rho)$ | 0.8 pts |
> | – Any other valid numerical method that is explained is accepted | |
> | Correct final result $T \in [36,47]^\circ\mathrm C$ | 0.2 pts |
>
> The following grading scheme is given to provide exact correspondences to the scheme of solution 1. Grading:
>
> | Criterion | Points |
> |---|---|
> | heat going away from skin (up) = heat going to skin (down) at the equilibrium | 0.4 pts |
> | Heat flux down $\kappa\frac{dT}{dx}$ | 0.2 pts |
> | Heat flux up magnitude $LD\frac{d\rho_v}{dx}$ (partial points available for the equivalents to the steps below) | 0.6 pts |
> | – Working with $\rho$ directly | 0.1 pts |
> | – Magnitude of heat flux up is $LJm$ | 0.3 pts |
> | – $n = \rho N_A/\mu$ | 0.1 pts |
> | – $\mu = mN_A$ | 0.1 pts |
> | Deducing that the direction of the heat flow is opposite to $\frac{dn}{dx}$ (explicitly mentioned or with the existence of the minus sign in the equations) | 0.1 pts |
> | $\rho_v = r\rho_v$ | 0.1 pts |
> | $\kappa(T-T_s) = LD(\rho(T_s)-r\rho(T))$ (i.e. integrating correctly) | 0.4 pts |
> | – Or doing a change from d → Δ in the derivatives has to be motivated properly (i.e. for heat conductivity no need for any explicit explanation but for Fick’s law one must state that $J$ is constant (due to the amount of particles is conserved)). | |
> | Reading $\rho$ correctly ($\rho_1 \in [800,815]\mathrm{g\,m^{-3}}$) | 0.2p pts |
> | Graphical method | 0.8 pts |
> | – Noticing that $\rho(T_s) = r\rho(T)+\frac\kappa{DL}(T-T_s)$ defines a straight line in $(T,\rho)$ | 0.8 pts |
> | – Any other valid numerical method that is explained is accepted | |
> | Correct final result $T \in [36,47]^\circ\mathrm C$ | 0.2 pts |
