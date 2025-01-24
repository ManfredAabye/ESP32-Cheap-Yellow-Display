# ESP32-Cheap-Yellow-Display

Es gibt ein ESP32 mit einem integrierten 320 x 240 2,8" LCD-Display mit Touchscreen namens "ESP32-2432S028R". Da dieser Name nicht leicht von der Zunge geht, schlage ich vor, es in "Cheap Yellow Display" oder kurz CYD umzubenennen. Dieses Display kostet nur etwa 15 $ inklusive Lieferung, was ich für ein sehr gutes Preis-Leistungs-Verhältnis halte.

## Merkmale

Das CYD bietet die folgenden Funktionen:

- ESP32 (mit Wi-Fi und Bluetooth)
- 320 x 240 LCD-Display (2,8")
- Touchscreen (resistiv)
- USB zum Betrieb und Programmieren
- SD-Kartensteckplatz, LED und einige zusätzliche Pins herausgeführt

## Für wen ist es geeignet?

Ich denke, es ist nützlich für folgende Arten von Personen:

- **Menschen, die gerade erst anfangen, mit Hardware zu arbeiten** - da alles bereits verbunden ist, sind keine Lötarbeiten oder zusätzlichen Komponenten erforderlich
- **Menschen, die mit Hardware vertraut sind, aber faul** - (wie ich) Manchmal möchte man einfach ein Projekt bauen, ohne Hardware zusammenbauen zu müssen
- **Menschen, die nicht wirklich etwas lernen möchten, sondern einfach nur coole Dinge bauen wollen** - Mehr dazu später.

## Was ist der Zweck dieser Seite?

Dies ist ziemlich gute Hardware zu einem günstigen Preis, aber die Softwareanleitungen/Unterstützung dazu sind ziemlich schlecht. Es gibt nur einen einzigen Link zu einer Zip-Datei auf einer zufälligen Website.

Vor ein paar Jahren habe ich das [ESP32 Trinity](https://github.com/witnessmenow/ESP32-Trinity) veröffentlicht, ein Open-Source-ESP32-Board zur Steuerung von Matrix-Displays. Ich denke, der Hauptvorteil, den die Leute aus meiner Arbeit am Trinity ziehen, ist nicht die Hardware, sondern die Dokumentation, Beispielcode und fertig vorbereitete Projekte.

Ich produziere keine Hardwareprodukte mehr, aber ich denke, es wäre interessant, wenn wir die gleiche Art von Community um dieses Display herum aufbauen könnten, in der Leute Beispiele und Projekte für dieses Display teilen können.

## Wie erkenne ich, ob ein Display ein CYD ist?
![CYD decision tree](http://www.plantuml.com/plantuml/png/RP0nJyCm48Nt_8gZNIb3fge3LD2b2q92235UamDRE7PaNuhyxxda7DGgJBs-zxtSE-yJO-IXSzKD6-e8UeVMLyQs1DJrdA6br4JRims-4fW9LiS4bY6JS-47qBTWC052QvEayyCAvA-wS-8vi01F7mS8SVevOxJeUK9zu55QzzP_Nw-exxPmz8tHJzRRsJq4cdo3Pu98oIQsCd4O6WDIbyXF4LN-JNMsYG7UNXyXUAUTLHDfqVeMJWClUfSPrY_OOyPtO_ivUPcfnoMV3iyXJh4cj_MGJd8lEleQkvQKi9TYUT_DvbukXnraIfTQURMT39Nu8kcrXInIwQYO-gCyNwgm6al-ZneTNIRqjLokqS2UV3jqxXS0)

## Wo kaufen?

Kaufen Sie dort, wo es am günstigsten ist:

- [Aliexpress\*](https://s.click.aliexpress.com/e/_DkSpIjB)
- [Aliexpress\*](https://s.click.aliexpress.com/e/_DkcmuCh)
- [Aliexpress](https://www.aliexpress.com/item/1005004502250619.html)
- [Makerfabs](https://www.makerfabs.com/sunton-esp32-2-8-inch-tft-with-touch.html) - Anscheinend kommt es mit einer 16GB SD-Karte. Makerfabs führt auch mein [ESP32 Trinity](https://github.com/witnessmenow/ESP32-Trinity) (HINWEIS: Es fallen Importgebühren in der EU von makerfabs an)

\* = Affiliate-Link

## Erste Schritte mit Ihrem CYD

Für Details, wie Sie mit Ihrem CYD loslegen, schauen Sie sich die Seite [Setup und Konfiguration](/SETUP.md) an.

## Code-Beispiele

### Die Grundlagen

Eine Sammlung von Beispielen, die zeigen, wie man die verschiedenen Funktionen des CYD verwendet. Dies ist ein guter Ausgangspunkt. [Schauen Sie sie sich hier an.](/Examples/Basics)

### Alternative Display-Bibliotheken

Die grundlegenden Beispiele basieren auf der TFT_eSPI-Display-Bibliothek, aber das CYD funktioniert auch mit anderen Display-Bibliotheken. Hier ist ein Beispielcode, wenn Sie eine alternative Arduino-Bibliothek verwenden möchten. [Schauen Sie sie sich hier an.](/Examples/AlternativeLibraries)

### ESPHome

Einige Beispiele für die Verwendung des CYD in ESPHome. [Schauen Sie sie sich hier an.](/Examples/ESPHome)

## Zusätzliche Informationen und Links

### Discord

Treten Sie der CYD-Diskussion auf [meinem Discord-Kanal](https://discord.gg/nnezpvq) bei.

### 3D-Druck

Einige Beispiele für 3D-gedruckte Ständer und Gehäuse. [Schauen Sie sie sich hier an.](/3dModels)

### Pin-Informationen

[Diese Seite](/PINS.md) enthält Informationen darüber, welche Pins wo verwendet werden und welche frei verwendet werden können.

### Add-ons

[Diese Seite](/ADDONS.md) enthält Informationen über zusätzliche Hardware-Erweiterungen, die Ihrem CYD zusätzliche Funktionen verleihen können.

### Fehlerbehebung

[Diese Seite](/TROUBLESHOOTING.md) enthält Informationen darüber, wie Sie Ihr CYD-Gerät fehlerbeheben können.

### Hardware-Modifikationen

[Diese Seite](/Mods/README.md) enthält Informationen über einige Hardware-Modifikationen, die am CYD durchgeführt werden können, um dessen Funktionalität zu verbessern oder zu ändern.

### Medien- und Video-Erwähnungen

[Diese Seite](/MEDIA.md) listet alle Gelegenheiten auf, bei denen das CYD-Projekt irgendwo erwähnt wurde!

## Lizenzinformationen

Dieses Projekt ist unter der MIT-Lizenz gemäß der [Lizenzdatei](/LICENSE) lizenziert.

Die einzige Ausnahme ist der Ordner [OriginalDocumentation](/OriginalDocumentation/), den ich nicht lizenzieren darf.

## Andere Sprachen

Einige Mitglieder der Community haben einige dieser Informationen in andere Sprachen portiert!

Bitte beachten: Ich kann die Genauigkeit der Übersetzung, wie aktuell sie sind oder den Inhalt im Allgemeinen nicht garantieren.

- [Französisch / Française](https://github.com/usini/ESP32-Cheap-Yellow-Display-Documentation-FR)
- [Deutsch / Deutsch](https://github.com/paelzer/ESP32-Cheap-Yellow-Display-Documentation-DE)

Wenn Sie eine Übersetzung beitragen möchten, benennen Sie das Repository mit dem Sprachennamen oder -code im Repository-Namen und Sie können es hier verlinken.
