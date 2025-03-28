# 1 Netzwerktechnik - Koaxialkabel

Koaxialkabel sind spezielle Kabel zur Übertragung von Hochfrequenzsignalen. Sie bestehen aus einem inneren Leiter (meist Kupfer), der von einer isolierenden Schicht umgeben ist, und einem äußeren leitenden Schirm. Diese koaxiale (gleichachsige) Anordnung ermöglicht eine hohe Störsicherheit und geringe Signalverluste, was sie ideal für die Netzwerktechnik, Fernsehsignale und Internetverbindungen macht.

**Kosten:**
- Je nach Typ und Qualität zwischen 0,50 und 2,50 Euro pro Meter
- Höherwertige Varianten für spezielle Anwendungen bis 5 Euro pro Meter

**Material:**
- Innenleiter: Kupfer oder versilbertes Kupfer
- Isolierung: Polyethylen (PE) oder Teflon (PTFE)
- Außenleiter/Schirm: Geflechtetes Kupfer oder Aluminiumfolie
- Mantel: PVC, PE oder halogenfrei (LSZH)

**Einsatzbereiche:**
- Kabelfernsehen und Satellitenempfang
- Ethernet-Netzwerke (früher: 10BASE2, 10BASE5)
- Breitband-Internetanschlüsse
- HF-Übertragungstechnik und Mobilfunk
- Mess- und Labortechnik

**Typen und Spezifikationen:**
- RG-6: 75 Ohm, Kabelfernsehen und Satellitenempfang
- RG-58: 50 Ohm, Netzwerktechnik und HF-Anwendungen
- RG-59: 75 Ohm, CCTV und Videoanwendungen
- RG-11: 75 Ohm, für längere Strecken und höhere Bandbreiten
- RG-174: 50 Ohm, dünne flexible Variante für mobile Anwendungen

**Zertifizierungen:**
- MIL-C-17 (Militärstandard)
- IEC 61196 (Internationale Norm)

## 1.1 Twisted-Pair-Kabel (Kupferkabel) - Ethernetkabel

Twisted-Pair-Kabel, auch als Kupferkabel bekannt, sind die meistverbreiteten Netzwerkkabel. Sie bestehen aus paarweise verdrillten Kupferadern, deren Verdrillung elektromagnetische Störungen reduziert und die Signalqualität verbessert. Diese flexiblen, kosteneffizienten Kabel werden hauptsächlich in Ethernet-Netzwerken eingesetzt und sind in ungeschirmten (UTP) und geschirmten (STP) Varianten erhältlich.

### 1.1.1 Unshielded Twisted Pair (UTP)

Unshielded Twisted Pair (UTP) Kabel sind die am weitesten verbreiteten Kabeltypen in modernen Ethernet-Netzwerken. Diese Kabel enthalten mehrere Paare verdrillter Kupferadern ohne zusätzliche metallische Abschirmung. Die Verdrillung der Adernpaare selbst bietet eine grundlegende Störfestigkeit durch gegenseitige Kompensation elektrischer Felder.

**Vorteile:**
- Kostengünstig in Anschaffung und Installation
- Leicht und flexibel, einfaches Handling
- Geringerer Durchmesser im Vergleich zu geschirmten Varianten
- Einfach zu terminieren und zu installieren

**Nachteile:**
- Geringere Störfestigkeit in Umgebungen mit starken elektromagnetischen Interferenzen (EMI)
- Höhere Anfälligkeit für Übersprechen zwischen Adernpaaren
- Begrenzte Eignung für industrielle Umgebungen mit starken elektrischen Störquellen

**Einsatzbereiche:**
- Bürogebäude und Wohnhäuser
- Normale gewerbliche Umgebungen
- Horizontale Verkabelung gemäß Strukturierter Verkabelung
- Lokale Netzwerke (LANs) mit geringen EMI-Belastungen

**Spezifikationen:**
- Typischerweise 4 verdrillte Paare (8 Adern)
- Normierte Farbcodierung der Adernpaare
- Gemäß TIA/EIA-568 und ISO/IEC 11801 Standards
- Standardimpedanz: 100 Ohm

### 1.1.2 Shielded Twisted Pair (STP) / F/UTP, S/FTP usw.

Shielded Twisted Pair (STP) Kabel bieten zusätzliche Abschirmungen gegen elektromagnetische Störungen. Diese Kabeltypen verfügen über verschiedene Schirmungsarten, die entweder die einzelnen Adernpaare und/oder das gesamte Kabel abschirmen. Die Abschirmung verbessert die Signalqualität in störbelasteten Umgebungen und ermöglicht höhere Übertragungsraten über längere Distanzen.

