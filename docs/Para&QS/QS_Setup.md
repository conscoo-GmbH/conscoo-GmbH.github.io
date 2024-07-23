# Notwendige Einrichtung:

## Rolle "Parameter Profil"

Wird die Rolle \"Parameter Profil\" eingerichtet, können auf die
wichtigsten Funktionen und Seiten auf der Startseite gefunden werden.

<div style="text-align: center;">
    <img src="../../images/Para&QS/QS1.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 1: Übersicht "Parameter Profil"</figcaption>
</div>

<br>

## LeBit Parameter & Qualitätssicherung Einrichtung

Zum Einrichten der LeBit Qualitätssicherung wird die Seite \"LeBit
Parameter & Qualitätssicherung Einrichtung\" genutzt.

Im Abschnitt \"Allgemein\" lassen sich Voreinstellungen zur Nutzung der
Qualitätssicherung vornehmen.

<div style="text-align: center;">
    <img src="../../images/Para&QS/QS2.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 2: LeBit Parameter & Qualitätssicherung Einrichtung</figcaption>
</div>

<br>

### Buchen zugelassen für Belegart

Die Zeile \"Buchen zugelassen für Belegart\" bestimmt, ob die
\"Buchen\"-Funktion nur auf Prüfaufträgen, nur auf Proben oder beiden
Belegen zur Verfügung steht.

<br>

### Hole Prüfentscheidung beim Buchen

Die Einrichtung \"Hole Prüfentscheidung beim Buchen\" legt fest, ob der
Zwischenschritt \"Entscheidung holen\" automatisch in der
\"Buchen\"-Funktion inbegriffen ist oder ob diese manuell ausgeführt
werden muss. Die Aktivierung bietet die Optionen \"Nein\", \"Beide\",
\"Prüfauftrag\" und \"Probe\".

<br>

### Vorgabe Warn-/ Limitwert Prozent

Die Felder \"Vorgabe Prozent Warnwert\" und \"Vorgabe Prozent
Limitwert\" legen Prozentsätze fest, die beim Erstellen der Warn- und
Grenzwerte im Wertehelfer vorgeschlagen werden.

<br>

### Rücksetzen der Prüfentscheidung erlaubt

Über das Feld \"Rücksetzen der Prüfentscheidung erlaubt\" kann eine
Anzeigebeschränkung der Funktion \"Rücksetzen Entscheidung\" auf der
Prüfauftragkarte festgelegt werden. Die Funktion ermöglicht das
Zurücksetzen der Prüfentscheidung auf \"Leer\".

Es gibt vier Auswahlmöglichkeiten:

**Beide:**
Die Funktion wird auf dem Prüfauftrag und der Probe angezeigt.

**Auftrag:**
Die Funktion wird nur auf dem Prüfauftrag angezeigt.

**Probe:**
Die Funktion wird nur auf der Probe angezeigt.

**Keine:**
Die Funktion wird auf keiner der beiden Seiten angezeigt und ein
Zurücksetzen der Prüfentscheidung ist nicht möglich.

<br>

### Prüfobjektqualität

Ein Prüfobjekt (Chargennr., Paketnr., Seriennr.) kann mehreren Proben
zugeordnet sein und dementsprechend mehrere Qualitäten erhalten. Es muss
also festgelegt werden, wie das Prüfobjekt final bewertet wird.

Dazu stehen in der Einrichtung zwei Optionen zur Auswahl.

**Option 1: letzte**

Das Prüfobjekt bekommt die Qualität der letzten gebuchten Probe, der es
zugeordnet ist.

**Option 2: schlechteste**

Das Prüfobjekt erhält die schlechteste Qualität aller gebuchten Proben,
denen es zugeordnet ist. Somit ist die Prüfobjektqualität \"schlecht\",
sobald eine Probe mit der Prüfentscheidung \"schlecht\" gebucht wird.

<br>

## Prüfparameter

