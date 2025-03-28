# 3 Computerkabel

Computerkabel sind die physischen Verbindungselemente moderner Informationstechnologie, die den Datenaustausch zwischen Hardware-Komponenten ermöglichen und die Stromversorgung sicherstellen. Diese spezialisierten Leitungen bilden das Nervensystem jeder IT-Infrastruktur und variieren stark in Design, Leistungsfähigkeit und Anwendungsbereichen.

**Historische Entwicklung:**
- 1980er-Jahre: Proprietäre Schnittstellen und parallele Datenübertragung dominieren
- 1990er-Jahre: Einführung standardisierter Schnittstellen (IDE, PS/2, seriell)
- 2000er-Jahre: USB-Revolution und Hochgeschwindigkeitsschnittstellen
- 2010er-Jahre bis heute: Konvergenz zu universellen Anschlüssen und exponentielles Bandbreitenwachstum

**Grundlegende Eigenschaften von Computerkabeln:**
- **Übertragungsarten:** Digital, analog oder gemischt
- **Schnittstellen:** Standardisierte Steckverbindungen zur Interoperabilität
- **Signalintegrität:** Abhängig von Abschirmung, Impedanz und Materialeigenschaften
- **Übertragungsgeschwindigkeit:** Von wenigen Kilobit bis zu mehreren Gigabit pro Sekunde
- **Stromführungsfähigkeit:** Bestimmt die Eignung für Stromversorgung und Geräteladung

**Elektrische Eigenschaften:**
- Leitermaterial (typischerweise Kupfer oder vergoldete Kontakte)
- Schirmung gegen elektromagnetische Interferenzen (EMI)
- Impedanzanpassung für Hochfrequenzübertragung
- Maximale Strombelastbarkeit und Spannungsfestigkeit

**Anwendungsbereiche:**
- Externe Peripherieanbindung (Drucker, Scanner, Speichermedien)
- Interne Komponentenverbindung (Festplatten, Mainboard, Erweiterungskarten)
- Netzwerkintegration (LAN, WLAN)
- Display-Anschlüsse (Monitore, Projektoren, TV-Geräte)
- Spezielle industrielle Anwendungen

## 3.1 USB-Kabel

Universal Serial Bus (USB) ist der meistverbreitete Standard für Computerschnittstellen weltweit und hat seit seiner Einführung 1996 eine kontinuierliche Evolution erfahren. USB-Kabel verbinden Computer mit peripheren Geräten und ermöglichen sowohl Daten- als auch Stromübertragung in einem einheitlichen Format.

**Technische Grundlagen:**
- Serielle Datenübertragungstechnologie
- Host-Controller-Architektur (ein Host steuert mehrere Geräte)
- Differentielles Signaling für höhere Störsicherheit
- Hot-Plug-fähig (Geräteverbindung im laufenden Betrieb)
- Verschiedene Topologie-Unterstützung (Sternförmig, Daisy Chain)

**Versionsgeschichte:**
- USB 1.0/1.1 (1996): 1,5/12 Mbit/s
- USB 2.0 (2000): 480 Mbit/s ("High-Speed")
- USB 3.0/3.1 Gen 1 (2008): 5 Gbit/s ("SuperSpeed")
- USB 3.1 Gen 2 (2013): 10 Gbit/s ("SuperSpeed+")
- USB 3.2 (2017): Bis 20 Gbit/s (multiple Lanes)
- USB4 (2019): Bis 40 Gbit/s (Thunderbolt-3-Protokollkompatibilität)

**Kabelaufbau:**
- Mehrere Leiterpaare (Daten und Stromversorgung)
- Abschirmung gegen Interferenzen
- Unterschiedliche Durchmesser je nach Stromübertragungskapazität
- Farbcodierung entsprechend USB-Spezifikation (meist Blau für 3.0, Gelb für Ladegeräte)
- Standardisierte Steckertypen an beiden Enden

**Stromversorgungsspezifikationen:**
- USB 2.0: 5V / 0,5A (2,5W)
- USB 3.0: 5V / 0,9A (4,5W)
- USB BC 1.2: 5V / 1,5A (7,5W)
- USB-PD (Power Delivery): 5V-20V / bis 5A (100W)

### 3.1.1 USB-A

USB-A bezeichnet den klassischen, flachen rechteckigen USB-Stecker, der seit der ersten USB-Generation verwendet wird. Er ist die am weitesten verbreitete USB-Steckverbindung und dient als Standard-Host-Interface auf Computern, Ladenetzteilen und zahlreichen anderen Geräten.

**Technische Spezifikationen:**
- Abmessungen: ca. 12mm × 4,5mm
- 4 Pins (USB 2.0) oder 9 Pins (USB 3.0 mit zusätzlichen SuperSpeed-Leitungen)
- Nur in einer Orientierung einsteckbar ("nicht-reversibel")
- Mechanische Lebensdauer: ca. 1.500-5.000 Steckzyklen

**USB-A Anschlussbelegung (USB 2.0):**
1. VBUS (+5V)
2. D- (Data minus)
3. D+ (Data plus)
4. GND (Ground)

**USB-A Anschlussbelegung (USB 3.0, zusätzlich):**
5. StdA_SSRX- (SuperSpeed receiver -)
6. StdA_SSRX+ (SuperSpeed receiver +)
7. GND_DRAIN (Ground for signal return)
8. StdA_SSTX- (SuperSpeed transmitter -)
9. StdA_SSTX+ (SuperSpeed transmitter +)

**Vorteile:**
- Höchste Verbreitung und Kompatibilität
- Robuste mechanische Konstruktion
- Unterstützt alle USB-Protokolle bis 3.2 Gen 2

**Nachteile:**
- Nicht rotationssymmetrisch (kann nur in einer Richtung eingesteckt werden)
- Größerer Bauraum erforderlich als modernere Steckertypen
- Geringere mechanische Lebensdauer als USB-C

