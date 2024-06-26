# LeBit Over-Shipment
 
#### Erstellt am: 30. November 2023  
##### App-Version:

## 1. Zweck
Durch einen Ausgangsüberschuss kann die Liefermenge eines Artikels nach der Freigabe des Verkaufsbeleges geändert werden. Zuvor muss ein Ausgangsüberschusscode eingerichtet und in der betroffenen Artikelkarte oder der Karte des betroffenen Debitors angewählt sein.

## 2. Notwendige Einrichtung
### 2.1 Anzeige bestehender Codes
Eine Liste aller Codes findet man über die Suche (Alt+Q) mit der Eingabe "Ausgangsüberschuss Codes".

<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment1.png" alt="OverShipment1" style="width: 100%; height: auto;">
    <figcaption>Abbildung 1: Übersicht Ausgangsüberschuss Codes</figcaption>
    <br>
</div>

### 2.2 Neuer Code
Um eine neue Ausgangsüberschussbeschränkung zu erstellen, muss der Button "[+]Neu" geklickt werden.

<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment2.png" alt="OverShipment2" style="width: 100%; height: auto;">
    <figcaption> Abbildung 2: Feld "[+]Neu"</figcaption>
</div>

<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment3.png" alt="OverShipment3" style="width: 100%; height: auto;">
    <figcaption>Abbildung 3: Erstellen neuer Ausgangüberschusscode</figcaption>
</div>

Um einen neuen Ausgangsüberschuss zu erstellen, müssen folgende Schritte erledigt werden:
1. In der Spalte "Code" erfolgt die Benennung des Überschusses (1).
2. Die Spalte "Beschreibung" dient zur Aufnahme zusätzlicher Informationen (2). 
3. Wird die Box in der Spalte "Standard" markiert, wird dieser Code standardmäßig ausgewählt (3).  
4. Die Einschränkung der Überschussmenge in Prozent wird in der Spalte "Ausgangsüberschuss Toleranz in %" (4) festgelegt. Die maximale Überschussmenge ist auf 100% beschränkt. Damit ist gemeint, dass das System es nur erlaubt, bis maximal 100% mehr zu liefern.
5. In der letzten Spalte "Genehmigung erforderlich" kann eine Box angewählt werden, um für diesen Überschusscode eine Genehmigung des Vorgesetzten festzulegen (5).

### 2.3 Voraussetzung
Um vom Ausgangsüberschuss Gebrauch machen zu können, muss im Debitorenkonto oder in der Artikelkarte ein Ausgangsüberschusscode ausgewählt sein.

#### 2.3.1 Debitorenkonto
Im Reiter "Lieferung" befindet sich die Zeile "Ausgangsüberschusscode".

<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment4.png" alt="OverShipment4" style="width: 100%; height: auto;">
    <figcaption>Abbildung 4: Feld Ausgangsüberschuss (Debitorenkonto)</figcaption>
</div>

#### 2.3.2 Artikelkarte

Um einen Verkaufsüberschuss auf einem Artikel anzusehen, wird die Artikelkarte benötigt. Das Auswahlfeld ist im Reiter "Lagerbestand" zu finden.
 
<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment5.png" alt="OverShipment5" style="width: 100%; height: auto;">
    <figcaption>Abbildung 5: Feld Ausgangsüberschuss (Artikelkarte)</figcaption>
</div>

### 2.4 Überbuchung mit Chargen
Damit eine Überbuchung von verfolgungspflichtigen Artikeln mit Chargen funktioniert, muss in der "LeBit Transportplanung Einrichtung" das Feld "WA- zu liefern an Artikelverfolgungszeile anpassen" aktiviert werden.

<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment6.png" alt="OverShipment6" style="width: 100%; height: auto;">
    <figcaption>Abbildung 6: WA- zu liefern an Artikelverfolgungszeile anpassen aktiviert</figcaption>
</div>

## 3. Funktionsbeschreibung
### 3.1 Mengenänderung im Verkaufsauftrag ohne Genehmigung
Es wird ein Auftrag mit einer Menge angelegt und freigegeben.

<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment7.png" alt="OverShipment7" style="width: 100%; height: auto;">
    <figcaption>Abbildung 7: Menge Verkaufsauftrag (vorher)</figcaption>
</div>

Nach der Freigabe wird die neue Menge bei "Zu liefern" eingetragen. Nachdem das Feld verlassen wird, aktualisiert sich die "Menge" automatisch auf den neuen Wert.

<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment8.png" alt="OverShipment8" style="width: 100%; height: auto;">
    <figcaption>Abbildung 8: Menge Verkaufsauftrag (nachher)</figcaption>
</div>

Es wird nun automatisch der festgelegte "Ausgangsüberschusscode" gewählt und die überschüssige Menge berechnet.

<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment9.png" alt="OverShipment9" style="width: 100%; height: auto;">
    <figcaption>Abbildung 9: Automatisches Ausfüllen des Überschusses</figcaption>
</div>

