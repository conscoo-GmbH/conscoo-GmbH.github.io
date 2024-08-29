<style>
body {
    font-family: "Century Gothic", "CenturyGothic", "AppleGothic", sans-serif;
}
</style>

# Funktionsbeschreibung:

## Reklamationsvorgänge

Die über die Suche zu findenden "Reklamationsvorgänge" bilden die Hauptfunktion der App "LeBit Reklamationen" indem Sie eine Übersicht über alle gestarteten Reklamationsvorgänge bietet (Standard-Reklamationen ausgeschlossen).




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints4.png" alt="Abbildung : Reklamationsvorgänge" style="width: 100%; height: auto;">
    <figcaption>Abbildung 4: Reklamationsvorgänge</figcaption>
    <br>
</div>

Da die Erweiterung alle Standard-Reklamationsfälle und weitere Benötigte, auf einer Seite abdeckt, sind manche Funktionen so benannt, dass sie alle Fälle abdecken. Außerdem werden einige Felder nicht in allen Prozessen benötigt, sodass diese entsprechen aktiviert oder deaktiviert sind.

Auf der sich dahinter befindenden Reklamationskarte können dann alle wichtigen Informationen für die Reklamation eingetragen werden.




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints5.png" alt="Abbildung : Reklamationskarte" style="width: 100%; height: auto;">
    <figcaption>Abbildung 5: Reklamationskarte</figcaption>
    <br>
</div>

### Reklamationskarte - Felder

