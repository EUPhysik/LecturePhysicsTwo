# Transversalwellen

Die physikalischen Eigenschaften einer Transversalwelle lassen sich am einfachsten am Beispiel einer Mechanischen Welle veranschaulichen.
Das Modell einer mechanischen Welle besteht aus einer Reihe von gekoppelten Oszillatoren (beispielsweise Federpendel), die gleichzeitig mit ihren benachbarten Oszillatoren über eine Feder verbunden sind. Eine Auslenkung des ersten Oszillators (auch Störung genannt), führt zu einer zeitlich versetzten Auslenkung des zweiten Oszillators (siehe {numref}`Abbildung %s <mech-welle-1>`)




```{figure} Bilder_Wellen/mech_welle.svg
---
width: 90%
alt: Welle
name: mech-welle-1
---
Darstellung einer Welle, diese ist zeit- und ortsabhängig.  
 ```

Ein oft gezeigtes Experiment zu Transversalwellen ist [hier](https://youtu.be/Ki5oqgyZi8A) zu sehen. 

## Herleichtung der Wellengleichung am Beispiel einer Gitarrensaite

Gesucht ist nun eine Gleichung, die die Position eines Oszillators am Punkt $x$ zum Zeitpunkt $t$ beschreibt. 
Dies wird im Folgenden anhand einer Gitarrensaite beschrieben.

```{figure} Bilder_Wellen/Gitarrensaite.svg
---
width: 90%
alt: Welle
name: gitarre-1
---
Darstellung der Kräfte entlang einer gezupften Gitarrensaite. 
 ```


Eine Gitarrensaite ist kontinuierlich. 
Im Modell kann sie beschrieben werden als eine eindimensionale Saite, welche aus unendlich vielen aneinandergereihten Oszillatoren besteht. Wird diese Saite nun an einer Stelle ausgelenkt, und anschließend losgelassen, breitet sich diese Störung als Welle auf der Saite aus. 

Die wirkenden Kräfte zu einem Zeitpunkt $t$ sind in {numref}`Abbildung %s <gitarre-1>` dargestellt. Entlang der Saite wirkt eine Kraft $F_S$, welche die Spannkraft ist, welche durch die Dehnung der Saite entsteht. Diese ist entsprechend des [Hook'schen Gesetzes](https://www.leifiphysik.de/mechanik/kraft-und-das-gesetz-von-hooke/grundwissen/gesetz-von-hooke) zu verstehen.

Diese Spannkräfte $\vec{F}_S$ werden nun vektoriell zerlegt in ihre $x$- und ihre $y$-Komponenten. Der Betrag von $\left| \vec{F}_S \right|$ ist konstant unter der Annahme, dass die Saite homogen ist und die Federkonstante auf der ganzen Saite konstant ist. 

Die Kräfte in x-Richtung heben sich auf $\Rightarrow \sum F_x = 0$ (die Massenelemente der Saite bewegen sich nur auf und ab, nicht aber nach rechts oder links).

In $y$-Richtung gibt es eine resultierende Kraft, die für die Schwingung sorgt. Die Kraft in y-Richtung ist 

$$F_y = F_S \cdot sin \left(\alpha\right) - F_S \cdot sin \left(\alpha + \Delta \alpha \right)$$

Da die Saite im allgemeinen viel länger ist als die Auslenkung, sind die Auslekungswinkel klein.

Für kleine Winkel gilt die Näherung

$$cos \left(\phi\right) \approx 1$$

und 

$$sin \left(\phi\right) \approx tan \left(\phi\right) \approx \phi$$

Mit dieser Näherung ist 

$$F_y = F_S \left(tan \left(\alpha + \Delta \alpha \right) - tan \left(\alpha  \right) \right) = F_S \left(\left(\alpha+ \Delta \alpha\right) - \left(\alpha\right) \right) = F_S \left(tan \left(\Delta \alpha \right) \right)$$

$tan\left(\alpha\right) = \frac{\Delta y(t,x)}{\Delta x}$ ist dabei gleichzeitig auch die Steigung der Kurve am Punkt $x$.


Mit dem 2. Newton’schen Axiom gilt 

$$F_y = m \frac{\partial^2 y (t,x)}{\partial t^2}$$(gl-1)

Da die Seite eine homogene Masse hat, ist die Dichte der Saite konstant. Da es sich bei der Saite im Modell um ein eindimensionales Objekt handelt, ist die Dichte in diesem Fall eine lineare Massendichte. Diese wird mit $\mu$ bezeichnet und hat die Einheit $\left[ \mu \right] = \frac{kg}{m}$.
Für eine konstante lineare Massendichte entlang der Saite gilt $m = \mu \Delta x$.

Damit ist dann 

$$\Rightarrow F_y = \mu \Delta x \frac{\partial^2 y(t,x)}{\partial t^2}$$(gl-2)

Gleichsetzen von Gleichung {eq}`gl-1` und Gleichung {eq}`gl-2` ergibt

$$\Rightarrow F_y = \mu \Delta x \frac{\partial^2 y(t,x)}{\partial t^2}   = F_S \frac{\Delta y(t,x)}{\Delta x}$$

Diese Gleichung kann umgeformt werden zu

$$\frac{y(t,x)}{\partial t^2}   = \frac{F_S}{\mu} \frac{\Delta y(t,x)}{\Delta x \Delta x}$$(gl-3)

Da $y(t,x)$  eine stetige, differenziertere Funktion ist und infinitesimal kleine Massenelemente betrachtet werden gilt $\Rightarrow \Delta x \rightarrow \partial x$

Damit wird Gleichung {eq}`gl-3` zu 

$$\frac{\partial^2 y(t,x)}{\partial t^2}   = \frac{F_S}{\mu} \frac{\partial^2 y(t,x)}{\partial x^2}$$ 

bzw. 

$$\frac{\partial^2 y(t,x)}{\partial x^2} = \frac{\mu}{F_S} \frac{\partial^2 y(t,x)}{\partial t^2}   $$

In einer komplizierteren Form ist eine Herleitung auch für beliebige Winkel möglich (beispielsweise im [Tipler](https://link.springer.com/book/10.1007/978-3-642-54166-7) zu finden).

Daraus ergibt sich die Differentialgleichung

$$\frac{\partial^2y}{\partial x^2} = \frac{1}{v^2}\frac{\partial^2y}{\partial t^2}$$(eq-wellengleichung-dgl)

mit $v = \sqrt{\frac{F_S}{\mu}}$

## Lösung der Wellengleichung für Transversalwellen

Die Lösung der Wellengleichung {eq}`eq-wellengleichung-dgl` wird Wellenfunktion genannt und beschreibt die Auslenkung eines harmonischen Oszillators zum Zeitpunkt $t$ am Ort $x$. Die Auslenkung eines Oszillators an einem Punkt $P$ ist in {numref}`Abbildung %s <mech-welle-2>` dargestellt. $P$ stellt dabei einen beliebigen Punkt entlang der Saite dar. 

```{figure} Bilder_Wellen/Welengleichung.svg
---
width: 80%
alt: Welle
name: mech-welle-2
---
Darstellung einer Welle, diese ist zeit- und ortsabhängig.  
 ```

Um eine Lösung für die Wellengleichung {eq}`eq-wellengleichung-dgl` zu finden, ist ein Ansatz hilfreich, der auf der Schwingungsgleichung des harmonischen Oszillators basiert. Dieser Ansatz soll dann um eine Ortsabhängigkeit erweitert werden. Schwingung eines harmonischen Oszillators wird beschrieben durch die Schwingungsgleichung 

$$y \left(t \right) = \hat{y} \text{cos} \left(\omega t\right)$$

Aufgrund der Kopplung der Teilchen wandert die Störung mit der Geschwindigkeit $v$ entlang der positiven $x$-Richtung.

Eine Störung erreicht den Punkt P nach der Zeit $\Delta t = \frac{x_P}{v}$. Die Wellenfunktion am Punkt $P$ kann durch Verschiebung der Schwingungsgleichung am Punkt $0$ berechnet werden. Am Punkt $P$ gilt dann

$$y \left(t,x \right) = \hat{y} \text{cos} \left(\omega t - \Delta t\right) 
= \hat{y} \text{cos} \left(\omega \left(t - \frac{x_P}{v}\right)\right)
=\hat{y} \text{cos} \left(\omega t - \omega\frac{x_P}{v}\right)$$

Mit $\omega = \frac{2\pi}{T}$ und $\lambda = v \cdot T$ gilt 

$$\Rightarrow y \left(t,x \right)  =\hat{y} \text{cos} \left(\omega t - \frac{2\pi}{\lambda}x_P\right)$$

Oft wird bei der Beschreibung einer Welle die Wellenzahl $k$ zur Beschreibung der Ortsabhängigkeit verwendet. Die Wellenzahl $k$ ist definiert als $k = \frac{2\pi}{\lambda}$.
Damit ist

$$\Rightarrow y \left(t,x \right) = \hat{y} \,\text{cos} \left(\omega t - k x_P\right)$$ 

Dies kann überprüft werden durch Einsetzen in die Wellengleichung

$$ \frac{\partial^2 y \left(t,x \right) }{\partial t^2} = -\omega^2 y \left(t,x \right)$$

$$ \frac{\partial^2 y \left(t,x \right) }{\partial x^2} = -k^2 y \left(t,x \right)$$

$$\frac{\partial^2y}{\partial x^2} = \frac{1}{v^2}\frac{\partial^2y}{\partial t^2} \Rightarrow - \omega^2 y\left(t,x\right) = \frac{-k^2}{v^2}y\left(t,x\right)
\Leftrightarrow \omega^2 = \frac{k^2}{v^2}\Leftrightarrow k = \frac{\omega}{v}$$

Auch hier kann die allgemeine Lösung generiert werden, in dem eine beliebige Phase zum Argument des Cosinus addiert wird. Diese ist dann durch die Anfangsbedingungen zu bestimmen.

Die allgemeine Lösung, sprich die alllgemeine Wellenfunktion, ist also

$$\Rightarrow y \left(t,x \right) = \hat{y} \,\text{cos} \left(\omega t - k x_P + \phi\right)$$

Wie bei der harmonischen Schwingung ist die harmonische Welle definiert durch

**Definition Harmonische Welle:**
Harmonische Wellen sind periodische Wellen, die mit Hilfe von Sinus- und Kosinusfunktionen und einer einzigen Kreisfrequenz und Kreiswellenzahl ausgedrückt werden können.
Sie werden beschrieben durch dei Gleichung

$$\Rightarrow y \left(t,x \right) = \hat{y} \,\text{cos} \left(\omega t - k x_P + \phi\right)$$


## Ausbreitung von Transversalwellen

Wellen breiten sich räumlich mit einer bestimmten Ausbreitungsgeschwindigkeit aus. Diese Ausbreitungsgeschwindigkeit kann durch die Betrachtung eines konstanten Punktes, beispielsweise eines Wellenbergs, bestimmt werden ({numref}`Abbildung %s <wellenausbreitung-1>`).

```{figure} Videos_Wellen/transversalwelle2.mp4 
---
width: 90%
alt: Welle
name: wellenausbreitung-1
---
Ausbreitung einer Transversalwelle, der rote Pfeil zeigt die Ausbreitungsgeschwindigkeit der Welle.  
 ```

Die Wellenfunktion 

$$y \left(t,x \right) = \hat{y} \,\text{cos} \left(\omega t - k x_P\right)$$

ist konstant, wenn die Phase $\omega t - k x_P$ konstant ist. Um die Ausbreitungsgeschwindigkeit zu bestimmen, muss also die Geschwindigkeit bestimmt werden, bei der $\omega t - k x_P$ konstant ist. Dazu wird die zeitliche Ableitung dieser Funktion betrachtet

$$\Rightarrow \frac{d}{dt} \left( \omega t - kx\right) = 0 \Leftrightarrow \omega - k\frac{dx}{dt} = 0 \Leftrightarrow v_{ph} = \frac{\omega}{k}$$

mit der Kreisfrequenz $\omega = \frac{2\pi}{T} = 2 \pi f$ und der Wellenzahl $k = \frac{2\pi}{\lambda}$ gilt der Zusammenhang 

$$v_{ph} = \lambda f$$



## Energietransport von Transversalwellen

Eine Welle, die sich längs einer Saite ausbreitet, transportiert in ihrer Ausbreitungsrichtung mechanische Energie (Schwingungsenergie). Wie bereits bei der Herleitung von Gleichung {eq}`eq-wellengleichung-dgl` gezeigt gilt für die wirkende Kraft in $y$-Richtung

$$F_y = F_S \cdot sin \left(\alpha\right) \approx F_S \cdot tan \left(\alpha\right) = F_S \frac{\partial y}{\partial x}$$

Wie in der Mechanik gelernt, ist die Mechanische Leistung definiert als

$$P = \frac{dE}{dt} = F \cdot v$$

Damit kann die Leistung berechnet werden:

$P = F \cdot v = F_y \cdot v_y = F_y \frac{\partial y}{\partial t} = F_S \frac{\partial y}{\partial x} \frac{\partial y}{\partial t}$


mit $ \frac{\partial y \left(t,x \right) }{\partial t} = -\omega \cdot \hat{y} \cdot sin \left(\omega t - kx\right)$

und $ \frac{\partial y \left(t,x \right) }{\partial x} = k \cdot \hat{y} \cdot sin \left(\omega t - kx \right)$

ist dann

$$P = F_S \cdot \frac{\partial y}{\partial x} \frac{\partial y}{\partial t} = - F_S \cdot \omega \cdot k \cdot \hat{y}^2 \cdot sin^2 \left(\omega t - kx\right)$$

Die mittlere Leistung $\left< P \right>$ ergibt sich durch Integration über eine Schwingungsdauer $T$

$\left<P\right> = \frac{1}{T} \int_0^T F_S \cdot\omega \cdot k \cdot \hat{y}^2 \cdot sin^2 \left(\omega t - kx\right) \, dt
= \frac{F_S \cdot \omega \cdot k \cdot \hat{y}^2}{T} \int_0^T sin^2 \left(\omega t - kx\right) \, dt$

$= F_S\frac{\omega \cdot k \cdot \hat{y}^2}{2T}T = F_S\frac{\omega \cdot k \cdot \hat{y}^2}{2}$

mit $v = \sqrt{\frac{F_S}{\mu}}$ und $\omega = v_{ph}\cdot k$ wird 

$$F_S \cdot k = \mu v_{ph}^2\frac{\omega}{v_{ph}} = \omega \mu v_{ph}$$

Somit ist die mittlere Leistung 

$$\left<P\right> = \frac{1}{2} \left( \mu v_{ph} \omega^2 \hat{y}^2\right)$$

Aus dieser mittleren Leistung kann die im Mittel transportierte Energie berechnet werden. 
Die mittlere transportierte Energie ist

$$\left< E\right> = \left<P\right> \Delta t = \frac{1}{2} \left( \mu v_{ph} \omega^2 \hat{y}^2\right)  \Delta t = \frac{1}{2} \left( \mu \omega^2 \hat{y}^2\right)  v_{ph}\Delta t = \frac{1}{2} \left( \mu \omega^2 \hat{y}^2\right)  \Delta x $$
