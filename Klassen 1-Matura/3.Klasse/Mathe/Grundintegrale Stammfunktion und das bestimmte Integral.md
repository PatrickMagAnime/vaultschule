[[3.Mathe]]
___
![[Pasted image 20250505112255.png]]

![[Pasted image 20250505112322.png]]

![[Pasted image 20250505112445.png]]

![[Pasted image 20250505112535.png]]

![[Pasted image 20250505112554.png]]

![[Pasted image 20250505112617.png]]
![[Pasted image 20250505112633.png]]

![[Pasted image 20250505112652.png]]
# Aufgabe 6.6

Gib die konkrete Bedeutung des Flächeninhalts an, der in der nachfolgenden Abbildung zwischen dem Funktionsgraphen und der Zeitachse liegt. Ermittele danach näherungsweise diesen Flächeninhalt.

---

### Aufgabe a)

An einer Messstelle einer Gaspipeline wurde die durchfließende Gasmenge von 60 Stunden aufgezeichnet: Abb. 6.11.

Die Fläche unter der Kurve entspricht der Gesamtmenge des durchgeflossenen Gases über die Zeit. Wir nähern die Fläche abschnittsweise durch Rechtecke und Trapeze an.

#### Schritt 1: Grobe Unterteilung der Fläche
Wir unterscheiden drei Bereiche:
1. **Bereich 1 (0–20 Stunden):** Konstante Durchflussmenge von $$600,000 \, \frac{m^3}{h}$$.
2. **Bereich 2 (20–40 Stunden):** Konstante Durchflussmenge von $$400,000 \, \frac{m^3}{h}$$.
3. **Bereich 3 (40–60 Stunden):** Konstante Durchflussmenge von $$200,000 \, \frac{m^3}{h}$$.

#### Schritt 2: Berechnung der Fläche

1. Für den ersten Bereich:
   $$\text{Fläche}_1 = 600,000 \cdot 20 = 12,000,000 \, m^3$$

2. Für den zweiten Bereich:
   $$\text{Fläche}_2 = 400,000 \cdot 20 = 8,000,000 \, m^3$$

3. Für den dritten Bereich:
   $$\text{Fläche}_3 = 200,000 \cdot 20 = 4,000,000 \, m^3$$

#### Schritt 3: Gesamte Fläche
Die gesamte Fläche ergibt sich durch Addition:
$$\text{Gesamtfläche} = \text{Fläche}_1 + \text{Fläche}_2 + \text{Fläche}_3$$
$$\text{Gesamtfläche} = 12,000,000 + 8,000,000 + 4,000,000 = 24,000,000 \, m^3$$

---

### Aufgabe b)

An einer Messstelle wurde der Schadstoffausstoß von 8 Uhr bis 20 Uhr gemessen: Abb. 6.12.

Die Fläche unter der Kurve entspricht der Gesamtemission des Schadstoffes über die Zeit. Da die Kurve nicht konstant ist, nähern wir die Fläche durch Trapezregel.

#### Schritt 1: Unterteilung in Zeitintervalle
Wir unterteilen den Bereich von 8 Uhr bis 20 Uhr in 6 gleich große Intervalle zu je 2 Stunden.

#### Schritt 2: Berechnung der Flächen
1. **Intervall 1 (8–10 Uhr):**
   Mittelwert der Werte: $$\frac{3 + 4}{2} = 3.5 \, \frac{\text{ng}}{\text{h}}$$  
   $$\text{Fläche}_1 = 3.5 \cdot 2 = 7 \, \text{ng}$$

2. **Intervall 2 (10–12 Uhr):**
   Mittelwert der Werte: $$\frac{4 + 3.5}{2} = 3.75 \, \frac{\text{ng}}{\text{h}}$$  
   $$\text{Fläche}_2 = 3.75 \cdot 2 = 7.5 \, \text{ng}$$

3. **Intervall 3 (12–14 Uhr):**
   Mittelwert der Werte: $$\frac{3.5 + 2.5}{2} = 3 \, \frac{\text{ng}}{\text{h}}$$  
   $$\text{Fläche}_3 = 3 \cdot 2 = 6 \, \text{ng}$$

