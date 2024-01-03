---
{"dg-publish":true,"permalink":"/Vzdělávání/Četnost/"}
---


[[Vzdělávání/Statistika 2. hodina Deskriptivní statistika\|Statistika 2. hodina Deskriptivní statistika]]
## Četnost
jak často se ve statistickém souboru vyskytuje určitá hodnota znaku.
Pokud znak = dichotomický (alternativní, vyjadřuje přítomnost určité vlastnosti - má hodnoty ano ne) četnost vyjadřujeme jako n<sub>i</sub> znaku i
## Absolutní četnost (f)
kolikrát se ve statistickém souboru vyskytuje určitá hodnota daného znaku tedy počet výskytů této hodnoty znaku.

## Relativní četnost (rf)
vztažená k celkovému počtu prvků souboru (_rozsahu souboru_). Má hodnotu v intervalu⟨ 0 , 1 ⟩ neboli 0 až 100 %. Relativní četnost se někdy nazývá **empirická pravděpodobnost**.

Relativní četnost i-tého znaku _fi_ se vypočte pomocí vzorce

## Příklad

Máme celkem 109 vzorků, což je absolutní četnost. Relativní četnost je tedy 100 %. Typ vzorku A se v celkovém počtu vzorků vyskytl 81krát, čili relativní četnost se vypočítá 81 / 109 = 74 %. Typ vzorku A má tedy relativní četnost 74 %. Stejně tak se postupuje i u typu vzorku B.[](https://www.wikiwand.com/cs/%C4%8Cetnost#cite_note-2)

|Vzorek|Absolutní četnost|Relativní četnost|
|---|---|---|
|celkem vzorků|109|100 %|
|typ vzorku A|81|74 %|
|typ vzorku B|61|56 %|

Vzhledem k tomu, že součet relativních četností typu A a B je větší než 100 %, je zřejmé, že některé vzorky patří do obou typů.

$$f_{i}={\frac {n_{i}}{N}}={\frac {n_{i}}{\sum _{i}n_{i}}}$$

## Kumulativní četnost
**je postupně načítaná četnost jednotlivých vzestupně uspořádaných hodnot**
Vedle sloupečku s absolutní četností výsledných známek můžeme zobrazit ještě jeden sloupeček s kumulativní četností. Prohlédněte si následující tabulku:

|Známka|Počet žáků|Kumulativní četnost|
|---|---|---|
|Výborně|7|7|
|Chvalitebně|13|20|
|Dobře|6|26|
|Dostatečně|3|29|
|Nedostatečně|1|30|

Ve druhém řádku máme ve sloupci kumulativní četnost hodnotu 20. Tu jsme získali tak, že jsme sečetli hodnoty počty žáků v prvním a ve druhém sloupci, tedy 7 + 13 = 20. Ve třetím řádku tak máme kumulativní četnost 26, protože 7 + 13 + 6 = 26. Jinýmy slovy jsou to součty četností všech řádků, které jsou výše než současný řádek plus hodnota z aktuálního řádku.

Na prvním řádku tak bude kumaltivní četnost shodná s absolutní četností, na posledním řádku bude kumulativní četnost rovna velikosti celé populace (ve třídě je třicet žáků).

Můžeme také spočítat kumulativní relativní četnosti:

|Známka|Relativní četnost|Kumulativní relativní četnost|
|---|---|---|
|Výborně|0,2333|0,2333...|
|Chvalitebně|0,4333|0,6666...|
|Dobře|0,2|0,86666...|
|Dostatečně|0,1|0,96666...|
|Nedostatečně|0,0333|1|

V prvním řádku opět máme u kumulativní relativní četnosti stejnou hodnotu jako ve sloupečku Relativní četnost. V posledním máme 1, což znamená 100 % populace.