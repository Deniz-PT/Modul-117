
## Teil 1: Netzwerkverkabelung
- Simplex/Unidirektional: Datenübertragung in eine Richtung
- Half-Duplex/Bidirektional: Datenübertragung in beide Richtungen, aber nicht gleichzeitig
- Duplex/Bidirektional: Datenübertragung in beide Richtungen gleichzeitig

Das heutige LAN funktioniert in der Regel im Duplex-Modus, da die meisten Netzwerke Vollduplex-Ethernet verwenden. Dadurch können Daten gleichzeitig in beide Richtungen übertragen werden, was die Effizienz und Leistung verbessert.

## Netzwerktopologien
- Bus-Topologie: Alle Geräte sind an einem gemeinsamen Kommunikationskabel angeschlossen.
- Ring-Topologie: Die Geräte sind in Form eines geschlossenen Rings verbunden.
- Stern-Topologie: Alle Geräte sind mit einem zentralen Knotenpunkt (Switch/Hub) verbunden.
- Baum-Topologie: Eine Hierarchie von Switches, bei der die Geräte über mehrere Ebenen verbunden sind.
- Mesh-Topologie: Jedes Gerät ist mit jedem anderen Gerät direkt verbunden.

Die Topologien unterscheiden sich in Bezug auf ihre Struktur, Ausfallsicherheit, Skalierbarkeit und Komplexität. Jede Topologie hat ihre Vor- und Nachteile. Zum Beispiel bietet die Bus-Topologie eine einfache Installation, ist aber anfällig für Single Points of Failure. Die Stern-Topologie bietet eine hohe Ausfallsicherheit, erfordert jedoch mehr Verkabelungsaufwand.

Der Spezialfall Nr. 5 bezieht sich auf die Punkt-zu-Punkt-Verbindung in der Mesh-Topologie, bei der jedes Gerät mit jedem anderen Gerät direkt verbunden ist.


## Draht, Litze und Glas
- Draht: Einfache Kupferdrähte, die in Ethernetkabeln verwendet werden.
- Litze: Mehrere dünne Kupferdrähte, die zu einem Kabelstrang verdrillt sind. Bietet Flexibilität und eignet sich für Patchkabel.
- Glas: Optische Fasern zur Übertragung von Daten mittels Lichtsignalen.

Die Vor- und Nachteile der drei Fabrikate sind:
- Draht: Einfach und kostengünstig, aber anfällig für elektromagnetische Störungen.
- Litze: Flexibel und gut für Patchkabel, aber anfälliger für Beschädigungen.
- Glas: Hohe Bandbreite und immun gegen elektromagnetische Störungen, aber teurer und schwieriger zu installieren.

Diese Fabrikate finden in der Netzwerktechnik Verwendung, wobei Draht und Litze in Kupfer-Ethernetkabeln verwendet werden, während Glasfasern in Glasfaserkabeln eingesetzt werden.

## Störeinflüsse abwehren
Die Kommunikation kann durch verschiedene Störeinflüsse gestört werden, darunter:
- Elektromagnetische Interferenzen (EMI)
- Radiofrequenzstörungen (RFI)
- Übersprechen
- Impulsrauschen
- Signalverlust

Um diese Störeinflüsse zu reduzieren, können Massnahmen wie Schirmung der Kabel, Verwendung von geschirmten Steckern, Vermeidung von Kabelinterferenzen und Verwendung von Signalverstärkern ergriffen werden.


## Kabel-Abschirmung
Die Kabelbezeichnung gibt Auskunft über den inneren Aufbau des Kabels:
- Unshielded [U]: Keine Abschirmung vorhanden.
- Screened [S]: Kupfergeflechtabschirmung über das ganze Kabel gegen niederfrequente Störungen.
- Shielded [S]: Kupfergeflechtabschirmung über die verdrillten Aderpaare gegen niederfrequente Störungen.
- Foiled [F]: Folienabschirmung gegen hochfrequente Störungen über das ganze Kabel oder über Aderpaare.
- Twisted Pair [TP]: Verdrillte Aderpaare zur Unterdrückung von Gleichtaktstörungen.

Die Kabelbezeichnungen der Skizzen (Kabelquerschnitte) können nicht direkt abgelesen werden, da diese Informationen fehlen.

## Kabelkategorien
Ethernetkabel werden in Kabelkategorien eingeteilt, wobei höhere Kategorien einen höheren maximalen Datendurchsatz bieten. Der Kabelaufbau kann sich dabei unterscheiden.

Es fehlen Informationen zu den Kabelkategorien.


## Ethernet-Medientypen
Beispiele für Ethernet-Medientypen sind:
- 1000Base-T: Kupferverbindung, Stern/Duplex, IEEE-Norm: 802.3ab, Brutto-Datendurchsatz: 1 Gb/s, Kabelkategorie mindestens: CAT5e, Segmentlänge max.: 100m.
- 1000Base-SX: Glasfaser/Fibre, Stern/Duplex, IEEE-Norm: 802.3z, Brutto-Datendurchsatz: 1 Gb/s, Technologie: Short-Wavelength (850nm), Segmentlänge max.: 275m für 62.5μm Multimode, 550m für 50μm Multimode.

Es existieren noch weitere Medientypen, die hier nicht aufgeführt sind.

## Universelle Gebäudeverkablung (UGV)
- Logische Topologie: Zeigt die Verbindungen zwischen Komponenten (PCs, Server, Switches, Router) auf. RJ45-Steckdosen und Verkabelungstechnologie sind hier nicht relevant.
- Physische Topologie oder Verkabelungsplan: Zeigt die Verkabelung anhand eines Gebäudegrundrisses. Dient als Vorgabe für die Verkabelung durch den Installateur.
- Das logische Layout und der Verkabelungsplan müssen in Bezug auf Anschluss und Beschriftung der Komponenten übereinstimmen.
- Festinstallationen werden als UGV ausgeführt, wobei die Komponenten von Netzwerksteckdose zu Netzwerksteckdose mit Patchkabeln verbunden werden.
