# LeBit Etiketten

#### Erstellt am: 23. Mai 2024

##### App-Version: 19.1.20142.0

## 1. Notwendige Einrichtung

### 1.1 Etikettendefinitionen

In den Etikettendefinitionen können Etiketten für den Andruck vorbereitet werden. Dazu wird im Dokumentenkopf definiert, für welche \"Art\" ein Etikett erstellt werden soll. Aktuell existieren Optionen für \"Artikel\", \"Chargen\", \"Pakete\" und \"Seriennummern\".

<div style="text-align: center;">
    <img src="../../images/Labels/Labels1.png" alt="Ein Bild, das Text, Screenshot, Reihe, Zahl enthält. Automatisch generierte Beschreibung" style="width: 100%; height: auto;">
    <figcaption>Abbildung 1: Etikettendefinitionen</figcaption>
    <br>
</div>

In den Zeilen wird dann definiert, welche Daten an welcher Stelle gedruckt werden sollen, wobei bei der App ein Bericht beiliegt, welcher genau diese Positionsnummern enthält, damit diese nach gewünschtem Format angeordnet werden können.

Außerdem können Tabellenrelationen eingerichtet werden, um auf weiterführende Informationen zuzugreifen.

<div style="text-align: center;">
    <img src="../../images/Labels/Labels2.png" alt="Ein Bild, das Text, Screenshot, Reihe enthält. Automatisch generierte Beschreibung" style="width: 100%; height: auto;">
    <figcaption>Abbildung 2: Einrichtung der Tabellenrelationen</figcaption>
    <br>
</div>

#### 1.1.1 Verbindung zu Kundenauftrag

In den Etikettenzeilen kann eine Verbindung zwischen der Etikettendefinition und den Kundenaufträgen gesetzt werden. Dafür wird in den Etikettenzeilen im Feld \"Tabellenname\" die Tabelle \"Reservierungsposten\" ausgewählt. Im Feld \"Feldname\" wird das Feld ausgewählt, welches aus der Reservierungspostentabelle gedruckt werden soll. Im Feld \"Tabellenrelation\" wird eine Relation zwischen den beiden Tabellen erstellt, die für das Drucken notwendig ist.

#### 1.1.2 Übersetzungen von Etikettentexten

In der Etikettendefinition ist es möglich, für die Etikettentexte Übersetzungen anzugeben. Die Übersetzungen werden gezogen, wenn der Reservierungsposten zu einem Verkaufsauftrag gehört, der über einen anderen Sprachcode verfügt. Hat der Verkaufsauftrag einen Sprachcode, für den es keine Übersetzung gibt, wird der Etikettentext gezogen.

<div style="text-align: center;">
    <img src="../../images/Labels/Labels3.png" alt="Ein Bild, das Text, Reihe, Schrift, Zahl enthält. Automatisch generierte Beschreibung" style="width: 100%; height: auto;">
    <figcaption>Abbildung 3: Etikettenzeilenübersetzungen</figcaption>
    <br>
</div>

### 1.2 Etikettenzuordnungen

In den Etikettenzuordnungen wird dann anschließend definiert, welches Etikett in welchem Moment gedruckt wird. Unterschieden wird zwischen Etiketten für \"Artikel\" und \"Debitoren\". Außerdem können hier die verschiedenen Datengrundlagen aus der vorher erstellen Etikettendefinitionen auf unterschiedlich formatierte Layouts legen, falls kundenspezifische Etikette gedruckt werden sollen. Über \"Anzahl Etiketten\" kann eingestellt werden, wie viele Etiketten gedruckt werden.

<div style="text-align: center;">
    <img src="../../images/Labels/Labels4.png" alt="Ein Bild, das Text, Screenshot, Zahl, Reihe enthält. Automatisch generierte Beschreibung" style="width: 100%; height: auto;">
    <figcaption>Abbildung 4: Etikettenzuordnungen</figcaption>
    <br>
</div>

#### 1.2.1 Etikettenzuordnungen in den Artikelkarten

Auf der Artikelkarte gibt es unter \"Zugehörig\" den Aufruf \"Etikettenzuordnungen\". In dieser gefilterten Ansicht werden nur die Etikettenzuordnungen angezeigt, die für diesen Artikel gedacht sind.

<div style="text-align: center;">
    <img src="../../images/Labels/Labels5.png" alt="Ein Bild, das Text, Reihe, Zahl, Schrift enthält. Automatisch generierte Beschreibung" style="width: 100%; height: auto;">
    <figcaption>Abbildung 5: Etikettenzuordnungen für einen Artikel</figcaption>
    <br>
</div>

## 2. Funktionsbeschreibung

### 2.1 Drucken von Etiketten

#### 2.1.1 Aus Business Central

Das Drucken der Etiketten ist von allen Datensätzen für welche Etiketten definiert wurden möglich. Aktuell auf den \"Artikel\", \"Chargen\", \"Pakete\" und \"Seriennummern\".

<div style="text-align: center;">
    <img src="../../images/Labels/Labels6.png" alt="Ein Bild, das Text, Screenshot, Schrift, Zahl enthält. Automatisch generierte Beschreibung" style="width: 100%; height: auto;">
    <figcaption>Abbildung 6: Drucken von der Charge</figcaption>
    <br>
</div>

#### 2.1.2 Drucken aus Fremdsystemen

Außerdem verfügt die App über eine API, welche das Drucken von außen ermöglicht.