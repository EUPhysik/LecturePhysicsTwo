# Optische Instrumente

Optische Instrumente verwenden Spiegel oder Linsen, um Objekte zu vergrößern. 

## Auge

Das Auge ist ein optisches Instrument, welches wir täglich automatisch verwenden. Im Wesentlichen besteht ein Auge aus einer Sammellinse mit variabler Brennweite. Um einen Gegenstand zu betrachten, wird die Brennweite des Auges so eingestellt, dass ein scharfes Bild auf der Netzhaut auf der Rückseite des Auges entsteht ({numref}`Abbildung %s <auge>`). 

```{figure} Bilder_geooptik/auge.svg
---
width: 100%
alt: Auge
name: auge
---
Bildentstehung am Auge.
 ```

Sehr weit entfernte Gegenstände ($g\rightarrow \infty$) kommen als quasi parallele Lichtstrahlen am Auge an. Diese können vom Auge fokussiert werden und es gilt

$$\frac{1}{f} = \frac{1}{g} + \frac{1}{b} \stackrel{g \rightarrow \infty}{=} \frac{1}{f} = \frac{1}{b} \Leftrightarrow b = f$$

Das Bild entsteht dann bei entspanntem Auge mit einer Bildweite, die er Brennweite des (entspannten) Auges entspricht. 

## Lupe
Eine Lupe ist eine Sammellinse, mit deren Hilfe die scheinbare Größe eines Gegenstandes vergrößern kann. Dies geschieht, wenn sich der zu vergrößernde Gegenstand innerhalb der Brennweite $f$ erzeugt eine Lupe ein aufrechtes virtuelles Bild des Gegenstandes. 

```{figure} Bilder_geooptik/lupe.svg
---
width: 100%
alt: Lupe
name: lupe
---
Vergrößerung bei der Lupe.
 ```

Bei der Gegenstandshöhe $G$ ergibt sich die Bildhöhe $B = V\cdot G$, wobei $V$ die Vergrößerung ist. Für den Winkel $\varepsilon$, unter dem das Bild dem Auge erscheint, gilt näherungsweise siehe ({numref}`Abbildung %s <lupe>`):

$$\varepsilon = \frac{VG}{\left| b\right|} = \frac{\left| b\right|}{g}\frac{G}{\left| b\right|} = \frac{G}{g} \Leftrightarrow V = \frac{\left|b\right|}{g}$$

Ein Lupe zeigt das vergrößerte Bild unter genau dem gleichen Winkel unter dem der Gegenstand erschiene, wenn die Linse entfernt würde, während Gegenstand und Auge in ihren Positionen blieben.
Das sich mit der Sammelinse ergebende Bild auf der Netzhaut ist daher ebenso groß, wie wenn der Gegenstand ohne Sammellinse betrachtet würde. 
Allerdings ist der Gegenstand so nah vor dem Auge, dass das Auge ohne Lupe einen so nahen Abstand gar nicht mehr fokussieren kann. Das virtuelle Bild ist weiter vom Auge entfernt und kann fokussiert werden. {numref}`Abbildung %s <lupe-2>` zeigt die Abbildung eines Gegenstandes ohne Lupe. 



```{figure} Bilder_geooptik/ohne_lupe.svg
---
width: 100%
alt: Lupe
name: lupe-2
---
Vergleich mit der Abbildung des Bildes ohne Lupe. 
 ```

Der Punkt, den das Auge gerade noch durch Minimierung der Brennweite des Auges fokussieren kann, wird als Nahpunkt des Auges bezeichnet. Dieser liegt im Durchschnitt bei einem Abstand von $s_0 = 25 \, cm$ vom Auge entfernt. Wird ein Gegenstand der Größe $G$ in diesem Abstand vor dem Auge platziert, so ist er unter dem Winkel 

$$\varepsilon_0 = \frac{G}{s_0}$$

vom Auge zu sehen.
Die Lupe sorgt dafür, dass der Gegenstand näher an das Auge herangeholt werden kann, sie funktioniert so lange, wie sich der Gegenstand innerhalb der Brennweite befindet. Je näher der Gegenstand an die Brennweite herangerückt wird, desto größer ist die Vergrößerung. Der maximale Betrachtungswinkel liegt daher bei

$$\varepsilon = \frac{G}{f}$$ 

Die Winkelvergrößerung der Lupe ist dann

$$V = \frac{\varepsilon}{\varepsilon_0} = \frac{G/f}{G/s_0} = \frac{s_0}{f}$$

## Mikroskop