| Feldname                   | Funktion                                                                                                                                                                                                               | Bemerkung                                                                                                                                                                                                 |
|----------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Register Allgemein**     |                                                                                                                                                                                                                        |                                                                                                                                                                                                           |
| Nr.                        | Nummernserie der Reklamation                                                                                                                                                                                           | Automatisch gefüllt                                                                                                                                                                                       |
| Beschreibung               | Sprechende Beschreibung der Rekla für einfachere Auswahl aus der Übersicht.                                                                                                                                            |                                                                                                                                                                                                           |
| Reklamationsart            | Verkauf - Einkauf - Umlagerung                                                                                                                                                                                         | An dieser Stelle kann eingestellt werden, um welche Art von Reklamation es sich handelt und welche Folgebelege erstellt werden.                                                                            |
| Referenznr.                | Look-Up entsprechend "Reklamationsart".                                                                                                                                                                                | - Zugehöriger Kreditor/Debitor bei Ver- und Einkauf. <br>- Bei Umlagerung wird hier ein Lagerort ausgewählt.                                                                                               |
| Lief. an                   | Look-Up zu den "Referenznr." Adressen Kreditor/Debitor und Lager von geb. Umlagerungs-Ausgänge.                                                                                                                                                                                 | - Muss, bei Ver- und Einkauf, nur gesetzt werden, falls die "Lief. An" Adresse von primären Stammdaten abweicht. <br>- Muss bei Umlagerung immer gesetzt werden.                      |
| Status                     | Zur Statusmeldung von Reklamationen                                                                                                                                                                                    | Aktuell nur manuell eingestellt, kann zur Filterung genutzt werden.                                                                                                                                       |
| Kontaktnummer              | Look-Up auf Kontakte am Debitor/Kreditor                                                                                                                                                                               | - Zur Weitergabe an Folgebelege. <br>- Bei Umlagerung ist das Feld nicht beschreibbar.                                                                                                                     |
| Kontakt                    | Automatisch gefüllt durch "Name" von "Kontaktnummer"                                                                                                                                                                   |                                                                                                                                                                                                           |
| Externe Belegnummer        | Referenz zur externen Belegnummer                                                                                                                                                                                      |                                                                                                                                                                                                           |
| Datum Externe Belegnummer  | Datum des Belegs aus "Externe Belegnummer"                                                                                                                                                                             |                                                                                                                                                                                                           |
| Muster/Dokumente           | Angehängt - Angefragt - nicht verfügbar                                                                                                                                                                                | Status zu externen Dokumenten, oder Muster der Reklamation                                                                                                                                                 |
| Reklamationsgrund          | Look-Up Reklamationsgründe                                                                                                                                                                                             | Hier kann der Grund für die Reklamation angegeben werden.                                                                                                                                                 |
| Reklamationsursache        | Automatisch gefüllt durch "Beschreibung" von Reklamationsgrund.                                                                                                                                                        |                                                                                                                                                                                                           |
| Reklamationslagerort       | Automatisch gefüllt durch "Standardlagerortcode" von Reklamationsgrund.                                                                                                                                               | Bestimmt den Lagerort bei den Reklamationszeilen. Wird automatisch ausgefüllt, wenn der Reklamationsgrund ein "Standardlagerortcode" hat. Wird der Reklamationsgrund verändert, wird in einer Abfrage gefragt, ob der Lagerort in den Reklamationszeilen auch verändert werden soll. |
| Verantwortlich             | Look-Up auf "Benutzer Einrichtung".                                                                                                                                                                                    | Hier kann ein verantwortlicher Benutzer eingetragen werden. Wenn ein Verantwortlicher für einen Reklamationsgrund gewählt wurde, füllt es sich automatisch aus, lässt sich aber wieder ändern.           |
| Erstellt von               | Automatisch mit ID des Erstellers gefüllt.                                                                                                                                                                             |                                                                                                                                                                                                           |
| Erstellt am                | Automatisch gefüllt mit Erstellungsdatum und Uhrzeit.                                                                                                                                                                  |                                                                                                                                                                                                           |
| Betrag Zeilen              | Addition aller Felder "Betrag" in "Reklamationszeilen".                                                                                                                                                                |                                                                                                                                                                                                           |
| Betrag Kosten              | Addition aller Felder "Zeilenbetrag" in "Reklamationskosten".                                                                                                                                                          |                                                                                                                                                                                                           |
| Betrag Gesamt              | Addiert die Summen von "Betrag Zeilen" und "Betrag Kosten".                                                                                                                                                            |                                                                                                                                                                                                           |                                                                                                                                                                                                                                                                                                                                                                                                                                                 
|Gehört zu Reklamationsvorgang        | Wird automatisch ausgefüllt, wenn bei einer Verkaufsreklamation über "Aktionen" die Funktion "Erstelle Einkaufsreklamationsvorgang" genutzt wird.                                                                      | Wenn im Register "Zusätzliche Informationen" der "Zustellercode" und die "Kreditorennr" ausgefüllt ist, wird Referenznr., Kontaktnr. und Kontakt automatisch ausgefüllt.                                   |
| **Register Bewertung**     |                                                                                                                                                                                                                        |                                                                                                                                                                                                           |
| Bewertung                  | Look-Up auf App eigene Tabelle gefüllt in der Einrichtung.                                                                                                                                                             | Bewertungsmaß für die Schwere der Beschädigung.                                                                                                                                                           |
| Ort des Verschuldens       | Look-Up auf App eigene Tabelle gefüllt in der Einrichtung.                                                                                                                                                             | Ort an welchem der Schaden entstanden ist.                                                                                                                                                                |
| Begründung                 | Freitextfeld                                                                                                                                                                                                           | Text für die Verschuldung, kann ggf. für interne Prozesse verwendet werden.                                                                                                                               |
| Vorbeugungsmaßnahme        | Look-Up auf App eigene Tabelle gefüllt in der Einrichtung.                                                                                                                                                             | Vorbeugungsmaßnahmen gegen erneutes Verschulden.                                                                                                                                                          |
| Entscheidung               | Look-Up auf App eigene Tabelle gefüllt in der Einrichtung.                                                                                                                                                             | Um eine Lösungsentscheidung festzuhalten, um Probleme in der Zukunft zu verringern.                                                                                                                       |
| Verursacher                | Look-Up auf App eigene Tabelle gefüllt in der Einrichtung.                                                                                                                                                             | Verursacher der Beschädigung                                                                                                                                                                              |
| **Register Zusätzliche Informationen**    |                                                                                                                                                                                                                        |                                                                                                                                                                                                           |
| Zustellercode           | Look-Up auf Zusteller                                                                                          | Weitergabe der Daten an Folgebelege                      |
| Kreditorennr.           | Look-Up auf Kreditoren                                                                                         | Nur für VK-Rekla, falls es sich um Handelsware handelt und eine Rekla an den Lieferanten weitergeleitet werden soll. |

