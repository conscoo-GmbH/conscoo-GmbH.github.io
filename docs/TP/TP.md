# LeBit Transportplanung 

##### Erstellt am: 25. März 2024

##### App-Version:


## 1. Zweck

Mit Hilfe der Transportplanung lassen sich Versendungen von ausgehenden
und eingehenden Herkunftsbelegzeilen leichter organisieren und planen.
Die ausgehende Transportplanung unterstützt dabei die Herkunftsbelege
Verkaufsauftrag, Umlagerungsauftrag, Serviceauftrage sowie die
Einkaufsreklamation. Die eingehende Transportplanung unterstützt die
Herkunftsbelege Einkaufsbestellung, Umlagerungsauftrag und
Verkaufsreklamation.

Es werden alle Logikbelege im ausgehenden und eingehenden Warenverkehr
unterstützt.

Um mehrere Herkunftsbelegzeilen bzw. Lagerbelegzeilen in einen
übergeordneten Beleg zu sammeln, wurde der Beleg Transportauftrag neu
geschaffen. Dieser bildet die Grundlage für eine vollständige
Integration mit Versandpartnern über eine nachrüstbare Schnittstelle
zwischen Business Central und einem Drittsystem.

## 2. Notwendige Einrichtung:

### 2.1 Transportplanung Einrichtung

Für diese LeBit Transportplanung existiert eine zentrale Einrichtung,
welche vor der ersten Nutzung zwingend eingerichtet werden muss.

<div style="text-align: center;">
    <img src="../../images/TP/Transport_Planning1.png" alt="" style="width: 90%; height: auto;">
    <figcaption>Abbildung 1: Transportplanung Einrichtung</figcaption>
    <br>
</div>





#### 2.1.1 Register Allgemein ausgehende Transportplanung

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


#### 2.1.2 Register Allgemein eingehende Transportplanung

| Feldname                                      | Funktion                                                                                                                                                                                                                                            |
|-----------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Mehrere Wareneingänge zulassen                | Im Standardsystemverhalten ist es nicht möglich, mehrere ungebuchte Warenausgänge anzulegen. Mit dieser Einrichtung ist es möglich mehrere ungebuchte Warenausgänge anlegen. Achtung: Gilt nur für den Beleg „Warenausgang“ <br> Wert = True: mehrere ungebuchte Warenausgänge erlaubt <br> Wert = False: mehrere ungebuchte Warenausgänge nicht erlaubt (Standardsystemverhalten) |
| Abweichende Wareneingangsmenge zulassen       | Im Standardsystemverhalten ist es nicht möglich, die Warenausgangsmenge zu beeinflussen. Mit dieser Einrichtung sind abweichende Warenausgangsmenge möglich. Achtung: Gilt nur für den Beleg „Warenausgang“. <br> Wert = True: abweichende Warenausgangsmenge erlaubt <br> Wert = False: abweichende Warenausgangsmenge nicht erlaubt (Standardsystemverhalten) |
| Wareneingang und Detailzeile automatisch erstellen | Das Feld bestimmt, ob beim Freigeben eines Auftrags, der Warenausgang und die Detailzeile automatisch erstellt wird. <br> Wert = True: beim Freigeben wird der Warenausgang und eine Detailzeile erstellt <br> Wert = False: beim Freigeben wird kein Warenausgang und keine Detailzeile erstellt |


#### 2.1.3 Register Transportbestellung

| Feldname                               | Funktion                                                                                                                                                                                                                           |
|----------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Standard Transportbestellung Zu-/Abschlag | Hier wird die Standard Transportbestellungsart eingefügt, die für Zu- und Abschläge genutzt wird.                                                                                                                                   |
| Transportbestellung Menge              | Gibt an, wie oft die Transportbestellung geschehen soll. <br> Wert = 1: die Menge der Transportbestellung, die erstellt wird, beträgt immer eins <br> Wert = WA-Menge: die Menge der Transportbestellung, die erstellt werden, ist flexibel und richtet sich nach der Warenausgangsmenge |


