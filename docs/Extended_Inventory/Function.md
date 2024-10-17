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

## Erstellung des Inventurauftrags

<br>

Es wird ein neuer Inventurauftrag erstellt. Über die
Standardfunktionalität unter \"Vorbereiten -> Berechnen -> Zeilen
berechnen...\" werden die Inventurauftragszeilen aufgebaut.

<!-- <div style="text-align: center;">
<br>
<img src="../../images/Extended_Inventory/Extended_Inventory2.png" alt="Workflowreaktion, Genehmigungseinstellungen" style="width: 85%; height: auto;">
<figcaption>Abbildung 2: Standardfunktion "Zeilen berechnen..." </figcaption>
</div> -->

<br>

### Erstellen einer Inventurerfassung

<br>

Über die Standardfunktion \"Neue Erfassung erstellen\" kann zu dem
Inventurauftrag eine neue Erfassung erstellt werden. Soll pro erwarteter
Inventurverfolgungszeile eine neue Inventurerfassungszeile erstellt
werden, muss bei Ausführen der Funktion der Punkt \"Neue Zeile für jede
Inventurverfolgung\" aktiviert sein. <br>

<div style="text-align: center;">
<br>
<img src="../../images/Extended_Inventory/Extended_Inventory3.png" alt="Workflowreaktion, Genehmigungseinstellungen" style="width: 85%; height: auto;">
<figcaption>Abbildung 2: Option "Neue Zeile für jede erwartete Inventurverfolgung" </figcaption> <br>
</div>


Nach der Bestätigung durch \"OK\" wird eine neue Inventurerfassung
erstellt. Wurde die zuvor genannte Option aktiviert, wird je erwarteter
Inventurverfolgungszeile eine Inventurerfassungszeile abgegrenzt durch
Chargennr./Seriennr. erstellt. <br>

<div style="text-align: center;">
<br>
<img src="../../images/Extended_Inventory/Extended_Inventory4.png" alt="Workflowreaktion, Genehmigungseinstellungen" style="width: 85%; height: auto;">
<figcaption>Abbildung 3: Inventurerfassungszeilen </figcaption> <br>
</div>

Innerhalb der Inventurerfassung ist es nicht möglich auf ggfs.
hinterlegte Dimensionen zuzugreifen.

<br>

### Beenden einer Inventurerfassung

<br>

Der Aufruf \"Alle Abweichenden Verfolgungszeilen\" wurde im Kopf des
Inventurauftrags im Aktionsmenü unter \"Zugehörig\" eingebaut. Der
Aufruf wird ohne Filter auf eine Inventurauftragszeile eingebaut. Dieser
Aufruf steht standardmäßig auch auf Zeilenebene zur Verfügung und ist
dort auf die Inventurauftragszeilen gefiltert.

Werden innerhalb der Inventurerfassungszeilen zur Inventurauftragszeile
abweichende Werte erfasst und der Status der Inventurerfassung auf
\"Beendet\" gesetzt, werden diese Zeilen in die abweichenden
Verfolgungszeilen des Inventurauftrags geschrieben. <br>

<div style="text-align: center;">
<br>
<img src="../../images/Extended_Inventory/Extended_Inventory5.png" alt="Workflowreaktion, Genehmigungseinstellungen" style="width: 85%; height: auto;">
<figcaption>Abbildung 4: Inventurauftrag - Aufruf "Alle abweichenden Verfolgungszeilen" aus dem Kopf </figcaption> <br>
</div>

<div style="text-align: center;">
<br>
<img src="../../images/Extended_Inventory/Extended_Inventory6.png" alt="Workflowreaktion, Genehmigungseinstellungen" style="width: 85%; height: auto;">
<figcaption>Abbildung 5: Inventurauftrag - Aufruf "Alle abweichenden Verfolgungszeilen" aus den Zeilen</figcaption> <br>
</div>

Auf der sich öffnenden Seite werden die abweichend erfassten Zeilen
inklusive ihrer Dimensionen angezeigt. <br>

<div style="text-align: center;">
<br>
<img src="../../images/Extended_Inventory/Extended_Inventory7.png" alt="Workflowreaktion, Genehmigungseinstellungen" style="width: 85%; height: auto;">
<figcaption>Abbildung 6: Abweichende Inventurverfolgungszeile gefiltert auf Inventurauftragszeile </figcaption> 
</div>

