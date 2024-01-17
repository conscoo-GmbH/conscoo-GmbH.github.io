# How to use Docfx and GitHub Pages

## Prerequisites

Das Repository besitzt zwei branches.
Der *main*-branch dient zu Änderungen von Inhalten.
Der *gh-pages*-branch deployed die Webseite.

Möglicherweise muss nach [*Schritt 1*](#1-github-repo-lokal-in-visual-studio-code-öffnen) ein lokaler *build* durchgeführt werden.

## 1. GitHub Repo lokal in Visual Studio Code öffnen


- Repository per Standardweg in VSC öffnen und lokal speichern


## 2. Erstellen einer neuen Markdown Seite

Zuerst muss eine Markdown-Datei im Ordner */_site/docs* erstellt werden.
Als Benennung für Datei zur App-Dokumentation bietet sich *LeBit-App-Name.md* an.
Die erstellte Datei kann mit der Dokumentation gefüllt werden.<br>
Informationen zur Syntax und Einfügen von Bildern sind [*hier*](#markdown-syntax)  zu finden.

## 3. Aufnahme in das Inhaltsverzeichnis

Damit die Page in das Inhaltsverzeichnis aufgenommen wird muss die Datei in der Table of Contents Datei aufgenommen werden. <br>
 */_site/docs/toc.yml*

Bsp.:

```yaml

- name: How to Markdown
  href: How-to-md.md 

```

## 4. Lokalen Build durchführen

Durch den lokalen *build* werden das Inhaltsverzeichnis und die Markdown Dateien in *html*-Pages umgewandelt, die vom Browser angezeigt werden können. <br><br>

In Powershell muss zuerst zum Ordner verwiesen werden und daraufhin kann folgende Syntax zum Build ausgeführt werden.

```shell

docfx.exe

```
Dies führt den lokalen *build* der Seite aus.

Alternativ kann mit dem Command

```shell

docfx docfx.json --serve

```

die Webseite im Localhost geöffnet werden. <br>
[*Localhost:8080*](Localhost:8080)

## 5. GitHub build

Der *build*  der GitHub Pages Seite wird beim pushen von Changes automatisch durch die GitHub Action in *main.yml* durchgeführt.

### Markdown Syntax

Im Internet gibt es einige Syntax Cheatsheets, die bei der Erfassung helfen können. Beispielsweise [*hier*](https://www.markdownguide.org/basic-syntax/).

#### Bilder einbeziehen

Zum Nutzen von Bildern in der Dokumentation müssen diese im Ordner <br>

*/_site/images* <br>

gespeichert werden.

Als Dateiformate werden *.jpg*,*.jpeg* und *.png* verarbeitet. Dateiformate können in der *docfx.json*-Datei hinzugefügt werden.

Damit die Bilder richtig auf der Webseite angezeigt werden ist folgende Syntax notwendig.

```html

	![Alternativtext](../images/"Name des Bildes")
    <figcaption>Bildunterschrift</figcaption>   

```

Beispiel

```html

	![Bild von Hund](../images/Hund.jpg)
    <figcaption>Hund</figcaption>  

```