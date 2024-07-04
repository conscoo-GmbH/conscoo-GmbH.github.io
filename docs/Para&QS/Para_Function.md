# Funktionsbeschreibung:

## Funktion \"Bereich\"

Wenn ein Parameter eines Elements einen zugewiesenen Wertebereich hat,
kann nur dieser Wertebereich für die Erfassung des Parameters an diesem
Element verwendet werden.

Für Parameter mit der Parameterart „Text" oder „Dezimal" können mögliche
Werte über den Aufruf „Zugehörig \> Bereich" hinzugefügt bzw. bearbeitet
werden. Aus diesen Werten kann dann am Element gewählt werden. Werden
keine Wertebereiche am Parameter definiert, können Parameterwerte
unabhängig erfasst werden.

![Ein Bild, das Text, Screenshot, Schrift, Reihe enthält. Automatisch
generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image38.png){width="6.24045384951881in"
height="1.0105577427821522in"}

Abbildung 38: Funktion \"Bereich\"

Für Parameter mit der Parameterwertart „Text" definiert jede Zeile einen
auswählbaren Textwert.

![Ein Bild, das Text, Screenshot, Schrift, Zahl enthält. Automatisch
generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image39.png){width="6.3in"
height="2.7194444444444446in"}

Abbildung 39: Beispieltexte Parameterwertart = Text

Für Parameter mit der Parameterwertart „Dezimal" definiert jede Zeile
eine Art Filter. Innerhalb dieses Bereichs muss sich der Parameterwert
am Element befinden.

Außerdem können Von -- Bis Wertebereiche (x .. y) definiert werden.
Innerhalb dieses Bereiches kann der Parameter an einem Element erfasst
werden.

![Ein Bild, das Text, Screenshot, Schrift, Zahl enthält. Automatisch
generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image40.png){width="6.3in"
height="2.745138888888889in"}

Abbildung 40: Wertebereiche Parameterwertart = Dezimal

### Option \"Wertebereichskopie zulassen\"

Über die Option „Wertebereichskopie zulassen" in der Parameterübersicht,
können in der Parameter-Artikel-Zuordnung die Wertebereiche des
Parameters in die Zuordnung am Artikel übernommen und nachträglich
modifiziert werden. Ist diese Option nicht aktiviert kann in der
Zuordnung der Wertebereich nichts angepasst werden.

![Ein Bild, das Tisch enthält. Automatisch generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image41.png){width="6.3in"
height="1.104861111111111in"}

Abbildung 41: Option \"Wertebereichskopie zulassen\"

## Funktion \"Parameter\"

Um Parameter in Belegen und Geschäftsprozessen nutzen zu können müssen
diese an den entsprechenden Stellen zugewiesen werden. Die Zuweisung
erfolgt über die Funktion \"Parameter\". Zugewiesene Parameter werden im
System zwischen Belegen weitergegeben.

### Parameterzuweisung am Artikel

Auf der Artikelkarte lassen sich die Parameter unter dem Aufruf
„Zugehörig \> Artikel \> Sonstiges \> Parameter" zuordnen.

![Ein Bild, das Text, Screenshot, Zahl, parallel enthält. Automatisch
generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image42.png){width="6.3in"
height="4.540277777777778in"}

Abbildung 42: Artikelkarte - Aufruf \"Parameter\"

