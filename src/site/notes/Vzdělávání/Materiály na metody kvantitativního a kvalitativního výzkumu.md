---
{"dg-publish":true,"permalink":"/Vzdělávání/Materiály na metody kvantitativního a kvalitativního výzkumu/"}
---


Ve více vzorcích se zobrazuje tento symbol:

∑: Suma (součet). Tento symbol značí, že máme sečíst hodnoty pro všechny hodnoty (od 𝑖=1i=1 do 𝑖=𝑛i=n).

Pro lepší pochopení následující látky je dobré si připomenout co to je Normální rozdělení a Centrální limitní věta.

>[!info]- Normální rozdělení
>>
<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/vzdelavani/statistika-7-hodina-normalni-rozdeleni/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">





ještě byl Baumík

test hlavně teorie
směrodatné odchylky
míry variability
výpočet nebo odvození z výpočtu

aritmetický průměr (poloha) spojená s, doplňuje aritm. SD(variabilita)
medián (poloha) doplňuje ho mezikvartilová odchylka (variabilita)

[[Vzdělávání/Teoretické rozdělení\|Teoretické rozdělení]]

# Normální rozdělení

pravidlo 68-95-99,7%, standardizované skóry (z-skóry), pravděpodobnosti a percentily

- mnoho proměnných je (přibližně) takto rozloženo
	- usuzovat, kolik/jaký podíl určitých hodnot v populaci
- mnoho statistických postupů s normálním rozdělením pracuje, předpokládá ho
- sekundárně - mnoho lidí je s ním aspoň základě seznámeno, takže když transformujeme proměnnou tak, aby normální rozložení měla, usnadníme tím interpretaci skórů


- unimodální (jeden vrchol) a symetrické
- průměr = mediánu = modusu
- okolo avr. častější než hodnoty vzdálenější od průměru
- Šikmost (skweness) je 0
- Špičatost (kurtosis) je 3. Téměř vždy se ale špičatost uvádí jako K - 3 (excess kurtosis),  normální rozdělení má šikmost i špičatost = 0


- jeden tvar, ale různá poloha (M) a různá míra roztažení (SD - sigma $\sigma$)

- Pravidlo 68-95-99,7 68,2 (34,1 půlka + půlka) - 95,4 (13,6) - 99,7 (2,15)
	- platí pro všechna normální rozdělení bez ohledu na jejich průměr (značí se různě M, M, $\mu$) a směrodatnou odchylku (SD, s, $\sigma$)
- Protože je rozložení symetrické a 50 pr. hodnot je nižších než průměr. lze z pravidla výše určit ostatní prv.

>[!info]- Graf N. rozdělení
>
>![](https://i.imgur.com/HXAYttu.png)


>[!warning]- Příklad
Kolik hodnot se nachází mimo +1 SD od průměru? 100 pr. - 95 pr.= 5
100 - 68 = 32 je odlehlejších, ale protože nám jde o jeden konec distr,, výsledek je 32/2 = 16
Kolik hodnot více než -1SD? Mezi pr. a 1SD se nachází 68/2 = 34 hodnot. Nad průměrem se nachází 50% hodnot. Výsledek je 34+50 = 84%



>[!warning]+ Příklad. 
>soubor pacientů se srdeční frekvencí. Známe pr. 110, min. 65, max 155. Jaká bude pravděpodobně standardní odchylka distribuce?


>[!warning]- Řešení  
==b)1<mark style="background: #FF5582A6;"></mark>5==  
c) 35  
d) 90
>- Předpokládejme, že všechny hodnoty se nacházejí maximálně 3 SD od průměru
>Takže do pozorovaného rozpětí 65 - 155 (90) by se mělo vlézt šest směrodatných odchylek
  90/6 = 15
>45 / 3 rozdíl průměrné od maxima nebo  minima


[[Vzdělávání/Z skor a Z test\|Z skor a Z test]]

>[!warning]+ Příklad
>dosáhl v SAT (Scholastic Aptitude Test) skóru 1800. Jan v ACT (American College Testing) skore 24. Kdo z nik podal lepší výkon
SAT skory vlnovka N(M=1500, SD=300)
ACT vlnovka n(M=21, SD=5)

Zápis proměnná to nahoře, znamená, že daná proměnná má normální rozdělení se stanoveným průměrem a směrodatnou odchylkou 


Zśkory
ZPavael = 1800-1500/300 = 1
Zjan= 24-21/5 = 0,6


- standardizovaný zskor mají z definice vždy průměr 0
- říká o kolik směrodatných odchylek se daná hodnota liší od průměru
- odlehlé hodnoty se často vymezeují jako hodnoty mající absol Z > 2, někdy jako absol. Z > 3 (tj. mimo dvě nebo tři SD od průměru)
- Z-skóry ale lze vypočítat pro kterékoli rozdělení (pro jiná než normální ale samozřejmě nepůatí pravidlo gausova rozdělení)
- obecná rovnice pro vápočet kde Xi jsou původní skóry, M průměr a SD daných výsledcích


