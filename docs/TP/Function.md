<style>
body {
    font-family: "Century Gothic", "CenturyGothic", "AppleGothic", sans-serif;
}

@media print {
    body {
        -webkit-hyphens: auto;
        -moz-hyphens: auto;
        -ms-hyphens: auto;
    }
}
</style>

# Funktionsbeschreibung

<br>

## Transportbedarfe

<br>

Die ausgehenden und eingehenden Transportbedarfe sammeln die
verschiedenen Herkunftsbelege und deren Logistikbelege. Die
Transportbedarfe sind in Master- und Detailzeile unterteilt. Die
Masterzeilen sind ein Abbild der Herkunftsbelegzeilen, so hat jede
Herkunftsbelegzeile genau eine Masterzeile. <br>

<div style="text-align: center;">
    <img src="../../images/TP/Transport_Planning5.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 4: Ausgehende Transportbedarfe</figcaption>
    <br>
</div>

<div style="text-align: center;">
    <img src="../../images/TP/Transport_Planning6.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 5: Eingehende Transportbedarfe</figcaption>
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

<br>

### Transportbedarfe Ungruppiert

<br>

Für die Transportbedarfe gibt es zusätzlich die Seiten \"Ausgehende
Transportbedarfe Ungruppiert\" und \"Eingehende Transportbedarfe
Ungruppiert\". Auf der Seite sind die Detailzeilen in der Struktur nicht
unter den Masterzeilen. Auf der Seite sind alle Funktionen der normalen
ausgehenden Transportbedarfe vorhanden, zusätzlich ist es möglich die
Seite zu Filtern und zu sortieren. <br>

<div style="text-align: center;">
    <img src="../../images/TP/Transport_Planning7.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 6: Ausgehende Transportbedarfe Ungruppiert</figcaption>
    <br>
</div>

<div style="text-align: center;">
    <img src="../../images/TP/Transport_Planning8.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 7: Eingehende Transportbedarfe Ungruppiert</figcaption>
</div>

<br>

## Funktionen in den Transportbedarfen

<br>

Auf den Seiten \"Ausgehende Transportbedarfe\", \"Ausgehende
Transportbedarfe Ungruppiert\", \"Eingehende Transportbedarfe\" und
\"Eingehende Transportbedarfe Ungruppiert\" gibt es verschiedene
Funktionen im Menüband. <br>

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

<br>

## Transportauftrag

<br>

Der Transportauftrag bildet die oberste Ebene der LeBit Transportplanung
und ermöglicht es, verschiedene Herkunftsbelege und deren Lagerbeleg in
einem Beleg zusammen zu fassen.

Der Transportauftrag kann dann entweder an ein weiterführendes
Logistiksystem übergeben werden oder dient als Beleg für die eigene
Versendung.

Der Transportauftrag ist in einen Kopf- und Zeilenbereich unterteilt.

<br>

### Transportauftragskopf

<br>

Der Transportauftragskopf beinhaltet alle relevanten Informationen,
welche für den gesamten Beleg von Bedeutung sind. <br>

<div style="text-align: center;">
    <img src="../../images/TP/Transport_Planning9.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 8: Transportauftragskopf</figcaption>
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

<br>

### Transportauftragszeile

<br>

Die Transportauftragszeile bildet die einzelnen Zeilen ab, welche
innerhalb dieses Transportauftrags gemeinsam versendet werden sollen.
Eine Zeile steht dabei für die Kombination eines Herkunftsbelegs zu
einem Logistikbeleg, somit kann pro Kombination eine
Transportauftragszeile entstehen.

Die Zeilen werden hauptsächlich über die Transportbedarfe gesteuert, sie
können darüber hinzugefügt und gelöscht werden.

<br>

## Funktionen im Transportauftrag

<br>

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

<br>

## Beendeter Transportauftrag

<br>

Der Beendetes Transportauftrag ist eine 1:1 Kopie des Transportauftrages
und bildet eine Kopie der Inhalte der Felder zum Zeitpunkt des Beendens.