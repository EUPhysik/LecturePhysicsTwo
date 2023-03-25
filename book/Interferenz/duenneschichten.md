# Interferenz an dünnen Schichten

Interferenz kann auch an dünnen Schichten entstehen, wie zum Beispiel an Seifenblasen.
Um diese zu berechnen, schaut man sich am besten wieder an, welchen Gangunterschied zwei interferierende Strahlen haben. 
Hierzu werden die Strahlengänge graphisch dargestellt (siehe {numref}`Abbildung %s <interferenz-11>`).


```{figure} Bilder/duenneSchichten_Int.png 
---
width: 80%
alt: Interferenz
name: interferenz-11
---
Darstellung des Strahlenganges an dünnen Schichten
 ```


Der geometrische Wegunterschied zwischen Strahl 1 und Strahl 2 ist:

$$
\begin{equation}
\Delta s = n \cdot \overline{AB} + n \cdot \overline{BC} - \overline{AD} =   2 \cdot n \cdot \overline{AB} - \overline{AD}
\end{equation}
$$(eq:delta_s)

da die Strecken $\overline{AB}$ und $\overline{BC}$ gleich sind und das Licht im Medium die Geschwindigkeit 
$\frac{c}{c_0} = \frac{n_1}{n_2} = n \Leftrightarrow c = c_0 \cdot n $ hat.
Da $n > 1$ tritt in $A$ ein Phasensprung von  $\pi$ auf.

Im folgenden werden die einzelnen Streckenabschnitte berechnet:

__Strecke $\overline{AB}$__

Die Strecke $\overline{AB}$ ergibt sich über trigonometrische Beziehungen zu 

$$cos \left( \theta_2 \right) = \frac{d}{\overline{AB}} \Leftrightarrow \overline{AB} = \frac{d}{cos \left( \theta_2 \right) }$$

__Strecke $\overline{AD}$__
Die Strecke $\overline{AD}$ ergibt sich über trigonometrische Beziehungen zu

$$sin \left( \theta_1 \right) = \frac{\overline{AD}}{\overline{AC}} 
\Leftrightarrow 
\overline{AD} = {\overline{AC}} \cdot sin \left( \theta_1 \right)$$

__weitere Zusammenhänge__
Die Strecke $\overline{AC}$ ist genau doppelt so lang wie die Strecke $\overline{EB}$. Für die Strecke $\overline{EB}$ gilt

$$sin \left( \theta_2 \right) = \frac{\overline{EB}}{\overline{AB}}$$

und

$$tan \left( \theta_2 \right) = \frac{\overline{EB}}{d}

\Leftrightarrow 
{\overline{EB}} = d \cdot tan \left( \theta_2 \right) 

$$

Damit ist 

$$\overline{AC} = 2d\cdot tan \left( \theta_2 \right) $$

__Snellius'sches Brechungsgesetz__
Es gilt

$$\frac{n_1}{n_2} = n = \frac{\sin \left( \theta_1 \right) }{\sin \left( \theta_2 \right) }$$ 

__Zusammensetzen__

Setzt man diese Zusammenhänge in Gleichung {eq}`eq:delta_s` ein, ergibt sich

$$
\begin{eqnarray}
\Delta s &=&  2  n \cdot \overline{AB} - \overline{AD} \\
&=& 2 \cdot   n \cdot\frac{d}{cos \left( \theta_2 \right) } -  \overline{AC} \cdot sin \left( \theta_1 \right) \\
& = & 2 \cdot  n \cdot \frac{d}{cos \left( \theta_2 \right) } -  2d\cdot tan \left( \theta_2 \right)  \cdot sin \left( \theta_1 \right) \\
& = & 2 \cdot   n \cdot \frac{d}{cos \left( \theta_2 \right) } -  2d\cdot \frac{sin \left( \theta_2 \right)}{cos \left( \theta_2 \right)}  \cdot sin \left( \theta_1 \right) \\
& = &  \frac{ 2 \cdot   n \cdot d}{cos \left( \theta_2 \right) } \left(1 -  \frac{sin \left( \theta_2 \right)}{n}  \cdot sin \left( \theta_1 \right)\right) \\
& = &  \frac{ 2 \cdot   n \cdot d}{cos \left( \theta_2 \right) } \left(1 -  \frac{sin \left( \theta_2 \right)}{\frac{\sin \left( \theta_1 \right) }{\sin \left( \theta_2 \right) }}  \cdot sin \left( \theta_1 \right)\right) \\
& = &  \frac{ 2 \cdot   n \cdot d}{cos \left( \theta_2 \right) } \left(1 -  sin^2 \left( \theta_2 \right) \right) \\
& = &  \frac{ 2 \cdot   n \cdot d}{cos \left( \theta_2 \right) } cos^2 \left( \theta_2 \right) \\
& = & 2 \cdot   n \cdot d \cdot cos \left( \theta_2 \right) \\
& = & 2 d \sqrt{n^2- sin^2\left( \theta_1 \right)} \\
\end{eqnarray}
$$

