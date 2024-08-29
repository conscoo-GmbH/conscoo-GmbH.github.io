<style>
body {
    font-family: "Century Gothic", "CenturyGothic", "AppleGothic", sans-serif;
}
</style>

# Funktionsbeschreibung

## Feinplanung erstellen

Die Feinplanung wird pro Arbeitsgang durchgeführt und basiert auf den
Auftragsvorräten einer Arbeitsplatzgruppe.

Über die Seite der Arbeitsplatzgruppen gelangt man zu den
Auftragsvorräten der einzelnen Arbeitsplatzgruppen.

<div style="text-align: center;">
<img src="../../images/Manufacturing/Manu5.png" alt="Kontingentzuordnung in der VK-Zeile" style="width: 85%; height: auto;">
<figcaption>Abbildung 4: Arbeitsplatzgruppen Übersicht</figcaption> <br>
</div>

Auf der Seite der Arbeitsplatzgruppen Auftragsvorräte sind alle
Arbeitsgänge, aus den Fertigungsaufträgen, aufgelistet, die zu der
Arbeitsplatzgruppe gehören. In der Übersicht können die einzelnen
Eigenschaften geprüft werden, so dass gleiche Arbeitsschritte in die
Planung übernommen werden können. Ebenfalls ist der Menüaufruf
\"Feinplanung\" zu finden, über den sich die dazugehörige Maske öffnet.

<div style="text-align: center;">
<img src="../../images/Manufacturing/Manu6.png" alt="Kontingentzuordnung in der VK-Zeile" style="width: 85%; height: auto;">
<figcaption>Abbildung 5: Auftragsvorräte Übersicht</figcaption> <br>
</div>

<div style="text-align: center;">
<img src="../../images/Manufacturing/Manu7.png" alt="Kontingentzuordnung in der VK-Zeile" style="width: 85%; height: auto;">
<figcaption>Abbildung 6: Feinplanung Übersicht</figcaption> <br>
</div>



1\. Solange keine Arbeitsgänge der Fertigungsaufträge feingeplant sind,
befinden sie sich im Potenzial und haben den Planungstyp \"ungeplant\".

2\. Sind die Arbeitsgänge in der Planung; ändert sich der Status auf
\"feingeplant\".

3\. Über das Menüband werden die Arbeitsgänge aus dem Potenzial in die
Planung verschoben und wieder zurück. Die Status ändern sich
automatisch, von \"ungeplant\" in \"feingeplant\" und wieder zurück,
wenn sie verschoben werden.

4\. Es ist möglich mehrere Arbeitsgänge parallel zu verschieben.

5\. Über die Menüpunkte \"Hoch\" und \"Runter\" wird die Reihenfolge der
Arbeitsgänge, die sich in der Planung befinden, bestimmt.

<div style="text-align: center;">
<img src="../../images/Manufacturing/Manu8.png" alt="Kontingentzuordnung in der VK-Zeile" style="width: 85%; height: auto;">
<figcaption>Abbildung 7: Funktion Fertigungsaufträge öffnen über den Arbeitsgang </figcaption> <br>
</div>

Über die Buttons \"Fertigungsauftrag\" (1) \| (2) in den Menübändern von
Potenzial und Planung lässt sich der Fertigungsauftrag öffnen, der zu
diesem Arbeitsgang gehört. Darüber lässt sich der Fertigungsauftrag
überprüfen und verändern.

Die Feinplanung kann erst vorgenommen werden, wenn die Aktion \"Zeit
berechnen\" durchgeführt wird. Bevor die Aktion durchgeführt wurde, sind
die Start- und Endzeiten der Arbeitsgänge aus den dazugehörigen
Fertigungsaufträgen übernommen.

<div style="text-align: center;">
<img src="../../images/Manufacturing/Manu9.png" alt="Kontingentzuordnung in der VK-Zeile" style="width: 85%; height: auto;">
<figcaption>Abbildung 8: Funktion Zeit berechnen</figcaption> <br>
</div>

Um die Feinplanung abzuschließen, muss die Aktion \"Feinplanung
übernehmen\" genutzt werden, sodass alle hinterlegten Aktionen
gespeichert werden.

<div style="text-align: center;">
<img src="../../images/Manufacturing/Manu10.png" alt="Kontingentzuordnung in der VK-Zeile" style="width: 85%; height: auto;">
<figcaption>Abbildung 9: Feinplanung übernehmen, nachdem Zeit berechnet, wurde </figcaption> <br>
</div>

Wird die Anfrage mit \"Ja\" bestätigt, ist die Feinplanung gespeichert.
Wird eine Feinplanung nicht gespeichert, werden die geänderten Start-
und Endzeiten nicht übernommen.

<br>

## Zeit berechnen

Die \"Zeit berechnen\"-Funktion beinhaltet drei Planungsfilter,
Startdatum, Dauer und Enddatum. Das Startdatum wird zunächst automatisch
auf das aktuelle Arbeitsdatum gesetzt, kann aber auch manuell umgestellt
werden. Neben dem Datum ist auch die Uhrzeit festlegbar. Die Dauer legt
fest, wie lange die Arbeitsgänge geplant werden können. Dabei ist das
Startdatum des Arbeitsganges relevant, fällt es in die Spanne der
Zeitberechnung, wird der Arbeitsgang mitgeplant, auch wenn das Enddatum
außerhalb liegt. Wird die Dauer festgelegt, füllt sich das Enddatum
automatisch.

<div style="text-align: center;">
<img src="../../images/Manufacturing/Manu11.png" alt="Kontingentzuordnung in der VK-Zeile" style="width: 85%; height: auto;">
<figcaption>Abbildung 10: Planungsfilter beim Zeit berechnen </figcaption> <br>
</div>

Die Arbeitsgänge, die nicht in der Zeitspanne angefangen werden, werden
in das Potenzial zurück verschoben. Die Start- und Endzeiten der
Arbeitsgänge wurden auf die hinterlegte Reihenfolge geändert. Für
Arbeitsgänge, die sich vor der Zeitberechnung im Potenzial befanden,
ändert sich die Start- und Endzeit nicht.

<div style="text-align: center;">
<img src="../../images/Manufacturing/Manu12.png" alt="Kontingentzuordnung in der VK-Zeile" style="width: 85%; height: auto;">
<figcaption>Abbildung 11: Veränderung der Zeiten, nachdem die Zeit berechnet wurde </figcaption>
</div>

<br>

## Bedarfsverursacher

Über die Auftragsvorräte, der Arbeitsplatzgruppen, sowie in der
Feinplanung sind die Bedarfsverursacher der einzelnen Fertigungsaufträge
zu finden.

<div style="text-align: center;">
<img src="../../images/Manufacturing/Manu13.png" alt="Kontingentzuordnung in der VK-Zeile" style="width: 85%; height: auto;">
<figcaption>Abbildung 12: Bedarfsverursacher über Auftragsvorräte der APG </figcaption> <br>
</div>

<div style="text-align: center;">
<img src="../../images/Manufacturing/Manu14.png" alt="Kontingentzuordnung in der VK-Zeile" style="width: 85%; height: auto;">
<figcaption>Abbildung 13: Bedarfsverursacher in Feinplanung </figcaption> <br>
</div>

<div style="text-align: center;">
<img src="../../images/Manufacturing/Manu15.png" alt="Kontingentzuordnung in der VK-Zeile" style="width: 85%; height: auto;">
<figcaption>Abbildung 14: Bedarfsverursacher Informationen </figcaption> <br>
</div>

Auf der Request Page des Bedarfsverursachers ist beispielsweise der
Verkaufsauftrag zu finden, der zu diesem Bedarf geführt hat.