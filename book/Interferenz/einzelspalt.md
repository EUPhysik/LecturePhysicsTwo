# Interferenz an einem Spalt

```{figure} https://upload.wikimedia.org/wikipedia/commons/1/17/Beugung_am_Einfachspalt_-_gruen.jpg
---
width: 60%
alt: Interferenz
name: interferenz-2
---
Interferenzbild am Einzelspalt (Quelle: Oliver Kurmis, CC BY-SA 2.0 de, https://commons.wikimedia.org/w/index.php?curid=89488364) 
 ```

Beugungseffekte kann man insbesondere sichtbar machen, wenn man Licht verwendet, welches aus nur einer Wellenlänge besteht und gleichphasig ist. Man spricht dann von monochromatischem (Licht mit einer Wellenlänge ) und kohärentem (Licht mit gleicher Phase) Licht. 
Trifft monochromatisches und kohärentes Licht  auf einem schmalen (nicht punktförmigen) Spalt, so entsteht auf einem dahinter liegenden Schirm ein Muster aus hellen und dunklen Streifen, ein sogenanntes Interferenzmuster (siehe {numref}`Abbildung %s <interferenz-2>`).

Dieses Interferenzmuster resultiert aus der abwechselnd konstruktiven bzw. destruktiven Überlagerung der einzelnen Teilwellen. Mit Hilfe des Wellenmodells kann die Intensitätsverteilung dieses Interferenzmusters berechnet werden, was ein guter Beleg für das Wellenmodell des Lichtes ist. 

 Die Berechnung dieses Interferenzmusters wird im folgenden gezeigt. 

 ```{figure} Bilder/Einzelspalt_3.png
---
width: 80%
alt: Interferenz
name: interferenz-3
---
Schematische Darstellung der Wellenausbreitung an einem schmalen (nicht punktförmigen) Spalt. Die zusätzliche zurückgelegte Wegstrecke der unteren Wellen ist abhängig vom Winkel $\theta$ unter dem auf dem Schirm beobachtet wird.
 ```

 ```{figure} Bilder/Einzelspalt_4.png
---
width: 80%
alt: Interferenz
name: interferenz-4
---
Schematische Darstellung der Zerlegung des Lichtstrahls, welcher durch den Spalt fällt in N Teilstrahlen. Jeder Teilstrahl $l$ legt im Vergleich zum obersten Strahl die zusätzliche Wegstrecke $\delta_l$ zurück.
 ```

{numref}`Abbildung %s <interferenz-3>` zeigt die schematische Darstellung der Wellenausbreitung an einem schmalen Spalt mit endlicher Breite $b$. Der Lichtstrahl wird im Modell in mehrere Teilstrahlen aufgeteilt. Diese Teilstrahlen legen in Abhängigkeit vom Beobachtungswinkel $\theta$ eine zusätzliche Wegstrecke zurück. Auf einem (im Vergleich zur Spaltbreite) weit entfernten Schirm überlagern sich die Wellen. 

Zur Berechung der Überlagerung der Wellen müssen die Teilwellen bestimmt und aufsummiert werden. 
Zunächst wird der Lichtstrahl wie in {numref}`Abbildung %s <interferenz-4>` dargestellt, in $N+1$ Teilstrahlen aufgeteilt (Nummerierung $l= 0,1,...,N$). Zwei benachbarte Strahlen haben dann die Phasendifferenz 

$$\Delta \phi = k \delta_2 
= \frac{2 \pi}{\lambda}\frac{b}{N} sin \left( \theta \right)  = \frac{1}{N}\Delta \phi_{ges}$$

wobei $\Delta \phi_{ges}$ die Phasenverschiebung zwischen den beiden äußeren Wellen ist. 

Die 0-te und $i$-te Welle haben dann die Phasendifferenz 

$$\Delta \phi_l = k \delta_l
= \frac{2 \pi}{\lambda}\frac{l \cdot b}{N} sin \left( \theta \right) = l\cdot \Delta \phi$$

Da der Lichtstrahl sich natürlich nicht in $N$ Teilstrahlen aufteilt, sondern sich prinzipiell unendlich viele Teilstrahlen aufteilt, betrachtet man die infinitesimalen Phasendifferenzen

 $$d \phi (y) = k \delta_l
