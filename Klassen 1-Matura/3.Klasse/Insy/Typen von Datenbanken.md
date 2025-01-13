[[3.Insy]]
____
# Typen von Datenbanken

## Relationale Datenbanken
- Daten in Form von Tabellen organisieren
- Beziehungen zwischen Tabellen

## Objekt Orientierte Datenbanken
- Daten in Form von Objekten
- Zusammenfassen von Klassen

## Hierarchische Datenbanken
- Daten werden in Form von Bäumen organisiert (Binärbaum)
- Eltern-Kind Beziehungen

## NoSQL Datenbank
- Flexible Datenschemata
- Dokumenten Orientierte Datenbank
- Spalten Orientierte Datenbank

### Relative Datenbank Systeme
- Datenstruktur: Tabelle

```markdown
|   A1   |   A2   |   A3   |   A4   |   A5   |   A6   |
|--------|--------|--------|--------|--------|--------|
|   W11  |   W12  |   W13  |   W14  |   W15  |   W16  |
|   W21  |   W22  |   W23  |   W24  |   W25  |   W26  |
```

## Daten Bank Entwurf
- Entwurf eines Datenmodells
- Überlegung, welche Daten wie gespeichert werden

### Begriffe
- **Tupel/Datensatz/Eintrag (Zeile)**
- **Relation**

### Beispiel Bibliothek

| ID         | Titel            | Autore/-n         | Verlag        | Sprache | Genre | Datum     | ID         | Verliehen an | Ver-Datum | Kunde-SVN    | Kunden ID   | E-Mail            |
|------------|------------------|-------------------|---------------|---------|-------|-----------|------------|--------------|-----------|--------------|-------------|-------------------|
| AA-aaa001  | Nur lernen SQL   | Hans Vielstreber  | Musterverlag  | Deutsch | IT    | Xx.xx.2007| AA-aaa001  | X            | X         | X            | X           | X                 |
| AA-aaa002  | Nur lernen SQL 2 | Hans Vielstreber  | Musterverlag  | Deutsch | IT    | Xx.xx.2015| AA-aaa002  | Markus Rühl  | 23.5.24   | 38-34-1203-1979 | K24-aaa001 | markus@rühl.com   |
| AA-aaa003  |                  |                   |               |         |       |           | AA-aaa003  |              |           |              |             |                   |
| AA-aaa004  |                  |                   |               |         |       |           | AA-aaa004  |              |           |              |             |                   |
| AA-aaa005  |                  |                   |               |         |       |           | AA-aaa005  |              |           |              |             |                   |
| AA-aaa006  |                  |                   |               |         |       |           | AA-aaa006  |              |           |              |             |                   |
| AA-aaa007  |                  |                   |               |         |       |           | AA-aaa007  |              |           |              |             |                   |

### ANSI 3-Schichten Modell
1. **Externe Ebene:**
   - Anwenderprogramme
   - Benutzeroberfläche
   
2. **Konzeptionelle Ebene:**
   - Festlegung der Datenstruktur
   - ERM (Entity Relationship Modell)
   
3. **Interne Ebene:**
   - Laufwerke
   - Pfade
   - Ordner
   - Dateien

### Entity Relationship Modell (ERM)
- Logisches Datenmodell
- Abbild eines Ausschnitts der realen Welt auf einer Datenbank
- Welche Daten sind notwendig und bedeutsam
- Welche Beziehungen bestehen zwischen den Objekten eines Datenmodells

**Objekte**:
- Schüler, Einrichtung, Inventar, Lehrperson, Handymarke, Schuhgröße, Schülernummer

**Entität:**
- **Beziehungen Lehrperson**
  - Unterrichtet Klasse
- **Attribute**
  - Kürzel (Lehrperson), Geburtsdatum
  - Klasse: Bezeichnung, Raum, JV