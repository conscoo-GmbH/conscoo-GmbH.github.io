<style>
body {
    font-family: "Century Gothic", "CenturyGothic", "AppleGothic", sans-serif;
}
</style>

# Notwendige Einrichtung

<br>

## Etikettendefinitionen

<br>

In den Etikettendefinitionen können Etiketten für den Andruck vorbereitet werden. Dazu wird im Dokumentenkopf definiert, für welche \"Art\" ein Etikett erstellt werden soll. Aktuell existieren Optionen für \"Artikel\", \"Chargen\", \"Pakete\" und \"Seriennummern\". <br>

<div style="text-align: center;">
    <img src="../../images/Labels/Labels1.png" alt="Ein Bild, das Text, Screenshot, Reihe, Zahl enthält. Automatisch generierte Beschreibung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 1: Etikettendefinitionen</figcaption>
    <br>
</div>

In den Zeilen wird dann definiert, welche Daten an welcher Stelle gedruckt werden sollen, wobei bei der App ein Bericht beiliegt, welcher genau diese Positionsnummern enthält, damit diese nach gewünschtem Format angeordnet werden können.

Außerdem können Tabellenrelationen eingerichtet werden, um auf weiterführende Informationen zuzugreifen. <br>

<div style="text-align: center;">
    <img src="../../images/Labels/Labels2.png" alt="Ein Bild, das Text, Screenshot, Reihe enthält. Automatisch generierte Beschreibung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 2: Einrichtung der Tabellenrelationen</figcaption>
</div>

<br>

### Verbindung zu Kundenauftrag

<br>

In den Etikettenzeilen kann eine Verbindung zwischen der Etikettendefinition und den Kundenaufträgen gesetzt werden. Dafür wird in den Etikettenzeilen im Feld \"Tabellenname\" die Tabelle \"Reservierungsposten\" ausgewählt. Im Feld \"Feldname\" wird das Feld ausgewählt, welches aus der Reservierungspostentabelle gedruckt werden soll. Im Feld \"Tabellenrelation\" wird eine Relation zwischen den beiden Tabellen erstellt, die für das Drucken notwendig ist. 

<br>

### Übersetzungen von Etikettentexten

<br>

In der Etikettendefinition ist es möglich, für die Etikettentexte Übersetzungen anzugeben. Die Übersetzungen werden gezogen, wenn der Reservierungsposten zu einem Verkaufsauftrag gehört, der über einen anderen Sprachcode verfügt. Hat der Verkaufsauftrag einen Sprachcode, für den es keine Übersetzung gibt, wird der Etikettentext gezogen. <br>

<div style="text-align: center;">
    <img src="../../images/Labels/Labels3.png" alt="Ein Bild, das Text, Reihe, Schrift, Zahl enthält. Automatisch generierte Beschreibung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 3: Etikettenzeilenübersetzungen</figcaption>
</div>

<br>

## Etikettenzuordnungen

<br>

In den Etikettenzuordnungen wird dann anschließend definiert, welches Etikett in welchem Moment gedruckt wird. Unterschieden wird zwischen Etiketten für \"Artikel\" und \"Debitoren\". Außerdem können hier die verschiedenen Datengrundlagen aus der vorher erstellen Etikettendefinitionen auf unterschiedlich formatierte Layouts legen, falls kundenspezifische Etikette gedruckt werden sollen. Über \"Anzahl Etiketten\" kann eingestellt werden, wie viele Etiketten gedruckt werden. <br>

<div style="text-align: center;">
    <img src="../../images/Labels/Labels4.png" alt="Ein Bild, das Text, Screenshot, Zahl, Reihe enthält. Automatisch generierte Beschreibung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 4: Etikettenzuordnungen</figcaption>
</div>

<br>

### Etikettenzuordnungen in den Artikelkarten

<br>

Auf der Artikelkarte gibt es unter \"Zugehörig\" den Aufruf \"Etikettenzuordnungen\". In dieser gefilterten Ansicht werden nur die Etikettenzuordnungen angezeigt, die für diesen Artikel gedacht sind. <br>

<div style="text-align: center;">
    <img src="../../images/Labels/Labels5.png" alt="Ein Bild, das Text, Reihe, Zahl, Schrift enthält. Automatisch generierte Beschreibung" style="width: 85%; height: auto;">
    <figcaption>Abbildung 5: Etikettenzuordnungen für einen Artikel</figcaption>
</div>