$\ z_i = \frac{x_i - M}{\sigma} $
Průměr 0, SD 1
Existují i jiné standardizované skóry (T-skóry s M 50 a SD 10, IQ M 100 a SD 15)


***Percentilové pořadí***
Pokud je rozdělení (přibližně) normální, lze Z-skóry použít pro výpočet percentilu/percentilového pořadí (rank)
To reprezentuje procentuální podíl pozorování menších nebo rovných než stanovená hodnota
Graficky je percentilové pořadí podíl oblasti pod křivkou nalevo od stanovené hodnoty


Značení kvantilů stand. normálního rozdělení
M 0 a SD 1
Mdn, Q1, P10, Q0,3
často i extra označení
z0,5 = 0
z0,16 = -1 (16% kvantil SNR -1)
z0,84 = 1 (84 kvantil SNR hod 1)
z0,975 = 1,96 (97,5 kvantil SNR má hodnotu 1,95)

v excelu fce norm.s.iniv

Př.
v testu Tomas SAT, umístil se mezi 10% nej. Jaký nejmenší skór mohl získat

zskor 1,28 je devadesátý percentil

$\ z_i = \frac{x_i - M}{\sigma} $


Lzde zskor převést na skór původní 
xi = (Zi x SD) + M
$ X_{Tomáš}=(1,28*300)+1500= 1884$


Čeho si všimneme normálnost přibližnou pozorovaného rozdělení

Tvar
- symetrická zvonovitost - histogram Q-Q plot (asymetrie se ukáže i na krabicovém)
- zešik - přibl 0 (ne více než +-1)
- špičatost - přibližně 0 (ne víc než +-1)

- Spojitost
	- musí být smysluplné předpokládat, že i když máme v datech diskrétí hodnoty, měřená veličina je spojitá
	- i pokud je ale víme, že rozdělení je diskrétní, můžeme v některých případech použít normální aproximaci (pracovat s ním, jako by normální bylo)

- Q- Q grafy
- zanesení kvantilů pozorovaného proti kvantilům normálního rozdělení



Pokud Q-Q graf ukazuje lineární vztah (body leží na jedné přímce)
Percentily hodnoty, které dělí data na 100 stejně velkých dílů(1 % hodnot je menších než 1. percentil mezi )


## Normalizace
Transformace skórů tak, aby měly normální rozdělení
Transformujeme hrubé skóry (původní hodnoty) na
percentilové pořadí.
Percentilové pořadí transformujeme na z-skóry, jako by
rozdělení bylo normální.
Nepovinný krok: Transformujeme z-skóry na jiné známé
standardní skóry:

staniny, staninové skóry (standard nine) (M = 5, SD = 2) + kategorizace zaokrouhlením na celá čísla od 1 do 9
steny, stenové skóry (standard ten) (M = 5,5, SD = 2)
+ kategorizace zaokrouhlením na celá čísla od 1 do 10.
T-skóry (M = 50, SD = 10).
IQ-skóry (M = 100, SD = 15)


Tabulka Z skorů https://www.ztable.net/

>[!info]+ Příklad
>Dejme tomu, že váha zavazadel cestujících, kteří využívají
leteckou dopravu, má přibližně normální rozdělení
s průměrem 20 kg a SD = 1,5 kg a že při překročení váhy
22,5 kg se musí platit příplatek.
Kolik procent cestujících přibližně tento příplatek musí
zaplatit?
> váha zavazadel = N (M=20, SD = 1,5)
> >[!tip]- Normální rozdělení graf
![](https://i.imgur.com/OLEhd7t.png)
>>>[!warning]- Řešení
>převedení na z skor $\frac{22,5-20} {1,5} = 1,667$
> To je v tabulce ,95154
> Takže asi 0,048 $\approx$ 5 % bude platit příplatek




>[!info]+ Příklad 2
>Víme, že v Los Angeles je průměrná denní teplota v
červnu 25 oc a SD = 2,8 oc. Předpokládejme, že rozdělení
těchto teplot je přibližně normální.
Jaké jsou přibližně teploty v nejchladnějších 20 % dní?
>>[!tip]- Normální rozdělení graf
>>![](https://i.imgur.com/w4noWZl.png)
>>>[!warning]- Řešení
>>>dolní mez hodnoty 3SD od pr. = 16.6
>>>z = -0,84, tedy horní mez bude 0,84 násobek SD pod pr.
>>>$25-0,84*2,8=22,6$
>> >v 20 % nejchladnějších dnů by měla být teplota v pásmu 16, 6 až 22,6 	








</div></div>




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

Parametrický test – Chí kvadrát test (χ2)

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