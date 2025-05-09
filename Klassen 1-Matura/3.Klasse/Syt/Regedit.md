[[3.Syt]]
___
## Teil A: Theoriefragen (Kurzantworten)

**1. Was ist die Windows-Registry und wofür wird sie verwendet?**  
Die Windows-Registry ist eine Datenbank in Windows in der Einstellungen und Informationen zum Betriebssystem zu Programmen, zu Benutzern und zur Hardware gespeichert werden. Sie wird dafür verwendet das Windows und Programme wissen, wie sie sich verhalten sollen.

**2. Nenne die fünf Hauptbereiche (Hives) der Registry und beschreibe jeweils kurz deren Zweck.**  
**HKEY_CLASSES_ROOT (HKCR):** Hier stehen Infos über Dateitypen und wie sie mit Programmen verknüpft sind.

	**HKEY_CURRENT_USER (HKCU):** Hier stehen Einstellungen, die nur für den aktuell angemeldeten Benutzer gelten.
	
	**HKEY_LOCAL_MACHINE (HKLM):** Hier stehen Einstellungen, die für alle Nutzer des Rechners gelten, zum Beispiel installierte Programme oder Hardware.
	
	**HKEY_USERS (HKU):** Hier sind für alle Benutzerkonten die Einstellungen gespeichert.
	
	**HKEY_CURRENT_CONFIG (HKCC):** Hier sind Infos zur aktuellen Hardware-Konfiguration gespeichert.

**3. Was ist der Unterschied zwischen einem Schlüssel und einem Wert in der Registry?**  
Ein Schlüssel ist wie ein Ordner, in dem Einstellungen liegen. Ein Wert ist wie eine Datei darin, die einen Namen und einen Inhalt hat.

**4. Welche Bedeutung haben folgende Datentypen in der Registry?**  
- **REG_SZ:** Das ist ein normaler Text (Zeichenfolge).
- **REG_DWORD:** Das ist eine Zahl, meistens 0 oder 1, manchmal aber auch andere Zahlen.
- **REG_BINARY:** Das sind Rohdaten, also Zahlen in einer bestimmten Form, die der Computer benutzt.

---

## Teil B: Praktische Aufgaben

**5. Öffne den Registrierungseditor (regedit). Navigiere zu folgendem Pfad und lies den vorhandenen Wert aus:**  
*HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion*

**a) Wie heißt der Schlüssel, der die Windows-Version enthält?**  
Ich habe im Registrierungseditor den Pfad geöffnet und nachgeschaut.  
Der Schlüssel heißt: `ProductName`

**b) Welcher Wert steht dort?**  
Bei mir steht dort:  
`Windows 10 Pro`  
(Das kann je nach Windows-Version unterschiedlich sein.)

---

**6. Erstelle folgenden neuen Schlüssel in der Registry:**  
- **Pfad:** HKEY_CURRENT_USER\Software\HTLTest  
- **Neuer Schlüssel:** TestKey  
- **Neuer Wert:** Name = "Patrick" (Typ: REG_SZ)  

**So bin ich vorgegangen:**  
1. Ich habe den Registrierungseditor (regedit) geöffnet.  
2. Dann bin ich zu `HKEY_CURRENT_USER\Software` gegangen.  
3. Dort habe ich mit Rechtsklick auf `Software` → `Neu` → `Schlüssel` ausgewählt und den Namen `HTLTest` vergeben.  
4. Danach habe ich auf `HTLTest` rechtsgeklickt, wieder `Neu` → `Schlüssel` und diesen `TestKey` genannt.  
5. Im Schlüssel `TestKey` habe ich rechts im Fenster Rechtsklick → `Neu` → `Zeichenfolge` ausgewählt.  
6. Die Zeichenfolge habe ich `Name` genannt.  
7. Mit Doppelklick auf `Name` habe ich als Wert `"Patrick"` eingetragen.

---

**7. Exportiere den erstellten Schlüssel (HTLTest) in eine .reg-Datei. Beschreibe den Aufbau dieser Datei.**  

**Schritte:**  
1. Im Registrierungseditor habe ich mit Rechtsklick auf `HTLTest` geklickt.  
2. Dann habe ich „Exportieren“ gewählt.  
3. Die Datei habe ich als `HTLTest.reg` gespeichert.

**Aufbau der .reg-Datei:**  
- Oben steht: `Windows Registry Editor Version 5.00`
- Dann steht der Pfad in eckigen Klammern, z.B. `[HKEY_CURRENT_USER\Software\HTLTest\TestKey]`
- Darunter steht der Wert als Text.

**Beispiel-Inhalt der Datei:**  
```
Windows Registry Editor Version 5.00

[HKEY_CURRENT_USER\Software\HTLTest\TestKey]
"Name"="Patrick"
```

---

## Teil C: Anwendungsbeispiele

**8. Welche Registry-Pfade sind für den Autostart von Programmen beim Windows-Login relevant?**  
- `HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Run` (nur für den aktuellen Benutzer)
- `HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Run` (für alle Benutzer)

**9. Recherchiere ein Beispiel, wie eine Software bei der Installation Registry-Werte verwendet.**  
Bei der Installation von vielen Programmen, zum Beispiel Google Chrome, wird in der Registry ein Eintrag für den Autostart gemacht.  
Das passiert oft im Pfad  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Run`  
Dort steht dann zum Beispiel:  
`"GoogleChromeAutoLaunch_..."="C:\Program Files\Google\Chrome\Application\chrome.exe --auto-launch-at-startup"`  
Dadurch startet Chrome automatisch, wenn man sich anmeldet.

---

## Zusatzaufgabe (freiwillig)

**10. Was sind die Gefahren bei der Bearbeitung der Registry? Wie kann man sich davor schützen?**  
- Gefahren:  
  - Wenn man etwas Falsches ändert oder löscht, kann Windows oder ein Programm nicht mehr richtig funktionieren.
  - Im schlimmsten Fall startet der Computer nicht mehr.
- Schutz:  
  - Vorher die Registry oder einzelne Schlüssel exportieren (sichern).
  - Nur etwas ändern, wenn man weiß, was man tut.
  - Keine Registry-Dateien aus dem Internet ausführen, denen man nicht vertraut.

---