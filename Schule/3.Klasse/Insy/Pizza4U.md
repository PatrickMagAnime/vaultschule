[[3.Insy]]
___
## Aufgabenstellung
![[Pizza4U Insy.jpg]]
## Entitäten und Attribute
1.**Kunde:**
Attribute:
- KundenID (Primärschlüssel)
- Name
- Adresse
- Telefonnummer
- Email (optional)

2. **Pizza:**
Attribute:
- PizzaID (Primärschlüssel)
- Bezeichnung
- Preis

3. **Zutat:**
Attribute:
- ZutatenID (Primärschlüssel)
- Name

4. **Bestellung:**
Attribute:
- BestellID (Primärschlüssel)
- KundenID (Fremdschlüssel)
- Bestelldatum

5. **Bestellposten:**
Attribute:
- BestellpostenID (Primärschlüssel)
- BestellID (Fremdschlüssel)
- PizzaID (Fremdschlüssel)
- Menge

6. **PizzaZutat:**
Attribute:
- PizzaID (Primärschlüssel, Fremdschlüssel)
- ZutatenID (Primärschlüssel, Fremdschlüssel)

## Beziehungen
- Ein Kunde kann mehrere Bestellungen aufgeben (One-to-Many Beziehung zwischen Kunde und Bestellung).
- Eine Bestellung kann mehrere Pizzen enthalten (One-to-Many Beziehung zwischen Bestellung und Bestellposten).
- Eine Pizza kann Teil mehrerer Bestellungen sein (Many-to-Many Beziehung zwischen Bestellposten und Pizza).
- Eine Pizza kann mehrere Zutaten haben (Many-to-Many Beziehung zwischen Pizza und Zutat).
# Formen
## 1. Normalform (1NF)
- Alle Attribute müssen atomar sein (d.h., jedes kleinste Detail).
- Jede Tabelle muss einen Primärschlüssel haben.
## 2. Normalform (2NF)
- Eine Tabelle muss in der 1. Normalform (1NF) sein.
- Alle nicht-schlüssel Attribute müssen voll funktional abhängig vom Primärschlüssel sein.
## 3. Normalform (3NF)
- Eine Tabelle muss in der 2. Normalform (2NF) sein.
- Es darf keine transitiven Abhängigkeiten zwischen nicht-schlüssel Attributen und dem Primärschlüssel geben.
## 4. Boyce-Codd-Normalform (BCNF)
- Eine Tabelle muss in der 3. Normalform (3NF) sein.
- Für jede nicht-triviale funktionale Abhängigkeit \( A \rightarrow B \) muss A ein Superschlüssel sein.
## 5. Normalform (4NF)
- Eine Tabelle muss in der Boyce-Codd-Normalform (BCNF) sein.
- Es dürfen keine mehrwertigen Abhängigkeiten existieren.
## 6. Normalform (5NF)
- Eine Tabelle muss in der 4. Normalform (4NF) sein.
- Es dürfen keine Join-Abhängigkeiten existieren, die nicht durch Kandidatenschlüssel impliziert werden.
## 7. Domänen-Schlüssel-Normalform (DKNF)
- Eine Tabelle muss in der 5. Normalform (5NF) sein.
- Alle Einschränkungen auf die Tabelle müssen durch Domänen- und Schlüsselabhängigkeiten erzwungen werden.