**Typische Anwendungen:**
- Computer-Hostports
- USB-Hubs und -Dockingstationen
- Festplatten und andere Peripheriegeräte
- Ladenetzteile und Powerbanks

**Bekannte Typen und Varianten:**
- Standard USB-A (alle Versionen)
- USB-A 3.0 (mit blauer Farbmarkierung)
- USB-A 3.1 Gen 2 (manchmal mit roter Farbmarkierung)

### 3.1.2 USB-B

USB-B ist ein quadratischer Steckertyp, der primär für größere Peripheriegeräte wie Drucker, Scanner und externe Speicherlaufwerke entwickelt wurde. Er dient als Device-seitiger Anschluss im klassischen USB-Host/Device-Konzept.

**Technische Spezifikationen:**
- Abmessungen Standard-B: ca. 8mm × 7,5mm
- Abmessungen SuperSpeed-B: ca. 12mm × 10,5mm
- 4 Pins (USB 2.0) oder 9 Pins (USB 3.0 mit zusätzlichen SuperSpeed-Leitungen)
- Robustes Design für häufige Verbindungen/Trennungen
- Mechanische Lebensdauer: ca. 1.500-5.000 Steckzyklen

**USB-B Anschlussbelegung (USB 2.0):**
1. VBUS (+5V)
2. D- (Data minus)
3. D+ (Data plus)
4. GND (Ground)

**USB-B Anschlussbelegung (USB 3.0, zusätzlich):**
5. StdB_SSTX- (SuperSpeed transmitter -)
6. StdB_SSTX+ (SuperSpeed transmitter +)
7. GND_DRAIN (Ground for signal return)
8. StdB_SSRX- (SuperSpeed receiver -)
9. StdB_SSRX+ (SuperSpeed receiver +)

**Varianten:**
- Standard-B: Quadratisch mit abgerundeten Ecken (USB 2.0)
- SuperSpeed-B: Ähnlich Standard-B mit zusätzlichem Rechteck (USB 3.0)
- Mini-B: Kleinere Version für mobile Geräte (veraltet)
- Micro-B: Noch kleinere Version für mobile Geräte (teilweise noch in Verwendung)

**Vorteile:**
- Stabile, robuste Verbindung
- Klare Unterscheidung zwischen Host und Device
- Höhere mechanische Beständigkeit als Micro/Mini-Varianten

**Nachteile:**
- Größere Bauform benötigt mehr Platz
- Geringere Verbreitung als USB-A
- Zunehmend durch USB-C ersetzt

**Typische Anwendungen:**
- Drucker und Scanner
- Externe Festplatten und optische Laufwerke
- Audio-Interfaces
- Industrielle Geräte und Messgeräte

### 3.1.3 USB-C

USB-C ist der modernste und vielseitigste USB-Steckertyp, der eine kompakte, beidseitig steckbare Verbindung ermöglicht. Der 2014 eingeführte Standard hat sich schnell zum universellen Anschluss für zahlreiche Anwendungen von Mobilgeräten bis zu professionellen Workstations entwickelt.

**Technische Spezifikationen:**
- Abmessungen: ca. 8,4mm × 2,6mm
- 24 Pins im symmetrischen Design
- Beidseitig steckbar (180° rotationssymmetrisch)
- Unterstützt USB 2.0, 3.x, USB4 sowie Alternate Modes
- Mechanische Lebensdauer: bis zu 10.000 Steckzyklen

**USB-C Anschlussbelegung (Auswahl wichtiger Pins):**
- A1/B1: GND (Ground)
- A4/B9: VBUS (+5V)
- A6/A7: D+/D- (USB 2.0 Datenleitungen)
- A2/A3/B10/B11: TX/RX Datenpaare (SuperSpeed)
- A8/B8: SBU1/SBU2 (Sideband Use)
- A5/B5: CC1/CC2 (Configuration Channel)

**Fähigkeiten und Modi:**
- USB-Datenkommunikation (2.0 bis USB4)
- USB Power Delivery bis 100W (USB-PD)
- DisplayPort Alternate Mode
- HDMI Alternate Mode
- Thunderbolt 3/4 (auf unterstützter Hardware)
- Audio Accessory Mode

**Vorteile:**
- Universeller Anschluss für Daten, Video, Audio und Stromversorgung
- Kompakte Bauform ideal für dünne Geräte
- Beidseitig steckbar (kein "falsches Herum" mehr)
- Zukunftssicher mit hoher Bandbreite

**Nachteile:**
- Fragmentierte Feature-Unterstützung je nach Gerät und Kabel
- Höhere Komplexität der Elektronik
- Anfälliger für Beschädigungen als größere Stecker
- Kompatibilitätsprobleme mit älteren Standards

**Kabel-Typen und Kennzeichnung:**
- USB 2.0-Kabel mit USB-C-Anschluss (nur USB 2.0-Geschwindigkeit)
- USB 3.2-Kabel mit USB-C-Anschluss (5/10/20 Gbit/s)
- USB4-Kabel mit USB-C-Anschluss (20/40 Gbit/s)
- Thunderbolt 3/4-Kabel mit USB-C-Anschluss (40 Gbit/s)
- Kennzeichnung nach USB-IF-Standard mit Symbolen für Geschwindigkeit und Leistung

**Typische Anwendungen:**
- Smartphones und Tablets (Android, neuer iPad)
- Ultrabooks und moderne Laptops
- Externe Speichermedien der neueren Generation
- Monitore und Docking-Stationen
- Leistungsstarke Lade- und Stromversorgungslösungen

### 3.1.4 USB 3.0

USB 3.0, später auch als USB 3.1 Gen 1 und USB 3.2 Gen 1 bezeichnet, markiert einen bedeutenden Sprung in der USB-Technologie mit deutlich höheren Datenübertragungsraten und verbesserter Stromversorgung gegenüber USB 2.0.

