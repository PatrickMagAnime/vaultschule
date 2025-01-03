[[3.Nwt]]
____

## Router Konfigurieren
````bash
# Router
## Router Konfiguration

- **Copy running config startup config!!!** oder **write memory**

### Beschreibung zu einer Schnittstelle Hinzufügen

- **Show ip interface brief**: Zeigt alle konfigurierten Interfaces an.
- **Show ip interface brief <Filter>**: Filtern der angezeigten Informationen. 
  - **section**: Zeigt den Abschnitt.
  - **include + wort**: Schließt das Wort ein.
  - **exclude - wort**: Schließt das Wort aus.
  - **begin**: Beginnt mit dem angegebenen Wort.

### Anzeigen der Routing Tabelle

- **Show ip route**: Zeigt die Routing-Tabelle an.

### Loopbackschnittstelle

- Virtuelle Schnittstelle, der man eine IP-Adresse geben kann, die aber nicht nach draußen kommunizieren kann. Sie wird zum Testen verwendet.
- **Befehl**: `interface loopback`

## Beispiel Konfiguration

enable
configure terminal

! Konfiguration der seriellen Schnittstelle
interface serial0/0
ip address 192.168.1.1 255.255.255.0
clock rate 10000
login synchronous
description Verbindung zur Remote Site
no shutdown
exit

! Konfiguration der Loopback-Schnittstelle
interface loopback0
ip address 10.1.1.1 255.255.255.255
description Loopback für Testzwecke
exit

! Speichern der aktuellen Konfiguration
copy running-config startup-config

! Anzeigen der konfigurierten Schnittstellen
show ip interface brief
show ip interface brief | include 192.168.1.1
show ip interface brief | exclude administratively
show ip interface brief | section FastEthernet

! Anzeigen der Routing-Tabelle
show ip route

## Erklärung

- **Interface Clockrate**: Setzt die Taktfrequenz auf der seriellen Schnittstelle (in diesem Fall 10 kbps).
- **Login Synchronous**: Wenn man einen Befehl tippt und die Konsole eine Rückmeldung gibt, bleibt der eingegebene Befehl sichtbar.
- **Show ip interface brief**: Zeigt alle konfigurierten Interfaces an.
- **Show ip interface brief <Filter>**: Filtert die angezeigten Informationen.
  - **include**: Zeigt nur Zeilen an, die das angegebene Wort enthalten.
  - **exclude**: Zeigt alle Zeilen an, außer denen, die das angegebene Wort enthalten.
  - **section**: Zeigt einen Abschnitt, beginnend mit dem angegebenen Wort.
- **Show ip route**: Zeigt die Routing-Tabelle an.
- **Loopback-Schnittstelle**: Virtuelle Schnittstelle, die zu Testzwecken verwendet wird.

Diese Konfiguration sollte dir einen guten Überblick geben, wie man grundlegende Einstellungen auf einem Router vornimmt.
```
