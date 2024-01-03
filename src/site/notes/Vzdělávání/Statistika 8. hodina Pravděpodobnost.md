---
{"dg-publish":true,"permalink":"/Vzdělávání/Statistika 8. hodina Pravděpodobnost/"}
---


Mgr. Rečka
datová matice
codebook - jméno pr., popis a co znamenají jejich hodnoty



# Pravděpodobnost

Náhodný pokus

**Jev** (událost) lze přibližně chápat jako hodnoty proměnných (Petr měří 180 cm / má IQ 130 / je dyslektik).

**Výběrový prostor** (pole jevů): množina hodnot, kterých může proměnná nabývat.

**Náhodný pokus** je proces, jehož možné výsledky (výběrový prostor) známe, ale nevíme, který z nich nastane (výběr a změření člověka, hod kostkou).


## Pojmy z pravděpodobnosti

–  _Náhodným pokusem získáváme z výběrového prostoru konkrétní jev (realizace)._

 **Náhodná proměnná** vzniká opakováním náhodného pokusu.



Pravděpodobnost je matematickým vyjádřením, modelem **nejistoty.**

Nejistota je **subjektivní** nedostatek informací

_P_(A) = Pravděpodobnost jevu A

Existují několik možných výkladů pravděpodobnosti, ale všechny z nich se shodují na tom, že:

$$0<-P(A)<-1$$
 Pravděpodobnost

 **Frekventistické pojetí**: Pravděpodobnost jevu je relativní četnost toho, kolikrát by daný jev nastal, pokud bychom mohli pozorovat náhodný proces nekonečněkrát.

$$0<-P(A)<-1=\frac{n(A)}{N}$$
blíží-li se počet pokusů nekonečnu  
(_n_ je četnost jevu a _N_ počet pokusů).

**Analytické řešení** – pokud víme, že všechny prvky výběrového prostoru mají stejnou pravděpodobnost:  
$$P(A)=\frac{1}{N}$$
kde _N_ je počet prvků výběrového prostoru.

**Bayesiánská pojetí**: pravděpodobnost jako subjektivní míra přesvědčení/jistota, míra podpořenosti důkazy.

Zákon velkých čísel

Podle **zákona velkých čísel** platí, že čím více pozorování získáme, tím přesnější bude odhad pravděpodobnosti určitého jevu na základě empirické relativní četnost daného jevu.

Jaká je pravděpodobnost, že na 6stěnné kostce padne 5? (analyticky)  
_1/6 = 0,16666_

Hody mincí

Dejme tomu, že 10 hodíte mincí a pokaždé padne panna. Jaká je pravděpodobnost, že při dalším, 11. hodu padne opět panna? 0,5, méně než 0,5, méně než 0,5?

Hody mincí

Dejme tomu, že 10 hodíte mincí a pokaždé padne panna. Jaká je pravděpodobnost, že při dalším, 11. hodu padne opět panna? 0,5, méně než 0,5, méně než 0,5?

Pravděpodobnost je stále 50 %

-        _P_(panna při 1. hodu) = _P_(panna při 10. hodu) = 0,50

-         Mince nikomu "nedluží", že by měl konečně padnout "orel".

-        Hody jsou vzájemně nezávislé; předchozí hody neovlivňují následné hody.

-      Nepochopení zákona velkých čísel – **klam hazardního hráče**.

## Šance

 I když se v běžném jazyce pojmy pravděpodobnost a šance často zaměňují a považují za synonyma, ve statistice mezi nimi děláme rozdíl.

**Šance (odds, O)** je poměr pravděpodobnosti, že nějaký jev nastane, vůči pravděpodobnosti, že nenastane:

$$O(A)=\frac{P(A)}{P(neA)}= \frac{P(A)}{1-P(A)}$$



 Šance se může pohybovat od nuly do nekonečna:  $O \in \langle 0, \infty \rangle$
 
Příklad: pokud je pravděpodobnost uzdravení 90%, znamená to šanci

$$O(A)=\frac{0,9}{(1-0,9)}=9$$

neboli 9 ku 1

**Poměr šancí (odds ratio, OR)** je obvyklý způsob srovnání šancí ve  
2 skupinách.

OR<sub>12</sub>$=\frac{O_1}{O_2}$


## Neslučitelné jevy a obecné součtové pravidlo

 Neslučitelné (vzájemně výlučné, disjunktní) jevy,  
