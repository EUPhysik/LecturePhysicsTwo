# Reflexion

Wenn ein Lichtstrahl auf die Grenzfläche zwischen zwei unterschiedlichen Medien trifft, dann wird ein Teil des Lichts reflektiert, und der andere Teil gelangt in das zweite Medium. 
Der Winkel zwischen dem einfallenden Strahl und dem Lot heißt Einfallswinkel ($\theta_1$ in {numref}`Abbildung %s <licht-2>`), und die Ebene, die durch diese beiden Linien aufgespannt wird, nennt man Einfallsebene. 
Der reflektierte Strahl liegt ebenfalls in der Einfallsebene und schließt mit der Normalen den Ausfallswinkel ($\theta_1^\prime$ in {numref}`Abbildung %s <licht-2>`) ein. 

```{figure} Bilder_Licht/Reflexion.svg
---
width: 80%
alt: Reflexion von  Licht
name: licht-2
---
Reflexion eines Lichtstrahls an einer Grenzfläche zwischen zwei Medien. 
 ```

Hier gilt

$$\theta_1 = \theta_1^\prime$$

Der reflektierte Strahl schließt mit dem 
Lot denselben Winkel ein, wie der einfallende
Strahl mit dem Lot.

Die Herleitung funktioniert auf Grundlage der Huygen'schen Prinzpis, wie bei den Wellen zuvor beschrieben.

## Transmission

Der Teil des Lichtes, der in das zweite Medium gelangt, wird gebrochen (siehe folgendes Kapitel). Man spricht auch von Anteil der Transmission.
Die relativen Intensitäten der transmittierten und reflektierten Lichtanteile sind komplex in der Berechnung und nicht Teil dieser Vorlesung.
Eine genaue Berechnung kann durch die Fresnel’schen Formeln erfolgen, Interessierte finden [hier](https://ap.physik.uni-konstanz.de/AP-public/Anleitungen/Fresnelsche-Formeln.pdf) weiterführende Litheratur. 

Für ___senkrechten___ Lichteinfall vereinfachen sich diese Formeln und der reflektierte Anteil kann berechnet werden durch

$I_R = \frac{n_1 - n_2}{n_1 + n_2} I_0$