[[3.Itsi]]
____
## Gefahren erkennen
**10.2.134.100:22**
Ist möglicherweise ein SSH Port an dem man sich einloggen könnte. Man sieht auch die Server-IP

**127.0.0.1:80**
Man kann daraus herausfinden das ein Webserver aktiv ist. Könnte man auslesen. Außer Locale Adr.

**8.8.8.8:53**
Das ist ein DNS von Google und der Port ist von einem DNS Dienst.

## Gefahren erkennen 2

**0.0.0.0:21**  
Port 21 ist für den FTP-Dienst (File Transfer Protocol) zuständig. Ein offener FTP-Port ohne Absicherung (z. B. fehlende Verschlüsselung oder schwache Zugangsdaten) könnte es Angreifern ermöglichen, auf Dateien des Servers zuzugreifen oder diese zu manipulieren. FTP ist besonders riskant, da Benutzernamen und Passwörter oft im Klartext übertragen werden.

---

**127.99.1.113:22**  
 Port 22 ist für den SSH-Dienst (Secure Shell) zuständig. Ein offener SSH-Port kann genutzt werden, um sich auf einem Server einzuloggen. Ist der Zugang schlecht gesichert (z. B. schwache Passwörter oder fehlende Zwei-Faktor-Authentifizierung), könnten Angreifer Zugriff auf den Server erhalten und ihn kontrollieren.

---

**220.113.1.3:443**  
Port 443 ist für HTTPS-Verbindungen zuständig. Dies ist die gesicherte Variante von HTTP. Ein offener HTTPS-Port ist grundsätzlich weniger anfällig als HTTP (Port 80), aber auch hier können Schwachstellen bestehen, etwa durch veraltete TLS-Versionen, falsch konfigurierte Zertifikate oder anfällige Webanwendungen, die über diesen Port zugänglich sind.

---

**172.16.0.1:445** 
Port 445 ist für SMB (Server Message Block) zuständig, der für Datei- und Druckerfreigaben verwendet wird. Ein offener SMB-Port ist sehr gefährlich, insbesondere wenn er von außen zugänglich ist, da er häufig Ziel von Ransomware-Angriffen und anderen Exploits (z. B. EternalBlue) ist. Der Port sollte niemals ohne Einschränkungen öffentlich verfügbar sein.
## Erklärung der Ports
**Ports:**
22: SSH
80: http
53: DNS
21: FTP Port
443: https
445 SMB