---
id: nbpho-2004-intl-theory-6
olympiad: NbPhO
year: 2004
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "6"
title: "Magnets"
points: 6
aliases: ["Magnets"]
topics: ["[[4 Магнетизм]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "Определить магнитные потоки в системе постоянных магнитов и ферромагнитных шаров."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 6. Magnets (6 pts)

**NbPhO 2004** · Международная олимпиада · теория · 10–12 класс · задача 6  
Источник: [[_pdf/NbPhO/nbpho-2004.pdf#page=2|условие, стр. 2]] · [[_pdf/NbPhO/nbpho-2004.pdf#page=4|решение, стр. 4]]

Темы: [[4 Магнетизм]]

> [!abstract] Кратко (составлено моделью)
> Определить магнитные потоки в системе постоянных магнитов и ферромагнитных шаров.

Certain type of magnetic toys are made up of ferromagnetic spheres and permanent magnets of cylindrical shape. These building blocks can be used to build, for instance, a tetrahedron, see figure (letter “N” marks the northern end of a magnet). Assume that all these permanent magnets are identical and each of them alone can create a magnetic flux $\Phi$ (assuming the both ends of the magnet are in contact with a U-shaped large piece of ferromagnetic material, so that a closed ferromagnetic contour is formed). Assume also that due to high magnetic permeability of the material of the building blocks, all the magnetic field lines are constrained inside of them (i.e. in the surrounding medium, the magnetic inductance $B=0$).

![[nbpho-2004-p2-f3.svg]]

**1)** Let us designated the fluxes in each permanent magnet (magnets A–F in figure) by $\Phi_A$ – $\Phi_F$. Write down equation relating $\Phi_A$, $\Phi_B$, and $\Phi_C$ to each other (and possibly to $\Phi$) (1 pt).

**2)** Write down equation relating $\Phi_A$, $\Phi_B$, and $\Phi_F$ to each other (and possibly to $\Phi$) (1 pt).

**3)** Find the ratio $\Phi_F/\Phi_C$ (1 pt).

**4)** Find the magnetic fluxes in each permanent magnet (2 pts).

**5)** Which of the magnets is the most difficult one to remove? Motivate your answer (1 pts).

> [!answer]- Ответ
> **1** — $\Phi_A+\Phi_B+\Phi_C=3\Phi$.
>
> **2** — $\Phi_A=\Phi_B+\Phi_F$.
>
> **3** — $\Phi_F/\Phi_C=1$.
>
> **4** — $\Phi_A=\frac32\Phi$, $\Phi_C=\Phi_F=\Phi$, $\Phi_B=\Phi_D=\Phi_E=\frac12\Phi$.

> [!solution]- Решение
> # 6. Magnets (6 pts)
>
> **1)** Each permanent magnet can be considered as a solenoidal molecular current at the surface of the magnets. Suppose that each magnet has net surface current $I$. Consider triangular contour going through the interiors of the magnets $A,B,C$. According to the circulation theorem for that contour, the circulation $B_Al+B_Bl+B_Cl$ is proportional to the overall molecular current through that contour: $B_Al+B_Bl+B_Cl=3kI$. Here, $B_A$ designates magnetic inductance inside the magnet $A$; $B_B$ and $B_C$ are defined analogously. For a single magnet attached to a massive U-shaped ferromagnetic, the circulation theorem yields $B_0l=kI$ (where $B_0$ is the magnetic inductance inside the magnet; the contribution to the circulation inside a massive U-shaped ferromagnetic can be neglected, because the magnetic field there is much smaller than inside the magnet). So, $B_A+B_B+B_C=3B_0$ and
> $\Phi_A+\Phi_B+\Phi_C=3\Phi$.
>
> **2)** There are no sources of magnetic field lines (and hence of the flux), so
> $\Phi_A=\Phi_B+\Phi_F$.
>
> **3)** Due to symmetry,
> $\Phi_F/\Phi_C=1$.
>
> **4)** Upon using symmetry, $\Phi_F=\Phi_C$ and $\Phi_D=\Phi_B$. From the circulation theorem for the triangle $CDE$, $\Phi_C+\Phi_E-\Phi_B=\Phi$. From the no-flux-source condition for the vertex with magnets $E,C,B$ we obtain $\Phi_E=\Phi_C-\Phi_B$. Together with the equations form questions 1 and 2,
> $\Phi_A=\frac32\Phi$, $\Phi_C=\Phi_F=\Phi$, $\Phi_B=\Phi_D=\Phi_E=\frac12\Phi$.
>
> **5)** The larger the flux, the more difficult to remove a magnet, because the magnetic flux needs to go through the air gap which will be formed (enlarging the magnetic energy), when starting the removal. So, the answer is “A”.
