---
{"dg-publish":true,"permalink":"/Vzdělávání/Statistika 9. hodina Vzorkování a hypotézy/"}
---


# Vzorkování

- Výběrová variabilita (sampling variability) 
	- rozptyl výsledků, které můžeme pozorovat v různých vzorcích populace. Opakované výběry z populace dají různé vzorky, způsobeno náhodným výběrem jednotlivých jednotek do vzorku
- Výběrová chyba (sampling error)
	- rozdíl mezi odhadem získaným z určitého vzorku a skutečnou hodnotou v populaci. Čím větší, tím méně je odhad ze vzorku přesný. 
- Deskriptivní st. - metody a techniky popisu a shrnutí dat 
- Inferenční st. - metody a techniky vyvozování závěrů a odhadů z informací získaných ze vzorků
- Výběrové rozdělení (sampling distributation)
	- rozdělení hodnot nějaké statistiky(pr. rozptyl,..) ze vzorků populace. Představuje možné hodnoty statistiky
- Standardní (směrodatná) chyba (standard error)
	- měření variability výsledků, které byly získány z různých vzorků populace. Ukazuje, jak dobře průměr vzorku reprezentuje průměr populace.
- Výběrové rozdělení rozdílů mezi průměry (sampling distributation of differences between means) 
	- rozdělení je klíčové zejména při porovnávání průměrů mezi různými skupinami v inferenční statistice, jako je například použití t-testů nebo analýzy rozptylu (ANOVA). Specifický typ výběrového rozdělení, mezi průměry získaných ze dvou nebo více vzorků, z různých populací


# Tradiční postup testování hypotéz

1. Stanovení výzkumné (alternativní) hypotézy (research alternative hypothes).
2. Stanovení nulové hypotézy (null statistical hypotheses)
3. Odvození výběrového rozdělení za předpokladu, že platí nulová hypotéza (sampling
distribution under null hypothes)
4. Sběr dat
5. Výpočet (testové) statistiky
6. Srovnání této statistiky s výběrový rozdělením předpokládajícím platnost nulové
hypotézy
7. Zamítnutí/nezamítnutí nulové hypotézy na základě toho, jak extrémní je zjištěná
statistika ve srovnání s ”nulovým” rozdělením


# Hypotézy

**Nulová (statistická) hypotéza (null/nill/statistical hypothesis).**
"Nic zajímavého se neděje": Rozhodnutí o povýšení a pohlaví uchazeče jsou nezávislé proměnné, nejedná se o diskriminaci žen, pozorovaný rozdíl nastal v důsledku "náhody" (výběrové variability).

**Výzkumná (alternativní) hypotéza (research/alternative hypothesis).**
 "Děje se něco zajímavého": Rozhodnutí o povýšení a pohlaví uchazeče spolu souvisejí, dochází k diskriminaci žen, pozorovaný rozdíl není důsledkem náhody.

Proč ji vlastně "potřebujeme" nulovou hypotézu?

 Argument falzifikace vs. verifikace.

Vágnost výzkumných hypotéz v sociálních vědách.

## Rekapitulace

Začínáme **nulovou hypotézou (H0)**, která představuje výchozí stav, skeptický postoj, status quo.

 Máme také **alternativní hypotézu (HA)**, která se týká výzkumné otázky, toho, co chceme zjistit.

Test hypotéz probíhá tak, že předpokládáme platnost nulové hypotézy a pomocí simulace nebo teoretických metod odvodíme "nulové" rozdělení (tj. **výběrové rozdělení testové statistiky při platnosti nulové hypotézy**).

Pak porovnáme náš výsledek, který jsme pozorovali,  
s nulovým rozdělením.

Pokud je pravděpodobnost našeho (nebo extrémnějšího) výsledku při platnosti nulové hypotézy malá, zamítáme nulovou hypotézu ve prospěch alternativní; v opačném případě nulovou hypotézu ponecháváme.

## Statistické závěry

 Zamítnutí nulové hypotézy.

 Nezamítnutí nulové hypotézy.

 Proč bychom neměli říkat, že jsme "prokázali" nulovou hypotézu?

Příklady na nulovou hypotézu
## **Příklad 1:**

**Nulová hypotéza (_H0_):** Průměr skóre testu studentů je roven 75.

**Alternativní hypotéza (_H1_):** Průměr skóre testu studentů je odlišný od 75.

