[[3.Insy]]
___
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