<style>
body {
    font-family: "Century Gothic", "CenturyGothic", "AppleGothic", sans-serif;
}
</style>

# Funktionsbeschreibung

<br>

## Funktion \"Bereich\"

<br>

Wenn ein Parameter eines Elements einen zugewiesenen Wertebereich hat,
kann nur dieser Wertebereich für die Erfassung des Parameters an diesem
Element verwendet werden.

Für Parameter mit der Parameterart „Text" oder „Dezimal" können mögliche
Werte über den Aufruf „Zugehörig \> Bereich" hinzugefügt bzw. bearbeitet
werden. Aus diesen Werten kann dann am Element gewählt werden. Werden
keine Wertebereiche am Parameter definiert, können Parameterwerte
unabhängig erfasst werden.

<!-- <div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter38.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 38: Funktion "Bereich"</figcaption> <br>
</div> -->

Für Parameter mit der Parameterwertart „Text" definiert jede Zeile einen
auswählbaren Textwert. <br>

<div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter39.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 32: Beispieltexte Parameterwertart = Text</figcaption> <br>
</div>

Für Parameter mit der Parameterwertart „Dezimal" definiert jede Zeile
eine Art Filter. Innerhalb dieses Bereichs muss sich der Parameterwert
am Element befinden.

Außerdem können Von -- Bis Wertebereiche (x .. y) definiert werden.
Innerhalb dieses Bereiches kann der Parameter an einem Element erfasst
werden. <br>

<div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter40.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 33: Wertebereiche Parameterwertart = Dezimal</figcaption> 
</div>

<br>

### Option \"Wertebereichskopie zulassen\"

<br>

Über die Option „Wertebereichskopie zulassen" in der Parameterübersicht,
können in der Parameter-Artikel-Zuordnung die Wertebereiche des
Parameters in die Zuordnung am Artikel übernommen und nachträglich
modifiziert werden. Ist diese Option nicht aktiviert kann in der
Zuordnung der Wertebereich nichts angepasst werden. <br>

<div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter41.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 34: Option "Wertebereichskopie zulassen"</figcaption> 
</div>

<br>

## Funktion \"Parameter\"

<br>

Um Parameter in Belegen und Geschäftsprozessen nutzen zu können müssen
diese an den entsprechenden Stellen zugewiesen werden. Die Zuweisung
erfolgt über die Funktion \"Parameter\". Zugewiesene Parameter werden im
System zwischen Belegen weitergegeben.

<br>

### Parameterzuweisung am Artikel

<br>

Auf der Artikelkarte lassen sich die Parameter unter dem Aufruf
„Zugehörig \> Artikel \> Sonstiges \> Parameter" zuordnen. <br>

<div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter42.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 35: Artikelkarte - Aufruf "Parameter"</figcaption> <br>
</div>

