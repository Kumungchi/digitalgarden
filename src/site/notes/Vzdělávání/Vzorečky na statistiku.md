---
{"dg-publish":true,"permalink":"/Vzdělávání/Vzorečky na statistiku/"}
---

# Deskriptivní
## Průměr
$$\bar{x} = \frac{\sum_{i=1}^{n} x_i}{n}$$
## Medián pro nepárový počet bodů
$$ x= {\frac {n+1}{2}}$$
## Pro sudý počet datových bodů


$$\text{Median} = \frac{x_{\frac{n}{2}} + x_{\frac{n}{2} + 1}}{2}$$

## Rozptyl

$$\sigma^2 = \frac{1}{n} \sum_{i=1}^{n} (x_i - \mu)^2
$$
## Směrodatná odchylka

$$\sigma = \sqrt{\frac{1}{n} \sum_{i=1}^{n} (x_i - \mu)^2}
$$
## Personův Korelační koeficient
$$\rho = \frac{\sum_{i=1}^{n} (x_i - \bar{x})(y_i - \bar{y})}{\sqrt{\sum_{i=1}^{n} (x_i - \bar{x})^2} \sqrt{\sum_{i=1}^{n} (y_i - \bar{y})^2}}
$$
## Spermanův korelační koeficient
$$r = 1 - \frac{6\sum{d_i^2}}{n(n^2-1)}
$$
# Inferenční
## Regresní rovnice

$$Y = \beta_0 + \beta_1X
$$

## Binomický rozdělovací vzorec
$$P(X = k) = \binom{n}{k} p^k (1-p)^{n-k}
$$
## Normální rozdělovací fce (Gausova funkce)
$$f(x) = \frac{1}{\sigma \sqrt{2\pi}} e^{ -\frac{1}{2} \left(\frac{x-\mu}{\sigma}\right)^2 }
$$

- f(x) je hodnota normální rozdělovací funkce při hodnotě x,
- μ je střední hodnota (průměr) normálního rozdělení,
- σ je směrodatná odchylka normálního rozdělení,
- e  je Eulerovo číslo (přibližně 2,71828).
Variace vzorce

$$f(x) = \frac{1}{\sigma \sqrt{2\pi}} e^{ -\left(\frac{(x-\mu)^2}{2\sigma}\right)}
$$



## Z skor
$$Z=\frac{x- \mu }{\sigma}$$