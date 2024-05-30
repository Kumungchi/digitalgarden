---
{"dg-publish":true,"permalink":"/Vzdělávání/Vzorečky na metody/"}
---


Vypracoval Robin Kovář

## Dvouvýběrový t-test

$$t = \frac{x_1 - x_2}{\sqrt{\frac{s_1^2}{n_1} + \frac{s_2^2}{n_2}}}$$


·       x1 a x2  - průměry 

·       s1 a s2 – směrodatné odchylky 

·       n1 a n2 – velikosti dvou nezávislých vzorků

**Kritická hodnota Pro α = 0.05 a 20 stupňů volnosti (df = 20): t​≈2.086**

## T-test pro párové hodnoty (parametrický)

$$t = \frac{\overline{d}}{\frac{s_d}{\sqrt{n}}}$$


·       d – průměr rozdílů mezi párovými hodnotami

·       sd – směrodatná odchylka rozdílů mezi párovými hodnotami

·       n – počet párů 

## Wilcoxonův test

**Postup**

1.       seřadíme čísla vzestupně, nejdříve samostatné řazení pro záporná, pak až kladná (-2, -2, 1, 2, 4, …). Když jsou dvě hodnoty stejné, opíšeme hodnotu čísla a přidáme 0,5

2.       sečtu sloupeček + a – jednotlivě = testovací kritérium  tvoří menší hodnota z celkového součtu sloupečku + nebo -

3.       Pokud je testové kritérium **menší** než **kritická hodnota , zamítáme nulovou hypotézu

## Mann-Whitneyův test

**Postup**

1.  Vzestupně seřadíme čísla a přiřadíme pořadí, pokud jsou dvě stejné hodnoty opisuji hodnoty a přičítám 0,5

2.       Udělám součet pořadí pro řádek x a y (např. první místo + druhé místo + třetí…) = Tx a Ty

3.       Použiju vzoreček u řádku x  $U_x = m*n + \frac{m(m+1)}{2} - T_x$ u
 řádku y  $U_y = mn + \frac{n(n+1)}{2} - T_y$    

a.   m – počet hodnot v prvním vzorku (x)

b.   n – počet hodnot v druhém vzorku (y)

c.   Tx nebo Ty – součet pro hodnoty v daném řádku

d.   Rx nebo Ry – v jakém pořadí jsou hodnoty potom co je seřadím

4.       Najdu testovací kritérium – vždycky menší výsledek řádku **x** nebo **y**

5.       Pokud je testovací kritérium **menší,** než kritická hodnota tak nulovou hypotézu zamítáme


## Kruskal-Walisův test

**Postup**

1.       Hodnoty seřadím vzestupně

2.       Vypočtu součet pořadí pro každou jednotlivou skupinu (např. skupina A, B,C=Ta,Tb,Tc)

3.       Výpočet celkového počtu pozorování (kolik čísel je v každé skupině) = _n_ a u jednotlivých skupin= A+B+C= na,nb,nc

4.     Dosazení do vzorce  

$H = \frac{12}{n(n+1)} \left( \frac{T_a^2}{n_a} + \frac{T_b^2}{n_b} + \frac{T_c^2}{n_c} \right) - 3(n+1)$

5.       Pokud je testovací kritérium **větší** než kritická hodnota, zamítáme nulovou hypotézu

## Dixonův test

1.       Seřadím čísla vzestupně

2.       Pokud kontroluju **nejmenší** hodnotu $Q_1 = \frac{x_2 - x_1}{x_n - x_1}$
 pokud kontroluju **největší** hodnotu:  $Q_n = \frac{x_n - x_{n-1}}{x_2 - x_1}$
 
 = testovací kritérium

a.   x1 – Nejmenší hodnota

b.   x2 – druhá nejmenší hodnota

c.   xn – největší hodnota

d.   xn-1 – druhá největší hodnota

3.       Porovnám s kritickou hodnotou (
většinou α=0,05)

4.       Pokud je testovací kritérium **větší** než kritická hodnota, vyloučíme danou hodnotu jako extrémní

## Chí kvadrátový test

$$\chi^{2}=\sum_{i=1}^{n}{\frac{(A_{i}{-}E_{i})^{2}}{E_{i}}}$$



  χ2: Chí kvadrátová statistika. Tento výsledek se porovnává s kritickou hodnotou z chí kvadrátového rozdělení, aby se rozhodlo, zda zamítneme nebo přijmeme nulovou hypotézu.

 n: Počet kategorií nebo skupin, které porovnáváme.

-   𝐴𝑖 Pozorovaná četnost v i-té kategorii. Toto jsou skutečné naměřené hodnoty.
 - 𝐸𝑖: Očekávaná četnost v i-té kategorii. Toto jsou hodnoty, které bychom očekávali na základě nulové hypotézy

- Pokud je výsledek chí-kvadrátu **vyšší** než kritická hodnota, hypotézu o shodě dvou rozdělení zamítáme.


**Testové kritérium Test dobré shody (rozdíl mezi dvěma kategoriálními)**
**Pro α = 0.05 a 2 stupně volnosti (df = 2): 5,991**


**Testové kritérium Test nezávislosti (zda pozorované četnosti v jedné kategorické odpovídají očekávaným na základě teoretického rozdělení)**
**Pro α = 0.05 a 3 stupně volnosti (df = 3): 7,815**