4. **Intervall 4 (14–16 Uhr):**
   Mittelwert der Werte: $$\frac{2.5 + 2}{2} = 2.25 \, \frac{\text{ng}}{\text{h}}$$  
   $$\text{Fläche}_4 = 2.25 \cdot 2 = 4.5 \, \text{ng}$$

5. **Intervall 5 (16–18 Uhr):**
   Mittelwert der Werte: $$\frac{2 + 1}{2} = 1.5 \, \frac{\text{ng}}{\text{h}}$$  
   $$\text{Fläche}_5 = 1.5 \cdot 2 = 3 \, \text{ng}$$

6. **Intervall 6 (18–20 Uhr):**
   Mittelwert der Werte: $$\frac{1 + 0}{2} = 0.5 \, \frac{\text{ng}}{\text{h}}$$  
   $$\text{Fläche}_6 = 0.5 \cdot 2 = 1 \, \text{ng}$$

#### Schritt 3: Gesamte Fläche
Die gesamte Fläche ergibt sich durch Addition:
$$\text{Gesamtfläche} = \text{Fläche}_1 + \text{Fläche}_2 + \text{Fläche}_3 + \text{Fläche}_4 + \text{Fläche}_5 + \text{Fläche}_6$$
$$\text{Gesamtfläche} = 7 + 7.5 + 6 + 4.5 + 3 + 1 = 29 \, \text{ng}$$

---
![[Pasted image 20250505112703.png]]
# Aufgabe 6.7

Ermittle elementargeometrisch das bestimmte Integral. Jede Rechnung wird ausführlich mit Schritten dargestellt.

---

### Aufgabe a)

Berechnung des Integrals:  
$$\int_{-1}^{3} \left( 2x - 1 \right) \, dx$$

#### Schritt 1: Interpretation des Funktionsgraphen
Die Funktion $$2x - 1$$ ist eine Gerade mit Steigung $$2$$ und y-Achsenabschnitt $$-1$$. Der Graph bildet zwei geometrische Figuren im Intervall $$[-1, 3]$$
- Ein Trapez im Bereich $$[0, 3]$$.
- Ein Dreieck im Bereich $$[-1, 0]$$.

#### Schritt 2: Flächenberechnung
1. **Dreieck im Bereich $$[-1, 0]$$:**  
   Das Dreieck hat die Basislänge $$1$$ (von $$x = -1$$ bis $$x = 0$$) und eine Höhe, die sich aus $$f(-1) = 2(-1) - 1 = -3$$ ergibt.  
   $$\text{Fläche}_{\text{Dreieck}} = \frac{1}{2} \cdot 1 \cdot 3 = 1.5$$  
   Da die Fläche unterhalb der x-Achse liegt, wird sie negativ:  
   $$\text{Fläche}_{\text{Dreieck}} = -1.5$$

2. **Trapez im Bereich $$[0, 3]$$:**  
   Das Trapez hat die Parallelseitenhöhen $$f(0) = -1$$ und $$f(3) = 2(3) - 1 = 5$$ sowie eine Breite von $$3$$ (Differenz der x-Werte).  
   $$\text{Fläche}_{\text{Trapez}} = \frac{1}{2} \cdot (\text{Höhe}_1 + \text{Höhe}_2) \cdot \text{Breite}$$  
   $$\text{Fläche}_{\text{Trapez}} = \frac{1}{2} \cdot (-1 + 5) \cdot 3 = \frac{1}{2} \cdot 4 \cdot 3 = 6$$

#### Schritt 3: Gesamtes Integral
$$\int_{-1}^{3} \left( 2x - 1 \right) \, dx = \text{Fläche}_{\text{Dreieck}} + \text{Fläche}_{\text{Trapez}}$$  
$$\int_{-1}^{3} \left( 2x - 1 \right) \, dx = -1.5 + 6 = 4.5$$

---

### Aufgabe b)

