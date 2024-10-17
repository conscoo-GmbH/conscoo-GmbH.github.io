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

# Notwendige Einrichtung

<br>

## Anzeige bestehender Codes

<br>

Eine Liste aller Codes findet man über die Suche (Alt+Q) mit der Eingabe "Ausgangsüberschuss Codes". <br>

<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment1.png" alt="OverShipment1" style="width: 100%; height: auto;">
    <figcaption>Abbildung 1: Übersicht Ausgangsüberschuss Codes</figcaption>
</div>

<br>

## Neuer Code

<br>

Um eine neue Ausgangsüberschussbeschränkung zu erstellen, muss der Button "[+]Neu" geklickt werden. <br>

<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment2.png" alt="OverShipment2" style="width: 100%; height: auto;">
    <figcaption> Abbildung 2: Feld "[+]Neu"</figcaption> <br>
</div>

<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment3.png" alt="OverShipment3" style="width: 100%; height: auto;">
    <figcaption>Abbildung 3: Erstellen neuer Ausgangüberschusscode</figcaption> <br>
</div>

Um einen neuen Ausgangsüberschuss zu erstellen, müssen folgende Schritte erledigt werden:
<ol>
<li> In der Spalte "Code" erfolgt die Benennung des Überschusses (1).
<li> Die Spalte "Beschreibung" dient zur Aufnahme zusätzlicher Informationen (2). 
<li> Wird die Box in der Spalte "Standard" markiert, wird dieser Code standardmäßig ausgewählt (3).  
<li> Die Einschränkung der Überschussmenge in Prozent wird in der Spalte "Ausgangsüberschuss Toleranz in %" (4) festgelegt. Die maximale Überschussmenge ist auf 100% beschränkt. Damit ist gemeint, dass das System es nur erlaubt, bis maximal 100% mehr zu liefern.
<li> In der letzten Spalte "Genehmigung erforderlich" kann eine Box angewählt werden, um für diesen Überschusscode eine Genehmigung des Vorgesetzten festzulegen (5).
</ol>

<br>

## Voraussetzung

<br>

Um vom Ausgangsüberschuss Gebrauch machen zu können, muss im Debitorenkonto oder in der Artikelkarte ein Ausgangsüberschusscode ausgewählt sein. 

<br>

### Debitorenkonto

<br>

Im Reiter "Lieferung" befindet sich die Zeile "Ausgangsüberschusscode". <br>

<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment4.png" alt="OverShipment4" style="width: 100%; height: auto;">
    <figcaption>Abbildung 4: Feld Ausgangsüberschuss (Debitorenkonto)</figcaption>
</div>

<br>

### Artikelkarte

<br>

Um einen Verkaufsüberschuss auf einem Artikel anzusehen, wird die Artikelkarte benötigt. Das Auswahlfeld ist im Reiter "Lagerbestand" zu finden. <br>

<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment5.png" alt="OverShipment5" style="width: 100%; height: auto;">
    <figcaption>Abbildung 5: Feld Ausgangsüberschuss (Artikelkarte)</figcaption>
</div>

<br>

## Überbuchung mit Chargen

<br>

Damit eine Überbuchung von verfolgungspflichtigen Artikeln mit Chargen funktioniert, muss in der "LeBit Transportplanung Einrichtung" das Feld "WA- zu liefern an Artikelverfolgungszeile anpassen" aktiviert werden. <br>

<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment6.png" alt="OverShipment6" style="width: 100%; height: auto;">
    <figcaption>Abbildung 6: WA- zu liefern an Artikelverfolgungszeile anpassen aktiviert</figcaption>
</div>