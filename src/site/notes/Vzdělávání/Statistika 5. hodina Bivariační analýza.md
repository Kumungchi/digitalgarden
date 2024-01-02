---
{"dg-publish":true,"permalink":"/Vzdělávání/Statistika 5. hodina Bivariační analýza/"}
---


# Bivariační analýza (dvourozměrné distribuce)

[[Vzdělávání/Vzorečky na statistiku#Binomický rozdělovací vzorec\|Vzorečky na statistiku#Binomický rozdělovací vzorec]]

- rozdělení dvou prom., třídění druhého stupně (druhostupňové třídění)
- sledování vztahů dvou prom. (vztah výšky a váhy, finančního ohodnocení a spokojenosti v práci, únavy a výkonu)
- Typy vztahů: shoda, protiklad, nezávislost


## Shoda
pozitivní souvislost - nízké hodnoty jedné se potkávají s nízkými hodnotami druhé, podobné potkávání u vysokých hodnot

## Protiklad
negativní souvislost - nízké s vysokými a naopak

## Nezávislost 
neexistenci souvislosti - nepozorujeme pravidelnost


# Možnosti zpracování
Tabulkové (kontingenční), krostabulace
Grafické znázornění - bodový graf
Numerické charakteristiky - korelační a kontingenční koeficienty


## Tabulkové zpr.
nezávislá a závislá prom
Nejčastěji bývá závislá nalevo v řádcích a nezávislá (vysvětlující) ve sloupcích

| Osobní pohoda | muž | žena | Sum |
| ------------- | --- | ---- | --- |
| 1 nespokojen  |  5 (41%)  |  2  (22%)  |  7   |
| 2             |  5 (41%)  |  1  (11%)  |  6   |
| 3 spokojen    |  2  (16%) |   6 (66%) |  8   |
| Sum           |  12 (100%)  |  9 (100%)   | 21    |
### Interpretace tabulek
závislá - ovlivňována, způsobována (nejčastěji v řádcích)
nezávislá - ovlivňuje, vysvětluje závislou (sloupce)

>[!warning] Pozor
>Směr kauzality je vždy věcí teorie, nelze ji určit z dat samotných

### Explanační interpretace dvourozměrné tabulky
1. osoby rozdělíme do podskupin podle úrovní nezávislé proměnné (muži/ženy)
2. Každá podsk. popsána podle hodnot proměnné (např. osobní pohoda)
3. Tabulku čteme tak, že porovnáváme navzájem podskupiny nezávislé proměnné (muži/ženy) podle hodnot závislé proměnné (osobní pohoda). Smysluplné je porovnávat distribuce napříč kategoriemi nezávislé proměnné 


### Relativní četnosti
- Rela. Řádkové četn. poměr hodnoty v políčku a součtu řádku násobený 100. Součet v každém řádku reprezentuje 100%
- Sloupcové - poměr hodnoty v políčku a součtu sloupce násobený 100. Součet v každém sloupci reprezentuje 100 %
- Relativní celkové četnosti = poměr hodnoty v políčku a celkového součtu násobený 100

### Souvislost znaků v tabulce (dvě závislé proměnné)

- Seskupení vysokých hodnot na diagonále tabulky naznačuje, že existuje souvislost mezi prom. (o závislých pro.)
- Souvislost může mít i jinou formu, např. v každém sloupci jsou pozorování nahromaděna do jediného pole, jehož pozice je pro každý sloupec jiná



## Korelace
vztah (souvislost, asociace) mezi dvěma proměnnými, jejichž hodnoty jsou uspořádány ve dvojicích
- Neznámá sama o sobě příčinný (kauzální) vztah!
- Sílu tohoto vztahu určuje korelační koeficient (napč. Pearson, Spearman, Kendall)
- Umožňuje odvodit procento společné variability

- Dvě proměnné (označují se X a Y ) - ptáme se, zda jsou nezávislé, nebo existuje mazi nimi souvislost (korelace) a jak je silná
- Součinový korelační koeficient (Pearson) r
- Pořadový korelační koeficient (Spearman) r<sub>s</sub> 𝛒 (ró)
- Kendallovo  $\tau$ (tau)

### Korelační koeficient
- Určuje stupeň vztahu mezi dvěma proměnnými. Je vyjadřován číslem s hodnotou mezi 0 a 1 (resp. 0 až -1). Žádný vztah znamená 0. ´plná kladní závislost je 1. Úplná záporná je -1

- S růstem hodnoty r od 0 k 1 (nebo -1) se míra těsnosti vztahu zvyšuje
- Hodnota korelačního koeficientu mezi výsledky dosaženými v prvním roce studia na univerzitě a výsledky v ročníku druhém je 0,75. Tento výsledek ukazuje na kladnou a těsnou (silnou) závislost)

- hodnoty k. koe. od 0,1 do 0,3 znamenají slabý vztah proměnných
- hodnoty nad 0,3 až 0,6 středně silný vztah
- hodnoty nad 0,6 silný vztah dvou proměnných
- Uvedené platí jak pro kladné tak záporné hodnoty korelací


#### Interpretace hodnot korelačního koeficientu v sociálních vědách (detailnější členění)
0,01 - 0,09 triviální, žádná
0,10 - 0,29 nízká až střední
0,30-0,49 střední až podstatní
0,50-0, 69 podstatná až velmi silná
0,70 - 0,89 velmi silná
0,90 - 0,99 téměř perfektní


#### Důležité vlastnosti korelačního koeficientu
1. Platí -1 -< r -< +1
2. Jestliže |r| = 1, leží všechny body na přímce
3. Jestliže r = 0, nazýváme X a Y nekorelované proměnné. Dvě náhodné proměnné jsou tím více korelovány, čím blíže je hodnota r k číslům +1 nebo -1. V tom případě lze vztah obou proměnných dobře vyjádřit

Druhou mocninou koeficientu korelace je koeficient **determinace**, jeho stonásobek udává, z kolika procent jsou změny hodnoty závisle proměnné Y vysvětlovány hodnotami nezávisle proměnné (proměnných), tj. vypočtenou regresní funkcí.
Stupnice těsnosti závislosti podle koeficientu determinace je zhruba takto:
r<sup>2</sup> < 10 %těsnost nízká
10 %  r<sup>2</sup> < 25 %těsnost mírná
25 %  r<sup>2</sup> < 50 %těsnost význačná
50 %  r<sup>2</sup> < 80 %těsnost velká
80 %  r<sup>2</sup> těsnost velmi vysoká



<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/vzdelavani/statistika-na-prvni-test/#pearsonuv" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">

$<div class="markdown-embed-title">

# Statistika na první test

</div>


## Pearsonův
popisuje lineární vztah mezi dvěma kvantitativními proměnnými.

**předpoklady, které musí data splňovat, pokud chcete použít Pearsonovo r:**

- Obě proměnné jsou na intervalové nebo poměrové úrovni měření
- Data z obou proměnných mají normální rozdělení
- Vaše data nemají žádné odlehlé hodnoty
- Vaše data pocházejí z náhodného nebo reprezentativního vzorku
- Očekáváte lineární vztah mezi dvěma proměnnými

je parametrický test, takže má vysoký výkon

Ale není to dobré měřítko korelace, pokud mají  proměnné nelineární vztah nebo pokud  data mají odlehlé hodnoty, zkreslená rozdělení nebo pocházejí z kategorických proměnných

**Vzorec**
$r = \frac{\sum{(x_i - \bar{x})(y_i - \bar{y})}}{\sqrt{\sum{(x_i - \bar{x})^2} \sum{(y_i - \bar{y})^2}}}
$
![](https://i.imgur.com/Fsd8dts.png)




</div></div>





<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/vzdelavani/statistika-na-prvni-test/#spermanuv" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">

$<div class="markdown-embed-title">

# Statistika na první test

</div>


## Spermanův
nejběžnější alternativou k Pearsonově 

Je to korelační koeficient pořadí, protože používá pořadí dat z každé proměnné (např. od nejnižší po nejvyšší) spíše než samotná nezpracovaná data

Spearmanův byste měli použít, když vaše data nesplňují předpoklady Pearsonova 

K tomu dochází, když je alespoň jedna z vašich proměnných na ordinální úrovni měření nebo když data z jedné nebo obou proměnných nesledují normální rozdělení.

Zatímco Pearsonův korelační koeficient měří linearitu vztahů, Spearmanův korelační koeficient měří monotónnost vztahů

V lineárním vztahu se každá proměnná mění v jednom směru stejnou rychlostí v celém rozsahu dat

V monotónním vztahu se také každá proměnná vždy mění pouze jedním směrem, ale ne nutně stejnou rychlostí.

- Pozitivní monotónní: když se jedna proměnná zvyšuje, zvyšuje se i druhá.
- Negativní monotónní: když se jedna proměnná zvyšuje, druhá klesá.

**Vzorec:**
Základní
$\rho = 1 - \frac{6\sum (x_i - y_i)^2}{n(n^2 - 1)}
$
Upravený o diviaci $d_i$ - rozdíl mezi x a y
$\rho = 1 - \frac{6\sum (d_i)^2}{n(n^2 - 1)}

$
Pro fajnšmekry, kompletně upravený
$\rho = 1 - \frac{6\sum (d_i)^2}{n^{3}-n}
$
![](https://i.imgur.com/77y5dmq.png)




</div></div>






<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/vzdelavani/statistika-na-prvni-test/#kendaluv" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">

$<div class="markdown-embed-title">

# Statistika na první test

</div>


## Kendalův

- měří vztah mezi dvěma sloupci seřazených dat
- není potřeba aby data byla normálně rozdělena

**Vzorec**
C - konrodtantní, +, jsou větší, souhlasné páry
D - diskonkordatní, -, jsou měnší, nesouhlasné páry

$\tau=\frac{C-D}{C+D}$

> [!task]+ Příklad
> Dva učitelé seřadí 12 svých žáků od nejhoršího po nejlepšího. Máme dva sloupce hodnocených dat, je vhodné použít Kendalla
> Budeme se dívat pouze na pozice u Učitele dva.



| Hráč   | Učitel 1 | Učitel 2 |
| ------ | -------- | -------- |
| Aj     |     1     |   <mark style="background: #FFB86CA6;">1</mark>      |
| Ben    |     2     |      2    |
| Ellito |     3     |    3      |
| Conner |     4     |     5     |
| Duane  |     5     |     4     |
| Frank  |    6      |     7     |
| Greg   |    7      |     6     |
| Hank   |    8      |      8    |
| Isaiah |     9     |      10    |
| Jim    |     10     |     9     |
| Kurt   |    11      |      11    |
| Luke   |     12     |     12     |

>[!warning]- Řešení
>Od prvního hráče, o kolik pozic pod ním jsou větší. Pod 1 je 11 větších - konkordantních.
>Pod dvojkou je 10 větších.
>Takhle pro všechny hráče až k nule
>Diskorkodantní kolik pozic je menších. Pokud není žádný tak píšeme nulu.
>Suma C 63
>Suma D 3
>Kendallovo Tau = 0,909



</div></div>



## Regresní a korelační analýza
-  zkoumání a hodnocení závislostí mezi kvantitativními (metrickými) statistickými
znaky, zpravidla označovanými jako proměnné.

- volné (statistické) závislosti, které v biologickém, sociálně-vědním i ekonomickém výzkumu
téměř výhradně převládají.

Volnou (nebo statistickou) závislostí rozumíme takový vztah
proměnných, kdy stejné hodnotě Xi nezávisle proměnné X při
opakovaném měření neodpovídá vždy shodná hodnota závisle
proměnné Y, ale celé pole rozdílných hodnot proměnné Y.
Se změnou hodnot nezávisle proměnné X (event. proměnných XI,
Xk) se mění i úroveň hodnot (tj. střed pole hodnot) závisle proměnné Y.


**Při regresní a korelační analýze prakticky vždy**
řešíme dvě základní úlohy:
Změřit těsnost zkoumané závislosti, tzv. korelaci.
Vyjadřujeme a hodnotíme ji podle vypočtených hodnot
charakteristik korelace a determinace.
Zjistit a vhodně vyjádřit průměrný průběh závislosti, tzv.
regresi. Vyjadřujeme ji výpočtem parametrů vhodné
regresní funkce.

Protože regresní a korelační analýzu provádíme téměř vždy
s daty naměřenými na výběrovém souboru statistických
jednotek, je možno považovat získané výsledky pouze za
odhady pro shodné závislosti v základním (populačním)
souboru.



