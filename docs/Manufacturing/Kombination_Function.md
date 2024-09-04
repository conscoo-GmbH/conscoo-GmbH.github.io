<style>
body {
    font-family: "Century Gothic", "CenturyGothic", "AppleGothic", sans-serif;
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
| Kombinationsplan       | Wahl zwischen Bahn und Format. Wird automatisch bei der Wahl der AP(G) gefüllt.                                                                       |                                                                                                                     |
| Berechnungsmethode     | Wahl zwischen Zähler und Gewicht, wird automatisch aus bei der Wahl der AP(G) gefüllt.                                                                |                                                                                                                     |
| Kapazitätsart          | Wahl zwischen Arbeitsplatzgruppe und Arbeitsplatz                                                                                                    |                                                                                                                     |
| Kapazitätsnr.          | Bestimmung, welche Arbeitsplatzgruppe oder welcher Arbeitsplatz genau für die Kombination zuständig ist.                                              |                                                                                                                     |
| Status                 | Der Status der Kombination "Offen" oder "Freigegeben"                                                                                                |                                                                                                                     |
| Anfertigung            | Kann einer Anfertigung hinzugefügt werden.                                                                                                            | Die Kombination kann auch nach dem Freigeben einer Anfertigung hinzugefügt werden, aber dann über die Anfertigung und nicht über der Kombinationskarte. |
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
| Menüband            |                                                                                                    |
| Fertigungsauftrag öffnen | Öffnet den markierten Fertigungsauftrag.                                                       |
| Neu                 | Über "Neu" können neue, passende Fertigungsaufträge hinzugefügt werden.                            |
| Löschen             | Löscht die markierte Kombinationszeile.                                                            |
| Kombinationszeilen  |                                                                                                    |
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

| Kombinationsplan | Berechnungsmethode | Einheit                      |
|------------------|--------------------|------------------------------|
| Bahn             | Zähler             | Einheit für Rolle            |
| Bahn             | Gewicht            | Mengeneinheit für Gewicht    |
| Format           | Zähler             | Einheit für Bogen            |
| Format           | Gewicht            | Mengeneinheit für Gewicht    |

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

<!-- <div style="text-align: center;">
<img src="../../images/Manufacturing/Manu24.png" alt="Kontingentzuordnung in der VK-Zeile" style="width: 85%; height: auto;">
<figcaption>Abbildung 23: Zeichen Planbestimmend </figcaption> <br>
</div> -->

Wenn ein Fertigungsauftrag mehr Menge in der Kombination geplant hat,
als er ursprünglich hatte, wird dies beim Freigeben abgefragt. In der
Abfrage gibt es die Möglichkeit die Menge der Fertigungsaufträge zu
erhöhen und die neu zu berechnen. Wird die Abfrage mit \"Nein\"
beantwortet, wird der Freigabeprozess abgebrochen.

<!-- <div style="text-align: center;">
<img src="../../images/Manufacturing/Manu25.png" alt="Kontingentzuordnung in der VK-Zeile" style="width: 85%; height: auto;">
<figcaption>Abbildung 24: Abfrage zum Erhöhen der Menge des Fertigungsauftrages </figcaption> <br>
</div> -->

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