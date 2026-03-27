# Auswertung des Laborversuchs

## Spezielle Randbedingungen des Laborversuchs

Der Zugversuch im Labor hat die Besonderheit, dass die Probenverformung aufgrund des Messbereichs des zur Verfügungstehenden Extensometers nur bei geringen Verformungen (elastischer und beginnender plastischer Bereich) direkt gemessen werden kann. Damit stehen zwei Diagramme zur Verfügung: Kraft-Traversenweg und Kraft-Extensometerweg. Die jeweiligen Größen sind immer in dem dafür geeigneten Diagramm abzulesen! Das ist bei $R_{eH}$ bzw. $R_{p0,2}$ und dem E-Modul das Kraft-Extensometerweg-Diagramm, bei $R_m$ und $R_u$ das Kraft-Traversenweg-Diagramm. 

Bei der Berechnung der Dehnung ist auf die richtige Bezugslänge zu achten, also immer die Länge, auf die sich die gemessene Verlängerung bezieht. Das ist bei der Bruchdehnung und der Brucheinschnürung die Anfangsmesslänge $L_0$. Bei $L_{p0,2}$ und der Dehnung zur Berechnung des E-Moduls die Extensometermesslänge $L_e$. 

```{note}
$L_0$ und $L_e$ sind beides Längen, die im Grunde nicht direkt an der Probe zu messen sind:

Anfangsmesslänge $L_0$ wird auf der Probe (frei) markiert, die Extensometermesslänge $L_e$ ergibt sich aus dem Abstand der Messschneiden/Bezugsebenen des Extensometers

```

## Verformbarkeitskennwerte
Die Messgrößen zur Berechnung der **Bruchdehnung** $A$ und der **Brucheinschürung** $Z$ efolgen direkt an der Probe vor und nach der Prüfung. Wie in der nachfolgenden Darstellung skizziert ist auf den richtigen Bezug bei der Messung zu achten: 

- die Bruchdehnung $A$ ergibt sich aus der Änderung der Anfangsmesslänge $L_u-L_0$ bezogen auf die Anfangsmesslänge $L_0$. Es ist darauf zu achten, dass $L_0$ und $L_u$ über die gleichen Messmarken gemessen werden. 

- die Brucheinschnürung $Z$ ergibt sich aus der Änderung der Querschnittsfläche aus $d_0$ und $d_u$.

![MessZP](MessZP.png)


## Festigkeitskennwerte

Allgemein ergeben sich die Festigkeitskennwerte aus den Gemessenen Kraft-Verformungs-DIagrammen. Bei Werkstoffen mit ausgeprägter **Streckgrenze** ist der Bereich der elastischen und der elastisch-plastischen Verfomung deutich unterscheidbar. Damit lassen sich die entsprechenden Kräfte direkt ablesen. 

Ohne ausgeprägte Streckgrenze existiert ein allmählicher Übergang von der (linear) elastischen Verformung zur elastisch-plastischen und damit kein gut und einheitlich zu definierender "Ablesepunkt". Um hier einen der Streckgrenze vergleichbaren Kennwert zu besitzen, wird eine **Dehngrenze** definiert, also die Spannung, bei der eine bestimmte plasistische Dehnung erreicht wird. Die Dehung wird typischerweise auf $0,2\%$ plasitsche Dehnung festgelegt. Abzulesen ist der Wert durch die um die um den Dehnungswert von $0,2\%$ verschobenen elastischen Geraden. Im Kraft-Verfomungsdiagramm also der Länge $L_{p0,2}=0,2\%\;L_e$

Die **Reissfestigkeit** ist eine nicht in der DIN EN ISO 6892-1 definierte Größe. Sie ist im Rahmen des Laborversuchs definierte als die Spannung, die kurz vor dem Bruch im kleinsten Querschnitt in der Einschnürung wirkt. Die so defineirte Festigkeitsgröße bezieht sich also auf den aktuellen Querscnitt bei Bruch $A_u$ und nicht wie bei den zuvor genannten Kenngrößen auf den Ausgangsquerschnitt. 

![KurveZV](KurveZV.png)

## Elastizitätsmodul

Der **Elastizitätsmodul** ist die Steigung der elastischen Geraden im Spannungs-Dehnungs-Diagramm. Ermittelbar ist er über zwei beliebige Punkte auf der elstischen Geraden. 
In aus dem Versuch ergibt sich aber zunächst ein Kraft-Verlängerungsdiagramm. Die Steigung hier ist nicht der E-Modul. Daher muss bei der Berechnung auf Basis des Kraft-Verlängerungs-Diagramms noch Umrechnung der Größen auf Spannungen und Dehnungen mit erfolgen:

![Bestimmung E-Modul](ZVBestE.png)



## Beispiel und Vergleichswerte

In der folgenden .pdf-Datei sind einige Beispiel der Auswertung des Zugversuchs wie er im Labor erfolgt enthalten:

[ZVBspAus](220623-ZV-Beispielauswertung.pdf)


Die folgende .pdf-Datei enthält Vergleichswerte für die Einordnnug des Werkstoffs:

[ZVVergl](220623_ZV-Vergleichswerte.pdf)


