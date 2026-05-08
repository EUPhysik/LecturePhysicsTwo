# Dispersion

Der Brechungsindex ist eine Materialeigenschaft und nur näherungsweise als konstant anzunehmen. Im Allgemeinen ist der Brechungsindex eine Funktion verschiedener Parameter wie beispielsweise

* der Dichte
* der (Kristall-) Struktur
* der Wellenlänge des einfallenden Lichtes

Die Abhängigkeit des Brechungsindex von der Wellenlänge bezeichnet man als Dispersion.
Diese Dispersion führt dazu, dass kurzwelliges Licht stärker gebrochen als langwelliges („Wer blau ist bricht besser“).
Weisses Licht wird daher in seine Spektralfarben zerlegt (Prisma, Regenbogen, siehe {numref}`Abbildung %s <licht-7>`). 

```{figure} https://upload.wikimedia.org/wikipedia/commons/2/24/Prism-rainbow.svg
---
width: 50%
alt: Dispersion
name: licht-7
---
Dispersion im Prisma erzeugt ein FarbspektrumTotalreflexion, Quelle: Suidroot, CC BY-SA 4.0, https://commons.wikimedia.org/w/index.php?curid=3728535
 ```

Durch Dispersion entsteht auch der Regenbogen. Die einfachste Möglichkeit ist die Farbzerlegung eines Sonnenstrahls im Regentropfen mit einer einmaligen inneren Reflexion (siehe {numref}`Abbildung %s <licht-8>`). Mehrfachere Reflexionen führen zu weiteren, schwächeren Regenbögen. 

```{figure} https://upload.wikimedia.org/wikipedia/commons/7/70/Rainbow1.svg
---
width: 50%
alt: Regenbogen
name: licht-8
---
Entstehung eines Regenbogens durch Dispersion, Quelle: KES47, Gemeinfrei, https://commons.wikimedia.org/w/index.php?curid=10636870
 ```

```{figure} Bilder_Licht/regenbogen.svg
---
width: 100%
alt: Regenbogen
name: licht-9
---
Strahlverlauf im Regentropfen mit einer einmaligen inneren Reflexion.
 ```

Erste Lichtbrechung

$$n_L sin (\alpha) = n_W sin(\beta) \Leftrightarrow \beta = arcsin \left( \frac{n_L}{n_W} sin (\alpha) \right)$$(equ-1)

Für das Dreieck in der Mitte gilt:

$$\beta + \gamma + \delta = 180^\circ$$(equ-2)

Da es sich um ein Dreieck im Thales-Kreis handelt, gilt

$$\beta = \gamma$$

Damit ist

$$2\beta + \delta = 180^\circ \Leftrightarrow \delta = 180^\circ - 2\beta$$(equ-3)

Darüber hinaus gilt

$$\theta + 2 \phi = 180^\circ \Leftrightarrow \theta = 180^\circ - 2 \phi$$(equ-4)

und

$$\alpha + \delta + \phi = 180^\circ \Leftrightarrow \phi = 180^\circ - \alpha - \delta $$(equ-5)

Gleichung {eq}`equ-5` in Gleichung {eq}`equ-4` einsetzen ergibt

$$\theta = 180^\circ - 2 \left( 180^\circ - \alpha - \delta\right) = - 180^\circ + 2 \alpha + 2\delta$$(equ-6)

Gleichung {eq}`equ-3` in Gleichung {eq}`equ-6` einsetzen ergibt

$$\theta = - 180^\circ + 2 \alpha + 2 \left( 180^\circ - 2\beta \right)  = 180^\circ + 2 \alpha - 4 \beta $$(equ-7)

Gleichung {eq}`equ-1` in Gleichung {eq}`equ-7` einsetzen ergibt

$$\theta = 180^\circ + 2 \alpha - 4 \, arcsin \left( \frac{n_L}{n_W} sin (\alpha) \right) $$(equ-8)

Dies ergibt einen Funktionalen Zusammenhang zwischen dem sogenannten Ablenkwinkel $\theta$ als Funktion des Einfallswinkels $\alpha$ (siehe {numref}`Abbildung %s <licht-10>`).

