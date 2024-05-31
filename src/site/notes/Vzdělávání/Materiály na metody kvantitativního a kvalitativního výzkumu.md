---
{"dg-publish":true,"permalink":"/Vzdělávání/Materiály na metody kvantitativního a kvalitativního výzkumu/"}
---


Ve více vzorcích se zobrazuje tento symbol:

∑: Suma (součet). Tento symbol značí, že máme sečíst hodnoty pro všechny hodnoty (od 𝑖=1i=1 do 𝑖=𝑛i=n).

Pro lepší pochopení následující látky je dobré si připomenout co to je Normální rozdělení a Centrální limitní věta.

[[Vzdělávání/Statistika 7. hodina Normální Rozdělení\|Statistika 7. hodina Normální Rozdělení]]



# Centrální limitní větu
**ta říká, že když máme velký počet pozorování,**
**tak jejich součet se chová jako náhodná veličina s normálním rozdělením.**

Vlastnosti a aplikace normálního rozdělení tedy můžeme často použít i na
součty mnoha pozorování. 

Později uvidíme, že toto je velice důležitý znát při výběru testů a modelů a jejich předpokladů.

# Členění statistiky a testování hypotéz

Než se pustíme více do metod výzkumu připomene si dva druhy statistiky

## Popisná (deskriptivní)

- zpřehlednit získaná data
- charakterizovat pomocí kvantitativních charakteristik (míry středu, míry variability, míry tvaru) [[Vzdělávání/Statistika na první test\|Statistika na první test]]

## Induktivní (inferenční, testovací)

- z pozorovaných dat děláme závěry s udáním stupně jejich spolehlivosti 

