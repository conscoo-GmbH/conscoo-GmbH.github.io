# LeBit Reklamationsmanagement


#### Erstellt am: 30. November 2023

#### App-Version: 19.10.17530.0



## 1. Zweck

Um die kaufmännischen Funktionen von Business Central um eine bessere interne Verwaltung zu erweitern, wurden die Reklamationsvorgänge erschaffen. Diese bilden eine Grundlage aus Mehrinformationen, welche dann für innerbetriebliche Workflows genutzt werden können. Außerdem wurden erste Schritte getätigt, um 8D Reporting abzubilden.




## 2. Notwendige Einrichtung:

### 2.1 LeBit Reklamation Einrichtung

In der Einrichtung wird eingestellt, welche Nummernserie benutzt wird.




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints1.png" alt="Abbildung : LeBit Reklamation Einrichtung -> Nummerierung" style="width: 100%; height: auto;">
    <figcaption>Abbildung : LeBit Reklamation Einrichtung -> Nummerierung</figcaption>
    <br>
</div>

Es wird empfohlen, eine neue Nummernserie für die Reklamations-App anzulegen, damit diese einen eigenen nachverfolgbaren Nummernkreis haben.




### 2.2 Stammdaten zur "Bewertung"

Um Stammdaten für die Bewertung zu pflegen, befinden sich im Menüband der "LeBit Reklamation Einrichtung" unter "Zugehörig" fünf Buttons zum Verwalten der entsprechenden Daten.




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints2.png" alt="Abbildung : Bewertungs-Stammdaten" style="width: 100%; height: auto;">
    <figcaption>Abbildung : Bewertungs-Stammdaten</figcaption>
    <br>
</div>

Die hier eingetragenen Daten können dann auf dem Reklamationsvorgang genutzt werden, um im Register "Bewertung" mehr Aussage über die Reklamation bringen zu können.




Dabei empfehlen wir folgende Nutzung der Parameter:




Bewertung:

Hierbei handelt es sich um die Bewertung des entstandenen Schadens, beispielsweise durch Beschreibung der Höhe des Schadens. Die Höhe des Schadens kann beispielsweise in leicht, mittel oder schwer unterteilt werden.




Ort:

Hierbei handelt es sich um den Ort an welchem das Problem, die Beschädigung entstanden ist. Um nicht immer wieder neue Codes anlegen zu müssen sollten diese hier allgemein gehalten werden, Formulierungsmöglichkeiten sind beispielsweise Verladung, Transport, Abladen oder Im Lager.




Vorbeugend:

Hier können Maßnahmen genannt werden, welche vorbeugend getätigt wurden, um den Schaden zu verhindern, wie zum Beispiel LuPo, Fest verbaut oder Kantenschutz.




Entscheidung:

Hier können Werte eingerichtet werden, welche eine Entscheidung beschreiben, um das Problem zukünftig vorzubeugen.




Verursacher:

Hier kann eingerichtet werden, wer für den Schaden verantwortlich ist, zum Beispiel der Versand, intern oder extern.




### 2.3 Reklamationsgründe


<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints3.png" alt="Abbildung : Reklamationsgründe Übersicht" style="width: 100%; height: auto;">
    <figcaption>Abbildung : Reklamationsgründe Übersicht</figcaption>
    <br>
</div>

Über die Suche zu finden sind die "Reklamationsgründe". Auf der Seite sind die Reklamationsgründe zu benennen, die bei der Reklamation verwendbar sind.

#### 2.3.1 Reklamationsgründe - Felder


### 3. Funktionsbeschreibung:

#### 3.1 Reklamationsvorgänge

Die über die Suche zu findenden "Reklamationsvorgänge" bilden die Hauptfunktion der App "LeBit Reklamationen" indem Sie eine Übersicht über alle gestarteten Reklamationsvorgänge bietet (Standard-Reklamationen ausgeschlossen).




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints4.png" alt="Abbildung : Reklamationsvorgänge" style="width: 100%; height: auto;">
    <figcaption>Abbildung : Reklamationsvorgänge</figcaption>
    <br>
</div>

Da die Erweiterung alle Standard-Reklamationsfälle und weitere Benötigte, auf einer Seite abdeckt, sind manche Funktionen so benannt, dass sie alle Fälle abdecken. Außerdem werden einige Felder nicht in allen Prozessen benötigt, sodass diese entsprechen aktiviert oder deaktiviert sind.

Auf der sich dahinter befindenden Reklamationskarte können dann alle wichtigen Informationen für die Reklamation eingetragen werden.




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints5.png" alt="Abbildung : Reklamationskarte" style="width: 100%; height: auto;">
    <figcaption>Abbildung : Reklamationskarte</figcaption>
    <br>
</div>

#### 3.1.1 Reklamationskarte - Felder


