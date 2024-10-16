<style>
body {
    font-family: "Century Gothic", "CenturyGothic", "AppleGothic", sans-serif;
}
</style>

# Funktionsbeschreibung

<br>

## Mengenänderung im Verkaufsauftrag ohne Genehmigung

<br>

Es wird ein Auftrag mit einer Menge angelegt und freigegeben. <br>

<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment7.png" alt="OverShipment7" style="width: 85%; height: auto;">
    <figcaption>Abbildung 7: Menge Verkaufsauftrag (vorher)</figcaption> <br>
</div>

Nach der Freigabe wird die neue Menge bei "Zu liefern" eingetragen. Nachdem das Feld verlassen wird, aktualisiert sich die "Menge" automatisch auf den neuen Wert. <br>

<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment8.png" alt="OverShipment8" style="width: 85%; height: auto;">
    <figcaption>Abbildung 8: Menge Verkaufsauftrag (nachher)</figcaption> <br>
</div>

Es wird nun automatisch der festgelegte "Ausgangsüberschusscode" gewählt und die überschüssige Menge berechnet. <br>

<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment9.png" alt="OverShipment9" style="width: 85%; height: auto;">
    <figcaption>Abbildung 9: Automatisches Ausfüllen des Überschusses</figcaption>
</div>

<br>

## Mengenänderung im Verkaufsauftrag mit Genehmigung

<br>

Wird die Box "Genehmigung" in einem Ausgangsüberschuss Code angewählt, muss beim Anfallen eines Überschusses die Genehmigung eines Befugten eingeholt werden. <br>

<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment10.png" alt="OverShipment10" style="width: 85%; height: auto;">
    <figcaption>Abbildung 10: Menge Verkaufsauftrag mit Genehmigung (vorher)</figcaption> <br>
</div>
<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment11.png" alt="OverShipment11" style="width: 85%; height: auto;">
    <figcaption>Abbildung 11: Menge Verkaufsauftrag mit Genehmigung (nachher)</figcaption> <br>
</div>

In diesem Fall ist beim Debitor ein Ausgangsüberschuss von max. 100% mit Genehmigung angewählt. Die Menge passt sich ebenfalls automatisch an und die Benachrichtigung erscheint, dass eine Ausgangsüberschuss-Menge für diesen Auftrag erfasst wurde. 
Der Warenausgang ist buchbar, jedoch ist der Verkaufsauftrag nicht buchbar, bis eine Genehmigung ausgestellt wurde. Eine Genehmigung wird angefragt durch die Funktion "Genehmigungsanforderung senden", diese findet man unter "Genehmigung anfordern", welche sich in "Aktionen" befinden. <br>

<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment12.png" alt="OverShipment12" style="width: 85%; height: auto;">
    <figcaption>Abbildung 12: Aktionen --> Genehmigung anfordern --> Genehmigungsanforderung senden</figcaption> <br>
</div>

Nachdem die Genehmigung erteilt wurde, kann der Auftrag gebucht werden.

<br>

## Mengenänderung im Warenausgang

<br>

Die Überlieferung kann auch im Warenausgang erfasst werden. Die Erfassung des Überschusses im Warenausgang funktioniert ähnlich wie der Überschuss im Verkaufsauftrag selbst. <br>

<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment13.png" alt="OverShipment13" style="width: 85%; height: auto;">
    <figcaption>Abbildung 13: Ursprünglicher Verkaufsbeleg</figcaption> <br>
</div>

Dabei wird die Menge in "Zu liefern" erhöht, verlässt man danach das Feld, aktualisiert sich der Wert in "Menge" automatisch. <br>

<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment14.png" alt="OverShipment14" style="width: 85%; height: auto;">
    <figcaption>Abbildung 14: Menge im Warenausgang erhöht</figcaption> <br>
</div>

Die Felder "Ausgangsüberschusscode" und "Ausgangsüberschuss-Menge" sind ebenfalls im Warenausgang zu finden und füllen sich aus, nachdem ein Überschuss erfasst wurde. <br>

<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment15.png" alt="OverShipment15" style="width: 85%; height: auto;">
    <figcaption>Abbildung 15: Ausgangsüberschusscode und Ausgangsüberschuss-Menge im Warenausgang</figcaption> <br>
</div>

Die Menge im Verkaufsauftrag bleibt unverändert, bis der Warenausgang freigegeben wird. Die Felder "Ausgangsüberschusscode" und "Ausgangsüberschuss-Menge" werden gefüllt. <br>

<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment16.png" alt="OverShipment16" style="width: 85%; height: auto;">
    <figcaption>Abbildung 16: Veränderte Menge im Verkaufsauftrag</figcaption> <br>
</div>
<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment17.png" alt="OverShipment17" style="width: 85%; height: auto;">
    <figcaption>Abbildung 17: Aufgefüllte Ausgangsüberschuss Spalten</figcaption>
</div>

<br>

## Überbuchung mit Chargennummern

<br>

Ein Verkaufsauftrag, in dem chargenpflichtige Artikel verwendet werden, kann mit der "LeBit Überlieferung App" ebenfalls einen Überschuss erhalten. Dafür erstellt man für diese Verkaufsaufträge einen Warenausgang. Über die "Artikelverfolgungszeilen" kann man dann eine oder mehrere Chargen auswählen, die man bei diesem Verkaufsauftrag verwenden will. <br>

<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment18.png" alt="OverShipment18" style="width: 85%; height: auto;">
    <figcaption>Abbildung 18: Artikelverfolgungszeilen im Warenausgang</figcaption> <br>
</div>

Mit der Funktion "Einträge auswählen" kann man die Chargen auswählen, die zum Artikel und Lagerort passen. 
Die Chargen können ausgewählt werden und mit "OK" wird die Auswahl gespeichert. <br>

<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment19.png" alt="OverShipment19" style="width: 85%; height: auto;">
    <figcaption>Abbildung 19: Auswahl der Chargen </figcaption> <br>
</div>

Nachdem die Artikelverfolgungszeilen geschlossen werden, wird der Ausgangsüberschuss übernommen und die Menge im Warenausgang wird verändert. <br>

<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment20.png" alt="OverShipment20" style="width: 85%; height: auto;">
    <figcaption>Abbildung 20: Menge aus der Chargenauswahl übernommen</figcaption> <br>
</div>

Der Warenausgang kann freigegeben und gebucht werden.