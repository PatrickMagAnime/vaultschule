[[3.Mathe]]
___
## Kettenregel bei Integralen

Die Kettenregel für Integrale wird verwendet, um Integrale einer Funktion zu berechnen, die eine andere Funktion als Argument hat. Dies ist besonders nützlich, wenn die innere Funktion und ihre Ableitung bekannt sind.

### Beispiel 1: 

Gegeben sei das Integral:
$\int f(g(x)) \cdot g'(x) \, dx$

**Schritt 1:** Setze $u = g(x)$.  
**Schritt 2:** Bestimme die Ableitung $du = g'(x) \, dx$. 

Das Integral wird somit umgeschrieben zu:
$\int f(u) \, du$

**Schritt 3:** Bestimme das Integral von $f(u)$:
$\int f(u) \, du = F(u) + C$

**Schritt 4:** Rücksubstitution $u = g(x)$:
$F(g(x)) + C$

### Beispiel 2:

Gegeben sei das Integral:
$\int \sin(3x) \cdot 3 \, dx$

**Schritt 1:** Setze $u = 3x$.  
**Schritt 2:** Bestimme die Ableitung $du = 3 \, dx$. 

Das Integral wird somit umgeschrieben zu:
$\int \sin(u) \, du$

**Schritt 3:** Bestimme das Integral von $\sin(u)$:
$\int \sin(u) \, du = -\cos(u) + C$

**Schritt 4:** Rücksubstitution $u = 3x$:
$-\cos(3x) + C$

### Beispiel 3:

Gegeben sei das Integral:
$\int e^{\sin(x)} \cos(x) \, dx$

**Schritt 1:** Setze $u = \sin(x)$.  
**Schritt 2:** Bestimme die Ableitung $du = \cos(x) \, dx$. 

Das Integral wird somit umgeschrieben zu:
$\int e^u \, du$

**Schritt 3:** Bestimme das Integral von $e^u$:
$\int e^u \, du = e^u + C$

**Schritt 4:** Rücksubstitution $u = \sin(x)$:
$e^{\sin(x)} + C$

## Substitutionsverfahren

Das Substitutionsverfahren ist eine Technik zur Vereinfachung von Integralen durch die Einführung einer neuen Variable.

### Beispiel 1:

Gegeben sei das Integral:
$\int x \cos(x^2) \, dx$

**Schritt 1:** Setze $u = x^2$.  
**Schritt 2:** Bestimme die Ableitung $du = 2x \, dx$ oder $\frac{1}{2} du = x \, dx$. 

Das Integral wird somit umgeschrieben zu:
$\int \cos(u) \cdot \frac{1}{2} \, du$

**Schritt 3:** Bestimme das Integral von $\cos(u)$:
$\frac{1}{2} \int \cos(u) \, du = \frac{1}{2} \sin(u) + C$

**Schritt 4:** Rücksubstitution $u = x^2$:
$\frac{1}{2} \sin(x^2) + C$

### Beispiel 2:

Gegeben sei das Integral:
$\int \frac{1}{x \ln(x)} \, dx$

**Schritt 1:** Setze $u = \ln(x)$.  
**Schritt 2:** Bestimme die Ableitung $du = \frac{1}{x} \, dx$. 

Das Integral wird somit umgeschrieben zu:
$\int \frac{1}{u} \, du$

**Schritt 3:** Bestimme das Integral von $\frac{1}{u}$:
$\int \frac{1}{u} \, du = \ln|u| + C$

**Schritt 4:** Rücksubstitution $u = \ln(x)$:
$\ln|\ln(x)| + C$

### Zusammenfassung

Die Kettenregel und das Substitutionsverfahren sind nützliche Werkzeuge zur Berechnung von Integralen, insbesondere wenn Funktionen miteinander verschachtelt sind. Durch die Einführung neuer Variablen und die Anwendung der Kettenregel können komplexe Integrale vereinfacht und gelöst werden.