Ein Mikroskop besteht aus mindestens zwei Konvexlinsen. Damit lässt sich eine starke Vergrößerung erreichen, mit der sehr kleine Gegenstände betrachtet werden können. 
Die erste Linse wird als Objektiv bezeichnet, die zweite als Okular.
Das Objektiv erzeugt ein reelles, vergrößertes und gespiegeltes Zwischenbild $B^\prime$ des Gegenstands.
Das Okular funktioniert wie eine Lupe, mit deren Hilfe das Zwischenbild $B^\prime$ betrachtet werden kann, welches vom Objektiv erzeugt wird. 
So wird aus dem Zwischenbild $B^\prime$ ein stark vergrößertes Bild $B$ erzeugt, welches dann mit dem Auge betrachtet werden kann (siehe ({numref}`Abbildung %s <mikroskop>`).
Um das Zwischenbild so stark wie möglich zu vergrößern, wird das Zwischenbild möglichst nah am Brennpunkt platziert. 

<!-- Das vom Objektiv erzeugte Zwischenbild befindet sich am Brennpunkt des Okulars, sodass die Lichtstrahlen aus dem Okular parallel austreten, als kämen sie aus großer Entfernung  -->

```{figure} Bilder_geooptik/mikroskop.svg
---
width: 100%
alt: Mikroskop
name: mikroskop
---
Vergrößerung bei einem einfachen Mikroskop.
 ```

Der Abstand zwischen dem zweiten Brennpunkt des Objektivs und dem ersten Brennpunkt des Okulars heißt Tubuslänge $l$. 

Die Vergrößerung des Objektivs ist

$$V_{obj} = \frac{B^\prime}{G} $$

Für den Winkel $\beta$ gilt

$$ tan \left( \beta\right) = \frac{G}{f_{Ob}} = \frac{B}{l}$$

Damit gilt für die Vergrößerung des Objektivs

$$V_{Ob} = \frac{B}{G} = \frac{l}{f_{Ob}}$$

Die Vergrößerung des Okulars entspricht der Lupe mit

$$V_{Ok} = \frac{s_0}{f_{Ok}}$$

Bei der Berechnung der Winkelvergrößerung des Mikroskops wird immer ein Bezug zu einer sogenannten Standartsituation genommen. Dies bezieht sich auf einen standartisierten Abstand des Auges vom Gegenstand und einer standartisierten Tubuslänge. Hierbei Abstand des Auges vom Gegenstand auf $s = 25 \, cm$ und die Tubuslänge auf $l = 160 \, mm$ festgelegt. 

Die gesamte Vergrößerung des Mikroskops ist damit

$$V_M = V_{Ob} \cdot V_{Ok} = \frac{l}{f_{Ob}} \cdot \frac{s_0}{f_{Ok}} = \frac{l \cdot s_0}{f_{Ob}\cdot f_{Ob}}$$

## Linsenteleskop

Mit einem Teleskop werden Gegenstände betrachtet, die weit entfernt und meist groß sind. Die Wirkung des Teleskops besteht darin, dass es ein reelles Bild des Gegenstands erzeugt, das dem Betrachter viel näher ist als der Gegenstand. 

Ein Teleskop erzeugt ein reelles Bild eines Gegenstandes, das dem Betrachter viel näher ist als der Gegenstand. 
Ein Linsenteleskop besteht aus zwei Sammellinsen.
Die eine dient als Objektiv und erzeugt ein reelles, umgekehrtes Bild des Gegenstands. 
Die zweite Linse ist das Okular und wird wieder wie eine Lupe verwendet. 
Da der Gegenstand sehr weit entfernt ist, liegt das vom Objektiv entworfene Bild in dessen Brennebene, und die Bildweite entspricht der Brennweite $f_{Ob}$. 
Das Okular wird so platziert, dass das vom Objektiv entworfene Bild in seiner Brennebene liegt, also von ihm den Abstand $f_{Ok}$ hat. 

$$tan \left( \varepsilon_{Ob}\right) = \frac{B}{f_{Ob}} \approx \varepsilon_{Ob}$$

$$tan \left( \varepsilon_{Ok}\right) = \frac{B}{f_{Ok}} \approx \varepsilon_{Ok}$$

$$V = \frac{\varepsilon_{Ok}}{\varepsilon_{Ob}} = \frac{f_{Ob}}{f_{Ok}}$$

```{figure} Bilder_geooptik/keplerfernrohr.svg
---
width: 100%
alt: Teleskop
name: teleskop
---
Vergrößerung bei einem einfachen Linsenteleskop.
 ```

<!-- 
## Spiegelteleskop

In der Astronomie werden oft sehr lichtschwache Objekte beobachtet, die oft gar nicht so klein sind (Nebel, Galaxien)
Daher ist bei astronomischen Teleskopen die Lichtstärke entscheidend.
Große Linsen sind schwierig herzustellen und sehr schwer, daraus resultieren auch mechanische Probleme.
Daher sind die großen Teleskope fast immer Spiegelteleskope.


```{figure} Bilder_geooptik/spiegelteleskop.svg
---
width: 100%
alt: Mikroskop
name: mikroskop
---
Vergrößerung bei einem einfachen Mikroskop.
 ```
 -->