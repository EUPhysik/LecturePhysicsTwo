# Linsen

## Bildentstehung an gekrümmter Oberfläche

Wie beim Spiegel kann auch an gekrümmten durchsichtigen Oberflächen ein Bild entstehen. Hier entsteht das Bild nicht durch Reflexion, sondern durch Brechung. 

```{figure} Bilder_geooptik/geometrische_Optik_7.svg
---
width: 100%
alt: Bildentstehung an gekrümmten durchsichtigen Oberflächen
name: linse-1
---
Bildentstehung an gekrümmten durchsichtigen Oberflächen.
 ```

Nach dem Snellius`schen Brechungsgesetz gilt

$$n_1 sin \left( \theta_1 \right) = n_2 sin \left( \theta_2 \right)$$

Bei kleinen Winkeln gilt die Näherung: $sin \left( \alpha \right) \approx tan \left( \alpha \right) \approx \alpha$.
Für den $tan$ gilt

$$ tan \left( \theta_1 \right) = \frac{G}{g}$$

$$ tan \left( \theta_2 \right) = - \frac{B}{b}$$

Daraus ergibt sich 

$$n_1 sin \frac{G}{g} = - n_2 \frac{B}{b} \Leftrightarrow \frac{B}{G} = - \frac{n_1 \cdot b}{n_2 \cdot g}$$

Bei der Brechung entstehen reelle Bilder, und zwar (vom Gegenstand aus gesehen) hinter der brechenden Fläche (siehe {numref}`Abbildung %s <linse-1>`). 
Virtuelle Bilder dagegen entstehen auf der Einfallsseite, vor der brechenden Fläche. 

Die Vorzeichenkonvention für die Brechung ähnelt derjenigen für die Reflexion. Es gilt:

* Die Gegenstandsweite g ist positiv für Gegenstände auf der Einfallsseite der brechenden Fläche. 
* Die Bildweite b ist positiv für Bilder auf der Transmissionsseite der brechenden Fläche. 
* Der Krümmungsradius r ist positiv, wenn der Krümmungsmittelpunkt auf der Transmissionsseite der brechenden Fläche liegt. 

Die Herleitung der entsprechenden Abbildungsgleichung erfolgt über verschiedene Winkelbetrachtungen.

```{figure} Bilder_geooptik/Brechung_sphaerische_Oberflaeche.svg
---
width: 100%
alt: Abbildungsgleichung an gekrümmten durchsichtigen Oberflächen
name: linse-2
---
Abbildungsgleichung an gekrümmten durchsichtigen Oberflächen.
 ```

Dreieck BDE: $180^\circ = \beta + \delta^\prime + \gamma^\prime$ außerdem: $180^\circ = \gamma^{\prime\prime} + \delta^\prime$ $\Rightarrow \gamma^{\prime\prime} = \beta + \gamma^\prime \Leftrightarrow \beta = \gamma^{\prime\prime} - \gamma^\prime$

Dreieck ABD: $180^\circ = \gamma + \delta + \gamma^{\prime\prime}$ außerdem: $180^\circ = \alpha + \delta$ $\Rightarrow \alpha = \gamma^{\prime\prime} + \gamma$

Brechungsgesetz: 

$$\frac{sin(\alpha)}{sin(\beta)} = \frac{n_2}{n_1} \approx \frac{\alpha}{\beta} = \frac{\gamma^{\prime\prime} + \gamma}{\gamma^{\prime\prime} - \gamma^\prime}
\Leftrightarrow n_2 \left( \gamma^{\prime\prime} - \gamma^\prime \right) = n_1 \left( \gamma^{\prime\prime} + \gamma\right)\Leftrightarrow \gamma^{\prime\prime} \left(n_2 - n_1 \right) = n_1 \gamma + n_2\gamma^\prime$$

Außerdem gilt für kleine Winkel ($\overline{CD} \gg \overline{C\leftrightarrow\text{Oberflaeche}}$)

$\gamma^{\prime\prime} \approx \frac{h}{r}$ 

$\gamma^{\prime} \approx \frac{h}{b}$

$\gamma \approx \frac{h}{g}$

Daraus ergibt sich

$$\Rightarrow \frac{h}{r} \left(n_2 - n_1 \right) = n_1 \frac{h}{g} + n_2 \frac{h}{b} \Leftrightarrow \frac{n_2 - n_1}{r}= \frac{n_1}{g} + \frac{n_2}{b}$$(eq:b-o)


## Dünne Linsen

Linsen sind optische Instrumente, die aus zwei durchsichtigen Oberflächen bestehen. Bei Linsen findet also Brechung an zwei Oberflächen statt. Je nach Form der beiden Oberflächen gibt es unterschiedliche Effekte bei der Bildentstehung.
Man unterscheidet konvexe Linsen (Sammellinsen) und konkave Linsen (Zerstreuungslinsen), Konvexe Linsen fokussieren parallel einfallendes Licht in einem Brennpunkt hinter der Linse, konkave Linsen defokussieren parallel einfallendes Licht (siehe {numref}`Abbildung %s <linse-3>`)

```{figure} Bilder_geooptik/linsenarten.svg
---
width: 100%
alt: Konvex- und Konkavlinsen
name: linse-3
---
Strahlengang bei Konvex- und Konkavlinsen
 ```

Im folgenden wird eine dünne Konvexlinse betrachtet, um die Linsengleichung herzuleiten. Dünne Linsen sind Linsen, wie sie in {numref}`Abbildung %s <linse-3>` dargestellt werden.

An beiden Oberflächen einer Linse tritt Brechung auf, wobei das von der ersten Oberfläche entworfene Bild  als virtueller Gegenstand für die Abbildung durch die zweite Oberfläche dient.

```{figure} Bilder_geooptik/duennelinsen.svg
---
width: 100%
alt: Dünne Linsen
name: linse-4
---
Strahlengang bei einer dünnen Konvexlinse
 ```

Der Gegenstand hat von der ersten Oberfläche den Abstand $g$. Für die Brechung an der ersten Oberfläche gilt nach {eq}`eq:b-o`
Bildweite durch die erste Oberfläche:

$$\frac{n_{L}}{g} + \frac{n_G}{\tilde{b}} = \frac{n_G-n_{L}}{r_1}$$(eq-linse-1)

Dabei ist $n_L$ der Brechungsindex der Luft und $n_G$ der Brechungsindex der Linse, hier Glas. $\tilde{b}$ ist die Bildweite des nach Brechung an der ersten Oberfläche des entstandenen Bildes und $r_1$ der Radius der ersten Linsenkrümmung.

Das an der ersten Oberfläche gebrochene Licht wird an der zweiten Oberfläche erneut gebrochen. Die an der zweiten Oberfläche gebrochenen Strahlen verlaufen innerhalb der Linse so, als gingen sie vom Bildpunkt $P^\prime$ aus. Dies bedeutet $\tilde{b} = - \tilde{g}$. Hier führt sie als erstes zu einem virtuellen Bild bei $P^{\prime\prime}$

$$\frac{n_G}{\tilde{g}^\prime} + \frac{n_L}{b} = \frac{n_G}{-\tilde{b}} + \frac{n_L}{b} = \frac{n_G - n_L}{r_2}$$(eq-linse-2)

Addieren von Gleichung {eq}`eq-linse-1` und Gleichung {eq}`eq-linse-2` ergibt

$$\frac{n_{L}}{g} + \frac{n_G}{\tilde{b}} +\frac{n_G}{-\tilde{b}} + \frac{n_L}{b} = \frac{n_G-n_{L}}{r_1} + \frac{n_L - n_G}{r_2}$$

$$\Leftrightarrow \frac{n_{L}}{g} + \frac{n_L}{b} = \frac{n_G-n_{L}}{r_1} + \frac{n_G - n_L}{r_2}$$
 
$$\Leftrightarrow \frac{1}{g} + \frac{1}{b} = \left( \frac{n_G}{n_L} - 1 \right) \left( \frac{1}{r_1} - \frac{1}{r_2}\right)$$

Der Term auf der rechten Seite ist der Kehrwert der Brennweite der Linse

$$\frac{1}{f} = \left( \frac{n_G}{n_L} - 1 \right) \left( \frac{1}{r_1} - \frac{1}{r_2}\right)$$

Die Brennweite ist definiert also die Bildweite bei einem unendlich weit entfernten Gegenstand 

($\Rightarrow b = f \text{ und } g\rightarrow \infty$). 

$$\Rightarrow
\frac{n_{Luft}}{f}
= \frac{r_2 \left(n-n_{Luft} \right) + r_1 \left(n_{Luft} - n \right)}{r_1 r_2}$$

$$
\Leftrightarrow 
\frac{1}{f} 
= \frac{ \left(n-n_{Luft} \right)}{n_{Luft}}\frac{r_2 - r_1}{r_1 r_2}
= \left( \frac{n}{n_{Luft}} - 1\right) \left(\frac{1}{r_1} - \frac{1}{r_2}\right)
$$

Damit ergibt sich die Linsengleichung

$$ \frac{1}{g} + \frac{1}{b} = \frac{1}{f}$$

Dabei ist $g$ die Gegenstandsweite vor der ersten Brechung und $b$ die Bildweite nach der zweiten Brechung. Die dünne Linse kann idealisiert also so betrachtet werden, als würde nur eine Brechung in der Mitte der Linse stattfinden.

Der Kehrwert der Brennweite wird auch als Brechkraft $D$ einer Linse bezeichnet.

$$D = \frac{1}{f}$$

mit $\frac{1}{f} = \left( \frac{n_G}{n_L} - 1 \right) \left( \frac{1}{r_1} - \frac{1}{r_2}\right)$

Dieser Zusammenhang gilt auch für Konkavlinsen oder kombinierte Linsen.

Es gilt folgende Vorzeichenkonvention für die Radien:
* $r$ ist positiv, wenn der Krümmungsmittelpunkt auf der gleichen Seite der Oberfläche liegt wie das gebrochene Licht 
* Die beiden Radien haben dann gleiche Vorzeichen, wenn die Mittelpunkte auf derselben Seite der Linse liegen (konvex-konkave Linse)
* Die beiden Radien haben ungleiche Vorzeichen, wenn die Linse bikonvex/bikonkav ist

## Bildentstehung an Linsen

Aus den im vorigen Kapitel abgeleiteten Zusammenhängen können folgende Regeln für die geometrische Bildkonstruktion an einer dünnen Linse formuliert werden. 

* Der achsenparallele Strahl wird so gebrochen, dass er durch den zweiten Brennpunkt der Linse verläuft.
* Der Mittelpunktsstrahl verläuft durch den Mittelpunkt der Linse und wird nicht aus seiner Richtung abgelenkt.
* Der Brennpunktsstrahl verläuft durch den ersten Brennpunkt und tritt achsenparallel aus. Bei einer Konkavlinse wird der Brennpunktsstrahl auf den ersten Brennpunkt, hinter der Linse, gerichtet.

```{figure} Bilder_geooptik/konvexlinse.svg
---
width: 100%
alt: Dünne Linsen
name: linse-5
---
Strahlengang bei einer dünnen Konvexlinse
 ```

 ```{figure} Bilder_geooptik/konkavlinse.svg
---
width: 100%
alt: Dünne Linsen
name: linse-6
---
Strahlengang bei einer dünnen Konkavlinse
 ```

<!-- ## Mehrere Linsen  -->