**Abschirmungsvarianten:**
1. **F/UTP** (Foiled Unshielded Twisted Pair): Gemeinsamer Folienschirm um alle ungeschirmten Adernpaare
2. **S/UTP** (Screened Unshielded Twisted Pair): Geflechtschirm um alle ungeschirmten Adernpaare
3. **SF/UTP** (Screened Foiled Unshielded Twisted Pair): Folien- und Geflechtschirm um alle ungeschirmten Adernpaare
4. **F/FTP** (Foiled Foiled Twisted Pair): Gesamtfolienschirm plus separate Folienschirme um jedes Adernpaar
5. **S/FTP** (Screened Foiled Twisted Pair): Geflechtschirm um alle einzeln foliengeschirmten Adernpaare
6. **U/FTP** (Unshielded Foiled Twisted Pair): Einzeln foliengeschirmte Adernpaare ohne Gesamtschirm

**Vorteile:**
- Hervorragende Abschirmung gegen elektromagnetische Störungen
- Minimales Übersprechen zwischen Adernpaaren
- Höhere Übertragungssicherheit und bessere Signalqualität
- Geeignet für Hochgeschwindigkeitsübertragungen (10 Gbit/s und mehr)

**Nachteile:**
- Höhere Kosten im Vergleich zu UTP-Kabeln
- Größerer Durchmesser und geringere Flexibilität
- Aufwändigere Installation und Terminierung
- Erfordert fachgerechte Erdung der Schirmung

**Einsatzbereiche:**
- Industrieumgebungen mit starken elektromagnetischen Störungen
- Rechenzentren und kritische Infrastrukturen
- Gebäude mit hoher Elektrifikation oder Sendeanlagen
- Übertragungsstrecken für hochbitratige Anwendungen

**Spezifikationen:**
- Standardimpedanz: 100 Ohm
- Schirmungseffektivität je nach Variante 40-90 dB
- Erfordert geschirmte Stecker und Buchsen (STP RJ45)
- Benötigt durchgehende Schirmung und Erdung aller Komponenten

### 1.1.3 Kategorien

Twisted-Pair-Kabel werden in verschiedene Kategorien (Cat) eingeteilt, die ihre elektrischen Eigenschaften und Übertragungsleistung definieren. Diese Klassifizierung bestimmt die maximale Übertragungsgeschwindigkeit, Bandbreite und die unterstützten Netzwerkprotokolle.

**Kategorie 1 (Cat 1):**
- Veraltet, für analoge Sprachübertragung (Telefonleitungen)
- Keine Datenübertragung spezifiziert
- Keine standardisierte Verdrillung

**Kategorie 2 (Cat 2):**
- Veraltet, für Datenübertragung bis 4 Mbit/s
- Bandbreite bis 1 MHz
- Historisch für Token Ring-Netzwerke verwendet

**Kategorie 3 (Cat 3):**
- Datenübertragung bis 10 Mbit/s
- Bandbreite bis 16 MHz
- Früher für 10BASE-T Ethernet verwendet
- Mindestens 3 Verdrillungen pro Meter

**Kategorie 4 (Cat 4):**
- Datenübertragung bis 16 Mbit/s
- Bandbreite bis 20 MHz
- Selten verwendet, heute weitgehend obsolet

**Kategorie 5 (Cat 5):**
- Datenübertragung bis 100 Mbit/s (Fast Ethernet)
- Bandbreite bis 100 MHz
- Vielfach durch Cat 5e ersetzt

**Kategorie 5e (Cat 5e):**
- Datenübertragung bis 1 Gbit/s (Gigabit Ethernet)
- Bandbreite bis 100 MHz mit verbesserten Übertragungseigenschaften
- Derzeit am weitesten verbreitet
- Verbesserte Parameter für Nebensprechen und Rückflussdämpfung

**Kategorie 6 (Cat 6):**
- Datenübertragung bis 1 Gbit/s, 10 Gbit/s über kurze Distanzen (bis 55 m)
- Bandbreite bis 250 MHz
- Strengere Spezifikationen für Nebensprechen und Rückflussdämpfung
- Dickerer Isolationsmantel für bessere Signalqualität

**Kategorie 6a (Cat 6a):**
- Datenübertragung bis 10 Gbit/s über volle 100 Meter
- Bandbreite bis 500 MHz
- Signifikant verbesserte Abschirmung gegen Alien Crosstalk (AXT)
- Oft in F/UTP oder S/FTP Ausführung

**Kategorie 7 (Cat 7):**
- Datenübertragung bis 10 Gbit/s mit Reserven
- Bandbreite bis 600 MHz
- Immer vollständig geschirmt (S/FTP)
- Nicht offiziell in TIA/EIA-Standards, aber in ISO/IEC-Standards definiert
- Verbesserte Kompatibilität mit künftigen Protokollen

**Kategorie 7a (Cat 7a):**
- Datenübertragung bis 10 Gbit/s, Potential für 40 Gbit/s über kurze Strecken
- Bandbreite bis 1000 MHz
- Vollständig geschirmt (S/FTP) mit strengen Spezifikationen

