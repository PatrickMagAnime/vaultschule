[[3.Itsi]]
____

| CIA=<br>Confidentiality<br>Integrity<br>Availability | - C I A<br>- Symmetrische & Asymmetrische Verschlüsselung<br>- Hashfunktionen |
| ---------------------------------------------------- | ----------------------------------------------------------------------------- |


Kryptographie ist die Lehre des Verschlüsselns und Entschlüsselns.

## 1. Sicherheitsziele

- **C I A**:
  - **Confidentiality (Vertraulichkeit)**: Schutz der Daten vor unbefugtem Zugriff.
  - **Integrity (Integrität)**: Sicherstellung, dass die Daten nicht unbemerkt verändert werden.
  - **Availability (Verfügbarkeit)**: Gewährleistung, dass die Daten für autorisierte Benutzer verfügbar sind.

- **Verschlüsselungstypen**:
  - **Symmetrische Verschlüsselung**
  - **Asymmetrische Verschlüsselung**
  - **Hashfunktionen**

## 2. Symmetrische Verschlüsselung

- **Definition**: Es gibt einen Schlüssel. Beide Seiten nutzen diesen.
- **Problem**: Beide müssen auf den selben Schlüssel kommen. Wenn einer von beiden den Schlüssel verliert oder wenn er öffentlich wird, ist die Sicherheit gefährdet.

- **Beispiele**:
  - AES, DES, und 3DES, Blowfish

- **Vorteile**:
  - Schnell und performant
  - Quanten-sicher

- **Nachteile**:
  - Schlüsselmanagement

### Details zu AES (Advanced Encryption Standard)

- **Blockweise Verschlüsselung**: Bei einer Datei von 1MB wird diese in 16 Byte oder 128 Bit Blöcke aufgeteilt. Jeder Block wird verschlüsselt und dann zusammengefügt.
- **Schlüssellänge**: Man kann sich die Schlüssellänge aussuchen (128 Bit, 256 Bit oder 512 Bit). Je nach Schlüssellänge läuft der Roundkey mehrmals durch.
- **Roundkeys**: Der Schlüssel wird in Roundkeys unterteilt. Bei 128 Bit läuft der Schlüssel 10 Mal durch und verschlüsselt 10 Mal, bei 256 Bit 14 Runden.
- **Kombination der Blöcke**: Die Blöcke werden so lange verschlüsselt, bis jeder Block verschlüsselt wurde. Dann werden sie kombiniert.

## 3. Asymmetrische Verschlüsselung

- **Definition**: Es gibt einen privaten und einen öffentlichen Schlüssel. Der öffentliche Schlüssel kann von jedem genutzt werden.
- **Funktionsweise**: Wenn Person A etwas an Person B schicken will, hat A drei Schlüssel: seine eigenen zwei und den öffentlichen Schlüssel des Empfängers. Der Empfänger entschlüsselt die Nachricht dann mit seinem privaten Schlüssel.

- **Beispiel**:
  - RSA (Rivest, Shamir, Adleman)

- **Vorteile**:
  - Jeder hat einen eigenen Schlüssel.
  - Ermöglicht die Authentifizierung.

- **Nachteile**:
  - Langsame Berechnung.
  - Kann durch Quantencomputer zurückgerechnet werden.