Zusätzlich befindet sich auf der Seite ein großes Textfeld für die Reklamationsbeschreibung, in welcher weitere Informationen über den Hergang der Beschädigung o.ä., im Freitext, hinterlegt werden können.




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints6.png" alt="Abbildung : Reklamationsbeschreibung Textfeld" style="width: 100%; height: auto;">
    <figcaption>Abbildung : Reklamationsbeschreibung Textfeld</figcaption>
    <br>
</div>




#### 3.1.2 Reklamationszeilen

In den Reklamationszeilen werden je nach Reklamationsart die zu reklamierenden Artikel erfasst. Außerdem können aus den sich hier befindlichen Zeilen direkt die Standardbelege von Business Central (Einkaufsreklamation und Verkaufsreklamation) erstellen.




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints7.png" alt="Abbildung : Reklamationszeilen" style="width: 100%; height: auto;">
    <figcaption>Abbildung : Reklamationszeilen</figcaption>
    <br>
</div>

Zeilenfelder




Zeilenfunktionen

Verwalten




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints8.png" alt="Abbildung : Reklamationszeilen  Verwalten" style="width: 100%; height: auto;">
    <figcaption>Abbildung : Reklamationszeilen  Verwalten</figcaption>
    <br>
</div>

Über die Funktion "Belegzeilenverfolgung", kann der gleichnamige Report geöffnet werden, welche alle verknüpften Zeilen der Auftragszeile darstellt.




Funktionen




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints9.png" alt="Abbildung : Reklamationszeilen  Funktionen" style="width: 100%; height: auto;">
    <figcaption>Abbildung : Reklamationszeilen  Funktionen</figcaption>
    <br>
</div>

Lieferzeilen holen

Über die Funktion "Lieferzeilen holen", können direkt mehrere zu reklamierenden Lieferzeilen in die "Reklamationszeilen" übertragen werden

Reklamierte Artikelverfolgungen auswählen

Falls keine Artikelverfolgung - keine Funktion

Sind der Lieferzeile Artikel mit Artikelverfolgung angehangen, kann an dieser Stelle ausgewählt werden, welche Chargen/Seriennummern von der Reklamation betroffen sein sollen. Eine Mehrfachauswahl ist möglich.




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints10.png" alt="Abbildung : Chargenauswahl" style="width: 100%; height: auto;">
    <figcaption>Abbildung : Chargenauswahl</figcaption>
    <br>
</div>

In dieser Ansicht können die Zeilen ausgewählt werden und mit okay, als zugeordnet markiert werden.

Reklamierte Artikelverfolgungen

Diese Funktion öffnet eine Ansicht aller zugeordneten Artikelverfolgungszeilen der ganzen Reklamation




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints11.png" alt="Abbildung : Reklamation Chargen" style="width: 100%; height: auto;">
    <figcaption>Abbildung : Reklamation Chargen</figcaption>
    <br>
</div>

Gutschrift/Reklamation erstellen

Diese Funktion erstellt zu all den markierten "Reklamationszeilen" eine Verkaufs-, Einkaufsreklamation bzw. eine Verkaufs- oder Einkaufsgutschrift, je nach ausgewählter "Reklamationsart" in Belegkopf. Zu jeder Zeile kann entweder eine Reklamation oder Gutschrift erstellt werden. Zu einer Zeile mehrere Reklamationen, mehrere Gutschriften oder eine Reklamation und eine Gutschrift zu machen ist nicht möglich.




#### 3.1.3 Reklamationskosten

In den Zeilen der Reklamationskosten, können zusätzlich entstandene Kosten geführt werden. Handelt es sich beispielsweise um einen Verkaufsreklamation, können mithilfe dieser Zeilen un dem eingetragenen Zusteller, die Frachtkosten direkt beim Lieferanten reklamiert werden. Wie auch schon in den Reklamationszeilen, können aus den Zeilen direkt die entsprechenden Business Central Belege (Einkaufsgutschrift und Verkaufsgutschrift) erstellt werden.




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints12.png" alt="Abbildung : Reklamationskosten" style="width: 100%; height: auto;">
    <figcaption>Abbildung : Reklamationskosten</figcaption>
    <br>
</div>




Zeilenfelder




Zeilenfunktionen

Funktionen




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints13.png" alt="Abbildung : Reklamationskosten --> Funktionen" style="width: 100%; height: auto;">
    <figcaption>Abbildung : Reklamationskosten --> Funktionen</figcaption>
    <br>
</div>

Mit der Funktion "Erstelle Gutschrift/Reklamation" wird aus allen markierten "Reklamationskosten"-Zeilen eine Einkaufs- oder Verkaufsgutschrift oder -reklamation erstellt. 




Erstelle Gutschrift/Reklamation

In den Reklamationszeilen und -kosten kann man die Reklamation oder Gutschrift erstellen.







