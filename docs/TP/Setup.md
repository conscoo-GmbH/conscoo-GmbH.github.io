<style>
body {
    font-family: "Century Gothic", "CenturyGothic", "AppleGothic", sans-serif;
}
</style>

# Notwendige Einrichtung

## Transportplanung Einrichtung

Für diese LeBit Transportplanung existiert eine zentrale Einrichtung,
welche vor der ersten Nutzung zwingend eingerichtet werden muss. <br>

<div style="text-align: center;">
    <img src="../../images/TP/Transport_Planning1.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 1: Transportplanung Einrichtung</figcaption>
</div>

<br>

### Register Allgemein ausgehende Transportplanung

| Feldname                                      | Funktion                                                                                                                                                                                                                                            |
|-----------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Automatische Chargenauswahl überspringen      | Einrichtungsmöglichkeit, ob innerhalb der Standardfunktion „Einträge auswählen“ in den „Artikelverfolgungszeilen“ die Standardchargenvorauswahl deaktiviert werden soll. <br> Wert = True: Standardchargenvorauswahl deaktiviert <br> Wert = False: Standardchargenvorauswahl aktiviert (Standardsystemverhalten) |
| Abweichende Warenausgangsmengen erlauben      | Im Standardsystemverhalten ist es nicht möglich, die Warenausgangsmenge zu beeinflussen. Mit dieser Einrichtung sind abweichende Warenausgangsmenge möglich. Achtung: Gilt nur für den Beleg „Warenausgang“. <br> Wert = True: abweichende Warenausgangsmenge erlaubt <br> Wert = False: abweichende Warenausgangsmenge nicht erlaubt (Standardsystemverhalten) |
| Mehrere Warenausgänge erlauben                | Im Standardsystemverhalten ist es nicht möglich, mehrere ungebuchte Warenausgänge anzulegen. Mit dieser Einrichtung ist es möglich mehrere ungebuchte Warenausgänge anlegen. Achtung: Gilt nur für den Beleg „Warenausgang“ <br> Wert = True: mehrere ungebuchte Warenausgänge erlaubt <br> Wert = False: mehrere ungebuchte Warenausgänge nicht erlaubt (Standardsystemverhalten) |
| Lösche teilgelieferten Warenausgang           | Im Standardsystemverhalten werden ungebuchte Warenausgänge erst dann gelöscht, wenn die geplante Menge aller Warenausgangszeilen komplett geliefert wurde. Mit Hilfe dieser Einstellung, werden Warenausgänge nach der ersten Buchung gelöscht. Losgelöst, ob der Warenausgang noch Restmengen hat oder nicht. <br> Wert = True: Warenausgang wird nach der ersten Buchung gelöscht <br> Wert = False: Warenausgang wird erst bei vollständiger Lieferung gelöscht (Standardsystemverhalten) |
| Buchungsdatum Warenausgang                    | Bei Anlage des Warenausgangs wird das Belegdatum sowie das Buchungsdatum des Belegs auf das Erstelldatum gesetzt. Wird nun das Buchungsdatum manuell nicht verändert, ist das Buchungsdatum gleich dem Erstelldatum. Da in gewissen Prozessen ein Vorbereiten von Warenausgängen notwendig ist, ist das Buchungsdatum in der Praxis nicht gleich dem Erstelldatum des Warenausgangs. Mit Hilfe dieser Einrichtung lässt sich die wie folgt einrichten <br> Wert = Standard: Buchungsdatum = Erstelldatum, außer wenn manuell verändert. <br> Wert = Arbeitsdatum: Buchungsdatum ist immer das Arbeitsdatum der tatsächlichen Buchung. Wert im Feld „Buchungsdatum“ ist hierbei irrelevant. |
| WA- zu liefern an Artikelverfolgungszeile anpassen | Ist diese Option aktiviert, so wird aus den in der Artikelverfolgung eingetragenen Zeilen (Chargen/Seriennummern) die Menge errechnet und automatisch in den Warenausgang geschrieben.                                                                 |
| Zu liefernde WA- Standardmenge                | Wert = Leer: Ein neuen Warenausgang wird mit leerer Menge „Zu liefern“ erstellt <br> Wert = Rest: Ein neuer Warenausgang wird mit voller bzw. Restmenge in „Zu liefern“ erstellt                                                                    |
| Warenausgang und Detailzeile automatisch erstellen | Das Feld bestimmt, ob beim Freigeben eines Auftrags, der Warenausgang und die Detailzeile automatisch erstellt wird. <br> Wert = True: beim Freigeben wird der Warenausgang und eine Detailzeile erstellt <br> Wert = False: beim Freigeben wird kein Warenausgang und keine Detailzeile erstellt |

<br>

### Register Allgemein eingehende Transportplanung