Zusätzlich befindet sich auf der Seite ein großes Textfeld für die Reklamationsbeschreibung, in welcher weitere Informationen über den Hergang der Beschädigung o.ä., im Freitext, hinterlegt werden können.




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints6.png" alt="Abbildung : Reklamationsbeschreibung Textfeld" style="width: 100%; height: auto;">
    <figcaption>Abbildung 6: Reklamationsbeschreibung Textfeld</figcaption>
    <br>
</div>




### Reklamationszeilen


In den Reklamationszeilen werden je nach Reklamationsart die zu reklamierenden Artikel erfasst. Außerdem können aus den sich hier befindlichen Zeilen direkt die Standardbelege von Business Central (Einkaufsreklamation und Verkaufsreklamation) erstellen.

<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints7.png" alt="Abbildung : Reklamationszeilen" style="width: 100%; height: auto;">
    <figcaption>Abbildung 7: Reklamationszeilen</figcaption>
    <br>
</div>

#### Zeilenfelder

| Feldname                       | Funktion                                                                                                                                                         | Bemerkung                                                                                                                                                |
|--------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------|
| Lieferungsnr.                  | Geb. Einkaufslieferung / Geb. Verkaufslieferung / Geb. Umlag.-Ausgänge; je nach Reklamationsart                                                                                           |                                                                                                                                   |
| Lieferzeilennr.                | Gibt die genaue Zeile an, welche in der Lieferung reklamiert wird. So muss nicht der ganze Beleg reklamiert werden.                                                | Kann erst ausgefüllt werden, wenn Lieferungsnr. ausgefüllt ist, sonst Fehlermeldung.                                                                     |
| Auftragsnr.                    | Auftrag/Bestellung zur "Lieferungsnr."                                                                                                                            |                                                                                                                                                          |
| Anzahl Artikelverfolgungen     | Übersicht aller Artikelverfolgungszeilen der entsprechenden Zeile                                                                                                 | Hier werden alle Zeilen angezeigt, jedoch keine Steuerung möglich                                                                                        |
| Buchungsdatum                  | Buchungsdatum des Auftrags/ der Bestellung                                                                                                                        |                                                                                                                                                          |
| Artikelnr.                     | Artikelnummer aus der Auftragszeile                                                                                                                               |                                                                                                                                                          |
| Lagerort                       | Automatisch gefüllt mit dem "Reklamationslagerort" aus "Reklamationsgrund"                                                                                        | - Wurde kein Reklamationslagerort bestimmt, wird der Lagerort mit dem Lagerortcode des Artikels befüllt. <br> - Der Lagerort kann manuell verändert werden.                                                  |
| Menge                          | Gesamtmenge der Lieferzeile, automatisch ausgefüllt                                                                                                               |                                                                                                                                                          |
| Menge zu reklamieren           | -Mit Artikelverfolgung: Menge der zu reklamierten Chargen/Seriennr. <br> -Ohne Artikelverfolgung: Frei eingetragene Menge                                                                                              | Kann nicht größer sein als der Wert, der in "Menge" steht.                                              |
| Anzahl reklamierter Artikelverfolgungen           | Durch Funktion "Reklamierte Artikelverfolgungen auswählen" ausgewählte Artikelverfolgungszeilen.                                              |                                                                                                                                                          |
| Einheitencode                  | Einheit aus Lieferzeile                                                                                                                                           |                                                                                                                                                          |
| Preis                          | Preis des Artikels aus der Verkaufsrechnung                                                                                                                       |                                                                                                                                                          |
| Betrag                         | "Preis" mit "Menge zu reklamieren" multipliziert.                                                                                                                 | Wird automatisch ausgefüllt und lässt sich nicht manuell bearbeiten.                                                                                      |
| Währung                        | Mandantenwährung oder Währung aus Lieferung.                                                                                                                       | Wird automatisch ausgefüllt, kann aber manuell verändert werden.                                                                                          |
| Belegart                       | Automatisch ausgefüllt und aktualisiert  | Die Belegart wird anfangs automatisch als "Angebot" angezeigt. Wenn eine Gutschrift oder Reklamation erstellt wird, ändert sich die Belegart automatisch in "Gutschrift" bzw. "Reklamation".|
| Belegnr.                       | Belegnummer der zur "Reklamationszeile" erstellten EK-/VK- oder Umlagrerreklamation.                                                                              |                                                                                                                                                          |


