# Didgeridoo-Übungsdämpfer

> [!IMPORTANT]
>
> ## Designidee / Vorversion
>
> **Dieses Repository beschreibt derzeit eine Designidee und einen vorläufigen Konstruktionsentwurf.**
>
> Ein physischer Prototyp dieser konkreten Konstruktion wurde noch nicht vollständig gebaut, getestet oder akustisch vermessen. Maße, Materialien und Konstruktionsdetails sind daher **vorläufige Entwurfswerte** und können sich nach den praktischen Versuchen ändern.
>
> Als nächste Projektschritte sind vorgesehen:
>
> * Bau eines oder mehrerer Prototypen
> * Beurteilung von Spielgefühl und Gegendruck
> * Schallpegelmessungen mit und ohne Dämpfer
> * Vergleich verschiedener Auslassdurchmesser
> * Versuche mit unterschiedlichen Absorbermaterialien
> * möglichst auch Frequenzspektrum-Messungen
> * Optimierung der Abmessungen anhand der Ergebnisse
>
> **Versuchsergebnisse und überarbeitete Blueprints werden in diesem Repository veröffentlicht.**
>
> Der aktuelle Stand ist daher als **Version 0.x – Konzept / Vorprototyp** zu verstehen und nicht als fertige oder validierte Konstruktion.

Ein einfacher DIY-Schalldämpfer-Entwurf für das leisere Üben mit einem Didgeridoo.

Ziel dieses Projekts ist es, die wahrgenommene Lautstärke eines Didgeridoos zu reduzieren, ohne den Luftstrom und den Gegendruck unnötig stark zu verändern.

Anstatt das offene Ende des Instruments einfach zu verschließen, verwendet die geplante Konstruktion eine **Expansionskammer, ein perforiertes Innenrohr und schallabsorbierendes Material**.

Der Dämpfer ist vor allem für das Üben in Wohnungen oder anderen Situationen gedacht, in denen die normale Lautstärke eines Didgeridoos störend wäre.

> Das Didgeridoo wird dadurch nicht vollständig lautlos. Es handelt sich um ein experimentelles passives Dämpferkonzept.

---

## Aktueller Projektstatus

**Status: Designidee / Vorprototyp**

Aktuelle Version:

**v0.1-concept**

Der derzeitige Konstruktionsplan basiert auf akustischen Grundprinzipien und technischen Abschätzungen.

Er wurde **noch nicht experimentell validiert**.

Praktische Versuche folgen.

Sobald Messdaten vorhanden sind, sollen Abschätzungen durch reale Versuchsergebnisse ersetzt werden.

---

## Vorgesehene Eigenschaften

* vollständig passiv
* keine Elektronik notwendig
* kostengünstige Materialien
* handelsübliche Rohrteile
* austauschbarer Glockenadapter
* einstellbare Auslassöffnung
* möglichst geringer zusätzlicher Gegendruck
* Reduktion höherer Obertöne und Schnarrgeräusche
* Anpassung an unterschiedliche Didgeridoo-Durchmesser
* einfache Veränderbarkeit für Versuche

---

## Vorgesehenes Funktionsprinzip

Ein Didgeridoo erzeugt neben seinem tiefen Grundton zahlreiche Obertöne.

Wird das Ende des Instruments einfach verschlossen, sinkt zwar die Lautstärke, gleichzeitig steigt aber der Gegendruck stark an und das Spielverhalten verändert sich.

Der geplante Dämpfer verwendet deshalb drei Stufen:

1. **Expansionskammer**

   Die aus dem Didgeridoo austretende Luft gelangt zunächst in einen größeren Raum.

2. **Perforiertes Innenrohr**

   Der Luftstrom läuft anschließend durch ein gelochtes Rohr.

   Schallenergie kann durch die Öffnungen in den umgebenden Absorber gelangen.

3. **Akustischer Absorber**

   Offenporiger Akustikschaum oder PET-Filz soll einen Teil der Schallenergie aufnehmen, insbesondere im höheren Frequenzbereich.

