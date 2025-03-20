[[3.Itsi]]
___
### Simple Brute-Force Attack

Ein **Simple Brute-Force Attack** (einfacher Brute-Force-Angriff) ist eine Methode, bei der jedes mögliche Passwort oder Schlüssel durchgeprobt wird, bis das richtige gefunden wird. Dieser Ansatz ist sehr umfangreich und zeitaufwendig, insbesondere wenn das Passwort lang oder komplex ist. Der Algorithmus durchläuft alle möglichen Kombinationen von Zeichen, beginnend mit den kürzesten und arbeitet sich dann zu längeren Kombinationen vor.

**Beispiel:**
- Angenommen, das Passwort besteht aus Kleinbuchstaben und ist 3 Zeichen lang.
- Der Angriff würde alle Kombinationen von `aaa` bis `zzz` durchprobieren.

### Dictionary Brute-Force Attack

Ein **Dictionary Brute-Force Attack** (Wörterbuch-Brute-Force-Angriff) verwendet eine Liste von vorgefertigten Wörtern oder Passwörtern, die häufig verwendet werden (wie aus einem Wörterbuch oder einer Liste von häufigen Passwörtern). Dieser Ansatz ist effizienter als ein einfacher Brute-Force-Angriff, da er nicht jede mögliche Kombination durchprobiert, sondern auf die Wahrscheinlichkeit setzt, dass das Passwort ein bekanntes Wort oder eine häufige Kombination ist.

**Beispiel:**
- Eine Wörterbuchdatei könnte Wörter wie `password`, `123456`, `qwerty`, `letmein` enthalten.
- Der Angriff würde diese Wörter nacheinander ausprobieren, um das Passwort zu knacken.

### Vergleich

- **Einfacher Brute-Force-Angriff:**
  - **Vorteile:** Kann theoretisch jedes Passwort knacken.
  - **Nachteile:** Sehr zeitaufwendig und ressourcenintensiv, besonders bei komplexen Passwörtern.

- **Wörterbuch-Brute-Force-Angriff:**
  - **Vorteile:** Schneller und effizienter, da er auf häufig verwendete Passwörter setzt.
  - **Nachteile:** Kann nicht jedes Passwort knacken, insbesondere wenn das Passwort nicht in der Wörterbuchdatei enthalten ist.

### Schutzmaßnahmen

Um sich gegen beide Arten von Angriffen zu schützen, empfiehlt es sich:

- **Starke Passwörter zu verwenden:** Längere Passwörter mit einer Mischung aus Groß- und Kleinbuchstaben, Zahlen und Sonderzeichen.
- **Passwort-Manager:** Verwenden, um einzigartige und sichere Passwörter für jedes Konto zu generieren und zu speichern.
- **Zweifaktor-Authentifizierung (2FA):** Aktivieren, um zusätzliche Sicherheit zu gewährleisten.