---
id: rompho-2021-intl-experiment-exp
olympiad: RomPhO
year: 2021
stage: "Международная олимпиада"
round: эксперимент
grade: ""
number: "exp"
title: "Measurement of $D^0$ lifetime"
aliases: ["Measurement of $D^0$ lifetime"]
topics: ["[[7 Эксперименты]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: true
source_damaged: false
summary: "Измерить время жизни мезона D⁰ по данным распадов, зарегистрированных детектором LHCb, с учётом фоновых событий."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# Experimental Problem - Measurement of $D^0$ lifetime

**RomPhO 2021** · Международная олимпиада · эксперимент  
Источник: [[_pdf/RomPhO/RomPhO-2021-exp.pdf#page=1|условие, стр. 1–13]] · [[_pdf/RomPhO/RomPhO-2021-exp-solution.pdf#page=10|критерии, стр. 10]]

Темы: [[7 Эксперименты]]

> [!abstract] Кратко (составлено моделью)
> Измерить время жизни мезона D⁰ по данным распадов, зарегистрированных детектором LHCb, с учётом фоновых событий.

## Introduction - Context overview

### Standard Model

The Standard Model of particle physics is the current theory which explains best the composition of matter to the sizes of atoms and nuclei constituents and the forces between them. Briefly, the visible matter is made of quarks (u, d, c, s, t, b) and leptons (electron, muon, taon) and their antimatter versions, anti-quarks and anti-leptons which interact between them by four fundamental forces: electromagnetic, weak, strong and gravitational, mediated by carrier particles called bosons (photons, Z, W+, W-, gluon), see the table form Figure 1 below. The quarks do not live free in nature, they combine with each other in combinations of 2, 3 or more. Combinations of three quarks are called baryons, for instance proton - (u, u, d) and neutron (u, d, d) which are also long living particles. Some combinations of three or two particles (called mesons) produce unstable particles which decay very fast.

![[rompho-2021-exp-problems-p1-f1.png]]
*Figure 1. The Standard Model table*

The unstable particles decay to less heavier particles, for instance the meson particle called D$^0$ can decay to kaon (K$^-$) consisting of a strange quark and an anti-up quark, and a pion (pi$^+$) which consists of a down anti-quark and an up quark. The +, - and 0 refer to the electric charge of the particle, whether it is positively charged, negatively charged or neutral. These particles have a lifetime which is long enough that they can be measured in current experiments.

D$^0$ (c anti-u) -> K$^-$ (s anti-u) + pi$^+$(u anti-d).

### The setup -LHCb detector

The Large Hadron Collider (LHC) is the largest research infrastructure dedicated for discovering the laws of the subatomic world. The LHCb detector, shown in Fig. 2., is one of the four large scale instruments which record the proton - proton collisions delivered by LHC. The LHCb has many layered subdetectors which contributes to reconstructing the trajectories of the particles coming out of the initial collisions. The place where the protons collide is called the primary vertex, while the places where unstable particles decay (like D0, or exotic particles) are called secondary (tertiary) vertices, or displaced vertices. The presence of the displaced vertices is a sign of an interesting event for physics. The LHCb is able to record the displaced vertices due to its detector called VELO, see Fig, 2, which is very close to the place where protons collide.

![[rompho-2021-exp-problems-p2-f1.png]]
*Figure 2: The LHCb detector. The Z axis is the direction of the LHC beamline.*

### The data

The data sample used for this exercise consists of candidates for a type of charmed particle known as a D$^0$ particle (and the anti-particle $\underline{D}^0$) found in a sample of randomly collected LHC interactions during 2011 datataking. The particles are measured decaying in the following mode $D^0\to K^-+\pi^+$ (and the conjugate mode $\underline{D}^0\to K^++\pi^-$) and they have been preselected such that you can see clearly the signal. In the same dataset there are also other events which are not true D0 candidates but which could not be eliminated with imposed conditions. These candidates are called background in the context of this exercise.

A distinctive feature of D$^0$ particles is their measurably long lifetime (the object of this exercise). From a practical point of view, this means that they form a "secondary" vertex which is displaced from the "primary" proton-proton interaction. This is illustrated in Fig. 3. Even with these distinctive features, background events, most of which consists of random combinations of particles produced in the proton-proton collision, are still present.

![[rompho-2021-exp-problems-p3-f1.png]]
*Figure 3: The D$^0$ particle secondary vertex ("D") displaced from the pp interaction.*

## The application

You will access the data through a graphical user interface (GUI) which is described below. For connectivity you should consult the technical guide available to you. The overall goal of the exercises is to determine the lifetime of the particle $D^0$ and the associated measurement uncertainties.

![[rompho-2021-exp-problems-p4-f1.png]]

For the first exercise you will use the ‘Event Display’ part of the application, while for the exercises 2 and 3 you will use the ‘D0 Exercise’ part of the application.

Notes:

- You can run in parallel more than one instance of the application
- To activate the ‘D0 exercise’ button you should first select at least one event in the ‘Event display’ part.
- The final saving of your plots, tables, notes will be done outside the application according to the technical guide.
- If during the contest you lose the internet connections you will lose the plots from inside the application, but you still have the ones saved on your computer.

## Exercise 1: Visual search

In this exercise you will use the first part of the application called ‘Event display’. You will have access to a visualization of the particle trajectories ("tracks") recorded by the LHCb experiment after a proton - proton collision. Each one will have access to 30 events, they are selected from the menu tab `Combinations`. Choose the combination with the number communicated to you.

The event display allows you to locate the displaced vertices belonging to D$^0$ particles in the vertex detector of the LHCb experiment. The tracks are colour coded, and a legend at the bottom of the GUI tells you which colour corresponds to which kind of particle. In order to make identifying vertices easier, you can view an event in three different two-dimensional projections: y-z, y-x, and x-z, show for one event in Fig. 4. Different events will be clearer in different projections! Displaced vertices appear as a pair of intersecting tracks, far away from the other tracks in the event. When you click on a particle, you will see its information, including mass and momentum, in the Particle Info box.

![[rompho-2021-exp-problems-p5-c0221.png]]
![[rompho-2021-exp-problems-p5-f2.png]]
*Figure 4: Three views of one event, in different planes: y-z, y-x, and x-z.*

A D$^0$ particle decays into a kaon and a pion, so you will need to find a displaced vertex where a kaon track intersects with a pion track. Once you find a track which you think is part of the displaced vertex, you can save it using the **Save Particle** button. Once you have saved two particles, you can compute their mass by clicking on the **Calculate** button. If you think this combination has a mass compatible with that of the D$^0$ particle, click on **Add** to save it : by saving a combination for each event, you will build up a histogram of the masses of the displaced vertices in the different events.

As you are looking at real data the set contains both signal and background, and the detector has a finite resolution, so not all displaced vertices will have exactly the D$^0$ mass (even the signal ones). They should, however, be within the range 1816-1914 MeV (this range is around 3% each way around the true D$^0$ mass). If you try to save a combination which is too far away from the real D$^0$ mass the application will warn you that you have not found the correct displaced vertex pair and won't let you save it.

### Tasks

**1.1** Look at the events you are given and for each event identify a $D^0$ or $\underline D^0$ candidate. Record, on paper or electronically, the candidates and the mass obtained in each event. Add the combination to the total mass (in the application).

| Evt. no | # D0 mass | # anti - D0 mass |
|---|---|---|
| x.1 | | |
| x.2 | | |
| x.3 | | |
| ... | | |
| ... | | |

If you are not able to find the displaced vertex for an event, you can move on to the next event and come back later to the events you skipped. Once you have looked at all events, you can examine your mass histogram by clicking the **Draw** button.

**1.2** With the data recorded, make similar histogram plots as in the previous task, distinctively for D0 and anti-D0 candidates. Compute the ratio between the number of the two types of candidates.

## Exercise 2: Measure the lifetime of D0

In this exercise you will use the second part of the application called ”D0 exercise”.

The object of this exercise is to use a data sample of about 50000 events to measure the lifetime of the D$^0$ particle. This is the same quantity as the half-life of a radioactive particle: the D$^0$ decays according to an exponential distribution, and if this exponential is fitted to a distribution of the D$^0$ decay times, the slope of this exponential is the lifetime of the D$^0$.

### Definitions:

After starting the exercise you will be able to draw plots of the data, change ranges of the variables, make fits of the invariant mass and the lifetime of the D0. The following variables will appear in the exercise:

- **D$^0$ mass:** this is the invariant mass of the D$^0$ particle. The signal can be seen as a peaking structure rising above a background. The range of masses relevant for this analysis is 1816-1914 MeV. The signal shape is described by the Gaussian (also known as "normal") distribution. The center ("mean") of this distribution is the mass of the D$^0$ particle, while the width represents the experimental resolution of the detector.
- **D$^0$ TAU:** this is the distribution of decay times of the D$^0$ candidates. The signal is described by a single exponential whose slope is the D$^0$ lifetime.
- **D0 IP:** this is the D$^0$ distance of closest approach ("impact parameter") with respect to the proton-proton interaction in the event. The smaller the impact parameter, the more likely it is that the D$^0$ actually came from that primary interaction. In order to simplify the drawing, we actually plot and cut on the logarithm (base 10) of this quantity in the exercise.
- **D$^0$ PT:** this is the momentum of the D$^0$ transverse to the LHC beamline.

### Fitting the signals: mass distribution and the lifetime

The application performs the fitting of the signal in two variables the mass of D0 and the lifetime, your choices are to select the ranges of the four variables mentioned above such that you select (and measure) the signal and remove the background events.

To obtain a value for the lifetime you will use the method of background subtraction described below.

1. Click on the **Plot D$^0$ mass** button to plot the overall mass distribution. You will see a peak (signal) on top of a distribution (background). The peak should be described by a Gaussian function, whose mean corresponds to the mass of the D$^0$ and whose width ($\sigma$) is determined by the experimental resolution of the LHCb detector.
2. Click on **Fit mass distribution** to fit this distribution using a Gaussian function for the signal and a linear function for the background.
3. Look at the fitted mass distribution. You can split it into three regions: the signal region and two background-only "sidebands": one above the signal (the upper sideband) and one below the signal (the lower sideband).
4. Use the slider labelled **Sig range** to define the beginning and end of the signal region. All events not falling into the signal region will be said to fall into the background region.
5. You can now use the definitions of the signal and background regions in the mass variable to determine the signal and background distributions in other variables. Click on the button labelled **Apply cuts and plot variables**. You will see the signal (blue) and background (red) distributions for the other three variables plotted next to the mass distribution.

You are also able to fit the lifetime of D0 at any time after you are applying some cuts. For every lifetime fit you make, we call it a measurement. Varying the cuts you can perform more measurements.

### Tasks

**2.1** Define a range for the D0 mass which should be your ‘signal region’. Comment on the criterion you used.

**2.2** Perform the fit and obtain the value and the statistical error for D0 lifetime.

**2.3** In addition to statistical uncertainties, measurements can suffer from systematic uncertainties, caused by a miscalibrated apparatus or an incorrect modelling of the backgrounds. One basic technique for estimating these is to repeat the measurement while changing the criteria used to select signal events. If the result changes significantly when changing the criteria, we know that there is something wrong!

Repeat your fit for the lifetime of the D$^0$ while varying the maximum allowed D$^0$ impact parameter. The allowed values range from -4.0 to 1.5 in the original fit. Move this upper value down, at least 10 points and make the plot of the lifetime obtained. The application records these points for you and does the plot. Save the plot (outside the application using ‘print screen’ or ‘snipping tool’, name it 2.3_YOURCODE), it will be required.

It helps to write down in a table the values shown on the screen like this

| | IP | t (lifetime) | error (statistical) |
|---|---|---|---|
| 1 | 1.5 | ... | ... |
| 2 | ... | ... | ... |
| 3 | ... | ... | ... |
| 4 | ... | ... | ... |
| ... | ... | ... | ... |

**2.4** The sigma-shaped plot you obtained is the indication of the presence of a systematic effect, which once identified can be removed. Make a hypothesis on what causes this systematic effect.

**2.5** Seeing the shape of the lifetime as a function of the upper cut on the impact parameter where would you consider to be ‘correct’ value of the lifetime? Give a criterion for where on the plot you would choose this ‘correct’ value to lie. You will do the same thing for the other variables so the criterion should be general to be applied in those cases too.

**2.6** Based on the criterion found above choose your best value for D0 lifetime the nominal value, and a range around this point. (Further you will use this range to estimate the systematic error of the measurement).

**2.7** Repeat the steps 2.3 and 2.6 for the **D$^0$ TAU** variable such that you `improve` the correct value of the lifetime. Create the table suggested above. Making the plot is optional, the application does not perform it.

**2.8** Repeat the steps 2.3 and 2.6 for the **D$^0$ PT** variable.

**2.9** Quote the final value of the D0 lifetime, called the nominal value and the statistical error associated with it.

## Exercise 3: Systematic errors

You saw previously an example of a systematic effect which was present in the initial dataset and which could be removed. Other sources of systematic uncertainty could be present for various reasons due to the phenomenon, the detector or the method we have used to make the measurement. The selection of the nominal value of the lifetime involved also choosing some ranges for every variable available for study. You can change the values of the upper cuts (or lower cuts) of these values and get more determinations of the lifetime. The study of these variations can give you an estimate of the systematic effects you have by using this method for the D0 lifetime determination.

### Tasks

**3.1** Investigate the systematic uncertainties on the D0 lifetime for every available dependent variable. Use the defined range of each variable to perform additional measurements and extract a value for the systematic uncertainty.

**Note:** Each source of uncertainty will be graded. Change only one variable at the time having the others fixed.

**3.2** Quote your final value for the D0 lifetime statistical and systematic uncertainties identified.

**3.3** Order the uncertainties you computed and comment on what source limits the most the precision of your study.

## Technical guide (tutorial for accessing the application)

Each participant will be provided from the organizers/ team leaders with the following information to connect to the application. The application is hosted inside a virtual machine at the address given below.

### Step 1. Connect to the virtual machine host

- Use the IP address: https://217.156.104.111:8006 or https://217.156.104.112:8006
- Username: (Example: BIH5_student)
- Password: xxxxxxxxxx
- a warning window will open (Warning: Potential Security Risk Ahead): Click **Advanced…** (the browser complains about missing the domain name on the URL). The page will extend, so scroll down and press the button **Accept the risk and Continue**
- the login window below will open:

![[rompho-2021-exp-problems-p10-f1.png]]
*Fig. 1*

- insert the username and password given
- at Realm: choose the **Proxmox VE authentication server**

- click **Login**
- over the next window, a new warning will appear (**No valid subscription**). Press **OK**

### Step 2. Open the virtual machine hosting the application

- From the interface, in the upper left corner select `Pool view` to see the virtual machine allocated to you/ select **Datacenter** select your dedicated machine (having your contest code) and open it.

![[rompho-2021-exp-problems-p11-f1.png]]
*Fig. 2. Select the `Pool view` to see the machine dedicated to you.*

- Double click on your machine and you should see the screen from Figure 3.
- press on **fullscreen** button as shown above

![[rompho-2021-exp-problems-p12-f1.png]]
*Fig. 3*

### Step 3. Feedback

To know that you arrived at the proper place, please access the Google Form from your computer (not in the virtual machine) at the address: https://forms.gle/hrAPzCfv7XE2NcgH8 answer the two questions and press the send button.

### Step 4. Start the application

![[rompho-2021-exp-problems-p12-f2.png]]

- to start the application, double click on the **LHC Master** link. The interface shown to the right will open
- choose the language
- write your name and surname (any character, it is not recorded)
- Grade? (any character, it is not recorded)
- Number: please introduce the given number
- In the **Set output directory** do not do anything
- To solve exercise 1 you will have to push **Event Display**
- To solve exercises 2, 3 you will have to push **D0 Exercise**

**Notes:**

- You can run in parallel more than one instance of the application
- The final saving of your plots, tables, notes will be done outside the applications.
- If during the contest you lose the internet connections you will lose the plots from inside the application, but you will still have the ones saved on your computer.

> [!solution]- Решение (схема оценивания)
> # Grading scheme for Experimental Problem
>
> ## Experimental Problem - Measurement of D0 lifetime
>
> ### Exercise 1: Visual search
>
> | Item | Content | Points |
> |---|---|---|
> | 1.1 | The table with the entries, maximum of points for all 30 events | 2,1p |
>
> | Evt. no | # D0 mass | # anti - D0 mass |
> |---|---|---|
> | x.1 | | |
> | x.2 | | |
> | x.3 | | |
> | ... | | |
> | ... | | |
>
> | Item | Content | Points |
> |---|---|---|
> | 1.2 | The histogram (an example below) and the ratio of #D0/# anti-D0 | 0,5 p |
>
> ![[rompho-2021-exp-solutions-p10-f1.png]]
>
> ### Exercise 2: Measure the lifetime of D0
>
> | Item | Content | Points |
> |---|---|---|
> | 2.1 | The central value for D0 mass 1866.6, the standard deviations 7.7. A Gaussian distribution contains 99.7% of its events within three standard deviations of the mean, so this "three σ" region around the mean is usually the definition of the signal region. The range (1843.5, 1869.7) | 1,5p |
> | 2.2 | The value and the fit of the lifetime | 0,5p |
>
> ![[rompho-2021-exp-solutions-p11-f1.png]]
>
> | Item | Content | Points |
> |---|---|---|
> | 2.3 | The plot with two levels | 1 p |
>
> ![[rompho-2021-exp-solutions-p11-f2.png]]
>
> | Item | Content | Points |
> |---|---|---|
> | 2.4 | Hypothesis of another signal coming from another particle with finite smaller lifetime. In this case the B0 mesons. Explaining the possibility of a intermediate decay | 1p |
>
> ![[rompho-2021-exp-solutions-p12-f1.png]]
>
> | Item | Content | Points |
> |---|---|---|
> | 2.5 | The working region for nominal value, of the D0 lifetime, should be a plateaux or a minimum. The uncertainty of the lifetime by variations around the nominal value should be comparable with the statistical uncertainty for the nominal value. | 1 p |
> | 2.6 | For the IP variable the nominal value should on the lower plateaux in the range (-1.7, -1.1) | 1,5p |
> | 2.7 | The measurements for the D0 TAU variable with values similar with the ones below | 1 p |
>
> | | D0 TAU | t (lifetime) | error (statistical) |
> |---|---|---|---|
> | 1 | 0,15 | 0,4268 | 0,003 |
> | 2 | 0,2 | 0,4212 | 0,003 |
> | 3 | 0,25 | 0,4195 | 0,0032 |
> | 4 | 0,3 | 0,4159 | 0,0032 |
> | ... | 0,35 | 0,416 | 0,0034 |
> | | 0,4 | 0,4122 | 0,0036 |
>
> | Item | Content | Points |
> |---|---|---|
> | 2.8 | The measurements for the D0 PT variable with values similar with the ones below | 1 p |
>
> | | D0 PT | t (lifetime) | error (statistical) |
> |---|---|---|---|
> | 1 | 2,5 | 0,4122 | 0,0036 |
> | 2 | 3 | 0,4109 | 0,0041 |
> | 3 | 3,5 | 0,4056 | 0,0045 |
> | 4 | 4 | 0,3983 | 0,005 |
> | ... | 4,5 | 0,4015 | 0,0061 |
>
> | Item | Content | Points |
> |---|---|---|
> | 2.9 | The quotation of the D0 lifetime and the ranges studied before for D0 IP, D0 TAU and D0 PT | 0,5 p |
>
> ### Exercise 3: Systematic errors
>
> | Item | Content | Points |
> |---|---|---|
> | 3.1 | Identify the availability of four variables for which the study can be made, D0 IP, D0 TAU, D0 PT and D0 Mass. For each variable it is repeated the same study of finding the uncertainty associated with choosing the allowed range and the working point. For the value of the uncertainty use a formula similar to the one below. Let x0 = nominal point. s_IP = sqrt((x_1-x0)**2 + (x_2-x0)**2 + …. (x_n-x0)**2)/n) | |
> | | s_D0 IP = | 1,6 p |
> | | s_D0 TAU = | 1,6 p |
> | | s_D0 PT = | 1,6 p |
> | | s_D0 M = | 1,6 p |
> | 3.2 | The quotation of the D0 lifetime with (1) statistical uncertainty, (2) systematic uncertainty for D0 IP (3) D0 TAU (4) D0 PT (5) D0 M | 1 p |
> | 3.3 | Order the uncertainty sources and comment on them | 1 p |
