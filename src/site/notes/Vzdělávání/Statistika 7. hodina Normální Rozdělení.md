---
{"dg-publish":true,"permalink":"/Vzdělávání/Statistika 7. hodina Normální Rozdělení/"}
---


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
![](https://i.imgur.com/HXAYttu.png)


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


$$\ z_i = \frac{x_i - M}{\sigma} $$
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

$$\ z_i = \frac{x_i - M}{\sigma} $$


Lzde zskor převést na skór původní 
xi = (Zi x SD) + M
$$ X_{Tomáš}=(1,28*300)+1500= 1884$$


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
>převedení na z skor $$\frac{22,5-20} {1,5} = 1,667$$
> To je v tabulce ,95154
> Takže asi 0,048 $\approx$ 5 % bude platit příplatek




>[!info]+ Příklad 2
>Víme, že v Los Angeles je průměrná denní teplota v
červnu 25 oc a SD = 2,8 oc. Předpokládejme, že rozdělení
těchto teplot je přibližně normální.
Jaké jsou přibližně teploty v 20 % dní?
>>[!tip]- Normální rozdělení graf
>>![](https://i.imgur.com/w4noWZl.png)
>>>[!warning]- Řešení
>>>dolní mez hodnoty 3SD od pr. = 16.6
>>>z = -0,84, tedy horní mez bude 0,84 násobek SD pod pr.
>>>$$25-0,84*2,8=22,8$$
>> >v 20 % nejchladnějších dnů by měla být teplota v pásmu 16, 6 až 22,6 	