**Technische Spezifikationen:**
- Maximale Datenübertragungsrate: 5 Gbit/s (SuperSpeed)
- Abwärtskompatibel mit USB 2.0/1.1
- Vollduplex-Betrieb (gleichzeitiges Senden und Empfangen)
- Verbesserte Effizienz durch Streaming-Protokoll
- Höhere Strombelastbarkeit: 900 mA (im Vergleich zu 500 mA bei USB 2.0)

**Kabelaufbau:**
- Zwei zusätzliche verdrillte Adernpaare für SuperSpeed-Übertragung
- Verbesserte Abschirmung gegen EMI
- Typische Typkennzeichnung durch blaue Färbung der Anschlüsse
- Maximale empfohlene Kabellänge: ca. 3 Meter (ohne aktive Verstärkung)

**Datenübertragungsprotokoll:**
- 8b/10b-Kodierung (10 Bit übertragen für 8 Bit Daten)
- Asynchrones Protokoll mit Paketbestätigung
- NRZI-Signalisierung (Non-Return-to-Zero Inverted)
- Unterstützung für Streaming-Transfer

**USB 3.0 Anschlüsse:**
- Standard-A: Erweiterter USB-A-Stecker mit zusätzlichen Kontakten
- Standard-B: Erweiterter USB-B-Stecker mit zusätzlichem Bereich
- Micro-B: Erweiterter Micro-USB-Stecker mit zusätzlichem Bereich
- USB-C: Vollständige Unterstützung aller USB 3.0-Funktionen

**Leistungsmerkmale:**
- Theoretische Übertragungsrate: 5 Gbit/s
- Praktische Übertragungsrate: ca. 3,2-4,0 Gbit/s (nach Protokoll-Overhead)
- Energiesparmodi durch Link-Power-Management
- Reduzierte Latenz gegenüber USB 2.0
- Unterstützung von Geräten bis 4,5 Watt (ohne spezielles Ladeprotokoll)

**Verbreitete Anwendungen:**
- Externe Festplatten und SSDs
- Hochgeschwindigkeits-USB-Sticks
- Dockingstationen und USB-Hubs
- Video-Capture-Geräte
- Backupsysteme mit hohem Datendurchsatz

**Kennzeichnung und Erkennung:**
- Typischerweise blaue Anschlüsse und/oder "SS"-Kennzeichnung (SuperSpeed)
- Interoperabilität mit USB 2.0-Geräten bei reduzierter Geschwindigkeit
- USB 3.0-Kabel funktionieren auch als USB 2.0-Kabel
- SS-Logo gemäß USB-IF-Zertifizierungsstandard

### 3.1.5 USB 3.1

USB 3.1, offiziell als USB 3.1 Gen 2 und später als USB 3.2 Gen 2 bezeichnet, bietet gegenüber USB 3.0 eine verdoppelte Datenrate und weitere Verbesserungen beim Energiemanagement und der Protokolleffizienz.

**Technische Spezifikationen:**
- Maximale Datenübertragungsrate: 10 Gbit/s (SuperSpeed+)
- Abwärtskompatibel mit USB 3.0/2.0/1.1
- Verbessertes Energiemanagement
- Effizientere Datencodierung (128b/132b statt 8b/10b)
- Power Delivery 2.0 Unterstützung für bis zu 100W

**Kabelaufbau:**
- Ähnlich wie USB 3.0, jedoch mit höherwertiger Abschirmung und Materialien
- Geringere Toleranzen für Signal-Integrität
- Typische Typkennzeichnung durch rot oder türkisfarbene Anschlüsse
- Maximale empfohlene Kabellänge: ca. 1-2 Meter (ohne aktive Verstärkung)

**Datenübertragungsprotokoll:**
- 128b/132b-Kodierung für höhere Effizienz
- Verbesserte Fehlerkorrektur
- Optimierte Header-Kompression
- Reduzierte Übertragungslatenz

**Besondere Merkmale:**
- USB Type-C Einführung als bevorzugter Anschlusstyp
- Alternativer Modus für nicht-USB-Protokolle (z.B. DisplayPort, HDMI)
- Verbessertes USB Power Delivery für vielseitige Stromversorgung
- Enhanced SuperSpeed (SuperSpeed+) Branding

**Leistungsmerkmale:**
- Theoretische Übertragungsrate: 10 Gbit/s
- Praktische Übertragungsrate: ca. 7,2-8,0 Gbit/s (nach Protokoll-Overhead)
- Verbesserte Energieeffizienz durch optimiertes Link-Power-Management
- Reduzierte CPU-Auslastung durch optimierte Host-Controller

**Verbreitete Anwendungen:**
- Hochleistungs-Speichersysteme
- Videoproduktion und -bearbeitung
- Virtual Reality-Systeme
- Externe GPUs
- Docking-Stationen und Port-Replikatoren für Laptops

**Kennzeichnung und Erkennung:**
- Typischerweise rote oder türkisfarbene Anschlüsse
- "SuperSpeed+" oder "SuperSpeed 10Gbps"-Logo
- USB-IF-Kennzeichnung mit SS10-Logo
- Oft auf USB-C-Anschlüssen zu finden, aber auch als USB-A oder USB-B

### 3.1.6 USB 3.2

USB 3.2 fasst alle vorherigen USB 3.x-Standards zusammen und führt neue Multi-Lane-Betriebsmodi ein, die insbesondere über USB-C-Anschlüsse Datenraten von bis zu 20 Gbit/s ermöglichen.

**Technische Spezifikationen:**
- USB 3.2 Gen 1: 5 Gbit/s (ehemals USB 3.0/USB 3.1 Gen 1)
- USB 3.2 Gen 2: 10 Gbit/s (ehemals USB 3.1 Gen 2)
- USB 3.2 Gen 2×2: 20 Gbit/s (neue Variante mit zwei Daten-Lanes)
- Umfassende Abwärtskompatibilität zu allen vorherigen USB-Standards
- Multi-Lane-Betrieb ausschließlich über USB-C-Anschlüsse

