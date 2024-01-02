---
{"dg-publish":true,"permalink":"/Vzdělávání/Statistika 6. hodina Korelace/"}
---


[[Vzdělávání/Statistika 5. hodina Bivariační analýza\|Statistika 5. hodina Bivariační analýza]]

test hlavně teorie
směrodatné odchylky
míry variability
výpočet nebo odvození z výpočtu

Pearsonův korelační koeficient
Pokud jsou kladné odchylky od průměru u X spojeny s kladnými odchylkami u Y, a záporné se zápornými, součin je kladný
$$r = \frac{\sum{(x_i - \bar{x})(y_i - \bar{y})}}{\sqrt{\sum{(x_i - \bar{x})^2} \sum{(y_i - \bar{y})^2}}}
$$

| x   | y   | x.y | x2  | y2  |
| --- | --- | --- | --- | --- |
| 4   | 3   | 12  | 16  | 9   |
| 6   | 1   | 6   | 36  | 1   |
| 8   | 4   | 32  | 64  | 16  |
| 5   | 4   | 20  | 25  | 16  |
| 6   | 2   | 12  | 36  | 4   |
| 6   | 4   | 24  | 36  | 16  |
| 10  | 6   | 60  | 100 | 36  |
| 9   | 5   | 45  | 81  | 25  |
| 6   | 7   | 42  | 36  | 49  |
| sum 60  | sum 36  | sum 253 | sum 430 | sum  172  |
9* 253-60* 36/odm.(9* 430- 60na2)* (9* 172 - 36n2)
r = 0,54935, nebo 0,45 zkontrolovat
Bezrozměrné číslo (poměr kovariace a směrodatných odchylek obou proměnných), -1 značí deterministickou negativní, +1 deterministickou pozitivní závislost

Koeficient pořadové korelace (Spearmanův)
Nahradíme každou hodnotu proměnné jejím pořadím a z pořadí spočítáme korelační koeficient. Lze užít výpočetní tvar
$$\rho = 1 - \frac{6\sum (x_i - y_i)^2}{n(n^2 - 1)}
$$

V závorce je diference v pořadí

rs= 0,525

| x   | y   | xpoř. | ypoř. | x-y  | (x-y)2 |
| --- | --- | ----- | ----- | ---- | ------ |
| 4   | 3   | 1     | 3     | -2   | 4      |
| 6   | 1   | 4,5   | 1     | 3,5  | 12,25  |
| 8   | 4   | 7     | 5     | 2    | 4      |
| 5   | 4   | 2     | 5     | -3   | 9      |
| 6   | 2   | 4,5   | 2     | 2,5  | 6,25   |
| 6   | 4   | 4,5   | 5     | -0,5 | 0,25   |
| 10  | 6   | 9     | 8     | 1    | 1      |
| 9   | 5   | 8     | 7     | 1    | 1      |
| 6   | 7   | 4,5   | 9     | -4,5 | 20,25  |



Kendallovo tau

Korespondence mezi pořadím případů podle hodnot proměnné x a y 

Konkordantní dvojice platí že xi > xa pak yi>ya a když xi< xa pak yi < ya
to znm. taková dvojice, kterou bychom seřadili podle hodnot x stejně jako podle proměnné y
Diskordantní dvojice
když xii > xaa, pak yii< yaa, a když xii< xaa, pak yii >yaa
taková dvojice, kterou bychom seřadili podle hodnot x opačně než podle hodnoty proměnné y

Ta=počet konk. - počet diskord./Celkový počet dvojic


Ta=nkk - nd/1/2 x n x(n-1)

Nevýhoda je, že tau-a nebere v potaz shodné hodnoty (tied values, ties), tj. když xi = xa nebo yi = ya

36 dvojic 

| x   | y   |
| --- | --- |
| 4   |  3   |
| 6   |   1  |
| 8   |   4  |
| 5   |    4 |
| 6   |    2 |
| 6   |    4 |
| 10  |    6 |
| 9   |    5 |
| 6    |   7  |

21 
7

Ta= 21-7/36
Ta = 0,388….

Korespondenci mezi pořadím případů podle hodnot proměnné x a y 