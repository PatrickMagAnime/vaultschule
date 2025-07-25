[[3.Syt]]
___
## Themen
- Grundlagen
- Von-Neumann-Prinzip
- Schichtenmodell
- Prozesse
- Speicherverwaltung
- Dateiverwaltung
---
### Aufgabe 1: Zusammenfassung lesen
Lest im Skriptum „1.2.2 Die Von-Neumann-Prinzipien“ (Seite 8–10). Markiert die wichtigsten Sätze.

#### Markierte Begriffe von 1.2.2
##### 1. Abbildung

- Steuerwerk
- Rechenwerk
- Speicher
- Eingabewerk
- Ausgabewerk
- „Der Rechner besteht aus fünf Funktionseinheiten, dem Steuerwerk, dem Rechenwerk, dem Speicher, dem Eingabewerk und dem Ausgabewerk.“

##### 2. Abbildung

- unabhängig von den zu bearbeitenden Problemen
- Programm
- Speicher
- Programme, Daten, Zwischen- und Endergebnisse
- gleichgroße Zellen
- Adresse
- RAM = Random Access Memory
- Aufeinanderfolgende Befehle
- aufeinanderfolgenden Speicherzellen
- Steuerwerk
- Befehlsadresse
- Sprungbefehle

##### 3. Abbildung

- arithmetische Befehle
- logische Befehle
- Transportbefehle
- bedingte Sprünge
- binär codiert
- Schaltwerke
- Decodierung

### Aufgabe 2: Fragen beantworten
1. **Was sind die 3 Grundprinzipien der Von-Neumann-Architektur?**
   - Prinzip der gespeicherten Programme
   - Einheitlicher Speicher für Daten und Programme
   - Sequentielle Ausführung von Befehlen

2. **Warum war diese Architektur ein Meilenstein in der Computerentwicklung?**
   - Sie ermöglichte die Entwicklung universeller Computer, die flexibel programmiert werden konnten.

3. **Wie sieht der typische „Fetch-Decode-Execute“-Zyklus aus?**
   - **Fetch**: Der nächste Befehl wird aus dem Speicher geholt.
   - **Decode**: Der Befehl wird interpretiert.
   - **Execute**: Der Befehl wird ausgeführt.

### Aufgabe 3: Zeichnung erstellen
Erstelle eine beschriftete Skizze eines Von-Neumann-Rechners. Enthalten sein müssen:
- CPU
- Hauptspeicher
- Ein-/Ausgabe
- Steuerwerk & Rechenwerk
- Daten- und Befehlsbus

![[Neumann-pc-vorstellung.png]]

---
## Schichtenmodell eines Computersystems

### Aufgabe 4: Skriptum durcharbeiten
Kapitel 1.2.3 – Das Schichtenmodell (Seite 11–14) lesen.

### Aufgabe 5: Zuordnungsaufgabe
Ordne die folgenden Begriffe der richtigen Schicht zu:
- **Mikrocode** -> Physikalische Geräte
- **Compiler** -> Systemsoftware
- **Webbrowser** -> Anwendungssoftware
- **CPU** -> Physikalische Geräte
- **Linker** -> Systemsoftware
- **Dateimanager** -> Systemsoftware
- **ROM** -> Physikalische Geräte
- **Kommandozeile** -> Systemsoftware

### Aufgabe 6: Eigenständige Erklärung
- **Warum ist das Schichtenmodell hilfreich?**
  - Es strukturiert die Komplexität eines Computersystems und erleichtert die Fehlersuche und Wartung.

- **Welche Vorteile ergeben sich für Programmierer?**
  - Programmierer können sich auf eine Schicht konzentrieren, ohne die Details der darunterliegenden Schichten verstehen zu müssen.

---
## Aufgaben des Betriebssystems & Prozesse

### Aufgabe 7: Leseauftrag
Lies Kapitel 1.2.5 + 2.1 über Aufgaben und Prozesse in Betriebssystemen.

### Aufgabe 8: Tabelle ausfüllen

| Betriebssystemaufgabe | Beschreibung | Beispiel |
|-----------------------|--------------|----------|
| Prozessverwaltung     | Verwaltung der Ausführung von Prozessen | Multitasking |
| Speicherverwaltung    | Zuweisung und Freigabe von Speicher | RAM-Management |
| Dateiverwaltung       | Organisation und Zugriff auf Dateien | Dateisysteme |
| Gerätesteuerung       | Verwaltung von Ein-/Ausgabegeräten | Druckersteuerung |
| Benutzerverwaltung    | Verwaltung von Benutzerkonten und Berechtigungen | Login-System |

### Aufgabe 9: Kurze Textanalyse
**Was ist ein Deadlock und wie kann das Betriebssystem damit umgehen?**
Ein Deadlock ist eine Situation, in der zwei oder mehr Prozesse auf Ressourcen warten, die von den anderen gehalten werden, und keiner der Prozesse fortfahren kann. Das Betriebssystem kann Deadlocks durch Techniken wie Ressourcenallokationsgraphen, Deadlock-Vermeidung oder -Erkennung und -Behebung handhaben.

**Beispiel aus dem Alltag:**
Stellen Sie sich vor, zwei Autos stehen sich in einer engen Straße gegenüber, und keines kann weiterfahren, weil beide darauf warten, dass das andere zurücksetzt. Eine Lösung könnte sein, dass ein Auto zurücksetzt, um den Weg freizumachen.

---

## Dateiverwaltung & Client-Server-Modell

### Aufgabe 10: Recherche & Skizze
Lies Kapitel 2.4 und 2.5.

**Flussdiagramm: Wie wird eine Datei geöffnet, gelesen und geschlossen?**
1. Datei öffnen
2. Datei lesen
3. Datei schließen

**Optional: Wie funktioniert eine Kommunikation im Client-Server-Modell?**
1. Client sendet Anfrage
2. Server empfängt Anfrage
3. Server verarbeitet Anfrage
4. Server sendet Antwort
5. Client empfängt Antwort

### Aufgabe 11: Reflexionsfragen
1. **Welche Rolle spielt Sicherheit beim Zugriff auf Dateien?**
   - Sicherheit ist entscheidend, um unbefugten Zugriff und Datenverlust zu verhindern.

2. **Warum ist das Client-Server-Modell heute so wichtig?**
   - Es ermöglicht verteilte Anwendungen und Dienste, die über das Internet zugänglich sind.

3. **Wie unterscheidet sich dein PC zuhause von einem Server?**
   - Ein PC ist für den persönlichen Gebrauch optimiert, während ein Server für die Bereitstellung von Diensten und die Verarbeitung vieler gleichzeitiger Anfragen ausgelegt ist.

### Aufgabe 12: Freie Schlussfrage
**Welche Aufgaben eines Betriebssystems findest du persönlich am wichtigsten – und warum?**
Die Prozessverwaltung ist besonders wichtig, da sie die Ausführung von Anwendungen ermöglicht und die Systemleistung optimiert. Ohne effiziente Prozessverwaltung wäre Multitasking nicht möglich.
