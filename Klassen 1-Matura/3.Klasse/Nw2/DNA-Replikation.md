[[3.Nw2]]
___
![[1.5 DNA-Replikation.pdf]]
## Grundlegende Schwierigkeiten

Damit sich eine Zelle selbst verdoppeln kann, muss sie vorher ihre gesamte DNA verdoppeln (replizieren). Dabei treten folgende Schwierigkeiten auf:

1. Die Synthese muss **fehlerfrei** ablaufen
2. Die Syntheserichtung ist immer **5'→3'** (aufgrund der DNA-Polymerase)
3. Die Verknüpfung wird durch die DNA-Polymerase katalysiert. Diese braucht einen Strang, an dem sie ansetzen und weiterbauen kann

## Form eines DNA-Doppelstrangs

Die beiden Stränge bilden eine Doppelhelix

>[!info]
>Video zur Visualisierung: https://youtu.be/WFCvkkDSfIU?t=178

![[DNA-Doppelhelix.png]]
*Von Zephyris, CC BY-SA 3.0, https://commons.wikimedia.org/w/index.php?curid=2118354*

## 1) Die Synthese muss fehlerfrei ablaufen

Für eine fehlerfreie Kopie sind die komplementären Basenpaarungen entscheidend:

- **Falsche Nucleotide** passen nicht und werden nicht angeknüpft
- **Richtige Nucleotide** passen und werden angeknüpft

Die Basenpaarungen erfolgen nach dem Prinzip:
- A paart sich mit T
- G paart sich mit C

## 2) Die Syntheserichtung ist immer 5'→3'

- Die DNA-abhängige DNA-Polymerase kann die Stränge nur in 5'→3' Richtung bauen
- Die DNA wird in eine Richtung entspiralisiert und geöffnet
- Ein Strang wird in Öffnungsrichtung gebaut (keine Schwierigkeiten)
- Der andere Strang kann nur gegen die Öffnungsrichtung synthetisiert werden (Problem)

### Leitstrang (Leading Strand)

- Wird kontinuierlich in Öffnungsrichtung gebaut (5'→3')
- Kann einfach verlängert werden, während die DNA weiter geöffnet wird
- Durchgängige Synthese

### Folgestrang (Lagging Strand)

- Kann nicht durchgängig gebaut werden, da die Baurichtung immer 5'→3' ist
- Müsste in 3'→5' Richtung weitergehen, was nicht möglich ist
- Wird daher stückweise in entgegengesetzter Richtung gebaut
- Diese Stücke nennt man **Okazaki-Fragmente**
- Die Okazaki-Fragmente werden später verbunden, um einen durchgängigen DNA-Strang zu erhalten

## 3) DNA-abhängige DNA-Polymerase

Neben der 5'→3' Richtungsbeschränkung benötigt die DNA-Polymerase einen Startpunkt:

- **Primer**: Start-Stück, an dem die Polymerase ansetzt (besteht aus RNA)
- Der Primer wird von der **Primase** hergestellt
- Die RNA-Primer werden am Schluss wieder durch DNA ersetzt (von der **Exonuklease**)

## Semikonservative Synthese

- Jeder der beiden neuen Doppelstränge besteht aus einem neuen und einem alten Einzelstrang
- Man spricht daher von einer **semikonservativen Synthese**

>[!info]
>Animationen zur Replikation in Zellen:
>- https://youtu.be/TNKWgcFPHqw?t=11
>- Realistisches Video: https://www.youtube.com/watch?v=6j8CV3droDw

## Polymerase-Kettenreaktion (PCR)

PCR ist ein Verfahren zur Vervielfältigung von DNA im Labor:

- Anstatt durch Helikasen wird der Doppelstrang durch **Hitze (95°C)** aufgeteilt
- Problem: Menschliche Polymerase kann bei so hohen Temperaturen nicht arbeiten
- Lösung: Verwendung der **Taq-Polymerase** aus dem thermophilen Bakterium *Thermus aquaticus*

### Nutzen der Primer-Notwendigkeit

Die Tatsache, dass die Polymerase einen Primer benötigt, lässt sich vorteilhaft nutzen:
- Man kann gezielt Primer herstellen, die zum Anfang eines bestimmten DNA-Bereichs passen
- So lassen sich spezifische DNA-Abschnitte gezielt vervielfältigen

### Genetischer Fingerabdruck

- Es werden etwa 8 bis 15 Abschnitte der DNA kopiert
- Man wählt bewusst Stellen, an denen sich Menschen mit großer Wahrscheinlichkeit unterscheiden
  (z.B. in der Länge repetitiver Bereiche)
- Dadurch erhält man für jeden Menschen ein (mit sehr großer Wahrscheinlichkeit) individuelles Profil

>[!important]
>Da jede Zelle des Menschen (Ausnahme Immunzellen) die komplette Erbinformation enthält, reicht eine einzige Zelle für ein DNA-Profil aus!

### Ablauf der PCR

Ein PCR-Zyklus besteht aus drei Schritten:

1. **Strangtrennung**: Die beiden Stränge des ursprünglichen DNA-Moleküls werden durch Erhitzen auf 95°C (15 Sekunden) getrennt
   
2. **Anlagerung der Primer**: Die Lösung wird schnell auf etwa 54°C abgekühlt, damit die Primer mit jeweils einem Strang hybridisieren können
   - Ein Primer hybridisiert mit dem 3'-Ende der Zielsequenz auf dem einen Strang
   - Der andere Primer mit dem 3'-Ende des komplementären Strangs
   - Da die Primer im Überschuss zugegeben werden, kommt es kaum zur Rückbildung des ursprünglichen DNA-Doppelstrangs
   - Primer sind meist 20 bis 30 Nucleotide lang
   
3. **DNA-Synthese**: Die Lösung wird auf 72°C erhitzt, die optimale Temperatur für die Taq-DNA-Polymerase
   - Dieses hitzestabile Enzym stammt aus *Thermus aquaticus*, einem thermophilen Bakterium aus heißen Quellen
   - Die Polymerase verlängert beide Primer in Richtung der Zielsequenz (immer von 5' nach 3')
   - Die Synthese erfolgt an beiden Strängen

>[!info]
>PCR Animation: https://www.youtube.com/watch?v=iQsu3Kz9NYo

### Anwendungen der PCR

1. **Forensik**:
   - Täter können durch den genetischen Fingerabdruck überführt werden
   - Profile können in Täterdatenbanken gespeichert werden

2. **Medizin**:
   - Krankheitserreger (Viren, Bakterien) können in Proben (Speichel, Blut, etc.) nachgewiesen werden
   - Spezielle Primer für die DNA des Erregers werden genutzt
   - Gendefekte können identifiziert werden, indem das Gen vervielfältigt und analysiert wird

3. **Biotechnologie**:
   - Herstellung von Insulin: Das menschliche Insulin-Gen wird vervielfältigt und in Bakterien oder Pilze eingeschleust
   - Diese Mikroorganismen produzieren dann Insulin für Diabetiker

### RT-PCR

- Liegt das Erbgut eines Virus in Form von RNA vor, muss die RNA zunächst in DNA umgeschrieben werden
- Dies erfolgt durch das Enzym **Reverse-Transkriptase (RT)**
- Beispiel: COVID-19-Testung (Das Coronavirus hat RNA als Erbinformationsspeicher)