obecné součtové pravidlo,

 výběrový prostor,

  rozdělení pravděpodobnosti (pravděpodobnostní distribuce),

opačné (doplňkové, komplementární) jevy

**(Vzájemně) neslučitelné/výlučné jevy**

Neslučitelné jevy jsou jevy, které nemohou nastat zároveň.

 Při jednom hodu mincí nemůže padnou panna a zároveň orel.

 Student nemůže zároveň úspěšně  
a neúspěšně vykonat zkoušku.

 1 karta vytažená z balíčku nemůže být zároveň eso a královna.

 **P(A** ∩ **B) = 0;** ∩ znamená konjunkci (A a zároveň B)

 **(Vzájemně) slučitelné/ nevýlučné jevy**

Slučitelné jevy mohou nastat zároveň.

Student může dostat A z Obecné psychologie a F ze statistiky.

 **P(A** ∩ **B)** **>** **0**

Sjednocení (disjunkce) výlučných jevů

 Sjednocení (disjunkce) se značí ∪ (můžeme číst jako "nebo")

Jaká je pravděpodobnost, že z dobře promíchaného balíčku hracích karet vytáhneme J nebo trojku?

$$P(K \cup 3)=P(J)+P(3)=\frac{4}{52}+\frac{4}{52}\approx0,154$$

Pro vzájemně výlučné jevy A a B platí:

**P (A nebo B) = P(A) + P(B)**

Sjednocení (disjunkce) slučitelných jevů

Jaká je pravděpodobnost, že z dobře promíchaného balíčku hracích karet vytáhneme J nebo kartu červené barvy (srdce, káry)?

$$P(Jnebo červená)= P(K)+P(č.)-P(K a č.)=\frac{4}{52}+\frac{26}{52}-\frac{2}{52}\approx0,538$$

Pro slučitelné jevy A a B platí:

P(A nebo B) = P(A) + P(B) - P(A a B)


**Obecné součtové pravidlo**

𝑷(𝑨 𝒏𝒆𝒃𝒐 𝑩)=𝑷(𝑨)+𝑷(𝑩)−𝑷(𝑨 𝒂 𝑩)

V případě neslučitelných jevů je P(a a B) = 0, takže lze rovnici zjednodušit na: P(A nebo B) = P(A) + P(B)

Příklad: Pravděpodobnost toho, že náhodně vybraný člověk má základní vzdělání nebo je vyučen.

**Výběrový prostor**

Výběrový prostor je souborem všech možných výsledků náhodného pokusu.

Příklad: muž a žena mají dvě děti, jaký je výběrový prostor pohlaví těchto dětí? Pro zjednodušení předpokládejme, že existují pouze dvě pohlaví – muž a žena.

𝑆={𝑀𝑀, ŽŽ, Ž𝑀,𝑀Ž}

**Rozdělení pravděpodobnosti**

Rozdělení  pravděpodobnosti zahrnuje všechny možné výsledky, které obsahuje výběrový prostor, a každému z nich přiděluje určitou pravděpodobnost.

**Komplementární (doplňkové) jevy**

Komplementární jevy jsou dva výlučné jevy, jejichž součet pravděpodobnostní se rovná jedné.

𝑷(𝑨 𝒂 𝑩)=𝟎;    𝑷(𝑨)+𝑷(𝑩)=𝟏

(malá odbočka: šance je poměr pravděpodobností dvou komplementárních jevů)

Neslučitelné vs. komplementární jevy

Je součet pravděpodobnostní dvou neslučitelných jevů vždy roven 1?

–  Ne vždy. Výběrový prostor mohou tvořit více než 2 neslučitelné jevy.

Je součet pravděpodobnostní dvou komplementární jevů vždy roven 1?

–  Ano, taková je totiž jejich definice. (Ale součet pravděpodobnostní neslučitelných jevů nemusí být nutně roven 1)

Všechny komplementární jevy jsou neslučitelné, ale ne všechny neslučitelné jevy jsou komplementární.

**Nezávislost**


Dva náhodné pokusy jsou nezávislé, pokud výsledek jednoho z nich neposkytuje žádné užitečné informace o výsledku druhého z nich.

Nezávislost

Dva procesy jsou nezávislé, pokud výsledek jednoho z nich neposkytuje žádné užitečné informace o výsledku druhého z nich.

