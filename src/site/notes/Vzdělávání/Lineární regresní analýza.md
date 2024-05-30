---
{"dg-publish":true,"permalink":"/Vzdělávání/Lineární regresní analýza/"}
---



snažíme se z hodnot jedné proměnné nebo lineární kombinace více proměnných predikovat hodnoty další proměnné

dva typy proměnných: **predikovaná** (závislá) **proměnná** a **prediktory** (nezávisle proměnné)

závislá proměnná se označuje také jako **regresand**, nezávislá jako **regresor**

predikovaná proměnná se označuje **Y,** prediktory **X1 , X2 …Xn**

pouze 1 prediktor – **jednoduchá regrese**

více prediktorů – **mnohonásobná regrese**

- regresní analýza umožňuje
	- porozumět vztahům mezi proměnnými,
	- predikovat hodnoty proměnné Y z hodnot proměnné X (s určitou přesností)
	- např. z hodnot známek na střední škole a/nebo z počtu bodů u přijímacího testu předpovědět úspěšnost na VŠ

## Jednoduchá regresní analýza

## Příklad -  Jak souvisí vzdělání respondenta se vzděláním otce?

tj. jak dobře můžeme předpovědět počet let formálního vzdělání respondenta z údaje o počtu let vzdělání jeho otce?

