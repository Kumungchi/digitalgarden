---
{"dg-publish":true,"permalink":"/Vzdělávání/Statistika 11. hodina Spojité vs kategorické/"}
---


 Spojité vs. kategorické proměnné - zajímají nás četnosti

Chí-kvadrát: typ pravděpodobnostního rozdělení; 
test, který toto rozdělení využívá.
- nezávislost dvou kategorických proměnných

Vzorec CHkv
$$f(\chi^{2})=\frac{1}{2^{\frac{k}{2}}\Gamma(k/2)}\chi^{2[(k/2)-1]}e^{\frac{-(x^{2})}{2}}$$



## Test dobré shody chí kvadrát (jedno-výběrový test chí-kvadrát)

•Zaznamenáme si pozorované četnosti.

• Vypočteme si četnosti očekávané (jaké četnosti bychom očekávali za předpokladu, že platí nulová hypotéza).

•Vypočteme čtverce rozdílů pozorovaných a očekávaných četností dělené očekávanými četnostmi.

•Sečteme výsledky přechozí operace a tím získáme testovou statistiku χ2.

•Vypočteme stupně volnosti _df_ (počet kategorií (n) – 1).

•Zjistíme pravděpodobnost pozorované nebo extrémnější testové statistiky  
v χ2-rozdělení s _df_ stupni volnosti.


Anglicky chi-square test of independence nebo chi-square test of homogeneity

ověřuje nezávislost dvou kat. pr.

Vzorec
$$\chi^{2}=\sum\frac{(O-E)^{2}}{E}$$
## Přehled předpokladů
- kategorické proměnné
- nezávislá pozorování
- Kategorie (nebo buňky v kontingenční tabulce) jsou vzájemně výlučné
- Očekávané četnosti by měly být aspoň 5 či více pro 80 % buněk a žádná očekávaná četnost by neměla být nižší než 1

## Nízké četnosti a jejich řešení

Sloučení některých kategorií (pokud takové sloučení dává smysl).

 Yatesova korekce kontinuity (Yates' continuity correction).

Fisherův exaktní test (Fisher exact test).

Simulace výběrového rozdělení.


## Více než 2 kategorie (4 x 2)
Jankowski, M. K., Leitenberg, H., Henning, K., & Coffey, P. (2002). Parental caring as a possible buffer against sexual revictimization in young adult survivors of child sexual abuse. _Journal of Traumatic Stress_, 15(3), 235–244. https://doi.org/10.1023/A:1015259412746

## Opakovaná měření
- McNemarův test


## Je chí-kvadrát jednostranný, nebo oboustranný test?
- Záleží na úhlu pohledu
- Jedno - sledujeme jeden konec distribuce
- Obou - nezohledňuje směr rozdílu (mezi pozorovanými a očekávanými četnostmi)



## Test poměru věrohodností (likelihood ratio test)
- Další způsob, jak analyzovat kategorická data
- Výhody: “Aditivní” povaha (analýza vztahů mezi více než dvěma kategorickými pr.)


Vzorce

$$\chi_{(c\!-\!1)}^{2}=2\sum{\cal O}_{i}\ln\left(\frac{{\cal O}_{i}}{E_{i}}\right)$$

$$\chi_{(R-1)(C-1)}^{2}=2\sum{\cal O}_{i j}\ln\left(\frac{{\cal O}_{i j}}{E_{i j}}\right)$$


## Mantel-Haenzelův test
- Hodí se pro případy, kdy chceme kontrolovat efekt nějaké třetí proměnné.
- Např. ověřit vztah mezi stresem (nízký/vysoký) a pracovní spokojeností (nízká/vysoká) mezi pracovníky různých firem (prostředí jako třetí proměnná)

Vzorec
$$M^{2}=\frac{(|\Sigma{\cal O}_{11k}-\,\Sigma E_{11k}|-\,\frac{1}{2})^{2}}{\sum n_{1\,+\,k}n_{2\,+\,k}n_{+\,1k}n_{+\,2k}/n_{+\,+\,k}^{2}(n_{++k}-\,1)}$$


## Velikost účinku
Kromě statistické významnosti je zapotřebí posoudit i praktickou významnost (velikost účinku).

**_d_****-family** (measures of differences): "rozdílové" velikosti účinku  
(vycházející z míry rozdílu mezi skupinami).

**_r_****-family** (measures of associations): "korelační" velikosti účinku  
(vycházející těsnosti vztahu mezi proměnnými)

### Příklad
- Kohortové studie (cohort study)
- Prospektivní (prospective) vs retrospektivní studie (retrospective study)
- Případová kontrolní studie (case-control study)
- Randomizovaná klinická zkouška (randomized clinical trial)
- Jednoduše zaslepená (single-blind) nebo dvojitě zaslepená (douuble-blind) studie

## Velikosti účinku

_d_-measures:

Riziko (risk), **rozdíl rizik** (risk difference) a **poměr rizik/relativní riziko** (risk ratio/relative risk).

Šance (odds) a **poměr šancí** (odds ratio).

_r_-measures:

Fí-koeficient (ϕ, phi-coefficient)

Cramérovo _V_ (Cramér's _V_).


Vzorce

$$\phi=\sqrt{\frac{\chi^{2}}{N}}$$


$$O R={\frac{O d d s\,|\,N o A s p i r i n}{O d d s\,|\,A s p i r i n}}={\frac{0.0174}{0.0095}}=\,1.83$$

$$V=\sqrt{\frac{\chi^{2}}{N(k-1)}}$$


## Shoda posuzovatelů
- Podíl shodných hodnocení
- Cohenovo kappa ($\kappa,Cohen´s kappa$)


$$\kappa=\frac{\sum\!f_{O}-\sum\!f_{E}}{N-\sum\!f_{E}}$$





