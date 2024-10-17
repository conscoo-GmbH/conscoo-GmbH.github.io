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

## Kombinationskarte

<br>

Auf der Seite \"Kombination\" werden die Kombination erstellt und
bearbeitet. <br>

<div style="text-align: center;">
<img src="../../images/Manufacturing/Manu20.png" alt="Kontingentzuordnung in der VK-Zeile" style="width: 85%; height: auto;">
<figcaption>Abbildung 19: Kombination Übersicht </figcaption>
</div>

<br>

### Menüband

<br>

| Feldname             | Funktion                                                                                              |
|----------------------|-------------------------------------------------------------------------------------------------------|
| Zeichne Kombination  | Mit der Funktion "Zeichne Kombination" wird die Kombination aufgebaut. Die verschiedenen FAs werden ausgesucht und in eine Reihenfolge gebracht. |
| Freigeben            | Die Kombination wird freigegeben.                                                                     |
| Status zurücksetzen  | Die Kombination kann wieder geöffnet und so überarbeitet werden.                                      |
| Anfertigung hinzufügen | Anfertigung wird zu der Kombination hinzugefügt, funktioniert nur, wenn die Kombination freigegeben ist. |
| Anfertigung entfernen | Hinzugefügte Anfertigung wird von der Kombination entfernt.                                          |
| FA Anpassen          | Damit können die Mengen der Fertigungsaufträge angepasst werden.                                      |
| Kombinationsgrafik   | Zeigt eine Grafik an, wie die Kombination hintereinander aufgebaut ist.                               |

<br>

### Register "Allgemein"

<br>

| Feldname               | Funktion                                                                                                                                             | Bemerkung                                                                                                           |
|------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------|
| Nr.                    | Die Nr. wird automatisch aus der Nummernserie eingefügt                                                                                               |                                                                                                                     |
| Beschreibung           | Kann frei gewählt werden                                                                                                                             |                                                                                                                     |
| Start                  | Bestimmt das Datum und die Uhrzeit, ab der diese Kombination laufen soll.                                                                             |                                                                                                                     |
| Ende                   | Bestimmt das Datum und die Uhrzeit, an dem die Kombination beendet werden soll.                                                                       |                                                                                                                     |
| Dauer                  | Zeigt die Dauer an, wie lange die Kombination läuft.                                                                                                  |                                                                                                                     |
| Kombinationsplan       | Wahl zwischen Bahn, Format und Format Asymmetrisch. Wird automatisch bei der Wahl der AP(G) gefüllt.                                                                       |                                                                                                                     |
| Berechnungsmethode     | Wahl zwischen Zähler und Gewicht, wird automatisch aus bei der Wahl der AP(G) gefüllt.                                                                |                                                                                                                     |
| Kapazitätsart          | Wahl zwischen Arbeitsplatzgruppe und Arbeitsplatz                                                                                                    |                                                                                                                     |
| Kapazitätsnr.          | Bestimmung, welche Arbeitsplatzgruppe oder welcher Arbeitsplatz genau für die Kombination zuständig ist.                                              |                                                                                                                     |
| Status                 | Der Status der Kombination "Offen" oder "Freigegeben"                                                                                                |                                                                                                                     |
| Anfertigung            | Gibt den Anfertigungscode an, zu dem die Kombination gehört.                                                                                                            |  |
| Arbeitsbreite          | Gibt die Arbeitsbreite an, die die Arbeitsplatzgruppe bzw. der Arbeitsplatz zur Verfügung hat, an.                                                    | Arbeitsbreite für jede Kombination notwendig.                                                                       |
| Genutzte Breite        | Summe der Breite der Bahnen.                                                                                                                          |                                                                                                                     |
| Arbeitslänge           | Gibt die Arbeitslänge an, die die Arbeitsplatzgruppe bzw. der Arbeitsplatz zur Verfügung hat, an.                                                     | Arbeitslänge notwendig, wenn der Kombinationsplan auf "Format" geschaltet ist.                                      |
| Genutzte Länge         | Summe der Länge der genutzten Fertigungsanträge.                                                                                                      |                                                                                                                     |
| Arbeitsmenge           | Zeigt die Menge einer Bahn in der Kombination an.                                                                                                     |                                                                                                                     |
| Arbeitsmengeneinheit   | Gibt die Einheit an, die bei der Kombination genutzt wird (LFM, BG)                                                                                   |                                                                                                                     |
| Menge                  | Gibt die Gesamtmenge der FAs in der Kombination an.                                                                                                   |                                                                                                                     |
| Menge (Basis)          | Gibt die Gesamtmenge der FAs in der Basiseinheit der Artikel an, die sich in der Kombination befinden.                                                |                                                                                                                     |
| Parameteransicht       | Wird automatisch ausgefüllt, mit der Parameteransicht aus der AP(G) bzw. der Vorgabe Parameteransicht aus der LeBit Produktion. Kann in der Kombination selbst verändert werden. |                                                                                                                     |
| Anzahl Messer längs    | Gibt an, wie viele Messer die AP(G) besitzt und dadurch wie viele Bahnen nebeneinander liegen können.                                                 |                                                                                                                     |
| Anzahl Messer quer     | Gibt an, wie viele Messer die AP(G) besitzt und dadurch wie viele Bahnen hintereinander liegen können.                                                |                                                                                                                     |