Der Ausgang bleibt offen, damit der Luftstrom nicht blockiert wird.

Das Funktionsprinzip ist technisch plausibel. Wie gut es in dieser konkreten Ausführung funktioniert, muss jedoch erst praktisch untersucht werden.

---

# Vorläufiger Blueprint

## Vorgesehene Hauptabmessungen

| Bauteil                    | Vorläufige Spezifikation |
| -------------------------- | ------------------------ |
| Hauptgehäuse               | DN125 PP/PVC/HT-Rohr     |
| Gehäuselänge               | 400 mm                   |
| typischer Außendurchmesser | ca. 125 mm               |
| Glockenadapter             | ca. 70–105 mm            |
| Einstecktiefe Didgeridoo   | ca. 40 mm                |
| freie Expansionskammer     | ca. 80 mm                |
| Absorberbereich            | ca. 230 mm               |
| Ausgangsbereich            | ca. 50 mm                |
| Innenrohr                  | ca. Ø50 mm               |
| Innenrohrlänge             | ca. 250 mm               |
| Bohrungen                  | Ø6 mm                    |
| Bohrungsraster             | ca. 15 mm                |
| Absorberdicke              | ca. 20–25 mm             |
| erste Testausgänge         | Ø50 / Ø40 / Ø32 mm       |
| Gesamtlänge                | ca. 440 mm               |

**Wichtig:** Diese Maße sind vorläufige Ausgangswerte für den ersten Prototyp und noch nicht experimentell optimiert.

---

## Vorgesehener Längsschnitt

```text
 DIDGERIDOO                         DÄMPFER

       Glocke
         /\
        /  \        80 mm          230 mm               50 mm
=======/    \====================================================
       \    / |                 ___________________
        \__/  |                /                   \
              |               |   Akustikschaum     |
       EVA-   |               |  ################   |
       Ring   |               |  # ............ #   |
              |               |  # : Ø50 Rohr : #---+----> OUT
              |               |  # : perforiert: #   |
              |               |  # ............ #   |
              |               |  ################   |
              |                \___________________/
===============================================================
              <----------- DN125 / 400 mm -------------------->
```

---

# Vorgesehene Materialien

| Bauteil        | Beschreibung                                    |
| -------------- | ----------------------------------------------- |
| Hauptrohr      | DN125 HT/PP/PVC                                 |
| Endkappe       | DN125                                           |
| Innenrohr      | Ø50 mm PP/PVC                                   |
| Glockenadapter | EVA-Schaum, EPDM oder ähnlich                   |
| Absorber       | PET-Akustikfilz oder offenporiger Akustikschaum |
| Schutznetz     | Nylon- oder Edelstahlgewebe                     |
| Dichtstoff     | neutrales Silikon, PU-Kleber o. Ä.              |
| Auslasseinsatz | PVC-/PP-Scheibe oder Rohrreduzierung            |

Keine lose Glas- oder Steinwolle verwenden, da Fasern in den Luftstrom gelangen könnten.

---

# Konzept des Glockenadapters

Das Didgeridoo sollte nicht direkt gegen harten Kunststoff geklemmt werden.

Ein elastischer Ring aus EVA oder EPDM soll übernehmen:

* Abdichtung
* mechanische Entkopplung
* Schutz des Instruments
* Anpassung an unterschiedliche Glockendurchmesser

Vorläufige Maße:

| Glockendurchmesser | Vorgesehene Adapteröffnung |
| -----------------: | -------------------------: |
|              70 mm |                   66–68 mm |
|              80 mm |                   76–78 mm |
|              90 mm |                   86–88 mm |
|             100 mm |                   96–98 mm |

Diese Werte müssen anhand realer Glockenformen und verschiedener Materialien praktisch überprüft werden.

---

# Konzept des perforierten Innenrohrs

Vorgesehene Ausgangswerte:

