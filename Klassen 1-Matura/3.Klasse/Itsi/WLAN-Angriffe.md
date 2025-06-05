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

##### 4-Way-Handshake-Attack (detailliert, WPA2-Personal)

Der **4-Way-Handshake** ist ein Authentifizierungsverfahren, das beim Verbindungsaufbau im WPA2-Personal (802.11i) zwischen Client und Access Point (AP) verwendet wird, um einen gemeinsamen Sitzungsschlüssel (**PTK**, Pairwise Transient Key) sicher zu erzeugen.

**Ablauf und Angriffsmöglichkeiten:**

1. **Start:**  
   Der AP sendet eine zufällige Nummer, die **ANonce** (Authenticator Nonce), an den Client.
2. **Antwort:**  
   Der Client erstellt ebenfalls eine zufällige Nummer, die **SNonce** (Supplicant Nonce), und berechnet zusammen mit der ANonce, den MAC-Adressen und dem gemeinsamen Passwort den PTK. Die SNonce schickt er an den AP zurück.
3. **Bestätigung:**  
   Beide Seiten haben nun alle nötigen Werte, um unabhängig voneinander den gleichen PTK zu generieren.
4. **Verschlüsselung:**  
   Die Kommunikation ist ab jetzt mit diesem Session-Key verschlüsselt.

**Angriffsszenario:**

- Ein Angreifer kann Clients durch gezielte Deauthentication-Frames („Deauth-Attacke“) zwingen, die Verbindung zum AP zu verlieren und sich neu zu verbinden.
- Dabei wird der komplette 4-Way-Handshake erneut durchlaufen.
- Der Angreifer schneidet diesen Handshake mit (z.B. mit Tools wie Wireshark oder aircrack-ng).
- Im mitgeschnittenen Handshake sind sowohl die ANonce als auch die SNonce enthalten.

**Offline-Passwort-Angriff:**  
Mit allen übertragenen Werten (ANonce, SNonce, MAC-Adressen) und dem mitgeschnittenen Handshake kann der Angreifer nun offline verschiedene Passwörter (Wörterbuch- oder Brute-Force-Angriff) ausprobieren, um das richtige Passwort zu finden.

**Wichtig:**  
- Betrifft ausschließlich **WPA2-Personal** (mit Pre-Shared Key, PSK), nicht WPA2-Enterprise.
- Die Nonces (ANonce, SNonce) sorgen dafür, dass der Schlüssel bei jeder Verbindung einzigartig ist.
- Ein erfolgreicher Angriff ist nur möglich, wenn das Passwort schwach ist oder im Wörterbuch enthalten ist.

**Zusammengefasst:**  
Beim 4-Way-Handshake werden ANonce (vom AP) und SNonce (vom Client) zum sicheren Schlüsselaustausch genutzt. Ein Angreifer kann den Handshake mitschneiden, um offline das WLAN-Passwort zu erraten.