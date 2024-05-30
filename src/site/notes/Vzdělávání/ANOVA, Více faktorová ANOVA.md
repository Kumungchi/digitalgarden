---
{"dg-publish":true,"permalink":"/Vzdělávání/ANOVA, Více faktorová ANOVA/"}
---


## Ideální případ 1:  

![](https://i.imgur.com/iLPk5ZE.png)

nejsou rozdíly v průměrech

Každé pozorování nebo údaj jsou stejné 


## Ideální případ 2  
![](https://i.imgur.com/9OYUFfK.png)
-      Jsou rozdíly v průměrech

Ale jsou navazující


## Rozdíly ve složkách rozptylu

·       **1. vnitroshlukový rozptyl**

-      Ideální případ 1  

![](https://i.imgur.com/AzrEAyn.png)


-      Velký vnitr. Rozptyl

-      **Ideální případ 2  **

![](https://i.imgur.com/RZgBDhL.png)


-      Malý vnitr. Rozptyl

## 2. mezishlukový rozptyl

-      Ideální případ 1  

![](https://i.imgur.com/571YRHv.png)


-      Malý mezishl. Rozptyl resp. 0


-      Ideální případ 2  

![](https://i.imgur.com/Us9x10H.png)


-      Velký mezishl. Rozptyl



## Předpoklady pro použití ANOVY 

- A) 1 metrická (obvykle kardinální tedy intervalová) proměnná (ZÁVISLÁ) – př. příjem, spokojenost, prestiž profese

- B) 1 proměnná určující příslušnost alespoň do tří skupin (FAKTOR) – př. vzdělání, region, typ zákazníka.

 (Poznámka: v případě členění na dvě skupiny lze užít t-testy). 

-  C) Požadavek shodných rozptylů (homogenity) ve skupinách (Levene test), nezávislosti skupin. Používá se na to F kritérium a F-rozdělení.



## Základní myšlenka


![](https://i.imgur.com/SiNDzsw.png)


·       **Podíl rozptylů pomůže určit, zda je rozdíl alespoň mezi 2 průměry statisticky významný**

## Základní hypotézy analýzy rozptylu

·       **nulová hypotéza (H0):** všechny průměry ve sledovaných skupinách jsou stejné (obecně nulové hypotézy většinou tvrdí, že neexistují rozdíly, resp. závislosti)

·       **alternativní hypotéza (H1):** alespoň mezi dvěma skupinami existuje statisticky významný (zobecnitelný) rozdíl

·       **Základní možnosti rozhodnutí ve statistickém testu:**

-      A) nezamítnutí nulové hypotézy

-      B) zamítnutí nulové hypotézy (přijetí hypotézy alternativní), tedy alespoň mezi 2 skupinami existuje statisticky významný rozdíl v průměrech

-     **Pomůcka pro rozhodnutí:** vypočtená hladina statistické významnosti (Sig., p, p-level, alfa-level apod.). ***Testovacím kritériem je F-test.***

**Rozhodnutí**: Při malé hodnotě (většinou do 0,05 zamítáme H0 při větších nezamítáme)

## Ukázka na tabulce z analýzy rozptylu


![](https://i.imgur.com/fRWFhQd.png)


## Poznámky závěrem

-      Lze posuzovat vliv více faktorů (nezávislých proměnných) než jen jednoho.

-      Jedna nezávislá proměnná – jednoduchá analýza rozptylu.

-      Dvě a více nezávislých proměnných - vícefaktorová analýza rozptylu.

-       Vliv jednoho či více faktorů na několik závislých proměnných – vícerozměrná (multidimenzionální) analýza rozptylu (MANOVA)

-      V případě malých výběrů a nedodržení předpokladů analýzy rozptylu lze užít neparametrické testy – **Kruskal-Wallisův test (K-W), Friedmanův test**

# Vícefaktorová analýza rozptylu

lze rozdělit na:
 
 opakovaná měření (Repeated Measures ANOVA) - vhodná, když jsou jednotlivé subjekty vystaveny více podmínkám a chceme zjistit rozdíly mezi těmito podmínkami

 analýza kovariance (ANCOVA) - Kombinace ANOVA a regrese, slouží k testování mezi skupinami při kontrole jedné nebo více souvislých proměnných (kovariant), můžeme odstranit vliv některých nežádoucích proměnných

 vícerozměrná analýza rozptylu (MANOVA - Multivariate Analysis of Variance)
 - rozšiřuje ANOVA na více závislých proměnných současně. Je užitečná, když chceme zjistit, zda skupiny ovlivňují kombinaci těchto proměnných

**Analýza rozptylu**

 porovnání více průměrů

sledujeme **F**-statistiku: **poměr rozptylu mezi skupinami a uvnitř skupin**

vliv jedné proměnné – jednoduchá (one-way) analýza rozptylu

## Jednofaktorová analýza rozptylu

-    **faktor** je v analýze rozptylu nezávislá proměnná

-    označuje se také jako analýza rozptylu při jednoduchém třídění (one-way ANOVA)

# Vícefaktorová analýza rozptylu

-      máme-li faktorů (nezávislých proměnných) více, použijeme vícefaktorovou (dvou-, třífaktorovou apod.) ANOVu

-     označuje se někdy jako faktoriální analýza rozptylu

-    může jít o porovnání nezávislých výběrů, o opakovaná měření nebo obojí najednou (tzv. mixed design – se smíšenými efekty) – 2 skupiny osob s různými typy terapie, hmotnost měřena před a po

## Příklad:

-      neuropsycholog zkoumá oblasti mozku odpovídající za tvorbu a porozumění řeči

-      vyšetří speciálním testem 24 náhodně vybraných pacientů s poškozenou levou hemisférou mozku – polovina z nich jsou muži a polovina ženy


kromě mezipohlavních rozdílů ho zajímá rovněž, zda bude rozdíl mezi praváky a leváky (těch je rovněž 12 a 12)

-     tento design se zapisuje 2x2 ANOVA

-      2 kategorie pohlaví (muži x ženy)

-      2 kategorie laterality (leváci x praváci)


![](https://i.imgur.com/e72Hx10.png)
  

Popisné statisitky 

![](https://i.imgur.com/fQpYTy1.png)
V tabulce vidíme Průměrnou lateralitu pro může a ženy a Celkovou za každé pohlaví


-     **vícefaktorová analýza rozptylu testuje**:
	- hlavní efekty
	- interakce

Vícefaktorová analýza rozptylu

-       **hlavní efekt** (main effect) – vliv jedné nezávislé proměnné zprůměrovaný pro všechny úrovně ostatních nezávislých proměnných

-      u faktoriální ANOVy jsou testovány hlavní efekty pro všechny faktory

-       v příkladu testujeme hlavní efekt pro **pohlaví a lateralitu**  

![](https://i.imgur.com/3ywgy8F.png)



-       průkazný (na hladině 1 %) hlavní efekt pro faktor pohlaví

-       ženy mají celkově vyšší skóry než muži (16,2 vs. 11,0) - to můžeme vidět v první tabulce v celkových Skórech z každého pohlaví

**Hlavní efekt: lateralita  **

![](https://i.imgur.com/4abjRfT.png)


průkazný (na hladině 1 %) hlavní efekt pro faktor lateralita

leváci mají celkově vyšší skóry než praváci (15,3 vs. 11,9) - Z posledního řádku první tabulky

**interakce** se projeví v případě, kdy vliv jedné nezávislé proměnné není stejný na všech úrovních druhé nezávislé proměnné

 **v příkladu – je vliv laterality stejný u mužů a žen?**

-      pokud ano, není zde interakce

![](https://i.imgur.com/zZKxrZz.png)

Z grafu a první tabulky můžeme vidět, že:

- **U mužů** je rozdíl mezi leváky a praváky větší. Leváci dosahují podstatně vyššího skóre než praváci.
- **U žen** je rozdíl mezi leváky a praváky menší. Praváci dosahují skóre podobného levákům.


Z tabulky ANOVA můžeme vidět vztah pohlaví a laterality s p=0,028, což je menší než 0,05, takže může říci, že  vztah laterality není stejný u mužů a žen. To znamená, že účinek laterality na výsledky testu se liší v závislosti na pohlaví.

  **Interakce**

interakce mezi pohlavím a lateralitou je průkazná (na 5 % hladině významnosti)

u žen nehraje lateralita pro výkon v testu roli – levačky a pravačky se neliší, zatímco u mužů leváci a praváci ano

## Grafy bez a s interakcí

**bez interakce – pouze hlavní efekt**


![](https://i.imgur.com/sRUkbUR.png)


Na grafu můžeme vidět, že vnitřní efekt A a meziskupinový B, jsou bez interakce Pro A1 jsou B stejné, stejně to funguje u všech dalších grafů

**interakce**


![](https://i.imgur.com/hpMq9fI.png)


Zde už nejsou výsledky stejné a můžeme vidět interakci mezi různými skupinami A a výsledky skupiny B

## Opakovaná měření

  analýza rozptylu může být aplikována také na data z opakovaných měření

-      podobně jako t-test pro závislé výběry; analýza rozptylu se použije v případě, máme-li více než dvě měření

např. změna hmotnosti u dívek s poruchami příjmu potravy po terapii – hmotnost by mohla být měřena i několikrát v průběhu terapie

 procedura se nazývá Analýza rozptylu pro opakovaná měření (Repeated measures)

logika výpočtu je obdobná jako u analýzy rozptylu pro nezávislá data

### Opakovaná měření s další nezávislou proměnnou

 faktoriální design je možno uplatnit i u analýzy opakovaných měření

interakce zde znamená, že jsou různě velké rozdíly mezi měřeními u jednotlivých kategorií nezávislé proměnné

**příklad**: psychiatr testující léčbu anorexie by mohl soubor rozdělit na dívky podstupující terapii dobrovolně a nedobrovolně

-      interakce by mohla vypadat třeba tak, že u motivovaných dívek by došlo k nárůstu hmotnosti, zatímco u nedobrovolných pacientek ke stagnaci  

![](https://i.imgur.com/irZLVXh.png)


-      A – vnitřní efekt – měření hmotnosti

-      B – meziskupinový efekt – dobrovolnost vs. nedobrovolnost

## Analýza kovariance

kromě kategoriálních faktorů je možno do analýzy zařadit také spojitou nezávislou proměnnou – tzv. kovariát

 pak jde o analýzu kovariance (ANCOVA)

  **příklad**: šéf firmy obdrží stížnost od zaměstnankyň, že ženy mají nižší platy než muži

podle porovnání průměrů to tak vypadá, ale co kdybychom do analýzy zařadili jako další faktor (kovariát) délku praxe?

## Vícerozměrná analýza rozptylu

 je možno testovat také vliv jednoho či více faktorů na několik závislých proměnných najednou

 tato analýza se označuje jako MANOVA (multivariate analysis of variance)

**příklad**: psycholog chce porovnat strukturu intelektu u mužů a žen

zadá jim IST (test struktury inteligence) s 9 subtesty

těchto 9 závislých proměnných pak porovná pro pohlaví subjektů jako faktor

# Kontrolní otázky

## Jaké typy rozptylu jsou v analýze rozptylu porovnávány?
 V analýze rozptylu (ANOVA) se porovnávají následující typy rozptylu:

1. **Meziskupinový (Between-Group) rozptyl:**
    
    - Tento rozptyl měří variabilitu mezi průměry různých skupin. Zkoumá, jak se jednotlivé skupiny liší mezi sebou.
    
1. **Vnitroskupinový (Within-Group) rozptyl:**
    
    - Tento rozptyl měří variabilitu uvnitř jednotlivých skupin. Zkoumá, jak jednotlivé hodnoty uvnitř každé skupiny kolísají kolem skupinového průměru.
    -
1. **Celkový (Total) rozptyl:**
    
    - Tento rozptyl je součtem meziskupinového a vnitroskupinového rozptylu a představuje celkovou variabilitu v datech.

## Uveďte příklady výzkumných plánů, při kterých by bylo možno použít:
#### Faktoriální analýza rozptylu (Factorial ANOVA):

Faktoriální ANOVA se používá, když chceme studovat efekt dvou nebo více nezávislých proměnných (faktorů) a jejich interakci na závislou proměnnou.

- **Příklad výzkumného plánu:**
    - **Výzkum:** Zkoumání vlivu typu výuky (tradiční vs. digitální) a typu školy (veřejná vs. soukromá) na výsledky studentů v testu.
    - **Nezávislé proměnné (faktory):** Typ výuky (2 úrovně: tradiční, digitální), typ školy (2 úrovně: veřejná, soukromá).
    - **Závislá proměnná:** Výsledky studentů v testu.

#### Analýza opakovaných měření s kovariátem (Repeated Measures ANCOVA):

Tento typ analýzy se používá, když jsou měření prováděna opakovaně na stejných subjektech a chceme kontrolovat vliv jedné nebo více kovariant (např. předchozí skóre nebo jiné proměnné).

- **Příklad výzkumného plánu:**
    - **Výzkum:** Hodnocení účinnosti různých typů terapie (kognitivní, behaviorální) na snížení úzkosti u pacientů, přičemž kontrolujeme vliv počáteční úrovně úzkosti.
    - **Nezávislé proměnné (faktory):** Typ terapie (2 úrovně: kognitivní, behaviorální).
    - **Kovariant:** Počáteční úroveň úzkosti.
    - **Závislá proměnná:** Úroveň úzkosti po terapii, měřená opakovaně v různých časových intervalech (např. po 1 měsíci, 3 měsících, 6 měsících).
#### Vícerozměrná analýza rozptylu (MANOVA):

MANOVA se používá, když máme více než jednu závislou proměnnou a chceme zjistit, zda existují rozdíly mezi skupinami ve více závislých proměnných současně.

- **Příklad výzkumného plánu:**
    - **Výzkum:** Zkoumání vlivu fyzické aktivity a stravy na různé aspekty zdraví (např. tělesná hmotnost, krevní tlak, hladina cholesterolu).
    - **Nezávislé proměnné (faktory):** Typ fyzické aktivity (3 úrovně: žádná, mírná, intenzivní), typ stravy (2 úrovně: běžná, nízkokalorická).
    - **Závislé proměnné:** Tělesná hmotnost, krevní tlak, hladina cholesterolu.

## Faktoriální analýzu rozptylu

používá k analýze efektu dvou nebo více nezávislých proměnných (faktorů) na jednu závislou proměnnou a jejich interakce.

#### Příklad výzkumného plánu:

- **Výzkum:** Zkoumání vlivu typu výuky (tradiční vs. digitální) a typu školy (veřejná vs. soukromá) na výsledky studentů v testu.
- **Nezávislé proměnné (faktory):**
    - Typ výuky (2 úrovně: tradiční, digitální)
    - Typ školy (2 úrovně: veřejná, soukromá)
- **Závislá proměnná:** Výsledky studentů v testu


## Analýzu opakovaných měření s kovariátem

používá, když jsou měření prováděna opakovaně na stejných subjektech a chceme kontrolovat vliv jedné nebo více kovariant.

#### Příklad výzkumného plánu:

- **Výzkum:** Hodnocení účinnosti různých typů terapie (kognitivní, behaviorální) na snížení úzkosti u pacientů, přičemž kontrolujeme vliv počáteční úrovně úzkosti.
- **Nezávislé proměnné (faktory):**
    - Typ terapie (2 úrovně: kognitivní, behaviorální)
- **Kovariant:** Počáteční úroveň úzkosti
- **Závislá proměnná:** Úroveň úzkosti po terapii, měřená opakovaně v různých časových intervalech (např. po 1 měsíci, 3 měsících, 6 měsících)


## Vícerozměrnou analýzu rozptylu

používá se, když máme více než jednu závislou proměnnou a chceme zjistit, zda existují rozdíly mezi skupinami ve více závislých proměnných současně.

#### Příklad výzkumného plánu:

- **Výzkum:** Zkoumání vlivu fyzické aktivity a stravy na různé aspekty zdraví (např. tělesná hmotnost, krevní tlak, hladina cholesterolu).
- **Nezávislé proměnné (faktory):**
    - Typ fyzické aktivity (3 úrovně: žádná, mírná, intenzivní)
    - Typ stravy (2 úrovně: běžná, nízkokalorická)
- **Závislé proměnné:**
    - Tělesná hmotnost
    - Krevní tlak
    - Hladina cholesterolu