V tomto příkladě je nulová hypotéza tvrzením, že průměrné skóre studentů v testu je přesně 75. Alternativní hypotéza naopak tvrdí, že průměrné skóre je odlišné od 75, ať už větší nebo menší.

## **Příklad 2:**

**Nulová hypotéza (_H0_):** Nová léčba nemá vliv na snížení bolesti.

**Alternativní hypotéza (_H1_):** Nová léčba snižuje bolest.

V tomto příkladě je nulová hypotéza tvrzením, že nová léčba nemá žádný vliv na snížení bolesti u pacientů. Naopak, alternativní hypotéza tvrdí, že nová léčba má vliv na snížení bolesti, což znamená, že pacienti pod touto léčbou mají menší bolestivost než ti, kteří léčbu nedostávají.

## **Příklad 3:**

**Nulová hypotéza (_H0_):** Střední výška rostlin v kontrolní skupině je stejná jako ve skupině s novým hnojivem.

**Alternativní hypotéza (_H1_):** Střední výška rostlin v kontrolní skupině se liší od střední výšky ve skupině s novým hnojivem.

V tomto příkladě nulová hypotéza tvrdí, že střední výška rostlin v kontrolní skupině (bez nového hnojiva) je stejná jako ve skupině, která byla ošetřena novým hnojivem. Alternativní hypotéza naopak navrhuje, že mezi skupinami existuje rozdíl v průměrné výšce rostlin.
## Testové statistiky

- Co je to testová statistika/testové kritérium (test statistics, test criterion)?
	- číselná hodnota používaná v rámci statistických testů k rozhodnutí o přijetí nebo zamítnutí statistické hypotézy. Testová statistika vypočítá z dat ve vzorku a následně se porovná s určitým kritickým prahem nebo se srovnává s teoretickým rozdělením pravděpodobnosti. To nám umožňuje určit, zda jsou naše pozorované výsledky v souladu s nějakou hypotézou nebo zda se od ní významně liší.


- Jaké existují testové statistiky?
	 1. **Z-test a T-test:** Používá se pro testování průměrů mezi dvěma skupinami nebo pro porovnání průměru s teoretickou hodnotou.
    
	 2. **Chi-kvadrát test:** Slouží k určení nezávislosti mezi dvěma kategoriálními proměnnými.
    
	3. **F-test (analýza rozptylu - ANOVA):** Používá se k porovnání více než dvou průměrů mezi třemi nebo více skupinami.
    
	4. **Korelační testy:** Jakými jsou Pearsonův korelační koeficient nebo Spearmanův rangový koeficient, které měří vztah mezi dvěma spojitými proměnnými.
    
	5. **Wilcoxonův test:** Používá se pro porovnání dvou spojitých proměnných v případě, že data nejsou normálně rozdělena.
    
	6. **Kolmogorov-Smirnovův test:** Slouží k testování shody mezi empirickým a teoretickým distribučním modelem dat.
	7.  A další ….


## Rozhodnutí o zamítnutí nulové hypotézy

 - Hladina statistické významnosti (rejection level, significance level).
	 - pravděpodobnost chyby, kterou jsme ochotni přijmout, když zamítneme nulovou hypotézu. Symbol $\alpha$ znamená pravděpodobnost chyby, kterou jsme připraveni akceptovat při zamítnutí nulové hypotézy. Nižší může vést k vyššímu riziku vynechání skutečných efektů.

- Kritická hodnota (critical value). https://www.socscistatistics.com/tests/criticalvalues/default.aspx 
	- určitá hodnota test. stat., za kterou pokud se dostane nebo přesáhne, zamítáme nulovou hypotézu, na základě zvolené hladiny významnosti a distribuce pravděpodobnosti

- Oblast zamítnutí (rejection region).
	- interval hodnot testové statistiky, ve kterém, pokud se nachází, zamítneme nulovou hypotézu. Určena hladinou významnosti a kritickou hodnotou

