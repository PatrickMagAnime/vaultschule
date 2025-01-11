[[3.Nwt]]
____
## Wichtige Befehle und Konzepte
```c
### Befehle zur Schnittstellenanzeige

````code
Show ip interface brief
Show ipv6 interface brief
````

### Netzwerkgrundlagen

- **Hub** leitet eingehende Daten an alle Ausgänge weiter.
- **Switch** überprüft nochmals, an wen die Daten gesendet werden sollen.

### Verbindungsgeschwindigkeiten und Modi

- **Geschwindigkeit**: auto /10/100/1000/10G/25G/100G/400G/
- **Duplex-Modi**: full (2 Kanäle) / half (für 10mb/100mb Ethernet)

### MDIX Auto

- Man kann das Einschalten von MDIX auto konfigurieren:
  - (no) Mdix auto

### Automatische Aushandlung (Auto negotiation)

- Ø Aushandlung der Bandbreite, Duplex und Ausbrenzung.
- Ø Nur bei TP-Ethernet.
- Ø Linkpulse: NLP/FLP zur Kollisionsvermeidung. Alle 16ms sendet eine Schnittstelle diese Linkpulse (100ns breit für 10Base-T Ethernet).

### SSH-Konfiguration

````c
copy
copy run start
crypto key generate rsa
# how many bits in the modulus [512]:
1024
[#####___________________] loading
SSH v.2 enabled
username 3ahitn password cisco
do show run
! Passwort sichtbar
username 3ahitn no
username 3ahitn secret cisco
enable secret class
````
````c
enable
password:
line con 0
login local
logging synchronous
````
````c
enable
conf t
line vty 0 4
login local
logging synchronous
transport input ssh
do wr
````
````c
ssh -l 3ahitn <ip-adresse-vom-switch>
password:
````

### Wichtige Informationen

- **Strg-Shift-6**: Um Vorgänge abzubrechen.
- **no ip domain-lookup**: Verhindert, dass der Switch versucht, bei Tippfehlern neue Nutzer zu erstellen (dauert sonst Minuten).

### VLANs

- **Unterschied zwischen Access Ports und Trunk Ports:**
  - **Access Ports**: Empfangen nur ungetaggte Datenrahmen, Markierung geht weg.
  - **Trunk Ports**: Markierung bleibt bestehen, überträgt nur getaggte Datenrahmen.

- **Standard (Default) VLAN**: Hat immer die Nummer 1 und sollte nicht benutzt werden (aus Sicherheitsgründen).

````code
show vlan brief
````

- **VLANs unter 1024**: Stehen in VLAN.dat. Am Ende der Übung die Konfiguration löschen:

````code
erase startup-config
delete flash:vlan.dat
````

### VLAN-Typen

- **Daten VLAN**: Daten werden zum Nutzer vermittelt.
- **Native VLAN**: Sendet Trunk ohne Markierung (muss auf beiden Seiten gleich konfiguriert sein).
- **Voice VLAN**: Sind höher priorisiert.
- **Management VLAN**: Sollte am besten gesichert sein. Erlaubt IP-Adressen-Konfiguration und erreicht alle Netzwerke.

- **Switchport nonegotiate**: Verhindert, dass man sich als Switch ausgeben und vollen Zugriff erhalten kann.

### Tags

- **802.1p**: 3-bit Priorität im Tag.
- **802.1Q**: VLAN-Tag.
