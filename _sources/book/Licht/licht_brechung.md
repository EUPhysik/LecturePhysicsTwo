# Brechung

Tritt der Lichtstrahl von einem in ein anderes Medium über, so wird der Lichtstrahl gebrochen, dies lässt sich mit Hilfe des [Huygen'schen Prinzips](../Wellen/wellenausbreitung2.md#huygensches-prinzip) und mit Hilfe des [Fermat'schen Prinzips](../Wellen/wellenausbreitung2.md#fermatsches-prinzip) berechnen. Grundlage hierfür ist wieder die Wellentheorie des Lichtes. 

```{figure} https://upload.wikimedia.org/wikipedia/commons/d/dc/Snells_law_wavefronts.gif
---
width: 50%
alt: Brechungsgesetz für Licht
name: licht-3
---
Brechungsgesetz für Licht an einer Grenzfläche zwischen zwei Medien. 
 ```

Das mit Hilfe des [Fermat'schen Prinzips](../Wellen/wellenausbreitung2.md#fermatsches-prinzip) hergeleitete Gesetz ist als Snellius'sches Brechungsgesetz bekannt. Nach Fermat gilt

$$\frac{sin \left( \theta_1 \right)}{c_1} = \frac{sin \left( \theta_2 \right)}{c_2}$$(snellius-1)

wobei $\theta_1$ der Einfallswinkel (siehe $\theta_1$ in {numref}`Abbildung %s <licht-4>`) und $\theta_2$ der Reflexionswinkel ($\theta_2$ in {numref}`Abbildung %s <licht-4>`) ist. $c_1$ ist die Lichtgeschwindigkeit im Medium 1 und $c_2$ die Lichgeschwindigkeit im Medium 2. 


```{figure} Bilder_Licht/Reflexion.svg
---
width: 80%
alt: Reflexion von  Licht
name: licht-4
---
Brechung eines Lichtstrahls an einer Grenzfläche zwischen zwei Medien. 
 ```

Mit der Definition des [Brechungsindex](../Licht/licht_grundlagen.md#lichtgeschwindigkeit-in-einem-medium)

$$n = \frac{c}{c_n}$$

kann man schreiben

$$\Rightarrow n_1 = \frac{c}{c_1} \Leftrightarrow c_1 \frac{c}{n_1}$$

und

$$\Rightarrow n_1 = \frac{c}{c_1} \Leftrightarrow c_1 \frac{c}{n_1}$$

Einsetzen dieser Zusammenhänge in Gleichung {eq}`snellius-1` ergibt den bekannten Zusammenhang

$$\frac{sin \left( \theta_1 \right)}{\frac{c}{n_1}} = \frac{sin \left( \theta_2 \right)}{\frac{c}{n_1}} \Leftrightarrow 
n_1 \cdot sin \left( \theta_1 \right) = n_2 \cdot sin \left( \theta_2 \right)$$(snellius-2)