#### 2.1.4 Register Ausgehende Transportbedarfe aktivieren

In diesem Register ist es möglich, einzurichten für welche
Herkunftsbelegarten die ausgehenden Transportbedarfe verwendet werden
sollen. Wenn für eine Belegart das Feld auf den Wert „true" gesetzt,
werden für die jeweilige Belegart ab diesem Zeitpunkt beim Freigeben des
Herkunftsbeleges die Transportbedarfe angelegt.

#### 2.1.5 Register Eingehende Transportbedarfe aktivieren

Hier ist es möglich, einzurichten für welche Herkunftsbelegarten die
eingehenden Transportbedarfe verwendet werden sollen. Wenn für eine
Belegart das Feld auf den Wert „true" gesetzt, werden für die jeweilige
Belegart ab diesem Zeitpunkt beim Freigeben des Herkunftsbeleges die
Transportbedarfe angelegt.

#### 2.1.6 Register Styles

In diesem Register wird der Stil festgelegt, für die offenen sowie den
gebuchten Zeilen. Dadurch lassen sich die Transportbedarfe optisch
besser unterscheiden. Bei Auswahl des Stils, wird dieser innerhalb des
Feldes angezeigt, so dass der Nutzer eine Vorschau des Stiles bekommt.

#### 2.1.7 Register Nummernserie

Hinterlegung der Nummernserie für den neuen Beleg Transportauftrag. Die
Nummernserie muss vorher innerhalb des Systems eingerichtet werden.

### 2.2 Nachtragereport "Erstelle Transportbedarfe"

In den LeBit Transportplanung Einrichtung ist es möglich rückwirkend
Transportbedarfe, für bereits freigegebene Dokumente, zu erstellen. Das
Dokument muss freigegeben sein und die Kategorie muss in der LeBit
Transportplanung Einrichtung aktiviert sein.

<div style="text-align: center;">
    <img src="../../images/TP/Transport_Planning2.png" alt="" style="width: 90%; height: auto;">
    <figcaption>Abbildung 2: Aktionen -> Erstelle Ausgehende Transportbedarfe</figcaption>
    <br>
</div>



Innerhalb des Reports ist es möglich noch weitere Filterungen
hinzufügen, um den Nachtragereport weiter einzuschränken.

<div style="text-align: center;">
    <img src="../../images/TP/Transport_Planning3.png" alt="" style="width: 90%; height: auto;">
    <figcaption>Abbildung 3: Funktion "Erstelle Ausgehende Transportbedarfe"</figcaption>
    <br>
</div>




### 2.3 Berichtsauswahl - Transportplanung

Das Produkt bringt ein Einrichtungsmöglichkeit für die folgenden Reports
mit:

Transportauftrag

Übernahmebescheinigung

Frachtbrief

Diese Berichtsauswahl kann über die Suche innerhalb des Systems
aufgerufen werden.

<div style="text-align: center;">
    <img src="../../images/TP/Transport_Planning4.png" alt="" style="width: 90%; height: auto;">
    <figcaption>Abbildung 4: Berichtsauswahl - Transportplanung</figcaption>
    <br>
</div>




### 2.4 Lagermitarbeiter

Im Standard ist es über die Lagermitarbeiter gesteuert, welche Lagerorte
und deren Logistikbelege durch welche Nutzer genutzt bzw. bedienen
werden dürfen. Um dem Standard hier zu folgen, müssen die Benutzer,
welche die Transportplanung nutzen sollen, für die entsprechenden
Lagerorte als Lagermitarbeiter eingerichtet sein.

### 2.5 Zuordnung Zusteller und Kontakt -- Kreditor

In der Tabelle der Zusteller wurde ein neues Feld geschaffen, in welchem
zu einem Zusteller ein Unternehmenskontakt zugewiesen werden kann.

