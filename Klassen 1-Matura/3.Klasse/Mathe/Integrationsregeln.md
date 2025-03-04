[[3.Mathe]]
___
- 6.28 b,e,f,h,j
- 6.29 e,g,h
- 6.30 a,b,e,g,h
- 6.31 a,c

![[mathebuch 6.28 - 6.29 - 6.30 - 6.31.png]]
[[3.Mathe]]
___
# Integrale berechnen  
## Wichtige Regeln  
### Faktorregel  
Wenn eine Konstante mit dem Integranden multipliziert wird, kann sie vor das Integral gezogen werden.  
**Formel:**  
$$\int c \cdot f(x) \,dx = c \int f(x) \,dx$$  

**Beispiel:**  
$$\int 5x \,dx = 5 \int x \,dx = 5 \cdot \frac{x^2}{2} + C = \frac{5x^2}{2} + C$$  

  
### Summenregel  
**Formel:**  
$$\int (f(x) \pm g(x)) \,dx = \int f(x) \,dx \pm \int g(x) \,dx$$  

**Beispiel:**  
$$\int (x^2 + 3x) \,dx = \int x^2 \,dx + \int 3x \,dx = \frac{x^3}{3} + \frac{3x^2}{2} + C$$
# Aufgabe 6.28  
## b)  
**Faktorregel:**  
$$\int 5x^0 \,dx = 5 \int x^0 \,dx = 5x + C$$  



## e)  
**Faktorregel:**  
$$\int \frac{x}{3} \,dx = \frac{1}{3} \int x \,dx = \frac{x^2}{6} + C$$  



## f)  
**Faktorregel:**  
$$\int \frac{-1}{3u} \,du = -\frac{1}{3} \int \frac{1}{u} \,du = -\frac{1}{3} \ln|u| + C$$  



## h)  
**Faktorregel:**  
$$\int \frac{3\cos x}{2\pi} \,dx = \frac{3}{2\pi} \int \cos x \,dx = \frac{3}{2\pi} \sin x + C$$  



## j)  
**Vereinfachung durch Umformung:**  
$$\int \frac{2x}{\sqrt[3]{x^3}} \,dx = \int \frac{2x}{x} \,dx = \int 2 \,dx = 2x + C$$
# Aufgabe 6.29  
## e)  
**Bruch kürzen:**  
$$\int \frac{x^3}{x^2} \,dx = \int x \,dx = \frac{x^2}{2} + C$$  



## g)  
**Summenregel:**  
$$\int (t + 2e^t) \,dt = \int t \,dt + \int 2e^t \,dt = \frac{t^2}{2} + 2e^t + C$$  



## h)  
**Summenregel + Faktorregel:**  
$$\int \frac{u^3 - 5}{u^3} \,du = \int \left(1 - \frac{5}{u^3} \right) du = \int 1 \,du - 5 \int u^{-3} \,du$$  
$$= u - 5 \cdot \frac{u^{-2}}{-2} + C = u + \frac{5}{2u^2} + C$$ 
# Aufgabe 6.30  
## a)  
**Faktorregel:**  
$$\int \sqrt{2x} \,dx = \sqrt{2} \int \sqrt{x} \,dx = \sqrt{2} \int x^{1/2} \,dx$$  
$$= \sqrt{2} \cdot \frac{x^{3/2}}{3/2} + C = \frac{2\sqrt{2} x^{3/2}}{3} + C$$  



## b)  
**Summenregel:**  
$$\int \frac{x^2 + 1}{x^2} \,dx = \int \left(1 + \frac{1}{x^2} \right) dx = \int 1 \,dx + \int x^{-2} \,dx$$  
$$= x - \frac{1}{x} + C$$  



## e)  
**Faktorregel:**  
$$\int e^{x+1} \,dx = \int e^x \cdot e^1 \,dx = e \int e^x \,dx = e e^x + C$$  



## g)  
**Binomische Formel & Summenregel:**  
$$\int (t - 2)^3 \,dt = \int (t^3 - 6t^2 + 12t - 8) \,dt$$  
$$= \frac{t^4}{4} - 2t^3 + 6t^2 - 8t + C$$  



## h)  
**Binomische Formel & Summenregel:**  
$$\int (1 - \frac{1}{t})^2 \,dt = \int (1 - \frac{2}{t} + \frac{1}{t^2}) \,dt$$  
$$= \int 1 \,dt - 2 \int \frac{1}{t} \,dt + \int t^{-2} \,dt$$  
$$= t - 2\ln |t| - \frac{1}{t} + C$$
# Aufgabe 6.31  
## a)  
**Überprüfung der Anfangsbedingung:**  
Gegeben: $F(1) = 2$ und Punkt $P(1|2)$.  
$$F(x) = 2x - 1$$  
Einsetzen von $x = 1$:  
$$F(1) = 2(1) - 1 = 1 \neq 2$$  
Stimmt nicht.



## c)  
**Überprüfung der Anfangsbedingung:**  
Gegeben: $F(1) = 2$  
$$F(x) = x^2 + x$$  
Einsetzen von $x = 1$:  
$$F(1) = 1^2 + 1 = 2$$  
Stimmt, daher ist $F(x) = x^2 + x$ die richtige Lösung.