**Kategorie 8 (Cat 8):**
- Datenübertragung bis 40 Gbit/s über bis zu 30 Meter
- Bandbreite bis 2000 MHz
- Für Rechenzentren und Hochleistungsanwendungen optimiert
- Ausgelegt für kurze Strecken mit maximalem Durchsatz
- Verfügbar als Cat 8.1 (RJ45-kompatibel) und Cat 8.2 (mit proprietären Anschlüssen)

Die Wahl der richtigen Kategorie hängt von den aktuellen und zukünftigen Anforderungen des Netzwerks ab, wobei Faktoren wie Übertragungsgeschwindigkeit, Umgebungsbedingungen und Kosten berücksichtigt werden sollten.

### 1.1.4 Stecker & Buchsen

Stecker und Buchsen bilden die Schnittstellen zwischen Twisted-Pair-Kabeln und Netzwerkgeräten. Die korrekte Auswahl und Installation dieser Komponenten ist entscheidend für die Gesamtleistung und Zuverlässigkeit des Netzwerks.

**RJ45-Stecker:**
- Standard-Steckerformat für Twisted-Pair-Ethernet
- 8P8C-Stecker (8 Position, 8 Contact)
- Verfügbar für UTP und geschirmte Versionen (STP)
- Austauschbare Steckerhüllen in verschiedenen Farben zur Kennzeichnung
- Kategorien entsprechend der verwendeten Kabel (Cat 5e, Cat 6, Cat 6a, etc.)

**RJ45-Buchsen:**
- Gegenstück zum RJ45-Stecker
- Eingebaut in Netzwerkgeräte, Patchpanels und Wanddosen
- Ausführungen für Aufputz- und Unterputzmontage
- Farbcodierte Anschlüsse für konsistente Verkabelung
- Automatische oder manuelle Klemm-/Schneidkontakte (LSA oder 110-Block)

**Keystone-Buchsen:**
- Modulare RJ45-Buchsen in standardisiertem Gehäuse
- Passen in Keystone-Rahmen von Patchpanels und Wanddosen
- Ermöglichen flexible Konfiguration von Anschlussfeldern
- Austauschbar bei Aufrüstung oder Defekten
- Erhältlich in verschiedenen Kategorien und Schirmungsvarianten

**Installationswerkzeuge:**
- **Crimpzange:** Zum fachgerechten Anbringen von RJ45-Steckern an Kabel
  * Präzisions-Crimpwerkzeuge mit Ratschenfunktion
  * Spezialeinsätze für verschiedene Steckertypen
  * Kombinierte Werkzeuge mit integrierten Abisolier- und Schneidfunktionen

- **LSA-Auflegewerkzeug:** Zur Installation von Kabeln in LSA-Anschlussleisten
  * Mit Sensor für gleichzeitiges Auflegen und Abschneiden
  * Federkraftunterstützt für optimalen Anpressdruck
  * Austauschbare Klingen für verschiedene Anschlusstypen

- **Kabeltester:** Zur Überprüfung der korrekten Verdrahtung und Kabelqualität
  * Einfache Durchgangsprüfer für Verdrahtung
  * Fortgeschrittene Tester für Parameter wie NEXT, Return Loss
  * Zertifizierungsgeräte für dokumentierte Netzwerkabnahmen

**Verkabelungsstandards:**
- **T568A:** Internationaler Standard nach ISO/IEC
  * Grün/Weiß, Grün, Orange/Weiß, Blau, Blau/Weiß, Orange, Braun/Weiß, Braun
  * Kompatibel mit älteren 1-, 2- und 3-paarigen Systemen

- **T568B:** In Nordamerika weit verbreitet
  * Orange/Weiß, Orange, Grün/Weiß, Blau, Blau/Weiß, Grün, Braun/Weiß, Braun
  * De-facto-Standard in vielen Netzwerken

- **Crossover:** Spezielle Verbindung zwischen gleichartigen Geräten (veraltet)
  * Vertauscht Sende- und Empfangspaar zwischen beiden Enden
  * Meist durch Auto-MDI/X-Funktion moderner Geräte ersetzt

**Wichtige Aspekte bei Installation:**
- Einhaltung des minimalen Biegeradius (typischerweise 4-8x Kabeldurchmesser)
- Vermeidung übermäßiger Zugbelastung während Installation
- Konsistente Verwendung eines Verkabelungsstandards im gesamten Netzwerk
- Beibehaltung der Verdrillung bis maximal 13 mm vor dem Kontaktpunkt
- Korrekte Erdung bei geschirmten Systemen

Die richtige Auswahl und fachgerechte Installation von Steckern und Buchsen ist entscheidend für die Vermeidung von Signalverlusten und die Gewährleistung zuverlässiger Netzwerkverbindungen.

### 1.1.5 Vertrieb