= \frac{2 \pi}{\lambda}b \cdot sin \left( \theta \right) \frac{y}{b}$$

Für die weitere Herleitung ist der Übergang ins komplexe sinnvoll. Um Verwechselungen zu vermeiden, wird $i$ als komplexe Zahl verwendet.

$$z_l \left(t,x \right) 
= \hat{z}_l \,e^{i\left(\omega t - k x  + \Delta \phi_l\right)}
=\ \hat{z}_l e^{i \left(\omega t - k x \right)}\,e^{i\left(\Delta \phi_i\right)}
= \hat{z}_l e^{i \left(\omega t - k x \right)} \,e^{i \frac{2 \pi}{\lambda}\frac{b}{N} sin \left( \theta \right)}$$

wobei jede der Teilwellen eine Amplitude von $\frac{\hat{z}}{N}$. 
Nun werden die Teilwellen aufsummiert, was für $N \rightarrow \infty$ in das Integral über die Breite $b$ des Spaltes für $y = 0..n$ übergeht

$$\longrightarrow 
z \left(t,x \right)
= \frac{\hat{z}}{b} e^{i \left(\omega t - k x \right)}
\,
\int_{0}^b e^{i
\frac{2 \pi}{\lambda}\cdot y \cdot sin \left( \theta \right)} dy
$$

Für das Integral gilt


$$
\int_{0}^b e^{i
\frac{2 \pi}{\lambda}\cdot y \cdot sin \left( \theta \right)} dy
= \left(i \frac{2 \pi}{\lambda}sin(\theta)\right)^{-1} 
\left. e^{i
\frac{2 \pi}{\lambda}\cdot b sin \left( \theta \right)} \right|_0^y
= \left(i \frac{2 \pi}{\lambda}sin(\theta)\right)^{-1} 
\left( e^{i
\frac{2 \pi}{\lambda}\cdot b sin \left( \theta \right)} - 1\right)
$$

Damit ist die resultierende Welle

$$
\longrightarrow 
z \left(t,x \right)
= \frac{\hat{z}}{b} e^{\left(\omega t - k x \right)}
\,
\left(i \frac{2 \pi}{\lambda}sin(\theta)\right)^{-1} 
\left( e^{i
\frac{2 \pi}{\lambda}\cdot b sin \left( \theta \right)} - 1\right)  
= \hat{z}_{int} e^{i\left(\omega t - k x \right)}
$$

wobei $\hat{z}_{int} $ die Amplitude der Interferenz ist. Die Intensität einer Welle ist $I \propto \text{Amplitude}^2$. Da wir hier eine komplexe Wellenfunktion haben, wird das Quadrat der Amplitude durch Multiplikation mit dem komplex konjugierten Term berechnet.

$$
\begin{eqnarray}
I  &\propto & \hat{z}_{int} \cdot \hat{z}_{int}^\ast \\
&\Rightarrow& \hat{z}_{int} \cdot \hat{z}_{int}^\ast  \nonumber \\
 & = & \frac{\hat{z}^2}{b^2} \left(i \frac{2 \pi}{\lambda}sin(\theta)\right)^{-1} 
\left( e^{i \frac{2 \pi}{\lambda}\cdot b sin \left( \theta \right)} - 1\right) 
\cdot
\left(-i \frac{2 \pi}{\lambda}sin(\theta)\right)^{-1} 
\left( e^{-i \frac{2 \pi}{\lambda}\cdot b sin \left( \theta \right)} - 1\right) 
 \\
