# Spiegel

Trifft Licht auf eine Spiegel, so wird es an diesem reflektiert. Die Form des Spiegels entscheidet darüber in welcher Form ein reflektiertes Bild entsteht. 

## Reflexion am ebenen Spiegel

An einem ebenen Spiegel wird das Licht gemäß des Gesetzes Einfallswinkel  = Reflexionswinkel reflektiert. Es entsteht ein Spiegelbild, welches ein Beobachter sehen kann (siehe {numref}`Abbildung %s <ebener-spiegel>`). 

```{figure} Bilder_geooptik/ebener_spiegel.svg
---
width: 80%
alt: Ebener Spiegel
name: ebener-spiegel
---
Reflexion am ebenen Spiegel.
 ```

## Reflexion am rauhen Spiegel

An einem rauhen Spiegel wird Licht ebenfalls gemäß des Gesetzes Einfallswinkel  = Reflexionswinkel reflektiert. Da der Spiegel aber rauh ist, variiert der Einfallswinkel räumlich sehr stark. Dies erzeugt ein diffuses Bild und kein ebenes Spiegelbild (siehe {numref}`Abbildung %s <rauher-spiegel>`).

```{figure} Bilder_geooptik/rauher_spiegel.svg
---
width: 60%
alt: Rauher Spiegel
name: rauher-spiegel
---
Reflexion am rauhen Spiegel.
 ```

## Reflexion am Hohlspiegel

Ein Hohlspiegel ist ein nach innen gewölbter Spiegel mit einem Krümmungsradius $r$. Trifft Licht auf diesen Spiegel, so wird es nach innen reflektiert. Aufgrund der gewölbten Konstruktion laufen die Strahlen alle in einem Punkt $P$ zusammen. Dieser Punkt wird als Brennpunkt $F$ des Hohlspiegels bezeichnet. Der Abstand des Brennpunktes zum Spiegel wird als Brennweite $f$ bezeichnet.


```{figure} Bilder_geooptik/geometrische_Optik_2.svg
---
width: 80%
alt: Hohlspiegel
name: hohlspiegel
---
Reflexion am Hohlspiegel.
 ```

Bei sphärischen Hohlspiegeln werden achsenferne Strahlen werden nicht zum Brennpunkt reflektiert. Bei parabolförmigen Spiegeln werden alle Strahlen in den Brennpunkt reflektiert, sie sind allerdings deutlich aufwändiger in der Herstellung. 

Für die Hauptstrahlen am Hohlspiegel gelten folgenden konstruktive Vorschriften

* Der achsenparallele Strahl wird in den Brennpunkt reflektiert. 
* Der Brennpunktsstrahl verläuft durch den Brennpunkt und wird achsenparallel reflektiert. 
* Der Mittelpunktsstrahl verläuft durch den Krümmungsmittelpunkt des Spiegels, trifft diesen senkrecht zur Oberfläche und wird daher in sich selbst reflektiert.
* Die Brennweite eines sphärischen Spiegels ist halb so groß wie der Krümmungsradius. Es gilt

$$f = \frac{1}{2}r$$

Mit Hilfe dieser Vorschriften kann das Spiegelbild konstruiert werden. {numref}`Abbildung %s <hohlspiegel-2>` zeigt die Konstruktion eines Bildes am Hohlspiegel, wenn sich das Bild ausserhalb des Brennpunktes befindet. Der A

```{figure} Bilder_geooptik/geometrische_Optik_3.svg
---
width: 80%
alt: Hohlspiegel
name: hohlspiegel-2
---
Strahlenkonstruktion bei Reflexion am Hohlspiegel.
 ```

Zur Berechnung sind die sogenanten Abbildungsgleichungen für sphärische Spiegel herangezogen werden. Es gilt

$$\frac{B}{G} = \frac{b}{g}$$(abb-1)

und

$$\frac{1}{b} + \frac{1}{g} = \frac{1}{f}$$(abb-2)

Diese beiden Gleichungen können leicht hergeleitet werden, wenn ähnliche Dreiecke betrachtet werden, die durch die Strahlengänge konstruiert werden. {numref}`Abbildung %s <hohlspiegel-2>` zeigt dieselbe Abbildungskonstruktion wie in {numref}`Abbildung %s <hohlspiegel-4>`. 

```{figure} Bilder_geooptik/geometrische_Optik_4.svg
---
width: 80%
alt: Hohlspiegel
name: hohlspiegel-4
---
Herleitung der Abbildungsgleichung $\frac{B}{G} = \frac{b}{g}$.
 ```

Das hellgrüne und hellviolette Dreieck in {numref}`Abbildung %s <hohlspiegel-4>` sind ähnlich (siehe auch [ähnliche Dreiecke](https://de.wikipedia.org/wiki/%C3%84hnlichkeitss%C3%A4tze)). Daraus lässt sich direkt die oben genannte Beziehung ableiten. Die Gegenstandsweite $g$ ist die horizontale Länge der langen Seite des grünen Dreiecks, die Gegenstandsgröße $G$ die Höhe des grünen Dreiecks. Die Bildweite $b$ ist die Länge der horizontalen langen Seite des violetten Dreiecks, die Bildgröße $B$ die Höhe des violetten Dreiecks. Daraus ergibt sich mit Hilfe des Ähnlichkeitssatzes

$$\frac{B}{b} = \frac{G}{g}$$

welches eine äquivalente Formulierung von {eq}`abb-1` ist. 

Auch in {numref}`Abbildung %s <hohlspiegel-5>` sind das grüne und das violette Dreieck ähnlich. Hier ist die Bildweite $b$ die Summe der horizontale Längen des grünen und des violetten Dreiecks, die horizontale Länge des violetten Dreiecks ist die Brennweite $f$. 

```{figure} Bilder_geooptik/geometrische_Optik_5.svg
---
width: 80%
alt: Hohlspiegel
name: hohlspiegel-5
---
Herleitung der Abbildungsgleichung $\frac{1}{b} + \frac{1}{g} = \frac{1}{f}$.
 ```

Daraus ergibt sich

$$\frac{B}{b-f} = \frac{G}{f}$$

Das kann umgestellt werden zu 

$$\frac{B}{G} = \frac{b-f}{f}$$

mit {eq}`abb-1` ergibt sich daraus

$$\frac{b}{g} = \frac{b-f}{f} = \frac{b}{f} - 1$$

Dividieren dieser Gleichung durch $b$ ergibt 

$$\frac{1}{g} = \frac{1}{f} - \frac{1}{b}$$

und damit die Abbildungsgleichung {eq}`abb-2`

$$\frac{1}{b} + \frac{1}{g} = \frac{1}{f}$$

Befindet sich der Gegenstand zwischen dem Spiegel und dessen Brennweite ($g < f$) entsteht ein aufrecht stehendes und virtuelles Bild (siehe {numref}`Abbildung %s <hohlspiegel-6>`)

```{figure} Bilder_geooptik/geometrische_Optik_6.svg
---
width: 80%
alt: Hohlspiegel
name: hohlspiegel-6
---
Bildkonstruktion bei $g < f$.
 ```

$$\frac{1}{b} + \frac{1}{g} = \frac{1}{f} \Leftrightarrow \frac{1}{b} = \frac{1}{f} - \frac{1}{g} = \frac{f-g}{f \cdot g} \Leftrightarrow b = \frac{f \cdot g}{f-g}$$

Ist $g < f$ ist somit die Bildweite $b$ negativ.