<br>

### Register "Kombinationszeilen"

<br>

| Feldname            | Funktion                                                                                           |
|---------------------|----------------------------------------------------------------------------------------------------|
| **Menüband**            |                                                                                                    |
| Fertigungsauftrag öffnen | Öffnet den markierten Fertigungsauftrag.                                                       |
| Neu                 | Über "Neu" können neue, passende Fertigungsaufträge hinzugefügt werden.                            |
| Löschen             | Löscht die markierte Kombinationszeile.                                                            |
| **Kombinationszeilen**  |                                                                                                    |
| Typ                 | Fertigungsauftrag                                                                                  |
| Planbestimmend      | Wird automatisch gesetzt, wenn der erste Fertigungsauftrag hinzugefügt wird.                       |
| FA-Nr.              | Trägt die Nummer des Fertigungsauftrags ein, der in der Zeile angesprochen wird.                   |
| FA-Zeilennr.        | Gibt die Zeilennummer des Fertigungsauftrags an, welche in dieser Zeile genutzt wird.              |
| Artikelnr.          | Gibt den Artikel der ausgewählten Zeile an.                                                        |
| Beschreibung        | Beschreibung des Artikels                                                                          |
| Menge               | Fügt die Menge des Artikels im Fertigungsauftrag an.                                               |
| Einheitencode       | Basiseinheit des Artikels.                                                                         |
| Menge (Basis)       | Menge des Artikels in der Basiseinheit des Artikels.                                               |
| X Position          | Gibt die X Position des FAs in der Kombination an.                                                 |
| Y Position          | Gibt die X Position des FAs in der Kombination an.                                                 |
| Breite              | Gibt die Breite des Artikels im FA an.                                                             |
| Länge               | Gibt die Länge des Artikels im FA an.                                                              |
| Gewicht pro Bogen   | Gibt das Gewicht je Bogen an, der in der Kombinationszeile erstellt wird.                          |
| Anzahl Würfe        | Gibt die Anzahl der erstellten Bögen an.                                                           |
| Parameter           | Bis zu zehn Parameter des Artikels können angezeigt werden, die in der Parameteransicht als "Sichtbar" gekennzeichnet worden sind. |

<br>

## Kombination erstellen

<br>

In der LeBit Produktion App ist es möglich vier verschiedene
Kombinationsarten zu erstellen.

Welche der vier Kombinationsarten genutzt wird, hängt von den Feldern
\"Kombinationsplan\" und \"Berechnungsmethode\" ab, die sich im
Kombinationskopf befinden. Die Felder werden aus der Arbeitsplatzgruppe
gefüllt.

