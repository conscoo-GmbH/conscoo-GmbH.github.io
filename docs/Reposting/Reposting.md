# LeBit Reposting

#### Erstellt am: 15. Februar 2024

##### App-Version: 22.0.19985.0

## 1. Zweck

Die Umbuchung kann für Chargen, Pakete und Serien verwendet werden.
Dabei kann einer Charge, einem Paket oder einer Serie ein anderer
Artikel zugeteilt werden oder der gleiche Artikel kann einer anderen
Charge oder Paket zugeteilt werden. Zusätzlich ist es möglich
Umlagerungen zu vollziehen.

## 2. Notwendige Einrichtungen

Auf der Seite \"Artikel Umbuch.-Blätter\" muss man im Feld
\"Buch.-Blattname\" eine Vorlage für das Artikel Umbuchung Buchblatt
auswählen.

<div style="text-align: center;">
    <img src="../../images/Reposting/Reposting1.png" alt="Ein Bild, das Text, Screenshot, Reihe enthält. Automatisch generierte Beschreibung" style="width: 100%; height: auto;">
    <figcaption>Abbildung 1: Buch.-Blattname</figcaption>
    <br>
</div>


Wenn das Feld ausgewählt wird, kann man die vorhandenen Vorlagen
bearbeiten und neue hinzufügen.

<div style="text-align: center;">
    <img src="../../images/Reposting/Reposting2.png" alt="Umbuchung Buchblatt-Vorlagen Übersicht" style="width: 100%; height: auto;">
    <figcaption>Abbildung 2: Umbuchung Buchblatt-Vorlagen Übersicht</figcaption>
    <br>
</div>


| Feldname                | Funktion                                                                                      | Bemerkung                                                                              |
|-------------------------|-----------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------|
| Code                    | Eingabe des Codes des Artikel Umbuch.-Buchblatt.                                               |                                                                                        |
| Beschreibung            | Eingabe der Beschreibung des Artikel Umbuch.-Buchblatts.                                       |                                                                                        |
| Montagenummernserie     | Wahl einer speziellen Nummernserie für die Montageaufträge, die durch die Artikel Umbuch.-Buchblatt entstehen. Falls keine Nummernserie hinterlegt ist, dann wird die Standardnummernserie der Montageaufträge genutzt. |                                                                                        |
| Artikel Buch.-Blattvorlage | Wahl der Buchblatt Vorlage von der Art "Umlagerung".                                           |                                                                                        |
| Artikel Buch.-Blatt     | Wahl einer Nummernserie, falls ein Artikel umgelagert werden soll. Falls keine Nummernserie angegeben ist, kann eine Umlagerung nicht genutzt werden. |                                                                                        |
## 3. Funktionsbeschreibung

### 3.1 Umbuchen und Umlagern

Über die Suchfunktion gelangt man zur Seite \"Artikel Umbuch.-Blätter\".

<div style="text-align: center;">
    <img src="../../images/Reposting/Reposting3.png" alt="Umbuchung Buchblatt-Vorlagen Übersicht" style="width: 100%; height: auto;">
    <figcaption>Abbildung 3: Artikel Umbuch.-Blätter Übersicht</figcaption>
    <br>
</div>



  | Feldname               | Funktion                                               | Bemerkung                                                              |
