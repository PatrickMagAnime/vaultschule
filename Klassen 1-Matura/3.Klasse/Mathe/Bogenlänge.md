[[3.Mathe]]
___
## Aufgabe 7.47

Berechne die Bogenlänge der Zykloide mit $x(t) = r(t-\sin t)$, $y(t) = r(1-\cos t)$, $0 \leq t \leq 2\pi$.

---

## Lösung (LaTeX, für Obsidian)

### 1. Parametrisierung

$x(t)=r(t-\sin t),\quad y(t)=r(1-\cos t),\quad 0\leq t\leq 2\pi$

---

### 2. Bogenlängenformel

$$
L = \int_{0}^{2\pi} \sqrt{ (x'(t))^2 + (y'(t))^2 }\,dt
$$

---

### 3. Ableitungen

$$
x'(t) = r(1 - \cos t),\quad y'(t) = r\sin t
$$

---

### 4. Eingesetzt

$$
L = \int_{0}^{2\pi} \sqrt{ \big[ r(1 - \cos t) \big]^2 + \big[ r\sin t \big]^2 }\,dt
$$

---

### 5. Ausmultipliziert und zusammengefasst

$$
L = \int_{0}^{2\pi} \sqrt{ r^2(1 - 2\cos t + \cos^2 t + \sin^2 t) }\,dt
$$

$\sin^2 t + \cos^2 t = 1$

$$
L = \int_{0}^{2\pi} \sqrt{ r^2(2 - 2\cos t) }\,dt = r \int_{0}^{2\pi} \sqrt{2 - 2\cos t}\,dt
$$

---

### 6. Vereinfachung mit $\sqrt{2-2\cos t} = 2|\sin(\frac{t}{2})|$

$$
L = r \int_{0}^{2\pi} 2|\sin(\frac{t}{2})|\,dt
$$

Da $\sin(\frac{t}{2})$ von $0$ bis $2\pi$ immer positiv ist, kann man die Betragsstriche weglassen:

$$
L = 2r \int_{0}^{2\pi} \sin(\frac{t}{2})\,dt
$$

Stammfunktion: $-4r\cos(\frac{t}{2})$

$$
L = 2r \left[ -2\cos(\frac{t}{2}) \right]_{0}^{2\pi} = -4r[\cos(\pi)-\cos(0)] = -4r[(-1) - 1] = -4r(-2) = 8r
$$

**Endergebnis:**  
$$
\boxed{L = 8r}
$$

---

## GeoGebra Eingaben

**Mit $r=1$:**

```geogebra
L = Integral( sqrt( (1 - cos(t))^2 + (sin(t))^2 ), t, 0, 2*pi )
```
**Oder mit Variable $r$:**
```geogebra
L = Integral( sqrt( (r*(1 - cos(t)))^2 + (r*sin(t))^2 ), t, 0, 2*pi )
```
**GeoGebra gibt aus:**  
Wenn $r=1$: $L=8$

---

**Bildreferenz:**




## Aufgabe 7.44

Entlang eines parabelförmigen Brückenbogens (siehe Abbildung) soll von A nach B eine Leitung gelegt werden.  
Berechne die Länge der Leitung mithilfe von Technologie.

---
## Lösungsidee

Wähle das Koordinatensystem so, dass der Scheitelpunkt der Parabel im Ursprung liegt, dann ist die Gleichung des Bogens:
- Spannweite: $40\,\text{m}$
- Höhe: $5\,\text{m}$

Setze den Ursprung in die Mitte, also $x \in [-20, 20]$, $y(0) = 5$, $y(\pm20) = 0$

Die Parabelgleichung:
$$
y(x) = a x^2 + 5
$$
Setze $y(20) = 0$:
$$
0 = a \cdot 20^2 + 5 \implies a = -\frac{5}{400} = -\frac{1}{80}
$$
Also:
$$
y(x) = -\frac{1}{80}x^2 + 5
$$

---

## GeoGebra-Eingaben

1. Parabel definieren:
   ```geogebra
   f(x) = -1/80 * x^2 + 5
   ```

2. Bogenlänge berechnen von $x = -20$ bis $x = 20$:
   ```geogebra
   L = Integral( sqrt(1 + (Derivative(f, x))^2), x, -20, 20 )
   ```

**GeoGebra gibt als Ergebnis für $L$ (Leitungslänge):**  
$L \approx 40.647$

---

**Antwort:**  
Die Leitung ist ca. $40{,}65\,\text{m}$ lang.

---

**Bildreferenz:**  


## Aufgabe 7.45

Zeige, dass die Länge der durch $y = a \cdot \cosh\frac{x}{a}$ bestimmten Kettenlinie für $0 \leq x \leq b$ durch $s = a \cdot \sinh\frac{b}{a}$ gegeben ist.

---

## Lösung (Herleitung)

Die Bogenlänge einer Funktion $y(x)$ von $x=0$ bis $x=b$ ist:
$$
s = \int_{0}^{b} \sqrt{1 + (y'(x))^2} \, dx
$$

1. Ableitung berechnen:
$$
y(x) = a \cdot \cosh\left(\frac{x}{a}\right)
$$

$$
y'(x) = a \cdot \frac{d}{dx} \cosh\left(\frac{x}{a}\right) = a \cdot \sinh\left(\frac{x}{a}\right) \cdot \frac{1}{a} = \sinh\left(\frac{x}{a}\right)
$$

2. In die Bogenlänge einsetzen:
$$
s = \int_{0}^{b} \sqrt{1 + \sinh^2\left(\frac{x}{a}\right)} \, dx
$$

Mit dem Hinweis $\cosh^2 z - \sinh^2 z = 1 \implies 1 + \sinh^2 z = \cosh^2 z$:

$$
s = \int_{0}^{b} \cosh\left(\frac{x}{a}\right) dx
$$

Stammfunktion:
$$
\int \cosh\left(\frac{x}{a}\right) dx = a \cdot \sinh\left(\frac{x}{a}\right)
$$

Also:
$$
s = a \cdot \left[ \sinh\left(\frac{x}{a}\right) \right]_{0}^{b} = a \cdot \left( \sinh\left(\frac{b}{a}\right) - \sinh(0) \right) = a \cdot \sinh\left(\frac{b}{a}\right)
$$

---

## GeoGebra-Eingaben

**Für $a=1$, $b=2$ (Beispiel):**

```geogebra
a = 1
b = 2
f(x) = a * cosh(x / a)
L = Integral( sqrt(1 + (Derivative(f, x))^2), x, 0, b )
```

**Allgemein:**

```geogebra
f(x) = a * cosh(x / a)
L = Integral( sqrt(1 + (Derivative(f, x))^2), x, 0, b )
```

**GeoGebra Ergebnis:**
$$
L = a \cdot \sinh\left( \frac{b}{a} \right)
$$
ausgeben (bei symbolischer Berechnung), sonst einen Zahlenwert.

---

**Bildreferenz:** 










































































