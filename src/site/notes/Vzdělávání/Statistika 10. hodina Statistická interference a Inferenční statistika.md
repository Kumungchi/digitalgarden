---
{"dg-publish":true,"permalink":"/Vzdělávání/Statistika 10. hodina Statistická interference a Inferenční statistika/"}
---


# Statistická inference

## **Výběrová variabilita a centrální limitní věta**

Výška českých žen

Populace – všechny ženy v ČR (𝜇, 𝜎).

–        Vzorek 1: 1000 žen z Moravskoslezského kraje: $\bar𝑋$<sub>MS</sub>

–        Vzorek 2: 1000 žen ze Zlínského kraje:$\bar X_z$

–        Vzorek 3: 1000 žen z Olomouckého kraje:  $\bar X$<sub>OL</sub>

Průměr populace: $\mu =\frac{x_1+x_2+...x_N}{N}$

SD populace: 
$$\text{S} = \sqrt{\frac{1}{N} \sum_{i=1}^{n} (x_i - \bar{x})^2}$$
Alternativní zápis
$$\sigma = \sqrt{\frac{\sum_{i=1}^{N} (x_{i} - \bar{x})^2}{N}}
$$
Výběrové rozdělení (průměrů vzorků):

–        **_průměr_**_:_ _𝑚𝑒𝑎𝑛_ $(\bar X)\approx\mu$

–        **_standardní chyba_**_:_ $SD(\bar X )=\frac{\sigma}{\sqrt{n}}$

Výběrové rozdělení průměrů by mělo mít průměr odpovídají průměru populační distribuce a směrodatnou odchylku odpovídající směrodatné odchylce populace dělené odmocninou z velikosti vzorku

**Centrální limitní věta (Central Limit Theorem)**

Distribuce některých výběrových statistik (např. průměrů), tj. jejich **výběrové rozdělení**, se s rostoucí velikostí vzorku **blíží normálnímu rozdělení** s průměrem rovným průměru populace a standardní odchylkou rovnou populační standardní odchylce dělené druhou odmocninou velikosti vzorku bez ohledu na tvar populačního rozdělení:

$$\bar{X} \sim \mathcal{N}(\text{mean} = \mu, \text{SE} = \frac{\sigma}{\sqrt{n}})
$$

Jinými slovy, lze předpokládat, že:

$$Z = \frac{\bar{x} - \mu}{\frac{\sigma}{\sqrt{n}}}
$$

