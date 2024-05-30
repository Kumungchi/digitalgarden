---
{"dg-publish":true,"permalink":"/Vzdělávání/Neparametrické testy/"}
---


- obvykle se požaduje aby rozdělení bylo spojitého typu
- někdy se nazývají íi pořadovými testy → přotože se netýkajparametrů rozdělení náhodných veličin, ale pořadí
- hodnoty jsou tedy seřazeny podle velikosti a očíslované
- Používáme
-  když neznáme typ rodení nádodné veličiny a nemůžeme pužít paramterický test
- sledovaná veličina není číselná, ale její úrovně umíme seřadit podle velikosti a přidat pořadové čísle (tvrdost, barva, hustotat, chuť, estetická vlastnost)
- Hodnoty této veličiny jsou subjektivní, ale jejicch pořadí je objektivní (hodnocení bodu sochovatelksých soutěží, šklní klasifikace, degustační soutěž)


## Přednosti neparamterických testů 
- Nezávislost na tvaru rozdělení

 - Použitelné pro kvalitativní i kvantitativní znaky

 - Po výpočtové stránce jsou jednodušší a rychlejší než parametrické testy

 - Mají všeobecnější použití

## Nevýhody
- menší síla, menší schopnost odmítnout nesprávnou nulovou hypotézu ve srovnání s parametrickými testy

 - pokud jsou splněny předpoklady pro použití parametrických testů a chceme použít alternativu v podobě neparametrického testu, potřebujeme větší rozsah náhodného výběru (abychom dosáhli stejné síly testu)



## Pořadí
Pořadí R udává počet čísel x1 , x2 ,..., xn , která jsou menší nebo rovna číslu xi
Jso li všechna čísla různá a seržazená podle velikosti, odpovídá pořadí indexu Ri=i
pokud je několik čísel x1, x2, ….xn stených přiřadíme průměrné pořadí


| Vzestupně uspořždané hodnoty | -2  | -2  | 1   | 8   | 8   | 8   | 22  |
| ---------------------------- | --- | --- | --- | --- | --- | --- | --- |
| Index                        | 1   | 2   | 3   | 4   | 5   | 6   | 7   |
| Porřadí Ri                   | 1,5 | 1,5 | 3   | 5   | 5   | 5   | 7   |

# Neparametrické testy -  Wilcoxonův test
**= neparametrická obdoba párového t-testu pro **závislé soubory***

Pro každou dvojici údajů vypočítáme rozdíly di=xi-yi

Nenulovým rozdílům přiřadíme pořadová čísla od 1 po _n_, přičemž stejným rozdílům přiřadíme stejné pořadí

Pořadová čísla rozdělíme do dvou skupin (kladné a záporné)

Pořadí kladných rozdílů sčítáme, součet označíme **W+,** podobně pořadí záporných rozdílů označíme **W-**

Testovací kritérium je menší hodnota: **W=min (W+, W-)**

Testovací kritérium porovnáme s kritickou hodnotou Wilcoxonového testu **Wα, (_n)_**

**Vyhodnocení:** pokud platí **W≤Wα,** **_(n)_****, zamítáme** nulovou hypotézu o shodě dvou středních hodnot (naopak než při parametrickém testě)

## _Příklad_

·       _Předpokládejme, že máme k dispozici údaje o dvou závislých souborech xi, yi (údaje jsou uvedené v tabulce)_