>[!info]- Stupně spolehlivosti příklad
>Máme 100 pozorování výšky obyvatel České republiky. 
>Průměr jejich výšek je 177. Dejme tomu, že jsme spočítali, že 95% interval spolehlivosti pro střední hodnotu jejich výšky je <173, 181>. 
>To nám fiká, že střední („průměrná") hodnota náhodné veličiny Výška Čecha se s 95% pravděpodobností nachází v tomto intervalu (<173, 181>)

## Testování hypotéz

- většinou pracujeme s výběrovými daty
	- potřebujeme vědět, zda to, co jsme naměřili ve vzorku platí v celé populaci

### Formální postup
- Zvolíme si hladinu významnosti, obvykle α (p)=0,05
	- pravděpodobnost, že zamítnu nulovou hypotézu
- Nulová a alternativní hypotéza
- Volba testu
- Výpočet testového kritéria
- Vyhodnocení hypotéz

# Chyby usuzování

- hladina významnosti α = pravděpodobnost
chyby 1. druhu


![](https://i.imgur.com/M8MNA2G.png)


![](https://i.imgur.com/OKYUTKw.png)[^Statistics for people who think they hate statistics 7th edition]

Buňka 2, ukazuje chybu I. typu. Zde jsme zamítli nulovou hypotézu,
(že neexistuje žádný rozdíl), i když je ve skutečnosti pravdivá (a rozdíl existuje).

Další typ chyby II. typu je v buňce 3. Zde jsme přijali nulovou hypotézu (že neexistuje žádný rozdíl). I když je ve skutečnosti nepravdivá (a ve skutečnosti rozdíl mezi skupinami existuje).


# Statistické testy

Umožňují odvodit z výsledků ve výběrech
(optimálně náhodných), závěry týkající se
základního souboru.

[[Vzdělávání/Vzorečky na metody\|Vzorečky na metody]]

[[Vzdělávání/Jak vybrat správný test\|Jak vybrat správný test]]

## Časté možnosti využití, když je třeba porovnáváme :

- dva výběry mezi sebou
- průměr náhodného výběru a teoretickou
střední hodnotu
- počty pozorované a očekávané atd.



**Statistické testy** jsou založeny na výpočtech testové statistiky, která mají známé teoretické rozdělení (normální, t-rozdělení, F, x<sup>2</sup>, U …)


![](https://i.imgur.com/MuRMfB0.png)




Lze určit, jakou hodnotu má testová statistika, pokud platí H<sub>0</sub> (výsledek je v rámci platnosti nulové hypotézy).


Podle výsledku testu (a stupňům volnosti, d.f., s.v. – určují se z počtu nezávislých pozorování) se stanoví, jestli pozorované odchylky ve výsledcích jsou jen dílem náhody nebo se jedná o signifikantní (tj. statisticky významné) výsledky.

## Jako výsledek statistického testu lze uvést:

hodnotu testové statistiky, testovacího kritéria (např. t, F, $\chi$ <sup>2</sup>, U…..)

![](https://i.imgur.com/nFVuW3a.png)



![](https://i.imgur.com/Xj1ZJgp.png)



![](https://i.imgur.com/PsrCiHT.png)


###  Příklady použití testů

testuji, zda můj výběr má střední hodnotu shodnou s danou hodnotou populace – **jednovýběrový t-test**
(H : μ = průměr hodnot x výběru)

dlouhodobá průměrná denní teplota v červnu je μ= 17.5 °C.  Byla letos stejná nebo se lišila signifikantně?

**testuji, zda dva náhodné výběry (nezávislé) pochází ze stejného základního souboru (mají stejnou střední hodnotu) – dvouvýběrový t-test** (H : μ = μ ) 


***Výkony žen a mužů v testu***

testuji, zda rozdíl párových hodnot (závislých) je roven dané hodnotě (většinou 0) - **párový t-test** (H : μ - μ =0)

**výkon v testu ráno a večer u stejné skupiny osob.**


# Parametrické vs Neparamatrické testy


## Parametrické testy

Výpočet je založen na využití parametrů (průměr,
rozptyl, směrodatná odchylka).

**Všechny zmíněné testy v tomto souboru jsou parametrické**


### Předpoklady použití:

- normalita dat
	- pokud mám dostatek dat, obvykle se rozdělení
	- blíží normálnímu [[Vzdělávání/Materiály na metody kvantitativního a kvalitativního výzkumu#Centrální limitní větu\|Centrální limitní věta]]
	- pokud mám dat málo (n=30, příp. méně), většinou nemůžu prokázat, že data pochází z normálního rozdělení
	- potřeba ověření je však v obou případech,

metrická stupnice (intervalová, poměrová)
- nepoužívají se u nominální a pořadové stupnice.


## Neparametrické testy

• Výpočet je založen zejména na mediánech a
pořadí. Nevyužívají se parametry.

- nejsou tak silné, jako parametrické

[[Vzdělávání/Neparametrické testy\|Neparametrické testy]]

### Použití neparametrických testů:
• Rozdělení dat odlišné od normálního.
• Malé výběry (cca do 30).
• Nemetrický charakter proměnných (pořadové,
nominální) nebo i metrické (kardinální)
proměnné s asymetrickým rozložením (tj. odlišné od normálního).


## Příklady alternativ

 - chci zjistit, jestli se liší znalosti (= počet bodů v testu) žáků 2 gymnázií
**dvouvýběrový t-test (parametrický)**
**U-test (neparametrický)**

- chci zjistit, jestli se liší znalosti (= počet bodů v testu) stejných žáků před a po prázdninách
 **párový t-test (parametrický)**
**Wilcoxonův test (neparametrický)**

![](https://i.imgur.com/YEVQlsA.png)

## Příklad

chci prokázat: žáci z gymnázia A mají lepší znalosti než z gymnázia B

formuluji hypotézu: H0 : Zjištěné znalosti ve výběrech žáků obou 0
gymnázií pochází z jednoho základního souboru (úroveň znalostí se neliší)

alternativní hypotéza: Ha : Výběry zjištěných znalostí žáků z A
gymnázií A a B nepochází z jednoho základního souboru (=
úroveň znalostí se liší)

provedu testování, do jaké míry je pravděpodobné, že oba výběry pochází ze stejného základního souboru

pokud je pravděpodobnost příslušná zjištění malá (p < 0.05), zamítnu H0 a akceptuji Ha

pokud je p > 0.05, nemůžu zamítnout H0

Zamítnutí nulové hypotézy zároveň značí, že mezi skupinami je ve znalostech statisticky významný rozdíl (signifikantní).



### Dvou výběrový t-test - postup
T-testy používáme, když neznáme populační směrodatnou odchylku a z-test když ano.


rovnají se rozptyly?

shodnost rozptylů testuji F-testem
(H : s2 = s2 )


Počítáme jako poměr většino rozptylu k menšímu rozptylu

$$F={\frac{s_{1}^{2}}{s_{2}^{2}}}$$

Kritické hodnoty se určují z F-rozdělení pro zvolenou hladinu významnosti (např. 0.05 pro 95% interval spolehlivosti) a pro odpovídající stupně volnosti, které jsou df1=n1−1  a df2=n2−1

Hodnotu hledáme ručně v tabulkách, pokud počítáme ručně.


pokud p větší než 0.05 – nemůžu zamítnout H0 → rozptyly se rovnají (to je většinou)

pokud p menší než 0.05 – můžu zamítnout H0→ rozptyly se nerovnají

## Dvouvýběrový t-test (Studentův test = t-test)

Testovací kritérium t - pro s 2 ~ s 2:

$$t={\frac{\left|{\overline{{x}}}_{1}-{\overline{{x}}}_{2}\right|}{\sqrt{n_{1}\,s_{1}^{2}+n_{2}\,s_{2}^{2}}}}\cdot{\sqrt{\frac{n_{1}\,n_{2}\left(n_{1}+n_{2}-2\right)}{n_{1}\,+n_{2}}}}$$


Testovací kritérium t - pro s 2 > s 2:

$$t{=}{\frac{\left|x_{1}-x_{2}\right|}{\sqrt{{\frac{s_{1}^{2}}{n_{1}-1}}+{\frac{s_{2}^{2}}{n_{2}-1}}}}}$$


(Počet stupňů volnosti: df = n - 1, df = n – 1).



## Grafické vyjádření

pro znázornění t-testu je vhodný krabicový graf
Krabicový graf 

![](https://i.imgur.com/TYaAPiO.png)




## T-test pro párované hodnoty (parametrický)

Testovací kritérium: $t=\frac{|\bar{d}\,|.\,\sqrt{n-1}}{S_{d}}$

kde |¯d| je absolutní hodnota průměrné diference párovaných hodnot a s je směrodatná odchylka této diference. Počítá se jako běžně směrodatná odchylka, tj.:

$$s_{d}=\sqrt{\frac{\sum\,d^{2}-\frac{(\sum\,d\,)^{2}}{n}}{n-1}}$$

>[!info] Proč n-1?
>Jelikož děláme příklad z dat, která nejsou sterjná jako data z celkové populace, poze odhadujeme. Pro případy kdy by byli reálné výsledky populace slabší, je lepší nadhodnocovat výsledky testových statistik



![](https://i.imgur.com/aKmHJNA.png)

Poté je třeba porovnat hodnotu testové statistiky t s hodnotou t-rozdělení, která náleží p=0,05 a df=9. Pokud je t vyšší, pak je signifikantní výsledek.
(Toto se uplatňuje při ručním počítání.) A používají se na to tabulky.



## T-test pro nezávislé výběry
(výstup z PSPP)
![](https://i.imgur.com/HrT5q6U.png)

Pro vyhodnocení se koukáme na sloupečky F (čím vyšší, tím lepší),  t (t-statistika), df (stupně volnosti), Sig. (2-tailed) p hodnota.

Takže by nás mohlo zajímat celková Signifikance, 5. řáded. Jenom první dvě jsou pod hodnotou 0,05.




## T-test pro závislé výběry
(výstup z PSPP)
![](https://i.imgur.com/KvbraPF.png)

Koukáme na poslední řádek, ten se rovná 0,47, což je větší než 0,05.


## Testy shody

**Parametrický test – Chí kvadrát test (χ2)**

·       **Podmínky:** žádná kategorie s nulovou četností; maximálně 20 % s četností menší než 5

Testovací kritérium 

$$\chi\,2{=}\sum_{i=1}^{n}{\frac{(A_{i}{-}E_{i})^{2}}{E_{i}}}$$

- Ai = pozorovaná četnost (někdy označováno jako Oa Ei = očekávaná četnost)


- Pokud je hodnota testovacího kritéria vyšší, než příslušná kritická hodnota rozdělení chí-kvadrát, hypotézu o shodě dvou rozdělení **zamítáme** (na příslušné hladině významnosti)


## ANOVA
[[Vzdělávání/ANOVA, Více faktorová ANOVA\|ANOVA, Více faktorová ANOVA]]

NÁZEV: Analýza rozptylu

CÍL: hledat rozdíly v průměrech několika skupin(nechceme porovnávat kontrolní a testovací skupinu, ale třeba kontrolní, druhá bude v posteli, třetí na zemi, čtvrtá na vodní posteli, pátá …)

Anglicky ANOVA – ANalysis Of VAriance

## Linerání regresní analýza
[[Vzdělávání/Lineární regresní analýza\|Lineární regresní analýza]]

Výsledkem je model vztahu mezi dvěma a více proměnnými
přesněji než korelace popisuje poodbu zvathu mezi proměnnámi