#### Zeilenfunktionen

##### Verwalten




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints8.png" alt="Abbildung : Reklamationszeilen  Verwalten" style="width: 100%; height: auto;">
    <figcaption>Abbildung 8: Reklamationszeilen  Verwalten</figcaption>
    <br>
</div>

Über die Funktion "Belegzeilenverfolgung", kann der gleichnamige Report geöffnet werden, welche alle verknüpften Zeilen der Auftragszeile darstellt.




##### Funktionen




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints9.png" alt="Abbildung : Reklamationszeilen  Funktionen" style="width: 100%; height: auto;">
    <figcaption>Abbildung 9: Reklamationszeilen  Funktionen</figcaption>
    <br>
</div>

1. Lieferzeilen holen

1.1 Über die Funktion "Lieferzeilen holen", können direkt mehrere zu reklamierenden Lieferzeilen in die "Reklamationszeilen" übertragen werden

2. Reklamierte Artikelverfolgungen auswählen

2.1 Falls keine Artikelverfolgung - keine Funktion

2.2 Sind der Lieferzeile Artikel mit Artikelverfolgung angehangen, kann an dieser Stelle ausgewählt werden, welche Chargen/Seriennummern von der Reklamation betroffen sein sollen. Eine Mehrfachauswahl ist möglich.




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints10.png" alt="Abbildung : Chargenauswahl" style="width: 100%; height: auto;">
    <figcaption>Abbildung 10: Chargenauswahl</figcaption>
    <br>
</div>

In dieser Ansicht können die Zeilen ausgewählt werden und mit okay, als zugeordnet markiert werden.

3. Reklamierte Artikelverfolgungen

3.1 Diese Funktion öffnet eine Ansicht aller zugeordneten Artikelverfolgungszeilen der ganzen Reklamation




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints11.png" alt="Abbildung : Reklamation Chargen" style="width: 100%; height: auto;">
    <figcaption>Abbildung 11: Reklamation Chargen</figcaption>
    <br>
</div>

4. Gutschrift/Reklamation erstellen

4.1 Diese Funktion erstellt zu all den markierten "Reklamationszeilen" eine Verkaufs-, Einkaufsreklamation bzw. eine Verkaufs- oder Einkaufsgutschrift, je nach ausgewählter "Reklamationsart" in Belegkopf. Zu jeder Zeile kann entweder eine Reklamation oder Gutschrift erstellt werden. Zu einer Zeile mehrere Reklamationen, mehrere Gutschriften oder eine Reklamation und eine Gutschrift zu machen ist nicht möglich.




### Reklamationskosten

In den Zeilen der Reklamationskosten, können zusätzlich entstandene Kosten geführt werden. Handelt es sich beispielsweise um einen Verkaufsreklamation, können mithilfe dieser Zeilen un dem eingetragenen Zusteller, die Frachtkosten direkt beim Lieferanten reklamiert werden. Wie auch schon in den Reklamationszeilen, können aus den Zeilen direkt die entsprechenden Business Central Belege (Einkaufsgutschrift und Verkaufsgutschrift) erstellt werden.




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints12.png" alt="Abbildung : Reklamationskosten" style="width: 100%; height: auto;">
    <figcaption>Abbildung 12: Reklamationskosten</figcaption>
    <br>
</div>




#### Zeilenfelder

