<style>
body {
    font-family: "Century Gothic", "CenturyGothic", "AppleGothic", sans-serif;
}
</style>


# Funktionsbeschreibung

<br>

## Schaltflächen am Bonusvertrag

<br>

In diesem Abschnitt sollen kurz, die wichtigsten Schaltflächen in der
Übersicht der Bonusverträge erklärt werden.

<br>

### Aktionen

<br>

Unter \"Aktionen\" werden folgende Funktionen bereitgestellt:

<!-- <div style="text-align: center;">
    <img src="../../images/Bonus/Bonus30.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 30: Bonus Vertrag - Aktionen </figcaption>
    <br>
</div> -->

Rückstellungen erzeugen:

Über diese Schaltfläche kann der Rückstellungslauf für den aktuellen
Bonusvertrag gefiltert aufgerufen werden. Das System filtert die
Stapelverarbeitung vor, so dass nur für diesen Bonusvertrag
Rückstellungen gebildet werden (siehe auch:
[Bonusrückstellungen](#bonusrückstellungen)).

Rückstellungen auflösen:

Diese Schaltfläche ruft die verbuchten Rückstellungen auf und bietet die
Möglichkeit, die erzeugten Rückstellungszeilen einzeln oder gesammelt,
durch markieren der entsprechenden Zeilen, aufzulösen. Die aufgelösten
Rückstellungszeilen verschwinden dann aus der Übersicht (siehe auch:
[Manuelles Auflösen der
Rückstellungen](#manuelles-auflösen-der-rückstellungen)).

Bonuslauf:

Durch Benutzen des Buttons \"Bonuslauf\" wird die Funktion zum Abrechnen
der Bonusverträge angestoßen. Die Maske öffnet sich dabei vorgefiltert
auf den jeweiligen Vertrag (siehe auch: [Bonuslauf](#bonuslauf)).

<br>

### Zugehörig

<br>

<!-- <div style="text-align: center;">
    <img src="../../images/Bonus/Bonus31.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 31: Bonus Vertrag - Zugehörig </figcaption>
    <br>
</div> -->

Zusätzlich zu den Filtern über Debitor und Bonusartikel werden unter
\"Zugehörig\" die Bonusposten angezeigt sowie alle Posten über \"In
Posten suchen\".

Bonusposten:

Bei jeder Erzeugung von Rückstellungen oder Bonusabrechnungen werden im
Hintergrund Bonusposten geschrieben. Diese Bonusposten können über diese
Schaltfläche je Bonusvertrag aufgerufen werden.

Die Bonusposten werden mit Hilfe der Postenart identifiziert, ob es sich
bei den Posten um eine Rückstellung, Rückstellungsauflösung oder ein
Bonus handelt. <br>

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus32.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 28: Bonusposten </figcaption>
    <br>
</div>

Beschreibung der einzelnen Felder der Bonuspostenübersicht: <br>

| Feld                               | Beschreibung                                                                                                                                                                                                                                                                                                                                                                                                                                     |
|------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Lfd. Nr.                           | Dieses Feld identifiziert den Bonusposten mit einer einmaligen, fortlaufenden Nr.                                                                                                                                                                                                                                                                                                                                                                 |
| Vertrag                            | Dieses Feld wird mit der Vertragsnummer der Bonusvereinbarung gefüllt.                                                                                                                                                                                                                                                                                                                                                                            |
| Prozessnr.                         | Beim Anlegen eines Bonusvertrages wird automatisch eine Prozessnr. gezogen. Diese dient zur Identifizierung der gebuchten Sachposten als Bonus bzw. Rückstellung. Es wird die Prozessnr. des jeweiligen Vertrages in die Bonusposten geschrieben.                                                                                                                                                                                                   |
| Postenart                          | Dieses Feld definiert die Art des Postens anhand folgender Optionen:<br>Rückstellung<br>Rückstellungsauflösung<br>Bonusposten                                                                                                                                                                                                                                                                                                                     |
| Bonusvertragszeile                 | Für Bonusposten mit der Postenart „Bonus“ werden in diesem Feld die Zeilennr. der zughörigen Bonusregel erfasst. Anhand dieser Zeilennr. kann identifiziert werden, mit welcher Bonusstaffelung der Bonusposten erstellt wurde.                                                                                                                                                                                                                  |
| Debitor                            | Dieses Feld wird mit dem Debitor aus dem Bonusvertrag gefüllt.                                                                                                                                                                                                                                                                                                                                                                                    |
| Lief. an Code                      | Dieses Feld wird mit dem Lieferkontakt aus dem Bonusvertrag gefüllt.                                                                                                                                                                                                                                                                                                                                                                              |
| Datum                              | Dieses Datumsfeld bezieht sich auf das Buchungsdatum der jeweiligen Sachposten.                                                                                                                                                                                                                                                                                                                                                                   |
| Absatzmenge                        | Hier wird die Menge der einzelnen Belegzeile der Abrechnungsgutschrift eingetragen.                                                                                                                                                                                                                                                                                                                                                                |
| Rechnungsempfänger                 | Dieses Feld wird mit dem Rechnungsempfänger der Bonusvereinbarung gefüllt.  Als Rechnungsempfänger kann auch ein abweichender Debitor hinterlegt werden.                                                                                                                                                                                                                                                                                           |
| Basisbetrag                        | In diesem Feld wird der Basisbetrag (Bemessungsgrundlage) des Quellbeleges erfasst.                                                                                                                                                                                                                                                                                                                                                               |
| berechneter Betrag                 | Dieses Feld zeigt den Betrag auf Basis der berechneten Rückstellungen und Bonusläufe an. Nach der Erstellung der Rückstellung bzw. Bonus im Rückstellungsbuchblatt bzw. Bonusgutschrift können wertmäßige Änderungen vorgenommen werden. Daher muss der errechnete Betrag nicht gleich identisch sein mit dem gebuchten Betrag.                                                                                                                             |
| errechneter Betrag inkl. MwSt.     | In diesem Feld wird der errechnete Betrag inkl. der MwSt. erfasst, wenn der Rechnungsempfänger anhand seiner Stammdateneinrichtung MwSt.-pflichtig ist.                                                                                                                                                                                                                                                                                              |
| gebuchter Betrag                   | Dieses Feld wird erst mit einem Wert gefüllt, wenn die zugehörige Bonusgutschrift bzw. das Rückstellungsbuchblatt verbucht wurde.                                                                                                                                                                                                                                                                                                                   |
| Skontobetrag                       | Dieses Feld beinhaltet den berechneten Skontobetrag.                                                                                                                                                                                                                                                                                                                                                                                              |
| Quellbelegart                      | Dieses Feld gibt an, ob es sich beim Quellbeleg um eine Verkaufsrechnung oder Verkaufsgutschrift handelt.                                                                                                                                                                                                                                                                                                                                         |
| Quellbelegnr.                      | In diesem Feld wird die Belegnr. des Quellbeleges hinterlegt.                                                                                                                                                                                                                                                                                                                                                                                     |
| Quellbelegzeilennr.                | Mit Hilfe dieses Feldes kann die Rechnungszeile bzw. Gutschriftzeile des Quellbeleges identifiziert werden.                                                                                                                                                                                                                                                                                                                                        |
| Bonusbelegtyp                      | Handelt es sich um ein Bonusposten mit der Postenart "Bonus“ wird in diesem Feld „Verkaufsgutschrift“ als Belegart hinterlegt.                                                                                                                                                                                                                                                                                                                    |
| Bonusbelegnummer                   | Handelt es sich um ein Bonusposten mit der Postenart "Bonus" wird in diesem Feld die Belegnr. der Bonusgutschrift erfasst.                                                                                                                                                                                                                                                                                                                        |
| Bonusbelegzeilen                   | Mit Hilfe des Feldes Bonusbelegzeilennr. kann identifiziert werden, in welcher Gutschriftzeile sich dieser Bonusposten in der Bonusgutschrift befindet.                                                                                                                                                                                                                                                                                            |
| Zuweisungsbelegart                 | In diesem Feld wird die Zuweisungsbelegart hinterlegt.                                                                                                                                                                                                                                                                                                                                                                                            |
| Zuweisungsbelegnummer              | Handelt es sich um ein Bonusposten mit der Postenart ‚Bonus‘ wird in diesem Feld die Zuweisungsbelegnummer der Bonusgutschrift erfasst.                                                                                                                                                                                                                                                                                                           |
| Zuweisungsbeleg-zeilennummer       | Mit Hilfe des Feldes Zuweisungsbelegzeilennummer kann identifiziert werden, in welcher Gutschriftzeile sich dieser Bonusposten in der Bonusgutschrift befindet.                                                                                                                                                                                                                                                                                     |
| Sachposten Lfd. Nr.                | Werden die Bonusposten mit der Postenart "Rückstellung" und "Rückstellungsauflösung" gebucht, wird dieses Feld mit der Lfd. Nr. des zugehörigen Sachpostens verknüpft.<br><br>**Hinweis:**<br>Dieses Feld wird nicht bei der Postenart "Bonus" gefüllt. Hier dient die Belegnr. der Bonusgutschrift als Nachweis.                                                                                                                                       |
| Storniert                          | Wird ein Bonusposten mit der Postenart "Rückstellung" durch ein Bonusposten mit der Postenart "Rückstellungsauflösung" aufgelöst, wird im Feld "Storniert" ein Häkchen gesetzt.                                                                                                                                                                                                                                                                     |
| Storniert durch Lfd. Nr.           | Durch die Lfd. Nr. in diesem Feld kann identifiziert werden, mit welchem Bonusposten die Rückstellung aufgelöst wurde.                                                                                                                                                                                                                                                                                                                             |
| Bonusbeleg gelöscht                | Gibt an, ob das Bonusdokument gelöscht wurde. Dies ist möglich, solange die Verkaufsgutschrift der Bonusabrechnung noch nicht gebucht ist.                                                                                                                                                                                                                                                                                                         |

<br>

Posten suchen:

Über \"Posten suchen\" werden wie gewohnt die erstellten Posten und
Belege aufgerufen.

Als Filter gilt hier die \"Prozessnr.\" <br>

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus33.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 29: Posten suchen </figcaption>
</div>

<br>

## Bonusrückstellungen

<br>

Bonusrückstellungen werden monatlich vor der eigentlichen
Bonusabrechnung erstellt. Der Anwender gibt den Zeitraum für die
Rückstellungen ein. Anhand von Filtereinstellungen kann der
Rückstellungslauf auf einzelne Verträge, Debitoren oder
Abrechnungsintervall eingegrenzt werden.

Die Funktion durchläuft alle relevanten Belege. Je Vertrag werden alle
Umsätze aus Rechnungen und Gutschriften der Periode summiert und mit dem
Rückstellungsprozentsatz des Vertrages bewertet bzw. ein Festbetrag je
Vertrag herangezogen.

Über die Suche \"Bonusrückstellungslauf\" erfassen: <br>

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus34.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 30: Bonusrückstellungslauf </figcaption>
</div>

Über die Bonusvertragskarte:

<!-- <div style="text-align: center;">
    <img src="../../images/Bonus/Bonus35.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 35: Bonusvertragskarte - Rückstellungen erzeugen </figcaption>
</div> -->

<br>

### Mit Rückstellungsmodus ‚Buchblattzeilen

<br>

Im Fibu-Buchblatt für Bonusrückstellungen, wird je Vertrag eine
Buchungszeile mit dem ermittelten Rückstellungsbetrag, den hinterlegten
Konten aus der Debitorenbuchungsgruppe und der Prozessnr. des Vertrages
erstellt.

Die Buch.-Blattzeilendimension werden entweder aus den Belegzeilen (bei
den Rückstellungsarten % vom Umsatz und Betrag je Einheit) oder aus den
Vertragsdimensionen (bei der Rückstellungsart Betrag in MW) übergeben.
Das Buchblatt wird anschließend manuell gebucht. <br>

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus36.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 31: FiBu Buch.-Blätter Rückstellung </figcaption>
    <br>
</div>

Das Buchblatt wird anschließend manuell gebucht.

Für alle Verträge, die in den Rückstellungen eingegangen sind, wird das
Periodenende in das Feld „Letzte Rückstellung am" in der
Bonusvertragskarte übernommen.

Das Feld ist zu entfernen, wenn der Rückstellungslauf erneut ausgerufen
werden muss. <br>

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus37.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 32: Bonusvertragskarte - letzte Rückstellung am </figcaption>
    <br>
</div>

> [!NOTE]
> Am Bonusvertrag werden mit jedem Aufruf zum Rückstellungslauf, Bonusposten erzeugt, auch wenn diese doppelt aufgerufen werden.


Bei Rückstellungen, welche gebucht wurden, ist das Feld \"Sachposten
lfd. Nummer\" an den Bonusposten entsprechend gefüllt. Nur diese Posten
werden bei der Auflösung der Rückstellungen berücksichtigt. <br>

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus38.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 33: Bonusposten</figcaption>
</div>

<br>

### Mit Rückstellungsmodus‚ Gutschrift

<br>

Bei dieser Variante ist die Verfahrensweise identisch, jedoch entsteht
nach dem Rückstellungslauf kein gefülltes Buchblatt, sondern es wird
eine Gutschrift im System vorerfasst. Das Erzeugen der Rückstellungen
erfolgt dabei über denselben Button \"Rückstellungen erzeugen\". Nach
Angabe des gewünschten Rückstellungszeitraums, werden die Rückstellungen
erzeugt und danach in einer Gutschrift als Zu-/ Abschläge dargestellt.
Als Debitor für die Rückstellungsbildungs- und Auflösungsbelege ist ein
interner statistischer Debitor angelegt werden (siehe auch: [Anlegen des
internen
Debitors](file:///H:\App%20Bonus\Doku%20LIS%20Bonusmodul%20v1.0_2017.docx#_Anlegen_des_internen)),
welcher an der Bonusvertragskarte eingetragen werden muss. Dieser sollte
interne statistische Buchungsgruppen besitzen, die, insofern sie noch
nicht anderweitig benötigt worden sind, angelegt werden müssen.

> [!NOTE]
> Bei dieser Rückstellungsvariante erzeugt das Modul anstelle von Buchblattzeilen; Verkaufsgutschriften mit einem eigenen Nummernkreis. In diesen Gutschriften werden Zu/Abschläge zur Rückstellungsermittlung verwendet. Der Vorteil dieser Variante ist, dass die Zu/Abschlagszeilen Wertposten erzeugen, welche sich auf Artikelbewegungen beziehen.

Die gebildeten Rückstellungen werden im Anschluss an den
Rückstellungslauf in einer Verkaufsgutschrift dargestellt und können
dann verbucht werden.

Prüfen Sie vor dem Verbuchen das Buchungsdatum. Es wird das Arbeitsdatum
vorgeschlagen und muss bei Bedarf geändert werden. <br>

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus39.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 34: Bonusrückstellung - Verkaufsgutschrift </figcaption>
    <br>
</div>

> [!NOTE]
> Sollte hier eine Verkaufsgutschrift erstellt worden sein, welche falsch ist, kann dieser Beleg gelöscht werden. Im Anschluss kann der Rückstellungslauf erneut aufgerufen werden. Das Feld \"letzte Rückstellung am\" ist an der Bonusvertragskarte vorab zu entfernen.

Über die Schaltfläche \"In Posten suchen\" an der Bonusvertragskarte
kann die erstellte Verkaufsgutschrift aufgerufen werden. <br>

<!-- <div style="text-align: center;">
    <img src="../../images/Bonus/Bonus40.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 40: In Posten suchen </figcaption>
    <br>
</div> -->

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus41.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 35: Posten suchen </figcaption>
    <br>
</div>

Gutschrift:

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus42.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 36: Gutschrift </figcaption>
</div>

<br>

## Bonuslauf

<br>

Unter Berücksichtigung der Filtereinstellungen im Bonuslauf und dem
Abrechnungsintervall aus der Vertragskarte, werden alle Rechnungs- und
Gutschriftzeilen des Zeitraums herangezogen, welche zusätzlich auf
Relevanz der entsprechenden Vertragsbedingungen (Bonusstaffeln) geprüft
werden. Je Debitor und Lieferadresscode wird eine Bonusgutschrift für
den Bonusempfänger erstellt.

Der Bonus wird in der Belegzeile als Zu-/ Abschläge dargestellt.

Mit den Bonuslauf wird automatisch die Auflösung der Rückstellungen
erstellt.

Der Bonuslauf kann über einen Vertrag gestartet Suche oder die Suche
gestartet werden.

<!-- <div style="text-align: center;">
    <img src="../../images/Bonus/Bonus43.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 43: Vertragskarte - Bonuslauf </figcaption>
    <br>
</div> -->

Es wird der Zeitraum zur Berechnung sowie das Buchungsdatum zur
Auflösung der Rückstellungen erfasst. <br>

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus44.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 37: Bonuslauf </figcaption>
</div>

<br>

### Bonuslauf mit Rückstellungsmodus \"Buchblattzeilen\"

<br>

Mit Durchführung des Bonuslaufs werden diese Posten automatisch
storniert, falls dies in der Einrichtung so hinterlegt worden ist. <br>

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus45.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 38: Sachposten zur automatischen Auflösung der Rückstellungen </figcaption>
    <br>
</div>

Die Verkaufsgutschrift für die Bonusabrechnung wird erstellt. <br>

> [!Important]
> Vor dem Buchen der Bonusgutschrift ist das Buchungsdatum zu prüfen. Es wird hier das Arbeitsdatum vorgeschlagen.

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus46.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 39: erstellte Bonus Verkaufsgutschrift </figcaption>
    <br>
</div>

Mit dem Buchen der Rückstellungsauflösung werden die Rückstellungsposten
mit \"Storniert\" gekennzeichnet. <br>

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus47.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 40: Rückstellungsposten mit "Storniert" gekennzeichnet</figcaption>
    <br>
</div>

In der Bonusvertragskarte wird das Datum „Letzte Abrechnung am" gefüllt. <br>

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus48.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 41: Bonusvertragskarte</figcaption>
</div>

<br>

### Bonuslauf mit Rückstellungsmodus \"Gutschrift\"

<br>

Beim Bonuslauf mit Rückstellungsmodus \"Gutschrift\" wird sowohl eine
Verkaufsgutschrift zum Verbuchen der Bonusauszahlung, sowie eine
Verkaufsrechnung erstellt, um die erzeugten Rückstellungen aufzulösen.

Es öffnet sich die Verkaufsgutschrift für die Bonusabrechnung. Als
Bonusabrechnungsbeleg muss die erstellte Verkaufsgutschrift geprüft und
gebucht werden. <br>

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus49.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 42: Verkaufsgutschrift Bonusabrechnung </figcaption>
    <br>
</div>

Die Verkaufsrechnung, zur Auflösung der gebuchten Rückstellungen, wird
mit dem internen Verrechnungsdebitor gefüllt und muss manuell verbucht
werden. <br>

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus50.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 43: Verkaufsrechnung Rückstellungsauflösung </figcaption>
    <br>
</div>

Nachdem die Verkaufsrechnung zur Rückstellungsauflösung verbucht worden
ist, werden die zum Vertrag gehörenden Rückstellungsposten mit
\"Storniert\" gekennzeichnet.

<br>

### Manuelles Auflösen der Rückstellungen

<br>

In manchen Fällen kann es notwendig sein, dass einzelne Rückstellungen
oder Rückstellungen basierend auf einem bestimmten Beleg, schon vor dem
eigentlichen Bonuslauf aufgelöst werden. Dies kann manuell in einem
Vertrag über \"Aktionen\" / \"Rückstellungen auflösen\" vorgenommen
werden.

<!-- <div style="text-align: center;">
    <img src="../../images/Bonus/Bonus51.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 51: Rückstellungen auflösen </figcaption>
    <br>
</div> -->

Daraufhin öffnet sich eine Übersicht, in der alle gebuchten
Rückstellungen angezeigt werden. Diese können einzeln oder zeilenweise
durch Markieren der gewünschten Zeilen, ausgewählt werden. <br>

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus52.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 44: Bonusrückstellungen auflösen </figcaption>
    <br>
</div>

Es werden die aufzulösenden Rückstellungposten markiert. Über den Button
\"Aktionen\"/ \"Rückstellungen auflösen\" werden die Werte
bereitgestellt. <br>

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus53.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 45: Posten zum Auflösen markiert </figcaption>
    <br>
</div>

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus54.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 46: Info zur Auflösung </figcaption>
    <br>
</div>

Es wird je nach Rückstellungsmodus ein Buchblatt bzw. eine
Verkaufsrechnung erzeugt. <br>

> [!Important]
> Als Buchungsdatum wird das Arbeitsdatum verwendet. Dieses bitte im vor dem Buchen prüfen und bei Bedarf ändern, ggf. auch die Beschreibung. <br>

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus55.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 47: manuelles Auflösen der Rückstellung Verkaufsrechnung
(Gutschriftsmodus) </figcaption>
</div>

<br>

## Auswertungsmöglichkeiten

<br>

### Fibujournal

<br>

Um zu analysieren, was das System im Hintergrund gebucht hat, kann das
Fibujournal aufgerufen werden. <br>

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus56.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 48: Fibujournale </figcaption>
</div>

<br>

### Prozessnummer 

<br>

Des Weiteren können die Posten nach der \"Prozessnr.\" gefiltert werden. <br>

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus57.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 49: Sachposten Prozessnr. </figcaption>
</div>

<br>

### Rückstellungsprotokoll

<br>

Das Protokoll über Rückstellungen kann von einem Vertrag aus oder über
die \"Suche\" (Rückstellungen) aufgerufen werden. Dieses wird gedruckt,
solange ausschließlich Rückstellungsposten an einem Vertrag zu vorhanden
sind. <br>

<!-- <div style="text-align: center;">
    <img src="../../images/Bonus/Bonus58.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 50: Berichte - Rückstellungen </figcaption>
    <br>
</div> -->

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus59.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 50: Bericht Bonusrückstellungen </figcaption>
</div>

<br>

### Bonusprotokoll

<br>

Das Bonusprotokoll kann von einem Vertrag aus oder über die \"Suche\"
aufgerufen werden. <br>

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus60.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 51: Bonusprotokoll </figcaption>
    <br>
</div>

<div style="text-align: center;">
    <img src="../../images/Bonus/Bonus61.png" alt="Abbildung : Erweiterungsverwaltung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 52: Ausschnitt Bonusprotokoll </figcaption>
    <br>
</div>