Auf der sich öffnenden Seite („Parameterzuordnung") können entsprechende
Parameter hinterlegt und Parameterwerte erfasst werden. Dazu können die
Parametercodes entweder manuell ausgewählt oder die Funktion „Aus
Vorlage kopieren" verwendet werden. <br>

<div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter43.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 36: Parameterzuordnung am Artikel</figcaption> <br>
</div>

Wurde für einen Parameter ein Wertebereich hinterlegt und ein Parameter
außerhalb dieses Bereichs wird erfasst, erfolgt eine Fehlermeldung.

<!-- <div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter44.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 37: Fehlermeldung - erfasster Wert befindet sich außerhalb des Wertebereiches</figcaption> <br>
</div> -->

Wurde in der Parametereinrichtung zuvor die Option „Wertebereichskopie
zulassen" für einen Parameter aktiviert, können innerhalb der
Parameterzuordnung die Wertebereiche modifiziert werden. Dazu muss
zuerst über die Funktion „Neuer Bereich" eine Wertebereichskopie des
Parameters erstellt werden.

Wurde die Option nicht innerhalb der Parameter Einrichtung aktiviert,
kann keine Wertebereichskopie innerhalb der Parameterzuordnung erstellt
und diese auch nicht bearbeitet werden.

<!-- <div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter45.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 45: Fehler - Option "Wertebereichskopie zulassen" nicht
aktivs</figcaption> 
</div> -->

<br>

#### Funktion \"Filtern nach Parametern\"

<br>

Auf der Artikelübersicht sowie auf der Seriennr.- bzw. Chargennr.-
Informationliste. wurde eine Funktion „Filtern nach Parametern"
eingebaut, die es ermöglicht nach Parametern und dazu erfassten Werten
zu filtern. <br>

<div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter46.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 37: Artikelübersicht - Option "Filtern nach Parametern"</figcaption> <br>
</div>

Bei Aufruf der Option öffnet sich eine neue Seite
„Parameterartikelfilter". Hier können die Parameter mit ihren Werten,
nach denen gefiltert werden soll, hinterlegt werden. <br>

<div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter47.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 38: Parameterartikelfilter</figcaption> <br>
</div>

Artikel, die den Filterkriterien entsprechen werden nun angezeigt.

<div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter48.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 39: gefundenes Element</figcaption> <br>
</div>

Wird die Funktion erneut aufgerufen, werden die dem Eintrag zugewiesenen
Parameter geöffnet. <br>

<div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter49.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 40: Parameterartikelfilter</figcaption> 
</div>

<br>

### Parameterzuweisung an einer Charge

<br>

Wird ein Artikel bspw. als Zugang gebucht, können in den
Chargeninformationen Parameterwerte hinterlegt werden. Die Parameter am
Artikel dienen dabei als Vorgabewerte und werden automatisch an die
Charge geschrieben. Besitzt ein Parameterwert nicht das Kennzeichen
„Variabler Parameter" kann dieser Wert auch innerhalb der
Chargenerfassung nicht geändert werden.

Variable Parameter hingegen können innerhalb der Chargenerfassung
geändert werden. <br>

<div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter50.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 41: Parameterzuordnung am Artikel</figcaption> <br>
</div>

> [!NOTE]
> In der Parameterzuordnung am Artikel kann nachträglich das Kennzeichen „Variabler Parameter" geändert werden. <br>

Auch hier gilt -- variable Parameter sind in grün farblich
gekennzeichnet. Nicht variable Parameter in schwarz.

Wird nun bspw. über das Artikelbuchblatt ein Zugang gebucht und dem
Artikel wird eine Chargennummer zugewiesen, erhält die Charge die
Parameterinformationen des Artikels.

> [!NOTE]
> Wird ein Artikel mit abweichenden Parametern in unterschiedlichen Chargen eingekauft (Einkaufsbestellung wird erzeugt) und es werden sowohl Belegzeilenparameter im Beleg als auch Chargenspezifische Parameter innerhalb der Artikelverfolgungszeilen angegeben, werden die Parameter des Artikels inklusive zusätzlich eingesteuerter Parameter (Kreditor/Lagerort/etc.) als Vorschlagswert zuerst in die Belegzeilenparameter übernommen. Beim Erzeugen der Charge innerhalb der Artikelverfolgungszeile werden dann als Vorschlagswert die Belegzeilenparameter geschrieben. Wird dieser Einkauf nun durch die Funktion „Buchen" abgeschlossen, werden die chargenspezifischen Parameter der Artikelverfolgungszeile in die Parameterinformationen der Charge übernommen. <br>

<div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter51.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 42: unveränderte Parameterzuordnung an der Charge</figcaption> <br>
</div>

Innerhalb dieser Zuordnung werden Parameter, die nicht das Kennzeichen
„Variabler Parameter" besitzen farblich rot dargestellt. Hier lässt sich
spezifisch für die Charge bestimmen, welcher Parameter variabel ist und
welcher nicht. Für nicht variable Parameter lassen sich die
Parameterwerte nicht ändern, bis das Kennzeichen „Variabler Parameter"
gesetzt wurde. <br>

<div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter52.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 43: Charge - geänderte Parameterinformationen</figcaption> <br>
</div>


Über die Seite „Chargennr.-Informationskarte" lassen sich über die
Funktion „Parameter", die der Chargennummer zugewiesenen Parameter
nachträglich einsehen. Sie sind an dieser Stelle nicht mehr editierbar. <br>

<div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter53.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 44: Chargennr.-Informationskarte -- Parameterübersicht</figcaption>
</div>

<br>

### Parameterzuweisung auf Belegen

<br>

Die Parameterzuweisung auf Belegzeilenebene erfolgt im ersten Schritt
vom Artikel. Parameter können an dieser Stelle unabhängig von bspw.
Chargeninformationen geändert werden.

Der Aufruf der Belegzeilenparameter erfolgt auf Zeilenebene über „Zeile
\> Parameter".

<!-- <div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter54.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 54: Aufruf Belegzeilenparameter</figcaption> <br>
</div> -->

Handelt es sich bei dem Artikel um einen verfolgungspflichtigen Artikel,
kann über die Artikelverfolgungszeilen bei Auswahl der entsprechenden
Informationen auf die dazugehörigen Parameter über den Aufruf „Zeile \>
Parameter Chargennr." Bzw. „Parameter Seriennr." Zugegriffen werden. <br>

<div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter55.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 45: Aufruf "Parameter Chargennr." Bzw. „Parameter Seriennr."</figcaption> <br>
</div>

Innerhalb des Parameteraufrufs lassen sich die Parameter
weiterbearbeiten und werden dann an Folgebelege weitergegeben.

<br>

#### Verfügbare Belege

<br>

<ol>
    <li>Verkauf
        <ul>
            <li>Verkaufsangebot</li>
            <li>Verkaufsauftrag</li>
            <li>Rahmenauftrag</li>
            <li>Verkaufsrechnung</li>
            <li>Verkaufsgutschrift</li>
            <li>Geb. Verkaufsrechnung</li>
            <li>Geb. Verkaufsgutschrift</li>
            <li>Geb. Verkaufslieferung</li>
        </ul>
    </li>
    <li>Logistik
        <ul>
            <li>Umlagerungsauftrag</li>
            <li>Wareneingang</li>
            <li>Warenausgang</li>
        </ul>
    </li>
    <li>Einkauf
        <ul>
            <li>Einkaufsanfrage</li>
            <li>Einkaufsbestellung</li>
            <li>Rahmenbestellung</li>
            <li>Einkaufsrechnung</li>
            <li>Einkaufsgutschrift</li>
            <li>Geb. Einkaufsrechnung</li>
            <li>Geb. Einkaufsgutschrift</li>
            <li>Geb. Einkaufslieferung</li>
        </ul>
    </li>
</ol>

<br>

### Parameterzuweisung am Debitor

<br>

Auf der Debitorenkarte können über den Aufruf „Zugehörig \> Sonstiges \>
Parameter" Parameter zum Debitor zugeordnet werden. <br>

<div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter56.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 46: Debitorenkarte -- Parameterzuweisung</figcaption> <br>
</div>

<div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter57.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 47: Parameterzuordnung</figcaption> <br>
</div>


Wurden auf der Debitorenkarte Parameter hinterlegt und der Debitor wird
einem Verkaufsbeleg zugewiesen und es wird eine Verkaufsbelegzeile
erstellt, werden die Parameterinformationen des Debitors in die
Belegzeilenparameter eingetragen. <br>

<div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter58.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 48: Verkaufsbeleg - Belegzeilenparameter Übernahme von Debitorenkarte</figcaption> <br>
</div>

Sofern ein Artikel mit Parametern innerhalb des Verkaufsbeleges
eingetragen wird, werden die Belegzeilenparameter um diese Informationen
ergänzt. <br>

<div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter59.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 49:Ergänzte Parameterinformationen</figcaption>
</div>

<br>

#### Verknüpfte Parameter (Debitor)

<br>

Auf der Debitorenkarte können über den Aufruf „Zugehörig \> Sonstiges \>
Verknüpfte Parameter" Verknüpfte Parameter zwischen Debitor und Artikel
hinterlegt werden. <br>

<div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter60.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 50: Debitorenkarte - Aufruf "Verknüpfte Parameter"</figcaption> <br>
</div>

Auf der sich öffnenden Seite „Verknüpfte Parameter" wird die Ansicht
beim Aufruf über die Debitorenkarte bereits vorgefiltert auf
„Referenzart = Debitor" und „Referenznr. = Debitornr." angezeigt. Im
Feld „Artikelnr." kann nun eine Artikelnummer ausgewählt werden, um eine
Parameterverknüpfung zwischen dem ausgewählten Debitor und dem Artikel
zu erzeugen.

Im Feld „Anzahl Parameter" wird angezeigt, wie viele Parameter zu dieser
Verknüpfung gehören. <br>

<div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter61.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 51: Verknüpfte Parameter - Übersicht</figcaption> <br>
</div>

Über den Aufruf „Parameter" im Menüband können der Verknüpfung Parameter
zugewiesen werden. <br>

<!-- <div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter62.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 62: Verknüpfte Parameter - Aufruf Parameterzuweisung</figcaption> <br>
</div> -->

<div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter63.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 52: Verknüpfte Parameter - Zugeordnete Parameter</figcaption> <br>
</div>

Wird diese Kombination nun in einem Verkaufsbeleg angegeben, werden die
Parameterinformationen der Belegzeile um die Informationen der
Verknüpfung ergänzt. <br>

<div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter64.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 53: Belegzeilenparameter - Ergänzung um Verknüpfte Parameter Debitor</figcaption> 
</div>

<br>

#### Verknüpfte Parameter an der \"Lief. An\" Adresse

<br>

Es können außerdem Verknüpfte Parameter explizit für eine „Lief.
An"-Adresse hinterlegt werden.

Dazu kann in der „Lief. An Adressen Übersicht" im Menüband über den
Aufruf „Zugehörig \> Sonstiges" die Einrichtung „Verknüpfte Parameter"
eingesehen und bearbeitet werden. <br>

<div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter63.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 54: Lief. An Adressen Übersicht - Aufruf Verknüpfte Parameter</figcaption> <br>
</div>

Auf der sich öffnenden Seite „Verknüpfte Parameter" wird die Ansicht
beim Aufruf über die „Lief. An Adressen Übersicht" bereits vorgefiltert
auf „Referenzart = Lieferadresse", „Referenznr. = Debitornr." Und
„Referenznr. 2 = Lief. An Adresse Code" angezeigt. Im Feld „Artikelnr."
kann nun eine Artikelnummer ausgewählt werden, um eine
Parameterverknüpfung zwischen der ausgewählten Lieferadresse und dem
Artikel zu erzeugen. <br>

<div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter66.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 55: Lieferadresse - Verknüpfte Parameter Parameterzuordnung</figcaption> <br>
</div>

Wird diese Kombination nun in einem Verkaufsbeleg angegeben, werden die
Parameterinformationen der Belegzeile um die Informationen der
Verknüpfung ergänzt. <br>

<div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter67.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 56:Belegzeilenparameter - Ergänzung um Verknüpfte Parameter Lieferadresse</figcaption> 
</div>

<br>

##### Einsteuerungslogik in Belege

<br>

Werden sowohl am Debitor als auch an der Lieferadresse die gleichen
Parameter erfasst, werden in den Belegzeilenparametern im ersten Schritt
die hinterlegten Parameterinformationen des Debitors berücksichtigt. <br>

<div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter68.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 57: Lief. an Adresse -- Parameterzuordnung</figcaption> <br>
</div>

<div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter69.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 58: Debitorenkarte -- Parameterzuordnung</figcaption> <br>
</div>

<div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter70.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 59: Belegzeilenparameter - Übernahme von Debitor</figcaption> <br>
</div>

Wird nun nachträglich die Lieferadresse im Belegkopf geändert erfolgt
eine Hinweismeldung.

Die Belegzeilenparameter werden nicht automatisch aktualisiert und
müssen nachträglich bearbeitet bzw. an die Parameterinformationen der
Lieferadresse angepasst werden.

<!-- <div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter71.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 61: Hinweismeldung zur Prüfung der Belegzeilenparameterinformationen</figcaption>
</div> -->

<br>

### Parameterzuweisung am Kreditor

<br>

Analog zur Parameterzuweisung am Debitor können auch für einen
Kreditoren Parameterinformationen im Menüband über den Aufruf „Zugehörig
\> Sonstiges \> Parameter" hinterlegt werden. <br>

<div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter72.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 60: Kreditorenkarte - Aufruf Parameter</figcaption> <br>
</div>

<div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter73.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 61: Kreditorenkarte -- Parameterzuordnung</figcaption> 
</div>

<br>

#### Verknüpfte Parameter (Kreditor)

<br>

Auf der Kreditorenkarte können über den Aufruf „Zugehörig \> Sonstiges
\> Verknüpfte Parameter" Verknüpfte Parameter zwischen Kreditor und
Artikel hinterlegt werden. <br>

<div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter74.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 62: Kreditorenkarte - Aufruf "Verknüpfte Parameter"</figcaption> <br>
</div>

Auf der sich öffnenden Seite „Verknüpfte Parameter" wird die Ansicht
beim Aufruf über die Kreditorenkarte bereits vorgefiltert auf
„Referenzart = Kreditor" und „Referenznr. = Kreditornr." angezeigt. Im
Feld „Artikelnr." kann nun eine Artikelnummer ausgewählt werden, um eine
Parameterverknüpfung zwischen dem ausgewählten Kreditor und dem Artikel
zu erzeugen.

Im Feld „Anzahl Parameter" wird angezeigt, wie viele Parameter zu dieser
Verknüpfung gehören.

Über den Aufruf „Parameter" im Menüband können der Verknüpfung Parameter
zugewiesen werden. <br>

<div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter75.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 63: Verknüpfte Parameter - Aufruf Parameterzuordnung</figcaption> <br>
</div>

<div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter76.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 64: Parameterzuordnung Verknüpfte Parameter Kreditor-Artikel</figcaption> <br>
</div>

Wird diese Kombination nun in einem Einkaufsbeleg angegeben, werden die
Parameterinformationen der Belegzeile um die Informationen der
Verknüpfung ergänzt. <br>

<div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter77.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 65: Einkaufsbeleg - Belegzeilenparameter Ergänzung Verknüpfte Parameter</figcaption> 
</div>

<br>

### Parameterzuweisung am Lagerort

<br>

Auf der Lagerortkarte können im Menüband über den Aufruf „Parameter"
Parameter hinterlegt werden. <br>

<!-- <div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter78.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 78: Lagerortkarte - Aufruf Parameter</figcaption> <br>
</div> -->

<div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter79.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 66: Lagerortkarte - Parameterzuordnung</figcaption> <br>
</div>

Wird dieser Lagerort nun innerhalb eines Beleges angegeben, werden die
Belegzeilenparameter um diese Parameterinformationen ergänzt. <br>

<div style="text-align: center;">
    <img src="../../images/Para&QS/Parameter80.png" alt="" style="width: 85%; height: auto;">
    <figcaption>Abbildung 67: Belegzeilenparameter - Ergänzung um Parameterinformationen Lagerort</figcaption> <br>
</div>

Die Parameterinformationen des Lagerortes werden außerdem an die
Logistikbelege (Wareneingang, Warenausgang) weitergegeben.