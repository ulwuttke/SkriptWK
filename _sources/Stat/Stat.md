# Auswerung

## Definition statistischer Größen 

|  |  |  |
| :-- | :-- | :-- |
| Mittelwert | arithmetisches Mittel | $\bar{x}=\frac{1}{n}\sum\nolimits_{i=1}^{n} x_i$ |
| Median | "der Wert in der Mitte" von nach der Größe geordneten Messerten | $\tilde{x}=\left \{\begin{array}{cl} x_{(n+1)/2},& \text{ n ungerade}\\ 1/2(x_{n/2}+x_{(n/2+1)}),& \text{ n gerade} \end{array}\right.$ |
| Spannweite |  | $r=x_{max}-x_{min}$ |
| relative Spannweite |  | $r_{rel}=r/\bar{x}$ |


## Beispiele

### Beispiel 1 

Beispiel in Anlehnung an die DIN EN ISO 6506-2 Abshcnitt 5 bzw. DIN EN ISO 6507-2 Abschnitt 5 

Härtewerte als Ergebnis der Härteprüfung nach DIN EN ISO 6507-1 mit 5 Eindrücken:
|  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: |
| 212 HV10 | 190 HV10 | 194 HV10 | 210 HV10 | 199 HV10 |


Härtewerte nach der Größe sortiert:
|  |  |  |  |  |  |
| :--:  | :--: | :--: | :--: | :--: | :--: |
| i | 1 | 2 | 3 | 4 | 5 |
| Härte | 190 HV10 | 194 HV10 | 199 HV10 | 210 HV10 | 212 HV10 |


Mittelwert: 

$\bar{x}=\bar{H}=(190+194+199+210+212)/5=201 \text{ HV10}$

Median:
|  |  |  |  |  |  |
| :--:  | :--: | :--: | :--: | :--: | :--: |
| i | 1 | 2 | 3 | 4 | 5 |
| Härte | 190 HV10 | 194 HV10 | **199 HV10** | 210 HV10 | 212 HV10 |

$\tilde{x}=\tilde{H}=199 \text{ HV10}$

Spannweite:

$r=212-190=22 \text{ HV10}$

relative Spannweite:

$r_{rel}=22/201= 0,109 = 10,9\text{ %}$


### Beispiel 2 

Beispiel für den Median bei einer geraden Anzahl von Messwerten

Ergebnis der Zugfestigkeit als Ergenis die Zugversuchs nach DIN EN ISO 6892-1 an 4 Zugproben 
|  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: |
| $R_m$ in MPa | 370 | 377 | 372 | 375 |


Werte nach der Größe sortiert:
|  |  |  |  |  |
| :--:  | :--: | :--: | :--: | :--: |
| i | 1 | 2 | 3 | 4 |
| $R_m$ in MPa  | 370 | 372 | 375 | 377 | 


Median:
|  |  |  |  |  |
| :--:  | :--: | :--: | :--: | :--: |
| i | 1 | 2 | 3 | 4 |
| $R_m$ in MPa  | 370 | **372** | **376** | 377 | 

$\tilde{x}=\tilde{R}_m=1/2 \cdot (372+376)\text{MPa} = 374\text{MPa}$


