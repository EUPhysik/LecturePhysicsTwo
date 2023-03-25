# Wellenausbreitung an Hindernissen

Wenn Wellen auf Hindernisse treffen, wechselwirken die Hindernisse mit den Wellen und verändern diese. Eine Berechnung dieser Effekte kann über die Wellengleichung erfolgen.
Eine leichter verständliche Alternative, welche auch hier im Rahmen der Vorlesung betrachtet wird, sind konstruktive Methoden, welche durch   Huygens und Fermat entwickelt wurden. Diese werden im Folgenden vorgestellt und darauf aufbauend die Effekte Beugung, Brechung und Reflexion betrachtet. 

## Huygen'sches Prinzip

Das Huygen'sches Prinzip ist ein geometrisches Prinzip.
Jeder Punkt einer bestehenden Wellenfront ist Ausgangspunkt einer neuen kugelförmigen Elementarwelle, die sich mit derselben Geschwindigkeit und Frequenz ausbreitet wie die ursprüngliche Wellenfront im betreffenden Medium. Die Einhüllende aller Elementarwellen ergibt die Wellenfront zu einem späteren Zeitpunkt (siehe {numref}`Abbildung %s <einhuellende-3>`). 


```{figure} Bilder_Wellen/einhuellende.svg
---
width: 45%
alt: Welle
name: einhuellende-3
---
Einhüllende einer Punktwelle.  
 ```


## Fermat’sches Prinzip

Das Fermat’sche Prinzip besagt, dass der Weg, den eine Welle von einem Punkt zu einem anderen einschlägt, stets derjenige ist, bei dem die dafür benötigte Zeitspanne minimal ist. 

Anschaulich kann dieses Prinzip hergeleitet werden mit Hilfe des Rettungsschwimmerprinzips. Dies ist in {numref}`Abbildung %s <fermat-1>` zu sehen. Der Rettungsschwimmer möchte einen Ertrinkenden retten und dazu diesen möglichst schnell erreichen. An Land kann er deutlich schneller rennen, als er im Wasser schwimmen kann. Also überlegt er, wie er denjenigen Weg, der die gesamte benötige Zeit minimiert.

```{figure} Bilder_Wellen/fermat.svg
---
width: 80%
alt: Welle
name: fermat-1
---
Einhüllende einer Punktwelle.  
 ```

Die gesamte zurückgelegte Strecke ist

$$s_{ges} = s_{Land} + s_{Wasser} = v_{Land}\cdot t_{Land} + v_{Wasser}\cdot t_{Wasser} = v_L \cdot t_L + v_W \cdot t_W$$

und die dazu benötigte Zeit ist

$$t_{ges} = t_{Land} + t_{Wasser} = t_L + t_W$$

Dabei gilt für die Teilstrecken

$$s_L = \left(x_L^2 + y_L^2\right)^{1/2}$$

$$s_W = \left(x_W^2 + y_W^2\right)^{1/2} = \left(\left( x - x_L \right)^2 + \left(y - y_L\right)^2\right)^{1/2}$$

Damit ist die Gesamtzeit

$$\Rightarrow t_{ges} = \frac{s_L}{v_L} + \frac{s_W}{v_W} = \frac{1}{v_L} \left(x_L^2 + y_L^2\right)^{1/2} + \frac{1}{v_W}\left(\left( x - x_L \right)^2 + \left(y - y_L\right)^2\right)^{1/2}$$

Da $x, \, y, \, y_1 = \text{konst.}$, wie in {numref}`Abbildung %s <fermat-1>` dargestellt ist, konstant ist, hängt $t_{ges}$ nur von $x_L$ ab. Um das Minimum dieser Funktion $t_{ges} \left( x_L \right)$ zu bestimmen, muss die Ableitung gebildet und $=0$ gesetzt werden. 

$$\frac{dt_{ges} \left( x_L\right) }{dx_L} = 0
\Leftrightarrow \frac{d}{dx_L}\left( \frac{1}{v_L} \left(x_L^2 + y_L^2\right)^{1/2} + \frac{1}{v_W}\left(\left( x - x_L \right)^2 + \left(y - y_L\right)^2\right)^{1/2} \right)
$$

$$\Leftrightarrow 
\frac{1}{2}\frac{1}{v_L} \left(x_L^2 + y_L^2\right)^{-1/2} 2 x_L
+ \frac{1}{2}\frac{1}{v_W}\left(\left( x - x_L \right)^2 + \left(y - y_L\right)^2\right)^{-1/2}\left(-2 \left(x-x_L\right)\right) 
= 0$$

$$\Leftrightarrow 
\frac{1}{v_L} \frac{x_L}{\sqrt{x_L^2 + y_L^2}} 
-\frac{1}{v_W} \frac{x-x_L}{\sqrt{ \left(x - x_L \right)^2 + \left(y - y_L\right)^2}} 
= 0$$

mit $sin \left(\alpha \right) = \frac{x_L}{\sqrt{x_L^2 + y_L^2}}$ und $sin \left( \beta \right) = \frac{x-x_L}{\sqrt{ \left(x - x_L \right)^2 + \left(y - y_L\right)^2}}$ wird dies zu

$$\frac{sin \left( \alpha \right)}{v_L} -\frac{sin \left( \beta \right)}{v_W} = 0
\Leftrightarrow \frac{sin \left( \alpha \right)}{v_L} = \frac{sin \left( \beta \right)}{v_W}$$