**Kabelaufbau für Gen 2×2:**
- Vier hochwertige Hochgeschwindigkeits-Datenleitungspaare
- Erweiterte Abschirmung für Signalintegrität bei 20 Gbit/s
- Strikte Qualitätsanforderungen für passive Kabel
- Maximale passive Kabellänge: ca. 1 Meter für volle Geschwindigkeit
- Typischerweise höherwertiges Kabeldesign und -materialien

**Datenübertragungsprotokoll:**
- 128b/132b-Kodierung wie bei USB 3.1 Gen 2
- Parallele Datenübertragung über multiple Lanes bei Gen 2×2
- Optimierte Host-Controller-Architektur
- Effizientere Datenstrukturierung für reduzierter Overhead

**Multi-Lane-Operation:**
- Verwendung von zwei TX/RX-Paaren für parallele Datenübertragung
- Nur über USB-C möglich (Unterstützung für mehr als ein Highspeed-Leitungspaar)
- Erfordert spezielle Kabel, die als "USB 3.2 Gen 2×2-tauglich" zertifiziert sind
- Kabelqualität ist kritisch für zuverlässige Leistung

**Leistungsmerkmale:**
- Gen 1: 5 Gbit/s (effektiv ca. 4 Gbit/s)
- Gen 2: 10 Gbit/s (effektiv ca. 8 Gbit/s)
- Gen 2×2: 20 Gbit/s (effektiv ca. 16 Gbit/s)
- Verbesserte Powermanagement-Funktionen
- Optimierte Protokolleffizienz für höhere Leistung

**Verbreitete Anwendungen:**
- Externe NVMe-SSDs mit hoher Geschwindigkeit
- Videoproduktionssysteme
- Virtuelle Realität und Augmented Reality
- Grafikintensive Arbeitsstationen
- Multi-Display-Dockingstationen

**Kennzeichnung und Branding:**
- USB 3.2 Gen 1: "SuperSpeed USB 5Gbps"
- USB 3.2 Gen 2: "SuperSpeed USB 10Gbps"
- USB 3.2 Gen 2×2: "SuperSpeed USB 20Gbps"
- Komplexe und oft verwirrende Nomenklatur mit häufigen Änderungen
- Meist auf USB-IF-zertifizierten Produkten zu finden

## 3.2 Thunderbolt-Kabel

Thunderbolt ist eine Hochleistungs-Schnittstellentechnologie, die ursprünglich von Intel und Apple entwickelt wurde. Sie kombiniert PCI Express und DisplayPort in einem seriellen Signalpfad und bietet im Vergleich zu Standard-USB-Verbindungen deutlich höhere Bandbreiten für professionelle Anwendungen.

**Technische Grundlagen:**
- Kombination aus DisplayPort und PCI Express
- Hohe Datenraten für Video- und Datenübertragung
- Unterstützung für Daisy-Chaining mehrerer Geräte
- Protokoll für PCIe-Tunneling über ein externes Kabel
- In neueren Versionen (TB3/4) mit USB-C-Anschlüssen kompatibel

**Versionsgeschichte:**
- Thunderbolt 1 (2011): 10 Gbit/s pro Kanal (2 Kanäle, bidirektional)
- Thunderbolt 2 (2013): 20 Gbit/s durch Kanalbündelung
- Thunderbolt 3 (2015): 40 Gbit/s über USB-C-Anschluss
- Thunderbolt 4 (2020): 40 Gbit/s mit erweiterten Mindestspezifikationen

**Kabelkonstruktion:**
- **Thunderbolt 1/2:**
  * Mini-DisplayPort-Anschluss
  * Aktive Kupferkabel für Längen bis 3m
  * Optische Kabel für Längen bis 60m
  * Controller-Chips in beiden Kabelenden

- **Thunderbolt 3/4:**
  * USB-C-Anschluss
  * Passive Kupferkabel bis 0,8m (40 Gbit/s)
  * Aktive Kupferkabel bis 2m (40 Gbit/s)
  * Aktive optische Kabel bis 50m

**Technische Spezifikationen (Thunderbolt 4):**
- 40 Gbit/s bidirektionale Bandbreite
- PCIe 3.0 x4 (32 Gbit/s)
- DisplayPort 1.4 (HBR3)
- USB4 Kompatibilität
- USB-PD Unterstützung bis 100W
- Wake-from-Sleep Unterstützung für angeschlossene Geräte
- Mindestanforderung: Zwei 4K-Displays oder ein 8K-Display

**Anwendungsbereiche:**
- Professionelle Videoproduktion und -bearbeitung
- High-End-Audiointerfaces und Musikproduktion
- Externe Grafikkarten (eGPU)
- Hochleistungs-Speichersysteme und RAID-Arrays
- Docking-Stationen mit umfangreicher Peripherie-Unterstützung

**Vorteile:**
- Extrem hohe Bandbreite für anspruchsvolle Anwendungen
- Kombinierte Video- und Datenübertragung
- Daisy-Chain-Fähigkeit (bis zu 6 Geräte)
- Geringere Latenz als viele andere Schnittstellen
- Direkte PCIe-Anbindung für höchste Leistung

**Nachteile:**
- Höhere Kosten als Standard-USB
- Begrenzte Kabellängen bei passiven Kupferkabeln
- Aktive Kabel deutlich teurer
- Stromverbrauch der Controller-Chips
- Nicht alle USB-C-Ports unterstützen Thunderbolt

**Kompatibilität:**
- Thunderbolt 3/4-Geräte funktionieren an USB-C-Ports (mit eingeschränkter Funktionalität)
- USB-C-Geräte funktionieren an Thunderbolt-Ports
- Thunderbolt 4 ist abwärtskompatibel zu Thunderbolt 3
- Adapter für Thunderbolt 1/2 auf Thunderbolt 3/4 verfügbar