<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints14.png" alt="Abbildung : Erstelle Gutschrift/Reklamation" style="width: 100%; height: auto;">
    <figcaption>Abbildung : Erstelle Gutschrift/Reklamation</figcaption>
    <br>
</div>

Nachdem man die Funktion "Erstelle Gutschrift/Reklamation" geklickt hat, hat man relevante Felder.




An Beleg anfügen - Beispiel




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints15.png" alt="Abbildung : Zeile, die einem Beleg angefügt werden soll" style="width: 100%; height: auto;">
    <figcaption>Abbildung : Zeile, die einem Beleg angefügt werden soll</figcaption>
    <br>
</div>




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints16.png" alt="Abbildung : Vor der Wahl des Beleges, die Wahl geht über die drei Punkte" style="width: 100%; height: auto;">
    <figcaption>Abbildung : Vor der Wahl des Beleges, die Wahl geht über die drei Punkte</figcaption>
    <br>
</div>




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints17.png" alt="Abbildung : Auswahl der Reklamationsbelege" style="width: 100%; height: auto;">
    <figcaption>Abbildung : Auswahl der Reklamationsbelege</figcaption>
    <br>
</div>

In dieser Ansicht werden alle schon bestehenden Reklamationsbelege angezeigt, die zur Reklamationsart (Ein- oder Verkauf) passen. Bei der Wahl der Belege spielt der Status eine Rolle, da die Gutschrift/ Reklamation nur an Belege hinzugefügt werden können, die den Status "Offen" tragen. Wenn Belege mit dem Status "Freigegeben" ausgewählt werden, erscheint eine Fehlermeldung, wenn man auf "OK" drückt.




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints18.png" alt="Abbildung : Ausgewählter Beleg Nr gelangt ins Feld" style="width: 100%; height: auto;">
    <figcaption>Abbildung : Ausgewählter Beleg Nr gelangt ins Feld</figcaption>
    <br>
</div>




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints19.png" alt="Abbildung : Reklamierte Zeile in ausgewählten Beleg hinzugefügt#" style="width: 100%; height: auto;">
    <figcaption>Abbildung : Reklamierte Zeile in ausgewählten Beleg hinzugefügt#</figcaption>
    <br>
</div>




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints20.png" alt="Abbildung : Belegart und Belegnr. verändern sich" style="width: 100%; height: auto;">
    <figcaption>Abbildung : Belegart und Belegnr. verändern sich</figcaption>
    <br>
</div>




Neuer Beleg - Beispiel




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints21.png" alt="Abbildung : Zeile für die eine Gutschrift erstellt wird" style="width: 100%; height: auto;">
    <figcaption>Abbildung : Zeile für die eine Gutschrift erstellt wird</figcaption>
    <br>
</div>




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints22.png" alt="Abbildung : Datum des neuen Beleges" style="width: 100%; height: auto;">
    <figcaption>Abbildung : Datum des neuen Beleges</figcaption>
    <br>
</div>




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints23.png" alt="Abbildung : Neuer Beleg" style="width: 100%; height: auto;">
    <figcaption>Abbildung : Neuer Beleg</figcaption>
    <br>
</div>

Der neu erstellte Beleg trägt im Kopf den gleichen Debitoren und Kontakt, der in der Reklamationskarte bestimmt wurde. Das Buchungsdatum ist das gleiche Datum, dass bei der Erstellung ausgewählt wurde. Die Zeilen repräsentieren die im Reklamationsvorgang erstellen Zeilen aus dem Bereich "Reklamationskosten".




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints24.png" alt="Abbildung : Veränderung der Belegart und Belegnr." style="width: 100%; height: auto;">
    <figcaption>Abbildung : Veränderung der Belegart und Belegnr.</figcaption>
    <br>
</div>

Reklamation Info




<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints25.png" alt="Abbildung : Infoboxen Reklamation" style="width: 100%; height: auto;">
    <figcaption>Abbildung : Infoboxen Reklamation</figcaption>
    <br>
</div>

Die Infoboxen der Reklamationen findet man ebenfalls auf der Reklamationskarte. Es gibt vier Kacheln, die sich auf die reklamierten Zeilen beziehen.







<div style="text-align: center;">
    <img src="../../images/Complaints/Complaints26.png" alt="Abbildung : Übersicht Gutschriftszeilen-Kachel" style="width: 100%; height: auto;">
    <figcaption>Abbildung : Übersicht Gutschriftszeilen-Kachel</figcaption>
    <br>
</div>

In den Kacheln sieht man um welche Zeilen es sich handelt und die wichtigsten Zeileninformationen. Zusätzlich dazu kann man den Beleg anzeigen lassen und bei den ungebuchten Zeilen schauen, ob es Zeilen gibt mit Artikelverfolgung.