Auf der sich öffnenden Seite („Parameterzuordnung") können entsprechende
Parameter hinterlegt und Parameterwerte erfasst werden. Dazu können die
Parametercodes entweder manuell ausgewählt oder die Funktion „Aus
Vorlage kopieren" verwendet werden.

![Ein Bild, das Text, Screenshot, Zahl, Software enthält. Automatisch
generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image43.png){width="6.3in"
height="3.0506944444444444in"}

Abbildung 43: Parameterzuordnung am Artikel

Wurde für einen Parameter ein Wertebereich hinterlegt und ein Parameter
außerhalb dieses Bereichs wird erfasst, erfolgt eine Fehlermeldung.

![Ein Bild, das Text enthält. Automatisch generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image44.png){width="6.3in"
height="1.6458333333333333in"}

Abbildung 44: Fehlermeldung - erfasster Wert befindet sich außerhalb des
Wertebereiches

Wurde in der Parametereinrichtung zuvor die Option „Wertebereichskopie
zulassen" für einen Parameter aktiviert, können innerhalb der
Parameterzuordnung die Wertebereiche modifiziert werden. Dazu muss
zuerst über die Funktion „Neuer Bereich" eine Wertebereichskopie des
Parameters erstellt werden.

Wurde die Option nicht innerhalb der Parameter Einrichtung aktiviert,
kann keine Wertebereichskopie innerhalb der Parameterzuordnung erstellt
und diese auch nicht bearbeitet werden.

![Ein Bild, das Text enthält. Automatisch generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image45.png){width="5.250732720909887in"
height="2.4795122484689416in"}

Abbildung 45: Fehler - Option \"Wertebereichskopie zulassen\" nicht
aktiv

#### Funktion \"Filtern nach Parametern\"

Auf der Artikelübersicht sowie auf der Seriennr.- bzw. Chargennr.-
Informationliste. wurde eine Funktion „Filtern nach Parametern"
eingebaut, die es ermöglicht nach Parametern und dazu erfassten Werten
zu filtern.

![](vertopal_2821de53d4144ecb9383d02a096bae73/media/image46.png){width="6.3in"
height="0.6833333333333333in"}

Abbildung 46: Artikelübersicht - Option \"Filtern nach Parametern\"

Bei Aufruf der Option öffnet sich eine neue Seite
„Parameterartikelfilter". Hier können die Parameter mit ihren Werten,
nach denen gefiltert werden soll, hinterlegt werden.

![Ein Bild, das Tisch enthält. Automatisch generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image47.png){width="6.3in"
height="2.2895833333333333in"}

Abbildung 47: Parameterartikelfilter

Artikel, die den Filterkriterien entsprechen werden nun angezeigt.

![Ein Bild, das Text, Screenshot, Bildschirm enthält. Automatisch
generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image48.png){width="6.3in"
height="0.99375in"}

Abbildung 48: gefundenes Element

Wird die Funktion erneut aufgerufen, werden die dem Eintrag zugewiesenen
Parameter geöffnet.

![Ein Bild, das Text, Screenshot, Zahl, Schrift enthält. Automatisch
generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image49.png){width="6.3in"
height="1.9909722222222221in"}

Abbildung 49: Parameterartikelfilter

### Parameterzuweisung an einer Charge

Wird ein Artikel bspw. als Zugang gebucht, können in den
Chargeninformationen Parameterwerte hinterlegt werden. Die Parameter am
Artikel dienen dabei als Vorgabewerte und werden automatisch an die
Charge geschrieben. Besitzt ein Parameterwert nicht das Kennzeichen
„Variabler Parameter" kann dieser Wert auch innerhalb der
Chargenerfassung nicht geändert werden.

Variable Parameter hingegen können innerhalb der Chargenerfassung
geändert werden.

![Ein Bild, das Tisch enthält. Automatisch generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image50.png){width="6.3in"
height="2.0236111111111112in"}

Abbildung 50: Parameterzuordnung am Artikel

Hinweis: In der Parameterzuordnung am Artikel kann nachträglich das
Kennzeichen „Variabler Parameter" geändert werden.

Auch hier gilt -- variable Parameter sind in grün farblich
gekennzeichnet. Nicht variable Parameter in schwarz.

Wird nun bspw. über das Artikelbuchblatt ein Zugang gebucht und dem
Artikel wird eine Chargennummer zugewiesen, erhält die Charge die
Parameterinformationen des Artikels.

Hinweis: Wird ein Artikel mit abweichenden Parametern in
unterschiedlichen Chargen eingekauft (Einkaufsbestellung wird erzeugt)
und es werden sowohl Belegzeilenparameter im Beleg als auch
Chargenspezifische Parameter innerhalb der Artikelverfolgungszeilen
angegeben, werden die Parameter des Artikels inklusive zusätzlich
eingesteuerter Parameter (Kreditor/Lagerort/etc.) als Vorschlagswert
zuerst in die Belegzeilenparameter übernommen. Beim Erzeugen der Charge
innerhalb der Artikelverfolgungszeile werden dann als Vorschlagswert die
Belegzeilenparameter geschrieben. Wird dieser Einkauf nun durch die
Funktion „Buchen" abgeschlossen, werden die chargenspezifischen
Parameter der Artikelverfolgungszeile in die Parameterinformationen der
Charge übernommen.

![Ein Bild, das Text, Zahl, Schrift, Screenshot enthält. Automatisch
generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image51.png){width="6.3in"
height="2.4166666666666665in"}

Abbildung 51: unveränderte Parameterzuordnung an der Charge

Innerhalb dieser Zuordnung werden Parameter, die nicht das Kennzeichen
„Variabler Parameter" besitzen farblich rot dargestellt. Hier lässt sich
spezifisch für die Charge bestimmen, welcher Parameter variabel ist und
welcher nicht. Für nicht variable Parameter lassen sich die
Parameterwerte nicht ändern, bis das Kennzeichen „Variabler Parameter"
gesetzt wurde.

![Ein Bild, das Tisch enthält. Automatisch generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image52.png){width="6.3in"
height="3.182638888888889in"}

Abbildung 52: Charge - geänderte Parameterinformationen

Über die Seite „Chargennr.-Informationskarte" lassen sich über die
Funktion „Parameter", die der Chargennummer zugewiesenen Parameter
nachträglich einsehen. Sie sind an dieser Stelle nicht mehr editierbar.

![Ein Bild, das Text, Screenshot, Zahl, Schrift enthält. Automatisch
generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image53.png){width="6.3in"
height="3.7395833333333335in"}

Abbildung 53: Chargennr.-Informationskarte -- Parameterübersicht

### Parameterzuweisung auf Belegen

Die Parameterzuweisung auf Belegzeilenebene erfolgt im ersten Schritt
vom Artikel. Parameter können an dieser Stelle unabhängig von bspw.
Chargeninformationen geändert werden.

Der Aufruf der Belegzeilenparameter erfolgt auf Zeilenebene über „Zeile
\> Parameter".

![Ein Bild, das Text enthält. Automatisch generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image54.png){width="6.3in"
height="1.2625in"}

Abbildung 54: Aufruf Belegzeilenparameter

Handelt es sich bei dem Artikel um einen verfolgungspflichtigen Artikel,
kann über die Artikelverfolgungszeilen bei Auswahl der entsprechenden
Informationen auf die dazugehörigen Parameter über den Aufruf „Zeile \>
Parameter Chargennr." Bzw. „Parameter Seriennr." Zugegriffen werden.

![Ein Bild, das Text, Screenshot, Reihe enthält. Automatisch generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image55.png){width="6.3in"
height="1.9076388888888889in"}

Abbildung 55: Aufruf \"Parameter Chargennr.\" Bzw. „Parameter Seriennr."

Innerhalb des Parameteraufrufs lassen sich die Parameter
weiterbearbeiten und werden dann an Folgebelege weitergegeben.

#### Verfügbare Belege

Belegzeilenparameter können an folgenden Belegen hinterlegt werden:

Verkauf:

Verkaufsangebot

Verkaufsauftrag

Rahmenauftrag

Verkaufsrechnung

Verkaufsgutschrift

Geb. Verkaufsrechnung

Geb. Verkaufsgutschrift

Geb. Verkaufslieferung

Logistik

Umlagerungsauftrag

Wareneingang

Warenausgang

Einkauf

Einkaufsanfrage

Einkaufsbestellung

Rahmenbestellung

Einkaufsrechnung

Einkaufsgutschrift

Geb. Einkaufsrechnung

Geb. Einkaufsgutschrift

Geb. Einkaufslieferung

### Parameterzuweisung am Debitor

Auf der Debitorenkarte können über den Aufruf „Zugehörig \> Sonstiges \>
Parameter" Parameter zum Debitor zugeordnet werden.

![Ein Bild, das Text, Screenshot, Zahl, Reihe enthält. Automatisch
generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image56.png){width="6.3in"
height="2.692361111111111in"}

Abbildung 56: Debitorenkarte -- Parameterzuweisung

![Ein Bild, das Text, Screenshot, Schrift, Zahl enthält. Automatisch
generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image57.png){width="6.3in"
height="1.448611111111111in"}

Abbildung 57: Parameterzuordnung

Wurden auf der Debitorenkarte Parameter hinterlegt und der Debitor wird
einem Verkaufsbeleg zugewiesen und es wird eine Verkaufsbelegzeile
erstellt, werden die Parameterinformationen des Debitors in die
Belegzeilenparameter eingetragen.

![Ein Bild, das Text, Screenshot, Schrift, Zahl enthält. Automatisch
generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image58.png){width="6.3in"
height="1.26875in"}

Abbildung 58: Verkaufsbeleg - Belegzeilenparameter Übernahme von
Debitorenkarte

Sofern ein Artikel mit Parametern innerhalb des Verkaufsbeleges
eingetragen wird, werden die Belegzeilenparameter um diese Informationen
ergänzt.

![Ein Bild, das Text, Screenshot, Zahl, Schrift enthält. Automatisch
generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image59.png){width="6.3in"
height="2.529861111111111in"}

Abbildung 59:Ergänzte Parameterinformationen

#### Verknüpfte Parameter (Debitor)

Auf der Debitorenkarte können über den Aufruf „Zugehörig \> Sonstiges \>
Verknüpfte Parameter" Verknüpfte Parameter zwischen Debitor und Artikel
hinterlegt werden.

![Ein Bild, das Text enthält. Automatisch generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image60.png){width="6.3in"
height="2.421527777777778in"}

Abbildung 60: Debitorenkarte - Aufruf \"Verknüpfte Parameter\"

Auf der sich öffnenden Seite „Verknüpfte Parameter" wird die Ansicht
beim Aufruf über die Debitorenkarte bereits vorgefiltert auf
„Referenzart = Debitor" und „Referenznr. = Debitornr." angezeigt. Im
Feld „Artikelnr." kann nun eine Artikelnummer ausgewählt werden, um eine
Parameterverknüpfung zwischen dem ausgewählten Debitor und dem Artikel
zu erzeugen.

Im Feld „Anzahl Parameter" wird angezeigt, wie viele Parameter zu dieser
Verknüpfung gehören.

![Ein Bild, das Tisch enthält. Automatisch generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image61.png){width="6.3in"
height="1.0319444444444446in"}

Abbildung 61: Verknüpfte Parameter - Übersicht

Über den Aufruf „Parameter" im Menüband können der Verknüpfung Parameter
zugewiesen werden.

![Ein Bild, das Text, Screenshot, Schrift, Reihe enthält. Automatisch
generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image62.png){width="5.948746719160105in"
height="1.2085017497812773in"}

Abbildung 62: Verknüpfte Parameter - Aufruf Parameterzuweisung

![Ein Bild, das Text enthält. Automatisch generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image63.png){width="6.3in"
height="1.4756944444444444in"}

Abbildung 63: Verknüpfte Parameter - Zugeordnete Parameter

Wird diese Kombination nun in einem Verkaufsbeleg angegeben, werden die
Parameterinformationen der Belegzeile um die Informationen der
Verknüpfung ergänzt.

![Ein Bild, das Text, Screenshot, Zahl, Schrift enthält. Automatisch
generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image64.png){width="6.3in"
height="2.8180555555555555in"}

Abbildung 64: Belegzeilenparameter - Ergänzung um Verknüpfte Parameter
Debitor

#### Verknüpfte Parameter an der \"Lief. An\" Adresse

Es können außerdem Verknüpfte Parameter explizit für eine „Lief.
An"-Adresse hinterlegt werden.

Dazu kann in der „Lief. An Adressen Übersicht" im Menüband über den
Aufruf „Zugehörig \> Sonstiges" die Einrichtung „Verknüpfte Parameter"
eingesehen und bearbeitet werden.

![Ein Bild, das Text, Screenshot, Schrift enthält. Automatisch
generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image65.png){width="6.3in"
height="1.6861111111111111in"}

Abbildung 65: Lief. An Adressen Übersicht - Aufruf Verknüpfte Parameter

Auf der sich öffnenden Seite „Verknüpfte Parameter" wird die Ansicht
beim Aufruf über die „Lief. An Adressen Übersicht" bereits vorgefiltert
auf „Referenzart = Lieferadresse", „Referenznr. = Debitornr." Und
„Referenznr. 2 = Lief. An Adresse Code" angezeigt. Im Feld „Artikelnr."
kann nun eine Artikelnummer ausgewählt werden, um eine
Parameterverknüpfung zwischen der ausgewählten Lieferadresse und dem
Artikel zu erzeugen.

![Ein Bild, das Text enthält. Automatisch generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image66.png){width="6.3in"
height="1.4145833333333333in"}

Abbildung 66: Lieferadresse - Verknüpfte Parameter Parameterzuordnung

Wird diese Kombination nun in einem Verkaufsbeleg angegeben, werden die
Parameterinformationen der Belegzeile um die Informationen der
Verknüpfung ergänzt.

![Ein Bild, das Text, Screenshot, Zahl, Software enthält. Automatisch
generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image67.png){width="6.3in"
height="3.1770833333333335in"}

Abbildung 67:Belegzeilenparameter - Ergänzung um Verknüpfte Parameter
Lieferadresse

##### Einsteuerungslogik in Belege

Werden sowohl am Debitor als auch an der Lieferadresse die gleichen
Parameter erfasst, werden in den Belegzeilenparametern im ersten Schritt
die hinterlegten Parameterinformationen des Debitors berücksichtigt.

![Ein Bild, das Tisch enthält. Automatisch generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image68.png){width="6.3in"
height="1.38125in"}

Abbildung 68: Lief. an Adresse -- Parameterzuordnung

![Ein Bild, das Text, Screenshot, Reihe, Schrift enthält. Automatisch
generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image69.png){width="6.3in"
height="1.0361111111111112in"}

Abbildung 69: Debitorenkarte -- Parameterzuordnung

![Ein Bild, das Text, Screenshot, Zahl, Schrift enthält. Automatisch
generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image70.png){width="6.3in"
height="3.407638888888889in"}

Abbildung 70: Belegzeilenparameter - Übernahme von Debitor

Wird nun nachträglich die Lieferadresse im Belegkopf geändert erfolgt
eine Hinweismeldung.

Die Belegzeilenparameter werden nicht automatisch aktualisiert und
müssen nachträglich bearbeitet bzw. an die Parameterinformationen der
Lieferadresse angepasst werden.

![Ein Bild, das Text, Screenshot, Software enthält. Automatisch
generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image71.png){width="5.765919728783902in"
height="1.7618088363954505in"}

Abbildung 71: Hinweismeldung zur Prüfung der
Belegzeilenparameterinformationen

### Parameterzuweisung am Kreditor

Analog zur Parameterzuweisung am Debitor können auch für einen
Kreditoren Parameterinformationen im Menüband über den Aufruf „Zugehörig
\> Sonstiges \> Parameter" hinterlegt werden.

![Ein Bild, das Text enthält. Automatisch generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image72.png){width="6.3in"
height="2.283333333333333in"}

Abbildung 72: Kreditorenkarte - Aufruf Parameter

![Ein Bild, das Text enthält. Automatisch generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image73.png){width="6.3in"
height="1.4083333333333334in"}

Abbildung 73: Kreditorenkarte -- Parameterzuordnung

#### Verknüpfte Parameter (Kreditor)

Auf der Kreditorenkarte können über den Aufruf „Zugehörig \> Sonstiges
\> Verknüpfte Parameter" Verknüpfte Parameter zwischen Kreditor und
Artikel hinterlegt werden.

![Ein Bild, das Text enthält. Automatisch generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image74.png){width="6.3in"
height="2.03125in"}

Abbildung 74: Kreditorenkarte - Aufruf \"Verknüpfte Parameter\"

Auf der sich öffnenden Seite „Verknüpfte Parameter" wird die Ansicht
beim Aufruf über die Kreditorenkarte bereits vorgefiltert auf
„Referenzart = Kreditor" und „Referenznr. = Kreditornr." angezeigt. Im
Feld „Artikelnr." kann nun eine Artikelnummer ausgewählt werden, um eine
Parameterverknüpfung zwischen dem ausgewählten Kreditor und dem Artikel
zu erzeugen.

Im Feld „Anzahl Parameter" wird angezeigt, wie viele Parameter zu dieser
Verknüpfung gehören.

Über den Aufruf „Parameter" im Menüband können der Verknüpfung Parameter
zugewiesen werden.

![Ein Bild, das Text, Screenshot, Reihe, Schrift enthält. Automatisch
generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image75.png){width="6.3in"
height="1.1923611111111112in"}

Abbildung 75: Verknüpfte Parameter - Aufruf Parameterzuordnung

![Ein Bild, das Text, Screenshot, Reihe, Schrift enthält. Automatisch
generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image76.png){width="6.3in"
height="1.1229166666666666in"}

Abbildung 76: Parameterzuordnung Verknüpfte Parameter Kreditor-Artikel

Wird diese Kombination nun in einem Einkaufsbeleg angegeben, werden die
Parameterinformationen der Belegzeile um die Informationen der
Verknüpfung ergänzt.

![Ein Bild, das Tisch enthält. Automatisch generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image77.png){width="6.3in"
height="2.6958333333333333in"}

Abbildung 77: Einkaufsbeleg - Belegzeilenparameter Ergänzung Verknüpfte
Parameter

### Parameterzuweisung am Lagerort

Auf der Lagerortkarte können im Menüband über den Aufruf „Parameter"
Parameter hinterlegt werden.

![](vertopal_2821de53d4144ecb9383d02a096bae73/media/image78.png){width="6.3in"
height="0.6493055555555556in"}

Abbildung 78: Lagerortkarte - Aufruf Parameter

![Ein Bild, das Text enthält. Automatisch generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image79.png){width="6.3in"
height="1.511111111111111in"}

Abbildung 79: Lagerortkarte -- Parameterzuordnung

Wird dieser Lagerort nun innerhalb eines Beleges angegeben, werden die
Belegzeilenparameter um diese Parameterinformationen ergänzt.

![Ein Bild, das Text, Screenshot, Zahl, Schrift enthält. Automatisch
generierte
Beschreibung](vertopal_2821de53d4144ecb9383d02a096bae73/media/image80.png){width="6.3in"
height="2.6708333333333334in"}

Abbildung 80: Belegzeilenparameter - Ergänzung um Parameterinformationen
Lagerort

Die Parameterinformationen des Lagerortes werden außerdem an die
Logistikbelege (Wareneingang, Warenausgang) weitergegeben.
