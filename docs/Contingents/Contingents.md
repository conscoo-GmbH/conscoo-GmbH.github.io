# LeBit Contingent

#### Erstellt am: 15. Februar 2024

#### App-Version:

## 1. Zweck
Der Grundgedanke der Kontingente ist, der Maschinenplanung gewisse Konstanten zu geben, da in der Prozessfertigung bestimmte Eigenschaftswechsel sehr zeit- und kostenaufwändig sind. Um den Bedarf zu planen, sollen Artikel aus dem Verkauf Kontingenten zugeordnet werden. Die Zuordnung an Kontingente hat keine Auswirkung auf die Fertigungsplanung, sondern nur auf die Bedarfstermine. <br>

## 2. Notwendige Einrichtungen

### 2.1 Aufruf

Die Stammdaten "Sorte" und "Kontingente" werden unter dem Reiter "LeBit" auf dem Rollencenter Verkaufsauftragsverarbeitung, Lagermitarbeiter - Lagerortverwaltungssystem und Vertriebsmanager angezeigt. Sie können aber auch aus jedem anderen Rollencenter über die Suche gefunden werden.

<div style="text-align: center;">

<img src="../../images/Contingents/Contingents_1.png" alt="Rollencenter Verkaufsauftragsverarbeitung" style="width: 100%; height: auto;">
<figcaption>Abbildung 1: Rollencenter Verkaufsauftragsverarbeitung </figcaption> <br>

</div>

Im Rollencenter Produktionsleiter sind die Seiten unter dem Register Fertigungsstammdaten zu finden.

<div style="text-align: center;">

<img src="../../images/Contingents/Contingents_2.png" alt="Rollencenter Produktionsleiter" style="width: 100%; height: auto;">
<figcaption>Abbildung 2: Rollencenter Produktionsleiter </figcaption> <br>

</div>

### 2.2 LeBit Kontingent Einrichtung

<div style="text-align: center;">

<img src="../../images/Contingents/Contingents_3.png" alt="LeBit Kontingent Einrichtung" style="width: 100%; height: auto;">
<figcaption>Abbildung 3: LeBit Kontingent Einrichtung </figcaption> <br>

</div>

Die Nummernserie für die Kontingente und die Einstellung zur Kontingentsüberlastung werden in der "LeBit Kontingent Einrichtung" hinterlegt.

Die "Kontingentsüberlastung %" gibt an, wie viel Prozent der eigentlichen Kapazität des Kontingents überschritten werden darf.

"Freigabestatus verwenden" gibt an, ob bei den Kontingenten der Freigabestatus beachtet werden soll. Wenn es angeschaltet ist, dann können nur freigegebene Kontingente in Verkaufsaufträgen ausgewählt werden und nur offene Kontingente bearbeitet werden.
<br>

### 2.3 Sorten
Auf der Seite "Sorten" werden Sorten definiert, die eine Maschine produziert, sodass diese später den Kontingenten und bestimmten Zeiten zugeordnet werden. Die Artikel, die an einer Maschine produziert werden, erhalten eine Sorte zugewiesen.

<div style="text-align: center;">

<img src="../../images/Contingents/Contingents_4.png" alt="Übersicht Sorten" style="width: 100%; height: auto;">
<figcaption>Abbildung 4: Übersicht Sorten </figcaption> <br>

</div>

Die Felder "Code" und "Beschreibung" unterliegen keiner Nummernserie und werden frei gewählt. <br>

#### 2.3.1 Artikel
In der Artikelkarte wird dem Artikel über das Register "Allgemein" eine Sorte zugeordnet. Jedem Artikel kann nur eine Sorte zugeordnet werden, aber einer Sorte können mehrere Artikel angehören.

<div style="text-align: center;">

<img src="../../images/Contingents/Contingents_5.png" alt="Zuordnung Sorte am Artikel" style="width: 100%; height: auto;">
<figcaption>Abbildung 5: Zuordnung Sorte am Artikel </figcaption> <br>

</div>

### 2.4 Kontingente

Über die Seite "Kontingente" wird den Kontingenten eine bestimmte Sorte zugeordnet. Eine Sorte kann mehreren Kontingenten zugeordnet werden, aber einem Kontingent kann nur eine Sorte zugeordnet werden.

<div style="text-align: center;">

<img src="../../images/Contingents/Contingents_6.png" alt="Übersicht Kontingente" style="width: 100%; height: auto;">
<figcaption>Abbildung 6: Übersicht Kontingente </figcaption> <br>

</div>

### 2.5 Abteilungen, Arbeitsplatzgruppen und Arbeitsplätze
Wenn ein Kontingent erstellt wird, wird dieses auch einer Abteilung, einer Arbeitsplatzgruppe und einem Arbeitsplatz zugeordnet.

<div style="text-align: center;">

<img src="../../images/Contingents/Contingents_7.png" alt="Abteilung, Arbeitsplatzgruppe und Arbeitsplatz beim Kontingent auswählen" style="width: 100%; height: auto;">
<figcaption>Abbildung 7: Abteilung, Arbeitsplatzgruppe und Arbeitsplatz beim Kontingent auswählen </figcaption> <br>

</div>

## 3. Funktionsbeschreibung
### 3.1 Zuordnung eines Kontingents in der Verkaufszeile
In der Verkaufszeile kann ein Kontingent ausgewählt werden. Es werden die Kontingente angezeigt, die auch der Sorte am Artikel entsprechen. Das Warenausgangsdatum wird automatisch auf das Enddatum des Kontingents gesetzt.

