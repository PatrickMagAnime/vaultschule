[[3.Mathe]]
___
![[Pasted image 20250526113306.png]]

**Aufgabe 7.32 – Volumen durch Rotation:**

Das Volumen $V$ eines Körpers, der durch Rotation des Funktionsgraphen $y=f(x)$ im Intervall $[a, b]$ um die x-Achse entsteht, berechnet sich mit:
$$
V = \pi \int_{a}^{b} [f(x)]^2 \, dx
$$
---
### a) 
$y = 1 - x^2,\;\; -1 \leq x \leq 1$

1. Funktion quadrieren:  
   $[f(x)]^2 = (1 - x^2)^2 = 1 - 2x^2 + x^4$

2. Integral aufstellen:  
   $V = \pi \int_{-1}^{1} (1 - 2x^2 + x^4) \, dx$

3. Stammfunktion:  
   $\int (1 - 2x^2 + x^4) dx = x - \frac{2}{3}x^3 + \frac{1}{5}x^5$

4. Grenzen einsetzen:  
   $V = \pi \left[ x - \frac{2}{3}x^3 + \frac{1}{5}x^5 \right]_{-1}^{1}$  
   $= \pi \left( [1 - \frac{2}{3} \cdot 1 + \frac{1}{5} \cdot 1] - [-1 + \frac{2}{3} \cdot 1 - \frac{1}{5} \cdot 1] \right)$  
   $= \pi \left( (1 - \frac{2}{3} + \frac{1}{5}) - (-1 + \frac{2}{3} - \frac{1}{5}) \right)$  
   $= \pi \left( (1 - \frac{2}{3} + \frac{1}{5}) + (1 - \frac{2}{3} + \frac{1}{5}) \right)$  
   $= 2\pi (1 - \frac{2}{3} + \frac{1}{5})$  
   $= 2\pi \left( \frac{15}{15} - \frac{10}{15} + \frac{3}{15} \right)$  
   $= 2\pi \cdot \frac{8}{15}$  
   $= \frac{16\pi}{15}$
---
### b) 
$y = \frac{1}{x},\;\; 1 \leq x \leq 2$

1. Funktion quadrieren:  
   $[f(x)]^2 = \left( \frac{1}{x} \right)^2 = \frac{1}{x^2}$

2. Integral aufstellen:  
   $V = \pi \int_{1}^{2} \frac{1}{x^2} dx$

3. Stammfunktion:  
   $\int x^{-2} dx = -x^{-1} = -\frac{1}{x}$

4. Grenzen einsetzen:  
   $V = \pi \left[ -\frac{1}{x} \right]_{1}^{2}$  
   $= \pi \left( -\frac{1}{2} + \frac{1}{1} \right)$  
   $= \pi \left( 1 - \frac{1}{2} \right)$  
   $= \frac{\pi}{2}$
---
### c) 
$y = \frac{1}{3}\sqrt{x}\cdot(x-3),\;\; 0 \leq x \leq 3$

1. Funktion quadrieren:  
   $[f(x)]^2 = \left( \frac{1}{3}\sqrt{x}(x-3) \right)^2 = \frac{1}{9} x (x-3)^2$  
   $(x-3)^2 = x^2 - 6x + 9$  
   $\Rightarrow [f(x)]^2 = \frac{1}{9} x (x^2 - 6x + 9) = \frac{1}{9}(x^3 - 6x^2 + 9x)$

2. Integral aufstellen:  
   $V = \pi \int_{0}^{3} \frac{1}{9}(x^3 - 6x^2 + 9x) dx$  
   $= \frac{\pi}{9} \int_{0}^{3} (x^3 - 6x^2 + 9x) dx$

3. Stammfunktion:  
   $\int (x^3 - 6x^2 + 9x) dx = \frac{1}{4}x^4 - 2x^3 + \frac{9}{2}x^2$

4. Grenzen einsetzen:  
   $V = \frac{\pi}{9} \left[ \frac{1}{4}x^4 - 2x^3 + \frac{9}{2}x^2 \right]_{0}^{3}$  
   Für $x = 3$:
   $\frac{1}{4} \cdot 81 - 2 \cdot 27 + \frac{9}{2} \cdot 9 = 20.25 - 54 + 40.5 = 6.75$  
   Für $x = 0$: $0$
   
   $V = \frac{\pi}{9} \cdot 6.75 = \frac{\pi}{9} \cdot \frac{27}{4} = \frac{3\pi}{4}$
---
**Ergebnisse:**
- **a)** $V = \frac{16\pi}{15}$
- **b)** $V = \frac{\pi}{2}$
- **c)** $V = \frac{3\pi}{4}$

![[Pasted image 20250526113957.png]]

**Aufgabe 7.34 – Wasserglas (Rotation, Volumen, Eichstrich) mit Rechenweg:**