Wenn dieser Unternehmenskontakt einem Kreditor zugewiesen wird, wird
dieser im Transportauftrag aus dem Zustellercode gefüllt.

## 3. Funktionsbeschreibung

### 3.1 Transportbedarfe

Die ausgehenden und eingehenden Transportbedarfe sammeln die
verschiedenen Herkunftsbelege und deren Logistikbelege. Die
Transportbedarfe sind in Master- und Detailzeile unterteilt. Die
Masterzeilen sind ein Abbild der Herkunftsbelegzeilen, so hat jede
Herkunftsbelegzeile genau eine Masterzeile.

<div style="text-align: center;">
    <img src="../../images/TP/Transport_Planning5.png" alt="" style="width: 90%; height: auto;">
    <figcaption>Abbildung 5: Ausgehende Transportbedarfe</figcaption>
    <br>
</div>




<div style="text-align: center;">
    <img src="../../images/TP/Transport_Planning6.png" alt="" style="width: 90%; height: auto;">
    <figcaption>Abbildung 6: Eingehende Transportbedarfe</figcaption>
    <br>
</div>




Es werden nur die Herkunftsbelegzeilen beachtet, zu denen in der
Einrichtung die Option bei „Transportbedarfe aktivieren" gleich „True"
ist.

Diese Transportbedarfszeilen werden beim Freigeben des Herkunftsbeleges
angelegt. Wird ein Herkunftsbeleg, mit bestehenden Transportbedarfen,
aus dem Status „Freigegeben" wieder zurückgesetzt, bleibt die
Transportbedarfszeile innerhalb der Transportbedarf stehen. Es erfolgt
eine Hervorhebung. Die Art der Hervorhebung wird in der
„Transportplanung Einrichtung" unter dem Punkt „Stil offene Zeilen"
festgelegt.

Innerhalb der Masterzeilen werden verschiedene Informationen aus den
Herkunftsbelegzeilen angezeigt. Eine tatsächliche Änderung der
Herkunftsinformationen ist bis auf wenige Ausnahmen nicht gestattet.

Die Detailzeilen entstehen unterhalb der Masterzeilen und sind immer mit
der Masterzeile verbunden. Die Detailzeilen bilden entsprechende
Lagerbelege ab. Je nach Einrichtung der Lagerorte, welche innerhalb der
Transportplanung geplant werden, sind dies Warenausgänge oder
Lagerkommissionierungen. In der Detailzeile ist der Zusteller und die
Zustellertransportart änderbar.

#### 3.1.1 Transportbedarfe Ungruppiert

Für die Transportbedarfe gibt es zusätzlich die Seiten \"Ausgehende
Transportbedarfe Ungruppiert\" und \"Eingehende Transportbedarfe
Ungruppiert\". Auf der Seite sind die Detailzeilen in der Struktur nicht
unter den Masterzeilen. Auf der Seite sind alle Funktionen der normalen
ausgehenden Transportbedarfe vorhanden, zusätzlich ist es möglich die
Seite zu Filtern und zu sortieren.

<div style="text-align: center;">
    <img src="../../images/TP/Transport_Planning7.png" alt="" style="width: 90%; height: auto;">
    <figcaption>Abbildung 7: Ausgehende Transportbedarfe Ungruppiert</figcaption>
    <br>
</div>




<div style="text-align: center;">
    <img src="../../images/TP/Transport_Planning8.png" alt="" style="width: 90%; height: auto;">
    <figcaption>Abbildung 8: Eingehende Transportbedarfe Ungruppiert</figcaption>
    <br>
</div>




### 3.2 Funktionen in den Transportbedarfen

Auf den Seiten \"Ausgehende Transportbedarfe\", \"Ausgehende
Transportbedarfe Ungruppiert\", \"Eingehende Transportbedarfe\" und
\"Eingehende Transportbedarfe Ungruppiert\" gibt es verschiedene
Funktionen im Menüband.

  | Feldname                             | Funktion                                                                                                                                                                                                                                        | Zutreffend für |