<br>

| Kombinationsplan    | Berechnungsmethode | Einheit                      |
|---------------------|--------------------|------------------------------|
| Bahn                | Zähler             | Einheit für Rolle            |
| Bahn                | Gewicht            | Mengeneinheit für Gewicht    |
| Format              | Zähler             | Einheit für Bogen            |
| Format              | Gewicht            | Mengeneinheit für Gewicht    |
| Format Asymmetrisch | Zähler             | Einheit für Bogen            |
| Format Asymmetrisch | Gewicht            | Mengeneinheit für Gewicht    |
 
<br>

Um die Fertigungsaufträge hinzuzufügen, gibt es zwei Möglichkeiten. Zum
einen kann man über die \"Zeichne Kombination\" im Menüband des
Kombinationskopfes oder über \"Neu\" im Menüband der Kombinationszeilen
die Fertigungsaufträge hinzufügen. <br>

<div style="text-align: center;">
<img src="../../images/Manufacturing/Manu21.png" alt="Kontingentzuordnung in der VK-Zeile" style="width: 85%; height: auto;">
<figcaption>Abbildung 20: Zeichne Kombination und Neu </figcaption> <br>
</div>

Wird die Funktion \"Zeichne Kombination\" genutzt, öffnet sich eine
Maske und über \"Aktionen\" und \"Neu\" werden die verschiedenen
Fertigungsaufträge eingefügt. <br>

<div style="text-align: center;">
<img src="../../images/Manufacturing/Manu22.png" alt="Kontingentzuordnung in der VK-Zeile" style="width: 85%; height: auto;">
<figcaption>Abbildung 21: "Zeichne Kombination" Übersicht bei Bahnen </figcaption> <br>
</div>

Wird ein Fertigungsauftrag ausgewählt, öffnet sich die Maske \"Bahnen
hinzufügen\". In dieser Maske sieht man, wie viele Bahnen von diesem
Fertigungsauftrag hinzugefügt werden können. Die maximale Anzahl der
Bahnen richtet sich nach der Länge und Breite der AP(G) und an der
Anzahl Messer längs und quer.

Außerdem kann entschieden werden, wie viel Menge man von dem
Fertigungsauftrag nutzt. Bei Kombinationen, die als Kombinationsplan
\"Format\" und als \"Gewicht\", wird außerdem das Feld \"Anzahl Würfe\"
in der Maske angezeigt.

Das Feld \"Menge\" zeigt die Gesamtmenge an, die von dem
Fertigungsauftrag genutzt werden soll, diese wird dann auf die
erstellten Bahnen aufgeteilt. <br>

<div style="text-align: center;">
<img src="../../images/Manufacturing/Manu23.png" alt="Kontingentzuordnung in der VK-Zeile" style="width: 85%; height: auto;">
<figcaption>Abbildung 22: Bahnen hinzufügen Maske </figcaption> <br>
</div>

Der 1. Fertigungsauftrag, der hinzugefügt wird, erhält das Zeichen
\"Planbestimmend\". Durch das Zeichen kann die Menge und die Anzahl
Würfe der weiteren Fertigungsaufträge nicht frei gewählt werden. Es ist
nur möglich zu bestimmen, wie viele Bahnen von dem Fertigungsauftrag
hinzugefügt werden.

Wenn die Fertigungsaufträge hinzugefügt worden sind, ist es ebenfalls
nur möglich die \"Menge\" und \"Anzahl Würfe\" bei den planbestimmenden
Kombinationszeilen zu bearbeiten, die Menge und Anzahl Würfe aller
anderen Kombinationszeilen passen sich an die veränderte Zeile an.

Wenn ein Fertigungsauftrag mehr Menge in der Kombination geplant hat,
als er ursprünglich hatte, wird dies beim Freigeben abgefragt. In der
Abfrage gibt es die Möglichkeit die Menge der Fertigungsaufträge zu
erhöhen und die neu zu berechnen. Wird die Abfrage mit \"Nein\"
beantwortet, wird der Freigabeprozess abgebrochen.