### 3.2 Mengenänderung im Verkaufsauftrag mit Genehmigung
Wird die Box "Genehmigung" in einem Ausgangsüberschuss Code angewählt, muss beim Anfallen eines Überschusses die Genehmigung eines Befugten eingeholt werden.
 
<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment10.png" alt="OverShipment10" style="width: 100%; height: auto;">
    <figcaption>Abbildung 10: Menge Verkaufsauftrag mit Genehmigung (vorher)</figcaption>
</div>
<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment11.png" alt="OverShipment11" style="width: 100%; height: auto;">
    <figcaption>Abbildung 11: Menge Verkaufsauftrag mit Genehmigung (nachher)</figcaption>
</div>

In diesem Fall ist beim Debitor ein Ausgangsüberschuss von max. 100% mit Genehmigung angewählt. Die Menge passt sich ebenfalls automatisch an und die Benachrichtigung erscheint, dass eine Ausgangsüberschuss-Menge für diesen Auftrag erfasst wurde. 
Der Warenausgang ist buchbar, jedoch ist der Verkaufsauftrag nicht buchbar, bis eine Genehmigung ausgestellt wurde. Eine Genehmigung wird angefragt durch die Funktion "Genehmigungsanforderung senden", diese findet man unter "Genehmigung anfordern", welche sich in "Aktionen" befinden.

<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment12.png" alt="OverShipment12" style="width: 100%; height: auto;">
    <figcaption>Abbildung 12: Aktionen --> Genehmigung anfordern --> Genehmigungsanforderung senden</figcaption>
</div>

Nachdem die Genehmigung erteilt wurde, kann der Auftrag gebucht werden.

### 3.3 Mengenänderung im Warenausgang
Die Überlieferung kann auch im Warenausgang erfasst werden. Die Erfassung des Überschusses im Warenausgang funktioniert ähnlich wie der Überschuss im Verkaufsauftrag selbst.

<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment13.png" alt="OverShipment13" style="width: 100%; height: auto;">
    <figcaption>Abbildung 13: Ursprünglicher Verkaufsbeleg</figcaption>
</div>

Dabei wird die Menge in "Zu liefern" erhöht, verlässt man danach das Feld, aktualisiert sich der Wert in "Menge" automatisch.

<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment14.png" alt="OverShipment14" style="width: 100%; height: auto;">
    <figcaption>Abbildung 14: Menge im Warenausgang erhöht</figcaption>
</div>

Die Felder "Ausgangsüberschusscode" und "Ausgangsüberschuss-Menge" sind ebenfalls im Warenausgang zu finden und füllen sich aus, nachdem ein Überschuss erfasst wurde.

<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment15.png" alt="OverShipment15" style="width: 100%; height: auto;">
    <figcaption>Abbildung 15: Ausgangsüberschusscode und Ausgangsüberschuss-Menge im Warenausgang</figcaption>
</div>

Die Menge im Verkaufsauftrag bleibt unverändert, bis der Warenausgang freigegeben wird. Die Felder "Ausgangsüberschusscode" und "Ausgangsüberschuss-Menge" werden gefüllt.

<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment16.png" alt="OverShipment16" style="width: 100%; height: auto;">
    <figcaption>Abbildung 16: Veränderte Menge im Verkaufsauftrag</figcaption>
</div>
<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment17.png" alt="OverShipment17" style="width: 100%; height: auto;">
    <figcaption>Abbildung 17: Aufgefüllte Ausgangsüberschuss Spalten</figcaption>
</div>

### 3.4 Überbuchung mit Chargennummern
Ein Verkaufsauftrag, in dem chargenpflichtige Artikel verwendet werden, kann mit der "LeBit Überlieferung App" ebenfalls einen Überschuss erhalten. Dafür erstellt man für diese Verkaufsaufträge einen Warenausgang. Über die "Artikelverfolgungszeilen" kann man dann eine oder mehrere Chargen auswählen, die man bei diesem Verkaufsauftrag verwenden will.

<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment18.png" alt="OverShipment18" style="width: 100%; height: auto;">
    <figcaption>Abbildung 18: Artikelverfolgungszeilen im Warenausgang</figcaption>
</div>

Mit der Funktion "Einträge auswählen" kann man die Chargen auswählen, die zum Artikel und Lagerort passen. 
Die Chargen können ausgewählt werden und mit "OK" wird die Auswahl gespeichert.

<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment19.png" alt="OverShipment19" style="width: 100%; height: auto;">
    <figcaption>Abbildung 19: Auswahl der Chargen </figcaption>
</div>

Nachdem die Artikelverfolgungszeilen geschlossen werden, wird der Ausgangsüberschuss übernommen und die Menge im Warenausgang wird verändert.

<div style="text-align: center;">
    <img src="../../images/Over-Shipment/OverShipment20.png" alt="OverShipment20" style="width: 100%; height: auto;">
    <figcaption>Abbildung 20: Menge aus der Chargenauswahl übernommen</figcaption>
</div>

Der Warenausgang kann freigegeben und gebucht werden.