**Erkennungsmerkmale:**
- Thunderbolt-Blitzsymbol auf Anschlüssen und Kabeln
- Zertifizierung durch Intel
- Typische Preise: 25-80€ für kurze passive Kabel, 60-200€ für aktive Kabel

## 3.3 FireWire-Kabel

FireWire (IEEE 1394) ist ein serieller Hochgeschwindigkeits-Datenübertragungsstandard, der in den 1990er Jahren von Apple entwickelt wurde. Er war einer der ersten Standards, der hohe Datenraten mit Echtzeitfähigkeit und direktem Speicherzugriff kombinierte, was ihn besonders für Audio- und Videoanwendungen wertvoll machte.

**Technische Grundlagen:**
- Serielle Bus-Technologie mit Punkt-zu-Punkt-Verbindungen
- Isochroner Datentransfer für zeitkritische Anwendungen
- Peer-to-Peer-Kommunikation ohne zentralen Host
- Hot-Plug-fähig mit automatischer Konfiguration
- Direkte Speicherzugriffe (DMA) für hohe Effizienz

**Versionsgeschichte:**
- FireWire 400 (IEEE 1394-1995): 400 Mbit/s
- FireWire 800 (IEEE 1394b-2002): 800 Mbit/s
- FireWire S1600 (IEEE 1394-2008): 1,6 Gbit/s (selten implementiert)
- FireWire S3200 (IEEE 1394-2008): 3,2 Gbit/s (selten implementiert)

**Steckervarianten:**
- 4-Pin: Standard-FireWire ohne Stromversorgung (typisch für Kleingeräte)
- 6-Pin: Standard-FireWire mit Stromversorgung (bis zu 30V, 1,5A)
- 9-Pin: FireWire 800 mit höherer Bandbreite
- Beta-Anschluss: Kleinere Form für mobile Geräte (selten)

**Kabelkonstruktion:**
- Verdrillte Adernpaare mit mehrstufiger Abschirmung
- 28-22 AWG Leiterstärke je nach Anwendung und Länge
- Typische maximale Kabellänge: 4,5 Meter
- Spezialkabel mit Signalverstärkern für längere Strecken bis 100m
- Feuerfestes PVC oder TPE als Außenmantel

**Pinbelegung (6-Pin):**
1. Power (ungeregelt, 8-30V DC)
2. Ground
3. TPB- (Twisted Pair B minus)
4. TPB+ (Twisted Pair B plus)
5. TPA- (Twisted Pair A minus)
6. TPA+ (Twisted Pair A plus)

**Anwendungsbereiche:**
- Professionelle Audio-/Videogeräte
- Digitale Camcorder und Videokameras
- Externe Festplatten (vor der USB 3.0-Ära)
- Audiointerfaces für Musikproduktion
- Industrielle Bildverarbeitungssysteme
- Medizintechnische Geräte

**Vorteile:**
- Isochroner Datentransfer für zeitkritische Anwendungen
- Höhere Bandbreite als USB 2.0
- Kein Host-Controller erforderlich (Peer-to-Peer)
- Stromversorgung für Peripheriegeräte (bei 6-Pin)
- Robuste Verbindungen mit hoher Störsicherheit

**Nachteile:**
- Durch USB 3.0/3.1 und Thunderbolt weitgehend ersetzt
- Wenige moderne Geräte unterstützen noch FireWire
- Höhere Kosten als USB-Kabel
- Abnehmende Verfügbarkeit von Hardware und Zubehör

**Marktsituation:**
- Seit ca. 2015 stark rückläufige Bedeutung
- Noch relevant in Legacy-Systemen und Spezialanwendungen
- Für professionelle Audiolösungen teilweise noch im Einsatz
- Meist über Adapter an modernen Computern angeschlossen

**Typische Preisklassen:**
- Standard-FireWire 400 Kabel: 8-15€
- FireWire 800 Kabel: 12-25€
- Adapter auf USB oder Thunderbolt: 15-40€
- Spezialkabel für Audiotechnik: 20-80€

## 3.4 PS/2-Kabel

PS/2 (Personal System/2) ist ein Schnittstellenstandard für die Verbindung von Tastaturen und Mäusen, der 1987 von IBM mit der gleichnamigen Computerserie eingeführt wurde. Trotz weitgehender Ablösung durch USB ist PS/2 in bestimmten Bereichen aufgrund seiner direkten Hardwareanbindung und Interrupt-Steuerung noch immer relevant.

**Technische Grundlagen:**
- Synchrone serielle Schnittstelle
- Hardware-Interrupt-gesteuert (keine Polling-Latenz)
- Dedizierte Anschlüsse für Tastatur und Maus
- Mini-DIN-6-Steckverbindung mit mechanischer Verriegelung
- Keine Hot-Plug-Fähigkeit (Geräteanschluss im ausgeschalteten Zustand)

**Kabelaufbau:**
- 4-6 Einzeladern (je nach Implementierung)
- Kernaufbau meist ungeschirmt
- Außendurchmesser typischerweise 4-5 mm
- Maximale praktische Kabellänge: ca. 3 Meter
- Typischerweise mit Mini-DIN-6-Stecker und gerätespezifischem Stecker

**Farbkodierung:**
- Lila: Tastatur (standardisierte IBM-Farbkennzeichnung)
- Grün: Maus (standardisierte IBM-Farbkennzeichnung)
- Mechanische Codierung verhindert falsches Einstecken

**Pinbelegung (Mini-DIN-6):**
1. Datensignal
2. Nicht belegt
3. Ground (Masse)
4. Vcc (+5V)
5. Taktsignal
6. Nicht belegt

**Anwendungsbereiche:**
- Legacy-Computer und -Systeme
- Gaming-PCs (wegen N-Key-Rollover und geringerer Latenz)
- BIOS-Konfiguration und System-Recovery
- Industrielle Steuerungssysteme
- Systeme mit hohen Sicherheitsanforderungen

