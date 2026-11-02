---
id: nbpho-2024-intl-theory-4
olympiad: NbPhO
year: 2024
stage: "Международная олимпиада"
round: теория
grade: "10–12"
number: "4"
title: "Totality"
points: 8
authors: ["Taavet Kalda", "Jaan Kalda"]
aliases: ["Totality"]
topics: ["[[1.6 Векторная кинематика]]", "[[1.3 Равноускоренное криволинейное движение]]", "[[6.1 Отражение]]"]
difficulty: 5
has_solution: true
has_hints: false
has_grading: true
source_damaged: false
summary: "По длительности полного солнечного затмения определить размеры и движение его полосы и частоту наблюдений."
status: "проверено: сверка"
lang: en
tags: [задача]
---

# 4. Totality (8 points) — Taavet Kalda, Jaan Kalda.

**NbPhO 2024** · Международная олимпиада · теория · 10–12 класс · задача 4  
Источник: [[_pdf/NbPhO/nbpho-2024.pdf#page=1|условие, стр. 1]] · [[_pdf/NbPhO/nbpho-2024.pdf#page=5|решение, стр. 5–6]]

Темы: [[1.6 Векторная кинематика]], [[1.3 Равноускоренное криволинейное движение]], [[6.1 Отражение]]

> [!abstract] Кратко (составлено моделью)
> По длительности полного солнечного затмения определить размеры и движение его полосы и частоту наблюдений.

Total solar eclipses are a rare phenomenon which occur when the Moon completely covers the disk of the Sun for some parts of the Earth. This doesn’t happen during every solar eclipse because the Moon’s apparent size in the sky is sometimes too small to fully cover the Sun, but also because the Moon’s shadow usually misses the Earth due its orbital inclination. As a result, total solar eclipses occur on average every 18 months.

Let us consider a total solar eclipse where during the peak, the centre-points of Earth, the Moon and the Sun lie on a line on the same plane as the equator. We measure that right before the total solar eclipse ends at latitude $\lambda = 28.5^\circ$, the totality lasts for $t_0 = 2\,\mathrm{min}$. Earth’s radius is $r_e = 6370\,\mathrm{km}$, Moon’s radius is $r_m = 1740\,\mathrm{km}$, orbital period of the Moon $T_m = 27.3\,\mathrm{d}$, orbital radius of the Moon $R_m = 384000\,\mathrm{km}$. One day on Earth is $T_0 = 24\,\mathrm{hrs}$.

**i)** (1.5 points) For how long is there a place on Earth where the total solar eclipse is observable?

**ii)** (1 point) How many degrees in longitude on Earth does the total solar eclipse cover?

**iii)** (1.5 points) What is the width of the path of totality near the equator?

**iv)** (1.5 points) What is the longest amount of time the total eclipse is visible for a single location on Earth?

**v)** (1 point) For how long is the total eclipse near the location described in iii), at the distance of $a = 50\,\mathrm{km}$ from the centreline of the eclipse path?

**vi)** (1.5 points) Find the average time interval between two total solar eclipses for a given location on Earth by making the following simplifying assumptions:

a) the average width of the full eclipse path is equal to the arithmetic average of its smallest and largest width;

b) typical width of a full eclipse path is half of the average width of the eclipse studied above;

c) typical length of a full eclipse path is equal to the length of the eclipse path studied above if the Earth were not rotating;

d) total solar eclipses occur with equal likelihood anywhere on Earth.

