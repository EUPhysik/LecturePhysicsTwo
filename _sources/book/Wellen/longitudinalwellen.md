# Longitudinalwellen

Longitudinalwellen sind anders strukturiert als Transversalwellen. Bei ihnen stehen Schwingungs- und Ausbreitungsrichtung senkrecht zueinander. Longutidinalwellen sind Druckwellen und kommen nur in einem Medium vor, dies bedeutet es sind kurzeitige Verdichtungen des Mediums in Ausbreitungsrichtung (siehe {numref}`Abbildung %s <long-welle-1>`). 

Beispielsweise Schallwellen sind Longitudinalwellen, die Frequenz der Schallwelle bestimmt die Tonhöhe. Seismische Wellen können longitudinal sein, man bezeichnet sie dann als P-Wellen, sie können auch transversal sein, man bezeichnet sie dann als S-Wellen. Wasserwellen sind oft eine Kombination aus longitudinalen und transversalen Wellen.

```{figure} Bilder_Wellen/Schallwelle.svg
---
width: 90%
alt: Welle
name: long-welle-1
---
Darstellung einer Longitudinalwelle (Druckwelle).  
 ```

## Wellengleichung für Longitudinalwellen

Um die Wellengleichung für Longitudinalwellen herzuleiten wird ein etwas anderes Modell als bei Transversalwellen benötigt. Dieses Modell ist in {numref}`Abbildung %s <long-welle-2>` dargestellt. 

Kolbenbewegung drückt Luftmoleküle zusammen und erzeugt lokale Kompression (Druckerhöhung), welche dann als longitudinale Welle weitertransportiert wird. 
Die einzelnen Luftmoleküle schwingen dabei um ihre Ruhelage (in x-Richtung). Dadurch erfolgt nur Energie- und kein Materietransport. 

Wenn der Kolben ruckartig mit der konstanten Geschwindigkeit $v_K$ nach rechts geschoben wird, dann hat sich nach einem kurzen Moment $\Delta t$ der Kolben um die Strecke $v_K \Delta t$ bewegt, und die gesamte Luft innerhalb der Entfernung $v_S \Delta t$ von der Anfangslage des Kolbens bewegt sich mit der Geschwindigkeit $v_S$ nach rechts (siehe {numref}`Abbildung %s <long-welle-2>`).

```{figure} Bilder_Wellen/Schallwelle2.svg
---
width: 90%
alt: Welle
name: long-welle-2
---
Molekülbewegung bei einer Longitudinalwelle (Druckwelle).  
 ```


Zwischen Kraftstoß und Impuls gilt der Zusammenhang

$$\left< F\right> = \frac{\Delta p}{\Delta t} \Leftrightarrow \left< F\right> \Delta t = \Delta p = m v_K = \rho \cdot V v_K = \rho \, A v_S \Delta t \, v_K$$(eq-long-1)

wobei $A v_S \Delta t$ das Volumen der unkomprimierten Luft ist.
Darüber hinaus gilt $\Delta p = \frac{F}{A} \Leftrightarrow F = A \, \Delta p$

Das [Kompressionsmodul](https://de.wikipedia.org/wiki/Kompressionsmodul) (von Luft) ist definiert als

$$K = -\frac{\Delta p}{\Delta V / V}$$

Damit lässt sich schreiben

$$\Delta p = - K\frac{\Delta V}{V} = -K \frac{- A v_K \Delta t}{A v_S \Delta t} = K\frac{v_K}{v_S} \Rightarrow F = A \Delta p = A K\frac{v_K}{v_S}$$(eq-long-2)

Gleichsetzen von {eq}`eq-long-1` und {eq}`eq-long-2` ergibt

$$ A K\frac{v_K}{v_S} = \rho \, A v_S \Delta t \, v_K \Leftrightarrow v_S = \sqrt{\frac{K}{\rho}}$$

Die Wellengleichung für Schallwellen lässt sich ebenfalls aus dem zweiten Newton’schen Axiom herleiten. Für eine eindimensionale Schallwelle gilt (analog zur Transversalwelle)

$$\frac{\partial^2s}{\partial x^2} = \frac{1}{v_S^2}\frac{\partial^2s}{\partial t^2}$$

Hierbei ist jedoch $s(x,t)$ die Auslenkung des Mediums in $x$-Richtung (nicht in $y$-Richtung wie bei der Transversalwelle !!) und $v_S = \sqrt{\frac{K}{\rho}}$ die Schallgeschwindigkeit im Medium, in dem sich die Welle ausbreitet. 

## Energietransport von Longitudinalwellen

Wie auch bei Transversalwellen kann auch bei Longitudinalwellen die mittlere transportierte Energie berechnet werden. Hier können die Erkenntnisse aus [ Kapitel Energietransport von Transversalwellen](../Wellen/transversalwellen.html#energietransport-von-transversalwellen) verwendet werden, um die entsprechenden Größen für Longitudinalwellen zu bestimmen, müssen lediglich einige Ersetzungen gemacht werden. 

Die mittlere transportierte Energie ist $\left< E\right>  = \frac{1}{2} \left( \mu \omega^2 \hat{y}^2\right)  \Delta x $

Für die Betrachtung von Schallwellen werden folgende Ersetzungen gemacht:

$\mu \Delta x \longrightarrow \rho_0 \Delta V $
und
$\hat{y} \longrightarrow s_{max}$

Damit gilt für Schallwellen $\left< E\right>  = \frac{1}{2} \rho_0 \omega^2 s_{max}^2 \Delta V $

Die mittlere Energiedichte ist dann

$$\frac{\left< E\right>}{\Delta V} = \frac{1}{2} \rho_0 \omega^2 s_{max}^2 $$