**Übertragungsprotokoll:**
- 8 Datenbits, 1 Startbit, 1 Paritätsbit, 1 Stoppbit
- Taktrate: 10-16,7 kHz
- Data wird nur bei Low-Takt übertragen
- Datenrichtung ist bidirektional (PC zu Gerät und umgekehrt)

**Vorteile:**
- Keine Treiberabhängigkeit (direkter Hardware-Zugriff)
- Funktioniert zuverlässig in BIOS/UEFI ohne Betriebssystem
- Geringere Latenz als USB-HID
- Dedizierte Anschlüsse vermeiden Ressourcenkonflikte
- Absolute Priorität für Tastatureingaben durch Hardware-Interrupts

**Nachteile:**
- Keine Hot-Plug-Fähigkeit
- Begrenzte Kabellänge
- Anfälligkeit für Schäden an den Pins bei unsachgemäßer Handhabung
- Keine Stromversorgung für komplexere Geräte
- Keine standardisierte Erweiterbarkeit wie USB

**Marktsituation:**
- Seit ca. 2005 rückläufige Bedeutung, aber nicht vollständig verschwunden
- Oft per Adapter an moderne Systeme angeschlossen
- Noch relevant im High-End-Gaming und industriellen Bereich
- Zunehmend auf Mainboards durch USB ersetzt

**Typische Preisklassen:**
- Standard-PS/2-Verlängerungskabel: 5-10€
- PS/2-zu-USB-Adapter: 3-15€
- PS/2-Splitter (Y-Adapter): 5-12€

## 3.5 SATA-Kabel

Serial ATA (SATA) ist der dominierende Standard für die Verbindung von Festplatten, SSDs und optischen Laufwerken mit dem Motherboard in modernen Computern. Diese flachen, schlanken Kabel ersetzten ab 2003 zunehmend die älteren, breiten IDE/PATA-Kabel und bieten höhere Datenübertragungsraten bei einfacherem Anschluss.

**Technische Grundlagen:**
- Serielle Punkt-zu-Punkt-Verbindung
- 7-poliger Stecker mit L-förmiger Kodierung
- Hot-Plug-fähig (in den meisten Konfigurationen)
- Getrennte Daten- und Stromversorgungsanschlüsse
- AHCI (Advanced Host Controller Interface) als Standard-Protokoll

**Versionsgeschichte:**
- SATA 1.0 (2003): 1,5 Gbit/s (150 MB/s)
- SATA 2.0 (2004): 3 Gbit/s (300 MB/s)
- SATA 3.0 (2008): 6 Gbit/s (600 MB/s)
- SATA 3.2 (2013): SATA Express, einige Erweiterungen, aber weiter 6 Gbit/s

**Kabelkonstruktion:**
- Flaches oder rundes Design 
- 7 Leiter für Datenübertragung
- Kabelbreite: ca. 7-12 mm
- Standardlängen: 30 cm, 45 cm, 60 cm, 100 cm
- Maximale spezifizierte Kabellänge: 1 Meter

**Steckervarianten:**
- Standard-SATA: Gerades Anschlussdesign
- SATA mit 90°-Winkel: Für beengte Platzverhältnisse
- eSATA: Robustere Version für externe Anwendungen
- Mini-SATA (mSATA): Für kleine Formfaktoren (veraltet)
- Micro-SATA: Für 1,8"-Laufwerke (selten)

**Pinbelegung (7-polig):**
1. GND (Ground)
2. A+ (Differentielles Signalpaar A, positiv)
3. A- (Differentielles Signalpaar A, negativ)
4. GND (Ground)
5. B- (Differentielles Signalpaar B, negativ)
6. B+ (Differentielles Signalpaar B, positiv)
7. GND (Ground)

**Spezielle Varianten:**
- SATA-Kabel mit Verriegelung für sicheren Halt
- Abgewinkelte Stecker für beengte Räume
- SATA-Splitter für mehrere Laufwerke (nur für Stromversorgung)
- SATA-Stromadapter (Molex zu SATA)
- RAID-optimierte SATA-Kabel mit verbesserter Abschirmung

**Anwendungsbereiche:**
- Festplatten (HDDs)
- Solid State Drives (SSDs)
- Optische Laufwerke (CD/DVD/Blu-ray)
- Interne Kartenleser
- Einige spezialisierte Erweiterungskarten

**Vorteile:**
- Schlankes Design verbessert Luftstrom im Gehäuse
- Einfache Steckverbindungen ohne Jumper-Konfiguration
- Hot-Swap-Fähigkeit
- Ausreichende Bandbreite für die meisten Speicheranwendungen
- Weit verbreiteter, kostengünstiger Standard

**Nachteile:**
- Bandbreitenlimitierung bei 6 Gbit/s
- Bei moderner NVMe-SSDs Leistungsengpass
- Fragile Stecker können bei häufigem Wechsel beschädigt werden
- Keine Weiterentwicklung über SATA 3.0 hinaus

**Typische Preisklassen:**
- Standard-SATA-Kabel: 2-5€
- Premium-SATA-Kabel mit Verriegelung: 5-10€
- SATA-Kabelsätze (3-6 Stück): 8-15€
- Spezial-SATA-Kabel (abgewinkelt, extra lang): 5-12€

## 3.6 eSATA-Kabel

External SATA (eSATA) wurde entwickelt, um die Vorteile der SATA-Schnittstelle auf externe Speichergeräte zu übertragen. Anders als USB bietet eSATA die gleiche native Bandbreite wie interne SATA-Verbindungen und vermeidet die Protokollumwandlung und damit verbundene Leistungseinbußen.

**Technische Grundlagen:**
- Externe Variante des SATA-Standards
- Identisches Protokoll wie interne SATA-Verbindungen
- Verstärkte, robustere Steckverbindung für externe Anwendungen
- Hot-Plug-fähig wie interne SATA
- Keine Stromversorgung über Datenkabel (separates Netzteil nötig)

