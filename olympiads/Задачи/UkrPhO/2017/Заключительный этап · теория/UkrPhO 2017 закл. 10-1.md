---
id: ukrpho-2017-final-theory-10-1
olympiad: UkrPhO
year: 2017
stage: "Заключительный этап"
round: теория
grade: 10
number: "10-1"
title: "Задача 10-1"
aliases: ["Задача 10-1"]
topics: ["[[1.17 Законы сохранения энергии и импульса]]", "[[1.16 Закон сохранения импульса]]"]
difficulty: 4
has_solution: true
has_hints: false
has_grading: false
source_damaged: false
summary: "По снижению орбиты станции оценить её эффективную лобовую площадь, учитывая передачу импульса частицам разреженной атмосферы."
status: "проверено: сверка, два чтения + арбитр"
lang: ru
lang_orig: uk
translated: "GPT Pro, ukrpho_tr03_p1_RESULT"
tags: [задача]
---

# 1.

**UkrPhO 2017** · Заключительный этап · теория · 10 класс · задача 10-1  
Источник: [[_pdf/UkrPhO/2017-final-theory-10-combined.pdf#page=1|условие, стр. 1]] · [[_pdf/UkrPhO/2017-final-theory-10-combined.pdf#page=3|решение, стр. 3–6]]

Темы: [[1.17 Законы сохранения энергии и импульса]], [[1.16 Закон сохранения импульса]]

> [!abstract] Кратко (составлено моделью)
> По снижению орбиты станции оценить её эффективную лобовую площадь, учитывая передачу импульса частицам разреженной атмосферы.

Международная Космическая Станция (МКС), двигаясь по приблизительно круговой орбите на высоте около 400 км со средней скоростью 7970 м/с, за 30 суток теряет 2 км высоты за счет сопротивления разреженной атмосферы (для поддержания высоты в некоторые моменты станцию ускоряют, включая ракетные двигатели). Считая, что взаимодействие МКС с атмосферой сводится к лобовому сопротивлению, и каждая частица после столкновения с поверхностью станции приобретает ее скорость, оценить эффективную площадь "лобовой поверхности" МКС, которая собирает частицы атмосферы. Масса МКС 420 тонн. Радиус Земли 6400 км. Плотность атмосферы на высоте 400 км равна $5{,}68\cdot10^{-13}$ кг/м³.

> [!answer]- Ответ
> $$
> S=\frac{m}{2\rho u(R_E+H)}\frac{\Delta H}{\Delta t}
> $$
>
> $$
> S\approx 5300\,\text{м}^2
> $$

> [!solution]- Решение
> *Решение:*
>
> Сопротивление атмосферы будет приводить к постепенному уменьшению полной энергии системы, которая складывается из потенциальной
>
> $$
> W_{\text{П}}=-\gamma\frac{Mm}{R_E+H}
> $$
>
> (здесь $\gamma$ — постоянная тяготения, $M$ и $m$ — массы Земли и МКС, $R_E$ — радиус Земли, $H$ — высота орбиты) и кинетической
>
> $$
> W_{\text{К}}=\frac{mu^2}{2}
> $$
>
> (здесь $u$ — скорость МКС). Изменение полной энергии станции за счёт передачи ей импульса от частиц атмосферы будет равно работе сил лобового сопротивления. За время $\Delta t$ высота орбиты уменьшится на $\Delta H$, а скорость возрастёт на $\Delta u$ кинетическая (более низкой орбите будет соответствовать большая скорость). Следовательно, разность энергий
>
> $$
> -\gamma\frac{Mm}{R_E+H}+\frac{mu^2}{2}-\left(-\gamma\frac{Mm}{R_E+H-\Delta H}+\frac{m(u+\Delta u)^2}{2}\right)=A(\Delta t)\tag{1}
> $$
>
> Сила лобового сопротивления составит
>
> $$
> F=u\frac{\Delta m_a}{\Delta t}
> $$
>
> (здесь $\frac{\Delta m_a}{\Delta t}$ — общая масса атмосферных частиц, столкнувшихся с лобовой поверхностью станции за единицу времени).
>
> Работа этой силы за время $\Delta t$ будет равна:
>
> $$
> A(\Delta t)=Fu\Delta t=u\frac{\Delta m_a}{\Delta t}\cdot u\Delta t=\Delta m_a\cdot u^2=\rho uS\Delta t\cdot u^2=\rho u^3S\Delta t\tag{2}
> $$
>
> (здесь $\Delta m_a$ будет общей массой атмосферных частиц, которые столкнутся с лобовой поверхностью станции за время $\Delta t$, $\rho$ — плотность атмосферы на высоте $H$, $S$ — эффективная площадь лобовой поверхности МКС, которую нам нужно найти). Таким образом, из (1) и (2) имеем:
>
> $$
> -\gamma\frac{Mm}{R_E+H}+\frac{mu^2}{2}-\left(-\gamma\frac{Mm}{R_E+H-\Delta H}+\frac{m(u+\Delta u)^2}{2}\right)=\rho u^3S\Delta t\tag{3}
> $$
>
> В составе этого выражения можно отдельно рассмотреть разность кинетических и разность потенциальных энергий. Для разности кинетических энергий имеем:
>
> $$
> W_{\text{К}}(0)-W_{\text{К}}(\Delta t)=\frac{mu^2}{2}-\frac{m(u+\Delta u)^2}{2}=\frac{mu^2}{2}\left(1-\left(1+\frac{\Delta u}{u}\right)^2\right)=\frac{mu^2}{2}\left(1-1-2\frac{\Delta u}{u}-\left(\frac{\Delta u}{u}\right)^2\right).\tag{4}
> $$
>
> Очевидно, изменение скорости МКС за счёт малой силы лобового сопротивления будет намного меньше самой её скорости ($\Delta u\ll u$). Тогда квадратом малой величины $\left(\frac{\Delta u}{u}\right)^2$ в (4) можно пренебречь. Получим:
>
> $$
> W_{\text{К}}(0)-W_{\text{К}}(\Delta t)=-mu\cdot\Delta u\tag{5}
> $$
>
> Для потенциальных энергий имеем:
>
> $$
> W_{\text{П}}(0)-W_{\text{П}}(\Delta t)=-\gamma\frac{Mm}{R_E+H}-\left(-\gamma\frac{Mm}{R_E+H-\Delta H}\right)=\gamma\frac{Mm}{(R_E+H)\left(1-\frac{\Delta H}{R_E+H}\right)}-\gamma\frac{Mm}{R_E+H}.\tag{6}
> $$
>
> Домножим числитель и знаменатель первого слагаемого в (6) на $\left(1+\frac{\Delta H}{R_E+H}\right)$.
>
> $$
> \gamma\frac{Mm\left(1+\frac{\Delta H}{R_E+H}\right)}{(R_E+H)\left(1-\frac{\Delta H}{R_E+H}\right)\left(1+\frac{\Delta H}{R_E+H}\right)}-\gamma\frac{Mm}{R_E+H}=\gamma\frac{Mm\left(1+\frac{\Delta H}{R_E+H}\right)}{(R_E+H)\left(1-\left(\frac{\Delta H}{R_E+H}\right)^2\right)}-\gamma\frac{Mm}{R_E+H}\tag{7}
> $$
>
> Квадратом малой величины $\left(\frac{\Delta H}{R_E+H}\right)^2$ также можно пренебречь. Тогда получится:
>
> $$
> W_{\text{П}}(0)-W_{\text{П}}(\Delta t)=\gamma\frac{Mm}{R_E+H}\left(1+\frac{\Delta H}{R_E+H}\right)-\gamma\frac{Mm}{R_E+H}=\gamma\frac{Mm}{(R_E+H)^2}\Delta H.\tag{8}
> $$
>
> С учётом (5) и (8) выражение (3) запишется в следующем виде:
>
> $$
> W_{\text{П}}(0)+W_{\text{К}}(0)-W_{\text{П}}(\Delta t)-W_{\text{К}}(\Delta t)=\gamma\frac{Mm}{(R_E+H)^2}\Delta H-mu\cdot\Delta u=\rho u^3S\Delta t\tag{9}
> $$
>
> Откуда получаем искомую площадь:
>
> $$
> S=\frac{\gamma Mm}{\rho u^3(R_E+H)^2}\frac{\Delta H}{\Delta t}-\frac{m}{\rho u^2}\frac{\Delta u}{\Delta t}.\tag{10}
> $$
>
> Массу Земли и ускорение $\frac{\Delta u}{\Delta t}$, которые в условии не даны, можно получить из равенства силы тяжести и центробежной силы инерции для круговой орбиты:
>
> $$
> \gamma\frac{Mm}{(R_E+H)^2}=\frac{mu^2}{R_E+H},\tag{11}
> $$
>
> то есть для высот $H$ и $H-\Delta H$ имеем:
>
> $$
> \gamma\frac{M}{R_E+H}=u^2,\qquad\gamma\frac{M}{R_E+H-\Delta H}=(u+\Delta u)^2,
> $$
>
> то есть
>
> $$
> \gamma\frac{M}{(R_E+H)\left(1-\frac{\Delta H}{R_E+H}\right)}=u^2\left(1+\frac{\Delta u}{u}\right)^2.\tag{12}
> $$
>
> В этом выражении, аналогично (7), в левой части можно домножить числитель и знаменатель на $\left(1+\frac{\Delta H}{R_E+H}\right)$ и после этого пренебречь $\left(\frac{\Delta H}{R_E+H}\right)^2$ в знаменателе. В правой части можно раскрыть скобки и пренебречь $\left(\frac{\Delta u}{u}\right)^2$. Получим:
>
> $$
> \gamma\frac{M\left(1+\frac{\Delta H}{R_E+H}\right)}{(R_E+H)\left(1-\frac{\Delta H}{R_E+H}\right)\left(1+\frac{\Delta H}{R_E+H}\right)}=\gamma\frac{M\left(1+\frac{\Delta H}{R_E+H}\right)}{(R_E+H)\left(1-\left(\frac{\Delta H}{R_E+H}\right)^2\right)}=u^2\left(1+2\frac{\Delta u}{u}+\left(\frac{\Delta u}{u}\right)^2\right)
> $$
>
> $$
> \gamma\frac{M}{(R_E+H)}\left(1+\frac{\Delta H}{R_E+H}\right)=u^2\left(1+\frac{2\Delta u}{u}\right),
> $$
>
> то есть в итоге
>
> $$
> \gamma\frac{M}{(R_E+H)^2}\Delta H\approx 2u\Delta u.\tag{13}
> $$
>
> Откуда можно найти изменение скорости $\Delta u$ через изменение высоты $\Delta H$:
>
> $$
> \Delta u=\frac{\gamma M}{2u(R_E+H)^2}\Delta H.\tag{14}
> $$
>
> Подставим (14) в выражение для площади (10).
>
> $$
> S=\frac{\gamma Mm}{\rho u^3(R_E+H)^2}\frac{\Delta H}{\Delta t}-\frac{m}{\rho u^2}\frac{\Delta u}{\Delta t}=\frac{\gamma Mm}{\rho u^3(R_E+H)^2}\frac{\Delta H}{\Delta t}-\frac{m}{\rho u^2}\frac{\gamma M}{2u(R_E+H)^2}\frac{\Delta H}{\Delta t}=\frac{\gamma Mm}{2\rho u^3(R_E+H)^2}\frac{\Delta H}{\Delta t},
> $$
>
> То есть эффективная площадь лобовой поверхности:
>
> $$
> S==\frac{\gamma Mm}{2\rho u^3(R_E+H)^2}\frac{\Delta H}{\Delta t}.\tag{15}
> $$
>
> Также из (11) для массы Земли можно записать:
>
> $$
> M=\frac{u^2}{\gamma}(R_E+H).\tag{16}
> $$
>
> Подставив (16) в (15), получим:
>
> $$
> S=\frac{m}{2\rho u(R_E+H)}\frac{\Delta H}{\Delta t}\tag{17}
> $$
>
> Отметим, что в этой формуле также удалось избавиться от гравитационной постоянной. Подставим теперь численные значения. Скорость потери высоты $\frac{\Delta H}{\Delta t}$ по условию составляет 2 км за 30 суток. Тогда
>
> $$
> \frac{\Delta H}{\Delta t}=\frac{2000}{30*24*60*60}\approx 7.72\cdot10^{-4}\,\frac{\text{м}}{\text{с}}.
> $$
>
> Подставив это, а также все остальные значения в (17), получим:
>
> $$
> S\approx 5300\,\text{м}^2\tag{18}
> $$
>
> *Эта оценка вполне соответствует параметрам МКС, которая имеет линейные размеры 108.5 м х 72.8 м х 20 м и оснащена солнечными батареями общей площадью около 4000м².*

> [!original]- Оригинал (украинский)
> # 1.
>
> Міжнародна Космічна Станція (МКС), рухаючись по приблизно коловій орбіті на висоті близько 400 км із середньою швидкістю 7970 м/с, за 30 діб втрачає 2 км висоти за рахунок опору розрідженої атмосфери (для утримання висоти у деякі моменти станцію прискорюють, вмикаючи ракетні двигуни). Вважаючи, що взаємодія МКС з атмосферою зводиться до лобового опору, і кожна частинка після зіткнення з поверхнею станції набуває її швидкості, оцінити ефективну площу «лобової поверхні» МКС, що збирає частинки атмосфери. Маса МКС 420 тон. Радіус Землі 6400 км. Густина атмосфери на висоті 400 км дорівнює $5{,}68\cdot10^{-13}$ кг/м³.
>
> > [!solution]- Розв’язання
> > *Розв'язок:*
> >
> > Опір атмосфери призводитиме до поступового зменшення повної енергії системи, яка складається з потенціальної
> >
> > $$
> > W_{\text{П}}=-\gamma\frac{Mm}{R_E+H}
> > $$
> >
> > (тут $\gamma$ — стала сили тяжіння, $M$ та $m$ — маси Землі та МКС, $R_E$ — радіус Землі, $H$ — висота орбіти) та кінетичної
> >
> > $$
> > W_{\text{К}}=\frac{mu^2}{2}
> > $$
> >
> > (тут $u$ — швидкість МКС). Зміна повної енергії станції за рахунок передачі імпульсу до неї від частинок атмосфери дорівнюватиме роботі сил лобового опору. За час $\Delta t$ висота орбіти зменшиться на $\Delta H$, а швидкість зросте на $\Delta u$ кінетична (нижчій орбіті відповідатиме більша швидкість). Отже, різниця енергій
> >
> > $$
> > -\gamma\frac{Mm}{R_E+H}+\frac{mu^2}{2}-\left(-\gamma\frac{Mm}{R_E+H-\Delta H}+\frac{m(u+\Delta u)^2}{2}\right)=A(\Delta t)\tag{1}
> > $$
> >
> > Сила лобового опору складатиме
> >
> > $$
> > F=u\frac{\Delta m_a}{\Delta t}
> > $$
> >
> > (тут $\frac{\Delta m_a}{\Delta t}$ — загальна маса атмосферних частинок, що зіткнулися з лобовою поверхнею станції за одиницю часу).
> >
> > Робота цієї сили за час $\Delta t$ дорівнюватиме:
> >
> > $$
> > A(\Delta t)=Fu\Delta t=u\frac{\Delta m_a}{\Delta t}\cdot u\Delta t=\Delta m_a\cdot u^2=\rho uS\Delta t\cdot u^2=\rho u^3S\Delta t\tag{2}
> > $$
> >
> > (тут $\Delta m_a$ буде загальною масою атмосферних частинок, що зіткнуться з лобовою поверхнею станції за час $\Delta t$, $\rho$ — густина атмосфери на висоті $H$, $S$ — ефективна площа лобової поверхні МКС, яку нам треба знайти). Таким чином, з (1) та (2) маємо:
> >
> > $$
> > -\gamma\frac{Mm}{R_E+H}+\frac{mu^2}{2}-\left(-\gamma\frac{Mm}{R_E+H-\Delta H}+\frac{m(u+\Delta u)^2}{2}\right)=\rho u^3S\Delta t\tag{3}
> > $$
> >
> > У складі цього виразу можна окремо розглянути різницю кінетичних і різницю потенціальних енергій. Для різниці кінетичних енергій маємо:
> >
> > $$
> > W_{\text{К}}(0)-W_{\text{К}}(\Delta t)=\frac{mu^2}{2}-\frac{m(u+\Delta u)^2}{2}=\frac{mu^2}{2}\left(1-\left(1+\frac{\Delta u}{u}\right)^2\right)=\frac{mu^2}{2}\left(1-1-2\frac{\Delta u}{u}-\left(\frac{\Delta u}{u}\right)^2\right).\tag{4}
> > $$
> >
> > Очевидно, зміна швидкості МКС за рахунок малої сили лобового опору буде набагато меншою за саму її швидкість ($\Delta u\ll u$). Тоді квадратом малої величини $\left(\frac{\Delta u}{u}\right)^2$ у (4) можна знехтувати. Отримаємо:
> >
> > $$
> > W_{\text{К}}(0)-W_{\text{К}}(\Delta t)=-mu\cdot\Delta u\tag{5}
> > $$
> >
> > Для потенціальних енергій маємо:
> >
> > $$
> > W_{\text{П}}(0)-W_{\text{П}}(\Delta t)=-\gamma\frac{Mm}{R_E+H}-\left(-\gamma\frac{Mm}{R_E+H-\Delta H}\right)=\gamma\frac{Mm}{(R_E+H)\left(1-\frac{\Delta H}{R_E+H}\right)}-\gamma\frac{Mm}{R_E+H}.\tag{6}
> > $$
> >
> > Домножимо чисельник та знаменник першого доданку в (6) на $\left(1+\frac{\Delta H}{R_E+H}\right)$.
> >
> > $$
> > \gamma\frac{Mm\left(1+\frac{\Delta H}{R_E+H}\right)}{(R_E+H)\left(1-\frac{\Delta H}{R_E+H}\right)\left(1+\frac{\Delta H}{R_E+H}\right)}-\gamma\frac{Mm}{R_E+H}=\gamma\frac{Mm\left(1+\frac{\Delta H}{R_E+H}\right)}{(R_E+H)\left(1-\left(\frac{\Delta H}{R_E+H}\right)^2\right)}-\gamma\frac{Mm}{R_E+H}\tag{7}
> > $$
> >
> > Квадратом малої величини $\left(\frac{\Delta H}{R_E+H}\right)^2$ також можна знехтувати. Тоді вийде:
> >
> > $$
> > W_{\text{П}}(0)-W_{\text{П}}(\Delta t)=\gamma\frac{Mm}{R_E+H}\left(1+\frac{\Delta H}{R_E+H}\right)-\gamma\frac{Mm}{R_E+H}=\gamma\frac{Mm}{(R_E+H)^2}\Delta H.\tag{8}
> > $$
> >
> > Враховуючи (5) та (8), вираз (3) запишеться у такому вигляді:
> >
> > $$
> > W_{\text{П}}(0)+W_{\text{К}}(0)-W_{\text{П}}(\Delta t)-W_{\text{К}}(\Delta t)=\gamma\frac{Mm}{(R_E+H)^2}\Delta H-mu\cdot\Delta u=\rho u^3S\Delta t\tag{9}
> > $$
> >
> > Звідки маємо шукану площу:
> >
> > $$
> > S=\frac{\gamma Mm}{\rho u^3(R_E+H)^2}\frac{\Delta H}{\Delta t}-\frac{m}{\rho u^2}\frac{\Delta u}{\Delta t}.\tag{10}
> > $$
> >
> > Масу Землі та прискорення $\frac{\Delta u}{\Delta t}$, які за умовою не даються, можна отримати з рівності сили тяжіння й відцентрової сили інерції для колової орбіти:
> >
> > $$
> > \gamma\frac{Mm}{(R_E+H)^2}=\frac{mu^2}{R_E+H},\tag{11}
> > $$
> >
> > тобто для висот $H$ та $H-\Delta H$ маємо:
> >
> > $$
> > \gamma\frac{M}{R_E+H}=u^2,\qquad\gamma\frac{M}{R_E+H-\Delta H}=(u+\Delta u)^2,
> > $$
> >
> > тобто
> >
> > $$
> > \gamma\frac{M}{(R_E+H)\left(1-\frac{\Delta H}{R_E+H}\right)}=u^2\left(1+\frac{\Delta u}{u}\right)^2.\tag{12}
> > $$
> >
> > В цьому виразі, аналогічно до (7), у лівій частині можна домножити чисельник та знаменник на $\left(1+\frac{\Delta H}{R_E+H}\right)$ і після цього знехтувати $\left(\frac{\Delta H}{R_E+H}\right)^2$ у знаменнику. У правій частині можна розкрити дужки і знехтувати $\left(\frac{\Delta u}{u}\right)^2$. Отримаємо:
> >
> > $$
> > \gamma\frac{M\left(1+\frac{\Delta H}{R_E+H}\right)}{(R_E+H)\left(1-\frac{\Delta H}{R_E+H}\right)\left(1+\frac{\Delta H}{R_E+H}\right)}=\gamma\frac{M\left(1+\frac{\Delta H}{R_E+H}\right)}{(R_E+H)\left(1-\left(\frac{\Delta H}{R_E+H}\right)^2\right)}=u^2\left(1+2\frac{\Delta u}{u}+\left(\frac{\Delta u}{u}\right)^2\right)
> > $$
> >
> > $$
> > \gamma\frac{M}{(R_E+H)}\left(1+\frac{\Delta H}{R_E+H}\right)=u^2\left(1+\frac{2\Delta u}{u}\right),
> > $$
> >
> > тобто врешті
> >
> > $$
> > \gamma\frac{M}{(R_E+H)^2}\Delta H\approx 2u\Delta u.\tag{13}
> > $$
> >
> > Звідки можна знайти зміну швидкості $\Delta u$ через зміну висоти $\Delta H$:
> >
> > $$
> > \Delta u=\frac{\gamma M}{2u(R_E+H)^2}\Delta H.\tag{14}
> > $$
> >
> > Підставимо (14) у вираз для площі (10).
> >
> > $$
> > S=\frac{\gamma Mm}{\rho u^3(R_E+H)^2}\frac{\Delta H}{\Delta t}-\frac{m}{\rho u^2}\frac{\Delta u}{\Delta t}=\frac{\gamma Mm}{\rho u^3(R_E+H)^2}\frac{\Delta H}{\Delta t}-\frac{m}{\rho u^2}\frac{\gamma M}{2u(R_E+H)^2}\frac{\Delta H}{\Delta t}=\frac{\gamma Mm}{2\rho u^3(R_E+H)^2}\frac{\Delta H}{\Delta t},
> > $$
> >
> > Тобто ефективна площа лобової поверхні:
> >
> > $$
> > S==\frac{\gamma Mm}{2\rho u^3(R_E+H)^2}\frac{\Delta H}{\Delta t}.\tag{15}
> > $$
> >
> > Також з (11) для маси Землі можна записати:
> >
> > $$
> > M=\frac{u^2}{\gamma}(R_E+H).\tag{16}
> > $$
> >
> > Підставивши (16) у (15), отримаємо:
> >
> > $$
> > S=\frac{m}{2\rho u(R_E+H)}\frac{\Delta H}{\Delta t}\tag{17}
> > $$
> >
> > Зазначимо, що у цій формулі також вдалося позбавитися від гравітаційної сталої. Підставимо тепер числові значення. Швидкість втрати висоти $\frac{\Delta H}{\Delta t}$ за умовою складає 2 км за 30 діб. Тоді
> >
> > $$
> > \frac{\Delta H}{\Delta t}=\frac{2000}{30*24*60*60}\approx 7.72\cdot10^{-4}\,\frac{\text{м}}{\text{с}}.
> > $$
> >
> > Підставивши це, а також усі інші значення у (17), отримаємо:
> >
> > $$
> > S\approx 5300\,\text{м}^2\tag{18}
> > $$
> >
> > *Ця оцінка цілком відповідає параметрам МКС, яка має лінійні розміри 108.5 м х 72.8 м х 20 м та оснащена сонячними батареями загальною площею близько 4000м².*