Der Vertrieb von Twisted-Pair-Kabeln erfolgt über verschiedene Kanäle, von Großhändlern bis hin zu Fachhändlern und Online-Shops. Die Verfügbarkeit und Preisgestaltung variieren je nach Kategorie, Schirmung und spezifischen Anforderungen.

**Hersteller und Marken:**
- **Premium-Segment:**
  * Belden: Bekannt für hochwertige, langlebige Kabel mit präzisen Spezifikationen
  * Nexans: Umfassendes Sortiment für verschiedene Anwendungen mit hoher Qualität
  * Leoni: Spezialist für maßgeschneiderte Kabellösungen und industrielle Anwendungen
  * Brand-Rex: Fokus auf Hochleistungskabel für kritische Infrastrukturen

- **Mittelklasse:**
  * Draka: Breites Portfolio mit gutem Preis-Leistungs-Verhältnis
  * Panduit: Bekannt für integrierte Verkabelungssysteme und Zubehör
  * R&M: Schwerpunkt auf strukturierte Verkabelungssysteme
  * AMP/TE Connectivity: Umfangreiches Sortiment an Kabeln und Anschlusskomponenten

- **Basissegment:**
  * Diverse regionale Hersteller
  * Eigenmarken von Großhändlern und Elektronikketten
  * OEM-Produkte ohne Markennamen

**Vertriebswege:**
- **Elektro-Großhandel:**
  * Umfangreiches Sortiment für Elektroinstallateure
  * Meist B2B mit Kundenkonten
  * Mengenrabatte und Projektpreise
  * Beispiele: Sonepar, Rexel, Würth Elektrogroßhandel

- **IT-Distributoren:**
  * Spezialisiert auf Netzwerktechnik und IT-Komponenten
  * Oft technische Beratung und Projektunterstützung
  * Beispiele: Ingram Micro, ALSO, Tech Data

- **Fachhandel für Netzwerktechnik:**
  * Spezialisten mit umfassendem Sortiment und Beratung
  * Installation und Service aus einer Hand
  * Häufig lokale oder regionale Anbieter

- **Online-Händler:**
  * Große Auswahl und Preisvergleichsmöglichkeiten
  * Von spezialisierten Fachhändlern bis zu Generalisten
  * Beispiele: Reichelt, Conrad Electronic, Voelkner, Amazon Business

- **Direktvertrieb der Hersteller:**
  * Vor allem für Großprojekte und spezielle Anforderungen
  * Technische Unterstützung direkt vom Hersteller
  * Oft kombiniert mit Planungs- und Beratungsleistungen

**Kaufkriterien und Preisgestaltung:**
- **Preisgestaltung nach Kategorie:**
  * Cat 5e: ca. 0,30 - 0,80 € pro Meter
  * Cat 6: ca. 0,50 - 1,20 € pro Meter
  * Cat 6a: ca. 0,80 - 2,00 € pro Meter
  * Cat 7/7a: ca. 1,20 - 3,50 € pro Meter
  * Cat 8: ca. 2,50 - 6,00 € pro Meter

- **Preisaufschläge für:**
  * Geschirmte Ausführungen (+20-100%)
  * Halogenfrei/LSZH-Ausführungen (+15-40%)
  * Outdoor-/Erdverlegeausführungen (+50-150%)
  * Sonderfarben und kundenspezifische Ausführungen

- **Lieferformen:**
  * Meterware von der Rolle (typisch 100, 250, 500, 1000m)
  * Konfektionierte Patchkabel in Standardlängen
  * Trommelware für Großprojekte
  * Kleinmengen für Endverbraucher (5-25m)

- **Zertifizierungen und Tests:**
  * Kabel mit unabhängigen Prüfzeugnissen (z.B. GHMT, Delta)
  * Einhaltung internationaler Standards (ISO/IEC, TIA/EIA)
  * CE-Kennzeichnung und CPR-Klassifizierung (Bauproduktenverordnung)
  * Umwelt- und Schadstoffzertifikate (RoHS, REACH)

**Kauf- und Beratungstipps:**
- Auswahl der Kategorie nach aktuellen und zukünftigen Anforderungen (Upgrade-Reserven)
- Berücksichtigung der Umgebungsbedingungen bei der Wahl der Schirmung
- Beachtung der Brandschutzklassen bei Installation in Gebäuden
- Kauf von etwas mehr Material als berechnet (5-10% Reserve)
- Bei kritischen Installationen auf Markenhersteller und geprüfte Qualität setzen
- Bei Großprojekten Musterinstallation und Zertifizierungsmessungen einplanen

Der Kauf von Netzwerkkomponenten sollte stets mit Blick auf die Gesamtkosten (TCO) und nicht nur den Anschaffungspreis erfolgen, da minderwertige Kabel zu erhöhten Ausfallraten und Wartungskosten führen können.

## 1.2 Glasfaserkabel