**Versionsgeschichte:**
- eSATA (2004): Parallel zur SATA 2.0-Spezifikation, 3 Gbit/s
- eSATAp (Power over eSATA): Kombiniert eSATA mit USB und Stromversorgung
- eSATA 6Gbps: Parallel zu SATA 3.0, 6 Gbit/s

**Kabelkonstruktion:**
- Verstärkte Außenhülle für höhere Widerstandsfähigkeit
- Verbesserte Abschirmung gegen externe Störquellen
- Längere maximale Kabellänge: bis zu 2 Meter (doppelt so lang wie internes SATA)
- Verbesserter Stecker mit stabilerer Verankerung
- Höhere Steckzyklen-Festigkeit (bis zu 5000 Zyklen)

**Steckervarianten:**
- Standard-eSATA: 7-polig wie SATA, aber robusteres Gehäuse
- eSATAp (auch bekannt als Power eSATA, eSATA/USB Combo): Kombinierter Anschluss mit USB und Stromversorgung

**Pinbelegung (7-polig, identisch zu SATA):**
1. GND (Ground)
2. A+ (Differentielles Signalpaar A, positiv)
3. A- (Differentielles Signalpaar A, negativ)
4. GND (Ground)
5. B- (Differentielles Signalpaar B, negativ)
6. B+ (Differentielles Signalpaar B, positiv)
7. GND (Ground)

**Anwendungsbereiche:**
- Externe Festplatten mit hoher Performance
- Externe SSD-Laufwerke
- Externe RAID-Systeme und NAS-Geräte
- Professionelle Backup-Lösungen
- Externe Boot-Laufwerke

**Leistungsmerkmale:**
- Gleiche Bandbreite wie interne SATA (bis 6 Gbit/s)
- Deutlich geringere CPU-Last im Vergleich zu USB 2.0
- Keine Protokollkonvertierung notwendig
- Native AHCI-Unterstützung für alle SATA-Features
- Geringere Latenz als bei USB oder FireWire

**Vorteile:**
- Hohe Performance ohne Protokoll-Overhead
- Direkte Anbindung ans SATA-Subsystem
- Vollständige SATA-Funktionalität (NCQ, TRIM, etc.)
- Höhere Zuverlässigkeit bei Dauerbelastung als USB
- Längere maximale Kabellänge als internes SATA

**Nachteile:**
- Keine Stromversorgung über Standardkabel
- Begrenzte Verbreitung und Akzeptanz
- Weitgehend durch USB 3.0/3.1 und Thunderbolt ersetzt
- Spezielle Treiber manchmal erforderlich
- Nicht so universell einsetzbar wie USB

**Marktsituation:**
- Seit ca. 2012 stark rückläufige Bedeutung
- In neuen Geräten kaum noch implementiert
- Nischenprodukt für spezifische Anwendungen
- Weitgehend durch USB 3.0+ und Thunderbolt abgelöst

**Typische Preisklassen:**
- Standard-eSATA-Kabel: 5-15€
- Premium-eSATA-Kabel: 10-25€
- eSATA-Adapterkabel: 8-20€
- eSATA PCIe-Erweiterungskarten: 15-40€

## 3.7 IDE-Kabel

IDE-Kabel (Integrated Drive Electronics), auch als PATA (Parallel ATA) bekannt, waren über viele Jahre der Standard für die Verbindung von Festplatten, optischen Laufwerken und anderen Speichermedien mit dem Computer-Motherboard, bevor sie durch SATA abgelöst wurden.

**Technische Grundlagen:**
- Parallele Datenübertragung über breites Flachbandkabel
- Typischerweise 40- oder 80-polige Anschlüsse
- Master/Slave-Konfiguration mit Jumpern
- Zwei Geräte pro Kanal (Primary/Secondary)
- Kein Hot-Plugging (nur Cold-Swap möglich)

**Versionsgeschichte:**
- ATA-1 (1994): bis zu 8,3 MB/s (PIO Mode 0-2, DMA Mode 0-2)
- ATA-2/EIDE (1996): bis zu 16,6 MB/s (PIO Mode 3-4)
- ATA-3 (1997): Verbesserungen ohne Geschwindigkeitserhöhung
- ATA/ATAPI-4 (UDMA/33, 1998): bis zu 33 MB/s
- ATA/ATAPI-5 (UDMA/66, 1999): bis zu 66 MB/s
- ATA/ATAPI-6 (UDMA/100, 2000): bis zu 100 MB/s
- ATA/ATAPI-7 (UDMA/133, 2002): bis zu 133 MB/s

**Kabelkonstruktion:**
- Flachbandkabel mit parallelen Leiterbahnen
- 40-polig für ältere IDE (ATA-33)
- 80-polig für neuere IDE (ATA-66/100/133) mit zusätzlichen Masseleitern
- Typische Breite: ca. 5 cm
- Maximale empfohlene Länge: 45 cm (18 Zoll)
- Farbkodierte Anschlüsse und Markierung für Pin 1

**Steckeranordnung:**
- Motherboard-Anschluss (typisch schwarz)
- Master-Geräteanschluss (typisch grau/schwarz)
- Slave-Geräteanschluss (typisch blau/grau)
- Kerbung zur Verhinderung falscher Steckverbindung
- Zusätzlicher "Twist" in einigen Kabeln für Cable-Select-Funktionalität

**Pinbelegung (ausgewählte wichtige Pins):**
- Pins 1-2: Resetleitung
- Pins 3-18, 20-24, 27-38: Datenleitungen und Adressbus
- Pin 19: Ground
- Pin 25: nicht belegt
- Pin 26: +5V
- Pins 39-40: Aktivitätsanzeige (-/+)

