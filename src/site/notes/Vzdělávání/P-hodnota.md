---
{"dg-publish":true,"permalink":"/Vzdělávání/P-hodnota/"}
---


míra, která informuje o míře důvěryhodnosti, s níž můžeme zamítnout nulovou hypotézu ve statistickém testu. Je to pravděpodobnost získání pozorovaného výsledku nebo ještě extrémnějšího výsledku, za podmínky, že nulová hypotéza je skutečně pravdivá. Čím nižší je _p_-hodnota, tím silnější jsou důkazy proti nulové hypotéze.



![](https://i.imgur.com/r45XHjS.png)

P-hodnota říká, že:
máme dostatek důkazů na zamítnutí nulové hypotézy ve prospěch alternativní hypotézy (že existuje rozdíl mezi skupinami nebo že efekt je přítomen).

Neříká, že:
_p_-hodnota sice ukazuje, že existuje statisticky významný rozdíl, ale neříká nám nic o praktické relevanci tohoto rozdílu. Může se jednat o malý, i když statisticky významný, rozdíl mezi skupinami. Také _p_-hodnota neříká nic o příčině nebo síle tohoto rozdílu.

## Použití p-hodnoty

Na základě testové statistiky vypočteme _p_-hodnotu (definici _p_-hodnoty už znáte).

Pokud je _p_-hodnota nižší než stanovené hladina statistické významnosti** **α**, znamená to, že výsledek, který jsme pozorovali, je nepravděpodobný v případě, že nulová hypotéza platí. Říkáme, že data podporují alternativní hypotézu. _Nulovou hypotézu tudíž zamítáme_ (a přijímáme alternativní).

 **Pokud je p-hodnota vyšší než** **α**, znamená to, že pozorovaný výsledek není při platnosti nulové hypotézy natolik nepravděpodobný, abychom mohli zamítnout nulovou hypotézu. Říkáme, že data nepřinesla podporu pro alternativní hypotézu. Proto _nulovou hypotézu nezamítáme, ale ponecháváme_.

 Protože p-hodnota byla vysoká (_p_ = 0,211), vyšší než  
α = 0,05, nezamítáme nulovou hypotézu.

Interpretace p-hodnoty

 Pokud je průměrný počet dosavadních vážných vztahů vysokoškolských studentů roven 3 (tj. kdyby průměr populace byl 3), pak bychom přibližně u 21 % náhodných vzorků o velikosti 50 studentů zjistili průměr 3,2 nebo vyšší.

Tato pravděpodobnost je docela vysoká. Jinými slovy průměr 3,2 může být způsoben pouhou **výběrovou variabilitou**.

Průměr vzorku 3,2 nebo více není nijak nepravděpodobný,  
i kdyby byl populační průměr = 3.

 Rozhodnutí

  Protože _p_-hodnota je vysoká (vyšší než 0,05),  
nezamítáme H0.

Data neposkytují dostatečně silný důkaz o tom, že vysokoškolští studenti mají v průměru více než 3 vážné vztahy.

Rozdíl mezi očekávanou hodnotou při platnosti nulové hypotézy (v průměru 3 vztahy) a pozorovaným průměrem vzorku (3,2 vztahy) může být způsoben pouhou náhodou (výběrovou variabilitou).

## Správná interpretace p-hodnot
[[Vzdělávání/P-hodnota\|P-hodnota]]

Dejme tomu, že ověřujeme nulovou hypotézu o rozdílech mezi průměry a zjistíme  
a dospějeme k _p_-hodnotě _p_ = 0,021.

Jaká je korektní interpretace tohoto výsledku? Co nám tato pravděpodobnost říká a neříká?

naznačuje, že existují důkazy o rozdílech mezi skupinami, ale nemáme informace o velikosti nebo významu tohoto rozdílu.

## P-hodnota závisí

1. **Velikost rozdílu mezi vzorkem a hypotetickou hodnotou:** Čím větší je rozdíl mezi vzorkem a hodnotou specifikovanou nulovou hypotézou (𝑋 ̅−𝜇_0), tím menší p-hodnota.
    
2. **Velikost standardní odchylky 𝜎:** Pokud je standardní odchylka velká, bude rozsah dat širší, což může vést ke zvýšení p-hodnoty, a naopak, pokud je malá, může to vést ke snížení p-hodnoty.
    
3. **Velikost vzorku 𝑛:** Čím větší je vzorek, tím přesnější bude odhad, což může snížit standardní chybu (SE). Malá standardní chyba obvykle vede k nižším p-hodnotám, protože malá variabilita ve vzorku znamená větší jistotu výsledků.
    
4. **Populační distribuce:** Pokud je populační distribuce šikmá nebo špičatá, může to ovlivnit tvar distribuce vzorku a tím i výpočet p-hodnoty.
    

Je důležité brát v úvahu všechny tyto faktory při interpretaci p-hodnoty, protože malá p-hodnota není vždy rovnocenná s velkým praktickým efektem nebo skutečným rozdílem v datech.

# Výpočet
Zskor https://www.socscistatistics.com/pvalues/normaldistribution.aspx
Tskor https://www.socscistatistics.com/pvalues/tdistribution.aspx
Chi-square https://www.socscistatistics.com/pvalues/chidistribution.aspx



# Tabulka [[Vzdělávání/Z skor a Z test\|Z skor a Z test]]
https://www.ztable.net/
# Tabulka T distributation table a [[Vzdělávání/T test\|T test]]
https://www.tdistributiontable.com/

## Kdy použít jaký
![](https://i.imgur.com/NkrCJnG.png)