Berechnung des Integrals:  
$$\int_{-3}^{0} \left( -\frac{2}{3}x + 4 \right) \, dx$$

#### Schritt 1: Interpretation des Funktionsgraphen
Die Funktion $$-\frac{2}{3}x + 4$$ ist eine Gerade mit negativer Steigung $$-\frac{2}{3}$$ und y-Achsenabschnitt $$4$$. Der Graph bildet ein Trapez im Intervall $$[-3, 0]$$.

#### Schritt 2: Flächenberechnung
1. **Trapez im Bereich $$[-3, 0]$$:**  
   Das Trapez hat die Parallelseitenhöhen $$f(-3) = -\frac{2}{3}(-3) + 4 = 2 + 4 = 6$$ und $$f(0) = -\frac{2}{3}(0) + 4 = 4$$ sowie eine Breite von $$3$$ (Differenz der x-Werte).  
   $$\text{Fläche}_{\text{Trapez}} = \frac{1}{2} \cdot (\text{Höhe}_1 + \text{Höhe}_2) \cdot \text{Breite}$$  
   $$\text{Fläche}_{\text{Trapez}} = \frac{1}{2} \cdot (6 + 4) \cdot 3 = \frac{1}{2} \cdot 10 \cdot 3 = 15$$

#### Schritt 3: Gesamtes Integral
$$\int_{-3}^{0} \left( -\frac{2}{3}x + 4 \right) \, dx = \text{Fläche}_{\text{Trapez}}$$  
$$\int_{-3}^{0} \left( -\frac{2}{3}x + 4 \right) \, dx = 15$$

---

### Aufgabe c)

Berechnung des Integrals:  
$$\int_{\frac{1}{2}}^{3} \left( \frac{4}{3}x - 1 \right) \, dx$$

#### Schritt 1: Interpretation des Funktionsgraphen
Die Funktion $$\frac{4}{3}x - 1$$ ist eine Gerade mit Steigung $$\frac{4}{3}$$ und y-Achsenabschnitt $$-1$$. Der Graph bildet ein Trapez im Intervall $$[\frac{1}{2}, 3]$$.

#### Schritt 2: Flächenberechnung
1. **Trapez im Bereich $$[\frac{1}{2}, 3]$$:**  
   Das Trapez hat die Parallelseitenhöhen $$f(\frac{1}{2}) = \frac{4}{3} \cdot \frac{1}{2} - 1 = \frac{2}{3} - 1 = -\frac{1}{3}$$ und $$f(3) = \frac{4}{3} \cdot 3 - 1 = 4 - 1 = 3$$ sowie eine Breite von $$2.5$$ (Differenz der x-Werte).  
   $$\text{Fläche}_{\text{Trapez}} = \frac{1}{2} \cdot (\text{Höhe}_1 + \text{Höhe}_2) \cdot \text{Breite}$$  
   $$\text{Fläche}_{\text{Trapez}} = \frac{1}{2} \cdot (-\frac{1}{3} + 3) \cdot 2.5 = \frac{1}{2} \cdot \frac{8}{3} \cdot 2.5 = \frac{10}{3} \cdot 2.5 = \frac{25}{3} \approx 8.33$$

#### Schritt 3: Gesamtes Integral
$$\int_{\frac{1}{2}}^{3} \left( \frac{4}{3}x - 1 \right) \, dx = \text{Fläche}_{\text{Trapez}}$$  
$$\int_{\frac{1}{2}}^{3} \left( \frac{4}{3}x - 1 \right) \, dx \approx 8.33$$

---

### Aufgabe d)

Berechnung des Integrals:  
$$\int_{1}^{3} \left( -\frac{2}{3}x - 1 \right) \, dx$$

#### Schritt 1: Interpretation des Funktionsgraphen
Die Funktion $$-\frac{2}{3}x - 1$$ ist eine Gerade mit negativer Steigung $$-\frac{2}{3}$$ und y-Achsenabschnitt $$-1$$. Der Graph bildet ein Trapez im Intervall $$[1, 3]$$.