## Beugung

Die Beugung oder Diffraktion ist die Ablenkung von Wellen an einem Hindernis. Durch Beugung kann sich eine Welle in Raumbereiche ausbreiten, die auf geradem Weg durch das Hindernis versperrt wären. Jede Art von physikalischen Wellen kann Beugung zeigen. 

Beugung kann unter anderem gut beobachtet werden, wenn geometrische Strukturen eine Rolle spielen, deren Größe mit der Wellenlänge der verwendeten Wellen vergleichbar ist. Abbildung {numref}`Abbildung %s <beug-1>` die Beugung einer Welle an einer kleinen Öffnung. 

 ```{figure} Bilder_Wellen/beugung.gif
---
width: 60%
alt: Beugung
name: beug-1
---
Beugung einer Welle an einer punktförmigen Öffnung, https://physics.stackexchange.com
 ```

Beugung kann mit Hilfe des Huygen'schen Prinzips erklärt werden. An der punktförmigen Öffnung trifft die Welle von links auf das Hindernis und kann sich nicht weiter nach rechts ausbreiten. Da nach dem Huygen'schen Prinzip jeder Punkt einer bestehenden Wellenfront wieder Ausgangspunkt einer neuen kugelförmigen Elementarwelle ist, breitet sich von der punktförmigen Öffnung eine neue Welle aus. 



## Reflexion und Transmission

Trifft eine Welle auf ein Hindernis, welches lichtdurchlässig ist, kann ein Teil der Welle reflektiert oder durchgelassen (transmittiert) werden. Auch diese beiden Phänomene können mit Hilfe des Huygen'schen Prinzips erklärt werden.

{numref}`Abbildung %s <ref-1>` zeigt die Reflexion eines Welle an einer ebenen Fläche. Da die Wellen unter einem Winkel auf die Oberfläche auftreffen und die Ausbreitungsgeschwindigkeit der Welle endlich ist, treffen die Wellenberge im Bild links einen kurzen Zeitpunkt $\Delta t = \frac{\lambda}{c}$ eher auf die Oberfläche auf. Dies führt dazu, dass sie diesen Zeitpunkt früher reflektiert werden. 
Der Eintrittswinkel und der Relexionswinkel (jeweils gemessen zur senkrechten) sind gleich. 

 ```{figure} Bilder_Wellen/Reflexion.svg
---
width: 90%
alt: Reflexion
name: ref-1
---
Reflexion einer Welle nach dem Huygen'schen Prinzip
 ```

Auch bei der Transmission treffen die Wellenberge im Bild links einen kurzen Zeitpunkt $\Delta t = \frac{\lambda}{c}$ eher auf die Oberfläche auf. Da sich bei Transmission das Medium durch dass die Wellen laufen ändert, ändert sich mit Durchtritt durch die Grenzfläche auch die Ausbreitungsgeschwindigkeit. Daher ändert sich auch die Ausbreitungsrichtung der Welle im Medium (siehe {numref}`Abbildung %s <trans-1>`).

  ```{figure} Bilder_Wellen/Transmission.svg
---
width: 90% 
alt: Reflexion
name: trans-1
---
Transmission einer Welle nach dem Huygen'schen Prinzip
 ```

Bei der Reflexion einer Welle kann zusätzlich ein Phasensprung von $\frac{\pi}{2}$ auftreten und zwar immer dann, wenn die Ausbreitungsgeschwindigkeit der Welle im Medium an dem die Reflexion stattfindet, geringer ist. Dies ist in {numref}`Abbildung %s <ref-trans-1>` dargestellt. 
In {numref}`Abbildung %s <ref-trans-1>` ist zu erkennen, dassein Teil des Wellenbergs wieder zurück läuft, und ein weiterer Teil bewegt sich weiter. 
Der reflektierte Wellenberg ist im Unterschied zum transmittierten invertiert, es ist ein  Phasensprung von $\frac{\pi}{2}$ aufgetreten.

 ```{figure} https://upload.wikimedia.org/wikipedia/commons/3/30/Partial_transmittance.gif
---
width: 70%
alt: Reflexion
name: ref-trans-1
---
Reflexion und Transmission einer Welle, Von Oleg Alexandrov, Gemeinfrei, https://commons.wikimedia.org/w/index.php?curid=3148138
 ```

Bei Transmission tritt kein Phasensprung auf, dies wird auch als Brechung bezeichnet.

## Brechung

Bei der Brechung ändert sich die Ausbreitungsrichtung einer Welle durch die Änderung der Ausbreitungsgeschwindigkeit in dem Medium das die Welle durchläuft. 
Die Änderung der Ausbreitungsrichtung kann mit Hilfe des Fermat’sches Prinzip berechnet werden. 
Wie [weiter oben](#fermatsches-prinzip) gezeigt gilt

$$\frac{sin \left( \alpha \right)}{v_L} = \frac{sin \left( \beta \right)}{v_W}$$

$\alpha$ ist der Einfallswinkel und $\beta$ ist der Reflexionswinkel. $v_L$ und $v_W$ sind die Ausbreitungsgeschwindigkeiten in den verschiedenen Medien. Damit ist der Reflexionswinkel

$$sin \left( \beta \right) = sin \left( \alpha \right) \frac{v_W}{v_L}$$

oder auch

$$\beta = arcsin \left( sin \left( \alpha \right) \frac{v_W}{v_L} \right)$$