* Außendurchmesser: ca. 50 mm
* Länge: ca. 250 mm
* perforierte Länge: ca. 200 mm
* Lochdurchmesser: 6 mm
* Raster: ca. 15 mm
* versetzte Lochreihen

Beispiel:

```text
   o     o     o
      o     o
   o     o     o
      o     o
   o     o     o
```

Etwa 80–120 Bohrungen sind vorgesehen.

Zum Vergleich:

```text
Querschnitt Ø50 mm ≈ 1960 mm²

100 × Ø6-mm-Bohrungen ≈ 2830 mm²
```

Dadurch sollten die Bohrungen selbst keinen starken Strömungswiderstand erzeugen. Das tatsächliche Druckverhalten muss jedoch gemessen werden.

---

# Einstellbarer Ausgang – Versuchswerte

Für die ersten Prototypversuche sind drei Öffnungen vorgesehen:

| Test   | Ausgang | Erwartetes Verhalten                             |
| ------ | ------: | ------------------------------------------------ |
| OPEN   |  Ø50 mm | geringster Widerstand                            |
| MEDIUM |  Ø40 mm | mittlere Einstellung                             |
| QUIET  |  Ø32 mm | vermutlich stärkere Dämpfung und mehr Gegendruck |

Diese Angaben sind **Erwartungen und keine Messergebnisse**.

Das tatsächliche Verhältnis zwischen Schalldämpfung und Gegendruck soll im Versuch ermittelt werden.

---

# Vorgesehener Zusammenbau

1. DN125-Gehäuse auf etwa **400 mm** schneiden.
2. Vorderseite für den Glockenadapter vorbereiten.
3. Ø50-mm-Innenrohr auf etwa **250 mm** schneiden.
4. Über etwa 200 mm Länge Ø6-mm-Bohrungen anbringen.
5. Perforierten Bereich mit dünnem Schutznetz umwickeln.
6. Etwa 20–25 mm Akustikabsorber anbringen.
7. Innenrohr mittig im DN125-Gehäuse befestigen.
8. Hinter der Didgeridoo-Glocke etwa **80 mm freien Expansionsraum** vorsehen.
9. Endkappe montieren.
10. Austauschbaren oder einstellbaren Ausgang montieren.
11. Sicherstellen, dass kein Absorbermaterial in den Luftweg gelangen kann.
12. Versuche zunächst mit der größten Ausgangsöffnung durchführen.

---

# Geplante Prototypversuche

Verglichen werden sollen zunächst:

```text
Test A: ohne Dämpfer
Test B: Ausgang Ø50 mm
Test C: Ausgang Ø40 mm
Test D: Ausgang Ø32 mm
```

Für jede Konfiguration sollen dokumentiert werden:

* wahrgenommene Lautstärke
* Spielkomfort
* Gegendruck
* Ansprache des Grundtons
* Zirkularatmung
* Stimmeinsatz
* Obertöne
* Kondenswasserverhalten

---

# Geplante akustische Messungen

Messungen sollen möglichst unter konstanten Bedingungen durchgeführt werden:

```text
Abstand:        1 Meter
Mikrofon:       gleiche Position
Raum:           gleicher Raum
Instrument:     gleiches Didgeridoo
Spielstärke:    möglichst konstant
```

Interessante Messwerte:

* durchschnittlicher dBA-Pegel
* maximaler dBA-Pegel
* Frequenzspektrum
* Pegel des Grundtons
* Pegel einzelner Obertöne
* Differenz mit und ohne Dämpfer

Messungen sollen möglichst mehrfach wiederholt werden.

---

# Erwartete akustische Wirkung

Im derzeitigen Projektstadium wird **keine konkrete Schalldämpfung in dB behauptet**.

Es ist zu erwarten, dass sich höhere Obertöne leichter reduzieren lassen als der sehr tiefe Grundton.

Möglicherweise reduziert werden:

* Schnarren
* höhere Obertöne
* Anschlaggeräusche
* Atemgeräusche
* hohe Frequenzanteile
* subjektiv wahrgenommene Gesamtlautstärke

