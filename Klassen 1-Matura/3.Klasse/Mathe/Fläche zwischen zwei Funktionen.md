[[3.Mathe]]
___
$$
\text{Berechne den Inhalt der Fläche, die von den beiden Graphen von } f \text{ und } g \text{ eingeschlossen wird.}
$$

### a)  
$$
f(x) = x^2, \quad g(x) = -x + 2
$$

1. **Schnittpunkte berechnen**  
   $$f(x) = g(x) \implies x^2 = -x + 2$$  
   $$x^2 + x - 2 = 0$$  
   $$x_{1,2} = \frac{-1 \pm \sqrt{1^2 - 4 \cdot 1 \cdot (-2)}}{2 \cdot 1} = \frac{-1 \pm \sqrt{9}}{2} = \{-2, 1\}$$  

2. **Integrationsgrenzen definieren**  
   Die Schnittpunkte sind \(x = -2\) und \(x = 1\).  

3. **Fläche berechnen**  
   $$A = \int_{-2}^{1} \left(g(x) - f(x)\right) \, dx$$  
   $$A = \int_{-2}^{1} \left((-x + 2) - (x^2)\right) \, dx$$  
   $$A = \int_{-2}^{1} (-x + 2 - x^2) \, dx$$  
   $$A = \left[-\frac{x^2}{2} + 2x - \frac{x^3}{3}\right]_{-2}^1$$  
   Einsetzen der Grenzen:  
   $$A = \left[-\frac{1^2}{2} + 2 \cdot 1 - \frac{1^3}{3}\right] - \left[-\frac{(-2)^2}{2} + 2 \cdot (-2) - \frac{(-2)^3}{3}\right]$$  
   $$A = \left[-\frac{1}{2} + 2 - \frac{1}{3}\right] - \left[-2 + (-4) - \left(-\frac{8}{3}\right)\right]$$  
   $$A = \left[\frac{6}{6} - \frac{3}{6} - \frac{2}{6}\right] - \left[-6 + \frac{8}{3}\right]$$  
   $$A = \text{(weiter zusammenfassen)}$$

---

### b)  
$$
f(x) = x^2 - 5x + 3, \quad g(x) = x - 2
$$

1. **Schnittpunkte berechnen**  
   $$f(x) = g(x) \implies x^2 - 5x + 3 = x - 2$$  
   $$x^2 - 6x + 5 = 0$$  
   $$x_{1,2} = \frac{-(-6) \pm \sqrt{(-6)^2 - 4 \cdot 1 \cdot 5}}{2 \cdot 1} = \frac{6 \pm \sqrt{16}}{2} = \{2, 4\}$$  

2. **Integrationsgrenzen definieren**  
   Die Schnittpunkte sind \(x = 2\) und \(x = 4\).  

3. **Fläche berechnen**  
   $$A = \int_{2}^{4} \left(g(x) - f(x)\right) \, dx$$  
   $$A = \int_{2}^{4} \left((x - 2) - (x^2 - 5x + 3)\right) \, dx$$  
   $$A = \int_{2}^{4} \left(-x^2 + 6x - 5\right) \, dx$$  
   $$A = \left[-\frac{x^3}{3} + 3x^2 - 5x\right]_{2}^4$$  
   Einsetzen der Grenzen:  
   $$A = \left[-\frac{4^3}{3} + 3 \cdot 4^2 - 5 \cdot 4\right] - \left[-\frac{2^3}{3} + 3 \cdot 2^2 - 5 \cdot 2\right]$$  
   $$A = \text{(weiter zusammenfassen)}$$  

---

### f)  
$$
f(x) = \frac{x^3}{8}, \quad g(x) = -\frac{x^2}{4} + x
$$

1. **Schnittpunkte berechnen**  
   $$f(x) = g(x) \implies \frac{x^3}{8} = -\frac{x^2}{4} + x$$  
   $$x^3 + 2x^2 - 8x = 0 \implies x(x^2 + 2x - 8) = 0$$  
   $$x = 0, \quad x_{1,2} = \frac{-2 \pm \sqrt{2^2 - 4 \cdot 1 \cdot (-8)}}{2 \cdot 1} = \{-4, 2\}$$  

2. **Integrationsgrenzen definieren**  
   Die Schnittpunkte sind \(x = -4\), \(x = 0\) und \(x = 2\).  

3. **Fläche berechnen**  
   $$A = \int_{-4}^{0} \left(g(x) - f(x)\right) \, dx + \int_{0}^{2} \left(f(x) - g(x)\right) \, dx$$  
   $$A = \int_{-4}^{0} \left(-\frac{x^2}{4} + x - \frac{x^3}{8}\right) \, dx + \int_{0}^{2} \left(\frac{x^3}{8} - \left(-\frac{x^2}{4} + x\right)\right) \, dx$$  
   $$A = \text{(Integrale berechnen)}$$  