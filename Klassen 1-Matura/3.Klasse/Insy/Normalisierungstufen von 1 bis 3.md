[[3.Insy]]
___
## 1. Normalform (1NF)
- Alle Attribute müssen atomar sein (d.h., jedes kleinste Detail).
- Jede Tabelle muss einen Primärschlüssel haben.

| KundeID | Name      | Telefonnummer          |
|---------|-----------|------------------------|
| 1       | Max Meier | 0123-456789, 0987-654321 |
| 2       | Lisa Müller | 0123-111111          |

**Problem:** Die Spalte "Telefonnummer" enthält mehrere Werte und ist somit nicht atomar.  
**Lösung (1NF-konform):**

| KundeID | Name        | Telefonnummer   |
|---------|-------------|----------------|
| 1       | Max Meier   | 0123-456789    |
| 1       | Max Meier   | 0987-654321    |
| 2       | Lisa Müller | 0123-111111    |

---

## 2. Normalform (2NF)
- Eine Tabelle muss in der 1. Normalform (1NF) sein.
- Alle nicht-schlüssel Attribute müssen voll funktional abhängig vom Primärschlüssel sein.

| ArtikelID | LagerID | Menge | ArtikelName |
|-----------|---------|-------|-------------|
| 1         | 101     | 50    | Schrauben   |
| 2         | 102     | 20    | Nägel       |

**Problem:** "ArtikelName" hängt nur von "ArtikelID" ab, nicht von der gesamten Kombination aus Primärschlüsseln ("ArtikelID", "LagerID").  
**Lösung (2NF-konform):**

**Tabelle 1: Lagerbestand**

| ArtikelID | LagerID | Menge |
|-----------|---------|-------|
| 1         | 101     | 50    |
| 2         | 102     | 20    |

**Tabelle 2: Artikel**

| ArtikelID | ArtikelName |
|-----------|-------------|
| 1         | Schrauben   |
| 2         | Nägel       |

---

## 3. Normalform (3NF)
- Eine Tabelle muss in der 2. Normalform (2NF) sein.
- Es darf keine transitiven Abhängigkeiten zwischen nicht-schlüssel Attributen und dem Primärschlüssel geben.

| MitarbeiterID | AbteilungID | AbteilungName |
|---------------|-------------|---------------|
| 1             | 10          | Vertrieb      |
| 2             | 20          | Marketing     |

**Problem:** "AbteilungName" hängt transitiv von "MitarbeiterID" über "AbteilungID" ab.  
**Lösung (3NF-konform):**

**Tabelle 1: Mitarbeiter**

| MitarbeiterID | AbteilungID |
|---------------|-------------|
| 1             | 10          |
| 2             | 20          |

**Tabelle 2: Abteilungen**

| AbteilungID | AbteilungName |
|-------------|---------------|
| 10          | Vertrieb      |
| 20          | Marketing     |
