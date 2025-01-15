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
