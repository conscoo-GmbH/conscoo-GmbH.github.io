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

Die LeBit Demand Query App stellt für die Materialbeschaffung und Sicherstellung der Ersatzteilverfügbarkeit die „Bedarfsanforderung“ (BANF) zur Verfügung. Die Bedarfsanforderung ist die Einbindung der Instandhaltungsmitarbeiter in den Einkaufsprozess für Ersatzteile (Artikel). <br>

## Seiten

<br>

Die App beinhaltet mehrere neue Seiten für Business Central, die bei der Bearbeitung von Bedarfsanforderungen unterstützen.
Bedarfsanforderungen

<br>

#### Bedarfsanforderungen

<br>

Die Seite Bedarfsanforderungen (lbtdq Demand Query List (5272895, List)) ist eine Listenansicht aller vorhandenen Bedarfsanforderungen. Aus der Liste kann die gesuchte Bedarfsanforderung ausgewählt und geöffnet werden.

In der Übersicht können Funktionen wie neue Bedarfsanforderungen erstellen, Genehmigungen anfordern usw. ausgeführt werden. <br>

<div style="text-align: center;">
    <img src="../../images/BANF/BANF3.png" alt="Abbildung 3: LeBit Bedarfsanforderung Einrichtung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 3: Bedarfsanforderungen   </figcaption>
    <br>
</div>

<br>

#### Bedarfsanforderung

<br>

Auf der Seite Bedarfsanforderung (lbtdq Demand Query (5272890, Document)) wird die BANF bearbeitet.

Nach dem Hinterlegen nötiger Informationen im Register Allgemein (z. B. Anforderer, Lagerortcode) können in den Zeilen die benötigten Artikel hinzugefügt werden. <br>

<div style="text-align: center;">
    <img src="../../images/BANF/BANF4.png" alt="Abbildung 4: LeBit Bedarfsanforderung Einrichtung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 4: Bedarfsanforderung </figcaption>
    <br>
</div>

<br>

#### Bedarfsanforderungszeilen

<br>

Auf der Seite Bedarfsanforderungszeilen (lbtdq Demand Query Lines (5272892, List)) können einzelne Zeilen aus Bedarfsanforderungen ausgewählt und per Funktion „Einkaufsdokumente erstellen“ Einkaufsbestellungen erstellt werden.

> [!NOTE]
> Aus der Bedarfsanforderung kann durch Klick auf das Feld „Betrag“ eine gefilterte Ansicht der Bedarfsanforderungszeilen geöffnet werden.

<br>

<div style="text-align: center;">
    <img src="../../images/BANF/BANF5.png" alt="Abbildung 3: LeBit Bedarfsanforderung Einrichtung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 5: Bedarfsanforderungzeilen   </figcaption>
    <br>
</div>

<br>

#### Bedarfsanforderung Posten

<br>

Auf der Seite Bedarfsanforderung Posten (lbtdq Demand Query Entries (5272897, List)) ist eine Listenansicht aller vorhandenen Posten der Bedarfsanforderungen.
Zustand der Bedarfsanforderungen <br>

#### Zustand der Bedarfsanforderungen

<br>

Auf der Seite Zustand der Bedarfsanforderungen (lbtdq Condition DemandQuer.s (5272898, List)) können alle Bedarfsanforderungen und ihr aktueller Stand eingesehen werden.
Bedarfsanforderungsarchive <br>

#### Bedarfsanforderungsarchive

<br>

Auf der Seite Bedarfsanforderungsarchive (lbtdq Demand Query Archives (5272893, List)) werden alle beendeten Bedarfsanforderungen verwahrt. Diese werden nur archiviert, wenn die Archivierung in der LeBit Bedarfsanforderung Einrichtung aktiviert ist. <br>

<div style="text-align: center;">
    <img src="../../images/BANF/BANF6.png" alt="Abbildung 3: LeBit Bedarfsanforderung Einrichtung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 6: Bedarfsanforderungsarchive  </figcaption>
    <br>
</div>

## Zusätzliche Umsetzung

<br>

Die LeBit Demand Query App enthält weitere Funktionen zur Erleichterung der Arbeit mit Bedarfsanforderungen.

<br>

### Aufgabe

<br>

#### Erledigte Bedarfsanforderungen löschen

Die Aufgabe „Erledigte Bedarfsanforderungen löschen“ (lbtdq Del. Finished Queries (5272891, Berichtsanforderung)) löscht Bedarfsanforderungen im Status „Beendet“. <br>

<div style="text-align: center;">
    <img src="../../images/BANF/BANF7.png" alt="Abbildung 3: LeBit Bedarfsanforderung Einrichtung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 7: Erledigt Bedarfsanforderungen löschen  </figcaption>
    <br>
</div>

### Funktion

<br>

#### Mehrfachauswahl aus der BANF

<br>

Mehrere Artikel können gleichzeitig den Zeilen hinzugefügt werden, indem die Funktion Artikel auswählen… verwendet wird. <br>

<div style="text-align: center;">
    <img src="../../images/BANF/BANF8.png" alt="Abbildung 3: LeBit Bedarfsanforderung Einrichtung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 8: Mehrfachauswahl  </figcaption>
    <br>
</div>

### Feld

<br>

#### BANF neuer Status 'abgelehnt' inkl. Löschroutine

<br>

Dem Feld „Status“ wurde der Status „abgelehnt“ hinzugefügt. Wird die Aufgabe „Erledigte Bedarfsanforderungen löschen“ ausgeführt, werden auch alle Bedarfsanforderungen mit dem Status „abgelehnt“ gelöscht.