![](https://i.imgur.com/BwWmPQu.png)


## Chyba I. a II. typu


![](https://i.imgur.com/ErJQxEB.png)

**Chyba l**- typu nastává, když zamítneme Ho, ačkoli platí
Pravděpodobnost chyby l- typu odpovídá zvolené hladině
statistické významnosti: = P(zamítnutí Ho I Ho platí)

**Chyba ll**- typu nastává, když nezamítneme Ho, ačkoli neplatí
Pravděpodobnost chyby Il. typu se značí a odpovídá
P(nezamítnutí Ho I Ho neplatí)-
Nevíme, zda platí Ho nebo HA, ale musíme vzít
v úvahu všechny možnosti

Příklad chyba I typu a II typu
Ověřování hypotéz se podobá soudnímu procesu.

–  **H0: Obžalovaný je nevinen**. Presumpce neviny – dokud nepřineseme dostatečné důkazy o vině, držíme se nulové hypotézy.

–         **HA: Obžalovaný je vinen**. Toto tvrzení musíme podložit dostatečnými důkazy, jinak nelze zamítnout H0.

***Který typ chyby odpovídá následujícím omylům?***

–         Prohlásíme obžalovaného nevinným, ačkoli je vinen.

–         Prohlásíme obžalovaného vinným, ačkoli je nevinen.

Testování hypotéz jako soudní proces

Ověřování hypotéz se podobá soudnímu procesu.

–         H0: Obžalovaný je nevinen. Presumpce neviny – dokud nepřineseme dostatečné důkazy o vině, držíme se nulové hypotézy.

–         HA: Obžalovaný je vinen. Toto tvrzení musíme podložit dostatečnými důkazy, jinak nelze zamítnout H0.

Který typ chyby odpovídá následujícím omylům?

–    Prohlásíme obžalovaného nevinným, ačkoli je vinen.

 **Chybě II. typu.**

–  Prohlásíme obžalovaného vinným, ačkoli je nevinen.

**Chybě I. typu.**

 Který typ chyby má horší dopad?

Chyba II. typu: Prohlásíme obžalovaného nevinným, ačkoli je vinen.

Chyba I. typu: Prohlásíme obžalovaného vinným, ačkoli je nevinen.

 William Blackstone (anglický soudce žijící v 18. století): "Je lepší, když 10 skutečných viníků unikne trestu, než aby jeden nevinný byl neprávem odsouzen" (Blackstonův poměr).

**Zamítáme H0, pokud je p-hodnota nižší než stanovená hladina statistické významnosti** **α** (nejčastěji používaná hladina α = 0,05).

To znamená, že když H0 platí, nechceme se dopustit chyby ve více než α-podílu případů.

Jinými slovy – při úrovni α = 0,05 existuje přibližně 5% pravděpodobnost chyby I. typu (nesprávného zamítnutí nulové hypotézy, ačkoli platí).

$\alpha=P(\text zamítnutí\; H_0|H_{0}\; platí)$

 **Proto často volíme poměrně konzervativní** **𝛂**, při vyšší α by častěji docházelo k chybě I. typu.

Zvolení hladiny α

Pokud je chyba I. typu velmi "nákladná", volíme nižší úroveň statistické významnosti (např.  
α = 0,01, 0,005 či 0,001).

Cíl: Chceme být velmi opatrní při zamítání H0, požadujeme proto velmi silné důkazy  
ve prospěch HA.

 Chyba II. typu
 **Pokud platí alternativní hypotéza, jaká je pravděpodobnost chyby II. typu** (tzn. nezamítnutí nulové hypotézy, ačkoli neplatí)?

–         Odpověď není jednoduchá.

–         Pokud je populační parametr velmi blízko nulové hodnotě, je obtížné detekovat rozdíl (zamítnout H0).

–         Pokud je populační parametr velmi vzdálen nulové hodnotě, je snadnější detekovat účinek, rozdíl, vztah.

–         β tedy závisí na velikosti účinku (rozdílu mezi bodovým odhadem a nulovou hodnotou).

### Testování hypotéz ohledně průměru


**Nulová hypotéza (H0)**: Výchozí skeptické stanovisko. Negace alternativní hypotézy.

**Alternativní hypotéza (HA)**: Opačné tvrzení. Obvykle se zajímáme právě o ni.

Nulovou hypotézu nezamítáme, dokud nemáme dostatečné důkazy podporující alternativní hypotézu.

Nulovou i alternativní hypotézu lze vyjádřit statisticky.

## Příklad

  Dříve jsme si zmínili výzkum, podle kterého bylo průměrné množství vážných vztahů v dosavadním životě vysokoškolských studentů 3,2.

 Lze říci, že data poskytují dostatečně silný důkaz o tom, že průměrné množství vážných vztahů je vyšší než 3?

Vypočtěte p-hodnotu čili 𝑷(𝑿 ̅≥𝟑,𝟐 ┤| 𝑯_𝟎:𝝁≤𝟑). 

Známe: 𝑛=50; 𝑋 ̅=3,2;𝑠=1,74;𝑆𝐸=0,246 = 1,74/$\sqrt{50}$

A víme, že testová statistika t: 𝑡=(𝑋 ̅−𝜇_0)/𝑆𝐸 

by měla mít při platnosti 𝐻_0 t-rozdělení se stupni volnosti v = n – 1.

Pravděpodobnost pozorovaného nebo extrémnějšího výsledku za předpokladu, že nulová hypotéza platí, čiliP(pozorovaný nebo extrémnější výsledek | H0 platí). 𝑛=50; 𝑋 ̅=3,2;𝜎=1,74;𝑆𝐸=0,246

p-hodnota: 𝑃(𝑋 ̅≥3,2 ┤| 𝐻_0:𝜇=3) 

testová statistika: 𝑡=(3,2−3)/0,246=0,81 
p-hodnota: 𝑃(𝑋 ̅≥3,2 ┤| 𝐻_0:𝜇=3)=𝑃(𝑡_(𝑑𝑓=49)≥0,81)=0,211

Pravděpodobnost pozorovaného nebo extrémnějšího výsledku za předpokladu, že nulová hypotéza platí, čili P(pozorovaný nebo extrémnější výsledek | H0 platí).

[[Vzdělávání/P-hodnota\|P-hodnota]]
## Typy testů

Jednostranné (směrové) testy (one-tailed/directional tests).

#### Oboustranné (nesměrové) testy (two-tailed/nondirectional tests).
 Definice p-hodnot je totožná, ale při výpočtu p-hodnoty musíme zohlednit oba konce výběrového rozdělení.
 
𝑃(𝑋 ̅≥3,2 𝑛𝑒𝑏𝑜 𝑋 ̅≤2,8 ┤| 𝐻_0:𝜇=3) 𝑝–ℎ𝑜𝑑𝑛𝑜𝑡𝑎=𝑃(𝑇_(𝑑𝑓=49)≥0,81)+𝑃(𝑇_(𝑑𝑓=49)≤−0,81)= =2×0,211=0,422

Proč jsou oboustranné testy používanější než jednostranné?

Pro ilustraci: https://rpsychologist.com/d3/nhst/

## Hypotézy ohledně populačního průměru, neznáme-li 𝜎

Předpokládáme náhodný výběr, normalitu populačního rozdělení (nebo dostatečně velký vzorek aby platila centrální limitní věta).. Pokud 𝜇=𝜇_0, pak platí, že testová statistika 𝒕=(𝒙 ̅−𝝁_𝟎)/(𝒔/√𝒏) má Studentovo T-rozdělení se stupni volnosti v = n – 1. Rozhodování na základě p-hodnot: Pokud 𝑯_𝟎:𝝁≥𝝁_𝟎, zamítáme 𝐻_0, když: 𝑃(𝑡_𝑣≤(𝑥 ̅−𝜇_0)/(𝑠/√𝑛))≤α. Pokud 𝑯_𝟎:𝝁≤𝝁_𝟎, zamítáme 𝐻_0, když: 𝑃(𝑡_𝑣≥(𝑥 ̅−𝜇_0)/(𝑠/√𝑛))≤α. Pokud 𝑯_𝟎:𝝁=𝝁_𝟎, zamítáme 
𝐻_0, když: 2×𝑃(𝑡_𝑣≥(|𝑥 ̅−𝜇_0 |)/(𝑠/√𝑛))≤α

#### Příklad
New York je znám jako "město, které nikdy nespí". 35 náhodně vybraných obyvatel New Yorku jsme se zeptali, jak dlouho obvykle spí. Zjistili jsme, že průměr vzorku činil 𝑥 ̅ = 7,73 hodin spánkua s = 0,77. Rozložení bylo pouze mírně levostranně zešikmené. Ověřte nulovou hypotézu H_0: 𝜇=8 na hladině 𝛼=0,05 Nejprve vypočteme standardní chybu: 𝑆𝐸=𝑠∕〖√𝑛=0,77∕〖√35=0,13〗〗 Zjistíme testovou statistiku: 𝑡=(|𝑥 ̅−𝜇_0 |)/𝑆𝐸=0,27/0,13=2,08 Vypočteme p-hodnotu pro oboustranný test (s 𝑣=𝑛−1) 𝑃(𝑇<−𝑡)+𝑃(𝑇>𝑡)=2𝑃(𝑇<−𝑡)=2𝑃(𝑇>𝑡)=0,045

## Shrnutí postupu testování hypotéz ohledně průměru


Stanovíme nulovou a alternativní hypotézu: 𝐻_0:𝜇=𝑛𝑢𝑙𝑙;𝐻_𝐴:𝜇<𝑛𝑢𝑙𝑙 𝑛𝑒𝑏𝑜 𝜇>𝑛𝑢𝑙𝑙 𝑛𝑒𝑏𝑜 𝜇≠𝑛𝑢𝑙𝑙 
Stanovíme hladinu 𝜶: pravděpodobnost chyby I. typu (zamítnutí 𝐻_0, ačkoli platí). Ověříme předpoklady (nezávislost pozorování, dostatečná velikost vzorku vzhledem k tvaru populačního rozdělení). 

Vypočteme testovou statistiku (z nebo t) a s ní spojenou 
p-hodnotu, která udává pravděpodobnost pozorovaného nebo extrémnějšího výsledku (testové statistiky) v případě platnosti nulové hypotézy. 
p-hodnotu porovnáme s hladinou 𝜶, pokud 𝑝<𝛼, zamítáme nulovou hypotézu ve prospěch alternativní, pokud 𝑝>𝛼, ponecháváme nulovou hypotézu. 
Užitečné je také vždy uvádět interval spolehlivosti, abychom vyjádřili nejistotu v odhadu populačního parametru..

## Vztah intervalů spolehlivosti, p-hodnot a hladiny $\alpha$(oboustranné testy)

Protože úroveň spolehlivosti je definována jako 1–α, lze hypotézy ověřovat i na základě intervalů spolehlivosti. Pro oboustranné testy platí následující. 

Pokud 1–α% interval spolehlivosti zahrnuje hodnotu populačního parametru implikovanou nulovou hypotézou, znamená to, že p-hodnota > α, tj. nemůžeme zamítnout H0. Pokud 1–α% interval spolehlivosti NEzahrnuje hodnotu populačního parametru implikovanou nulovou hypotézou, znamená to, že p-hodnota < α, tj. můžeme zamítnout H0. 

Kdybychom například ověřovali 𝐻_0:𝜇=0 na hladině α = 0,05 a 95% CI by nezahrnoval hodnotu 0, znamenalo by to, že p-hodnota < 0,05 Platilo by to i obráceně, pokud by p-hodnota < 0,05, znamenalo by to, že 95% CI pro 𝜇 neobsahuje hodnotu 0.
## Velikost účinku

- velikost účinku (effect size).
	- statistický ukazatel, měří sílu nebo velikost rozdílů nebo vztahu mezi dvěma skupinami, proměnnými nebo podmínkami ve statistické analýze.
	- P-hodnota a statistická významnost se soustředí na to, zda je pozorovaný rozdíl mezi skupinami statisticky významný, velikost účinku se zaměřuje na samostatnou velikost tohoto rozdílu

- statistická vs. praktická významnost.
	- statistická významnost - zda je vztah mezi skupinami, proměnnými stat. významný na základě p-hodnoty a hladiny významnosti. Měří zda máme dostatek důkazů pro zamítnutí nulové hypotézy
	- praktická - skutečný význam tohoto rozdílu pro reálný svět nezávisle na stat. anal. Analýza může zohlednit, jak velký je rozdíl nebo jak moc je výsledek významný z hlediska praktických důsledků. Například malý, statisticky významný rozdíl nemusí být prakticky významný, zatímco velký, ale nesignifikantní rozdíl může být v praxi významný.

- "nestandardizované" vs "standardizované" velikosti účinku.
	- nest. ukazatele účinku jsou v původních jednotkách měření, což znamená, že neprovádějí žádnou standardizaci nebo normalizaci dat.
	- standard. - transformovány do jednotného měřítka, často bezrozměrného, což umožňuje snazší porovnání mezi různými studiemi nebo různými typy dat
