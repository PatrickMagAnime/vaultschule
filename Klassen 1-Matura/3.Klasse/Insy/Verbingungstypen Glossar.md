[[3.Insy]]
___
Beziehungstypen gehören zu den grundlagen von relationalen Datenbanken. Beziehungstypen beschreiben die Art der Verknüpfung zwischen zwei oder mehreren Tabellen in einer Datenbank. Davon gibt es drei Haupttypen:

    1:1 (Eins zu Eins) - Jede Zeile in Tabelle A ist mit genau einer Zeile in Tabelle B verknüpft.
    1:N (Eins zu Viele) - Eine Zeile in Tabelle A kann mit mehreren Zeilen in Tabelle B verknüpft sein.
    N:M (Viele zu Viele) - Mehrere Zeilen in Tabelle A können mit mehreren Zeilen in Tabelle B verknüpft sein.

Beispiel: In einer Datenbank zur Kursen könnte eine Beziehung zwischen der Tabelle „Studenten“ und „Kurse“ vom Typ N:M sein, da ein Student mehrere Kurse haben kann, und ein Kurs mehrere Studenten haben kann.

Quelle: https://mediencommunity.de/system/files/Beziehungen%20in%20Datenbanken.pdf