> [!answer]- Ответ
> **i**
>
> $$
> T_{ecl}=\frac{2r_e}{v_m}=\frac{r_e}{\pi R_m}T_m\approx12.5\times10^3\,\mathrm s=3.46\,\mathrm h.
> $$
>
> **ii** — $|180(1-2T_{ecl}/T_0)|\approx128$ degrees.
>
> **iii** — $w_{eq}=v_mt_0+\alpha r_e=180\,\mathrm{km}$.
>
> **iv** — $t_{eq}=w_{eq}/v_{rel}=276\,\mathrm s=4.6\,\mathrm{min}$.
>
> **v**
>
> $$
> \frac1{v_{rel}}\sqrt{w_{eq}^2-4a^2}=230\,\mathrm s=3.8\,\mathrm{min}.
> $$
>
> **vi**
>
> $$
> \frac{16r_e}{w_\lambda+w_{eq}}\cdot18\text{ months}\approx500\text{ years}.
> $$

> [!solution]- Решение
> # 4. Totality (8 points) — Solution by Tudor Plopeanu, Taavet Kalda.
>
> **i)** (1.5 points) As the distance from the Moon to the Sun is much larger than the distance from the Moon to the Earth, we can consider the speed of the Moon’s shadow on Earth to be equal to the Moon’s speed altogether. The speed of the Moon is the ratio of the circumference of its orbit to its period:
>
> $$v_m=\frac{2\pi R_m}{T_m}=1.02\,\mathrm{km/s}.$$
>
> Because during the peak of the eclipse, the centre-points of Earth, the Moon and the Sun lie on the same line, the shadow of the Moon must move along the diameter of the Earth when viewed face-on. As such, the shadow travels a distance of $2r_e$ while it’s still visible on Earth and the eclipse will be observable for time
>
> $$T_{ecl}=\frac{2r_e}{v_m}=\frac{r_e}{\pi R_m}T_m\approx12.5\times10^3\,\mathrm s=3.46\,\mathrm h.$$
>
> **ii)** (1 point) In absence of the Earth’s rotation, the Moon’s shadow would cover close to $\pi$ radians. Over $T_{ecl}$, the Earth rotates by $2\pi\frac{T_{ecl}}{T_0}$ radians. The Earth’s rotation goes ”in the same direction” as the Moon’s shadow, and therefore the total longitudinal reach of the eclipse is
>
> $|180(1-2T_{ecl}/T_0)|\approx128$ degrees.
>
> **iii)** (1.5 points) Right near the end of the eclipse, the Earth’s rotation moves the surface under the Moon’s shadow almost perpendicularly to the Moon’s shadow’s velocity. As such, the width of the Moon’s shadow is equal to the distance travelled by the Moon’s shadow for the duration of the totality at that point,
>
> $$w_\lambda=v_mt_0=2\pi R_m\frac{t_0}{T_m}\approx123\,\mathrm{km}.$$
>
> At the equator, the surface of the Earth is closer by $r_e$ to the Moon compared to the point where the eclipse ends, serving to further increase the area of the full shadow. As the Moon covers an angle of approximately $\alpha=2r_m/R_m$ radians in the sky, when getting closer to the moon by $r_e$, the width of its shadow will increase by roughly $\alpha r_e\approx57.7\,\mathrm{km}$. As such, the total width of the shadow near the equator is around
>
> $w_{eq}=v_mt_0+\alpha r_e=180\,\mathrm{km}$.
>
> **iv)** (1.5 points) The peak of the eclipse occurs on the equator, firstly because that’s where the Moon’s shadow is the biggest due to it being closer to the Moon, but also because the Earth’s rotation is the fastest there, and the rotation of the Earth serves to lengthen the effect of the eclipse. At the equator the surface of the Earth moves with speed $v_e=2\pi r_e/T_0=0.46\,\mathrm{km/s}$. The angle between the velocity of the Earth’s surface at the equator and the Moon’s shadow’s velocity is $\lambda$, so the relative speed of the Moon’s shadow can be obtained from cosine theorem as
>
> $$v_{rel}=\sqrt{v_m^2+v_e^2-2v_mv_e\cos\lambda}=0.654\,\mathrm{km/s}.$$
>
> The duration while the eclipse can be observed during the peak is thus
>
> $t_{eq}=w_{eq}/v_{rel}=276\,\mathrm s=4.6\,\mathrm{min}$.
>
> **v)** (1 point) Because $a\ll R_e$, we can treat the relative velocity between the Moon’s shadow and Earth to be the same as in the previous subpart. The full shadow of the Moon on the Earth at the equator is a circle, and we can find the distance the Moon’s shadow has to travel over the course of the totality at a point displaced by $a$ using the Pythagorean Theorem as $2(w_{eq}^2/4-a^2)^{1/2}$. The eclipse is then observable for
>
> $$\frac1{v_{rel}}\sqrt{w_{eq}^2-4a^2}=230\,\mathrm s=3.8\,\mathrm{min}.$$
>
> **vi)** (1.5 points) With our assumptions, the typical width of an eclipse is $(w_\lambda+w_{eq})/4$, and the typical length on the surface of the Earth is $\pi r_e$. As such, a typical eclipse covers an area equal to the product of the two above values. From there, we deduce the probability of an eclipse being noticeable from a given arbitrary point on Earth as the area spanned by the eclipse, $\pi r_e(w_\lambda+w_{eq})/4$, divided by the surface area of Earth, $4\pi r_e^2$. Then, the expected number of eclipses until one covers a given arbitrary point is the multiplicative inverse of the above probability. As eclipses occur, on average, every 18 months, the expected time for this to happen is
>
> $$\frac{16r_e}{w_\lambda+w_{eq}}\cdot18\text{ months}\approx500\text{ years}.$$