Wie stark diese Effekte tatsächlich ausfallen, muss jedoch erst experimentell bestimmt werden.

Zukünftige dB-Angaben in diesem Repository sollen ausdrücklich als **gemessene Versuchsergebnisse** gekennzeichnet werden.

---

# Sicherheit

Dieses Projekt ist experimentell.

Nicht verwenden, wenn:

* der Luftstrom stark eingeschränkt wird
* das Atmen unangenehm wird
* hoher Druck entsteht
* Bauteile locker werden
* Absorbermaterial in den Luftstrom gelangen kann

Nur saubere und gesundheitlich unbedenkliche Materialien im Luftweg verwenden.

Der Dämpfer darf niemals einen luftdichten Verschluss bilden.

---

# Reinigung

Die Konstruktion sollte möglichst zerlegbar bleiben.

Da beim Didgeridoo-Spielen Kondenswasser entsteht:

* nach Gebrauch trocknen lassen
* Absorber möglichst herausnehmbar gestalten
* Innenrohr regelmäßig reinigen
* auf Schimmel und Verschmutzung kontrollieren
* verschmutztes Absorbermaterial ersetzen

---

# Geplante Weiterentwicklung

Mögliche spätere Varianten:

* einstellbare Irisblende
* wechselbare Absorberkartuschen
* 3D-gedruckte Glockenadapter
* unterschiedliche Expansionskammern
* unterschiedliche Gehäusedurchmesser
* Helmholtz-Resonatoren
* Viertelwellenresonatoren
* mehrstufige Absorberkammern
* interne Schallleitbleche
* Kondenswasser-Auffangsystem
* optimierte Low-Back-Pressure-Version

---

# Entwicklungsstufen

```text
v0.1  Designidee / vorläufiger Blueprint
 ↓
v0.2  erster physischer Prototyp
 ↓
v0.3  erste akustische Messungen
 ↓
v0.4  Optimierung von Geometrie und Absorber
 ↓
v0.5  zweite Prototypgeneration
 ↓
v1.0  getestete und dokumentierte Konstruktion
```

Die tatsächliche Entwicklung kann sich abhängig von den Versuchsergebnissen ändern.

---

# Mitmachen

Eigene Versuche und unabhängige Prototypen sind ausdrücklich willkommen.

Besonders interessant sind:

* Fotos gebauter Prototypen
* SPL-Messungen
* Frequenzspektren
* Gegendruckmessungen
* unterschiedliche Absorbermaterialien
* alternative Abmessungen
* 3D-druckbare Komponenten
* Versuche mit verschiedenen Didgeridoos

Bitte klar unterscheiden zwischen:

**Entwurfsannahmen**, **subjektiven Beobachtungen** und **gemessenen Ergebnissen**.

---

# Haftungsausschluss

Dieses Repository enthält derzeit eine **experimentelle Designidee und keinen validierten fertigen Dämpfer**.

Die Konstruktion ist weder als medizinisches Gerät noch als geprüftes akustisches oder sicherheitstechnisches Produkt zertifiziert.

Die Verwendung eines Prototyps erfolgt auf eigene Verantwortung.

Es wird keine Garantie übernommen hinsichtlich:

* Schalldämpfung
* mechanischer Sicherheit
* Atemwiderstand
* Spielverhalten
* Kompatibilität mit bestimmten Instrumenten

---

# Lizenz

Für mechanische Konstruktionen, Zeichnungen und CAD-Dateien bietet sich beispielsweise die **CERN Open Hardware Licence Version 2 – Permissive (CERN-OHL-P-2.0)** an.

Später hinzukommende Software kann separat lizenziert werden.

Maßgeblich ist die im Repository enthaltene Datei `LICENSE`.

---

## Projektstatus

**v0.1 – Designidee / Vorprototyp**

**Der Bau und die praktischen Versuche folgen.**

Versuchsergebnisse, Fehlschläge, Änderungen und verbesserte Blueprints sollen offen in diesem Repository dokumentiert werden.