#### Schritt 2: Flächenberechnung
1. **Trapez im Bereich $$[1, 3]$$:**  
   Das Trapez hat die Parallelseitenhöhen $$f(1) = -\frac{2}{3} \cdot 1 - 1 = -\frac{2}{3} - 1 = -\frac{5}{3}$$ und $$f(3) = -\frac{2}{3} \cdot 3 - 1 = -2 - 1 = -3$$ sowie eine Breite von $$2$$ (Differenz der x-Werte).  
   $$\text{Fläche}_{\text{Trapez}} = \frac{1}{2} \cdot (\text{Höhe}_1 + \text{Höhe}_2) \cdot \text{Breite}$$  
   $$\text{Fläche}_{\text{Trapez}} = \frac{1}{2} \cdot (-\frac{5}{3} + -3) \cdot 2 = \frac{1}{2} \cdot -\frac{14}{3} \cdot 2 = -\frac{14}{3} \approx -4.67$$

#### Schritt 3: Gesamtes Integral
$$\int_{1}^{3} \left( -\frac{2}{3}x - 1 \right) \, dx = \text{Fläche}_{\text{Trapez}}$$  
$$\int_{1}^{3} \left( -\frac{2}{3}x - 1 \right) \, dx \approx -4.67$$

---
![[Pasted image 20250505112709.png]]
### Aufgabe a:
Die Funktion $f(x)$ ist stückweise definiert:
$$
f(x) =
\begin{cases} 
\frac{1}{2}x + 2 & \text{für } -2 \leq x < 0, \\
4 & \text{für } 0 \leq x \leq 3.
\end{cases}
$$

Wir berechnen das bestimmte Integral von $f(x)$ über den gesamten Definitionsbereich $[-2, 3]$. Dazu teilen wir das Integral in zwei Abschnitte auf:

$$
\int_{-2}^{3} f(x) \, dx = \int_{-2}^{0} \left(\frac{1}{2}x + 2\right) \, dx + \int_{0}^{3} 4 \, dx.
$$

#### Schritt 1: Berechnung des ersten Integrals
$$
\int_{-2}^{0} \left(\frac{1}{2}x + 2\right) \, dx
$$

Das Integral wird aufgeteilt:
$$
\int_{-2}^{0} \left(\frac{1}{2}x + 2\right) \, dx = \int_{-2}^{0} \frac{1}{2}x \, dx + \int_{-2}^{0} 2 \, dx.
$$

Berechnung der einzelnen Terme:
1. $$\int_{-2}^{0} \frac{1}{2}x \, dx = \left[\frac{1}{4}x^2\right]_{-2}^{0} = \frac{1}{4}(0)^2 - \frac{1}{4}(-2)^2 = 0 - 1 = -1.$$
2. $$\int_{-2}^{0} 2 \, dx = \left[2x\right]_{-2}^{0} = 2(0) - 2(-2) = 0 + 4 = 4.$$

Zusammen ergibt sich:
$$
\int_{-2}^{0} \left(\frac{1}{2}x + 2\right) \, dx = -1 + 4 = 3.
$$

#### Schritt 2: Berechnung des zweiten Integrals
$$
\int_{0}^{3} 4 \, dx = \left[4x\right]_{0}^{3} = 4(3) - 4(0) = 12 - 0 = 12.
$$

#### Schritt 3: Gesamtergebnis
$$
\int_{-2}^{3} f(x) \, dx = 3 + 12 = 15.
$$

---

### Aufgabe b:
Die Funktion $f(x)$ ist stückweise definiert:
$$
f(x) =
\begin{cases} 
x + 2 & \text{für } -1 \leq x < 1, \\
-x - 4 & \text{für } 1 \leq x \leq 4.
\end{cases}
$$

Wir berechnen das bestimmte Integral von $f(x)$ über den gesamten Definitionsbereich $[-1, 4]$. Dazu teilen wir das Integral in zwei Abschnitte auf:

$$
\int_{-1}^{4} f(x) \, dx = \int_{-1}^{1} (x + 2) \, dx + \int_{1}^{4} (-x - 4) \, dx.
$$

