# LeBit Contingent
 
#### Erstellt am: 15. Februar 2024
 
#### App-Version:
 
## 1. Zweck
Der Grundgedanke der Kontingente ist, der Maschinenplanung gewisse Konstanten zu geben, da in der Prozessfertigung bestimmte Eigenschaftswechsel sehr zeit- und kostenaufwändig sind. Um den Bedarf zu planen, sollen Artikel aus dem Verkauf Kontingenten zugeordnet werden. Die Zuordnung an Kontingente hat keine Auswirkung auf die Fertigungsplanung, sondern nur auf die Bedarfstermine.
 
## 2. Notwendige Einrichtungen
 
### 2.1 Aufruf
 
Die Stammdaten "Sorte" und "Kontingente" werden unter dem Reiter "LeBit" auf dem Rollencenter Verkaufsauftragsverarbeitung, Lagermitarbeiter - Lagerortverwaltungssystem und Vertriebsmanager angezeigt. Sie können aber auch aus jedem anderen Rollencenter über die Suche gefunden werden.
 
![Abbildung 1: Rollencenter Verkaufsauftragsverarbeitung](../images/Contingents_1.png)
 
Im Rollencenter Produktionsleiter sind die Seiten unter dem Register Fertigungsstammdaten zu finden.
 
![Abbildung 2: Rollencenter Produktionsleiter](../images/Contingents_2.png)
 
### 2.2 LeBit Kontingent Einrichtung
 
![Abbildung 3: LeBit Kontingent Einrichtung](../images/Contingents_3.png)
 
Die Nummernserie für die Kontingente und die Einstellung zur Kontingentsüberlastung werden in der "LeBit Kontingent Einrichtung" hinterlegt.
 
Die "Kontingentsüberlastung %" gibt an, wie viel Prozent der eigentlichen Kapazität des Kontingents überschritten werden darf.
 
"Freigabestatus verwenden" gibt an, ob bei den Kontingenten der Freigabestatus beachtet werden soll. Wenn es angeschaltet ist, dann können nur freigegebene Kontingente in Verkaufsaufträgen ausgewählt werden und nur offene Kontingente bearbeitet werden.
 
### 2.3 Sorten
Auf der Seite "Sorten" werden Sorten definiert, die eine Maschine produziert, sodass diese später den Kontingenten und bestimmten Zeiten zugeordnet werden. Die Artikel, die an einer Maschine produziert werden, erhalten eine Sorte zugewiesen.
 
![Abbildung 4: Übersicht Sorten](../images/Contingents_4.png)
 
Die Felder "Code" und "Beschreibung" unterliegen keiner Nummernserie und werden frei gewählt.
 
#### 2.3.1 Artikel
In der Artikelkarte wird dem Artikel über das Register "Allgemein" eine Sorte zugeordnet. Jedem Artikel kann nur eine Sorte zugeordnet werden, aber einer Sorte können mehrere Artikel angehören.
 
![Abbildung 5: Zuordnung Sorte am Artikel](../images/Contingents_5.png)
 
### 2.4 Kontingente
Über die Seite "Kontingente" wird den Kontingenten eine bestimmte Sorte zugeordnet. Eine Sorte kann mehreren Kontingenten zugeordnet werden, aber einem Kontingent kann nur eine Sorte zugeordnet werden.
 
![Abbildung 6: Übersicht Kontingente](../images/Contingents_6.png)
 
### 2.5 Abteilungen, Arbeitsplatzgruppen und Arbeitsplätze
Wenn ein Kontingent erstellt wird, wird dieses auch einer Abteilung, einer Arbeitsplatzgruppe und einem Arbeitsplatz zugeordnet.
 
![Abbildung 7: Abteilung, Arbeitsplatzgruppe und Arbeitsplatz beim Kontingent auswählen](../images/Contingents 7.png)
 
## 3. Funktionsbeschreibung
### 3.1 Zuordnung eines Kontingents in der Verkaufszeile
In der Verkaufszeile kann ein Kontingent ausgewählt werden. Es werden die Kontingente angezeigt, die auch der Sorte am Artikel entsprechen. Das Warenausgangsdatum wird automatisch auf das Enddatum des Kontingents gesetzt.
 
