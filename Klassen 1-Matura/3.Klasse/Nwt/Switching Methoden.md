[[3.Nwt]]
____

# Switching Methoden

## Ethernet Typen:

- **0x0800**: IPv4
  - IPv4 (Internet Protocol version 4) ist ein Protokoll für die Vermittlung von Datenpaketen über Netzwerke. Es verwendet 32-Bit-Adressen und ist weit verbreitet im Internet.

- **0x0806**: ARP
  - ARP (Address Resolution Protocol) wird verwendet, um die MAC-Adresse eines Geräts im lokalen Netzwerk zu ermitteln, das zu einer bekannten IP-Adresse gehört.

- **0x8600**: IPv6
  - IPv6 (Internet Protocol version 6) ist die neueste Version des Internetprotokolls. Es verwendet 128-Bit-Adressen, um die zunehmende Anzahl an Internetgeräten zu unterstützen und bietet Verbesserungen in Bezug auf Sicherheit und Effizienz gegenüber IPv4.

- **0x9100**: VLAN - Tag
  - VLAN-Tagging ermöglicht es, mehrere logische Netzwerke (VLANs) innerhalb eines physischen Netzwerks zu erstellen. Jedes VLAN hat seine eigene Broadcast-Domäne, was die Netzwerkeffizienz und -sicherheit erhöht.
  - Das VLAN-Tagging wird durch das IEEE 802.1Q-Protokoll definiert und ist unerlässlich für den Betrieb von VLANs über Trunk-Links zwischen Switches.

## Zusatzinformationen zu Switching Methoden

- **Store-and-Forward**:
  - Der Switch empfängt das gesamte Datenpaket, überprüft es auf Fehler und leitet es erst dann weiter. Dies bietet eine hohe Sicherheit und Integrität der Daten, kann aber zu Verzögerungen führen.

- **Cut-Through**:
  - Der Switch beginnt mit dem Weiterleiten des Datenpakets, sobald die Zieladresse ausgelesen wurde, ohne auf den gesamten Paketempfang zu warten. Dies verringert die Latenz, birgt jedoch das Risiko, fehlerhafte Pakete weiterzuleiten.

- **Fragment-Free**:
  - Eine Kombination aus Store-and-Forward und Cut-Through. Der Switch liest die ersten 64 Bytes des Pakets, bevor er es weiterleitet. Dies reduziert die Wahrscheinlichkeit, dass fehlerhafte Pakete weitergeleitet werden.

- **Adaptive Switching**:
  - Der Switch wechselt dynamisch zwischen den verschiedenen Switching-Methoden (Store-and-Forward, Cut-Through, Fragment-Free) basierend auf den Netzwerkbedingungen und der Fehlerhäufigkeit.
