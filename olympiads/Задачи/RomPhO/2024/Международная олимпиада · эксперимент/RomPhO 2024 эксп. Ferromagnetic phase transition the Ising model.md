---
id: rompho-2024-intl-experiment-exp
olympiad: RomPhO
year: 2024
stage: "Международная олимпиада"
round: эксперимент
grade: ""
number: "exp"
title: "Ferromagnetic phase transition: the Ising model"
aliases: ["Ferromagnetic phase transition: the Ising model"]
topics: ["[[4 Магнетизм]]", "[[2.12 Молекулярно-кинетическая теория]]", "[[7 Эксперименты]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Исследовать ферромагнитный фазовый переход в двумерной модели Изинга и определить критическую температуру."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# Ferromagnetic phase transition: the Ising model

**RomPhO 2024** · Международная олимпиада · эксперимент  
Источник: [[_pdf/RomPhO/RomPhO-2024-exp.pdf#page=1|условие, стр. 1–4]] · [[_pdf/RomPhO/RomPhO-2024-exp-solution.pdf#page=5|решение, стр. 5–14]]

Темы: [[4 Магнетизм]], [[2.12 Молекулярно-кинетическая теория]], [[7 Эксперименты]]

> [!abstract] Кратко (составлено моделью)
> Исследовать ферромагнитный фазовый переход в двумерной модели Изинга и определить критическую температуру.

Depending on the external parameters imposed on a physical system, its properties can vary drastically. One only needs to think of water at usual temperatures and pressures to see how, within a temperature range of about 100 K, it can change from solid to liquid, and finally onto gas. These three different states are examples of what is more generally called a phase of matter. The different phases of matter are characterized by differing physical properties, that undergo an abrupt change at a phase transition. The phase transitions are characterized by the external temperatures and pressures at which they can occur. One notes that phase transitions are emergent phenomena, meaning that they are specific to thermodynamic systems, which exhibit a very large number of microscopic degrees of freedom. When reducing the number of constituents of a system, the transition smoothens out. In such cases, one rather talks about regimes of matter and their crossovers.

The concept of a phase transition is not limited to the solid, liquid and gas states. Depending on the physical properties taken into account, one can distinguish further states of matter. More generally, we can associate to a phase transition with any process that involves a sudden change in the ”order” of a system. Such order can be characterized by a well-chosen parameter of the system which allows to distinction between the ordered and the unordered phases.

For example, the magnetic state of a material is also subject to a phase transition. A material is in a ferromagnetic state when it exhibits a large, nonzero magnetization even in the absence of any external magnetic field. For example, iron at room temperature is in a ferromagnetic state. On the contrary, a material is in a paramagnetic state when it exhibits a zero net magnetization in the absence of a magnetic field, and applying an external magnetic field gives rise to a (small) colinear nonzero magnetization. This justifies that, in this case, the magnetization of the system is a possible order parameter describing the phase transition.

Before going forward, one must note that most solids at room temperature are paramagnetic, with few exceptions. One also distinguishes a third class of materials, called diamagnetic, that also have zero net magnetization in the absence of an external field, and which respond with a magnetization that opposes an external applied field. In this problem, we only consider transitions between ferromagnetic and paramagnetic states.

At a given temperature, most substances will either be in a ferromagnetic or in a paramagnetic state. At very low temperatures, a substance will always be ferromagnetic, and above a certain temperature $T_c$, called the Curie temperature, it will suddenly lose its magnetization and transition to a paramagnetic state. In this problem, we will investigate the Ising model of ferromagnetism. The system described by this model is simple enough to give an intuition of the physical situation, yet powerful enough to yield many qualitative features of real ferromagnets. Furthermore, it allows to explore the influence of the number of constituents on the phase transition.

In the Ising model, we consider a two-dimensional $L\times L$ lattice of spins, which can each either point up or down. The state of the spin at position $(i,j)$ in the lattice is encoded by the number $\sigma_{ij}$, as follows

$$
\sigma_{ij}=\begin{cases}+1 & \text{if the spin }(i,j)\text{ points up}\\-1 & \text{if the spin }(i,j)\text{ points down}\end{cases} \tag{1}
$$

The main assumption of this model is that neighboring spins in the lattice interact by a mechanism called exchange interaction. The parameter describing the exchange interaction for a ferromagnet is denoted by $J>0$. If two neighboring spins point the same way (either both up or both down), the state is energetically favorable and contributes $-J$ to the energy of the system. When two neighboring spins point opposite ways, the state is energetically unfavorable and contributes an energy $+J$ to the system. Furthermore, one assumes for simplicity periodic boundary conditions: the spins on row $L$ are assumed to neighbor those on row 1 (as well as those on column $L$ neighbor those on column 1). Then, the total energy of a given system of spins is given by

$$
E=-\frac{J}{2}\sum_u\sum_{v\text{ neighbor of }u}\sigma_u\sigma_v \tag{2}
$$

In such a system, the distinction between the ferromagnetic and the paramagnetic state can be done by choosing the magnetization per unit spin $M$ as an order parameter. Its definition is

$$
M=\frac{1}{L^2}\sum_{(i,j)}\sigma_{ij} \tag{3}
$$

The absolute value of $M$ will be very close to one in a ferromagnetic phase, whereas it will be almost zero in a paramagnetic phase.

The thermal description of the Ising model relies on Boltzmann statistics. In this description, two states $\alpha$ and $\beta$ of a given system at temperature $T$, having energies $E_\alpha$ and $E_\beta$, will arise with probabilities $p_\alpha$ and $p_\beta$ whose ratio is

$$
\frac{p_\alpha}{p_\beta}=\exp\left(-\frac{E_\alpha-E_\beta}{k_B T}\right) \tag{4}
$$

In order to compute the expectation values of thermodynamic parameters in the Ising model, one needs to consider all the possible spin configurations, compute their associated probabilities, and then average over all the different states with their corresponding probabilities. Given that there are $2^{L^2}$ possible configurations of an $L\times L$ spin-lattice, for $N$ as low as 10, this already becomes a formidable task.

One can mitigate this limitation by noting that most of these states will yield a negligible contribution to the expected values. In fact, only a few of these most likely states will make a significant contribution. Selecting the relevant states, however, is also a non-trivial task. The solution that we take in this case is a Monte Carlo simulation. This approach relies on random sampling of states according to wisely chosen probability distributions, following Boltzmann statistics. Starting from a randomly chosen initial state, one evolves it through random spin flips, occurring with probabilities chosen by Boltzmann statistics. After a certain number of steps $N_{eq}$, the system can be considered as equilibrated, meaning that it will only be evolving among the most likely states mentioned before. Then, the system continues to evolve according to the same random procedure for a further number of steps $N_{MC}$. The expectation of a thermodynamic parameter is then obtained by computing its value for each of the states obtained during the Monte Carlo procedure and averaging over all the obtained values.

We provide an implementation of the said Monte Carlo algorithm. The adjustable parameters are the lattice size $L$, the exchange constant $J$, the temperature $T$ of the system, as well as the number of steps in the Monte Carlo procedure $N_{MC}$. The number of equilibration steps is always chosen as $N_{eq}=N_{MC}/10$. The algorithm returns the expectation of the average magnetization per spin with its error bar, as obtained from the algorithm. The algorithm may also generate, for visualization purposes, a graphical representation for a thermal equilibrium configuration of spins. The purpose of this problem is to investigate the behavior of the average magnetization $M$ as the three adjustable parameters vary.

One notes that the results generated by the algorithm correspond to the thermodynamic limit only asymptotically, ie. upon considering a very large system of spins undergoing a very high number of Monte Carlo steps. In practice, the algorithm is still quite time-consuming, and a single run can last up to several minutes. As such, for time efficiency reasons, you must limit the number of spins as well as the number of iterations. In doing so, you must be careful with the following trade-off: reducing these values too much might lead you to obtain non-relevant thermodynamics, and you might not be able to observe the required phase transitions! The strategy we suggest is the following: first, read through the entire problem to get a feeling of the questions you need to study. Then, take a while to play with the algorithm and get a feel of its typical runtime. Start with small lattices and small numbers of Monte Carlo steps, and increase the values steadily up until you get clear phase transitions in a reasonable runtime. Always mention the lattice size and the number of steps you use on your answer sheet.

You will need to produce several graphs and plots: you can either create them on your computer, using an available software of your choice (such as Excel), or using millimeter paper provided to you. If you create a digital graph, make sure to save it and hand it in, and explicitly mention the file name on your answer sheet. Also, hand in all of the data files on which your solution is based, and always mention the file name where the corresponding data is located. Your answers will not be graded if the graphs and data files are not handed in or not appropriately referenced in your solution.

## A Phase transition and the critical temperature

In this section, work with a lattice size $L=20$. Select an appropriate number of iterations so as to reach thermodynamic equilibrium.

**A.1.** (1 point) Set $J=1$ and toggle the animation on. Observe the system at the temperatures $T=1$, $T=2$, $T=3$ and $T=4$. Qualitatively describe the results. Do you observe a phase transition? In what temperature range?

**A.2.** (2 points) Set $J=1$ and plot the resulting (absolute value of) magnetization versus temperature. Present your data in a table. Obtain an estimate for the phase transition temperature.

**A.3.** (4 points) Repeat the experiment for several values of $J$. Plot the dependence of the critical temperature on the exchange parameter $J$ and suggest a reasonable fit.

**A.4.** (1 point) In the ferromagnetic regime, is there a preferred direction of magnetization? Perform a sufficient number of experiments to draw a conclusion.

## B The crossover regime

**B.1.** (3 points) Repeat the experiment for a small $L=10$ and $L=5$. How does the phase transition change?

## C Lattice in an external magnetic field

Here, we introduce an additional term in the energy, accounting for an external magnetic field $H$, having the form

$$
E_H=-H\sum_{(i,j)}\sigma_{ij} \tag{5}
$$

Work again with a lattice size $L=20$. Fix the value of $J=1$.

**C.1.** (2 points) Repeat the experiment for $H=0.1$ and $H=1$. Plot the magnetization versus temperature curves and compare them with the curve obtained in the absence of a magnetic field. Does the external field influence the temperature of the phase transition?

**C.2.** (1 point) Focus on the ferromagnetic regime. Is there a preferred direction of magnetization in this case? Study both cases $H=0.1$ and $H=1$.

**C.3.** (2 points) Focus on the paramagnetic regime. Plot the dependence of the magnetization on the external field $0<H<2$ for five different temperatures. Compare these dependences and discuss.

For small enough external fields, one can assume that the magnetization responds linearly to the applied field. In that case, one can define the susceptibility of the system as

$$
\chi=\frac{M}{H} \tag{6}
$$

For paramagnetic substances, the susceptibility strongly depends on the temperature, according to the Curie-Weiss law

$$
\chi(T)=\frac{\chi_0}{T-T_c} \tag{7}
$$

where $\chi_0$ is a fitting constant and $T_c$ is the Curie temperature at which the phase transition occurs.

**C.4.** (2 points) Compute the susceptibilities from the previous question and investigate their temperature dependence. Compare with the Curie-Weiss law and comment.

## D Antiferromagnetism

Setting a negative value for the exchange parameter $J<0$ results in qualitatively different behavior, usually called antiferromagnetism.

**D.1.** (1 point) Set $J=-1$ and describe the resulting states for different temperatures. What are the phases of this system?

**D.2.** (1 point) Explain why magnetization is no longer the relevant parameter to describe the phase transition. Propose an alternative order parameter.

> [!answer]- Ответ
> **A.2** — $T \approx 2.2 \pm 0.1$, which indicates that it is the temperature at which the phase transition takes place.
>
> **A.3** — $2.29 \pm 0.03$.
>
> **C.4** — $T_c = 2.58 \pm 0.16$.
>
> **D.2**
>
> $$
> A = \frac{1}{L^2}\sum_{(i,j)}(-1)^{i+j}\sigma_{ij}
> $$

> [!solution]- Решение
> # Ferromagnetic phase transition: the Ising model
> ## Solution and guidelines for grading
> May 12, 2024
>
> The aim of this document is two-fold. At first, it will provide details on the implementation of the Monte Carlo simulation that was provided to the students. Hence, the first part is for information purposes only. The second part of this document provides a model solution of the experimental tasks, as well as guidelines for grading. The task was designed by Tudor Mocioi (Ecole Polytechnique), with significant debugging help from Victor Dumbravă (Ecole Polytechnique). Many details of the implementation as well as some optimization ideas are based on the course of Lauren Hayward (Perimeter Institute) presented during Perimeter Institute’s PSI Summer Program.
>
> ## 1 Implementation of the Monte Carlo simulation
> The simulation software is written in Python 3. Below, we introduce the basic building blocks of this software. At first, we introduce the relevant modules onto which the simulation software is based, as in the code block below.
>
> [47]:
> ```python
> import matplotlib.pyplot as plt
> import matplotlib.colors as colors
> import numpy as np
> import time
> import pandas as pd
> from scipy.optimize import curve_fit
> from IPython import display bw_cmap = colors.ListedColormap(['black', 'white'])
> ```
> For efficiency purposes, the spin configurations will be stored as bidimensional numpy arrays. First, we implement a function that, given a spin configuration as well as the value of the coupling parameter $J$, in an external field $H$, returns the energy of the spin configuration.
>
> [3]:
> ```python
> def get_energy(spins, J, H):
>     energy = -H*np.sum(spins)-J*np.sum(spins*np.roll(spins, 1, axis = 0) +
>                                       spins*np.roll(spins, 1, axis = 1))
>     return energy
> ```
> Next, we implement the function that performs one step of the Monte Carlo simulation. Given a spin configuration, the procedure is the following
>
> - First, choose an arbitrary position in the spin lattice, and flip its sign. All positions are chosen with an equal probability.
>
> - If the resulting spin configuration has a lower energy, accept the new spin configuration.
> - If the resulting spin configuration has an energy that is higher than before, by a value $\Delta E$, randomly choose whether to accept the new spin configuration, with a probability $\exp\left(-\frac{\Delta E}{k_B T}\right)$.
>
> For convenience, note that our implementation operates with temperatures expressed in units of energy, i.e. the corresponding value of $k_B T$.
>
> [4]:
> ```python
> def monte_carlo_step(spins, J, T, H):
>     L = np.shape(spins)[0]
>     N_spins = L*L
>     i = np.random.randint(0,N_spins) # randomly choose which spin to consider flipping
>     i_row = i//L # row corresponding to i
>     i_col = i%L  # column corresponding to i
>
>     # look at the four nearest neighbours to calculate the change in energy for this proposed move:
>     deltaE = 2*H*spins[i_row,i_col]+2*J*spins[i_row,i_col] * (spins[(i_row+1)%L,i_col] + spins[(i_row-1)%L,i_col] + spins[i_row,(i_col+1)%L] + spins[i_row,(i_col-1)%L] )
>     if (deltaE <= 0) or (np.random.rand() < np.exp(-deltaE/T)):
>         spins[i_row,i_col] = -spins[i_row,i_col] #accept the spin flip
>     return spins
> ```
> Now, we implement the function which performs one Monte Carlo simulation, for a given set of $J$, $T$ and $H$, with a number of steps $N$, for a square lattice of size $L$.
>
> [5]:
> ```python
> def monte_carlo_simulation(L, J, T, H, N, animate):
>     spins = 2 * np.random.randint(0, 2, size=((L,L))) - 1 # start from a random spin configuration
>
>     # first, perform the equilibration steps
>     N_eq = N//10
>     for _ in range(N_eq):
>         spins = monte_carlo_step(spins, J, T, H)
>
>     # then, perform further Monte Carlo steps and record the corresponding magnetizations
>     Ms = []
>     for _ in range(N):
>         spins = monte_carlo_step(spins, J, T, H)
>         Ms.append(np.sum(spins))
>         if animate:
>             #Display the current spin configuration:
> ```
>
> ```python
>             plt.clf()
>             plt.imshow( spins.reshape((L,L)), cmap=bw_cmap, norm=colors.BoundaryNorm([-1,0,1], bw_cmap.N), interpolation='nearest' )
>             plt.xticks([])
>             plt.yticks([])
>             #plt.title('%d x %d Ising model, T = %.3f' %(L,L,T))
>             display.display(plt.gcf())
>             display.clear_output(wait=True)
>             plt.pause(0.01)
>
>     # finally, compute the average magnetization per spin and its standard deviation
>     magnetization = np.average(Ms)/(L*L)
>     std_magnetization = np.std(Ms)/(L*L*np.sqrt(len(Ms) - 1))
>     return (magnetization, std_magnetization)
> ```
> Finally, we implement a function that performs the Monte Carlo simulations for ranges of values for $J$, $T$ and $H$.
>
> [6]:
> ```python
> def simulations(L, Js, Ts, Hs, N, N_repeat, animate):
>     dict = {'J':[], 'T':[], 'H':[], 'M':[], 'M_err':[]}
>     for J in np.nditer(Js):
>         for T in np.nditer(Ts):
>             for H in np.nditer(Hs):
>                 for _ in range(N_repeat):
>                     M, M_err = monte_carlo_simulation(L, J, T, H, N, animate)
>                     dict['J'].append(J)
>                     dict['T'].append(T)
>                     dict['H'].append(H)
>                     dict['M'].append(M)
>                     dict['M_err'].append(M_err)
>     results = pd.DataFrame(dict)
>     return results
> ```
> The final step of the implementation, which we omit in this document, is to package the above functions into the graphical user interface that was provided to the participants.
>
> ## 2 Model solution and guidelines for grading
> ### A. Phase transition and the critical temperature
> **Question A.1.** We notice that the behaviour of the spin system is qualitatively different for the temperatures $T = 3$ and $T = 4$ than for $T = 1$ and $T = 2$. Indeed, for the lower temperatures there is a well-defined ordered state of the spins, with some random fluctuations around this order. The fluctuations are more frequent as the temperature increases. For the two higher temperatures, one cannot distinguish any sort of order between the spins, which just seem to randomly flip at all times. Furthermore, for the higher temperature it seems like the spin flips happen more and more frequently, with less and less order. A diagram showing typical spin configurations for the four temperatures is shown below.
>
> *Note for graders: depending on the initial seed of the random simulation, the students might not observe just one direction of alignment, but perhaps several “domains”, each pointing either up or down. Full marks may also be given for such remark, as long as the concept of **order** is clearly stated in the answer.*
>
> ![[rompho-2024-exp-solutions-p8-f1.png]]
>
> **Question A.2.** The figure below shows, for the given lattice size and number of Monte Carlo steps, at $J = 1$, the dependence of the system magnetization on temperature. One notices a very sharp drop around
> $T \approx 2.2 \pm 0.1$, which indicates that it is the temperature at which the phase transition takes place.
>
> *Note for graders: accept results within $\pm 0.2$ of the value above. It is important that, around the phase transition, the participants go in finer steps (say 0.1), so as to detect the transition correctly. Deduct marks for answers that miss the phase transition due to the steps being too coarse, as well as for answers not presenting an error bar.*
>
> ![[rompho-2024-exp-solutions-p9-f1.png]]
>
> **Question A.3.** We redo the experiment for several values of $J$. We always focus on a temperature range around $2.2T$. The results of our analysis are included in the table below. The analysis shows that the dependence of the transition temperature $T$ on the exchange parameter $J$ is very well described by a line passing through the origin, with slope
> $2.29 \pm 0.03$.
>
> *Note: an exact solution, in the thermodynamic limit (infinite lattice size), leads to $\frac{T}{J} = \frac{2}{\ln(1+\sqrt{2})} \approx 2.26$. Such solution is outside the scope of the exam.*
>
> *Note for grading: for full marks, accept linear dependencies roughly passing through the origin, with slopes between 2.2 and 2.4. At least 10 different data points need to be presented, deduct points for less. All values (critical temperatures, slopes) need to be presented with error bars.*
>
> [36]:
> | | Exchange constant J | Phase transition temperature Tc | Temperature errorbar |
> |---|---:|---:|---:|
> | 0 | 1 | 2.3 | 0.1 |
> | 1 | 2 | 4.7 | 0.1 |
> | 2 | 3 | 7.0 | 0.2 |
> | 3 | 4 | 8.8 | 0.2 |
> | 4 | 5 | 11.6 | 0.3 |
> | 5 | 6 | 13.7 | 0.3 |
> | 6 | 7 | 16.8 | 0.5 |
> | 7 | 8 | 18.0 | 0.5 |
> | 8 | 9 | 21.0 | 0.5 |
> | 9 | 10 | 23.0 | 1.0 |
>
> ********************
> ```text
> slope =     2.2914 +/-  0.0325
> intercept = 0.0383 +/-  0.0997
> ********************
> ```
> ![[rompho-2024-exp-solutions-p10-f1.png]]
>
> **Question A.4.** To assess whether one direction of magnetization is preferred in the ferromagnetic regime, we run an experiment for $J = 1$ and $T = 1$ for 100 repeats, at zero external magnetic field, each time recording the direction of the magnetization. Our simulations show that, out of 100 runs, 48 of them have a positive magnetization (pointing ‘up’) and 52 of them have a negative magnetization (pointing ‘down’). This allows us to reasonably conclude that there is no preferred direction of magnetization, and that the system randomly chooses a direction along which it spontaneously magnetizes.
>
> *Note for graders: award full marks for similar remarks based on at least 20 repeats.*
>
> ### B. The crossover regime
> **Question B.1.** The figure below shows the magnetization versus temperature curve for the three specified lattice sizes, for $J = 1$. One notices that as the lattice size decreases, the transition stays sharp, but that there is more variability in its outcome. The transition temperature also seems to be effectively shifted.
>
> *Note for graders: award full marks for similar observations, based on a plot similar to the one presented here.*
>
> ![[rompho-2024-exp-solutions-p11-f1.png]]
>
> ### C. Lattice in an external field
> **Question C.1.** The figure below compares the magnetization versus temperature curves in the presence and in the absence of an external field. One can notice that, below the ferromagnetic phase transition temperature, the magnetization remains saturated at its maximum regardless of the external field. Above the transition temperature, the system starts to demagnetize, but still preserves some magnetization which, at a given temperature, is stronger as the external field increases. As the temperature increases, the magnetization decreases for each value of the external field. The field also “smoothens out” the phase transition, making it less obvious to detect. Still, one notices similar effects at similar temperatures so one could assert that introducing an external field does not affect the temperature of the phase transition.
>
> *Note for graders: award full marks for answers specifying all of the above explicitly, based on an appropriate plot.*
>
> ![[rompho-2024-exp-solutions-p12-f1.png]]
>
> **Question C.2.** For this question, we set $T = 1$, and we perform 100 runs each for each of the external fields $H = 0.1$ and $H = 1$. For $H = 0.1$, after 98 of the 100 runs, the spins were aligned on the same direction with the external field (positive magnetization). For $H = 1$, all 100 runs led to a positive magnetization. Thus, we conclude that indeed the direction oriented along the field is preferred in this case.
>
> *Note for graders: award full marks for similar observations made on at least 20 runs for each field.*
>
> **Question C.3.** The plot below shows the magnetization-applied field dependences at five different temperatures. One notices that the magnetization increases with the applied field, and that after an initial linear increase regime, the magnetization tends to saturate. As the temperature increases, the dependences become less and less saturated.
>
> *Note for graders: award full marks for a similar plot with the same remarks, for five different temperatures.*
>
> ![[rompho-2024-exp-solutions-p13-f1.png]]
>
> **Question C.4.** The above dependences allow us to extract the susceptibilities. In the table below we show the obtained susceptibilities at the different temperatures. To compare with the Curie-Weiss law, we study a linearized dependence $\chi^{-1}(T)$, shown in the figure below. The data is very well fit by a line. From the slope and the intercept of the line, we obtain the Curie temperature
> $T_c = 2.58 \pm 0.16$.
>
> This value is in line with the ones obtained previously but it is slightly larger, showing that the Curie-Weiss model of paramagnetism does not quantitatively reproduce the results of the Ising model. Still, such a model yields impressively many of the same qualitative features.
>
> *Note for graders: for full marks, the participants need to show a data table with at least five susceptibilities. All results need to be presented with error bars. Any reasonable comparison with the Curie-Weiss law is acceptable. The takeaways of the discussion need to be those mentioned above.*
>
> [124]:
> | | T | chi | chi err |
> |---|---:|---:|---:|
> | 0 | 3.0 | 3.405652 | 0.170283 |
> | 1 | 3.5 | 1.664007 | 0.083200 |
> | 2 | 4.0 | 1.019137 | 0.050957 |
> | 3 | 4.5 | 0.774814 | 0.038741 |
> | 4 | 5.0 | 0.570666 | 0.028533 |
>
> ```text
> ********************
> slope =     0.6864 +/-  0.0270
> intercept =    -1.7711 +/-  0.0886
> Tc = 2.580218391369748 +/- 0.16431716852133216
> ********************
> ```
> ![[rompho-2024-exp-solutions-p14-f1.png]]
>
> ### D. Antiferromagnetism
> **Question D.1.** The behaviour remains largely the same: there is still a phase transition and it occurs around a similar temperature. The only change is how the ordered state looks like: rather than the spins being all aligned in the same direction, they form a checkerboard pattern, where each spin tends to align in the opposite directions of its neighbors.
>
> *Note for graders: award full marks for answers including all of the above.*
>
> **Question D.2.** Magnetization is no longer the relevant order parameter as, regardless of whether the system is in an ordered or an unordered state, the magnetization will still be equal to zero. In particular, there will be no sharp change in magnetization upon the phase transition. An alternative order parameter could be, for example
>
> $$
> A = \frac{1}{L^2}\sum_{(i,j)}(-1)^{i+j}\sigma_{ij}
> $$
>
> which takes into account the tendency of neighboring spins to oppose each other through the factor $(-1)^{i+j}$. Another order parameter could be the energy of the system, that jumps from a (significantly) nonzero value to zero upon the phase transition.
>
> *Note for graders: award full marks for any of the two suggestions above.*