#### Schritt 1: Berechnung des ersten Integrals
$$
\int_{-1}^{1} (x + 2) \, dx
$$

Das Integral wird aufgeteilt:
$$
\int_{-1}^{1} (x + 2) \, dx = \int_{-1}^{1} x \, dx + \int_{-1}^{1} 2 \, dx.
$$

Berechnung der einzelnen Terme:
1. $$\int_{-1}^{1} x \, dx = \left[\frac{1}{2}x^2\right]_{-1}^{1} = \frac{1}{2}(1)^2 - \frac{1}{2}(-1)^2 = \frac{1}{2} - \frac{1}{2} = 0.$$
2. $$\int_{-1}^{1} 2 \, dx = \left[2x\right]_{-1}^{1} = 2(1) - 2(-1) = 2 + 2 = 4.$$

Zusammen ergibt sich:
$$
\int_{-1}^{1} (x + 2) \, dx = 0 + 4 = 4.
$$

#### Schritt 2: Berechnung des zweiten Integrals
$$
\int_{1}^{4} (-x - 4) \, dx
$$

Das Integral wird aufgeteilt:
$$
\int_{1}^{4} (-x - 4) \, dx = \int_{1}^{4} -x \, dx + \int_{1}^{4} -4 \, dx.
$$

Berechnung der einzelnen Terme:
1. $$\int_{1}^{4} -x \, dx = \left[-\frac{1}{2}x^2\right]_{1}^{4} = -\frac{1}{2}(4)^2 + \frac{1}{2}(1)^2 = -8 + 0.5 = -7.5.$$
2. $$\int_{1}^{4} -4 \, dx = \left[-4x\right]_{1}^{4} = -4(4) + 4(1) = -16 + 4 = -12.$$

Zusammen ergibt sich:
$$
\int_{1}^{4} (-x - 4) \, dx = -7.5 - 12 = -19.5.
$$

#### Schritt 3: Gesamtergebnis
$$
\int_{-1}^{4} f(x) \, dx = 4 - 19.5 = -15.5.
$$

---
![[Pasted image 20250505112719.png]]
### Aufgabe a)

Gegeben:
- \(f(x) = 0.5x + 2\)
- \(a = 0\), \(b = 2\), \(n = 4\)

#### Schritt 1: Berechnung der Intervallbreite
$$\Delta x = \frac{b-a}{n} = \frac{2-0}{4} = 0.5$$

#### Schritt 2: Unterteilung der Intervalle
Die Intervalle sind: 
\([0, 0.5], [0.5, 1], [1, 1.5], [1.5, 2]\).

#### Schritt 3: Berechnung der Untersumme
Für die Untersumme nehmen wir jeweils den linken Intervallrand:
$$x_0 = 0, \, x_1 = 0.5, \, x_2 = 1, \, x_3 = 1.5$$

Berechnung:
$$
f(x_0) = 0.5 \cdot 0 + 2 = 2 \\
f(x_1) = 0.5 \cdot 0.5 + 2 = 2.25 \\
f(x_2) = 0.5 \cdot 1 + 2 = 2.5 \\
f(x_3) = 0.5 \cdot 1.5 + 2 = 2.75
$$

Untersumme:
$$
U = \Delta x \cdot (f(x_0) + f(x_1) + f(x_2) + f(x_3)) = 0.5 \cdot (2 + 2.25 + 2.5 + 2.75) = 4.75
$$

#### Schritt 4: Berechnung der Obersumme
Für die Obersumme nehmen wir jeweils den rechten Intervallrand:
$$x_1 = 0.5, \, x_2 = 1, \, x_3 = 1.5, \, x_4 = 2$$

Berechnung:
$$
f(x_1) = 0.5 \cdot 0.5 + 2 = 2.25 \\
f(x_2) = 0.5 \cdot 1 + 2 = 2.5 \\
f(x_3) = 0.5 \cdot 1.5 + 2 = 2.75 \\
f(x_4) = 0.5 \cdot 2 + 2 = 3
$$

