# Grundlagen

## Kennwerte nach DIN EN ISO 6892-1:2020-06, Übersicht

| Kennwert |  Definiton |
| -------- | ------------------------- | 
| Anfangsquerschnittsfläche | $S_0=\pi d_0^2/4$ (Kreisquerschnitt)
| kleinster Querschnitt nach Bruch | $S_u=\pi d_u^2/4$ (Kreisquerschnitt)
| obere Streckgrenze | $R_{eH}=F_{eH}/S_0$ |
| 0,2%-Dehngrenze | $R_{p0,2}=F_{p0,2}/S_0$ |
| Zugfestigkeit | $R_{m}=F_{m}/S_0$ |
| Reissfestigkeit (nicht in der DIN EN ISO 6892-1 enthalten) | $R_u=F_u/S_u$ |
| Bruchdehnung | $A=(L_u-L_0)/L_0$ |
| Brucheinschnürung | $Z=(S_0-S_u)/S_0$ |
| E-Modul | $E=(R_2-R_1)/(e_2-e_1)=\Delta R / \Delta e \text{   } (=\Delta \sigma / \Delta \epsilon )$ |

![SigEps](ZV/SigEps.png)


## Beschreibung

Der Zugversuch 
- liefert die wichtigsten Werkstoffkennwerte für die Bauteildimensionierung (Festigkeits- und Verformbarkeitskennwerte)

- ist ein einfaches, international genormtes und relativ kostengünstiges Prüfverfahren zur Qualitätssicherung

- ist ein zerstörendes Prüfverfahren

Für verschiedene Werktosffgruppen gibt es unterschiedliche Prüfnormen, in denen der Zugversuche geregelt ist und in denen auch die Angaben zur Prüfung festgelegt sind. Im folgenden wird sich auf die *DIN EN ISO 6892-1:2020-06, Metallische Werkstoffe - Zugversuch - Teil 1: Prüfverfahren bei Raumtemperatur (ISO 6892-1:2019); Deutsche Fassung EN ISO 6892-1:2019* bezogen.

Die Prüfung erfolgt an einer glatten Zugprobe (homogener Beanspruchungszustand) unter einachsigem Zug (einachsiger Spannungszustand). Die Prüfung erfolgt quasistatisch. Die Kennwerte beziehen sich also auf eine vorwiegend ruhende Beanspruchung (kein Einfluss der Prüfgeschwindigkeit).  
Die Last wird weggeregelt aufgebracht, duch ein konstantes Verfahren der Traverse der Prüfmaschine. Die dabei entstehenden Kräfte und die Verformung direkt an der Probe werden im Versuch mit gemessen. 

[Zugversuch in der Werkstoffprüfung](https://youtu.be/Hy4yZFu-dWU?si=zwWEQoiJbFbOxBS6)  
[Der Zugversuch erklärt](https://youtu.be/QSztAECV4V0?si=aQl4yDS6y3alHko8)  

## Berechnnugsgrößen, allg.

Um von der Probenform und größe unabhänige Werstoffkennwerte zu erhalten, werden als Kennwerte nicht die direkten Messwerte *Kraft* und *Verlängerung* verwendet, sondern die bezogene Größen *Spannung* und *Dehnung*.  

![SpDe](ZV/SpDe.png)

Allgemein finden sich in der Literatur für die Spannung und die Dehnung die folgenden definitionen:  
$\sigma=F/A$; die Spannung $\sigma$ ergibt sich aus der Kraft $F$ bezogen auf die Fläche $A$.  
$\epsilon=\Delta l/l_{0}$; die Dehnung $\epsilon$ ergibt sich aus der Längenändeurng $\Delta l$ bezogen auf die Messlänge $l_0$

In der DIN EN ISO 6892-1 werden die folgenden Symbole verwendet:  
$R=F/S_0$, mit $R$ der Spannung und $S_0$ der Bezugsfläche.  
$e=\Delta L/L_{0}$, mit $e$ der Dehnung