Das Anlegen von Prüfparameter erfolgt auf der Seite Parameter. Diese ist
über die Suche im Business Central über \"Prüfparameter\" und
\"Parameter\" zu erreichen. Hier sind alle Parameter der LeBit Parameter
& Qualitätssicherung gelistet.

<br>

### Prüfparameter anlegen

Über den \[+\]Neu-Button lässt sich ein neuer Parameter anlegen. Es kann
ein manueller Code für den Parameter eingegeben werden oder dieser wird
aus einer festgelegten Nummernserie generiert. Die Beschreibung ist
optional auszufüllen.

<br>

#### Parameterart

In der Spalte der Parameterart lässt sich zwischen den Optionen
\"Prüfung \" und \"Parameter\" wählen. Um den Parameter in Prüfplänen
einrichten und in Prüfaufträgen prüfen zu können, muss der Parameter die
Art \"Prüfung\" zugewiesen haben.

<br>

#### Wertart

Folgende Parameterwertarten stehen zur Verfügung:

**Dezimal:**

Parameter vom Typ \"Dezimal\" können Wertebereiche (\"Von - Bis\")
besitzen.

**Text:**

Für Parameter vom Typ \"Text\" können wählbare Textwerte in einer
Tabelle erfasst werden.

**Boolean:**

Auswahl zwischen true/false

**Datum:**

Mit Hilfe von Parametern vom Typ \"Datum\" können zusätzliche
Informationen, wie bspw. das Erstellungsdatum eines Artikels oder das
Fertigungsdatum einer Charge spezifiziert werden.

**Referenz:**

Mit Parametern des Typs \"Referenz\" kann eine Verbindung zu anderen
Tabellen innerhalb Microsoft Dynamics Business Central hinterlegt
werden.

<br>

#### Wertebereichskopie zulassen

Bei dem Feld \"Wertebereichskopie zulassen\" handelt es sich um ein
Booleanfeld. Ist der Haken in diesem Feld angewählt, kann diesem
Parameter im Prüfplan ein spezifischer Wertebereich zugeordnet werden.
Diese Einstellung lässt sich nur im Parameter direkt an- oder abwählen.

<br>

## Prüfplan

Prüfpläne können über die Suche nach \"Prüfplanübersicht\" gefunden
werden. In der Liste werden alle bestehenden Prüfpläne angezeigt. Über
die \[+\]Neu-Funktion werden neue Prüfpläne erstellt. Der Prüfplan dient
zur Festlegung der Prüfparameter und wird dem Prüfauslöser in der
Prüfvorlage zugeordnet.

<br>

### Prüfplan anlegen

Zur Erstellung des Prüfplanes ist die Eingabe eines Codes notwendig. Das
Beschreibungsfeld kann optional gefüllt werden. In der Zeilenansicht des
Prüfplans werden zu prüfende Parameter hinterlegt. Alternativ kann dazu
die \"Prüfparameter\"-Funktion im Menüband verwendet werden.

Per DropDown-Menü lassen sich Prüfparameter nach Codes auswählen. Die
Felder \"Wertart\", \"Formel\" und \"Wertebereichskopie zulassen\"
werden aus dem Parameter übernommen. Bei den restlichen Feldern handelt
es sich um Prüfplanspezifische Felder, die nur für den bestimmten
Prüfplan gelten.

<div style="text-align: center;">
    <img src="../../images/Para&QS/QS3.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 3: Prüfplankarte</figcaption>
</div>

<br>

#### Wertebereiche

Für die im Prüfplan festgelegten Parameter können spezifische
Wertebereiche eingestellt werden. Dazu dient die Funktion \"Spez.
Wertebereich\" im Menüband.

<div style="text-align: center;">
    <img src="../../images/Para&QS/QS4.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 4: Funktion "Spezifischer Wertebereich"</figcaption> <br>
</div>