Das Rotationsvolumen berechnet sich mit:
$$
V = \pi \int_{a}^{b} [f(x)]^2\, dx
$$

Gegeben:  
$f(x) = \frac{1}{40}x^2 - \frac{1}{20}x + 3,\;\; 0 \leq x \leq 12$
---
### a) Fassungsvermögen (Volumen) berechnen

1. Funktion quadrieren:  
$[f(x)]^2 = \left(\frac{1}{40}x^2 - \frac{1}{20}x + 3\right)^2$

2. Integral aufstellen:  
$V = \pi \int_0^{12} \left(\frac{1}{40}x^2 - \frac{1}{20}x + 3\right)^2 dx$

3. Binom ausmultiplizieren:  
$= \left(\frac{1}{40}x^2\right)^2 - 2\cdot\frac{1}{40}x^2\cdot\frac{1}{20}x + 2\cdot\frac{1}{40}x^2\cdot3 + \left(\frac{1}{20}x\right)^2 - 2\cdot\frac{1}{20}x\cdot3 + 3^2$  
$= \frac{1}{1600}x^4 - \frac{1}{400}x^3 + \frac{3}{20}x^2 + \frac{1}{400}x^2 - \frac{3}{10}x + 9$  
$= \frac{1}{1600}x^4 - \frac{1}{400}x^3 + \frac{3}{20}x^2 + \frac{1}{400}x^2 - \frac{3}{10}x + 9$

(Achte darauf, die Terme sauber zu addieren und zu kombinieren!)

4. Integral berechnen (Stammfunktionen):  
$\int \frac{1}{1600}x^4 dx = \frac{1}{8000}x^5$  
$\int -\frac{1}{400}x^3 dx = -\frac{1}{1600}x^4$  
$\int \frac{3}{20}x^2 dx = \frac{1}{20}x^3$  
$\int \frac{1}{400}x^2 dx = \frac{1}{1200}x^3$  
$\int -\frac{3}{10}x dx = -\frac{3}{20}x^2$  
$\int 9 dx = 9x$

Zusammengefasst:  
$F(x) = \frac{1}{8000}x^5 - \frac{1}{1600}x^4 + \frac{1}{20}x^3 + \frac{1}{1200}x^3 - \frac{3}{20}x^2 + 9x$

$\frac{1}{20}+\frac{1}{1200} = \frac{61}{1200}$

Also:  
$F(x) = \frac{1}{8000}x^5 - \frac{1}{1600}x^4 + \frac{61}{1200}x^3 - \frac{3}{20}x^2 + 9x$

5. Grenzen einsetzen:

Für $x=12$  
$F(12) = \frac{1}{8000} \cdot 248832 - \frac{1}{1600} \cdot 20736 + \frac{61}{1200} \cdot 1728 - \frac{3}{20} \cdot 144 + 9 \cdot 12$

Werte:  
$12^5 = 248832$  
$12^4 = 20736$  
$12^3 = 1728$  
$12^2 = 144$

$= 31.104 - 12.96 + 87.888 - 21.6 + 108$  
$= (31.104 - 12.96) + (87.888 - 21.6) + 108$  
$= 18.144 + 66.288 + 108 = 192.432$

Für $x=0$: $F(0)=0$

Also:  
$V = \pi \cdot 192.432\ \text{cm}^3$

Das sind ca. $V \approx 605\ \text{cm}^3 = 0.605\ \text{Liter}$

---
### b) Lage des 0,5-Liter-Eichstrichs

Gesucht: $d$ so, dass $V(d) = 0.5\ \text{Liter} = 500\ \text{cm}^3$

Setze:  
$V(d) = \pi \left[\frac{1}{8000}d^5 - \frac{1}{1600}d^4 + \frac{61}{1200}d^3 - \frac{3}{20}d^2 + 9d\right] = 500$

Löse nach $d$ (am besten numerisch, z.B. mit Technologieeinsatz wie CAS oder Tabellenkalkulation).

---
**Ergebnisse:**
- **a)** $V \approx 605\ \text{cm}^3 \approx 0{,}6\ \text{Liter}$
- **b)** $d$ so, dass $V(d) = 500\ \text{cm}^3$ → Numerische Lösung.

![[Pasted image 20250526113326.png]]

**Aufgabe 7.35 – Volumen durch Rotation um die y-Achse (a und c) mit Rechenweg:**

Das Volumen $V$ eines Körpers, der durch Rotation um die y-Achse entsteht, berechnet sich mit:
$$
V = \pi \int_{a}^{b} [x(y)]^2\, dy
$$
---
### a) 
$y = \frac{1}{x},\;\; 1 \leq y \leq 2$

1. Umstellen nach $x(y)$:  
   $y = \frac{1}{x} \implies x = \frac{1}{y}$

