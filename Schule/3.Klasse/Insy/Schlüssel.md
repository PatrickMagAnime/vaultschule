[[3.Insy]]
____
## Ist ein Attribut und dient dazu, Einträge zu unterscheiden

### Attribut zur eindeutigen Unterscheidung von Einträgen einer Tabelle

### Schlüsselkandidat

- Attribute, aus denen man einen eindeutigen Schlüssel erstellen kann. Ein Schlüssel kann auch aus mehreren Attributen zusammengesetzt werden.

### Primärschlüssel

- Jede Tabelle benötigt einen eindeutigen Schlüssel
  -> Primärschlüssel (Primary Key)
- Mittels des PS kann man alle Einträge einer Tabelle miteinander unterscheiden
  -> automatisch: unique, not null

### Definition eines Primärschlüssels

1. Es existiert ein eindeutiges Attribut in der Tabelle und man erklärt es zum Primary Key.
2. Es existieren keine Attribute, die eindeutig sind. Man fügt ein eindeutiges Ordnungsattribut hinzu.
3. Man bildet eine Kombination von mehreren nicht eindeutigen Attributen zu einem eindeutigen Primärschlüssel.

## Nützliches Wissen

- **Einzigartigkeit**: Ein Primärschlüssel stellt sicher, dass jede Zeile in einer Tabelle eindeutig identifiziert werden kann.
- **Integrität**: Ein Primärschlüssel hilft, die Datenintegrität zu bewahren, indem er sicherstellt, dass keine zwei Zeilen dieselbe Primärschlüssel-Wertekombination haben.
- **Beziehungen**: Primärschlüssel sind oft mit Fremdschlüsseln in anderen Tabellen verknüpft, um Beziehungen zwischen Tabellen darzustellen.
- **Automatisches Inkrementieren**: In vielen Datenbanksystemen kann ein Primärschlüssel automatisch inkrementiert werden, was das Hinzufügen neuer Datensätze erleichtert.
