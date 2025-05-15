[[3.Itsi]]
___
#### Acces Points
Haben eine:
**BSSID**: Basic Service Set Identifier
**SSID**: Service Set Identifier

Diese deckt ein **BSS**:Basic Servide Set ab (Netzbereich)
___
![[Acess Point dies das.excalidraw]]
Wenn man zwischen mehreren **BSS** herum wechselt, nennt man das Roamen.

Das cuppen der Verbindung ist eine **DEAUTHENTICATION**
Verbindungsaufbau bei TCP: Freeway Handshake, FINAK, AK, FIN

Daher jeder Deauthetifizierungen schicken kann, kann man damit auch angreifen.

#### WLAN-Security
WEP Veraltet
WPA Veraltet

WPA-2
WPA-3
Davon gibt es jewiels Personal(Pre-Shared-Key) und Enterprise(RADIUS)
RADIUS(802.1x)

Enterprise(RADIUS) nutzt eine Nutzerauthentication beim Anmelden
### Deauthentication Angriff
1. WLAN Monitoren
2. Wichtige Infos Aufzeichnen: SSID, BSSID, Client
3. Deauthentication Frames absenden -> DoS

##### Evil Twin/Rogue Acess Point
Das gesamte Netzwerk kopieren, daneben parralel aufbauen und als original ausgeben. Deauthentications senden und der Client verbindet sich mit dem geclonten AP. Dann alle Daten aus-sniffen von Verbundenen Clients.

##### 4-Way-Handshake-Attack
Betrifft nur WPA-2-Personal