<br>

## Buchen mit Postendimensionen

<br>

Der Aufruf erfolgt im gebuchten Inventurauftrag auf Zeilenebene über
\"Zugehörig -> Dimensionen\". Dimensionen werden nur erzeugt, wenn bei
der Einrichtung der Haken bei \"Dimensionen von Posten\" gesetzt ist.

Es wurden neue Artikelposten mit unterschiedlichen Kriterien und
abweichenden Dimensionen erzeugt. Sofern ein Artikel nicht
verfolgungspflichtig ist, werden die Dimensionen in die
Inventurauftragszeile geschrieben. <br>

<div style="text-align: center;">
<br>
<img src="../../images/Extended_Inventory/Extended_Inventory8.png" alt="Workflowreaktion, Genehmigungseinstellungen" style="width: 85%; height: auto;">
<figcaption>Abbildung 7: Erzeugung von Artikelposten </figcaption> <br>
</div>

<div style="text-align: center;">
<br>
<img src="../../images/Extended_Inventory/Extended_Inventory9.png" alt="Workflowreaktion, Genehmigungseinstellungen" style="width: 85%; height: auto;">
<figcaption> Abbildung 8: Berechnete Inventurauftragszeilen</figcaption> <br>
</div>

Die gebuchten Inventurauftragszeilen werden um die Dimensionen des
Ursprungspostens ergänzt, auch bei nicht verfolgungspflichtigen
Artikeln. Dabei wird folgender Artikelposten berücksichtigt:

1.  Artikelnummer = Artikelnummer der Inventurauftragszeile

2.  Lagerort = Lagerort der Inventurauftragszeile

3.  Chargennummer/Seriennummer = Chargennummer/Seriennummer der

Inventurverfolgungszeile

4.  Restmenge <> 0

Existieren mehrere Artikelposten im Filter, wird nur der letzte
Artikelposten, sortiert nach \"Lfd. Nr.\", verwendet. <br>

<div style="text-align: center;">
<br>
<img src="../../images/Extended_Inventory/Extended_Inventory10.png" alt="Workflowreaktion, Genehmigungseinstellungen" style="width: 85%; height: auto;">
<figcaption> Abbildung 9: Inventurverfolgungsübersicht - Artikelposten</figcaption> 
</div>

<br>

## Erfassungsunterstützung "Vorhanden"

<br>

In der Inventurerfassungszeile wurde ein neues Kennzeichen \"Vorhanden\"
eingebaut. Der Haken ist standardmäßig nicht gesetzt.

Wird der Haken gesetzt, wird der Wert aus dem Feld \"Menge (Basis)\" aus
der Inventurverfolgungszeile in das Feld \"Menge\" der
Inventurerfassungszeile automatisch übernommen. Wenn bereits ein Wert in
dem Feld \"Menge\" erfasst war und das Kennzeichen \"Vorhanden\" wird
nachträglich gesetzt, wird der manuell erfasste Wert überschrieben. <br>

<div style="text-align: center;">
<br>
<img src="../../images/Extended_Inventory/Extended_Inventory11.png" alt="Workflowreaktion, Genehmigungseinstellungen" style="width: 85%; height: auto;">
<figcaption> Abbildung 10: "Menge" Inventurerfassungszeilen</figcaption> <br>
</div>

Wird der Haken bei \"Vorhanden\" nun wieder entfernt, wird automatisch
der Wert im Feld \"Menge\" der Inventurerfassungszeile auf 0 gesetzt. <br>

<div style="text-align: center;">
<br>
<img src="../../images/Extended_Inventory/Extended_Inventory12.png" alt="Workflowreaktion, Genehmigungseinstellungen" style="width: 85%; height: auto;">
<figcaption>Abbildung 11: autom. Zurücksetzen der Menge</figcaption> 
</div>

<br>

## Fehlerhandling

<br>

Für das Fehlerhandling wurde eine neue Funktion \"Teste Dimensionen\" im
Inventurauftrag unter \"Aktionen -> Buchen\" eingebaut.

