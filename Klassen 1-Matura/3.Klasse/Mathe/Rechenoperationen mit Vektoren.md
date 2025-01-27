[[Zweite Mathe Schularbeit Lernen]]
___
## Addition und Subtraktion

**Addition von Vektoren**  
$\vec{a} = \left(\begin{array}{c} 2 \\ 3 \end{array}\right), \vec{b} = \left(\begin{array}{c} -1 \\ 4 \end{array}\right)$  
$\vec{a} + \vec{b} = \left(\begin{array}{c} 2 + (-1) \\ 3 + 4 \end{array}\right) = \left(\begin{array}{c} 1 \\ 7 \end{array}\right)$  

**Subtraktion von Vektoren**  
$\vec{a} = \left(\begin{array}{c} 5 \\ 6 \end{array}\right), \vec{b} = \left(\begin{array}{c} 2 \\ 4 \end{array}\right)$  
$\vec{a} - \vec{b} = \left(\begin{array}{c} 5 - 2 \\ 6 - 4 \end{array}\right) = \left(\begin{array}{c} 3 \\ 2 \end{array}\right)$  
## Mit Skalar Multiplizieren

**Skalarmultiplikation**  
$\vec{a} = \left(\begin{array}{c} 3 \\ -2 \end{array}\right), k = 4$  
$k \cdot \vec{a} = 4 \cdot \left(\begin{array}{c} 3 \\ -2 \end{array}\right) = \left(\begin{array}{c} 4 \cdot 3 \\ 4 \cdot (-2) \end{array}\right) = \left(\begin{array}{c} 12 \\ -8 \end{array}\right)$  

**Negative Skalare**  
$\vec{b} = \left(\begin{array}{c} -1 \\ 5 \end{array}\right), k = -3$  
$k \cdot \vec{b} = -3 \cdot \left(\begin{array}{c} -1 \\ 5 \end{array}\right) = \left(\begin{array}{c} -3 \cdot (-1) \\ -3 \cdot 5 \end{array}\right) = \left(\begin{array}{c} 3 \\ -15 \end{array}\right)$  
## Das Skalar Produkt

**Berechnung des Skalarprodukts**  
$\vec{a} = \left(\begin{array}{c} 1 \ 2 \end{array}\right), \vec{b} = \left(\begin{array}{c} 3 \ 4 \end{array}\right)$  
$\vec{a} \cdot \vec{b} = (1 \cdot 3) + (2 \cdot 4) = 3 + 8 = 11$

**Alternative Formel mit Winkel**  
$\vec{a} \cdot \vec{b} = |\vec{a}| \cdot |\vec{b}| \cdot \cos(\varphi)$

**Beispiel**  
$|\vec{a}| = \sqrt{1^2 + 2^2} = \sqrt{1 + 4} = \sqrt{5}$  
$|\vec{b}| = \sqrt{3^2 + 4^2} = \sqrt{9 + 16} = \sqrt{25} = 5$  
$\cos(\varphi) = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}| \cdot |\vec{b}|} = \frac{11}{\sqrt{5} \cdot 5} = \frac{11}{5\sqrt{5}}$
$\varphi =\arccos( \frac{\vec{a} \cdot \vec{b}}{|\vec{a}| \cdot |\vec{b}|})$
## Einheitsvektor

**Berechnung des Einheitsvektors**  
$\vec{a} = \left(\begin{array}{c} 6 \\ 8 \end{array}\right)$  
Betrag von $\vec{a}$:  
$|\vec{a}| = \sqrt{6^2 + 8^2} = \sqrt{36 + 64} = \sqrt{100} = 10$  
Einheitsvektor:  
$\vec{a}_e = \frac{\vec{a}}{|\vec{a}|} = \frac{1}{10} \cdot \left(\begin{array}{c} 6 \\ 8 \end{array}\right) = \left(\begin{array}{c} 0.6 \\ 0.8 \end{array}\right)$  
## Normal Vektor

**Berechnung eines Normalvektors in 2D**  
$\vec{a} = \left(\begin{array}{c} 3 \\ 4 \end{array}\right)$  
Normalvektoren (orthogonal):  
Tausche die Koordinaten und ändere ein Vorzeichen.
$\vec{n}_1 = \left(\begin{array}{c} -4 \\ 3 \end{array}\right), \vec{n}_2 = \left(\begin{array}{c} 4 \\ -3 \end{array}\right)$  

**Berechnung eines Normalvektors in 3D**  
$\vec{a} = \left(\begin{array}{c} 1 \\ 2 \\ 3 \end{array}\right), \vec{b} = \left(\begin{array}{c} 4 \\ 5 \\ 6 \end{array}\right)$  
Verwende das Kreuzprodukt.
$\vec{n} = \vec{a} \times \vec{b} = \left(\begin{array}{c} (2 \cdot 6 - 3 \cdot 5) \\ (3 \cdot 4 - 1 \cdot 6) \\ (1 \cdot 5 - 2 \cdot 4) \end{array}\right) = \left(\begin{array}{c} -3 \\ 6 \\ -3 \end{array}\right)$  