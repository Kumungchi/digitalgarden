---
{"dg-publish":true,"permalink":"/Vzdělávání/Statistika 3. hodina  Univariační analýza  numerické charakteristiky/"}
---


[[Vzdělávání/Vzorečky na statistiku\|Vzorečky na statistiku]]


## Numerické charakteristiky jednorozměrného rozdělení
### Míry polohy (středu, střední hodnoty, míry centrální tendence - aritm., medián, modus)
- měří polohu statistického souboru na ose x a mají stejný rozměr jako samotná pozorování
	- aritmetický průměr - težistě hodnot
	

$$\bar{x} = \frac{\sum_{i=1}^{n} x_i}{n}
$$
	 medián - prostřední hodnota uspořádaného souboru
		(Me, MD, Q<sub>2</sub>, median) střední hodnota souboru, který je seřazen od nejmenší po největší hodnotu. Pokud sudý počet hodnot je medián aritmetický průměr hodnot na místech n/2 a n/2+1

$$ \text{Median} = x{\frac{n+1}{2}}$$
- Stanovují se kvartily (dělí soubor na 4 části), decily a percentily (na 100 částí)
- Obecné označení je kvantily
- Medián je druhý kvartil, padesáty percentil
- modus - nejčastější hodnota (důležitý pro kvalitativní znaky)
	- (Mo, mode) představuje nejčastěji se vyskytující hodnotu proměnné v souboru dat
	- Může mít více hodnot četnější a stejný výsledek - lze pak stanovit dva a více modusů

Nominální znaky → modus
Ordinální → medián
Kardinální → aritmetický průměr
### Míry variability (variační rozpětí, mezikvartilové rozpětí, rozptyl, standardní odchylka, variační koeficient)
- proměnlivost hodnot znaku (proměnné) v statistickém souboru
- Charakteristiky (míry)
	- variační rozpětí - rozdíl mezi nejvyšší a nejnižší hodnotou v datech (závisí na extrémních hodnotách)
	- mezikvartilové rozpětí - rozdíl 3. a 1. kvartilu
	- Rozptyl - průměrná kvadratická odchylka od průměru
	- směrodatná odchylka - odmocnina z rozptylu


- variační rozpětí (rozpětí, R, range) jednoduchá míra variability. Poloze pro rychlou orientaci
- Vypočítá se jako rozdíl mezi největší a nejmenší hodnotou v souboru
	- R = x(max) - x(min)


- Mezikvartilové rozpětí (interkvartilové rozpětí, Q, RQ, interquartile roange) - úředstavuje rozdíl mezi horním (třetím) a dolním (prvním) kvartilem. Reprezentuje oblast středních 50 procentech hodnot proměnné. Pesnější míra oproti variačnímu rozpětí

RQ = Q<sub>3</sub> - Q<sub>1</sub>


- Rozptyl (střední kvadratická odchylka, disperze, s<sup>2</sup>, variace) často využívanou mírou variability
- Rovná se průměrnému čtverci odchylek hodnot od průměru
- Čím je rozptyl větší, tím více se údaje odchylují od průměru
- Vzorec
$$\text{Var} = \frac{1}{n} \sum_{i=1}^{n} (x_i - \bar{x})^2
$$
- Směrodatná odchylka (standardí odchylka, s, SD, standard deviation)
- je odmocněný rozptyl. Tím se odstraňuje vliv umocňování při výpočtu hodnoty rozptylu
- Průměrný rozdíl mezi hodnotami a jejich průměrem při ignorování znamének
- $$\text{S} = \sqrt{\frac{1}{n-1} \sum_{i=1}^{n} (x_i - \bar{x})^2}
$$
- Variační koeficient (VK, CV)
- představuje relativní míru variability
- jestliže chceme posoudit relativní velikost rozptýlenosti dat vzhledem k průměru
- Počítáme ho, když chceme porovnat rozptýlnost dat měření stejné proměnné s různými průměry
- Jako podíl standardní odchylky a průměru
	- VK = SD/AM
	- nebo v procentech VK=SD/AM x 100

$$CV = \left(\frac{\text{SD}}{\bar{x}}\right) \times 100\%
$$
# Příklad
Součet všech odchylek od průměru musí být nula 

> [!example] Máme pozorování 7 2 5 4 3 1 8 2 6 2 Součet řady, n a průměr?
> 1. **Součet řady (suma):**
>  7+2+5+4+3+1+8+2+6+2=407+2+5+4+3+1+8+2+6+2=40
> 2. **Celkový počet prvků: 10**
> 3. **Průměr**
> $$průměr = \frac{40}{10} = 4  $$


- Krabicový graf 
Horizontální čára
představuje medián, horní
hrana krabice 75. percentil
a dolní hrana 25. percentil.

Délka obdélníku
představuje středních 50%
hodnot souboru.
Dolní anténa — minimální
hodnota, horní anténa —
maximální hodnota.
![](https://i.imgur.com/a8DCqAP.png)




### Míry tvaru (koeficient šikmosti, koeficient špičatosti)
- Šikmost (nesouměrnost, skewness) - ukazuje směr a míru asymetrie rozdělení proměnné

- Koeficient šikmosti - míra šikmosti, bezrozměrné číslo, vyhodnocuje se:
- S<sub>1</sub> = 0 symetrické rozdělení
- > 0 pozitivní (pravostranná) asymetrie
- < 0 negativní (levostranná) asymetrie

- Kladná (pravostranná šikmost) hodnota znamená, že většina je menší jako průměr, záporná hodnota (levostranná šikmost) znamená, že většina hodnot je větší jako průměr


- Špičatost (strmost, kurtosis) - měří hustotu chvostů rozdělení proměnné, t. j. charakterizuje výskyt extrémně vysokých a extrémně nízkých hodnot

- Koeficient špičatosti - míra strmosti
- bezrozměrné číslo
- S<sub>2</sub> = 0 normální rozdělení (mezokurtické)
- < 0 plochší rozdělení (platykurtické)
- > 0 špičatější rozdělení (leptokurtické)