<!-- <div style="text-align: center;">
<br>
<img src="../../images/Extended_Inventory/Extended_Inventory13.png" alt="Workflowreaktion, Genehmigungseinstellungen" style="width: 85%; height: auto;">
<figcaption>Abbildung 13: Inventurauftrag - Neue Funktion \"Teste Dimensionen\" </figcaption> <br>
</div> -->

Wird diese Funktion aufgerufen öffnet sich eine neue Seite
\"Fehlermeldungen\". Sofern Fehlermeldungen vorhanden sind, werden diese
dort detailliert angezeigt. <br>

<div style="text-align: center;">
<br>
<img src="../../images/Extended_Inventory/Extended_Inventory14.png" alt="Workflowreaktion, Genehmigungseinstellungen" style="width: 85%; height: auto;">
<figcaption>Abbildung 12: Übersicht Fehlermeldungen</figcaption> <br>
</div>


Zusätzlich wurde in den Inventurauftragszeilen eine neue Spalte
\"Zeilenfehler\" eingebaut. Das Feld ist nicht editierbar. <br>

<div style="text-align: center;">
<br>
<img src="../../images/Extended_Inventory/Extended_Inventory15.png" alt="Workflowreaktion, Genehmigungseinstellungen" style="width: 85%; height: auto;">
<figcaption>Abbildung 13: Inventurauftragszeilen - neue Spalte "Zeilenfehlen"</figcaption> 
</div>

<br>

### Dimensionsfehler beim Erstellen der Inventurauftragszeile

<br>

Tritt bei Ausführung der Funktion \"Buchen\" im Inventurauftrag ein
Fehler der Dimensionen auf, weil bspw. eine Dimension bzw. ein
Dimensionswert gesperrt ist, erfolgt beim Buchen des Inventurauftrags
eine Fehlermeldung.

Im ersten Schritt wurden neue Artikelposten mit unterschiedlichen
Kriterien und abweichenden Dimensionen erzeugt. <br>

<div style="text-align: center;">
<br>
<img src="../../images/Extended_Inventory/Extended_Inventory16.png" alt="Workflowreaktion, Genehmigungseinstellungen" style="width: 85%; height: auto;">
<figcaption>Abbildung 14: Artikelposten mit unterschiedlichen Kriterien und
abweichenden Dimensionen</figcaption> 
</div>

<br>

#### Dimensionswert gesperrt

<br>

Bevor die Inventurauftragszeilen berechnet werden, wird ein
Dimensionswert gesperrt. <br>

<div style="text-align: center;">
<br>
<img src="../../images/Extended_Inventory/Extended_Inventory17.png" alt="Workflowreaktion, Genehmigungseinstellungen" style="width: 85%; height: auto;">
<figcaption>Abbildung 15: Dimensionswert für Dimension "Abteilung Code" Gesperrt </figcaption> <br>
</div>

Im Inventurauftrag werden nun die Zeilen berechnet und die
Inventurerfassung erstellt. Wird der Inventurauftrag nun gebucht,
erfolgt eine Fehlermeldung zum gesperrten Dimensionswert.

<br>

#### Dimension gesperrt

<br>

Bevor die Inventurauftragszeilen berechnet werden, wird eine Dimension
gesperrt. <br>

<div style="text-align: center;">
<br>
<img src="../../images/Extended_Inventory/Extended_Inventory18.png" alt="Workflowreaktion, Genehmigungseinstellungen" style="width: 85%; height: auto;">
<figcaption>Abbildung 16: Dimension "Abteilung" gesperrt</figcaption> <br>
</div>

Im Inventurauftrag werden nun die Zeilen berechnet und die
Inventurerfassung erstellt. Wird der Inventurauftrag nun gebucht,
erfolgt eine Fehlermeldung zur gesperrten Dimension.

<br>

### Fehlerhandling in den Abweichenden Inventurverfolgungszeilen

<br>

Um möglichst schnell Dimensionsfehler beim Buchen des Inventurauftrages
beheben zu können, können alle Dimension innerhalb der abweichenden
Inventurverfolgungszeilen angepasst werden. <br>

<div style="text-align: center;">
<br>
<img src="../../images/Extended_Inventory/Extended_Inventory19.png" alt="Workflowreaktion, Genehmigungseinstellungen" style="width: 85%; height: auto;">
<figcaption>Abbildung 17: Dimensionen in der erw. Inventurverfolgung bearbeitbar</figcaption> <br>
</div>