[[3.Itsi]]
___
## Packet Sniffing
Auf einer Seite gibt es einen Client und auf der anderen Seite einen Server die beide Verbunden sind. Wireshark ein SNiffing tool kann man auf beider der seiten installieren. Wireshark wird alles aufzeichnen was eingehen und ausgehende datenpackete sind. so kann mna im kleinsten detail herauslesen was gerade im netzwerk pasiert.

**Was sieht man?**
Gesendete nachrichten vom Client (ausgehend) sowie (zum client)
Broadcast (eingehend) & Multicasts (eingehend)

Mitlesen und Nachrichten im idealen netz.
- Hub (Eingehende nachrichten werden an einen slot eingehen aber an allen slots ausgeschickt)

![[Pc mit Hub zu server verbunden.png]]
Angreifer Schließt sich am hub an und kann alle nachrichten mitlesen da der hub alles weiterleitet.

Der client mit wireshark nimmt nur packete an die an ihn selbst gerichtet sind.

Es gibt aber den **promiscous mode** der es erlaubt alle packete anzunehmen selbst die die nicht an ihm gerichtet sind. Dafür muss man wireshark mit administrator öffnen.

### Managed Switch
auf einem unmanaged switch kann man nicht konfigurieren und hat keine vlans. ein managed switch hat mehrere funktionen und man kann einen hub mithilfe von **mirror port** einrichten.