$\Delta s$ ist also die Wegstrecke, die der Strahl 2 im Vergleich zu Strahl 1 zusätzlich zurückgelegt hat. Um den Gangunterschied $\delta$ zwischen den beiden Strahlen zu berechnen, müssen zusätzliche Phasensprünge bei Reflexion berücksichtigt werden. 

```{figure} Bilder/duenneSchichten_Int_2.png
---
width: 80%
alt: Interferenz
name: interferenz-12
---
Fallunterscheidung zur Bestimmung des Gangunterschiedes bei Interferenz an dünnen Schichten. \\
	Fall 1:(links) Medium unter der dünnen Schicht hat einen kleineren Brechungsindex als die dünne Schicht (Bsp. Seifenblasen). \\
	Fall 2:(rechts) Medium unter der dünnen Schicht hat einen größeren Brechungsindex als die dünne Schicht (Bsp. Ölfilm auf Wasser)
 ```

## Fall 1

```{figure} Bilder/Seifenblasen_pillars.jpg
---
width: 80%
alt: Interferenz
name: interferenz-13
---
Interferenz auf Seifenblasen (Quelle: Esa) 
 ```

Bei der Reflexion in Punkt $A$ tritt bei Strahl 1 eine Phasenverschiebung von $\pi$ auf, da $n>1$ ist.
Im Punkt $B$ tritt keine Phasenverschiebung auf, da $n_3 <n$.
Daher ist der Gangunterschied zwischen Strahl 1 und 2

$$
\begin{equation}
\delta = \Delta s - \pi = 2 d \sqrt{n^2- sin^2\left( \theta_1 \right)} - \frac{\lambda}{2}
\end{equation}
$$

Dann ergibt sich konstruktive Interferenz (Maxima) bei:

$$
\begin{equation}
\delta = \Delta s - \pi = 2 d \sqrt{n^2- sin^2\left( \theta_1 \right)} - \frac{\lambda}{2} = n\cdot \lambda 
\end{equation}
$$

mit $n \in {1,2,3,...}$ 

und destruktive Interferenz (Minima) bei 

$$
\begin{equation}
\delta = \Delta s - \pi = 2 d \sqrt{n^2- sin^2\left( \theta_1 \right)} - \frac{\lambda}{2} = \left( n - \frac{1}{2} \right) \cdot \lambda 
\end{equation}
$$

mit $n \in {1,2,3,...}$ 

Videoempfehlung: [Interferenz an dünnen Schichten](https://www.youtube.com/watch?v=V8C_AUzBW3Y)


## Fall 2

```{figure} Bilder/Dieselrainbow.jpg
---
width: 80%
alt: Interferenz
name: interferenz-14
---
Interferenz auf Ölfilm, Quelle: John, CC BY-SA 2.5, https://commons.wikimedia.org/w/index.php?curid=4081809
 ```
Bei der Reflexion in Punkt $A$ tritt bei Strahl 1 eine Phasenverschiebung von $\pi$ auf, da $n>1$ ist.
Im Punkt $B$ tritt ebenfalls Phasenverschiebung auf, da $n_3 > n$.
Daher ist der Gangunterschied zwischen Strahl 1 und 2

$$
\begin{equation}
\delta = \Delta s = 2 d \sqrt{n^2- sin^2\left( \theta_1 \right)} 
\end{equation}
$$

Dann ergibt sich konstruktive Interferenz (Maxima) bei:

$$
\begin{equation}
\delta = \Delta s - \pi = 2 d \sqrt{n^2- sin^2\left( \theta_1 \right)} = n\cdot \lambda 
\end{equation}
$$

mit $n \in {1,2,3,...}$ 

und destruktive Interferenz (Minima) bei 

$$
\begin{equation}
\delta = \Delta s - \pi = 2 d \sqrt{n^2- sin^2\left( \theta_1 \right)} = \left( n - \frac{1}{2} \right) \cdot \lambda 
\end{equation}
$$

mit $n \in {1,2,3,...}$