**Anwendungsbereiche (historisch):**
- 3,5" und 5,25" Festplatten
- CD/DVD/Blu-ray-Laufwerke
- Zip-Laufwerke und andere Wechselmedien
- Bandlaufwerke und andere Backup-Medien
- Einige ältere Flash-basierende Speichergeräte

**Leistungsmerkmale:**
- Maximale Bandbreite: 133 MB/s (UDMA/133)
- Bus-Sharing zwischen zwei Geräten (Master/Slave)
- PIO- und DMA-Übertragungsmodi
- 8- oder 16-Bit-Datenübertragung
- CRC-Fehlerprüfung bei neueren Standards

**Vorteile (historisch):**
- Zuverlässig und robust
- Weit verbreitet und standardisiert
- Einfache Fehlerdiagnose
- Kompatibilität mit älterer Hardware
- Niedrige Kosten

**Nachteile:**
- Breite Kabel behindern Luftstrom im Gehäuse
- Begrenzte Bandbreite (max. 133 MB/s)
- Komplexe Jumper-Konfiguration erforderlich
- Master/Slave-Konflikte möglich
- Keine Hot-Swap-Fähigkeit

**Marktsituation:**
- Seit ca. 2006-2008 nahezu vollständig durch SATA ersetzt
- Nur noch für Legacy-Systeme und Vintage-Computing relevant
- Abnehmende Verfügbarkeit von Neuware
- Bedeutung für historische Computer und Datenrettung
- Adapter zu SATA verfügbar für Übergangslösungen

**Typische Preisklassen heute:**
- Standard-IDE-Kabel (40-polig): 3-8€
- 80-polig Ultra-ATA-Kabel: 5-12€
- IDE-zu-SATA-Adapter: 8-20€
- IDE-Controller-Karten: 15-40€

## 3.8 Flachbandkabel

Flachbandkabel, auch als Ribbon-Kabel bekannt, sind flexible Verbindungselemente mit einer Vielzahl parallel verlaufender Leiter in einer flachen, bandartigen Anordnung. Sie werden in verschiedenen internen Computerkomponenten und elektronischen Geräten eingesetzt, wo mehrere Signale gleichzeitig übertragen werden müssen.

**Technische Grundlagen:**
- Parallele Anordnung mehrerer isolierter Leiter
- Standardisierte Abstände zwischen den Leitern (typisch 1,27 mm oder 2,54 mm)
- Flexible Konstruktion für einfache Verlegung
- IDC-Anschlusstechnik (Insulation Displacement Connector)
- Viele verschiedene Steckervarianten und Pin-Konfigurationen

**Gängige Varianten:**
- 10-polig bis 64-polig (typische Computerkabel)
- Farbcodierte erste Ader (typischerweise rot oder blau)
- Verschiedene Breiten je nach Anzahl der Leitungen
- Mit oder ohne Abschirmung
- Standard- oder Twisted-Pair-Ausführungen

**Kabelkonstruktion:**
- Parallele Kupferleiter (üblicherweise 28-30 AWG)
- PVC oder anderes flexibles Isolationsmaterial
- Graue oder regenbogenfarbene Farbcodierung
- Typische Breite: zwischen 12 mm (10-polig) und 82 mm (64-polig)
- Isolationswiderstand: typisch >1000 MΩ
- Zugfestigkeit: ca. 10N pro Kontakt

**Anwendungen in Computern:**
- **Floppy-Laufwerk-Kabel:** 34-polig mit Twist für Laufwerksauswahl
- **IDE/PATA-Kabel:** 40-polig oder 80-polig (mit Masseleitungen)
- **SCSI-Kabel:** 50-, 68- oder 80-polig
- **Frontpanel-Anschlüsse:** Verschiedene kleine Flachbandkabel für Power/Reset/LED
- **Bordinterne Erweiterungen:** USB-Header, Audio-Header etc.

**Steckertypen:**
- IDC-Stecker (Insulation Displacement Connector)
- DIP-Header-Stecker
- Card-Edge-Connector
- D-Sub-Stecker (bei Adapter-Konfigurationen)
- BERG/Mini-Stecker (für Floppy-Anschlüsse)

**Besondere Ausführungen:**
- **Twisted-Pair-Flachbandkabel:** Verdrillung bestimmter Leitungspaare zur Störungsminimierung
- **Abgeschirmte Flachbandkabel:** Mit Folienschirmung gegen EMI
- **High-Temp-Ausführungen:** Für erhöhte Temperaturbereiche bis 125°C
- **Hochflexible Ausführungen:** Für bewegliche Anwendungen mit erhöhter Biegefestigkeit
- **Low-Smoke-Zero-Halogen:** Für erhöhte Sicherheitsanforderungen

**Vorteile:**
- Kostengünstige Herstellung
- Einfache Massenproduktion
- Gleichmäßige elektrische Eigenschaften
- Platzsparend bei vielen parallelen Verbindungen
- Einfache Identifikation durch Farbcodierung
- Gute Flexibilität in einer Ebene

**Nachteile:**
- Empfindlich gegen Störeinstrahlung (bei ungeschirmten Typen)
- Signalübersprechen zwischen benachbarten Leitungen
- Begrenzte Einsatzmöglichkeiten bei hohen Frequenzen
- Nicht für Power-Anwendungen geeignet
- Behindern Luftstrom in engen Gehäusen

**Marktsituation:**
- Abnehmende Bedeutung in modernen Computern
- Ersetzung durch serielle Schnittstellen mit weniger Leitern
- Weiterhin relevant in eingebetteten Systemen und Industrieanwendungen
- Wichtig für Reparatur und Restaurierung älterer Computer
- Standardbauteil in der Elektronikentwicklung und Prototyping

**Typische Preisklassen:**
- Standard-Flachbandkabel (40-polig, 50 cm): 3-8€
- Floppy-Kabel (34-polig mit Twist): 3-7€
- IDE-Kabel (40/80-polig): 4-10€
- Angepasste/Spezial-Flachbandkabel: 5-20€