Obersumme:
$$
O = \Delta x \cdot (f(x_1) + f(x_2) + f(x_3) + f(x_4)) = 0.5 \cdot (2.25 + 2.5 + 2.75 + 3) = 5.25
$$

---

### Aufgabe b)

Gegeben:
- \(f(x) = \frac{1}{2}x^2\)
- \(a = 0\), \(b = 3\), \(n = 6\)

#### Schritt 1: Berechnung der Intervallbreite
$$\Delta x = \frac{b-a}{n} = \frac{3-0}{6} = 0.5$$

#### Schritt 2: Unterteilung der Intervalle
Die Intervalle sind:
\([0, 0.5], [0.5, 1], [1, 1.5], [1.5, 2], [2, 2.5], [2.5, 3]\).

#### Schritt 3: Berechnung der Untersumme
Für die Untersumme nehmen wir jeweils den linken Intervallrand:
$$x_0 = 0, \, x_1 = 0.5, \, x_2 = 1, \, x_3 = 1.5, \, x_4 = 2, \, x_5 = 2.5$$

Berechnung:
$$
f(x_0) = \frac{1}{2} \cdot 0^2 = 0 \\
f(x_1) = \frac{1}{2} \cdot 0.5^2 = 0.125 \\
f(x_2) = \frac{1}{2} \cdot 1^2 = 0.5 \\
f(x_3) = \frac{1}{2} \cdot 1.5^2 = 1.125 \\
f(x_4) = \frac{1}{2} \cdot 2^2 = 2 \\
f(x_5) = \frac{1}{2} \cdot 2.5^2 = 3.125
$$

Untersumme:
$$
U = \Delta x \cdot (f(x_0) + f(x_1) + f(x_2) + f(x_3) + f(x_4) + f(x_5)) = 0.5 \cdot (0 + 0.125 + 0.5 + 1.125 + 2 + 3.125) = 3.4375
$$

#### Schritt 4: Berechnung der Obersumme
Für die Obersumme nehmen wir jeweils den rechten Intervallrand:
$$x_1 = 0.5, \, x_2 = 1, \, x_3 = 1.5, \, x_4 = 2, \, x_5 = 2.5, \, x_6 = 3$$

Berechnung:
$$
f(x_1) = \frac{1}{2} \cdot 0.5^2 = 0.125 \\
f(x_2) = \frac{1}{2} \cdot 1^2 = 0.5 \\
f(x_3) = \frac{1}{2} \cdot 1.5^2 = 1.125 \\
f(x_4) = \frac{1}{2} \cdot 2^2 = 2 \\
f(x_5) = \frac{1}{2} \cdot 2.5^2 = 3.125 \\
f(x_6) = \frac{1}{2} \cdot 3^2 = 4.5
$$

Obersumme:
$$
O = \Delta x \cdot (f(x_1) + f(x_2) + f(x_3) + f(x_4) + f(x_5) + f(x_6)) = 0.5 \cdot (0.125 + 0.5 + 1.125 + 2 + 3.125 + 4.5) = 5.6875
$$
![[Pasted image 20250505112737.png]]
![[Pasted image 20250505112809.png]]
![[Pasted image 20250505112827.png]]
![[Pasted image 20250505112845.png]]

![[Pasted image 20250505112916.png]]

![[Pasted image 20250505112956.png]]

![[Pasted image 20250505113003.png]]

![[Pasted image 20250505113011.png]]

![[Pasted image 20250505113021.png]]

![[Pasted image 20250505113030.png]]

![[Pasted image 20250505113037.png]]

![[Pasted image 20250505113110.png]]

![[Pasted image 20250505113130.png]]

![[Pasted image 20250505113144.png]]

![[Pasted image 20250505113158.png]]

![[Pasted image 20250505113209.png]]

![[Pasted image 20250505113224.png]]

![[Pasted image 20250505113236.png]]

![[Pasted image 20250505113250.png]]

![[Pasted image 20250505113259.png]]

![[Pasted image 20250505113315.png]]

![[Pasted image 20250505113328.png]]

![[Pasted image 20250505113337.png]]