```{figure} Bilder_Licht/regenbogen_winkel.png
---
width: 80%
alt: Regenbogen
name: licht-10
---
Ablenkwinkel $\theta$ als Funktion des Einfallswinkels $\alpha$.
 ```

Die Intensität des abgelenkten Lichtstrahls ich dann maximal, wenn sich der Ablenkwinkel bei Variation des Einfallswinkels minimal ändert. Dies geschieht, wenn die Ableitung nach dem Eintrittswinkel null wird, also für 

$$\frac{d \theta}{d \alpha} \stackrel{!}{=} 0$$

Dies ergibt

$$\frac{d \theta}{d \alpha} = \frac{d}{d \alpha} \left( 180^\circ + 2 \alpha - 4 \, arcsin \left( \frac{n_L}{n_W} sin (\alpha) \right) \right)$$

$$ = 2 - 4 \frac{1}{\sqrt{1 - \left( \frac{n_L}{n_W} sin (\alpha)\right)^2}} \cdot \frac{n_L}{n_W} cos (\alpha)  \stackrel{!}{=} 0$$

$$\Leftrightarrow \sqrt{1 - \left( \frac{n_L}{n_W} sin (\alpha)\right)^2} = 2 \cdot \frac{n_L}{n_W} cos (\alpha)$$

$$\Leftrightarrow 1 - \left( \frac{n_L}{n_W}\right)^2 sin (\alpha)^2 = 4 \cdot \left( \frac{n_L}{n_W} \right)^2 cos^2 (\alpha)$$

$$\Leftrightarrow 1  = 4 \cdot \left( \frac{n_L}{n_W} \right)^2 cos^2 (\alpha) + \left( \frac{n_L}{n_W}\right)^2 sin (\alpha)^2$$

$$\Leftrightarrow sin (\alpha)^2 + cos (\alpha)^2  = 4 \cdot \left( \frac{n_L}{n_W} \right)^2 cos^2 (\alpha) + \left( \frac{n_L}{n_W}\right)^2 sin (\alpha)^2$$

$$\Leftrightarrow sin (\alpha)^2 - \left( \frac{n_L}{n_W}\right)^2 sin (\alpha)^2  = 4 \cdot \left( \frac{n_L}{n_W} \right)^2 cos^2 (\alpha) - cos (\alpha)^2 $$

$$\Leftrightarrow sin (\alpha)^2\left(1  - \left( \frac{n_L}{n_W}\right)^2 \right)  = cos^2 (\alpha)\left( 4 \cdot \left( \frac{n_L}{n_W} \right)^2  - 1 \right)$$

$$\Leftrightarrow \frac{sin (\alpha)^2}{cos (\alpha)^2}  
= \left( \frac{sin (\alpha)}{cos (\alpha)} \right)^2
= tan^2 (\alpha) 
= \frac{\left( 4 \cdot \left( \frac{n_L}{n_W} \right)^2  - 1 \right)}{\left(1  - \left( \frac{n_L}{n_W}\right)^2 \right) }$$

$$\Leftrightarrow tan(\alpha) 
= \sqrt{\frac{\left( 4 \cdot \left( \frac{n_L}{n_W} \right)^2  - 1 \right)}{\left(1  - \left( \frac{n_L}{n_W}\right)^2 \right) }}$$

mit $n_{Luft} = 1$ und $n_{Wasser} = 1.34$

ist dies bei 

$$\Leftrightarrow \alpha
= arctan \left( \sqrt{\frac{4 \cdot \left( \frac{n_L}{n_W} \right)^2  - 1 }{1  - \left( \frac{n_L}{n_W}\right)^2 }} \right)
= arctan \left( \sqrt{\frac{4 \cdot \left( \frac{1}{1.34} \right)^2  - 1 }{1  - \left( \frac{1}{1.34}\right)^2 }} \right)
= 1.03 = 60^\circ$$

Dazu gehört der Ablenkwinkel

$$\theta \approx 138^\circ$$

Dies entspricht einem Öffnungswinkel von $2\phi \approx 42^\circ$.