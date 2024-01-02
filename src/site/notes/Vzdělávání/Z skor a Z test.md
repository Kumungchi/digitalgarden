---
{"dg-publish":true,"permalink":"/Vzdělávání/Z skor a Z test/"}
---


z-skóre (nazývané také jako standardní skóre)  dává představu o tom, jak daleko od střední hodnoty je datový bod. Je to míra toho, kolik standardních odchylek pod nebo nad populací znamená hrubé skóre.

Je-li z je negativní je x je pod průměrem, je-li z pozitivní je x výše průměrem.

![](https://i.imgur.com/V72rTDA.png)

# Vzorec
$$Z=\frac{x- \mu }{\sigma}$$
μ je střední hodnota (průměr) souboru
σ je směrodatná odchylka souboru dat

https://www.ztable.net/

#  Z test
statistický test, který se používá k testování hypotéz o průměrech nebo podílech dvou nezávislých vzorků. Tento test porovnává z-skóre (standardizované hodnoty) s předpokládaným průměrem a směrodatnou odchylkou, aby se rozhodlo, zda jsou dvě sady dat statisticky významně odlišné.

Pro použití z-testu je důležité nejprve provést výpočet z-skóre pro data a pak aplikovat specifický z-test v závislosti na konkrétní situaci nebo testované hypotéze.

Můžeme použít pokud:
Nezávislá data
Jsou normálně distr. a známe populační rozptyl
Vzorek je dost veliký, a data kopírují distribuci s konkrétním průměrem a rozptylem

https://www.wolframalpha.com/input/?i=z-test+calculator&f1=.5&f=ZTest.mu0_.5&f2=32&f=ZTest.n_32&f3=1&f=ZTest.sigma_1&f4=.5&f=ZTest.xbar_.5&x=0&y=0
## Vzorec z testu
Jedno vzorkový

$$Z = \frac{\overline{x} - \mu_{0}}{\frac{\sigma}{\sqrt{n}}}$$
Dvou vzorkový 
$$Z = \frac{(\overline{x}_1 - \overline{x}_2) }{\sqrt{\frac{\sigma_1^2}{n_1} + \frac{\sigma_2^2}{n_2}}}$$

## Z test kritické hodnoty
u tohoto testu standardní normální distribuce nemění tvar s růstem velikosti vzorku



| Úroveň významnosti | Typ testu | Kritické hodnoty |
| ---- | ---- | ---- |
| 0,01 | Two-Tailed | ±2.576 |
| 0,01 | Left Tail | –2.326 |
| 0,01 | Right Tail | +2.326 |
| 0,05 | Two Tailed | ±1.960 |
| 0,05 | Left Tail | +1.650 |
| 0,05 | Right Tail | –1.650 |

## Ukázka 

Předpokládejme, že jsme náhodně vybrali předměty z programu vyznamenání. Chceme zjistit, zda se jejich průměrné IQ skóre liší od běžné populace. Skóre IQ běžné populace je definováno jako průměr 100 a standardní odchylka 15.

Zjistíme, zda je rozdíl mezi průměrem našeho vzorku a předpokládaným průměrem populace 100 statisticky významný.

Konkrétně použijeme dvoustrannou analýzu s hladinou významnosti 0,05. Při pohledu na tabulku výše uvidíte, že tento Z test má kritické hodnoty ± 1,960. Naše výsledky jsou statisticky významné, pokud je naše statistika Z pod –1,960 nebo nad +1,960.

Hypotézy jsou následující:

- Null (Ho ) : u = 100
- Alternativa (HA ) : µ ≠ 100

### Zadání našich výsledků do vzorce

Zde jsou hodnoty z naší studie, které musíme zadat do vzorce Z testu:

- Průměr vzorku skóre IQ (x): 107
- Velikost vzorku (n): 25
- Předpokládaný průměr populace (µ 0 ): 100
- Směrodatná odchylka populace (σ): 15


![](https://i.imgur.com/nAW4oLU.png)


Z-skóre je 2,333. Tato hodnota je větší než kritická hodnota 1,960, takže výsledky jsou statisticky významné.


![](https://i.imgur.com/BDreLsx.png)


Můžeme odmítnout nulu a dojít k závěru, že průměrné skóre IQ pro populaci studentů s vyznamenáním se nerovná 100. Na základě průměru vzorku 107 víme, že jejich průměrné skóre IQ je vyšší.

Nyní najdeme p-hodnotu. 

Abychom našli p-hodnotu, která odpovídá Z-skóre z dvoustranné analýzy, musíme najít zápornou hodnotu našeho Z-skóre (i když je kladné) a zdvojnásobit ji.

V níže uvedené zkrácené Z-tabulce zvýrazním buňku odpovídající Z-skóre -2,33.

![Použití Z-tabulky k nalezení p-hodnoty.](https://i0.wp.com/statisticsbyjim.com/wp-content/uploads/2022/11/Z_test_table_example.png?resize=460%2C143&ssl=1)

Hodnota buňky 0,00990 představuje oblast nebo pravděpodobnost nalevo od Z-skóre -2,33. Potřebujeme ji zdvojnásobit, abychom zahrnuli plochu > +2,33, abychom získali p-hodnotu pro dvoustrannou analýzu.

P-hodnota = 0,00990 * 2 = 0,0198

Tato p-hodnota je přibližná, protože používá Z-skóre 2,33 spíše než 2,333. Pomocí online kalkulačky je p-hodnota pro náš Z test přesnější 0,0196. Tato p-hodnota je menší než naše hladina významnosti 0,05, což znovu potvrzuje statisticky významné výsledky.


![](https://i.imgur.com/bAjF9aS.png)




## Graf Z Skore
![](https://i.imgur.com/So7Nk2w.png)
