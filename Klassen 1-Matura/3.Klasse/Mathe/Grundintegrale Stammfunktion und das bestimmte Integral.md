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
1. **Bereich 1 (0–20 Stunden):** Konstante Durchflussmenge von $$600,000 \, \frac{m^3}{h}$$
2. **Bereich 2 (20–40 Stunden):** Konstante Durchflussmenge von $$400,000 \, \frac{m^3}{h}$$
3. **Bereich 3 (40–60 Stunden):** Konstante Durchflussmenge von $$200,000 \, \frac{m^3}{h}$$
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
- Ein Trapez im Bereich $$[0, 3]$$
- Ein Dreieck im Bereich $$[-1, 0]$$
#### Schritt 2: Flächenberechnung
1. **Dreieck im Bereich $$[-1, 0]$$**
   Das Dreieck hat die Basislänge $$1$$ (von $$x = -1$$ bis $$x = 0$$) und eine Höhe, die sich aus $$f(-1) = 2(-1) - 1 = -3$$ ergibt.  
   $$\text{Fläche}_{\text{Dreieck}} = \frac{1}{2} \cdot 1 \cdot 3 = 1.5$$
   Da die Fläche unterhalb der x-Achse liegt, wird sie negativ:  
   $$\text{Fläche}_{\text{Dreieck}} = -1.5$$
2. **Trapez im Bereich $$[0, 3]$$**
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
Die Funktion $$-\frac{2}{3}x + 4$$ ist eine Gerade mit negativer Steigung $$-\frac{2}{3}$$ und y-Achsenabschnitt $$4$$Der Graph bildet ein Trapez im Intervall $$[-3, 0]$$
#### Schritt 2: Flächenberechnung
1. **Trapez im Bereich $$[-3, 0]$$**  
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
Die Funktion $$\frac{4}{3}x - 1$$ ist eine Gerade mit Steigung $$\frac{4}{3}$$ und y-Achsenabschnitt $$-1$$. Der Graph bildet ein Trapez im Intervall $$[\frac{1}{2}, 3]$$
#### Schritt 2: Flächenberechnung
1. **Trapez im Bereich $$[\frac{1}{2}, 3]$$**
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
Die Funktion $$-\frac{2}{3}x - 1$$ ist eine Gerade mit negativer Steigung $$-\frac{2}{3}$$ und y-Achsenabschnitt $$-1$$Der Graph bildet ein Trapez im Intervall $$[1, 3]$$

#### Schritt 2: Flächenberechnung
1. **Trapez im Bereich $$[1, 3]$$**  
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
### Aufgabe a
Die Funktion lautet: $$f(x) = x + 1$$
**Schritt 1: Stammfunktionen bestimmen**
Eine Stammfunktion von \( f(x) \) ist eine Funktion \( F(x) \), deren Ableitung \( f(x) \) ergibt. 
Die Regel lautet: $$\int f(x) dx = \text{Stammfunktion + C (Integrationskonstante)}$$
Berechnen wir zwei Stammfunktionen:

1. $$F_1(x) = \int (x + 1) dx = \frac{x^2}{2} + x + C_1$$
2. $$F_2(x) = \int (x + 1) dx = \frac{x^2}{2} + x + C_2$$
**Schritt 2: Nachweis durch Ableiten**
Ableitung von \( F_1(x) \):
$$\frac{d}{dx}\left(\frac{x^2}{2} + x + C_1\right) = x + 1$$

Ableitung von \( F_2(x) \):
$$\frac{d}{dx}\left(\frac{x^2}{2} + x + C_2\right) = x + 1$$
Da beide Ableitungen \( f(x) \) ergeben, sind \( F_1(x) \) und \( F_2(x) \) Stammfunktionen von \( f(x) \).

---
### Aufgabe b
Die Funktion lautet: $$f(x) = 3x$$
**Schritt 1: Stammfunktionen bestimmen**

1. $$F_1(x) = \int 3x dx = \frac{3x^2}{2} + C_1$$
2. $$F_2(x) = \int 3x dx = \frac{3x^2}{2} + C_2$$
**Schritt 2: Nachweis durch Ableiten**
Ableitung von \( F_1(x) \):
$$\frac{d}{dx}\left(\frac{3x^2}{2} + C_1\right) = 3x$$
Ableitung von \( F_2(x) \):
$$\frac{d}{dx}\left(\frac{3x^2}{2} + C_2\right) = 3x$$
Beide Ableitungen ergeben \( f(x) \), also sind \( F_1(x) \) und \( F_2(x) \) Stammfunktionen.

---
### Aufgabe c
Die Funktion lautet: $$f(x) = \frac{x}{2}$$
**Schritt 1: Stammfunktionen bestimmen**

1. $$F_1(x) = \int \frac{x}{2} dx = \frac{x^2}{4} + C_1$$
2. $$F_2(x) = \int \frac{x}{2} dx = \frac{x^2}{4} + C_2$$
**Schritt 2: Nachweis durch Ableiten**
Ableitung von \( F_1(x) \):
$$\frac{d}{dx}\left(\frac{x^2}{4} + C_1\right) = \frac{x}{2}$$

Ableitung von \( F_2(x) \):
$$\frac{d}{dx}\left(\frac{x^2}{4} + C_2\right) = \frac{x}{2}$$

Damit sind \( F_1(x) \) und \( F_2(x) \) Stammfunktionen.

---

### Aufgabe d
Die Funktion lautet: $$f(x) = x^2 + x$$
**Schritt 1: Stammfunktionen bestimmen**
1. $$F_1(x) = \int (x^2 + x) dx = \frac{x^3}{3} + \frac{x^2}{2} + C_1$$
2. $$F_2(x) = \int (x^2 + x) dx = \frac{x^3}{3} + \frac{x^2}{2} + C_2$$

**Schritt 2: Nachweis durch Ableiten**
Ableitung von \( F_1(x) \):
$$\frac{d}{dx}\left(\frac{x^3}{3} + \frac{x^2}{2} + C_1\right) = x^2 + x$$

Ableitung von \( F_2(x) \):
$$\frac{d}{dx}\left(\frac{x^3}{3} + \frac{x^2}{2} + C_2\right) = x^2 + x$$

Die Ableitungen zeigen, dass \( F_1(x) \) und \( F_2(x) \) Stammfunktionen sind.

---
### Aufgabe e
Die Funktion lautet: $$f(x) = 1 + \frac{1}{x}$$
**Schritt 1: Stammfunktionen bestimmen**
1. $$F_1(x) = \int \left( 1 + \frac{1}{x} \right) dx = x + \ln|x| + C_1$$
2. $$F_2(x) = \int \left( 1 + \frac{1}{x} \right) dx = x + \ln|x| + C_2$$
**Schritt 2: Nachweis durch Ableiten**
Ableitung von \( F_1(x) \):
$$\frac{d}{dx}\left(x + \ln|x| + C_1\right) = 1 + \frac{1}{x}$$
Ableitung von \( F_2(x) \):
$$\frac{d}{dx}\left(x + \ln|x| + C_2\right) = 1 + \frac{1}{x}$$
Da die Ableitungen \( f(x) \) ergeben, sind \( F_1(x) \) und \( F_2(x) \) Stammfunktionen.

---
![[Pasted image 20250506122205.png]]
### Aufgabe a
$$
\int \frac{x}{x-1} \, dx
$$
**Rechnungsschritte:**
1. Wir schreiben den Bruch als Summe:
   $$
   \frac{x}{x-1} = 1 + \frac{1}{x-1}
   $$
2. Anschließend integrieren wir beide Terme getrennt:
   $$
   \int \frac{x}{x-1} \, dx = \int 1 \, dx + \int \frac{1}{x-1} \, dx
   $$
3. Die Integrale lösen sich wie folgt:
   - $\int 1 \, dx = x$
   - $\int \frac{1}{x-1} \, dx = \ln|x-1|$

4. Kombinieren der Ergebnisse:
   $$
   \int \frac{x}{x-1} \, dx = x + \ln|x-1| + C
   $$
---
**Alternative Darstellung:**
$$
\int \frac{1}{x-1} \, dx
$$
Hierbei handelt es sich lediglich um das Integral des zweiten Terms aus der Zerlegung:
   $$
   \int \frac{1}{x-1} \, dx = \ln|x-1| + C
   $$
---
### Aufgabe b
$$
\int \sin^2(x) \, dx
$$
**Rechnungsschritte:**
1. Verwende die Identität für $\sin^2(x)$:
   $$
   \sin^2(x) = \frac{1 - \cos(2x)}{2}
   $$
2. Ersetze $\sin^2(x)$ im Integral:
   $$
   \int \sin^2(x) \, dx = \int \frac{1 - \cos(2x)}{2} \, dx
   $$
3. Zerlege das Integral:
   $$
   \int \sin^2(x) \, dx = \frac{1}{2} \int 1 \, dx - \frac{1}{2} \int \cos(2x) \, dx
   $$
4. Löse die einzelnen Integrale:
   - $\int 1 \, dx = x$
   - $\int \cos(2x) \, dx = \frac{\sin(2x)}{2}$

5. Füge die Ergebnisse zusammen:
   $$
   \int \sin^2(x) \, dx = \frac{1}{2}x - \frac{1}{4}\sin(2x) + C
   $$
