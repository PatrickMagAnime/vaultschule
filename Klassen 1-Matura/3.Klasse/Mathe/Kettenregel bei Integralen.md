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

## Aufgaben
- 6.38 a
- 6.37 b c d e
- 6.45 a c
![[mathebuch 6.38.png]]
![[mathebuch 6.37.png]]
![[mathebuch 6.45.png]]
# Lösungen zu den Integralen

## Aufgabe 6.38 a
Berechne das Integral:  
$$\int \frac{2}{2+x}dx$$  
Lösung:  
Setze $u = 2 + x$, dann ist $du = dx$.  
$$\int \frac{2}{u} du = 2 \int \frac{1}{u} du = 2 \ln |u| + C = 2 \ln |2+x| + C$$  

## Aufgabe 6.37 b
Berechne das Integral:  
$$\int (3+2x)^4dx$$  
Lösung:  
Substitution: $u = 3 + 2x \Rightarrow du = 2dx \Rightarrow dx = \frac{du}{2}$  
$$\int u^4 \cdot \frac{du}{2} = \frac{1}{2} \int u^4 du = \frac{1}{2} \cdot \frac{u^5}{5} = \frac{(3+2x)^5}{10} + C$$  
### Aufgabe d:
$$I = \int \frac{1}{\sqrt{1 - x}} \,dx$$  
Setze \( u = 1 - x \Rightarrow du = -dx \):  
$$I = \int \frac{-du}{\sqrt{u}} = - \int u^{-\frac{1}{2}} \, du$$  
Integriere:  
$$= - \frac{u^{\frac{1}{2}}}{\frac{1}{2}} + C = - 2\sqrt{u} + C$$  
Rücksubstitution \( u = 1 - x \):  
$$I = -2\sqrt{1 - x} + C$$  

### Aufgabe e:
$$I = \int (5z - 2)^2 \,dz$$  
Multipliziere aus:  
$$= \int (25z^2 - 20z + 4) \, dz$$  
Integriere termweise:  
$$= 25 \frac{z^3}{3} - 20 \frac{z^2}{2} + 4z + C$$  
Vereinfache:  
$$= \frac{25}{3} z^3 - 10z^2 + 4z + C$$  


## Aufgabe 6.45 a
Führe die Integration mit der vorgegebenen Substitution durch:  
$$\int \frac{x}{x^2+1}dx, \quad u = x^2+1$$  
Lösung:  
Ableitung von $u$: $du = 2x dx \Rightarrow \frac{du}{2} = x dx$  
$$\int \frac{x}{x^2+1}dx = \int \frac{1}{u} \cdot \frac{du}{2} = \frac{1}{2} \int \frac{1}{u} du = \frac{1}{2} \ln |u| + C = \frac{1}{2} \ln |x^2+1| + C$$  

## Aufgabe 6.45 c
Führe die Integration mit der vorgegebenen Substitution durch:  
$$\int \frac{\cos x}{\sin x}dx, \quad u = \sin x$$  
Lösung:
Ableitung von $u$: $du = \cos x dx$  
$$\int \frac{\cos x}{\sin x}dx = \int \frac{1}{u} du = \ln |u| + C = \ln |\sin x| + C$$  
![[mathebuch 6.42 & 6.43.png]]