Wird von einem Fertigungsauftrag nicht die volle Menge genutzt, kann die
Restmenge des Fertigungsauftrages in einer weiteren Kombination
ausgewählt werden.

Über die \"Aktionen\" kann man auch die Funktion \"Kombinationsgrafik\"
verwenden, um sich so die Kombination bildlich darstellen zu lassen. <br>

<div style="text-align: center;">
<img src="../../images/Manufacturing/Manu26.png" alt="Kontingentzuordnung in der VK-Zeile" style="width: 85%; height: auto;">
<figcaption>Abbildung 23: Kombinationsgrafik bei Bahnen </figcaption>
</div>

<br>

### Format Asymmetrisch

Bei der Kombinationsplanung \"Format Asymmetrisch\" gibt es Unterschiede
zu den anderen Kombinationsplanungen.

Wird die Kombinationsplanung ausgewählt, ist das Feld \"Vorgabe
Gesamtmenge\" beschreibbar.

Wird das Feld gefüllt, wird die Gesamtmenge auf die verschiedenen
Kombinationszeilen verteilt. Die Berechnung, wie viel Menge in den
einzelnen Kombinationszeilen vorhanden ist, bestimmt sich durch die
Breiten der Artikel in den Fertigungsanträgen.

Der erste Fertigungsauftrag erhält beim ersten Hinzufügen die
Gesamtmenge. Wenn der zweite Fertigungsauftrag hinzugefügt wird, soll
sich die Menge wie folgt berechnen: 

Menge 2. Fertigungsauftrag = (Breite 2. Fertigungsauftrag / Gesamtbreite
in der Kombination) \* Gesamtmenge der Kombination, angegeben in Vorgabe
Gesamtmenge Die Menge des 1. Fertigungsauftrags wird ebenfalls neu
berechnet:

Menge 1. Fertigungsauftrag = (Breite 1. Fertigungsauftrag / Gesamtbreite
in der Kombination) \* Gesamtmenge der Kombination, angegeben in
Arbeitsmenge 

Wird das Feld \"Vorgabe Gesamtmenge\" leer gelassen, dann ist der 1.
Fertigungsauftrag planbestimmend. Die zusätzlich hinzugefügten
Fertigungsaufträge berechnen sich wie folgt:

Menge 2. Fertigungsauftrag = (Menge 1. Fertigungsauftrag /
Gesamtbreite 1. Fertigungsauftrag) \* Gesamtbreite 2. Fertigungsauftrag 


### Funktion Format drehen

<br>

Wenn man eine Kombination hat mit dem Kombinationsplan \"Format\" ist es
möglich, die Formate in der \"Zeichne Kombination\" Maske zu drehen.
Dafür muss man auf die gewünschte Bahn mit der rechten Maustaste klicken
und die Auswahl \"Drehen\" nutzen. <br>

<div style="text-align: center;">
<img src="../../images/Manufacturing/Manu27.png" alt="Kontingentzuordnung in der VK-Zeile" style="width: 85%; height: auto;">
<figcaption>Abbildung 24: Funktion Drehen </figcaption> <br>
</div>

## Anfertigungen

### Zweck

Mit der Anfertigung ist es möglich, mehrere Kombinationen hintereinander
zu planen.

### Anfertigungen erstellen

Über die Suchfunktion sind die Anfertigungen zu finden. In der Übersicht
ist es möglich, die erstellten Anfertigungen auszuwählen, sowie neue
Anfertigungen zu erstellen.

<div style="text-align: center;">
<img src="../../images/Manufacturing/Manu28.png" alt="Kontingentzuordnung in der VK-Zeile" style="width: 85%; height: auto;">
<figcaption>Abbildung 25: Anfertigung Übersicht </figcaption> <br>
</div>

<div style="text-align: center;">
<img src="../../images/Manufacturing/Manu29.png" alt="Kontingentzuordnung in der VK-Zeile" style="width: 85%; height: auto;">
<figcaption>Abbildung 26: Anfertigungskarte Übersicht </figcaption> <br>
</div>