---
**Alternative Darstellung:**
$$
\int -\frac{1}{2}\cos(2x) \, dx
$$
Hierbei handelt es sich um die Umformung des zweiten Terms:
   $$
   \int -\frac{1}{2}\cos(2x) \, dx = -\frac{1}{4}\sin(2x) + C
   $$
![[Pasted image 20250505112956.png]]
### Aufgabe 6.16
**Gegeben:**
In Abb. 6.15 sind zwei Funktionsgraphen dargestellt. Es soll argumentiert werden, warum \( F \) eine Stammfunktion der Funktion \( f \) ist.

---
#### Argumentation:
1. **Steigung von \( F \):**
   - Die Steigung des Graphen von \( F \) in jedem Punkt entspricht dem Funktionswert von \( f \) an dieser Stelle.
   - Das bedeutet, die Ableitungsregel \( F'(x) = f(x) \) ist erfüllt.
   $$
   F'(x) = f(x)
   $$
1. **Monotonieverhalten:**
   - Wenn \( f(x) > 0 \), steigt \( F(x) \) an (der Graph von \( F \) ist ansteigend).
   - Wenn \( f(x) < 0 \), fällt \( F(x) \) ab (der Graph von \( F \) ist abfallend).
   $$
   f(x) > 0 \implies F(x) \text{ ist ansteigend}
   $$
   $$
   f(x) < 0 \implies F(x) \text{ ist abfallend}
   $$
1. **Nullstellen:**
   - Die Nullstellen von \( f(x) \) entsprechen den Extrempunkten von \( F(x) \), da an diesen Stellen \( F'(x) = 0 \).
   $$
   f(x) = 0 \implies \text{Extrempunkt von } F(x)
   $$
1. **Flächeninhalt:**
   - Der Wert von \( F(x) \) in einem Intervall repräsentiert den Flächeninhalt unter dem Graphen von \( f(x) \) in diesem Intervall (bis auf eine Integrationskonstante).
   $$
   F(x) = \int f(x) \, dx
   $$
---
#### Schlussfolgerung:
Die genannten Eigenschaften sind hinreichende Argumente dafür, dass \( F \) die Stammfunktion von \( f \) ist.
![[Pasted image 20250505113003.png]]
### Aufgabe 6.17
**Gegeben:**
In Abb. 6.16 sind die Graphen von vier Funktionen \( f_1 \), \( f_2 \), \( f_3 \) und \( f \) dargestellt. Es soll geprüft werden, ob eine der Funktionen \( f_1 \), \( f_2 \) oder \( f_3 \) eine Stammfunktion von \( f \) sein könnte.

---
#### Lösung und Erklärung:
1. **Eigenschaft der Stammfunktion:**
   - Eine Funktion \( F(x) \) ist eine Stammfunktion von \( f(x) \), wenn die Ableitung von \( F(x) \) gleich \( f(x) \) ist, also:
     $$
     F'(x) = f(x)
     $$

2. **Vorgehen:**
   - Überprüfe, ob die Steigung des Graphen von \( f_1 \), \( f_2 \) oder \( f_3 \) an jedem Punkt dem Funktionswert von \( f \) entspricht.

3. **Monotonieverhalten:**
   - Wenn \( f(x) > 0 \), muss die entsprechende Stammfunktion ansteigend sein.
   - Wenn \( f(x) < 0 \), muss die entsprechende Stammfunktion abfallend sein.

4. **Nullstellen:**
   - Die Nullstellen von \( f(x) \) müssen Extremstellen der Stammfunktion sein, da an diesen Punkten die Steigung der Stammfunktion \( F(x) \) gleich null ist.
---
#### Ergebnis:
- Vergleiche die Graphen in Abb. 6.16 gemäß den oben genannten Kriterien, um zu prüfen, welche der Funktionen \( f_1 \), \( f_2 \) oder \( f_3 \) eine Stammfunktion von \( f \) sein könnte.
![[Pasted image 20250505113011.png]]
### Aufgabe a
$$\int x^3 \, dx$$
Rechnung:
1. Verwende die allgemeine Regel für Potenzfunktionen: $$\int x^n \, dx = \frac{x^{n+1}}{n+1} + C$$
2. Setze $$n = 3$$ ein:  
   $$\int x^3 \, dx = \frac{x^{3+1}}{3+1} + C$$
3. Vereinfache:  
   $$\int x^3 \, dx = \frac{x^4}{4} + C$$
Probe:
1. Bilde die Ableitung des Ergebnisses:  
   $$\frac{d}{dx}\left(\frac{x^4}{4} + C\right) = x^3$$
2. Das entspricht dem ursprünglichen Integranden, daher ist das Ergebnis korrekt.
---
### Aufgabe b
$$\int x^5 \, dx$$
Rechnung:
1. Verwende die Regel für Potenzfunktionen: $$\int x^n \, dx = \frac{x^{n+1}}{n+1} + C$$
2. Setze $$n = 5$$ ein: 
   $$\int x^5 \, dx = \frac{x^{5+1}}{5+1} + C$$
3. Vereinfache:  
   $$\int x^5 \, dx = \frac{x^6}{6} + C$$
Probe:
1. Bilde die Ableitung des Ergebnisses:  
   $$\frac{d}{dx}\left(\frac{x^6}{6} + C\right) = x^5$$
2. Das entspricht dem ursprünglichen Integranden, daher ist das Ergebnis korrekt.
---
### Aufgabe c
$$\int x \, dx$$
Rechnung:
1. Verwende die Regel für Potenzfunktionen: $$\int x^n \, dx = \frac{x^{n+1}}{n+1} + C$$
2. Setze $$n = 1$$ ein:  
   $$\int x \, dx = \frac{x^{1+1}}{1+1} + C$$
3. Vereinfache:  
   $$\int x \, dx = \frac{x^2}{2} + C$$
Probe:
1. Bilde die Ableitung des Ergebnisses:  
   $$\frac{d}{dx}\left(\frac{x^2}{2} + C\right) = x$$
2. Das entspricht dem ursprünglichen Integranden, daher ist das Ergebnis korrekt.
---
### Aufgabe d
$$\int 1 \, dx$$
Rechnung:
1. Das Integral einer Konstanten $$k$$ ist $$\int k \, dx = kx + C$$
2. Setze $$k = 1$$ ein:  
   $$\int 1 \, dx = 1 \cdot x + C = x + C$$
Probe:
1. Bilde die Ableitung des Ergebnisses:  
   $$\frac{d}{dx}(x + C) = 1$$
2. Das entspricht dem ursprünglichen Integranden, daher ist das Ergebnis korrekt.
---
### Aufgabe e
$$\int 0 \, dx$$
Rechnung:
1. Das Integral von $$0$$ ist immer null, da keine Fläche unter der Kurve existiert:  
   $$\int 0 \, dx = 0 + C = C$$
Probe:
1. Bilde die Ableitung des Ergebnisses:  
   $$\frac{d}{dx}(C) = 0$$
2. Das entspricht dem ursprünglichen Integranden, daher ist das Ergebnis korrekt.
---
### Aufgabe f
$$\int \frac{1}{x} \, dx$$
Rechnung:
1. Das Integral von $$\frac{1}{x}$$ ist eine bekannte Regel:  
   $$\int \frac{1}{x} \, dx = \ln|x| + C$$

Probe:
1. Bilde die Ableitung des Ergebnisses:  
   $$\frac{d}{dx}(\ln|x| + C) = \frac{1}{x}$$
2. Das entspricht dem ursprünglichen Integranden, daher ist das Ergebnis korrekt.
---
### Aufgabe g
$$\int \frac{1}{x^3} \, dx$$

Rechnung:
1. Schreibe den Bruch als Potenz: $$\frac{1}{x^3} = x^{-3}$$
2. Verwende die Regel für Potenzfunktionen: $$\int x^n \, dx = \frac{x^{n+1}}{n+1} + C$$
3. Setze $$n = -3$$ ein:  $$\int x^{-3} \, dx = \frac{x^{-3+1}}{-3+1} + C$$
4. Vereinfache:  
   $$\int x^{-3} \, dx = \frac{x^{-2}}{-2} + C = -\frac{1}{2x^2} + C$$
Probe:
1. Bilde die Ableitung des Ergebnisses:  
   $$\frac{d}{dx}\left(-\frac{1}{2x^2} + C\right) = x^{-3} = \frac{1}{x^3}$$
2. Das entspricht dem ursprünglichen Integranden, daher ist das Ergebnis korrekt.
---
### Aufgabe h
$$\int x^{-4} \, dx$$
Rechnung:
1. Verwende die Regel für Potenzfunktionen: $$\int x^n \, dx = \frac{x^{n+1}}{n+1} + C$$
2. Setze $$n = -4$$ ein:  
   $$\int x^{-4} \, dx = \frac{x^{-4+1}}{-4+1} + C$$
3. Vereinfache:  
   $$\int x^{-4} \, dx = \frac{x^{-3}}{-3} + C = -\frac{1}{3x^3} + C$$
Probe:
1. Bilde die Ableitung des Ergebnisses:  
   $$\frac{d}{dx}\left(-\frac{1}{3x^3} + C\right) = x^{-4}$$
2. Das entspricht dem ursprünglichen Integranden, daher ist das Ergebnis korrekt.
---
### Aufgabe i
$$\int x \cdot x^3 \, dx$$
Rechnung:
1. Vereinfache den Integranden: $$x \cdot x^3 = x^{1+3} = x^4$$
2. Verwende die Regel für Potenzfunktionen: $$\int x^n \, dx = \frac{x^{n+1}}{n+1} + C$$
3. Setze $$n = 4$$ ein:  $$\int x^4 \, dx = \frac{x^{4+1}}{4+1} + C$$
4. Vereinfache:  
   $$\int x^4 \, dx = \frac{x^5}{5} + C$$
Probe:
1. Bilde die Ableitung des Ergebnisses:  
   $$\frac{d}{dx}\left(\frac{x^5}{5} + C\right) = x^4$$
2. Das entspricht dem ursprünglichen Integranden, daher ist das Ergebnis korrekt.
---
### Aufgabe j
$$\int x^{-4} \cdot x^3 \, dx$$
Rechnung:
1. Vereinfache den Integranden: $$x^{-4} \cdot x^3 = x^{-4+3} = x^{-1}$$
2. Das Integral von $$x^{-1}$$ ist bekannt:  
   $$\int x^{-1} \, dx = \ln|x| + C$$
Probe:
1. Bilde die Ableitung des Ergebnisses:  
   $$\frac{d}{dx}(\ln|x| + C) = x^{-1} = \frac{1}{x}$$
2. Das entspricht dem ursprünglichen Integranden, daher ist das Ergebnis korrekt.
![[Pasted image 20250505113021.png]]
### Aufgabe a
Bestimmen des unbestimmten Integrals:
$$ \int \sqrt[3]{x} \, dx $$
Rechenschritte:
1. Schreibe den Radikand in Potenzschreibweise:
   $$ \int x^{\frac{1}{3}} \, dx $$
2. Wende die Potenzregel für Integrale an:
   $$ \int x^n \, dx = \frac{x^{n+1}}{n+1} + C, \, n \neq -1 $$
   Hier ist \( n = \frac{1}{3} \).
3. Integriere:
   $$ \frac{x^{\frac{1}{3} + 1}}{\frac{1}{3} + 1} + C = \frac{x^{\frac{4}{3}}}{\frac{4}{3}} + C $$
4. Schreibe den Bruch um:
   $$ \frac{3}{4} x^{\frac{4}{3}} + C $$
Ergebnis:
$$ \int \sqrt[3]{x} \, dx = \frac{3}{4} x^{\frac{4}{3}} + C $$
---
### Aufgabe b

Bestimmen des unbestimmten Integrals:
$$ \int \frac{1}{\sqrt{x}} \, dx $$
Rechenschritte:
1. Schreibe den Bruch in Potenzschreibweise:
   $$ \int x^{-\frac{1}{2}} \, dx $$
2. Wende die Potenzregel für Integrale an:
   $$ \int x^n \, dx = \frac{x^{n+1}}{n+1} + C, \, n \neq -1 $$
   Hier ist \( n = -\frac{1}{2} \).
3. Integriere:
   $$ \frac{x^{-\frac{1}{2} + 1}}{-\frac{1}{2} + 1} + C = \frac{x^{\frac{1}{2}}}{\frac{1}{2}} + C $$
4. Schreibe den Bruch um:
   $$ 2 x^{\frac{1}{2}} + C $$
5. Schreibe das Ergebnis zurück in Wurzelnotation:$$ 2 \sqrt{x} + C $$
Ergebnis:
$$ \int \frac{1}{\sqrt{x}} \, dx = 2 \sqrt{x} + C $$
---
### Aufgabe c
Bestimmen des unbestimmten Integrals:
$$ \int \sqrt{\frac{1}{x}} \, dx $$
Rechenschritte:
1. Schreibe den Radikand in Potenzschreibweise:$$ \int \left(\frac{1}{x}\right)^{\frac{1}{2}} \, dx $$
2. Schreibe den Bruch in Potenzform:
   $$ \int x^{-\frac{1}{2}} \, dx $$
3. Wende die Potenzregel für Integrale an:
   $$ \int x^n \, dx = \frac{x^{n+1}}{n+1} + C, \, n \neq -1 $$
   Hier ist \( n = -\frac{1}{2} \).
4. Integriere:
   $$ \frac{x^{-\frac{1}{2} + 1}}{-\frac{1}{2} + 1} + C = \frac{x^{\frac{1}{2}}}{\frac{1}{2}} + C $$
5. Schreibe den Bruch um:
   $$ 2 x^{\frac{1}{2}} + C $$
6. Schreibe das Ergebnis zurück in Wurzelnotation:
   $$ 2 \sqrt{x} + C $$
Ergebnis:
$$ \int \sqrt{\frac{1}{x}} \, dx = 2 \sqrt{x} + C $$
---
### Aufgabe d
Bestimmen des unbestimmten Integrals:
$$ \int x \cdot \sqrt{x} \, dx $$
Rechenschritte:
1. Schreibe den Term in Potenzschreibweise:
   $$ \int x \cdot x^{\frac{1}{2}} \, dx $$
2. Vereinfachen:
   $$ \int x^{1 + \frac{1}{2}} \, dx = \int x^{\frac{3}{2}} \, dx $$
3. Wende die Potenzregel für Integrale an:
   $$ \int x^n \, dx = \frac{x^{n+1}}{n+1} + C, \, n \neq -1 $$
   Hier ist \( n = \frac{3}{2} \).
4. Integriere:
   $$ \frac{x^{\frac{3}{2} + 1}}{\frac{3}{2} + 1} + C = \frac{x^{\frac{5}{2}}}{\frac{5}{2}} + C $$
5. Schreibe den Bruch um:
   $$ \frac{2}{5} x^{\frac{5}{2}} + C $$
6. Schreibe das Ergebnis zurück in Wurzelnotation:
   $$ \frac{2}{5} x^{\frac{5}{2}} + C = \frac{2}{5} x^2 \sqrt{x} + C $$
Ergebnis:
$$ \int x \cdot \sqrt{x} \, dx = \frac{2}{5} x^2 \sqrt{x} + C $$
![[Pasted image 20250505113030.png]]
### Aufgabe a
$$
\int \sin(x) \, dx = -\cos(x) + C
$$
#### Erklärung:
Das unbestimmte Integral der Sinusfunktion ist die Funktion, deren Ableitung die Sinusfunktion ergibt. Dies ist die negative Kosinusfunktion.

---
### Aufgabe b
$$
\int \cos(x) \, dx = \sin(x) + C
$$
#### Erklärung:
Das unbestimmte Integral der Kosinusfunktion ergibt die Funktion, deren Ableitung der Kosinus ist, also die Sinusfunktion.

---
### Aufgabe c
$$
\int e^x \, dx = e^x + C
$$
#### Erklärung:
Das unbestimmte Integral der Exponentialfunktion \(e^x\) ist wieder \(e^x\), da die Ableitung von \(e^x\) ebenfalls \(e^x\) ist.

---
### Aufgabe d
$$
\int 2^x \, dx = \frac{2^x}{\ln(2)} + C
$$
#### Erklärung:
Das unbestimmte Integral einer Exponentialfunktion \(a^x\) mit Basis \(a > 0\) ist \(\frac{a^x}{\ln(a)}\), da die Ableitung von \(\frac{a^x}{\ln(a)}\) wieder \(a^x\) ergibt.

---
### Aufgabe e
$$
\int x^{\frac{1}{3}} \, dx = \frac{3}{4}x^{\frac{4}{3}} + C
$$
#### Erklärung:
Für Potenzfunktionen \(x^n\) gilt: \(\int x^n \, dx = \frac{x^{n+1}}{n+1} + C\), solange \(n \neq -1\).

---
### Aufgabe f
$$
\int 4^{-x} \, dx = -\frac{4^{-x}}{\ln(4)} + C
$$
#### Erklärung:
Das unbestimmte Integral einer Exponentialfunktion mit negativem Exponenten folgt derselben Regel wie bei positiver Basis, wobei der negative Exponent beachtet wird.

---
### Aufgabe g
$$
\int \frac{1}{\cos^2(x)} \, dx = \tan(x) + C
$$
#### Erklärung:
Die Funktion \(\frac{1}{\cos^2(x)}\) ist identisch mit der Ableitung der Tangensfunktion \(\tan(x)\).

---
### Aufgabe h
$$
\int \frac{1}{\sin^2(x)} \, dx = -\cot(x) + C
$$
#### Erklärung:
Die Funktion \(\frac{1}{\sin^2(x)}\) ist identisch mit der Ableitung der Kotangensfunktion \(-\cot(x)\).

---
### Aufgabe i
$$
\int \frac{1}{1+x^2} \, dx = \arctan(x) + C
$$
#### Erklärung:
Die Funktion \(\frac{1}{1+x^2}\) ist die Ableitung der Arkustangensfunktion \(\arctan(x)\).

---
### Aufgabe j
$$
\int \frac{1}{\sqrt{1+x^2}} \, dx = \ln|x + \sqrt{1+x^2}| + C
$$
#### Erklärung:
Die Funktion \(\frac{1}{\sqrt{1+x^2}}\) ist das unbestimmte Integral, das zur natürlichen Logarithmusfunktion führt, angewendet auf \(x + \sqrt{1+x^2}\).
![[Pasted image 20250505113037.png]]
### Aufgabe a
Gesucht ist die Stammfunktion \(F(x)\) von \(f(x) = x^2\), die durch den Punkt \(P = (3|10)\) geht.
1. Stammfunktion berechnen:
   $$F(x) = \int x^2 \, dx = \frac{x^3}{3} + C$$
2. Konstante \(C\) bestimmen:
   Punkt einsetzen: \(F(3) = 10\)
   $$\frac{3^3}{3} + C = 10$$$$\frac{27}{3} + C = 10$$$$9 + C = 10$$$$C = 1$$

3. Endgültige Stammfunktion:
   $$F(x) = \frac{x^3}{3} + 1$$
---
### Aufgabe b
Gesucht ist die Stammfunktion \(F(x)\) von \(f(x) = \frac{1}{x^3}\), die durch den Punkt \(P = (1|2)\) geht.
1. Stammfunktion berechnen:
   $$F(x) = \int \frac{1}{x^3} \, dx = \int x^{-3} \, dx = -\frac{1}{2x^2} + C$$
2. Konstante \(C\) bestimmen:
   Punkt einsetzen: \(F(1) = 2\)
   $$-\frac{1}{2 \cdot 1^2} + C = 2$$
   $$-\frac{1}{2} + C = 2$$
   $$C = 2 + \frac{1}{2}$$
   $$C = \frac{5}{2}$$
3. Endgültige Stammfunktion:
   $$F(x) = -\frac{1}{2x^2} + \frac{5}{2}$$
---
### Aufgabe c
Gesucht ist die Stammfunktion \(F(x)\) von \(f(x) = \frac{1}{\sqrt{x}}\), die durch den Punkt \(P = (4|5)\) geht.
1. Stammfunktion berechnen:
   $$F(x) = \int \frac{1}{\sqrt{x}} \, dx = \int x^{-\frac{1}{2}} \, dx = 2\sqrt{x} + C$$
2. Konstante \(C\) bestimmen:
   Punkt einsetzen: \(F(4) = 5\)
   $$2\sqrt{4} + C = 5$$
   $$2 \cdot 2 + C = 5$$
   $$4 + C = 5$$
   $$C = 1$$
3. Endgültige Stammfunktion:
   $$F(x) = 2\sqrt{x} + 1$$
---
### Aufgabe d
Gesucht ist die Stammfunktion \(F(x)\) von \(f(x) = e^x\), die durch den Punkt \(P = (0|3)\) geht.
1. Stammfunktion berechnen:
   $$F(x) = \int e^x \, dx = e^x + C$$
2. Konstante \(C\) bestimmen:
   Punkt einsetzen: \(F(0) = 3\)
   $$e^0 + C = 3$$
   $$1 + C = 3$$
   $$C = 2$$
3. Endgültige Stammfunktion:
   $$F(x) = e^x + 2$$
---
### Aufgabe e
Gesucht ist die Stammfunktion \(F(x)\) von \(f(x) = \sin(x)\), die durch den Punkt \(P = (\pi|2)\) geht.
1. Stammfunktion berechnen:
   $$F(x) = \int \sin(x) \, dx = -\cos(x) + C$$
2. Konstante \(C\) bestimmen:
   Punkt einsetzen: \(F(\pi) = 2\)
   $$-\cos(\pi) + C = 2$$
   $$-(-1) + C = 2$$
   $$1 + C = 2$$
   $$C = 1$$
3. Endgültige Stammfunktion:
   $$F(x) = -\cos(x) + 1$$
---
### Aufgabe f
Gesucht ist die Stammfunktion \(F(x)\) von \(f(x) = \sinh(x)\), die durch den Punkt \(P = (-1|2)\) geht.
1. Stammfunktion berechnen:
   $$F(x) = \int \sinh(x) \, dx = \cosh(x) + C$$
2. Konstante \(C\) bestimmen:
   Punkt einsetzen: \(F(-1) = 2\)
   $$\cosh(-1) + C = 2$$
   $$\cosh(-1) = \cosh(1) = \frac{e^1 + e^{-1}}{2} = \frac{e + \frac{1}{e}}{2}$$
   $$C = 2 - \cosh(1)$$
3. Endgültige Stammfunktion:
   $$F(x) = \cosh(x) + 2 - \cosh(1)$$
---
![[Pasted image 20250505113110.png]]
![[Pasted image 20250505113130.png]]
### Aufgabe a
$$
\int_{0}^{3} x^2 \, dx = \left[\frac{x^3}{3}\right]_{0}^{3} = \frac{3^3}{3} - \frac{0^3}{3} = \frac{27}{3} - 0 = 9
$$
---
### Aufgabe b
$$
\int_{-2}^{2} x^2 \, dx = \left[\frac{x^3}{3}\right]_{-2}^{2} = \frac{2^3}{3} - \frac{(-2)^3}{3} = \frac{8}{3} - \frac{-8}{3} = \frac{8}{3} + \frac{8}{3} = \frac{16}{3}
$$
---
### Aufgabe c
$$
\int_{-2}^{2} t^3 \, dt = \left[\frac{t^4}{4}\right]_{-2}^{2} = \frac{2^4}{4} - \frac{(-2)^4}{4} = \frac{16}{4} - \frac{16}{4} = 4 - 4 = 0
$$
---
### Aufgabe d
$$
\int_{0}^{2} x^3 \, dx = \left[\frac{x^4}{4}\right]_{0}^{2} = \frac{2^4}{4} - \frac{0^4}{4} = \frac{16}{4} - 0 = 4
$$
---
### Aufgabe e
$$
\int_{1}^{2} 1 \, dx = \left[x\right]_{1}^{2} = 2 - 1 = 1
$$
---
### Aufgabe f
$$
\int_{1}^{2} x^{-3} \, dx = \left[\frac{x^{-2}}{-2}\right]_{1}^{2} = \left[-\frac{1}{2x^2}\right]_{1}^{2} = -\frac{1}{2 \cdot 2^2} + \frac{1}{2 \cdot 1^2} = -\frac{1}{8} + \frac{1}{2} = \frac{-1 + 4}{8} = \frac{3}{8}
$$
---
### Aufgabe g
$$
\int_{1}^{2} \frac{1}{x} \, dx = \left[\ln|x|\right]_{1}^{2} = \ln|2| - \ln|1| = \ln(2) - \ln(1) = \ln(2)
$$
---
### Aufgabe h
$$
\int_{-2}^{-1} \frac{1}{x} \, dx = \left[\ln|x|\right]_{-2}^{-1} = \ln|-1| - \ln|-2| = \ln(1) - \ln(2) = 0 - \ln(2) = -\ln(2)
$$
---
### Aufgabe i
$$
\int_{0.5}^{1} \frac{1}{t^2} \, dt = \int_{0.5}^{1} t^{-2} \, dt = \left[-\frac{1}{t}\right]_{0.5}^{1} = -\frac{1}{1} + \frac{1}{0.5} = -1 + 2 = 1
$$
---
### Aufgabe j
$$
\int_{1}^{4} \frac{1}{\sqrt{v}} \, dv = \int_{1}^{4} v^{-\frac{1}{2}} \, dv = \left[2v^{\frac{1}{2}}\right]_{1}^{4} = 2\sqrt{4} - 2\sqrt{1} = 2 \cdot 2 - 2 \cdot 1 = 4 - 2 = 2
$$
---
### Aufgabe k
$$
\int_{0.5}^{1} \sqrt{t} \, dt = \int_{0.5}^{1} t^{\frac{1}{2}} \, dt = \left[\frac{2}{3}t^{\frac{3}{2}}\right]_{0.5}^{1} = \frac{2}{3}(1^{\frac{3}{2}}) - \frac{2}{3}(0.5^{\frac{3}{2}}) = \frac{2}{3} - \frac{2}{3} \cdot \sqrt{0.5^3} = \frac{2}{3} - \frac{2}{3} \cdot \sqrt{0.125}
$$
Da $$\sqrt{0.125} \approx 0.3536$$
$$
\frac{2}{3} - \frac{2}{3} \cdot 0.3536 \approx \frac{2}{3} - 0.2357 = \frac{2}{3} - \frac{2357}{10000} = \frac{20000 - 2357}{30000} = \frac{17643}{30000}
$$
---
### Aufgabe l
$$
\int_{0.5}^{1} \sqrt{\frac{1}{t}} \, dt = \int_{0.5}^{1} t^{-\frac{1}{2}} \, dt = \left[2t^{\frac{1}{2}}\right]_{0.5}^{1} = 2\sqrt{1} - 2\sqrt{0.5} = 2 - 2\sqrt{0.5}
$$
Da $$\sqrt{0.5} \approx 0.7071$$
$$
2 - 2 \cdot 0.7071 = 2 - 1.4142 = 0.5858
$$
![[Pasted image 20250505113144.png]]
### Aufgabe a)
Berechne das Integral:
$$\int_{-2}^{1} e^x \, dx$$

Rechnung:

1. Stammfunktion von \(e^x\) ist ebenfalls \(e^x\).
2. Einsetzen der Grenzen:
   $$\left[ e^x \right]_{-2}^{1} = e^1 - e^{-2}$$
   $$e^1 = e \quad \text{und} \quad e^{-2} = \frac{1}{e^2}$$
   Daraus folgt:
   $$e - \frac{1}{e^2}$$
---

### Aufgabe b)
Berechne das Integral:
$$\int_{-1}^{1} (2 + e^x) \, dx$$
Rechnung:
1. Zerlegen des Integrals:
   $$\int_{-1}^{1} (2 + e^x) \, dx = \int_{-1}^{1} 2 \, dx + \int_{-1}^{1} e^x \, dx$$
2. Berechnung des ersten Terms:
   $$\int_{-1}^{1} 2 \, dx = 2 \cdot \left[ x \right]_{-1}^{1} = 2 \cdot \left( 1 - (-1) \right) = 2 \cdot 2 = 4$$
3. Berechnung des zweiten Terms:
   $$\int_{-1}^{1} e^x \, dx = \left[ e^x \right]_{-1}^{1} = e^1 - e^{-1} = e - \frac{1}{e}$$
4. Zusammenfügen der Ergebnisse:
   $$4 + \left( e - \frac{1}{e} \right)$$
---
### Aufgabe c)
Berechne das Integral:
$$\int_{-1}^{0} (x + e^x) \, dx$$
Rechnung:
1. Zerlegen des Integrals:
   $$\int_{-1}^{0} (x + e^x) \, dx = \int_{-1}^{0} x \, dx + \int_{-1}^{0} e^x \, dx$$
2. Berechnung des ersten Terms (\(x\)):
   $$\int_{-1}^{0} x \, dx = \left[ \frac{x^2}{2} \right]_{-1}^{0} = \frac{0^2}{2} - \frac{(-1)^2}{2} = 0 - \frac{1}{2} = -\frac{1}{2}$$
3. Berechnung des zweiten Terms (\(e^x\)):
   $$\int_{-1}^{0} e^x \, dx = \left[ e^x \right]_{-1}^{0} = e^0 - e^{-1} = 1 - \frac{1}{e}$$
4. Zusammenfügen der Ergebnisse:
   $$-\frac{1}{2} + \left( 1 - \frac{1}{e} \right)$$
---
### Aufgabe d)
Berechne das Integral:
$$\int_{1}^{3} 2x \, dx$$
Rechnung:
1. Stammfunktion von \(2x\) ist \(x^2\).
2. Einsetzen der Grenzen:
   $$\left[ x^2 \right]_{1}^{3} = 3^2 - 1^2 = 9 - 1 = 8$$
---
### Aufgabe e)
Berechne das Integral:
$$\int_{0}^{1} \left( 1 + \frac{x}{3} \right) \, dx$$
Rechnung:
1. Zerlegen des Integrals:
   $$\int_{0}^{1} \left( 1 + \frac{x}{3} \right) \, dx = \int_{0}^{1} 1 \, dx + \int_{0}^{1} \frac{x}{3} \, dx$$
2. Berechnung des ersten Terms:
   $$\int_{0}^{1} 1 \, dx = \left[ x \right]_{0}^{1} = 1 - 0 = 1$$
3. Berechnung des zweiten Terms:
   $$\int_{0}^{1} \frac{x}{3} \, dx = \frac{1}{3} \int_{0}^{1} x \, dx = \frac{1}{3} \cdot \left[ \frac{x^2}{2} \right]_{0}^{1} = \frac{1}{3} \cdot \left( \frac{1^2}{2} - \frac{0^2}{2} \right) = \frac{1}{3} \cdot \frac{1}{2} = \frac{1}{6}$$
4. Zusammenfügen der Ergebnisse:
   $$1 + \frac{1}{6} = \frac{6}{6} + \frac{1}{6} = \frac{7}{6}$$
---
### Aufgabe f)
Berechne das Integral:
$$\int_{0}^{\pi/2} \sin x \, dx$$
Rechnung:
1. Stammfunktion von \(\sin x\) ist \(-\cos x\).
2. Einsetzen der Grenzen:
   $$\left[ -\cos x \right]_{0}^{\pi/2} = -\cos\left(\frac{\pi}{2}\right) - \left(-\cos(0)\right)$$
3. Werte einsetzen:
   $$-\cos\left(\frac{\pi}{2}\right) = -0 \quad \text{und} \quad \cos(0) = 1$$
4. Ergebnis:
   $$0 - (-1) = 1$$
---
### Aufgabe g)
Berechne das Integral:
$$\int_{0}^{\pi} \sin t \, dt$$
Rechnung:
1. Stammfunktion von \(\sin t\) ist \(-\cos t\).
2. Einsetzen der Grenzen:
   $$\left[ -\cos t \right]_{0}^{\pi} = -\cos(\pi) - \left(-\cos(0)\right)$$
3. Werte einsetzen:
   $$-\cos(\pi) = -(-1) = 1 \quad \text{und} \quad \cos(0) = 1$$
4. Ergebnis:
   $$1 - (-1) = 2$$
---
### Aufgabe h)
Berechne das Integral:
$$\int_{-\pi/2}^{\pi/2} \cos t \, dt$$
Rechnung:
1. Stammfunktion von \(\cos t\) ist \(\sin t\).
2. Einsetzen der Grenzen:
   $$\left[ \sin t \right]_{-\pi/2}^{\pi/2} = \sin\left(\frac{\pi}{2}\right) - \sin\left(-\frac{\pi}{2}\right)$$
3. Werte einsetzen:
   $$\sin\left(\frac{\pi}{2}\right) = 1 \quad \text{und} \quad \sin\left(-\frac{\pi}{2}\right) = -1$$
4. Ergebnis:
   $$1 - (-1) = 2$$
---
![[Pasted image 20250505113158.png]]
### Aufgabe a)
Berechne das Integral:
$$\int_{-2}^{2} x^3 \, dx$$
Rechnung:
1. Stammfunktion von \(x^3\) ist \(\frac{x^4}{4}\).
2. Einsetzen der Grenzen:
   $$\left[ \frac{x^4}{4} \right]_{-2}^{2} = \frac{2^4}{4} - \frac{(-2)^4}{4}$$
3. Werte einsetzen:
   $$\frac{2^4}{4} = \frac{16}{4} = 4 \quad \text{und} \quad \frac{(-2)^4}{4} = \frac{16}{4} = 4$$
4. Ergebnis:
   $$4 - 4 = 0$$
Das Integral ist **null**.
---
### Aufgabe b)
Berechne das Integral:
$$\int_{-2}^{2} (-x^2) \, dx$$
Rechnung:
1. Stammfunktion von \(-x^2\) ist \(-\frac{x^3}{3}\).
2. Einsetzen der Grenzen:
   $$\left[ -\frac{x^3}{3} \right]_{-2}^{2} = -\frac{2^3}{3} - \left(-\frac{(-2)^3}{3}\right)$$
3. Werte einsetzen:
   $$-\frac{2^3}{3} = -\frac{8}{3} \quad \text{und} \quad -\left(-\frac{(-2)^3}{3}\right) = -\left(-\frac{-8}{3}\right) = \frac{-8}{3}$$
4. Ergebnis:
   $$-\frac{8}{3} - \frac{-8}{3} = -\frac{8}{3} + \frac{8}{3} = 0$$
Das Integral ist **null**.
---
### Aufgabe c)
Berechne das Integral:
$$\int_{2}^{4} e^x \, dx$$
Rechnung:
1. Stammfunktion von \(e^x\) ist ebenfalls \(e^x\).
2. Einsetzen der Grenzen:
   $$\left[ e^x \right]_{2}^{4} = e^4 - e^2$$
Das Integral ist **positiv**, da \(e^4 > e^2\).
---
### Aufgabe d)
Berechne das Integral:
$$\int_{-\pi}^{\pi} \sin x \, dx$$
Rechnung:
1. Stammfunktion von \(\sin x\) ist \(-\cos x\).
2. Einsetzen der Grenzen:
   $$\left[ -\cos x \right]_{-\pi}^{\pi} = -\cos(\pi) - \left(-\cos(-\pi)\right)$$
3. Werte einsetzen:
   $$-\cos(\pi) = -(-1) = 1 \quad \text{und} \quad -\cos(-\pi) = -(-1) = 1$$
4. Ergebnis:
   $$1 - 1 = 0$$
Das Integral ist **null**.
---
### Aufgabe e)
Berechne das Integral:
$$\int_{-\pi}^{\pi} \cos x \, dx$$
Rechnung:
1. Stammfunktion von \(\cos x\) ist \(\sin x\).
2. Einsetzen der Grenzen:
   $$\left[ \sin x \right]_{-\pi}^{\pi} = \sin(\pi) - \sin(-\pi)$$
3. Werte einsetzen:
   $$\sin(\pi) = 0 \quad \text{und} \quad \sin(-\pi) = 0$$
4. Ergebnis:
   $$0 - 0 = 0$$
Das Integral ist **null**.
---
![[Pasted image 20250505113209.png]]
### Aufgabe a)
Gegeben ist die Gleichung:
$$\int_a^5 x \, dx = 12$$
1. Berechnung der Stammfunktion \( F(x) \):$$F(x) = \frac{x^2}{2}$$
2. Einsetzen der Integrationsgrenzen in die Stammfunktion:
   $$\left[ \frac{x^2}{2} \right]_a^5 = 12$$
3. Auflösen der Gleichung:$$\frac{5^2}{2} - \frac{a^2}{2} = 12$$
4. Vereinfachen:
   $$\frac{25}{2} - \frac{a^2}{2} = 12$$
5. Multiplizieren mit \(2\), um die Brüche zu eliminieren:
   $$25 - a^2 = 24$$
6. Umstellen nach \(a^2\):
   $$a^2 = 25 - 24$$
   $$a^2 = 1$$
7. Wurzel ziehen:
   $$a = \pm1$$
Da \(a\) kleiner als die obere Grenze (\(5\)) sein muss, ist:
   $$a = 1$$
---
### Aufgabe b)
Gegeben ist die Gleichung:
$$\int_1^b \sqrt{x} \, dx = \frac{14}{3}$$
1. Berechnung der Stammfunktion \( F(x) \):
   $$F(x) = \frac{2}{3}x^{\frac{3}{2}}$$
2. Einsetzen der Integrationsgrenzen in die Stammfunktion:
   $$\left[ \frac{2}{3}x^{\frac{3}{2}} \right]_1^b = \frac{14}{3}$$
3. Auflösen der Gleichung:
   $$\frac{2}{3}b^{\frac{3}{2}} - \frac{2}{3} \cdot 1^{\frac{3}{2}} = \frac{14}{3}$$
4. Vereinfachen:
   $$\frac{2}{3}b^{\frac{3}{2}} - \frac{2}{3} = \frac{14}{3}$$
5. Umstellen nach \(b^{\frac{3}{2}}\):
   $$\frac{2}{3}b^{\frac{3}{2}} = \frac{14}{3} + \frac{2}{3}$$
   $$\frac{2}{3}b^{\frac{3}{2}} = \frac{16}{3}$$
6. Multiplizieren mit \( \frac{3}{2} \), um die Brüche zu eliminieren:
   $$b^{\frac{3}{2}} = \frac{16}{3} \cdot \frac{3}{2}$$
   $$b^{\frac{3}{2}} = 8$$
7. Umformen nach \(b\):
   $$b = \left(8\right)^{\frac{2}{3}}$$
8. Vereinfachen:
   $$b = \left(2^3\right)^{\frac{2}{3}}$$
   $$b = 2^2$$
   $$b = 4$$
--- 
![[Pasted image 20250505113224.png]]
![[Pasted image 20250505113236.png]]
![[Pasted image 20250505113250.png]]
### Aufgabe a
Berechne das Integral $$\int 2e^x \, dx$$
1. Die Funktion \( 2e^x \) ist die Ableitung von \( 2e^x \), daher:
   $$\int 2e^x \, dx = 2e^x + C$$
   wobei \( C \) die Integrationskonstante ist.
---
### Aufgabe b
Berechne das Integral $$\int 5x^0 \, dx$$
1. \( x^0 = 1 \), daher wird die Gleichung zu:
   $$\int 5 \cdot 1 \, dx = \int 5 \, dx$$
2. Das Integral einer Konstante \( 5 \) ist \( 5x \):
   $$\int 5x^0 \, dx = 5x + C$$
---
### Aufgabe c
Berechne das Integral $$\int 7 \, dx$$
1. Dies ist ein einfaches Integral einer Konstante:
   $$\int 7 \, dx = 7x + C$$
---
### Aufgabe d
Berechne das Integral $$\int x \ln 2 \, dx$$
1. Da \( \ln 2 \) eine Konstante ist, kann sie ausgeklammert werden:
   $$\int x \ln 2 \, dx = \ln 2 \int x \, dx$$
2. Das Integral von \( x \) ist \( \frac{x^2}{2} \):
   $$\ln 2 \int x \, dx = \ln 2 \cdot \frac{x^2}{2} + C$$
3. Zusammengefasst ergibt sich:
   $$\int x \ln 2 \, dx = \frac{\ln 2}{2} x^2 + C$$
---
### Aufgabe e
Berechne das Integral $$\int \frac{a}{x^2} \, dx$$
1. Schreibe den Bruch als Potenz: \( \frac{a}{x^2} = a \cdot x^{-2} \):
   $$\int \frac{a}{x^2} \, dx = \int a \cdot x^{-2} \, dx$$
2. Ziehe die Konstante \( a \) vor das Integral:
   $$a \int x^{-2} \, dx$$
3. Das Integral von \( x^n \) (mit \( n \neq -1 \)) ist \( \frac{x^{n+1}}{n+1} \):
   $$a \cdot \frac{x^{-1}}{-1} + C = -\frac{a}{x} + C$$
4. Zusammengefasst ergibt sich:
   $$\int \frac{a}{x^2} \, dx = -\frac{a}{x} + C$$
---
### Aufgabe f
Berechne das Integral $$\int \frac{1}{3} u^2 \, du$$
1. Ziehe die Konstante \( \frac{1}{3} \) vor das Integral:
   $$\frac{1}{3} \int u^2 \, du$$
2. Das Integral von \( u^2 \) ist \( \frac{u^3}{3} \):
   $$\frac{1}{3} \cdot \frac{u^3}{3} + C = \frac{u^3}{9} + C$$
3. Zusammengefasst ergibt sich:
   $$\int \frac{1}{3} u^2 \, du = \frac{u^3}{9} + C$$
---
### Aufgabe g
Berechne das Integral $$\int \frac{1}{2x} \, dx$$
1. Ziehe die Konstante \( \frac{1}{2} \) vor das Integral:
   $$\frac{1}{2} \int \frac{1}{x} \, dx$$
2. Das Integral von \( \frac{1}{x} \) ist \( \ln|x| \):
   $$\frac{1}{2} \ln|x| + C$$
3. Zusammengefasst ergibt sich:
   $$\int \frac{1}{2x} \, dx = \frac{1}{2} \ln|x| + C$$
---
### Aufgabe h
Berechne das Integral $$\int \frac{x}{2b \sqrt{x}} \, dx$$
1. Vereinfache den Bruch: \( \frac{x}{\sqrt{x}} = \sqrt{x} \):
   $$\int \frac{x}{2b \sqrt{x}} \, dx = \frac{1}{2b} \int \sqrt{x} \, dx$$
2. Schreibe \( \sqrt{x} \) als Potenz: \( x^{\frac{1}{2}} \):
   $$\frac{1}{2b} \int x^{\frac{1}{2}} \, dx$$
3. Das Integral von \( x^n \) (mit \( n \neq -1 \)) ist \( \frac{x^{n+1}}{n+1} \):
   $$\frac{1}{2b} \cdot \frac{x^{\frac{3}{2}}}{\frac{3}{2}} + C = \frac{1}{3b} x^{\frac{3}{2}} + C$$
4. Zusammengefasst ergibt sich:
   $$\int \frac{x}{2b \sqrt{x}} \, dx = \frac{1}{3b} x^{\frac{3}{2}} + C$$
---
### Aufgabe i
Berechne das Integral $$\int \frac{2x}{\sqrt[3]{x}} \, dx$$
1. Schreibe den Bruch als Potenz: \( \frac{x}{\sqrt[3]{x}} = x^{1 - \frac{1}{3}} = x^{\frac{2}{3}} \):
   $$\int \frac{2x}{\sqrt[3]{x}} \, dx = \int 2x^{\frac{2}{3}} \, dx$$
2. Ziehe die Konstante \( 2 \) vor das Integral:
   $$2 \int x^{\frac{2}{3}} \, dx$$
3. Das Integral von \( x^n \) (mit \( n \neq -1 \)) ist \( \frac{x^{n+1}}{n+1} \):
   $$2 \cdot \frac{x^{\frac{5}{3}}}{\frac{5}{3}} + C = \frac{6}{5} x^{\frac{5}{3}} + C$$
4. Zusammengefasst ergibt sich:
   $$\int \frac{2x}{\sqrt[3]{x}} \, dx = \frac{6}{5} x^{\frac{5}{3}} + C$$
---
### Aufgabe j
Berechne das Integral $$\int \sin \frac{x}{2} \, dx$$
1. Setze \( u = \frac{x}{2} \), sodass \( du = \frac{1}{2} dx \) und \( dx = 2 \, du \):
   $$\int \sin \frac{x}{2} \, dx = 2 \int \sin u \, du$$
2. Das Integral von \( \sin u \) ist \( -\cos u \):
   $$2 \cdot (-\cos u) + C = -2 \cos u + C$$
3. Rücksubstitution \( u = \frac{x}{2} \):
   $$-2 \cos \frac{x}{2} + C$$
4. Zusammengefasst ergibt sich:
   $$\int \sin \frac{x}{2} \, dx = -2 \cos \frac{x}{2} + C$$
---
### Aufgabe k
Berechne das Integral $$\int \frac{1}{\sqrt{2}} \cdot 4 \sin x \, dx$$
1. Ziehe die Konstanten \( \frac{1}{\sqrt{2}} \cdot 4 \) vor das Integral:
   $$\frac{4}{\sqrt{2}} \int \sin x \, dx$$
2. Das Integral von \( \sin x \) ist \( -\cos x \):
   $$\frac{4}{\sqrt{2}} \cdot (-\cos x) + C = -\frac{4}{\sqrt{2}} \cos x + C$$
3. Vereinfache den Vorfaktor:
   $$-\frac{4}{\sqrt{2}} = -2\sqrt{2}$$
4. Zusammengefasst ergibt sich:
   $$\int \frac{1}{\sqrt{2}} \cdot 4 \sin x \, dx = -2\sqrt{2} \cos x + C$$
---
### Aufgabe l
Berechne das Integral $$\int \frac{5}{3} \cdot \frac{\cos x}{2\pi} \, dx$$
1. Ziehe die Konstanten \( \frac{5}{3} \cdot \frac{1}{2\pi} \) vor das Integral:
   $$\frac{5}{6\pi} \int \cos x \, dx$$
2. Das Integral von \( \cos x \) ist \( \sin x \):
   $$\frac{5}{6\pi} \sin x + C$$
3. Zusammengefasst ergibt sich:
   $$\int \frac{5}{3} \cdot \frac{\cos x}{2\pi} \, dx = \frac{5}{6\pi} \sin x + C$$
![[Pasted image 20250505113259.png]]
### Aufgabe a
Die gegebene Aufgabe lautet:
$$\int (2x^3 - 4x + 5) \, dx$$
#### Lösung:
1. Jede Potenz von \(x\) wird integriert, indem man die Potenz um eins erhöht und den Koeffizienten durch die neue Potenz teilt:
   - \(2x^3 \to \frac{2}{4}x^4 = \frac{1}{2}x^4\)
   - \(-4x \to \frac{-4}{2}x^2 = -2x^2\)
   - \(5 \to 5x\)

2. Summiere die integrierten Terme:
$$\frac{1}{2}x^4 - 2x^2 + 5x + C$$
---
### Aufgabe b
Die gegebene Aufgabe lautet:
$$\int \left( \frac{5}{3}x - \frac{1}{3} \right) \, dx$$
#### Lösung:
1. Jede Potenz von \(x\) wird integriert:
   - \(\frac{5}{3}x \to \frac{5}{3} \cdot \frac{x^2}{2} = \frac{5}{6}x^2\)
   - \(-\frac{1}{3} \to -\frac{1}{3}x\)

2. Summiere die integrierten Terme:
$$\frac{5}{6}x^2 - \frac{1}{3}x + C$$
---

### Aufgabe c
Die gegebene Aufgabe lautet:
$$\int \left( \frac{2}{x} + \frac{1}{x^2} \right) \, dx$$
#### Lösung:
1. Integriere jeden Term einzeln:
   - \(\frac{2}{x} \to 2 \ln|x|\)
   - \(\frac{1}{x^2} \to -\frac{1}{x}\)

2. Summiere die integrierten Terme:
$$2 \ln|x| - \frac{1}{x} + C$$
---
### Aufgabe d
Die gegebene Aufgabe lautet:
$$\int \left( \frac{2t - 1}{2} \right) \, dt$$
#### Lösung:
1. Vereinfache den Ausdruck:
   \(\frac{2t - 1}{2} = t - \frac{1}{2}\)

2. Integriere jeden Term einzeln:
   - \(t \to \frac{t^2}{2}\)
   - \(-\frac{1}{2} \to -\frac{1}{2}t\)

3. Summiere die integrierten Terme:
$$\frac{t^2}{2} - \frac{1}{2}t + C$$
---
### Aufgabe e
Die gegebene Aufgabe lautet:
$$\int \left( x + \frac{3}{x} \right) \, dx$$
#### Lösung:
1. Integriere jeden Term einzeln:
   - \(x \to \frac{x^2}{2}\)
   - \(\frac{3}{x} \to 3 \ln|x|\)

2. Summiere die integrierten Terme:
$$\frac{x^2}{2} + 3 \ln|x| + C$$
---
### Aufgabe f
Die gegebene Aufgabe lautet:
$$\int \left( t + 2e^t \right) \, dt$$
#### Lösung:
1. Integriere jeden Term einzeln:
   - \(t \to \frac{t^2}{2}\)
   - \(2e^t \to 2e^t\)

2. Summiere die integrierten Terme:
$$\frac{t^2}{2} + 2e^t + C$$
---
### Aufgabe g
Die gegebene Aufgabe lautet:
$$\int \left( \frac{2 - t}{t^2} \right) \, dt$$
#### Lösung:
1. Teile jeden Term durch \(t^2\):
   \(\frac{2 - t}{t^2} = \frac{2}{t^2} - \frac{t}{t^2} = 2t^{-2} - t^{-1}\)

2. Integriere jeden Term einzeln:
   - \(2t^{-2} \to 2 \cdot \frac{t^{-1}}{-1} = -\frac{2}{t}\)
   - \(-t^{-1} \to -\ln|t|\)

3. Summiere die integrierten Terme:
$$-\frac{2}{t} - \ln|t| + C$$
---
### Aufgabe h
Die gegebene Aufgabe lautet:
$$\int \left( \frac{u + 5}{u^3} \right) \, du$$
#### Lösung:
1. Teile jeden Term durch \(u^3\):
   \(\frac{u + 5}{u^3} = \frac{u}{u^3} + \frac{5}{u^3} = u^{-2} + 5u^{-3}\)

2. Integriere jeden Term einzeln:
   - \(u^{-2} \to \frac{u^{-1}}{-1} = -\frac{1}{u}\)
   - \(5u^{-3} \to 5 \cdot \frac{u^{-2}}{-2} = -\frac{5}{2u^2}\)

3. Summiere die integrierten Terme:
$$-\frac{1}{u} - \frac{5}{2u^2} + C$$
![[Pasted image 20250505113315.png]]
### Aufgabe a)
$$\int \sqrt{2x} \, dx$$
1. Setze \( u = 2x \), sodass \( du = 2 \, dx \).
2. Die Gleichung wird zu:
   $$\frac{1}{2} \int \sqrt{u} \, du$$
3. Das Integral von \( \sqrt{u} \) ist:
   $$\frac{1}{2} \cdot \frac{2}{3} u^{\frac{3}{2}} + C$$
4. Rücksubstitution führt zu:
   $$\frac{1}{3} (2x)^{\frac{3}{2}} + C$$
---
### Aufgabe b)
$$\int \sqrt{\frac{x}{2}} \, dx$$
1. Schreibe um zu:
   $$\int \frac{\sqrt{x}}{\sqrt{2}} \, dx = \frac{1}{\sqrt{2}} \int x^{\frac{1}{2}} \, dx$$
2. Das Integral von \( x^{\frac{1}{2}} \) ist:
   $$\frac{1}{\sqrt{2}} \cdot \frac{2}{3} x^{\frac{3}{2}} + C$$
3. Das ergibt:
   $$\frac{\sqrt{2}}{3} x^{\frac{3}{2}} + C$$
---
### Aufgabe c)
$$\int \left(\frac{1}{\sqrt{x}} - \frac{\sqrt{x}}{x}\right) \, dx$$
1. Zerlege in zwei Terme:
   $$\int \frac{1}{\sqrt{x}} \, dx - \int \frac{\sqrt{x}}{x} \, dx$$
2. Der erste Term:
   $$\int x^{-\frac{1}{2}} \, dx = 2x^{\frac{1}{2}}$$
3. Der zweite Term:
   $$\int x^{-1} \, dx = \ln|x|$$
4. Zusammen ergibt das:
   $$2\sqrt{x} - \ln|x| + C$$
---
### Aufgabe d)
$$\int \frac{x^2 + x}{2x} \, dx$$
1. Schreibe als:
   $$\int \frac{x^2}{2x} \, dx + \int \frac{x}{2x} \, dx$$
2. Vereinfache:
   $$\int \frac{x}{2} \, dx + \int \frac{1}{2} \, dx$$
3. Der erste Term:
   $$\frac{1}{2} \int x \, dx = \frac{1}{2} \cdot \frac{x^2}{2} = \frac{x^2}{4}$$
4. Der zweite Term:
   $$\frac{1}{2} \int 1 \, dx = \frac{x}{2}$$
5. Zusammen ergibt das:
   $$\frac{x^2}{4} + \frac{x}{2} + C$$
---
### Aufgabe e)
$$\int \frac{x^2 - x + 1}{x^2} \, dx$$

1. Zerlege in:
   $$\int 1 \, dx - \int \frac{x}{x^2} \, dx + \int \frac{1}{x^2} \, dx$$
2. Der erste Term:
   $$\int 1 \, dx = x$$
3. Der zweite Term:
   $$\int x^{-1} \, dx = \ln|x|$$
4. Der dritte Term:
   $$\int x^{-2} \, dx = -\frac{1}{x}$$
5. Zusammen ergibt das:
   $$x - \ln|x| - \frac{1}{x} + C$$
---
### Aufgabe f)
$$\int \frac{2 - x}{\sqrt{x}} \, dx$$
1. Zerlege in:
   $$\int \frac{2}{\sqrt{x}} \, dx - \int \frac{x}{\sqrt{x}} \, dx$$
2. Der erste Term:
   $$2 \int x^{-\frac{1}{2}} \, dx = 4x^{\frac{1}{2}}$$
3. Der zweite Term:
   $$\int x^{\frac{1}{2}} \, dx = \frac{2}{3} x^{\frac{3}{2}}$$
4. Zusammen ergibt das:
   $$4\sqrt{x} - \frac{2}{3}x^{\frac{3}{2}} + C$$
---
### Aufgabe g)
$$\int e^{x+1} \, dx$$
1. Setze \( u = x+1 \), sodass \( du = dx \).
2. Das Integral wird:
   $$\int e^u \, du = e^u + C$$
3. Rücksubstitution ergibt:
   $$e^{x+1} + C$$
---
### Aufgabe h)
$$\int 2^{2x} \, dx$$
1. Schreibe um zu:
   $$\int (2^x)^2 \, dx = \int 4^x \, dx$$
2. Das Integral von \( a^x \) ist:
   $$\frac{a^x}{\ln(a)}$$
3. Das ergibt:
   $$\frac{4^x}{\ln(4)} + C$$
---
### Aufgabe i)
$$\int (t+1)^2 \, dt$$
1. Entwickle den Term:
   $$\int (t^2 + 2t + 1) \, dt$$
2. Integriere jeden Term:
   $$\frac{t^3}{3} + t^2 + t + C$$
---
### Aufgabe j)
$$\int \left(1 + \frac{1}{x}\right)^2 \, dx$$
1. Entwickle den Term:
   $$\int \left(1 + 2\frac{1}{x} + \frac{1}{x^2}\right) \, dx$$
2. Der erste Term:
   $$\int 1 \, dx = x$$
3. Der zweite Term:
   $$2 \int \frac{1}{x} \, dx = 2\ln|x|$$
4. Der dritte Term:
   $$\int x^{-2} \, dx = -\frac{1}{x}$$
5. Zusammen ergibt das:
   $$x + 2\ln|x| - \frac{1}{x} + C$$
___
### Aufgabe k)
$$\int (t-2)^3 \, dt$$
1. Entwickle den Term:
   $$(t-2)^3 = t^3 - 6t^2 + 12t - 8$$
2. Integriere jeden Term:
   $$\frac{t^4}{4} - 2t^3 + 6t^2 - 8t + C$$
---
### Aufgabe l)
$$\int (t-1)^{\frac{1}{3}} \, dt$$

1. Setze \( u = t-1 \), sodass \( du = dt \).
2. Das Integral wird:
   $$\int u^{\frac{1}{3}} \, du$$
3. Das Integral von \( u^{\frac{1}{3}} \) ist:
   $$\frac{3}{4} u^{\frac{4}{3}} + C$$
4. Rücksubstitution ergibt:
   $$\frac{3}{4} (t-1)^{\frac{4}{3}} + C$$
---
### Aufgabe m)
$$\int \left(\frac{x+2}{2x}\right)^2 \, dx$$
1. Schreibe als:
   $$\int \frac{(x+2)^2}{4x^2} \, dx$$
2. Entwickle den Zähler:
   $$\int \frac{x^2 + 4x + 4}{4x^2} \, dx = \frac{1}{4} \int \left(1 + \frac{4}{x} + \frac{4}{x^2}\right) \, dx$$
3. Integriere jeden Term:
   $$\frac{1}{4} \left(x + 4\ln|x| - \frac{4}{x}\right) + C$$
---
### Aufgabe n)
$$\int \left(\frac{1}{u} - 1\right)^2 \, du$$
1. Entwickle den Term:
   $$\int \left(\frac{1}{u^2} - \frac{2}{u} + 1\right) \, du$$
2. Integriere jeden Term:
   $$-\frac{1}{u} - 2\ln|u| + u + C$$
---
### Aufgabe o)
$$\int (1 + \sqrt{x})^2 \, dx$$
1. Entwickle den Term:
   $$\int (1 + 2\sqrt{x} + x) \, dx$$
2. Integriere jeden Term:
   $$x + \frac{2}{3}x^{\frac{3}{2}} + \frac{x^2}{2} + C$$
---
### Aufgabe p)
$$\int \frac{x-1}{\sqrt{x}} \, dx$$
1. Zerlege in:
   $$\int \frac{x}{\sqrt{x}} \, dx - \int \frac{1}{\sqrt{x}} \, dx$$
2. Der erste Term:
   $$\int x^{\frac{1}{2}} \, dx = \frac{2}{3}x^{\frac{3}{2}}$$
3. Der zweite Term:
   $$\int x^{-\frac{1}{2}} \, dx = 2\sqrt{x}$$
4. Zusammen ergibt das:
   $$\frac{2}{3}x^{\frac{3}{2}} - 2\sqrt{x} + C$$
![[Pasted image 20250505113328.png]]
### Aufgabe a
Gegeben: $$f(x) = 2x - 1$$
1. Stammfunktion bestimmen:
   $$F(x) = \int f(x) \, dx = \int (2x - 1) \, dx = x^2 - x + C$$
2. Anfangsbedingung anwenden: $$F(1) = 2$$
   $$1^2 - 1 + C = 2$$
   $$C = 2$$
3. Stammfunktion mit bestimmter Konstante:
   $$F(x) = x^2 - x + 2$$
---
### Aufgabe b
Gegeben: $$f(x) = x^2 + x$$
1. Stammfunktion bestimmen:
   $$F(x) = \int f(x) \, dx = \int (x^2 + x) \, dx = \frac{x^3}{3} + \frac{x^2}{2} + C$$
2. Anfangsbedingung anwenden: $$F(1) = 2$$
   $$\frac{1^3}{3} + \frac{1^2}{2} + C = 2$$
   $$\frac{1}{3} + \frac{1}{2} + C = 2$$
   $$C = 2 - \frac{1}{3} - \frac{1}{2} = \frac{6}{3} - \frac{1}{3} - \frac{3}{6} = \frac{10}{6}$$
3. Stammfunktion mit bestimmter Konstante:
   $$F(x) = \frac{x^3}{3} + \frac{x^2}{2} + \frac{10}{6}$$
---
### Aufgabe c
Gegeben: $$f(x) = 2^x$$
1. Stammfunktion bestimmen:
   $$F(x) = \int f(x) \, dx = \int 2^x \, dx = \frac{2^x}{\ln(2)} + C$$
2. Anfangsbedingung anwenden: $$F(1) = 2$$
   $$\frac{2^1}{\ln(2)} + C = 2$$
   $$C = 2 - \frac{2}{\ln(2)}$$
3. Stammfunktion mit bestimmter Konstante:
   $$F(x) = \frac{2^x}{\ln(2)} + 2 - \frac{2}{\ln(2)}$$
---
### Aufgabe d
Gegeben: $$f(x) = \cos(x)$$
1. Stammfunktion bestimmen:
   $$F(x) = \int f(x) \, dx = \int \cos(x) \, dx = \sin(x) + C$$
2. Anfangsbedingung anwenden: $$F(1) = 2$$
   $$\sin(1) + C = 2$$
   $$C = 2 - \sin(1)$$
3. Stammfunktion mit bestimmter Konstante:
   $$F(x) = \sin(x) + 2 - \sin(1)$$
![[Pasted image 20250505113337.png]]
### Aufgabe a
Gegeben: Punkt $$P = (2|3)$$ und der Graph von $$f$$ ist eine lineare Funktion.
1. Steigung $$m$$ bestimmen:
   Der Graph zeigt, dass die Steigung $$m = 1$$ (jede Einheit in $$x$$ führt zu einer Einheit in $$y$$
2. Funktion aufstellen:
   $$f(x) = mx + b = 1x + b = x + b$$
3. Punkt einsetzen, um $$b$$ zu bestimmen:
   $$f(2) = 3$$
   $$2 + b = 3$$
   $$b = 1$$
4. Die Funktion lautet:
   $$f(x) = x + 1$$
5. Stammfunktion bestimmen:
   $$F(x) = \int f(x) \, dx = \int (x + 1) \, dx = \frac{x^2}{2} + x + C$$
6. Anfangsbedingung für die Stammfunktion anwenden: $$F(2) = 3$$
   $$\frac{2^2}{2} + 2 + C = 3$$
   $$2 + 2 + C = 3$$
   $$C = -1$$
7. Die Stammfunktion lautet:
   $$F(x) = \frac{x^2}{2} + x - 1$$
---
### Aufgabe b
Gegeben: Punkt $$P = (1|3)$$ und der Graph von $$f$$ ist eine negative lineare Funktion.
1. Steigung $$m$$ bestimmen:
   Der Graph zeigt, dass die Steigung $$m = -2$$ (jede Einheit in $$x$$ führt zu einer Abnahme von 2 Einheiten in $$y$$
2. Funktion aufstellen:
   $$f(x) = mx + b = -2x + b$$
3. Punkt einsetzen, um $$b$$ zu bestimmen:
   $$f(1) = 3$$
   $$-2(1) + b = 3$$
   $$b = 5$$
4. Die Funktion lautet:
   $$f(x) = -2x + 5$$
5. Stammfunktion bestimmen:
   $$F(x) = \int f(x) \, dx = \int (-2x + 5) \, dx = -x^2 + 5x + C$$
6. Anfangsbedingung für die Stammfunktion anwenden: $$F(1) = 3$$$$-(1^2) + 5(1) + C = 3$$$$-1 + 5 + C = 3$$$$C = -1$$
7. Die Stammfunktion lautet:$$F(x) = -x^2 + 5x - 1$$