![](https://i.imgur.com/DsMuvvq.png)

_Pořadové čísla rozdělíme do dvou skupin, jedna pro kladné a druhá pro záporné rozdíly. Pořadí kladných rozdílů spočítáme a součet označíme W+, pořadí záporných rozdílů podobně spočítáme a součet označíme W-. Testovací kritérium tvoří menší hodnota z obou součtů W+ a W-.  
W=7,5  
W__α_ _(12) =13_

_Jelikož hodnota_ _testovacího kritéria (7,5) je menší než kritická hodnota (13), zamítáme nulovou hypotézu o shodě dvou středních hodnot závislých souborů ve prospěch alternativní hypotézy, která tvrdí opak_


## Neparametrické testy - Mann-Whitney test
**= neparametrická obdoba dvojvýběrového t-testu pro nezávislé soubory**

Uspořádáme oba soubory podle velikosti a přiřadíme jim pořadová čísla, tzn. očíslujeme hodnoty od nejmenší po největší. Stejným hodnotám přidělíme stejné průměrné pořadí.

Rx1, Rx2…Rxm	Ry1, Ry2…Ryn

uděláme součet pořadí pro x i pro y (označíme T)

Tx=Rx1+…+Rxm	Ty=Ry1+…+Ryn

vypočítáme

$U_x = m*n + \frac{m(m+1)}{2} - T_x$ 	a $U_y = mn + \frac{n(n+1)}{2} - T_y$ 

testovací kritérium

$U=min⁡(U_x,U_y)$	

**Vyhodnocení: pokud je vypočítané testovací kritérium menší, resp. rovné kritické hodnotě Uα, H0 zamítáme **

## Příklad
Předpokládejme, že máme k dispozici údaje o dvou nezávislých souborech xi , yi (údaje jsou uvedené v tabulce):


![](https://i.imgur.com/LcluHPF.png)

_Uspořádáme oba soubory podle velikosti a přiřadíme jim pořadová čísla (tzn. očíslujeme hodnoty od nejmenší po největší přirozenými čísly


![](https://i.imgur.com/XVN201L.png)


·       _Testovací kritérium je menší než kritická hodnota, tj. nulovou hypotézu **zamítáme** ve prospěch alternativní hypotézy na hladině významnosti α = 0,05_

## Neparamterické testy - Kruskal-Wallisův test
·       = neparametrická obdoba **jednofaktorové analýzy rozptylu**

·       Všechny hodnoty z „m“ výběrů (všech úrovní faktoru) seřadíme do jedné rostoucí posloupnosti (n1, n2…, n)

·       Určíme pořadí každého prvku (stejným hodnotám přiřadíme stejné průměrné pořadí)

·       Spočítáme pořadová čísla pro každý výběrový soubor (T1, T2…,Tm)

·       Testovací kritérium má tvar

$$H={\textstyle\frac{12}{n(n+1)}}\sum_{i=1}^{m}{\frac{T_{i}^{2}}{n_{i}}}-3({\mathrm{n}}+1),$$

$n=\sum_{i=1}^{m} n_{i}$

·       Statistika H má $\chi$ <sup>2</sup> rozdělení s m-1 stupni volnosti a hladinou významnosti _α._

·       **Vyhodnocení:** pokud je H≤_$\chi$ <sup>2</sup>(m-1), **H0 nezamítáme**_

## Příklad

·       _Zjistěte, zda existuje statisticky významný rozdíl v hmotnostních přírůstech za čas t u kachen chovaných třemi různými způsoby A, B, C:  
__

![](https://i.imgur.com/KLToacW.png)

·       _Všechny hodnoty způsobu chovu seřadíme do jedné rostoucí posloupnosti a určíme pořadí každého prvku (stejným hodnotám přiřadíme stejné průměrné pořadí)._ _Spočítáme pořadová čísla jednotlivých pozorování pro každý výběrový soubor:  


![](https://i.imgur.com/UGOk4B8.png)




$$H=\frac{12}{n.(n+1)},\sum_{i=1}^{n}\frac{T_{i}^{2}}{n_{i}}-3.(n+1)=\frac{12}{12.15},\left(\frac{20^{2}}{4}+\frac{17^{2}}{4}+\frac{41^{2}}{4}\right)=6,577$$


$$\chi^2_{0.05}(2) = 5.991$$





·       _Vypočítaná hodnota testovacího kritéria je větší než kritická hodnota tzn., že **zamítáme H0,** a můžeme tvrdit, že způsob chovu ovlivňuje hmotnostní přírůsty kachen._

## Dixonův test

·       = test **extrémních** hodnot

·       Pomocí testu ověřujeme, zda minimální anebo maximální hodnota v souboru údajů není zatížená hrubou chybou (výrazné zkreslení výsledků)

·       Hodnoty uspořádáme podle velikosti vzestupně  
_x1, x2, x3…, xn-1, xn_

·       extrémní hodnoty se nacházejí na začátku a na konci

testovací kritérium má tvar, pro nejmenší hodnotu


$$Q_{1}={\frac{x_{2}-x_{1}}{x_{n}-x_{1}}}$$
ori největší hodnotu

$$Q_{n}={\frac{x_{n}-x_{n-1}}{x_{n}-x_{1}}}$$
·       porovnáme s kritickou hodnotou Dixonova testu pro _pro α=0,05, a n=5 je_ 0,642


·       **Vyhodnocení:** pokud platí **Qn** **≥ Qn, α**_,_ resp. **Q1** ≥ **Q1,α**, extrémní hodnotu vyloučíme

## Příklad      

·       _Předpokládejme, že máme k dispozici naměřené hodnoty uspořádané podle velikosti:  
3, 15     3, 20     3,25     3, 30     4, 00_

_Ověřte, zda extrémní hodnotu **4, 00**, která se na první pohled jeví výrazně odlišná od ostatních hodnot, je nutné se souboru vyloučit (zda je extrémní)  
  
_

$$Q_{n}={\frac{Q_{n}-Q_{n-1}}{Q_{n}-Q_{1}}}={\frac{4,00-3,30}{4,00-3,15}}={\frac{0,7}{0,85}}=0,8235$$


 _Vypočítaná hodnota testovacího kritéria je větší než kritická 0,8235_ _> 0,642, to znamená, že hodnotu 4,00 ze souboru vyloučíme jako extrémní_

**_Poznámka:_** _nulová hypotéza předpokládala, že hodnota není extrémní_



## Dva nezávislé výběry

Mann-Whitneyho test (U-test) pro nezávislé výběry


![](https://i.imgur.com/83pdp7F.png)

   pro ordinální veličiny, také kdy neplatí normalita a je malý počet pozorování

 H0: mediány u dvou závislých proměnných (výběrů) se rovnají

  H1: mediány u dvou závislých proměnných se liší

   př.: u stejného respondenta zjišťujeme rozdíl dvou měření,

ptáme se po nějaké době toho samého respondenta znovu na totéž,

ptáme se členů jedné rodiny na stejné téma,

 ptáme se stejných lidí na související otázky atd.


![](https://i.imgur.com/EKrt3PN.png)

Zajímá nás poslední Asymp. Sig. = p hodnota 0,55 je větší než 0,05. Nulovou hypotézu nemůže zamítnout.



## Test shody: Neparametrický test pro rozdělení (distribuci) proměnných

Kolmogorovův-Smirnovův test pro 1 výběr



  Testuje, zda rozdělení námi vybrané proměnné odpovídá některému z teoretických (normální, rovnoměrné, Poissonovo, exponenciální)·       



H0: Rozdělení sledované proměnné odpovídá teoretickému rozdělení

 H1: Rozdělení sledované proměnné neodpovídá teoretickému rozdělení

Tento test je vhodný zejména pro ověřování předpokladů pro určité statistické procedury, např. normalita proměnné pro parametrické testy. 

Statisticky nevýznamný výsledek značí, že data mají normální rozdělení (odpovídá formulaci nulové hypotézy).



![](https://i.imgur.com/VpTkK76.png)