Glasfaserkabel sind Hightech-Übertragungsmedien, die Licht statt elektrischer Signale zur Datenübertragung nutzen. Sie bestehen aus hauchdünnen Glasfasern, die von mehreren Schutzschichten umgeben sind. Diese Technologie ermöglicht extrem hohe Bandbreiten, große Übertragungsdistanzen und vollständige Immunität gegenüber elektromagnetischen Störungen.

**Kosten:**
- Singlemode-Kabel: 1-3 € pro Meter (Basis-Ausführung)
- Multimode-Kabel: 0,50-2 € pro Meter (Basis-Ausführung)
- Konfektionierte Kabel: 15-100 € je nach Länge und Steckertyp
- Armierte/Outdoor-Varianten: 2-10 € pro Meter

**Material und Aufbau:**
- Kern: Hochreines Quarzglas oder Spezialpolymere
- Mantel: Glas mit niedrigerem Brechungsindex
- Primärcoating: Acrylat-Schutzschicht
- Sekundärschutz: Tight-Buffer oder Loose-Tube-Konstruktion
- Zugentlastungselemente: Aramid-Fasern (Kevlar)
- Außenmantel: PVC, LSZH, PE oder TPU

**Haupttypen:**
1. **Singlemode-Fasern (SMF):**
   - Extrem dünner Kern (8-9 µm)
   - Übertragung nur eines Lichtstrahls (Modus)
   - Typisch gelbe Ummantelung
   - Geringste Dämpfung und höchste Bandbreite
   - Einsatz für Langstrecken (mehrere km bis >100 km)
   - Betrieb mit Laserlicht (typisch 1310 oder 1550 nm)

2. **Multimode-Fasern (MMF):**
   - Größerer Kern (50 oder 62,5 µm)
   - Übertragung mehrerer Lichtstrahlen (Modi)
   - Typisch aqua (OM3/OM4) oder orange (OM1/OM2) Ummantelung
   - Höhere Dämpfung und Modendispersion
   - Einsatz für kürzere Strecken (bis ca. 300-600 m)
   - Betrieb mit LED oder VCSEL (typisch 850 oder 1300 nm)

**OM-Klassifizierung für Multimode:**
- **OM1:** 62,5/125 µm, Bandbreite 200 MHz·km bei 850 nm
- **OM2:** 50/125 µm, Bandbreite 500 MHz·km bei 850 nm
- **OM3:** 50/125 µm, Bandbreite 2000 MHz·km bei 850 nm, laseroptimiert
- **OM4:** 50/125 µm, Bandbreite 4700 MHz·km bei 850 nm, laseroptimiert
- **OM5:** 50/125 µm, für Wellenlängenmultiplex im 850-950 nm Bereich optimiert

**OS-Klassifizierung für Singlemode:**
- **OS1:** Für Innenanwendungen, Dämpfung max. 1,0 dB/km bei 1310 nm
- **OS2:** Für Außen- und Innenanwendungen, Dämpfung max. 0,4 dB/km bei 1310 nm

**Steckertypen:**
- **LC:** Compact-Stecker mit Rasthebel, heute Standard in der IT
- **SC:** Square-Connector mit Push-Pull-Mechanik
- **ST:** Straight-Tip mit Bajonett-Verriegelung (ältere Systeme)
- **FC:** Ferrule-Connector mit Schraubgewinde (Messtechnik)
- **MPO/MTP:** Multifaser-Steckverbindungen für Hochdichte-Anwendungen

**Anwendungsbereiche:**
- Backbone-Verkabelung in Gebäuden und Rechenzentren
- Weitverkehrsnetzwerke (WAN) und Telekommunikation
- Hochgeschwindigkeits-Datenverbindungen (40G, 100G, 400G)
- Industrieumgebungen mit starken EMI-Störfeldern
- Sicherheitskritische Installationen (keine Abstrahlungen)
- Messgeräte- und Sensortechnik

**Vorteile:**
- Extrem hohe Bandbreiten (nahezu unbegrenzt)
- Sehr geringe Dämpfung (lange Strecken ohne Verstärker)
- Komplett immun gegen elektromagnetische Störungen
- Kein Übersprechen zwischen benachbarten Fasern
- Keine Erdungsprobleme, galvanisch getrennt
- Geringes Gewicht und kleiner Durchmesser
- Kein Diebstahlrisiko (kein Metallwert)

**Nachteile:**
- Höhere Kosten für Komponenten und Werkzeuge
- Empfindlicher gegen mechanische Beschädigung
- Spezielles Know-how für Installation erforderlich
- Aufwändigere Steckerinstallation und Spleißen
- Höhere Kosten für aktive Komponenten

**Zertifizierungen:**
- IEC 60793/60794 (internationale Normen)
- TIA-568/TIA-492 (nordamerikanische Standards)
- EN 50173 (europäische Norm)
- ITU-T G.65x-Serie (Telekommunikationsstandards)

