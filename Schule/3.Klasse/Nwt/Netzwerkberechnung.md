[[3.Nwt]]
____
# Netzwerkberechnung

## 10.97.3.18/28

- **Binär**: 00001010.01100001.00000011.0001|0010
- **Netzwerk-Adresse (NW-A)**: 10.97.3.16
- **Subnetzmaske (SM)**: 255.255.255.240
- **Broadcast-Adresse (BC-A)**: 10.79.3.31
- **Anzahl der Adressen (Anz)**: 31

## 178.16.50.200/23

- **Netzwerk-Adresse (NW-A)**: 178.16.50.0
- **Subnetzmaske (SM)**: 255.255.254.0
- **Broadcast-Adresse (BC-A)**: 178.16.51.255
- **Anzahl der Adressen (Anz)**: 510

## 199.67.18.10/12

- **Netzwerk-Adresse (NW-A)**: 199.67.0.0
- **Subnetzmaske (SM)**: 255.240.0.0
- **Broadcast-Adresse (BC-A)**: 199.79.255.255
- **Anzahl der Adressen (Anz)**: 1,048,574

---

# Erklärung des Inhalts

Diese Mitschrift behandelt die Berechnung von Netzwerkadressen basierend auf gegebenen IP-Adressen und Subnetzmasken. Für jede IP-Adresse werden die Netzwerkadresse (NW-A), die Subnetzmaske (SM), die Broadcast-Adresse (BC-A) und die Anzahl der möglichen Adressen (Anz) berechnet und angegeben.

- **Netzwerk-Adresse (NW-A)**: Die erste Adresse im Subnetz, die das Netzwerk selbst darstellt.
- **Subnetzmaske (SM)**: Eine Maske, die verwendet wird, um den Netzwerk- und den Hostteil einer IP-Adresse zu trennen.
- **Broadcast-Adresse (BC-A)**: Die letzte Adresse im Subnetz, die verwendet wird, um Daten an alle Hosts im Netzwerk zu senden.
- **Anzahl der Adressen (Anz)**: Die Gesamtzahl der verfügbaren Adressen im Subnetz, einschließlich der Netzwerk- und Broadcast-Adressen.

### Berechnung der Anzahl der Hostadressen

Die Anzahl der Hostadressen in einem Subnetz lässt sich mit der Formel berechnen:


\[ \text{Hostadressen} = 2^{(32 - \text{Anzahl der Netzwerkbits})} - 2 \]



Hier ist der Schritt-für-Schritt-Prozess:

1. **Ermittlung der Anzahl der Netzwerkbits:**
   - Die Anzahl der Netzwerkbits wird durch die Subnetzmaske bestimmt. Zum Beispiel, für die Subnetzmaske /28, gibt es 28 Netzwerkbits.
   - Die Anzahl der Hostbits ist dann \( 32 - \text{Anzahl der Netzwerkbits} \). Für /28 sind das \( 32 - 28 = 4 \) Hostbits.

2. **Berechnung der möglichen Hostadressen:**
   - Die Gesamtzahl der möglichen Adressen im Subnetz ist \( 2^{\text{Anzahl der Hostbits}} \). Für /28 sind das \( 2^4 = 16 \).

3. **Abzug der speziellen Adressen:**
   - Von den möglichen Adressen müssen zwei spezielle Adressen abgezogen werden: die Netzwerkadresse und die Broadcastadresse.
   - Daher ist die Anzahl der nutzbaren Hostadressen \( 2^{\text{Anzahl der Hostbits}} - 2 \). Für /28 ergibt das \( 16 - 2 = 14 \) nutzbare Hostadressen.

### Beispiel

Nehmen wir das Beispiel 10.97.3.18/28:

1. **Subnetzmaske /28**:
   - Anzahl der Netzwerkbits = 28
   - Anzahl der Hostbits = 32 - 28 = 4

2. **Berechnung der möglichen Hostadressen**:
   - Gesamtzahl der Adressen = \( 2^4 = 16 \)

3. **Abzug der speziellen Adressen**:
   - Nutzbare Hostadressen = \( 16 - 2 = 14 \)

Für ein weiteres Beispiel, nehmen wir 178.16.50.200/23:

1. **Subnetzmaske /23**:
   - Anzahl der Netzwerkbits = 23
   - Anzahl der Hostbits = 32 - 23 = 9

2. **Berechnung der möglichen Hostadressen**:
   - Gesamtzahl der Adressen = \( 2^9 = 512 \)

3. **Abzug der speziellen Adressen**:
   - Nutzbare Hostadressen = \( 512 - 2 = 510 \)

Durch diese Schritte kannst du die Anzahl der nutzbaren Hostadressen in jedem Subnetz berechnen.