![Abbildung 8: Kontingentzuordnung in der VK-Zeile](../images/Contingents_8.png)
 
Sobald ein Kontingent in der Verkaufszeile ausgewählt und der Verkaufsauftrag gespeichert wird, wird in dem entsprechenden Kontingent die Anzahl in "Menge in Auftrag" ausgegeben und die verfügbare Restmenge angezeigt.
 
![Abbildung 9: Veränderung der Menge durch offene Verkaufsaufträge](../images/Contingents_9.png)
 
Wird ein Verkaufsauftrag freigegeben, wird die Menge aus der Verkaufszeile von "Menge in Auftrag" in "Freigegebene Menge" verschoben.
 
![Abbildung 10: Verschiebung der Menge in Freigegebene Menge](../images/Contingents_10.png)
 
Wenn die Menge des Produkts in der Verkaufszeile die Menge des Kontingents übersteigt, aber nicht die erlaubte Überlastung, dann erscheint eine Warnmeldung. Der Verkaufsauftrag, der das Kontingent überlastet, kann nicht freigegeben werden. Andere Verkaufsaufträge können allerdings freigegeben werden, solange das Kontingent nicht überlastet wird.
 
### 3.2 Workflow
Um Kontingente zu steuern, ist es möglich, einen Genehmigungsworkflow zu aktivieren. Die Auswahl und Einrichtung des Workflows erfolgt über die Workflows mit der Auswahl einer Workflowvorlage.
 
![Abbildung 11: Workflowvorlage Kontingente](../images/Contingents
_11.png)
 
![Abbildung 12: Kontingent Genehmigungsworkflow](../images/Contingents_12.png)
 
Bevor der Workflow aktiviert wird (1), müssen Einstellungen in der Datensatzeinschränkung vorgenommen werden. Diese werden vorgenommen, indem man auf die erste Antwort "(+) Fügt eine Datensatzeinschränkung hinzu." (2) klickt.
 
![Abbildung 13: Workflowreaktion, Genehmigungseinstellungen](../images/Contingents_13.png)
 
Es öffnet sich die Maske:
 
1. Nun klickt man auf die zweite Antwort, damit sich die unteren Optionen öffnen.
2. Der Genehmigertyp wird auf Genehmiger gestellt.
3. Die Einschränkungsart Genehmiger wird auf Direkter Genehmiger gestellt.
4. Die Aktion Genehmigungsbenutzereinrichtungen öffnen, damit für die einzelnen Benutzer Einrichtungen getroffen werden können.
 
![Abbildung 14: Genehmigungsbenutzereinrichtungen](../images/Contingents_14.png)
 
Die Maske "Genehmigungsbenutzereinrichtung" öffnet sich.
 
1. Die Benutzer-ID gibt den Benutzer an, der das Kontingent zurücksetzen will.
2. Die Genehmiger-ID gibt den Benutzer an, der die Genehmigung für das Zurücksetzen der Kontingente erteilt.
3. Es kann ein Genehmigungsadministrator gewählt werden, der als einziger keinen Genehmiger braucht.
 
Nachdem die Einrichtungen vorgenommen worden sind, kann die Maske geschlossen werden und die Workflowreaktion mit dem Button OK abgeschlossen werden.
 
Der Workflow kann nun aktiviert werden.
 
![Abbildung 15: Kontingent Genehmigungsworkflow aktiviert](../images/Contingents_15.png)
 
Wenn der Workflow aktiviert ist, lässt sich ein Kontingent freigeben, aber um den Status zurückzusetzen, um Veränderungen vorzunehmen, braucht man die Genehmigung des Genehmigers.
 
![Abbildung 16: Kontingent Status zurücksetzen anfordern](../images/Contingents_16.png)
 
Wenn man eine Genehmigungsanforderung gesendet hat, erhält man eine Bestätigung, dass die Anfrage gesendet wurde