|------------------------|--------------------------------------------------------|------------------------------------------------------------------------|
| Menüband               |                                                        |                                                                        |
| Löschen                | Über Verwalten zu finden, löscht alle vorhandenen Zeilen des Buchblatts. |                                                                        |
| Buchen                 | Bucht alle vorhandenen Zeilen des Buchblatts.          |                                                                        |
| Buchen markierte       | Bucht die markierten Zeilen des Buchblatts.            |                                                                        |
| Chargennr. auswählen   | Look-Up zur Chargennr.-Informationsliste.              |                                                                        |
| Seriennr. auswählen    | Look-Up zur Seriennr.-Informationsliste.               |                                                                        |
| Paketnr. auswählen     | Look-Up zur Paketnr.-Informationsliste.                |                                                                        |
| Zeilen                 |                                                        |                                                                        |
| Code                   | Automatisch mit dem Code der Vorlage befüllt.          |                                                                        |
| Zeilennr.              | Gibt die Zeilennummer im Buchblatt an.                 | Wird automatisch in 1000er Schritte gefüllt.                           |
| Artikelnr.             | Wahl des Artikels, der umgebucht werden soll.          |                                                                        |
| Artikelbeschreibung    | Wird mit der Beschreibung des ausgewählten Artikels gefüllt. |                                                                        |
| Variantencode          | Hier kann die Variante des Artikels gewählt werden.    |                                                                        |
| Chargennr.             | Auswahl der Charge, die umgebucht werden soll.         |                                                                        |
| Seriennr.              | Auswahl der Serie, die umgebucht werden soll.          |                                                                        |
| Paketnr.               | Auswahl des Pakets, das umgebucht werden soll.         |                                                                        |
| Neue Artikelnr.        | Der Artikel wird ausgewählt, auf den umgebucht wird.   |                                                                        |
| Neue Artikelbeschreibung | Wird mit der Beschreibung des neuen Artikels gefüllt.   |                                                                        |
| Neuer Variantencode    | Wahl der Variante, auf die die Charge gebucht wird.    | Wenn eine Charge einer Variante zugeordnet ist, dann kann die Charge auch auf eine andere Variante umgebucht werden. |
| Neue Chargennr.        | Gibt die Charge an, auf die der Artikel gebucht werden soll. |                                                                        |
| Neue Seriennr.         | Gibt die Seriennummer an, auf die der Artikel gebucht werden soll. |                                                                        |
| Neue Paket-Nr.         | Gibt das Paket an, auf den der Artikel gebucht werden soll. |                                                                        |
| Lagerortcode           | Gibt den Lagerort an, in dem der Artikel vor der Umbuchung ist. |                                                                        |
| Lagerplatzcode         | Gibt den Lagerplatz an, an dem der Artikel vor der Umbuchung ist. |                                                                        |
| Neuer Lagerortcode     | Gibt den Lagerort an, in dem der Artikel nach der Umbuchung ist. |                                                                        |
| Neuer Lagerplatzcode   | Gibt den Lagerplatz an, an dem der Artikel nach der Umbuchung ist. |                                                                        |
| Menge                  | Hier wird die Menge angegeben, die umgebucht werden soll. |                                                                        |
| Einheitencode          | Die Einheit wird automatisch aus dem Artikel ausgefüllt. |                                                                        |
| Menge (Basis)          | Hier wird die Menge in der Basiseinheit des Artikels angegeben. |                                                                        |
| Buchungsdatum          | Buchungsdatum wird hier eingesetzt.                    |                                                                        |

<div style="text-align: center;">
    <img src="../../images/Reposting/Reposting4.png" alt="Funktion "Buchen" und "Buchen markierte"  style="width: 100%; height: auto;">
    <figcaption>Abbildung 4: Funktion "Buchen" und "Buchen markierte"</figcaption>
    <br>
</div>



Über die Funktion \"Verwalten\" kann man die ausgewählten
Buchblattzeilen löschen. Die Buchung des Buchblatts kann über zwei
Funktionen genutzt werden \"Buchen\" und \"Buchen markierte\". Nutzt man
die Funktion \"Buchen\" das komplette Buchblatt buchen, nutzt man die
Funktion \"Buchen markierte\" werden nur die markierten Zeilen des
Buchblatts gebucht. Nachdem eine Buch-Funktion verwendet wird, dann
werden die gebuchten Zeilen des Buchblatts geleert.

<div style="text-align: center;">
    <img src="../../images/Reposting/Reposting5.png" alt="Chargenumbuchung Buchblatt geleert" style="width: 100%; height: auto;">
    <figcaption>Abbildung 5: Chargenumbuchung Buchblatt geleert</figcaption>
    <br>
</div>



Für die Zeilen, die einen neuen Artikel erhalten haben, werden
Montageaufträge erstellt und gebucht. Zu finden sind sie unter den
\"Gebuchten Montageaufträge\" und in den \"Artikelposten\".

Die Zeilen, die nur einen neuen Lagerort oder einen neuen Lagerplatz
erhalten, werden umgelagert. Die Zeilen sind dann unter den \"Gebuchten
Umlagerungs-Ausgängen\", den \"Gebuchten Umlagerungs-Eingängen\" und den
\"Artikelposten\" zu finden.

### 3.2 Dimensionen

Es ist möglich Dimensionen an ein \"Artikel Umbuch.-Blatt\" zu setzen.
Die Dimensionen werden in den \"Umbuchung Buchblatt-Vorlagen\"
hinterlegt und bei der Buchung des Buchblatts übernommen.

<div style="text-align: center;">
    <img src="../../images/Reposting/Reposting6.png" alt="Dimensionen im Menüband der Buchblatt-Vorlagen" style="width: 100%; height: auto;">
    <figcaption>Abbildung 6: Dimensionen im Menüband der Buchblatt-Vorlagen</figcaption>
    <br>
</div>