Glasfaserkabel sind die zukunftssicherste Verkabelungslösung für moderne Netzwerke und bieten nahezu unbegrenzte Übertragungskapazitäten. Mit der steigenden Nachfrage nach höheren Bandbreiten werden sie zunehmend auch in der horizontalen Verkabelung und in Access-Netzen eingesetzt.

## 1.3 Koaxialkabel

Koaxialkabel sind konzentrisch aufgebaute Kabel mit einem inneren Leiter, einer isolierenden Schicht und einem äußeren Schirmleiter. Diese Struktur ermöglicht die Übertragung hochfrequenter Signale mit minimaler Abstrahlung und geringem Signalverlust. Sie wurden historisch für Ethernet-Netzwerke genutzt und sind heute noch in Kabelfernsehen, Satelliten-TV, Breitband-Internet und HF-Anwendungen verbreitet.

**Aufbau:**
- **Innenleiter:** Massiver oder mehrdrähtiger Kupferleiter, teilweise versilbert
- **Dielektrikum:** Isoliermaterial (PE, PTFE, Luft/PE-Schaum für geringere Dämpfung)
- **Außenleiter/Schirm:** Geflechtschirm aus Kupfer und/oder Aluminiumfolie
- **Mantel:** PVC, PE oder halogenfrei (LSZH) in verschiedenen Farben

**Wichtige Kenngrößen:**
- **Wellenwiderstand:** Typisch 50 Ohm (Datentechnik, Messtechnik) oder 75 Ohm (Video, TV)
- **Dämpfung:** Zunahme mit steigender Frequenz und Länge, wichtig für maximale Strecke
- **Schirmdämpfung:** Maß für die Qualität der Abschirmung gegen Störeinstrahlung
- **Maximale Betriebsfrequenz:** Abhängig vom Kabeltyp, von wenigen MHz bis zu GHz-Bereich

**Gängige Typen:**
1. **RG-58/U:** 
   - 50 Ohm, ca. 5 mm Durchmesser
   - Ehemals für 10BASE2 Ethernet ("Thin Ethernet")
   - Heute für HF-Anwendungen, Funkanlagen
   - Dämpfung ca. 0,5 dB/m bei 100 MHz

2. **RG-59/U:**
   - 75 Ohm, ca. 6 mm Durchmesser
   - Analog-TV, CCTV-Kameras, Kurzstrecken-Video
   - Preisgünstige Basiskabel für einfache Anwendungen
   - Dämpfung ca. 0,3 dB/m bei 100 MHz

3. **RG-6/U:**
   - 75 Ohm, ca. 7 mm Durchmesser
   - Standard für Kabel-TV, Satellitenempfang, digitales Fernsehen
   - Bessere Schirmung und geringere Dämpfung als RG-59
   - Dämpfung ca. 0,2 dB/m bei 100 MHz

4. **RG-11/U:**
   - 75 Ohm, ca. 10 mm Durchmesser
   - Längere Strecken in CATV-Netzen
   - Dickerer Innenleiter für geringere Dämpfung
   - Dämpfung ca. 0,1 dB/m bei 100 MHz

5. **RG-174/U:**
   - 50 Ohm, ca. 2,5 mm Durchmesser
   - Miniaturkabel für mobile Geräte, Messgeräte
   - Sehr flexibel, aber höhere Dämpfung
   - Dämpfung ca. 1,0 dB/m bei 100 MHz

6. **RG-213/U:**
   - 50 Ohm, ca. 10 mm Durchmesser
   - Leistungsfähige HF-Anwendungen, Sendeanlagen
   - Dicke Ausführung für hohe Leistungen
   - Dämpfung ca. 0,1 dB/m bei 100 MHz

**Typische Steckverbinder:**
- **F-Stecker:** Standard für TV- und Satellitenanwendungen (75 Ohm)
- **BNC-Stecker:** Früher für Ethernet und Instrumentierung, heute noch für Video und Messtechnik
- **N-Stecker:** Robuste Hochfrequenzstecker für Leistungsanwendungen
- **SMA/SMB/SMC:** Miniatur-HF-Verbinder für kleinere Geräte

**Anwendungsgebiete:**
- **Kabelfernsehen (CATV):** Verteilung von TV-Signalen über 75 Ohm Koaxialkabel
- **Satellitenempfang:** Verbindung von LNB zur Satellitenempfangsanlage
- **Breitband-Internet:** Kabelmodems nutzen das CATV-Netz für Internetzugang
- **Sicherheitstechnik:** CCTV-Kameras mit analoger Übertragung
- **Funkanwendungen:** Verbindung von Antennen mit Empfängern/Sendern
- **Messtechnik:** Verbindung von HF-Messgeräten und Komponenten

**Netzwerkhistorie:**
- **10BASE5 ("Thick Ethernet"):** Verwendet 0,4" dickes Koaxialkabel mit Vampirklemmen
- **10BASE2 ("Thin Ethernet"):** Verwendet RG-58 mit BNC-T-Stücken und Terminatoren
- Heute in modernen Ethernet-Netzen durch Twisted-Pair ersetzt