Ist dem Parameter in der angewählten Zeile noch kein Wertebereich
zugeordnet erscheint die Abfrage, ob eine Kopie des Wertebereiches
erstellt werden soll. Voraussetzung dafür ist das aktivierte Feld
\"Wertebereichskopie zulassen\" am Parameter. Wird die Abfrage mit
\"Ja\" beantwortet öffnet sich die Wertebereiche Ansicht.

<div style="text-align: center;">
    <img src="../../images/Para&QS/QS5.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 5: Wertebereiche</figcaption> <br>
</div>

Über die \"Liste bearbeiten\"-Funktion öffnet sich die Zeilenansicht. Im
Feld Erfassungstext wird der Eingabewert eingegeben. Dieser
unterscheidet sich je nach Wertart des Parameters. Ist der Parameter als
Dezimalwert eingerichtet kann durch die Syntax \"(Mindestwert) ..
(Maximalwert)\" ein Bereich eingerichtet werden. Der Erfassungstext wird
bei korrekter Eingabe automatisch in das Feld \"Wert\" übertragen. Über
die Spalte Prüfentscheidung wird festgelegt, ob der eingetragene Wert
ein Fehler, eine Warnung oder OK ausgibt.

<br>

##### Werthelfer

Mithilfe des Werthelfers können die Wertebereiche festgelegt werden.
Dieser kann über die drei Punkte im Menüband erreicht werden.

<div style="text-align: center;">
    <img src="../../images/Para&QS/QS6.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 6: Werthelfer öffnen</figcaption> <br>
</div>

<div style="text-align: center;">
    <img src="../../images/Para&QS/QS7.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 7: Werthelfer leer</figcaption> <br>
</div>

Die Felder \"Grenzwert Prozent\" und \"Warnung Prozent\" berechnen
basierend auf dem Normwert die Grenz- und Warnwerte.

<div style="text-align: center;">
    <img src="../../images/Para&QS/QS8.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 8: Werthelfer gefüllt</figcaption> <br>
</div>

Bei Bestätigung mit \"Ok\" werden die Wertebereiche in der Reihenfolge
Unterer Grenzwert, Unterer Warnwert, OK, Oberer Warnwert, Oberer
Grenzwert sortiert. Der Normwert und die Prüfgrenzen werden in die
Prüfplanzeilen übertragen.

<div style="text-align: center;">
    <img src="../../images/Para&QS/QS9.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 9: Normwert, Einheit, Prüfgrenzen auf Prüfplan</figcaption> <br>
</div>

Zudem werden die hinterlegten Wertebereiche in der Infobox je Parameter
angezeigt. Dabei ist die jeweilige Entscheidung farblich markiert, wobei
rote Schriftfarbe \"Fehler\", gelbe Schriftfarbe \"Warnung\" und grüne
Schriftfarbe \"OK\" bedeutet.

<br>

### Kopiere vom Prüfplan

Mit der Funktion \"Kopiere vom Prüfplan\" lassen sich die Inhalte eines
bestehenden Prüfplans in einen neuen oder anderen Prüfplan kopieren.

Bei diesem Schritt ist zu beachten, dass bereits ein Code im neuen
Prüfplan eingegeben sein muss.

<div style="text-align: center;">
    <img src="../../images/Para&QS/QS11.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 10: Funktion "Kopiere vom Prüfplan"</figcaption> <br>
</div>

Das Klicken der Funktion öffnet die Prüfplanübersicht und ein
bestehender Prüfplan kann zum Kopieren ausgewählt werden.

<div style="text-align: center;">
    <img src="../../images/Para&QS/QS12.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 11: Übersicht Prüfpläne</figcaption> <br>
</div>

Hier wird der Prüfplan \"ABMESSUNG\" gewählt.

Nach Auswahl des Prüfplans erscheint eine Überprüfung zur Kopie des
bestehenden Prüfplaninhaltes in den neu erstellten Prüfplan.

<div style="text-align: center;">
    <img src="../../images/Para&QS/QS13.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 12: Abfrage Prüfplankopie</figcaption> <br>