Vztahy mezi proměnnými

Ověření nezávislosti

Pro **nezávislé jevy** platí, že

–  **podmíněná pravděpodobnost** jevu A, platí-li B (podmínka), je stejná, jako prostá pravděpodobnost A (nezohledňující jev B):

**_𝑷(𝑨|B)=𝑷(𝑨)_**

–  **sdružená pravděpodobnost** jevu A a B je rovna součinu jednotlivých pravděpodobností jevu A a jevu B.

𝑷(𝑨 𝒂 𝑩)=𝑷(𝑨)×𝑷(𝑩)

Po **závislé jevy** tedy platí naopak:  
**_𝑷(𝑨|B)_****_≠_****_𝑷(𝑨)_***𝑷(𝑨 𝒂 𝑩)****_≠_****𝑷(𝑨)×****𝑷(𝑩)***


>[!tip]+ Příklad
>V roce 2013 proběhl v Severní Karolině v USA průzkum, který se dotazoval na názor respondentů ohledně držení zbraní? Chrání liberální zákony ohledně držení zbraní bezúhonné občany, nebo naopak ohrožují bezpečnost ve společnosti? Že tyto zákony chrání občany uvedlo:
>
>_58 % všech respondentů,_
>
>_67 % bělochů,_
>
 >_28 % černochů,_
>
 >_a 64 % Hispánců._
 >
>Názor na držení zbraní a etnická příslušnost jsou:  
a) komplementární, b) vzájemně výlučné, c) nezávislé,  
<mark style="background: #FFB8EBA6;">d) závislé</mark>, e) disjunktní.


**Posouzení nezávislosti na základ dat ze vzorku**

Pozorujeme-li rozdíl mezi podmíněnými pravděpodobnostmi, nasvědčuje to závislosti mezi proměnnými – musíme ale provést test této hypotézy (na úrovni populace nemusí rozdíl existovat)

Ale pokud je pozorovaný rozdíl velmi výrazný, jedná se o silný důkaz toho, že tento rozdíl je "skutečný" – že existuje i na úrovni populace.

Pokud je náš vzorek obrovský, pak i malý rozdíl může být dostatečným důkazem o rozdílu na úrovni populace.

Součinové pravidlo pro nezávislé jevy

Jsou-li jevy A a B nezávislé, pak platí, že  jejich sdružená pravděpodobnost je rovná součinu jednotlivých pravděpodobností jevu A a jevu B:

**_𝑷𝑨 𝒂 𝑩=𝑷(𝑨)×𝑷(𝑩)

Když učiníme 2 hody mincí, jaká je pravděpodobnost, že dvakrát za sebou padne panna?

$$P(p1\;ap\;2)=P(p1)\times P(p2)=\frac{1}{2}\times \frac{1}{2}= \frac{1}{4}$$

Obecně, pokud jsou jevy A<sub>1</sub>, A<sub>2</sub>… až A<sub>k</sub> nezávislé, platí:

$$P(A_1aA_2....A_k)=P(A_{1)})\times P(A_{2)}) \times ..... P(A_k)$$



Obecné součtové pravidlo:  
$$P(A\; a\; \;B)= P(A) \times P(B)$$

Bayesova věta

Podle Bayesovy věty platí, že podmíněná pravděpodobnost jevu A při B je rovna sdružené pravděpodobnosti jevů A a B dělené (marginální) pravděpodobností jevu B:  

$$P(A|B)=\frac{P(A\;a\;B)}{P(B)}$$


Násobíme-li obě strny P(B), dostaneme součinové pravidlo:

$$P(A\;a\;B)=P(A|B)\times P(B)$$
Nezávislost a podmíněné pravděpodobnosti
- Obecně platí, že pokud P(A|B)= P(A), pak jsou jevy A a B nezávislé
	- Logicky Známe-li B nezpřesňuje to informace o P(A)
	- Matematicky pokud jsou oba jevy nezávislé, tedy pokud P(A a B) = P(A)x P(B), pak platí
	- $$P(A \mid B) = \frac{P(A\; a\; B)}{P(B)} = \frac{P(A) \times P(B)}{P(B)} = P(A)
$$


# Pravděpodobnost doplnění
$$p=\frac{A}{A+B}$$
marginální P(a)
společná P(a,b) P(A a B)
podmíněná P(A|B, C …)






