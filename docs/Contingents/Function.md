# Funktionsbeschreibung
 
## Zuordnung eines Kontingents in der Verkaufszeile

In der Verkaufszeile kann ein Kontingent ausgewählt werden. Es werden die Kontingente angezeigt, die auch der Sorte am Artikel entsprechen. Das Warenausgangsdatum wird automatisch auf das Enddatum des Kontingents gesetzt. <br>

<div style="text-align: center;">
<img src="../../images/Contingents/Contingents8.png" alt="Kontingentzuordnung in der VK-Zeile" style="width: 85%; height: auto;">
<figcaption>Abbildung 8: Kontingentzuordnung in der VK-Zeile </figcaption> <br>
</div>

Sobald ein Kontingent in der Verkaufszeile ausgewählt und der Verkaufsauftrag gespeichert wird, wird in dem entsprechenden Kontingent die Anzahl in "Menge in Auftrag" ausgegeben und die verfügbare Restmenge angezeigt. <br>

<div style="text-align: center;">
<img src="../../images/Contingents/Contingents9.png" alt="Veränderung der Menge durch offene Verkaufsaufträge" style="width: 85%; height: auto;">
<figcaption>Abbildung 9: Veränderung der Menge durch offene Verkaufsaufträge </figcaption> <br>
</div>

Wird ein Verkaufsauftrag freigegeben, wird die Menge aus der Verkaufszeile von "Menge in Auftrag" in "Freigegebene Menge" verschoben.
<br>

<div style="text-align: center;">
<img src="../../images/Contingents/Contingents10.png" alt="Verschiebung der Menge in Freigegebene Menge" style="width: 85%; height: auto;">
<figcaption>Abbildung 10: Verschiebung der Menge in Freigegebene Menge </figcaption> <br>
</div>

Wenn die Menge des Produkts in der Verkaufszeile die Menge des Kontingents übersteigt, aber nicht die erlaubte Überlastung, dann erscheint eine Warnmeldung. Der Verkaufsauftrag, der das Kontingent überlastet, kann nicht freigegeben werden. Andere Verkaufsaufträge können allerdings freigegeben werden, solange das Kontingent nicht überlastet wird.

<br>

## Workflow

Um Kontingente zu steuern, ist es möglich, einen Genehmigungsworkflow zu aktivieren. Die Auswahl und Einrichtung des Workflows erfolgt über die Workflows mit der Auswahl einer Workflowvorlage. <br>

<div style="text-align: center;">
<img src="../../images/Contingents/Contingents11.png" alt="Workflowvorlage Kontingente" style="width: 85%; height: auto;">
<figcaption>Abbildung 11: Workflowvorlage Kontingente </figcaption> <br>
</div>
 
<div style="text-align: center;">
<img src="../../images/Contingents/Contingents12.png" alt="Kontingent Genehmigungsworkflow" style="width: 85%; height: auto;">
<figcaption>Abbildung 12: Kontingent Genehmigungsworkflow </figcaption> <br>
</div>
 
Bevor der Workflow aktiviert wird (1), müssen Einstellungen in der Datensatzeinschränkung vorgenommen werden. Diese werden vorgenommen, indem man auf die erste Antwort "(+) Fügt eine Datensatzeinschränkung hinzu." (2) klickt.

<div style="text-align: center;">
<br>
<img src="../../images/Contingents/Contingents13.png" alt="Workflowreaktion, Genehmigungseinstellungen" style="width: 85%; height: auto;">
<figcaption>Abbildung 13: Workflowreaktion, Genehmigungseinstellungen </figcaption> <br>
</div>
 
Es öffnet sich die Maske:

<ol>
    <li> Nun klickt man auf die zweite Antwort, damit sich die unteren Optionen öffnen.
    <li> Der Genehmigertyp wird auf Genehmiger gestellt.
    <li> Die Einschränkungsart Genehmiger wird auf Direkter Genehmiger gestellt.
    <li> Die Aktion Genehmigungsbenutzereinrichtungen öffnen, damit für die einzelnen Benutzer Einrichtungen getroffen werden können.
</ol>

<div style="text-align: center;">
<br>
<img src="../../images/Contingents/Contingents14.png" alt="Genehmigungsbenutzereinrichtungen" style="width: 85%; height: auto;">
<figcaption>Abbildung 14: Genehmigungsbenutzereinrichtungen </figcaption> <br>
</div>
 
Die Maske "Genehmigungsbenutzereinrichtung" öffnet sich.

<ol>
    <li> Die Benutzer-ID gibt den Benutzer an, der das Kontingent zurücksetzen will.
    <li> Die Genehmiger-ID gibt den Benutzer an, der die Genehmigung für das Zurücksetzen der Kontingente erteilt.
    <li> Es kann ein Genehmigungsadministrator gewählt werden, der als einziger keinen Genehmiger braucht.
</ol>

Nachdem die Einrichtungen vorgenommen worden sind, kann die Maske geschlossen werden und die Workflowreaktion mit dem Button OK abgeschlossen werden.
 
Der Workflow kann nun aktiviert werden. <br>

<div style="text-align: center;">
<img src="../../images/Contingents/Contingents15.png" alt="Abbildung 15: Kontingent Genehmigungsworkflow aktiviert" style="width: 85%; height: auto;">
<figcaption>Abbildung 15: Kontingent Genehmigungsworkflow aktiviert</figcaption>
<br>
</div>

Wenn der Workflow aktiviert ist, lässt sich ein Kontingent freigeben, aber um den Status zurückzusetzen, um Veränderungen vorzunehmen, braucht man die Genehmigung des Genehmigers. <br>

<div style="text-align: center;">
<img src="../../images/Contingents/Contingents16.png" alt="Kontingent Status zurücksetzen anfordern" style="width: 85%; height: auto;">
<figcaption>Abbildung 16: Kontingent Status zurücksetzen anfordern </figcaption> <br>
</div>

Wenn man eine Genehmigungsanforderung gesendet hat, erhält man eine Bestätigung, dass die Anfrage gesendet wurde.