**Vorteile:**
- Exzellente Abschirmung vor elektromagnetischen Störungen
- Geringe Dämpfung auch bei höheren Frequenzen
- Bewährte und robuste Technologie
- Keine Probleme mit Übersprechen (im Gegensatz zu Twisted-Pair)

**Nachteile:**
- Höhere Kosten pro Meter im Vergleich zu Twisted-Pair
- Geringere Flexibilität und größerer Biegeradius
- Aufwändigere Installation und Terminierung
- Begrenzte Bandbreite im Vergleich zu Glasfaser

Obwohl Koaxialkabel in modernen LAN-Installationen weitgehend durch Twisted-Pair und Glasfaserkabel ersetzt wurden, behalten sie ihre Bedeutung in spezialisierten Anwendungen aufgrund ihrer ausgezeichneten Abschirmung und guten Hochfrequenzeigenschaften.

## 1.4 Telefonkabel

Telefonkabel sind spezialisierte Leitungen für die Übertragung von Sprach- und Datensignalen in Telekommunikationsnetzen. Ursprünglich für analoge Sprachübertragung entwickelt, werden sie heute auch für DSL-Internet und andere digitale Dienste verwendet. Sie zeichnen sich durch einfachen Aufbau und moderate Übertragungseigenschaften aus.

**Aufbau und Typen:**

1. **Installationskabel (J-Y(St)Y):**
   - Standard für Gebäude-Telefoninstallationen in Deutschland
   - Verdrillte Adernpaare mit gemeinsamer Abschirmung
   - 2-20 Adernpaare, farbcodiert nach DIN-Norm
   - Durchmesser typisch 0,6 mm oder 0,8 mm
   - Charakteristisch für öffentliche Telefonanlagen

2. **Western-Kabel:**
   - 2-4 Adernpaare in flacher oder runder Ausführung
   - Typisch für Endgeräte-Anschlüsse
   - In Deutschland bekannt als UAE-Anschlusskabel
   - Durchmesser typisch 0,4-0,5 mm pro Ader

3. **ISDN-Kabel:**
   - Speziell für ISDN-Anwendungen (2B+D)
   - 2 Adernpaare, kontrollierte Impedanz
   - Verbesserte Übertragungseigenschaften für digitale Signale

4. **DSL-Anschlusskabel:**
   - Optimiert für höherfrequente Übertragung
   - Oft mit zusätzlicher Abschirmung
   - Kompatibel mit RJ11/RJ45-Steckern

**Technische Eigenschaften:**
- Impedanz: ca. 100-120 Ohm (unspezifiziert bei älteren Kabeln)
- Dämpfung: Variiert mit Frequenz und Durchmesser
- Übertragungsleistung: Von einfacher Sprachübertragung (POTS) bis VDSL2
- Maximale Frequenz: Von wenigen kHz (Sprache) bis 30+ MHz (VDSL)

**Anschlusskomponenten:**
- **RJ11:** 6P2C oder 6P4C Stecker für 1-2 Telefonleitungen
- **RJ12:** 6P6C Stecker für bis zu 3 Telefonleitungen
- **RJ45:** 8P8C Stecker für strukturierte Verkabelung, auch für Telefonie
- **TAE-Stecker:** Deutscher Standard für Telefon/Anschluss-Einheiten
  * TAE-F: Für Telefone
  * TAE-N: Für Nebengeräte (Fax, Anrufbeantworter)
  * TAE-NFN: Kombinierte Anschlussdose

**Anwendungsbereiche:**
- Traditionelle Festnetz-Telefonverbindungen
- DSL-Internetanschlüsse über Telefonleitungen
- Hausinterne Telefonanlagen und Nebenstellen
- Einfache Datenübertragung und Türsprechsysteme
- Alarm- und Sicherheitsanlagen

**Vorteile:**
- Kostengünstig und einfach zu installieren
- Weit verbreitete, standardisierte Infrastruktur
- Ausreichende Leistung für viele grundlegende Anwendungen
- Keine spezialisierten Werkzeuge für einfache Installationen nötig

**Nachteile:**
- Begrenzte Bandbreite im Vergleich zu neueren Kabeltypen
- Anfällig für elektromagnetische Störungen
- Begrenzte Reichweite für hochbitratige Dienste
- Wird zunehmend durch Ethernet und Glasfaser ersetzt

**Historische Entwicklung:**
- Ursprünglich ungeschirmte Einzeladern für analoge Telefonie
- Entwicklung zu verdrillten Paaren für verbesserte Störfestigkeit
- Integration von Abschirmungen für höhere Datenraten (DSL)
- Allmähliche Ersetzung durch strukturierte Verkabelung mit Kategorie-Kabeln