|--------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------|
| Lagerbelege erstellen                | Die Funktion „Lagerbelege erstellen“ kann genutzt werden, um für einen kommissionierungspflichtigen Lagerort die dazugehörigen „Lagerkommissionierungen“ direkt zu erstellen.                                                                    | Beides         |
| **Buchen**                               |                                                                                                                                                                                                                                                 |                |
| Warenausgang buchen                  | Mit der Funktion kann man den Warenausgang liefern und fakturieren.                                                                                                                                                                             | Ausgehend      |
| Wareneingang buchen                  | Mit der Funktion kann man den Wareneingang liefern und fakturieren.                                                                                                                                                                              | Eingehend      |
| Buchen und drucken                   | Der Herkunftsbeleg kann dadurch gebucht werden.                                                                                                                                                                                                 | Beides         |
| **Aktionen**                             |                                                                                                                                                                                                                                                 |                |
| Transportauftrag erstellen           | Für die Detailzeile wird ein neuer Transportauftrag sein.                                                                                                                                                                                       | Beides         |
| Transportauftrag zuweisen            | Die Detailzeile kann mit der Funktion einem Transportauftrag zugewiesen werden.                                                                                                                                                                 | Beides         |
| Transportauftragszeile löschen       | Wenn eine Detailzeile in einem Transportauftrag vorhanden ist, kann sie mit der Funktion aus dem Transportauftrag wieder gelöscht werden.                                                                                                        | Beides         |
| Kommissionierung erstellen           | Für eine Masterzeile kann eine Kommissionierung erstellt werden.                                                                                                                                                                                | Ausgehend      |
| Warenausgang erstellen               | Für eine Masterzeile kann ein Warenausgang erstellt werden. Sofern in der "LeBit Transportplanung Einrichtung" eingerichtet ist, dass die Warenausgänge abweichende Mengen haben dürfen, kann vor der Erstellung des Warenausgangs innerhalb der Spalte „Menge zu liefern“ die Warenausgangsmenge angepasst werden. Wenn die Option nicht gesetzt ist, ist die Spalte ausgeblendet. | Ausgehend      |
| Warenausgang zuweisen                | Einer Masterzeile kann ein schon bestehender Warenausgang zugewiesen werden. Die Funktion berechnet die „Menge zu liefern“ neu.                                                                                                                 | Ausgehend      |
| Warenausgangzeile löschen            | Ein Warenausgang wird gelöscht, damit wird ebenfalls die Detailzeile gelöscht. Die Funktion berechnet die „Menge zu liefern“ neu.                                                                                                               | Ausgehend      |
| Wareneingang erstellen               | Erstellt einen Wareneingang für eine Masterzeile. Wenn in der "LeBit Transportplanung Einrichtung" eingerichtet ist, dass die Wareneingänge eine abweichende Menge haben dürfen, kann vor der Erstellung des Wareneingangs in der Spalte "Menge zu liefern" eine Wareneingangsmenge angepasst werden. Wenn die Option nicht gesetzt ist, ist die Spalte ausgeblendet. | Eingehend      |
| Wareneingang zuweisen                | Die Masterzeile kann einen schon bestehenden Wareneingang zugewiesen werden. Die Funktion berechnet "Menge zu liefern" neu.                                                                                                                     | Eingehend      |
| Wareneingangszeile löschen           | Der Wareneingang und die Detailzeile werden durch diese Funktion gelöscht. Die "Menge zu liefern" wird neu berechnet.                                                                                                                           | Eingehend      |
| Lieferschein drucken                 | Mit der Funktion kann der Lieferschein gedruckt werden.                                                                                                                                                                                         | Beides         |
| **Zugehörig**                            |                                                                                                                                                                                                                                                 |                |
| Herkunftsbeleg                       | Öffnet den Herkunftsbeleg, der Master-/ Detailzeile.                                                                                                                                                                                            | Beides         |
| Geb. Herkunftsbeleg                  | Öffnet den gebuchten Herkunftsbeleg, der Master-/Detailzeile.                                                                                                                                                                                   | Beides         |
| Artikelverfolgungszeilen             | Zeigt die Artikelverfolgungszeilen der Detailzeile an.                                                                                                                                                                                          | Beides         |
| Lagerbelegzeilen                     | Zeigt die zugehörigen Lagerbelegzeilen an.                                                                                                                                                                                                      | Beides         |
| Warenausgangszeilen                  | Zeigt die zugehörigen Warenausgangszeilen.                                                                                                                                                                                                      | Ausgehend      |
| Kommissionierungszeilen              | Zeigt die Kommissionierungszeilen an, die zur Masterzeile gehören. Erstellte Kommissionierungen können auch in der Tabellenspalte "Kommissionierung" gesehen werden.                                                                             | Ausgehend      |
| Registrierte Kommissionierungszeilen | Zeigt die registrierten Kommissionierungszeilen an. Registrierte Kommissionierungen können auch in der Tabellenspalte "Registrierte Kommissionierung" gesehen werden.                                                                             | Ausgehend      |
| Wareneingangszeilen                  | Zeigt die zugehörigen Wareneingangszeilen.                                                                                                                                                                                                      | Eingehend      |
| Einlagerungszeilen                   | Zeigt die Einlagerungszeilen an, die zur Masterzeile gehören. Erstellte Einlagerungen können auch in der Tabellenspalte "Einlagerung" angezeigt werden.                                                                                          | Eingehend      |
| Registrierte Einlagerungszeilen      | Zeigt die registrierten Einlagerungszeilen an, diese können auch in der Tabellenspalte "Registrierte Einlagerung" angezeigt werden.                                                                                                              | Eingehend      |
| Transportauftrag                     | Öffnet den zugehörigen Transportauftrag.                                                                                                                                                                                                        | Beides         |
| Transportbestellung                  | Öffnet die zugehörige Transportbestellung.                                                                                                                                                                                                      | Beides         |


