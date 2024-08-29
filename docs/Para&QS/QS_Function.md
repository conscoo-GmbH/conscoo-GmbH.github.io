<style>
body {
    font-family: "Century Gothic", "CenturyGothic", "AppleGothic", sans-serif;
}
</style>

# Funktionsbeschreibung:

Sobald ein Prüfauslöser greift, wird ein Prüfauftrag in der
Prüfauftragübersicht erstellt. Im Kopf des Prüfauftrages wird die
Prüfauftragsnummer aus einer Nummernserie generiert und weitere
Auftragsdaten angegeben. Die \"Kreditornr.\" und der \"Kreditorname\"
füllen sich aus dem Herkunftsbeleg, sofern dort ein Kreditor vorhanden
ist.

<div style="text-align: center;">
    <img src="../../images/Para&QS/QS25.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 24: Prüfauftragskopf</figcaption> <br>
</div>

Die Zeilenansicht darunter wird mit den Prüfparametern des zugehörigen
Prüfplanes gefüllt.

<div style="text-align: center;">
    <img src="../../images/Para&QS/QS26.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 25: Prüfauftrag Zeilenansicht</figcaption> <br>
</div>


Im Menüband befinden sich die Funktionen zum Bearbeiten des
Prüfauftrages. Mit der Funktion \"Zeilen füllen\" werden die
Parameterzeilen aus dem zugeordneten Prüfplan eingefügt. Sind die Zeilen
bereits gefüllt erscheint eine Fehlermeldung.

<br>

## Prüfungsprozess

### Prüfauftrag 

Einer Liste aller Prüfaufträge ist über die Suche mit Suchbegriff
\"Prüfauftragübersicht\" zu finden.

Im Prüfauftrag können Proben erstellt werden. Diese werden bei
zugehöriger Artikelverfolgung bei Erstellung angelegt. Ist keine
Artikelverfolgung hinterlegt wird das Feld \"Benötigte Proben\" mit der
entsprechenden Anzahl gefüllt. Die Anzahl der Proben hängt vom
jeweiligen Intervall am Auslöser ab.

Bei angelegter Artikelverfolgung werden den Proben Prüfobjekte
zugewiesen. Die Zuordnung ist abhängig vom Prüfintervall. Über die
Aufrufe \"Erstellte Proben\", \"Gebuchte Proben\", lassen sich die Liste
der zugehörigen Proben aufrufen.

<div style="text-align: center;">
    <img src="../../images/Para&QS/QS27.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 26: Proben auf Prüfauftrag</figcaption>
</div>

<br>

### Probe

Die Proben werden auf dem Prüfauftrag gesammelt.

Zusätzlich kann über die Suche nach \"Probenübersicht\" eine Übersicht
aller offenen Proben geöffnet werden.

Die Seitenansicht der Probe gleicht dem Prüfauftrag bis auf die
Probenfelder. Die Entscheidung der Probe bestimmt die Prüfobjektqualität
an der Chargenr., Paketnr. oder Serienr. Daher werden die gemessenen
Parameterwerte in der Probe ausgefüllt und gebucht.

Wird ein Wert eingegeben füllt sich automatisch das Booleanfeld
\"Erfassung\". Die Spalte \"Prüfung erforderlich\" wird vom Prüfplan
übergeben. Außerdem wird nach Eingabe eines Wertes die Prüfentscheidung
der jeweiligen Zeile generiert.

<div style="text-align: center;">
    <img src="../../images/Para&QS/QS28.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 27: Gefüllte Parameterwerte Prüfauftragkarte</figcaption> <br>
</div>

Durch die Funktion \"Entscheidung holen\" erhält die Probe eine
Prüfentscheidung und eine Prüfobjektqualität.

<div style="text-align: center;">
    <img src="../../images/Para&QS/QS29.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 28: Probe mit Entscheidung</figcaption> <br>
</div>

Nun kann die Probe gebucht werden und das zugeordnete Prüfobjekt erhält
die Qualität Durchschnitt\". Zur Beeinflussung der Prüfobjektqualität
muss das Feld \"Erfassung\" angewählt sein.

<br>

### Prüfobjekte

Im Prozess der Qualitätssicherung wird bei Prüfobjekten von Chargennr.,
Paketnr. und Seriennr. gesprochen. Je nach Intervall werden die
Prüfobjekte eines Auftrages in die Prüfung übernommen. Die Qualität
erhalten die Prüfobjekte durch das Buchen von Proben.

Auf der Paketnr.- und Chargennr.- Informationskarte wird die \"Test
Qualität\" hinterlegt.

<div style="text-align: center;">
    <img src="../../images/Para&QS/QS30.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 29: Paketnr. Informationskarte</figcaption> <br>
</div>

In der Infobox werden die Prüfparameter sowie die geprüften Werte des
Prüfobjektes angezeigt. Um eine detailliertere Ansicht zu erhalten,
dient die Funktion \"Prüfparameter\" im Menüband, welche die Seite
Prüfparameterzusammenfassung öffnet.

<div style="text-align: center;">
    <img src="../../images/Para&QS/QS31.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 30: Prüfparameterzusammenfassung</figcaption> <br>
</div>

Es werden alle geprüften Parameter des Prüfobjektes aufgelistet.
Zusätzlich wird der Durchschnitt, der erste, letzte, niedrigste und
höchste Wert angezeigt. Die Spalte \"Anzahl Werte\" zeigt alle Proben,
die dem Prüfobjekt zugeordnet sind, sowie die geprüften Werte, aus denen
sich der Durchschnittswert errechnet.

<div style="text-align: center;">
    <img src="../../images/Para&QS/QS32.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 31: Zusammenfassung Prüfposten</figcaption>
</div>