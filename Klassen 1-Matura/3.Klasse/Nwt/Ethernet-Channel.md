![[Ethernet-Channel.excalidraw]]

## EC-Voraussetzungen
- gleiche Geschwindigkeit
- gleiche Duplex
- gleiche Ports (Access/Trunk)
- gleiches native VLAN, ACL-VLAN

## Konfiguration eines EC
- **Erstellung des EtherChannels:**
    
    - Erstelle ein EtherChannel-Interface auf dem Switch:
        
        ```bash
        interface Port-channel <num>
        ```
        
- **Auswahl des Modus:**
    
    - Konfiguriere den EtherChannel-Modus auf "On", "Active" (LACP) oder "Passive" (LACP):
        
        ```bash
        interface range <interface-range>
        channel-group <num> mode <mode>
        ```
        
        - `mode on` – Festlegung eines statischen EtherChannels ohne LACP.
        - `mode active` – LACP aktivieren, um eine dynamische Link-Aggregation zu erzwingen.
        - `mode passive` – LACP im passiven Modus, bei dem der Switch auf LACP-Anfragen wartet.
- **Überprüfen der EtherChannel-Konfiguration:**
    
    - Zeige die Statusinformationen für den EtherChannel an:
        
        ```bash
        show etherchannel summary
        ```
        
- **Verwenden des richtigen Protokolls (LACP/PAgP):**
    
    - LACP (Link Aggregation Control Protocol) ist das Standardprotokoll für EtherChannels. PAgP kann als Alternative verwendet werden.
    - Um LACP zu konfigurieren, stelle sicher, dass LACP auf den betroffenen Schnittstellen aktiviert ist:
        
        ```bash
        interface range <interface-range>
        switchport mode trunk
        channel-group <num> mode active
        ```
        
- **Prüfung auf Fehler:**
    
    - Achte auf potenzielle Fehler wie "misconfigurations" in der EtherChannel-Konfiguration:
        
        ```bash
        show interface etherchannel <num> detail
        show running-config | include channel-group
        ```
        
- **Verbindungstests:**
    
    - Teste die Konnektivität über den EtherChannel mit „ping“ oder anderen Netzwerktools.
- **VLAN-Konfiguration:**
    
    - Stelle sicher, dass alle VLANs sowohl auf der Access- als auch auf der Trunk-Seite des EtherChannel konfiguriert sind.
        
        ```bash
        vlan <VLAN-ID>
        name <VLAN-Name>
        ```