### 3.3 Transportauftrag

Der Transportauftrag bildet die oberste Ebene der LeBit Transportplanung
und ermöglicht es, verschiedene Herkunftsbelege und deren Lagerbeleg in
einem Beleg zusammen zu fassen.

Der Transportauftrag kann dann entweder an ein weiterführendes
Logistiksystem übergeben werden oder dient als Beleg für die eigene
Versendung.

Der Transportauftrag ist in einen Kopf- und Zeilenbereich unterteilt.

#### 3.3.1 Transportauftragskopf

Der Transportauftragskopf beinhaltet alle relevanten Informationen,
welche für den gesamten Beleg von Bedeutung sind.

<div style="text-align: center;">
    <img src="../../images/TP/Transport_Planning9.png" alt="" style="width: 90%; height: auto;">
    <figcaption>Abbildung 9: Transportauftragskopf</figcaption>
    <br>
</div>




  | Feldname                     | Funktion                                                                                                                                                                                                  |
|------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Erstellungsdatum             | Wird bei der Erstellung aus den Transportbedarfen automatisiert mit dem Tag der Erstellung gefüllt.                                                                                                        |
| Zeit                         | Wird beim Erstellen aus den Transportbedarfen automatisiert mit der Zeit der Erstellung gefüllt.                                                                                                           |
| LKW Kennzeichen              | Kann manuell mit der entsprechenden Information gefüllt werden.                                                                                                                                           |
| LKW Anhänger Kennzeichen     | Kann manuell mit der entsprechenden Information gefüllt werden.                                                                                                                                           |
| Containernr.                 |                                                                                                                                                                                                           |
| Kreditorennr.                | Wird automatisiert aus dem Zusteller gefüllt, sofern dieser eine Zuordnung zu einem Unternehmenskontakt hat, welcher wiederrum eine Zuordnung zu einem Kreditor haben muss.                                 |
| Kreditorenname               | Wird automatisiert aus der Kreditorennr. gefüllt.                                                                                                                                                          |
| Abholddatum von              | Kann manuell mit der entsprechenden Information gefüllt werden.                                                                                                                                           |
| Abholdatum bis               | Kann manuell mit der entsprechenden Information gefüllt werden.                                                                                                                                           |
| Abholzeit vor                | Kann manuell mit der entsprechenden Information gefüllt werden.                                                                                                                                           |
| Abholzeit bis                | Kann manuell mit der entsprechenden Information gefüllt werden.                                                                                                                                           |
| Zustellercode                | Wird, sofern vorhanden, bei Erstellung der Transportauftrages, aus der entsprechenden Detailzeile der Transportbedarfe übergeben.                                                                          |
| Zustellertransportcode       | Wird, sofern vorhanden, bei Erstellung der Transportauftrages, aus der entsprechenden Detailzeile der Transportbedarfe übergeben.                                                                          |
| Transportbestellung erstellt | Wenn eine Transportbestellung vorhanden ist, ist das Feld mit "Ja" gefüllt und darüber kann man direkt zur Transportbestellung springen.                                                                   |


