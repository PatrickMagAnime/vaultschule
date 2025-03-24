Gegeben ist das bestimmte Integral:

$$
\int_{\frac{1}{2}}^a \frac{1}{\sqrt{x}} \,dx = \sqrt{2}
$$

### **Schritt 1: Bestimme die Stammfunktion**  
Die Funktion unter dem Integral lautet:  
$$f(x) = \frac{1}{\sqrt{x}}$$ 

Schreiben wir das als Potenzfunktion um:  
$$f(x) = x^{-\frac{1}{2}}$$

Die allgemeine Regel zur Bestimmung der Stammfunktion für Potenzfunktionen lautet:  
$$
\int x^n \,dx = \frac{x^{n+1}}{n+1}, \quad \text{für } n \neq -1.
$$

Für  $$n = -\frac{1}{2}$$ ergibt sich:  
$$
\int x^{-\frac{1}{2}} \,dx = \frac{x^{\frac{1}{2}}}{\frac{1}{2}} = 2\sqrt{x}.
$$

Damit ist die Stammfunktion:  
$$
F(x) = 2\sqrt{x}.
$$

---

### **Schritt 2: Bestimme das bestimmte Integral**  
Nun setzen wir die Integrationsgrenzen $$\frac{1}{2}$$ und  $$a$$ ein:  
$$
\int_{\frac{1}{2}}^a \frac{1}{\sqrt{x}} \,dx = \left[ 2\sqrt{x} \right]_{\frac{1}{2}}^a
$$

Das bedeutet:  
$$
2\sqrt{a} - 2\sqrt{\frac{1}{2}} = \sqrt{2}.
$$

---

### **Schritt 3: Vereinfachung der Gleichung**  
Berechnung von $$\sqrt{\frac{1}{2}}$$:  
$$
\sqrt{\frac{1}{2}} = \frac{\sqrt{2}}{2}.
$$

Einsetzen:  
$$
2\sqrt{a} - 2 \cdot \frac{\sqrt{2}}{2} = \sqrt{2}.
$$

Kürzen der 2 im zweiten Term:  
$$
2\sqrt{a} - \sqrt{2} = \sqrt{2}.
$$

Nun addieren wir $$\sqrt{2}$$ auf beiden Seiten:  
$$
2\sqrt{a} = 2\sqrt{2}.
$$

---

### **Schritt 4: Berechnung von \( a \)**  
Teilen durch 2:  
$$
\sqrt{a} = \sqrt{2}.
$$

Quadrieren beider Seiten:  
$$
a = (\sqrt{2})^2 = 2.
$$

---

### **Schritt 5: Antwort**  
Die gesuchte obere Integrationsgrenze ist:  
$$
\boxed{a = 2}
$$