2. Quadratisieren:  
   $[x(y)]^2 = \left(\frac{1}{y}\right)^2 = \frac{1}{y^2}$

3. Integral aufstellen:  
   $V = \pi \int_{1}^{2} \frac{1}{y^2} dy$

4. Stammfunktion:  
   $\int y^{-2} dy = -y^{-1} = -\frac{1}{y}$

5. Grenzen einsetzen:  
   $V = \pi \left[-\frac{1}{y}\right]_{1}^{2}$  
   $= \pi \left(-\frac{1}{2} + 1\right)$  
   $= \pi \cdot \frac{1}{2}$  
   $= \frac{\pi}{2}$
---
### c) 
$y = x^2,\;\; 0 \leq y \leq 2$

1. Umstellen nach $x(y)$:  
   $y = x^2 \implies x = \sqrt{y}$

2. Quadratisieren:  
   $[x(y)]^2 = (\sqrt{y})^2 = y$

3. Integral aufstellen:  
   $V = \pi \int_{0}^{2} y \, dy$

4. Stammfunktion:  
   $\int y \, dy = \frac{1}{2} y^2$

5. Grenzen einsetzen:  
   $V = \pi \left[\frac{1}{2} y^2\right]_{0}^{2}$  
   $= \pi \cdot \left(\frac{1}{2} \cdot 4 - 0\right)$  
   $= \pi \cdot 2$  
   $= 2\pi$

---

**Ergebnisse:**
- **a)** $V = \frac{\pi}{2}$
- **c)** $V = 2\pi$

![[Pasted image 20250526114326.png]]

**Aufgabe 7.39 – Fass: Volumen durch Rotation einer Polynomfunktion (mit Rechenweg):**

Wir bestimmen das Volumen des Fasses durch Rotation eines Polynoms $y = f(x)$ um die x-Achse.

---
### 1. Ansatz: Polynom 2. Grades für den Rand

Wir haben die Punkte (aus Abb. 7.21, Mittelachse liegt bei $y=0$, $x$ reicht von $-60$ bis $+60$):

- $(-60,\, 0)$  (linker Rand)
- $(0,\, 72)$   (mittig, maximaler Radius)
- $(60,\, 0)$   (rechter Rand)

Gesucht: $f(x) = a x^2 + b x + c$

**Gleichungssystem:**
1. $f(-60) = 0 \implies a \cdot 3600 - 60b + c = 0$
2. $f(0) = 72 \implies c = 72$
3. $f(60) = 0 \implies a \cdot 3600 + 60b + c = 0$

Setze $c = 72$ ein:

1. $3600a - 60b + 72 = 0$
2. $3600a + 60b + 72 = 0$

Ziehe die Gleichungen voneinander ab:
$$(3600a + 60b + 72) - (3600a - 60b + 72) = 0$$
$$120b = 0 \implies b = 0$$

Setze $b = 0$ in die erste Gleichung:
$$3600a + 72 = 0 \implies a = -\frac{72}{3600} = -0.02$$

**Das Polynom lautet also:**
$f(x) = -0.02x^2 + 72$
---
### 2. Volumenintegral aufstellen

Das Volumen durch Rotation um die x-Achse:
$$
V = \pi \int_{-60}^{60} [f(x)]^2\, dx
$$

Setze $f(x)$ ein:
$$
V = \pi \int_{-60}^{60} \left(-0.02x^2 + 72\right)^2 dx
$$

Multipliziere aus:
$$
\left(-0.02x^2 + 72\right)^2 = 0.0004x^4 - 2.88x^2 + 5184
$$
---
### 3. Integral berechnen

Stammfunktionen:
- $\int 0.0004x^4 dx = 0.00008x^5$
- $\int -2.88x^2 dx = -0.96x^3$
- $\int 5184 dx = 5184x$

Also:
$F(x) = 0.00008x^5 - 0.96x^3 + 5184x$

Berechne $F(60)$ und $F(-60)$:
- $60^5 = 77\,760\,000$
- $60^3 = 216\,000$
- $60^1 = 60$

$F(60) = 0.00008 \cdot 77\,760\,000 - 0.96 \cdot 216\,000 + 5184 \cdot 60$
$= 6220.8 - 207360 + 311040 = 109900.8$

$F(-60) = 0.00008 \cdot (-77\,760\,000) - 0.96 \cdot (-216\,000) + 5184 \cdot (-60)$
$= -6220.8 + 207360 - 311040 = -109900.8$

Jetzt das Volumen:
$V = \pi \left[F(60) - F(-60)\right] = \pi \left(109900.8 - (-109900.8)\right) = \pi \cdot 219801.6$
---
### 4. Ergebnis

$V = 219801.6* \pi \approx 690\,314.5{cm}^3 \approx 690L$

---
**Antwort:**
Das Fass fasst etwa $690\,\text{Liter}$.