| Feldname                    | Funktion                                                                 | Bemerkung                                                                                                        |
|-----------------------------|--------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|
| **Menüband**                 |                                                                          |                                                                                                                  |
| Kombination auswählen        | Über die Funktion lassen sich freigegebene Kombinationen hinzufügen.      | Bevor Kombinationen hinzugefügt werden können, muss eine Arbeitsplatzgruppe/ ein Arbeitsplatz in der Kapazitätsnr. ausgewählt werden. |
| Freigeben                    | Die Anfertigung wird freigegeben.                                         |                                                                                                                  |
| Status zurücksetzen          | Die Anfertigung kann wieder geöffnet und bearbeitet werden.               |                                                                                                                  |
| **Register Allgemein**       |                                                                          |                                                                                                                  |
| Nr.                          | Wird automatisch ausgefüllt.                                             |                                                                                                                  |
| Beschreibung                 | Freibeschreibbares Feld.                                                 |                                                                                                                  |
| Start Datum/Zeit             | Gibt an, wann die Anfertigung startet.                                    |                                                                                                                  |
| Ende Datum/Zeit              | Gibt an, wann die Anfertigung endet.                                      |                                                                                                                  |
| Kapazitätsart                | Wahl zwischen Arbeitsplatzgruppe und Arbeitsplatz.                        |                                                                                                                  |
| Kapazitätsnr.                | Wahl des spezifischen Arbeitsplatzes/ der Arbeitsplatzgruppe.             |                                                                                                                  |
| Status                       | Zeigt an, ob die Anfertigung offen oder freigegeben ist.                  |                                                                                                                  |
| Menge                        | Wird aus den Mengen der Kombinationen berechnet, die in der Anfertigung vorhanden sind. |                                                                                                                  |
| Menge (Basis)                | Wird ebenfalls aus den Kombinationen berechnet, die in der Anfertigung vorhanden sind. |                                                                                                                  |
| **Anfertigungszeilen Menüband** |                                                                          |                                                                                                                  |
| Zeile löschen                | Darüber kann eine Kombination aus der Anfertigung entfernt werden.        | Eine Mehrfachauswahl ist möglich.                                                                                 |
| Beleg anzeigen               | Die gewählte Kombination kann geöffnet und bearbeitet werden.             |                                                                                                                  |
| Hoch                         | Darüber können die Kombinationen sortiert werden.                        |                                                                                                                  |
| Runter                       | Darüber können die Kombinationen sortiert werden.                        |                                                                                                                  |
| **Anfertigungszeilen**       |                                                                          |                                                                                                                  |
| Kombination                  | Nummer der Kombination                                                   |                                                                                                                  |
| Beschreibung                 | Beschreibung der Kombination                                             |                                                                                                                  |
| Reihenfolge                  | Gibt an, welchen Platz die Kombination in der Anfertigung hat.            |                                                                                                                  |
| Genutzte Länge               | Gibt die Länge an, die in der Kombination genutzt wird.                   |                                                                                                                  |
| Genutzte Breite              | Gibt die Breite an, die in der Kombination genutzt wird.                  |                                                                                                                  |
| Anzahl Würfe                 | Gibt die Anzahl an Würfen an, die in der Kombination genutzt wird.        |                                                                                                                  |
| Anzahl X                     | Gibt die Anzahl an Fertigungsaufträgen an, die auf der X-Achse sind, die in der Kombination genutzt wird. |                                                                                                                  |
| Anzahl Y                     | Gibt die Anzahl an Fertigungsaufträgen an, die auf der Y-Achse sind, die in der Kombination genutzt wird. |                                                                                                                  |
| Menge                        | Gibt die Menge an, die in der Kombination ist.                            |                                                                                                                  |
| Menge (Basis)                | Gibt die Menge (Basis) an, die in der Kombination ist.                    |                                                                                                                  |
