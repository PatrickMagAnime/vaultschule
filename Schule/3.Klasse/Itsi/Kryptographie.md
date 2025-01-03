[[3.Itsi]]
|   |   |   |   |
|---|---|---|---|
|||||
||||1.<br><br>Confidentiality<br><br>Integrity<br><br>Availability|
||- C I A<br>- Symetrische & Asymetrische verschlüsselung<br>- Hashfunktionen||
||||

Kryptographie ist die Lehre des Verschlüsseln und entschlüsseln

2.

Symetrische Verschlüsselung:

Es gibt einen Schlüssel. Beide Seiten nutzen diesen.

Problem: beide müssen auf den selben Schlüssel kommen. Wenn einer von beiden den Schlüssel verliert oder wenn er öffentlich ist.

Beispiele: -AES, DES, und 3DES, Blowfish

Vorteile: Schnell und Performant, Quanten sicher

Nachteile: Schlüsselmanagement

AES ist in Blöcke aufgeteilt. Bei einer Datei von 1mb wird diese in 16byte oder 128bit Blöcke aufgeteilt. Jeder Block wird Verschlüsselt und dann zusammengefügt.

Bei dem Schlüssel kann man sich die Schlüssellänge aussuchen(128bit, 256bit oder 512bit(Je nach Schlüssellänge läuft der rounkey mehrmals durch).

Der Schlüssel wird dann in roundkeys unterteilt.(Der läuft 10 mal durch und verschlüsselt 10mal bei 128bit) bei 256 14 runden

Das ganze wird so lange gemacht bis jeder Block verschlüsselt wurde. Dann werden sie noch kombiniert.

3.

A-symetrische verschlüsselung

Es gibt einen privaten und einen öffentlichen schlüssel

Den öffentlichen kann jeder haben.

Wenn person A etwas zu B Schicken will, hat A 3 schlüssel. Seine eigenen 2, und den public key des anderen. Der andere entschlüsselt das dann mit dem privaten.

RSA- Rivest,Samir,Adleman

Vorteile:

Jeder hat einen eigenen schlüssel

Ermöglicht die authentifizierung

Nachteile:

Langsame berechnung

Kann zurückgerechnet werden durch quantencomputer