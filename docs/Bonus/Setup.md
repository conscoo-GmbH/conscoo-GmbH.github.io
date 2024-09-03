<style>
body {
    font-family: "Century Gothic", "CenturyGothic", "AppleGothic", sans-serif;
}
</style>

# Notwendige Einrichtungen

<br>

## Installation der notwendigen Apps

Neben der App \"LeBit Bonus\" ist die App \"Prozessmanagement\" zu
installieren. Diese ist wichtig für die Prozessnummer, über welche alle
Posten zu den Bonusverträgen angezeigt werden. Die Prozessnummer
befindet sich am Bonusvertrag.

Die App \"LeBit Bonus\" ist abhängig von der App \"LeBit
Prozessmanagement\", welche bei der Installation aus AppSource
automatisch mitinstalliert wird. Diese bringt eine Prozessnummer mit
sich, welche über alle Posten zu den Bonusverträgen angezeigt wird.
Außerdem findet sie sich am Bonusvertrag.

<br>

### LeBit Bonus

Die App \"LeBit Bonus\" ist nach erfolgreicher Installation unter
„Erweiterungsverwaltung" zu finden.

Des Weiteren ist die App \"Prozessmanagement\" zu installiere

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus1.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 1: Erweiterungsverwaltung</figcaption>
</div>

<br>

### LeBit Prozessmanagement

Die App \"Prozessmanagement\" ist nach erfolgreicher Installation unter
„Erweiterungsverwaltung" zu finden.

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus2.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 2: Erweiterungsverwaltung</figcaption>
</div>

<br>

## Grundeinrichtung

Bevor alle Funktionen der App verwendet werden können, müssen bestimmte
Grundeinrichtungen vorgenommen werden.

<br>

### LeBit Bonus Einrichtung 

Die zentrale Bonus Einrichtung befindet sich auf der Registerkarte
„LeBit Bonus Einrichtung".

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus3.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 3: LeBit Bonus Einrichtung</figcaption>
    <br>
</div>

Hier gibt es zwei unterschiedliche Varianten, um Bonusrückstellungen zu
erzeugen. Entweder werden die ermittelten Rückstellungsbeträge in ein
Buchblatt geschrieben und über Sachkonten verbucht oder es werden
sogenannte Bonusrückstellungsbelege erzeugt, in denen anhand von
Zu/Abschlägen Rückstellungen ermittelt werden.

<br>

### Feldbeschreibung der LeBit Bonus Einrichtung

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus4.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 4: LeBit Bonus Einrichtung</figcaption>
    <br>
</div>