&=& 
\frac{\hat{z}^2}{b^2} \frac{1}{\left(\frac{2 \pi}{\lambda}sin(\theta)\right)^2} 
\left( e^{i \frac{2 \pi}{\lambda}\cdot b sin \left( \theta \right)} - 1\right) 
\cdot
\left( e^{-i \frac{2 \pi}{\lambda}\cdot b sin \left( \theta \right)} - 1\right) 
\\
&=& 
\frac{\hat{z}^2}{b^2} \frac{1}{\left(\frac{2 \pi}{\lambda}sin(\theta) \right)^2} 
\left( e^{i
\frac{2 \pi}{\lambda}\cdot b sin \left( \theta \right)} -  e^{- j
\frac{2 \pi}{\lambda}\cdot b sin \left( \theta \right)} -2 \right) 
\\
&=& 
\frac{\hat{z}^2}{b^2} \frac{1}{\left(\frac{2 \pi}{\lambda}sin(\theta) \right)^2} 
\left( 2 - 2 \cdot cos \left(
\frac{2 \pi}{\lambda}\cdot b sin \left( \theta \right)\right) \right) 
\\
&=& 
\frac{\hat{z}^2}{b^2} \frac{1}{\left(\frac{2 \pi}{\lambda}sin(\theta) \right)^2} 
\left( 2 - 2 \cdot cos \left(
\frac{2 \pi}{\lambda}\cdot b sin \left( \theta \right)\right) \right)
\\
&=& 
\frac{\hat{z}^2}{b^2} \frac{2}{\frac{1}{2}\left(\frac{2 \pi}{\lambda}sin(\theta)\right)^2} 
\left( 1 -  cos \left(
\frac{2 \pi}{\lambda}\cdot b sin \left( \theta \right)\right) \right) 
\\
&=&
\frac{\hat{z}^2}{b^2} \frac{2}{\left(\frac{2 \pi}{\lambda}sin(\theta) \right)^2} 
2 sin^2 \left(\frac{1}{2}
\frac{2 \pi}{\lambda}\cdot b sin \left( \theta \right)\right) 
\\
&=&
\frac{\hat{z}^2}{b^2} \frac{sin^2 \left(
\frac{\pi}{\lambda}\cdot b \cdot sin \left( \theta \right)\right) 
}{\left(\frac{\pi}{\lambda} sin(\theta) \right)^2} 
\end {eqnarray}$$


mit 

$$\left( e^{ix} - 1 \right)\left( e^{-ix} - 1 \right) = e^{ix -ix} - e^{ix} - e^{-ix} + 1 = 2 - \left( e^{ix} - e^{-ix} \right)$$ 

und 

$$ e^{ix} - e^{-ix} = 2 cos \left(x\right)$$

und

$$cos \left(2x \right) = 1- 2 sin^2 \left(x\right)\Leftrightarrow1 - cos\left(2x \right) = 2 sin^2 \left(x\right) $$

Damit ist die Intensität

$$
\begin{equation}
I = I_0 \frac{sin^2 \left(
\frac{\pi \cdot b}{\lambda} \cdot sin \left( \theta \right)\right) 
}{\left(\frac{\pi\cdot b}{\lambda} sin(\theta) \right)^2} 
\end{equation}
$$

mit $I_0 = \hat{z}^2$ und $lim_{\theta \rightarrow 0}\, I = I_0 $.

 ```{figure} Bilder/Einzelspalt_int.png
---
width: 80%
alt: Interferenz
name: interferenz-5
---
Intensitätsverteilung Interferenz am Einzelspalt
 ```

Die Intensitätsverteilung des daraus resultierenden Interferenzmusters ist in {numref}`Abbildung %s <interferenz-5>` zu sehen.
Die Positionen der Maxima und Minima berechnen sich über
$\frac{dI}{d\theta} \stackrel{!}{=} 0$

$\frac{dI}{d\theta}$ hat Nullstellen bei $\Rightarrow \frac{\pi\cdot b}{\lambda} sin (\theta)  = (n + \frac{1}{2})\pi$ mit $n = 0,1,2,...$ oder $\frac{\pi\cdot b}{\lambda} sin (\theta) = n \cdot \pi$ mit $n = 0,1,2,...$.
Für die Minima gilt darüber hinaus $I = 0 \Rightarrow \frac{\pi\cdot b}{\lambda} sin (\theta)  = (n + \frac{1}{2})\pi$.
Damit liegen die Minima bei

$$
\begin{equation}
\frac{\pi\cdot b}{\lambda} sin (\theta)  = (n + \frac{1}{2})\pi
\Leftrightarrow \frac{b\cdot sin (\theta)}{\lambda}   = (n + \frac{1}{2})
\end{equation}
$$

und die Maxima bei 

$$
\begin{equation}
\frac{sin (\theta) \cdot b}{\lambda}  = n 
\end{equation}
$$

mit $n = 0,1,2,...$.

