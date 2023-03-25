# Mathematisches Pendel

Das mathematische Pendel ist eine einfache zweidimensionale Pendelbewegung, die einfach durch eine Masse an einem Faden realisiert werden kann. 

```{figure} Bilder_Schwingungen/Fadenpendel.svg
---
width: 70%
alt: Fadenpendel
name: mat-1
---
Schematische Darstellung eines mathematischen Pendels.
 ```

Allgemein gilt für ein mathematisches Pendel

* Ein mathematisches Pendel ist ein idealisiertes Pendel
* Es ist ein Pendel, bei dem die Pendelmasse punktförmig ist und der Faden keine Masse hat

Als **Amplitude** ist hierbei die maximale Auslenkung des Pendels zu verstehen und als **Schwingungsdauer** wird die Zeit zwischen zwei Durchgängen eines Umkehrpunktes bezeichnet. 

Da die Pendellänge konstant ist, bewegt sich die Masse auf einer (Teil-) Kreisbahn. Wie bei der Kreisbewegung kann auch hier das Problem von einem zweidimensionalen auf ein eindimensionales Problem reduziert werden. Dazu werden Polarkoordinaten verwendet und es gilt

$$\left(x,y \right) \longrightarrow \left(r,\phi\right)$$

$$x = r \cdot sin \left(\phi\right)$$

$$y = - r \cdot cos \left(\phi\right)$$

da $r = l = \text{konst}.$ ist

$$\left(x,y \right) = \left(l \cdot sin \left( \phi \right), - l \cdot cos \left( \phi \right) \right)$$

und $s = l \cdot \phi$

```{figure} Bilder_Schwingungen/Fadenpendel_2.svg
---
width: 70%
alt: Fadenpendel
name: mat-2
---
Polarkoordinaten zur Beschreibung eines mathematischen Pendels.
 ```
Auf das (reibungsfreie) Pendel wirkt zum einen die Gewichtskraft $\vec{F}_G = m \cdot \vec{g}$, die in -$y$ wirkt. Der Faden hält die Masse auf der Kreisbahn, die entsprechende Seilkraft wirkt demnach in Richtung des Kreismittelpunktes (siehe {numref}`Abbildung %s <mat-3>`).

Für die Betrachtung der Bewegungsgleichung sind nur die Kräfte entlang von $s=\phi\cdot l$ relevant.
Damit gilt:

$$m \frac{d^2s}{dt^2} =m \frac{d^2 \left( \phi \cdot l\right)}{dt^2} =  m \cdot l\frac{d^2 \left( \phi \right)}{dt^2} = - m g sin \left(\phi\right)$$


 ```{figure} Bilder_Schwingungen/Fadenpendel_3.png
---
width: 70%
alt: Fadenpendel
name: mat-3
---
Wirkende Kräfte beim mathematischen Pendels.
 ```

Diese Differentialgleichung ist analytisch nur lösbar für kleine Winkel. Dann gilt näherungsweise $sin \left( \phi \right) \approx \phi$ und die Differentialgleichung wird zu

$$m \cdot l\frac{d^2 \left( \phi \right)}{dt^2} = - m g \phi$$

Als Lösungsansatz wird wieder ein e-Funktion verwendet

$\phi(t) = c_1\cdot e^{i\cdot c_2 \cdot t} $

$\Rightarrow \frac{d\phi(t)}{dt} = c_1\cdot i \cdot c_2\cdot e^{i\cdot c_2 \cdot t}$

$\Rightarrow \frac{d^2\phi(t)}{dt^2} = - c_1 \cdot c_2^2\cdot e^{i\cdot c_2 \cdot t} = -  \frac{g}{l} \phi = -  \frac{g}{l} c_1\cdot e^{i\cdot c_2 \cdot t}$

Damit kann $c_2$ einfach bestimmt werden

$$c_2^2 = \frac{g}{l} \Rightarrow c_2 = \pm \sqrt{\frac{g}{l}}$$

Einsetzen der Lösungen mit $c_2 = \pm \sqrt{\frac{g}{l}}$

$$\phi(t) = c_1\cdot e^{i\cdot \frac{g}{l} \cdot t} +  c_1\cdot e^{- i\cdot \frac{g}{l} \cdot t} = c_1\left(e^{i\cdot \omega \cdot t}
+ \cdot e^{- i\cdot \omega \cdot t}\right) = 2c_1\left(cos \left( \omega \cdot t\right)\right)$$

mit $\omega = \sqrt{\frac{g}{l}}$

$2c_1 =: \hat{\phi}$ erhält man aus der Anfangsbedingung $\phi (t = 0) = \hat{\phi}$

Allgemeine Bewegungsgleichung:

$$\phi(t) = \hat{\phi}\left(cos \left( \omega \cdot t\right)+ \delta\right)$$

Mit

$\hat{\phi}$: maximale Winkelauslenkung des Pendels

$\omega$: Kreisfrequenz der Schwingung

$\delta$: Phasenverschiebung

Achtung:
$\omega$ ist hier die sogenannte Kreisfrequenz — nicht die Winkelgeschwindigkeit —
Die Winkelgeschwindigkeit $\dot\phi(t)$ ist zeitabhängig!!!

Es gilt der bekannte Zusammenhang: $\omega = 2\pi f= \frac{2\pi}{T}$

Aus der Bewegungsgleichung wissen wir, dass gilt: $\omega = \sqrt{\frac{g}{l}}$

Damit ist $\omega = \frac{2\pi}{T} = \sqrt{\frac{g}{l}}\Leftrightarrow T = 2 \pi \sqrt{\frac{l}{g}}$

Die Schwingungsdauer hängt also nur ab von 
* Der Pendellänge $l$
* Der Erdbeschleunigung $g$

$\Rightarrow$ Durch Messung von $l$ und $T$ kann $g$ bestimmt werden!

