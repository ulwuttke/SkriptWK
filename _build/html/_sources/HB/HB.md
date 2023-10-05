

# Brinell

(ueber)=
## Übersicht Prüfung

| [Härteprüfung nach Brinell](https://de.wikipedia.org/wiki/H%C3%A4rte#Brinell) | DIN EN ISO 6507-1:2015-02 |
| ----------- | ----------- |
| [Prüfkörper](probe) | Glatte ebene Prüffläche, Mindestdicke $8\cdot\textit{Eindringtiefe}$
| Eindringkörper | Kugel mit $D=1; 2,5; 5; 10 \text{ mm}$ aus Hartmetall (früher auch gehärteter Stahl)|
| [Prüfkraft](pk) | Je nach Werkstoff und Kugeldurchmesser zwischen 9,807 N und 29,420 kN, definiert über den Beanspruchungsgrad |
| Position Eindruck | (fast) frei wählbar; Rand und Lochabstände beachten (vgl. DIN EN ISO 6507-1 Abschn. 8.8) |
| Ablauf | 1. belasten in $7^{+1}_{-5}$ s, 2. halten (Einwirkdauer) $14^{+1}_{-4}$ s (bei abweichender Zeit mit anzugeben), 3. komplett entlasten |
| [Ausmessen des Eindrucks](eindr)  | Eindruckdiagonalen $d_1$ und $d_2$| 
| [Berechnung des Härtewertes](ber) | Brinell-Härte $= 0,102\cdot\frac{2F}{\pi{} D^2(1-\sqrt{1-d^2/D^2})}$, $F$ in N, $d=\frac{d_1+d_2}{2}$ in mm |
| [Angabe des Wertes](wert) | *Zahlenwert* **HBW** *Kugeldurchmesser* **/** *Prüfkraft in kgf* **/** *ggf. Haltezeit in s*, z.B. 133 HBW 1/30/20, 120 HBW 2,5/62,5| 

(probe)=
## Prüfkörper

Die Prüfung muss an einer glatten une ebenen Oberflächer vorgenommen werden. 
Die Dicke der Probe muss mindestens das 8-Fache der Eindringtiefe betragen. 

$\textit{Mindestdicke}=8\cdot h=8\cdot\frac{D}{2}(1-\sqrt{1-d^2/D^2})$

bzw. (bei einer vorhandenen Probe) die maximal zu verwendende Prüfkraft $F_{max}$ zu

$F_{max}=\textit{"HV"}\cdot d^{2} / 0,1891 = \textit{"HV"}\cdot (\textit{Probendicke}/1,5)^{2} / 0,1891 \cdot 1\text{N}/(1\text{mm}^2)$


[Übersicht](ueber) 


(pk)=
## Prüfkräfte

Die Prüfkräfte sind so zu wählen, dass der Eindruckdurchmesser zwischen den Werten 0,24 D 0,6 D liegt. Dies wird i.A. durch die Wahl der Prüfkraft anhand des Beanspruchungsgrades $(=0,102\cdot F/D^2)$ erreicht, der für bestimmte Härteniveaus bzw. typische Werkstoffe in der DIN EN ISO 6506-1 definiert ist:

|Werkstoff| Brinellhärte|Beanspruchungsgrad|
| ----------- | ----------- |----------- |
|Stahl, Nickel- und Titanleg.| |30|
|Gusseisen |$<140$ |10 |
| |$\geq140$ | 30 |
|Kupfer, -leg.|$<35$ | 5 |
| | $35$ bis $200$  | 10 |
| |  >$200$ | 30 |
| Leitmetalle, -leg. | $<35$ | 2,5 |
| | $35$ bis $80$ / >$80$ | 5/10/15|
| | >$80$ | 10/15 |
|Blei, Zinn| | 1 |

Für einen einen Kugeldurchmesser von $D=2,5\text{ mm}$ ergeben sich damit je nach Beanspruchungsgrad über die Gleichung

$F=\frac{\text{Beanspruchungsgrad}\cdot D^2}{0,102}$

 die folgenden Prüfkräfte

|Symbol Härte| Beanspruchungsgrad |Prüfkraft  in N|
| ----------- | ----------- |----------- |
| HBW 2,5/187,5 | 30 | $1839$ |
| HBW 2,5/62,5 | 10 | $612,9$ |
| HBW 2,5/31,25 | 5 | $306,5$ |
| HBW 2,5/15,625 | 2,5 | $153,2$ |
| HBW 2,5/6,25 | 1 | $61,29$ |


[Übersicht](ueber) 

(eindr)=
## Ausmessen des Eindrucks
Zur Bewertung des plastischen Eindrucks ist der Durchmesser des Eindrucks in zwei etwas senkrecht zueinander liegenden Richtungen zu messen. 

![Eindruck](HBPKEindr.png)

[Übersicht](ueber) 


(ber)=
## Berechnung des Härtewertes

Der Härtewert ergibt sich aus der Prüfkraft $F$ und der Oberfläche des Eindrucks $A_{D}$. Die Berechnung der Oberfläche des Eindrucks ergibt sich über das "eingedrungene" [Kugelsement](https://de.wikipedia.org/wiki/Kugelsegment), über die  mittlere gemessene Eindruckhdiagonale

$d=\frac{d_1+d_2}{2}$

![Eindruckoberflaeche](HB_Aeind.png)
Mit der Oberfläche des Kugelsegments

$A_D=\frac{\pi D}{2}(D-\sqrt(D^2-d^2)$

ergibt sich der Härtewert

$ \textit{Brinell-Härtewert} = 0,102\frac{2F}{\pi D(D-\sqrt{D^2-d^2})} $ mit $F$ in N mit $d$ in mm



Der berechnete Wert wird der Härteskala zugeordnet und ist ein reiner Zahlenwert ohne Dimension. Da die Brinell-Härteskala bereits zu beginn des 20. Jahrhunderts entwickelt wurde, hat ist mit den alten Härtewerten die alte Krafteinheit $kp=kgf$ (*Kilopond*) verbunden. Die Umrechnung erfolgt über die Erdbeschleunigung:

$[F]=1 \text{N} = g_{n} \cdot 1 \text{kp}$ mit $g_{n}= 9,80665 \frac{\text{m}}{\text{s}^2}$


Hieraus resultirt der Faktor $0,102\approx1/9,80665$


[Übersicht](ueber) 


(wert)=
## Angabe des Härtewertes

Da die Härte ein relative Maß ist, die Maßzahlen unterschiedlicher Skalen nicht direkt vergleichbar sind und die Härtewerte von den Prüfbedingungen abhängen, ist eine korrekte Angabe des Härtewertes nach der jeweiligen Prüfnorm essentiell. Ansonsten ist der Zahlenwert nutzlos!

![Eindruckoberflaeche](HB_angabe.png)

Der Prüfbericht muss in Anlehnung an DIN EN ISO 6506-1:2015, Absch. 9 folgende Angaben enthalten:

a) Normenverweis

b) Prbenbezeichnung zur eindeutigen Zuordnung

c) Prüfdatum

d) Prüftemperatur

e) ggf. das Verhältnis von Eindruckdruchmesser und Eindringkörperdurchmesser

f) Prüfergebnis

g) ggf. Grundlage und Verfahren der Umwertung

h) alle wesentlichen Randbedingunen der Prüfung, die nicht in der Norm festgelegt sind

i) Ereignisse oder Bedinugnen die ggf. das Prüfergebnis beeinträchtigen können


[Übersicht](ueber) 

