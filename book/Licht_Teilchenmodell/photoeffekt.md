# Photoeffekt

__Experiment__

```{figure} Bilder/Photoeffekt_Schema.png
---
width: 60%
alt: Photoeffekt
name: photo-1
---
Schematische Darstellung eines Versuchsaufbaus zum Photoeffekt.
 ```

Um den Photoeffekt zu beweisen, kann man folgenden einfachen Versuchsaufbau machen (siehe auch {numref}`Abbildung %s <photo-1>`):

Eine Kathode, beispielsweise aus Zink wird negativ aufgeladen, die Ladung der Kathode wird mit einem  [Elektroskop](https://de.wikipedia.org/wiki/Elektroskop) gemessen. Dann wird die Zinkplatte mit einer [Quecksilberdampflampe](https://de.wikipedia.org/wiki/Quecksilberdampflampe) bestrahlt. Beim Bestrahlen der Zinkplatte geht der Zeigerausschlag am Elektroskop zurück – die Zinkplatte wird also entladen.
Wann funktioniert das Experiment nicht, wenn beispielsweise

* die Zinkplatte positiv geladen wurde
* sich eine Glasscheibe zwischen Lampe und Zinkplatte befindet?
* beispielsweise eine [Natriumdampflampe](https://de.wikipedia.org/wiki/Natriumdampflampe) verwendet wird?. Auch bei einer Erhöhung der Strahlungsintensität führt die Bestrahlung mit einer Natriumdampflampe nicht zum Entladen der Zinkplatte. 

__Erklärung__

Die Quecksilberdampflampe erzeugt UV-Licht mit einer hohen Frequenz (geringer Wellenlänge). Dieses Licht ist in der Lage, einzelne negativ geladene Teilchen (Elektronen) aus der Zinkkathode herauszulösen. Dadurch wird die Ladung der Kathode positiver. Das Licht verrichtet aus Arbeit an der Zinkplatte. Diese Arbeit bezeichnet man auch als Ablösearbeit $W_A$, da die Elektroden aus dem Material abgelöst werden. 
Die Natriumdampflampe erzeugt deutlich langwelligeres Licht, welches nicht in der Lage ist, Elektronen aus der Kathode zu lösen.

Dies bedeutet: 

Nur das kurzwelligere UV-Licht kann $W_A$ verrichten, nicht das sichtbare Licht und zwar unabhängig von der Intensität des Lichtes.
Die Energieübertragung des Lichts auf die Elektronen muss sich also bei UV-Licht von sichtbarem Licht unterscheiden. Dies steht im Widerspruch zur Wellentheorie, denn nach dieser sollte bei höherer Intensität auch mehr Energie übertragen werden.

Zur Erinnerung: Energie einer Welle

$$E= \frac{m}{2} \omega^2 \hat{y}^2$$

Die Intensität $I$ von Licht ist definiert also die Energie, die pro Zeit auf eine bestimmte Fläche fällt

$$ I = \frac{dE}{dt\cdot A} \rightarrow  \frac{E}{\Delta t\cdot A}$$ 

wenn $I =$ konstant. Also gilt

$$
\begin{equation}
I \propto E \propto \hat{y}^2 	
\end{equation}
$$

__Verständnisfragen__

Warum funktioniert das Experiment nicht, wenn eine Glasscheibe zwischen Lampe und Kathode ist?

```{figure} Bilder/Photoeffekt_Schema_2.png
---
width: 80%
alt: Photoeffekt
name: photo-2
---
Schematische Darstellung eines Versuchsaufbaus zum Photoeffekt mit Messung des Photostrom
 ```

Bei diesem Experiment kann man nicht nur sehen, dass die Elektronen aus der Zinkkathode herausgelöst werden, diese haben sogar eine gewisse kinetische Energie. Dies kann durch eine geringfügige Ergänzung des Experiments, wie in {numref}`Abbildung %s <photo-2>` dargestellt, gezeigt werden. Hier wird vor die Kathode ein Metallgitter platziert, welches die Photoelektronen aufnimmt und somit negativ geladen wird. Dadurch entsteht eine Potentialdifferenz zwischen der dann positiv geladenen Kathode und dem negativ geladenen Gitter und es fließt ein Strom, der so genannte Photostrom. Dieser kann mit Hilfe eines Messverstärkers sichtbar gemacht werden. 

Da der Photoeffekt nicht mit Hilfe des Wellenmodells erklärt werden kann, muss an dieser Stelle das Teilchenmodell des Lichtes zur Hilfe genommen werden. 
Im Teilchenbild interpretiert man das Licht als einen Teilchenstrom. Die einzelnen Lichtteilchen werden als Photonen bezeichnet. 
Ein Photon besitzt Teilcheneigenschaften, wie Masse und Impuls. 

__Funktionale Zusammenhänge__ (Ohne Herleitung) 

Es kann gezeigt werden, dass die Energie eines Photons linear mit der zugehörigen Frequenz zusammenhängt, die Proportionaliätskonstante dieses Zusammenhangs ist das sogenannte Plank'sche Wirkungsquantum und wird mit $h$ bezeichnet. Im Teilchenmodell gelten für das Photon folgende Teilcheneigenschaften:

__Energie__ $E = h \cdot f$ mit $h = 6.626 \cdot 10^{-34} \, Js$ (Planck'sches Wirkungsquantum)

__Impuls__ $p = \frac{E}{c} = \frac{h \cdot f}{c}$

__Masse__ $m = \frac{E}{c^2} = \frac{h \cdot f}{c^2} $



## Gegenfeldmethode

Genauer kann der Fotoeffekt mit der sogenannten Gegenfeldmethode vermessen werden (siehe {numref}`Abbildung %s <photo-3>`).

```{figure} Bilder/Photoeffekt_gegenfeldmethode_neu.png
---
width: 80%
alt: Photoeffekt
name: photo-3
---
Gegenfeldmethode zur Bestimmung der Kenngrößen des Photoeffektes, Quelle: Jkrieger - CC BY-SA 3.0, https://commons.wikimedia.org/w/index.php?curid=18130611
 ```
Die Gegenfeldmethode ist ein Verfahren, mit dem man die Geschwindigkeit und damit die Energie von geladenen Teilchen (Elektronen, Ionen) bestimmen kann. 

### Theorie

Die herausgelösten Elektronen haben die kinetische Energie $E_{kin}$ und bewegen sich von der Photokathode weg in Richtung Auffanganode (das zuvor beschriebene Gitter). Das angelegte Gegenfeld hat eine Spannung $U$. Wenn ein elektrisch geladenes Teilchen sich in einem Spannungspotential bewegt, so verrichtet es dabei die Arbeit $W_e = U\cdot q$. Da die Elektronen die Ladung $e$ haben, gilt:

$$W_e = e\cdot U_0$$

wobei $U_0$ die angelegte Gegenspannung ist. Diese Gegenspannung kann geregelt werden und wird solange erhöht, bis gerade keine Photoelektronen mehr die Anode erreichen. Dann gilt

$$
\begin{equation}
E_{kin} = W_e \Leftrightarrow \frac{1}{2} \,m \,v^2 = e\cdot U
\end{equation}
$$(gegenfeld)

Daher kann also mit Hilfe der Abbremsspannung die Geschwindigkeit der Elektronen bestimmt werden.
Aus Gleichung {eq}`gegenfeld` ergibt sich

$$
\begin{equation}
v = \sqrt{\frac{2eU}{m}}
\end{equation}
$$

Dieses Experiment kann mit Hilfe von Filtern, welche zwischen die Lampe und die Kathode gesetzt werden, für verschiedene Lichtfarben durchgeführt werden.
Das Ergebnis eines derartigen Experimentes ist in {numref}`Abbildung %s <photo-4>` dargestellt.

```{figure} Bilder/Photoelectric_effect_diagram.png
---
width: 80%
alt: Photoeffekt
name: photo-4
---
Gegenfeldmethode zur Bestimmung der Kenngrößen des Photoeffektes, Quelle: Klaus-Dieter Keller, CC BY 3.0, https://commons.wikimedia.org/w/index.php?curid=24751457
 ```

Folgende Zusammenhänge sind erkennbar:

* Die maximale Gegenspannung (und damit die Energie der schnellsten Fotoelektronen) hängt von der Frequenz des eingestrahlten Lichts ab, nicht aber von der Intensität.
* Je größer die Frequenz des eingestrahlten Lichts ist, umso größer ist die maximale kinetische Energie der Fotoelektronen.
* Die Intensität bestimmt die Größe des Fotostroms, nicht aber die notwendige Gegenspannung, bei der dieser auf Null absinkt.

Die Grenzfrequenz, bei der Photoelektronen ausgelöst werden ist natürlich materialabhängig, das heisst bei einem anderen Material als Zink, würde diese an einer anderen Frequenz liegen. 

Die Energie eines Photons, das ein Elektron ausgelöst hat, wird in der Regel größer sein als die Auslösearbeit. Die überschüssige Energie wird in kinetische Energie des Photoelektrons umgewandelt.

$$
\begin{equation}
E_{Photon} = E_{kin} + W_A
\end{equation}
$$(eq:einstein)

Diese Gleichung ist auch als Einsteingleichung bekannt, welcher für seine Arbeit zu Photonen mit dem Nobelpreis ausgezeichnet wurde.
Mit Hilfe dieser Gleichung kann die Auslösearbeit bestimmt werden. Setzt man die von oben bekannten Ausdrücke in Gleichung {eq}`eq:einstein` ein, so erhält man 

$$
\begin{eqnarray}
&& E_{kin} = E_{Photon} -W_A \nonumber \\
&\Leftrightarrow& U \cdot e = h \cdot f - W_A 
\end{eqnarray}(eq:wa)
$$

Die kinetische Energie $U\cdot e$ lässt sich also darstellen als lineare Funktion der Frequenz $f$ mit y-Achsenabschnitt $W_A$ darstellen. Durch Messung der kinetischen Energie der Photoelektronen bei verschiedenen Frequenzen des einfallenden Lichtes kann die Funktion bestimmt werden. Natürlich können nur für $E_{kin} > 0$ Messdaten genommen werden, da unterhalb dieser Schwelle keine Elektronen ausgelöst werden. Die Ausgleichsgrade durch diese Datenpunkte muss also extrapoliert werden, um den y-Achsenabschnitt zu bestimmen (siehe {numref}`Abbildung %s <photo-4>`). Für Zink ergibt sich damit 

$$W_{A,Zink} = -4.3 \, eV$$

## Innerer Photoeffekt 

Neben dem oben beschriebenen Photoeffekt, der auch äußerer Photoeffekt genannt wird, gibt es einen weiteren Photoeffekt, der etwas schwieriger zu beobachten, aber nicht weniger wichtig ist. Dies ist der innere Photoeffekt. Im Unterschied zum äußeren Photoeffekt, werden hier die Elektronen nicht aus dem Metall herausgelöst, sondern innerhalb eines Festkörpers auf ein höheres Energieniveau angehoben. 
Dies spielt beispielsweise bei Halbleitern eine große Rolle, da hier Elektronen vom Valenzband ins Leitungsband angehoben werden und der zuvor nicht leitende Halbleiter zum Leiter wird (siehe {numref}`Abbildung %s <innerer_photo>`).

```{figure} Bilder/innerer_photo.png
---
width: 80%
alt: Photoeffekt
name: innerer_photo
---
Schematische Darstellung des inneren Photoeffektes
 ```

 ```{figure} https://commons.wikimedia.org/wiki/File:Photodiode-closeup.jpg#/media/Datei:Photodiode-closeup.jpg
---
width: 80%
alt: Photoeffekt
name: R_foto
---
Fotodiode, Quelle: John Maushammer, 2006, CC BY-SA 2.5, https://commons.wikimedia.org/w/index.php?curid=3352608
 ```

Eine Fotodiode (siehe {numref}`Abbildung %s <R_foto>`) ist solch ein homogener Halbleiter, bei dem der innere Fotoeffekt ausgenutzt wird. Häufig wird Silizium hierzu eingesetzt. 
Bei Silizium beträgt die Bandlücke zwischen Valenz- und Leitungsband $W_{Band} = 1.1 \, eV$. Photonen mit der Frequenz 

$$f > \frac{W_{Band}}{h} \approx 2,4 \cdot 10^14 \,Hz$$

lösen hier den inneren Fotoeffekt aus. Diese Frequenz entspricht einer Wellenlänge von 

$$ \lambda = \frac{c}{f} = 1200 \, \longrightarrow \text{ infrarot }$$

Wird der Fotowiderstand mit Licht mit dieser oder einer geringeren Wellenlänge bestrahlt, werden Elektronen aus dem Valenzband in das Leitungsband gehoben und der Fotowiderstand wird leitend.B