</div>

Bei \"Ja\" wird der neue Prüfplan gefüllt.

<div style="text-align: center;">
    <img src="../../images/Para&QS/QS14.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 13: Prüfplan mit kopiertem Inhalt</figcaption> <br>
</div>

Auf den Parametern erfasste Wertebereich im ursprünglichen Prüfplan
werden übertragen. Die bestehenden Parameterzeilen werden im Ziel
Prüfplan ersetzt.

<br>

## Prüfintervall

Das Prüfintervall wird über die Prüfvorlage einem Artikel zugwiesen. Es
bestimmt die Anzahl der generierten Proben aus einem Beleg. Je nach Art
wird das Intervall auf unterschiedliche Bestandteile des Beleges
aufgeteilt. Unterschieden wird in die vier Arten:

**Nach Posten**

**Nach Menge**

**Mischprobe**

**Je Menge**

<br>

### Nach Posten

<div style="text-align: center;">
    <img src="../../images/Para&QS/QS15.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 14: Prüfintervall "nach Posten"</figcaption> <br>
</div>

Die Intervalleinstellung \"nach Posten\" prüft die
Artikelverfolgungszeilen und wendet darauf das Intervall an. Das
Intervall kann aus mehreren Eskalationsstufen bestehen. Zum Anlegen
einer Zeile muss ein Code eingegeben werden. Die Spalte \"Intervall\"
gibt an, ab welcher Menge an Buchungen eine Prüfung erfolgen soll. Dabei
wird immer die erste Position geprüft und daraufhin wird je nach
Intervall jede n-te Position geprüft. Entsteht eine Schlecht-Prüfung
setzt die nächste Zeile des Intervalls ein. Die Spalte \"Anzahl
notwendiger, zusammenhängender OK-Prüfungen\" legt fest wie viele
OK-Prüfungen derselben Intervallzeile nacheinander notwendig sind, damit
in der Eskalation zurück iteriert wird.

<br>

### Nach Menge

Die Intervallart \"Nach Menge\" bestimmt die Probenanzahl ab einer
bestimmten zu prüfenden Menge (Basis).

<div style="text-align: center;">
    <img src="../../images/Para&QS/QS16.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 15: Prüfintervall "nach Menge"</figcaption> <br>
</div>

Die Eskalationsstufen werden über das Referenzergebnis und die Menge
gesteuert. Die Auswahl \"Fail\" greift, wenn die letzte Probe der
vorherigen Zeile einen Fehler aufweist.

<br>

### Mischproben

Die Intervallart \"Mischprobe\" basiert auf derselben Spaltenaufteilung
wie \"Nach Posten\". Die Spalte Intervall bestimmt hierbei Posten bzw.
aufeinanderfolgende Prüfobjekte, die einer Probe zugeordnet werden
sollen. Jedes Prüfobjekt wird einer Probe zugeordnet.

<div style="text-align: center;">
    <img src="../../images/Para&QS/QS17.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 16: Prüfintervall "Mischproben"</figcaption> <br>
</div>

Je Prüfplan wird eine Probe erstellt und die im Intervall hinterlegten
Anzahl an Prüfobjekten zugeordnet.

<br>

### Je Menge

Die Intervallart \"Je Menge\" legt fest wie viele Proben je Menge
erstellt werden. Die Menge in der Spalte \"ab Menge\", legt fest für
welche Basis Menge ein Prüfauftrag erstellt wird. Besteht eine Rest
Basis Menge wird ein weiterer Prüfauftrag angelegt.

Die Eskalationsstufen werden über das Referenzergebnis und die Menge
gesteuert. Die Auswahl \"Fail\" greift, wenn die letzte Probe der
vorherigen Zeile einen Fehler aufweist.

<div style="text-align: center;">
    <img src="../../images/Para&QS/QS18.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 17: Prüfintervall "Je Menge"</figcaption>