#### 3.3.2 Transportauftragszeile

Die Transportauftragszeile bildet die einzelnen Zeilen ab, welche
innerhalb dieses Transportauftrags gemeinsam versendet werden sollen.
Eine Zeile steht dabei für die Kombination eines Herkunftsbelegs zu
einem Logistikbeleg, somit kann pro Kombination eine
Transportauftragszeile entstehen.

Die Zeilen werden hauptsächlich über die Transportbedarfe gesteuert, sie
können darüber hinzugefügt und gelöscht werden.

### 3.4 Funktionen im Transportauftrag

| Feldname                       | Funktion                                                                                                                                                                                                                                                                      |
|--------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Beenden**                        | Mit dieser Funktion wird der aktuell Transportauftrag beendet. Das Beenden sorgt dafür, dass der Transportauftrag mit all seinen Informationen in die Tabelle der „beendeten Transportaufträge" übergeben wird. <br> Diese Funktion sorgt dafür, dass die Übersicht der Transportaufträge übersichtlich bleibt, aber die abgeschlossenen Transportaufträge für Nachforschungen verfügbar bleiben. |
| **Aktionen**                       |                                                                                                                                                                                                                                                                               |
| Transportbestellung erstellen  | Eine Transportbestellung kann für den Transportauftrag erstellt werden.                                                                                                                                                                                                       |
| **Zugehörig**                      |                                                                                                                                                                                                                                                                               |
| Ausgehende Transportbedarfe    | Öffnet die zugehörigen ausgehenden Transportbedarfe.                                                                                                                                                                                                                          |
| Eingehende Transportbedarfe    | Öffnet die zugehörigen eingehenden Transportbedarfe.                                                                                                                                                                                                                          |
| Transportbestellung            | Öffnet die zugehörige Transportbestellung.                                                                                                                                                                                                                                    |
| **Berichte**                       |                                                                                                                                                                                                                                                                               |
| Transportauftrag               | Mit dieser Funktion ist es möglich, die in der „Berichtsauswahl – Transportplanung“ unter der Verwendung „Transportauftrag“ hinterlegen Reports auszudrucken.                                                                                                                  |
| Übernahmebescheinigung         | Mit dieser Funktion ist es möglich, die in der „Berichtsauswahl – Transportplanung“ unter der Verwendung „Übernahmebescheinigung“ hinterlegen Reports auszudrucken.                                                                                                            |
| Frachtbrief                    | Mit dieser Funktion ist es möglich, die in der „Berichtsauswahl – Transportplanung“ unter der Verwendung „Frachtbrief“ hinterlegen Reports auszudrucken.                                                                                                                       |


### 3.5 Beendeter Transportauftrag

Der Beendetes Transportauftrag ist eine 1:1 Kopie des Transportauftrages
und bildet eine Kopie der Inhalte der Felder zum Zeitpunkt des Beendens.