| Feldname                                      | Funktion                                                                                                                                                                                                                                            |
|-----------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Mehrere Wareneingänge zulassen                | Im Standardsystemverhalten ist es nicht möglich, mehrere ungebuchte Warenausgänge anzulegen. Mit dieser Einrichtung ist es möglich mehrere ungebuchte Warenausgänge anlegen. Achtung: Gilt nur für den Beleg „Warenausgang“ <br> Wert = True: mehrere ungebuchte Warenausgänge erlaubt <br> Wert = False: mehrere ungebuchte Warenausgänge nicht erlaubt (Standardsystemverhalten) |
| Abweichende Wareneingangsmenge zulassen       | Im Standardsystemverhalten ist es nicht möglich, die Warenausgangsmenge zu beeinflussen. Mit dieser Einrichtung sind abweichende Warenausgangsmenge möglich. Achtung: Gilt nur für den Beleg „Warenausgang“. <br> Wert = True: abweichende Warenausgangsmenge erlaubt <br> Wert = False: abweichende Warenausgangsmenge nicht erlaubt (Standardsystemverhalten) |
| Wareneingang und Detailzeile automatisch erstellen | Das Feld bestimmt, ob beim Freigeben eines Auftrags, der Warenausgang und die Detailzeile automatisch erstellt wird. <br> Wert = True: beim Freigeben wird der Warenausgang und eine Detailzeile erstellt <br> Wert = False: beim Freigeben wird kein Warenausgang und keine Detailzeile erstellt |

<br>

### Register Transportbestellung

| Feldname                               | Funktion                                                                                                                                                                                                                           |
|----------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Standard Transportbestellung Zu-/Abschlag | Hier wird die Standard Transportbestellungsart eingefügt, die für Zu- und Abschläge genutzt wird.                                                                                                                                   |
| Transportbestellung Menge              | Gibt an, wie oft die Transportbestellung geschehen soll. <br> Wert = 1: die Menge der Transportbestellung, die erstellt wird, beträgt immer eins <br> Wert = WA-Menge: die Menge der Transportbestellung, die erstellt werden, ist flexibel und richtet sich nach der Warenausgangsmenge |

<br>

### Register Ausgehende Transportbedarfe aktivieren

In diesem Register ist es möglich, einzurichten für welche
Herkunftsbelegarten die ausgehenden Transportbedarfe verwendet werden
sollen. Wenn für eine Belegart das Feld auf den Wert „true" gesetzt,
werden für die jeweilige Belegart ab diesem Zeitpunkt beim Freigeben des
Herkunftsbeleges die Transportbedarfe angelegt.

<br>

### Register Eingehende Transportbedarfe aktivieren

Hier ist es möglich, einzurichten für welche Herkunftsbelegarten die
eingehenden Transportbedarfe verwendet werden sollen. Wenn für eine
Belegart das Feld auf den Wert „true" gesetzt, werden für die jeweilige
Belegart ab diesem Zeitpunkt beim Freigeben des Herkunftsbeleges die
Transportbedarfe angelegt.

<br>

### Register Styles

In diesem Register wird der Stil festgelegt, für die offenen sowie den
gebuchten Zeilen. Dadurch lassen sich die Transportbedarfe optisch
besser unterscheiden. Bei Auswahl des Stils, wird dieser innerhalb des
Feldes angezeigt, so dass der Nutzer eine Vorschau des Stiles bekommt.

<br>

### Register Nummernserie

Hinterlegung der Nummernserie für den neuen Beleg Transportauftrag. Die
Nummernserie muss vorher innerhalb des Systems eingerichtet werden.

<br>

## Nachtragereport "Erstelle Transportbedarfe"

In den LeBit Transportplanung Einrichtung ist es möglich rückwirkend
Transportbedarfe, für bereits freigegebene Dokumente, zu erstellen. Das
Dokument muss freigegeben sein und die Kategorie muss in der LeBit
Transportplanung Einrichtung aktiviert sein. <br>

Innerhalb des Reports ist es möglich noch weitere Filterungen
hinzufügen, um den Nachtragereport weiter einzuschränken. <br>

<div style="text-align: center;">
    <img src="../../images/TP/Transport_Planning3.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 2: Funktion "Erstelle Ausgehende Transportbedarfe"</figcaption>
</div>

<br>

## Berichtsauswahl - Transportplanung

Das Produkt bringt ein Einrichtungsmöglichkeit für die folgenden Reports
mit:

Transportauftrag

Übernahmebescheinigung

Frachtbrief

Diese Berichtsauswahl kann über die Suche innerhalb des Systems
aufgerufen werden.

<div style="text-align: center;">
    <img src="../../images/TP/Transport_Planning4.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 3: Berichtsauswahl - Transportplanung</figcaption>
</div>

<br>

## Lagermitarbeiter

Im Standard ist es über die Lagermitarbeiter gesteuert, welche Lagerorte
und deren Logistikbelege durch welche Nutzer genutzt bzw. bedienen
werden dürfen. Um dem Standard hier zu folgen, müssen die Benutzer,
welche die Transportplanung nutzen sollen, für die entsprechenden
Lagerorte als Lagermitarbeiter eingerichtet sein.

<br>

## Zuordnung Zusteller und Kontakt -- Kreditor

In der Tabelle der Zusteller wurde ein neues Feld geschaffen, in welchem
zu einem Zusteller ein Unternehmenskontakt zugewiesen werden kann.

Wenn dieser Unternehmenskontakt einem Kreditor zugewiesen wird, wird
dieser im Transportauftrag aus dem Zustellercode gefüllt.

