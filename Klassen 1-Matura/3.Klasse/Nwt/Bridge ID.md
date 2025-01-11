[[3.Nwt]]
____
# Bridge ID

## Bedeutung und Verwendung

Die Bridge ID ist ein wesentlicher Bestandteil des Spanning Tree Protocol (STP), das dazu dient, Schleifen in Netzwerken zu vermeiden und eine stabile Baumstruktur zu schaffen.

### Bestandteile der Bridge ID

- **Priorität**: Ein 2-Byte-Wert (0-61440 in Schritten von 4096), der die Priorität der Bridge angibt. Niedrigere Werte haben höhere Priorität.
- **MAC-Adresse**: Die eindeutige physische Adresse der Bridge. Sie wird verwendet, um zwischen Bridges mit gleicher Priorität zu unterscheiden.

### Auswahl der Root Bridge

Die Root Bridge ist die zentrale Bridge im Spanning Tree. Sie wird anhand der niedrigsten Bridge ID ausgewählt.

1. **Priorität**: Die Bridge mit der niedrigsten Priorität wird bevorzugt.
2. **MAC-Adresse**: Bei gleicher Priorität wird die Bridge mit der niedrigsten MAC-Adresse bevorzugt.

### Beispiel

Angenommen, wir haben zwei Bridges mit den folgenden Bridge IDs:

- **Bridge 1**: Priorität 32768, MAC-Adresse 00:11:22:33:44:55
- **Bridge 2**: Priorität 32768, MAC-Adresse 00:11:22:33:44:54

In diesem Beispiel wird Bridge 2 zur Root Bridge, da sie die niedrigere MAC-Adresse hat, obwohl beide die gleiche Priorität haben.

### Wichtigkeit

Die Bridge ID ist entscheidend für die Effizienz und Stabilität eines Netzwerks. Sie ermöglicht die Bestimmung der optimalen Pfade und verhindert Netzwerk-Schleifen, die zu Datenüberlastungen und Netzwerkstörungen führen könnten.
