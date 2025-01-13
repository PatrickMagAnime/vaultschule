[[3.Insy]]
____
- Objekte -> welche Information?
- Beziehungen ->  welche Beziehungen?
### Entität (Entity)  
- Ein Exemplar einer Person, Ware, nicht materiellen Gutes über welches Informationen gespeichert wird.

zB: ein Laptop, Wissen (nicht Materiell)
- Einträge Datensatz

Entitäten erden zu einer Klasse zusammengefasst.
- Entitäts typ.
- Lehrperson, oder eine Schulklasse
- Tabelle

Entitäten haben Eigenschaften/Eigenschaften
	zB: Lehrperson Kürzel, Name, Klasse, (JV), Geb.Daten

Attribute haben einen konkreten Wert. zB: Nachname "Müller"
- Spalten in einer Tabelle
![[ERM Table beispeil.png]]
## Entity Relationship Model
Logisches Datenmodel
Beziehungen zwischen Entitäten:
- Entitäten können zueinander in Beziehungen stehen um deren verhalten genaurer zu beschreiben.
z.B: Kunde kauft Produkt
- Lehrperson unterrichtet Klasse
- Beziehungen haben einen Typ und müssen immer in beide Richtungen betrachtet werden.

 - (müssen immer in beide Richtungen betrachtet werden)

**1:1**    
Eine Entität eines Typs hat eine Beziehung zu genau eine Entität eines anderen Typs

z.B eine Person hat eine Sozialversicherungsnummer.

Oder eine Sozialversicherungsnummer hat genau nur eine person.

3 Beziehungstypen:

**1:n**     
Eine Entität hat Beziehungen zu mehreren Entitäten eines anderen Typs. In der anderen Richtung besteht eine Einfachbeziehung

z.B: Eine Klasse besteht aus mehreren SchülerInnen, eine SchülerIn besucht genau eine Klasse

**n:m**   
Eine Entität eines Typs hat Beziehungen zu mehreren Entitäten enes anderen Typs und umgekehrt.

z.B: Lehrperson und Klasse

Eine LP unterrichtet mehrere Klassen
Eine klasse wird von mehreren Lehrern unterrichtet

Kardinalität - Wertigkeit einer Beziehung (Einfach oder Mehrfachbeziehung).

Optionalität - Eine Beziehung kann oder muss bestehen. zB: Schüler besucht Klasse (Kann es sein das ein Schüler keine Klasse besucht?)

![[ERM Bezeichnungen und Zeichen.png]]