</div>

<br>

## Prüfvorlage

Die Prüfvorlage bestimmt, wann ein Prüfauftrag erstellt werden soll. Die
Prüfvorlage wird einem oder mehreren Artikeln zugeordnet. Im Kopf der
Prüfvorlage sind der zu prüfende Artikel und die Prüfobjektzuweisung zu
finden. In der Zeilenansicht lassen sich Prüfauslöser und Prüfpläne
hinterlegen. Außerdem lässt sich bestimmen, ob dem Prüfauftrag eine
Chargen-, Paket- oder Seriennummer zugeordnet werden soll. Die
Prüfvorlage ist über das Feld \"Prüfvorlage\" am Artikel oder separat
Suchfunktion mit \"Prüfvorlageübersicht\" zu finden und einzurichten.
Mit der \[+\]Neu-Funktion wird eine neue, leere Prüfvorlagekarte
erstellt.

<div style="text-align: center;">
    <img src="../../images/Para&QS/QS19.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 18: Prüfauslöser auf Prüfvorlage</figcaption>
</div>

<br>

### Kopiere Prüfvorlage

Bereits bestehende Prüfvorlagen können kopiert werden. Über die Funktion
\"Kopiere Prüfvorlage\" kann eine bestehende Prüfvorlage ausgewählt
werden, die den aktuellen Datensatz ersetzen soll.

<div style="text-align: center;">
    <img src="../../images/Para&QS/QS20.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 19: Funktion "Kopiere Prüfvorlage"</figcaption>
</div>

<br>

### Prüfauslöser

Der Prüfauslöser bestimmt den Prozess, bei dem ein Prüfauftrag ausgelöst
wird. Ist dem Prüfauslöser ein Prüfplan zugeordnet, wird dieser
aktiviert. Über das Dropdown-Menü kann der Prüfauslöser geändert werden.
Sollen mehrere Prüfauslöser greifen, müssen diese als weitere Zeilen
hinzugefügt werden. Die aufgelisteten Prüfauslöser \"Manual\" dienen als
Platzhalter für mögliche Kundenindividuelle Prüfauslöser.

<div style="text-align: center;">
    <img src="../../images/Para&QS/QS21.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 20: Prüfauslöser</figcaption> <br>
</div>

In der Spalte \"Zugeordneter Prüfplan\" wird der Prüfplan mit den
entsprechenden Prüfparametern hinterlegt sowie das Prüfintervall.

<div style="text-align: center;">
    <img src="../../images/Para&QS/QS22.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 21: Prüfvorschlagszeilenpläne</figcaption>
</div>

<br>

### Prüfevents

Im Menüband der Prüfvorlagekarte befinden sich die Prüfevents. Hier
können die Prüfobjekte Chargen-, Paket- und Seriennummern für bestimmte
Aktionen gesperrt werden. In den Booleanfeldern am Ende der Zeile wird
festgelegt bei welcher Qualität das Prüfobjekt gesperrt werden soll und
somit nicht mehr in dem entsprechenden Prozess genutzt werden kann.

<div style="text-align: center;">
    <img src="../../images/Para&QS/QS23.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 22: Prüfevents mit Prüfereignis</figcaption>
</div>

<br>

## Artikel einrichten

Wurde eine Prüfvorlage angelegt und ein Prüfauslöser mit einem Prüfplan
aktiviert muss der Prüfplan einem Artikel zugewiesen werden. Die
Zuordnung geschieht über das Feld \"Prüfvorlage\" auf der Artikelkarte.

<div style="text-align: center;">
    <img src="../../images/Para&QS/QS24.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 23: Prüfvorlage auf Artikelkarte</figcaption> <br>
</div>

Außerdem kann optional eine Artikelverfolgung angelegt werden. Wird
diese im Herkunftsbeleg gefüllt dienen Chargen-, Paket- und
Seriennummern als Prüfobjekte im Prüfauftrag und der Probe.