Obwohl Telefonkabel in modernen Neubauten zunehmend durch leistungsfähigere strukturierte Verkabelung ersetzt werden, bleibt ihre umfangreiche Installationsbasis für viele Telekommunikationsanwendungen, insbesondere für den "letzten Kilometer" zu Privathaushalten, weiterhin relevant.

## 1.5 Twinaxial Kabel

Twinaxial-Kabel (kurz Twinax) sind Hochleistungs-Kupferkabel, die zwei parallel verlaufende Innenleiter mit gemeinsamer Abschirmung kombinieren. Diese Technologie vereint die Störfestigkeit von Koaxialkabeln mit differentiellen Übertragungseigenschaften und findet vor allem in Hochgeschwindigkeits-Datenübertragungen mit kurzer Reichweite Anwendung.

**Aufbau:**
- Zwei parallele Innenleiter (oft versilbert)
- Isolierung der einzelnen Leiter (typisch PE oder FEP)
- Gemeinsame Abschirmung (Geflecht und/oder Folie)
- Kunststoffmantel (PVC, LSZH oder PUR)
- Typischer Durchmesser: 5-8 mm

**Technische Eigenschaften:**
- Impedanz: Typisch 100, 110 oder 150 Ohm
- Charakteristische Bandbreite: Bis über 10 GHz
- Maximale Geschwindigkeit: Bis 56 Gbit/s je nach Protokoll
- Typische Länge: 0,5 bis 10 Meter (anwendungsabhängig)

**Hauptanwendungen:**

1. **Direct Attach Copper (DAC) Kabel:**
   - Fertig konfektionierte, passive Twinax-Kabel mit integrierten SFP+/QSFP+/QSFP28-Transceivern
   - Kostengünstige Alternative zu optischen Transceivern für kurze Strecken
   - Unterstützt 10G, 25G, 40G, 56G und 100G Ethernet
   - Typisch für Server-zu-Switch und Switch-zu-Switch Verbindungen in Rechenzentren
   - Länge: 0,5 bis 7 Meter (typischerweise max. 5m für 100G)

2. **Active Twinax Cables:**
   - Twinax-Kabel mit integrierter aktiver Signalaufbereitung
   - Erweiterte Reichweite gegenüber passiven DACs
   - Höherer Stromverbrauch, aber niedrigere Kosten als optische Lösungen
   - Länge: bis zu 15-20 Meter für 10G/25G Anwendungen

3. **Spezialisierte Anwendungen:**
   - Ursprünglich für IBM-Systeme (5250 Terminal, AS/400)
   - Hochfrequenz-Messtechnik und Laborausstattung
   - Militärische und Luftfahrt-Anwendungen

**Vorteile:**
- Geringere Kosten als vergleichbare optische Lösungen
- Niedrigere Latenz als optische Transceiver
- Geringerer Stromverbrauch als aktive optische Komponenten
- Hohe Störfestigkeit durch abgeschirmte Konstruktion
- Einfache Plug-and-Play-Installation ohne Reinigung von Fasern

**Nachteile:**
- Stark begrenzte Reichweite (max. ca. 15m bei 10G, weniger bei höheren Raten)
- Höheres Gewicht und größerer Durchmesser als Glasfaser
- Aufwändigere Verlegung bei engen Biegeradien
- Weniger flexibel bei Kabelrouting als strukturierte Verkabelung

**Steckertypen und Interfaces:**
- **SFP+ DAC:** 10 Gbit/s Ethernet, FC, SAS für Server und Switches
- **QSFP+ DAC:** 4x 10 Gbit/s (40G Ethernet) für Hochleistungsverbindungen
- **QSFP28 DAC:** 4x 25 Gbit/s (100G Ethernet) für Datacenter-Backbone
- **QSFP56 DAC:** 4x 56 Gbit/s (200G Ethernet) für neue Hochleistungsnetzwerke
- **IBM Twinax:** Proprietäre Stecker für IBM-Systeme
- **BNC Twinax:** Für Messtechnikanwendungen

**Hersteller und Markttrends:**
- Führende Anbieter: Cisco, Juniper, Mellanox (NVIDIA), Dell, HP, Arista
- Zunehmende Bedeutung in Rechenzentren mit hoher Portdichte
- Wirtschaftliche Alternative für kurze Hochgeschwindigkeitsverbindungen
- Wachsende Nachfrage mit steigendem Bedarf an 25G/40G/100G-Verbindungen
- Übergang zu PAM4-Signalmodulation für höhere Bandbreiten

Twinaxial-Kabel, insbesondere als vorkonfektionierte DAC-Lösungen, bieten eine optimale Balance zwischen Kosten, Leistung und Energieeffizienz für kurze Hochgeschwindigkeitsverbindungen in modernen Rechenzentren und sind eine unverzichtbare Komponente im Mix aus Kupfer- und Glasfaserverkabelung.