<div style="text-align: center;">

<img src="../../images/Contingents/Contingents_8.png" alt="Kontingentzuordnung in der VK-Zeile" style="width: 100%; height: auto;">
<figcaption>Abbildung 8: Kontingentzuordnung in der VK-Zeile </figcaption> <br>

</div>

Sobald ein Kontingent in der Verkaufszeile ausgewählt und der Verkaufsauftrag gespeichert wird, wird in dem entsprechenden Kontingent die Anzahl in "Menge in Auftrag" ausgegeben und die verfügbare Restmenge angezeigt.

<div style="text-align: center;">

<img src="../../images/Contingents/Contingents_9.png" alt="Veränderung der Menge durch offene Verkaufsaufträge" style="width: 100%; height: auto;">
<figcaption>Abbildung 9: Veränderung der Menge durch offene Verkaufsaufträge </figcaption> <br>

</div>

Wird ein Verkaufsauftrag freigegeben, wird die Menge aus der Verkaufszeile von "Menge in Auftrag" in "Freigegebene Menge" verschoben.

<div style="text-align: center;">

<img src="../../images/Contingents/Contingents_10.png" alt="EVerschiebung der Menge in Freigegebene Menge" style="width: 100%; height: auto;">
<figcaption>Abbildung 10: Verschiebung der Menge in Freigegebene Menge </figcaption> <br>

</div>

Wenn die Menge des Produkts in der Verkaufszeile die Menge des Kontingents übersteigt, aber nicht die erlaubte Überlastung, dann erscheint eine Warnmeldung. Der Verkaufsauftrag, der das Kontingent überlastet, kann nicht freigegeben werden. Andere Verkaufsaufträge können allerdings freigegeben werden, solange das Kontingent nicht überlastet wird. <br>

### 3.2 Workflow
Um Kontingente zu steuern, ist es möglich, einen Genehmigungsworkflow zu aktivieren. Die Auswahl und Einrichtung des Workflows erfolgt über die Workflows mit der Auswahl einer Workflowvorlage.

<div style="text-align: center;">

<img src="../../images/Contingents/Contingents_11.png" alt="Workflowvorlage Kontingente" style="width: 100%; height: auto;">
<figcaption>Abbildung 11: Workflowvorlage Kontingente </figcaption> <br>

</div>

<div style="text-align: center;">

<img src="../../images/Contingents/Contingents_12.png" alt="Kontingent Genehmigungsworkflow" style="width: 100%; height: auto;">
<figcaption>Abbildung 12: Kontingent Genehmigungsworkflow </figcaption> <br>

</div>

Bevor der Workflow aktiviert wird (1), müssen Einstellungen in der Datensatzeinschränkung vorgenommen werden. Diese werden vorgenommen, indem man auf die erste Antwort "(+) Fügt eine Datensatzeinschränkung hinzu." (2) klickt.

<div style="text-align: center;">

<img src="../../images/Contingents/Contingents_13.png" alt="Workflowreaktion, Genehmigungseinstellungen" style="width: 100%; height: auto;">
<figcaption>Abbildung 13: Workflowreaktion, Genehmigungseinstellungen </figcaption> <br>

</div>

Es öffnet sich die Maske:

1. Nun klickt man auf die zweite Antwort, damit sich die unteren Optionen öffnen.
2. Der Genehmigertyp wird auf Genehmiger gestellt.
3. Die Einschränkungsart Genehmiger wird auf Direkter Genehmiger gestellt.
4. Die Aktion Genehmigungsbenutzereinrichtungen öffnen, damit für die einzelnen Benutzer Einrichtungen getroffen werden können.

<div style="text-align: center;">

<img src="../../images/Contingents/Contingents_14.png" alt="Genehmigungsbenutzereinrichtungen" style="width: 100%; height: auto;">
<figcaption>Abbildung 14: Genehmigungsbenutzereinrichtungen </figcaption> <br>

</div>

Die Maske "Genehmigungsbenutzereinrichtung" öffnet sich.

1. Die Benutzer-ID gibt den Benutzer an, der das Kontingent zurücksetzen will.
2. Die Genehmiger-ID gibt den Benutzer an, der die Genehmigung für das Zurücksetzen der Kontingente erteilt.
3. Es kann ein Genehmigungsadministrator gewählt werden, der als einziger keinen Genehmiger braucht.

Nachdem die Einrichtungen vorgenommen worden sind, kann die Maske geschlossen werden und die Workflowreaktion mit dem Button OK abgeschlossen werden.

Der Workflow kann nun aktiviert werden.

<div style="text-align: center;">
    <img src="../../images/Contingents/Contingents_15.png" alt="Abbildung 15: Kontingent Genehmigungsworkflow aktiviert" style="width: 75%; height: auto;">
    <figcaption>Abbildung 15: Kontingent Genehmigungsworkflow aktiviert</figcaption>
    <br>
</div>


Wenn der Workflow aktiviert ist, lässt sich ein Kontingent freigeben, aber um den Status zurückzusetzen, um Veränderungen vorzunehmen, braucht man die Genehmigung des Genehmigers.

<div style="text-align: center;">

<img src="../../images/Contingents/Contingents_2.png" alt="Kontingent Status zurücksetzen anfordern" style="width: 100%; height: auto;">
<figcaption>Abbildung 16: Kontingent Status zurücksetzen anfordern </figcaption> <br>

</div>

Wenn man eine Genehmigungsanforderung gesendet hat, erhält man eine Bestätigung, dass die Anfrage gesendet wurde.