má standardní normální rozdělení ($\bar x -\mu$ jsou odchylky průměrů vzorku od populačního průměru a ${\frac{\sigma}{\sqrt{n}}}$ je standardní chyba čili standardní odchylka výběrového rozdělení.

CLT tedy vypovídá o tvaru, střední hodnotě a variabilitě výběrového rozdělení.

**Podmínky CLT**

**Nezávislost pozorování**: Pozorování by měla být nezávislá.

Náhodný výběr/znáhodnění.

**Velikost vzorku a šikmost**. Populační distribuce by měla být normální; pokud je zešikmená, měli bychom mít dostatečně velký vzorek ($n \geq 30$; ale čím větší zešikmení, tím větší vzorek je nutný).

## Příklady
### Př. 1
U Wechslerových inteligenčních škál jsou skóry normálně rozložené s μ = 100 a σ = 15 (toto jsou populační parametry). Představte si, že jsme otestovali náhodný vzorek 9 lidí, spočítali jejich průměrný skór a celou proceduru zopakovali 100krát. Odhadněte směrodatnou odchylku těch 100 výběrových průměrů teoreticky i pomocí simulace.

$$\frac{15}{\sqrt9}=5$$
teoreticky očekáváme, že směrodatná odchylka průměrů 100 výběrů bude 5.

 http://fssvm6.fss.muni.cz/sampling_dist/
### Př. 2

U Wechslerových inteligenčních škál jsou skóry normálně rozložené s μ = 100 a σ = 15 (toto jsou populační parametry). 

Představte si, že jsme otestovali náhodný vzorek 9 lidí, spočítali jejich průměrný skór a celou proceduru zopakovali 1000krát. Zhruba jaká část (v %) těchto výběrových průměrů s n = 9 by byla vyšší než 105? A než 110? 

Protože SE = 5, odpovídá hodnota 105 z-skóru 1 a hodnota 110 z-skóru 2. 
P(Z > 1) je přibližně 16 % a P(Z > 2) je přibližně 2,5 %.

[[Vzdělávání/Z skor a Z test\|Z skor a Z test]]

## Příklad 3.

U Wechslerových inteligenčních škál jsou skóry normálně rozložené s μ = 100 a σ = 15 (toto jsou populační parametry). Představte si, že jsme otestovali náhodný vzorek 9 lidí, spočítali jejich průměrný skór a celou proceduru zopakovali 100krát. Zhruba jaká část (v %) těchto výběrových průměrů s n = 9 by byla mezi 95 a 105? A mezi 90 a 110? 

1. **Procento výběrových průměrů mezi 95 a 105:**

Zde budeme používat znalost, že 68 % hodnot v normálním rozdělení leží v intervalu μ±1μ±1 směrodatné odchylky a 95 % hodnot leží v intervalu μ±1.96μ±1.96 směrodatné odchylky.

Pokud máme směrodatnou odchylku 15 a průměr 100, potom interval μ±1μ±1 směrodatné odchylky je 100±15100±15 nebo 8585 až 115115. To pokrývá přibližně 68 % hodnot v normálním rozdělení.

Jestliže se větší část hodnot v rozdělení nachází v intervalu μ±1μ±1 směrodatné odchylky, pak zhruba 68 % výběrových průměrů (s n=9n=9) by mělo být mezi 95 a 105.



Přibližně 68 %, resp. 95 %

2. **Procento výběrových průměrů mezi 90 a 110:**

Interval μ±2μ±2 směrodatné odchylky pro tento rozdělení je 100±(2×15)100±(2×15) nebo 7070 až 130130. To pokrývá přibližně 95 % hodnot v normálním rozdělení.

Proto by zhruba 95 % výběrových průměrů (s n=9n=9) mělo být mezi 90 a 110.

## Intervaly spolehlivosti (CI)

Interval spolehlivosti: věrohodné rozmezí hodnot pro odhad populačního parametru. 

Jinými slovy interval obsahující populační parametr se stanovenou mírou pravděpodobnosti, kde pravděpodobnost chápeme frekventisticky jako podíl intervalů spolehlivosti z mnoha vzorků, které zahrnují skutečnou hodnotu populačního parametru (např. populačního průměru). Bodový odhad (jedna hodnota): je velmi nepravděpodobné, že by se populační parametr přesně rovnal bodovému odhadu. Interval možných hodnot: větší pravděpodobnost, že zachytí populační parametr. Simulace intervalů spolehlivosti pro průměry vzorků pocházejících ze standardního normálního rozdělení: 
https://rpsychologist.com/d3/ci/


## Korektní interpretace (na příkladu 95% CI)


Opakovaný výběr vzorků z populace. Pokud bychom populace vybírali náhodné vzorky a pro každý z nich vypočítali 95% interval spolehlivosti, pak přibližně 95 % těchto intervalů bude zahrnovat skutečnou hodnotu populační parametru. Jakýkoli budoucí, potenciální vzorek. Existuje 95% pravděpodobnost, že pokud provedeme výzkum a vypočteme 95 % interval spolehlivosti, bude tento interval zahrnovat skutečnou hodnotu populačního parametru. Zamítnutí určitých hodnot populačního parametru. Kdybychom prováděli výzkumy a počítali 95% intervaly spolehlivosti a vždy tvrdili/věřili, že skutečná hodnota populačního parametru se nachází v tomto intervalu pak bychom se mýlili přibližně v 100% – 95% = 5 % případů.

## Interval spolehlivosti pro průměr populace


Vypočítá se jako průměr vzorku plus/mínus mezní chyba, angl. margin of error (kritická hodnota odpovídající vybranému podílu normální distribuce krát standardní chyba): 𝑿 ̅±𝒁×𝝈/√𝒏 
Z = 1 pro 68% CI; Z = 1,64 pro 90% CI; Z = 1,96 pro 95% CI; Z = 2,58 pro 99% CI. 

Podmínky: Nezávislost. Pozorování musí být nezávislá. Znalost populační 𝝈. Jinak bychom měli použít t-rozdělení, zvláště pokud máme malý vzorek. Normalita populačního rozdělení. Anebo dostatečně velký vzorek pro platnost centrální limitní věty.


## Interval spolehlivosti pro průměr populace, neznáme-li 𝝈


Když neznáme populační standardní odchylku 𝝈, musíme ji odhadnout pomocí standardní odchylky vzorku 𝒔, ze Z se pak stává: 𝑇=(𝑥 ̅−𝜇)/(𝑠/√𝑛) Je-li populační rozdělení normální, bude rozdělení T odpovídat Studentovu t-rozdělení, jehož tvar bude záviset na tzv. stupních volnosti (značí se df nebo v), které vyplývají z velikosti vzorků: 𝑑𝑓=𝑛−1. Stupně volnosti odpovídají počtu hodnot, které lze libovolně měnit, známe-li hodnotu nějaké statistiky (např. 𝑥 ̅). Jinými slovy – jedná se o počet hodnot, které musíme znát, abychom znali všechny ostatní hodnoty. Kdyby např. byla velikost vzorku 𝑛=10 a znali bychom průměr vzorku 𝑥 ̅=100, stačilo by znát 𝑛−1=99 hodnot, abychom věděli, jaká je zbývající hodnota.


- Podobá se normálnímu, ale má těžší chvosty
- Čím více stupňů volnosti, tím více se podobá norm. rozdělení


![](https://i.imgur.com/3eqrXLM.png)


Pokud chceme intervaly spolehlivosti vypočíst ručně, postupujeme následovně: Stanovíme si úroveň spolehlivosti, často 0,95 (obecně 1−𝛼, kde 𝛼 představuje pravděpodobnost, že interval nebude obsahovat hodnotu populačního parametru). Vypočteme směrodatnou odchylku 𝒔, průměr vzorku 𝒙 ̅a stupně volnosti 𝒅𝒇=𝒏−𝟏. Nalezneme příslušný kvantil t-distribuce, 𝒕_(𝟏−𝜶/𝟐)., kde 𝜶=𝟏−ú𝒓𝒐𝒗𝒆ň 𝒔𝒑𝒐𝒍𝒆𝒉𝒍𝒊𝒗𝒐𝒔𝒕𝒊 Vypočteme samotný interval spolehlivosti pro průměr populace: (𝒙 ̅−𝒕_(𝟏−𝜶/𝟐) 𝒔/√𝒏;𝒙 ̅+𝒕_(𝟏−𝜶/𝟐) 𝒔/√𝒏) 

Např. při 95% (alfa = 5 %) úrovni spolehlivosti a 𝑑𝑓=30 bude 𝑡_0,975=2,042.


## Interval spolehlivosti pro relativní četnost: Exaktní výpočet

Pokud podmínky normální aproximace nejsou splněny, nebo je velikost vzorku někde "na rozhraní" přijatelnosti normální aproximace, měli bychom použít "exaktní" výpočet. Zaznamenáme si počet "úspěchů" k a velikost vzorku n. Stanovíme si úroveň spolehlivosti, např. 95 %, a α = 1 – úroveň spolehlivosti. Vygenerujeme si sekvenci možných populačních pravděpodobností p od 0 do 1 po velmi malých krocích (např. 0,000, 0,001, 0,002 atd. až 1,000). Horní mez intervalu stanovíme tak, že nalezneme nejvyšší p, pro které platí, že P(k či méně úspěchů z n pokusů ) > 1/2 α. =BINOM.DIST(k; n; p; PRAVDA) Dolní mez intervalu stanovíme tak, že nalezneme nejnižší p, pro které platí, že P(k či více úspěchů z n pokusů ) > 1/2 α. =1-BINOM.DIST(k-1; n; p; PRAVDA)


## Percentilový bootstap

Představme si, že bychom tentýž výzkum provedli 1000 krát na různých vzorcích téže velikosti a z téže populace. Pro každý vzorek bychom vypočetli např. průměr a zjistili bychom, že 95 % průměrů se pohybuje od 3 do 10. Jinými slovy 2,5% kvantil výběrového rozdělení by byl 3 a 97,5% kvantil výběrového rozdělení by byl 10 a 95% CI pro populační průměr by byl [3; 10]. Z tohoto principu vychází percentilový bootstrap, ale místo toho, abychom výzkum 1000krát replikovali, získáváme výběrové rozdělení pomocí simulace. Z našeho původního vzorku tvoříme bootstrapové vzorky tak, že provádíme náhodný výběr z našeho vzorku s navrácením prvků. K našemu původnímu vzorku se tedy chováme jako k populaci, ze které provádíme náhodný výběr s navrácením prvků pro tvorbu tzv. boostrapových vzorků.

Máme např. 𝑛 případů, tzn. 𝑋_1,𝑋_2, …𝑋_𝑛. Z těchto případů získáme bootstrapový vzorek o stejné velikosti 𝒏 náhodným výběrem s navrácením prvků (jakýkoli prvek 𝑋 tak můžeme vybrat 0 až 𝑛-krát). Získáme tedy bootstrapový vzorek 𝑋_1^∗,𝑋_2^∗,… 𝑋_𝑛^∗. Takto simulujeme mnoho bootstrapových vzorků (např. 2000). Původní hodnoty:1, 4, 2, 19, 4, 12, 29, 4, 9, 16. 1. bootstrapový vzorek (příklad):2, 9, 16, 2, 4, 12, 4, 29, 16, 19. 2. bootstrapový vzorek (příklad):29, 16, 29, 19, 2, 16, 2, 9, 4, 29.

U všech těchto 1000 bootstapových vzorků vypočteme průměr, Všech 1000 průměru seřadíme od nejmenšího po největší 95% CI pro populační průměr zjistíme na základě prostředních 95 % bootstrapových průměrů (hodnot 2,5% a 97,5% kvantilu). Vyzkoušejte si sami pomocí této aplikace:http://fssvm6.fss.muni.cz/bootstrap/ Zkuste zjistit 90% bootstrapový interval spolehlivosti pro podíl covid pozitivních, pokud jsme. Protože je 25 covid–, 5 covid+, musíme vložit celkem třicet hodnot: 0 (25krát) a 1 (5krát).

## Velikost vzorku nutná pro stanovenou mezní chybu

Výpočet potřebné velikosti vzorku

Stanovíme-li si předem **mezní chybu** (_ME_, tj. margin of error) a **úroveň spolehlivosti** (obvykle 95 %) a známe-li variabilitu populační distribuce (standardní odchylku, 𝜎), můžeme vypočíst potřebnou velikost vzorku pro dosažení stanovené ME.

 Protože ME je násobkem příslušného _z_- nebo _t_-skóru a standardní chyby:

$$\text{ME} = Z \times \frac{\sigma}{\sqrt{n}}
$$

Můžeme si z této rovnice vyjádřit _n_:

$$\sqrt{n} = \frac{Z \times \sigma}{\text{ME}};
n = \left(\frac{Z \times \sigma}{\text{ME}}\right)^2
$$



Dejme tomu, že chceme ověřit účinek užívání antiepileptik u těhotných žen na kognitivní vývoj jejich dítěte. Konkrétně chceme odhadnout průměrné IQ 3letých dětí, které se narodily matkám užívajícím v průběhu těhotenství antiepileptika. Podle předchozích výzkumů je standardní odchylka IQ skórů u tříletých dětí 18 bodů. Kolik takových dětí musíme vyšetřit, abychom získali 90% interval spolehlivosti s ME maximálně 4 body IQ?


𝑀𝐸=4 𝐶𝐿=90% 𝑍=1,65 𝜎=18 𝑛=((1,65×18)/4)^2=55,13

Potřebujeme tedy vzorek o velikosti aspoň n = 56


Zjistili jsme, že potřebujeme vzorek aspoň 56 dětí, aby stanovená ME = 4. Jak by se potřebná velikost vzorku změnila, pokud bychom chtěli dosáhnout ME = 2. √𝑛=𝑍×𝑠/𝑀𝐸 √𝑛×2=𝑍×𝑠/(𝑀𝐸∕2) 𝑛×2^2=((𝑍×𝑠)/(𝑀𝐸/2))^2 Obecně: Pokud má být nová 𝑴𝑬 pouze 𝟏/𝒌 násobkem původní 𝑀𝐸, je nutné 𝒌^𝟐-násobná velikost vzorku. vysvětlení: SE, a tedy i ME je lineárně závislá nikoli na n, ale na odmocnině z n. Takže např. navýšení vzorku o +10 osob bude mít větší efekt na standardní chybu, pokud je původní vzorek malý (např. 10 osob), než když je rozsáhlý (např. 1000 osob)


# Inferenční (Induktivní statistika)

[[Vzdělávání/Statistika 9. hodina Vzorkování a hypotézy#Hypotézy\|Statistika 9. hodina Vzorkování a hypotézy#Hypotézy]]
## Statistická síla  


**Statistická síla** (síla testu) představuje pravděpodobnost, že správně zamítneme H0, když H0 neplatí a platí a HA

_P_(zamítnutí H0 | H0 neplatí) = 1 – _P_(nezamítnutí H0 | H0 neplatí)

Rovná se **1 –** **β***

Vizualizace statistické síly pro ověřování rozdílu mezi průměry

 https://rpsychologist.com/d3/NHST/

## GPower

K power analýze pro základní statistické testy se nejčastěji používá freewarový program GPower:

 https://www.psychologie.hhu.de/arbeitsgruppen/allgemeine-psychologie-und-arbeitspsychologie/gpower

Umožňuje několik druhů analýz, mimo jiné:

**Apriorní power analýzu**: výpočet potřebné velikosti vzorku na základě předem stanovené hladiny alfa, požadované statistické síly a očekávané velikosti účinku. Tento typ power analýzu je nejdůležitější při plánování výzkumu.

**Power analýzu senzitivity**: výpočet potřebné velikosti účinku na základě stanovené hladiny alfa, požadované statistické síly  
a velikosti vzorku.

**Post-hoc power analýzu**: výpočet dosažené statistické síly na základě stanovené hladiny alfa, velikosti vzorku a pozorované velikosti účinku.

### Příklad

Průměrné hodnoty IQ ve společnosti neustále stoupají, přibližně o tři body za deset let. Ne všechny součásti inteligenčních škál však zaznamenávají růst, některé zůstávají s přibližně totožnou hodnotou po desítky let. Tento fenomén se nazývá Flynnův efekt. Jak velký vzorek musíme získat, abychom tento efekt detekovali s 80 % statistickou silou při hladině alfa = 0,05? Předpokládejme, že inteligenční test, který se chystáme použít, byl před deseti lety aktuální, a průměrné IQ v populaci tedy bylo 100. Očekáváme, že (při použití stejných norem testu) je současné průměrné IQ populace 103.