| Feldname      | Funktion                                                                                                         | Bemerkung                                                                                                                                                            |
|---------------|------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Art           | Leer - Artikel - Ressource - Anlage - Zu-/Abschlag (Artikel)                                                     | Hier kann ausgesucht werden, wie die nächsten Felder gefiltert sein sollen                                                                                           |
| Nr.           | Look-Up auf "Art"                                                                                                |                                                                                                                                                                      |
| Beschreibung  | Gefüllt durch Beschreibung aus "Nr."                                                                             |                                                                                                                                                                      |
| Lagerort      | Muss manuell gefüllt werden.                                                                                     |                                                                                                                                                                      |
| Menge         | Beschreibt die Menge der Zeile                                                                                   |                                                                                                                                                                      |
| VK-Preis      | Beschreibt den VK-Preis der Zeile                                                                                |                                                                                                                                                                      |
| Zeilenbetrag  | "Menge" mit "VK-Preis" multipliziert                                                                             |                                                                                                                                                                      |
| Währung       | Mandantenwährung oder Währung aus Lieferung                                                                      |                                                                                                                                                                      |
| Belegart      | Automatisch ausgefüllt und aktualisiert                                                                          | Die Belegart wird anfangs automatisch als "Angebot" angezeigt. Wenn eine Gutschrift oder Reklamation erstellt wird, ändert sich die Belegart automatisch in "Gutschrift" bzw. "Reklamation". |
| Belegnummer   | Nach von den Zeilen beschriebenen erstellte EK-/VK-Gutschriften                                                  |                                                                                                                                                                      |

#### Zeilenfunktionen

##### Funktionen




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints13.png" alt="Abbildung : Reklamationskosten --> Funktionen" style="width: 100%; height: auto;">
    <figcaption>Abbildung 13: Reklamationskosten --> Funktionen</figcaption>
    <br>
</div>

Mit der Funktion "Erstelle Gutschrift/Reklamation" wird aus allen markierten "Reklamationskosten"-Zeilen eine Einkaufs- oder Verkaufsgutschrift oder -reklamation erstellt. 




### Erstelle Gutschrift/Reklamation

In den Reklamationszeilen und -kosten kann man die Reklamation oder Gutschrift erstellen.




| Feldname         | Funktion                                                              | Bemerkung                                                                                                                                |
|------------------|-----------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------|
| Belegart         | Auswahl zwischen Reklamation und Gutschrift                           |                                                                                                                                          |
| Neuer Beleg      | Entscheidung, ob ein neuer Beleg erstellt werden soll oder nicht      |                                                                                                                                          |
| An Beleg anfügen | Wenn "Neuer Beleg" ja ist, dann ist das Feld ausgegraut. Ansonsten kann man hier einen schon vorhandenen Beleg aussuchen, je nach "Belegart". Die reklamierte Zeile wird dem ausgewählten Beleg hinzugefügt.             |  |
| Buchungsdatum    | Wenn "Neuer Beleg" nein ist, dann ist das Feld ausgegraut. Ist es angeschaltet wird der neue Beleg auf das gewählte Datum erstellt.           |                                                                   |


<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints14.png" alt="Abbildung : Erstelle Gutschrift/Reklamation" style="width: 100%; height: auto;">
    <figcaption>Abbildung 14: Erstelle Gutschrift/Reklamation</figcaption>
    <br>
</div>

Nachdem man die Funktion "Erstelle Gutschrift/Reklamation" geklickt hat, hat man relevante Felder.




#### An Beleg anfügen - Beispiel




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints15.png" alt="Abbildung : Zeile, die einem Beleg angefügt werden soll" style="width: 100%; height: auto;">
    <figcaption>Abbildung 15: Zeile, die einem Beleg angefügt werden soll</figcaption>
    <br>
</div>




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints16.png" alt="Abbildung : Vor der Wahl des Beleges, die Wahl geht über die drei Punkte" style="width: 100%; height: auto;">
    <figcaption>Abbildung 16: Vor der Wahl des Beleges, die Wahl geht über die drei Punkte</figcaption>
    <br>
</div>




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints17.png" alt="Abbildung : Auswahl der Reklamationsbelege" style="width: 100%; height: auto;">
    <figcaption>Abbildung 17: Auswahl der Reklamationsbelege</figcaption>
    <br>
</div>

In dieser Ansicht werden alle schon bestehenden Reklamationsbelege angezeigt, die zur Reklamationsart (Ein- oder Verkauf) passen. Bei der Wahl der Belege spielt der Status eine Rolle, da die Gutschrift/ Reklamation nur an Belege hinzugefügt werden können, die den Status "Offen" tragen. Wenn Belege mit dem Status "Freigegeben" ausgewählt werden, erscheint eine Fehlermeldung, wenn man auf "OK" drückt.




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints18.png" alt="Abbildung : Ausgewählter Beleg Nr gelangt ins Feld" style="width: 100%; height: auto;">
    <figcaption>Abbildung 18: Ausgewählter Beleg Nr gelangt ins Feld</figcaption>
    <br>