![](https://i.imgur.com/DhHFdSV.png)

snažíme se najít rovnici tzv. regresní přímky

 **regresní přímka** je taková přímka, od které je vzdálenost bodů (představujících naměřená data) co nejmenší

taková přímka, která nejlépe vystihuje data


![](https://i.imgur.com/6hX65yw.png)


jednou z metod, jak regresní přímku nalézt, je **metoda nejmenších čtverců**

 je zvolena taková přímka, kdy platí, že součet čtverců vzdáleností jednotlivých bodů od přímky je minimální (když vezmeme jednu hodnotu, umocníme → dostaneme čtverec, neboli čtverečnou hodnotu)

![](https://i.imgur.com/Lu8k39b.png)

## Předpoklady regresní analýzy

 dostatečná variabilita všech proměnných

 rozdělení hodnot proměnných je normální

u malých výběrů zkontrolovat extrémní hodnoty

 vztahy mezi Y a každou X jsou lineární

zkontrolovat scatter plotem

vzájemné korelace mezi prediktory nejsou příliš vysoké (tzv. problém multikolinearity)

pokud ano, je vhodné buď některou z nich vyřadit, nebo z nich vytvořit např. faktorovou analýzou jeden skór

rozdělení reziduálních hodnot (reziduálů) je normální

zkontrolovat analýzou reziduálů – histogramem, pravděpodobnostním grafem






## Obecná rovnice regresní přímky  

**Y’ = a + bX**

**a** je **konstanta** (predikovaná hodnota Y, když hodnota X je 0)

**b** je **směrnice** regresní přímky (úhel přímky vzhledem k ose; kolikrát se Y zvětší s každou jednotkou X);

rozdíl mezi naměřenou a predikovanou hodnotou = **reziduální hodnota predikce**, chyba predikce (e)

$$b = r_{xy} * \frac{s_y}{s_x}$$
$$a = \overline{y} - b \cdot \overline{x}$$


 v příkladu vychází rovnice regresní přímky  

**Y’ = 9,93 + 0,32* X



- pro děti otců s 0 lety vzdělání předpovídáme necelých 10 let vzdělání

- s každým dalším rokem otcova vzdělání předpovídáme o 0,32 roku vzdělání respondenta více

-  s každým dalším rokem otcova vzdělání předpovídáme o 0,32 roku vzdělání respondenta více

![](https://i.imgur.com/ZQcLmWC.png)



- pokud proměnné standardizujeme pomocí směrodatných odchylek a průměrů na z-skóry, pak

-  regresní přímka prochází počátkem os

- regresní koeficient se rovná korelačnímu koeficientu



![](https://i.imgur.com/9CA7XPK.png)



## Mnohonásobná regresní analýza

predikujeme závislou proměnnou z více prediktorů

vliv každého z prediktorů na závislou proměnnou je **kontrolován** pro vliv všech ostatních prediktorů (jde tedy o vliv „očištěný“ od vlivů ostatních proměnných – počítáme tzv. **parciální** koeficienty)

**příklad** – kromě vzdělání otce (X1) může mít na dosažené vzdělání vliv také počet dalších dětí v rodině (X2)

-      rovnice regresní přímky je **Y’ = a + b1X1 + b2X2**

-      Y’ = 10,68 + 0,30* X1 – 0,13* X2

-      vliv vzdělání otce (b=0,30) je o něco menší než u jednoduché regresní analýzy (b=0,32) – je kontrolován pro počet dalších dětí v rodině, který je zřejmě mírně ovlivněn také vzděláním otce

-      vliv počtu dětí v rodině je záporný – tj. čím více dětí, tím nižší vzdělání

- mnohonásobná regresní analýza nám umožní srovnat vliv všech prediktorů na závislou proměnnou

- můžeme dojít k závěru, že větší vliv na vzdělání respondenta má vzdělání otce než počet dětí v rodině?

- pokud chceme srovnávat vliv prediktorů měřených v různých jednotkách, je nutné použít **standardizované regresní koeficienty** = $\beta$

- ukazují, kolikrát vzroste hodnota závislé proměnné, pokud se změní hodnota prediktoru o 1 směrodatnou odchylku a hodnoty ostatních prediktorů přitom zůstanou konstantní

![](https://i.imgur.com/FncaZjS.png)

-   $\beta$ pro vzdělání otce je 0,43 

-      pro počet dětí v rodině -0,13

-      větší vliv má tedy vzdělání otce než počet dětí v rodině

·       kromě regresních koeficientů je počítán také tzv. **koeficient mnohonásobné korelace** – korelace všech prediktorů se závislou proměnnou; ozn. **R**

- jde o korelaci mezi pozorovanými hodnotami závislé proměnné a hodnotami predikovanými na základě regresního modelu

- koeficient **mnohonásobné determinace** –% vysvětleného rozptylu (závislé proměnné) lineární kombinací prediktorů; ozn. **R2**


![](https://i.imgur.com/maczCH2.png)


-  u jednoduché regresní analýzy je **koeficient mnohonásobné korelace** roven korelaci mezi oběma proměnnými


## Testování hypotéz v regresní analýze

 jsou testovány 2 typy hypotéz

1) zda se R průkazně liší od 0

**testuje se analýzou rozptylu (porovnává rozptyl vysvětlený regresním modelem a reziduální rozptyl)**

2) zda se regresní koeficienty $\beta$ průkazně liší od 0

**testuje se t-testem**



![](https://i.imgur.com/2okhNbu.png)

## Reziduály

- výsledkem regresní analýzy jsou **predikované skóry** (na základě regresní rovnice)

- z nich je možno odvodit **reziduální skóry** – rozdíl mezi skutečnou a predikovanou hodnotou proměnné


# Shrnutí

### Účel

Regresní analýza je statistická technika používaná k modelování vztahu mezi závislou proměnnou (response variable) a jednou nebo více nezávislými proměnnými (predictor variables). 

==Účely regresní analýzy zahrnují:==

**Predikce**: Použití modelu k předpovědi hodnot závislé proměnné na základě hodnot nezávislých proměnných.

**Modelování**: Vytvoření matematického modelu, který popisuje vztah mezi proměnnými.

**Identifikace vlivu**: Zjištění, které nezávislé proměnné mají významný vliv na závislou proměnnou.

**Kvantifikace vztahů**: Odhad velikosti vlivu nezávislých proměnných na závislou proměnnou.

#### Obecná rovnice regresní funkce

Obecná rovnice lineární regresní funkce je:

y=β0+β1x1+βn​xn​+ϵ

kde:

- y je závislá proměnná.
- β0​ je intercept (průsečík y-ové osy).
- β1,….,βn​ jsou regresní koeficienty pro nezávislé proměnné x1,x2,…,xnx1​,x2​,…,xn​.
- ϵ je náhodná složka (chyba)

#### Jak se interpretují regresní koeficienty

**Intercept (β0​)**: Hodnota závislé proměnné, když jsou všechny nezávislé proměnné rovny nule.

**Regresní koeficienty (βi​)**: Odhadují změnu závislé proměnné yy při jednotkové změně nezávislé proměnné xi​, když ostatní proměnné jsou konstantní. Např. β1​ udává změnu v y při zvýšení x1​ o jednu jednotku, pokud ostatní proměnné zůstávají nezměněny.
#### Co je to koeficient mnohonásobné korelace?

Koeficient mnohonásobné korelace, označovaný jako R nebo R<sup>2</sup> v kontextu mnohonásobné lineární regrese, měří sílu a směr lineárního vztahu mezi jednou závislou proměnnou a více nezávislými proměnnými.

**R**: Koeficient mnohonásobné korelace, který je odmocninou R<sup>2</sup>.

**R<sup>2</sup>** Koeficient determinace, který udává podíl variability závislé proměnné vysvětlené modelem. Hodnoty se pohybují mezi 0 a 1, kde vyšší hodnoty naznačují lepší model.


#### Předpoklady regresní analýzy

Pro správné použití a interpretaci lineární regresní analýzy je důležité dodržet následující předpoklady:

1. **Linearita**: Vztah mezi závislou a nezávislými proměnnými je lineární.
2. **Normalita reziduí**: Rezidua (chyby) modelu jsou normálně rozdělená.
3. **Homoskedasticita**: Variance reziduí je konstantní pro všechny hodnoty nezávislých proměnných.
4. **Nezávislost reziduí**: Rezidua jsou nezávislá na sobě (neexistuje autokorelace).
5. **Nepřítomnost multikolinearity**: Nezávislé proměnné nejsou silně korelované mezi sebou, aby se zabránilo problémům s interpretací koeficientů.

Dodržení těchto předpokladů je klíčové pro validitu a spolehlivost výsledků regresní analýzy.