> [!grading]- Критерии оценивания
> Grading: (preliminary)
>
> | Criterion | Points |
> |---|---|
> | In this task, numerical errors in the answers give (as long as the answer is reasonable) | -0.1 pts |
>
> **i)**
>
> Grading: (preliminary)
>
> | Criterion | Points |
> |---|---|
> | Explains that the moons shadow can be approximated by the moons position | 0.5 pts |
> | Correct speed of the moon | 0.5 pts |
> | Correct final expression | 0.5 pts |
> | Minor mistake in final expression | -0.2 pts |
>
> **ii)**
>
> Grading: (preliminary)
>
> | Criterion | Points |
> |---|---|
> | Figures out that the angle is $\pi$ without the rotation of the earth | 0.3 pts |
> | Explains that the angle becomes smaller than $\pi$ due to earths rotation | 0.3 pts |
> | Correct final formula and answer | 0.4 pts |
> | Thinks earths rotation goes against the moons rotation and obtains an angle $>\pi$ | -0.3 pts |
>
> **iii)**
>
> Grading: (preliminary)
>
> | Criterion | Points |
> |---|---|
> | Realizes that the velocities are perpendicular at the end of the eclipse | 0.4 pts |
> | Calculates the width of the eclipse at some point on earth | 0.5 pts |
> | Correctly finds how to translate the width to the width at the equator | 0.5 pts |
> | Correct final answer | 0.1 pts |
>
> **iv)**
>
> Grading: (preliminary)
>
> | Criterion | Points |
> |---|---|
> | Shows that the eclipse must be observable the longest time at the equator | 0.5 pts |
> | Finds the relative velocity between the moon’s shadow and the velocity of the surface of the earth | 0.5 pts |
> | From this finds the formula for the maximum duration of the eclipse | 0.5 pts |
> | Forgetting to take the angle between the velocities into account | -0.3 pts |
>
> **v)**
>
> Grading: (preliminary)
>
> | Criterion | Points |
> |---|---|
> | Argues that the relative velocity is approximately the same as in the previous task | 0.5 pts |
> | Correct geometry and answer | 0.5 pts |
>
> **vi)**
>
> Grading: (preliminary)
>
> | Criterion | Points |
> |---|---|
> | Shows that the probability per eclipse is equal to the area covered by the eclipse divided by the total area of the earth | 0.5 pts |
> | Finds the area covered by one eclipse | 0.5 pts |
> | Correctly multiplies the inverse probability with the duration between eclipses and finds the correct answer | 0.5 pts |