</div>




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints19.png" alt="Abbildung : Reklamierte Zeile in ausgewählten Beleg hinzugefügt#" style="width: 100%; height: auto;">
    <figcaption>Abbildung 19: Reklamierte Zeile in ausgewählten Beleg hinzugefügt#</figcaption>
    <br>
</div>




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints20.png" alt="Abbildung : Belegart und Belegnr. verändern sich" style="width: 100%; height: auto;">
    <figcaption>Abbildung 20: Belegart und Belegnr. verändern sich</figcaption>
    <br>
</div>




#### Neuer Beleg - Beispiel




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints21.png" alt="Abbildung : Zeile für die eine Gutschrift erstellt wird" style="width: 100%; height: auto;">
    <figcaption>Abbildung 21: Zeile für die eine Gutschrift erstellt wird</figcaption>
    <br>
</div>




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints22.png" alt="Abbildung : Datum des neuen Beleges" style="width: 100%; height: auto;">
    <figcaption>Abbildung 22: Datum des neuen Beleges</figcaption>
    <br>
</div>




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints23.png" alt="Abbildung : Neuer Beleg" style="width: 100%; height: auto;">
    <figcaption>Abbildung 23: Neuer Beleg</figcaption>
    <br>
</div>

Der neu erstellte Beleg trägt im Kopf den gleichen Debitoren und Kontakt, der in der Reklamationskarte bestimmt wurde. Das Buchungsdatum ist das gleiche Datum, dass bei der Erstellung ausgewählt wurde. Die Zeilen repräsentieren die im Reklamationsvorgang erstellen Zeilen aus dem Bereich "Reklamationskosten".




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints24.png" alt="Abbildung : Veränderung der Belegart und Belegnr." style="width: 100%; height: auto;">
    <figcaption>Abbildung 24: Veränderung der Belegart und Belegnr.</figcaption>
    <br>
</div>

### Reklamation Info


| Feldname               | Funktion                                                                                                                                                                                           | Bemerkung                                                                                                                                                                                                                     |
|------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Gutschriftszeilen      | Wird aus den Reklamationszeilen oder -kosten eine Gutschrift erstellt, aber nicht gebucht, dann ist sie bei den Gutschriftszeilen zu finden.                                                      |                                                                                                                                                                                                                               |
| Geb. Gutschriftszeilen | Wird der Gutschriftsbeleg gebucht, wechselt der Beleg aus den "Gutschriftszeilen" in die "Geb. Gutschriftszeilen.  |   Zu sehen sind die wichtigsten Informationen der gebuchten Gutschriftszeilen und es gibt die Möglichkeit die gebuchten Gutschriftsbelege anzusehen.                                                                                                                                                                                                                            |
| Rücksendezeilen        | Wird aus den Reklamationszeilen oder -kosten eine Reklamation erstellt, aber nicht gebucht, dann ist sie bei den Rücksendezeilen zu finden.                                                       |                                                                                                                                                                                                                               |
| Geb. Rücksendezeilen   | Wird die Reklamation dann gebucht, gelangt sie in die "Geb. Rücksendezeilen".                                                                                                                     |                                                                                                                                                                                                                               |

<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints25.png" alt="Abbildung : Infoboxen Reklamation" style="width: 100%; height: auto;">
    <figcaption>Abbildung 25: Infoboxen Reklamation</figcaption>
    <br>
</div>

Die Infoboxen der Reklamationen findet man ebenfalls auf der Reklamationskarte. Es gibt vier Kacheln, die sich auf die reklamierten Zeilen beziehen.







<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints26.png" alt="Abbildung : Übersicht Gutschriftszeilen-Kachel" style="width: 100%; height: auto;">
    <figcaption>Abbildung 26: Übersicht Gutschriftszeilen-Kachel</figcaption>
    <br>
</div>

In den Kacheln sieht man um welche Zeilen es sich handelt und die wichtigsten Zeileninformationen. Zusätzlich dazu kann man den Beleg anzeigen lassen und bei den ungebuchten Zeilen schauen, ob es Zeilen gibt mit Artikelverfolgung.
