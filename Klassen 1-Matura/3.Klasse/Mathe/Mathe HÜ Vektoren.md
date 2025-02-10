[[3.Mathe]]
___
## Motor
### 1) Gleichung der Geraden $b$ in Parameterform
- Richtungsvektor $\vec{AP}$:
  $\vec{AP} = (472.2 - 427, 279.4 - 273) = (45.2, 6.4)$
- Normalenvektor:
  $\vec{n} = (-6.4, 45.2)$
- Parameterform von $b$:
  $\vec{b} = \begin{pmatrix} 472.2 \\ 279.4 \end{pmatrix} + t \cdot \begin{pmatrix} -6.4 \\ 45.2 \end{pmatrix}$
### 2) Schnittpunkt $S$
- Gleichungssystem:
  $\begin{cases} 387 + 22t = 472.2 - 6.4s \\ 295 - 40t = 279.4 + 45.2s \end{cases}$
- Lösung:
  $t \approx 3.00, \quad s \approx 5.63$
- Schnittpunkt:
  $S = \begin{pmatrix} 387 + 22 \cdot 3.00 \\ 295 - 40 \cdot 3.00 \end{pmatrix} = \begin{pmatrix} 453 \\ 175 \end{pmatrix}$
### 3) Spitzer Winkel $\alpha$
- Skalarprodukt:  
  $\vec{u} \cdot \vec{v} = 22 \cdot (-6.4) + (-40) \cdot 45.2 = -1948.8$
- Beträge:
  $|\vec{u}| = \sqrt{22^2 + (-40)^2} = \sqrt{2084} \approx 45.65$
  $|\vec{v}| = \sqrt{(-6.4)^2 + 45.2^2} = \sqrt{2084} \approx 45.65$
- Winkel:
  $\cos(\alpha) = \frac{| -1948.8 |}{2084} = 0.935 \quad \Rightarrow \quad \alpha = \arccos(0.935) \approx 36.86^\circ$
### 4) Einheitsvektor
- 
  $\vec{v}_{\text{norm}} = \left( \frac{-6.4}{45.65}, \frac{45.2}{45.65} \right) \approx (-0.14, 0.99)$
---
## Nähmaschine

### 1) Fehleranalyse
- Geradengleichung:
  $X = \begin{pmatrix} -4 \\ 35 \\ 25 \end{pmatrix} + \lambda \begin{pmatrix} 2 \\ 3 \\ 5 \end{pmatrix}$
- Da $y_B = 20$ gegeben ist:
  $35 + 3\lambda = 20$
  $\lambda = \frac{-15}{3} = -5$
- Setzen wir $\lambda = -5$ in die anderen Gleichungen ein:
  $x_B = -4 + 2(-5) = -14$
  $z_B = 25 + 5(-5) = 0$
- Damit ist $B(-14|20|0)$.
### 2) Geometrische Deutung
  $\overrightarrow{BC} \cdot \overrightarrow{CD} = 0$
  Das bedeutet, dass die Vektoren orthogonal sind und somit die Strecken senkrecht aufeinander stehen.
### 3) Länge des Fadens
  $DE = \sqrt{(2 - 1)^2 + (11 - 3)^2 + (18 - 10)^2} = \sqrt{129} \approx 11.36 \text{ cm}$
  $EF = \sqrt{(1 - 2)^2 + (0 - 11)^2 + (8 - 18)^2} = \sqrt{222} \approx 14.9 \text{ cm}$
- Gesamtlänge:
  $DE + EF = 11.36 + 14.9 = 26.26 \text{ cm}$
---
### Endergebnisse
1. Gerade $b$: 
   $\vec{b} = \begin{pmatrix} 472.2 \\ 279.4 \end{pmatrix} + t \cdot \begin{pmatrix} -6.4 \\ 45.2 \end{pmatrix}$
2. Schnittpunkt $S = (453, 175)$
3. Spitzer Winkel $\alpha \approx 36.86^\circ$
4. Einheitsvektor $\vec{v}_{\text{norm}} \approx (-0.14, 0.99)$
5. Fadenlänge: $26.26$ cm.