| Feld                                    | Beschreibung                                                                                                                                                                                                                                    |
|-----------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Menüband Bonus Einrichtung**          |                                                                                                                                                                                                                                                |
| Zugehörig/ Bonusverträge                | Hier können Bonusverträge angezeigt bzw. angelegt werden.                                                                                                                                                                                      |
| **Nummernserie**                        |                                                                                                                                                                                                                                                |
| Bonusvertrags-nummer                    | Hier wird die Nummernserie hinterlegt, welche für den Bonus Vertrag verwendet werden soll.                                                                                                                                                     |
| Rückstellungs-gutschriftsnummer         | Hier wird die Nummernserie für die interne Gutschrift hinterlegt, wenn für Rückstellungen Bonusrückstellungsbelege erzeugt werden sollen. Die Belegnummer wird sowohl für die Gutschrift zur Rückstellungsbildung als auch für die Rechnung zur Rückstellungsauflösung verwendet. Sie wird für die gebuchten Belege unverändert übernommen. |
| Abrechnungs-gutschriftnummer            | Hier wird die Nummernserie hinterlegt, welche für die Bonusabrechnung verwendet werden soll.                                                                                                                                                    |
| **Rückstellungen**                      |                                                                                                                                                                                                                                                |
| Rückstellungsmodus                      | Auswahl des Rückstellungsmodus                                                                                                                                                                                                                 |
| Buch.-Blattvorlage                      | Eintragen der Buchblattvorlage, in dem sich das Buchblatt für die Bonusrückstellungen befindet                                                                                                                                                  |
| Buch.-Blattname                         | Auswahl des Buchblatts, in das die zu verbuchenden Bonusrückstellungen eingetragen werden                                                                                                                                                       |
| Geschäftsbuchungs-gruppe                | Geschäftsbuchungsgruppe, die für die Rückstellungsgutschrift in den Rückstellungsbelegen verwendet wird – hier sollte, sofern nicht vorhanden, eine interne Geschäftsbuchungsgruppe angelegt werden, um die gewünschten Konten anzusprechen        |
| Debitorenbuchungs-gruppe                | Debitorenbuchungsgruppe, die für die Rückstellungsermittlung in den Rückstellungsbelegen verwendet wird – die Einrichtung der Debitorenbuchungsgruppe sollte dementsprechend auf ein Konto für Bonusrückstellungen verweisen (siehe auch: [Debitorenbuchungsgruppe für Rückstellungsgutschrift](#debitorenbuchungsgruppe-für-rückstellungsgutschrift)) |
| Ursachencode                            | Alle gebuchten Rückstellungsposten werden mit einem Ursachencode gekennzeichnet. Durch diese Kennzeichnung ist es möglich, Sachposten zusammen zu filtern und später Rückstellungen manuell aufzulösen.                                          |
| **Rückstellungsauflösung**              |                                                                                                                                                                                                                                                |
| Rückstellungs-auflösungsmodus           | Auswahl, ob Rückstellungen manuell oder automatisch aufgelöst werden sollen. Diese Einrichtung greift beim Rückstellungsmodus "Buchungszeile".                                                                                                  |
| Buchblatt Bonusrückstellungs-auflösung  | Buchblatt zur Auflösung der verbuchten Bonusrückstellungen                                                                                                                                                                                      |

<br>

#### Rückstellungsmodus - Buchblatt

Bei diesem Modus werden die zu verbuchenden Rückstellungen in ein
Buchblatt übergeben.

Die notwendigen Sachkonten für die Rückstellungen werden an den
\"Debitorenbuchungsgruppen\" in den zusätzlichen Spalten
\"Bonusrückstellungskonto\" und \"Bonusrückstellungsgegenkonto\"
hinterlegt und sind je nach Sachkontenrahmen auszuwählen.

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus5.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 5: Hinterlegung der Sachkonten Rückstellungsbuchung Modus
Buchblatt</figcaption>
    <br>
</div>

Die Auflösung der Rückstellungen kann manuell oder automatisch beim
Starten des Bonuslaufs geschehen. Ist für den Auflösungsmodus
\"automatisch\" gewählt, muss kein extra Buchblatt verbucht werden. Die
Verfahrensweise bei diesem Rückstellungsmodus ist für den Anwender
teilweise komfortabler als beim Modus \"Gutschrift\".

<br>

#### Rückstellungsmodus - Gutschrift 

Bei dieser Rückstellungsvariante erzeugt das Modul anstelle von
Buchblattzeilen Verkaufsgutschriften mit einem eigenen internen
Nummernkreis. In diesen Gutschriften werden entsprechende
Rückstellungszu -/abschläge zur Rückstellungsermittlung verwendet (siehe
auch: [Anlegen der Rückstellungs- und Abrechnungszu-
/abschläge](#anlegen-der-rückstellungs--und-abrechnungszuschläge)).

Der Vorteil dieser Variante ist, dass die Zu-/Abschlagszeilen Wertposten
erzeugen, welche sich auf die Artikelbewegungen beziehen. In
Auswertungen auf Basis der Wertposten kann jetzt der Verkaufsbeleg um
den Soll-Bonus gemindert werden.

Etwas erhöhter Aufwand entsteht für den Anwender bei diesem
Rückstellungsmodus dadurch, dass die Rückstellungsauflösung nur
halbautomatisch erfolgt. Hier wird zur Auflösung ein Gegenbeleg (in
diesem Fall eine Verkaufsrechnung) erstellt, welche vom Anwender
verbucht werden muss. Analog zur Rückstellungsbildung erfolgt auch die
Auflösung der Rückstellung mit Hilfe von Zu-/Abschlägen.

Als Debitor für die Rückstellungsbelege wird ein statistischer Debitor
zur internen Verrechnung verwendet (siehe auch: [Anlegen des internen
Debitors](#anlegen-des-internen-debitors)).

<br>

#### Buch.-Blattvorlage und Buch.-Blattname

Die beim Rückstellungsmodus \"Buchblatt\" zu verwendende
Buch.-Blattvorlage muss, sofern noch nicht vorhanden, angelegt und
eingetragen werden.

Des Weiteren sind hier die notwendigen Buchblätter für die Bonus
Rückstellung und zur Auflösung der Rückstellung zu hinterlegen.

Das Feld \"MwSt.Einr. in Bu.Bl.Zeile kopieren\" ist nicht zu setzten.

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus6.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 6: Fibu Buch.-Blattnamen</figcaption>
    <br>
</div>

Die Buchblätter sind entsprechend in der \"LeBit Bonus Einrichtung\" zu
hinterlegen.

<br>

#### Geschäftsbuchungsgruppe für Rückstellungsgutschrift 

Falls noch nicht vorhanden, ist hier eine interne
Geschäftsbuchungsgruppe zu erstellen.

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus7.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 7: Geschäftsbuchungsgruppe INTERN </figcaption>
    <br>
</div>

Für die korrekte steuerliche Behandlung ist hier ebenfalls die MwSt
Geschäftsbuchungsgruppe zu hinterlegen und gemäß der bekannten
Standardeinrichtungen zu ergänzen (MwSt Buchungsmatrix).

<br>

#### Debitorenbuchungsgruppe für Rückstellungsgutschrift

Mit der Debitorenbuchungsgruppe wird das Rückstellungskonto, sowie das
Gegenkonto angesprochen. Für die Buchungsgruppe sollte dazu, als
Debitorensammelkonto, ein internes Forderungskonto angelegt werden. Die
entsprechenden Rückstellungskonten sind je nach Sachkontenrahmen
auszuwählen.

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus6.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 8: Hinterlegung der Sachkonten Rückstellungsbuchung Modus
Gutschrift </figcaption>
    <br>
</div>

### Einrichtung Ursachencodes

Der Ursachencode kann neu angelegt werden und sollte zur einfachen
Erkennung einen treffenden Code, sowie Beschreibung bekommen.

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus9.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 9: Ursachencode </figcaption>
</div>

<br>

#### Einrichtung Prozessmanagement

Mit den Prozessmanagement besteht die Möglichkeit Posten mit ein und
derselben Nummer zu identifizieren.

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus10.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 10: Einrichtung Prozessmanagement </figcaption>
    <br>
</div>

An einem Bonusvertrag wird eine Prozessnummer analog der Vertragsnummer
automatisch angelegt. Alternativ kann die Prozessnummer manuell mit
einer Nummer aus der hier hinterlegten Nummernserie verwendet bzw.
manuell erfasst werden, je nach Einstellung der Nummernserie.

<br>

#### Debitoren & Verkauf Einrichtung

Beim Bilden von Rückstellungen, sowie beim Bonuslauf, durchläuft das
System alle Rechnungen und Gutschriften für den entsprechenden Zeitraum
und Debitor. Damit die Gutschriften berücksichtigt werden, müssen in der
\"Debitoren & Verkauf Einrichtung\" jeweils die Felder \"Lieferschein b.
VK-Rechnung\" und \"Rücksendung bei Gutschrift\" gesetzt werden.

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus11.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 11: Debitoren & Verkauf Einr. </figcaption>
</div>

<br>

### Anlegen der benötigten Stammdaten 

Zum Bilden und Auflösen von Rückstellungen, werden für die erzeugten
Belege bestimmte Stammdaten, wie ein \"Artikel Zu-/abschlag\" oder der
\"statistische Debitor\" für Rückstellungsbelege für den Modus
\"Gutschrift\" benötigt.

Die Erstellung der Bonusabrechnung erfolgt ebenfalls über \"Artikel
Zu-/abschlag\".

Folgende Punkte erklären deren Einrichtung und können als Vorschlag für
Buchungsgruppen und ähnliches dienen.

<br>

#### Anlegen des internen Debitors

Der interne statistische Debitor wird für die Gutschrift zur
Rückstellungsbildung und Rechnung zur Auflösung als Debitor eingetragen.
Er muss, sofern noch nicht vorhanden, neu angelegt werden. Zur schnellen
Identifikation sollte als Nummer eine passende Beschreibung verwendet
werden.

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus12.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 12: interner Debitor </figcaption>
    <br>
</div>

Als Debitoren- und Geschäftsbuchungsgruppen sollten die davor angelegten
internen Buchungsgruppen verwendet werden. Durch deren Kombination
werden beim Verbuchen der Belege dich entsprechenden Konten
angesprochen.

<br>

#### Produktbuchungsgruppe

Für die anzulegenden \"Artikel Zu-/Abschläge\" für die Bonusrückstellung
sowie der Bonusabrechnung ist eine Produktbuchungsgruppe anzulegen.

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus13.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 13: Produktbuchungsgruppe </figcaption>
    <br>
</div>

In der \"Buchungsmatrix Einrichtung\" müssen der Produktbuchungsgruppe
\"Bonus\" die entsprechenden Kombinationen zugeordnet werden.

Durch diese ergibt sich der Vorteil, dass unterschiedliche Sachkonten
angesprochen werden können und darüber hinaus eine differenziertere
Auswertung über die Wertposten vorgenommen werden kann.

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus14.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 14: Buchungsmatrix Bonus </figcaption>
    <br>
</div>

Werden beispielsweise Rückstellungen erzeugt oder aufgelöst, tritt die
Kombination

Geschäftsbuchungsgruppe = INTERN und Produktbuchungsgruppe = BONUS auf.
Damit diese

Kombination auftritt, muss der Debitor für interne Buchungen die
Geschäftsbuchungsgruppe INTERN

haben. Bei der Bonusabrechnung wiederrum, wird der Bonusempfänger des
Vertrages in die Gutschrift eingetragen, welcher beispielswiese die
Geschäftsbuchungsgruppe EU, EXPORT, INLAND etc. haben kann, wodurch eine
andere Kombination auftritt.

<br>

#### Anlegen der Rückstellungs- und Abrechnungszuschläge

Wenn der Rückstellungsmodus \"Gutschrift\" ausgewählt ist, müssen für
die Bonusverträge die entsprechenden Zu-/Abschläge eingerichtet werden.
Diese sind wie folgt einzurichten:

Rückstellung Bonus

Verkaufsbonus

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus15.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 15: Artikel Zu-/Abschläge </figcaption>
    <br>
</div>

Es ist die Produktbuchungsgruppe \"Bonus\" zu hinterlegen. Die
notwendigen Sachkonten werden entsprechend der Buchungsmatrix verwendet
(siehe auch: [Produktbuchungsgruppe](#produktbuchungsgruppe)).

Es ist zu beachten, dass sich die Zu-/Abschläge an den Bonusverträgen
zwischen \"Rückstellung Bonus\" (wird für die Gutschrift zum Verbuchen
und in der Rechnung zum Auflösen von Rückstellungen verwendet) und
\"Abrechnung Bonus\" (wird in der Bonusabrechnungsgutschrift verwendet)
unterscheiden.

Dies muss in der Einrichtung, sowie der Anlage von neuen Bonusverträgen
berücksichtigt werden.

<br>

#### Debitorenbonusgruppe

Die Debitorenbonusgruppe kann an Debitoren hinterlegt werden. Wird einem
Debitor eine Bonusgruppe zugewiesen, so kann in einem Bonusvertrag nach
dieser Gruppe gefiltert werden.

Es werden Umsätze von Debitoren mit der jeweiligen Debitorenbonusgruppe
zur Bemessungsgrundlage herangezogen.

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus16.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 16: Debitorenbonusgruppe </figcaption>
</div>

<br>

#### Artikelbonusgruppe

Die Artikelbonusgruppe kann an Artikeln hinterlegt werden.

Wird einem Artikel eine Bonusgruppe zugewiesen, so kann in einem
Bonusvertrag nach dieser Gruppe gefiltert werden. Es werden Umsätze von
Artikeln mit der jeweiligen Artikelbonusgruppe zur Bemessungsgrundlage
herangezogen.

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus17.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 17: Artikelbonusgruppe </figcaption>
</div>

<br>

### Bonusverträge 

Die Bonusverträge können über die \"LeBit Bonus Einrichtung\" bzw. über
die \"Suche\" aufgerufen und angelegt werden.

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus18.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 18: Aufruf Bonusverträge </figcaption>
    <br>
</div>

Je Vertrag können mehrere Kunden mit unterschiedlichen Lieferadressen
gepflegt werden.

<br>

#### Feldbeschreibungen der Bonusverträge

| Feld                         | Bezeichnung |
|------------------------------|-------------|
| **Allgemein**                |             |
| Nr.                          | Hier wird aus der hinterlegten Nummernserie, je nach Einstellung, eine Nummer vergeben, mit welcher der Vertrag jederzeit identifiziert werden kann. |
| Beschreibung                 | Nähere Erläuterung zum Bonusvertrag, wie z.B. der Bonusempfänger |
| Abrechnungsintervall         | Datumsformel zur Bestimmung der Abrechnungsperiode. Berechnungsformel: Letzte Abrechnung am + Abrechnungsintervall <= (kleiner gleich) Arbeitsdatum, dann wird der Vertrag beim Bonuslauf berücksichtigt |
| Gültig von                   | Hier wird das Datum erfasst, ab wann gebuchte Verkaufsbelege für die Bonusabrechnung berücksichtigt werden sollen. |
| Gültig bis                   | Hier wird das Datum erfasst, bis wann gebuchte Verkaufsbelege für die Bonusabrechnung berücksichtigt werden sollen. |
| Prozessnr.                   | Die Prozessnr. wird analog der Nummer des Vertrages automatisch erstellt, soweit diese so eingerichtet ist. Über diese Prozessnummer können alle Buchungen identifiziert werden. |
| Bonusabrechnungsart          | Es gibt drei verschieden Arten zur Berechnung einer Bonusabrechnung:<br>„% vom Umsatz“<br>„Betrag(MW)“<br>„Betrag je Einheit“<br>Die ausgewählte Art wird für die Bonusgutschrifterstellung benötigt. |
| Bonusabrechnungseinheit      | In Abhängigkeit der Bonusabrechnungsart "Betrag je Einheit" kann hier die notwendige Einheit ausgewählt werden. |
| Bonusstaffelart              | Die Staffelart gibt an, ob die Berechnung des Bonus auf Grundlage des "Absatzes" oder "Umsatzes" erfolgt. |
| Artikeleinheit               | Wird ein Bonusvertrag nach Einheiten angerechnet, ist hier die Einheit, z.B. kg, zu erfassen. Diese Einheit gilt für die Bonusstaffel. |
| Letzte Abrechnung am         | Wird nach der Bonusabrechnung vom System gefüllt.<br><br>Achtung: Wurden Bonusgutschriften vor der Verbuchung gelöscht und müssen nochmals erstellt werden, so ist dieses Feld vorab zu leeren. |
| Bonusempfänger               | Hier wird der Debitor eingetragen, der den Bonus empfängt und bei der Erstellung der Verkaufsgutschrift verwendet wird. |
| Abrechnungszuschlag          | Hinterlegung des entsprechenden Zu/-Abschlags, der bei der Erstellung der Abrechnungsgutschrift verwendet werden soll. |
| **Rückstellung**             |             |
| Debitor Rückstellungsgutschrift | Ist der Rückstellungsmodus auf "Gutschrift" eingestellt, so ist hier der interne Debitor zu hinterlegen. |
| Rückstellungswert            | Gibt den Wert zur Berechnung der Rückstellung an. |
| Rückstellungsart             | Angabe eines Rückstellungswertes (Betrag in MW, prozentual oder pro Artikeleinheit)<br>Es gibt drei verschiedene Arten, um Rückstellungen zu bilden:<br>% vom Umsatz:<br>Der Rückstellungslauf bildet prozentual anhand der Belege Rückstellungen. Für jede Rechnungs- bzw. Gutschriftzeile wird eine Buchungszeile im Rückstellungsbuchblatt erzeugt.<br>Betrag (MW):<br>Ein Festbetrag wird je nach Abrechnungszeitraum zurückgestellt.<br>Betrag je Einheit:<br>Rückstellungen bezogen auf die Menge der Artikeleinheiten aus den Verträgen. Für jede Rechnungs- bzw. Gutschriftzeile wird eine Buchungszeile im Rückstellungsbuchblatt erzeugt. |
| Rückstellungseinheit         | Ist im Vertrag hinterlegt, dass der Rückstellungslauf anhand der Option „Betrag je Einheit“ durchgeführt wird, muss eine Artikeleinheit zur Berechnung hinterlegt werden. |
| Letzte Rückstellung am       | Wird nach der Bonusrückstellung vom System gefüllt.<br><br>Achtung: Wurden Rückstellungen vor der Verbuchung gelöscht und müssen nochmals erstellt werden, so ist dieses Feld vorab zu leeren. |
| Rückstellungszuschlag        | Ist der Rückstellungsmodus auf "Gutschrift" gestellt, ist der entsprechenden Zu/-Abschlags zu hinterlegen, der bei der Erstellung der Rückstellungsgutschrift sowie zum Auflösen der Rückstellung über die Rückstellungsrechnung verwendet werden soll. |
| Bonusstaffel - Subform siehe Bonusstaffel - Berechnungsregeln |             |

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus19.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 19: Bonusvertrag </figcaption>
</div>

<br>

#### Filterung nach Debitoren, Lieferadresse

Der Bonusvertrag kann nach Debitoren wie auch Lieferadressen gefiltert
werden. Die Debitoren, für welche Umsätze für die Bonusabrechnung zu
berücksichtigen sind, sind hier zu hinterlegen.

Unter \"Zugehörig\" / \"Debitor\" öffnet sich der Filterbereich.

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus20.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 20: Bonusvertragskarte - Zugehörig Debitor </figcaption>
    <br>
</div>



<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus21.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 21: Bonus Debitoren </figcaption>
</div>

<br>

#### Filterung nach Bonusartikel, Attributfilter

Am Bonusvertrag ist zwingend der Filter für die Bonusartikel zu
hinterlegen.

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus22.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 22: Bonusvertragskarte - Zugehörig Artikel </figcaption>
    <br>
</div>

Wird nicht nach bestimmten Artikeln gefiltert, ist der Filter über alle
Artikel zu setzten, ansonsten bei Bedarf je Artikel.

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus23.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 23: Bonus Artikel </figcaption>
    <br>
</div>

Nach dem Setzten eines Filters wird die Anzahl der Artikel angezeigt.

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus24.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 24: Filter Bonus Artikel </figcaption>
    <br>
</div>

Neben dem Artikelfilter ist es möglich einen Filter nach einem Attribut
zu setzen. Hierbei ist zu beachten, dass Attribute nur nach einer Option
zu filtern sind und nicht gleichzeitig nach mehreren.

Beispiel:

Richtig:

Artikel Lampe nach Farbe rot

Artikel Lampe nach Farbe grün

Falsch:

Artikel Lampe nach Farbe rot und grün

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus25.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 25: Filter Bonus Artikel </figcaption>
    <br>
</div>

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus26.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 26: Attribute Filter </figcaption>
    <br>
</div>

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus27.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 27: Beispiel Artikel Attribut rot </figcaption>
    <br>
</div>


Über die Details am Bonusvertrag ist ersichtlich, dass Filter gesetzt
sind.

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus28.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 28: Bonusvertrag Details </figcaption>
</div>

<br>

#### Bonusstaffel - Berechnungsregeln

Am Bonusvertrag, wird in der Subform, die zum Vertrag dazugehörige
Bonusstaffel angezeigt. Je Vertrag wird eine Staffelung des Bonusbetrags
in Abhängigkeit des Umsatzes oder der Absatzmenge hinterlegt. Wird die
Bonusart \"Absatz\" gewählt, gehen nur Artikel mit der hinterlegten
Artikeleinheit in der Berechnungsregel in die Bonusabrechnung ein. Mit
Hilfe der Summe der Artikelmenge oder des Umsatzbetrages aus den
Belegzeilen der Periode, wird die gültige Staffel bestimmt. Der Wert der
Staffel wird in Abhängigkeit von der Werteinheit des Vertrages für die
Bonusberechnung verwendet.

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus29.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 29: Ausschnitt Bonusstaffel </figcaption>
</div>

<br>

#### Berechnung des Skontos in % 

Für die Bonus- und Rückstellungsermittlung kann Skonto mit herangezogen
werden. Sobald die Rückstellungeinheit oder die Bonusabrechnungseinheit
geändert wird, wird das Felder \"Skonto %\" geleert. Wird das Felder
verwendet, wird angenommen, das für alle Zahlungen ein Skonto mit dem
gleichen Prozentsatz gewährt wird.

Die Berechnung der einzelnen Beträge findet dabei wie folgt statt:

Wenn das Feld ‚Rabatt %' gefüllt ist und die
Rückstellungseinheit gleich ‚%', dann werden die Rückstellungsbeträge
für jeden Beleg um den Rabatt gemindert.

Berechnung:

Rabatt = (Nettorechnungsbetrag -- Skonto) \* ‚Rabatt %'

 

Wenn das Feld ‚Skonto %' gefüllt ist und
Rückstellungseinheit gleich ‚%', dann werden die Rückstellungsbeträge
für jeden Beleg um den Skonto gemindert.

Berechnung:

Skonto= Nettorechnungsbetrag \* ‚Skonto %'

 

Die Berechnung der Rückstellung erfolgt folgendermaßen:

Rückstellungsbasis = (Nettorechnungsbetrag - Skonto - Rabatt)

Rückstellungsbetrag = Rückstellungsbasis \* Rückstellung %

 

Beispiel: 

Rechnungsnettobetrag = 10000€ Skonto = 3%, Rabatt = 5%, Bonus = 2%

Skontobetrag = 10000€ \* 3% = 300€ Rabattbetrag = (10000€ -- 300€) \* 5%
= 485 €

Bonusbetrag bzw. Rückstellungsbetrag = (10000€ -- 300€ -- 485€) \* 2% =
184,30€

<br>